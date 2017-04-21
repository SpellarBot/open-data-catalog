# New York State Enacted Budget Appropriations: 2013-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-enacted-budget-appropriations-2013-2014) |
| Metadata | [Link](https://data.ny.gov/api/views/wbuv-35mw) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/wbuv-35mw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/wbuv-35mw/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | wbuv-35mw |
| Name | New York State Enacted Budget Appropriations: 2013-2014 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Tags | appropriation, ftes, budget, enacted budget, integrity |
| Created | 2013-05-03T19:15:27Z |
| Publication Date | 2016-05-12T21:05:50Z |

## Description

This data set includes appropriation, reappropriations and workforce levels for the prior and current fiscal year as they relate to the 2013-14 Enacted Budget.

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
| Yes      | numeric metric | appropriations_available_2012_13 | Appropriations Available 2012-13 | money     | money       |
| Yes      | numeric metric | enacted_appropriations_2013_14   | Enacted Appropriations 2013-14   | money     | money       |
| Yes      | numeric metric | enacted_reappropriations_2013_14 | Enacted Reappropriations 2013-14 | money     | money       |
| Yes      | numeric metric | estimated_ftes_03_31_2013        | Estimated FTEs 03/31/2013        | number    | number      |
| Yes      | numeric metric | estimated_ftes_03_31_2014        | Estimated FTEs 03/31/2014        | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wbuv-35mw d:2013-01-01T00:00:00.000Z t:fund_name="State Operations Account" t:fund_type="General Fund" t:subfund_name="State Purposes Account" t:program_name=Administration t:appropriation_category="State Operations" t:agency_name="Adirondack Park Agency" t:subfund=10050 m:enacted_reappropriations_2013_14=0 m:enacted_appropriations_2013_14=4385400 m:appropriations_available_2012_13=4386000 m:estimated_ftes_03_31_2014=54 m:estimated_ftes_03_31_2013=54

series e:wbuv-35mw d:2013-01-01T00:00:00.000Z t:fund_name="Federal Miscellaneous Operating Grants Fund" t:fund_type="Special Revenue Funds - Federal" t:subfund_name="APA - Wetlands Mapping" t:program_name=Administration t:appropriation_category="State Operations" t:agency_name="Adirondack Park Agency" t:subfund=25327 m:enacted_reappropriations_2013_14=2200000 m:enacted_appropriations_2013_14=700000 m:appropriations_available_2012_13=700000 m:estimated_ftes_03_31_2014=0 m:estimated_ftes_03_31_2013=0

series e:wbuv-35mw d:2013-01-01T00:00:00.000Z t:fund_name="Federal Miscellaneous Operating Grants Fund" t:fund_type="Special Revenue Funds - Federal" t:subfund_name="Transportation Enhancement Account" t:program_name=Administration t:appropriation_category="State Operations" t:agency_name="Adirondack Park Agency" t:subfund=253XH m:enacted_reappropriations_2013_14=100000 m:enacted_appropriations_2013_14=0 m:appropriations_available_2012_13=0 m:estimated_ftes_03_31_2014=0 m:estimated_ftes_03_31_2013=0
```

## Meta Commands

```ls
metric m:appropriations_available_2012_13 p:long l:"Appropriations Available 2012-13" d:"Appropriations available for the prior fiscal year" t:dataTypeName=money

metric m:enacted_appropriations_2013_14 p:long l:"Enacted Appropriations 2013-14" d:"Enacted Appropriations for the current fiscal year" t:dataTypeName=money

metric m:enacted_reappropriations_2013_14 p:long l:"Enacted Reappropriations 2013-14" d:"Enacted Reappropriations for prior fiscal year" t:dataTypeName=money

metric m:estimated_ftes_03_31_2013 p:integer l:"Estimated FTEs 03/31/2013" d:"Workforce FTE estimate for end of prior fiscal year" t:dataTypeName=number

metric m:estimated_ftes_03_31_2014 p:integer l:"Estimated FTEs 03/31/2014" d:"Workforce FTE estimate for end of the current fiscal" t:dataTypeName=number

entity e:wbuv-35mw l:"New York State Enacted Budget Appropriations: 2013-2014" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/wbuv-35mw

property e:wbuv-35mw t:meta.view v:id=wbuv-35mw v:category="Government & Finance" v:attributionLink=http://openbudget.ny.gov/ v:averageRating=0 v:name="New York State Enacted Budget Appropriations: 2013-2014" v:attribution="Division of the Budget"

property e:wbuv-35mw t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:wbuv-35mw t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:wbuv-35mw t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| agency_name            | fund_type                       | fund_name                                   | subfund | subfund_name                           | program_name                         | appropriation_category | appropriations_available_2012_13 | enacted_appropriations_2013_14 | enacted_reappropriations_2013_14 | estimated_ftes_03_31_2013 | estimated_ftes_03_31_2014 | 
| ====================== | =============================== | =========================================== | ======= | ====================================== | ==================================== | ====================== | ================================ | ============================== | ================================ | ========================= | ========================= | 
| Adirondack Park Agency | General Fund                    | State Operations Account                    | 10050   | State Purposes Account                 | Administration                       | State Operations       | 4386000                          | 4385400                        | 0                                | 54                        | 54                        | 
| Adirondack Park Agency | Special Revenue Funds - Federal | Federal Miscellaneous Operating Grants Fund | 25327   | APA - Wetlands Mapping                 | Administration                       | State Operations       | 700000                           | 700000                         | 2200000                          | 0                         | 0                         | 
| Adirondack Park Agency | Special Revenue Funds - Federal | Federal Miscellaneous Operating Grants Fund | 253XH   | Transportation Enhancement Account     | Administration                       | State Operations       | 0                                | 0                              | 100000                           | 0                         | 0                         | 
| Aging, Office for the  | Enterprise Funds                | Agency Enterprise                           | 50303   | Aging Enterprises                      | Administration and Grants Management | State Operations       | 100000                           | 100000                         | 0                                | 0                         | 0                         | 
| Aging, Office for the  | General Fund                    | Community Projects Fund                     | 10253   | Community Projects Account CC          | Community Projects                   | Aid To Localities      | 0                                | 0                              | 41250                            | 0                         | 0                         | 
| Aging, Office for the  | General Fund                    | Local Assistance Account                    | 10000   | Local Assistance Account               | Community Services                   | Aid To Localities      | 113904500                        | 114069500                      | 81104920                         | 0                         | 0                         | 
| Aging, Office for the  | General Fund                    | State Operations Account                    | 10050   | State Purposes Account                 | Administration and Grants Management | State Operations       | 2722600                          | 1608000                        | 0                                | 19                        | 19                        | 
| Aging, Office for the  | Special Revenue Funds - Federal | Federal Block Grants Fund                   | 252R1   | V642B-LIEA02-TADA                      | Administration and Grants Management | State Operations       | 0                                | 0                              | 0                                | 5                         | 5                         | 
| Aging, Office for the  | Special Revenue Funds - Federal | Federal Health and Human Services Fund      | 25100   | Federal Health and Human Services Fund | Administration and Grants Management | State Operations       | 9394000                          | 9394000                        | 16794000                         | 70                        | 70                        | 
| Aging, Office for the  | Special Revenue Funds - Federal | Federal Health and Human Services Fund      | 25100   | Federal Health and Human Services Fund | Community Services                   | Aid To Localities      | 105385000                        | 105385000                      | 149242000                        | 0                         | 0                         | 
```