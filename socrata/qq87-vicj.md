# New York State Executive Budget Appropriations: 2013-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-executive-budget-appropriations-2013-2014) |
| Metadata | [Link](https://data.ny.gov/api/views/qq87-vicj) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/qq87-vicj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/qq87-vicj/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | qq87-vicj |
| Name | New York State Executive Budget Appropriations: 2013-2014 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Tags | appropriation, ftes |
| Created | 2013-02-19T18:48:36Z |
| Publication Date | 2016-05-13T21:39:37Z |

## Description

This data set includes 2013-14 Executive Budget appropriations, reappropriations and workforce levels for the current State fiscal year and upcoming budget year.

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
| Yes      | numeric metric | appropriations_available_2012_13     | Appropriations Available 2012-13     | money     | money       |
| Yes      | numeric metric | appropriations_recommended_2013_14   | Appropriations Recommended 2013-14   | money     | money       |
| Yes      | numeric metric | reappropriations_recommended_2013_14 | Reappropriations Recommended 2013-14 | money     | money       |
| Yes      | numeric metric | estimated_ftes_03_31_2013            | Estimated FTEs 03/31/2013            | number    | number      |
| Yes      | numeric metric | estimated_ftes_03_31_2014            | Estimated FTEs 03/31/2014            | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qq87-vicj d:2013-01-01T00:00:00.000Z t:fund_name="State Exposition Special Fund" t:fund_type="Enterprise Funds" t:subfund_name="State Fair Account" t:program_name=Technology t:appropriation_category="State Operations" t:agency_name="Information Technology Services, Office of" t:subfund=50051 m:reappropriations_recommended_2013_14=0 m:appropriations_recommended_2013_14=0 m:appropriations_available_2012_13=0 m:estimated_ftes_03_31_2014=1 m:estimated_ftes_03_31_2013=1

series e:qq87-vicj d:2013-01-01T00:00:00.000Z t:fund_name="Local Assistance Account" t:fund_type="General Fund" t:subfund_name="Local Assistance Account" t:program_name="Employment and Training" t:appropriation_category="Aid To Localities" t:agency_name="Labor, Department of" t:subfund=10000 m:reappropriations_recommended_2013_14=28732000 m:appropriations_recommended_2013_14=0 m:appropriations_available_2012_13=4450000 m:estimated_ftes_03_31_2014=0 m:estimated_ftes_03_31_2013=0

series e:qq87-vicj d:2013-01-01T00:00:00.000Z t:fund_name="Local Assistance Account" t:fund_type="General Fund" t:subfund_name="Local Assistance Account" t:program_name="STARC Payment" t:appropriation_category="Aid To Localities" t:agency_name="Payments to STARC / NYC" t:subfund=10000 m:reappropriations_recommended_2013_14=0 m:appropriations_recommended_2013_14=170000000 m:appropriations_available_2012_13=170000000 m:estimated_ftes_03_31_2014=0 m:estimated_ftes_03_31_2013=0
```

## Meta Commands

```ls
metric m:appropriations_available_2012_13 p:long l:"Appropriations Available 2012-13" d:"Appropriations available for the current fiscal year" t:dataTypeName=money

metric m:appropriations_recommended_2013_14 p:long l:"Appropriations Recommended 2013-14" d:"Appropriations recommended in the Executive Budget" t:dataTypeName=money

metric m:reappropriations_recommended_2013_14 p:long l:"Reappropriations Recommended 2013-14" d:"Reappropriations recommended in the Executive" t:dataTypeName=money

metric m:estimated_ftes_03_31_2013 p:integer l:"Estimated FTEs 03/31/2013" d:"Workforce FTE estimate for end of current fiscal year" t:dataTypeName=number

metric m:estimated_ftes_03_31_2014 p:integer l:"Estimated FTEs 03/31/2014" d:"Workforce FTE estimate for end of next fiscal year" t:dataTypeName=number

entity e:qq87-vicj l:"New York State Executive Budget Appropriations: 2013-2014" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/qq87-vicj

property e:qq87-vicj t:meta.view v:id=qq87-vicj v:category="Government & Finance" v:attributionLink=http://openbudget.ny.gov/ v:averageRating=0 v:name="New York State Executive Budget Appropriations: 2013-2014" v:attribution="Division of the Budget"

property e:qq87-vicj t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:qq87-vicj t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:qq87-vicj t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| agency_name                                | fund_type                       | fund_name                                   | subfund | subfund_name                       | program_name                         | appropriation_category | appropriations_available_2012_13 | appropriations_recommended_2013_14 | reappropriations_recommended_2013_14 | estimated_ftes_03_31_2013 | estimated_ftes_03_31_2014 | 
| ========================================== | =============================== | =========================================== | ======= | ================================== | ==================================== | ====================== | ================================ | ================================== | ==================================== | ========================= | ========================= | 
| Information Technology Services, Office of | Enterprise Funds                | State Exposition Special Fund               | 50051   | State Fair Account                 | Technology                           | State Operations       | 0                                | 0                                  | 0                                    | 1                         | 1                         | 
| Labor, Department of                       | General Fund                    | Local Assistance Account                    | 10000   | Local Assistance Account           | Employment and Training              | Aid To Localities      | 4450000                          | 0                                  | 28732000                             | 0                         | 0                         | 
| Payments to STARC / NYC                    | General Fund                    | Local Assistance Account                    | 10000   | Local Assistance Account           | STARC Payment                        | Aid To Localities      | 170000000                        | 170000000                          | 0                                    | 0                         | 0                         | 
| Green Thumb                                | General Fund                    | State Operations Account                    | 10050   | State Purposes Account             | Green Thumb Program                  | State Operations       | 2831000                          | 2831000                            | 0                                    | 0                         | 0                         | 
| Agriculture and Markets, Department of     | General Fund                    | State Operations Account                    | 10050   | State Purposes Account             | Administration                       | State Operations       | 6640000                          | 7541000                            | 3920000                              | 72                        | 72                        | 
| Adirondack Park Agency                     | General Fund                    | State Operations Account                    | 10050   | State Purposes Account             | Administration                       | State Operations       | 4386000                          | 4385400                            | 0                                    | 54                        | 54                        | 
| Adirondack Park Agency                     | Special Revenue Funds - Federal | Federal Miscellaneous Operating Grants Fund | 25327   | APA - Wetlands Mapping             | Administration                       | State Operations       | 700000                           | 700000                             | 2200000                              | 0                         | 0                         | 
| Adirondack Park Agency                     | Special Revenue Funds - Federal | Federal Miscellaneous Operating Grants Fund | 253XH   | Transportation Enhancement Account | Administration                       | State Operations       | 0                                | 0                                  | 100000                               | 0                         | 0                         | 
| Aging, Office for the                      | Enterprise Funds                | Agency Enterprise                           | 50303   | Aging Enterprises                  | Administration and Grants Management | State Operations       | 100000                           | 100000                             | 0                                    | 0                         | 0                         | 
| Aging, Office for the                      | General Fund                    | Local Assistance Account                    | 10000   | Local Assistance Account           | Community Services                   | Aid To Localities      | 113904500                        | 112769500                          | 80372800                             | 0                         | 0                         | 
```