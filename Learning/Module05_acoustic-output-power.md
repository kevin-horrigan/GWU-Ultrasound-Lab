# Module 05: Acoustic Output Power

**Equipment:** RFB (Ohmic UPM-DT-10AV / Onda), balance

## Learn
Radiation force -> watts; W=Fc vs Fc/2; FDA I_spta limits.

## Do (hands-on) - rough acoustic power + efficiency on the RFB
1. Prep the tank (degas if convenient - see lesson below), mount the element, no bubbles on face/target.
2. Drive the element at a known **electrical** power (forward - reflected on the Bird, Module 03).
3. Read the radiation force off the balance -> **acoustic watts** (W = F*c absorbing target, F*c/2 reflecting).
4. **Headline number: efficiency = W_acoustic / W_electrical.** Spatial-avg intensity = W_ac / face area.

## Lessons from the bench
- **Degassing is a soft-gate for the RFB, not mandatory.** The real error is **bubbles on the target/face**:
  on a force balance a bubble is both buoyancy (false weight) and scatter (power reads low). Cavitation only
  matters at high power; low-V board validation is safe. If undegassed: brush bubbles off, let the balance
  settle, watch for drift. Degas target if you do it: DO < ~2-3 mg/L (<~20-30% sat).
- **Rough IS the goal.** RFB ~+/-10-20%, efficiency ~+/-20% - plenty to validate a design. Sanity anchors at
  30-50 V drive: ~0.5-2 W electrical, ~0.2-1 W acoustic, ~0.3-1.5 W/cm2.
- **MI/pressure is NOT an RFB output** - that needs the hydrophone + its per-serial M(f) cal sheet (Module 04).
- Don't run high-power CW long enough to heat the bath (baseline drifts).

## Reference
- Run sheet Step 3 + Day-1 plan: `../SOPs/transducer-characterization.md`.
  Instruments: [`../Equipment/items/22_reflective-radiation-force-balance/notes.md`](../Equipment/items/22_reflective-radiation-force-balance/notes.md),
  [`../Equipment/items/23_absorptive-radiation-force-balance/notes.md`](../Equipment/items/23_absorptive-radiation-force-balance/notes.md).

## Notes
