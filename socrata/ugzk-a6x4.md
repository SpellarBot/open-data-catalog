# Revenue Budget & Financial Plan -- Exec\Adpt\Prel

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/revenue-budget-financial-plan) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ugzk-a6x4) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ugzk-a6x4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ugzk-a6x4/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ugzk-a6x4 |
| Name | Revenue Budget & Financial Plan -- Exec\Adpt\Prel |
| Attribution | Mayor?s Office of Management & Budget (OMB) |
| Category | City Government |
| Created | 2016-05-03T19:07:36Z |
| Publication Date | 2017-02-08T17:24:08Z |

## Description

This dataset contains agency revenue data for Adopted, Modified and five years of Financial Plan by   Revenue Class, Revenue Category and Revenue Source (Revenue Structure) or FPS Group name.  The numbers within can be summarized to match pages from either the Supporting Schedule, Departmental Estimate or the Expense, Revenue, Contact Budget.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| No       |                | publication_date               | Publication Date               | text      | text        |
| Yes      | time           | fiscal_year                    | Fiscal Year                    | number    | number      |
| Yes      | series tag     | fundind_source_name            | Fundind Source Name            | text      | text        |
| Yes      | series tag     | fps_group                      | FPS Group                      | text      | number      |
| Yes      | series tag     | fps_group_name                 | FPS Group Name                 | text      | text        |
| Yes      | series tag     | agency_number                  | Agency Number                  | text      | text        |
| Yes      | series tag     | agency_name                    | Agency Name                    | text      | text        |
| Yes      | numeric metric | revenue_category               | Revenue Category               | number    | number      |
| Yes      | series tag     | revenue_category_name          | Revenue Category Name          | text      | text        |
| Yes      | series tag     | revenue_class_code             | Revenue Class Code             | text      | text        |
| Yes      | series tag     | revenue_class_name             | Revenue Class Name             | text      | text        |
| Yes      | series tag     | budget_code                    | Budget Code                    | text      | text        |
| Yes      | series tag     | revenue_source                 | Revenue Source                 | text      | text        |
| Yes      | series tag     | revenue_source_name            | Revenue Source Name            | text      | text        |
| Yes      | series tag     | revenue_structure_description  | Revenue Structure Description  | text      | text        |
| Yes      | numeric metric | adopted_budget_amount          | Adopted Budget Amount          | number    | number      |
| Yes      | numeric metric | current_modified_budget_amount | Current Modified Budget Amount | number    | number      |
| Yes      | numeric metric | yr1_fy                         | Yr1_FY                         | number    | number      |
| Yes      | numeric metric | year_1_revenue_amount          | Year 1 Revenue Amount          | number    | number      |
| Yes      | numeric metric | year_2_revenue_amount          | Year 2 Revenue Amount          | number    | number      |
| Yes      | numeric metric | year_3_revenue_amount          | Year 3 Revenue Amount          | number    | number      |
| Yes      | numeric metric | year_4_revenue_amount          | Year 4 Revenue Amount          | number    | number      |
| Yes      | numeric metric | year_5_revenue_amount          | Year 5 Revenue Amount          | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = publication_date
```

## Data Commands

```ls
series e:ugzk-a6x4 d:2017-01-01T00:00:00.000Z t:fundind_source_name="City Funds" t:fps_group=1 t:revenue_source_name="ACCRUED REAL ESTATE TAX REVENUE" t:revenue_class_code=001 t:revenue_class_name="GENERAL PROPERTY TAXES" t:budget_code=0421 t:revenue_structure_description="REAL ESTATE TX REV-NON-CASH" t:agency_number=002 t:revenue_category_name=TAXES t:agency_name=Mayoralty t:fps_group_name="Real Property" t:revenue_source=00049 m:current_modified_budget_amount=295000000 m:year_2_revenue_amount=300000000 m:yr1_fy=2016 m:adopted_budget_amount=260000000 m:year_5_revenue_amount=320000000 m:year_4_revenue_amount=310000000 m:year_3_revenue_amount=305000000 m:revenue_category=20 m:year_1_revenue_amount=295000000

series e:ugzk-a6x4 d:2017-01-01T00:00:00.000Z t:fundind_source_name="City Funds" t:fps_group=1 t:revenue_source_name="REAL ESTATE TAX REFUNDS" t:revenue_class_code=001 t:revenue_class_name="GENERAL PROPERTY TAXES" t:budget_code=0421 t:revenue_structure_description="GEN PROPERTY TAXES REFUNDS" t:agency_number=002 t:revenue_category_name=TAXES t:agency_name=Mayoralty t:fps_group_name="Real Property" t:revenue_source=00021 m:current_modified_budget_amount=-275000000 m:year_2_revenue_amount=-400000000 m:yr1_fy=2016 m:adopted_budget_amount=-395000000 m:year_5_revenue_amount=-400000000 m:year_4_revenue_amount=-400000000 m:year_3_revenue_amount=-400000000 m:revenue_category=20 m:year_1_revenue_amount=-275000000

series e:ugzk-a6x4 d:2017-01-01T00:00:00.000Z t:fundind_source_name="City Funds" t:fps_group=1 t:revenue_source_name="REAL PROP TAX 1ST QUART" t:revenue_class_code=001 t:revenue_class_name="GENERAL PROPERTY TAXES" t:budget_code=0421 t:revenue_structure_description="REAL PROP TAX 1ST QUART" t:agency_number=002 t:revenue_category_name=TAXES t:agency_name=Mayoralty t:fps_group_name="Real Property" t:revenue_source=00001 m:current_modified_budget_amount=9827756000 m:year_2_revenue_amount=10367155000 m:yr1_fy=2016 m:adopted_budget_amount=9462447000 m:year_5_revenue_amount=12165584000 m:year_4_revenue_amount=11623746000 m:year_3_revenue_amount=10976702000 m:revenue_category=20 m:year_1_revenue_amount=9811756000
```

## Meta Commands

```ls
metric m:revenue_category p:double l:"Revenue Category" d:"2-digit code which identifies a rollup level for the revenue source" t:dataTypeName=number

metric m:adopted_budget_amount p:long l:"Adopted Budget Amount" d:"Financial plan for the City and its agencies for a fiscal year, setting forth estimated revenues as authorized by the City Council." t:dataTypeName=number

metric m:current_modified_budget_amount p:long l:"Current Modified Budget Amount" d:"The Adopted Budget as revised through modification and approval in accordance with the City Charter." t:dataTypeName=number

metric m:yr1_fy p:integer l:Yr1_FY t:dataTypeName=number

metric m:year_1_revenue_amount p:long l:"Year 1 Revenue Amount" d:"Fiscal Year 1 $ amount" t:dataTypeName=number

metric m:year_2_revenue_amount p:long l:"Year 2 Revenue Amount" d:"Fiscal Year 2 $ amount" t:dataTypeName=number

metric m:year_3_revenue_amount p:long l:"Year 3 Revenue Amount" d:"Fiscal Year 3 $ amount" t:dataTypeName=number

metric m:year_4_revenue_amount p:long l:"Year 4 Revenue Amount" d:"Fiscal Year 4 $ amount" t:dataTypeName=number

metric m:year_5_revenue_amount p:long l:"Year 5 Revenue Amount" d:"Fiscal Year 5 $ amount" t:dataTypeName=number

entity e:ugzk-a6x4 l:"Revenue Budget & Financial Plan -- Exec\Adpt\Prel" t:attribution="Mayor?s Office of Management & Budget (OMB)" t:url=https://data.cityofnewyork.us/api/views/ugzk-a6x4

property e:ugzk-a6x4 t:meta.view v:id=ugzk-a6x4 v:category="City Government" v:averageRating=0 v:name="Revenue Budget & Financial Plan -- Exec\Adpt\Prel" v:attribution="Mayor?s Office of Management & Budget (OMB)"

property e:ugzk-a6x4 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ugzk-a6x4 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| publication_date | fiscal_year | fundind_source_name | fps_group | fps_group_name      | agency_number | agency_name | revenue_category | revenue_category_name | revenue_class_code | revenue_class_name     | budget_code | revenue_source | revenue_source_name             | revenue_structure_description  | adopted_budget_amount | current_modified_budget_amount | yr1_fy | year_1_revenue_amount | year_2_revenue_amount | year_3_revenue_amount | year_4_revenue_amount | year_5_revenue_amount | 
| ================ | =========== | =================== | ========= | =================== | ============= | =========== | ================ | ===================== | ================== | ====================== | =========== | ============== | =============================== | ============================== | ===================== | ============================== | ====== | ===================== | ===================== | ===================== | ===================== | ===================== | 
| 2016 04 26       | 2017        | City Funds          | 1         | Real Property       | 002           | Mayoralty   | 20               | TAXES                 | 001                | GENERAL PROPERTY TAXES | 0421        | 00049          | ACCRUED REAL ESTATE TAX REVENUE | REAL ESTATE TX REV-NON-CASH    | 260000000             | 295000000                      | 2016   | 295000000             | 300000000             | 305000000             | 310000000             | 320000000             | 
| 2016 04 26       | 2017        | City Funds          | 1         | Real Property       | 002           | Mayoralty   | 20               | TAXES                 | 001                | GENERAL PROPERTY TAXES | 0421        | 00021          | REAL ESTATE TAX REFUNDS         | GEN PROPERTY TAXES REFUNDS     | -395000000            | -275000000                     | 2016   | -275000000            | -400000000            | -400000000            | -400000000            | -400000000            | 
| 2016 04 26       | 2017        | City Funds          | 1         | Real Property       | 002           | Mayoralty   | 20               | TAXES                 | 001                | GENERAL PROPERTY TAXES | 0421        | 00001          | REAL PROP TAX 1ST QUART         | REAL PROP TAX 1ST QUART        | 9462447000            | 9827756000                     | 2016   | 9811756000            | 10367155000           | 10976702000           | 11623746000           | 12165584000           | 
| 2016 04 26       | 2017        | City Funds          | 1         | Real Property       | 002           | Mayoralty   | 20               | TAXES                 | 001                | GENERAL PROPERTY TAXES | 0421        | 00002          | REAL PROP TAX 2ND QUART         | REAL PROP TAX 2ND QUART        | 1779139000            | 1805238000                     | 2016   | 1722238000            | 1819727000            | 1926719000            | 2040293000            | 2135401000            | 
| 2016 04 26       | 2017        | City Funds          | 1         | Real Property       | 002           | Mayoralty   | 20               | TAXES                 | 001                | GENERAL PROPERTY TAXES | 0421        | 00003          | REAL PROP TAX 3RD QUART         | REAL ESTATE TAXES 3RD QUARTER  | 9454230000            | 9066315000                     | 2016   | 9605315000            | 10149029000           | 10745751000           | 11379179000           | 11909618000           | 
| 2016 04 26       | 2017        | City Funds          | 1         | Real Property       | 002           | Mayoralty   | 20               | TAXES                 | 001                | GENERAL PROPERTY TAXES | 0421        | 00004          | REAL PROP TAX 4TH QUART         | REAL PROP TAX 4TH QUART        | 1760376000            | 1756883000                     | 2016   | 1575883000            | 1665086000            | 1762987000            | 1866908000            | 1953933000            | 
| 2016 04 26       | 2017        | City Funds          | 1         | Real Property       | 002           | Mayoralty   | 20               | TAXES                 | 001                | GENERAL PROPERTY TAXES | 0421        | 00034          | REAL PROPERTY TAX LIEN SALES    | REAL PROPERTY TAX LIEN SALES   | 63000000              | 80000000                       | 2016   | 80000000              | 80000000              | 80000000              | 80000000              | 80000000              | 
| 2016 04 26       | 2017        | City Funds          | 2         | Personal Income     | 002           | Mayoralty   | 20               | TAXES                 | 004                | INCOME TAXES           | 0421        | 00090          | PERSONAL INCOME TAX             | PERSONAL INCOME TAX            | 11996000000           | 12308000000                    | 2016   | 12234000000           | 12347000000           | 12683000000           | 13145000000           | 13660000000           | 
| 2016 04 26       | 2017        | City Funds          | 2         | Personal Income     | 002           | Mayoralty   | 20               | TAXES                 | 004                | INCOME TAXES           | 0421        | 00091          | REFUNDS OF PERSONAL INCOME TAX  | REFUNDS OF PERSONAL INCOME TAX | -1402000000           | -1275000000                    | 2016   | -1340000000           | -1357000000           | -1382000000           | -1425000000           | -1475000000           | 
| 2016 04 26       | 2017        | City Funds          | 3         | General Corporation | 002           | Mayoralty   | 20               | TAXES                 | 004                | INCOME TAXES           | 0421        | 00093          | GENERAL CORPORATION TAX         | GENERAL CORPORATION TAX        | 4500000000            | 4131161000                     | 2016   | 4064161000            | 4426000000            | 4671000000            | 4673000000            | 4719000000            | 
```