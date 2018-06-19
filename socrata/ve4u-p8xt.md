# Administrative Hearings - Top 5 Violations Report, all Departments - Fiscal Year 2011 Incomplete

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/administrative-hearings-top-5-violations-report-all-departments-fiscal-year-2011-incomplet-7abeb) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/ve4u-p8xt) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ve4u-p8xt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ve4u-p8xt/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | ve4u-p8xt |
| Name | Administrative Hearings - Top 5 Violations Report, all Departments - Fiscal Year 2011 Incomplete |
| Attribution | Cook County Department of Administrative Hearings |
| Category | Courts |
| Created | 2011-09-28T15:26:32Z |
| Publication Date | 2014-10-09T22:58:39Z |

## Description

Data covers December 2010 through August 2011

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                   | Data Type | Render Type |
| ======== | ============== | ==================================== | ====================================== | ========= | =========== |
| Yes      | series tag     | violation_code                       | Violation Code                         | text      | text        |
| Yes      | series tag     | top_5_violations_12_1_2010_8_31_2011 | Top 5 Violations 12/1/2010 - 8/31/2011 | text      | text        |
| Yes      | numeric metric | number_of_violations                 | Number of Violations                   | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ve4u-p8xt d:2011-01-01T00:00:00.000Z t:top_5_violations_12_1_2010_8_31_2011="FAILED TO REMIT TAX" t:violation_code=74-272 m:number_of_violations=986

series e:ve4u-p8xt d:2011-01-01T00:00:00.000Z t:top_5_violations_12_1_2010_8_31_2011="NO VALID REGISTRATION" t:violation_code=82-125(F) m:number_of_violations=448

series e:ve4u-p8xt d:2011-01-01T00:00:00.000Z t:top_5_violations_12_1_2010_8_31_2011="TRAFFIC CODE ADOPTED" t:violation_code=4/1/01 m:number_of_violations=447
```

## Meta Commands

```ls
metric m:number_of_violations p:integer l:"Number of Violations" t:dataTypeName=number

entity e:ve4u-p8xt l:"Administrative Hearings - Top 5 Violations Report, all Departments - Fiscal Year 2011 Incomplete" t:attribution="Cook County Department of Administrative Hearings" t:url=https://datacatalog.cookcountyil.gov/api/views/ve4u-p8xt

property e:ve4u-p8xt t:meta.view v:id=ve4u-p8xt v:category=Courts v:averageRating=0 v:name="Administrative Hearings - Top 5 Violations Report, all Departments - Fiscal Year 2011 Incomplete" v:attribution="Cook County Department of Administrative Hearings"

property e:ve4u-p8xt t:meta.view.license v:name="Public Domain"

property e:ve4u-p8xt t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:ve4u-p8xt t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| violation_code | top_5_violations_12_1_2010_8_31_2011 | number_of_violations | 
| ============== | ==================================== | ==================== | 
| 74-272         | FAILED TO REMIT TAX                  | 986                  | 
| 82-125(F)      | NO VALID REGISTRATION                | 448                  | 
| 4/1/01         | TRAFFIC CODE ADOPTED                 | 447                  | 
| 74-552         | NO WHEEL TAX STICKER                 | 438                  | 
| 2/4/01         | Hours of Operation(after hours)      | 429                  | 
| Total          |                                      | 2748                 | 
```