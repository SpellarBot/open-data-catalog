# Liquor Tax Collections and Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/liquor-tax-collections-and-permits) |
| Metadata | [Link](https://data.hawaii.gov/api/views/wajt-vrqf) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/wajt-vrqf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/wajt-vrqf/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | wajt-vrqf |
| Name | Liquor Tax Collections and Permits |
| Created | 2015-01-29T23:04:24Z |
| Publication Date | 2016-01-20T18:57:02Z |

## Description

This series shows collections of the liquor tax and permit fees, and penalties and interest on the tax.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | source_destination | SOURCE/DESTINATION | text          | text          |
| Yes      | series tag     | first_district     | FIRST DISTRICT     | text          | money         |
| Yes      | series tag     | second_district    | SECOND DISTRICT    | text          | money         |
| Yes      | series tag     | third_district     | THIRD DISTRICT     | text          | money         |
| Yes      | series tag     | fourth_district    | FOURTH DISTRICT    | text          | money         |
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
series e:wajt-vrqf d:2000-01-31T00:00:00.000Z t:fourth_district=232056.00 t:third_district=482503.00 t:month=01 t:source_destination=Wholesale t:type=REVENUE t:all_districts=4333127.00 t:first_district=3143815.00 t:second_district=474754.00 m:cumulative_totals=21883353

series e:wajt-vrqf d:2000-01-31T00:00:00.000Z t:fourth_district=0 t:third_district=0 t:month=01 t:source_destination="Penalties and Interest" t:type=REVENUE t:all_districts=9 t:first_district=9 t:second_district=0 m:cumulative_totals=17

series e:wajt-vrqf d:2000-01-31T00:00:00.000Z t:fourth_district=0 t:third_district=0 t:month=01 t:source_destination="Permit Fees" t:type=REVENUE t:all_districts=0 t:first_district=0 t:second_district=0 m:cumulative_totals=68
```

## Meta Commands

```ls
metric m:cumulative_totals p:double l:"CUMULATIVE TOTALS" t:dataTypeName=money

entity e:wajt-vrqf l:"Liquor Tax Collections and Permits" t:url=https://data.hawaii.gov/api/views/wajt-vrqf

property e:wajt-vrqf t:meta.view v:id=wajt-vrqf v:averageRating=0 v:name="Liquor Tax Collections and Permits"

property e:wajt-vrqf t:meta.view.owner v:id=vx5q-wjs8 v:screenName=ninomid v:displayName=ninomid

property e:wajt-vrqf t:meta.view.tableauthor v:id=vx5q-wjs8 v:screenName=ninomid v:roleName=publisher v:displayName=ninomid
```

## Top Records

```ls
| source_destination     | first_district | second_district | third_district | fourth_district | all_districts | cumulative_totals | type    | date                | month | year | 
| ====================== | ============== | =============== | ============== | =============== | ============= | ================= | ======= | =================== | ===== | ==== | 
| Wholesale              | 3143815.00     | 474754.00       | 482503.00      | 232056.00       | 4333127.00    | 21883353.00       | REVENUE | 2000-01-31T00:00:00 | 01    | 2000 | 
| Penalties and Interest | 9              | 0               | 0              | 0               | 9             | 17                | REVENUE | 2000-01-31T00:00:00 | 01    | 2000 | 
| Permit Fees            | 0              | 0               | 0              | 0               | 0             | 68                | REVENUE | 2000-01-31T00:00:00 | 01    | 2000 | 
| Wholesale              | 1827391.00     | 529872.00       | 694260.00      | 310853.00       | 3362375.00    | 25245729.00       | REVENUE | 2000-02-29T00:00:00 | 02    | 2000 | 
| Penalties and Interest | 0              | 0               | 0              | 0               | 0             | 17                | REVENUE | 2000-02-29T00:00:00 | 02    | 2000 | 
| Permit Fees            | 5              | 0               | 0              | 0               | 5             | 73                | REVENUE | 2000-02-29T00:00:00 | 02    | 2000 | 
| Wholesale              | 2602025.00     | 764270.00       | 416631.00      | 193185.00       | 3976111.00    | 29221840.00       | REVENUE | 2000-03-31T00:00:00 | 03    | 2000 | 
| Penalties and Interest | 0              | 0               | 0              | 0               | 0             | 17                | REVENUE | 2000-03-31T00:00:00 | 03    | 2000 | 
| Permit Fees            | 3              | 0               | 0              | 0               | 3             | 75                | REVENUE | 2000-03-31T00:00:00 | 03    | 2000 | 
| Wholesale              | 2175114.00     | 245781.00       | 415480.00      | 192076.00       | 3028451.00    | 32250291          | REVENUE | 2000-04-30T00:00:00 | 04    | 2000 | 
```