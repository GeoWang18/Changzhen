
## [](#header-2)4. Spatial Study of Religion 
This platform integrates various data from economy, population and religion to provide tools for researchers.

Data:
* Extract religious data from 2004 Economic Census in China and classify them into Christianity, Buddhism, Islamism, and Taoism on the province, prefecture, county, and township level per year.
* Integrate data from 2010 Populcation Census in China and extract variables to write them into xml.
* Integrate data from 2004 Economic Census in China and extract variables to write them into xml.
* Integrate data from grid and compute any variables on each grid.
* Integrate OpenStreetMap into the platform.

Programming: 
* Integrate pySAL to compute spatial weight matrix and Moran's I statistics.
* Integrate scripts of C++ to compute global Geary's C, local Geary's C and local G statistics.
* Integrate GeoMap library to render the tiled web map.
* Java + Flex + BlaseDS + tomcat + postgreSQL/PostGIS.
* Geoserver is used to manage and public GIS services.

Below are some case studies from my master thesis.

![](https://github.com/SmartWang18/Changzhen/blob/master/img/ChristianityBuddhism.png)
> The number of Christianity and Buddhism sites in Mainland China, 2004

![](https://github.com/SmartWang18/Changzhen/blob/master/img/GlobalMoranI.png)
> Apply Global Moran's I to detect whether Christianity affected Buddhism or not

![](https://github.com/SmartWang18/Changzhen/blob/master/img/GlobalMoran2.png)
> Apply Global Moran's I to detect whether Buddhism affected Christianity or not

![](https://github.com/SmartWang18/Changzhen/blob/master/img/LocalGi.png)
> Apply Local Gi to detect hot spots of Buddhism in Zhejiang province

![](https://github.com/SmartWang18/Changzhen/blob/master/img/LocalGi2.png)
> Apply Local Gi to detect hot spots of Christianity in Zhejiang province
