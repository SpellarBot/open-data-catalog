# Mount Rainier: County Designated Historical Sites & National Register of Historic Places Sites

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mount-rainier-county-designated-historical-sites-national-register-of-historic-places-site-0fc5d) |
| Metadata | [Link](https://data.maryland.gov/api/views/nifh-ijgb) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/nifh-ijgb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/nifh-ijgb/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | nifh-ijgb |
| Name | Mount Rainier: County Designated Historical Sites & National Register of Historic Places Sites |
| Attribution | City of Mount Rainier |
| Category | Planning |
| Tags | mount rainier, historic sites, national register of historic places, tourism |
| Created | 2014-11-10T15:48:10Z |
| Publication Date | 2014-11-10T21:27:10Z |

## Description

Mount Rainier is a designated National Register Historic District. This dataset shows historical sites within Mount Rainier designated by Prince George's County, as well as sites designated by the National Register of Historical Places.

## Columns

```ls
| Included | Schema Type | Field Name                                  | Name                                          | Data Type | Render Type |
| ======== | =========== | =========================================== | ============================================= | ========= | =========== |
| No       | time        | :updated_at                                 | updated_at                                    | meta_data | meta_data   |
| Yes      | series tag  | historic_site                               | Historic Site                                 | text      | text        |
| No       |             | address                                     | Address                                       | text      | text        |
| Yes      | series tag  | prince_george_s_co_designated_historic_site | Prince George's Co. Designated Historic Site? | checkbox  | checkbox    |
| Yes      | series tag  | national_register_of_historic_places_site   | National Register of Historic Places Site?    | checkbox  | checkbox    |
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
series e:nifh-ijgb d:2014-11-10T13:26:56.000Z t:historic_site="Vallonia House" t:national_register_of_historic_places_site=true m:row_number.nifh-ijgb=1

series e:nifh-ijgb d:2014-11-10T13:26:56.000Z t:historic_site="Prince George's Bank" t:prince_george_s_co_designated_historic_site=true m:row_number.nifh-ijgb=2

series e:nifh-ijgb d:2014-11-10T13:26:56.000Z t:historic_site="Cornell House" t:national_register_of_historic_places_site=true m:row_number.nifh-ijgb=3
```

## Meta Commands

```ls
metric m:row_number.nifh-ijgb p:long l:"Row Number"

entity e:nifh-ijgb l:"Mount Rainier: County Designated Historical Sites & National Register of Historic Places Sites" t:attribution="City of Mount Rainier" t:url=https://data.maryland.gov/api/views/nifh-ijgb

property e:nifh-ijgb t:meta.view v:id=nifh-ijgb v:category=Planning v:attributionLink=http://www.mountrainiermd.org/visitors/experience-historic-mount-rainier/ v:averageRating=0 v:name="Mount Rainier: County Designated Historical Sites & National Register of Historic Places Sites" v:attribution="City of Mount Rainier"

property e:nifh-ijgb t:meta.view.license v:name="Public Domain"

property e:nifh-ijgb t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:nifh-ijgb t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| :updated_at | historic_site             | address         | prince_george_s_co_designated_historic_site | national_register_of_historic_places_site | 
| =========== | ========================= | =============== | =========================================== | ========================================= | 
| 1415626016  | Vallonia House            | 4118 29th St.   |                                             | true                                      | 
| 1415626016  | Prince George's Bank      | 3800 34th St.   | true                                        |                                           | 
| 1415626016  | Cornell House             | 4507 29th St.   |                                             | true                                      | 
| 1415626016  | Conway House              | 3004 Upshur St. |                                             | true                                      | 
| 1415626016  | Lakecrest House           | 4115 28th St.   |                                             | true                                      | 
| 1415626016  | Richards House            | 3806 30th St.   | true                                        |                                           | 
| 1415626016  | Oak Park House            | 3112 Varnum St. |                                             | true                                      | 
| 1415626016  | Windsor House             | 3207 Upshur St. |                                             | true                                      | 
| 1415626016  | Thomas W. Smith Farmhouse | 3426 Newton St. | true                                        |                                           | 
| 1415626016  | Bellman House             | 4012 33rd St.   | true                                        |                                           | 
```