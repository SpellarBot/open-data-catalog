# Coach Bus Passengers per Month at Port Authority of NY NJ Airports: Beginning 2002

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/coach-bus-passengers-per-month-at-port-authority-of-ny-nj-airports-beginning-2002) |
| Metadata | [Link](https://data.ny.gov/api/views/39r6-cbzf) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/39r6-cbzf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/39r6-cbzf/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 39r6-cbzf |
| Name | Coach Bus Passengers per Month at Port Authority of NY NJ Airports: Beginning 2002 |
| Attribution | The Port Authority of New York & New Jersey |
| Category | Transportation |
| Tags | the port authority of new york & new jersey, airport, coach bus, bus passengers, ground transportation |
| Created | 2014-02-10T20:00:53Z |
| Publication Date | 2016-11-10T20:05:22Z |
| Rows Updated | 2016-11-10T20:05:10Z |

## Description

The Port Authority of New York & New Jersey quarterly produces a data file and provides information on monthly in-bound, out-bound, and connecting Coach Bus passengers between John F. Kennedy International Airport, LaGuardia Airport, and Newark Liberty International Airport; and between aforementioned airports and NYC bus stations beginning in 2002. The dataset represents aggregate numbers of single destination (e.g. A -> B) Coach Bus ticket sale by the Coach Bus companies.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | airport          | Airport          | text      | text        |
| Yes      | time           | year             | Year             | number    | number      |
| Yes      | numeric metric | month            | Month            | number    | number      |
| Yes      | numeric metric | coach_passengers | Coach Passengers | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:39r6-cbzf d:2002-01-01T00:00:00.000Z t:airport="Kennedy International Airport" m:coach_passengers=30338 m:month=1

series e:39r6-cbzf d:2002-01-01T00:00:00.000Z t:airport="Kennedy International Airport" m:coach_passengers=26409 m:month=2

series e:39r6-cbzf d:2002-01-01T00:00:00.000Z t:airport="Kennedy International Airport" m:coach_passengers=36206 m:month=3
```

## Meta Commands

```ls
metric m:month p:integer l:Month t:dataTypeName=number

metric m:coach_passengers p:integer l:"Coach Passengers" t:dataTypeName=number

entity e:39r6-cbzf l:"Coach Bus Passengers per Month at Port Authority of NY NJ Airports: Beginning 2002" t:attribution="The Port Authority of New York & New Jersey" t:url=https://data.ny.gov/api/views/39r6-cbzf

property e:39r6-cbzf t:meta.view v:id=39r6-cbzf v:category=Transportation v:attributionLink=http://www.panynj.gov/airports/ewr-public-transportation.html v:averageRating=0 v:name="Coach Bus Passengers per Month at Port Authority of NY NJ Airports: Beginning 2002" v:attribution="The Port Authority of New York & New Jersey"

property e:39r6-cbzf t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:39r6-cbzf t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:39r6-cbzf t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```