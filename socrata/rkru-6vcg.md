# Air Traffic Passenger Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/air-traffic-passenger-statistics) |
| Metadata | [Link](https://data.sfgov.org/api/views/rkru-6vcg) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/rkru-6vcg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/rkru-6vcg/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | rkru-6vcg |
| Name | Air Traffic Passenger Statistics |
| Category | Transportation |
| Tags | passengers, airport, travel |
| Created | 2016-04-19T23:51:23Z |
| Publication Date | 2017-03-14T21:16:56Z |

## Description

San Francisco International Airport Report on Monthly Passenger Traffic Statistics by Airline. Airport data is seasonal in nature, therefore any comparative analyses should be done on a period-over-period basis (i.e. January 2010 vs. January 2009) as opposed to period-to-period (i.e. January 2010 vs. February 2010). It is also important to note that fact and attribute field relationships are not always 1-to-1. For example, Passenger Counts belonging to United Airlines will appear in multiple attribute fields and are additive, which provides flexibility for the user to derive categorical Passenger Counts as desired.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | time           | activity_period             | Activity Period             | number    | number      |
| Yes      | series tag     | operating_airline           | Operating Airline           | text      | text        |
| Yes      | series tag     | operating_airline_iata_code | Operating Airline IATA Code | text      | text        |
| Yes      | series tag     | published_airline           | Published Airline           | text      | text        |
| Yes      | series tag     | published_airline_iata_code | Published Airline IATA Code | text      | text        |
| Yes      | series tag     | geo_summary                 | GEO Summary                 | text      | text        |
| Yes      | series tag     | geo_region                  | GEO Region                  | text      | text        |
| Yes      | series tag     | activity_type_code          | Activity Type Code          | text      | text        |
| Yes      | series tag     | price_category_code         | Price Category Code         | text      | text        |
| Yes      | series tag     | terminal                    | Terminal                    | text      | text        |
| Yes      | series tag     | boarding_area               | Boarding Area               | text      | text        |
| Yes      | numeric metric | passenger_count             | Passenger Count             | number    | number      |
```

## Time Field

```ls
Value = activity_period
Format & Zone = yyyyMM
```

## Data Commands

```ls
series e:rkru-6vcg d:2005-07-01T00:00:00.000Z t:activity_type_code=Deplaned t:boarding_area=B t:terminal="Terminal 1" t:geo_summary=Domestic t:geo_region=US t:operating_airline_iata_code=TZ t:published_airline="ATA Airlines" t:published_airline_iata_code=TZ t:operating_airline="ATA Airlines" t:price_category_code="Low Fare" m:passenger_count=27271

series e:rkru-6vcg d:2005-07-01T00:00:00.000Z t:activity_type_code=Enplaned t:boarding_area=B t:terminal="Terminal 1" t:geo_summary=Domestic t:geo_region=US t:operating_airline_iata_code=TZ t:published_airline="ATA Airlines" t:published_airline_iata_code=TZ t:operating_airline="ATA Airlines" t:price_category_code="Low Fare" m:passenger_count=29131

series e:rkru-6vcg d:2005-07-01T00:00:00.000Z t:activity_type_code="Thru / Transit" t:boarding_area=B t:terminal="Terminal 1" t:geo_summary=Domestic t:geo_region=US t:operating_airline_iata_code=TZ t:published_airline="ATA Airlines" t:published_airline_iata_code=TZ t:operating_airline="ATA Airlines" t:price_category_code="Low Fare" m:passenger_count=5415
```

## Meta Commands

```ls
metric m:passenger_count p:integer l:"Passenger Count" t:dataTypeName=number

entity e:rkru-6vcg l:"Air Traffic Passenger Statistics" t:url=https://data.sfgov.org/api/views/rkru-6vcg

property e:rkru-6vcg t:meta.view v:id=rkru-6vcg v:category=Transportation v:averageRating=0 v:name="Air Traffic Passenger Statistics"

property e:rkru-6vcg t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:rkru-6vcg t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:rkru-6vcg t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| activity_period | operating_airline | operating_airline_iata_code | published_airline | published_airline_iata_code | geo_summary   | geo_region | activity_type_code | price_category_code | terminal      | boarding_area | passenger_count | 
| =============== | ================= | =========================== | ================= | =========================== | ============= | ========== | ================== | =================== | ============= | ============= | =============== | 
|                 |                   |                             |                   |                             |               |            |                    |                     |               |               |                 | 
|                 |                   |                             |                   |                             |               |            |                    |                     |               |               |                 | 
|                 | Operating Airline | Operating Airline IATA Code | Published Airline | Published Airline IATA Code | GEO Summary   | GEO Region | Activity Type Code | Price Category Code | Terminal      | Boarding Area |                 | 
| 200507          | ATA Airlines      | TZ                          | ATA Airlines      | TZ                          | Domestic      | US         | Deplaned           | Low Fare            | Terminal 1    | B             | 27271           | 
| 200507          | ATA Airlines      | TZ                          | ATA Airlines      | TZ                          | Domestic      | US         | Enplaned           | Low Fare            | Terminal 1    | B             | 29131           | 
| 200507          | ATA Airlines      | TZ                          | ATA Airlines      | TZ                          | Domestic      | US         | Thru / Transit     | Low Fare            | Terminal 1    | B             | 5415            | 
| 200507          | Air Canada        | AC                          | Air Canada        | AC                          | International | Canada     | Deplaned           | Other               | Terminal 1    | B             | 35156           | 
| 200507          | Air Canada        | AC                          | Air Canada        | AC                          | International | Canada     | Enplaned           | Other               | Terminal 1    | B             | 34090           | 
| 200507          | Air China         | CA                          | Air China         | CA                          | International | Asia       | Deplaned           | Other               | International | G             | 6263            | 
| 200507          | Air China         | CA                          | Air China         | CA                          | International | Asia       | Enplaned           | Other               | International | G             | 5500            | 
```