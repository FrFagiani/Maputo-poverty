# Maputo poverty profiles

The goal of this project is to identify and assign a poverty level for each morphological area in the Greater Maputo.
There is not an existing detailed map of poverty in Maputo, but literature identify many factors that are strictly related to wealth, in Sub-Saharan countries, but also for the peculiar case of Maputo.

To define the wealth level, we consider some factors that influence the poverty rate and that affect single family and their houses or the entire neighbour in which they are sited. Some factors are related to neighbourhood rate of services and accessibility, and other to single family availability, resources, and income. 

Here the complete list.

- access to drinking water at home
- adequate sanitation at home
- source of reliable energy
- access to information and communication technology
- access to public transport
- access to CBD (Central Business District)
- access to health facilities
- access to education system

- having a permanent source of income or savings
- house construction material
- building density
- infrastructure density
- access to real estate market (affordable houses)

- Informal business
- Financial services


### Access to health system

Used the isochrone to define access to health facilities, giving a differend score according to health hierarchy and walking time distance.

Should we also add pharmacy?

### Access to education system

Used the isochrone to define access to education system, giving a differend score according to school level and walking time distance.

### Access to water

In order to define the access to water we considered water point (AdeM) and water network. The only one report to provide spatial dimension for water sources has been developed in 2011. Worl Bank developed a detailed map of water point in Beira, but no updated information has been found for Maputo.

Chen, G. (2017, July 19). Shared toilets as the path to health and dignity. World Bank: https://blogs.worldbank.org/water/shared-toilets-path-health-and-dignity

Club of Mozambique. (2020, February 11). Club of Mozambique: FIPAG promises to bring Maputo water supply to 40 per cent – AIM report: https://clubofmozambique.com/news/mozambique-fipag-promises-to-bring-maputo-water-supply-to-40-per-cent-aim-report-152353/

Chaponniere, E., & Collignon, B. (2011). PPP with local informal providers aimed at improving water supply in the peri-urban areas of Maputo, Mozambique. WEDC, Loughborough University.

### Access to CBD

According woth World Bank report, the access to the central business district (CBD) o f Maputo is really important and influence also real estate market and some gentrification process ongoing in greater Maputo.
We consider access to CBD not just simply as distance, but also considering the level of connection by public transport.

### Source of reliable energy

We considered two main source of data: Facebook energy map and NASA night light map.
For both we applied a score for the single HRSL pixel and then aggregate the result for morphological area. The final result is a range 1-10 for access to energy given by the average night lights per HRSL from FB map and night light NASA (blue band) per HRSL.
Both the sources has a very low detailed, so it is difficult to provide proper results.
>Building Electrical Grid Maps begins by taking monthly images from the VIIRS satellite, and creating a composite. We then apply a custom image processing filter to remove background and reflected light, and identify locations that consistently demonstrate night-time lighting. These then serve as a proxy for the existence of grid electricity. Using known electrical grids as templates based on data available from energydata.info, we employ a custom algorithm to connect the communities and infer grid paths based on their likelihood to follow roads, avoid water, and follow the shortest paths possible. For more technical information about this methodology, visit: https://code.fb.com/connectivity/electrical-grid-mapping/

Facebook Engineering. (2019, January 25). A new predictive model for more accurate electrical grid mapping. Tratto da Facebook Engineering: https://engineering.fb.com/connectivity/electrical-grid-mapping/

### Financial services
Consider the presence of ATM points and POS operation, in some way identify commercial areas and concentration of formal commerce (much rich)

Sousa, S. (2018, December 7). Street food in Maputo, Mozambique: availability and nutritional value of homemade foods. Nutrition and health, p. 37-46.

### House material
The world bank report divide houses in two category for construction material: durable and non-durable.
Not considered

### Urban morphology
### Roof material
### Infrastructure density
### Services/POI density

## References

World Bank. 2017. Greater Maputo : Urban Poverty and Inclusive Growth. World Bank, Washington, DC. © World Bank.

Jones, S., Egger, E.-M., & Santos, R. (2020, April 21). Analysis: The five criteria low income countries must have in place for lockdowns to work. Tratto da Club of Mozambique: https://clubofmozambique.com/news/analysis-the-five-criteria-low-income-countries-must-have-in-place-for-lockdowns-to-work-158244/
