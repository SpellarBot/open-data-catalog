# New York State Executive Budget Appropriations: 2015-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-executive-budget-appropriations-2015-2016) |
| Metadata | [Link](https://data.ny.gov/api/views/nkdr-eaaf) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/nkdr-eaaf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/nkdr-eaaf/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | nkdr-eaaf |
| Name | New York State Executive Budget Appropriations: 2015-2016 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Tags | appropriation, ftes |
| Created | 2015-01-21T18:55:40Z |
| Publication Date | 2015-01-21T19:07:00Z |

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
| Yes      | numeric metric | appropriations_available_2014_15     | Appropriations Available 2014-15     | money     | money       |
| Yes      | numeric metric | appropriations_recommended_2015_16   | Appropriations Recommended 2015-16   | money     | money       |
| Yes      | numeric metric | reappropriations_recommended_2015_16 | Reappropriations Recommended 2015-16 | money     | money       |
| Yes      | numeric metric | estimated_ftes_03_31_2015            | Estimated FTEs 03/31/2015            | number    | number      |
| Yes      | numeric metric | estimated_ftes_03_31_2016            | Estimated FTEs 03/31/2016            | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nkdr-eaaf d:2015-01-01T00:00:00.000Z t:fund_name="State Operations Account" t:fund_type="General Fund" t:subfund_name="State Purposes Account" t:program_name="Abandoned Property Contingency Reserve" t:appropriation_category="State Operations" t:agency_name="Abandoned Property Contingency Reserve" t:subfund=10050 m:appropriations_recommended_2015_16=100000000 m:appropriations_available_2014_15=0 m:reappropriations_recommended_2015_16=0 m:estimated_ftes_03_31_2016=0 m:estimated_ftes_03_31_2015=0

series e:nkdr-eaaf d:2015-01-01T00:00:00.000Z t:fund_name="State Operations Account" t:fund_type="General Fund" t:subfund_name="State Purposes Account" t:program_name=Administration t:appropriation_category="State Operations" t:agency_name="Adirondack Park Agency" t:subfund=10050 m:appropriations_recommended_2015_16=4563000 m:appropriations_available_2014_15=4385400 m:reappropriations_recommended_2015_16=0 m:estimated_ftes_03_31_2016=54 m:estimated_ftes_03_31_2015=54

series e:nkdr-eaaf d:2015-01-01T00:00:00.000Z t:fund_name="Federal Miscellaneous Operating Grants Fund" t:fund_type="Special Revenue Funds - Federal" t:subfund_name="APA - Wetlands Mapping" t:program_name=Administration t:appropriation_category="State Operations" t:agency_name="Adirondack Park Agency" t:subfund=25327 m:appropriations_recommended_2015_16=700000 m:appropriations_available_2014_15=700000 m:reappropriations_recommended_2015_16=3410000 m:estimated_ftes_03_31_2016=0 m:estimated_ftes_03_31_2015=0
```

## Meta Commands

```ls
metric m:appropriations_available_2014_15 p:long l:"Appropriations Available 2014-15" d:"Appropriations available for the current fiscal year" t:dataTypeName=money

metric m:appropriations_recommended_2015_16 p:long l:"Appropriations Recommended 2015-16" d:"Appropriations recommended in the Executive Budget" t:dataTypeName=money

metric m:reappropriations_recommended_2015_16 p:long l:"Reappropriations Recommended 2015-16" d:"Reappropriations recommended in the Executive Budget" t:dataTypeName=money

metric m:estimated_ftes_03_31_2015 p:integer l:"Estimated FTEs 03/31/2015" d:"Workforce FTE estimate for end of current fiscal year" t:dataTypeName=number

metric m:estimated_ftes_03_31_2016 p:integer l:"Estimated FTEs 03/31/2016" d:"Workforce FTE estimate for end of next fiscal year" t:dataTypeName=number

entity e:nkdr-eaaf l:"New York State Executive Budget Appropriations: 2015-2016" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/nkdr-eaaf

property e:nkdr-eaaf t:meta.view v:id=nkdr-eaaf v:category="Government & Finance" v:attributionLink=http://openbudget.ny.gov/ v:averageRating=0 v:name="New York State Executive Budget Appropriations: 2015-2016" v:attribution="Division of the Budget"

property e:nkdr-eaaf t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:nkdr-eaaf t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:nkdr-eaaf t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| agency_name                            | fund_type                       | fund_name                                   | subfund | subfund_name                           | program_name                           | appropriation_category | appropriations_available_2014_15 | appropriations_recommended_2015_16 | reappropriations_recommended_2015_16 | estimated_ftes_03_31_2015 | estimated_ftes_03_31_2016 | 
| ====================================== | =============================== | =========================================== | ======= | ====================================== | ====================================== | ====================== | ================================ | ================================== | ==================================== | ========================= | ========================= | 
| Abandoned Property Contingency Reserve | General Fund                    | State Operations Account                    | 10050   | State Purposes Account                 | Abandoned Property Contingency Reserve | State Operations       | 0                                | 100000000                          | 0                                    | 0                         | 0                         | 
| Adirondack Park Agency                 | General Fund                    | State Operations Account                    | 10050   | State Purposes Account                 | Administration                         | State Operations       | 4385400                          | 4563000                            | 0                                    | 54                        | 54                        | 
| Adirondack Park Agency                 | Special Revenue Funds - Federal | Federal Miscellaneous Operating Grants Fund | 25327   | APA - Wetlands Mapping                 | Administration                         | State Operations       | 700000                           | 700000                             | 3410000                              | 0                         | 0                         | 
| Aging, Office for the                  | Enterprise Funds                | Agency Enterprise                           | 50303   | Aging Enterprises                      | Administration and Grants Management   | State Operations       | 100000                           | 100000                             | 0                                    | 0                         | 0                         | 
| Aging, Office for the                  | General Fund                    | Local Assistance Account                    | 10000   | Local Assistance Account               | Community Services                     | Aid To Localities      | 121197000                        | 126458500                          | 38341000                             | 0                         | 0                         | 
| Aging, Office for the                  | General Fund                    | State Operations Account                    | 10050   | State Purposes Account                 | Administration and Grants Management   | State Operations       | 1439000                          | 1311000                            | 0                                    | 19                        | 12                        | 
| Aging, Office for the                  | Special Revenue Funds - Federal | Federal Block Grants Fund                   | 252R1   | V642B-LIEA02-TADA                      | Administration and Grants Management   | State Operations       | 0                                | 0                                  | 0                                    | 2                         | 2                         | 
| Aging, Office for the                  | Special Revenue Funds - Federal | Federal Health and Human Services Fund      | 25100   | Federal Health and Human Services Fund | Administration and Grants Management   | State Operations       | 0                                | 0                                  | 0                                    | 72                        | 79                        | 
| Aging, Office for the                  | Special Revenue Funds - Federal | Federal Health and Human Services Fund      | 25177   | D2202P1-01370-AGING                    | Administration and Grants Management   | State Operations       | 8161000                          | 8161000                            | 13616000                             | 0                         | 0                         | 
| Aging, Office for the                  | Special Revenue Funds - Federal | Federal Health and Human Services Fund      | 25177   | D2202P1-01370-AGING                    | Community Services                     | Aid To Localities      | 105385000                        | 105385000                          | 163084000                            | 0                         | 0                         | 
```