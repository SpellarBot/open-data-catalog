# Department of Revenue Services - Tax Credit Carryforwards from Fiscal Year 2012-13 Filings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-revenue-services-tax-credit-carryforwards-from-fiscal-year-2012-13-filings) |
| Metadata | [Link](https://data.ct.gov/api/views/ig6u-cthx) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/ig6u-cthx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/ig6u-cthx/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | ig6u-cthx |
| Name | Department of Revenue Services - Tax Credit Carryforwards from Fiscal Year 2012-13 Filings |
| Attribution | Department of Economic and Community Development |
| Category | Business |
| Tags | executive order 38, drs, department of revenue services, tax, tax credits, tax credits claimed, tax credit carry forward, decd, department of economic and community development |
| Created | 2014-03-21T19:00:51Z |
| Publication Date | 2014-03-25T19:17:05Z |

## Description

Department of Revenue Services Tax Credit Carryforwards from Fiscal Year 2012-2013 (July 1, 2012 through June 30, 2013) Filings

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | type_of_credit           | Type of Credit           | text      | text        |
| Yes      | numeric metric | count1                   | Count1                   | number    | number      |
| Yes      | numeric metric | corporation_business_tax | Corporation Business Tax | money     | money       |
| Yes      | numeric metric | count2                   | Count2                   | number    | number      |
| Yes      | numeric metric | insurance_premiums_taxes | Insurance Premiums Taxes | money     | money       |
| Yes      | numeric metric | count3                   | Count3                   | number    | number      |
| Yes      | numeric metric | public_service_companies | Public Service Companies | money     | money       |
| Yes      | numeric metric | total_count              | Total Count              | number    | number      |
| Yes      | numeric metric | total_carryforwards      | Total Carryforwards      | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ig6u-cthx d:2012-01-01T00:00:00.000Z t:type_of_credit="Electronic Data Processing" m:total_carryforwards=109595424 m:public_service_companies=0 m:count2=15 m:count1=1547 m:corporation_business_tax=92495412 m:insurance_premiums_taxes=17100012 m:total_count=1562 m:count3=0

series e:ig6u-cthx d:2012-01-01T00:00:00.000Z t:type_of_credit="Fixed Capital" m:total_carryforwards=295985217 m:count1=1974 m:corporation_business_tax=295985217 m:total_count=1974

series e:ig6u-cthx d:2012-01-01T00:00:00.000Z t:type_of_credit="Job Expansion" m:total_carryforwards=0 m:count2=0 m:count1=0 m:corporation_business_tax=0 m:insurance_premiums_taxes=0
```

## Meta Commands

```ls
metric m:count1 p:integer l:Count1 t:dataTypeName=number

metric m:corporation_business_tax p:integer l:"Corporation Business Tax" t:dataTypeName=money

metric m:count2 p:integer l:Count2 t:dataTypeName=number

metric m:insurance_premiums_taxes p:integer l:"Insurance Premiums Taxes" t:dataTypeName=money

metric m:count3 p:integer l:Count3 t:dataTypeName=number

metric m:public_service_companies p:integer l:"Public Service Companies" t:dataTypeName=money

metric m:total_count p:integer l:"Total Count" t:dataTypeName=number

metric m:total_carryforwards p:integer l:"Total Carryforwards" t:dataTypeName=money

entity e:ig6u-cthx l:"Department of Revenue Services - Tax Credit Carryforwards from Fiscal Year 2012-13 Filings" t:attribution="Department of Economic and Community Development" t:url=https://data.ct.gov/api/views/ig6u-cthx

property e:ig6u-cthx t:meta.view v:id=ig6u-cthx v:category=Business v:averageRating=0 v:name="Department of Revenue Services - Tax Credit Carryforwards from Fiscal Year 2012-13 Filings" v:attribution="Department of Economic and Community Development"

property e:ig6u-cthx t:meta.view.owner v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:displayName="Kara Sene"

property e:ig6u-cthx t:meta.view.tableauthor v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:roleName=editor v:displayName="Kara Sene"
```

## Top Records

```ls
| type_of_credit                         | count1 | corporation_business_tax | count2 | insurance_premiums_taxes | count3 | public_service_companies | total_count | total_carryforwards | 
| ====================================== | ====== | ======================== | ====== | ======================== | ====== | ======================== | =========== | =================== | 
| Electronic Data Processing             | 1547   | 92495412                 | 15     | 17100012                 | 0      | 0                        | 1562        | 109595424           | 
| Fixed Capital                          | 1974   | 295985217                |        |                          |        |                          | 1974        | 295985217           | 
| Job Expansion                          | 0      | 0                        | 0      | 0                        |        |                          |             | 0                   | 
| Research and Development               | 324    | 1425934351               |        |                          |        |                          | 324         | 1425934351          | 
| Research and Experimentation           | 223    | 536604048                |        |                          |        |                          | 223         | 536604048           | 
| Urban and Industrial Site Reinvestment | 10     | 14101858                 | 1      | 399446                   | 0      | 0                        | 11          | 14501304            | 
```