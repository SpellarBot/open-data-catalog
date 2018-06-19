# New York State Enacted Budget Appropriations (Non-Capital): 2016-2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-enacted-budget-appropriations-non-capital-2016-2017) |
| Metadata | [Link](https://data.ny.gov/api/views/q2z7-9eaw) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/q2z7-9eaw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/q2z7-9eaw/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | q2z7-9eaw |
| Name | New York State Enacted Budget Appropriations (Non-Capital): 2016-2017 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Tags | appropriation, ftes |
| Created | 2016-06-03T19:50:48Z |
| Publication Date | 2016-06-03T20:01:48Z |

## Description

This data set includes appropriation, reappropriations and workforce levels for the current State fiscal year and upcoming budget year, as they relate to the 2016-17 Enacted Budget.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| Yes      | series tag     | agency_name                      | Agency Name                      | text      | text        |
| Yes      | series tag     | fund_type                        | Fund Type                        | text      | text        |
| Yes      | series tag     | fund_name                        | Fund Name                        | text      | text        |
| Yes      | series tag     | subfund                          | Subfund                          | text      | text        |
| Yes      | series tag     | subfund_name                     | Subfund Name                     | text      | text        |
| Yes      | series tag     | program_name                     | Program Name                     | text      | text        |
| Yes      | series tag     | appropriation_category           | Appropriation Category           | text      | text        |
| Yes      | numeric metric | appropriations_available_2015_16 | Appropriations Available 2015-16 | number    | number      |
| Yes      | numeric metric | enacted_appropriations_2016_17   | Enacted Appropriations 2016-17   | number    | number      |
| Yes      | numeric metric | enacted_reappropriations_2016_17 | Enacted Reappropriations 2016-17 | number    | number      |
| Yes      | numeric metric | estimated_ftes_03_31_2016        | Estimated FTEs 03/31/2016        | number    | number      |
| Yes      | numeric metric | estimated_ftes_03_31_2017        | Estimated FTEs 03/31/2017        | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:q2z7-9eaw d:2016-01-01T00:00:00.000Z t:fund_name="State Operations Account" t:fund_type="General Fund" t:subfund_name="State Purposes Account" t:program_name="Abandoned Property Contingency Reserve" t:appropriation_category="State Operations" t:agency_name="Abandoned Property Contingency Reserve" t:subfund=10050 m:estimated_ftes_03_31_2017=0 m:estimated_ftes_03_31_2016=0 m:appropriations_available_2015_16=100000000 m:enacted_appropriations_2016_17=0 m:enacted_reappropriations_2016_17=0

series e:q2z7-9eaw d:2016-01-01T00:00:00.000Z t:fund_name="State Operations Account" t:fund_type="General Fund" t:subfund_name="State Purposes Account" t:program_name="Additional Statewide Counter - Terrorism" t:appropriation_category="State Operations" t:agency_name="Additional Statewide Counter-Terrorism" t:subfund=10050 m:estimated_ftes_03_31_2017=0 m:estimated_ftes_03_31_2016=0 m:appropriations_available_2015_16=0 m:enacted_appropriations_2016_17=3000000 m:enacted_reappropriations_2016_17=0

series e:q2z7-9eaw d:2016-01-01T00:00:00.000Z t:fund_name="State Operations Account" t:fund_type="General Fund" t:subfund_name="State Purposes Account" t:program_name=Administration t:appropriation_category="State Operations" t:agency_name="Adirondack Park Agency" t:subfund=10050 m:estimated_ftes_03_31_2017=54 m:estimated_ftes_03_31_2016=54 m:appropriations_available_2015_16=4563000 m:enacted_appropriations_2016_17=4344000 m:enacted_reappropriations_2016_17=0
```

## Meta Commands

```ls
metric m:appropriations_available_2015_16 p:long l:"Appropriations Available 2015-16" d:"Appropriations available for the current fiscal year" t:dataTypeName=number

metric m:enacted_appropriations_2016_17 p:long l:"Enacted Appropriations 2016-17" d:"Enacted Appropriations" t:dataTypeName=number

metric m:enacted_reappropriations_2016_17 p:long l:"Enacted Reappropriations 2016-17" d:"Enacted Reappropriations" t:dataTypeName=number

metric m:estimated_ftes_03_31_2016 p:integer l:"Estimated FTEs 03/31/2016" d:"Workforce FTE estimate for end of current fiscal year" t:dataTypeName=number

metric m:estimated_ftes_03_31_2017 p:integer l:"Estimated FTEs 03/31/2017" d:"Workforce FTE estimate for end of next fiscal year" t:dataTypeName=number

entity e:q2z7-9eaw l:"New York State Enacted Budget Appropriations (Non-Capital): 2016-2017" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/q2z7-9eaw

property e:q2z7-9eaw t:meta.view v:id=q2z7-9eaw v:category="Government & Finance" v:attributionLink=http://openbudget.ny.gov/ v:averageRating=0 v:name="New York State Enacted Budget Appropriations (Non-Capital): 2016-2017" v:attribution="Division of the Budget"

property e:q2z7-9eaw t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:q2z7-9eaw t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| agency_name                            | fund_type                       | fund_name                                   | subfund | subfund_name                           | program_name                             | appropriation_category | appropriations_available_2015_16 | enacted_appropriations_2016_17 | enacted_reappropriations_2016_17 | estimated_ftes_03_31_2016 | estimated_ftes_03_31_2017 | 
| ====================================== | =============================== | =========================================== | ======= | ====================================== | ======================================== | ====================== | ================================ | ============================== | ================================ | ========================= | ========================= | 
| Abandoned Property Contingency Reserve | General Fund                    | State Operations Account                    | 10050   | State Purposes Account                 | Abandoned Property Contingency Reserve   | State Operations       | 100000000                        | 0                              | 0                                | 0                         | 0                         | 
| Additional Statewide Counter-Terrorism | General Fund                    | State Operations Account                    | 10050   | State Purposes Account                 | Additional Statewide Counter - Terrorism | State Operations       | 0                                | 3000000                        | 0                                | 0                         | 0                         | 
| Adirondack Park Agency                 | General Fund                    | State Operations Account                    | 10050   | State Purposes Account                 | Administration                           | State Operations       | 4563000                          | 4344000                        | 0                                | 54                        | 54                        | 
| Adirondack Park Agency                 | Special Revenue Funds - Federal | Federal Miscellaneous Operating Grants Fund | 25327   | APA - Wetlands Mapping                 | Administration                           | State Operations       | 700000                           | 500000                         | 3917000                          | 0                         | 0                         | 
| Aging, Office for the                  | Enterprise Funds                | Agency Enterprise                           | 50303   | Aging Enterprises                      | Administration and Grants Management     | State Operations       | 100000                           | 100000                         | 0                                | 0                         | 0                         | 
| Aging, Office for the                  | General Fund                    | Local Assistance Account                    | 10000   | Local Assistance Account               | Community Services                       | Aid To Localities      | 130638000                        | 132883000                      | 79279000                         | 0                         | 0                         | 
| Aging, Office for the                  | General Fund                    | State Operations Account                    | 10050   | State Purposes Account                 | Administration and Grants Management     | State Operations       | 1311000                          | 1236000                        | 0                                | 12                        | 12                        | 
| Aging, Office for the                  | Special Revenue Funds - Federal | Federal Block Grants Fund                   | 252R1   | V642B-LIEA02-TADA                      | Administration and Grants Management     | State Operations       | 0                                | 0                              | 0                                | 2                         | 2                         | 
| Aging, Office for the                  | Special Revenue Funds - Federal | Federal Health and Human Services Fund      | 25100   | Federal Health and Human Services Fund | Administration and Grants Management     | State Operations       | 0                                | 0                              | 0                                | 79                        | 79                        | 
| Aging, Office for the                  | Special Revenue Funds - Federal | Federal Health and Human Services Fund      | 25177   | D2202P1-01370-AGING                    | Administration and Grants Management     | State Operations       | 8161000                          | 8161000                        | 13164000                         | 0                         | 0                         | 
```