# Iowa DOT Cost Center Mile Post Break Points

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-dot-cost-center-mile-post-break-points) |
| Metadata | [Link](https://data.iowa.gov/api/views/45hs-d2sp) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/45hs-d2sp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/45hs-d2sp/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 45hs-d2sp |
| Name | Iowa DOT Cost Center Mile Post Break Points |
| Attribution | Iowa Department of Transportation - Office of Maintenance |
| Category | Transportation & Utilities |
| Tags | boundary, reference, maintenance, iowa dot, cost center, iowa department of transportation |
| Created | 2016-06-08T21:14:47Z |
| Publication Date | 2016-06-08T21:16:47Z |

## Description

These are custom made milepost locations to be used as reference points at primary route intersections, breaks in cost center locations and many county lines.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | route         | ROUTE         | text      | text        |
| Yes      | series tag     | route_name    | ROUTE_NAME    | text      | text        |
| No       |                | latitude      | LATITUDE      | number    | number      |
| No       |                | longitude     | LONGITUDE     | number    | number      |
| Yes      | series tag     | county_number | COUNTY_NUMBER | text      | number      |
| Yes      | numeric metric | mile_post     | MILE_POST     | number    | text        |
| Yes      | series tag     | district      | DISTRICT      | text      | number      |
| Yes      | series tag     | cost_center   | COST_CENTER   | text      | text        |
| Yes      | series tag     | objectid      | OBJECTID      | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:45hs-d2sp d:2016-06-08T21:14:47.000Z t:cost_center=552833 t:county_number=33 t:route_name="US 18" t:route=18 t:objectid=1 t:district=2 m:mile_post=252.06

series e:45hs-d2sp d:2016-06-08T21:14:47.000Z t:cost_center=556604 t:county_number=10 t:route_name="US 20" t:route=20 t:objectid=2 t:district=6 m:mile_post=245.67

series e:45hs-d2sp d:2016-06-08T21:14:47.000Z t:cost_center=554613 t:county_number=80 t:route_name="IA 2" t:route=2 t:objectid=3 t:district=4 m:mile_post=85.6
```

## Meta Commands

```ls
metric m:mile_post p:float l:MILE_POST d:"Mile Post" t:dataTypeName=number

entity e:45hs-d2sp l:"Iowa DOT Cost Center Mile Post Break Points" t:attribution="Iowa Department of Transportation - Office of Maintenance" t:url=https://data.iowa.gov/api/views/45hs-d2sp

property e:45hs-d2sp t:meta.view v:id=45hs-d2sp v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Maintenance/Cost_Center_Break_Points/MapServer/0 v:averageRating=0 v:name="Iowa DOT Cost Center Mile Post Break Points" v:attribution="Iowa Department of Transportation - Office of Maintenance"

property e:45hs-d2sp t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:45hs-d2sp t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | route | route_name | latitude                                           | longitude                                          | county_number | mile_post | district | cost_center | objectid | 
| =========== | ===== | ========== | ================================================== | ================================================== | ============= | ========= | ======== | =========== | ======== | 
| 0           | 18    | US 18      | 42.96484643000000147594619193114340305328369140625 | -92.042520010000004049288691021502017974853515625  | 33            | 252.06    | 2        | 552833      | 1        | 
| 0           | 20    | US 20      | 42.44901569999999679794200346805155277252197265625 | -92.0555552400000038915095501579344272613525390625 | 10            | 245.67    | 6        | 556604      | 2        | 
| 0           | 2     | IA 2       | 40.7118261199999977861807565204799175262451171875  | -94.47107990000000654617906548082828521728515625   | 80            | 85.6      | 4        | 554613      | 3        | 
| 0           | 20    | US 20      | 42.421267540000002327360562048852443695068359375   | -94.9547999699999962786023388616740703582763671875 | 81            | 82        | 3        | 553606      | 4        | 
| 0           | 2     | IA 2       | 40.74261320000000097252268460579216480255126953125 | -95.385329799999993838355294428765773773193359375  | 73            | 28.63     | 4        | 554616      | 5        | 
| 0           | 74    | I 74       | 41.5961742799999996123005985282361507415771484375  | -90.52542149999999310239218175411224365234375      | 82            | 0         | 6        | 556812      | 6        | 
| 0           | 18    | US 18      | 43.18622500000000030695446184836328029632568359375 | -96.009962779999995063917594961822032928466796875  | 84            | 37.179    | 3        | 553809      | 7        | 
| 0           | 20    | US 20      | 42.45209564999999685142029193229973316192626953125 | -94.2907939899999973931699059903621673583984375    | 94            | 114.2     | 1        | 551611      | 8        | 
| 0           | 904   | IA 904     | 41.01257901000000316571458824910223484039306640625 | -92.069245429999995167236193083226680755615234375  | 51            | 0         | 5        | 555851      | 9        | 
| 0           | 18    | US 18      | 43.08287949000000338628524332307279109954833984375 | -94.442600010000006705013220198452472686767578125  | 55            | 119.6     | 2        | 552655      | 10       | 
```