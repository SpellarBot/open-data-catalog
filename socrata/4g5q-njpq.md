# DCF Children in Placement: Annual Point-in-Time Trend By Race/Ethnicity Group

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dcf-children-in-placement-annual-point-in-time-trend-by-race-ethnicity-group) |
| Metadata | [Link](https://data.ct.gov/api/views/4g5q-njpq) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/4g5q-njpq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/4g5q-njpq/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 4g5q-njpq |
| Name | DCF Children in Placement: Annual Point-in-Time Trend By Race/Ethnicity Group |
| Attribution | Department of Children and Families, Office for Research and Evaluation |
| Category | Health and Human Services |
| Tags | dcf, department of children and families, children, placement, race, ethnicity, race/ethnicity, trend |
| Created | 2014-08-05T14:54:54Z |
| Publication Date | 2014-08-05T15:01:09Z |

## Description

This file contains a row for the unique combination of in-care date (first of each state fiscal year), DCF Region/Office responsible for the child's case, Race/Ethnicity Group and whether the placement is inside or outside of CT.  Additional columns provide the numbers of children residing in each placement type on the in-care date. This file will be updated on an annual basis, on or about October 1st of each year.  Rollups that Sum across Month-In-Care dates are NOT valid; though Averages, Medians, Minimum or Maximum values can be calculated with meaningful results.  See attached metadata document for more detail and column definitions.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | time           | data_as_of              | DATA_AS_OF              | calendar_date | calendar_date |
| Yes      | series tag     | region                  | REGION                  | text          | text          |
| Yes      | series tag     | office_name             | OFFICE_NAME             | text          | text          |
| Yes      | series tag     | demographic             | DEMOGRAPHIC             | text          | text          |
| Yes      | series tag     | outofstate              | OUTOFSTATE              | text          | text          |
| No       |                | month_in_care           | MONTH_IN_CARE           | calendar_date | calendar_date |
| Yes      | numeric metric | foster_care             | FOSTER_CARE             | number        | number        |
| Yes      | numeric metric | relative_care           | RELATIVE_CARE           | number        | number        |
| Yes      | numeric metric | special_study           | SPECIAL_STUDY           | number        | number        |
| Yes      | numeric metric | therapeutic_foster_care | THERAPEUTIC_FOSTER_CARE | number        | number        |
| Yes      | numeric metric | pdc_safe_home           | PDC_SAFE_HOME           | number        | number        |
| Yes      | numeric metric | shelter                 | SHELTER                 | number        | number        |
| Yes      | numeric metric | group_home              | GROUP_HOME              | number        | number        |
| Yes      | numeric metric | residential             | RESIDENTIAL             | number        | number        |
| Yes      | numeric metric | dcf_highmeadows         | DCF_HIGHMEADOWS         | number        | number        |
| Yes      | numeric metric | dcf_solnit              | DCF_SOLNIT              | number        | number        |
| Yes      | numeric metric | dcf_cjts                | DCF_CJTS                | number        | number        |
| Yes      | numeric metric | medical                 | MEDICAL                 | number        | number        |
| Yes      | numeric metric | independent_living      | INDEPENDENT_LIVING      | number        | number        |
```

## Time Field

```ls
Value = data_as_of
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = month_in_care
```

## Data Commands

```ls
series e:4g5q-njpq d:2014-06-26T00:00:00.000Z t:region=Other t:office_name=NULL t:outofstate=N t:demographic=WHITE m:group_home=0 m:independent_living=0 m:relative_care=0 m:dcf_solnit=0 m:medical=0 m:dcf_highmeadows=0 m:shelter=0 m:residential=0 m:pdc_safe_home=0 m:foster_care=1 m:therapeutic_foster_care=0 m:special_study=0 m:dcf_cjts=0

series e:4g5q-njpq d:2014-06-26T00:00:00.000Z t:region=Other t:office_name=Aftercare t:outofstate=N t:demographic=BLACK m:group_home=1 m:independent_living=0 m:relative_care=0 m:dcf_solnit=0 m:medical=0 m:dcf_highmeadows=0 m:shelter=0 m:residential=5 m:pdc_safe_home=0 m:foster_care=0 m:therapeutic_foster_care=0 m:special_study=0 m:dcf_cjts=4

series e:4g5q-njpq d:2014-06-26T00:00:00.000Z t:region=Other t:office_name=Aftercare t:outofstate=Y t:demographic=BLACK m:group_home=0 m:independent_living=0 m:relative_care=0 m:dcf_solnit=0 m:medical=0 m:dcf_highmeadows=0 m:shelter=0 m:residential=3 m:pdc_safe_home=0 m:foster_care=0 m:therapeutic_foster_care=0 m:special_study=0 m:dcf_cjts=0
```

## Meta Commands

```ls
metric m:foster_care p:integer l:FOSTER_CARE t:dataTypeName=number

metric m:relative_care p:integer l:RELATIVE_CARE t:dataTypeName=number

metric m:special_study p:integer l:SPECIAL_STUDY t:dataTypeName=number

metric m:therapeutic_foster_care p:integer l:THERAPEUTIC_FOSTER_CARE t:dataTypeName=number

metric m:pdc_safe_home p:integer l:PDC_SAFE_HOME t:dataTypeName=number

metric m:shelter p:integer l:SHELTER t:dataTypeName=number

metric m:group_home p:integer l:GROUP_HOME t:dataTypeName=number

metric m:residential p:integer l:RESIDENTIAL t:dataTypeName=number

metric m:dcf_highmeadows p:integer l:DCF_HIGHMEADOWS t:dataTypeName=number

metric m:dcf_solnit p:integer l:DCF_SOLNIT t:dataTypeName=number

metric m:dcf_cjts p:integer l:DCF_CJTS t:dataTypeName=number

metric m:medical p:integer l:MEDICAL t:dataTypeName=number

metric m:independent_living p:integer l:INDEPENDENT_LIVING t:dataTypeName=number

entity e:4g5q-njpq l:"DCF Children in Placement:  Annual Point-in-Time Trend By Race/Ethnicity Group" t:attribution="Department of Children and Families, Office for Research and Evaluation" t:url=https://data.ct.gov/api/views/4g5q-njpq

property e:4g5q-njpq t:meta.view v:id=4g5q-njpq v:category="Health and Human Services" v:averageRating=0 v:name="DCF Children in Placement:  Annual Point-in-Time Trend By Race/Ethnicity Group" v:attribution="Department of Children and Families, Office for Research and Evaluation"

property e:4g5q-njpq t:meta.view.license v:name="Public Domain"

property e:4g5q-njpq t:meta.view.owner v:id=hd87-ziyn v:screenName="Fred North" v:displayName="Fred North"

property e:4g5q-njpq t:meta.view.tableauthor v:id=hd87-ziyn v:screenName="Fred North" v:roleName=editor v:displayName="Fred North"
```

## Top Records

```ls
| data_as_of          | region | office_name          | demographic | outofstate | month_in_care       | foster_care | relative_care | special_study | therapeutic_foster_care | pdc_safe_home | shelter | group_home | residential | dcf_highmeadows | dcf_solnit | dcf_cjts | medical | independent_living | 
| =================== | ====== | ==================== | =========== | ========== | =================== | =========== | ============= | ============= | ======================= | ============= | ======= | ========== | =========== | =============== | ========== | ======== | ======= | ================== | 
| 2014-06-26T00:00:00 | Other  | NULL                 | WHITE       | N          | 2004-07-01T00:00:00 | 1           | 0             | 0             | 0                       | 0             | 0       | 0          | 0           | 0               | 0          | 0        | 0       | 0                  | 
| 2014-06-26T00:00:00 | Other  | Aftercare            | BLACK       | N          | 2004-07-01T00:00:00 | 0           | 0             | 0             | 0                       | 0             | 0       | 1          | 5           | 0               | 0          | 4        | 0       | 0                  | 
| 2014-06-26T00:00:00 | Other  | Aftercare            | BLACK       | Y          | 2004-07-01T00:00:00 | 0           | 0             | 0             | 0                       | 0             | 0       | 0          | 3           | 0               | 0          | 0        | 0       | 0                  | 
| 2014-06-26T00:00:00 | Other  | Aftercare            | HISPANIC    | N          | 2004-07-01T00:00:00 | 0           | 0             | 0             | 0                       | 0             | 0       | 0          | 6           | 0               | 0          | 7        | 0       | 0                  | 
| 2014-06-26T00:00:00 | Other  | Aftercare            | WHITE       | N          | 2004-07-01T00:00:00 | 0           | 0             | 0             | 0                       | 0             | 0       | 0          | 2           | 0               | 0          | 3        | 0       | 0                  | 
| 2014-06-26T00:00:00 | Other  | Aftercare            | WHITE       | Y          | 2004-07-01T00:00:00 | 0           | 0             | 0             | 0                       | 0             | 0       | 0          | 5           | 0               | 0          | 0        | 0       | 0                  | 
| 2014-06-26T00:00:00 | Other  | Gen'l Administration | BLACK       | N          | 2004-07-01T00:00:00 | 0           | 0             | 0             | 0                       | 0             | 0       | 0          | 4           | 0               | 0          | 1        | 0       | 0                  | 
| 2014-06-26T00:00:00 | Other  | Gen'l Administration | BLACK       | Y          | 2004-07-01T00:00:00 | 0           | 0             | 0             | 0                       | 0             | 0       | 0          | 2           | 0               | 0          | 0        | 0       | 0                  | 
| 2014-06-26T00:00:00 | Other  | Gen'l Administration | HISPANIC    | N          | 2004-07-01T00:00:00 | 0           | 0             | 0             | 0                       | 0             | 0       | 0          | 0           | 0               | 0          | 3        | 0       | 0                  | 
| 2014-06-26T00:00:00 | Other  | Gen'l Administration | HISPANIC    | Y          | 2004-07-01T00:00:00 | 0           | 0             | 0             | 0                       | 0             | 0       | 0          | 3           | 0               | 0          | 0        | 0       | 0                  | 
```