# Local Government Expenditures By Category ? Fiscal Year 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/local-government-expenditures-by-category-fiscal-year-2010-3f3e9) |
| Metadata | [Link](https://data.maryland.gov/api/views/aid4-m6ib) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/aid4-m6ib/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/aid4-m6ib/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | aid4-m6ib |
| Name | Local Government Expenditures By Category ? Fiscal Year 2010 |
| Attribution | Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Servic... |
| Category | Budget |
| Tags | expenditures, budget, county, municipality, counties, municipalities, spending, dls, department of legislative services |
| Created | 2014-08-08T15:33:31Z |
| Publication Date | 2014-08-08T15:45:54Z |

## Description

State, county, and municipal expenditures by spending category. Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                                                        | Data Type | Render Type |
| ======== | ============== | ======================== | =========================================================== | ========= | =========== |
| Yes      | series tag     | category                 | Category                                                    | text      | text        |
| Yes      | numeric metric | total_local_expenditures | Total Local Expenditures (County+Municipality Expenditures) | money     | money       |
| Yes      | numeric metric | percent_of_total         | Category's Portion of Total Local Expenditures              | percent   | percent     |
| Yes      | numeric metric | municipal_expenditures   | Municipal Expenditures                                      | money     | money       |
| Yes      | numeric metric | percent_municipal        | Percentage of Local Funding from Municipalities             | percent   | percent     |
| Yes      | numeric metric | county_expenditures      | County Expenditures                                         | money     | money       |
| Yes      | numeric metric | percent_county           | Percentage of Local Funding from Counties                   | percent   | percent     |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:aid4-m6ib d:2010-01-01T00:00:00.000Z t:category="General Government" m:municipal_expenditures=182501451 m:county_expenditures=1510756065 m:percent_county=89.2 m:percent_municipal=10.8 m:total_local_expenditures=1693257516 m:percent_of_total=6.1

series e:aid4-m6ib d:2010-01-01T00:00:00.000Z t:category="Public Safety: Police" m:municipal_expenditures=216952228 m:county_expenditures=1418782326 m:percent_county=86.7 m:percent_municipal=13.3 m:total_local_expenditures=1635734554 m:percent_of_total=5.9

series e:aid4-m6ib d:2010-01-01T00:00:00.000Z t:category="Public Safety: Fire" m:municipal_expenditures=49075801 m:county_expenditures=829253363 m:percent_county=94.4 m:percent_municipal=5.6 m:total_local_expenditures=878329164 m:percent_of_total=3.2
```

## Meta Commands

```ls
metric m:total_local_expenditures p:long l:"Total Local Expenditures (County+Municipality Expenditures)" t:dataTypeName=money

metric m:percent_of_total p:float l:"Category's Portion of Total Local Expenditures" t:dataTypeName=percent

metric m:municipal_expenditures p:integer l:"Municipal Expenditures" t:dataTypeName=money

metric m:percent_municipal p:float l:"Percentage of Local Funding from Municipalities" t:dataTypeName=percent

metric m:county_expenditures p:long l:"County Expenditures" t:dataTypeName=money

metric m:percent_county p:float l:"Percentage of Local Funding from Counties" t:dataTypeName=percent

entity e:aid4-m6ib l:"Local Government Expenditures By Category ? Fiscal Year 2010" t:attribution="Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)" t:url=https://data.maryland.gov/api/views/aid4-m6ib

property e:aid4-m6ib t:meta.view v:id=aid4-m6ib v:category=Budget v:attributionLink=http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf v:averageRating=0 v:name="Local Government Expenditures By Category ? Fiscal Year 2010" v:attribution="Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)"

property e:aid4-m6ib t:meta.view.license v:name="Public Domain"

property e:aid4-m6ib t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:aid4-m6ib t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| category                                | total_local_expenditures | percent_of_total | municipal_expenditures | percent_municipal | county_expenditures | percent_county | 
| ======================================= | ======================== | ================ | ====================== | ================= | =================== | ============== | 
| General Government                      | 1693257516               | 6.10             | 182501451              | 10.80             | 1510756065          | 89.20          | 
| Public Safety: Police                   | 1635734554               | 5.90             | 216952228              | 13.30             | 1418782326          | 86.70          | 
| Public Safety: Fire                     | 878329164                | 3.20             | 49075801               | 5.60              | 829253363           | 94.40          | 
| Public Safety: Corrections              | 358376521                | 1.30             | 0                      | 0.00              | 358376521           | 100.00         | 
| Public Safety: Other                    | 298248673                | 1.10             | 32006141               | 10.70             | 266242532           | 89.30          | 
| Public Works: Transportation            | 1470421205               | 5.30             | 171845287              | 11.70             | 1298575918          | 88.30          | 
| Public Works: Sewer/Solid & Waste/Water | 2015204739               | 7.20             | 283433256              | 14.10             | 1731771483          | 85.90          | 
| Public Works: Other                     | 94190431                 | 0.30             | 88007332               | 93.40             | 6183099             | 6.60           | 
| Education: Public Schools               | 13012621906              | 46.80            | 0                      | 0.00              | 13012621906         | 100.00         | 
| Education: Community Colleges           | 1162275853               | 4.20             | 0                      | 0.00              | 1162275853          | 100.00         | 
```