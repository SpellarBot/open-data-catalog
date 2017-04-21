# Libraries - 2012 Circulation by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2012-circulation-by-location-847d3) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/jsdv-pwf2) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/jsdv-pwf2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/jsdv-pwf2/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | jsdv-pwf2 |
| Name | Libraries - 2012 Circulation by Location |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | performance metrics, libraries, circulation |
| Created | 2012-02-17T20:59:39Z |
| Publication Date | 2013-04-08T21:13:46Z |

## Description

Circulation figures include new checkouts as well as renewals. In January all branch locations were closed on Monday, January 9, Monday, January 23 and Monday, January 30. Beginning in February, all branch locations restored partial Monday hours, from 2 p.m. to 6 p.m. On June 18, all branch locations restored full Monday hours. Edgewater closed 6/16/11 for construction of a new branch scheduled to open in mid-2013. The library?s bookmobile opened 6/24/11 for Edgewater holds pickup and returns. Douglass closed for 10 days in February for roof repairs. Humboldt Park closed 3/26/12 for facility improvements and expansion. Lincoln Park closed for four days in August for replacement of the air conditioning system. Many locations experienced sporadic closures in summer 2012 due to air conditioning issues and area power outages. Albany Park closed 9/22/12 for construction of a new branch and will remain closed until 2014. Brighton Park, Jefferson Park and Portage Cragin were closed 11/26/12-12/7/12 for replacement of their HVAC systems.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | location   | LOCATION  | text      | text        |
| No       |                | address    | ADDRESS   | text      | text        |
| Yes      | series tag     | city       | CITY      | text      | text        |
| Yes      | series tag     | zip        | ZIP       | text      | text        |
| Yes      | numeric metric | january    | JANUARY   | number    | number      |
| Yes      | numeric metric | february   | FEBRUARY  | number    | number      |
| Yes      | numeric metric | march      | MARCH     | number    | number      |
| Yes      | numeric metric | april      | APRIL     | number    | number      |
| Yes      | numeric metric | may        | MAY       | number    | number      |
| Yes      | numeric metric | june       | JUNE      | number    | number      |
| Yes      | numeric metric | july       | JULY      | number    | number      |
| Yes      | numeric metric | august     | AUGUST    | number    | number      |
| Yes      | numeric metric | september  | SEPTEMBER | number    | number      |
| Yes      | numeric metric | october    | OCTOBER   | number    | number      |
| Yes      | numeric metric | november   | NOVEMBER  | number    | number      |
| Yes      | numeric metric | december   | DECEMBER  | number    | number      |
| Yes      | numeric metric | ytd        | YTD       | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:jsdv-pwf2 d:2012-01-01T00:00:00.000Z t:zip=60625 t:location="Albany Park" t:city=CHICAGO m:december=16 m:may=9045 m:november=15 m:march=11220 m:april=10173 m:february=9737 m:june=10014 m:january=10173 m:ytd=83297 m:august=8373 m:july=11196 m:october=74 m:september=3261

series e:jsdv-pwf2 d:2012-01-01T00:00:00.000Z t:zip=60827 t:location=Altgeld t:city=CHICAGO m:december=976 m:may=531 m:november=1030 m:march=401 m:april=631 m:february=513 m:june=661 m:january=674 m:ytd=10010 m:august=987 m:july=809 m:october=1451 m:september=1346

series e:jsdv-pwf2 d:2012-01-01T00:00:00.000Z t:zip=60632 t:location="Archer Heights" t:city=CHICAGO m:december=7698 m:may=7704 m:november=8793 m:march=8151 m:april=7703 m:february=7682 m:june=7294 m:january=7855 m:ytd=97256 m:august=7886 m:july=7735 m:october=9679 m:september=9076
```

## Meta Commands

```ls
metric m:january p:long l:JANUARY t:dataTypeName=number

metric m:february p:long l:FEBRUARY t:dataTypeName=number

metric m:march p:long l:MARCH t:dataTypeName=number

metric m:april p:long l:APRIL t:dataTypeName=number

metric m:may p:long l:MAY t:dataTypeName=number

metric m:june p:long l:JUNE t:dataTypeName=number

metric m:july p:long l:JULY t:dataTypeName=number

metric m:august p:long l:AUGUST t:dataTypeName=number

metric m:september p:long l:SEPTEMBER t:dataTypeName=number

metric m:october p:long l:OCTOBER t:dataTypeName=number

metric m:november p:long l:NOVEMBER t:dataTypeName=number

metric m:december p:long l:DECEMBER t:dataTypeName=number

metric m:ytd p:long l:YTD t:dataTypeName=number

entity e:jsdv-pwf2 l:"Libraries - 2012 Circulation by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/jsdv-pwf2

property e:jsdv-pwf2 t:meta.view v:id=jsdv-pwf2 v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - 2012 Circulation by Location" v:attribution="Chicago Public Library"

property e:jsdv-pwf2 t:meta.view.owner v:id=jitu-w2pw v:screenName=GPeck v:displayName=GPeck

property e:jsdv-pwf2 t:meta.view.tableauthor v:id=jitu-w2pw v:screenName=GPeck v:roleName=editor v:displayName=GPeck
```

## Top Records

```ls
| location       | address                     | city    | zip   | january | february | march | april | may   | june  | july  | august | september | october | november | december | ytd    | 
| ============== | =========================== | ======= | ===== | ======= | ======== | ===== | ===== | ===== | ===== | ===== | ====== | ========= | ======= | ======== | ======== | ====== | 
| Albany Park    | 5150 N. Kimball Avenue      | CHICAGO | 60625 | 10173   | 9737     | 11220 | 10173 | 9045  | 10014 | 11196 | 8373   | 3261      | 74      | 15       | 16       | 83297  | 
| Altgeld        | 13281 S. Corliss Avenue     | CHICAGO | 60827 | 674     | 513      | 401   | 631   | 531   | 661   | 809   | 987    | 1346      | 1451    | 1030     | 976      | 10010  | 
| Archer Heights | 5055 S. Archer Avenue       | CHICAGO | 60632 | 7855    | 7682     | 8151  | 7703  | 7704  | 7294  | 7735  | 7886   | 9076      | 9679    | 8793     | 7698     | 97256  | 
| Austin         | 5615 W. Race Avenue         | CHICAGO | 60644 | 2120    | 1964     | 1960  | 2117  | 1960  | 2004  | 2329  | 2466   | 2686      | 2738    | 2311     | 1869     | 26524  | 
| Austin-Irving  | 6100 W. Irving Park Road    | CHICAGO | 60634 | 12495   | 12977    | 13369 | 12672 | 11622 | 13316 | 13630 | 13640  | 14050     | 14362   | 13429    | 11843    | 157405 | 
| Avalon         | 8148 S. Stony Island Avenue | CHICAGO | 60617 | 5515    | 5290     | 5717  | 5270  | 4985  | 5422  | 5543  | 6068   | 6257      | 6737    | 5344     | 4737     | 66885  | 
| Beverly        | 1962 W. 95th Street         | CHICAGO | 60643 | 7375    | 7477     | 8110  | 7279  | 6798  | 8735  | 8791  | 8108   | 7819      | 7739    | 6800     | 5670     | 90701  | 
| Bezazian       | 1226 W. Ainslie Street      | CHICAGO | 60640 | 14238   | 13819    | 14949 | 14142 | 14328 | 15243 | 15999 | 16184  | 15233     | 15893   | 14405    | 13423    | 177856 | 
| Blackstone     | 4904 S. Lake Park Avenue    | CHICAGO | 60615 | 10487   | 10675    | 11585 | 11231 | 11007 | 12791 | 12979 | 12364  | 12284     | 11786   | 10794    | 10363    | 138346 | 
| Brainerd       | 1350 W. 89th Street         | CHICAGO | 60620 | 1042    | 942      | 1094  | 1043  | 945   | 1164  | 1296  | 1517   | 1491      | 1650    | 1367     | 1262     | 14813  | 
```