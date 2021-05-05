What you see below are a few examples of climate-hazard maps. 

##### They display several hazards at different points across space, time, climate scenarios, climate models and probability distributions. 

##### These maps were made for research purposes using open-source data (references below) and code I wrote in `R`.

###### *webpage under development*

### Flood hazard map

Data for this map comes from the [Aqueduct Floods](https://www.wri.org/aqueduct/floods) research programme, conducted by the World Resources Institute (WRI) & a consortium of partners. 
This map shows the extent of flood that will have a 1/10 chance of occurring in any given year (10-year return period) in India and Pakistan around the 2050 horizon and according to climate simulations run using scenario RCP 8.5.

![Image1](/map_india.png)

###### WRI made all technical information available [here](https://www.wri.org/research/aqueduct-floods-methodology).

###### Flood risk linked to subsidence was included. The multi-model mean - using projections from all 5 General Circulation Models (GCMs) - was calculated for riverine flood. The 95th percentile was selected for coastal flood. Version #2 of Aqueduct Floods - released 10/2020 - was used.

This map of the Netherlands was generated using the same source (Aqueduct Floods version 2) and same parameters (RCP 8.5, 2050, 10% Annual Exceedance Probability). 

![Image1](/map_nl.png)


### High-resolution flood modelling over the Seine river basin

Flood risk for the Paris region was modelled at an ultra-high resolution by services of the French administration with support from French research laboratories. 

What you see below is the extent of flood under scenario 1.4, dubbed "extreme", as seen in a geobrowser. Darker colors depict higher levels of flood.

![Image2](/image001.jpg)

##### The [TRI map](http://www.driee.ile-de-france.developpement-durable.gouv.fr/tri-de-la-metropole-francilienne-a1769.html) for the Paris region (Territoires à risque important d’inondation, métropole francilienne) was produced by the Préfecture d'Île-de-France and DRIEAT. Documentation for this data source is available [here](http://webissimo.developpement-durable.gouv.fr/IMG/pdf/20170209_atlas_idf_a3_paysage_document_principal_cle5be11d.pdf).



### Web application: an interactive hazard map showing critical infrastructure

This is a snapshot of a web application I developed using climate-hazard projections and geographic coordinates for critical energy & industry infrastructure - all open source. A dashboard in another tab computes statistics on the exposure of local infrastructure to hazards. 

##### Just before this snapshot was taken, a bunch of layers for the South-Eastern region of France were selected.

![Image3](/snap_app.png)

##### Data for this web app comes from various plaforms managed by services of the French administration ([DataSud](https://www.datasud.fr/), [GeoIDE](http://carto.geo-ide.application.developpement-durable.gouv.fr/1131/environnement.map), [GeoRisques](https://www.georisques.gouv.fr/donnees/bases-de-donnees)) and from the International Union for Conservation of Nature's (IUCN) World Database on Protected Areas [(WDPA)](https://www.iucn.org/theme/protected-areas/our-work/quality-and-effectiveness/world-database-protected-areas-wdpa). Base layers are from OpenStreetMap and Stamen.









