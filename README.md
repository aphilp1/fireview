# FireView — Silvertip Fire Data Logger

Unofficial, personal live data log for the Silvertip Fire (Bob Marshall Wilderness, Montana). Auto-updates roughly every hour from real surface station observations, GOES-18 satellite imagery, and WFIGS fire perimeter data.

**This is not an official source.** For official information and evacuation guidance, see [InciWeb](https://inciweb.wildfire.gov/) or [NIFC](https://www.nifc.gov/).

Live at: https://aphilp1.github.io/firesense/

## What it shows

- Real-time wind speed/direction/gust for ~50 stations within 75 miles of the fire, in mph
- Interactive maps (real terrain, satellite, and GOES-18 imagery) with the fire's actual perimeter overlaid
- Hourly cycle-by-cycle observation log, including explicit "NO DATA" markers for anything that couldn't be retrieved that cycle — no fabricated or interpolated values, ever
- Live GOES-18 satellite imagery (NASA GIBS) with the target fire's real location marked

## Source data

Surface stations: Iowa Environmental Mesonet (MT_ASOS, MT_RWIS, MT_DCP, ID_ASOS, WA_ASOS, ID_RWIS). Fire perimeter/status: NIFC WFIGS. Satellite: NOAA/NASA GOES-18 via NASA GIBS. Basemaps: ESRI ArcGIS Online (Topo/Imagery/Hillshade, public, no key required).
