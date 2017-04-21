# SHA Facilities Statewide

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sha-facilities-statewide-4369f) |
| Metadata | [Link](https://data.maryland.gov/api/views/p76f-zpri) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/p76f-zpri/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/p76f-zpri/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | p76f-zpri |
| Name | SHA Facilities Statewide |
| Attribution | State Highway Administration |
| Category | Transportation |
| Tags | state highway administration, sha, facilities, roadways, maintenance, roadway maintenance, landscape, mdot, maryland department of transportation |
| Created | 2014-10-21T14:46:11Z |
| Publication Date | 2014-10-21T15:22:10Z |

## Description

This dataset shows the 36 facilities of the State Highway Administration (SHA), including maintenance offices, landscape depots, and district offices, as well as the SHA Headquarters in Baltimore City and Hanover Complex.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | facility_location_name | Facility Location/Name | text      | text        |
| No       |             | address                | Address                | text      | text        |
| Yes      | series tag  | district               | District               | text      | number      |
| Yes      | series tag  | maintenance_office     | Maintenance Office?    | checkbox  | checkbox    |
| Yes      | series tag  | landscape_depot        | Landscape Depot?       | checkbox  | checkbox    |
| Yes      | series tag  | district_office        | District Office?       | text      | checkbox    |
| Yes      | series tag  | zip_code               | Zip Code               | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:p76f-zpri d:2014-10-21T08:22:04.000Z t:zip_code=21629 t:maintenance_office=true t:district=2 t:facility_location_name=Denton m:row_number.p76f-zpri=1

series e:p76f-zpri d:2014-10-21T08:22:04.000Z t:zip_code=21076 t:district=5 t:facility_location_name="Hanover Complex (Regional Lab)" m:row_number.p76f-zpri=2

series e:p76f-zpri d:2014-10-21T08:22:04.000Z t:zip_code=20650 t:maintenance_office=true t:district=5 t:facility_location_name=Leonardtown m:row_number.p76f-zpri=3
```

## Meta Commands

```ls
metric m:row_number.p76f-zpri p:long l:"Row Number"

entity e:p76f-zpri l:"SHA Facilities Statewide" t:attribution="State Highway Administration" t:url=https://data.maryland.gov/api/views/p76f-zpri

property e:p76f-zpri t:meta.view v:id=p76f-zpri v:category=Transportation v:attributionLink=http://roads.maryland.gov v:averageRating=0 v:name="SHA Facilities Statewide" v:attribution="State Highway Administration"

property e:p76f-zpri t:meta.view.license v:name="Public Domain"

property e:p76f-zpri t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:p76f-zpri t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| :updated_at | facility_location_name         | address                                                | district | maintenance_office | landscape_depot | district_office | zip_code | 
| =========== | ============================== | ====================================================== | ======== | ================== | =============== | =============== | ======== | 
| 1413879724  | Denton                         | 508 Caroline Street Denton MD 21629                    | 2        | true               |                 |                 | 21629    | 
| 1413879724  | Hanover Complex (Regional Lab) | 7491 CONNELLY DRIVE Hanover, Maryland 21076            | 5        |                    |                 |                 | 21076    | 
| 1413879724  | Leonardtown                    | 27345 Point Lookout Road Leonardtown, MD. 20650        | 5        | true               |                 |                 | 20650    | 
| 1413879724  | Westminster                    | 150 Wyndtryst Drive Westminster, Maryland 21157        | 7        | true               |                 |                 | 21157    | 
| 1413879724  | Greenbelt                      | 9300 Kenilworth Avenue Greenbelt, MD 20770             | 3        | true               |                 | true            | 20770    | 
| 1413879724  | Gaithersburg                   | 502 Quince Orchard Road Gaithersburg, MD 20878         | 3        | true               |                 |                 | 20878    | 
| 1413879724  | Prince Frederick               | 100 Hallowing Point Road Prince Frederick, MD. 20678   | 5        | true               |                 |                 | 20678    | 
| 1413879724  | Snow Hill                      | 5603 Market Street Snow Hill, MD 21863                 | 1        | true               |                 |                 | 21863    | 
| 1413879724  | Princess Anne                  | 10980 Market Lane Princess Anne, MD 21861              | 1        | true               |                 |                 | 21861    | 
| 1413879724  | Hagerstown                     | 18320 Col. Henry K. Douglas Drive Hagerstown, MD 21740 | 6        | true               |                 |                 | 21740    | 
```