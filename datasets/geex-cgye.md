# Department of Revenue Services- Tax Credits Claimed For FY 2011-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-revenue-services-tax-credits-claimed-for-fy-2011-2012) |
| Metadata | [Link](https://data.ct.gov/api/views/geex-cgye) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/geex-cgye/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/geex-cgye/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | geex-cgye |
| Name | Department of Revenue Services- Tax Credits Claimed For FY 2011-2012 |
| Category | Business |
| Tags | executive order 38, drs, department of revenue services, tax, tax credits, tax credits claimed, decd, department of economic and community development |
| Created | 2015-03-03T19:46:18Z |
| Publication Date | 2015-03-03T19:52:06Z |

## Description

Department of Revenue Services Tax Credits Claimed during fiscal year 2011-12 (July 1, 2011 through June 30, 2012) Corporation Business, Insurance Premiums and Public Service Companies Tax Returns

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
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:geex-cgye d:2011-01-01T00:00:00.000Z t:public_service_companies_hospital_net_patient_revenue_taxes=n/a t:insurance_premiums_taxes=23,962,856 t:type_of_credit="Digital Animation" m:total_amount_of_credits_claimed=24647091 m:count2=59 m:total_number_of_credits=61 m:count1=2 m:corporation_business_tax=684235

series e:geex-cgye d:2011-01-01T00:00:00.000Z t:public_service_companies_hospital_net_patient_revenue_taxes=10,216,288 t:insurance_premiums_taxes=8,696,177 t:type_of_credit="Electronic Data Processing" m:total_amount_of_credits_claimed=29637821 m:count2=38 m:total_number_of_credits=1169 m:count1=1128 m:corporation_business_tax=10725356 m:count3=3

series e:geex-cgye d:2011-01-01T00:00:00.000Z t:public_service_companies_hospital_net_patient_revenue_taxes=n/a t:insurance_premiums_taxes=19,260,601 t:type_of_credit="Film Production" m:total_amount_of_credits_claimed=45057232 m:count2=26 m:total_number_of_credits=53 m:count1=27 m:corporation_business_tax=25796631
```

## Meta Commands

```ls
metric m:count1 p:integer l:Count1 t:dataTypeName=number

metric m:corporation_business_tax p:integer l:"Corporation Business Tax" t:dataTypeName=number

metric m:count2 p:integer l:Count2 t:dataTypeName=number

metric m:count3 p:integer l:Count3 t:dataTypeName=number

metric m:total_number_of_credits p:integer l:"Total Number of Credits" t:dataTypeName=number

metric m:total_amount_of_credits_claimed p:integer l:"Total Amount of Credits Claimed" t:dataTypeName=number

entity e:geex-cgye l:"Department of Revenue Services- Tax Credits Claimed For FY 2011-2012" t:url=https://data.ct.gov/api/views/geex-cgye

property e:geex-cgye t:meta.view v:id=geex-cgye v:category=Business v:averageRating=0 v:name="Department of Revenue Services- Tax Credits Claimed For FY 2011-2012"

property e:geex-cgye t:meta.view.owner v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:displayName="Kara Sene"

property e:geex-cgye t:meta.view.tableauthor v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:roleName=editor v:displayName="Kara Sene"
```

## Top Records

```ls
| type_of_credit                         | count1 | corporation_business_tax | count2 | insurance_premiums_taxes | count3 | public_service_companies_hospital_net_patient_revenue_taxes | total_number_of_credits | total_amount_of_credits_claimed | 
| ====================================== | ====== | ======================== | ====== | ======================== | ====== | =========================================================== | ======================= | =============================== | 
| Digital Animation                      | 2      | 684235                   | 59     | 23,962,856               |        | n/a                                                         | 61                      | 24647091                        | 
| Electronic Data Processing             | 1128   | 10725356                 | 38     | 8,696,177                | 3      | 10,216,288                                                  | 1169                    | 29637821                        | 
| Film Production                        | 27     | 25796631                 | 26     | 19,260,601               |        | n/a                                                         | 53                      | 45057232                        | 
| Film Production Infrastructure         | 3      | 1477765                  | 16     | 5,384,948                |        | n/a                                                         | 19                      | 6862713                         | 
| Fixed Capital                          | 1727   | 63125737                 |        | n/a                      |        | n/a                                                         | 1727                    | 63125737                        | 
| Job Expansion (JET)                    | 111    | 2223373                  | 2      | 196,593                  |        |                                                             | 113                     | 2419966                         | 
| Research and Development               | 145    | 5392832                  |        | n/a                      |        | n/a                                                         | 145                     | 5392832                         | 
| Research and Experimentation           | 180    | 20681089                 |        | n/a                      |        | n/a                                                         | 180                     | 20681089                        | 
| Urban and Industrial Site Reinvestment | 14     | 14371333                 | 8      | 2,226,942                | 1      | 2,005,000                                                   | 23                      | 18603275                        | 
```