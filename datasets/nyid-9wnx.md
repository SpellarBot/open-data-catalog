# Department of Revenue Services - Tax Credits Claimed During Fiscal Year 2012-13

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-revenue-services-tax-credits-claimed-during-fiscal-year-2012-13) |
| Metadata | [Link](https://data.ct.gov/api/views/nyid-9wnx) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/nyid-9wnx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/nyid-9wnx/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | nyid-9wnx |
| Name | Department of Revenue Services - Tax Credits Claimed During Fiscal Year 2012-13 |
| Attribution | Department of Economic and Community Development |
| Category | Business |
| Tags | executive order 38, drs, department of revenue services, tax, tax credits, tax credits claimed, decd, department of economic and community development |
| Created | 2014-03-21T18:51:40Z |
| Publication Date | 2014-03-25T19:17:27Z |

## Description

Department of Revenue Services Tax Credits Claimed during fiscal year 2012-13 (July 1, 2012 through June 30, 2013) Corporation Business, Insurance Premiums and Public Service Companies Tax Returns

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
| Yes      | numeric metric | total_credits_claimed    | Total Credits Claimed    | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nyid-9wnx d:2012-01-01T00:00:00.000Z t:type_of_credit="Digital Animation" m:total_credits_claimed=16935372 m:count2=49 m:count1=3 m:corporation_business_tax=3602813 m:insurance_premiums_taxes=13332559 m:total_count=52

series e:nyid-9wnx d:2012-01-01T00:00:00.000Z t:type_of_credit="Electronic Data Processing" m:total_credits_claimed=24485857 m:public_service_companies=4697361 m:count2=37 m:count1=1193 m:corporation_business_tax=11093917 m:insurance_premiums_taxes=8694579 m:total_count=1232 m:count3=2

series e:nyid-9wnx d:2012-01-01T00:00:00.000Z t:type_of_credit="Film Production" m:total_credits_claimed=52790639 m:count2=24 m:count1=21 m:corporation_business_tax=18959058 m:insurance_premiums_taxes=33831581 m:total_count=45
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

metric m:total_credits_claimed p:integer l:"Total Credits Claimed" t:dataTypeName=money

entity e:nyid-9wnx l:"Department of Revenue Services - Tax Credits Claimed During Fiscal Year 2012-13" t:attribution="Department of Economic and Community Development" t:url=https://data.ct.gov/api/views/nyid-9wnx

property e:nyid-9wnx t:meta.view v:id=nyid-9wnx v:category=Business v:averageRating=0 v:name="Department of Revenue Services - Tax Credits Claimed During Fiscal Year 2012-13" v:attribution="Department of Economic and Community Development"

property e:nyid-9wnx t:meta.view.owner v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:displayName="Kara Sene"

property e:nyid-9wnx t:meta.view.tableauthor v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:roleName=editor v:displayName="Kara Sene"
```

## Top Records

```ls
| type_of_credit                         | count1 | corporation_business_tax | count2 | insurance_premiums_taxes | count3 | public_service_companies | total_count | total_credits_claimed | 
| ====================================== | ====== | ======================== | ====== | ======================== | ====== | ======================== | =========== | ===================== | 
| Digital Animation                      | 3      | 3602813                  | 49     | 13332559                 |        |                          | 52          | 16935372              | 
| Electronic Data Processing             | 1193   | 11093917                 | 37     | 8694579                  | 2      | 4697361                  | 1232        | 24485857              | 
| Film Production                        | 21     | 18959058                 | 24     | 33831581                 |        |                          | 45          | 52790639              | 
| Film Production Infrastructure         | 1      | 525581                   | 13     | 793426                   |        |                          | 14          | 1319007               | 
| Fixed Capital                          | 1791   | 68144853                 |        |                          |        |                          | 1791        | 68144853              | 
| Job Expansion                          | 14     | 76844                    | 2      | 196593                   |        |                          | 16          | 273437                | 
| Research and Development               | 130    | 4804654                  |        |                          |        |                          | 130         | 4804654               | 
| Research and Experimentation           | 165    | 15231553                 |        |                          |        |                          | 165         | 15231553              | 
| Urban and Industrial Site Reinvestment | 13     | 8652245                  | 9      | 1434772                  | 0      | 0                        | 22          | 10087017              | 
```