Flightflow v0.3.1 prototype

Changes from v0.3:
- New Plan starts a clean flight-specific workspace while retaining aircraft defaults.
- Calculate Plan changes to Recalculate Plan after first calculation; any pre-departure input can be corrected and the complete unused plan regenerated.
- Added local flight date and local departure time.
- Added manual time-zone label and UTC/GMT offset in 30-minute increments.
- Added date-aware Local <-> Zulu conversion, including previous/next UTC date crossings.
- Navigation log now shows ETA Local and ETA Zulu.
- Remaining-flight plan also shows local and Zulu ETD/ETA.
- Updated PWA cache version.

Calculation engine remains deterministic. AI is not used for safety-critical calculations.
