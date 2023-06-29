# Data

This project is based on a variety of public and open data sources of third parties including statistical and geospatial data. Additionally, latest academic research is taken into account to determine the concrete carbon sink potential of different ecosystems.

- The **"GHG Emissions of EU-27 Countries"** dataset used in this project is owned by the European Environment Agency (EEA) and licensed under CC-BY. It was obtained from the **EEA greenhouse gases — data viewer**. The dataset can be found at [EEA greenhouse gases - data viewer](https://www.eea.europa.eu/data-and-maps/data/data-viewers/greenhouse-gases-viewer), under the "Sectors" tab. 

- Data regarding carbon pools and sequestration rates is derived from the ETC/ULS Report 10/2021 [Carbon pools and sequestration potential of wetlands in the European Union](https://www.eionet.europa.eu/etcs/etc-di/products/etc-uls-report-10-2021-carbon-pools-and-sequestration-potential-of-wetlands-in-the-european-union/@@download/file/Carbon%20pools%20and%20sequestration%20potential.pdf) as well as the referenced paper [Carbon stocks and sequestration in terrestrial and marine ecosystems: a lever for nature restoration?](https://www.eea.europa.eu/publications/carbon-stocks-and-sequestration-rates/carbon-stocks-and-sequestration-in/carbon-stocks/download) by Hendricks et al. (2020) 

- The **NUTS (Nomenclature of territorial units for statistics) 2021** classification and its administrative boundaries used in this project are obtained from the [Eurostat website](https://ec.europa.eu/eurostat/web/gisco/geodata/reference-data/administrative-units-statistical-units/nuts#nuts21) (© EuroGeographics for the administrative boundaries)

- The **CORINE Land Cover 2018** dataset used in this project is published by the European Environment Agency (EEA) under the framework of the Copernicus programme. It was obtained from the [Copernicus Programme Website](https://land.copernicus.eu/pan-european/corine-land-cover/clc2018) and can be found under the "Download" tab of the CLC 2018 data product.

- The **"Emissions from Drained organic soils"** dataset used in this project is owned by the Food and Agriculture Organization of the United Nations (FAO). Citation: FAOSTAT. License: CC BY-NC-SA 3.0 IGO. Extracted from: https://www.fao.org/faostat/en/#data. Data of Access: 27-06-2023.

## NUTS 2021 Classification

The NUTS classification (Nomenclature of territorial units for statistics) is a hierarchical system for dividing up the economic territory of the EU and the UK for various purposes. More information can be found on the offical EU website: https://ec.europa.eu/eurostat/web/nuts/background

The NUTS data is used in this project for two purposes:
1. A convenient way to use the geometry of the country Germany to filter the Corine Land Cover 2018 data
2. Present different administrative units on a map, here: aggregate area data by NUTS zone.

The data can be downloaded from the official source here:

- https://ec.europa.eu/eurostat/web/gisco/geodata/reference-data/administrative-units-statistical-units/nuts

Or directly from here:

- https://gisco-services.ec.europa.eu/distribution/v2/nuts/topojson/NUTS_RG_01M_2021_4326_LEVL_0.json
- https://gisco-services.ec.europa.eu/distribution/v2/nuts/topojson/NUTS_RG_01M_2021_4326_LEVL_3.json