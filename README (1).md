# Appendix H — Turning Proportion and Vehicle Composition Computations

This repository contains the CSV data tables for **Appendix H** of a study of traffic conditions at four successive intersections along MacArthur Highway in Agoo, La Union, Philippines.

The data cover **September 17–23, 2026** and are provided as three separate CSV files.

## Files

| Filename | Contents | Data rows |
|---|---|---:|
| `Appendix_H_Turning_Proportions.csv` | Intersection, peak period, arrival direction, date, road segment, through flow (veh/h), turn share (%), and east share (%) | 112 |
| `Appendix_H_Vehicle_Composition_Counts.csv` | Daily vehicle counts by intersection for tricycles, cars, motorcycles, buses, and trucks | 28 |
| `Appendix_H_Vehicle_Composition_Percentages.csv` | Daily totals and vehicle-class percentages by intersection | 28 |

**Total:** 168 data rows across the three files (excluding headers).

## How to access the data

Select a CSV file above on GitHub to preview its contents. To download a particular CSV, open it and select **Raw**, then save the file. Alternatively, download the repository as a ZIP file using **Code → Download ZIP**.

These files are shared as supplementary appendix data. Their numerical entries were transcribed from the corresponding LaTeX appendix tables without recalculation.

## Notes

- `AM` and `PM` identify the morning and afternoon observation periods.
- `I1` through `I4` identify the four intersections.
- Flow is expressed in vehicles per hour (`veh/h`); proportions are expressed as percentages.
- Dates in the turning-proportion file use `YYYY-MM-DD`. Dates in the composition tables use `MM-DD` and refer to 2026.

