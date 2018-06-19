# Expense Financial Plan - Adpt\Prel

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expense-financial-plan-adptprel) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/e4p3-6ecr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/e4p3-6ecr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/e4p3-6ecr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | e4p3-6ecr |
| Name | Expense Financial Plan - Adpt\Prel |
| Attribution | Mayor's Office of Management and Budget (OMB) |
| Category | City Government |
| Created | 2016-06-17T21:27:02Z |
| Publication Date | 2017-02-08T17:07:10Z |

## Description

This dataset contains agency summary level data for PS, OTPS and Total by type of funds.  The dollar amount fields are rounded to the thousands. The Adopted and Preliminary reports,  published by July 1 and January or February respectively,  contain the current fiscal year plus four out years of data which  coincide with the release of the published financial plan.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name                    | Data Type | Render Type |
| ======== | ============== | =========== | ======================= | ========= | =========== |
| Yes      | time           | pub_date    | Publication Date        | text      | number      |
| Yes      | series tag     | agency_cd   | Agency Number           | text      | text        |
| Yes      | numeric metric | rpt_sort    | Report Sort             | number    | number      |
| Yes      | series tag     | agency_name | Agency Name             | text      | text        |
| Yes      | series tag     | lineno      | Line Number             | text      | number      |
| Yes      | series tag     | lineno_dsc  | Line Number Description | text      | text        |
| Yes      | numeric metric | yr1_fy      | Fiscal Year 1           | number    | number      |
| Yes      | numeric metric | year1_frcst | Year 1 Forecast         | number    | number      |
| Yes      | numeric metric | year2_amt   | Year 2 Estimate         | number    | number      |
| Yes      | numeric metric | year3_amt   | Year 3 Estimate         | number    | number      |
| Yes      | numeric metric | year4_amt   | Year 4 Estimate         | number    | number      |
| Yes      | numeric metric | year5_amt   | Year 5 Estimate         | number    | number      |
```

## Time Field

```ls
Value = pub_date
Format & Zone = yyyyMMdd
```

## Data Commands

```ls
series e:e4p3-6ecr d:2016-06-14T00:00:00.000Z t:lineno=704 t:lineno_dsc="704  Total Department" t:agency_cd=002 t:agency_name=Mayoralty m:year4_amt=134854 m:yr1_fy=2016 m:year1_frcst=126285 m:rpt_sort=2704 m:year2_amt=138095 m:year3_amt=129678 m:year5_amt=130773

series e:e4p3-6ecr d:2016-06-14T00:00:00.000Z t:lineno=705 t:lineno_dsc="705      Salaries and Wages" t:agency_cd=002 t:agency_name=Mayoralty m:year4_amt=100114 m:yr1_fy=2016 m:year1_frcst=98704 m:rpt_sort=2705 m:year2_amt=102676 m:year3_amt=100661 m:year5_amt=99118

series e:e4p3-6ecr d:2016-06-14T00:00:00.000Z t:lineno=706 t:lineno_dsc="706      Fringe Benefits" t:agency_cd=002 t:agency_name=Mayoralty m:year4_amt=176 m:yr1_fy=2016 m:year1_frcst=443 m:rpt_sort=2706 m:year2_amt=193 m:year3_amt=176 m:year5_amt=176
```

## Meta Commands

```ls
metric m:rpt_sort p:integer l:"Report Sort" d:"Sequence of report" t:dataTypeName=number

metric m:yr1_fy p:integer l:"Fiscal Year 1" t:dataTypeName=number

metric m:year1_frcst p:integer l:"Year 1 Forecast" t:dataTypeName=number

metric m:year2_amt p:integer l:"Year 2 Estimate" t:dataTypeName=number

metric m:year3_amt p:integer l:"Year 3 Estimate" t:dataTypeName=number

metric m:year4_amt p:integer l:"Year 4 Estimate" t:dataTypeName=number

metric m:year5_amt p:integer l:"Year 5 Estimate" t:dataTypeName=number

entity e:e4p3-6ecr l:"Expense Financial Plan - Adpt\Prel" t:attribution="Mayor's Office of Management and Budget (OMB)" t:url=https://data.cityofnewyork.us/api/views/e4p3-6ecr

property e:e4p3-6ecr t:meta.view v:id=e4p3-6ecr v:category="City Government" v:averageRating=0 v:name="Expense Financial Plan - Adpt\Prel" v:attribution="Mayor's Office of Management and Budget (OMB)"

property e:e4p3-6ecr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:e4p3-6ecr t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| pub_date | agency_cd | rpt_sort | agency_name | lineno | lineno_dsc                 | yr1_fy | year1_frcst | year2_amt | year3_amt | year4_amt | year5_amt | 
| ======== | ========= | ======== | =========== | ====== | ========================== | ====== | =========== | ========= | ========= | ========= | ========= | 
| 20160614 | 002       | 2704     | Mayoralty   | 704    | 704 Total Department       | 2016   | 126285      | 138095    | 129678    | 134854    | 130773    | 
| 20160614 | 002       | 2705     | Mayoralty   | 705    | 705 Salaries and Wages     | 2016   | 98704       | 102676    | 100661    | 100114    | 99118     | 
| 20160614 | 002       | 2706     | Mayoralty   | 706    | 706 Fringe Benefits        | 2016   | 443         | 193       | 176       | 176       | 176       | 
| 20160614 | 002       | 2707     | Mayoralty   | 707    | 707 Total Personal Service | 2016   | 99147       | 102869    | 100837    | 100290    | 99294     | 
| 20160614 | 002       | 2708     | Mayoralty   | 708    | 708 City Funds             | 2016   | 67909       | 76799     | 77355     | 77522     | 76526     | 
| 20160614 | 002       | 2709     | Mayoralty   | 709    | 709 Other Categorical      | 2016   | 5674        | 4537      | 4462      | 4436      | 4436      | 
| 20160614 | 002       | 2710     | Mayoralty   | 710    | 710 Capital Funds-I.F.A.   | 2016   | 11537       | 11950     | 12046     | 12046     | 12046     | 
| 20160614 | 002       | 2711     | Mayoralty   | 711    | 711 State                  | 2016   | 589         | 271       | 273       | 273       | 273       | 
| 20160614 | 002       | 2712     | Mayoralty   | 712    | 712 Federal - JTPA         | 2016   | 0           | 0         | 0         | 0         | 0         | 
| 20160614 | 002       | 2713     | Mayoralty   | 713    | 713 Federal - C.D.         | 2016   | 7811        | 5893      | 3321      | 3328      | 3328      | 
```