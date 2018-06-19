# Libraries - 2012 Holds Filled by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2012-holds-filled-by-location-bb78a) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/egku-46f2) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/egku-46f2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/egku-46f2/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | egku-46f2 |
| Name | Libraries - 2012 Holds Filled by Location |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, holds |
| Created | 2012-02-17T21:16:03Z |
| Publication Date | 2013-04-08T21:35:23Z |

## Description

Materials pulled to fulfill patron holds.  In January all branch locations were closed on Monday, January 9, Monday, January 23 and Monday, January 30. Beginning in February, all branch locations restored partial Monday hours, from 2 p.m. to 6 p.m. On June 18, all branch locations restored full Monday hours. Edgewater closed 6/16/11 for construction of a new branch scheduled to open in mid-2013. The library?s bookmobile opened 6/24/11 for Edgewater holds pickup and returns. Douglass closed for 10 days in February for roof repairs. Humboldt Park closed 3/26/12 for facility improvements and expansion. Lincoln Park closed for four days in August for replacement of the air conditioning system. Many locations experienced sporadic closures in summer 2012 due to air conditioning issues and area power outages. Albany Park closed 9/22/12 for construction of a new branch and will remain closed until 2014. Brighton Park, Jefferson Park and Portage Cragin were closed 11/26/12-12/7/12 for replacement of their HVAC systems.

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
series e:egku-46f2 d:2012-01-01T00:00:00.000Z t:zip=60625 t:location="Albany Park" t:city=CHICAGO m:december=0 m:may=2121 m:november=0 m:march=2338 m:april=2197 m:february=2267 m:june=2149 m:january=2507 m:ytd=17848 m:august=1436 m:july=2402 m:october=8 m:september=423

series e:egku-46f2 d:2012-01-01T00:00:00.000Z t:zip=60827 t:location=Altgeld t:city=CHICAGO m:december=446 m:may=557 m:november=516 m:march=427 m:april=413 m:february=577 m:june=465 m:january=616 m:ytd=6349 m:august=596 m:july=493 m:october=642 m:september=601

series e:egku-46f2 d:2012-01-01T00:00:00.000Z t:zip=60632 t:location="Archer Heights" t:city=CHICAGO m:december=1343 m:may=1675 m:november=1615 m:march=1862 m:april=1515 m:february=1607 m:june=1593 m:january=1726 m:ytd=19846 m:august=1787 m:july=1746 m:october=1793 m:september=1584
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

entity e:egku-46f2 l:"Libraries - 2012 Holds Filled by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/egku-46f2

property e:egku-46f2 t:meta.view v:id=egku-46f2 v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - 2012 Holds Filled by Location" v:attribution="Chicago Public Library"

property e:egku-46f2 t:meta.view.owner v:id=jitu-w2pw v:screenName=GPeck v:displayName=GPeck

property e:egku-46f2 t:meta.view.tableauthor v:id=jitu-w2pw v:screenName=GPeck v:roleName=editor v:displayName=GPeck
```

## Top Records

```ls
| location       | address                     | city    | zip   | january | february | march | april | may  | june | july | august | september | october | november | december | ytd   | 
| ============== | =========================== | ======= | ===== | ======= | ======== | ===== | ===== | ==== | ==== | ==== | ====== | ========= | ======= | ======== | ======== | ===== | 
| Albany Park    | 5150 N. Kimball Avenue      | CHICAGO | 60625 | 2507    | 2267     | 2338  | 2197  | 2121 | 2149 | 2402 | 1436   | 423       | 8       | 0        | 0        | 17848 | 
| Altgeld        | 13281 S. Corliss Avenue     | CHICAGO | 60827 | 616     | 577      | 427   | 413   | 557  | 465  | 493  | 596    | 601       | 642     | 516      | 446      | 6349  | 
| Archer Heights | 5055 S. Archer Avenue       | CHICAGO | 60632 | 1726    | 1607     | 1862  | 1515  | 1675 | 1593 | 1746 | 1787   | 1584      | 1793    | 1615     | 1343     | 19846 | 
| Austin         | 5615 W. Race Avenue         | CHICAGO | 60644 | 808     | 808      | 761   | 755   | 785  | 726  | 740  | 849    | 771       | 903     | 697      | 628      | 9231  | 
| Austin-Irving  | 6100 W. Irving Park Road    | CHICAGO | 60634 | 3503    | 3350     | 3425  | 3168  | 3101 | 3262 | 3453 | 3680   | 3113      | 3515    | 3105     | 2570     | 39245 | 
| Avalon         | 8148 S. Stony Island Avenue | CHICAGO | 60617 | 1620    | 1629     | 1562  | 1347  | 1582 | 1497 | 1568 | 1816   | 1776      | 1916    | 1478     | 1492     | 19283 | 
| Beverly        | 1962 W. 95th Street         | CHICAGO | 60643 | 2451    | 2428     | 2701  | 2280  | 2612 | 2707 | 2556 | 2717   | 2381      | 2675    | 2293     | 1780     | 29581 | 
| Bezazian       | 1226 W. Ainslie Street      | CHICAGO | 60640 | 5085    | 4817     | 4913  | 4637  | 4881 | 4646 | 4843 | 4873   | 4139      | 4842    | 4060     | 3598     | 55334 | 
| Blackstone     | 4904 S. Lake Park Avenue    | CHICAGO | 60615 | 3636    | 3425     | 3430  | 3470  | 3598 | 3400 | 3476 | 3736   | 3289      | 3565    | 3555     | 3063     | 41643 | 
| Brainerd       | 1350 W. 89th Street         | CHICAGO | 60620 | 657     | 650      | 674   | 600   | 695  | 712  | 755  | 730    | 648       | 710     | 581      | 487      | 7899  | 
```