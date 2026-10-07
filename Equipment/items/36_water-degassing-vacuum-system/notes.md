# Water degassing vacuum system

| | |
|---|---|
| **Official inventory name** | Water degassing vacuum system |
| **Manufacturer** | Ted Pella (Pelco) |
| **Model** | Air-out |
| **Category** | WATER |
| **Asset #** | _TODO_ |
| **Location** | Zderic Lab, GW SEH |
| **Status** | in official inventory |

## Photos
_Add 1-6 photos to `photos/`._

## Purpose
Degasses the tank water (removes dissolved gas -> fewer bubbles/cavitation). THE degassing method (not the heated bath).

## TWO DIFFERENT DEVICES - confirmed by photo 2026-08-17

A self-contained box labelled **INLINE DEGASSER** is on the bench, with a **WIKA vacuum gauge
(0 to -30 in.Hg)**, two tubes through the front panel, and a reservoir bottle. **Observed reading
about -20 in.Hg.**

That is NOT the batch desiccator method described below. An inline degasser pulls vacuum across a
gas-permeable membrane while water FLOWS through it, so it degasses continuously and suits a
recirculating loop. The desiccator method degasses a static batch and generally reaches a lower
gas concentration per pass.

Both are useful and they are not interchangeable:

| | inline unit | batch desiccator |
|---|---|---|
| water | flowing | static |
| suits | flow phantom loop, topping up a tank | preparing tank water before a session |
| depth per pass | modest, but recirculates | deeper |

**The observed -20 in.Hg is below the 25-30 in.Hg this file recommends.** Either the target does
not apply to the inline unit or it is not pulling as hard as it should. Worth resolving before any
measurement that depends on gas content, and worth splitting into its own equipment entry since it
is a distinct instrument.

## Basic operating principle
Vacuum degassing. Water goes in a sealed desiccator/flask and an **oil-less diaphragm pump** pulls the
headspace down near water's vapor pressure. Dissolved gas comes out of solution (visible bubbles form and
rise). Not a catalogued "Air-out" product - it's a component desiccator + diaphragm-pump method.

## Typical settings
- Pull to **~25-30 inHg (~85-100 mbar absolute)**. **30-60+ min.** A gentle **stir** nucleates bubbles.
- Target **dissolved O2 < ~2-3 mg/L (<20-30% saturation)** - verify on the Control Company O2 meter (item 34).
- **Use a knock-out / trap flask** between the vessel and the pump so water vapor never reaches the pump.
- Degassed water **re-absorbs gas over hours** - degas same-session, keep covered, use promptly.

## Safety considerations
Oil-less/diaphragm pump only (water vapor ruins oil pumps). Don't pull hard vacuum on glassware that isn't
vacuum-rated (implosion). Release vacuum slowly.

## Connected equipment / typical workflow
tank/flask -> Pelco vacuum (+ trap flask) -> verify O2 (item 34) -> acoustic measurement.md` Day 1 plan.

## Manuals / datasheet / website
- Manual: _TODO (add PDF to `../../Manuals/ted-pella-pelco/`)_
- Datasheet: _TODO_
- Website: _TODO_
- QR code: _TODO_

## Relevant publications
- _TODO_

## Research ideas (what could we do with this today?)
- _TODO_

## Lab notes
<!-- date / who / what happened. Append freely. -->

