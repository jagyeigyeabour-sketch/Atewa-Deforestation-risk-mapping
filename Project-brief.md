 # Project Brief - Atewa Forest Deforestation Risk Mapping

Background:
Atewa Forest is one of Ghana's most important forest reserves - home to many endemic species and headwater of 3 major rivers (Ayensu, Densu, Birim). It is under serious threat from galamsey.

Objective:
To produce a risk map that shows which parts of Atewa are most vulnerable.

Datasets
   - Sentinel-2A Images: Jan 2020 & Jan 2024 (Tile T30NWM) from https://dataspace.copernicus.eu
   - SRTM DEM 30m from https://earthexplorer.usgs.gov
   - Atewa Boundary: Protected Planet WDPA ID 555542958
   - Roads/Settlements: OpenStreetMap via QGIS QuickOSM plugin

 Methodology (100% Desktop):
   - Step 1: Land Cover Classification (Forest vs Bareland/Farm/Mining) using Semi-Automatic Classification Plugin in QGIS
   - Step 2: Change Detection 2020-2024 using Raster Calculator
   - Step 3: Slope analysis from SRTM DEM
   - Step 4: Proximity analysis to roads/settlements
   - Step 5: Weighted Overlay to create Final Risk Map (High, Medium, Low)

Expected Output:
   - Map 1: Land Cover 2020 vs 2024
   - Map 2: Forest Loss (in hectares)
   - Map 3: Final Deforestation Risk Zoning Map

Application:
This map can be used by Forestry Commission (RMSC), Water Resources Commission and for my MSc application in Tropical Forestry (TU Dresden, Germany).

How to Reproduce:
All data and QGIS workflow will be shared in this repo.
