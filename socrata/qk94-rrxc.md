# Film Tax Credit

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/film-tax-credit) |
| Metadata | [Link](https://data.hawaii.gov/api/views/qk94-rrxc) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/qk94-rrxc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/qk94-rrxc/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | qk94-rrxc |
| Name | Film Tax Credit |
| Created | 2015-02-25T21:01:05Z |
| Publication Date | 2016-02-03T20:56:21Z |

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================= | ============================== | ============= | ============= |
| Yes      | time           | effective_date                | Effective Date                 | calendar_date | calendar_date |
| Yes      | series tag     | production                    | Production                     | text          | text          |
| No       |                | prod_year                     | Prod. Year                     | number        | text          |
| Yes      | series tag     | type                          | Type                           | text          | text          |
| Yes      | numeric metric | total_qualified_expend        | Total Qualified Expend.        | number        | number        |
| Yes      | numeric metric | total_estimated_rebate        | Total Estimated Rebate         | number        | number        |
| Yes      | numeric metric | total_estimated_tax_generated | Total Estimated Tax Generated* | number        | number        |
| Yes      | numeric metric | sales_geerated_into_economy   | Sales Geerated into Economy    | number        | number        |
| Yes      | numeric metric | household_income_generated    | Household Income Generated     | number        | number        |
| Yes      | numeric metric | oahu_expend                   | Oahu Expend.                   | number        | number        |
| Yes      | numeric metric | neighbor_isle_total           | Neighbor Isle Total            | number        | number        |
| Yes      | numeric metric | big_island_expend             | Big Island Expend.             | number        | number        |
| Yes      | numeric metric | kauai_expend                  | Kauai Expend.                  | number        | number        |
| Yes      | numeric metric | maui_epend                    | Maui Epend.                    | number        | number        |
| Yes      | series tag     | molokai_expend                | Molokai Expend.                | text          | text          |
| Yes      | series tag     | lanai_expend                  | Lanai Expend.                  | text          | text          |
| Yes      | numeric metric | local_hawaii_hires            | Local Hawaii Hires             | number        | number        |
| Yes      | numeric metric | out_of_state_hires            | Out of State Hires             | number        | number        |
| Yes      | numeric metric | jobs_generated                | Jobs Generated                 | number        | number        |
```

## Time Field

```ls
Value = effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = prod_year
```

## Data Commands

```ls
series e:qk94-rrxc d:2013-12-31T00:00:00.000Z t:type=Commercial t:production="Prod 1" m:total_estimated_tax_generated=48000 m:total_estimated_rebate=80000 m:total_qualified_expend=400000 m:local_hawaii_hires=55 m:household_income_generated=168000 m:sales_geerated_into_economy=700000 m:out_of_state_hires=10 m:oahu_expend=400000

series e:qk94-rrxc d:2013-12-31T00:00:00.000Z t:type=Commercial t:production="Prod 2" m:total_estimated_tax_generated=54000 m:total_estimated_rebate=90000 m:total_qualified_expend=450000 m:local_hawaii_hires=44 m:household_income_generated=189000 m:sales_geerated_into_economy=787500 m:out_of_state_hires=1 m:oahu_expend=450000

series e:qk94-rrxc d:2013-12-31T00:00:00.000Z t:type=Commercial t:production="Prod 3" m:total_estimated_tax_generated=27000 m:total_estimated_rebate=45000 m:total_qualified_expend=225000 m:local_hawaii_hires=18 m:household_income_generated=94500 m:sales_geerated_into_economy=393750 m:out_of_state_hires=18 m:oahu_expend=225000
```

## Meta Commands

```ls
metric m:total_qualified_expend p:integer l:"Total Qualified Expend." t:dataTypeName=number

metric m:total_estimated_rebate p:integer l:"Total Estimated Rebate" t:dataTypeName=number

metric m:total_estimated_tax_generated p:integer l:"Total Estimated Tax Generated*" t:dataTypeName=number

metric m:sales_geerated_into_economy p:integer l:"Sales Geerated into Economy" t:dataTypeName=number

metric m:household_income_generated p:integer l:"Household Income Generated" t:dataTypeName=number

metric m:oahu_expend p:integer l:"Oahu Expend." t:dataTypeName=number

metric m:neighbor_isle_total p:integer l:"Neighbor Isle Total" t:dataTypeName=number

metric m:big_island_expend p:integer l:"Big Island Expend." t:dataTypeName=number

metric m:kauai_expend p:integer l:"Kauai Expend." t:dataTypeName=number

metric m:maui_epend p:integer l:"Maui Epend." t:dataTypeName=number

metric m:local_hawaii_hires p:integer l:"Local Hawaii Hires" t:dataTypeName=number

metric m:out_of_state_hires p:integer l:"Out of State Hires" t:dataTypeName=number

metric m:jobs_generated p:integer l:"Jobs Generated" t:dataTypeName=number

entity e:qk94-rrxc l:"Film Tax Credit" t:url=https://data.hawaii.gov/api/views/qk94-rrxc

property e:qk94-rrxc t:meta.view v:id=qk94-rrxc v:averageRating=0 v:name="Film Tax Credit"

property e:qk94-rrxc t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:qk94-rrxc t:meta.view.tableauthor v:id=wktp-67q4 v:screenName=karen v:roleName=administrator v:displayName=karen
```

## Top Records

```ls
| effective_date      | production | prod_year | type              | total_qualified_expend | total_estimated_rebate | total_estimated_tax_generated | sales_geerated_into_economy | household_income_generated | oahu_expend | neighbor_isle_total | big_island_expend | kauai_expend | maui_epend | molokai_expend | lanai_expend | local_hawaii_hires | out_of_state_hires | jobs_generated | 
| =================== | ========== | ========= | ================= | ====================== | ====================== | ============================= | =========================== | ========================== | =========== | =================== | ================= | ============ | ========== | ============== | ============ | ================== | ================== | ============== | 
| 2013-12-31T00:00:00 | Prod 1     | 2013      | Commercial        | 400000                 | 80000                  | 48000                         | 700000                      | 168000                     | 400000      |                     |                   |              |            |                |              | 55                 | 10                 |                | 
| 2013-12-31T00:00:00 | Prod 2     | 2013      | Commercial        | 450000                 | 90000                  | 54000                         | 787500                      | 189000                     | 450000      |                     |                   |              |            |                |              | 44                 | 1                  |                | 
| 2013-12-31T00:00:00 | Prod 3     | 2013      | Commercial        | 225000                 | 45000                  | 27000                         | 393750                      | 94500                      | 225000      |                     |                   |              |            |                |              | 18                 | 18                 |                | 
| 2013-12-31T00:00:00 | Prod 4     | 2013      | Television        | 1190034                | 297508                 | 142804                        | 2082560                     | 499814                     |             | 1190034             | 1190034           |              |            |                |              | 17                 | 11                 |                | 
| 2013-12-31T00:00:00 | Prod 5     | 2013      | Commercial 290000 | 58000                  | 34800                  | 507500                        | 121800                      | 290000                     |             |                     |                   |              |            |                |              | 30                 | 0                  |                | 
| 2013-12-31T00:00:00 | Prod 6     | 2013      | Commercial        | 250000                 | 50000                  | 30000                         | 437500                      | 105000                     | 250000      |                     |                   |              |            |                |              | 30                 | 29                 |                | 
| 2013-12-31T00:00:00 | Prod 7     | 2013      | Television        | 5719597                | 1143919                | 686352                        | 10009295                    | 2402231                    | 5719597     |                     |                   |              |            |                |              | 776                | 72                 |                | 
| 2013-12-31T00:00:00 | Prod 8     | 2013      | Feature           | 475000                 | 95000                  | 57000                         | 831250                      | 199500                     | 475000      |                     |                   |              |            |                |              | 73                 | 11                 |                | 
| 2013-12-31T00:00:00 | Prod 9     | 2013      | Commercial        | 275000                 | 55000                  | 33000                         | 481250                      | 115500                     | 275000      |                     |                   |              |            |                |              | 55                 | 20                 |                | 
| 2013-12-31T00:00:00 | Prod 10    | 2013      | Commercial        | 300000                 | 60000                  | 36000                         | 525000                      | 126000                     | 300000      |                     |                   |              |            |                |              | 45                 | 20                 |                | 
```