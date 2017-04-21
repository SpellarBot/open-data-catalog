# New York State Executive Budget Appropriations: 2016-17

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-executive-budget-appropriations-2016-17) |
| Metadata | [Link](https://data.ny.gov/api/views/hxy8-46bu) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/hxy8-46bu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/hxy8-46bu/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | hxy8-46bu |
| Name | New York State Executive Budget Appropriations: 2016-17 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Tags | appropriation, ftes |
| Created | 2016-01-13T16:44:39Z |
| Publication Date | 2016-01-13T19:56:13Z |

## Description

This data set includes appropriation, reappropriations and workforce levels for the current State fiscal year and upcoming budget year.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | agency_name                          | Agency Name                          | text      | text        |
| Yes      | series tag     | fund_type                            | Fund Type                            | text      | text        |
| Yes      | series tag     | fund_name                            | Fund Name                            | text      | text        |
| Yes      | series tag     | subfund                              | Subfund                              | text      | text        |
| Yes      | series tag     | subfund_name                         | Subfund Name                         | text      | text        |
| Yes      | series tag     | program_name                         | Program Name                         | text      | text        |
| Yes      | series tag     | appropriation_category               | Appropriation Category               | text      | text        |
| Yes      | numeric metric | appropriations_available_2015_16     | Appropriations Available 2015-16     | money     | money       |
| Yes      | numeric metric | appropriations_recommended_2016_17   | Appropriations Recommended 2016-17   | money     | money       |
| Yes      | numeric metric | reappropriations_recommended_2016_17 | Reappropriations Recommended 2016-17 | money     | money       |
| Yes      | numeric metric | estimated_ftes_03_31_2016            | Estimated FTEs 03/31/2016            | number    | number      |
| Yes      | numeric metric | estimated_ftes_03_31_2017            | Estimated FTEs 03/31/2017            | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hxy8-46bu d:2016-01-01T00:00:00.000Z t:fund_name="Department of Health Income" t:fund_type="Debt Service Funds" t:subfund_name="Health Income Fund" t:program_name="Financing Agreements" t:appropriation_category="Debt Service" t:agency_name="Debt Service" t:subfund=40301 m:estimated_ftes_03_31_2017=0 m:estimated_ftes_03_31_2016=0 m:reappropriations_recommended_2016_17=0 m:appropriations_available_2015_16=31600000 m:appropriations_recommended_2016_17=33500000

series e:hxy8-46bu d:2016-01-01T00:00:00.000Z t:fund_name="State Operations Account" t:fund_type="General Fund" t:subfund_name="State Purposes Account" t:program_name="Uniform Code Enforcement" t:appropriation_category="State Operations" t:agency_name="State, Department of" t:subfund=10050 m:estimated_ftes_03_31_2017=0 m:estimated_ftes_03_31_2016=0 m:reappropriations_recommended_2016_17=700000 m:appropriations_available_2015_16=0 m:appropriations_recommended_2016_17=0

series e:hxy8-46bu d:2016-01-01T00:00:00.000Z t:fund_name="State Operations Account" t:fund_type="General Fund" t:subfund_name="State Purposes Account" t:program_name="Abandoned Property Contingency Reserve" t:appropriation_category="State Operations" t:agency_name="Abandoned Property Contingency Reserve" t:subfund=10050 m:estimated_ftes_03_31_2017=0 m:estimated_ftes_03_31_2016=0 m:reappropriations_recommended_2016_17=0 m:appropriations_available_2015_16=100000000 m:appropriations_recommended_2016_17=0
```

## Meta Commands

```ls
metric m:appropriations_available_2015_16 p:long l:"Appropriations Available 2015-16" d:"Appropriations available for the current fiscal year" t:dataTypeName=money

metric m:appropriations_recommended_2016_17 p:long l:"Appropriations Recommended 2016-17" d:"Appropriations recommended in the Executive Budget" t:dataTypeName=money

metric m:reappropriations_recommended_2016_17 p:long l:"Reappropriations Recommended 2016-17" d:"Reappropriations recommended in the Executive Budget" t:dataTypeName=money

metric m:estimated_ftes_03_31_2016 p:integer l:"Estimated FTEs 03/31/2016" d:"Workforce FTE estimate for end of current fiscal year" t:dataTypeName=number

metric m:estimated_ftes_03_31_2017 p:integer l:"Estimated FTEs 03/31/2017" d:"Workforce FTE estimate for end of next fiscal year" t:dataTypeName=number

entity e:hxy8-46bu l:"New York State Executive Budget Appropriations: 2016-17" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/hxy8-46bu

property e:hxy8-46bu t:meta.view v:id=hxy8-46bu v:category="Government & Finance" v:attributionLink=http://openbudget.ny.gov/ v:averageRating=0 v:name="New York State Executive Budget Appropriations: 2016-17" v:attribution="Division of the Budget"

property e:hxy8-46bu t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:hxy8-46bu t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| agency_name                            | fund_type                       | fund_name                                   | subfund | subfund_name             | program_name                             | appropriation_category | appropriations_available_2015_16 | appropriations_recommended_2016_17 | reappropriations_recommended_2016_17 | estimated_ftes_03_31_2016 | estimated_ftes_03_31_2017 | 
| ====================================== | =============================== | =========================================== | ======= | ======================== | ======================================== | ====================== | ================================ | ================================== | ==================================== | ========================= | ========================= | 
| Debt Service                           | Debt Service Funds              | Department of Health Income                 | 40301   | Health Income Fund       | Financing Agreements                     | Debt Service           | 31600000                         | 33500000                           | 0                                    | 0                         | 0                         | 
| State, Department of                   | General Fund                    | State Operations Account                    | 10050   | State Purposes Account   | Uniform Code Enforcement                 | State Operations       | 0                                | 0                                  | 700000                               | 0                         | 0                         | 
| Abandoned Property Contingency Reserve | General Fund                    | State Operations Account                    | 10050   | State Purposes Account   | Abandoned Property Contingency Reserve   | State Operations       | 100000000                        | 0                                  | 0                                    | 0                         | 0                         | 
| Additional Statewide Counter-Terrorism | General Fund                    | State Operations Account                    | 10050   | State Purposes Account   | Additional Statewide Counter - Terrorism | State Operations       | 0                                | 3000000                            | 0                                    | 0                         | 0                         | 
| Adirondack Park Agency                 | General Fund                    | State Operations Account                    | 10050   | State Purposes Account   | Administration                           | State Operations       | 4563000                          | 4344000                            | 0                                    | 54                        | 54                        | 
| Adirondack Park Agency                 | Special Revenue Funds - Federal | Federal Miscellaneous Operating Grants Fund | 25327   | APA - Wetlands Mapping   | Administration                           | State Operations       | 700000                           | 500000                             | 3917000                              | 0                         | 0                         | 
| Aging, Office for the                  | Enterprise Funds                | Agency Enterprise                           | 50303   | Aging Enterprises        | Administration and Grants Management     | State Operations       | 100000                           | 100000                             | 0                                    | 0                         | 0                         | 
| Aging, Office for the                  | General Fund                    | Local Assistance Account                    | 10000   | Local Assistance Account | Community Services                       | Aid To Localities      | 130638000                        | 129860500                          | 28102500                             | 0                         | 0                         | 
| Aging, Office for the                  | General Fund                    | State Operations Account                    | 10050   | State Purposes Account   | Administration and Grants Management     | State Operations       | 1311000                          | 1236000                            | 0                                    | 12                        | 12                        | 
| Aging, Office for the                  | Special Revenue Funds - Federal | Federal Block Grants Fund                   | 252R1   | V642B-LIEA02-TADA        | Administration and Grants Management     | State Operations       | 0                                | 0                                  | 0                                    | 2                         | 2                         | 
```