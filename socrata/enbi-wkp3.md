# SDOT Pavement Moratoriums

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pavement-moratorium-c11ca) |
| Metadata | [Link](https://data.seattle.gov/api/views/enbi-wkp3) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/enbi-wkp3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/enbi-wkp3/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | enbi-wkp3 |
| Name | SDOT Pavement Moratoriums |
| Category | Transportation |
| Tags | sdot, transportation, streets, construction, agencies, row, right-of-way, pavement, moratoriums |
| Created | 2012-10-29T21:42:16Z |
| Publication Date | 2012-12-10T16:41:52Z |

## Description

Displays the pavement moratoriums based on status. This layer supports SDOT Director?s Rule 5-2009 which includes a three-year moratorium on opening new pavement except under certain circumstances.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type  | Render Type |
| ======== | ============== | ================= | ================= | ========== | =========== |
| No       |                | shape             | Shape             | geospatial | geospatial  |
| Yes      | series tag     | objectid          | OBJECTID          | text       | number      |
| Yes      | series tag     | mora_status       | MORA_STATUS       | text       | text        |
| Yes      | series tag     | mrtrmstat         | MRTRMSTAT         | text       | text        |
| Yes      | time           | mora_start_date   | MORA_START_DATE   | date       | date        |
| No       |                | mora_expire_date  | MORA_EXPIRE_DATE  | date       | date        |
| Yes      | series tag     | mora_project_name | MORA_PROJECT_NAME | text       | text        |
| Yes      | series tag     | mora_block_id     | MORA_BLOCK_ID     | text       | text        |
| Yes      | series tag     | mora_geobasys_id  | MORA_GEOBASYS_ID  | text       | number      |
| Yes      | series tag     | block_descr       | BLOCK_DESCR       | text       | text        |
| Yes      | numeric metric | compkey           | COMPKEY           | number     | number      |
| Yes      | numeric metric | shape_length      | Shape_Length      | number     | number      |
```

## Time Field

```ls
Value = mora_start_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = shape,mora_expire_date
```

## Data Commands

```ls
series e:enbi-wkp3 d:2015-03-05T00:00:00.000Z t:shape.longitude=-122.38197394999997 t:shape.needs_recoding=false t:mrtrmstat=No t:shape.latitude=47.64658658500008 t:mora_geobasys_id=10750020 t:mora_status=CURRENT t:objectid=1 t:block_descr="20TH AVE W BETWEEN THORNDYKE AVE W AND W DRAVUS ST" m:shape_length=682.5813745211697 m:compkey=3090

series e:enbi-wkp3 d:2007-01-01T00:00:00.000Z t:shape.longitude=-122.37365962999996 t:shape.needs_recoding=false t:mrtrmstat=No t:shape.latitude=47.550129318000074 t:mora_geobasys_id=23950040 t:mora_status=CURRENT t:objectid=2 t:block_descr="32ND AVE SW BETWEEN SW JUNEAU ST AND SW RAYMOND ST" m:shape_length=664.1625201928889 m:compkey=5051

series e:enbi-wkp3 d:2014-09-03T00:00:00.000Z t:shape.longitude=-122.28094162499997 t:shape.needs_recoding=false t:mrtrmstat=No t:shape.latitude=47.67797343800004 t:mora_geobasys_id=35800010 t:mora_status=CURRENT t:objectid=3 t:block_descr="44TH PL NE BETWEEN 44TH AVE NE AND NE 70TH ST" m:shape_length=621.3186243837863 m:compkey=6779
```

## Meta Commands

```ls
metric m:compkey p:integer l:COMPKEY d:COMPKEY t:dataTypeName=number

metric m:shape_length p:long l:Shape_Length d:Shape_Length t:dataTypeName=number

entity e:enbi-wkp3 l:"SDOT Pavement Moratoriums" t:url=https://data.seattle.gov/api/views/enbi-wkp3

property e:enbi-wkp3 t:meta.view v:id=enbi-wkp3 v:category=Transportation v:averageRating=0 v:name="SDOT Pavement Moratoriums"

property e:enbi-wkp3 t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:enbi-wkp3 t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| shape                                                                                                                                                                                                                                                                                                                                                                                                                | objectid | mora_status | mrtrmstat | mora_start_date | mora_expire_date | mora_project_name | mora_block_id | mora_geobasys_id | block_descr                                               | compkey | shape_length                                      | 
| ==================================================================================================================================================================================================================================================================================================================================================================================================================== | ======== | =========== | ========= | =============== | ================ | ================= | ============= | ================ | ========================================================= | ======= | ================================================= | 
| [null, 47.64658658500008, -122.38197394999997, null, false, {paths=[[[-122.38197394999997, 47.64658658500008], [-122.38198155999999, 47.64845786600006]]]}]                                                                                                                                                                                                                                                          | 1        | CURRENT     | No        | 1425513600      | 1583366400       |                   |               | 10750020         | 20TH AVE W BETWEEN THORNDYKE AVE W AND W DRAVUS ST        | 3090    | 682.581374521169664149056188762187957763671875    | 
| [null, 47.550129318000074, -122.37365962999996, null, false, {paths=[[[-122.37365962999996, 47.550129318000074], [-122.37368759499998, 47.54830862000006]]]}]                                                                                                                                                                                                                                                        | 2        | CURRENT     | No        | 1167609600      | 3692217600       |                   |               | 23950040         | 32ND AVE SW BETWEEN SW JUNEAU ST AND SW RAYMOND ST        | 5051    | 664.162520192888905512518249452114105224609375    | 
| [null, 47.67797343800004, -122.28094162499997, null, false, {paths=[[[-122.28094162499997, 47.67797343800004], [-122.280940768, 47.67805055300005], [-122.28092547399996, 47.67809949300005], [-122.28084933499997, 47.67815670600004], [-122.28037000799998, 47.678290282000034], [-122.28032068199997, 47.678313407000076], [-122.28027229399999, 47.67837026600006], [-122.28029228199995, 47.67941313000006]]]}] | 3        | CURRENT     | No        | 1409702400      | 1567468800       |                   |               | 35800010         | 44TH PL NE BETWEEN 44TH AVE NE AND NE 70TH ST             | 6779    | 621.318624383786300313659012317657470703125       | 
| [null, 47.60723100700005, -122.32781844699997, null, false, {paths=[[[-122.32781844699997, 47.60723100700005], [-122.32847075299998, 47.60794452500005]]]}]                                                                                                                                                                                                                                                          | 4        | CURRENT     | No        | 1405468800      | 1563235200       |                   | 08-09         | 47850090         | 8TH AVE BETWEEN MARION ST AND MADISON ST                  | 8275    | 305.99172173932674922980368137359619140625        | 
| [null, 47.58831285400004, -122.395504142, null, false, {paths=[[[-122.395504142, 47.58831285400004], [-122.39816974299998, 47.586011178000035]]]}]                                                                                                                                                                                                                                                                   | 5        | CURRENT     | No        | 1438819200      | 1596672000       | WO #320578        |               | 50950050         | ALKI AVE SW BETWEEN SW HAMPSHIRE ST AND SW ILLINOIS ST    | 8786    | 1066.578921288450146676041185855865478515625      | 
| [null, 47.54668273900006, -122.38719538199996, null, false, {paths=[[[-122.38719538199996, 47.54668273900006], [-122.38720232899999, 47.54603416100008]]]}]                                                                                                                                                                                                                                                          | 6        | CURRENT     | No        | 1375228800      | 1532995200       |                   |               | 57900350         | CALIFORNIA AVE SW BETWEEN SW GRAHAM ST AND SW EDDY ST     | 9563    | 236.58444630409923092884127981960773468017578125  | 
| [null, 47.523297024000044, -122.36049011999995, null, false, {paths=[[[-122.36049011999995, 47.523297024000044], [-122.36009936199997, 47.522861343000045]]]}]                                                                                                                                                                                                                                                       | 7        | CURRENT     | No        | 1385510400      | 1543276800       |                   |               | 63200300         | DELRIDGE WAY SW BETWEEN 21ST S AVE SW AND SW HENDERSON ST | 9988    | 185.950153761741461266865371726453304290771484375 | 
| [null, 47.68474778900003, -122.35529822399997, null, false, {paths=[[[-122.35529822399997, 47.68474778900003], [-122.35529869399994, 47.68548556300004]]]}]                                                                                                                                                                                                                                                          | 8        | CURRENT     | No        | 1340928000      | 1498694400       |                   |               | 71050470         | GREENWOOD AVE N BETWEEN N 77TH ST AND N 78TH ST           | 10744   | 269.1148130400180207288940437138080596923828125   | 
| [null, 47.69698666900007, -122.371407998, null, false, {paths=[[[-122.371407998, 47.69698666900007], [-122.37006477099999, 47.69766850100007]]]}]                                                                                                                                                                                                                                                                    | 9        | CURRENT     | No        | 1414713600      | 1572480000       |                   |               | 73600070         | HOLMAN RD NW BETWEEN 12TH AVE NW AND 11TH AVE NW          | 10941   | 413.84641722183499723541899584233760833740234375  | 
| [null, 47.51827120400003, -122.27102538999998, null, false, {paths=[[[-122.27102538999998, 47.51827120400003], [-122.27087934499997, 47.51805305100004]]]}]                                                                                                                                                                                                                                                          | 10       | CURRENT     | No        | 1462752000      | 1620518400       |                   |               | 94250450         | RENTON AVE S BETWEEN S CAMBRIDGE ST AND 50TH AVE S        | 12528   | 87.3756885983591047306617838330566883087158203125 | 
```