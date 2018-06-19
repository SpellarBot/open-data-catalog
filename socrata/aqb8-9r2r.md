# Nighttime Power Runups

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nighttime-power-runups) |
| Metadata | [Link](https://data.sfgov.org/api/views/aqb8-9r2r) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/aqb8-9r2r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/aqb8-9r2r/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | aqb8-9r2r |
| Name | Nighttime Power Runups |
| Attribution | San Francisco International Airport |
| Category | Transportation |
| Tags | aircraft, engine runs, airport, sfo, noise, complaints |
| Created | 2016-04-08T22:43:25Z |
| Publication Date | 2016-04-08T22:59:33Z |

## Description

A power runup is a procedure used to test an aircraft engine or aircraft system after maintenance is completed.  This is done to ensure safe and normal operating standards prior to returning aircraft to service.  High power runups performed by aircraft operators are monitored to manage noise.

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                        | Data Type | Render Type |
| ======== | ============== | =========================================== | =========================================== | ========= | =========== |
| No       |                | year                                        | Year                                        | number    | number      |
| No       |                | month                                       | Month                                       | number    | number      |
| Yes      | series tag     | airline_code                                | Airline Code                                | text      | text        |
| Yes      | series tag     | airline                                     | Airline                                     | text      | text        |
| Yes      | numeric metric | number_of_power_run_ups                     | Number of Power Run-ups                     | number    | number      |
| Yes      | numeric metric | number_of_power_run_ups_per_1000_departures | Number of Power Run-ups per 1000 Departures | number    | number      |
| Yes      | numeric metric | percentage_of_power_run_ups_for_the_period  | Percentage of Power Run-ups for the Period  | percent   | percent     |
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
series e:aqb8-9r2r d:2005-01-01T00:00:00.000Z t:airline_code=DHL t:airline=DHL m:number_of_power_run_ups_per_1000_departures=23.5 m:number_of_power_run_ups=1 m:percentage_of_power_run_ups_for_the_period=4

series e:aqb8-9r2r d:2005-01-01T00:00:00.000Z t:airline_code=AAL t:airline="AMERICAN AIRLINES" m:number_of_power_run_ups_per_1000_departures=11.9 m:number_of_power_run_ups=12 m:percentage_of_power_run_ups_for_the_period=43

series e:aqb8-9r2r d:2005-01-01T00:00:00.000Z t:airline_code=UAL t:airline="UNITED AIR LINES" m:number_of_power_run_ups_per_1000_departures=3.8 m:number_of_power_run_ups=15 m:percentage_of_power_run_ups_for_the_period=54
```

## Meta Commands

```ls
metric m:number_of_power_run_ups p:integer l:"Number of Power Run-ups" t:dataTypeName=number

metric m:number_of_power_run_ups_per_1000_departures p:float l:"Number of Power Run-ups per 1000 Departures" t:dataTypeName=number

metric m:percentage_of_power_run_ups_for_the_period p:integer l:"Percentage of Power Run-ups for the Period" t:dataTypeName=percent

entity e:aqb8-9r2r l:"Nighttime Power Runups" t:attribution="San Francisco International Airport" t:url=https://data.sfgov.org/api/views/aqb8-9r2r

property e:aqb8-9r2r t:meta.view v:id=aqb8-9r2r v:category=Transportation v:attributionLink=http://www.flysfo.com v:averageRating=0 v:name="Nighttime Power Runups" v:attribution="San Francisco International Airport"

property e:aqb8-9r2r t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:aqb8-9r2r t:meta.view.owner v:id=pswe-pn7t v:screenName=NoiseAbatementOffice@flysfo.com v:displayName=NoiseAbatementOffice@flysfo.com

property e:aqb8-9r2r t:meta.view.tableauthor v:id=pswe-pn7t v:screenName=NoiseAbatementOffice@flysfo.com v:roleName=editor v:displayName=NoiseAbatementOffice@flysfo.com
```

## Top Records

```ls
| year | month | airline_code | airline            | number_of_power_run_ups | number_of_power_run_ups_per_1000_departures | percentage_of_power_run_ups_for_the_period | 
| ==== | ===== | ============ | ================== | ======================= | =========================================== | ========================================== | 
| 2005 | 1     | DHL          | DHL                | 1                       | 23.5                                        | 4                                          | 
| 2005 | 1     | AAL          | AMERICAN AIRLINES  | 12                      | 11.9                                        | 43                                         | 
| 2005 | 1     | UAL          | UNITED AIR LINES   | 15                      | 3.8                                         | 54                                         | 
| 2005 | 2     | DAL          | DELTA AIR LINES    | 1                       | 2.3                                         | 4                                          | 
| 2005 | 2     | KAL          | KOREAN AIR         | 1                       | 27.0                                        | 4                                          | 
| 2005 | 2     | AAL          | AMERICAN AIRLINES  | 5                       | 5.5                                         | 19                                         | 
| 2005 | 2     | UAL          | UNITED AIR LINES   | 20                      | 5.5                                         | 74                                         | 
| 2005 | 3     | AAL          | AMERICAN AIRLINES  | 12                      | 11.7                                        | 32                                         | 
| 2005 | 3     | UAL          | UNITED AIR LINES   | 26                      | 6.3                                         | 68                                         | 
| 2005 | 4     | AMT          | AMERICAN TRANS AIR | 1                       | 6.8                                         | 3                                          | 
```