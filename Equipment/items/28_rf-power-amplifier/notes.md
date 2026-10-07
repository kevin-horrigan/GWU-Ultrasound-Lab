# RF power amplifier

<img src="photos/IMG_8062.jpg" alt="RF power amplifier" width="380">

| | |
|---|---|
| **Official inventory name** | RF power amplifier |
| **Manufacturer** | Amplifier Research |
| **Model** | 150A100B (150 W) |
| **Category** | DRIVE |
| **Asset #** | _TODO_ |
| **Location** | Zderic Lab, GW SEH |
| **Status** | confirmed (photo) |

## Photos
_2 photos in `photos/`._
## Purpose
Boosts the function-generator signal to drive transducers. Orange front panel, DO NOT EXCEED 260 mV input. CONFIRMED in photos.

## Basic operating principle
_TODO_

## Typical settings
_TODO_

## Safety considerations
_TODO_

## Connected equipment / typical workflow
Function Gen -> RF Amp -> Transducer

## Manuals / datasheet / software
- **Datasheet (AR 150A100B):** https://www.testequipmenthq.com/datasheets/AMPLIFIER%20RESEARCH-150A100B-Datasheet.pdf
- **Website:** https://www.arworld.us/
- QR code: _generate from the Manual/software URL above_

## Relevant publications
- _TODO_

## Research ideas (what could we do with this today?)
- _TODO_

## Lab notes
<!-- date / who / what happened. Append freely. -->
- 2026-07-10 (Kevin): **NO-GAIN FAULT.** Fed a clean **2 MHz sine at ~150 mVpp** into RF INPUT (verified
  on a FNIRSI scope at the input), amp POWER: ON / STATUS: OK, into a 50 ohm dummy via the Bird 4021 -
  output stayed at the **~2 mW noise floor** regardless of drive or GAIN. Sensor confirmed **not reversed**
  (RFL also ~0). A working amp would make watts at that input, so the AR is **not amplifying**. Needs a
  quirk/enable check with Vesna/Pouria or service. Workarounds while it is down: Electraft custom US
  driving amp (item 41), direct drive from the 33250A (~0.25-0.5 W), or a pulser (UT340 / 5073PR) for
  pulsed work.
