# Makati Robbery Map, 2026

An interactive map of **reported** robbery incidents in Makati City, Metro Manila,
1 January – 5 October 2026. Open `index.html`, or the published page.

Click any dot for the incident's location, notes, flags, how precisely it was placed,
and a link to its source. The Table tab lists every row and exports CSV.

## Read this before using the data

**This maps where robberies are *reported*, not where they happen.** The two differ a
lot, and not randomly.

- **Blue** = verified by an official police statement, news reporting, or a condominium
  memo. **Orange** = social-media report, unverified. They are not comparable; do not
  read the two colours as one count.
- **This is a small fraction of even the officially reported total.** No 2026
  Makati-level count is public. The closest official figure — 32 theft+robbery cases in
  Makati in Dec 2024, 13 in Jan 2025 — implies roughly 150–350 reported cases a year.
- **No dot is a real address.** Sources rarely give one. Each row records how it was
  placed, from `intersection` (~50 m) down to `barangay` (~900 m). Roughly a third are
  accurate only to a neighbourhood. Use the precision-radius toggle to see it.
- **Dates are soft.** Only about half the incidents are dated to the day. Community
  reports usually carry the date someone *posted*, not the date of the incident, so the
  timeline reads as "when this was reported".
- **Coverage is skewed.** News clusters on wealthy victims and foreign nationals; the
  community record clusters on the CBD, Salcedo and Legazpi, where the people who post
  live and work. Several barangays return almost nothing from either — a reporting gap,
  not an absence of crime.
- **Barangay attribution is unreliable.** Many rows have no barangay. One official
  police statement in this dataset describes a victim robbed at gunpoint while "walking
  toward a hotel in Brgy. Poblacion" but places the scene in Barangay Bel-Air — so a
  nightlife robbery is counted against the neighbouring barangay. Treat the Makati
  Avenue / P. Burgos corridor as an attribution boundary.
- **Poblacion is under-represented here, not low-crime.** Reports from the nightlife
  district are overwhelmingly undated or second-hand, because its victims are the least
  likely to post a dated first-hand account. No rows were invented to close that gap.

Use this to see where reports concentrate. Do not use it to compare how safe
neighbourhoods are, and do not treat an absence of dots as an absence of crime.

## Privacy

Two incidents were reported in the press with the victims' names. Those names are
removed here: a searchable map pinning a named person's home is a different thing from a
news article. No victim names, unit numbers or contact details appear anywhere on this
page or in its CSV export.

## Credits

Basemap drawn from [OpenStreetMap](https://www.openstreetmap.org/copyright) data, © OpenStreetMap
contributors, ODbL. No tile server — the page is self-contained and works offline.
Incident sources are linked from each dot.
