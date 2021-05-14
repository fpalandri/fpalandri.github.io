What you will find here are a few examples of physical climate risk maps. _- This webpage is under development -_

##### They display several climate hazards at different points across space, time, climate scenarios, climate models and probability distributions. I made these maps for research purposes using open-source data and computer programs I wrote.


### Drought risk for power plants (CNRM - CLIMSEC)

These maps show the change in the drought index in France in winter over time (columns) and across climate scenarios (rows).

![Image4](/drought.png)

###### The lower the SPI (Standardized Precipitation Index), the more severe the drought. Drought was modelled by CNRM (Centre National de Recherches Météorologiques, led by Météo-France and CNRS) under the [CLIMSEC project](http://www.umr-cnrm.fr/spip.php?article605) (documentation is [here](http://www.umr-cnrm.fr/IMG/pdf/2011_fmaif_rapport_final_v2.2.pdf)) and made available via [DRIAS](http://www.drias-climat.fr/accompagnement/sections/187). C-MIP4 simulations and CNRM's hydrometeorological model were used. 

###### Whenever data was available, I computed the multi-model mean (i.e. mean of respective changes in SPI as projected by CNRM-ARPEGE, MPI-ECHAM5 and CCCMA-CGCM3). 

###### Power-plant data comes from WRI's [Global Power Plant Database](https://datasets.wri.org/dataset/globalpowerplantdatabase).



### Flood hazard maps - (WRI - Aqueduct)

These maps of India and the Netherlands show the extent of a flood that will have a 1/10 chance of occurring in any given year around the 2050 horizon, according to a climate simulations run using scenario RCP 8.5.

![Image1](/map_india.png)

![Image1](/map_nl.png)

###### Data for this map comes from the [Aqueduct Floods](https://www.wri.org/aqueduct/floods) research programme, conducted by the World Resources Institute (WRI) & a consortium of partners. Relevant documentation is [here](https://www.wri.org/research/aqueduct-floods-methodology).

###### Flood risk linked to subsidence was included. For riverine flood, I calculated the multi-model mean using projections from all 5 available General Circulation Models (GCMs). For coastal flood, I selected the 95th percentile value, singled out as default by WRI. Both maps show floods with a 10-year return period, i.e. a 10% Annual Exceedance Probability (AEP). 1-(0.9^10) ≈ 0.65 <=> A flood associated with a 10% AEP is 65% likely to occur in any 10-year period.

###### Version #2 of Aqueduct Floods - released 10/2020 - was used.


### High-resolution flood modelling over the Seine river basin (TRI)

What you see below is the extent of flood under scenario 1.4, dubbed "extreme", as seen in a geobrowser. I used darker colors to depict higher levels of flood.

![Image2](/paris.jpg)

###### The [TRI map](http://www.driee.ile-de-france.developpement-durable.gouv.fr/tri-de-la-metropole-francilienne-a1769.html) for the Paris region (Territoires à risque important d’inondation, métropole francilienne) was built by the Préfecture d'Île-de-France and DRIEAT with support from French research laboratories. Documentation is available [here](http://webissimo.developpement-durable.gouv.fr/IMG/pdf/20170209_atlas_idf_a3_paysage_document_principal_cle5be11d.pdf).



### Web application: an interactive map for climate hazards, biodiversity-rich areas and critical infrastructure

###### Just before this snapshot was taken, a bunch of map layers for the South-Eastern region of France were selected.

###### A dashboard I set up in another tab of this app computes statistics on the exposure of infrastructure to the climate hazard selected by the user.

![Image3](/snap_app.png)

###### Data for this web app comes from several data plaforms managed by services of the French administration ([DataSud](https://www.datasud.fr/), [GeoIDE](http://carto.geo-ide.application.developpement-durable.gouv.fr/1131/environnement.map), [GeoRisques](https://www.georisques.gouv.fr/donnees/bases-de-donnees)) and from the International Union for Conservation of Nature's (IUCN) World Database on Protected Areas [(WDPA)](https://www.iucn.org/theme/protected-areas/our-work/quality-and-effectiveness/world-database-protected-areas-wdpa). 
###### Base layers are provided by OpenStreetMap and Stamen.





