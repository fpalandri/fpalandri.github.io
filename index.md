What you will find here are a few examples of physical climate risk maps. _webpage under development_

##### They display several climate hazards at different points across space, time, climate scenarios, climate models and probability distributions. These maps were made for research purposes using open-source data and code I wrote in `R`.


### Drought risk for power plants (CNRM - CLIMSEC)

These maps show the change in the drought index in France in winter over time (columns) and across climate scenarios (rows).

![Image4](/drought.png)

###### The lower the SPI (Standardized Precipitation Index), the more severe the drought. Drought was modelled by CNRM (Centre National de Recherches Météorologiques, led by Météo-France and CNRS) under the [CLIMSEC project](http://www.umr-cnrm.fr/spip.php?article605) (documentation is [here](http://www.umr-cnrm.fr/IMG/pdf/2011_fmaif_rapport_final_v2.2.pdf)) and made available via [DRIAS](http://www.drias-climat.fr/accompagnement/sections/187). C-MIP4 simulations and CNRM's hydrometeorological model were used. 

###### Whenever data was available, the multi-model mean was computed (i.e. mean of respective changes in SPI as projected by CNRM-ARPEGE, MPI-ECHAM5 and CCCMA-CGCM3). 

###### Power-plant data comes from WRI's [Global Power Plant Database](https://datasets.wri.org/dataset/globalpowerplantdatabase).



### Heatwave days (ECMWF - EURO-CORDEX, Copernicus)

_coming_


### Flood hazard maps - (WRI - Aqueduct)

These maps of India and the Netherlands show the extent of a flood that will have a 1/10 chance of occurring in any given year around the 2050 horizon, according to climate simulations run using scenario RCP 8.5.

![Image1](/map_india.png)

![Image1](/map_nl.png)

###### Data for this map comes from the [Aqueduct Floods](https://www.wri.org/aqueduct/floods) research programme, conducted by the World Resources Institute (WRI) & a consortium of partners. Relevant documentation is [here](https://www.wri.org/research/aqueduct-floods-methodology).

###### Flood risk linked to subsidence was included. The multi-model mean - using projections from all 5 General Circulation Models (GCMs) - was calculated for riverine flood. The 95th percentile was selected for coastal flood. Both maps show floods with a 10-year return period, i.e. 10% Annual Exceedance Probability (AEP). Version #2 of Aqueduct Floods - released 10/2020 - was used.


### High-resolution flood modelling over the Seine river basin (TRI)

What you see below is the extent of flood under scenario 1.4, dubbed "extreme", as seen in a geobrowser. Darker colors depict higher levels of flood.

![Image2](/image001.jpg)

###### The [TRI map](http://www.driee.ile-de-france.developpement-durable.gouv.fr/tri-de-la-metropole-francilienne-a1769.html) for the Paris region (Territoires à risque important d’inondation, métropole francilienne) was built by the Préfecture d'Île-de-France and DRIEAT with support from French research laboratories. Documentation is available [here](http://webissimo.developpement-durable.gouv.fr/IMG/pdf/20170209_atlas_idf_a3_paysage_document_principal_cle5be11d.pdf).



### Web application: an interactive map for climate hazards, biodiversity-rich areas and critical infrastructure

###### Just before this snapshot was taken, a bunch of layers for the South-Eastern region of France were selected.

###### A dashboard in another tab computes statistics on the exposure of infrastructure to the climate hazard selected by the user.

![Image3](/snap_app.png)

###### Data for this web app comes from various data plaforms managed by services of the French administration ([DataSud](https://www.datasud.fr/), [GeoIDE](http://carto.geo-ide.application.developpement-durable.gouv.fr/1131/environnement.map), [GeoRisques](https://www.georisques.gouv.fr/donnees/bases-de-donnees)) and from the International Union for Conservation of Nature's (IUCN) World Database on Protected Areas [(WDPA)](https://www.iucn.org/theme/protected-areas/our-work/quality-and-effectiveness/world-database-protected-areas-wdpa). 
###### Base layers are provided by OpenStreetMap and Stamen.





