# Department of Revenue Services - Tax Credits Claimed For 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-revenue-services-tax-credits-claimed-for-2010) |
| Metadata | [Link](https://data.ct.gov/api/views/3hed-rxb7) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/3hed-rxb7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/3hed-rxb7/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 3hed-rxb7 |
| Name | Department of Revenue Services - Tax Credits Claimed For 2010 |
| Attribution | Department of Economic and Community Development |
| Category | Business |
| Tags | executive order 38, drs, department of revenue services, tax, tax credits, tax credits claimed, decd, department of economic and community development |
| Created | 2014-03-21T18:06:18Z |
| Publication Date | 2014-03-25T19:19:45Z |

## Description

Department of Revenue Services Tax Credits Claimed on 2010 Corporation Business, Insurance Premiums and Public Service Companies Tax Returns

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
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3hed-rxb7 d:2010-01-01T00:00:00.000Z t:type_of_credit="Digital Animation" m:total_amount_of_credits_claimed=12822107 m:count2=11 m:total_number_of_credits=13 m:count1=2 m:corporation_business_tax=1743055 m:insurance_premiums_taxes=11079052

series e:3hed-rxb7 d:2010-01-01T00:00:00.000Z t:type_of_credit="Electronic Data Processing" m:total_amount_of_credits_claimed=31472043 m:public_service_companies=5459891 m:count2=37 m:total_number_of_credits=1276 m:count1=1234 m:corporation_business_tax=10930347 m:insurance_premiums_taxes=15081805 m:count3=5

series e:3hed-rxb7 d:2010-01-01T00:00:00.000Z t:type_of_credit="Film Production" m:total_amount_of_credits_claimed=49524994 m:count2=32 m:total_number_of_credits=35 m:count1=3 m:corporation_business_tax=1926102 m:insurance_premiums_taxes=47598892
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

entity e:3hed-rxb7 l:"Department of Revenue Services - Tax Credits Claimed For 2010" t:attribution="Department of Economic and Community Development" t:url=https://data.ct.gov/api/views/3hed-rxb7

property e:3hed-rxb7 t:meta.view v:id=3hed-rxb7 v:category=Business v:averageRating=0 v:name="Department of Revenue Services - Tax Credits Claimed For 2010" v:attribution="Department of Economic and Community Development"

property e:3hed-rxb7 t:meta.view.owner v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:displayName="Kara Sene"

property e:3hed-rxb7 t:meta.view.tableauthor v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:roleName=editor v:displayName="Kara Sene"
```

## Top Records

```ls
| type_of_credit                         | count1 | corporation_business_tax | count2 | insurance_premiums_taxes | count3 | public_service_companies | total_number_of_credits | total_amount_of_credits_claimed | 
| ====================================== | ====== | ======================== | ====== | ======================== | ====== | ======================== | ======================= | =============================== | 
| Digital Animation                      | 2      | 1743055                  | 11     | 11079052                 |        |                          | 13                      | 12822107                        | 
| Electronic Data Processing             | 1234   | 10930347                 | 37     | 15081805                 | 5      | 5459891                  | 1276                    | 31472043                        | 
| Film Production                        | 3      | 1926102                  | 32     | 47598892                 |        |                          | 35                      | 49524994                        | 
| Film Production Infrastructure         | 1      | 422564                   | 21     | 5634860                  |        |                          | 22                      | 6057424                         | 
| Fixed Capital                          | 1821   | 79475794                 |        |                          |        |                          | 1821                    | 79475794                        | 
| Research and Development               | 153    | 4585699                  |        |                          |        |                          | 153                     | 4585699                         | 
| Research and Experimentation           | 158    | 14798423                 |        |                          |        |                          | 158                     | 14798423                        | 
| Urban and Industrial Site Reinvestment | 13     | 9831021                  | 5      | 5402177                  | 0      | 0                        | 18                      | 15233198                        | 
```