# Module 03: Driving a Transducer

**Equipment:** Function gen, AR 150A100B amp, Bird 4421, scope, 50 ohm load

## Learn
The driving chain, forward/reflected power, safe drive-up, matching.

## Do (hands-on) - build the drive chain + safe drive-up
1. **Test the amp into a 50 ohm dummy load FIRST** (never open/cold). Func gen -> AR 150A100B -> Bird -> 50 ohm.
2. Set the drive frequency = **fs from Module 06**. Start at minimum amplitude and bring it up slowly.
3. Read **forward and reflected** power on the Bird. Net electrical in = forward - reflected; high reflected =
   poor match (see Module 06).
4. Swap the dummy for the element in water and repeat the drive-up.

## Lessons from the bench
- **AR 150A100B wants <=1 mW input for 150 W out.** Set the func-gen level AND any input attenuation BEFORE
  keying up - overdriving the input is how you kill the amp (danger).
- **Never run the amp into an open or cold** - always a load (dummy or matched element).
- Bird needs the **2 MHz slug** and correct **SOURCE/LOAD orientation** to read right.
- Reflected power is your live matching readout - minimizing it is what Module 06's matching network is for.

## Reference
- Run sheet Step 2: `../SOPs/transducer-characterization.md`.
  Manuals (AR limit, Bird slug): `../Manuals/README.md`.
  Instrument: [`../Equipment/items/28_rf-power-amplifier/notes.md`](../Equipment/items/28_rf-power-amplifier/notes.md).

## Notes
