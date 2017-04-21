# Los Angeles International Airport - Flight Operations By Month

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/los-angeles-international-airport-flight-operations-by-month-afb2a) |
| Metadata | [Link](https://data.lacity.org/api/views/ajiv-uc63) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/ajiv-uc63/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/ajiv-uc63/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | ajiv-uc63 |
| Name | Los Angeles International Airport - Flight Operations By Month |
| Category | A Prosperous City |
| Tags | lax, airport, terminal, flight, carrier |
| Created | 2014-05-29T15:59:18Z |
| Publication Date | 2014-05-29T17:20:39Z |

## Description

Number of Flights That Occurred at the Airport

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | time           | dataextractdate        | DataExtractDate        | calendar_date | calendar_date |
| No       |                | reportperiod           | ReportPeriod           | calendar_date | calendar_date |
| Yes      | series tag     | flighttype             | FlightType             | text          | text          |
| Yes      | series tag     | arrival_departure      | Arrival_Departure      | text          | text          |
| Yes      | series tag     | domestic_international | Domestic_International | text          | text          |
| Yes      | numeric metric | flightopscount         | FlightOpsCount         | number        | number        |
```

## Time Field

```ls
Value = dataextractdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = reportperiod
```

## Data Commands

```ls
series e:ajiv-uc63 d:2014-05-01T00:00:00.000Z t:domestic_international=Domestic t:arrival_departure=Arrival t:flighttype=Charter m:flightopscount=57

series e:ajiv-uc63 d:2014-05-01T00:00:00.000Z t:domestic_international=International t:arrival_departure=Arrival t:flighttype=Charter m:flightopscount=299

series e:ajiv-uc63 d:2014-05-01T00:00:00.000Z t:domestic_international=Domestic t:arrival_departure=Departure t:flighttype=Charter m:flightopscount=62
```

## Meta Commands

```ls
metric m:flightopscount p:integer l:FlightOpsCount t:dataTypeName=number

entity e:ajiv-uc63 l:"Los Angeles International Airport - Flight Operations By Month" t:url=https://data.lacity.org/api/views/ajiv-uc63

property e:ajiv-uc63 t:meta.view v:id=ajiv-uc63 v:category="A Prosperous City" v:averageRating=0 v:name="Los Angeles International Airport - Flight Operations By Month"

property e:ajiv-uc63 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:ajiv-uc63 t:meta.view.owner v:id=gudt-ccne v:profileImageUrlMedium=/api/users/gudt-ccne/profile_images/THUMB v:profileImageUrlLarge=/api/users/gudt-ccne/profile_images/LARGE v:screenName="LAWA OpenData" v:profileImageUrlSmall=/api/users/gudt-ccne/profile_images/TINY v:displayName="LAWA OpenData"

property e:ajiv-uc63 t:meta.view.tableauthor v:id=gudt-ccne v:profileImageUrlMedium=/api/users/gudt-ccne/profile_images/THUMB v:profileImageUrlLarge=/api/users/gudt-ccne/profile_images/LARGE v:screenName="LAWA OpenData" v:profileImageUrlSmall=/api/users/gudt-ccne/profile_images/TINY v:roleName=publisher v:displayName="LAWA OpenData"
```

## Top Records

```ls
| dataextractdate     | reportperiod        | flighttype | arrival_departure | domestic_international | flightopscount | 
| =================== | =================== | ========== | ================= | ====================== | ============== | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Charter    | Arrival           | Domestic               | 57             | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Charter    | Arrival           | International          | 299            | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Charter    | Departure         | Domestic               | 62             | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Charter    | Departure         | International          | 5              | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Commuter   | Arrival           | Domestic               | 5996           | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Commuter   | Arrival           | International          | 31             | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Commuter   | Departure         | Domestic               | 5995           | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Commuter   | Departure         | International          | 31             | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Scheduled  | Arrival           | Domestic               | 13695          | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Scheduled  | Arrival           | International          | 4026           | 
```