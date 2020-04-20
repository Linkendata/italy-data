![Image of Linkendata](https://linkendata.it/wp-content/uploads/2019/12/logo-linkendata-55.png)<br>
https://linkendata.it
<br>
[![GitHub commit](https://img.shields.io/github/last-commit/Linkendata/italy-data)](https://github.com/Linkendata/italy-data/commits/master) 

**Data Sources** 

* [ISTAT](http://dati.istat.it/Index.aspx?QueryId=18460#)
* [tuttitalia.it](https://www.tuttitalia.it/province/)

## italy-data

The purpose of this repository is to provide italian data in json format, which can be used for the development 
of web applications.<br>
Linkendata assumes no responsibility about the validity of the data and for any damage caused by its use.<br>

**provinces.json** <br>
This file provide the relatives datas for each italian region:
```
|
|-- region_code         // Code of the Region (ISTAT 2019)
|   name                // Name of the Region
|   population          // Population (ISTAT 2019)
|-- provinces
    |--  code           // Code of the Province (ISTAT 2019)
         name           // Name of the Province (ISTAT 2019)
         tag            // Province Abbreviation
         population     // Population of the Province (ISTAT 2019)
         area           // Area in square kilometers (Source https://tuttitalia.it)
 ```
