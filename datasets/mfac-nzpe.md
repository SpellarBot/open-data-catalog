# Choose Maryland: Compare Counties - Geography

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/choose-maryland-compare-counties-geography) |
| Metadata | [Link](https://data.maryland.gov/api/views/mfac-nzpe) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/mfac-nzpe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/mfac-nzpe/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | mfac-nzpe |
| Name | Choose Maryland: Compare Counties - Geography |
| Attribution | Maryland Department of Commerce |
| Category | Energy and Environment |
| Tags | maryland, county, compare, geography, land area, elevation, shoreline |
| Created | 2013-08-23T18:42:31Z |
| Publication Date | 2014-06-18T18:01:15Z |

## Description

Portrait of county land / land use - area, elevations, and shoreline.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                                     | Data Type | Render Type |
| ======== | ============== | ================================== | ======================================== | ========= | =========== |
| No       | time           | :updated_at                        | updated_at                               | meta_data | meta_data   |
| Yes      | series tag     | county                             | County                                   | text      | text        |
| Yes      | numeric metric | land_area_sqmi                     | Land Area (sq. mi.)                      | number    | number      |
| Yes      | numeric metric | highest_elevation_ft               | Highest Elevation (ft.)                  | number    | number      |
| Yes      | numeric metric | lowest_elevation_ft                | Lowest Elevation (ft.)                   | number    | number      |
| Yes      | numeric metric | shoreline_mi                       | Shoreline (mi.)                          | number    | number      |
| Yes      | numeric metric | land_use_developed_residential     | Land Use - Developed Residential (%)     | percent   | percent     |
| Yes      | numeric metric | land_use_developed_non_residential | Land Use - Developed Non-Residential (%) | percent   | percent     |
| Yes      | numeric metric | land_use_undeveloped               | Land Use - Undeveloped (%)               | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mfac-nzpe d:2014-06-18T11:00:41.000Z t:county="Allegany County" m:land_use_undeveloped=86.6 m:highest_elevation_ft=2895 m:lowest_elevation_ft=420 m:land_use_developed_residential=9.9 m:land_area_sqmi=427.62 m:shoreline_mi=0 m:land_use_developed_non_residential=3.5

series e:mfac-nzpe d:2014-06-18T11:00:41.000Z t:county="Anne Arundel County" m:land_use_undeveloped=49.1 m:highest_elevation_ft=300 m:lowest_elevation_ft=0 m:land_use_developed_residential=37 m:land_area_sqmi=418.37 m:shoreline_mi=508 m:land_use_developed_non_residential=13.9

series e:mfac-nzpe d:2014-06-18T11:00:41.000Z t:county="Baltimore City" m:land_use_undeveloped=8.2 m:highest_elevation_ft=480 m:lowest_elevation_ft=0 m:land_use_developed_residential=47.3 m:land_area_sqmi=80.34 m:shoreline_mi=61 m:land_use_developed_non_residential=44.6
```

## Meta Commands

```ls
metric m:land_area_sqmi p:float l:"Land Area (sq. mi.)" t:dataTypeName=number

metric m:highest_elevation_ft p:integer l:"Highest Elevation (ft.)" t:dataTypeName=number

metric m:lowest_elevation_ft p:integer l:"Lowest Elevation (ft.)" t:dataTypeName=number

metric m:shoreline_mi p:integer l:"Shoreline (mi.)" t:dataTypeName=number

metric m:land_use_developed_residential p:float l:"Land Use - Developed Residential (%)" t:dataTypeName=percent

metric m:land_use_developed_non_residential p:float l:"Land Use - Developed Non-Residential (%)" t:dataTypeName=percent

metric m:land_use_undeveloped p:float l:"Land Use - Undeveloped (%)" t:dataTypeName=percent

entity e:mfac-nzpe l:"Choose Maryland:  Compare Counties - Geography" t:attribution="Maryland Department of Commerce" t:url=https://data.maryland.gov/api/views/mfac-nzpe

property e:mfac-nzpe t:meta.view v:id=mfac-nzpe v:category="Energy and Environment" v:attributionLink=http://commerce.maryland.gov v:averageRating=0 v:name="Choose Maryland:  Compare Counties - Geography" v:attribution="Maryland Department of Commerce"

property e:mfac-nzpe t:meta.view.owner v:id=m2gt-bxeg v:screenName="Mike Grandel" v:displayName="Mike Grandel"

property e:mfac-nzpe t:meta.view.tableauthor v:id=m2gt-bxeg v:screenName="Mike Grandel" v:roleName=editor v:displayName="Mike Grandel"
```

## Top Records

```ls
| :updated_at | county              | land_area_sqmi | highest_elevation_ft | lowest_elevation_ft | shoreline_mi | land_use_developed_residential | land_use_developed_non_residential | land_use_undeveloped | 
| =========== | =================== | ============== | ==================== | =================== | ============ | ============================== | ================================== | ==================== | 
| 1403089241  | Allegany County     | 427.62         | 2895                 | 420                 | 0            | 9.9                            | 3.5                                | 86.6                 | 
| 1403089241  | Anne Arundel County | 418.37         | 300                  | 0                   | 508          | 37.0                           | 13.9                               | 49.1                 | 
| 1403089241  | Baltimore City      | 80.34          | 480                  | 0                   | 61           | 47.3                           | 44.6                               | 8.2                  | 
| 1403089241  | Baltimore County    | 597.60         | 966                  | 0                   | 232          | 35.4                           | 11.8                               | 52.9                 | 
| 1403089241  | Calvert County      | 213.23         | 168                  | 0                   | 230          | 33.8                           | 3.7                                | 62.5                 | 
| 1403089241  | Caroline County     | 320.79         | 79                   | 0                   | 120          | 11.3                           | 1.6                                | 87.1                 | 
| 1403089241  | Carroll County      | 451.98         | 1120                 | 260                 | 0            | 25.6                           | 3.8                                | 70.6                 | 
| 1403089241  | Cecil County        | 359.55         | 535                  | 0                   | 217          | 18.3                           | 5.1                                | 76.6                 | 
| 1403089241  | Charles County      | 451.58         | 235                  | 0                   | 305          | 21.2                           | 3.8                                | 75.0                 | 
| 1403089241  | Dorchester County   | 593.22         | 57                   | 0                   | 1539         | 5.2                            | 1.3                                | 93.5                 | 
```