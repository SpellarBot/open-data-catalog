# Administrative Hearings - Top 5 Environmental Control Violations - Fiscal Year 2011 Incomplete

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/administrative-hearings-top-5-environmental-control-violations-fiscal-year-2011-incomplete-915d0) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/rmtf-njph) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/rmtf-njph/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/rmtf-njph/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | rmtf-njph |
| Name | Administrative Hearings - Top 5 Environmental Control Violations - Fiscal Year 2011 Incomplete |
| Attribution | Cook County Department of Administrative Hearings |
| Category | Courts |
| Created | 2011-09-28T15:42:56Z |
| Publication Date | 2014-10-09T23:09:30Z |

## Description

Data covers December 1, 2010 through September 22, 2011

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                            | Data Type | Render Type |
| ======== | ============== | =========================================== | =============================================== | ========= | =========== |
| Yes      | series tag     | violation_code_                             | Violation Code                                  | text      | text        |
| Yes      | series tag     | top_5_violations_report_12_1_2010_9_22_2011 | Top 5 Violations Report - 12/1/2010 - 9/22/2011 | text      | text        |
| Yes      | numeric metric | number_of_violations                        | Number of Violations                            | number    | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rmtf-njph d:2011-01-01T00:00:00.000Z t:violation_code_=30-92 t:top_5_violations_report_12_1_2010_9_22_2011="Late payment of fees" m:number_of_violations=60

series e:rmtf-njph d:2011-01-01T00:00:00.000Z t:violation_code_=30-186 t:top_5_violations_report_12_1_2010_9_22_2011="no valid certificate of operation" m:number_of_violations=56

series e:rmtf-njph d:2011-01-01T00:00:00.000Z t:violation_code_="30-544 (b) 2-a" t:top_5_violations_report_12_1_2010_9_22_2011="No valid Demolition permit" m:number_of_violations=9
```

## Meta Commands

```ls
metric m:number_of_violations p:integer l:"Number of Violations" t:dataTypeName=number

entity e:rmtf-njph l:"Administrative Hearings - Top 5 Environmental Control Violations - Fiscal Year 2011 Incomplete" t:attribution="Cook County Department of Administrative Hearings" t:url=https://datacatalog.cookcountyil.gov/api/views/rmtf-njph

property e:rmtf-njph t:meta.view v:id=rmtf-njph v:category=Courts v:averageRating=0 v:name="Administrative Hearings - Top 5 Environmental Control Violations - Fiscal Year 2011 Incomplete" v:attribution="Cook County Department of Administrative Hearings"

property e:rmtf-njph t:meta.view.license v:name="Public Domain"

property e:rmtf-njph t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:rmtf-njph t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| violation_code_ | top_5_violations_report_12_1_2010_9_22_2011 | number_of_violations | 
| =============== | =========================================== | ==================== | 
| 30-92           | Late payment of fees                        | 60                   | 
| 30-186          | no valid certificate of operation           | 56                   | 
| 30-544 (b) 2-a  | No valid Demolition permit                  | 9                    | 
| 30-544(b)2-b    | no valid ACM Abatement Permit               | 9                    | 
| 30-544(b)2-a    | NO VALID DEMOLITION PERMIT                  | 9                    | 
| Total           |                                             | 143                  | 
```