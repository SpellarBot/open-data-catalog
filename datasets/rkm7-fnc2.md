# New York State Enacted Budget Appropriations: 2014-2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-enacted-budget-appropriations-2014-2015) |
| Metadata | [Link](https://data.ny.gov/api/views/rkm7-fnc2) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/rkm7-fnc2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/rkm7-fnc2/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | rkm7-fnc2 |
| Name | New York State Enacted Budget Appropriations: 2014-2015 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Tags | appropriation, ftes, budget, enacted budget, integrity |
| Created | 2014-05-09T19:31:51Z |
| Publication Date | 2016-05-12T21:03:46Z |

## Description

This data set includes appropriation, reappropriations and workforce levels for the prior and current fiscal year as they relate to the 2014-15 Enacted Budget.

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
| Yes      | numeric metric | appropriations_available_2013_14 | Appropriations Available 2013-14 | money     | money       |
| Yes      | numeric metric | enacted_appropriations_2014_15   | Enacted Appropriations 2014-15   | money     | money       |
| Yes      | numeric metric | enacted_reappropriations_2014_15 | Enacted Reappropriations 2014-15 | money     | money       |
| Yes      | numeric metric | estimated_ftes_03_31_2014        | Estimated FTEs 03/31/2014        | number    | number      |
| Yes      | numeric metric | estimated_ftes_03_31_2015        | Estimated FTEs 03/31/2015        | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rkm7-fnc2 d:2014-01-01T00:00:00.000Z t:fund_name="State Operations Account" t:fund_type="General Fund" t:subfund_name="State Purposes Account" t:program_name="Election Enforcement" t:appropriation_category="State Operations" t:agency_name="Elections, State Board of" t:subfund=10050 m:appropriations_available_2013_14=0 m:enacted_appropriations_2014_15=4260000 m:enacted_reappropriations_2014_15=0 m:estimated_ftes_03_31_2015=29 m:estimated_ftes_03_31_2014=0

series e:rkm7-fnc2 d:2014-01-01T00:00:00.000Z t:fund_name="State Operations Account" t:fund_type="General Fund" t:subfund_name="State Purposes Account" t:program_name=Administration t:appropriation_category="State Operations" t:agency_name="Adirondack Park Agency" t:subfund=10050 m:appropriations_available_2013_14=4385400 m:enacted_appropriations_2014_15=4385400 m:enacted_reappropriations_2014_15=0 m:estimated_ftes_03_31_2015=54 m:estimated_ftes_03_31_2014=54

series e:rkm7-fnc2 d:2014-01-01T00:00:00.000Z t:fund_name="Federal Miscellaneous Operating Grants Fund" t:fund_type="Special Revenue Funds - Federal" t:subfund_name="APA - Wetlands Mapping" t:program_name=Administration t:appropriation_category="State Operations" t:agency_name="Adirondack Park Agency" t:subfund=25327 m:appropriations_available_2013_14=700000 m:enacted_appropriations_2014_15=700000 m:enacted_reappropriations_2014_15=2760000 m:estimated_ftes_03_31_2015=0 m:estimated_ftes_03_31_2014=0
```

## Meta Commands

```ls
metric m:appropriations_available_2013_14 p:long l:"Appropriations Available 2013-14" d:"Appropriations available for the prior fiscal year" t:dataTypeName=money

metric m:enacted_appropriations_2014_15 p:long l:"Enacted Appropriations 2014-15" d:"Enacted Appropriations for the current fiscal year" t:dataTypeName=money

metric m:enacted_reappropriations_2014_15 p:long l:"Enacted Reappropriations 2014-15" d:"Enacted Reappropriations for prior fiscal year" t:dataTypeName=money

metric m:estimated_ftes_03_31_2014 p:integer l:"Estimated FTEs 03/31/2014" d:"Workforce FTE estimate for end of prior fiscal year" t:dataTypeName=number

metric m:estimated_ftes_03_31_2015 p:integer l:"Estimated FTEs 03/31/2015" d:"Workforce FTE estimate for end of the current fiscal" t:dataTypeName=number

entity e:rkm7-fnc2 l:"New York State Enacted Budget Appropriations: 2014-2015" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/rkm7-fnc2

property e:rkm7-fnc2 t:meta.view v:id=rkm7-fnc2 v:category="Government & Finance" v:attributionLink=http://openbudget.ny.gov/ v:averageRating=0 v:name="New York State Enacted Budget Appropriations: 2014-2015" v:attribution="Division of the Budget"

property e:rkm7-fnc2 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:rkm7-fnc2 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:rkm7-fnc2 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| agency_name                 | fund_type                       | fund_name                                   | subfund | subfund_name                           | program_name                         | appropriation_category | appropriations_available_2013_14 | enacted_appropriations_2014_15 | enacted_reappropriations_2014_15 | estimated_ftes_03_31_2014 | estimated_ftes_03_31_2015 | 
| =========================== | =============================== | =========================================== | ======= | ====================================== | ==================================== | ====================== | ================================ | ============================== | ================================ | ========================= | ========================= | 
| Elections, State Board of   | General Fund                    | State Operations Account                    | 10050   | State Purposes Account                 | Election Enforcement                 | State Operations       | 0                                | 4260000                        | 0                                | 0                         | 29                        | 
| Adirondack Park Agency      | General Fund                    | State Operations Account                    | 10050   | State Purposes Account                 | Administration                       | State Operations       | 4385400                          | 4385400                        | 0                                | 54                        | 54                        | 
| Adirondack Park Agency      | Special Revenue Funds - Federal | Federal Miscellaneous Operating Grants Fund | 25327   | APA - Wetlands Mapping                 | Administration                       | State Operations       | 700000                           | 700000                         | 2760000                          | 0                         | 0                         | 
| Aging, Office for the       | Enterprise Funds                | Agency Enterprise                           | 50303   | Aging Enterprises                      | Administration and Grants Management | State Operations       | 100000                           | 100000                         | 0                                | 0                         | 0                         | 
| Aging, Office for the       | General Fund                    | Community Projects Fund                     | 10253   | Community Projects Account CC          | Community Projects                   | Aid To Localities      | 0                                | 0                              | 18750                            | 0                         | 0                         | 
| Aging, Office for the       | General Fund                    | Local Assistance Account                    | 10000   | Local Assistance Account               | Community Services                   | Aid To Localities      | 114069500                        | 121197000                      | 106072770                        | 0                         | 0                         | 
| Aging, Office for the       | General Fund                    | State Operations Account                    | 10050   | State Purposes Account                 | Administration and Grants Management | State Operations       | 1608000                          | 1439000                        | 0                                | 19                        | 19                        | 
| City University of New York | General Fund                    | Local Assistance Account                    | 10000   | Local Assistance Account               | Senior College Pension Payments      | Aid To Localities      | 2000000                          | 2000000                        | 0                                | 0                         | 0                         | 
| Aging, Office for the       | Special Revenue Funds - Federal | Federal Block Grants Fund                   | 252R1   | V642B-LIEA02-TADA                      | Administration and Grants Management | State Operations       | 0                                | 0                              | 0                                | 2                         | 2                         | 
| Aging, Office for the       | Special Revenue Funds - Federal | Federal Health and Human Services Fund      | 25100   | Federal Health and Human Services Fund | Administration and Grants Management | State Operations       | 0                                | 0                              | 17425000                         | 67                        | 72                        | 
```