# Chesapeake Bay Pollution Loads - Phosphorus

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chesapeake-bay-pollution-loads-phosphorus-f735e) |
| Metadata | [Link](https://data.maryland.gov/api/views/eumn-ip4q) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/eumn-ip4q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/eumn-ip4q/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | eumn-ip4q |
| Name | Chesapeake Bay Pollution Loads - Phosphorus |
| Attribution | MD Dept. of Environment |
| Category | Energy and Environment |
| Tags | chesapeake, bay, baystat, watershed, pollution, causes, phosphorus, wip |
| Created | 2013-10-04T15:56:22Z |
| Publication Date | 2014-03-28T18:39:32Z |

## Description

Phosphorus pollution from contributing sources in Bay watershed, pounds per year. 1985, 2007, and 2009 - 2012 progress; 2017 and 2025 targets. Data source: EPA Phase 5.3.2 Watershed Model.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                       | Data Type | Render Type |
| ======== | ============== | ================== | ========================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at                 | meta_data | meta_data   |
| Yes      | series tag     | land_river_segment | Land-River Segment         | text      | text        |
| Yes      | series tag     | fips               | FIPS                       | text      | text        |
| Yes      | series tag     | county             | County                     | text      | text        |
| Yes      | series tag     | trib_basin         | Tributary Basin            | text      | text        |
| Yes      | series tag     | major_basin        | Major Basin                | text      | text        |
| Yes      | series tag     | source_sector      | Source Sector              | text      | text        |
| Yes      | numeric metric | 1985               | Total P, 1985 (lb.)        | number    | number      |
| Yes      | numeric metric | 2007               | Total P, 2007 (lb.)        | number    | number      |
| Yes      | numeric metric | 2009               | Total P, 2009 (lb.)        | number    | number      |
| Yes      | numeric metric | 2010               | Total P, 2010 (lb.)        | number    | number      |
| Yes      | numeric metric | 2011               | Total P, 2011 (lb.)        | number    | number      |
| Yes      | numeric metric | 2012               | Total P, 2012 (lb.)        | number    | number      |
| Yes      | numeric metric | 2013               | Total P, 2013 (lb.)        | number    | number      |
| Yes      | numeric metric | tp_target_2017     | Total P Target, 2017 (lb.) | number    | number      |
| Yes      | numeric metric | tp_target_2025     | Total P Target 2025 (lb.)  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:eumn-ip4q d:2014-03-28T11:38:35.000Z t:trib_basin="Upper Potomac" t:major_basin="Potomac River Basin" t:county=ALLEGANY t:land_river_segment=A24001PU0_3871_3690 t:fips=24001 t:source_sector=Agriculture m:2009=553.0039258 m:2007=661.0127096 m:2013=402.6339249 m:1985=1858.864389 m:2012=421.8310678 m:2011=483.0480137 m:2010=521.4615183 m:tp_target_2025=476.7207472 m:tp_target_2017=507.2340186

series e:eumn-ip4q d:2014-03-28T11:38:35.000Z t:trib_basin="Upper Potomac" t:major_basin="Potomac River Basin" t:county=ALLEGANY t:land_river_segment=A24001PU0_3871_3690 t:fips=24001 t:source_sector=Forest m:2009=2117.196496 m:2007=2138.672523 m:2013=2098.779388 m:1985=2261.991288 m:2012=2128.680687 m:2011=2123.066192 m:2010=2120.383041 m:tp_target_2025=2159.097873 m:tp_target_2017=2142.337322

series e:eumn-ip4q d:2014-03-28T11:38:35.000Z t:trib_basin="Upper Potomac" t:major_basin="Potomac River Basin" t:county=ALLEGANY t:land_river_segment=A24001PU0_3871_3690 t:fips=24001 t:source_sector="Non-Tidal Atm" m:2009=1.831472993 m:2007=1.831472993 m:2013=1.831472993 m:1985=1.831472993 m:2012=1.831472993 m:2011=1.831472993 m:2010=1.831472993 m:tp_target_2025=1.831473331 m:tp_target_2017=1.831473196
```

## Meta Commands

```ls
metric m:1985 p:double l:"Total P, 1985 (lb.)" d:"total phosphorus for fiscal year 1985 (pounds/year)" t:dataTypeName=number

metric m:2007 p:double l:"Total P, 2007 (lb.)" d:"total phosphorus for fiscal year 2007 (pounds/year)" t:dataTypeName=number

metric m:2009 p:double l:"Total P, 2009 (lb.)" d:"total phosphorus for fiscal year 2009 (pounds/year)" t:dataTypeName=number

metric m:2010 p:double l:"Total P, 2010 (lb.)" d:"total phosphorus for fiscal year 2010 (pounds/year)" t:dataTypeName=number

metric m:2011 p:double l:"Total P, 2011 (lb.)" d:"total phosphorus for fiscal year 2011 (pounds/year)" t:dataTypeName=number

metric m:2012 p:double l:"Total P, 2012 (lb.)" d:"total phosphorus for fiscal year 2012 (pounds/year)" t:dataTypeName=number

metric m:2013 p:double l:"Total P, 2013 (lb.)" d:"total phosphorus for fiscal year 2013 (pounds/year)" t:dataTypeName=number

metric m:tp_target_2017 p:double l:"Total P Target, 2017 (lb.)" d:"Maryland phase II watershed implementation plan target loads, fiscal year 2017 (pounds/year)." t:dataTypeName=number

metric m:tp_target_2025 p:double l:"Total P Target 2025 (lb.)" d:"Maryland phase II watershed implementation plan final target loads, fiscal year 2025 (pounds/year)." t:dataTypeName=number

entity e:eumn-ip4q l:"Chesapeake Bay Pollution Loads - Phosphorus" t:attribution="MD Dept. of Environment" t:url=https://data.maryland.gov/api/views/eumn-ip4q

property e:eumn-ip4q t:meta.view v:id=eumn-ip4q v:category="Energy and Environment" v:attributionLink=http://www.mde.state.md.us v:averageRating=0 v:name="Chesapeake Bay Pollution Loads - Phosphorus" v:attribution="MD Dept. of Environment"

property e:eumn-ip4q t:meta.view.license v:name="Public Domain"

property e:eumn-ip4q t:meta.view.owner v:id=2ryv-bq8b v:profileImageUrlMedium=/api/users/2ryv-bq8b/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ryv-bq8b/profile_images/LARGE v:screenName=ESRGC v:profileImageUrlSmall=/api/users/2ryv-bq8b/profile_images/TINY v:displayName=ESRGC

property e:eumn-ip4q t:meta.view.tableauthor v:id=2ryv-bq8b v:profileImageUrlMedium=/api/users/2ryv-bq8b/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ryv-bq8b/profile_images/LARGE v:screenName=ESRGC v:profileImageUrlSmall=/api/users/2ryv-bq8b/profile_images/TINY v:roleName=editor v:displayName=ESRGC
```

## Top Records

```ls
| :updated_at | land_river_segment  | fips  | county   | trib_basin    | major_basin         | source_sector | 1985        | 2007        | 2009        | 2010        | 2011        | 2012        | 2013        | tp_target_2017 | tp_target_2025 | 
| =========== | =================== | ===== | ======== | ============= | =================== | ============= | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ============== | ============== | 
| 1396006715  | A24001PU0_3871_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Agriculture   | 1858.864389 | 661.0127096 | 553.0039258 | 521.4615183 | 483.0480137 | 421.8310678 | 402.6339249 | 507.2340186    | 476.7207472    | 
| 1396006715  | A24001PU0_3871_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Forest        | 2261.991288 | 2138.672523 | 2117.196496 | 2120.383041 | 2123.066192 | 2128.680687 | 2098.779388 | 2142.337322    | 2159.097873    | 
| 1396006715  | A24001PU0_3871_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Non-Tidal Atm | 1.831472993 | 1.831472993 | 1.831472993 | 1.831472993 | 1.831472993 | 1.831472993 | 1.831472993 | 1.831473196    | 1.831473331    | 
| 1396006715  | A24001PU0_3871_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Septic        | 0           | 0           | 0           | 0           | 0           | 0           | 0           | 0              | 0              | 
| 1396006715  | A24001PU0_3871_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Stormwater    | 795.7854018 | 561.2883269 | 558.5875506 | 556.9635956 | 554.1230781 | 554.2856496 | 1090.889577 | 473.6757112    | 417.0678183    | 
| 1396006715  | A24001PU0_3871_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Wastewater    | 102.4774017 | 15.26717812 | 84.80158668 | 28.87496549 | 29.22881681 | 35.57773572 | 33.78249049 | 46.08848286    | 20.27974698    | 
| 1396006715  | A24001PU1_3100_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Agriculture   | 3222.323925 | 1145.82592  | 958.7092375 | 904.0014196 | 837.8157389 | 731.2260892 | 697.9628325 | 879.3544383    | 826.4512388    | 
| 1396006715  | A24001PU1_3100_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Forest        | 569.719471  | 565.4199162 | 561.4761467 | 563.2672405 | 565.2623768 | 567.5947762 | 557.1657085 | 568.1708649    | 572.6340104    | 
| 1396006715  | A24001PU1_3100_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Non-Tidal Atm | 2.403793097 | 2.403793097 | 2.403793097 | 2.403793097 | 2.403793097 | 2.403793097 | 2.403793097 | 2.403792966    | 2.403792879    | 
| 1396006715  | A24001PU1_3100_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Septic        | 0           | 0           | 0           | 0           | 0           | 0           | 0           | 0              | 0              | 
```