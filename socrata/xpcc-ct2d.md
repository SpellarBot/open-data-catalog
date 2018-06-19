# Lead By Example Hawaii State Agencies Electricity Consumption

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lead-by-example-hawaii-state-agencies-electricity-consumption-c0684) |
| Metadata | [Link](https://data.hawaii.gov/api/views/xpcc-ct2d) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/xpcc-ct2d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/xpcc-ct2d/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | xpcc-ct2d |
| Name | Lead By Example Hawaii State Agencies Electricity Consumption |
| Created | 2012-11-21T18:05:09Z |
| Publication Date | 2017-02-22T22:32:26Z |

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                     | Data Type | Render Type |
| ======== | ============== | ============================ | ======================== | ========= | =========== |
| No       | time           | :updated_at                  | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year                  | Fiscal Year              | text      | text        |
| Yes      | numeric metric | electrical_consumption_gwhs  | Million Kilowatt - hours | number    | number      |
| Yes      | numeric metric | cost_of_electricity_millions | Difference               | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xpcc-ct2d d:2017-02-22T22:25:27.000Z t:fiscal_year="FY 10" m:cost_of_electricity_millions=-2.8 m:electrical_consumption_gwhs=643.35

series e:xpcc-ct2d d:2017-02-22T22:26:24.000Z t:fiscal_year="FY 11" m:cost_of_electricity_millions=0.6 m:electrical_consumption_gwhs=647.12

series e:xpcc-ct2d d:2017-02-22T22:26:55.000Z t:fiscal_year="FY 12" m:cost_of_electricity_millions=-0.8 m:electrical_consumption_gwhs=641.65
```

## Meta Commands

```ls
metric m:electrical_consumption_gwhs p:float l:"Million Kilowatt - hours" t:dataTypeName=number

metric m:cost_of_electricity_millions p:float l:Difference t:dataTypeName=percent

entity e:xpcc-ct2d l:"Lead By Example Hawaii State Agencies Electricity Consumption" t:url=https://data.hawaii.gov/api/views/xpcc-ct2d

property e:xpcc-ct2d t:meta.view v:id=xpcc-ct2d v:averageRating=0 v:name="Lead By Example Hawaii State Agencies Electricity Consumption"

property e:xpcc-ct2d t:meta.view.owner v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:displayName="Jerome Koehler"

property e:xpcc-ct2d t:meta.view.tableauthor v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:roleName=publisher v:displayName="Jerome Koehler"
```

## Top Records

```ls
| :updated_at | fiscal_year | electrical_consumption_gwhs | cost_of_electricity_millions | 
| =========== | =========== | =========================== | ============================ | 
| 1487802327  | FY 10       | 643.35                      | -2.8                         | 
| 1487802384  | FY 11       | 647.12                      | 0.6                          | 
| 1487802415  | FY 12       | 641.65                      | -0.8                         | 
| 1487802465  | FY 13       | 645.89                      | 0.7                          | 
| 1487802489  | FY 14       | 662.4                       | 2.6                          | 
| 1487802575  | FY 16       | 643.63                      | 0.6                          | 
| 1487802641  | FY 15       | 639.78                      | -3.4                         | 
| 1487802655  | FY 09       | 661.92                      | -5.7                         | 
```