## [](#header-2) Selected projects

## [](#header-2) 1. City Prosperity Initiative (CPI)

This program aims to measure and monitor sustainable urban development spatially and comparably for city authorities to identify opportunities and potential areas of intervention from six dimensions: productivity, infrastructure development, quality of life, equity and social inclusion, environmental sustainability, urban governance and legislation.

> pic is coming.


## [](#header-2) 2. Advanced Spatial Analysis of Urban Buildings 

This program focuses on exploring the distributions and interactions between buildings, populations, public facilities, and urban planning to assist the city decision-makers to improve housing affordability and public facility allocation.
Below is one example of the application.

![](https://github.com/SmartWang18/Changzhen/blob/master/img/buildings.png)
> The relationship between actual FAR and FAR baseline


## [](#header-2) 3. Land Use Integrated Management Information System 

This novel web-based system aims to provide large-scale data and powerful tools for urban planners and city manager to analyze and visualize land use and urban planning issues. Currently, it has 148 layers, 12 tools and 100 active group users from 40 institutions.

![](http://www.wlsp.org.cn/UploadFiles/Images//admin/201604/%E7%B3%BB%E7%BB%9F%E6%88%AA%E5%9B%BE.jpg.axd)
> data source: http://www.wlsp.org.cn/


## [](#header-2) 4. One Map of Wuhan Econ Tech. Development Zone 

The system integrates multi-source data from Wuhan Econ & Tech. Development Zone into one map, and provide technical support for decision-makers to track the changes of approval and illegal land use for housing and road. 

![](http://www.wlsp.org.cn/UploadFiles/Images//admin/201710/%E6%AD%A6%E6%B1%89%E5%BC%80%E5%8F%91%E5%8C%BA%EF%BC%88%E6%B1%89%E5%8D%97%E5%8C%BA%EF%BC%89%E7%BB%BC%E5%90%88%E4%B8%80%E5%BC%A0%E5%9B%BE%E7%B3%BB%E7%BB%9F%E6%88%AA%E5%9B%BE1_%E5%89%AF%E6%9C%AC.jpg.axd)
> data source: http://www.wlsp.org.cn/

![](http://www.wlsp.org.cn/UploadFiles/Images//admin/201710/%E6%AD%A6%E6%B1%89%E5%BC%80%E5%8F%91%E5%8C%BA%EF%BC%88%E6%B1%89%E5%8D%97%E5%8C%BA%EF%BC%89%E7%BB%BC%E5%90%88%E4%B8%80%E5%BC%A0%E5%9B%BE%E7%B3%BB%E7%BB%9F%E6%88%AA%E5%9B%BE4_%E5%89%AF%E6%9C%AC.jpg.axd)
> data source: http://www.wlsp.org.cn/


## [](#header-2) 5. Spatial Study of Religion 
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

