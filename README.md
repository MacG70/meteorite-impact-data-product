# Meteorite Impact Data Product

## Purpose
A minimal, versioned data product based on NASA’s public Meteorite Landings dataset. This repo provides raw source, a curated output, and clear metadata so others can reliably consume the data.

## Interface (what consumers should use)
- **Curated CSV**: `data/curated/meteorites_curated_latest.csv`  
- **Schema**: see `metadata/schema.md`  
- **Provenance**: raw source from NASA Open Data (dataset id gh4g-9sfh)
- **Link**: use this URL to fetch the current dataset: https://raw.githubusercontent.com/MacG70/meteorite-impact-data-product/refs/heads/main/data/raw/meteorites_raw_2025-11-06.csv
- **Curated Link**: use this URL to access the curated data from an HTTP endpoint: https://raw.githubusercontent.com/MacG70/meteorite-impact-data-product/refs/heads/main/data/curated/meteorites_curated_2025-11-06.csv

## Update cadence
Ad hoc for this demo. Replace with weekly or monthly if you automate later.

## Contacts
- Owner: <your name or team>
- Issues: use GitHub Issues in this repo

## License
- Data: NASA public domain (source attribution recommended)
- This repo’s packaging, docs, and transformations: CC BY 4.0

## Metadata
- [Source](metadata/source.md)
- [Schema](metadata/schema.md)
- [Transformations](metadata/transformations.md)
- [Quality Indicators](metadata/quality.md)

## Visualization
View interactive dashboard in Power BI:
[Open Dashboard](https://app.high.powerbigov.us/links/YI2xurXJF-?ctid=ce6c365b-795b-4ca4-8d59-5fc68b58a2be&pbi_source=linkShare)

