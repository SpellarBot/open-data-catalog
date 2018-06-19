# Employment, Unemployment, and Labor Force Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/employment-unemployment-and-labor-force-data) |
| Metadata | [Link](https://data.maryland.gov/api/views/ub9y-b3wy) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/ub9y-b3wy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/ub9y-b3wy/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | ub9y-b3wy |
| Name | Employment, Unemployment, and Labor Force Data |
| Attribution | U.S. Bureau of Labor Statistics |
| Category | Business and Economy |
| Tags | labor force participation, unemployment, employment, bls, bureau of labor statistics |
| Created | 2017-01-04T15:53:06Z |
| Publication Date | 2017-03-24T15:51:21Z |

## Description

This dataset uses seasonally adjusted data from the US Bureau of Labor Statistics to present information on Maryland's labor force participation rate, employment rate, and unemployment rate.

## Columns

```ls
| Included | Schema Type    | Field Name                                         | Name                                  | Data Type     | Render Type   |
| ======== | ============== | ================================================== | ===================================== | ============= | ============= |
| Yes      | time           | date                                               | Date                                  | calendar_date | calendar_date |
| No       |                | year                                               | Year                                  | number        | text          |
| No       |                | month                                              | Month                                 | text          | text          |
| No       |                | date_label                                         | Date Label                            | text          | text          |
| Yes      | numeric metric | civilian_non_institutional_population              | Civilian Non-institutional Population | number        | number        |
| Yes      | numeric metric | civilian_labor_force                               | Civilian Labor Force                  | number        | number        |
| Yes      | numeric metric | seasonally_adjusted_labor_force_participation_rate | Labor Force Participation Rate        | percent       | percent       |
| Yes      | numeric metric | employed                                           | Employed                              | number        | number        |
| Yes      | numeric metric | seasonally_adjusted_employment_rate                | Employment Rate                       | percent       | percent       |
| Yes      | numeric metric | unemployed_percent_of_population                   | Unemployed                            | number        | number        |
| Yes      | numeric metric | seasonally_adjusted_unemployment_rate              | Unemployment Rate                     | percent       | percent       |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_label,year,month
```

## Data Commands

```ls
series e:ub9y-b3wy d:2012-01-31T00:00:00.000Z m:seasonally_adjusted_unemployment_rate=6.9 m:seasonally_adjusted_employment_rate=63.1 m:unemployed_percent_of_population=214812 m:civilian_labor_force=3107283 m:civilian_non_institutional_population=4583192 m:seasonally_adjusted_labor_force_participation_rate=67.8 m:employed=2892471

series e:ub9y-b3wy d:2012-02-28T00:00:00.000Z m:seasonally_adjusted_unemployment_rate=6.9 m:seasonally_adjusted_employment_rate=63.1 m:unemployed_percent_of_population=214122 m:civilian_labor_force=3108975 m:civilian_non_institutional_population=4586821 m:seasonally_adjusted_labor_force_participation_rate=67.8 m:employed=2894853

series e:ub9y-b3wy d:2012-03-31T00:00:00.000Z m:seasonally_adjusted_unemployment_rate=6.9 m:seasonally_adjusted_employment_rate=63.1 m:unemployed_percent_of_population=214172 m:civilian_labor_force=3110484 m:civilian_non_institutional_population=4590439 m:seasonally_adjusted_labor_force_participation_rate=67.8 m:employed=2896312
```

## Meta Commands

```ls
metric m:civilian_non_institutional_population p:integer l:"Civilian Non-institutional Population" d:"Represents the civilian, non-institutional population of Maryland aged 16 and over. This is the universe of the labor pool." t:dataTypeName=number

metric m:civilian_labor_force p:integer l:"Civilian Labor Force" d:"This represents the number from the labor pool who are either employed or are seeking employment." t:dataTypeName=number

metric m:seasonally_adjusted_labor_force_participation_rate p:float l:"Labor Force Participation Rate" d:"The civilian labor force divided by the total civilian non-institutional population. This represents the ratio of those employed or seeking employment out of the total potential labor pool." t:dataTypeName=percent

metric m:employed p:integer l:Employed d:"The number of employed civilian, non-institutional residents age 16 and up" t:dataTypeName=number

metric m:seasonally_adjusted_employment_rate p:float l:"Employment Rate" d:"The number of employed residents divided by the civilian labor force. This represents the percentage of those employed out of those who want to be employed (employed or seeking employment)." t:dataTypeName=percent

metric m:unemployed_percent_of_population p:integer l:Unemployed d:"The number of unemployed civilian, non-institutional residents age 16 and up" t:dataTypeName=number

metric m:seasonally_adjusted_unemployment_rate p:float l:"Unemployment Rate" d:"The number of unemployed residents divided by the civilian labor force. This represents the percentage of those not employed out of those who want to be employed (employed or seeking employment)." t:dataTypeName=percent

entity e:ub9y-b3wy l:"Employment, Unemployment, and Labor Force Data" t:attribution="U.S. Bureau of Labor Statistics" t:url=https://data.maryland.gov/api/views/ub9y-b3wy

property e:ub9y-b3wy t:meta.view v:id=ub9y-b3wy v:category="Business and Economy" v:attributionLink=https://www.bls.gov/web/laus/ststdsadata.txt v:averageRating=0 v:name="Employment, Unemployment, and Labor Force Data" v:attribution="U.S. Bureau of Labor Statistics"

property e:ub9y-b3wy t:meta.view.license v:name="Public Domain"

property e:ub9y-b3wy t:meta.view.owner v:id=9ei4-2q5c v:screenName="Pat Pscherer" v:displayName="Pat Pscherer"

property e:ub9y-b3wy t:meta.view.tableauthor v:id=9ei4-2q5c v:screenName="Pat Pscherer" v:roleName=administrator v:displayName="Pat Pscherer"
```

## Top Records

```ls
| date                | year | month     | date_label | civilian_non_institutional_population | civilian_labor_force | seasonally_adjusted_labor_force_participation_rate | employed | seasonally_adjusted_employment_rate | unemployed_percent_of_population | seasonally_adjusted_unemployment_rate | 
| =================== | ==== | ========= | ========== | ===================================== | ==================== | ================================================== | ======== | =================================== | ================================ | ===================================== | 
| 2012-01-31T00:00:00 | 2012 | January   | Jan 2012   | 4583192                               | 3107283              | 67.8                                               | 2892471  | 63.1                                | 214812                           | 6.9                                   | 
| 2012-02-28T00:00:00 | 2012 | February  | Feb 2012   | 4586821                               | 3108975              | 67.8                                               | 2894853  | 63.1                                | 214122                           | 6.9                                   | 
| 2012-03-31T00:00:00 | 2012 | March     | Mar 2012   | 4590439                               | 3110484              | 67.8                                               | 2896312  | 63.1                                | 214172                           | 6.9                                   | 
| 2012-04-30T00:00:00 | 2012 | April     | Apr 2012   | 4594078                               | 3111805              | 67.7                                               | 2897197  | 63.1                                | 214608                           | 6.9                                   | 
| 2012-05-31T00:00:00 | 2012 | May       | May 2012   | 4597729                               | 3113233              | 67.7                                               | 2898204  | 63                                  | 215029                           | 6.9                                   | 
| 2012-06-30T00:00:00 | 2012 | June      | Jun 2012   | 4601637                               | 3115037              | 67.7                                               | 2899860  | 63                                  | 215177                           | 6.9                                   | 
| 2012-07-31T00:00:00 | 2012 | July      | Jul 2012   | 4605667                               | 3117351              | 67.7                                               | 2902369  | 63                                  | 214982                           | 6.9                                   | 
| 2012-08-31T00:00:00 | 2012 | August    | Aug 2012   | 4609883                               | 3120053              | 67.7                                               | 2905501  | 63                                  | 214552                           | 6.9                                   | 
| 2012-09-30T00:00:00 | 2012 | September | Sep 2012   | 4614155                               | 3122961              | 67.7                                               | 2908807  | 63                                  | 214154                           | 6.9                                   | 
| 2012-10-31T00:00:00 | 2012 | October   | Oct 2012   | 4618405                               | 3125628              | 67.7                                               | 2911791  | 63                                  | 213837                           | 6.8                                   | 
```