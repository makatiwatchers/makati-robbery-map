# Makati Robbery Map, 2026

An interactive map of **reported** robbery incidents in Makati City, Metro Manila,
covering **2024, 2025 and 2026** (2026 to 5 October). Open `index.html`, or the
published page. Use the year filter to view one year at a time.

Click any dot for the incident's location, notes, flags, how precisely it was placed,
and a link to its source. The Table tab lists every row and exports CSV.

## Read this before using the data

**This maps where robberies are *reported*, not where they happen.** The two differ a
lot, and not randomly.

- **Years are not comparable — this is the most important caveat.** The counts rise
  steeply across years (10 / 17 / 56), and that is overwhelmingly coverage, not crime.
  The one official figure available —
  **295 "crime cases" in Makati in 2024** — is a claim in the mayor's State of the City
  Address covering all crime types, with the scope never defined and no police source,
  so it is not a robbery denominator. A year-on-year comparison from this data measures
  journalism, not crime.

- **This is a small fraction of even the officially reported total.** The closest
  official figures are monthly and combine theft with robbery: 32 cases in Dec 2024,
  13 in Jan 2025. No full-year Makati figure has been published for 2025 or 2026.
- **No dot is a real address.** Sources rarely give one. Each row records how it was
  placed, from `intersection` (~50 m) down to `barangay` (~900 m). Roughly a third are
  accurate only to a neighbourhood. Use the precision-radius toggle to see it.
- **Dates are estimated based on when it was reported/shared.** Only about half the incidents are dated to the day.
- **Coverage is skewed.** News clusters on wealthy victims and foreign nationals; the
  community record clusters on the CBD, Salcedo and Legazpi, where the people who post
  live and work. Poblacion is under-represented here, not low-crime.

Use this to see where reports concentrate. Do not use it to compare how safe
neighbourhoods are, and do not treat an absence of dots as an absence of crime.


## A note on two columns

`barangay_disputed` flags a location whose barangay attribution is contested — the EMBO
barangays transferred from Makati to Taguig in 2021, and one incident on the
Makati–Pasay boundary. `location_precision` records how each dot was placed, from
`intersection` (~50 m) to `barangay` (~900 m).

## Credits

Basemap drawn from [OpenStreetMap](https://www.openstreetmap.org/copyright) data, © OpenStreetMap
contributors, ODbL. No tile server — the page is self-contained and works offline.
Incident sources are linked from each dot.
