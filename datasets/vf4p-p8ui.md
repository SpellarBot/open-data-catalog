# Revenue Budget & Financial Plan--Qtr1

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/revenue-budget-financial-plan-qtr1) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vf4p-p8ui) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vf4p-p8ui/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vf4p-p8ui/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vf4p-p8ui |
| Name | Revenue Budget & Financial Plan--Qtr1 |
| Attribution | Mayor's Office of Management and Budget (OMB) |
| Category | City Government |
| Tags | omb, revenue, budget, financial, plan |
| Created | 2016-11-29T22:44:14Z |
| Publication Date | 2016-11-29T22:53:00Z |

## Description

This dataset contains agency revenue data for Adopted, Modified and four years of Financial Plan by Revenue Class, Revenue Category and Revenue Source (Revenue Structure) or FPS Group name.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                           | Data Type | Render Type |
| ======== | ============== | ============================= | ============================== | ========= | =========== |
| No       |                | publication_date              | Publication Date               | text      | text        |
| Yes      | time           | fiscal_year                   | Fiscal Year                    | number    | number      |
| Yes      | series tag     | funding_source_name           | Fundind Source Name            | text      | text        |
| Yes      | series tag     | fps_group                     | FPS Group                      | text      | number      |
| Yes      | series tag     | fps_group_name                | FPS Group Name                 | text      | text        |
| Yes      | series tag     | agency_number                 | Agency Number                  | text      | text        |
| Yes      | series tag     | agency_name                   | Agency Name                    | text      | text        |
| Yes      | numeric metric | revenue_category              | Revenue Category               | number    | number      |
| Yes      | series tag     | revenue_category_name         | Revenue Category Name          | text      | text        |
| Yes      | series tag     | revenue_class_code            | Revenue Class Code             | text      | text        |
| Yes      | series tag     | revenue_class_name            | Revenue Class Name             | text      | text        |
| Yes      | series tag     | budget_code                   | Budget Code                    | text      | text        |
| Yes      | series tag     | revenue_source                | Revenue Source                 | text      | text        |
| Yes      | series tag     | revenue_source_name           | Revenue Source Name            | text      | text        |
| Yes      | series tag     | revenue_structure_description | Revenue Structure Description  | text      | text        |
| Yes      | numeric metric | adopted_amt                   | Adopted Budget Amount          | number    | number      |
| Yes      | numeric metric | curr_mod_amt                  | Current Modified Budget Amount | number    | number      |
| Yes      | numeric metric | yr1_fy                        | Yr1_FY                         | number    | number      |
| Yes      | numeric metric | yr1_fp_rev_amt                | Year 1 Revenue Amount          | number    | number      |
| Yes      | numeric metric | yr2_fp_rev_amt                | Year 2 Revenue Amount          | number    | number      |
| Yes      | numeric metric | yr3_fp_rev_amt                | Year 3 Revenue Amount          | number    | number      |
| Yes      | numeric metric | yr4_fp_rev_amt                | Year 4 Revenue Amount          | number    | number      |
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
series e:vf4p-p8ui d:2017-01-01T00:00:00.000Z t:fps_group=1 t:revenue_source_name="REAL PROP TAX 1ST QUART" t:revenue_class_code=001 t:revenue_class_name="GENERAL PROPERTY TAXES" t:budget_code=0421 t:revenue_structure_description="REAL PROP TAX 1ST QUART" t:funding_source_name="City Funds" t:agency_number=002 t:revenue_category_name=TAXES t:agency_name=Mayoralty t:fps_group_name="Real Property" t:revenue_source=00001 m:yr1_fp_rev_amt=10364353000 m:yr4_fp_rev_amt=12151245000 m:yr1_fy=2017 m:yr2_fp_rev_amt=10959257000 m:adopted_amt=10386162000 m:revenue_category=20 m:curr_mod_amt=10386162000 m:yr3_fp_rev_amt=11607958000

series e:vf4p-p8ui d:2017-01-01T00:00:00.000Z t:fps_group=1 t:revenue_source_name="REAL PROP TAX 2ND QUART" t:revenue_class_code=001 t:revenue_class_name="GENERAL PROPERTY TAXES" t:budget_code=0421 t:revenue_structure_description="REAL PROP TAX 2ND QUART" t:funding_source_name="City Funds" t:agency_number=002 t:revenue_category_name=TAXES t:agency_name=Mayoralty t:fps_group_name="Real Property" t:revenue_source=00002 m:yr1_fp_rev_amt=1823017000 m:yr4_fp_rev_amt=2137319000 m:yr1_fy=2017 m:yr2_fp_rev_amt=1927657000 m:adopted_amt=1823062000 m:revenue_category=20 m:curr_mod_amt=1823062000 m:yr3_fp_rev_amt=2041759000

series e:vf4p-p8ui d:2017-01-01T00:00:00.000Z t:fps_group=1 t:revenue_source_name="REAL PROP TAX 3RD QUART" t:revenue_class_code=001 t:revenue_class_name="GENERAL PROPERTY TAXES" t:budget_code=0421 t:revenue_structure_description="REAL ESTATE TAXES 3RD QUARTER" t:funding_source_name="City Funds" t:agency_number=002 t:revenue_category_name=TAXES t:agency_name=Mayoralty t:fps_group_name="Real Property" t:revenue_source=00003 m:yr1_fp_rev_amt=9991423000 m:yr4_fp_rev_amt=11714020000 m:yr1_fy=2017 m:yr2_fp_rev_amt=10564922000 m:adopted_amt=10167635000 m:revenue_category=20 m:curr_mod_amt=10167635000 m:yr3_fp_rev_amt=11190281000
```

## Meta Commands

```ls
metric m:revenue_category p:double l:"Revenue Category" t:dataTypeName=number

metric m:adopted_amt p:long l:"Adopted Budget Amount" t:dataTypeName=number

metric m:curr_mod_amt p:long l:"Current Modified Budget Amount" t:dataTypeName=number

metric m:yr1_fy p:integer l:Yr1_FY t:dataTypeName=number

metric m:yr1_fp_rev_amt p:long l:"Year 1 Revenue Amount" t:dataTypeName=number

metric m:yr2_fp_rev_amt p:long l:"Year 2 Revenue Amount" t:dataTypeName=number

metric m:yr3_fp_rev_amt p:long l:"Year 3 Revenue Amount" t:dataTypeName=number

metric m:yr4_fp_rev_amt p:long l:"Year 4 Revenue Amount" t:dataTypeName=number

entity e:vf4p-p8ui l:"Revenue Budget & Financial Plan--Qtr1" t:attribution="Mayor's Office of Management and Budget (OMB)" t:url=https://data.cityofnewyork.us/api/views/vf4p-p8ui

property e:vf4p-p8ui t:meta.view v:id=vf4p-p8ui v:category="City Government" v:averageRating=0 v:name="Revenue Budget & Financial Plan--Qtr1" v:attribution="Mayor's Office of Management and Budget (OMB)"

property e:vf4p-p8ui t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vf4p-p8ui t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| publication_date | fiscal_year | funding_source_name | fps_group | fps_group_name      | agency_number | agency_name | revenue_category | revenue_category_name | revenue_class_code | revenue_class_name     | budget_code | revenue_source | revenue_source_name             | revenue_structure_description  | adopted_amt | curr_mod_amt | yr1_fy | yr1_fp_rev_amt | yr2_fp_rev_amt | yr3_fp_rev_amt | yr4_fp_rev_amt | 
| ================ | =========== | =================== | ========= | =================== | ============= | =========== | ================ | ===================== | ================== | ====================== | =========== | ============== | =============================== | ============================== | =========== | ============ | ====== | ============== | ============== | ============== | ============== | 
| 2016 11 17       | 2017        | City Funds          | 1         | Real Property       | 002           | Mayoralty   | 20               | TAXES                 | 001                | GENERAL PROPERTY TAXES | 0421        | 00001          | REAL PROP TAX 1ST QUART         | REAL PROP TAX 1ST QUART        | 10386162000 | 10386162000  | 2017   | 10364353000    | 10959257000    | 11607958000    | 12151245000    | 
| 2016 11 17       | 2017        | City Funds          | 1         | Real Property       | 002           | Mayoralty   | 20               | TAXES                 | 001                | GENERAL PROPERTY TAXES | 0421        | 00002          | REAL PROP TAX 2ND QUART         | REAL PROP TAX 2ND QUART        | 1823062000  | 1823062000   | 2017   | 1823017000     | 1927657000     | 2041759000     | 2137319000     | 
| 2016 11 17       | 2017        | City Funds          | 1         | Real Property       | 002           | Mayoralty   | 20               | TAXES                 | 001                | GENERAL PROPERTY TAXES | 0421        | 00003          | REAL PROP TAX 3RD QUART         | REAL ESTATE TAXES 3RD QUARTER  | 10167635000 | 10167635000  | 2017   | 9991423000     | 10564922000    | 11190281000    | 11714020000    | 
| 2016 11 17       | 2017        | City Funds          | 1         | Real Property       | 002           | Mayoralty   | 20               | TAXES                 | 001                | GENERAL PROPERTY TAXES | 0421        | 00004          | REAL PROP TAX 4TH QUART         | REAL PROP TAX 4TH QUART        | 1668138000  | 1668138000   | 2017   | 1866204000     | 1973323000     | 2090128000     | 2187952000     | 
| 2016 11 17       | 2017        | City Funds          | 1         | Real Property       | 002           | Mayoralty   | 20               | TAXES                 | 001                | GENERAL PROPERTY TAXES | 0421        | 00021          | REAL ESTATE TAX REFUNDS         | GEN PROPERTY TAXES REFUNDS     | -400000000  | -400000000   | 2017   | -400000000     | -400000000     | -400000000     | -400000000     | 
| 2016 11 17       | 2017        | City Funds          | 1         | Real Property       | 002           | Mayoralty   | 20               | TAXES                 | 001                | GENERAL PROPERTY TAXES | 0421        | 00034          | REAL PROPERTY TAX LIEN SALES    | REAL PROPERTY TAX LIEN SALES   | 80000000    | 80000000     | 2017   | 80000000       | 80000000       | 80000000       | 80000000       | 
| 2016 11 17       | 2017        | City Funds          | 1         | Real Property       | 002           | Mayoralty   | 20               | TAXES                 | 001                | GENERAL PROPERTY TAXES | 0421        | 00049          | ACCRUED REAL ESTATE TAX REVENUE | REAL ESTATE TX REV-NON-CASH    | 300000000   | 300000000    | 2017   | 300000000      | 305000000      | 310000000      | 320000000      | 
| 2016 11 17       | 2017        | City Funds          | 2         | Personal Income     | 002           | Mayoralty   | 20               | TAXES                 | 004                | INCOME TAXES           | 0421        | 00090          | PERSONAL INCOME TAX             | PERSONAL INCOME TAX            | 12347000000 | 12347000000  | 2017   | 12311000000    | 12683000000    | 13145000000    | 13660000000    | 
| 2016 11 17       | 2017        | City Funds          | 2         | Personal Income     | 002           | Mayoralty   | 20               | TAXES                 | 004                | INCOME TAXES           | 0421        | 00091          | REFUNDS OF PERSONAL INCOME TAX  | REFUNDS OF PERSONAL INCOME TAX | -1122000000 | -1122000000  | 2017   | -1127000000    | -1130000000    | -1174000000    | -1224000000    | 
| 2016 11 17       | 2017        | City Funds          | 3         | General Corporation | 002           | Mayoralty   | 20               | TAXES                 | 004                | INCOME TAXES           | 0421        | 00093          | GENERAL CORPORATION TAX         | GENERAL CORPORATION TAX        | 4426000000  | 4426000000   | 2017   | 4394000000     | 4671000000     | 4673000000     | 4719000000     | 
```