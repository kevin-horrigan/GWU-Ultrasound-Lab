# Module 04: Hydrophones

**Equipment:** Onda HGL-0200 + preamp, XY9 robot, tank

## Learn
Pressure, intensity, beam profiles, MI, I_spta, calibration (V/Pa).

## Do (hands-on) - beam map + peak pressure
1. In degassed water, position the calibrated hydrophone on the beam axis (Arrick XY positioner).
2. Record peak-positive and **peak-negative** pressure; scan across to map the beam.
3. Convert with the **per-serial M(f) sensitivity** + preamp gain: p = V / (M(f) * gain).
4. **MI = p_neg[MPa] / sqrt(f_c[MHz])**; Ispta from the pressure-squared integral.

## Lessons from the bench
- **The per-serial M(f) cal sheet + preamp gain is MANDATORY for absolute pressure/MI.** Without it you get
  **relative beam shape only** - so if the sheet can't be found, treat the hydrophone as a beam-shape tool and
  get absolute numbers from the RFB (Module 05) instead. Track the cal sheet down ahead of a session.
- MI general form is **1/sqrt(f_c)**, not the "/sqrt(2)" 2-MHz special case.
- The hydrophone element is tiny and fragile - handle per manual, never sonicate it.

## Reference
- Run sheet Step 4: `../SOPs/transducer-characterization.md`.
  Instrument: [`../Equipment/items/31_hydrophone-pre-amplifier/notes.md`](../Equipment/items/31_hydrophone-pre-amplifier/notes.md).

## Notes
