# Shared Ride Passengers at Port Authority of NY NJ Airports: Beginning 2005

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/shared-ride-passengers-at-port-authority-of-ny-nj-airports-beginning-2005) |
| Metadata | [Link](https://data.ny.gov/api/views/bhdi-gm53) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/bhdi-gm53/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/bhdi-gm53/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | bhdi-gm53 |
| Name | Shared Ride Passengers at Port Authority of NY NJ Airports: Beginning 2005 |
| Attribution | The Port Authority of NY & NJ |
| Category | Transportation |
| Tags | the port authority of new york & new jersey, airport, ground transportation, shared ride, shared, passengers, private bus, private van |
| Created | 2014-02-10T20:27:57Z |
| Publication Date | 2016-11-10T20:06:43Z |

## Description

The Port Authority of New York and New Jersey quarterly produces a data file and provides information on Shared Ride reservations. Shared Ride activity is defined as multiple stop ?door to door? services  by authorized providers.    Although both reservation and passenger number for Shared Ride are simultaneously registered at the Port Authority?s Welcome Center when an individual makes a reservation, the Port Authority?s Ground Transportation Information System (GTIS) counts reservation numbers and passenger numbers separately as one reservation can have multiple passengers. This Shared Ride Reservation dataset reflects only the Shared Ride passengers.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | airport                | Airport                | text      | text        |
| No       |                | year                   | Year                   | number    | number      |
| No       |                | month                  | Month                  | number    | number      |
| Yes      | numeric metric | shared_ride_passengers | Shared Ride Passengers | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:bhdi-gm53 d:2005-01-01T00:00:00.000Z t:airport="Kennedy International Airport" m:shared_ride_passengers=20778

series e:bhdi-gm53 d:2005-02-01T00:00:00.000Z t:airport="Kennedy International Airport" m:shared_ride_passengers=20816

series e:bhdi-gm53 d:2005-03-01T00:00:00.000Z t:airport="Kennedy International Airport" m:shared_ride_passengers=26850
```

## Meta Commands

```ls
metric m:shared_ride_passengers p:integer l:"Shared Ride Passengers" t:dataTypeName=number

entity e:bhdi-gm53 l:"Shared Ride Passengers at Port Authority of NY NJ Airports: Beginning 2005" t:attribution="The Port Authority of NY & NJ" t:url=https://data.ny.gov/api/views/bhdi-gm53

property e:bhdi-gm53 t:meta.view v:id=bhdi-gm53 v:category=Transportation v:attributionLink=http://www.panynj.gov/airports/ewr-taxi-car-van-service.html v:averageRating=0 v:name="Shared Ride Passengers at Port Authority of NY NJ Airports: Beginning 2005" v:attribution="The Port Authority of NY & NJ"

property e:bhdi-gm53 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:bhdi-gm53 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:bhdi-gm53 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| airport                       | year | month | shared_ride_passengers | 
| ============================= | ==== | ===== | ====================== | 
| Kennedy International Airport | 2005 | 1     | 20778                  | 
| Kennedy International Airport | 2005 | 2     | 20816                  | 
| Kennedy International Airport | 2005 | 3     | 26850                  | 
| Kennedy International Airport | 2005 | 4     | 27261                  | 
| Kennedy International Airport | 2005 | 5     | 29432                  | 
| Kennedy International Airport | 2005 | 6     | 27721                  | 
| Kennedy International Airport | 2005 | 7     | 28165                  | 
| Kennedy International Airport | 2005 | 8     | 26675                  | 
| Kennedy International Airport | 2005 | 9     | 25503                  | 
| Kennedy International Airport | 2005 | 10    | 25770                  | 
```