# Adult family health plus levels

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adult-family-health-plus-levels-82909) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/2enn-s52j) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/2enn-s52j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/2enn-s52j/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 2enn-s52j |
| Name | Adult family health plus levels |
| Attribution | Human Resources Administration (HRA) |
| Category | City Government |
| Tags | jobs and economic mobility, human resources administration, hra, health, plus, adult |
| Created | 2013-03-19T18:07:23Z |
| Publication Date | 2013-06-21T20:09:58Z |

## Description

This table represents details of Family Health Plus insurance program. Family Health Plus is a public health insurance program for adults between the ages of 19 and 64 who do not have health insurance - either on their own or through their employers - but have incomes too high to qualify for Medicaid.  The Family Health Plus Premium Assistance Program is available to help eligible lower-income employees and their families participate in their employer?s health insurance plan.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name               | Data Type | Render Type |
| ======== | ============== | ============== | ================== | ========= | =========== |
| No       | time           | :updated_at    | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | family_size    | Family Size        | text      | text        |
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
series e:2enn-s52j d:2013-03-19T11:07:30.000Z t:family_size="Single Adult and 19 - 20 Years Old
living alone" m:yearly_income=11172 m:weekly_income=215 m:monthly_income=931

series e:2enn-s52j d:2013-03-19T11:07:30.000Z t:family_size="Couples with No Childrens" m:yearly_income=15132 m:weekly_income=291 m:monthly_income=1261

series e:2enn-s52j d:2013-03-19T11:07:30.000Z t:family_size=1 m:yearly_income=16764 m:weekly_income=322 m:monthly_income=1397
```

## Meta Commands

```ls
metric m:yearly_income p:integer l:"Yearly Income ($)" t:dataTypeName=number

metric m:monthly_income p:integer l:"Monthly Income ($)" t:dataTypeName=number

metric m:weekly_income p:integer l:"Weekly Income ($)" t:dataTypeName=number

entity e:2enn-s52j l:"Adult family health plus levels" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/2enn-s52j

property e:2enn-s52j t:meta.view v:id=2enn-s52j v:category="City Government" v:attributionLink=http://www.nyc.gov/html/hia/html/public_insurance/adults.shtml v:averageRating=0 v:name="Adult family health plus levels" v:attribution="Human Resources Administration (HRA)"

property e:2enn-s52j t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:2enn-s52j t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | family_size                                     | yearly_income | monthly_income | weekly_income | 
| =========== | =============================================== | ============= | ============== | ============= | 
| 1363691250  | Single Adult and 19 - 20 Years Old living alone | 11172         | 931            | 215           | 
| 1363691250  | Couples with No Childrens                       | 15132         | 1261           | 291           | 
| 1363691250  | 1                                               | 16764         | 1397           | 322           | 
| 1363691250  | 2                                               | 22704         | 1892           | 437           | 
| 1363691250  | 3                                               | 28644         | 2387           | 551           | 
| 1363691250  | 4                                               | 34584         | 2882           | 665           | 
| 1363691250  | 5                                               | 40524         | 3377           | 779           | 
| 1363691250  | For each additional person add                  | 5940          | 495            | 114           | 
```