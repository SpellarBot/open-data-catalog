# Floating Restroom Locations

## Dataset

* [Dataset URL](https://data.oregon.gov/api/views/pf2v-pv7v/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/floating-restroom-locations-27f25)
* [Metadata URL](https://data.oregon.gov/api/views/pf2v-pv7v)
* Id = pf2v-pv7v
* Name = Floating Restroom Locations
* Attribution = Oregon State Marine Board
* [Attribution Link](http://www.oregon.gov/osmb/Pages/about_us.aspx)
* Category = Recreation
* Tags = [public floating restroom boating on-water restrooms port-a-potty]
* Created = 2013-01-25T22:37:42Z
* Publication Date = 2014-10-20T17:23:55Z
* Rows Updated = 2014-10-20T17:23:49Z

## Description

This is a list of Oregon's floating restrooms on some of Oregon's most heavily used waterbodies.  More than 3 million gallons of human waste is collected from these facilities each year...help keep our waterways clean and pristine -and use a floating restroom!

## Columns

```ls
| Name                                  | Field Name                            | Data Type | Render Type | Schema Type    | Included | 
| ===================================== | ===================================== | ========= | =========== | ============== | ======== | 
| updated_at                            | :updated_at                           | meta_data | meta_data   | time           | No       | 
| Type                                  | type                                  | text      | text        | series tag     | Yes      | 
| Waterbody                             | waterbody                             | text      | text        | series tag     | Yes      | 
| River Mile                            | river_mile                            | text      | text        | series tag     | Yes      | 
| Restroom Proximity                    | facility                              | text      | text        | series tag     | Yes      | 
| Managed By                            | name                                  | text      | text        | series tag     | Yes      | 
| Phone                                 | phone                                 | text      | text        | series tag     | Yes      | 
| Icon                                  | icon                                  | photo     | photo       | series tag     | Yes      | 
| Point Size                            | point_size                            | number    | number      | numeric metric | Yes      | 
| Marine Board's Environmental Programs | marine_board_s_environmental_programs | url       | url         | series tag     | Yes      | 
| Photo                                 | photo                                 | photo     | photo       | series tag     | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:pf2v-pv7v d:2014-10-20T10:18:28.000Z t:icon=HKrggq8czm_4ZTx7KboBSAbK2Q4GBVs2Fs6VbajgWGo t:phone=503-854-3366 t:facility="Detroit Lake  (Blowout Arm)" t:waterbody="Detroit Lake" t:name="USFS, Detroit Ranger District" t:type="Floating Restroom" m:point_size=20

series e:pf2v-pv7v d:2014-10-20T10:21:27.000Z t:icon=HKrggq8czm_4ZTx7KboBSAbK2Q4GBVs2Fs6VbajgWGo t:phone=541-776-7001 t:facility="Howard Prairie Reservoir" t:waterbody="Howard Praire Reservoir" t:name="Jackson County" t:type="Floating Restroom" m:point_size=10

series e:pf2v-pv7v d:2014-10-20T10:23:18.000Z t:icon=HKrggq8czm_4ZTx7KboBSAbK2Q4GBVs2Fs6VbajgWGo t:phone=541-682-2000 t:facility="Siltcoos Lake" t:waterbody="Siltcoos Lake" t:name="Lane County" t:river_mile=--- t:type="Floating Restroom" m:point_size=5
```

## Meta Commands

```ls
metric m:point_size p:integer l:"Point Size" t:dataTypeName=number

entity e:pf2v-pv7v l:"Floating Restroom Locations" t:attribution="Oregon State Marine Board" t:url=https://data.oregon.gov/api/views/pf2v-pv7v

property e:pf2v-pv7v t:meta.view d:2017-03-08T01:10:51.171Z v:id=pf2v-pv7v v:category=Recreation v:attributionLink=http://www.oregon.gov/osmb/Pages/about_us.aspx v:averageRating=0 v:name="Floating Restroom Locations" v:attribution="Oregon State Marine Board"

property e:pf2v-pv7v t:meta.view.owner d:2017-03-08T01:10:51.171Z v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:roleName=editor v:displayName="Ashley Massey"

property e:pf2v-pv7v t:meta.view.tableauthor d:2017-03-08T01:10:51.171Z v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:roleName=editor v:displayName="Ashley Massey"
```