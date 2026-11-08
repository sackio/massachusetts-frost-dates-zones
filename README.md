# Massachusetts frost dates and hardiness zones

Two free tables for Massachusetts gardeners, compiled by [Katama Creek](https://katamacreek.com/), a small farm in Groton, Massachusetts.

| file | rows | what it holds |
|---|---|---|
| `massachusetts-frost-dates.csv` | 50 stations | Last spring and first fall frost (32 °F) at each NOAA station with at least 15 years of data: the median (50%) date, the date the last spring frost is later than only 1 year in 10, frost-free days, elevation, years of data and station id. |
| `massachusetts-hardiness-zones.csv` | 508 places | USDA plant hardiness zone and average coldest-night range for one ZIP code in each Massachusetts town or village. |
| `massachusetts-hard-freeze-dates.csv` | 50 stations | First fall frost (32 °F), first hard freeze (28 °F) and 24 °F at the same NOAA stations: median (50%) dates, the date before which a 28 °F night comes only 1 year in 10, days from 32 °F to 28 °F, and station id. Fields ANN-TMIN-PRBFST-T32FP50, -T28FP50, -T24FP50, -T28FP10, fetched 2026-11-07. Used for [when to dig dahlias in Massachusetts](https://katamacreek.com/guides/when-to-dig-dahlias-massachusetts/). |

## Sources and method
- Frost dates: NOAA NCEI U.S. Climate Normals 1991–2020, freeze-date probabilities. https://www.ncei.noaa.gov/products/land-based-station/us-climate-normals
- Zones: 2023 USDA Plant Hardiness Zone data (PRISM Climate Group, Oregon State University), looked up by ZIP through phzmapi.org; place names and ZIPs from GeoNames.
- A station a few miles away can differ from your garden. Height and distance from the coast both matter.

Readable versions, and a lookup by town:
- https://katamacreek.com/guides/massachusetts-frost-dates/
- https://katamacreek.com/guides/massachusetts-hardiness-zones/
- https://katamacreek.com/tools/massachusetts-town-frost-zone/

## License
CC BY 4.0. Use it freely, and credit "Katama Creek (katamacreek.com)" with a link. The underlying NOAA data is public domain. Please cite PRISM and the USDA for the zone data.
