# Department of Revenue Services - Tax Credits Claimed For 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-revenue-services-tax-credits-claimed-for-2009) |
| Metadata | [Link](https://data.ct.gov/api/views/ezba-7ycx) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/ezba-7ycx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/ezba-7ycx/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | ezba-7ycx |
| Name | Department of Revenue Services - Tax Credits Claimed For 2009 |
| Attribution | Department of Economic and Community Development |
| Category | Business |
| Tags | executive order 38, drs, department of revenue services, tax, tax credits, tax credits claimed, decd, department of economic and community development |
| Created | 2014-03-21T18:17:18Z |
| Publication Date | 2014-03-25T19:18:53Z |

## Description

Department of Revenue Services Tax Credits Claimed on 2009 Corporation Business, Insurance Premiums and Public Service Companies Tax Returns

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
| Yes      | numeric metric | public_service_companies        | Public Service Companies        | money     | money       |
| Yes      | numeric metric | total_number_of_credits         | Total Number of Credits         | number    | number      |
| Yes      | numeric metric | total_amount_of_credits_claimed | Total Amount of Credits Claimed | money     | money       |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ezba-7ycx d:2009-01-01T00:00:00.000Z t:type_of_credit="Digital Animation" m:total_amount_of_credits_claimed=9541762 m:count2=9 m:total_number_of_credits=10 m:count1=1 m:corporation_business_tax=928726 m:insurance_premiums_taxes=8613036

series e:ezba-7ycx d:2009-01-01T00:00:00.000Z t:type_of_credit="Electronic Data Processing" m:total_amount_of_credits_claimed=28524705 m:public_service_companies=3518073 m:count2=40 m:total_number_of_credits=1322 m:count1=1278 m:corporation_business_tax=9442103 m:insurance_premiums_taxes=15564529 m:count3=4

series e:ezba-7ycx d:2009-01-01T00:00:00.000Z t:type_of_credit="Film Production" m:total_amount_of_credits_claimed=34980896 m:count2=36 m:total_number_of_credits=37 m:count1=1 m:corporation_business_tax=2963504 m:insurance_premiums_taxes=32017392
```

## Meta Commands

```ls
metric m:count1 p:integer l:Count1 t:dataTypeName=number

metric m:corporation_business_tax p:integer l:"Corporation Business Tax" t:dataTypeName=money

metric m:count2 p:integer l:Count2 t:dataTypeName=number

metric m:insurance_premiums_taxes p:integer l:"Insurance Premiums Taxes" t:dataTypeName=money

metric m:count3 p:integer l:Count3 t:dataTypeName=number

metric m:public_service_companies p:integer l:"Public Service Companies" t:dataTypeName=money

metric m:total_number_of_credits p:integer l:"Total Number of Credits" t:dataTypeName=number

metric m:total_amount_of_credits_claimed p:integer l:"Total Amount of Credits Claimed" t:dataTypeName=money

entity e:ezba-7ycx l:"Department of Revenue Services - Tax Credits Claimed For 2009" t:attribution="Department of Economic and Community Development" t:url=https://data.ct.gov/api/views/ezba-7ycx

property e:ezba-7ycx t:meta.view v:id=ezba-7ycx v:category=Business v:averageRating=0 v:name="Department of Revenue Services - Tax Credits Claimed For 2009" v:attribution="Department of Economic and Community Development"

property e:ezba-7ycx t:meta.view.owner v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:displayName="Kara Sene"

property e:ezba-7ycx t:meta.view.tableauthor v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:roleName=editor v:displayName="Kara Sene"
```

## Top Records

```ls
| type_of_credit                         | count1 | corporation_business_tax | count2 | insurance_premiums_taxes | count3 | public_service_companies | total_number_of_credits | total_amount_of_credits_claimed | 
| ====================================== | ====== | ======================== | ====== | ======================== | ====== | ======================== | ======================= | =============================== | 
| Digital Animation                      | 1      | 928726                   | 9      | 8613036                  |        |                          | 10                      | 9541762                         | 
| Electronic Data Processing             | 1278   | 9442103                  | 40     | 15564529                 | 4      | 3518073                  | 1322                    | 28524705                        | 
| Film Production                        | 1      | 2963504                  | 36     | 32017392                 |        |                          | 37                      | 34980896                        | 
| Film Production Infrastructure         | 9      | 611376                   | 11     | 5159840                  |        |                          | 20                      | 5771216                         | 
| Fixed Capital                          | 1805   | 80814859                 |        |                          |        |                          | 1805                    | 80814859                        | 
| Research and Development               | 155    | 5809064                  |        |                          |        |                          | 155                     | 5809064                         | 
| Research and Experimentation           | 161    | 15389000                 |        |                          |        |                          | 161                     | 15389000                        | 
| Urban and Industrial Site Reinvestment | 11     | 3761601                  | 7      | 6725928                  |        | 0                        | 18                      | 10487529                        | 
```