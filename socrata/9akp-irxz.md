# Basin Town County 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/basin-town-county-2010-46e4e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9akp-irxz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9akp-irxz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9akp-irxz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9akp-irxz |
| Name | Basin Town County 2010 |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | department of environmental protection, dep, environment, water, reservoir, health, ecosystem, eco-system, agua, water system, water supply, nyc, tap, tap water, conservation, basin town, basin, h... |
| Created | 2011-09-30T18:14:22Z |
| Publication Date | 2013-06-21T19:44:59Z |

## Description

County and Town Area Statistics for the NYC East-of-Hudson Watershed (including towns within a watershed county that are completely outside watershed)

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                      | Data Type | Render Type |
| ======== | ============== | ========================================= | ========================================= | ========= | =========== |
| Yes      | series tag     | town_                                     | TOWN**                                    | text      | text        |
| Yes      | numeric metric | amawalk                                   | Amawalk                                   | number    | number      |
| Yes      | numeric metric | bog_brook                                 | Bog Brook                                 | number    | number      |
| Yes      | numeric metric | boyds_corner                              | Boyds Corner                              | number    | number      |
| Yes      | numeric metric | cross_river                               | Cross River                               | number    | number      |
| Yes      | numeric metric | croton_falls                              | Croton Falls                              | number    | number      |
| Yes      | numeric metric | diverting                                 | Diverting                                 | number    | number      |
| Yes      | numeric metric | east_branch                               | East Branch                               | number    | number      |
| Yes      | numeric metric | kensico                                   | Kensico                                   | number    | number      |
| Yes      | numeric metric | lake_gilead                               | Lake Gilead                               | number    | number      |
| Yes      | numeric metric | lake_gleneida                             | Lake Gleneida                             | percent   | percent     |
| Yes      | numeric metric | middle_branch                             | Middle Branch                             | number    | number      |
| Yes      | numeric metric | muscoot                                   | Muscoot                                   | number    | number      |
| Yes      | numeric metric | new_croton                                | New Croton                                | number    | number      |
| Yes      | numeric metric | titicus                                   | Titicus                                   | number    | number      |
| Yes      | numeric metric | west_branch                               | West Branch                               | number    | number      |
| Yes      | numeric metric | sub_total_town_acres_inside_nyc_watershed | Sub-total Town Acres Inside NYC Watershed | number    | number      |
| Yes      | numeric metric | town_acres_outside_nyc_watershed          | Town Acres Outside NYC Watershed          | number    | number      |
| Yes      | numeric metric | total_town_acreage                        | Total Town Acreage                        | number    | number      |
| Yes      | numeric metric | of_each_town_in_nyc_watershed             | % of each Town in NYC Watershed           | percent   | percent     |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9akp-irxz d:2010-01-01T00:00:00.000Z m:sub_total_town_acres_inside_nyc_watershed=0

series e:9akp-irxz d:2010-01-01T00:00:00.000Z m:town_acres_outside_nyc_watershed=27921.6 m:total_town_acreage=27921.6

series e:9akp-irxz d:2010-01-01T00:00:00.000Z m:of_each_town_in_nyc_watershed=0
```

## Meta Commands

```ls
metric m:amawalk p:double l:Amawalk t:dataTypeName=number

metric m:bog_brook p:double l:"Bog Brook" t:dataTypeName=number

metric m:boyds_corner p:double l:"Boyds Corner" t:dataTypeName=number

metric m:cross_river p:double l:"Cross River" t:dataTypeName=number

metric m:croton_falls p:double l:"Croton Falls" t:dataTypeName=number

metric m:diverting p:double l:Diverting t:dataTypeName=number

metric m:east_branch p:double l:"East Branch" t:dataTypeName=number

metric m:kensico p:double l:Kensico t:dataTypeName=number

metric m:lake_gilead p:double l:"Lake Gilead" t:dataTypeName=number

metric m:lake_gleneida p:float l:"Lake Gleneida" t:dataTypeName=percent

metric m:middle_branch p:float l:"Middle Branch" t:dataTypeName=number

metric m:muscoot p:float l:Muscoot t:dataTypeName=number

metric m:new_croton p:double l:"New Croton" t:dataTypeName=number

metric m:titicus p:float l:Titicus t:dataTypeName=number

metric m:west_branch p:float l:"West Branch" t:dataTypeName=number

metric m:sub_total_town_acres_inside_nyc_watershed p:float l:"Sub-total Town Acres Inside NYC Watershed" t:dataTypeName=number

metric m:town_acres_outside_nyc_watershed p:double l:"Town Acres Outside NYC Watershed" t:dataTypeName=number

metric m:total_town_acreage p:float l:"Total Town Acreage" t:dataTypeName=number

metric m:of_each_town_in_nyc_watershed p:float l:"% of each Town in NYC Watershed" t:dataTypeName=percent

entity e:9akp-irxz l:"Basin Town County 2010" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/9akp-irxz

property e:9akp-irxz t:meta.view v:id=9akp-irxz v:category=Environment v:averageRating=0 v:name="Basin Town County 2010" v:attribution="Department of Environmental Protection (DEP)"

property e:9akp-irxz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9akp-irxz t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| town_           | amawalk | bog_brook | boyds_corner | cross_river | croton_falls | diverting | east_branch | kensico | lake_gilead | lake_gleneida | middle_branch | muscoot | new_croton | titicus | west_branch | sub_total_town_acres_inside_nyc_watershed | town_acres_outside_nyc_watershed | total_town_acreage | of_each_town_in_nyc_watershed | 
| =============== | ======= | ========= | ============ | =========== | ============ | ========= | =========== | ======= | =========== | ============= | ============= | ======= | ========== | ======= | =========== | ========================================= | ================================ | ================== | ============================= | 
| Dutchess County |         |           |              |             |              |           |             |         |             |               |               |         |            |         |             |                                           |                                  |                    |                               | 
| Amenia          |         |           |              |             |              |           |             |         |             |               |               |         |            |         |             |                                           |                                  |                    |                               | 
|                 |         |           |              |             |              |           |             |         |             |               |               |         |            |         |             | 0.00                                      |                                  |                    |                               | 
|                 |         |           |              |             |              |           |             |         |             |               |               |         |            |         |             |                                           | 27921.60                         | 27921.60           |                               | 
|                 |         |           |              |             |              |           |             |         |             |               |               |         |            |         |             |                                           |                                  |                    | 0.00                          | 
| Beekman         |         |           |              |             |              |           |             |         |             |               |               |         |            |         |             |                                           |                                  |                    |                               | 
|                 |         |           |              |             |              |           | 12.5603     |         |             |               |               |         |            |         |             |                                           |                                  |                    |                               | 
|                 |         |           |              |             |              |           |             |         |             |               | 987.285       |         |            |         |             |                                           |                                  |                    |                               | 
|                 |         |           |              |             |              |           |             |         |             |               |               |         |            |         |             | 999.85                                    | 18669.70                         | 19669.55           | 5.08                          | 
| City of Beacon  |         |           |              |             |              |           |             |         |             |               |               |         |            |         |             |                                           |                                  |                    |                               | 
```