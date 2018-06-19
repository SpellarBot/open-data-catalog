# Air Carrier Runway Use

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/air-carrier-runway-use) |
| Metadata | [Link](https://data.sfgov.org/api/views/hatm-btvp) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/hatm-btvp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/hatm-btvp/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | hatm-btvp |
| Name | Air Carrier Runway Use |
| Attribution | San Francisco International Airport |
| Category | Transportation |
| Tags | airlines, air carrier, sfo, airport, runway, runways |
| Created | 2016-04-08T22:23:43Z |
| Publication Date | 2016-04-08T23:06:16Z |

## Description

Air carrier runway use for all hours.  Amount of operations by runway is provided. Percent of departures and arrivals are calculated based on the month's total departures and total arrivals.  This data shows runway usage resulting in certain air traffic patterns used by aircraft to safely take-off and land.

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | ============== | ===================================== | ===================================== | ========= | =========== |
| No       |                | year                                  | Year                                  | number    | number      |
| No       |                | month                                 | Month                                 | number    | number      |
| Yes      | numeric metric | 01l_r_departure                       | 01L/R Departure                       | number    | number      |
| Yes      | numeric metric | 01l_r_departurepercentage_utilization | 01L/R DeparturePercentage Utilization | percent   | percent     |
| Yes      | numeric metric | 10l_r_departure                       | 10L/R Departure                       | number    | number      |
| Yes      | numeric metric | 10l_r_departurepercentage_utilization | 10L/R DeparturePercentage Utilization | percent   | percent     |
| Yes      | numeric metric | 19l_r_departure                       | 19L/R Departure                       | number    | number      |
| Yes      | numeric metric | 19l_r_departurepercentage_utilization | 19L/R DeparturePercentage Utilization | percent   | percent     |
| Yes      | numeric metric | 28l_r_departure                       | 28L/R Departure                       | number    | number      |
| Yes      | numeric metric | 28l_r_departurepercentage_utilization | 28L/R DeparturePercentage Utilization | percent   | percent     |
| Yes      | numeric metric | 01l_r_arrival                         | 01L/R Arrival                         | number    | number      |
| Yes      | numeric metric | 01l_r_arrivalpercentage_utilization   | 01L/R ArrivalPercentage Utilization   | percent   | percent     |
| Yes      | numeric metric | 10l_r_arrival                         | 10L/R Arrival                         | number    | number      |
| Yes      | numeric metric | 10l_r_arrivalpercentage_utilization   | 10L/R ArrivalPercentage Utilization   | percent   | percent     |
| Yes      | numeric metric | 19l_r_arrival                         | 19L/R Arrival                         | number    | number      |
| Yes      | numeric metric | 19l_r_arrivalpercentage_utilization   | 19L/R ArrivalPercentage Utilization   | percent   | percent     |
| Yes      | numeric metric | 28l_r_arrival                         | 28L/R Arrival                         | number    | number      |
| Yes      | numeric metric | 28l_r_arrivalpercentage_utilization   | 28L/R ArrivalPercentage Utilization   | percent   | percent     |
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
series e:hatm-btvp d:2005-01-01T00:00:00.000Z m:10l_r_arrivalpercentage_utilization=0 m:28l_r_arrivalpercentage_utilization=86.1 m:28l_r_departure=2943 m:28l_r_departurepercentage_utilization=25.2 m:01l_r_departure=6977 m:28l_r_arrival=10142 m:10l_r_departure=1554 m:10l_r_departurepercentage_utilization=13.3 m:19l_r_arrival=1642 m:01l_r_departurepercentage_utilization=59.7 m:10l_r_arrival=0 m:19l_r_departure=206 m:01l_r_arrival=0 m:19l_r_arrivalpercentage_utilization=13.9 m:01l_r_arrivalpercentage_utilization=0 m:19l_r_departurepercentage_utilization=1.8

series e:hatm-btvp d:2005-02-01T00:00:00.000Z m:10l_r_arrivalpercentage_utilization=1.2 m:28l_r_arrivalpercentage_utilization=79.1 m:28l_r_departure=1730 m:28l_r_departurepercentage_utilization=16.2 m:01l_r_departure=6584 m:28l_r_arrival=8533 m:10l_r_departure=2348 m:10l_r_departurepercentage_utilization=22 m:19l_r_arrival=2125 m:01l_r_departurepercentage_utilization=61.6 m:10l_r_arrival=125 m:19l_r_departure=24 m:01l_r_arrival=0 m:19l_r_arrivalpercentage_utilization=19.7 m:01l_r_arrivalpercentage_utilization=0 m:19l_r_departurepercentage_utilization=0.2

series e:hatm-btvp d:2005-03-01T00:00:00.000Z m:10l_r_arrivalpercentage_utilization=0 m:28l_r_arrivalpercentage_utilization=89.6 m:28l_r_departure=3650 m:28l_r_departurepercentage_utilization=30.2 m:01l_r_departure=7165 m:28l_r_arrival=10930 m:10l_r_departure=1232 m:10l_r_departurepercentage_utilization=10.2 m:19l_r_arrival=1144 m:01l_r_departurepercentage_utilization=59.3 m:10l_r_arrival=0 m:19l_r_departure=30 m:01l_r_arrival=118 m:19l_r_arrivalpercentage_utilization=9.4 m:01l_r_arrivalpercentage_utilization=1 m:19l_r_departurepercentage_utilization=0.2
```

## Meta Commands

```ls
metric m:01l_r_departure p:integer l:"01L/R Departure" t:dataTypeName=number

metric m:01l_r_departurepercentage_utilization p:float l:"01L/R DeparturePercentage Utilization" t:dataTypeName=percent

metric m:10l_r_departure p:integer l:"10L/R Departure" t:dataTypeName=number

metric m:10l_r_departurepercentage_utilization p:float l:"10L/R DeparturePercentage Utilization" t:dataTypeName=percent

metric m:19l_r_departure p:integer l:"19L/R Departure" t:dataTypeName=number

metric m:19l_r_departurepercentage_utilization p:float l:"19L/R DeparturePercentage Utilization" t:dataTypeName=percent

metric m:28l_r_departure p:integer l:"28L/R Departure" t:dataTypeName=number

metric m:28l_r_departurepercentage_utilization p:float l:"28L/R DeparturePercentage Utilization" t:dataTypeName=percent

metric m:01l_r_arrival p:integer l:"01L/R Arrival" t:dataTypeName=number

metric m:01l_r_arrivalpercentage_utilization p:float l:"01L/R ArrivalPercentage Utilization" t:dataTypeName=percent

metric m:10l_r_arrival p:integer l:"10L/R Arrival" t:dataTypeName=number

metric m:10l_r_arrivalpercentage_utilization p:float l:"10L/R ArrivalPercentage Utilization" t:dataTypeName=percent

metric m:19l_r_arrival p:integer l:"19L/R Arrival" t:dataTypeName=number

metric m:19l_r_arrivalpercentage_utilization p:float l:"19L/R ArrivalPercentage Utilization" t:dataTypeName=percent

metric m:28l_r_arrival p:integer l:"28L/R Arrival" t:dataTypeName=number

metric m:28l_r_arrivalpercentage_utilization p:float l:"28L/R ArrivalPercentage Utilization" t:dataTypeName=percent

entity e:hatm-btvp l:"Air Carrier Runway Use" t:attribution="San Francisco International Airport" t:url=https://data.sfgov.org/api/views/hatm-btvp

property e:hatm-btvp t:meta.view v:id=hatm-btvp v:category=Transportation v:attributionLink=http://www.flysfo.com v:averageRating=0 v:name="Air Carrier Runway Use" v:attribution="San Francisco International Airport"

property e:hatm-btvp t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:hatm-btvp t:meta.view.owner v:id=pswe-pn7t v:screenName=NoiseAbatementOffice@flysfo.com v:displayName=NoiseAbatementOffice@flysfo.com

property e:hatm-btvp t:meta.view.tableauthor v:id=pswe-pn7t v:screenName=NoiseAbatementOffice@flysfo.com v:roleName=editor v:displayName=NoiseAbatementOffice@flysfo.com
```

## Top Records

```ls
| year | month | 01l_r_departure | 01l_r_departurepercentage_utilization | 10l_r_departure | 10l_r_departurepercentage_utilization | 19l_r_departure | 19l_r_departurepercentage_utilization | 28l_r_departure | 28l_r_departurepercentage_utilization | 01l_r_arrival | 01l_r_arrivalpercentage_utilization | 10l_r_arrival | 10l_r_arrivalpercentage_utilization | 19l_r_arrival | 19l_r_arrivalpercentage_utilization | 28l_r_arrival | 28l_r_arrivalpercentage_utilization | 
| ==== | ===== | =============== | ===================================== | =============== | ===================================== | =============== | ===================================== | =============== | ===================================== | ============= | =================================== | ============= | =================================== | ============= | =================================== | ============= | =================================== | 
| 2005 | 1     | 6977            | 59.7                                  | 1554            | 13.3                                  | 206             | 1.8                                   | 2943            | 25.2                                  | 0             | 0.0                                 | 0             | 0.0                                 | 1642          | 13.9                                | 10142         | 86.1                                | 
| 2005 | 2     | 6584            | 61.6                                  | 2348            | 22.0                                  | 24              | 0.2                                   | 1730            | 16.2                                  | 0             | 0.0                                 | 125           | 1.2                                 | 2125          | 19.7                                | 8533          | 79.1                                | 
| 2005 | 3     | 7165            | 59.3                                  | 1232            | 10.2                                  | 30              | 0.2                                   | 3650            | 30.2                                  | 118           | 1.0                                 | 0             | 0.0                                 | 1144          | 9.4                                 | 10930         | 89.6                                | 
| 2005 | 4     | 7494            | 64.0                                  | 833             | 7.1                                   | 69              | 0.6                                   | 3322            | 28.3                                  | 0             | 0.0                                 | 2             | 0.0                                 | 794           | 6.7                                 | 11077         | 93.3                                | 
| 2005 | 5     | 7767            | 63.1                                  | 792             | 6.4                                   | 2               | 0.0                                   | 3743            | 30.4                                  | 0             | 0.0                                 | 0             | 0.0                                 | 677           | 5.4                                 | 11799         | 94.6                                | 
| 2005 | 6     | 5980            | 48.4                                  | 156             | 1.3                                   | 0               | 0.0                                   | 6217            | 50.3                                  | 0             | 0.0                                 | 0             | 0.0                                 | 72            | 0.6                                 | 12463         | 99.4                                | 
| 2005 | 7     | 8380            | 68.5                                  | 69              | 0.6                                   | 0               | 0.0                                   | 3782            | 30.9                                  | 3             | 0.0                                 | 0             | 0.0                                 | 0             | 0.0                                 | 12648         | 100.0                               | 
| 2005 | 8     | 9640            | 74.8                                  | 88              | 0.7                                   | 0               | 0.0                                   | 3164            | 24.5                                  | 0             | 0.0                                 | 0             | 0.0                                 | 0             | 0.0                                 | 13104         | 100.0                               | 
| 2005 | 9     | 8999            | 75.1                                  | 153             | 1.3                                   | 0               | 0.0                                   | 2838            | 23.7                                  | 0             | 0.0                                 | 0             | 0.0                                 | 0             | 0.0                                 | 12355         | 100.0                               | 
| 2005 | 10    | 9060            | 74.6                                  | 232             | 1.9                                   | 0               | 0.0                                   | 2857            | 23.5                                  | 0             | 0.0                                 | 0             | 0.0                                 | 78            | 0.6                                 | 12515         | 99.4                                | 
```