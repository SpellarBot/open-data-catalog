# Air Traffic Landings Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/air-traffic-landings-statistics) |
| Metadata | [Link](https://data.sfgov.org/api/views/fpux-q53t) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/fpux-q53t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/fpux-q53t/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | fpux-q53t |
| Name | Air Traffic Landings Statistics |
| Category | Transportation |
| Tags | landings, airlines, airport, flights, sfo |
| Created | 2016-04-26T01:09:37Z |
| Publication Date | 2017-03-14T21:17:30Z |

## Description

San Francisco International Airport data on Landings Statistics. Airport data is seasonal in nature, therefore any comparative analyses should be done on a period-over-period basis (i.e. January 2010 vs. January 2009) as opposed to period-to-period (i.e. January 2010 vs. February 2010). It is also important to note that fact and attribute field relationships are not always 1-to-1. For example, Aircraft Landings belonging to United Airlines will appear in multiple attribute fields and are additive, which provides flexibility for the user to derive categorical Aircraft Landings Statistics as desired.

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
| Yes      | series tag     | landing_aircraft_type       | Landing Aircraft Type       | text      | text        |
| Yes      | series tag     | aircraft_body_type          | Aircraft Body Type          | text      | text        |
| Yes      | series tag     | aircraft_manufacturer       | Aircraft Manufacturer       | text      | text        |
| Yes      | series tag     | aircraft_model              | Aircraft Model              | text      | text        |
| Yes      | series tag     | aircraft_version            | Aircraft Version            | text      | text        |
| Yes      | numeric metric | landing_count               | Landing Count               | number    | number      |
| Yes      | numeric metric | total_landed_weight         | Total Landed Weight         | number    | number      |
```

## Time Field

```ls
Value = activity_period
Format & Zone = yyyyMM
```

## Data Commands

```ls
series e:fpux-q53t d:2005-07-01T00:00:00.000Z t:aircraft_body_type="Narrow Body" t:aircraft_version=30 t:aircraft_manufacturer="McDonnell Douglas" t:geo_summary=Domestic t:geo_region=US t:operating_airline_iata_code=GB t:aircraft_model=DC-9 t:published_airline="ABX Air" t:published_airline_iata_code=GB t:landing_aircraft_type=Freighter t:operating_airline="ABX Air" m:total_landed_weight=4066000 m:landing_count=40

series e:fpux-q53t d:2005-07-01T00:00:00.000Z t:aircraft_body_type="Narrow Body" t:aircraft_version=41 t:aircraft_manufacturer="McDonnell Douglas" t:geo_summary=Domestic t:geo_region=US t:operating_airline_iata_code=GB t:aircraft_model=DC-9 t:published_airline="ABX Air" t:published_airline_iata_code=GB t:landing_aircraft_type=Freighter t:operating_airline="ABX Air" m:total_landed_weight=102000 m:landing_count=1

series e:fpux-q53t d:2005-07-01T00:00:00.000Z t:aircraft_body_type="Narrow Body" t:aircraft_version=200 t:aircraft_manufacturer=Boeing t:geo_summary=Domestic t:geo_region=US t:operating_airline_iata_code=TZ t:aircraft_model=757 t:published_airline="ATA Airlines" t:published_airline_iata_code=TZ t:landing_aircraft_type=Passenger t:operating_airline="ATA Airlines" m:total_landed_weight=396000 m:landing_count=2
```

## Meta Commands

```ls
metric m:landing_count p:integer l:"Landing Count" t:dataTypeName=number

metric m:total_landed_weight p:integer l:"Total Landed Weight" t:dataTypeName=number

entity e:fpux-q53t l:"Air Traffic Landings Statistics" t:url=https://data.sfgov.org/api/views/fpux-q53t

property e:fpux-q53t t:meta.view v:id=fpux-q53t v:category=Transportation v:averageRating=0 v:name="Air Traffic Landings Statistics"

property e:fpux-q53t t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:fpux-q53t t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:fpux-q53t t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| activity_period | operating_airline | operating_airline_iata_code | published_airline | published_airline_iata_code | geo_summary   | geo_region | landing_aircraft_type | aircraft_body_type | aircraft_manufacturer | aircraft_model | aircraft_version | landing_count | total_landed_weight | 
| =============== | ================= | =========================== | ================= | =========================== | ============= | ========== | ===================== | ================== | ===================== | ============== | ================ | ============= | =================== | 
| 200507          | ABX Air           | GB                          | ABX Air           | GB                          | Domestic      | US         | Freighter             | Narrow Body        | McDonnell Douglas     | DC-9           | 30               | 40            | 4066000             | 
| 200507          | ABX Air           | GB                          | ABX Air           | GB                          | Domestic      | US         | Freighter             | Narrow Body        | McDonnell Douglas     | DC-9           | 41               | 1             | 102000              | 
| 200507          | ATA Airlines      | TZ                          | ATA Airlines      | TZ                          | Domestic      | US         | Passenger             | Narrow Body        | Boeing                | 757            | 200              | 2             | 396000              | 
| 200507          | ATA Airlines      | TZ                          | ATA Airlines      | TZ                          | Domestic      | US         | Passenger             | Narrow Body        | Boeing                | 757            | 300              | 167           | 37408000            | 
| 200507          | Air Canada        | AC                          | Air Canada        | AC                          | International | Canada     | Passenger             | Wide Body          | Boeing                | 767            | 333              | 1             | 320000              | 
| 200507          | Air Canada        | AC                          | Air Canada        | AC                          | International | Canada     | Passenger             | Narrow Body        | Airbus                | A319           | 114              | 160           | 21520000            | 
| 200507          | Air Canada        | AC                          | Air Canada        | AC                          | International | Canada     | Passenger             | Narrow Body        | Airbus                | A320           | 211              | 146           | 20761200            | 
| 200507          | Air Canada        | AC                          | Air Canada        | AC                          | International | Canada     | Passenger             | Narrow Body        | Airbus                | A321           | 211              | 2             | 343040              | 
| 200507          | Air China         | CA                          | Air China         | CA                          | International | Asia       | Passenger             | Wide Body          | Boeing                | 747            | 400              | 23            | 14490000            | 
| 200507          | Air France        | AF                          | Air France        | AF                          | International | Europe     | Passenger             | Wide Body          | Boeing                | 747            | 400              | 31            | 18855500            | 
```