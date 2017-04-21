# Department of Revenue Services - Tax Credits Claimed For 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-revenue-services-tax-credits-claimed-for-2007) |
| Metadata | [Link](https://data.ct.gov/api/views/aem3-ujda) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/aem3-ujda/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/aem3-ujda/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | aem3-ujda |
| Name | Department of Revenue Services - Tax Credits Claimed For 2007 |
| Attribution | Department of Economic and Community Development |
| Category | Business |
| Tags | executive order 38, drs, department of revenue services, tax, tax credits, tax credits claimed, decd, department of economic and community development |
| Created | 2014-03-21T18:46:19Z |
| Publication Date | 2014-03-25T19:17:53Z |

## Description

Department of Revenue Services Tax Credits Claimed on 2007 Corporation Business, Insurance Premiums and Public Service Companies Tax Returns

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
Value = 2007
Format & Zone = yyyy
```

## Data Commands

```ls
series e:aem3-ujda d:2007-01-01T00:00:00.000Z t:type_of_credit="Digital Animation" m:total_amount_of_credits_claimed=0 m:total_number_of_credits=0 m:count1=0 m:corporation_business_tax=0

series e:aem3-ujda d:2007-01-01T00:00:00.000Z t:type_of_credit="Electronic Data Processing" m:total_amount_of_credits_claimed=29385494 m:public_service_companies=318309 m:count2=38 m:total_number_of_credits=1518 m:count1=1477 m:corporation_business_tax=13736970 m:insurance_premiums_taxes=15330215 m:count3=3

series e:aem3-ujda d:2007-01-01T00:00:00.000Z t:type_of_credit="Film Production" m:total_amount_of_credits_claimed=54132334 m:count2=14 m:total_number_of_credits=24 m:count1=10 m:corporation_business_tax=11438432 m:insurance_premiums_taxes=42693902
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

entity e:aem3-ujda l:"Department of Revenue Services - Tax Credits Claimed For 2007" t:attribution="Department of Economic and Community Development" t:url=https://data.ct.gov/api/views/aem3-ujda

property e:aem3-ujda t:meta.view v:id=aem3-ujda v:category=Business v:averageRating=0 v:name="Department of Revenue Services - Tax Credits Claimed For 2007" v:attribution="Department of Economic and Community Development"

property e:aem3-ujda t:meta.view.owner v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:displayName="Kara Sene"

property e:aem3-ujda t:meta.view.tableauthor v:id=nbd6-fawc v:profileImageUrlMedium=/api/users/nbd6-fawc/profile_images/THUMB v:profileImageUrlLarge=/api/users/nbd6-fawc/profile_images/LARGE v:screenName="Kara Sene" v:profileImageUrlSmall=/api/users/nbd6-fawc/profile_images/TINY v:roleName=editor v:displayName="Kara Sene"
```

## Top Records

```ls
| type_of_credit                         | count1 | corporation_business_tax | count2 | insurance_premiums_taxes | count3 | public_service_companies | total_number_of_credits | total_amount_of_credits_claimed | 
| ====================================== | ====== | ======================== | ====== | ======================== | ====== | ======================== | ======================= | =============================== | 
| Digital Animation                      | 0      | 0                        |        |                          |        |                          | 0                       | 0                               | 
| Electronic Data Processing             | 1477   | 13736970                 | 38     | 15330215                 | 3      | 318309                   | 1518                    | 29385494                        | 
| Film Production                        | 10     | 11438432                 | 14     | 42693902                 |        |                          | 24                      | 54132334                        | 
| Film Production Infrastructure         | 0      | 0                        |        |                          |        |                          | 0                       | 0                               | 
| Fixed Capital                          | 2207   | 46228288                 |        |                          |        |                          | 2207                    | 46228288                        | 
| Research and Development               | 134    | 5321279                  |        |                          |        |                          | 134                     | 5321279                         | 
| Research and Experimentation           | 153    | 10637252                 |        |                          |        |                          | 153                     | 10637252                        | 
| Urban and Industrial Site Reinvestment | 1      | 560040                   | 1      | 287621                   |        | 0                        | 2                       | 847661                          | 
```