# New York State Executive Budget Appropriations (Non-Capital), as Amended: 2015-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-executive-budget-appropriations-with-executive-amendments-2015-2016) |
| Metadata | [Link](https://data.ny.gov/api/views/dpaa-qunx) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/dpaa-qunx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/dpaa-qunx/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | dpaa-qunx |
| Name | New York State Executive Budget Appropriations (Non-Capital), as Amended: 2015-2016 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Tags | appropriation, ftes, executive amendment |
| Created | 2015-03-04T20:52:42Z |
| Publication Date | 2015-03-04T21:05:20Z |

## Description

This data set includes appropriation, reappropriations and workforce levels for the current State fiscal year and upcoming budget year as they relate to the 2015-16 Executive Budget with Executive Amendments.

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
series e:dpaa-qunx d:2015-01-01T00:00:00.000Z t:fund_name="State Operations Account" t:fund_type="General Fund" t:subfund_name="State Purposes Account" t:program_name="Green Thumb Program" t:appropriation_category="State Operations" t:agency_name="Green Thumb" t:subfund=10050 m:appropriations_recommended_2015_16=3142000 m:appropriations_available_2014_15=2964000 m:reappropriations_recommended_2015_16=0 m:estimated_ftes_03_31_2016=0 m:estimated_ftes_03_31_2015=0

series e:dpaa-qunx d:2015-01-01T00:00:00.000Z t:fund_name="Local Assistance Account" t:fund_type="General Fund" t:subfund_name="Local Assistance Account" t:program_name=Administration t:appropriation_category="Aid To Localities" t:agency_name="Arts, Council on the" t:subfund=10000 m:appropriations_recommended_2015_16=0 m:appropriations_available_2014_15=0 m:reappropriations_recommended_2015_16=317000 m:estimated_ftes_03_31_2016=0 m:estimated_ftes_03_31_2015=0

series e:dpaa-qunx d:2015-01-01T00:00:00.000Z t:fund_name="State Operations Account" t:fund_type="General Fund" t:subfund_name="State Purposes Account" t:program_name=Administration t:appropriation_category="State Operations" t:agency_name="Law, Department of" t:subfund=10050 m:appropriations_recommended_2015_16=15307000 m:appropriations_available_2014_15=15307000 m:reappropriations_recommended_2015_16=0 m:estimated_ftes_03_31_2016=185 m:estimated_ftes_03_31_2015=185
```

## Meta Commands

```ls
metric m:appropriations_available_2014_15 p:long l:"Appropriations Available 2014-15" d:"Appropriations available for the current fiscal year" t:dataTypeName=money

metric m:appropriations_recommended_2015_16 p:long l:"Appropriations Recommended 2015-16" d:"Appropriations recommended in the Executive Budget with Executive Amendments" t:dataTypeName=money

metric m:reappropriations_recommended_2015_16 p:long l:"Reappropriations Recommended 2015-16" d:"Reappropriations recommended in the Executive Budget with Executive Amendments" t:dataTypeName=money

metric m:estimated_ftes_03_31_2015 p:integer l:"Estimated FTEs 03/31/2015" d:"Workforce FTE estimate for end of current fiscal year" t:dataTypeName=number

metric m:estimated_ftes_03_31_2016 p:integer l:"Estimated FTEs 03/31/2016" d:"Workforce FTE estimate for end of next fiscal year" t:dataTypeName=number

entity e:dpaa-qunx l:"New York State Executive Budget Appropriations (Non-Capital), as Amended: 2015-2016" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/dpaa-qunx

property e:dpaa-qunx t:meta.view v:id=dpaa-qunx v:category="Government & Finance" v:attributionLink=http://openbudget.ny.gov/ v:averageRating=0 v:name="New York State Executive Budget Appropriations (Non-Capital), as Amended: 2015-2016" v:attribution="Division of the Budget"

property e:dpaa-qunx t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:dpaa-qunx t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:dpaa-qunx t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| agency_name                            | fund_type                       | fund_name                    | subfund | subfund_name             | program_name                           | appropriation_category | appropriations_available_2014_15 | appropriations_recommended_2015_16 | reappropriations_recommended_2015_16 | estimated_ftes_03_31_2015 | estimated_ftes_03_31_2016 | 
| ====================================== | =============================== | ============================ | ======= | ======================== | ====================================== | ====================== | ================================ | ================================== | ==================================== | ========================= | ========================= | 
| Green Thumb                            | General Fund                    | State Operations Account     | 10050   | State Purposes Account   | Green Thumb Program                    | State Operations       | 2964000                          | 3142000                            | 0                                    | 0                         | 0                         | 
| Arts, Council on the                   | General Fund                    | Local Assistance Account     | 10000   | Local Assistance Account | Administration                         | Aid To Localities      | 0                                | 0                                  | 317000                               | 0                         | 0                         | 
| Law, Department of                     | General Fund                    | State Operations Account     | 10050   | State Purposes Account   | Administration                         | State Operations       | 15307000                         | 15307000                           | 0                                    | 185                       | 185                       | 
| Audit and Control, Department of       | General Fund                    | State Operations Account     | 10050   | State Purposes Account   | Administration                         | State Operations       | 13778000                         | 13778000                           | 0                                    | 111                       | 111                       | 
| Education Department, State            | Special Revenue Funds - Federal | Federal Education Fund       | 25210   | 11000-Education DOE      | Cultural Education                     | State Operations       | 0                                | 0                                  | 0                                    | 45                        | 45                        | 
| Human Rights, Division of              | General Fund                    | State Operations Account     | 10050   | State Purposes Account   | Administration                         | State Operations       | 12010000                         | 12010000                           | 0                                    | 124                       | 124                       | 
| Education Department, State            | Internal Service Funds          | Agency Internal Service Fund | 55052   | Archives Record Mgmt     | Cultural Education                     | State Operations       | 2124000                          | 2124000                            | 0                                    | 16                        | 16                        | 
| Adirondack Park Agency                 | General Fund                    | State Operations Account     | 10050   | State Purposes Account   | Administration                         | State Operations       | 4385400                          | 4563000                            | 0                                    | 54                        | 54                        | 
| Abandoned Property Contingency Reserve | General Fund                    | State Operations Account     | 10050   | State Purposes Account   | Abandoned Property Contingency Reserve | State Operations       | 0                                | 100000000                          | 0                                    | 0                         | 0                         | 
| Debt Service                           | General Fund                    | State Operations Account     | 10050   | State Purposes Account   | Rebates to Federal Government          | Debt Service           | 20000000                         | 20000000                           | 0                                    | 0                         | 0                         | 
```