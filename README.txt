Flightflow v0.3 prototype

Open index.html locally or host the folder on GitHub Pages.
Use “Load today’s example” to populate YCAB–YKRY–Cooyar–YWSG–YCAB.

All safety-critical calculations are deterministic prebuilt logic:
- wind triangle and variation
- magnetic heading
- groundspeed and ETE
- landing allowances
- fixed and mandatory INTER/TEMPO reserves
- final fuel rounded upward
- ETA, last-light target and daylight margin
- remaining-flight revision from a selected point

AI is not used for headings, groundspeed, fuel, reserve or daylight calculations.
A future online AI component may translate METAR/TAF text, but the raw weather and pilot-confirmed reserve logic must remain visible.
