# Administrative Hearings - Top 5 Sheriff's Police Violations - Fiscal Year 2011 Incomplete

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/administrative-hearings-top-5-sheriffs-police-violations-fiscal-year-2011-incomplete-8d16e) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/wp8p-jvuw) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/wp8p-jvuw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/wp8p-jvuw/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | wp8p-jvuw |
| Name | Administrative Hearings - Top 5 Sheriff's Police Violations - Fiscal Year 2011 Incomplete |
| Attribution | Cook County Department of Administrative Hearings |
| Category | Courts |
| Created | 2011-09-28T15:49:59Z |
| Publication Date | 2014-10-09T22:58:51Z |

## Description

Data covers December 1, 2010 through September 22, 2011

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                            | Data Type | Render Type |
| ======== | ============== | =========================================== | =============================================== | ========= | =========== |
| Yes      | series tag     | violation_code                              | Violation Code                                  | text      | text        |
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
series e:wp8p-jvuw d:2011-01-01T00:00:00.000Z t:violation_code=74-552 t:top_5_violations_report_12_1_2010_9_22_2011="NO WHEEL TAX STICKER" m:number_of_violations=929

series e:wp8p-jvuw d:2011-01-01T00:00:00.000Z t:violation_code=82-125(F) t:top_5_violations_report_12_1_2010_9_22_2011="NO VALID REGISTRATION" m:number_of_violations=885

series e:wp8p-jvuw d:2011-01-01T00:00:00.000Z t:violation_code=82-125(A) t:top_5_violations_report_12_1_2010_9_22_2011="NO FRONT OR REAR PLATE" m:number_of_violations=189
```

## Meta Commands

```ls
metric m:number_of_violations p:integer l:"Number of Violations" t:dataTypeName=number

entity e:wp8p-jvuw l:"Administrative Hearings - Top 5 Sheriff's Police Violations - Fiscal Year 2011 Incomplete" t:attribution="Cook County Department of Administrative Hearings" t:url=https://datacatalog.cookcountyil.gov/api/views/wp8p-jvuw

property e:wp8p-jvuw t:meta.view v:id=wp8p-jvuw v:category=Courts v:averageRating=0 v:name="Administrative Hearings - Top 5 Sheriff's Police Violations - Fiscal Year 2011 Incomplete" v:attribution="Cook County Department of Administrative Hearings"

property e:wp8p-jvuw t:meta.view.license v:name="Public Domain"

property e:wp8p-jvuw t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:wp8p-jvuw t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| violation_code | top_5_violations_report_12_1_2010_9_22_2011        | number_of_violations | 
| ============== | ================================================== | ==================== | 
| 74-552         | NO WHEEL TAX STICKER                               | 929                  | 
| 82-125(F)      | NO VALID REGISTRATION                              | 885                  | 
| 82-125(A)      | NO FRONT OR REAR PLATE                             | 189                  | 
| 82-128         | BROKEN OR INOPERABLE LAMPS;BROKEN OR CRACKED GLASS | 90                   | 
| 82-114(B)      | TWO HEADLIGHTS REQUIRED                            | 62                   | 
```