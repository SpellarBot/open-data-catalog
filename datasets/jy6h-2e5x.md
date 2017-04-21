# City Budget and Actual Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-budget-and-actual-expenditures-7652e) |
| Metadata | [Link](https://data.iowa.gov/api/views/jy6h-2e5x) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/jy6h-2e5x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/jy6h-2e5x/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | jy6h-2e5x |
| Name | City Budget and Actual Expenditures |
| Attribution | Ted Nellesen, Department of Management |
| Category | Government |
| Tags | city, budget, actual |
| Created | 2016-12-06T17:17:41Z |
| Publication Date | 2016-12-06T17:30:33Z |

## Description

The budget and actual expenditures self-reported by each city via their yearly budget forms filed with the Department of Management. Actual expenditure data lags budget expenditures by a couple of fiscal years.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                      | Data Type | Render Type |
| ======== | ============== | ========================================= | ========================================= | ========= | =========== |
| Yes      | time           | fiscal_year                               | Fiscal Year                               | number    | text        |
| Yes      | series tag     | county_code                               | County Code                               | text      | number      |
| Yes      | series tag     | county                                    | County                                    | text      | text        |
| Yes      | series tag     | gnis_feature_id                           | GNIS Feature ID                           | text      | text        |
| Yes      | series tag     | city_fips                                 | City FIPS                                 | text      | text        |
| Yes      | series tag     | city_code                                 | City Code                                 | text      | text        |
| Yes      | series tag     | city_name                                 | City Name                                 | text      | text        |
| Yes      | numeric metric | public_safety_budget                      | Public Safety Budget                      | number    | number      |
| Yes      | numeric metric | public_works_budget                       | Public Works Budget                       | number    | number      |
| Yes      | numeric metric | health_and_social_services_budget         | Health and Social Services Budget         | number    | number      |
| Yes      | numeric metric | culture_and_recreation_budget             | Culture and Recreation Budget             | number    | number      |
| Yes      | numeric metric | community_and_economic_development_budget | Community and Economic Development Budget | number    | number      |
| Yes      | numeric metric | general_government_budget                 | General Government Budget                 | number    | number      |
| Yes      | numeric metric | debt_service_budget                       | Debt Service Budget                       | number    | number      |
| Yes      | numeric metric | capital_projects_budget                   | Capital Projects Budget                   | number    | number      |
| Yes      | numeric metric | business_type_enterprise_budget           | Business Type / Enterprise Budget         | number    | number      |
| Yes      | numeric metric | transfers_out_total_budget                | Transfers Out Total Budget                | number    | number      |
| Yes      | numeric metric | total_budget                              | Total Expenditures Budget                 | number    | number      |
| Yes      | numeric metric | public_safety_actual                      | Public Safety Actual                      | number    | number      |
| Yes      | numeric metric | public_works_actual                       | Public Works Actual                       | number    | number      |
| Yes      | numeric metric | health_and_social_services_actual         | Health and Social Services Actual         | number    | number      |
| Yes      | numeric metric | culture_and_recreation_actual             | Culture and Recreation Actual             | number    | number      |
| Yes      | numeric metric | community_and_economic_development_actual | Community and Economic Development Actual | number    | number      |
| Yes      | numeric metric | general_government_actual                 | General Government Actual                 | number    | number      |
| Yes      | numeric metric | debt_service_actual                       | Debt Service Actual                       | number    | number      |
| Yes      | numeric metric | capital_projects_actual                   | Capital Projects Actual                   | number    | number      |
| Yes      | numeric metric | business_type_enterprise_actual           | Business Type / Enterprise Actual         | number    | number      |
| Yes      | numeric metric | transfers_out_total                       | Transfers Out Total                       | number    | number      |
| Yes      | numeric metric | total_actual                              | Total Actual                              | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jy6h-2e5x d:2016-01-01T00:00:00.000Z t:city_name=PLANO t:gnis_feature_id=460204 t:county=APPANOOSE t:city_fips=1963345 t:city_code=04G023 t:county_code=4 m:capital_projects_budget=0 m:health_and_social_services_budget=0 m:business_type_enterprise_budget=0 m:community_and_economic_development_budget=0 m:general_government_budget=6591 m:public_works_budget=6317 m:transfers_out_total_budget=0 m:public_safety_budget=673 m:debt_service_budget=0 m:culture_and_recreation_budget=0 m:total_budget=13581

series e:jy6h-2e5x d:2016-01-01T00:00:00.000Z t:city_name="SPRING HILL" t:gnis_feature_id=461898 t:county=WARREN t:city_fips=1974685 t:city_code=91G881 t:county_code=91 m:capital_projects_budget=0 m:health_and_social_services_budget=0 m:business_type_enterprise_budget=0 m:community_and_economic_development_budget=0 m:general_government_budget=5140 m:public_works_budget=13428 m:transfers_out_total_budget=0 m:public_safety_budget=0 m:debt_service_budget=0 m:culture_and_recreation_budget=2500 m:total_budget=21068

series e:jy6h-2e5x d:2017-01-01T00:00:00.000Z t:city_name=HARVEY t:gnis_feature_id=457308 t:county=MARION t:city_fips=1934860 t:city_code=63G596 t:county_code=63 m:capital_projects_budget=0 m:health_and_social_services_budget=0 m:business_type_enterprise_budget=80000 m:community_and_economic_development_budget=0 m:general_government_budget=19200 m:public_works_budget=28000 m:transfers_out_total_budget=0 m:public_safety_budget=5100 m:debt_service_budget=0 m:culture_and_recreation_budget=11500 m:total_budget=143800
```

## Meta Commands

```ls
metric m:public_safety_budget p:integer l:"Public Safety Budget" d:"Budgeted expenditure total of all public safety functions of the city during the budget fiscal year." t:dataTypeName=number

metric m:public_works_budget p:integer l:"Public Works Budget" d:"Budgeted expenditure total of all public works functions of the city during the budget fiscal year." t:dataTypeName=number

metric m:health_and_social_services_budget p:integer l:"Health and Social Services Budget" d:"Budgeted expenditure total of all public heath and social service functions of the city during the budget fiscal year." t:dataTypeName=number

metric m:culture_and_recreation_budget p:integer l:"Culture and Recreation Budget" d:"Budgeted expenditure total of all recreation or culture-focused functions of the city during the budget fiscal year." t:dataTypeName=number

metric m:community_and_economic_development_budget p:integer l:"Community and Economic Development Budget" d:"Budgeted expenditure total of all economic or community improvement functions of the city during the budget fiscal year." t:dataTypeName=number

metric m:general_government_budget p:integer l:"General Government Budget" d:"Budgeted expenditure total of general administrative functions of the city during the budget fiscal year." t:dataTypeName=number

metric m:debt_service_budget p:integer l:"Debt Service Budget" d:"Budgeted expenditure total of all payments to outstanding debts of the city during the budget fiscal year." t:dataTypeName=number

metric m:capital_projects_budget p:integer l:"Capital Projects Budget" d:"Budgeted expenditure total of all higher cost, non-yearly project work of the city during the budget fiscal year." t:dataTypeName=number

metric m:business_type_enterprise_budget p:integer l:"Business Type / Enterprise Budget" d:"Budgeted expenditure total of all fee-supported programs during the budget fiscal year. Examples: Water/Sewer/Gas/Electric/Telecom utilities, Parking systems, etc..." t:dataTypeName=number

metric m:transfers_out_total_budget p:integer l:"Transfers Out Total Budget" d:"Total of all budgeted fund to fund transfers for the year. This expenditure total does not leave the city." t:dataTypeName=number

metric m:total_budget p:integer l:"Total Expenditures Budget" d:"Total of all budgeted expenditures and internal transfers for the budget fiscal year." t:dataTypeName=number

metric m:public_safety_actual p:integer l:"Public Safety Actual" d:"Actual total of all public safety expenditures of the city during the fiscal year. Self reported by the city at year end." t:dataTypeName=number

metric m:public_works_actual p:integer l:"Public Works Actual" d:"Actual total of all public works expenditures of the city during the fiscal year. Self reported by the city at year end." t:dataTypeName=number

metric m:health_and_social_services_actual p:integer l:"Health and Social Services Actual" d:"Actual total of all public health and social service expenditures of the city during the fiscal year. Self reported by the city at year end." t:dataTypeName=number

metric m:culture_and_recreation_actual p:integer l:"Culture and Recreation Actual" d:"Actual total of all recreation and cultural purpose expenditures of the city during the fiscal year. Self reported by the city at year end." t:dataTypeName=number

metric m:community_and_economic_development_actual p:integer l:"Community and Economic Development Actual" d:"Actual total of all economic and community improvement expenditures of the city during the fiscal year. Self reported by the city at year end." t:dataTypeName=number

metric m:general_government_actual p:integer l:"General Government Actual" d:"Actual total of all general administration expenditures of the city during the fiscal year. Self reported by the city at year end." t:dataTypeName=number

metric m:debt_service_actual p:integer l:"Debt Service Actual" d:"Actual total of all expenditures toward paying the outstanding debts of the city during the fiscal year. Self reported by the city at year end." t:dataTypeName=number

metric m:capital_projects_actual p:integer l:"Capital Projects Actual" d:"Actual total of all expenditures toward higher cost, non-yearly projects of the city during the fiscal year. Self reported by the city at year end." t:dataTypeName=number

metric m:business_type_enterprise_actual p:integer l:"Business Type / Enterprise Actual" d:"Actual total of all expenditures toward fee-supported programs of the city during the fiscal year. Self reported by the city at year end." t:dataTypeName=number

metric m:transfers_out_total p:integer l:"Transfers Out Total" d:"Actual total of all internal transfers of funds in the city during the fiscal year. Self reported by the city at year end." t:dataTypeName=number

metric m:total_actual p:integer l:"Total Actual" d:"Total actual expenditures and internal transfers of the city during the fiscal year. Self-reported by the city at fiscal year end." t:dataTypeName=number

entity e:jy6h-2e5x l:"City Budget and Actual Expenditures" t:attribution="Ted Nellesen, Department of Management" t:url=https://data.iowa.gov/api/views/jy6h-2e5x

property e:jy6h-2e5x t:meta.view v:id=jy6h-2e5x v:category=Government v:attributionLink=https://dom.iowa.gov/cities v:averageRating=0 v:name="City Budget and Actual Expenditures" v:attribution="Ted Nellesen, Department of Management"

property e:jy6h-2e5x t:meta.view.owner v:id=58aa-5akg v:profileImageUrlMedium=/api/users/58aa-5akg/profile_images/THUMB v:profileImageUrlLarge=/api/users/58aa-5akg/profile_images/LARGE v:screenName="IDOM, Local Budget & Finance" v:profileImageUrlSmall=/api/users/58aa-5akg/profile_images/TINY v:displayName="IDOM, Local Budget & Finance"

property e:jy6h-2e5x t:meta.view.tableauthor v:id=58aa-5akg v:profileImageUrlMedium=/api/users/58aa-5akg/profile_images/THUMB v:profileImageUrlLarge=/api/users/58aa-5akg/profile_images/LARGE v:screenName="IDOM, Local Budget & Finance" v:profileImageUrlSmall=/api/users/58aa-5akg/profile_images/TINY v:roleName=editor v:displayName="IDOM, Local Budget & Finance"
```

## Top Records

```ls
| fiscal_year | county_code | county    | gnis_feature_id | city_fips | city_code | city_name   | public_safety_budget | public_works_budget | health_and_social_services_budget | culture_and_recreation_budget | community_and_economic_development_budget | general_government_budget | debt_service_budget | capital_projects_budget | business_type_enterprise_budget | transfers_out_total_budget | total_budget | public_safety_actual | public_works_actual | health_and_social_services_actual | culture_and_recreation_actual | community_and_economic_development_actual | general_government_actual | debt_service_actual | capital_projects_actual | business_type_enterprise_actual | transfers_out_total | total_actual | 
| =========== | =========== | ========= | =============== | ========= | ========= | =========== | ==================== | =================== | ================================= | ============================= | ========================================= | ========================= | =================== | ======================= | =============================== | ========================== | ============ | ==================== | =================== | ================================= | ============================= | ========================================= | ========================= | =================== | ======================= | =============================== | =================== | ============ | 
| 2016        | 4           | APPANOOSE | 460204          | 1963345   | 04G023    | PLANO       | 673                  | 6317                | 0                                 | 0                             | 0                                         | 6591                      | 0                   | 0                       | 0                               | 0                          | 13581        |                      |                     |                                   |                               |                                           |                           |                     |                         |                                 |                     |              | 
| 2016        | 91          | WARREN    | 461898          | 1974685   | 91G881    | SPRING HILL | 0                    | 13428               | 0                                 | 2500                          | 0                                         | 5140                      | 0                   | 0                       | 0                               | 0                          | 21068        |                      |                     |                                   |                               |                                           |                           |                     |                         |                                 |                     |              | 
| 2017        | 63          | MARION    | 457308          | 1934860   | 63G596    | HARVEY      | 5100                 | 28000               | 0                                 | 11500                         | 0                                         | 19200                     | 0                   | 0                       | 80000                           | 0                          | 143800       |                      |                     |                                   |                               |                                           |                           |                     |                         |                                 |                     |              | 
| 2017        | 36          | FREMONT   | 457781          | 1938055   | 36G340    | IMOGENE     | 1634                 | 10211               | 0                                 | 1060                          | 2000                                      | 10100                     | 0                   | 0                       | 0                               | 0                          | 25005        |                      |                     |                                   |                               |                                           |                           |                     |                         |                                 |                     |              | 
| 2017        | 54          | KEOKUK    | 458099          | 1941475   | 54G508    | KINROSS     | 200                  | 4500                | 0                                 | 100                           | 100                                       | 15650                     | 0                   | 0                       | 0                               | 0                          | 20550        |                      |                     |                                   |                               |                                           |                           |                     |                         |                                 |                     |              | 
| 2016        | 54          | KEOKUK    | 458099          | 1941475   | 54G508    | KINROSS     | 150                  | 9100                | 0                                 | 2050                          | 500                                       | 7100                      | 0                   | 0                       | 0                               | 0                          | 18900        |                      |                     |                                   |                               |                                           |                           |                     |                         |                                 |                     |              | 
| 2016        | 48          | IOWA      | 460031          | 1961770   | 48G445    | PARNELL     | 3582                 | 30500               | 0                                 | 3350                          | 2993                                      | 22200                     | 0                   | 0                       | 31000                           | 0                          | 93625        |                      |                     |                                   |                               |                                           |                           |                     |                         |                                 |                     |              | 
| 2016        | 67          | MONONA    | 462360          | 1979185   | 67G638    | TURIN       | 500                  | 10975               | 0                                 | 0                             | 5000                                      | 5375                      | 0                   | 0                       | 0                               | 0                          | 21850        |                      |                     |                                   |                               |                                           |                           |                     |                         |                                 |                     |              | 
| 2017        | 90          | WAPELLO   | 454105          | 1900640   | 90G862    | AGENCY      | 10000                | 218750              | 1000                              | 50000                         | 0                                         | 77490                     | 0                   | 0                       | 208200                          | 0                          | 565440       |                      |                     |                                   |                               |                                           |                           |                     |                         |                                 |                     |              | 
| 2017        | 27          | DECATUR   | 458257          | 1944580   | 27G252    | LE ROY      | 290                  | 3325                | 0                                 | 0                             | 600                                       | 2050                      | 0                   | 0                       | 0                               | 0                          | 6265         |                      |                     |                                   |                               |                                           |                           |                     |                         |                                 |                     |              | 
```