# Department of Revenue Services - Tax Credits Claimed For 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-revenue-services-tax-credits-claimed-for-2008) |
| Metadata | [Link](https://data.ct.gov/api/views/nmm6-jyfp) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/nmm6-jyfp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/nmm6-jyfp/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | nmm6-jyfp |
| Name | Department of Revenue Services - Tax Credits Claimed For 2008 |
| Attribution | Department of Economic and Community Development |
| Category | Business |
| Tags | executive order 38, drs, department of revenue services, tax, tax credits, tax credits claimed, decd, department of economic and community development |
| Created | 2014-03-21T18:34:22Z |
| Publication Date | 2014-03-25T19:18:37Z |

## Description

Department of Revenue Services Tax Credits Claimed on 2008 Corporation Business, Insurance Premiums and Public Service Companies Tax Returns

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type | Render Type |
| ======== | ============== | =============================== | =============================== | ========= | =========== |
| Yes      | series tag     | type_of_credit                  | Type of Credit                  | text      | text        |
| Yes      | numeric metric | count1                          | Count1                          | number    | number      |
| Yes      | numeric metric | corporation_business_tax        | Corporation Business Tax        | money     | money       |
| Yes      | numeric metric | count2                          | Count2                          | number    | number      |
| Yes      | numeric metric | insurance_premiums_taxes        | Insurance Premiums Taxes        | money     | money       |
| Yes      | numeric metric | count3                          | Count3                          | number    | number      |
| Yes      | numeric metric | public_service_companies        | Public Service Companies        | number    | number      |
| Yes      | numeric metric | total_number_of_credits         | Total Number of Credits         | number    | number      |
| Yes      | numeric metric | total_amount_of_credits_claimed | Total Amount of Credits Claimed | money     | money       |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nmm6-jyfp d:2008-01-01T00:00:00.000Z t:type_of_credit="Digital Animation" m:total_amount_of_credits_claimed=0 m:count2=0 m:total_number_of_credits=0 m:count1=0 m:corporation_business_tax=0 m:insurance_premiums_taxes=0

series e:nmm6-jyfp d:2008-01-01T00:00:00.000Z t:type_of_credit="Electronic Data Processing" m:total_amount_of_credits_claimed=30643032 m:public_service_companies=1316200 m:count2=39 m:total_number_of_credits=1413 m:count1=1371 m:corporation_business_tax=13025091 m:insurance_premiums_taxes=16301741 m:count3=3

series e:nmm6-jyfp d:2008-01-01T00:00:00.000Z t:type_of_credit="Film Production" m:total_amount_of_credits_claimed=63066399 m:count2=33 m:total_number_of_credits=44 m:count1=11 m:corporation_business_tax=12923918 m:insurance_premiums_taxes=50142481
```

## Meta Commands

```ls
metric m:count1 p:integer l:Count1 t:dataTypeName=number

metric m:corporation_business_tax p:integer l:"Corporation Business Tax" t:dataTypeName=money

metric m:count2 p:integer l:Count2 t:dataTypeName=number

metric m:insurance_premiums_taxes p:integer l:"Insurance Premiums Taxes" t:dataTypeName=money

metric m:count3 p:integer l:Count3 t:dataTypeName=number

metric m:public_service_companies p:integer l:"Public Service Companies" t:dataTypeName=number

metric m:total_number_of_credits p:integer l:"Total Number of Credits" t:dataTypeName=number

metric m:total_amount_of_credits_claimed p:integer l:"Total Amount of Credits Claimed" t:dataTypeName=money

entity e:nmm6-jyfp l:"Department of Revenue Services - Tax Credits Claimed For 2008" t:attribution="Department of Economic and Community Development" t:url=https://data.ct.gov/api/views/nmm6-jyfp

property e:nmm6-jyfp t:meta.view v:id=nmm6-jyfp v:category=Business v:averageRating=0 v:name="Department of Revenue Services - Tax Credits Claimed For 2008" v:attribution="Department of Economic and Community Development"

property e:nmm6-jyfp t:meta.view.owner v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:displayName="Kara Sene"

property e:nmm6-jyfp t:meta.view.tableauthor v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:roleName=editor v:displayName="Kara Sene"
```

## Top Records

```ls
| type_of_credit                         | count1 | corporation_business_tax | count2 | insurance_premiums_taxes | count3 | public_service_companies | total_number_of_credits | total_amount_of_credits_claimed | 
| ====================================== | ====== | ======================== | ====== | ======================== | ====== | ======================== | ======================= | =============================== | 
| Digital Animation                      | 0      | 0                        | 0      | 0                        |        |                          | 0                       | 0                               | 
| Electronic Data Processing             | 1371   | 13025091                 | 39     | 16301741                 | 3      | 1316200                  | 1413                    | 30643032                        | 
| Film Production                        | 11     | 12923918                 | 33     | 50142481                 |        |                          | 44                      | 63066399                        | 
| Film Production Infrastructure         | 2      | 323                      | 5      | 1596465                  |        |                          | 7                       | 1596788                         | 
| Fixed Capital                          | 2076   | 69555015                 |        |                          |        |                          | 2076                    | 69555015                        | 
| Research and Development               | 130    | 4827816                  |        |                          |        |                          | 130                     | 4827816                         | 
| Research and Experimentation           | 153    | 20564948                 |        |                          |        |                          | 153                     | 20564948                        | 
| Urban and Industrial Site Reinvestment | 8      | 1850045                  | 4      | 6775397                  | 0      | 0                        | 12                      | 8625442                         | 
```