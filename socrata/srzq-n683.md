# Department of Revenue Servies Tax Credits Claimed for 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-revenue-servies-tax-credits-claimed-for-2013) |
| Metadata | [Link](https://data.ct.gov/api/views/srzq-n683) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/srzq-n683/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/srzq-n683/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | srzq-n683 |
| Name | Department of Revenue Servies Tax Credits Claimed for 2013 |
| Attribution | Department of Revenue Services |
| Category | Business |
| Tags | executive order 38, drs, department of revenue services, tax, tax credits, tax credits claimed, decd, department of economic and community development |
| Created | 2016-04-01T20:37:51Z |
| Publication Date | 2016-04-01T20:39:46Z |

## Description

Tax Credits Claimed on 2013 Corporation Business, Insurance Premiums, Public Service Companies and Hospital Net Patient Revenue Tax Returns

## Columns

```ls
| Included | Schema Type    | Field Name                                                  | Name                                                          | Data Type | Render Type |
| ======== | ============== | =========================================================== | ============================================================= | ========= | =========== |
| Yes      | series tag     | type_of_credit                                              | Type of Credit                                                | text      | text        |
| Yes      | numeric metric | count1                                                      | Count1                                                        | number    | number      |
| Yes      | numeric metric | corporation_business_tax                                    | Corporation Business Tax                                      | number    | number      |
| Yes      | numeric metric | count2                                                      | Count2                                                        | number    | number      |
| Yes      | series tag     | insurance_premiums_taxes                                    | Insurance Premiums Taxes                                      | text      | text        |
| Yes      | numeric metric | count3                                                      | Count3                                                        | number    | number      |
| Yes      | series tag     | public_service_companies_hospital_net_patient_revenue_taxes | Public Service Companies & Hospital Net Patient Revenue Taxes | text      | text        |
| Yes      | numeric metric | total_number_of_credits                                     | Total Number of Credits                                       | number    | number      |
| Yes      | numeric metric | total_amount_of_credits_claimed                             | Total Amount of Credits Claimed                               | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:srzq-n683 d:2013-01-01T00:00:00.000Z t:public_service_companies_hospital_net_patient_revenue_taxes=n/a t:insurance_premiums_taxes=8,565,238 t:type_of_credit="Digital Animation" m:total_amount_of_credits_claimed=9899365 m:count2=32 m:total_number_of_credits=35 m:count1=3 m:corporation_business_tax=1334127

series e:srzq-n683 d:2013-01-01T00:00:00.000Z t:public_service_companies_hospital_net_patient_revenue_taxes=210,542 t:insurance_premiums_taxes=7,486,902 t:type_of_credit="Electronic Data Processing" m:total_amount_of_credits_claimed=21969033 m:count2=34 m:total_number_of_credits=1145 m:count1=1108 m:corporation_business_tax=14271589 m:count3=3

series e:srzq-n683 d:2013-01-01T00:00:00.000Z t:public_service_companies_hospital_net_patient_revenue_taxes=n/a t:insurance_premiums_taxes=22,297,860 t:type_of_credit="Film Production" m:total_amount_of_credits_claimed=42929091 m:count2=27 m:total_number_of_credits=56 m:count1=29 m:corporation_business_tax=20631231
```

## Meta Commands

```ls
metric m:count1 p:integer l:Count1 t:dataTypeName=number

metric m:corporation_business_tax p:integer l:"Corporation Business Tax" t:dataTypeName=number

metric m:count2 p:integer l:Count2 t:dataTypeName=number

metric m:count3 p:integer l:Count3 t:dataTypeName=number

metric m:total_number_of_credits p:integer l:"Total Number of Credits" t:dataTypeName=number

metric m:total_amount_of_credits_claimed p:integer l:"Total Amount of Credits Claimed" t:dataTypeName=number

entity e:srzq-n683 l:"Department of Revenue Servies Tax Credits Claimed for 2013" t:attribution="Department of Revenue Services" t:url=https://data.ct.gov/api/views/srzq-n683

property e:srzq-n683 t:meta.view v:id=srzq-n683 v:category=Business v:averageRating=0 v:name="Department of Revenue Servies Tax Credits Claimed for 2013" v:attribution="Department of Revenue Services"

property e:srzq-n683 t:meta.view.owner v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:displayName="Kara Sene"

property e:srzq-n683 t:meta.view.tableauthor v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:roleName=editor v:displayName="Kara Sene"
```

## Top Records

```ls
| type_of_credit                         | count1 | corporation_business_tax | count2 | insurance_premiums_taxes | count3 | public_service_companies_hospital_net_patient_revenue_taxes   | total_number_of_credits | total_amount_of_credits_claimed | 
| ====================================== | ====== | ======================== | ====== | ======================== | ====== | ============================================================= | ======================= | =============================== | 
| Type of Credit                         |        |                          |        | Insurance Premiums Taxes |        | Public Service Companies & Hospital Net Patient Revenue Taxes |                         |                                 | 
| Digital Animation                      | 3      | 1334127                  | 32     | 8,565,238                |        | n/a                                                           | 35                      | 9899365                         | 
| Electronic Data Processing             | 1108   | 14271589                 | 34     | 7,486,902                | 3      | 210,542                                                       | 1145                    | 21969033                        | 
| Film Production                        | 29     | 20631231                 | 27     | 22,297,860               |        | n/a                                                           | 56                      | 42929091                        | 
| Film Production Infrastructure         | 4      | 15351283                 | 23     | 13,880,938               |        | n/a                                                           | 27                      | 29232221                        | 
| Fixed Capital                          | 1689   | 78900661                 |        | n/a                      |        | n/a                                                           | 1689                    | 78900661                        | 
| Job Expansion (JET)                    | 41     | 4894935                  | 3      | 223,291                  | 0      | 0                                                             | 44                      | 5118226                         | 
| Research and Development               | 163    | 7003450                  |        | n/a                      |        | n/a                                                           | 163                     | 7003450                         | 
| Research and Experimentation           | 205    | 19113361                 |        | n/a                      |        | n/a                                                           | 205                     | 19113361                        | 
| Urban and Industrial Site Reinvestment | 15     | 10346444                 | 11     | 4,936,470                | 7      | 33,550,000                                                    | 33                      | 48832914                        | 
```