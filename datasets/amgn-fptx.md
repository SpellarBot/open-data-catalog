# SHA Districts by County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sha-districts-by-county-071db) |
| Metadata | [Link](https://data.maryland.gov/api/views/amgn-fptx) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/amgn-fptx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/amgn-fptx/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | amgn-fptx |
| Name | SHA Districts by County |
| Attribution | State Highway Administration |
| Category | Transportation |
| Tags | sha, state highway administration |
| Created | 2014-10-10T02:59:48Z |
| Publication Date | 2014-10-10T03:09:04Z |

## Description

This dataset shows the boundaries of the State Highway Administration's (SHA's) seven regions.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | county               | County               | text      | text        |
| Yes      | series tag  | district             | District             | text      | number      |
| No       |             | latitude_of_capital  | Latitude of Capital  | number    | number      |
| No       |             | longitude_of_capital | Longitude of Capital | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude_of_capital,longitude_of_capital
```

## Data Commands

```ls
series e:amgn-fptx d:2014-10-09T19:59:53.000Z t:county=STATEWIDE m:row_number.amgn-fptx=1

series e:amgn-fptx d:2014-10-09T19:59:53.000Z t:county="BALTIMORE CITY" m:row_number.amgn-fptx=2

series e:amgn-fptx d:2014-10-09T20:01:18.000Z t:county=ALLEGANY t:district=6 m:row_number.amgn-fptx=3
```

## Meta Commands

```ls
metric m:row_number.amgn-fptx p:long l:"Row Number"

entity e:amgn-fptx l:"SHA Districts by County" t:attribution="State Highway Administration" t:url=https://data.maryland.gov/api/views/amgn-fptx

property e:amgn-fptx t:meta.view v:id=amgn-fptx v:category=Transportation v:attributionLink=http://roads.maryland.gov v:averageRating=0 v:name="SHA Districts by County" v:attribution="State Highway Administration"

property e:amgn-fptx t:meta.view.license v:name="Public Domain"

property e:amgn-fptx t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:amgn-fptx t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| :updated_at | county           | district | latitude_of_capital | longitude_of_capital | 
| =========== | ================ | ======== | =================== | ==================== | 
| 1412884793  | STATEWIDE        |          |                     |                      | 
| 1412884793  | BALTIMORE CITY   |          | 39.3290206          | -76.615228299999998  | 
| 1412884878  | ALLEGANY         | 6        | 39.6518858          | -78.759668300000001  | 
| 1412884879  | ANNE ARUNDEL     | 5        | 38.976455199999997  | -76.530206399999997  | 
| 1412884914  | BALTIMORE COUNTY | 4        | 39.400737200000002  | -76.600834599999999  | 
| 1412884929  | CALVERT          | 5        | 38.541384000000001  | -76.582970599999996  | 
| 1412884938  | CAROLINE         | 2        | 38.881688500000003  | -75.832937000000001  | 
| 1412884941  | CARROLL          | 7        | 39.584612900000003  | -77.010851700000003  | 
| 1412884961  | CECIL            | 2        | 39.612273600000002  | -75.833537399999997  | 
| 1412884966  | CHARLES          | 5        | 38.545828200000003  | -76.969940800000003  | 
```