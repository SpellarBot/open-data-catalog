# Christmas Tree Recycling Locations (2016 - current)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/christmas-tree-recycling-locations-2016) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/drnp-neza) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/drnp-neza/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/drnp-neza/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | drnp-neza |
| Name | Christmas Tree Recycling Locations (2016 - current) |
| Attribution | City of Chicago |
| Category | Environment & Sustainable Development |
| Tags | recycling, sustainability |
| Created | 2016-01-08T16:22:27Z |
| Publication Date | 2016-01-08T16:39:34Z |

## Description

Locations provided by the city to recycle Christmas trees from January 3 through January 21, 2017. These locations were established in 2016. For more information, see http://chicagorecycles.org

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | community_area_name | COMMUNITY AREA NAME | text      | text        |
| No       |                | address             | ADDRESS             | text      | text        |
| Yes      | series tag     | free_mulch          | FREE MULCH          | text      | text        |
| Yes      | series tag     | zip_code            | ZIP CODE            | text      | text        |
| Yes      | series tag     | community_area      | COMMUNITY AREA      | text      | text        |
| Yes      | series tag     | ward                | WARD                | text      | text        |
| Yes      | numeric metric | x_coord             | X_COORD             | number    | number      |
| Yes      | numeric metric | y_coord             | Y_COORD             | number    | number      |
| No       |                | latitude            | LATITUDE            | number    | number      |
| No       |                | longitude           | LONGITUDE           | number    | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address,latitude,longitude
```

## Data Commands

```ls
series e:drnp-neza d:2016-01-01T00:00:00.000Z t:ward=28 t:zip_code=60624 t:free_mulch=No t:community_area_name="East Garfield Park" t:community_area=27 m:y_coord=1900689.9233949387 m:x_coord=1152446.6860846397

series e:drnp-neza d:2016-01-01T00:00:00.000Z t:ward=10 t:zip_code=60617 t:free_mulch=No t:community_area_name="East Side" t:community_area=52 m:y_coord=1828812.9670539126 m:x_coord=1201873.579176487

series e:drnp-neza d:2016-01-01T00:00:00.000Z t:ward=26 t:zip_code=60622 t:free_mulch=No t:community_area_name="West Town" t:community_area=24 m:y_coord=1893290.6779660492 m:x_coord=1156257.7654432377
```

## Meta Commands

```ls
metric m:x_coord p:double l:X_COORD t:dataTypeName=number

metric m:y_coord p:double l:Y_COORD t:dataTypeName=number

entity e:drnp-neza l:"Christmas Tree Recycling Locations (2016 - current)" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/drnp-neza

property e:drnp-neza t:meta.view v:id=drnp-neza v:category="Environment & Sustainable Development" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Christmas Tree Recycling Locations (2016 - current)" v:attribution="City of Chicago"

property e:drnp-neza t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:drnp-neza t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| community_area_name | address               | free_mulch | zip_code | community_area | ward | x_coord            | y_coord            | latitude      | longitude      | 
| =================== | ===================== | ========== | ======== | ============== | ==== | ================== | ================== | ============= | ============== | 
| East Garfield Park  | 100 N Central Park Dr | No         | 60624    | 27             | 28   | 1152446.6860846397 | 1900689.9233949387 | 41.8833553223 | -87.7156652316 | 
| East Side           | 11546 S Avenue L      | No         | 60617    | 52             | 10   | 1201873.579176487  | 1828812.9670539126 | 41.6850020813 | -87.5366156494 | 
| West Town           | 1369 N Sacramento Ave | No         | 60622    | 24             | 26   | 1156257.7654432377 | 1893290.6779660492 | 41.8629749141 | -87.7018705161 | 
| McKinley Park       | 2210 W Pershing Rd    | No         | 60609    | 59             | 12   | 1162172.3933990514 | 1878822.9594745843 | 41.8231525443 | -87.6805621474 | 
| Morgan Park         | 2427 W 113th St       | No         | 60643    | 75             | 19   | 1162083.8358381828 | 1829585.9497994445 | 41.6880407683 | -87.6822540351 | 
| Lincoln Park        | 2440 N Cannon Dr      | Yes        | 60614    | 07             | 43   | 1174425.9291710549 | 1916760.22025054   | 41.9269905544 | -87.6344756315 | 
| Douglas             | 3117 S Rhodes Ave     | No         | 60616    | 35             | 04   | 1180450.455266103  | 1884343.8893340114 | 41.8379017347 | -87.6133377317 | 
| North Center        | 3400 N Rockwell St    | No         | 60618    | 05             | 47   | 1158226.523075392  | 1922486.977007251  | 41.9430520411 | -87.693844427  | 
| Mount Greenwood     | 3721 W 111th St       | Yes        | 60655    | 74             | 19   | 1153420.7703238295 | 1830692.554124107  | 41.691252806  | -87.7139400014 | 
| Portage Park        | 4100 N Long Ave       | No         | 60641    | 15             | 38   | 1139577.6563066659 | 1926748.6757861765 | 41.9551078677 | -87.7622845814 | 
```