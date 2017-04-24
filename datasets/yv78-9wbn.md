# New York State Executive Budget Appropriations: 2017-2018

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-executive-budget-appropriations-2017-2018) |
| Metadata | [Link](https://data.ny.gov/api/views/yv78-9wbn) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/yv78-9wbn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/yv78-9wbn/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | yv78-9wbn |
| Name | New York State Executive Budget Appropriations: 2017-2018 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Tags | appropriation, ftes |
| Created | 2017-01-18T22:16:04Z |
| Publication Date | 2017-01-19T18:17:56Z |

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
| Yes      | numeric metric | appropriations_available_2016_17     | Appropriations Available 2016-17     | money     | money       |
| Yes      | numeric metric | appropriations_recommended_2017_18   | Appropriations Recommended 2017-18   | money     | money       |
| Yes      | numeric metric | reappropriations_recommended_2017_18 | Reappropriations Recommended 2017-18 | money     | money       |
| Yes      | numeric metric | estimated_ftes_03_31_2017            | Estimated FTEs 03/31/2017            | number    | number      |
| Yes      | numeric metric | estimated_ftes_03_31_2018            | Estimated FTEs 03/31/2018            | number    | number      |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:yv78-9wbn d:2017-01-01T00:00:00.000Z t:fund_name="State Operations Account" t:fund_type="General Fund" t:subfund_name="State Purposes Account" t:program_name="Additional Statewide Counter-Terrorism" t:appropriation_category="State Operations" t:agency_name="Additional Statewide Counter-Terrorism" t:subfund=10050 m:appropriations_available_2016_17=3000000 m:appropriations_recommended_2017_18=0 m:estimated_ftes_03_31_2018=0 m:estimated_ftes_03_31_2017=0 m:reappropriations_recommended_2017_18=3000000

series e:yv78-9wbn d:2017-01-01T00:00:00.000Z t:fund_name="State Operations Account" t:fund_type="General Fund" t:subfund_name="State Purposes Account" t:program_name=Administration t:appropriation_category="State Operations" t:agency_name="Adirondack Park Agency" t:subfund=10050 m:appropriations_available_2016_17=4474000 m:appropriations_recommended_2017_18=4444000 m:estimated_ftes_03_31_2018=54 m:estimated_ftes_03_31_2017=54 m:reappropriations_recommended_2017_18=0

series e:yv78-9wbn d:2017-01-01T00:00:00.000Z t:fund_name="Federal Miscellaneous Operating Grants Fund" t:fund_type="Special Revenue Funds - Federal" t:subfund_name="APA - Wetlands Mapping" t:program_name=Administration t:appropriation_category="State Operations" t:agency_name="Adirondack Park Agency" t:subfund=25327 m:appropriations_available_2016_17=500000 m:appropriations_recommended_2017_18=200000 m:estimated_ftes_03_31_2018=0 m:estimated_ftes_03_31_2017=0 m:reappropriations_recommended_2017_18=1707000
```

## Meta Commands

```ls
metric m:appropriations_available_2016_17 p:long l:"Appropriations Available 2016-17" d:"Appropriations available for the current fiscal year" t:dataTypeName=money

metric m:appropriations_recommended_2017_18 p:long l:"Appropriations Recommended 2017-18" d:"Appropriations recommended in the Executive Budget" t:dataTypeName=money

metric m:reappropriations_recommended_2017_18 p:long l:"Reappropriations Recommended 2017-18" d:"Reappropriations recommended in the Executive Budget" t:dataTypeName=money

metric m:estimated_ftes_03_31_2017 p:integer l:"Estimated FTEs 03/31/2017" d:"Workforce FTE estimate for end of current fiscal year" t:dataTypeName=number

metric m:estimated_ftes_03_31_2018 p:integer l:"Estimated FTEs 03/31/2018" d:"Workforce FTE estimate for end of next fiscal year" t:dataTypeName=number

entity e:yv78-9wbn l:"New York State Executive Budget Appropriations: 2017-2018" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/yv78-9wbn

property e:yv78-9wbn t:meta.view v:id=yv78-9wbn v:category="Government & Finance" v:attributionLink=http://openbudget.ny.gov/ v:averageRating=0 v:name="New York State Executive Budget Appropriations: 2017-2018" v:attribution="Division of the Budget"

property e:yv78-9wbn t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:yv78-9wbn t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| agency_name                            | fund_type                       | fund_name                                   | subfund | subfund_name                           | program_name                           | appropriation_category | appropriations_available_2016_17 | appropriations_recommended_2017_18 | reappropriations_recommended_2017_18 | estimated_ftes_03_31_2017 | estimated_ftes_03_31_2018 | 
| ====================================== | =============================== | =========================================== | ======= | ====================================== | ====================================== | ====================== | ================================ | ================================== | ==================================== | ========================= | ========================= | 
| Additional Statewide Counter-Terrorism | General Fund                    | State Operations Account                    | 10050   | State Purposes Account                 | Additional Statewide Counter-Terrorism | State Operations       | 3000000                          | 0                                  | 3000000                              | 0                         | 0                         | 
| Adirondack Park Agency                 | General Fund                    | State Operations Account                    | 10050   | State Purposes Account                 | Administration                         | State Operations       | 4474000                          | 4444000                            | 0                                    | 54                        | 54                        | 
| Adirondack Park Agency                 | Special Revenue Funds - Federal | Federal Miscellaneous Operating Grants Fund | 25327   | APA - Wetlands Mapping                 | Administration                         | State Operations       | 500000                           | 200000                             | 1707000                              | 0                         | 0                         | 
| Aging, Office for the                  | Enterprise Funds                | Agency Enterprise                           | 50303   | Aging Enterprises                      | Administration and Grants Management   | State Operations       | 100000                           | 100000                             | 0                                    | 0                         | 0                         | 
| Aging, Office for the                  | General Fund                    | Local Assistance Account                    | 10000   | Local Assistance Account               | Community Services                     | Aid To Localities      | 132883000                        | 120189500                          | 116869800                            | 0                         | 0                         | 
| Aging, Office for the                  | General Fund                    | State Operations Account                    | 10050   | State Purposes Account                 | Administration and Grants Management   | State Operations       | 1236000                          | 1236000                            | 0                                    | 12                        | 12                        | 
| Aging, Office for the                  | Special Revenue Funds - Federal | Federal Block Grants Fund                   | 252R1   | V642B-LIEA02-TADA                      | Administration and Grants Management   | State Operations       | 0                                | 0                                  | 0                                    | 2                         | 2                         | 
| Aging, Office for the                  | Special Revenue Funds - Federal | Federal Health and Human Services Fund      | 25100   | Federal Health and Human Services Fund | Administration and Grants Management   | State Operations       | 0                                | 0                                  | 0                                    | 79                        | 79                        | 
| Aging, Office for the                  | Special Revenue Funds - Federal | Federal Health and Human Services Fund      | 25177   | D2202P1-01370-AGING                    | Administration and Grants Management   | State Operations       | 8161000                          | 8161000                            | 8778000                              | 0                         | 0                         | 
| Aging, Office for the                  | Special Revenue Funds - Federal | Federal Health and Human Services Fund      | 25177   | D2202P1-01370-AGING                    | Community Services                     | Aid To Localities      | 105385000                        | 105385000                          | 164240000                            | 0                         | 0                         | 
```