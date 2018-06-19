# NYC Cool Roofs Buildings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-cool-roofs-buildings-c0392) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/uuxn-wzxe) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/uuxn-wzxe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/uuxn-wzxe/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | uuxn-wzxe |
| Name | NYC Cool Roofs Buildings |
| Attribution | Department of Buildings (DOB) |
| Category | Environment |
| Tags | nyc cool roofs buildings, dob, environment, cooling, greenhouse gas, reflective, clean web |
| Created | 2012-06-26T15:59:52Z |
| Publication Date | 2013-06-21T19:42:20Z |

## Description

Locations of buildings participating in the Cool Roofs initiative.  NYC Cool Roofs buildings have a reflective surface applied to their rooftop, helping to reduce cooling costs, cut energy usage and lower greenhouse gas emissions.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag     | neighborhood | Neighborhood | text      | text        |
| Yes      | numeric metric | total_sq_ft  | Total Sq Ft  | number    | number      |
| No       |                | address_1    | Address 1    | text      | text        |
| No       |                | address_2    | Address 2    | text      | text        |
| Yes      | series tag     | zip          | Zip          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_1,address_2
```

## Data Commands

```ls
series e:uuxn-wzxe d:2012-06-29T10:20:54.000Z t:zip=11634 t:neighborhood="Oakland Gardens" m:total_sq_ft=5000

series e:uuxn-wzxe d:2012-06-29T10:21:01.000Z t:zip=10474 t:neighborhood=Bronx m:total_sq_ft=6000

series e:uuxn-wzxe d:2012-06-29T10:21:01.000Z t:zip=10003 t:neighborhood=Bowery m:total_sq_ft=5027
```

## Meta Commands

```ls
metric m:total_sq_ft p:integer l:"Total Sq Ft" t:dataTypeName=number

entity e:uuxn-wzxe l:"NYC Cool Roofs Buildings" t:attribution="Department of Buildings (DOB)" t:url=https://data.cityofnewyork.us/api/views/uuxn-wzxe

property e:uuxn-wzxe t:meta.view v:id=uuxn-wzxe v:category=Environment v:averageRating=0 v:name="NYC Cool Roofs Buildings" v:attribution="Department of Buildings (DOB)"

property e:uuxn-wzxe t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:uuxn-wzxe t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | neighborhood       | total_sq_ft | address_1                 | address_2               | zip   | 
| =========== | ================== | =========== | ========================= | ======================= | ===== | 
| 1340965254  | Oakland Gardens    | 5000        | 79-50 Bell Blvd           | Windsor Park Library    | 11634 | 
| 1340965261  | Bronx              | 6000        | 812 Edgewater Rd          | Rocking the Boat        | 10474 | 
| 1340965261  | Bowery             | 5027        | 333 Bowery                | Kenton Hall             | 10003 | 
| 1340965261  | High Bridge        | 4658        | 1665 Macombs Road         |                         | 10453 | 
| 1340965261  | East New York      | 3540        | 486 Williams Ave          |                         | 11207 | 
| 1340965261  | Greenwich Village  | 2164        | 46 Barrow Street          |                         | 10014 | 
| 1340965261  | Far Rockaway       | 8099        | 155 beach 19th st         |                         | 11691 | 
| 1340965261  | Bedford Stuyvesant | 8000        | 247 Herkimer Street       |                         | 11216 | 
| 1340965261  | East Corona        | 8600        | 100-01 Northern Blvd      | Langston Hughes Library | 11369 | 
| 1340965261  | Mott Haven         | 4100        | 409-411 East 146th Street | Betances                | 10455 | 
```