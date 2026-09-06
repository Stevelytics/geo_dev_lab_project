# Urban Growth in Ibeju-Lekki, Lagos State

Week 1 — question chosen, hardest dataset being verified.

---

## 1. The Question

How much has the built-up area of Ibeju-Lekki Local Government Area, Lagos State expanded since 2015?

## 2. Why It Matters

Ibeju-Lekki is growing fast and largely informally around major infrastructure (the Lekki Free Trade Zone, Dangote Refinery, Lekki Deep Sea Port, Alaro City). Planning and utility agencies need to know *where* new settlement is forming so roads, drainage, and services can be planned ahead of the growth rather than after it. This is also a place where remote-sensing results can be sanity-checked against real, well-documented development.

## 3. The Data I Need

- [ ] LGA administrative boundary for Ibeju-Lekki
- [ ] Built-up/settlement extent, at least two time points (2015 and most recent)
- [ ] Population trend as a cross-check on where growth is concentrated
- [ ] Satellite imagery to visually verify the built-up layer against reality

## 4. Where Each Dataset Comes From

| # | Dataset | Source | Link | Format | Checked on |
|---|---------|--------|------|--------|------------|
| 1 | Ibeju-Lekki LGA boundary | GRID3 Nigeria / OCHA Nigeria admin boundaries | https://data.grid3.org (search "Nigeria LGA boundaries") or https://data.humdata.org (search "Nigeria administrative boundaries") | Shapefile / GeoJSON | 2026-09-07 |
| 2 | Multi-year built-up area | GHSL (Global Human Settlement Layer), JRC/Copernicus | https://human-settlement.emergency.copernicus.eu/download.php | GeoTIFF | 2026-09-07 |
| 3 | Population trend, gridded | WorldPop | https://hub.worldpop.org | GeoTIFF | 2026-09-07 |
| 4 | Satellite imagery, 2015 vs recent | Sentinel-2, via Copernicus Data Space | https://dataspace.copernicus.eu | Cloud-optimized GeoTIFF | 2026-09-07 |


## 5. What I Would Build

A before/after map of built-up area in Ibeju-Lekki (2015 vs today), updated quarterly, that flags which newly-built-up areas still have no paved road within reach something an LGA planning officer could actually open and act on, not just a static map.

---

## Study Area

**Place:** Ibeju-Lekki Local Government Area, Lagos State, Nigeria
**Why this place:** Rapid, well-documented growth since 2015 around named infrastructure projects, giving an unusual amount of public record to check the data against — and a single LGA is small enough to actually finish in a year.


## License / Attribution

Data used in this project is credited to its original source in the table above (e.g. © OpenStreetMap contributors, ODbL). This repository's own code and writing: [MIT / CC-BY / your choice].
