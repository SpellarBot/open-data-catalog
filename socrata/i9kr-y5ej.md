# Job Count by Industry - State of Hawaii

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/job-count-by-industry-state-of-hawaii-fa974) |
| Metadata | [Link](https://data.hawaii.gov/api/views/i9kr-y5ej) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/i9kr-y5ej/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/i9kr-y5ej/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | i9kr-y5ej |
| Name | Job Count by Industry - State of Hawaii |
| Category | Employment |
| Created | 2014-05-28T21:45:06Z |
| Publication Date | 2014-06-19T22:55:19Z |

## Description

This dataset shows the job counts by industry for the State of Hawaii and will be updated monthly with new data.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag     | industry             | Industry             | text          | text          |
| Yes      | series tag     | industry_type        | Industry Type        | text          | text          |
| Yes      | series tag     | industry_sub_type    | Industry Sub-Type    | text          | text          |
| Yes      | series tag     | category             | Category             | text          | text          |
| Yes      | series tag     | sub_category         | Sub-Category         | text          | text          |
| Yes      | series tag     | sub_sub_category     | Sub-Sub-Category     | text          | text          |
| Yes      | series tag     | sub_sub_sub_category | Sub-Sub-Sub-Category | text          | text          |
| Yes      | series tag     | original_title       | Original Title       | text          | text          |
| Yes      | numeric metric | jan                  | Jan                  | number        | number        |
| Yes      | numeric metric | feb                  | Feb                  | number        | number        |
| Yes      | numeric metric | mar                  | Mar                  | number        | number        |
| Yes      | numeric metric | apr                  | Apr                  | number        | number        |
| Yes      | numeric metric | may                  | May                  | number        | number        |
| Yes      | numeric metric | jun                  | Jun                  | number        | number        |
| Yes      | numeric metric | jul                  | Jul                  | number        | number        |
| Yes      | numeric metric | aug                  | Aug                  | number        | number        |
| Yes      | numeric metric | sep                  | Sep                  | number        | number        |
| Yes      | numeric metric | oct                  | Oct                  | number        | number        |
| Yes      | numeric metric | nov                  | Nov                  | number        | number        |
| Yes      | numeric metric | dec                  | Dec                  | number        | number        |
| Yes      | numeric metric | annual               | Annual               | number        | number        |
| No       |                | year                 | Year                 | number        | number        |
| Yes      | time           | year_date            | Year (Date)          | calendar_date | calendar_date |
```

## Time Field

```ls
Value = year_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:i9kr-y5ej d:2014-12-31T00:00:00.000Z t:category=N/A t:sub_sub_sub_category=N/A t:original_title="TOTAL NONAGRICULTURAL WAGE & SALARY JOBS" t:industry_type=All t:sub_sub_category=N/A t:industry_sub_type=N/A t:industry=Nonagricultural t:sub_category=N/A m:apr=623500 m:feb=620200 m:mar=623100 m:jan=616200

series e:i9kr-y5ej d:2014-12-31T00:00:00.000Z t:category=N/A t:sub_sub_sub_category=N/A t:original_title="Total Private" t:industry_type=Private t:sub_sub_category=N/A t:industry_sub_type=N/A t:industry=Nonagricultural t:sub_category=N/A m:apr=495400 m:feb=491800 m:mar=494200 m:jan=491200

series e:i9kr-y5ej d:2014-12-31T00:00:00.000Z t:category=N/A t:sub_sub_sub_category=N/A t:original_title=Goods-Producing t:industry_type=Private t:sub_sub_category=N/A t:industry_sub_type=Goods-Producing t:industry=Nonagricultural t:sub_category=N/A m:apr=44200 m:feb=43900 m:mar=43700 m:jan=43500
```

## Meta Commands

```ls
metric m:jan p:integer l:Jan t:dataTypeName=number

metric m:feb p:integer l:Feb t:dataTypeName=number

metric m:mar p:integer l:Mar t:dataTypeName=number

metric m:apr p:integer l:Apr t:dataTypeName=number

metric m:may p:long l:May t:dataTypeName=number

metric m:jun p:long l:Jun t:dataTypeName=number

metric m:jul p:long l:Jul t:dataTypeName=number

metric m:aug p:long l:Aug t:dataTypeName=number

metric m:sep p:long l:Sep t:dataTypeName=number

metric m:oct p:long l:Oct t:dataTypeName=number

metric m:nov p:long l:Nov t:dataTypeName=number

metric m:dec p:long l:Dec t:dataTypeName=number

metric m:annual p:long l:Annual t:dataTypeName=number

entity e:i9kr-y5ej l:"Job Count by Industry - State of Hawaii" t:url=https://data.hawaii.gov/api/views/i9kr-y5ej

property e:i9kr-y5ej t:meta.view v:id=i9kr-y5ej v:category=Employment v:averageRating=0 v:name="Job Count by Industry - State of Hawaii"

property e:i9kr-y5ej t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:i9kr-y5ej t:meta.view.tableauthor v:id=wktp-67q4 v:screenName=karen v:roleName=administrator v:displayName=karen
```

## Top Records

```ls
| industry        | industry_type | industry_sub_type | category                               | sub_category              | sub_sub_category | sub_sub_sub_category | original_title                           | jan    | feb    | mar    | apr    | may | jun | jul | aug | sep | oct | nov | dec | annual | year | year_date           | 
| =============== | ============= | ================= | ====================================== | ========================= | ================ | ==================== | ======================================== | ====== | ====== | ====== | ====== | === | === | === | === | === | === | === | === | ====== | ==== | =================== | 
| Nonagricultural | All           | N/A               | N/A                                    | N/A                       | N/A              | N/A                  | TOTAL NONAGRICULTURAL WAGE & SALARY JOBS | 616200 | 620200 | 623100 | 623500 |     |     |     |     |     |     |     |     |        | 2014 | 2014-12-31T00:00:00 | 
| Nonagricultural | Private       | N/A               | N/A                                    | N/A                       | N/A              | N/A                  | Total Private                            | 491200 | 491800 | 494200 | 495400 |     |     |     |     |     |     |     |     |        | 2014 | 2014-12-31T00:00:00 | 
| Nonagricultural | Private       | Goods-Producing   | N/A                                    | N/A                       | N/A              | N/A                  | Goods-Producing                          | 43500  | 43900  | 43700  | 44200  |     |     |     |     |     |     |     |     |        | 2014 | 2014-12-31T00:00:00 | 
| Nonagricultural | Private       | Goods-Producing   | Nat. Resources & Mining & Construction | N/A                       | N/A              | N/A                  | Nat. Resources & Mining & Construction   | 30100  | 30500  | 30300  | 30600  |     |     |     |     |     |     |     |     |        | 2014 | 2014-12-31T00:00:00 | 
| Nonagricultural | Private       | Goods-Producing   | Nat. Resources & Mining & Construction | Construction of Buildings | N/A              | N/A                  | Construction of Buildings                | 9300   | 9300   | 9400   | 9400   |     |     |     |     |     |     |     |     |        | 2014 | 2014-12-31T00:00:00 | 
| Nonagricultural | Private       | Goods-Producing   | Nat. Resources & Mining & Construction | Special Trade Contractors | N/A              | N/A                  | Special Trade Contractors                | 17100  | 17200  | 17200  | 17300  |     |     |     |     |     |     |     |     |        | 2014 | 2014-12-31T00:00:00 | 
| Nonagricultural | Private       | Goods-Producing   | Manufacturing                          | N/A                       | N/A              | N/A                  | Manufacturing                            | 13400  | 13400  | 13400  | 13600  |     |     |     |     |     |     |     |     |        | 2014 | 2014-12-31T00:00:00 | 
| Nonagricultural | Private       | Goods-Producing   | Manufacturing                          | Durable Goods             | N/A              | N/A                  | Durable Goods                            | 3600   | 3500   | 3500   | 3600   |     |     |     |     |     |     |     |     |        | 2014 | 2014-12-31T00:00:00 | 
| Nonagricultural | Private       | Goods-Producing   | Manufacturing                          | Non-Durable Goods         | N/A              | N/A                  | Non-Durable Goods                        | 9800   | 9900   | 9900   | 10000  |     |     |     |     |     |     |     |     |        | 2014 | 2014-12-31T00:00:00 | 
| Nonagricultural | Private       | Service-Providing | N/A                                    | N/A                       | N/A              | N/A                  | Service-Providing                        | 572700 | 576300 | 579400 | 579300 |     |     |     |     |     |     |     |     |        | 2014 | 2014-12-31T00:00:00 | 
```