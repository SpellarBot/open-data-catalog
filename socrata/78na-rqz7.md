# Shared Ride Reservations at Port Authority of NY NJ Airports: Beginning 2005

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/shared-ride-reservations-at-port-authority-of-ny-nj-airports-beginning-2005) |
| Metadata | [Link](https://data.ny.gov/api/views/78na-rqz7) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/78na-rqz7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/78na-rqz7/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 78na-rqz7 |
| Name | Shared Ride Reservations at Port Authority of NY NJ Airports: Beginning 2005 |
| Attribution | The Port Authority of New York & New Jersey |
| Category | Transportation |
| Tags | the port authority of new york & new jersey, airport, ground transportation, shared ride, reservation, booking, private bus, private van |
| Created | 2014-02-10T20:35:34Z |
| Publication Date | 2016-11-10T20:06:59Z |

## Description

The Port Authority of New York and New Jersey quarterly produces a data file and provides information on Shared Ride (airport transportation services by authorized vehicles) reservations. Shared Ride service is defined as multiple stop ?door to door? services by authorized providers.  Although both reservation and passenger number for Shared Ride are simultaneously registered at the Port Authority?s Welcome Center when an individual makes a reservation, the Port Authority?s Ground Transportation Information System (GTIS) counts reservation numbers and passenger numbers separately as one reservation can have multiple passengers. This Shared Ride Reservation dataset reflects only the Shared Ride reservations.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | airport                 | Airport                 | text      | text        |
| No       |                | year                    | Year                    | number    | number      |
| No       |                | month                   | Month                   | number    | number      |
| Yes      | numeric metric | shared_ride_reservation | Shared Ride Reservation | number    | number      |
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
series e:78na-rqz7 d:2005-01-01T00:00:00.000Z t:airport="Kennedy International Airport" m:shared_ride_reservation=14691

series e:78na-rqz7 d:2005-02-01T00:00:00.000Z t:airport="Kennedy International Airport" m:shared_ride_reservation=13348

series e:78na-rqz7 d:2005-03-01T00:00:00.000Z t:airport="Kennedy International Airport" m:shared_ride_reservation=16661
```

## Meta Commands

```ls
metric m:shared_ride_reservation p:integer l:"Shared Ride Reservation" t:dataTypeName=number

entity e:78na-rqz7 l:"Shared Ride Reservations at Port Authority of NY NJ Airports: Beginning 2005" t:attribution="The Port Authority of New York & New Jersey" t:url=https://data.ny.gov/api/views/78na-rqz7

property e:78na-rqz7 t:meta.view v:id=78na-rqz7 v:category=Transportation v:attributionLink=http://www.panynj.gov/airports/ewr-taxi-car-van-service.html v:averageRating=0 v:name="Shared Ride Reservations at Port Authority of NY NJ Airports: Beginning 2005" v:attribution="The Port Authority of New York & New Jersey"

property e:78na-rqz7 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:78na-rqz7 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:78na-rqz7 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| airport                       | year | month | shared_ride_reservation | 
| ============================= | ==== | ===== | ======================= | 
| Kennedy International Airport | 2005 | 1     | 14691                   | 
| Kennedy International Airport | 2005 | 2     | 13348                   | 
| Kennedy International Airport | 2005 | 3     | 16661                   | 
| Kennedy International Airport | 2005 | 4     | 16621                   | 
| Kennedy International Airport | 2005 | 5     | 18781                   | 
| Kennedy International Airport | 2005 | 6     | 17499                   | 
| Kennedy International Airport | 2005 | 7     | 16625                   | 
| Kennedy International Airport | 2005 | 8     | 16103                   | 
| Kennedy International Airport | 2005 | 9     | 16322                   | 
| Kennedy International Airport | 2005 | 10    | 15731                   | 
```