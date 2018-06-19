# Chesapeake Bay Pollution Loads - Nitrogen

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chesapeake-bay-pollution-loads-nitrogen-2076b) |
| Metadata | [Link](https://data.maryland.gov/api/views/rsrj-4w3t) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/rsrj-4w3t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/rsrj-4w3t/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | rsrj-4w3t |
| Name | Chesapeake Bay Pollution Loads - Nitrogen |
| Attribution | MD Dept. of Environment |
| Category | Energy and Environment |
| Tags | chesapeake, bay, baystat, watershed, pollution, causes, nitrogen, wip |
| Created | 2013-10-04T15:00:58Z |
| Publication Date | 2014-03-28T18:33:39Z |

## Description

Nitrogen pollution from contributing sources in Bay watershed, pounds per year. 1985, 2007, and 2009 - 2012 progress; 2017 and 2025 targets. Data source: EPA Phase 5.3.2 Watershed Model.

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
| Yes      | numeric metric | 1985               | Total N, 1985 (lb.)        | number    | number      |
| Yes      | numeric metric | 2007               | Total N, 2007 (lb.)        | number    | number      |
| Yes      | numeric metric | 2009               | Total N, 2009 (lb.)        | number    | number      |
| Yes      | numeric metric | 2010               | Total N, 2010 (lb.)        | number    | number      |
| Yes      | numeric metric | 2011               | Total N, 2011 (lb.)        | number    | number      |
| Yes      | numeric metric | 2012               | Total N, 2012 (lb.)        | number    | number      |
| Yes      | numeric metric | 2013               | Total N, 2013 (lb.)        | number    | number      |
| Yes      | numeric metric | tn_target_2017     | Total N Target, 2017 (lb.) | number    | number      |
| Yes      | numeric metric | tn_target_2025     | Total N Target 2025 (lb.)  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rsrj-4w3t d:2014-03-28T08:42:12.000Z t:trib_basin="Upper Potomac" t:major_basin="Potomac River Basin" t:county=ALLEGANY t:land_river_segment=A24001PU0_3871_3690 t:fips=24001 t:source_sector=Agriculture m:2009=3289.672684 m:tn_target_2025=3353.446939 m:2007=3884.912003 m:2013=2611.30702 m:tn_target_2017=3327.937237 m:1985=9471.032853 m:2012=2948.610696 m:2011=3246.607872 m:2010=3341.383244

series e:rsrj-4w3t d:2014-03-28T08:42:12.000Z t:trib_basin="Upper Potomac" t:major_basin="Potomac River Basin" t:county=ALLEGANY t:land_river_segment=A24001PU0_3871_3690 t:fips=24001 t:source_sector=Forest m:2009=44013.49732 m:tn_target_2025=44936.36639 m:2007=44291.18848 m:2013=43439.70019 m:tn_target_2017=44567.21876 m:1985=51155.91944 m:2012=44065.74414 m:2011=44127.95483 m:2010=44071.13037

series e:rsrj-4w3t d:2014-03-28T08:42:12.000Z t:trib_basin="Upper Potomac" t:major_basin="Potomac River Basin" t:county=ALLEGANY t:land_river_segment=A24001PU0_3871_3690 t:fips=24001 t:source_sector="Non-Tidal Atm" m:2009=11.60046959 m:tn_target_2025=11.60046885 m:2007=11.60046959 m:2013=11.60046959 m:tn_target_2017=11.60046915 m:1985=23.74480057 m:2012=11.60046959 m:2011=11.60046959 m:2010=11.60046959
```

## Meta Commands

```ls
metric m:1985 p:double l:"Total N, 1985 (lb.)" d:"total nitrogen for fiscal year 1985 (pounds/year)" t:dataTypeName=number

metric m:2007 p:double l:"Total N, 2007 (lb.)" d:"total nitrogen for fiscal year 2007 (pounds/year)" t:dataTypeName=number

metric m:2009 p:double l:"Total N, 2009 (lb.)" d:"total nitrogen for fiscal year 2009 (pounds/year)" t:dataTypeName=number

metric m:2010 p:double l:"Total N, 2010 (lb.)" d:"total nitrogen for fiscal year 2010 (pounds/year)" t:dataTypeName=number

metric m:2011 p:double l:"Total N, 2011 (lb.)" d:"total nitrogen for fiscal year 2011 (pounds/year)" t:dataTypeName=number

metric m:2012 p:double l:"Total N, 2012 (lb.)" d:"total nitrogen for fiscal year 2012 (pounds/year)" t:dataTypeName=number

metric m:2013 p:double l:"Total N, 2013 (lb.)" d:"total nitrogen for fiscal year 2013 (pounds/year)" t:dataTypeName=number

metric m:tn_target_2017 p:double l:"Total N Target, 2017 (lb.)" d:"Maryland phase II wastershed implementation plan target loads, fiscal year 2017 (pounds/year)." t:dataTypeName=number

metric m:tn_target_2025 p:double l:"Total N Target 2025 (lb.)" d:"Maryland phase II watershed implementation plan final target loads, fiscal year 2025 (pounds/year)." t:dataTypeName=number

entity e:rsrj-4w3t l:"Chesapeake Bay Pollution Loads - Nitrogen" t:attribution="MD Dept. of Environment" t:url=https://data.maryland.gov/api/views/rsrj-4w3t

property e:rsrj-4w3t t:meta.view v:id=rsrj-4w3t v:category="Energy and Environment" v:attributionLink=http://www.mde.state.md.us v:averageRating=0 v:name="Chesapeake Bay Pollution Loads - Nitrogen" v:attribution="MD Dept. of Environment"

property e:rsrj-4w3t t:meta.view.owner v:id=2ryv-bq8b v:profileImageUrlMedium=/api/users/2ryv-bq8b/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ryv-bq8b/profile_images/LARGE v:screenName=ESRGC v:profileImageUrlSmall=/api/users/2ryv-bq8b/profile_images/TINY v:displayName=ESRGC

property e:rsrj-4w3t t:meta.view.tableauthor v:id=2ryv-bq8b v:profileImageUrlMedium=/api/users/2ryv-bq8b/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ryv-bq8b/profile_images/LARGE v:screenName=ESRGC v:profileImageUrlSmall=/api/users/2ryv-bq8b/profile_images/TINY v:roleName=editor v:displayName=ESRGC
```

## Top Records

```ls
| :updated_at | land_river_segment  | fips  | county   | trib_basin    | major_basin         | source_sector | 1985        | 2007        | 2009        | 2010        | 2011        | 2012        | 2013        | tn_target_2017 | tn_target_2025 | 
| =========== | =================== | ===== | ======== | ============= | =================== | ============= | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ============== | ============== | 
| 1395996132  | A24001PU0_3871_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Agriculture   | 9471.032853 | 3884.912003 | 3289.672684 | 3341.383244 | 3246.607872 | 2948.610696 | 2611.30702  | 3327.937237    | 3353.446939    | 
| 1395996132  | A24001PU0_3871_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Forest        | 51155.91944 | 44291.18848 | 44013.49732 | 44071.13037 | 44127.95483 | 44065.74414 | 43439.70019 | 44567.21876    | 44936.36639    | 
| 1395996132  | A24001PU0_3871_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Non-Tidal Atm | 23.74480057 | 11.60046959 | 11.60046959 | 11.60046959 | 11.60046959 | 11.60046959 | 11.60046959 | 11.60046915    | 11.60046885    | 
| 1395996132  | A24001PU0_3871_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Septic        | 593.9841919 | 539.5734253 | 534.8148193 | 532.0961914 | 530.2841187 | 527.5651245 | 687.8466187 | 466.8039131    | 421.4633089    | 
| 1395996132  | A24001PU0_3871_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Stormwater    | 4163.487261 | 2510.113876 | 2473.74525  | 2463.564675 | 2455.81718  | 2456.445068 | 5187.855037 | 2278.617397    | 2148.532161    | 
| 1395996132  | A24001PU0_3871_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Wastewater    | 153.1799011 | 54.93151528 | 298.7707029 | 111.2639855 | 113.8582849 | 101.0508813 | 93.21610671 | 160.7122332    | 68.67325344    | 
| 1395996132  | A24001PU1_3100_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Agriculture   | 15441.9993  | 6334.096958 | 5363.781002 | 5447.929184 | 5298.208617 | 4807.539082 | 4257.63057  | 5426.166399    | 5467.756663    | 
| 1395996132  | A24001PU1_3100_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Forest        | 12118.45764 | 11013.50366 | 10978.34619 | 11011.17828 | 11052.81519 | 11051.16974 | 10846.24414 | 11117.06508    | 11209.54435    | 
| 1395996132  | A24001PU1_3100_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Non-Tidal Atm | 29.3120594  | 14.32032967 | 14.32032967 | 14.32032967 | 14.32032967 | 14.32032967 | 14.32032967 | 14.32033053    | 14.3203311     | 
| 1395996132  | A24001PU1_3100_3690 | 24001 | ALLEGANY | Upper Potomac | Potomac River Basin | Septic        | 0           | 358.9631958 | 346.29599   | 340.4533081 | 337.1145935 | 333.7806091 | 403.3226929 | 300.3192831    | 269.6681451    | 
```