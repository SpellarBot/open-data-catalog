# Family planning benefit program income levels

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/family-planning-benefit-program-income-levels-2071e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/a9es-3fcm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/a9es-3fcm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/a9es-3fcm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | a9es-3fcm |
| Name | Family planning benefit program income levels |
| Attribution | Human Resources Administration (HRA) |
| Category | Health |
| Tags | hra, human resources administration, jobs and economic mobility, family planning benefit program income levels |
| Created | 2013-03-19T17:02:36Z |
| Publication Date | 2016-03-02T20:17:19Z |

## Description

The Family Planning Benefit Program (FPBP) is a free and completely confidential New York State program that provides family planning services to teens, women and men who meet certain income and residency requirements, and who are not enrolled in Medicaid or Family Health Plus. You may obtain coverage through FPBP if you meet certain Eligibility Criteria and your income is equal to or less than the income levels listed here. This chart is only a guide. Individuals should see an enrollment counselor for eligibility screening.?   
* Pregnant Women count as two individuals.
NOTE: Chart effective January 1, 2012; subject to annual income updates.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | family_size    | Family Size    | text      | text        |
| Yes      | numeric metric | yearly_income  | Yearly Income  | number    | text        |
| Yes      | numeric metric | monthly_income | Monthly Income | number    | text        |
| Yes      | numeric metric | weekly_income  | Weekly Income  | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:a9es-3fcm d:2016-03-02T12:16:36.000Z t:family_size=1 m:yearly_income=26256 m:weekly_income=505 m:monthly_income=2188

series e:a9es-3fcm d:2016-03-02T12:16:36.000Z t:family_size=2 m:yearly_income=35532 m:weekly_income=683 m:monthly_income=2961

series e:a9es-3fcm d:2016-03-02T12:16:36.000Z t:family_size=3 m:yearly_income=44808 m:weekly_income=862 m:monthly_income=3734
```

## Meta Commands

```ls
metric m:yearly_income p:integer l:"Yearly Income" t:dataTypeName=number

metric m:monthly_income p:integer l:"Monthly Income" t:dataTypeName=number

metric m:weekly_income p:integer l:"Weekly Income" t:dataTypeName=number

entity e:a9es-3fcm l:"Family planning benefit program income levels" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/a9es-3fcm

property e:a9es-3fcm t:meta.view v:id=a9es-3fcm v:category=Health v:attributionLink=http://www.nyc.gov/html/hia/html/public_insurance/family.shtml v:averageRating=0 v:name="Family planning benefit program income levels" v:attribution="Human Resources Administration (HRA)"

property e:a9es-3fcm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:a9es-3fcm t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | family_size                                                            | yearly_income | monthly_income | weekly_income | 
| =========== | ====================================================================== | ============= | ============== | ============= | 
| 1456920996  | 1                                                                      | 26256         | 2188           | 505           | 
| 1456920996  | 2                                                                      | 35532         | 2961           | 683           | 
| 1456920996  | 3                                                                      | 44808         | 3734           | 862           | 
| 1456920996  | 4                                                                      | 54084         | 4507           | 1040          | 
| 1456920996  | 5                                                                      | 63360         | 5280           | 1218          | 
| 1456920996  | For each additional person add:                                        | 9288          | 774            | 179           | 
| 1456920996  | Note: Income Levels are awaiting 2016 updates pending Federal approval |               |                |               | 
```