# West Seattle Water Taxi average ridership by run (dataset)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/west-seattle-water-taxi-average-ridership-by-run-dataset-95901) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/kqqn-tyfu) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/kqqn-tyfu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/kqqn-tyfu/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | kqqn-tyfu |
| Name | West Seattle Water Taxi average ridership by run (dataset) |
| Attribution | King County Ferry District |
| Category | Transportation |
| Tags | water taxi, west seattle, transportation, ferry |
| Created | 2013-11-15T01:07:36Z |
| Publication Date | 2013-11-15T01:18:32Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | day         | Run        | text      | text        |
| Yes      | numeric metric | 6_15_a_m    | 6:15 a.m.  | number    | number      |
| Yes      | numeric metric | 6_45_a_m    | 6:45 a.m.  | number    | number      |
| Yes      | numeric metric | 7_15_a_m    | 7:15 a.m.  | number    | number      |
| Yes      | numeric metric | 7_45_a_m    | 7:45 a.m.  | number    | number      |
| Yes      | numeric metric | 8_15_a_m    | 8:15 a.m.  | number    | number      |
| Yes      | numeric metric | 8_45_a_m    | 8:45 a.m.  | number    | number      |
| Yes      | numeric metric | 3_45_p_m    | 3:45 p.m.  | number    | number      |
| Yes      | numeric metric | 4_15_p_m    | 4:15 p.m.  | number    | number      |
| Yes      | numeric metric | 4_45_p_m    | 4:45 p.m.  | number    | number      |
| Yes      | numeric metric | 5_15_p_m    | 5:15 p.m.  | number    | number      |
| Yes      | numeric metric | 5_45_p_m    | 5:45 p.m.  | number    | number      |
| Yes      | numeric metric | 6_15_p_m    | 6:15 p.m.  | number    | number      |
| Yes      | numeric metric | 6_45_p_m    | 6:45 p.m.  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kqqn-tyfu d:2013-11-14T17:07:39.000Z t:day=Monday m:6_15_p_m=59 m:3_45_p_m=76 m:8_45_a_m=37 m:4_15_p_m=61 m:6_45_p_m=40 m:6_15_a_m=10 m:8_15_a_m=47 m:5_45_p_m=43 m:5_15_p_m=101 m:7_45_a_m=47 m:4_45_p_m=56 m:7_15_a_m=32 m:6_45_a_m=20

series e:kqqn-tyfu d:2013-11-14T17:07:39.000Z t:day=Tuesday m:6_15_p_m=53 m:3_45_p_m=72 m:8_45_a_m=42 m:4_15_p_m=55 m:6_45_p_m=55 m:6_15_a_m=13 m:8_15_a_m=41 m:5_45_p_m=84 m:5_15_p_m=87 m:7_45_a_m=50 m:4_45_p_m=68 m:7_15_a_m=32 m:6_45_a_m=21

series e:kqqn-tyfu d:2013-11-14T17:07:39.000Z t:day=Wednesday m:6_15_p_m=57 m:3_45_p_m=83 m:8_45_a_m=44 m:4_15_p_m=63 m:6_45_p_m=37 m:6_15_a_m=11 m:8_15_a_m=42 m:5_45_p_m=86 m:5_15_p_m=92 m:7_45_a_m=48 m:4_45_p_m=62 m:7_15_a_m=39 m:6_45_a_m=23
```

## Meta Commands

```ls
metric m:6_15_a_m p:integer l:"6:15 a.m." t:dataTypeName=number

metric m:6_45_a_m p:integer l:"6:45 a.m." t:dataTypeName=number

metric m:7_15_a_m p:integer l:"7:15 a.m." t:dataTypeName=number

metric m:7_45_a_m p:integer l:"7:45 a.m." t:dataTypeName=number

metric m:8_15_a_m p:integer l:"8:15 a.m." t:dataTypeName=number

metric m:8_45_a_m p:integer l:"8:45 a.m." t:dataTypeName=number

metric m:3_45_p_m p:integer l:"3:45 p.m." t:dataTypeName=number

metric m:4_15_p_m p:integer l:"4:15 p.m." t:dataTypeName=number

metric m:4_45_p_m p:integer l:"4:45 p.m." t:dataTypeName=number

metric m:5_15_p_m p:integer l:"5:15 p.m." t:dataTypeName=number

metric m:5_45_p_m p:integer l:"5:45 p.m." t:dataTypeName=number

metric m:6_15_p_m p:integer l:"6:15 p.m." t:dataTypeName=number

metric m:6_45_p_m p:integer l:"6:45 p.m." t:dataTypeName=number

entity e:kqqn-tyfu l:"West Seattle Water Taxi average ridership by run (dataset)" t:attribution="King County Ferry District" t:url=https://data.kingcounty.gov/api/views/kqqn-tyfu

property e:kqqn-tyfu t:meta.view v:id=kqqn-tyfu v:category=Transportation v:attributionLink=http://kingcounty.gov/transportation/kcdot/WaterTaxi/ v:averageRating=0 v:name="West Seattle Water Taxi average ridership by run (dataset)" v:attribution="King County Ferry District"

property e:kqqn-tyfu t:meta.view.license v:name="Public Domain"

property e:kqqn-tyfu t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:kqqn-tyfu t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| :updated_at | day       | 6_15_a_m | 6_45_a_m | 7_15_a_m | 7_45_a_m | 8_15_a_m | 8_45_a_m | 3_45_p_m | 4_15_p_m | 4_45_p_m | 5_15_p_m | 5_45_p_m | 6_15_p_m | 6_45_p_m | 
| =========== | ========= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | 
| 1384448859  | Monday    | 10       | 20       | 32       | 47       | 47       | 37       | 76       | 61       | 56       | 101      | 43       | 59       | 40       | 
| 1384448859  | Tuesday   | 13       | 21       | 32       | 50       | 41       | 42       | 72       | 55       | 68       | 87       | 84       | 53       | 55       | 
| 1384448859  | Wednesday | 11       | 23       | 39       | 48       | 42       | 44       | 83       | 63       | 62       | 92       | 86       | 57       | 37       | 
| 1384448859  | Thursday  | 10       | 19       | 27       | 41       | 41       | 46       | 49       | 51       | 68       | 78       | 63       | 46       | 34       | 
| 1384448859  | Friday    | 10       | 16       | 30       | 34       | 37       | 26       | 77       | 56       | 70       | 71       | 75       | 55       | 39       | 
```