# Prison Forecast History, Comparison to Actual, Detail

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/prison-forecast-history-comparison-to-actual-detail-a681e) |
| Metadata | [Link](https://data.oregon.gov/api/views/dmqk-bvvc) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/dmqk-bvvc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/dmqk-bvvc/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | dmqk-bvvc |
| Name | Prison Forecast History, Comparison to Actual, Detail |
| Attribution | Damon Bell, Oregon Office of Economic Analysis |
| Tags | prison inmate population forecast actual count comparison oregon projection estimate inmates prisoners corrections economic analysis oea |
| Created | 2012-02-13T14:51:24Z |
| Publication Date | 2012-02-13T15:04:47Z |

## Description

Oregon prison inmate forecast values for all OEA forecasts (1995 on), and some from 1993, 1994. Includes actual population counts and differences for each forecast value (if actual is known).

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | time           | dateofforecast       | DateOfForecast       | date      | date        |
| No       |                | dateofforecast_year  | DateOfForecast_Year  | text      | number      |
| Yes      | series tag     | dateofforecast_month | DateOfForecast_Month | text      | text        |
| No       |                | futuredate           | FutureDate           | date      | date        |
| No       |                | futureyear           | FutureYear           | number    | number      |
| Yes      | series tag     | futuremonth          | FutureMonth          | text      | text        |
| Yes      | numeric metric | yearsintofuture      | YearsIntoFuture      | number    | number      |
| Yes      | numeric metric | monthsintofuture     | MonthsIntoFuture     | number    | number      |
| Yes      | numeric metric | monthremainder       | MonthRemainder       | number    | number      |
| Yes      | numeric metric | forecastvalue        | ForecastValue        | number    | number      |
| Yes      | numeric metric | actualvalue          | ActualValue          | number    | number      |
| Yes      | numeric metric | forecastminusactual  | ForecastMinusActual  | number    | number      |
| Yes      | numeric metric | actualminusforecast  | ActualMinusForecast  | number    | number      |
| Yes      | series tag     | note                 | Note                 | text      | text        |
```

## Time Field

```ls
Value = dateofforecast
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = futuredate,futureyear,dateofforecast_year
```

## Data Commands

```ls
series e:dmqk-bvvc d:1993-01-01T08:00:00.000Z t:dateofforecast_month=January t:futuremonth=January t:note=a m:monthremainder=0 m:forecastvalue=6487 m:forecastminusactual=0 m:yearsintofuture=0 m:actualminusforecast=0 m:actualvalue=6487 m:monthsintofuture=0

series e:dmqk-bvvc d:1993-01-01T08:00:00.000Z t:dateofforecast_month=January t:futuremonth=July t:note=a m:monthremainder=6 m:forecastvalue=6550 m:forecastminusactual=54 m:yearsintofuture=0 m:actualminusforecast=-54 m:actualvalue=6496 m:monthsintofuture=6

series e:dmqk-bvvc d:1993-01-01T08:00:00.000Z t:dateofforecast_month=January t:futuremonth=January t:note=a m:monthremainder=0 m:forecastvalue=6550 m:forecastminusactual=-107 m:yearsintofuture=1 m:actualminusforecast=107 m:actualvalue=6657 m:monthsintofuture=12
```

## Meta Commands

```ls
metric m:yearsintofuture p:integer l:YearsIntoFuture t:dataTypeName=number

metric m:monthsintofuture p:integer l:MonthsIntoFuture t:dataTypeName=number

metric m:monthremainder p:integer l:MonthRemainder t:dataTypeName=number

metric m:forecastvalue p:integer l:ForecastValue t:dataTypeName=number

metric m:actualvalue p:integer l:ActualValue t:dataTypeName=number

metric m:forecastminusactual p:integer l:ForecastMinusActual t:dataTypeName=number

metric m:actualminusforecast p:integer l:ActualMinusForecast t:dataTypeName=number

entity e:dmqk-bvvc l:"Prison Forecast History, Comparison to Actual, Detail" t:attribution="Damon Bell, Oregon Office of Economic Analysis" t:url=https://data.oregon.gov/api/views/dmqk-bvvc

property e:dmqk-bvvc t:meta.view v:id=dmqk-bvvc v:averageRating=0 v:name="Prison Forecast History, Comparison to Actual, Detail" v:attribution="Damon Bell, Oregon Office of Economic Analysis"

property e:dmqk-bvvc t:meta.view.license v:name="Public Domain"

property e:dmqk-bvvc t:meta.view.owner v:id=am3y-vzet v:screenName="Damon Bell" v:displayName="Damon Bell"

property e:dmqk-bvvc t:meta.view.tableauthor v:id=am3y-vzet v:screenName="Damon Bell" v:displayName="Damon Bell"
```

## Top Records

```ls
| dateofforecast | dateofforecast_year | dateofforecast_month | futuredate | futureyear | futuremonth | yearsintofuture | monthsintofuture | monthremainder | forecastvalue | actualvalue | forecastminusactual | actualminusforecast | note | 
| ============== | =================== | ==================== | ========== | ========== | =========== | =============== | ================ | ============== | ============= | =========== | =================== | =================== | ==== | 
|                |                     | DateOfForecast_Month |            |            | FutureMonth |                 |                  |                |               |             |                     |                     | Note | 
| 725875200      | 1993                | January              | 725875200  | 1993       | January     | 0               | 0                | 0              | 6487          | 6487        | 0                   | 0                   | a    | 
| 725875200      | 1993                | January              | 741510000  | 1993       | July        | 0               | 6                | 6              | 6550          | 6496        | 54                  | -54                 | a    | 
| 725875200      | 1993                | January              | 757411200  | 1994       | January     | 1               | 12               | 0              | 6550          | 6657        | -107                | 107                 | a    | 
| 725875200      | 1993                | January              | 773046000  | 1994       | July        | 1               | 18               | 6              | 6650          | 6832        | -182                | 182                 | a    | 
| 725875200      | 1993                | January              | 788947200  | 1995       | January     | 2               | 24               | 0              | 6550          | 7057        | -507                | 507                 | a    | 
| 725875200      | 1993                | January              | 804582000  | 1995       | July        | 2               | 30               | 6              | 6500          | 7532        | -1032               | 1032                | a    | 
| 725875200      | 1993                | January              | 820483200  | 1996       | January     | 3               | 36               | 0              | 6575          | 7886        | -1311               | 1311                | a    | 
| 725875200      | 1993                | January              | 836204400  | 1996       | July        | 3               | 42               | 6              | 6700          | 8490        | -1790               | 1790                | a    | 
| 725875200      | 1993                | January              | 852105600  | 1997       | January     | 4               | 48               | 0              | 6800          | 8544        | -1744               | 1744                | a    | 
```