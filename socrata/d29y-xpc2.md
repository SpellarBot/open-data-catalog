# Department of Revenue Services - Tax Credits Claimed For 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-revenue-services-tax-credits-claimed-for-2011) |
| Metadata | [Link](https://data.ct.gov/api/views/d29y-xpc2) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/d29y-xpc2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/d29y-xpc2/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | d29y-xpc2 |
| Name | Department of Revenue Services - Tax Credits Claimed For 2011 |
| Attribution | Department of Economic and Community Development |
| Category | Business |
| Tags | department of revenue services, drs, tax credits, tax credits claimed, executive order 38, decd, department of economic and community development |
| Created | 2014-03-17T14:27:52Z |
| Publication Date | 2014-03-20T19:35:03Z |

## Description

Department of Revenue Services Tax Credits Claimed on 2011 Corporation Business, Insurance Premiums and Public Service Companies Tax Returns

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
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:d29y-xpc2 d:2011-01-01T00:00:00.000Z t:type_of_credit="Digital Animation" m:total_amount_of_credits_claimed=11922965 m:count2=25 m:total_number_of_credits=28 m:count1=3 m:corporation_business_tax=3602804 m:insurance_premiums_taxes=8320161

series e:d29y-xpc2 d:2011-01-01T00:00:00.000Z t:type_of_credit="Electronic Data Processing" m:total_amount_of_credits_claimed=27608599 m:public_service_companies=8452895 m:count2=35 m:total_number_of_credits=1250 m:count1=1208 m:corporation_business_tax=10713974 m:insurance_premiums_taxes=8441730 m:count3=7

series e:d29y-xpc2 d:2011-01-01T00:00:00.000Z t:type_of_credit="Film Production" m:total_amount_of_credits_claimed=54625047 m:count2=27 m:total_number_of_credits=46 m:count1=19 m:corporation_business_tax=18561449 m:insurance_premiums_taxes=36063598
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

entity e:d29y-xpc2 l:"Department of Revenue Services - Tax Credits Claimed For 2011" t:attribution="Department of Economic and Community Development" t:url=https://data.ct.gov/api/views/d29y-xpc2

property e:d29y-xpc2 t:meta.view v:id=d29y-xpc2 v:category=Business v:averageRating=0 v:name="Department of Revenue Services - Tax Credits Claimed For 2011" v:attribution="Department of Economic and Community Development"

property e:d29y-xpc2 t:meta.view.owner v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:displayName="Kara Sene"

property e:d29y-xpc2 t:meta.view.tableauthor v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:roleName=editor v:displayName="Kara Sene"
```

## Top Records

```ls
| type_of_credit                         | count1 | corporation_business_tax | count2 | insurance_premiums_taxes | count3 | public_service_companies | total_number_of_credits | total_amount_of_credits_claimed | 
| ====================================== | ====== | ======================== | ====== | ======================== | ====== | ======================== | ======================= | =============================== | 
| Digital Animation                      | 3      | 3602804                  | 25     | 8320161                  |        |                          | 28                      | 11922965                        | 
| Electronic Data Processing             | 1208   | 10713974                 | 35     | 8441730                  | 7      | 8452895                  | 1250                    | 27608599                        | 
| Film Production                        | 19     | 18561449                 | 27     | 36063598                 |        |                          | 46                      | 54625047                        | 
| Film Production Infrastructure         | 2      | 525581                   | 5      | 1520077                  |        |                          | 7                       | 2045658                         | 
| Fixed Capital                          | 1811   | 65265476                 |        |                          |        |                          | 1811                    | 65265476                        | 
| Research and Development               | 134    | 4968847                  |        |                          |        |                          | 134                     | 4968847                         | 
| Research and Experimentation           | 164    | 14805642                 |        |                          |        |                          | 164                     | 14805642                        | 
| Urban and Industrial Site Reinvestment | 14     | 8214617                  | 15     | 5120914                  | 0      | 0                        | 29                      | 13335531                        | 
```