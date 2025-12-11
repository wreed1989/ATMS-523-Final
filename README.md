# ATMS-523-Final

This repository contains code used to analyze frost and freeze frequency for Plant City, Florida (station USC00087205) and to examine how extreme cold events relate to ENSO sea-surface temperature anomalies.

## Data Sources

Daily temperature (GHCN-D):
- http://noaa-ghcn-pds.s3.amazonaws.com/ghcnd-stations.txt
- http://noaa-ghcn-pds.s3.amazonaws.com/ghcnd-inventory.txt
- s3://noaa-ghcn-pds/csv/by_station/USC00087205.csv

ENSO indices and SST fields:
- https://www.cpc.ncep.noaa.gov/data/indices/sstoi.indices
- https://www.ncei.noaa.gov/access/monitoring/enso/sst

## Objectives

- Compute October–January frost (≤32°F) and freeze (≤28°F) climatology for 1991–2020.
- Identify which Niño region (NINO1+2, NINO3, NINO4, NINO3.4) shows the strongest correlation with Plant City freeze events.
