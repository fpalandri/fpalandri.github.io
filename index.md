Here are a few examples of maps showing climate hazards. They display different hazards at different points across space and time - and also across climate scenarios, climate models and probability distributions. 

These maps were made for research purposes using open-source data (references below) and code I wrote in `R`.

*webpage under development*

### Flood hazard map

Data for this map comes from the [Aqueduct Floods](https://www.wri.org/aqueduct/floods) research programme, conducted by the World Resources Institute (WRI) & a consortium of partners. What you see below is the extent of flood that will have a 1/10 chance of occurring in any given year (10-year return period) in India and Pakistan around the 2050 horizon and according to climate simulations run using scenario RCP 8.5.

![Image1](/map_india.png)

##### WRI made all technical information available [here](https://www.wri.org/research/aqueduct-floods-methodology).

###### The map below was generated using the same source (Aqueduct Floods version 2) and same parameters (RCP 8.5, 2050, 10% Annual Exceedance Probability). Flood risk linked to subsidence was included. The multi-model mean - using projections from all 5 General Circulation Models (GCMs) - was calculated for riverine risk, and the 95th percentile was selected for coastal risk. Version #2 of Aqueduct Floods - released 10/2020 - was used.

![Image1](/map_nl.png)



### High-resolution flood modelling over the Seine river basin

Flood risk was modelled by services of the French administration at an ultra-high resolution. What you see below is the extent of flood under scenario 1.4, dubbed "extreme" - as seen in a geobrowser. Darker colors depict higher levels of flood.

![Image2](/image001.jpg)

##### The [TRI map](http://www.driee.ile-de-france.developpement-durable.gouv.fr/tri-de-la-metropole-francilienne-a1769.html) for the Paris region (Territoires à risque important d’inondation, métropole francilienne) was produced by the Préfecture d'Île-de-France and DRIEAT (Direction régionale et interdépartementale de l'Environnement, de l'Aménagement et des Transports d'Île-de-France). Documentation for this data source is available [here](http://webissimo.developpement-durable.gouv.fr/IMG/pdf/20170209_atlas_idf_a3_paysage_document_principal_cle5be11d.pdf).



### Web application: an interactive hazard map showing critical infrastructure

What you see below is a snapshot of a web application I developed using open source data on climate hazards and open source geographic coordinates for critical energy & industry infrastructure. 

A dashboard in another tab computes statistics on the exposure of local infrastructure to hazards. Below, a bunch of layers for the South-Eastern region of France are selected.

![Image3](/snap_app.png)

##### Data is from various plaforms managed by services of the French administration ([DataSud](https://www.datasud.fr/), [GeoIDE](http://carto.geo-ide.application.developpement-durable.gouv.fr/1131/environnement.map), [GeoRisques](https://www.georisques.gouv.fr/donnees/bases-de-donnees)). Base layers are from OpenStreetMap and Stamen.









