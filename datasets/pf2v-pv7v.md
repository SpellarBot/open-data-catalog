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
series e:pf2v-pv7v d:2014-10-20T10:18:28.000Z t:icon=HKrggq8czm_4ZTx7KboBSAbK2Q4GBVs2Fs6VbajgWGo t:phone=503-854-3366 t:facility="Detroit Lake  (Blowout Arm)" t:waterbody="Detroit Lake" t:name="USFS, Detroit Ranger District" t:marine_board_s_environmental_programs=http://www.oregon.gov/OSMB/Clean/pages/index.aspx t:type="Floating Restroom" m:point_size=20

series e:pf2v-pv7v d:2014-10-20T10:21:27.000Z t:icon=HKrggq8czm_4ZTx7KboBSAbK2Q4GBVs2Fs6VbajgWGo t:phone=541-776-7001 t:facility="Howard Prairie Reservoir" t:waterbody="Howard Praire Reservoir" t:name="Jackson County" t:marine_board_s_environmental_programs=http://www.oregon.gov/OSMB/Clean/pages/index.aspx t:type="Floating Restroom" m:point_size=10

series e:pf2v-pv7v d:2014-10-20T10:23:18.000Z t:icon=HKrggq8czm_4ZTx7KboBSAbK2Q4GBVs2Fs6VbajgWGo t:phone=541-682-2000 t:facility="Siltcoos Lake" t:waterbody="Siltcoos Lake" t:name="Lane County" t:river_mile=--- t:marine_board_s_environmental_programs=http://www.oregon.gov/OSMB/Clean/pages/index.aspx t:type="Floating Restroom" m:point_size=5
```

## Meta Commands

```ls
metric m:point_size p:integer l:"Point Size" t:dataTypeName=number

entity e:pf2v-pv7v l:"Floating Restroom Locations" t:attribution="Oregon State Marine Board" t:url=https://data.oregon.gov/api/views/pf2v-pv7v

property e:pf2v-pv7v t:meta.view v:id=pf2v-pv7v v:category=Recreation v:attributionLink=http://www.oregon.gov/osmb/Pages/about_us.aspx v:averageRating=0 v:name="Floating Restroom Locations" v:attribution="Oregon State Marine Board"

property e:pf2v-pv7v t:meta.view.owner v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:displayName="Ashley Massey"

property e:pf2v-pv7v t:meta.view.tableauthor v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:roleName=editor v:displayName="Ashley Massey"
```