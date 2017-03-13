# Libraries - 2012 Holds Placed by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2012-holds-placed-by-location-7fc19) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/cpva-49fs) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/cpva-49fs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/cpva-49fs/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | cpva-49fs |
| Name | Libraries - 2012 Holds Placed by Location |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, holds |
| Created | 2012-02-17T21:26:21Z |
| Publication Date | 2013-04-08T21:31:48Z |
| Rows Updated | 2013-04-08T21:30:29Z |

## Description

Patrons may place holds on desired materials either online or by contacting any CPL location.  In January all branch locations were closed on Monday, January 9, Monday, January 23 and Monday, January 30. Beginning in February, all branch locations restored partial Monday hours, from 2 p.m. to 6 p.m. On June 18, all branch locations restored full Monday hours. Edgewater closed 6/16/11 for construction of a new branch scheduled to open in mid-2013. The library?s bookmobile opened 6/24/11 for Edgewater holds pickup and returns. Douglass closed for 10 days in February for roof repairs. Humboldt Park closed 3/26/12 for facility improvements and expansion. Lincoln Park closed for four days in August for replacement of the air conditioning system. Many locations experienced sporadic closures in summer 2012 due to air conditioning issues and area power outages. Albany Park closed 9/22/12 for construction of a new branch and will remain closed until 2014. Brighton Park, Jefferson Park and Portage Cragin were closed 11/26/12-12/7/12 for replacement of their HVAC systems.

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
Value = 
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:cpva-49fs d:2012-01-01T00:00:00.000Z t:zip=60625 t:location="Albany Park" t:city=CHICAGO m:december=0 m:may=195 m:november=0 m:march=230 m:april=239 m:february=224 m:june=197 m:january=198 m:ytd=1719 m:august=137 m:july=254 m:october=1 m:september=44

series e:cpva-49fs d:2012-01-01T00:00:00.000Z t:zip=60827 t:location=Altgeld t:city=CHICAGO m:december=29 m:may=8 m:november=12 m:march=16 m:april=21 m:february=20 m:june=5 m:january=30 m:ytd=216 m:august=9 m:july=19 m:october=13 m:september=34

series e:cpva-49fs d:2012-01-01T00:00:00.000Z t:zip=60632 t:location="Archer Heights" t:city=CHICAGO m:december=73 m:may=139 m:november=122 m:march=109 m:april=122 m:february=76 m:june=106 m:january=88 m:ytd=1344 m:august=143 m:july=136 m:october=128 m:september=102
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

entity e:cpva-49fs l:"Libraries - 2012 Holds Placed by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/cpva-49fs

property e:cpva-49fs t:meta.view v:id=cpva-49fs v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - 2012 Holds Placed by Location" v:attribution="Chicago Public Library"

property e:cpva-49fs t:meta.view.owner v:id=jitu-w2pw v:screenName=GPeck v:roleName=editor v:displayName=GPeck

property e:cpva-49fs t:meta.view.tableauthor v:id=jitu-w2pw v:screenName=GPeck v:roleName=editor v:displayName=GPeck
```