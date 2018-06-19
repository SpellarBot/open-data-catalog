# Floating Restroom Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/floating-restroom-locations-27f25) |
| Metadata | [Link](https://data.oregon.gov/api/views/pf2v-pv7v) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/pf2v-pv7v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/pf2v-pv7v/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | pf2v-pv7v |
| Name | Floating Restroom Locations |
| Attribution | Oregon State Marine Board |
| Category | Recreation |
| Tags | public floating restroom boating on-water restrooms port-a-potty |
| Created | 2013-01-25T22:37:42Z |
| Publication Date | 2014-10-20T17:23:55Z |

## Description

This is a list of Oregon's floating restrooms on some of Oregon's most heavily used waterbodies.  More than 3 million gallons of human waste is collected from these facilities each year...help keep our waterways clean and pristine -and use a floating restroom!

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | ============== | ===================================== | ===================================== | ========= | =========== |
| No       | time           | :updated_at                           | updated_at                            | meta_data | meta_data   |
| Yes      | series tag     | type                                  | Type                                  | text      | text        |
| Yes      | series tag     | waterbody                             | Waterbody                             | text      | text        |
| Yes      | series tag     | river_mile                            | River Mile                            | text      | text        |
| Yes      | series tag     | facility                              | Restroom Proximity                    | text      | text        |
| Yes      | series tag     | name                                  | Managed By                            | text      | text        |
| Yes      | series tag     | phone                                 | Phone                                 | text      | text        |
| Yes      | series tag     | icon                                  | Icon                                  | photo     | photo       |
| Yes      | numeric metric | point_size                            | Point Size                            | number    | number      |
| Yes      | series tag     | marine_board_s_environmental_programs | Marine Board's Environmental Programs | url       | url         |
| Yes      | series tag     | photo                                 | Photo                                 | photo     | photo       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:pf2v-pv7v d:2014-10-20T10:18:28.000Z t:marine_board_s_environmental_programs=http://www.oregon.gov/OSMB/Clean/pages/index.aspx t:phone=503-854-3366 t:name="USFS, Detroit Ranger District" t:icon=HKrggq8czm_4ZTx7KboBSAbK2Q4GBVs2Fs6VbajgWGo t:waterbody="Detroit Lake" t:type="Floating Restroom" t:facility="Detroit Lake  (Blowout Arm)" m:point_size=20

series e:pf2v-pv7v d:2014-10-20T10:21:27.000Z t:marine_board_s_environmental_programs=http://www.oregon.gov/OSMB/Clean/pages/index.aspx t:phone=541-776-7001 t:name="Jackson County" t:icon=HKrggq8czm_4ZTx7KboBSAbK2Q4GBVs2Fs6VbajgWGo t:waterbody="Howard Praire Reservoir" t:type="Floating Restroom" t:facility="Howard Prairie Reservoir" m:point_size=10

series e:pf2v-pv7v d:2014-10-20T10:23:18.000Z t:marine_board_s_environmental_programs=http://www.oregon.gov/OSMB/Clean/pages/index.aspx t:river_mile=--- t:phone=541-682-2000 t:name="Lane County" t:icon=HKrggq8czm_4ZTx7KboBSAbK2Q4GBVs2Fs6VbajgWGo t:waterbody="Siltcoos Lake" t:type="Floating Restroom" t:facility="Siltcoos Lake" m:point_size=5
```

## Meta Commands

```ls
metric m:point_size p:integer l:"Point Size" t:dataTypeName=number

entity e:pf2v-pv7v l:"Floating Restroom Locations" t:attribution="Oregon State Marine Board" t:url=https://data.oregon.gov/api/views/pf2v-pv7v

property e:pf2v-pv7v t:meta.view d:2017-09-25T07:25:29.314Z v:averageRating=0 v:name="Floating Restroom Locations" v:attribution="Oregon State Marine Board" v:attributionLink=http://www.oregon.gov/osmb/Pages/about_us.aspx v:id=pf2v-pv7v v:category=Recreation

property e:pf2v-pv7v t:meta.view.owner d:2017-09-25T07:25:29.314Z v:displayName="Ashley Massey" v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:id=a2bu-8256 v:screenName="Ashley Massey" v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB

property e:pf2v-pv7v t:meta.view.tableauthor d:2017-09-25T07:25:29.314Z v:displayName="Ashley Massey" v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:roleName=editor v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:id=a2bu-8256 v:screenName="Ashley Massey" v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB
```

## Top Records

```ls
| :updated_at | type              | waterbody               | river_mile | facility                               | name                          | phone        | icon                                        | point_size | marine_board_s_environmental_programs                     | photo | 
| =========== | ================= | ======================= | ========== | ====================================== | ============================= | ============ | =========================================== | ========== | ========================================================= | ===== | 
| 1413376466  |                   |                         |            |                                        |                               |              |                                             |            | [null, null]                                              |       | 
| 1413800295  | Floating Restroom | Brownlee Reservoir      | ---        | Brownlee Reservoir                     | Baker County                  | 541-893-6147 | HKrggq8czm_4ZTx7KboBSAbK2Q4GBVs2Fs6VbajgWGo |            | [http://www.oregon.gov/OSMB/Clean/pages/index.aspx, null] |       | 
| 1413800308  | Floating Restroom | Detroit Lake            |            | Detroit Lake (Blowout Arm)             | USFS, Detroit Ranger District | 503-854-3366 | HKrggq8czm_4ZTx7KboBSAbK2Q4GBVs2Fs6VbajgWGo | 20         | [http://www.oregon.gov/OSMB/Clean/pages/index.aspx, null] |       | 
| 1413800375  | Floating Restroom | Fern Ridge Reservoir    |            | Fern Ridge Reservoir                   | Lane County                   | 541-682-2000 | HKrggq8czm_4ZTx7KboBSAbK2Q4GBVs2Fs6VbajgWGo |            | [http://www.oregon.gov/OSMB/Clean/pages/index.aspx, null] |       | 
| 1413800456  | Floating Restroom | Columbia River          | 117        | Government Island                      | State Parks                   | 800-551-6949 | HKrggq8czm_4ZTx7KboBSAbK2Q4GBVs2Fs6VbajgWGo |            | [http://www.oregon.gov/OSMB/Clean/pages/index.aspx, null] |       | 
| 1413800465  | Floating Restroom | Green Peter Reservoir   | ---        | Green Peter Reservoir (Quartzville)    | Linn County                   | 541-967-3917 | HKrggq8czm_4ZTx7KboBSAbK2Q4GBVs2Fs6VbajgWGo |            | [http://www.oregon.gov/OSMB/Clean/pages/index.aspx, null] |       | 
| 1413800476  | Floating Restroom | Green Peter Reservoir   |            | Green Peter Reservoir (Rumbaugh)       | Linn County                   | 541-967-3918 | HKrggq8czm_4ZTx7KboBSAbK2Q4GBVs2Fs6VbajgWGo |            | [http://www.oregon.gov/OSMB/Clean/pages/index.aspx, null] |       | 
| 1413800487  | Floating Restroom | Howard Praire Reservoir |            | Howard Prairie Reservoir               | Jackson County                | 541-776-7001 | HKrggq8czm_4ZTx7KboBSAbK2Q4GBVs2Fs6VbajgWGo | 10         | [http://www.oregon.gov/OSMB/Clean/pages/index.aspx, null] |       | 
| 1413800509  | Floating Restroom | Lake Billy Chinook      |            | Lake Billy Chinook (Crook Rvr Arm)     | State Parks                   | 800-551-6949 | HKrggq8czm_4ZTx7KboBSAbK2Q4GBVs2Fs6VbajgWGo |            | [http://www.oregon.gov/OSMB/Clean/pages/index.aspx, null] |       | 
| 1413800520  | Floating Restroom | Lake Billy Chinook      | ---        | Lake Billy Chinook (Deschutes Rvr Arm) | State Parks                   | 800-551-6949 | HKrggq8czm_4ZTx7KboBSAbK2Q4GBVs2Fs6VbajgWGo |            | [http://www.oregon.gov/OSMB/Clean/pages/index.aspx, null] |       | 
```