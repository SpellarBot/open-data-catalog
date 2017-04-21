# Monthly Interstate Ferry Ridership, Port Authority: Beginning 1998

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-interstate-ferry-ridership-port-authority-beginning-1998) |
| Metadata | [Link](https://data.ny.gov/api/views/v2hx-3snr) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/v2hx-3snr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/v2hx-3snr/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | v2hx-3snr |
| Name | Monthly Interstate Ferry Ridership, Port Authority: Beginning 1998 |
| Attribution | Port Authority of NY & NJ |
| Category | Transportation |
| Tags | port authority of ny & nj, ferries, transportation, transit |
| Created | 2013-05-10T15:21:45Z |
| Publication Date | 2016-10-11T19:54:46Z |

## Description

This dataset provides total monthly ridership trends on New York/New Jersey interstate ferry routes.   It counts ridership as unlinked trips, covering both directions of travel between the two states.  It includes only scheduled interstate ferry services, and excludes tour and charter trips.   The dataset provides separate totals columns for ferry terminals serving Midtown (W 39th St/Pier 79) and Downtown (Pier 11 and the World Financial Center).

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | time           | year                | Year                | number    | number      |
| Yes      | series tag     | month               | Month               | text      | text        |
| Yes      | numeric metric | downtown_passengers | Downtown Passengers | number    | number      |
| Yes      | numeric metric | midtown_passengers  | Midtown Passengers  | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:v2hx-3snr d:1998-01-01T00:00:00.000Z t:month=Jan m:midtown_passengers=279478 m:downtown_passengers=289961

series e:v2hx-3snr d:1998-01-01T00:00:00.000Z t:month=Feb m:midtown_passengers=218735 m:downtown_passengers=257651

series e:v2hx-3snr d:1998-01-01T00:00:00.000Z t:month=Mar m:midtown_passengers=260248 m:downtown_passengers=326425
```

## Meta Commands

```ls
metric m:downtown_passengers p:integer l:"Downtown Passengers" d:"Average weekday ferry passengers on scheduled routes between New Jersey and Lower Manhattan (Pier 11 or World Financial Center ferry terminals)" t:dataTypeName=number

metric m:midtown_passengers p:integer l:"Midtown Passengers" d:"Average weekday ferry passengers on scheduled routes between New Jersey and Midtown Manhattan (W. 39th St/Pier 79 ferry terminal)" t:dataTypeName=number

entity e:v2hx-3snr l:"Monthly Interstate Ferry Ridership, Port Authority:  Beginning 1998" t:attribution="Port Authority of NY & NJ" t:url=https://data.ny.gov/api/views/v2hx-3snr

property e:v2hx-3snr t:meta.view v:id=v2hx-3snr v:category=Transportation v:averageRating=0 v:name="Monthly Interstate Ferry Ridership, Port Authority:  Beginning 1998" v:attribution="Port Authority of NY & NJ"

property e:v2hx-3snr t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:v2hx-3snr t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| year | month | downtown_passengers | midtown_passengers | 
| ==== | ===== | =================== | ================== | 
| 1998 | Jan   | 289961              | 279478             | 
| 1998 | Feb   | 257651              | 218735             | 
| 1998 | Mar   | 326425              | 260248             | 
| 1998 | Apr   | 348325              | 310767             | 
| 1998 | May   | 328677              | 270107             | 
| 1998 | Jun   | 390825              | 293411             | 
| 1998 | Jul   | 396057              | 289414             | 
| 1998 | Aug   | 378776              | 290998             | 
| 1998 | Sep   | 358268              | 262106             | 
| 1998 | Oct   | 347688              | 279391             | 
```