### Hi, I'm Peter: geospatial data engineer in London, UK

I build data pipelines that turn open geospatial and demographic data into reliable, documented
datasets and maps: from LiDAR and Sentinel-2 to census, postcode and network data, on Databricks,
Azure and PostGIS. **Open to geospatial data engineering roles.**

**Portfolio:** [petersolan.github.io](https://petersolan.github.io) · **LinkedIn:** [linkedin.com/in/petersolan](https://www.linkedin.com/in/petersolan/)

| Project | What it shows | Links |
|---|---|---|
| **Exeter 4G/5G Coverage Checker & Signal Atlas** | Mobile coverage model from Ofcom open drive tests: 531 4G cells located from the measurements, terrain diffraction over EA LiDAR, clutter fitted per operator, 5G on the estimated masts; validated on held-out areas, then counted against 152k Census residents: who gets indoor 4G or good 5G from each operator, in any area you draw | [Coverage checker](https://petersolan.github.io/Mobile-Signal-Strength/coverage.html) · [Signal Atlas](https://petersolan.github.io/Mobile-Signal-Strength/) · [Code](https://github.com/petersolan/Mobile-Signal-Strength) |
| **Demographic & Geospatial Pipelines on Databricks** | Medallion pipeline (PySpark, Delta, Unity Catalog, Asset Bundles): NHS/ONS postcode and boundary joins with native spatial SQL, versioned lookups, reconciliation, pseudonymisation and disclosure control; incremental monthly updates (Auto Loader + MERGE into an effective-dated history); calibrated against real NHS England registrations; AI/BI dashboard with a map, deployed as code | [Live demo](https://petersolan.github.io/GB-Demographic-Geospatial-Databricks/) · [Code](https://github.com/petersolan/GB-Demographic-Geospatial-Databricks) |
| **GB Census Population Map** | Census population shared out to 41.6M address points across Great Britain, 10 m population grid, cloud-optimised GeoTIFF on an interactive map | [Live demo](https://petersolan.github.io/GB-Census-Population-Map/cog.html) · [Code](https://github.com/petersolan/GB-Census-Population-Map) |
| **Exeter 3D City Model** | 3D buildings with heights, 127k tree crowns and terrain from Environment Agency LiDAR, validated against OS, Microsoft and OpenStreetMap | [Live demo](https://petersolan.github.io/Exeter-3D-City-Model/) · [Code](https://github.com/petersolan/Exeter-3D-City-Model) |
| **Fibre Planning Pipeline** | Kedro pipeline into PostGIS with Alembic, FastAPI, GeoServer and a QGIS plugin: which premises lack gigabit broadband and which roads reach them | [Live demo](https://petersolan.github.io/GB-Fibre-Planning-Pipeline/) · [Code](https://github.com/petersolan/GB-Fibre-Planning-Pipeline) |
| **Green Space Indicators for Devon** | Geospatial lakehouse on Azure (ADLS Gen2, Delta Lake), Sentinel-2 greenness, ISO 19115 / DCAT-AP / SDMX metadata | [Live demo](https://petersolan.github.io/GB-Green-Space-Indicators/) · [Code](https://github.com/petersolan/GB-Green-Space-Indicators) |

**Tools I use:** Python · SQL · PostGIS · DuckDB · Databricks · PySpark · Delta Lake · Azure ·
Kedro · FastAPI · GeoServer · QGIS / PyQGIS · GeoPandas · Rasterio · SciPy · Xarray · MapLibre · GeoLibre · Docker ·
GitHub Actions
