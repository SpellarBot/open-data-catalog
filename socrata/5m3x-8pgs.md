# IDOT Weigh Stationsx

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idot-weigh-stationsx-b083f) |
| Metadata | [Link](https://data.illinois.gov/api/views/5m3x-8pgs) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/5m3x-8pgs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/5m3x-8pgs/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 5m3x-8pgs |
| Name | IDOT Weigh Stationsx |
| Attribution | Illinois Department of Transportation |
| Category | Transportation |
| Created | 2011-06-16T13:46:02Z |
| Publication Date | 2012-01-26T15:26:41Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| No       |                | id          | ID         | text      | number      |
| Yes      | series tag     | name        | NAME       | text      | text        |
| Yes      | series tag     | route       | ROUTE      | text      | text        |
| Yes      | series tag     | route2      | ROUTE2     | text      | text        |
| Yes      | series tag     | location    | LOCATION   | text      | text        |
| Yes      | series tag     | phone_num   | PHONE_NUM  | text      | text        |
| Yes      | series tag     | district    | DISTRICT   | text      | number      |
| Yes      | numeric metric | st_copdist  | ST_COPDIST | number    | number      |
| No       |                | point_x     | POINT_X    | number    | number      |
| No       |                | point_y     | POINT_Y    | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id,point_x,point_y
```

## Data Commands

```ls
series e:5m3x-8pgs d:2011-06-16T06:46:05.000Z t:phone_num=847-395-8742 t:location="North of IL 173" t:route=U041 t:name="Rosecrans (South Bound)" t:district=1 m:st_copdist=2

series e:5m3x-8pgs d:2011-06-16T06:46:05.000Z t:phone_num=815-943-8281 t:location="3 miles North of Harvard" t:route=U014 t:name=Harvard t:district=1 m:st_copdist=2

series e:5m3x-8pgs d:2011-06-16T06:46:05.000Z t:phone_num=630-530-5902 t:location="Junction of St. Charles Road" t:route=S083 t:name="Villa Park" t:district=1 m:st_copdist=2
```

## Meta Commands

```ls
metric m:st_copdist p:integer l:ST_COPDIST t:dataTypeName=number

entity e:5m3x-8pgs l:"IDOT Weigh Stationsx" t:attribution="Illinois Department of Transportation" t:url=https://data.illinois.gov/api/views/5m3x-8pgs

property e:5m3x-8pgs t:meta.view v:id=5m3x-8pgs v:category=Transportation v:averageRating=0 v:name="IDOT Weigh Stationsx" v:attribution="Illinois Department of Transportation"

property e:5m3x-8pgs t:meta.view.owner v:id=ibpp-yb7w v:screenName="Jim Conlon" v:displayName="Jim Conlon"

property e:5m3x-8pgs t:meta.view.tableauthor v:id=ibpp-yb7w v:screenName="Jim Conlon" v:displayName="Jim Conlon"
```

## Top Records

```ls
| :updated_at | id | name                      | route | route2 | location                        | phone_num    | district | st_copdist | point_x  | point_y  | 
| =========== | == | ========================= | ===== | ====== | =============================== | ============ | ======== | ========== | ======== | ======== | 
| 1308206765  | 1  | Rosecrans (South Bound)   | U041  |        | North of IL 173                 | 847-395-8742 | 1        | 2          | -87.9473 | 42.46856 | 
| 1308206765  | 2  | Harvard                   | U014  |        | 3 miles North of Harvard        | 815-943-8281 | 1        | 2          | -88.6030 | 42.45383 | 
| 1308206765  | 3  | Villa Park                | S083  |        | Junction of St. Charles Road    | 630-530-5902 | 1        | 2          | -87.9625 | 41.88996 | 
| 1308206765  | 4  | Carlock (East Bound)      | I074  |        | East of Carlock (Mile Post 122) | 309-376-4111 | 3        | 6          | -89.1074 | 40.55742 | 
| 1308206765  | 5  | Richmond                  | U012  |        | North of IL 173                 | 815-678-4840 | 1        | 2          | -88.3087 | 42.49150 | 
| 1308206765  | 6  | Bolingbrook (South Bound) | I055  |        | West of IL 53 (Mile Post 265)   | 630-759-9837 | 1        | 5          | -88.0930 | 41.67255 | 
| 1308206765  | 7  | East Moline (East Bound)  | I080  |        | Mile Post 2                     | 309-496-2911 | 2        | 7          | -90.3425 | 41.55613 | 
| 1308206765  | 8  | Chicago Heights           | U030  |        | East of Torrence Avenue         | 708-758-9733 | 1        |            | -87.5546 | 41.50682 | 
| 1308206765  | 9  | Wadsworth                 | U041  |        | South of IL 173                 | 847-360-1457 | 1        | 2          | -87.9459 | 42.46466 | 
| 1308206765  | 10 | Frankfort (West Bound)    | I080  |        | East of US 45 (Mile Post 147)   | 708-532-9802 | 1        | 5          | -87.8205 | 41.55108 | 
```