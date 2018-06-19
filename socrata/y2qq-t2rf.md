# New York State Executive Budget Appropriations (Non-Capital), as Amended: 2016-2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-executive-budget-appropriations-non-capital-as-amended-2016-2017) |
| Metadata | [Link](https://data.ny.gov/api/views/y2qq-t2rf) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/y2qq-t2rf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/y2qq-t2rf/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | y2qq-t2rf |
| Name | New York State Executive Budget Appropriations (Non-Capital), as Amended: 2016-2017 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Created | 2016-02-18T19:57:11Z |
| Publication Date | 2016-02-18T20:30:18Z |

## Description

This data set includes appropriation, reappropriations and workforce levels for the current State fiscal year and upcoming budget year, as they relate to the 2016-17 Executive Budget with Executive Amendments.

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
series e:y2qq-t2rf d:2016-01-01T00:00:00.000Z t:fund_name="State Operations Account" t:fund_type="General Fund" t:subfund_name="State Purposes Account" t:program_name="Adult Services" t:appropriation_category="State Operations" t:agency_name="Mental Health, Office of" t:subfund=10050 m:estimated_ftes_03_31_2017=0 m:estimated_ftes_03_31_2016=0 m:reappropriations_recommended_2016_17=0 m:appropriations_available_2015_16=796000 m:appropriations_recommended_2016_17=796000

series e:y2qq-t2rf d:2016-01-01T00:00:00.000Z t:fund_name="State Operations Account" t:fund_type="General Fund" t:subfund_name="State Purposes Account" t:program_name=Operations t:appropriation_category="State Operations" t:agency_name="National and Community Service" t:subfund=10050 m:estimated_ftes_03_31_2017=0 m:estimated_ftes_03_31_2016=0 m:reappropriations_recommended_2016_17=0 m:appropriations_available_2015_16=333500 m:appropriations_recommended_2016_17=333500

series e:y2qq-t2rf d:2016-01-01T00:00:00.000Z t:fund_name="Debt Reduction Reserve Fund" t:fund_type="Debt Service Funds" t:subfund_name="Debt Reduction Reserve Fund" t:program_name="Debt Reduction" t:appropriation_category="Debt Service" t:agency_name="Debt Service" t:subfund=40000 m:estimated_ftes_03_31_2017=0 m:estimated_ftes_03_31_2016=0 m:reappropriations_recommended_2016_17=0 m:appropriations_available_2015_16=500000000 m:appropriations_recommended_2016_17=500000000
```

## Meta Commands

```ls
metric m:appropriations_available_2015_16 p:long l:"Appropriations Available 2015-16" d:"Appropriations available for the current fiscal year" t:dataTypeName=money

metric m:appropriations_recommended_2016_17 p:long l:"Appropriations Recommended 2016-17" d:"Appropriations recommended in the Executive Budget with Executive Amendments" t:dataTypeName=money

metric m:reappropriations_recommended_2016_17 p:long l:"Reappropriations Recommended 2016-17" d:"Reappropriations recommended in the Executive Budget with Executive Amendments" t:dataTypeName=money

metric m:estimated_ftes_03_31_2016 p:integer l:"Estimated FTEs 03/31/2016" d:"Workforce FTE estimate for end of current fiscal year" t:dataTypeName=number

metric m:estimated_ftes_03_31_2017 p:integer l:"Estimated FTEs 03/31/2017" d:"Workforce FTE estimate for end of next fiscal year" t:dataTypeName=number

entity e:y2qq-t2rf l:"New York State Executive Budget Appropriations (Non-Capital), as Amended: 2016-2017" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/y2qq-t2rf

property e:y2qq-t2rf t:meta.view v:id=y2qq-t2rf v:category="Government & Finance" v:attributionLink=http://openbudget.ny.gov/ v:averageRating=0 v:name="New York State Executive Budget Appropriations (Non-Capital), as Amended: 2016-2017" v:attribution="Division of the Budget"

property e:y2qq-t2rf t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:y2qq-t2rf t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| agency_name                            | fund_type                       | fund_name                                   | subfund | subfund_name                | program_name                             | appropriation_category | appropriations_available_2015_16 | appropriations_recommended_2016_17 | reappropriations_recommended_2016_17 | estimated_ftes_03_31_2016 | estimated_ftes_03_31_2017 | 
| ====================================== | =============================== | =========================================== | ======= | =========================== | ======================================== | ====================== | ================================ | ================================== | ==================================== | ========================= | ========================= | 
| Mental Health, Office of               | General Fund                    | State Operations Account                    | 10050   | State Purposes Account      | Adult Services                           | State Operations       | 796000                           | 796000                             | 0                                    | 0                         | 0                         | 
| National and Community Service         | General Fund                    | State Operations Account                    | 10050   | State Purposes Account      | Operations                               | State Operations       | 333500                           | 333500                             | 0                                    | 0                         | 0                         | 
| Debt Service                           | Debt Service Funds              | Debt Reduction Reserve Fund                 | 40000   | Debt Reduction Reserve Fund | Debt Reduction                           | Debt Service           | 500000000                        | 500000000                          | 0                                    | 0                         | 0                         | 
| State, Department of                   | General Fund                    | State Operations Account                    | 10050   | State Purposes Account      | Administration                           | State Operations       | 4156000                          | 4156000                            | 0                                    | 102                       | 102                       | 
| Abandoned Property Contingency Reserve | General Fund                    | State Operations Account                    | 10050   | State Purposes Account      | Abandoned Property Contingency Reserve   | State Operations       | 100000000                        | 0                                  | 0                                    | 0                         | 0                         | 
| Additional Statewide Counter-Terrorism | General Fund                    | State Operations Account                    | 10050   | State Purposes Account      | Additional Statewide Counter - Terrorism | State Operations       | 0                                | 3000000                            | 0                                    | 0                         | 0                         | 
| Adirondack Park Agency                 | General Fund                    | State Operations Account                    | 10050   | State Purposes Account      | Administration                           | State Operations       | 4563000                          | 4344000                            | 0                                    | 54                        | 54                        | 
| Adirondack Park Agency                 | Special Revenue Funds - Federal | Federal Miscellaneous Operating Grants Fund | 25327   | APA - Wetlands Mapping      | Administration                           | State Operations       | 700000                           | 500000                             | 3917000                              | 0                         | 0                         | 
| Aging, Office for the                  | Enterprise Funds                | Agency Enterprise                           | 50303   | Aging Enterprises           | Administration and Grants Management     | State Operations       | 100000                           | 100000                             | 0                                    | 0                         | 0                         | 
| Aging, Office for the                  | General Fund                    | Local Assistance Account                    | 10000   | Local Assistance Account    | Community Services                       | Aid To Localities      | 130638000                        | 129860500                          | 28102500                             | 0                         | 0                         | 
```