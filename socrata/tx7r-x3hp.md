# Los Angeles International Airport - Air Cargo Volume

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/los-angeles-international-airport-air-cargo-volume-a9a5d) |
| Metadata | [Link](https://data.lacity.org/api/views/tx7r-x3hp) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/tx7r-x3hp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/tx7r-x3hp/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | tx7r-x3hp |
| Name | Los Angeles International Airport - Air Cargo Volume |
| Category | A Prosperous City |
| Tags | lax, airport, flight, freight, carrier, cargo |
| Created | 2014-05-29T16:11:51Z |
| Publication Date | 2014-05-31T04:07:54Z |

## Description

Tons of cargo that moved in and out through the Airport

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | time           | dataextractdate        | DataExtractDate        | calendar_date | calendar_date |
| No       |                | reportperiod           | ReportPeriod           | calendar_date | calendar_date |
| Yes      | series tag     | arrival_departure      | Arrival_Departure      | text          | text          |
| Yes      | series tag     | domestic_international | Domestic_International | text          | text          |
| Yes      | series tag     | cargotype              | CargoType              | text          | text          |
| Yes      | numeric metric | aircargotons           | AirCargoTons           | number        | number        |
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
series e:tx7r-x3hp d:2014-05-01T00:00:00.000Z t:domestic_international=Domestic t:arrival_departure=Arrival t:cargotype=Freight m:aircargotons=35703

series e:tx7r-x3hp d:2014-05-01T00:00:00.000Z t:domestic_international=Domestic t:arrival_departure=Arrival t:cargotype=Mail m:aircargotons=3209

series e:tx7r-x3hp d:2014-05-01T00:00:00.000Z t:domestic_international=International t:arrival_departure=Arrival t:cargotype=Freight m:aircargotons=46391
```

## Meta Commands

```ls
metric m:aircargotons p:integer l:AirCargoTons t:dataTypeName=number

entity e:tx7r-x3hp l:"Los Angeles International Airport - Air Cargo Volume" t:url=https://data.lacity.org/api/views/tx7r-x3hp

property e:tx7r-x3hp t:meta.view v:id=tx7r-x3hp v:category="A Prosperous City" v:averageRating=0 v:name="Los Angeles International Airport - Air Cargo Volume"

property e:tx7r-x3hp t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:tx7r-x3hp t:meta.view.owner v:id=gudt-ccne v:profileImageUrlMedium=/api/users/gudt-ccne/profile_images/THUMB v:profileImageUrlLarge=/api/users/gudt-ccne/profile_images/LARGE v:screenName="LAWA OpenData" v:profileImageUrlSmall=/api/users/gudt-ccne/profile_images/TINY v:displayName="LAWA OpenData"

property e:tx7r-x3hp t:meta.view.tableauthor v:id=gudt-ccne v:profileImageUrlMedium=/api/users/gudt-ccne/profile_images/THUMB v:profileImageUrlLarge=/api/users/gudt-ccne/profile_images/LARGE v:screenName="LAWA OpenData" v:profileImageUrlSmall=/api/users/gudt-ccne/profile_images/TINY v:roleName=publisher v:displayName="LAWA OpenData"
```

## Top Records

```ls
| dataextractdate     | reportperiod        | arrival_departure | domestic_international | cargotype | aircargotons | 
| =================== | =================== | ================= | ====================== | ========= | ============ | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Arrival           | Domestic               | Freight   | 35703        | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Arrival           | Domestic               | Mail      | 3209         | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Arrival           | International          | Freight   | 46391        | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Arrival           | International          | Mail      | 548          | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Departure         | Domestic               | Freight   | 36702        | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Departure         | Domestic               | Mail      | 2845         | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Departure         | International          | Freight   | 31748        | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Departure         | International          | Mail      | 971          | 
| 2014-05-01T00:00:00 | 2006-02-01T00:00:00 | Arrival           | Domestic               | Freight   | 35065        | 
| 2014-05-01T00:00:00 | 2006-02-01T00:00:00 | Arrival           | Domestic               | Mail      | 2551         | 
```