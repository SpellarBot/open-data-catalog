# Local Government Expenditures - Fiscal Year 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/local-government-expenditures-fiscal-year-2010-29b1e) |
| Metadata | [Link](https://data.maryland.gov/api/views/sem9-aqf8) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/sem9-aqf8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/sem9-aqf8/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | sem9-aqf8 |
| Name | Local Government Expenditures - Fiscal Year 2010 |
| Attribution | Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Servic... |
| Category | Budget |
| Tags | expenditures, budget, county, municipality, counties, municipalities, spending, dls, department of legislative services |
| Created | 2014-08-08T15:20:49Z |
| Publication Date | 2014-08-08T15:29:47Z |

## Description

Municipal expenditures by county for FY2010. Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | county                 | County                 | text      | text        |
| Yes      | numeric metric | county_expenditures    | County Expenditures    | money     | money       |
| Yes      | numeric metric | municipal_expenditures | Municipal Expenditures | money     | money       |
| Yes      | numeric metric | total_expenditures     | Total Expenditures     | money     | money       |
| Yes      | numeric metric | percent_county         | Percent County         | percent   | percent     |
| Yes      | numeric metric | percent_municipal      | Percent Municipal      | percent   | percent     |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:sem9-aqf8 d:2010-01-01T00:00:00.000Z t:county=Allegany m:municipal_expenditures=55100000 m:county_expenditures=261200000 m:total_expenditures=316300000 m:percent_county=82.6 m:percent_municipal=17.4

series e:sem9-aqf8 d:2010-01-01T00:00:00.000Z t:county="Anne Arundel" m:municipal_expenditures=107100000 m:county_expenditures=2077700000 m:total_expenditures=2184800000 m:percent_county=95.1 m:percent_municipal=4.9

series e:sem9-aqf8 d:2010-01-01T00:00:00.000Z t:county="Baltimore City" m:municipal_expenditures=0 m:county_expenditures=3580800000 m:total_expenditures=3580800000 m:percent_county=100 m:percent_municipal=0
```

## Meta Commands

```ls
metric m:county_expenditures p:long l:"County Expenditures" t:dataTypeName=money

metric m:municipal_expenditures p:integer l:"Municipal Expenditures" t:dataTypeName=money

metric m:total_expenditures p:long l:"Total Expenditures" t:dataTypeName=money

metric m:percent_county p:float l:"Percent County" t:dataTypeName=percent

metric m:percent_municipal p:float l:"Percent Municipal" t:dataTypeName=percent

entity e:sem9-aqf8 l:"Local Government Expenditures - Fiscal Year 2010" t:attribution="Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)" t:url=https://data.maryland.gov/api/views/sem9-aqf8

property e:sem9-aqf8 t:meta.view v:id=sem9-aqf8 v:category=Budget v:attributionLink=http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf v:averageRating=0 v:name="Local Government Expenditures - Fiscal Year 2010" v:attribution="Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)"

property e:sem9-aqf8 t:meta.view.license v:name="Public Domain"

property e:sem9-aqf8 t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:sem9-aqf8 t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| county           | county_expenditures | municipal_expenditures | total_expenditures | percent_county | percent_municipal | 
| ================ | =================== | ====================== | ================== | ============== | ================= | 
| Allegany         | 261200000           | 55100000               | 316300000          | 82.60          | 17.40             | 
| Anne Arundel     | 2077700000          | 107100000              | 2184800000         | 95.10          | 4.90              | 
| Baltimore City   | 3580800000          | 0                      | 3580800000         | 100.00         | 0.00              | 
| Baltimore County | 3061600000          | 0                      | 3061600000         | 100.00         | 0.00              | 
| Calvert          | 404600000           | 10900000               | 415500000          | 97.40          | 2.60              | 
| Caroline         | 132000000           | 13400000               | 145400000          | 90.80          | 9.20              | 
| Carroll          | 684200000           | 48700000               | 733000000          | 93.30          | 6.70              | 
| Cecil            | 356700000           | 34200000               | 390900000          | 91.30          | 8.70              | 
| Charles          | 681100000           | 14300000               | 695300000          | 97.90          | 2.10              | 
| Dorchester       | 139100000           | 23500000               | 162600000          | 85.50          | 14.50             | 
```