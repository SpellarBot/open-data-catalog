# Department of Revenue Services Tax Credits Claimed during FY 15

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-revenue-services-tax-credits-claimed-during-fy-15) |
| Metadata | [Link](https://data.ct.gov/api/views/qivg-ffqa) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/qivg-ffqa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/qivg-ffqa/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | qivg-ffqa |
| Name | Department of Revenue Services Tax Credits Claimed during FY 15 |
| Attribution | Department of Revenue Services |
| Category | Business |
| Tags | executive order 38, drs, department of revenue services, tax, tax credits, tax credits claimed, decd, department of economic and community development |
| Created | 2016-04-01T20:43:29Z |
| Publication Date | 2016-04-01T20:45:13Z |

## Description

Tax Credits Claimed during FY 2014-15 (July 1, 2014 through June 30, 2015)

## Columns

```ls
| Included | Schema Type    | Field Name                                      | Name                                               | Data Type | Render Type |
| ======== | ============== | =============================================== | ================================================== | ========= | =========== |
| No       | time           | :updated_at                                     | updated_at                                         | meta_data | meta_data   |
| Yes      | series tag     | type_of_credit                                  | Type of Credit                                     | text      | text        |
| Yes      | numeric metric | count1                                          | Count1                                             | number    | number      |
| Yes      | numeric metric | corporation_business_tax                        | Corporation Business Tax                           | number    | number      |
| Yes      | numeric metric | count2                                          | Count2                                             | number    | number      |
| Yes      | series tag     | insurance_premiums_taxes                        | Insurance Premiums Taxes                           | text      | text        |
| Yes      | numeric metric | count3                                          | Count3                                             | number    | number      |
| Yes      | series tag     | public_service_cos_hospital_net_patient_revenue | Public Service Cos. & Hospital Net Patient Revenue | text      | text        |
| Yes      | numeric metric | total_count                                     | Total Count                                        | number    | number      |
| Yes      | numeric metric | total_credits_claimed                           | Total Credits Claimed                              | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qivg-ffqa d:2016-04-01T13:43:33.000Z t:insurance_premiums_taxes=6,875,794 t:public_service_cos_hospital_net_patient_revenue=n/a t:type_of_credit="Digital Animation" m:total_credits_claimed=8209925 m:count2=19 m:count1=3 m:corporation_business_tax=1334131 m:total_count=22

series e:qivg-ffqa d:2016-04-01T13:43:33.000Z t:insurance_premiums_taxes=10,111,160 t:public_service_cos_hospital_net_patient_revenue=65,675 t:type_of_credit="Electronic Data Processing" m:total_credits_claimed=24857856 m:count2=37 m:count1=1118 m:corporation_business_tax=14681021 m:total_count=1157 m:count3=2

series e:qivg-ffqa d:2016-04-01T13:43:33.000Z t:insurance_premiums_taxes=19,636,413 t:public_service_cos_hospital_net_patient_revenue=n/a t:type_of_credit="Film Production" m:total_credits_claimed=40225185 m:count2=31 m:count1=27 m:corporation_business_tax=20588772 m:total_count=58
```

## Meta Commands

```ls
metric m:count1 p:integer l:Count1 t:dataTypeName=number

metric m:corporation_business_tax p:integer l:"Corporation Business Tax" t:dataTypeName=number

metric m:count2 p:integer l:Count2 t:dataTypeName=number

metric m:count3 p:integer l:Count3 t:dataTypeName=number

metric m:total_count p:integer l:"Total Count" t:dataTypeName=number

metric m:total_credits_claimed p:integer l:"Total Credits Claimed" t:dataTypeName=number

entity e:qivg-ffqa l:"Department of Revenue Services Tax Credits Claimed during FY 15" t:attribution="Department of Revenue Services" t:url=https://data.ct.gov/api/views/qivg-ffqa

property e:qivg-ffqa t:meta.view v:id=qivg-ffqa v:category=Business v:averageRating=0 v:name="Department of Revenue Services Tax Credits Claimed during FY 15" v:attribution="Department of Revenue Services"

property e:qivg-ffqa t:meta.view.owner v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:displayName="Kara Sene"

property e:qivg-ffqa t:meta.view.tableauthor v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:roleName=editor v:displayName="Kara Sene"
```

## Top Records

```ls
| :updated_at | type_of_credit                         | count1 | corporation_business_tax | count2 | insurance_premiums_taxes | count3 | public_service_cos_hospital_net_patient_revenue    | total_count | total_credits_claimed | 
| =========== | ====================================== | ====== | ======================== | ====== | ======================== | ====== | ================================================== | =========== | ===================== | 
| 1459518213  | Type of Credit                         |        |                          |        | Insurance Premiums Taxes |        | Public Service Cos. & Hospital Net Patient Revenue |             |                       | 
| 1459518213  | Digital Animation                      | 3      | 1334131                  | 19     | 6,875,794                |        | n/a                                                | 22          | 8209925               | 
| 1459518213  | Electronic Data Processing             | 1118   | 14681021                 | 37     | 10,111,160               | 2      | 65,675                                             | 1157        | 24857856              | 
| 1459518213  | Film Production                        | 27     | 20588772                 | 31     | 19,636,413               |        | n/a                                                | 58          | 40225185              | 
| 1459518213  | Film Production Infrastructure         | 5      | 15393505                 | 30     | 15,598,778               |        | n/a                                                | 35          | 30992283              | 
| 1459518213  | Fixed Capital                          | 1708   | 79884093                 |        | n/a                      |        | n/a                                                | 1708        | 79884093              | 
| 1459518213  | Job Expansion                          | 41     | 5237156                  | 3      | 226,090                  |        | n/a                                                | 44          | 5463246               | 
| 1459518213  | Research and Development               | 171    | 7611515                  |        | n/a                      |        | n/a                                                | 171         | 7611515               | 
| 1459518213  | Research and Experimentation           | 208    | 20037054                 |        | n/a                      |        | n/a                                                | 208         | 20037054              | 
| 1459518213  | Urban and Industrial Site Reinvestment | 16     | 16885172                 | 5      | 7,836,360                | 5      | 51,080,000                                         | 21          | 75801532              | 
```