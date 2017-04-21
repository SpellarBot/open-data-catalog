# Prenatal care services (monthly income levels)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/prenatal-care-services-monthly-income-levels-5b645) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/s2zm-f47y) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/s2zm-f47y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/s2zm-f47y/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | s2zm-f47y |
| Name | Prenatal care services (monthly income levels) |
| Attribution | Human Resources Administration (HRA) |
| Category | City Government |
| Tags | jobs and economic mobility, human resources administration, hra, prenatal |
| Created | 2013-03-19T18:03:36Z |
| Publication Date | 2016-03-02T20:34:47Z |

## Description

This table represents details of Prenatal Care Services program. Prenatal Care Services through Medicaid is a comprehensive prenatal care program that offers complete pregnancy care and other health services to women and teens who live in New York State and meet income guidelines. Health insurance is available for pregnant women regardless of their immigration status. Under Prenatal Care Services, pregnant women receive prenatal health services, such as lab tests, HIV tests, nutrition screenings, and other services related to their pregnancy and for at least two months after delivery.  Babies receive health care services for at least one year after birth.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name               | Data Type | Render Type |
| ======== | ============== | ============== | ================== | ========= | =========== |
| No       | time           | :updated_at    | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | household_size | Household Size     | text      | text        |
| Yes      | numeric metric | yearly_income  | Yearly Income ($)  | number    | text        |
| Yes      | numeric metric | monthly_income | Monthly Income ($) | number    | text        |
| Yes      | numeric metric | weekly_income  | Weekly Income ($)  | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:s2zm-f47y d:2016-03-02T12:32:51.000Z t:household_size=2 m:yearly_income=35532 m:weekly_income=683 m:monthly_income=2961

series e:s2zm-f47y d:2016-03-02T12:32:51.000Z t:household_size=3 m:yearly_income=44808 m:weekly_income=862 m:monthly_income=3734

series e:s2zm-f47y d:2016-03-02T12:32:51.000Z t:household_size=4 m:yearly_income=54084 m:weekly_income=1040 m:monthly_income=4507
```

## Meta Commands

```ls
metric m:yearly_income p:integer l:"Yearly Income ($)" t:dataTypeName=number

metric m:monthly_income p:integer l:"Monthly Income ($)" t:dataTypeName=number

metric m:weekly_income p:integer l:"Weekly Income ($)" t:dataTypeName=number

entity e:s2zm-f47y l:"Prenatal care services (monthly income levels)" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/s2zm-f47y

property e:s2zm-f47y t:meta.view v:id=s2zm-f47y v:category="City Government" v:attributionLink=http://www.nyc.gov/html/hia/html/public_insurance/pregnant.shtml v:averageRating=0 v:name="Prenatal care services (monthly income levels)" v:attribution="Human Resources Administration (HRA)"

property e:s2zm-f47y t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:s2zm-f47y t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | household_size                                                         | yearly_income | monthly_income | weekly_income | 
| =========== | ====================================================================== | ============= | ============== | ============= | 
| 1456921971  | 2                                                                      | 35532         | 2961           | 683           | 
| 1456921971  | 3                                                                      | 44808         | 3734           | 862           | 
| 1456921971  | 4                                                                      | 54084         | 4507           | 1040          | 
| 1456921971  | 5                                                                      | 63360         | 5280           | 1218          | 
| 1456921971  | For each additional person add:                                        | 9288          | 774            | 179           | 
| 1456921971  | Note: Income Levels are awaiting 2016 updates pending Federal approval |               |                |               | 
```