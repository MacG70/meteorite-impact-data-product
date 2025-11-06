# Schema

Source columns include:
- `name` (meteorite name)
- `id` (source identifier)
- `recclass` (meteorite class)
- `mass` (grams, may be missing)
- `year` (discovery or landing year, may need parsing to YYYY)
- `reclat` (latitude, numeric, may be missing)
- `reclong` (longitude, numeric, may be missing)
- `fall` (Fell or Found)
- `GeoLocation` (string coordinates)

Curated output will:
- Standardize `year` to YYYY (integer)
- Cast `reclat` and `reclong` to numeric where possible
- Keep only records with valid coordinates and year when needed
- Add a `source_url` field pointing to NASA Open Data record
