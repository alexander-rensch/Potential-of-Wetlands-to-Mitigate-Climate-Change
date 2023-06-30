# Data

This project is based on a variety of public and open data sources of third parties including statistical and geospatial data. Additionally, latest academic research is taken into account to determine the concrete carbon sink potential of different ecosystems.

-  The **"GHG Emissions of EU-27 Countries"** dataset from the European Environment Agency (EEA) lists the greenhouse gas emissions in the EU-27 countries by sector since 1990. From this, we can derive the current state of our progress towards net-neutrality and the main contributors to the emissions in the EU.
-  The **CORINE Land Cover 2018** dataset from the European Environment Agency (EEA) under the framework of the Copernicus programme comprises an inventory of land cover classes for europe derived from satellite imagery. We use it to determine where wetlands are located in Germany and how large their area is.
-  The **NUTS (Nomenclature of territorial units for statistics) 2021** classification and its administrative boundaries from eurostat effectively gives us the geometry data for Germany and a useful subdivision into administrative units (e.g., "Kreise") which we can use for aggregation of data.
-  The **"Emissions from Drained organic soils"** dataset by the Food and Agriculture Organization of the United Nations (FAO) gives us the emissions and area from drained organic soils - areas which are drained for agricultural purposes for example, which effectively work against the carbon sink potential of wetlands.
-  Data regarding carbon pools and sequestration rates is derived from the ETC/ULS Report 10/2021 as well as the referenced paper by Hendricks et al. (2020). We use this data to highlight the theoretical potential of wetlands (and other ecosystems in comparison).

## GHG Emissions of EU-27 Countries

The **"GHG Emissions of EU-27 Countries"** dataset used in this project is owned by the European Environment Agency (EEA) and licensed under CC-BY. It was obtained from the **EEA greenhouse gases — data viewer**. The dataset can be found at [EEA greenhouse gases - data viewer](https://www.eea.europa.eu/data-and-maps/data/data-viewers/greenhouse-gases-viewer), under the "Sectors" tab. 

The dataset includes greenhouse gas emissions and removals, sent by countries to UNFCCC and the EU Greenhouse Gas Monitoring Mechanism, differentiated by country and sector. It is used to get an overview of the aggregated emissions over all EU-27 countries since 1990, as well as the latest division of emissions by sector for 2021.

## CORINE Land Cover 2018

The **CORINE Land Cover 2018** dataset used in this project is published by the European Environment Agency (EEA) under the framework of the Copernicus programme. It was obtained from the [Copernicus Programme Website](https://land.copernicus.eu/pan-european/corine-land-cover/clc2018) and can be found under the "Download" tab of the CLC 2018 data product. To download the vector-based data used in this project, a (free) registration on the website is required.

The CORINE Land Cover 2018 consists of an inventory of land cover in 44 classes based on Sentinel-2 and Landsat-8 data. More information about the classification can be found in the [CORINE Land Cover nomenclature guidelines](https://land.copernicus.eu/user-corner/technical-library/corine-land-cover-nomenclature-guidelines/html/index.html).

## NUTS 2021 Classification

The NUTS classification (Nomenclature of territorial units for statistics) is a hierarchical system for dividing up the economic territory of the EU and the UK for various purposes. More information can be found on the offical EU website: https://ec.europa.eu/eurostat/web/nuts/background

The NUTS data is used in this project for two purposes:
1. A convenient way to use the geometry of Germany to filter the CORINE Land Cover 2018 dataset
2. Present different administrative units on a map and aggregate area data by those units.

The data can be downloaded in different formats from the official source here:

- https://ec.europa.eu/eurostat/web/gisco/geodata/reference-data/administrative-units-statistical-units/nuts

Or the format used in this project directly from here:

- https://gisco-services.ec.europa.eu/distribution/v2/nuts/topojson/NUTS_RG_01M_2021_4326_LEVL_3.json

## Emissions From Drained Organic Soils

The **"Emissions from Drained organic soils"** dataset used in this project is owned by the Food and Agriculture Organization of the United Nations (FAO). It can be obtained from FAOSTAT in the domain "Climate Change: Agrifood systems emissions" > "Emissions from Land use and change" or directly here: https://www.fao.org/faostat/en/#data/GV

The FAOSTAT domain Drained organic soils consists of nitrous oxide (N2O) and carbon dioxide (CO2) emissions associated with the mineralization and oxidation of the organic matter in organic soils that are drained for agriculture (cropland and grassland). Information is disseminated by country on: activity data (in hectares of organic soils drained for agriculture); and greenhouse gas (GHG) emissions (in kilotonnes of N2O and CO2). 

The data is used in this project to show the hot spots and development of drainage area in the EU-27 countries in the last years.
