# General Excise and Use Tax Collections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/general-excise-and-use-tax-collections) |
| Metadata | [Link](https://data.hawaii.gov/api/views/8u5c-ci7r) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/8u5c-ci7r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/8u5c-ci7r/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 8u5c-ci7r |
| Name | General Excise and Use Tax Collections |
| Created | 2015-01-29T22:55:34Z |
| Publication Date | 2016-01-20T18:58:45Z |

## Description

This series shows taxable income and taxes collected for the general excise tax, broken down by activity of the taxpayer (e.g., retailing, services, contracting, etc.)

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
series e:8u5c-ci7r d:1999-01-31T00:00:00.000Z t:month=01 t:source_destination=Retailing t:type=REVENUE t:all_districts=44365390 m:cumulative_totals=356737866

series e:8u5c-ci7r d:1999-01-31T00:00:00.000Z t:month=01 t:source_destination=Services t:type=REVENUE t:all_districts=17468089 m:cumulative_totals=127385509

series e:8u5c-ci7r d:1999-01-31T00:00:00.000Z t:month=01 t:source_destination=Contracting t:type=REVENUE t:all_districts=8993687 m:cumulative_totals=71098262
```

## Meta Commands

```ls
metric m:cumulative_totals p:long l:"CUMULATIVE TOTALS" t:dataTypeName=money

entity e:8u5c-ci7r l:"General Excise and Use Tax Collections" t:url=https://data.hawaii.gov/api/views/8u5c-ci7r

property e:8u5c-ci7r t:meta.view v:id=8u5c-ci7r v:averageRating=0 v:name="General Excise and Use Tax Collections"

property e:8u5c-ci7r t:meta.view.owner v:id=vx5q-wjs8 v:screenName=ninomid v:displayName=ninomid

property e:8u5c-ci7r t:meta.view.tableauthor v:id=vx5q-wjs8 v:screenName=ninomid v:roleName=publisher v:displayName=ninomid
```

## Top Records

```ls
| source_destination           | all_districts | cumulative_totals | type    | date                | month | year | 
| ============================ | ============= | ================= | ======= | =================== | ===== | ==== | 
| Retailing                    | 44365390      | 356737866         | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
| Services                     | 17468089      | 127385509         | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
| Contracting                  | 8993687       | 71098262          | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
| Theater, Amuse., Radio, etc. | 444754        | 5242980           | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
| Interest                     | 766753        | 5240840           | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
| Commissions                  | 2255130       | 15223247          | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
| Hotel Rentals                | 5345252       | 45805757          | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
| All Other Rentals            | 13529722      | 87453398          | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
| Use (4%)                     | 1992366       | 11186110          | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
| All Others (4%)              | 3377345       | 27450712          | REVENUE | 1999-01-31T00:00:00 | 01    | 1999 | 
```