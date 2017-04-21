# Administrative Hearings -Top 5 Animal Control Violations - Fiscal Year 2011 Incomplete

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/administrative-hearings-top-5-animal-control-violations-fiscal-year-2011-incomplete-a95f4) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/f9s7-cv2j) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/f9s7-cv2j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/f9s7-cv2j/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | f9s7-cv2j |
| Name | Administrative Hearings -Top 5 Animal Control Violations - Fiscal Year 2011 Incomplete |
| Attribution | Cook County Department of Administrative Hearings |
| Category | Courts |
| Created | 2011-09-28T15:55:30Z |
| Publication Date | 2014-10-09T23:00:09Z |

## Description

Data covers December 1, 2010 through September 22, 2011

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                            | Data Type | Render Type |
| ======== | ============== | =========================================== | =============================================== | ========= | =========== |
| Yes      | series tag     | violation_code                              | Violation Code                                  | text      | text        |
| Yes      | series tag     | top_5_violations_report_12_1_2010_9_22_2011 | Top 5 Violations Report - 12/1/2010 - 9/22/2011 | text      | text        |
| Yes      | numeric metric | animal_control                              | Animal Control                                  | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:f9s7-cv2j d:2011-01-01T00:00:00.000Z t:violation_code=10-41 t:top_5_violations_report_12_1_2010_9_22_2011="NOT CURRENT WITH RABIES VACCINATION ORDINANCE SECTION" m:animal_control=105

series e:f9s7-cv2j d:2011-01-01T00:00:00.000Z t:violation_code=10-42b2 t:top_5_violations_report_12_1_2010_9_22_2011="FAILURE TO TAKE ANIMAL TO VET FOR TEN DAY RABIES OBSERVATION" m:animal_control=97

series e:f9s7-cv2j d:2011-01-01T00:00:00.000Z t:violation_code=10-42b1 t:top_5_violations_report_12_1_2010_9_22_2011="FAILURE TO TAKE ANIMAL TO VET FOR TEN DAYS RABIES OBSERVATION" m:animal_control=33
```

## Meta Commands

```ls
metric m:animal_control p:integer l:"Animal Control" t:dataTypeName=number

entity e:f9s7-cv2j l:"Administrative Hearings -Top 5 Animal Control Violations - Fiscal Year 2011 Incomplete" t:attribution="Cook County Department of Administrative Hearings" t:url=https://datacatalog.cookcountyil.gov/api/views/f9s7-cv2j

property e:f9s7-cv2j t:meta.view v:id=f9s7-cv2j v:category=Courts v:averageRating=0 v:name="Administrative Hearings -Top 5 Animal Control Violations - Fiscal Year 2011 Incomplete" v:attribution="Cook County Department of Administrative Hearings"

property e:f9s7-cv2j t:meta.view.license v:name="Public Domain"

property e:f9s7-cv2j t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:f9s7-cv2j t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| violation_code | top_5_violations_report_12_1_2010_9_22_2011                       | animal_control | 
| ============== | ================================================================= | ============== | 
| 10-41          | NOT CURRENT WITH RABIES VACCINATION ORDINANCE SECTION             | 105            | 
| 10-42b2        | FAILURE TO TAKE ANIMAL TO VET FOR TEN DAY RABIES OBSERVATION      | 97             | 
| 10-42b1        | FAILURE TO TAKE ANIMAL TO VET FOR TEN DAYS RABIES OBSERVATION     | 33             | 
| 10-42B         | FAILURE TO TAKE ANIMAL BACK TO VET FOR TEN DAY RABIES OBSERVATION | 10             | 
| 10-42(F)       | OTHER-BITING ANIMAL                                               | 3              | 
| Total          |                                                                   | 248            | 
```