# HART Proposed Budget 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hart-proposed-budget-2012-e2685) |
| Metadata | [Link](https://data.honolulu.gov/api/views/ifzd-2k3p) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/ifzd-2k3p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/ifzd-2k3p/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | ifzd-2k3p |
| Name | HART Proposed Budget 2012 |
| Created | 2012-06-04T21:20:33Z |
| Publication Date | 2012-06-23T02:55:38Z |

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | dept                     | Dept                     | text      | text        |
| Yes      | numeric metric | division                 | Division                 | number    | number      |
| Yes      | numeric metric | fund                     | Fund                     | number    | number      |
| Yes      | series tag     | object_code              | Object Code              | text      | number      |
| Yes      | numeric metric | fy_2009_actual           | FY 2009 Actual           | number    | number      |
| Yes      | numeric metric | fy_2010_actual           | FY 2010 Actual           | number    | number      |
| Yes      | numeric metric | fy_2011_budget           | FY 2011 Budget           | number    | number      |
| Yes      | numeric metric | fy_2012_current_services | FY 2012 Current Services | number    | number      |
| Yes      | numeric metric | fy_2012_budget_issues    | FY 2012 Budget Issues    | number    | number      |
| Yes      | numeric metric | fy_2012_proposed_budget  | FY 2012 Proposed Budget  | number    | number      |
| Yes      | series tag     | department_name          | Department Name          | text      | text        |
| Yes      | series tag     | division_name            | Division Name            | text      | text        |
| Yes      | series tag     | fund_name                | Fund Name                | text      | text        |
| Yes      | series tag     | object_name              | Object Name              | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ifzd-2k3p d:2012-01-01T00:00:00.000Z t:fund_name="Transit Fund" t:object_name="Regular Pay" t:dept=HRT t:department_name="Honolulu Authority for Rapid Transportation" t:division_name="Rapid Transit" t:object_code=1101 m:fy_2011_budget=0 m:fy_2012_budget_issues=1667238 m:division=1690 m:fy_2009_actual=0 m:fund=290 m:fy_2010_actual=0 m:fy_2012_current_services=7816836 m:fy_2012_proposed_budget=9484074

series e:ifzd-2k3p d:2012-01-01T00:00:00.000Z t:fund_name="Transit Fund" t:object_name="Non-Holiday Overtime Pay" t:dept=HRT t:department_name="Honolulu Authority for Rapid Transportation" t:division_name="Rapid Transit" t:object_code=1102 m:fy_2011_budget=0 m:fy_2012_budget_issues=0 m:division=1690 m:fy_2009_actual=0 m:fund=290 m:fy_2010_actual=0 m:fy_2012_current_services=46000 m:fy_2012_proposed_budget=46000

series e:ifzd-2k3p d:2012-01-01T00:00:00.000Z t:fund_name="Transit Fund" t:object_name="Night Shift Pay" t:dept=HRT t:department_name="Honolulu Authority for Rapid Transportation" t:division_name="Rapid Transit" t:object_code=1108 m:fy_2011_budget=0 m:fy_2012_budget_issues=0 m:division=1690 m:fy_2009_actual=0 m:fund=290 m:fy_2010_actual=0 m:fy_2012_current_services=1000 m:fy_2012_proposed_budget=1000
```

## Meta Commands

```ls
metric m:division p:integer l:Division t:dataTypeName=number

metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:fy_2009_actual p:integer l:"FY 2009 Actual" t:dataTypeName=number

metric m:fy_2010_actual p:integer l:"FY 2010 Actual" t:dataTypeName=number

metric m:fy_2011_budget p:integer l:"FY 2011 Budget" t:dataTypeName=number

metric m:fy_2012_current_services p:integer l:"FY 2012 Current Services" t:dataTypeName=number

metric m:fy_2012_budget_issues p:integer l:"FY 2012 Budget Issues" t:dataTypeName=number

metric m:fy_2012_proposed_budget p:integer l:"FY 2012 Proposed Budget" t:dataTypeName=number

entity e:ifzd-2k3p l:"HART Proposed Budget 2012" t:url=https://data.honolulu.gov/api/views/ifzd-2k3p

property e:ifzd-2k3p t:meta.view v:id=ifzd-2k3p v:averageRating=0 v:name="HART Proposed Budget 2012"

property e:ifzd-2k3p t:meta.view.owner v:id=gcjf-354x v:screenName="Mick Thompson" v:displayName="Mick Thompson"

property e:ifzd-2k3p t:meta.view.tableauthor v:id=gcjf-354x v:screenName="Mick Thompson" v:displayName="Mick Thompson"
```

## Top Records

```ls
| dept | division | fund | object_code | fy_2009_actual | fy_2010_actual | fy_2011_budget | fy_2012_current_services | fy_2012_budget_issues | fy_2012_proposed_budget | department_name                             | division_name | fund_name    | object_name              | 
| ==== | ======== | ==== | =========== | ============== | ============== | ============== | ======================== | ===================== | ======================= | =========================================== | ============= | ============ | ======================== | 
| HRT  | 1690     | 290  | 1101        | 0              | 0              | 0              | 7816836                  | 1667238               | 9484074                 | Honolulu Authority for Rapid Transportation | Rapid Transit | Transit Fund | Regular Pay              | 
| HRT  | 1690     | 290  | 1102        | 0              | 0              | 0              | 46000                    | 0                     | 46000                   | Honolulu Authority for Rapid Transportation | Rapid Transit | Transit Fund | Non-Holiday Overtime Pay | 
| HRT  | 1690     | 290  | 1108        | 0              | 0              | 0              | 1000                     | 0                     | 1000                    | Honolulu Authority for Rapid Transportation | Rapid Transit | Transit Fund | Night Shift Pay          | 
| HRT  | 1690     | 290  | 1109        | 0              | 0              | 0              | 1000                     | 0                     | 1000                    | Honolulu Authority for Rapid Transportation | Rapid Transit | Transit Fund | Temporary Assignment Pay | 
| HRT  | 1690     | 290  | 1113        | 0              | 0              | 0              | 3961601                  | 0                     | 3961601                 | Honolulu Authority for Rapid Transportation | Rapid Transit | Transit Fund | Fringe Benefits (HART)   | 
| HRT  | 1690     | 290  | 1501        | 0              | 0              | 0              | 400                      | 0                     | 400                     | Honolulu Authority for Rapid Transportation | Rapid Transit | Transit Fund | Service Or Merit Awards  | 
| HRT  | 1690     | 290  | 2051        | 0              | 0              | 0              | 69000                    | 0                     | 69000                   | Honolulu Authority for Rapid Transportation | Rapid Transit | Transit Fund | Office Supplies          | 
| HRT  | 1690     | 290  | 2331        | 0              | 0              | 0              | 9000                     | 0                     | 9000                    | Honolulu Authority for Rapid Transportation | Rapid Transit | Transit Fund | Computer Supplies        | 
| HRT  | 1690     | 290  | 2352        | 0              | 0              | 0              | 100                      | 0                     | 100                     | Honolulu Authority for Rapid Transportation | Rapid Transit | Transit Fund | Meals-Breakfast          | 
| HRT  | 1690     | 290  | 2354        | 0              | 0              | 0              | 300                      | 0                     | 300                     | Honolulu Authority for Rapid Transportation | Rapid Transit | Transit Fund | Meals-Dinner             | 
```