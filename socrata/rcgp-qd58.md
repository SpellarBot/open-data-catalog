# Average Weekday Interstate Ferry Ridership Figures for Port Authority: Beginning 1998

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/average-weekday-interstate-ferry-ridership-figures-for-port-authority-beginning-1998) |
| Metadata | [Link](https://data.ny.gov/api/views/rcgp-qd58) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/rcgp-qd58/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/rcgp-qd58/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | rcgp-qd58 |
| Name | Average Weekday Interstate Ferry Ridership Figures for Port Authority: Beginning 1998 |
| Attribution | Port Authority of NY & NJ |
| Category | Transportation |
| Tags | port authority of ny & nj, ferries, transportation, transit |
| Created | 2013-05-10T16:56:58Z |
| Publication Date | 2016-10-21T18:07:01Z |

## Description

This dataset provides average weekday ridership trends on New York/New Jersey interstate ferry routes.   It counts ridership as unlinked trips, covering both directions of travel between the two states.  It includes only scheduled interstate ferry services, and excludes tour and charter trips.  The dataset provides separate totals columns for ferry terminals serving Midtown (W 39th St/Pier 79) and Downtown (Pier 11 and the World Financial Center).

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
series e:rcgp-qd58 d:1998-01-01T00:00:00.000Z t:month=Jan m:midtown_passengers=13837 m:downtown_passengers=9380

series e:rcgp-qd58 d:1998-01-01T00:00:00.000Z t:month=Feb m:midtown_passengers=13756 m:downtown_passengers=8940

series e:rcgp-qd58 d:1998-01-01T00:00:00.000Z t:month=Mar m:midtown_passengers=15040 m:downtown_passengers=9577
```

## Meta Commands

```ls
metric m:downtown_passengers p:integer l:"Downtown Passengers" d:"Average weekday ferry passengers on scheduled routes between New Jersey and Lower Manhattan (Pier 11 or World Financial Center ferry terminals)" t:dataTypeName=number

metric m:midtown_passengers p:integer l:"Midtown Passengers" d:"Average weekday ferry passengers on scheduled routes between New Jersey and Midtown Manhattan (W. 39th St/Pier 79 ferry terminal)" t:dataTypeName=number

entity e:rcgp-qd58 l:"Average Weekday Interstate Ferry Ridership Figures for Port Authority:  Beginning 1998" t:attribution="Port Authority of NY & NJ" t:url=https://data.ny.gov/api/views/rcgp-qd58

property e:rcgp-qd58 t:meta.view v:id=rcgp-qd58 v:category=Transportation v:averageRating=0 v:name="Average Weekday Interstate Ferry Ridership Figures for Port Authority:  Beginning 1998" v:attribution="Port Authority of NY & NJ"

property e:rcgp-qd58 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:rcgp-qd58 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:rcgp-qd58 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | month | downtown_passengers | midtown_passengers | 
| ==== | ===== | =================== | ================== | 
| 1998 | Jan   | 9380                | 13837              | 
| 1998 | Feb   | 8940                | 13756              | 
| 1998 | Mar   | 9577                | 15040              | 
| 1998 | Apr   | 10643               | 15863              | 
| 1998 | May   | 10000               | 15634              | 
| 1998 | Jun   | 11201               | 17361              | 
| 1998 | Jul   | 10889               | 17221              | 
| 1998 | Aug   | 10947               | 17006              | 
| 1998 | Sep   | 10246               | 16308              | 
| 1998 | Oct   | 10709               | 16342              | 
```