# AGR-Wineries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/agr-wineries-6f95d) |
| Metadata | [Link](https://data.illinois.gov/api/views/i8zb-z82e) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/i8zb-z82e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/i8zb-z82e/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | i8zb-z82e |
| Name | AGR-Wineries |
| Category | Recreation |
| Tags | wineries, vineyards |
| Created | 2012-02-03T15:33:16Z |
| Publication Date | 2012-02-03T15:40:50Z |

## Description

This is a listing of wineries in Illinois

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | winery_name | Winery Name | text      | text        |
| Yes      | series tag  | street      | Street      | text      | text        |
| Yes      | series tag  | state       | State       | text      | text        |
| Yes      | series tag  | zip         | Zip         | text      | number      |
| Yes      | series tag  | phone       | Phone       | text      | text        |
| Yes      | series tag  | url         | URL         | text      | text        |
| No       |             | longitude   | Longitude   | number    | number      |
| No       |             | latitude    | Latitude    | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = longitude,latitude
```

## Data Commands

```ls
series e:i8zb-z82e d:2012-02-03T07:33:21.000Z t:zip=60510 t:phone=630-761-8888 t:winery_name="Acqua Viva" t:street="1501 E WILSON ST" t:state=IL m:row_number.i8zb-z82e=1

series e:i8zb-z82e d:2012-02-03T07:33:21.000Z t:zip=62905 t:phone=618-893-4898 t:winery_name="Alto Vineyards, LTD" t:street="PO BOX 51" t:state=IL m:row_number.i8zb-z82e=2

series e:i8zb-z82e d:2012-02-03T07:33:21.000Z t:zip=62881 t:phone=618-548-0895 t:winery_name="Apple Ridge Vineyard" t:street="3205 COUNTY FARM RD" t:state=IL m:row_number.i8zb-z82e=3
```

## Meta Commands

```ls
metric m:row_number.i8zb-z82e p:long l:"Row Number"

entity e:i8zb-z82e l:AGR-Wineries t:url=https://data.illinois.gov/api/views/i8zb-z82e

property e:i8zb-z82e t:meta.view v:id=i8zb-z82e v:category=Recreation v:attributionLink="http://www.agr.state.il.us/agrihappenings/list.php?cat=8" v:averageRating=0 v:name=AGR-Wineries

property e:i8zb-z82e t:meta.view.owner v:id=zuaf-d327 v:screenName=mknepler v:displayName=mknepler

property e:i8zb-z82e t:meta.view.tableauthor v:id=zuaf-d327 v:screenName=mknepler v:roleName=publisher v:displayName=mknepler
```

## Top Records

```ls
| :updated_at | winery_name                | street                | state | zip   | phone        | url                                       | longitude           | latitude           | 
| =========== | ========================== | ===================== | ===== | ===== | ============ | ========================================= | =================== | ================== | 
| 1328254401  | Acqua Viva                 | 1501 E WILSON ST      | IL    | 60510 | 630-761-8888 |                                           | -88.272205999999997 | 41.854036999999998 | 
| 1328254401  | Alto Vineyards, LTD        | PO BOX 51             | IL    | 62905 | 618-893-4898 |                                           | -89.334100000000007 | 37.577800000000003 | 
| 1328254401  | Apple Ridge Vineyard       | 3205 COUNTY FARM RD   | IL    | 62881 | 618-548-0895 |                                           | -88.901422999999994 | 38.589354999999998 | 
| 1328254401  | Arbor Hill Vineyards, Inc. | 7458 W MOUNT HOPE RD  | IL    | 61036 | 815-777-1804 |                                           | -90.356949999999998 | 42.397840000000002 | 
| 1328254401  | Baxters Vineyards          | 2010 PARLEY ST        | IL    | 62354 | 217-453-2528 |                                           | -91.369601000000003 | 40.542610000000003 | 
| 1328254401  | Bay Creek Vineyard         | RR# 3 Box 3097        | IL    | 62363 | 217-285-4141 |                                           | -90.786000000000001 | 39.596200000000003 | 
| 1328254401  | Belleview Hollow Vineyard  | RR# 1 Box72           | IL    | 62355 | 217-734-9307 | http://Harvest Celebration 3rd Sat in Oct | -90.766199999999998 | 39.404499999999999 | 
| 1328254401  | Berryville Vineyards       | 1910 N PRAIRIETON RD  | IL    | 62421 | 618-456-2335 | http://www.berryvillevineyards.com        | -87.928218000000001 | 38.641967999999999 | 
| 1328254401  | Black Diamond Vineyard     | 3505 BLACK DIAMOND RD | IL    | 62263 | 618-336-5353 |                                           | -89.417951000000002 | 38.265810999999999 | 
| 1328254401  | Black Jack Vineyard        | 3 RIFLE RANGE RD      | IL    | 62958 | 618-549-0620 |                                           | -89.222522999999995 | 37.663215000000001 | 
```