# Dataset and third-party notices

Original project code is MIT licensed. Source datasets are not relicensed by this repository.

- **Sentinel-1 / Sentinel-2:** contains modified Copernicus Sentinel data (2022 and 2026). Original data and derivatives remain subject to the [Copernicus Sentinel Data Legal Notice](https://sentinels.copernicus.eu/documents/247904/690755/Sentinel_Data_Legal_Notice). Processing and delivery providers (ESA, Microsoft Planetary Computer, Element 84) are identified in each source record. A STAC license field is retained when supplied; it is not rewritten into a project license.
- **GHSL:** European Commission Joint Research Centre, GHS-BUILT-S R2023A V1.0, CC BY 4.0. Derived crops and rectangle aggregations by AQUA PULSE. Exact dataset URLs, citation and methodology are in `public/data/urban/index.json`.
- **JRC Global Surface Water:** historical maximum extent v1.5, 1984–2024, used as a processing constraint rather than a present water observation. Source and terms: <https://global-surface-water.appspot.com/download>.
- **CONAGUA / SMN, SADM and Gobierno de Nuevo León:** selected factual table transcriptions with source links and evidence notes. Public access does not imply an unrestricted open license. The source PDFs are not redistributed here. Consult each publisher's terms before redistribution beyond the included factual extracts.
- **ERA5 via Open-Meteo:** modelled reanalysis delivered by Open-Meteo; retain provider and Copernicus attribution. Sources, model, retrieval date and coordinates are in `public/data/hydrology/weather.json`. See <https://open-meteo.com/en/terms> and <https://cds.climate.copernicus.eu/>.
- **NASA CMR / ASF / NISAR:** metadata evidence and official GIBS GCOV RGB browse imagery. These visualizations are not numerical backscatter products and are not used to derive water area. Source product maturity is preserved. Credit NASA/JPL-Caltech, ASF and NASA GIBS. NASA branding is not used to imply endorsement.
- **NASA GIBS:** online MODIS Terra visual context, dated 4 November 2026. Attribution remains visible on the map. <https://www.earthdata.nasa.gov/data/tools/gibs>.
- **OpenStreetMap:** optional online map tiles, © OpenStreetMap contributors. <https://www.openstreetmap.org/copyright>. No bulk download or offline tile cache is included.
- **Leaflet 1.9.4:** BSD-2-Clause; its distributed copyright/license notices remain with the vendor files produced by the build.

Per-observation source metadata takes precedence for version, acquisition date, coverage, units, quality and processing limitations. Temporary signed download URLs and credentials are excluded.
