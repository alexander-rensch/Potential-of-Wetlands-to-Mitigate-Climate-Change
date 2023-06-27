# The Potential of Wetlands to Mitigate Climate Change

## Introduction
Climate change is one of the biggest and most complex challenges of our time. To combat it, we need to drastically reduce our greenhouse gas emissions: the EU has set the goal to cut the GHG emissions by at least 55% by 2030, and to reach net neutrality by 2050 - a task which is still facing a variety of problems. The natural environment plays a vital role in this endeavour: forests, agroecosystems, marine and other ecosystems offer many and varied benefits to us and the planet. One of those major ecosystems are wetlands which slowly begin to take a larger part in public discussions for their high capability to act as carbon sinks.

By illustrating the capacity of wetlands to act as carbon sinks and store significant amounts of greenhouse gases, this visualization project emphasizes their potential in reducing atmospheric concentrations and combating climate change. 

This project has been executed in the course of the "Data Visualization and Visual Analytics" module of the FH Kiel in the summer term 2023.

## Getting Started

The visualization project is realized inside a Jupyter notebook with [Altair](https://altair-viz.github.io/) as a visualization library. It can be found in the root folder of this project: ``notebook.ipynb``.

The notebook has been tested under Python 3.10.11 installed in a [Conda](https://docs.conda.io/en/latest/) environment and has the following dependencies:
- Pandas
- GeoPandas
- Altair

For the data, the notebook assumes that all datasets are stored in the `data` subfolder. See the `Readme.md` there for further details.

## Data Sources and References

This project is based on a variety of public and open data sources of third parties including statistical and geospatial data. Additionally, latest academic research is taken into account to determine the concrete carbon sink potential of different ecosystems.

- The **"GHG Emissions of EU-27 Countries"** dataset used in this project is owned by the European Environment Agency (EEA) and licensed under CC-BY. It was obtained from the **EEA greenhouse gases — data viewer**. The dataset can be found at [EEA greenhouse gases - data viewer](https://www.eea.europa.eu/data-and-maps/data/data-viewers/greenhouse-gases-viewer), under the "Sectors" tab. 

- Data regarding carbon pools and sequestration rates is derived from the ETC/ULS Report 10/2021 [Carbon pools and sequestration potential of wetlands in the European Union](https://www.eionet.europa.eu/etcs/etc-di/products/etc-uls-report-10-2021-carbon-pools-and-sequestration-potential-of-wetlands-in-the-european-union/@@download/file/Carbon%20pools%20and%20sequestration%20potential.pdf) as well as the referenced paper [Carbon stocks and sequestration in terrestrial and marine ecosystems: a lever for nature restoration?](https://www.eea.europa.eu/publications/carbon-stocks-and-sequestration-rates/carbon-stocks-and-sequestration-in/carbon-stocks/download) by Hendricks et al. (2020) 

- The **NUTS (Nomenclature of territorial units for statistics) 2021** classification and its administrative boundaries used in this project are obtained from the [Eurostat website](https://ec.europa.eu/eurostat/web/gisco/geodata/reference-data/administrative-units-statistical-units/nuts#nuts21) (© EuroGeographics for the administrative boundaries)

- The **CORINE Land Cover 2018** dataset used in this project is published by the European Environment Agency (EEA) under the framework of the Copernicus programme. It was obtained from the [Copernicus Programme Website](https://land.copernicus.eu/pan-european/corine-land-cover/clc2018) and can be found under the "Download" tab of the CLC 2018 data product.

- The **"Emissions from Drained organic soils"** dataset used in this project is owned by the Food and Agriculture Organization of the United Nations (FAO). Citation: FAOSTAT. License: CC BY-NC-SA 3.0 IGO. Extracted from: https://www.fao.org/faostat/en/#data. Data of Access: 27-06-2023.
