# State Tax Collections and Distribution

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-tax-collections-and-distribution) |
| Metadata | [Link](https://data.hawaii.gov/api/views/evqj-e9i8) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/evqj-e9i8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/evqj-e9i8/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | evqj-e9i8 |
| Name | State Tax Collections and Distribution |
| Created | 2015-01-30T00:09:35Z |
| Publication Date | 2016-01-20T18:53:42Z |

## Description

This series shows collections of taxes administered by the State and the allocations of the taxes among the State's general fund and the various special funds.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | source_destination | SOURCE/DESTINATION | text          | text          |
| Yes      | series tag     | all_districts      | ALL DISTRICTS      | text          | money         |
| Yes      | numeric metric | cumulative_totals  | CUMULATIVE TOTALS  | money         | money         |
| Yes      | series tag     | type               | TYPE               | text          | text          |
| Yes      | time           | date               | DATE               | calendar_date | calendar_date |
| Yes      | series tag     | month              | MONTH              | text          | text          |
| No       |                | year               | YEAR               | number        | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:evqj-e9i8 d:1999-01-31T00:00:00.000Z t:month=01 t:source_destination="Banks/Financial Corp." t:type=REVENUE t:all_districts=669349.00 m:cumulative_totals=7186314

series e:evqj-e9i8 d:1999-01-31T00:00:00.000Z t:month=01 t:source_destination=Conveyance t:type=REVENUE t:all_districts=114812.00 m:cumulative_totals=4192333

series e:evqj-e9i8 d:1999-01-31T00:00:00.000Z t:month=01 t:source_destination="Employment Sec. Contri." t:type=REVENUE t:all_districts=8875851.00 m:cumulative_totals=82691008
```

## Meta Commands

```ls
metric m:cumulative_totals p:double l:"CUMULATIVE TOTALS" t:dataTypeName=money

entity e:evqj-e9i8 l:"State Tax Collections and Distribution" t:url=https://data.hawaii.gov/api/views/evqj-e9i8

property e:evqj-e9i8 t:meta.view v:id=evqj-e9i8 v:averageRating=0 v:name="State Tax Collections and Distribution"

property e:evqj-e9i8 t:meta.view.owner v:id=vx5q-wjs8 v:screenName=ninomid v:displayName=ninomid

property e:evqj-e9i8 t:meta.view.tableauthor v:id=vx5q-wjs8 v:screenName=ninomid v:roleName=publisher v:displayName=ninomid
```

## Top Records

```ls
| source_destination                | all_districts | cumulative_totals | type    | date                | month | year | 
| ================================= | ============= | ================= | ======= | =================== | ===== | ==== | 
| Banks/Financial Corp.             | 669349.00     | 7186314.00        | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
| Conveyance                        | 114812.00     | 4192333.00        | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
| Employment Sec. Contri.           | 8875851.00    | 82691008.00       | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
| Fuel                              | 11490999.00   | 79943929.00       | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
| GE License/Fees                   | 44447.00      | 300765.00         | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
| General Excise & Use              | 108049293.00  | 820730277.00      | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
| Income-Corp.: Decl. of Est. Taxes | 8007587.00    | 40315950.00       | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
| Income-Corp.: Payment W/Returns   | 907044.00     | 5319897.00        | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
| Income-Corp.: Refunds             | -2582091.00   | -30192150.00      | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
| Income-Ind.: Decl. of Est. Taxes  | 35824043.00   | 105424098.00      | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
```