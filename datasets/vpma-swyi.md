# Libraries - 2014 Holds Filled by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2014-holds-filled-by-location-d46e1) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/vpma-swyi) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/vpma-swyi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/vpma-swyi/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | vpma-swyi |
| Name | Libraries - 2014 Holds Filled by Location |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, holds |
| Created | 2014-06-09T19:06:45Z |
| Publication Date | 2015-01-12T19:33:41Z |

## Description

Materials pulled to fulfill patron holds. The Chicago Public Library consists of the Harold Washington Library Center, Sulzer and Woodson regional libraries and over 75 neighborhood branches. Albany Park Branch closed 9/22/2012 for construction of a new branch expected to open in Fall 2014. Interim services had been provided in the Albany Park community. Many locations experience sporadic emergency closures due to heating or air conditioning issues, or area power outages.

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
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:vpma-swyi d:2014-01-01T00:00:00.000Z t:zip=60625 t:location="Albany Park" t:city=CHICAGO m:december=2415 m:may=2 m:november=2354 m:march=1 m:april=0 m:february=0 m:june=0 m:january=20 m:ytd=7775 m:august=0 m:july=0 m:october=2526 m:september=457

series e:vpma-swyi d:2014-01-01T00:00:00.000Z t:zip=60827 t:location=Altgeld t:city=CHICAGO m:december=265 m:may=345 m:november=318 m:march=316 m:april=324 m:february=336 m:june=396 m:january=388 m:ytd=4232 m:august=356 m:july=458 m:october=345 m:september=385

series e:vpma-swyi d:2014-01-01T00:00:00.000Z t:zip=60632 t:location="Archer Heights" t:city=CHICAGO m:december=1287 m:may=1135 m:november=1088 m:march=1319 m:april=1412 m:february=1202 m:june=1376 m:january=1184 m:ytd=15598 m:august=1367 m:july=1382 m:october=1406 m:september=1440
```

## Meta Commands

```ls
metric m:january p:integer l:JANUARY t:dataTypeName=number

metric m:february p:integer l:FEBRUARY t:dataTypeName=number

metric m:march p:integer l:MARCH t:dataTypeName=number

metric m:april p:integer l:APRIL t:dataTypeName=number

metric m:may p:integer l:MAY t:dataTypeName=number

metric m:june p:integer l:JUNE t:dataTypeName=number

metric m:july p:integer l:JULY t:dataTypeName=number

metric m:august p:integer l:AUGUST t:dataTypeName=number

metric m:september p:integer l:SEPTEMBER t:dataTypeName=number

metric m:october p:integer l:OCTOBER t:dataTypeName=number

metric m:november p:integer l:NOVEMBER t:dataTypeName=number

metric m:december p:integer l:DECEMBER t:dataTypeName=number

metric m:ytd p:integer l:YTD t:dataTypeName=number

entity e:vpma-swyi l:"Libraries - 2014 Holds Filled by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/vpma-swyi

property e:vpma-swyi t:meta.view v:id=vpma-swyi v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - 2014 Holds Filled by Location" v:attribution="Chicago Public Library"

property e:vpma-swyi t:meta.view.owner v:id=cmhs-sm84 v:screenName="Ebony Jones" v:displayName="Ebony Jones"

property e:vpma-swyi t:meta.view.tableauthor v:id=cmhs-sm84 v:screenName="Ebony Jones" v:roleName=editor v:displayName="Ebony Jones"
```

## Top Records

```ls
| location          | address                     | city    | zip   | january | february | march | april | may  | june | july | august | september | october | november | december | ytd   | 
| ================= | =========================== | ======= | ===== | ======= | ======== | ===== | ===== | ==== | ==== | ==== | ====== | ========= | ======= | ======== | ======== | ===== | 
| Albany Park       | 5150 N. Kimball Avenue      | CHICAGO | 60625 | 20      | 0        | 1     | 0     | 2    | 0    | 0    | 0      | 457       | 2526    | 2354     | 2415     | 7775  | 
| Altgeld           | 13281 S. Corliss Avenue     | CHICAGO | 60827 | 388     | 336      | 316   | 324   | 345  | 396  | 458  | 356    | 385       | 345     | 318      | 265      | 4232  | 
| Archer Heights    | 5055 S. Archer Avenue       | CHICAGO | 60632 | 1184    | 1202     | 1319  | 1412  | 1135 | 1376 | 1382 | 1367   | 1440      | 1406    | 1088     | 1287     | 15598 | 
| Austin            | 5615 W. Race Avenue         | CHICAGO | 60644 | 589     | 451      | 558   | 530   | 575  | 510  | 597  | 579    | 560       | 612     | 535      | 569      | 6665  | 
| Austin-Irving     | 6100 W. Irving Park Road    | CHICAGO | 60634 | 2484    | 2284     | 2667  | 2909  | 2488 | 2806 | 2950 | 2851   | 2643      | 2574    | 2119     | 2200     | 30975 | 
| Avalon            | 8148 S. Stony Island Avenue | CHICAGO | 60617 | 1182    | 1141     | 1270  | 1261  | 1230 | 1290 | 1211 | 1336   | 1262      | 1246    | 1104     | 1042     | 14575 | 
| Back of the Yards | 2111 W. 47th Street         | CHICAGO | 60609 | 1039    | 936      | 1103  | 1066  | 1053 | 1069 | 1133 | 1099   | 988       | 903     | 817      | 745      | 11951 | 
| Beverly           | 1962 W. 95th Street         | CHICAGO | 60643 | 1944    | 1818     | 1972  | 2149  | 1785 | 1984 | 2048 | 1991   | 2074      | 1831    | 1450     | 1650     | 22696 | 
| Bezazian          | 1226 W. Ainslie Street      | CHICAGO | 60640 | 3429    | 2992     | 3262  | 3443  | 3429 | 3701 | 4154 | 3538   | 3767      | 3798    | 3120     | 3092     | 41725 | 
| Blackstone        | 4904 S. Lake Park Avenue    | CHICAGO | 60615 | 2948    | 2463     | 3069  | 2904  | 2732 | 3496 | 3262 | 3266   | 3168      | 2760    | 2447     | 2593     | 35108 | 
```