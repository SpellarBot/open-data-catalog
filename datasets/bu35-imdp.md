# Per Capita County Revenues By Source ? Fiscal Year 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/per-capita-county-revenues-by-source-fiscal-year-2010-65489) |
| Metadata | [Link](https://data.maryland.gov/api/views/bu35-imdp) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/bu35-imdp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/bu35-imdp/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | bu35-imdp |
| Name | Per Capita County Revenues By Source ? Fiscal Year 2010 |
| Attribution | Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Servic... |
| Category | Budget |
| Tags | taxes, revenues, budget, county, counties, municipalities, dls, department of legislative services |
| Created | 2014-08-08T15:58:21Z |
| Publication Date | 2014-08-08T16:05:16Z |

## Description

Per capita revenues by county and by source for FY2010. Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| Yes      | series tag     | county                             | County                             | text      | text        |
| Yes      | numeric metric | property_taxes_revenue_per_capita  | Property Taxes Revenue per Capita  | money     | money       |
| Yes      | numeric metric | income_taxes_revenue_per_capita    | Income Taxes Revenue per Capita    | money     | money       |
| Yes      | numeric metric | other_taxes_revenue_per_capita     | Other Taxes Revenue per Capita     | money     | money       |
| Yes      | numeric metric | service_charges_revenue_per_capita | Service Charges Revenue per Capita | money     | money       |
| Yes      | numeric metric | federal_grants_revenue_per_capita  | Federal Grants Revenue per Capita  | money     | money       |
| Yes      | numeric metric | state_grants_revenue_per_capita    | State Grants Revenue per Capita    | money     | money       |
| Yes      | numeric metric | other_revenue_per_capita           | Other Revenue per Capita           | money     | money       |
| Yes      | numeric metric | debt_proceeds_revenue_per_capita   | Debt Proceeds Revenue per Capita   | money     | money       |
| Yes      | numeric metric | total_revenue_per_capita           | Total Revenue per Capita           | money     | money       |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bu35-imdp d:2010-01-01T00:00:00.000Z t:county=Allegany m:state_grants_revenue_per_capita=1757 m:total_revenue_per_capita=3779 m:other_revenue_per_capita=248 m:income_taxes_revenue_per_capita=328 m:other_taxes_revenue_per_capita=51 m:service_charges_revenue_per_capita=351 m:federal_grants_revenue_per_capita=485 m:property_taxes_revenue_per_capita=560 m:debt_proceeds_revenue_per_capita=0

series e:bu35-imdp d:2010-01-01T00:00:00.000Z t:county="Anne Arundel" m:state_grants_revenue_per_capita=864 m:total_revenue_per_capita=3974 m:other_revenue_per_capita=129 m:income_taxes_revenue_per_capita=683 m:other_taxes_revenue_per_capita=202 m:service_charges_revenue_per_capita=501 m:federal_grants_revenue_per_capita=219 m:property_taxes_revenue_per_capita=1079 m:debt_proceeds_revenue_per_capita=297

series e:bu35-imdp d:2010-01-01T00:00:00.000Z t:county="Baltimore City" m:state_grants_revenue_per_capita=1944 m:total_revenue_per_capita=5625 m:other_revenue_per_capita=216 m:income_taxes_revenue_per_capita=349 m:other_taxes_revenue_per_capita=225 m:service_charges_revenue_per_capita=662 m:federal_grants_revenue_per_capita=759 m:property_taxes_revenue_per_capita=1188 m:debt_proceeds_revenue_per_capita=282
```

## Meta Commands

```ls
metric m:property_taxes_revenue_per_capita p:integer l:"Property Taxes Revenue per Capita" t:dataTypeName=money

metric m:income_taxes_revenue_per_capita p:integer l:"Income Taxes Revenue per Capita" t:dataTypeName=money

metric m:other_taxes_revenue_per_capita p:integer l:"Other Taxes Revenue per Capita" t:dataTypeName=money

metric m:service_charges_revenue_per_capita p:integer l:"Service Charges Revenue per Capita" t:dataTypeName=money

metric m:federal_grants_revenue_per_capita p:integer l:"Federal Grants Revenue per Capita" t:dataTypeName=money

metric m:state_grants_revenue_per_capita p:integer l:"State Grants Revenue per Capita" t:dataTypeName=money

metric m:other_revenue_per_capita p:integer l:"Other Revenue per Capita" t:dataTypeName=money

metric m:debt_proceeds_revenue_per_capita p:integer l:"Debt Proceeds Revenue per Capita" t:dataTypeName=money

metric m:total_revenue_per_capita p:integer l:"Total Revenue per Capita" t:dataTypeName=money

entity e:bu35-imdp l:"Per Capita County Revenues By Source ? Fiscal Year 2010" t:attribution="Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)" t:url=https://data.maryland.gov/api/views/bu35-imdp

property e:bu35-imdp t:meta.view v:id=bu35-imdp v:category=Budget v:attributionLink=http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf v:averageRating=0 v:name="Per Capita County Revenues By Source ? Fiscal Year 2010" v:attribution="Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)"

property e:bu35-imdp t:meta.view.license v:name="Public Domain"

property e:bu35-imdp t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:bu35-imdp t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| county           | property_taxes_revenue_per_capita | income_taxes_revenue_per_capita | other_taxes_revenue_per_capita | service_charges_revenue_per_capita | federal_grants_revenue_per_capita | state_grants_revenue_per_capita | other_revenue_per_capita | debt_proceeds_revenue_per_capita | total_revenue_per_capita | 
| ================ | ================================= | =============================== | ============================== | ================================== | ================================= | =============================== | ======================== | ================================ | ======================== | 
| Allegany         | 560                               | 328                             | 51                             | 351                                | 485                               | 1757                            | 248                      | 0                                | 3779                     | 
| Anne Arundel     | 1079                              | 683                             | 202                            | 501                                | 219                               | 864                             | 129                      | 297                              | 3974                     | 
| Baltimore City   | 1188                              | 349                             | 225                            | 662                                | 759                               | 1944                            | 216                      | 282                              | 5625                     | 
| Baltimore County | 1041                              | 628                             | 132                            | 367                                | 321                               | 924                             | 87                       | 232                              | 3730                     | 
| Calvert          | 1502                              | 629                             | 73                             | 332                                | 181                               | 1331                            | 154                      | 223                              | 4425                     | 
| Caroline         | 696                               | 300                             | 60                             | 156                                | 375                               | 1992                            | 138                      | 482                              | 4198                     | 
| Carroll          | 1185                              | 636                             | 90                             | 179                                | 197                               | 1260                            | 118                      | 421                              | 4085                     | 
| Cecil            | 1001                              | 464                             | 57                             | 194                                | 290                               | 1371                            | 119                      | 129                              | 3624                     | 
| Charles          | 1337                              | 608                             | 112                            | 473                                | 361                               | 1520                            | 166                      | 116                              | 4694                     | 
| Dorchester       | 903                               | 270                             | 110                            | 210                                | 516                               | 1654                            | 146                      | 651                              | 4460                     | 
```