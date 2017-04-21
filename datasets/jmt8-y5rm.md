# Port of Los Angeles - Cruise Passenger (1990 - 2014)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/port-of-los-angeles-cruise-passenger) |
| Metadata | [Link](https://data.lacity.org/api/views/jmt8-y5rm) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/jmt8-y5rm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/jmt8-y5rm/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | jmt8-y5rm |
| Name | Port of Los Angeles - Cruise Passenger (1990 - 2014) |
| Attribution | Port of Los Angeles |
| Category | A Prosperous City |
| Tags | jobs, economy, business, port, cruise, passenger |
| Created | 2014-03-24T19:45:14Z |
| Publication Date | 2015-04-03T22:05:14Z |

## Description

Port of Los Angeles - Cruise Passenger (1990 - 2014) Historical published data. The Port no longer collected cruise passenger data.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | time           | year                | Year                | number    | text        |
| Yes      | numeric metric | ship_calls          | Ship Calls          | number    | number      |
| Yes      | numeric metric | passengers          | Passengers          | number    | number      |
| Yes      | numeric metric | passengers_per_ship | Passengers Per Ship | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jmt8-y5rm d:1990-01-01T00:00:00.000Z m:passengers=617876 m:passengers_per_ship=819 m:ship_calls=377

series e:jmt8-y5rm d:1991-01-01T00:00:00.000Z m:passengers=680559 m:passengers_per_ship=882 m:ship_calls=386

series e:jmt8-y5rm d:1992-01-01T00:00:00.000Z m:passengers=902453 m:passengers_per_ship=1030 m:ship_calls=438
```

## Meta Commands

```ls
metric m:ship_calls p:integer l:"Ship Calls" t:dataTypeName=number

metric m:passengers p:integer l:Passengers t:dataTypeName=number

metric m:passengers_per_ship p:integer l:"Passengers Per Ship" t:dataTypeName=number

entity e:jmt8-y5rm l:"Port of Los Angeles - Cruise Passenger (1990 - 2014)" t:attribution="Port of Los Angeles" t:url=https://data.lacity.org/api/views/jmt8-y5rm

property e:jmt8-y5rm t:meta.view v:id=jmt8-y5rm v:category="A Prosperous City" v:averageRating=0 v:name="Port of Los Angeles - Cruise Passenger (1990 - 2014)" v:attribution="Port of Los Angeles"

property e:jmt8-y5rm t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:jmt8-y5rm t:meta.view.owner v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:displayName="Port of Los Angeles"

property e:jmt8-y5rm t:meta.view.tableauthor v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:roleName=publisher v:displayName="Port of Los Angeles"
```

## Top Records

```ls
| year | ship_calls | passengers | passengers_per_ship | 
| ==== | ========== | ========== | =================== | 
| 1990 | 377        | 617876     | 819                 | 
| 1991 | 386        | 680559     | 882                 | 
| 1992 | 438        | 902453     | 1030                | 
| 1993 | 417        | 880534     | 1056                | 
| 1994 | 373        | 793256     | 1063                | 
| 1995 | 287        | 794448     | 1384                | 
| 1996 | 324        | 945180     | 1459                | 
| 1997 | 324        | 942773     | 1455                | 
| 1998 | 319        | 961187     | 1507                | 
| 1999 | 295        | 992979     | 1683                | 
```