# Activity By County And Waterbody

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/activity-by-county-and-waterbody-6edbb) |
| Metadata | [Link](https://data.oregon.gov/api/views/6cn5-hn6g) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/6cn5-hn6g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/6cn5-hn6g/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 6cn5-hn6g |
| Name | Activity By County And Waterbody |
| Attribution | Oregon State Marine Board |
| Category | Recreation |
| Tags | waterbody, destination, ramp, launch, marina, county, trips, use days, activity, fishing, sailing, pwc, water skiing, cruising, days, boat, boats, boating |
| Created | 2011-10-27T20:37:19Z |
| Publication Date | 2011-10-31T14:59:31Z |

## Description

Triennial Survey Results for 2010

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                               | Data Type | Render Type |
| ======== | ============== | ================================ | ================================== | ========= | =========== |
| No       | time           | :updated_at                      | updated_at                         | meta_data | meta_data   |
| Yes      | series tag     | waterbody_destination_           | Waterbody (Destination)            | text      | text        |
| Yes      | series tag     | ramp_launch_site_marinea_origin_ | Ramp Launch Site, Marinea (origin) | text      | text        |
| Yes      | series tag     | county                           | County                             | text      | text        |
| Yes      | numeric metric | use_days                         | Use Days                           | number    | number      |
| Yes      | numeric metric | trips                            | Trips                              | number    | number      |
| Yes      | numeric metric | activity_days                    | Activity Days                      | number    | number      |
| Yes      | numeric metric | fishing_days                     | Fishing days                       | number    | number      |
| Yes      | numeric metric | fhising_                         | Fishing %                          | number    | number      |
| Yes      | numeric metric | sailing_days                     | Sailing Days                       | number    | number      |
| Yes      | numeric metric | sailing_                         | Sailing %                          | number    | number      |
| Yes      | numeric metric | pwc_days                         | PWC Days                           | number    | number      |
| Yes      | numeric metric | pwc_                             | PWC %                              | number    | number      |
| Yes      | numeric metric | water_skiing_days                | Water Skiing Days                  | number    | number      |
| Yes      | numeric metric | water_skiing_                    | Water Skiing %                     | number    | number      |
| Yes      | numeric metric | cruising_days                    | Cruising Days                      | number    | number      |
| Yes      | numeric metric | cruising_                        | Cruising %                         | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:6cn5-hn6g d:2011-10-27T13:37:21.000Z t:waterbody_destination_="Agate Reservoir" t:county=Jackson t:ramp_launch_site_marinea_origin_="Agate Lake" m:use_days=1296 m:pwc_days=0 m:water_skiing_=0 m:trips=1296 m:sailing_=0 m:water_skiing_days=0 m:cruising_=0 m:fishing_days=1296 m:cruising_days=0 m:pwc_=0 m:fhising_=100 m:activity_days=1296 m:sailing_days=0

series e:6cn5-hn6g d:2011-10-27T13:37:21.000Z t:waterbody_destination_="Agency Lake" t:county=Klamath t:ramp_launch_site_marinea_origin_=Unknown m:use_days=616 m:pwc_days=0 m:water_skiing_=0 m:trips=616 m:sailing_=0 m:water_skiing_days=0 m:cruising_=0 m:fishing_days=616 m:cruising_days=0 m:pwc_=0 m:fhising_=100 m:activity_days=616 m:sailing_days=0

series e:6cn5-hn6g d:2011-10-27T13:37:21.000Z t:waterbody_destination_="Agency Lake" t:county=Klamath t:ramp_launch_site_marinea_origin_="Henzel Park" m:use_days=2219 m:pwc_days=0 m:water_skiing_=0 m:trips=308 m:sailing_=0 m:water_skiing_days=0 m:cruising_=28 m:fishing_days=308 m:cruising_days=616 m:pwc_=0 m:fhising_=14 m:activity_days=2219 m:sailing_days=0
```

## Meta Commands

```ls
metric m:use_days p:integer l:"Use Days" t:dataTypeName=number

metric m:trips p:integer l:Trips t:dataTypeName=number

metric m:activity_days p:integer l:"Activity Days" t:dataTypeName=number

metric m:fishing_days p:integer l:"Fishing days" t:dataTypeName=number

metric m:fhising_ p:integer l:"Fishing %" t:dataTypeName=number

metric m:sailing_days p:integer l:"Sailing Days" t:dataTypeName=number

metric m:sailing_ p:integer l:"Sailing %" t:dataTypeName=number

metric m:pwc_days p:integer l:"PWC Days" t:dataTypeName=number

metric m:pwc_ p:integer l:"PWC %" t:dataTypeName=number

metric m:water_skiing_days p:integer l:"Water Skiing Days" t:dataTypeName=number

metric m:water_skiing_ p:integer l:"Water Skiing %" t:dataTypeName=number

metric m:cruising_days p:integer l:"Cruising Days" t:dataTypeName=number

metric m:cruising_ p:integer l:"Cruising %" t:dataTypeName=number

entity e:6cn5-hn6g l:"Activity By County And Waterbody" t:attribution="Oregon State Marine Board" t:url=https://data.oregon.gov/api/views/6cn5-hn6g

property e:6cn5-hn6g t:meta.view v:id=6cn5-hn6g v:category=Recreation v:attributionLink=http://www.boatoregon.com v:averageRating=0 v:name="Activity By County And Waterbody" v:attribution="Oregon State Marine Board"

property e:6cn5-hn6g t:meta.view.owner v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:displayName="Ashley Massey"

property e:6cn5-hn6g t:meta.view.tableauthor v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:roleName=editor v:displayName="Ashley Massey"
```

## Top Records

```ls
| :updated_at | waterbody_destination_ | ramp_launch_site_marinea_origin_ | county      | use_days | trips | activity_days | fishing_days | fhising_ | sailing_days | sailing_ | pwc_days | pwc_ | water_skiing_days | water_skiing_ | cruising_days | cruising_ | 
| =========== | ====================== | ================================ | =========== | ======== | ===== | ============= | ============ | ======== | ============ | ======== | ======== | ==== | ================= | ============= | ============= | ========= | 
| 1319722641  | Agate Reservoir        | Agate Lake                       | Jackson     | 1296     | 1296  | 1296          | 1296         | 100      | 0            | 0        | 0        | 0    | 0                 | 0             | 0             | 0         | 
| 1319722641  | Agency Lake            | Unknown                          | Klamath     | 616      | 616   | 616           | 616          | 100      | 0            | 0        | 0        | 0    | 0                 | 0             | 0             | 0         | 
| 1319722641  | Agency Lake            | Henzel Park                      | Klamath     | 2219     | 308   | 2219          | 308          | 14       | 0            | 0        | 0        | 0    | 0                 | 0             | 616           | 28        | 
| 1319722641  | Agency Lake            | Petric Park                      | Klamath     | 185      | 185   | 185           | 185          | 100      | 0            | 0        | 0        | 0    | 0                 | 0             | 0             | 0         | 
| 1319722641  | Alsea Bay              | Unknown                          | Lincoln     | 709      | 533   | 709           | 709          | 100      | 0            | 0        | 0        | 0    | 0                 | 0             | 0             | 0         | 
| 1319722641  | Alsea Bay              | McKinleys Marina                 | Lincoln     | 191      | 82    | 191           | 191          | 100      | 0            | 0        | 0        | 0    | 0                 | 0             | 0             | 0         | 
| 1319722641  | Alsea Bay              | Port of Alsea                    | Lincoln     | 13782    | 10440 | 15548         | 13267        | 85       | 0            | 0        | 0        | 0    | 0                 | 0             | 0             | 0         | 
| 1319722641  | Alsea Bay              | Private Site                     | Lincoln     | 977      | 39    | 977           | 977          | 100      | 0            | 0        | 0        | 0    | 0                 | 0             | 0             | 0         | 
| 1319722641  | Alsea River            | Unknown                          | Lincoln     | 323      | 323   | 323           | 323          | 100      | 0            | 0        | 0        | 0    | 0                 | 0             | 0             | 0         | 
| 1319722641  | Alsea River            | Unknown                          | No Response | 646      | 646   | 646           | 646          | 100      | 0            | 0        | 0        | 0    | 0                 | 0             | 0             | 0         | 
```