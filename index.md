Here are a few examples of maps showing climate hazards. They display different hazards at different points across space, time - and across climate scenarios, climate models and probability distributions. 

These maps were made for research purposes using code I wrote in `R` and open-source data (references below).

*webpage under development*

### Flood hazard map

Data for this map comes from the Aqueduct Floods research programme, conducted by the World Resources Institute (WRI) & a consortium of partners. What you see below is the extent of flood that will have a 1/10 chance of occurring in any given year (10-year return period) in India and Pakistan around the 2050 horizon and according to a RCP 8.5 scenario.

![Image1](/map_india.png)

WRI made all technical information available [here](https://www.wri.org/aqueduct/floods).

###### The map below was generated using the same source (Aqueduct Floods version 2) and parameters (RCP 8.5, 2050, 10% Annual Exceedance Probability). Flood risk linked to subsidence was included. The multi-model mean - using projections from all 5 General Circulation Models (GCMs) - was calculated for riverine risk, and the 95th percentile was selected for coastal risk. Version #2 of Aqueduct Floods - launched 10/2020 - was used.

![Image1](/map_nl.png)



### High-resolution flood modelling over the Seine river basin

The TRI map for the Paris region (Territoires à risque important d’inondation, métropole francilienne) was produced by services of the French administration: Préfecture d'Île-de-France and DRIEAT (Direction régionale et interdépartementale de l'Environnement, de l'Aménagement et des Transports d'Île-de-France). 

What you see below is the extent of flood under scenario 1.4, dubbed "extreme" - as seen in a geobrowser. Darker colors depict higher levels of flood.

Documentation for this data source is available [here](http://www.driee.ile-de-france.developpement-durable.gouv.fr/tri-de-la-metropole-francilienne-a1769.html).

##### Small text bold

![Image2](/image001.jpg)


### Web app

This snapshot is of a web application I coded using data made available by the French administration. A dashboard in another tab computes statistics on the hazard exposure of assets.

![Image3](/snap_app.png)
