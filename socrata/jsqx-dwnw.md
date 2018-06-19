# Tobacco Tax Collections and Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tobacco-tax-collections-and-permits) |
| Metadata | [Link](https://data.hawaii.gov/api/views/jsqx-dwnw) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/jsqx-dwnw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/jsqx-dwnw/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | jsqx-dwnw |
| Name | Tobacco Tax Collections and Permits |
| Created | 2015-01-29T23:08:08Z |
| Publication Date | 2016-01-20T18:55:33Z |

## Description

This series shows collections of the cigarette and tobacco taxes, broken down by type of tobacco product. The series also shows how the tax on cigarettes is allocated among the various special funds.

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
series e:jsqx-dwnw d:2000-01-31T00:00:00.000Z t:fourth_district=0 t:third_district=163 t:month=01 t:source_destination=Cigarettes t:type=REVENUE t:all_districts=3590180.00 t:first_district=3590018.00 t:second_district=0 m:cumulative_totals=23767622

series e:jsqx-dwnw d:2000-01-31T00:00:00.000Z t:fourth_district=0 t:third_district=1282.00 t:month=01 t:source_destination="All Other Tobacco Products" t:type=REVENUE t:all_districts=150891.00 t:first_district=145367.00 t:second_district=4242.00 m:cumulative_totals=1180240

series e:jsqx-dwnw d:2000-01-31T00:00:00.000Z t:fourth_district=0 t:third_district=0 t:month=01 t:source_destination="Penalties and Interest" t:type=REVENUE t:all_districts=70039.00 t:first_district=70039.00 t:second_district=0 m:cumulative_totals=167511
```

## Meta Commands

```ls
metric m:cumulative_totals p:double l:"CUMULATIVE TOTALS" t:dataTypeName=money

entity e:jsqx-dwnw l:"Tobacco Tax Collections and Permits" t:url=https://data.hawaii.gov/api/views/jsqx-dwnw

property e:jsqx-dwnw t:meta.view v:id=jsqx-dwnw v:averageRating=0 v:name="Tobacco Tax Collections and Permits"

property e:jsqx-dwnw t:meta.view.owner v:id=vx5q-wjs8 v:screenName=ninomid v:displayName=ninomid

property e:jsqx-dwnw t:meta.view.tableauthor v:id=vx5q-wjs8 v:screenName=ninomid v:roleName=publisher v:displayName=ninomid
```

## Top Records

```ls
| source_destination         | first_district | second_district | third_district | fourth_district | all_districts | cumulative_totals | type    | date                | month | year | 
| ========================== | ============== | =============== | ============== | =============== | ============= | ================= | ======= | =================== | ===== | ==== | 
| Cigarettes                 | 3590018.00     | 0               | 163            | 0               | 3590180.00    | 23767622.00       | REVENUE | 2000-01-31T00:00:00 | 01    | 2000 | 
| All Other Tobacco Products | 145367.00      | 4242.00         | 1282.00        | 0               | 150891.00     | 1180240.00        | REVENUE | 2000-01-31T00:00:00 | 01    | 2000 | 
| Penalties and Interest     | 70039.00       | 0               | 0              | 0               | 70039.00      | 167511.00         | REVENUE | 2000-01-31T00:00:00 | 01    | 2000 | 
| License Fees               | 5              | 0               | 3              | 0               | 8             | 165               | REVENUE | 2000-01-31T00:00:00 | 01    | 2000 | 
| Cigarettes                 | 2672231.00     | 0               | 48             | 0               | 2672278.00    | 26439900.00       | REVENUE | 2000-02-29T00:00:00 | 02    | 2000 | 
| All Other Tobacco Products | 110436.00      | 4336.00         | 1040.00        | 0               | 115812.00     | 1296053.00        | REVENUE | 2000-02-29T00:00:00 | 02    | 2000 | 
| Penalties and Interest     | 71141.00       | 0               | 0              | 0               | 71141.00      | 238652.00         | REVENUE | 2000-02-29T00:00:00 | 02    | 2000 | 
| License Fees               | 8              | 0               | 0              | 0               | 8             | 173               | REVENUE | 2000-02-29T00:00:00 | 02    | 2000 | 
| Cigarettes                 | 3941266.00     | 0               | 188            | 0               | 3941453.00    | 30381354.00       | REVENUE | 2000-03-31T00:00:00 | 03    | 2000 | 
| All Other Tobacco Products | 170352.00      | 4090.00         | 1079.00        | 0               | 175522.00     | 1471575.00        | REVENUE | 2000-03-31T00:00:00 | 03    | 2000 | 
```