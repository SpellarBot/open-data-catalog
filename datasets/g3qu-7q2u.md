# Los Angeles International Airport - Passenger Traffic By Terminal

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/los-angeles-international-airport-passenger-traffic-by-terminal-756ee) |
| Metadata | [Link](https://data.lacity.org/api/views/g3qu-7q2u) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/g3qu-7q2u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/g3qu-7q2u/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | g3qu-7q2u |
| Name | Los Angeles International Airport - Passenger Traffic By Terminal |
| Category | A Prosperous City |
| Tags | airport, lax, passenger, terminal, flight, lawa |
| Created | 2014-05-28T18:11:05Z |
| Publication Date | 2014-05-29T17:36:08Z |

## Description

Los Angeles International Airport - Passenger Statistic By Terminal

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | time           | dataextractdate        | DataExtractDate        | calendar_date | calendar_date |
| No       |                | reportperiod           | ReportPeriod           | calendar_date | calendar_date |
| Yes      | series tag     | terminal               | Terminal               | text          | text          |
| Yes      | series tag     | arrival_departure      | Arrival_Departure      | text          | text          |
| Yes      | series tag     | domestic_international | Domestic_International | text          | text          |
| Yes      | numeric metric | passenger_count        | Passenger_Count        | number        | number        |
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
series e:g3qu-7q2u d:2014-05-01T00:00:00.000Z t:domestic_international=Domestic t:terminal="Imperial Terminal" t:arrival_departure=Arrival m:passenger_count=490

series e:g3qu-7q2u d:2014-05-01T00:00:00.000Z t:domestic_international=Domestic t:terminal="Imperial Terminal" t:arrival_departure=Departure m:passenger_count=498

series e:g3qu-7q2u d:2014-05-01T00:00:00.000Z t:domestic_international=Domestic t:terminal="Misc. Terminal" t:arrival_departure=Arrival m:passenger_count=753
```

## Meta Commands

```ls
metric m:passenger_count p:integer l:Passenger_Count t:dataTypeName=number

entity e:g3qu-7q2u l:"Los Angeles International Airport - Passenger Traffic By Terminal" t:url=https://data.lacity.org/api/views/g3qu-7q2u

property e:g3qu-7q2u t:meta.view v:id=g3qu-7q2u v:category="A Prosperous City" v:averageRating=0 v:name="Los Angeles International Airport - Passenger Traffic By Terminal"

property e:g3qu-7q2u t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:g3qu-7q2u t:meta.view.owner v:id=gudt-ccne v:profileImageUrlMedium=/api/users/gudt-ccne/profile_images/THUMB v:profileImageUrlLarge=/api/users/gudt-ccne/profile_images/LARGE v:screenName="LAWA OpenData" v:profileImageUrlSmall=/api/users/gudt-ccne/profile_images/TINY v:displayName="LAWA OpenData"

property e:g3qu-7q2u t:meta.view.tableauthor v:id=gudt-ccne v:profileImageUrlMedium=/api/users/gudt-ccne/profile_images/THUMB v:profileImageUrlLarge=/api/users/gudt-ccne/profile_images/LARGE v:screenName="LAWA OpenData" v:profileImageUrlSmall=/api/users/gudt-ccne/profile_images/TINY v:roleName=publisher v:displayName="LAWA OpenData"
```

## Top Records

```ls
| dataextractdate     | reportperiod        | terminal          | arrival_departure | domestic_international | passenger_count | 
| =================== | =================== | ================= | ================= | ====================== | =============== | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Imperial Terminal | Arrival           | Domestic               | 490             | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Imperial Terminal | Departure         | Domestic               | 498             | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Misc. Terminal    | Arrival           | Domestic               | 753             | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Misc. Terminal    | Departure         | Domestic               | 688             | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Terminal 1        | Arrival           | Domestic               | 401535          | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Terminal 1        | Departure         | Domestic               | 389745          | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Terminal 1        | Departure         | International          | 561             | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Terminal 2        | Arrival           | Domestic               | 98991           | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Terminal 2        | Arrival           | International          | 163067          | 
| 2014-05-01T00:00:00 | 2006-01-01T00:00:00 | Terminal 2        | Departure         | Domestic               | 93672           | 
```