# Municipal Revenues by Source ? Fiscal Year 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/municipal-revenues-by-source-fiscal-year-2010-cbcc5) |
| Metadata | [Link](https://data.maryland.gov/api/views/idsb-kajn) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/idsb-kajn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/idsb-kajn/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | idsb-kajn |
| Name | Municipal Revenues by Source ? Fiscal Year 2010 |
| Attribution | Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Servic... |
| Category | Budget |
| Tags | taxes, budget, county, counties, dls, department of legislative services, revenues |
| Created | 2014-08-08T18:14:33Z |
| Publication Date | 2014-08-08T18:22:04Z |

## Description

Municipal revenue sources for each county's municipalities. Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                                                       | Data Type | Render Type |
| ======== | ============== | ========================================================== | ========================================================== | ========= | =========== |
| Yes      | series tag     | county                                                     | County                                                     | text      | text        |
| Yes      | numeric metric | percentage_of_total_municipal_revenue_from_property_taxes  | Percentage of Total Municipal Revenue from Property Taxes  | percent   | percent     |
| Yes      | numeric metric | percentage_of_total_municipal_revenue_from_income_taxes    | Percentage of Total Municipal Revenue from Income Taxes    | percent   | percent     |
| Yes      | numeric metric | percentage_of_total_municipal_revenue_from_other_taxes     | Percentage of Total Municipal Revenue from Other Taxes     | percent   | percent     |
| Yes      | numeric metric | percentage_of_total_municipal_revenue_from_service_charges | Percentage of Total Municipal Revenue from Service Charges | percent   | percent     |
| Yes      | numeric metric | percentage_of_total_municipal_revenue_from_federal_grants  | Percentage of Total Municipal Revenue from Federal Grants  | percent   | percent     |
| Yes      | numeric metric | percentage_of_total_municipal_revenue_from_state_grants    | Percentage of Total Municipal Revenue from State Grants    | percent   | percent     |
| Yes      | numeric metric | percentage_of_total_municipal_revenue_from_county_grants   | Percentage of Total Municipal Revenue from County Grants   | percent   | percent     |
| Yes      | numeric metric | percentage_of_total_municipal_revenue_from_other_sources   | Percentage of Total Municipal Revenue from Other Sources   | percent   | percent     |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:idsb-kajn d:2010-01-01T00:00:00.000Z t:county=Allegany m:percentage_of_total_municipal_revenue_from_county_grants=0.7 m:percentage_of_total_municipal_revenue_from_service_charges=36.5 m:percentage_of_total_municipal_revenue_from_state_grants=5.8 m:percentage_of_total_municipal_revenue_from_other_taxes=0.3 m:percentage_of_total_municipal_revenue_from_income_taxes=4.2 m:percentage_of_total_municipal_revenue_from_property_taxes=19.2 m:percentage_of_total_municipal_revenue_from_federal_grants=7.9 m:percentage_of_total_municipal_revenue_from_other_sources=25.4

series e:idsb-kajn d:2010-01-01T00:00:00.000Z t:county="Anne Arundel" m:percentage_of_total_municipal_revenue_from_county_grants=3.6 m:percentage_of_total_municipal_revenue_from_service_charges=26.5 m:percentage_of_total_municipal_revenue_from_state_grants=5.7 m:percentage_of_total_municipal_revenue_from_other_taxes=1.1 m:percentage_of_total_municipal_revenue_from_income_taxes=5.5 m:percentage_of_total_municipal_revenue_from_property_taxes=44.2 m:percentage_of_total_municipal_revenue_from_federal_grants=5.5 m:percentage_of_total_municipal_revenue_from_other_sources=7.9

series e:idsb-kajn d:2010-01-01T00:00:00.000Z t:county=Calvert m:percentage_of_total_municipal_revenue_from_county_grants=2.4 m:percentage_of_total_municipal_revenue_from_service_charges=31.9 m:percentage_of_total_municipal_revenue_from_state_grants=8 m:percentage_of_total_municipal_revenue_from_other_taxes=10.9 m:percentage_of_total_municipal_revenue_from_income_taxes=1.9 m:percentage_of_total_municipal_revenue_from_property_taxes=40.9 m:percentage_of_total_municipal_revenue_from_federal_grants=0.4 m:percentage_of_total_municipal_revenue_from_other_sources=3.7
```

## Meta Commands

```ls
metric m:percentage_of_total_municipal_revenue_from_property_taxes p:float l:"Percentage of Total Municipal Revenue from Property Taxes" t:dataTypeName=percent

metric m:percentage_of_total_municipal_revenue_from_income_taxes p:float l:"Percentage of Total Municipal Revenue from Income Taxes" t:dataTypeName=percent

metric m:percentage_of_total_municipal_revenue_from_other_taxes p:float l:"Percentage of Total Municipal Revenue from Other Taxes" t:dataTypeName=percent

metric m:percentage_of_total_municipal_revenue_from_service_charges p:float l:"Percentage of Total Municipal Revenue from Service Charges" t:dataTypeName=percent

metric m:percentage_of_total_municipal_revenue_from_federal_grants p:float l:"Percentage of Total Municipal Revenue from Federal Grants" t:dataTypeName=percent

metric m:percentage_of_total_municipal_revenue_from_state_grants p:float l:"Percentage of Total Municipal Revenue from State Grants" t:dataTypeName=percent

metric m:percentage_of_total_municipal_revenue_from_county_grants p:float l:"Percentage of Total Municipal Revenue from County Grants" t:dataTypeName=percent

metric m:percentage_of_total_municipal_revenue_from_other_sources p:float l:"Percentage of Total Municipal Revenue from Other Sources" t:dataTypeName=percent

entity e:idsb-kajn l:"Municipal Revenues by Source ? Fiscal Year 2010" t:attribution="Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)" t:url=https://data.maryland.gov/api/views/idsb-kajn

property e:idsb-kajn t:meta.view v:id=idsb-kajn v:category=Budget v:attributionLink=http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf v:averageRating=0 v:name="Municipal Revenues by Source ? Fiscal Year 2010" v:attribution="Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)"

property e:idsb-kajn t:meta.view.license v:name="Public Domain"

property e:idsb-kajn t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:idsb-kajn t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| county       | percentage_of_total_municipal_revenue_from_property_taxes | percentage_of_total_municipal_revenue_from_income_taxes | percentage_of_total_municipal_revenue_from_other_taxes | percentage_of_total_municipal_revenue_from_service_charges | percentage_of_total_municipal_revenue_from_federal_grants | percentage_of_total_municipal_revenue_from_state_grants | percentage_of_total_municipal_revenue_from_county_grants | percentage_of_total_municipal_revenue_from_other_sources | 
| ============ | ========================================================= | ======================================================= | ====================================================== | ========================================================== | ========================================================= | ======================================================= | ======================================================== | ======================================================== | 
| Allegany     | 19.2                                                      | 4.2                                                     | 0.3                                                    | 36.5                                                       | 7.9                                                       | 5.8                                                     | 0.7                                                      | 25.4                                                     | 
| Anne Arundel | 44.2                                                      | 5.5                                                     | 1.1                                                    | 26.5                                                       | 5.5                                                       | 5.7                                                     | 3.6                                                      | 7.9                                                      | 
| Calvert      | 40.9                                                      | 1.9                                                     | 10.9                                                   | 31.9                                                       | 0.4                                                       | 8.0                                                     | 2.4                                                      | 3.7                                                      | 
| Caroline     | 43.3                                                      | 3.9                                                     | 0.2                                                    | 29.3                                                       | 6.3                                                       | 6.1                                                     | 0.1                                                      | 10.9                                                     | 
| Carroll      | 31.4                                                      | 9.7                                                     | 0.7                                                    | 35.6                                                       | 6.2                                                       | 3.6                                                     | 6.1                                                      | 6.7                                                      | 
| Cecil        | 32.3                                                      | 5.9                                                     | 0.3                                                    | 40.4                                                       | 2.2                                                       | 11.5                                                    | 2.8                                                      | 4.6                                                      | 
| Charles      | 30.8                                                      | 9.3                                                     | 0.0                                                    | 39.6                                                       | 1.6                                                       | 7.7                                                     | 0.1                                                      | 10.8                                                     | 
| Dorchester   | 39.0                                                      | 2.9                                                     | 0.5                                                    | 39.1                                                       | 2.7                                                       | 5.1                                                     | 6.5                                                      | 4.3                                                      | 
| Frederick    | 38.6                                                      | 6.2                                                     | 0.4                                                    | 31.8                                                       | 3.4                                                       | 3.9                                                     | 5.4                                                      | 10.3                                                     | 
| Garrett      | 17.7                                                      | 5.5                                                     | 1.2                                                    | 25.8                                                       | 19.5                                                      | 4.7                                                     | 3.4                                                      | 22.3                                                     | 
```