# Module 06: Impedance & Matching

**Equipment:** Omicron Bode 100

## Learn
Resonance (fs/fp), coupling, matching network, bandwidth, poling check.

## Do (hands-on) - One-Port impedance sweep + poling check on a real element
1. **Connectorize.** Solder the PZT element to an SMA pigtail (RG316; red=center/hot to the hot electrode,
   black=shield to the ground/foil face). DMM-verify the leads (SMA center<->red, shell<->black).
2. **DMM capacitance pre-screen.** A piezo IS a capacitor. Foil(ground)<->hot lead should read ~nF.
   *Worked example (this lab's 10 mm PZT-5A disc): 1.489 nF through the SMA -> healthy.* Near-0/pF = open;
   dead short = hot-to-ground short.
3. **One-Port on the Bode 100.** Element pigtail -> SMA->BNC -> **OUTPUT only** (CH1/CH2 idle; internal
   50 ohm source). Bode Analyzer Suite -> Impedance -> One-Port. Sweep 0.5-3 MHz.
4. **Calibrate O/S/L at the element plane** (pigtail tip), not the Bode port.
5. **Read** fs (|Z| minimum), fp (|Z| maximum), |Z|@fs, and coupling **k_eff^2 = (fp^2 - fs^2)/fp^2**.
6. **Poling verdict:** sharp dip at fs + a distinct fp = POLED; smooth 1/f capacitor curve = depoled.

## Lessons from the bench
- **Capacitance != poling.** A depoled disc still reads ~the same nF (still a parallel-plate cap). Only the
  *resonance dip* proves poling.
- **Calibrate at the cable end.** ~0.8 m of RG316 adds ~80 pF shunt that shifts absolute fs/|Z| a few %.
  O/S/L at the pigtail tip de-embeds it.
- **You can back-solve thickness from C.** C = eps0*K*A/t. Worked: 1.489 nF minus ~0.08 nF cable on a 10 mm
  PZT-5A (K~1900) -> t~0.94 mm -> expect **fs ~2.0 MHz**; the sweep confirms it.
- One-Port optimum ~0.5 ohm-10 kohm covers a piezo across resonance; the B-WIC adapter (uses both inputs) is
  only needed for wider-range work.

## Reference
- Run sheet: `../SOPs/transducer-characterization.md` (Steps 1 + 1a).
  Bench manuals: `../Manuals/README.md`.
  Instrument: [`../Equipment/items/21_impedance-analyzer/notes.md`](../Equipment/items/21_impedance-analyzer/notes.md).

## Notes
