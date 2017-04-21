# Crime & Safety (2010-2014)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/crime-safety-2010-2013) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/qmw9-b8ep) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/qmw9-b8ep/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/qmw9-b8ep/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | qmw9-b8ep |
| Name | Crime & Safety (2010-2014) |
| Attribution | The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI) |
| Category | Neighborhoods |
| Tags | crime, bnia |
| Created | 2015-05-14T19:58:08Z |
| Publication Date | 2016-04-15T15:33:29Z |

## Description

All crime data for Vital Signs indicators are provided by the Baltimore City Police Department. BNIA-JFI normalizes this data by population to establish crime rates. Normalizing data allows for the rates to reflect the concentration of the crime relative to the population in the area and allows for comparison between areas of different populations.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | neighborhood | Neighborhood | text      | text        |
| Yes      | numeric metric | crime10      | crime10      | number    | number      |
| Yes      | numeric metric | crime11      | crime11      | number    | number      |
| Yes      | numeric metric | crime12      | crime12      | number    | number      |
| Yes      | numeric metric | crime13      | crime13      | number    | number      |
| Yes      | numeric metric | crime14      | crime14      | number    | number      |
| Yes      | numeric metric | viol10       | viol10       | number    | number      |
| Yes      | numeric metric | viol11       | viol11       | number    | number      |
| Yes      | numeric metric | viol12       | viol12       | number    | number      |
| Yes      | numeric metric | viol13       | viol13       | number    | number      |
| Yes      | numeric metric | viol14       | viol14       | number    | number      |
| Yes      | numeric metric | prop11       | prop11       | number    | number      |
| Yes      | numeric metric | prop12       | prop12       | number    | number      |
| Yes      | numeric metric | prop13       | prop13       | number    | number      |
| Yes      | numeric metric | prop14       | prop14       | number    | number      |
| Yes      | numeric metric | juvarr11     | juvarr11     | number    | number      |
| Yes      | numeric metric | juvviol11    | juvviol11    | number    | number      |
| Yes      | numeric metric | juvdrug11    | juvdrug11    | number    | number      |
| Yes      | numeric metric | domvio10     | domvio10     | number    | number      |
| Yes      | numeric metric | domvio11     | domvio11     | number    | number      |
| Yes      | numeric metric | domvio12     | domvio12     | number    | number      |
| Yes      | numeric metric | shoot11      | shoot11      | number    | number      |
| Yes      | numeric metric | shoot12      | shoot12      | number    | number      |
| Yes      | numeric metric | caslt11      | caslt11      | number    | number      |
| Yes      | numeric metric | caslt12      | caslt12      | number    | number      |
| Yes      | numeric metric | narc11       | narc11       | number    | number      |
| Yes      | numeric metric | narc12       | narc12       | number    | number      |
| Yes      | numeric metric | caracc11     | caracc11     | number    | number      |
| Yes      | numeric metric | caracc12     | caracc12     | number    | number      |
| Yes      | numeric metric | gunhom11     | gunhom11     | number    | number      |
| Yes      | numeric metric | gunhom12     | gunhom12     | number    | number      |
| Yes      | numeric metric | gunhom13     | gunhom13     | number    | number      |
| Yes      | numeric metric | gunhom14     | gunhom14     | number    | number      |
| Yes      | numeric metric | arrest14     | arrest14     | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qmw9-b8ep d:2010-01-01T00:00:00.000Z t:neighborhood="Allendale/Irvington/S. Hilton" m:crime11=46.2 m:gunhom13=0.4 m:crime12=45.4 m:gunhom14=0.4 m:crime10=40.6 m:crime13=47.3 m:crime14=55.1 m:prop14=44.5 m:juvdrug11=22.2 m:caslt12=79.7 m:caslt11=84.4 m:prop12=31.6 m:prop13=33.9 m:viol10=12.6 m:prop11=33.7 m:gunhom11=0.2 m:shoot12=2.3 m:gunhom12=0.6 m:viol13=12.6 m:viol14=10.1 m:viol11=12.5 m:viol12=13.9 m:arrest14=34.5 m:juvarr11=54.8 m:narc11=78.8 m:narc12=79.7 m:juvviol11=12.4 m:domvio11=65.4 m:domvio12=61 m:caracc11=44 m:caracc12=43 m:domvio10=59.4 m:shoot11=2.5

series e:qmw9-b8ep d:2010-01-01T00:00:00.000Z t:neighborhood="Beechfield/Ten Hills/West Hills" m:crime11=36.1 m:gunhom13=0 m:crime12=36.6 m:gunhom14=0.1 m:crime10=33.6 m:crime13=36 m:crime14=46.6 m:prop14=38.7 m:juvdrug11=5.3 m:caslt12=50.6 m:caslt11=51.2 m:prop12=29.6 m:prop13=28.7 m:viol10=8.4 m:prop11=28.9 m:gunhom11=0.2 m:shoot12=1.1 m:gunhom12=0.2 m:viol13=6.4 m:viol14=6.9 m:viol11=7.2 m:viol12=7 m:arrest14=16.5 m:juvarr11=22 m:narc11=24.7 m:narc12=32.6 m:juvviol11=9.1 m:domvio11=44.8 m:domvio12=42.4 m:caracc11=31.9 m:caracc12=29.8 m:domvio10=47.9 m:shoot11=2

series e:qmw9-b8ep d:2010-01-01T00:00:00.000Z t:neighborhood=Belair-Edison m:crime11=57.1 m:gunhom13=0.5 m:crime12=52.7 m:gunhom14=0.3 m:crime10=50.3 m:crime13=57.4 m:crime14=56.6 m:prop14=45.4 m:juvdrug11=16.2 m:caslt12=81.5 m:caslt11=77.6 m:prop12=37.7 m:prop13=43.3 m:viol10=13.3 m:prop11=43 m:gunhom11=0.3 m:shoot12=2.2 m:gunhom12=0.3 m:viol13=12.3 m:viol14=10.2 m:viol11=14.1 m:viol12=14.9 m:arrest14=41.6 m:juvarr11=54.8 m:narc11=50.2 m:narc12=53.9 m:juvviol11=17.5 m:domvio11=57.8 m:domvio12=60.9 m:caracc11=45.4 m:caracc12=46.1 m:domvio10=51.1 m:shoot11=1.5
```

## Meta Commands

```ls
metric m:crime10 p:float l:crime10 t:dataTypeName=number

metric m:crime11 p:float l:crime11 t:dataTypeName=number

metric m:crime12 p:float l:crime12 t:dataTypeName=number

metric m:crime13 p:float l:crime13 t:dataTypeName=number

metric m:crime14 p:float l:crime14 d:"Part 1 Crime Rate per 1,000 Residents (2014)" t:dataTypeName=number

metric m:viol10 p:float l:viol10 t:dataTypeName=number

metric m:viol11 p:float l:viol11 t:dataTypeName=number

metric m:viol12 p:float l:viol12 t:dataTypeName=number

metric m:viol13 p:float l:viol13 t:dataTypeName=number

metric m:viol14 p:float l:viol14 d:"Violent Crime Rate per 1,000 Residents (2014)" t:dataTypeName=number

metric m:prop11 p:float l:prop11 t:dataTypeName=number

metric m:prop12 p:float l:prop12 t:dataTypeName=number

metric m:prop13 p:float l:prop13 t:dataTypeName=number

metric m:prop14 p:float l:prop14 d:"Property Crime Rate per 1,000 Residents (2014)" t:dataTypeName=number

metric m:juvarr11 p:float l:juvarr11 t:dataTypeName=number

metric m:juvviol11 p:float l:juvviol11 t:dataTypeName=number

metric m:juvdrug11 p:float l:juvdrug11 t:dataTypeName=number

metric m:domvio10 p:float l:domvio10 t:dataTypeName=number

metric m:domvio11 p:float l:domvio11 t:dataTypeName=number

metric m:domvio12 p:float l:domvio12 d:"Domestic Violence Calls For Service per 1,000 Residents (2012)" t:dataTypeName=number

metric m:shoot11 p:float l:shoot11 t:dataTypeName=number

metric m:shoot12 p:float l:shoot12 d:"Number of Shootings per 1,000 Residents (2012)" t:dataTypeName=number

metric m:caslt11 p:float l:caslt11 t:dataTypeName=number

metric m:caslt12 p:float l:caslt12 d:"Number of Common Assault Calls for Service per 1,000 Residents (2012)" t:dataTypeName=number

metric m:narc11 p:float l:narc11 t:dataTypeName=number

metric m:narc12 p:float l:narc12 d:"Number of Narcotics Calls for Service per 1,000 Residents (2012)" t:dataTypeName=number

metric m:caracc11 p:float l:caracc11 t:dataTypeName=number

metric m:caracc12 p:float l:caracc12 d:"Number of Automobile Accident Calls for Service per 1,000 Residents (2012)" t:dataTypeName=number

metric m:gunhom11 p:float l:gunhom11 t:dataTypeName=number

metric m:gunhom12 p:float l:gunhom12 t:dataTypeName=number

metric m:gunhom13 p:float l:gunhom13 t:dataTypeName=number

metric m:gunhom14 p:float l:gunhom14 d:"Rate of Gun Homicides per 1,000 Residents (2014)" t:dataTypeName=number

metric m:arrest14 p:float l:arrest14 d:"Number of Adult Arrests per 1,000 Residents (Over Age of 18) (2014)" t:dataTypeName=number

entity e:qmw9-b8ep l:"Crime & Safety (2010-2014)" t:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)" t:url=https://data.baltimorecity.gov/api/views/qmw9-b8ep

property e:qmw9-b8ep t:meta.view v:id=qmw9-b8ep v:category=Neighborhoods v:attributionLink=http://bniajfi.org v:averageRating=0 v:name="Crime & Safety (2010-2014)" v:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)"

property e:qmw9-b8ep t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:qmw9-b8ep t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:qmw9-b8ep t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| neighborhood                      | crime10 | crime11 | crime12 | crime13 | crime14 | viol10 | viol11 | viol12 | viol13 | viol14 | prop11 | prop12 | prop13 | prop14 | juvarr11 | juvviol11 | juvdrug11 | domvio10 | domvio11 | domvio12 | shoot11 | shoot12 | caslt11 | caslt12 | narc11 | narc12 | caracc11 | caracc12 | gunhom11 | gunhom12 | gunhom13 | gunhom14 | arrest14 | 
| ================================= | ======= | ======= | ======= | ======= | ======= | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======== | ========= | ========= | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ====== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | 
| Allendale/Irvington/S. Hilton     | 40.6    | 46.2    | 45.4    | 47.3    | 55.1    | 12.6   | 12.5   | 13.9   | 12.6   | 10.1   | 33.7   | 31.6   | 33.9   | 44.5   | 54.8     | 12.4      | 22.2      | 59.4     | 65.4     | 61.0     | 2.5     | 2.3     | 84.4    | 79.7    | 78.8   | 79.7   | 44.0     | 43.0     | 0.2      | 0.6      | 0.4      | 0.4      | 34.5     | 
| Beechfield/Ten Hills/West Hills   | 33.6    | 36.1    | 36.6    | 36.0    | 46.6    | 8.4    | 7.2    | 7.0    | 6.4    | 6.9    | 28.9   | 29.6   | 28.7   | 38.7   | 22.0     | 9.1       | 5.3       | 47.9     | 44.8     | 42.4     | 2.0     | 1.1     | 51.2    | 50.6    | 24.7   | 32.6   | 31.9     | 29.8     | 0.2      | 0.2      | 0.0      | 0.1      | 16.5     | 
| Belair-Edison                     | 50.3    | 57.1    | 52.7    | 57.4    | 56.6    | 13.3   | 14.1   | 14.9   | 12.3   | 10.2   | 43.0   | 37.7   | 43.3   | 45.4   | 54.8     | 17.5      | 16.2      | 51.1     | 57.8     | 60.9     | 1.5     | 2.2     | 77.6    | 81.5    | 50.2   | 53.9   | 45.4     | 46.1     | 0.3      | 0.3      | 0.5      | 0.3      | 41.6     | 
| Brooklyn/Curtis Bay/Hawkins Point | 81.7    | 79.1    | 62.1    | 61.3    | 54.9    | 25.3   | 21.3   | 15.2   | 16.1   | 14.1   | 57.8   | 46.9   | 43.7   | 40.1   | 83.3     | 16.8      | 30.8      | 68.0     | 74.1     | 63.5     | 2.9     | 2.1     | 158.5   | 144.6   | 101.1  | 85.0   | 39.9     | 39.6     | 0.3      | 0.2      | 0.1      | 0.2      | 94.1     | 
| Canton                            | 61.0    | 64.8    | 57.9    | 56.4    | 46.5    | 8.3    | 7.7    | 6.7    | 6.9    | 6.3    | 57.2   | 51.2   | 49.1   | 39.5   | 81.5     | 14.8      | 7.4       | 34.3     | 39.6     | 35.8     | 0.0     | 0.1     | 46.2    | 44.3    | 4.0    | 3.7    | 32.8     | 34.6     | 0.0      | 0.0      | 0.0      |          | 8.6      | 
| Cedonia/Frankford                 | 43.7    | 48.4    | 46.7    | 52.2    | 52.3    | 12.0   | 11.3   | 12.1   | 11.8   | 12.8   | 37.1   | 34.6   | 39.5   | 38.8   | 46.5     | 9.5       | 10.7      | 60.2     | 70.2     | 66.7     | 0.8     | 0.8     | 10.7    | 61.6    | 22.8   | 24.2   | 26.5     | 24.8     | 0.3      | 0.3      | 0.0      | 0.4      | 21.7     | 
| Cherry Hill                       | 60.0    | 64.7    | 59.1    | 50.6    | 53.5    | 22.6   | 22.2   | 19.6   | 16.2   | 15.5   | 42.6   | 39.5   | 33.2   | 37.1   | 61.6     | 13.8      | 29.4      | 62.9     | 71.1     | 78.6     | 6.0     | 5.2     | 110.2   | 125.1   | 97.4   | 94.6   | 25.2     | 21.6     | 0.5      | 0.4      | 0.4      | 0.1      | 77.0     | 
| Chinquapin Park/Belvedere         | 43.6    | 33.4    | 44.5    | 42.8    | 47.7    | 12.6   | 7.1    | 9.0    | 9.2    | 9.0    | 26.3   | 35.5   | 32.9   | 37.9   | 37.9     | 10.2      | 7.3       | 39.7     | 44.2     | 47.3     | 0.3     | 1.2     | 60.1    | 64.0    | 17.9   | 27.2   | 38.9     | 35.1     | 0.0      | 0.4      | 0.1      |          | 13.4     | 
| Claremont/Armistead               | 52.6    | 63.2    | 49.0    | 50.1    | 46.3    | 13.2   | 12.6   | 8.9    | 7.9    | 9.8    | 50.5   | 40.1   | 41.7   | 36.0   | 18.7     | 7.7       | 3.3       | 60.4     | 68.8     | 67.4     | 0.9     | 1.5     | 10.9    | 67.8    | 19.9   | 25.4   | 60.1     | 64.4     | 0.1      | 0.1      | 0.0      |          | 29.2     | 
| Clifton-Berea                     | 57.9    | 61.0    | 56.4    | 57.1    | 55.0    | 23.3   | 23.5   | 20.0   | 15.4   | 16.8   | 37.5   | 36.5   | 40.2   | 36.8   | 144.9    | 33.2      | 63.7      | 49.7     | 63.5     | 61.8     | 7.3     | 3.9     | 121.0   | 130.5   | 201.9  | 264.8  | 47.0     | 45.8     | 0.6      | 0.8      | 0.6      | 0.6      | 131.9    | 
```