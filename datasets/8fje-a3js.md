# Administrative Hearings - Top 5 Cigarette Tax Violations - Fiscal Year 2011 Incomplete

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/administrative-hearings-top-5-cigarette-tax-violations-fiscal-year-2011-incomplete-db887) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/8fje-a3js) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/8fje-a3js/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/8fje-a3js/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 8fje-a3js |
| Name | Administrative Hearings - Top 5 Cigarette Tax Violations - Fiscal Year 2011 Incomplete |
| Attribution | Cook County Department of Administrative Hearings |
| Category | Courts |
| Created | 2011-09-28T16:17:41Z |
| Publication Date | 2014-10-09T22:59:56Z |

## Description

Data covers December 1, 2010 through September 22, 2011

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                            | Data Type | Render Type |
| ======== | ============== | =========================================== | =============================================== | ========= | =========== |
| Yes      | series tag     | violation_code_                             | Violation Code                                  | text      | text        |
| Yes      | series tag     | top_5_violations_report_12_1_2010_9_22_2011 | Top 5 Violations Report - 12/1/2010 - 9/22/2011 | text      | text        |
| Yes      | numeric metric | number_of_violations                        | Number of Violations                            | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8fje-a3js d:2011-01-01T00:00:00.000Z t:violation_code_=74-432(d) t:top_5_violations_report_12_1_2010_9_22_2011="MUTILATED OR ALTERED TAX STAMPS" m:number_of_violations=296

series e:8fje-a3js d:2011-01-01T00:00:00.000Z t:violation_code_=74-432(F) t:top_5_violations_report_12_1_2010_9_22_2011="Sales of Indvidual/ Unpackaged Cigarettes" m:number_of_violations=112

series e:8fje-a3js d:2011-01-01T00:00:00.000Z t:violation_code_=74-435A-4 t:top_5_violations_report_12_1_2010_9_22_2011="VIOLATION OF TOBACCO TAX" m:number_of_violations=99
```

## Meta Commands

```ls
metric m:number_of_violations p:integer l:"Number of Violations" t:dataTypeName=number

entity e:8fje-a3js l:"Administrative Hearings - Top 5 Cigarette Tax Violations - Fiscal Year 2011 Incomplete" t:attribution="Cook County Department of Administrative Hearings" t:url=https://datacatalog.cookcountyil.gov/api/views/8fje-a3js

property e:8fje-a3js t:meta.view v:id=8fje-a3js v:category=Courts v:averageRating=0 v:name="Administrative Hearings - Top 5 Cigarette Tax Violations - Fiscal Year 2011 Incomplete" v:attribution="Cook County Department of Administrative Hearings"

property e:8fje-a3js t:meta.view.license v:name="Public Domain"

property e:8fje-a3js t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:8fje-a3js t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| violation_code_ | top_5_violations_report_12_1_2010_9_22_2011        | number_of_violations | 
| =============== | ================================================== | ==================== | 
| 74-432(d)       | MUTILATED OR ALTERED TAX STAMPS                    | 296                  | 
| 74-432(F)       | Sales of Indvidual/ Unpackaged Cigarettes          | 112                  | 
| 74-435A-4       | VIOLATION OF TOBACCO TAX                           | 99                   | 
| 74-435B-3       | VIOLATION OF TOBACCO TAX ORDINANCE SECTION: 74-430 | 75                   | 
| 74-435A4        | VI0OLATION OF TOBACCO TAX ORDINANCE SECTION 74-430 | 53                   | 
| Total           |                                                    | 635                  | 
```