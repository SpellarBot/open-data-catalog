# Late Night Preferential Runway Use

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/late-night-preferential-runway-use) |
| Metadata | [Link](https://data.sfgov.org/api/views/42ye-cb9x) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/42ye-cb9x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/42ye-cb9x/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 42ye-cb9x |
| Name | Late Night Preferential Runway Use |
| Category | Transportation |
| Tags | sfo, runways, runway, airlines, noise |
| Created | 2016-04-08T22:37:09Z |
| Publication Date | 2016-04-08T23:01:48Z |

## Description

The preferred departing runways from 1:00 a.m. to 6:00 a.m. are 10L/R, 01L/R or 28L/R with an immediate right-turn when safety, weather and traffic permits.  This reduces aircraft noise in residential communities surrounding the airport as over water-departure procedures directs aircraft over the bay. This dataset provides the amount of aircraft late night departures by runways.  The percent of departures are calculated based on the month's total departures.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       |                | year                        | Year                        | number    | number      |
| No       |                | month                       | Month                       | number    | number      |
| Yes      | numeric metric | 01l_r                       | 01L/R                       | number    | number      |
| Yes      | numeric metric | 01l_r_percent_of_departures | 01L/R Percent of Departures | percent   | percent     |
| Yes      | numeric metric | 10l_r                       | 10L/R                       | number    | number      |
| Yes      | numeric metric | 10l_r_percent_of_departures | 10L/R Percent of Departures | percent   | percent     |
| Yes      | numeric metric | 19l_r                       | 19L/R                       | number    | number      |
| Yes      | numeric metric | 19l_r_percent_of_departures | 19L/R Percent of Departures | percent   | percent     |
| Yes      | numeric metric | 28l_r                       | 28L/R                       | number    | number      |
| Yes      | numeric metric | 28l_r_percent_of_departures | 28L/R Percent of Departures | percent   | percent     |
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
series e:42ye-cb9x d:2005-01-01T00:00:00.000Z m:19l_r_percent_of_departures=2 m:28l_r=49 m:28l_r_percent_of_departures=21 m:10l_r_percent_of_departures=71 m:01l_r_percent_of_departures=6 m:19l_r=4 m:10l_r=164 m:01l_r=14

series e:42ye-cb9x d:2005-02-01T00:00:00.000Z m:19l_r_percent_of_departures=0 m:28l_r=25 m:28l_r_percent_of_departures=13 m:10l_r_percent_of_departures=80 m:01l_r_percent_of_departures=7 m:19l_r=0 m:10l_r=158 m:01l_r=14

series e:42ye-cb9x d:2005-03-01T00:00:00.000Z m:19l_r_percent_of_departures=0 m:28l_r=65 m:28l_r_percent_of_departures=27 m:10l_r_percent_of_departures=69 m:01l_r_percent_of_departures=4 m:19l_r=0 m:10l_r=165 m:01l_r=10
```

## Meta Commands

```ls
metric m:01l_r p:integer l:01L/R t:dataTypeName=number

metric m:01l_r_percent_of_departures p:integer l:"01L/R Percent of Departures" t:dataTypeName=percent

metric m:10l_r p:integer l:10L/R t:dataTypeName=number

metric m:10l_r_percent_of_departures p:integer l:"10L/R Percent of Departures" t:dataTypeName=percent

metric m:19l_r p:integer l:19L/R t:dataTypeName=number

metric m:19l_r_percent_of_departures p:integer l:"19L/R Percent of Departures" t:dataTypeName=percent

metric m:28l_r p:integer l:28L/R t:dataTypeName=number

metric m:28l_r_percent_of_departures p:integer l:"28L/R Percent of Departures" t:dataTypeName=percent

entity e:42ye-cb9x l:"Late Night Preferential Runway Use" t:url=https://data.sfgov.org/api/views/42ye-cb9x

property e:42ye-cb9x t:meta.view v:id=42ye-cb9x v:category=Transportation v:averageRating=0 v:name="Late Night Preferential Runway Use"

property e:42ye-cb9x t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:42ye-cb9x t:meta.view.owner v:id=pswe-pn7t v:screenName=NoiseAbatementOffice@flysfo.com v:displayName=NoiseAbatementOffice@flysfo.com

property e:42ye-cb9x t:meta.view.tableauthor v:id=pswe-pn7t v:screenName=NoiseAbatementOffice@flysfo.com v:roleName=editor v:displayName=NoiseAbatementOffice@flysfo.com
```

## Top Records

```ls
| year | month | 01l_r | 01l_r_percent_of_departures | 10l_r | 10l_r_percent_of_departures | 19l_r | 19l_r_percent_of_departures | 28l_r | 28l_r_percent_of_departures | 
| ==== | ===== | ===== | =========================== | ===== | =========================== | ===== | =========================== | ===== | =========================== | 
| 2005 | 1     | 14    | 6                           | 164   | 71                          | 4     | 2                           | 49    | 21                          | 
| 2005 | 2     | 14    | 7                           | 158   | 80                          | 0     | 0                           | 25    | 13                          | 
| 2005 | 3     | 10    | 4                           | 165   | 69                          | 0     | 0                           | 65    | 27                          | 
| 2005 | 4     | 26    | 9                           | 99    | 32                          | 0     | 0                           | 180   | 59                          | 
| 2005 | 5     | 36    | 10                          | 90    | 24                          | 0     | 0                           | 242   | 66                          | 
| 2005 | 6     | 26    | 6                           | 96    | 24                          | 0     | 0                           | 285   | 70                          | 
| 2005 | 7     | 73    | 18                          | 63    | 15                          | 0     | 0                           | 275   | 67                          | 
| 2005 | 8     | 113   | 28                          | 85    | 21                          | 0     | 0                           | 211   | 52                          | 
| 2005 | 9     | 50    | 13                          | 140   | 38                          | 0     | 0                           | 181   | 49                          | 
| 2005 | 10    | 53    | 15                          | 131   | 36                          | 0     | 0                           | 181   | 50                          | 
```