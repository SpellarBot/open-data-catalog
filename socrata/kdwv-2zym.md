# County Revenues By Source ? Fiscal Year 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/county-revenues-by-source-fiscal-year-2010-b0246) |
| Metadata | [Link](https://data.maryland.gov/api/views/kdwv-2zym) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/kdwv-2zym/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/kdwv-2zym/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | kdwv-2zym |
| Name | County Revenues By Source ? Fiscal Year 2010 |
| Attribution | Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Servic... |
| Category | Budget |
| Tags | taxes, budget, county, counties, dls, department of legislative services, revenues |
| Created | 2014-08-08T15:50:09Z |
| Publication Date | 2014-08-08T15:54:08Z |

## Description

Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                                             | Data Type | Render Type |
| ======== | ============== | ================================================ | ================================================ | ========= | =========== |
| Yes      | series tag     | county                                           | County                                           | text      | text        |
| Yes      | numeric metric | percentage_of_total_revenue_from_property_taxes  | Percentage of Total Revenue from Property Taxes  | percent   | percent     |
| Yes      | numeric metric | percentage_of_total_revenue_from_income_taxes    | Percentage of Total Revenue from Income Taxes    | percent   | percent     |
| Yes      | numeric metric | percentage_of_total_revenue_from_other_taxes     | Percentage of Total Revenue from Other Taxes     | percent   | percent     |
| Yes      | numeric metric | percentage_of_total_revenue_from_service_charges | Percentage of Total Revenue from Service Charges | percent   | percent     |
| Yes      | numeric metric | percentage_of_total_revenue_from_federal_grants  | Percentage of Total Revenue from Federal Grants  | percent   | percent     |
| Yes      | numeric metric | percentage_of_total_revenue_from_state_grants    | Percentage of Total Revenue from State Grants    | percent   | percent     |
| Yes      | numeric metric | percentage_of_total_revenue_from_other_sources   | Percentage of Total Revenue from Other Sources   | percent   | percent     |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kdwv-2zym d:2010-01-01T00:00:00.000Z t:county=Allegany m:percentage_of_total_revenue_from_service_charges=9.3 m:percentage_of_total_revenue_from_state_grants=46.5 m:percentage_of_total_revenue_from_income_taxes=8.7 m:percentage_of_total_revenue_from_other_taxes=1.3 m:percentage_of_total_revenue_from_property_taxes=14.8 m:percentage_of_total_revenue_from_other_sources=6.6 m:percentage_of_total_revenue_from_federal_grants=12.8

series e:kdwv-2zym d:2010-01-01T00:00:00.000Z t:county="Anne Arundel" m:percentage_of_total_revenue_from_service_charges=13.6 m:percentage_of_total_revenue_from_state_grants=23.5 m:percentage_of_total_revenue_from_income_taxes=18.6 m:percentage_of_total_revenue_from_other_taxes=5.5 m:percentage_of_total_revenue_from_property_taxes=29.3 m:percentage_of_total_revenue_from_other_sources=3.5 m:percentage_of_total_revenue_from_federal_grants=6

series e:kdwv-2zym d:2010-01-01T00:00:00.000Z t:county="Baltimore City" m:percentage_of_total_revenue_from_service_charges=12.4 m:percentage_of_total_revenue_from_state_grants=36.4 m:percentage_of_total_revenue_from_income_taxes=6.5 m:percentage_of_total_revenue_from_other_taxes=4.2 m:percentage_of_total_revenue_from_property_taxes=22.2 m:percentage_of_total_revenue_from_other_sources=4 m:percentage_of_total_revenue_from_federal_grants=14.2
```

## Meta Commands

```ls
metric m:percentage_of_total_revenue_from_property_taxes p:float l:"Percentage of Total Revenue from Property Taxes" t:dataTypeName=percent

metric m:percentage_of_total_revenue_from_income_taxes p:float l:"Percentage of Total Revenue from Income Taxes" t:dataTypeName=percent

metric m:percentage_of_total_revenue_from_other_taxes p:float l:"Percentage of Total Revenue from Other Taxes" t:dataTypeName=percent

metric m:percentage_of_total_revenue_from_service_charges p:float l:"Percentage of Total Revenue from Service Charges" t:dataTypeName=percent

metric m:percentage_of_total_revenue_from_federal_grants p:float l:"Percentage of Total Revenue from Federal Grants" t:dataTypeName=percent

metric m:percentage_of_total_revenue_from_state_grants p:float l:"Percentage of Total Revenue from State Grants" t:dataTypeName=percent

metric m:percentage_of_total_revenue_from_other_sources p:float l:"Percentage of Total Revenue from Other Sources" t:dataTypeName=percent

entity e:kdwv-2zym l:"County Revenues By Source ? Fiscal Year 2010" t:attribution="Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)" t:url=https://data.maryland.gov/api/views/kdwv-2zym

property e:kdwv-2zym t:meta.view v:id=kdwv-2zym v:category=Budget v:attributionLink=http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf v:averageRating=0 v:name="County Revenues By Source ? Fiscal Year 2010" v:attribution="Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)"

property e:kdwv-2zym t:meta.view.license v:name="Public Domain"

property e:kdwv-2zym t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:kdwv-2zym t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| county         | percentage_of_total_revenue_from_property_taxes | percentage_of_total_revenue_from_income_taxes | percentage_of_total_revenue_from_other_taxes | percentage_of_total_revenue_from_service_charges | percentage_of_total_revenue_from_federal_grants | percentage_of_total_revenue_from_state_grants | percentage_of_total_revenue_from_other_sources | 
| ============== | =============================================== | ============================================= | ============================================ | ================================================ | =============================================== | ============================================= | ============================================== | 
| Allegany       | 14.8                                            | 8.7                                           | 1.3                                          | 9.3                                              | 12.8                                            | 46.5                                          | 6.6                                            | 
| Anne Arundel   | 29.3                                            | 18.6                                          | 5.5                                          | 13.6                                             | 6.0                                             | 23.5                                          | 3.5                                            | 
| Baltimore City | 22.2                                            | 6.5                                           | 4.2                                          | 12.4                                             | 14.2                                            | 36.4                                          | 4.0                                            | 
| Baltimore      | 29.7                                            | 17.9                                          | 3.8                                          | 10.5                                             | 9.2                                             | 26.4                                          | 2.5                                            | 
| Calvert        | 35.7                                            | 15.0                                          | 1.7                                          | 7.9                                              | 4.3                                             | 31.7                                          | 3.7                                            | 
| Caroline       | 18.7                                            | 8.1                                           | 1.6                                          | 4.2                                              | 10.1                                            | 53.6                                          | 3.7                                            | 
| Carroll        | 32.3                                            | 17.4                                          | 2.4                                          | 4.9                                              | 5.4                                             | 34.4                                          | 3.2                                            | 
| Cecil          | 28.6                                            | 13.3                                          | 1.6                                          | 5.5                                              | 8.3                                             | 39.2                                          | 3.4                                            | 
| Charles        | 29.2                                            | 13.3                                          | 2.4                                          | 10.3                                             | 7.9                                             | 33.2                                          | 3.6                                            | 
| Dorchester     | 23.7                                            | 7.1                                           | 2.9                                          | 5.5                                              | 13.5                                            | 43.4                                          | 3.8                                            | 
```