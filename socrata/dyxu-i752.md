# Short-term Occupational Projections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/short-term-occupational-projections) |
| Metadata | [Link](https://data.ny.gov/api/views/dyxu-i752) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/dyxu-i752/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/dyxu-i752/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | dyxu-i752 |
| Name | Short-term Occupational Projections |
| Attribution | New York State Department of Labor |
| Category | Economic Development |
| Tags | occupation, forecast, outlook, employment, projections |
| Created | 2014-09-03T16:13:22Z |
| Publication Date | 2016-03-03T17:21:50Z |

## Description

Short-term Occupational Projections for a 2 year time horizon are provided for the state and 10 labor market regions to provide individuals and organizations with an occupational outlook to make informed decisions.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                               | Data Type | Render Type |
| ======== | ============== | =========================== | ================================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                         | meta_data | meta_data   |
| Yes      | series tag     | area                        | Area                               | text      | text        |
| Yes      | series tag     | period                      | Period                             | text      | text        |
| Yes      | series tag     | occupation_code             | Occupation Code                    | text      | text        |
| Yes      | series tag     | occupation_title            | Occupation Title                   | text      | text        |
| Yes      | numeric metric | base_year                   | Base Year Employment Estimate      | number    | number      |
| Yes      | numeric metric | projected_year              | Projected Year Employment Estimate | number    | number      |
| Yes      | numeric metric | net_change                  | Net Change                         | number    | number      |
| Yes      | numeric metric | percent_change              | Percent Change                     | percent   | percent     |
| Yes      | numeric metric | total_annual_openings       | Total Annual Openings              | number    | number      |
| Yes      | numeric metric | growth_annual_openings      | Growth Annual Openings             | number    | number      |
| Yes      | numeric metric | replacement_annual_openings | Replacement Annual Openings        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:dyxu-i752 d:2016-03-03T03:17:53.000Z t:occupation_code='00-0000 t:area="New York State" t:period=2015-2017 t:occupation_title="Total, All Occupations" m:base_year=9855610 m:net_change=255320 m:percent_change=2.6 m:total_annual_openings=358970 m:replacement_annual_openings=226640 m:projected_year=10110930 m:growth_annual_openings=132330

series e:dyxu-i752 d:2016-03-03T03:17:53.000Z t:occupation_code='11-0000 t:area="New York State" t:period=2015-2017 t:occupation_title="Management Occupations" m:base_year=549560 m:net_change=13220 m:percent_change=2.4 m:total_annual_openings=18540 m:replacement_annual_openings=11910 m:projected_year=562780 m:growth_annual_openings=6630

series e:dyxu-i752 d:2016-03-03T03:17:53.000Z t:occupation_code='11-1000 t:area="New York State" t:period=2015-2017 t:occupation_title="Top Executives" m:base_year=183690 m:net_change=4770 m:percent_change=2.6 m:total_annual_openings=6500 m:replacement_annual_openings=4120 m:projected_year=188460 m:growth_annual_openings=2380
```

## Meta Commands

```ls
metric m:base_year p:integer l:"Base Year Employment Estimate" d:"A numerical value representing a base year employment estimate for an occupation." t:dataTypeName=number

metric m:projected_year p:integer l:"Projected Year Employment Estimate" d:"A numerical value representing the projected year employment estimate for an occupation." t:dataTypeName=number

metric m:net_change p:integer l:"Net Change" d:"Numeric change in employment between the projected estimate and the base estimate." t:dataTypeName=number

metric m:percent_change p:float l:"Percent Change" d:"Percent change in employment over period." t:dataTypeName=percent

metric m:total_annual_openings p:integer l:"Total Annual Openings" d:"A value representing the total annual average openings due to growth and net replacements." t:dataTypeName=number

metric m:growth_annual_openings p:integer l:"Growth Annual Openings" d:"A value representing the annual average openings due to growth." t:dataTypeName=number

metric m:replacement_annual_openings p:integer l:"Replacement Annual Openings" d:"A value representing the annual average openings due to net replacement." t:dataTypeName=number

entity e:dyxu-i752 l:"Short-term Occupational Projections" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/dyxu-i752

property e:dyxu-i752 t:meta.view v:id=dyxu-i752 v:category="Economic Development" v:attributionLink=http://labor.ny.gov/stats/lsproj.shtm v:averageRating=0 v:name="Short-term Occupational Projections" v:attribution="New York State Department of Labor"

property e:dyxu-i752 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:dyxu-i752 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:dyxu-i752 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | area           | period    | occupation_code | occupation_title                                                         | base_year | projected_year | net_change | percent_change | total_annual_openings | growth_annual_openings | replacement_annual_openings | 
| =========== | ============== | ========= | =============== | ======================================================================== | ========= | ============== | ========== | ============== | ===================== | ====================== | =========================== | 
| 1456975073  | New York State | 2015-2017 | '00-0000        | Total, All Occupations                                                   | 9855610   | 10110930       | 255320     | 2.6            | 358970                | 132330                 | 226640                      | 
| 1456975073  | New York State | 2015-2017 | '11-0000        | Management Occupations                                                   | 549560    | 562780         | 13220      | 2.4            | 18540                 | 6630                   | 11910                       | 
| 1456975073  | New York State | 2015-2017 | '11-1000        | Top Executives                                                           | 183690    | 188460         | 4770       | 2.6            | 6500                  | 2380                   | 4120                        | 
| 1456975073  | New York State | 2015-2017 | '11-1011        | Chief Executives                                                         | 25650     | 25810          | 160        | 0.6            | 510                   | 80                     | 430                         | 
| 1456975073  | New York State | 2015-2017 | '11-1021        | General and Operations Managers                                          | 150980    | 155580         | 4600       | 3.0            | 5850                  | 2300                   | 3550                        | 
| 1456975073  | New York State | 2015-2017 | '11-1031        | Legislators                                                              | 7070      | 7070           | 0          | 0.0            | 140                   | 0                      | 140                         | 
| 1456975073  | New York State | 2015-2017 | '11-2000        | Advertising, Marketing, Promotions, Public Relations, and Sales Managers | 43680     | 45070          | 1390       | 3.2            | 1780                  | 690                    | 1090                        | 
| 1456975073  | New York State | 2015-2017 | '11-2011        | Advertising and Promotions Managers                                      | 4910      | 5190           | 280        | 5.7            | 300                   | 140                    | 160                         | 
| 1456975073  | New York State | 2015-2017 | '11-2021        | Marketing Managers                                                       | 12990     | 13420          | 430        | 3.3            | 510                   | 220                    | 290                         | 
| 1456975073  | New York State | 2015-2017 | '11-2022        | Sales Managers                                                           | 18580     | 18980          | 400        | 2.2            | 610                   | 200                    | 410                         | 
```