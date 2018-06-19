# Pet License Sales Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-license-sales-locations-e9940) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/mwyh-gr8i) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/mwyh-gr8i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/mwyh-gr8i/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | mwyh-gr8i |
| Name | Pet License Sales Locations |
| Attribution | King County |
| Category | Pets |
| Tags | king, county, animal, pet, license, tag, sales, locations |
| Created | 2011-07-06T22:26:43Z |
| Publication Date | 2014-07-23T18:01:23Z |

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type | Render Type |
| ======== | =========== | ======================== | ======================== | ========= | =========== |
| No       | time        | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag  | city                     | City                     | text      | text        |
| Yes      | series tag  | agency                   | Agency                   | text      | text        |
| Yes      | series tag  | suite                    | Suite                    | text      | text        |
| Yes      | series tag  | telephone                | Telephone                | text      | text        |
| Yes      | series tag  | tags_available_          | Tags Available?          | text      | text        |
| Yes      | series tag  | mail_in_forms_available_ | Mail-in Forms Available? | text      | text        |
| Yes      | series tag  | notes                    | Notes                    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mwyh-gr8i d:2011-07-06T15:26:47.000Z t:tags_available_=Y t:agency="Parks, Arts and Recreation" t:mail_in_forms_available_=Y t:telephone=253-931-3043 t:city=Auburn m:row_number.mwyh-gr8i=1

series e:mwyh-gr8i d:2011-07-06T15:26:48.000Z t:tags_available_=Y t:agency="QFC #809" t:mail_in_forms_available_=Y t:telephone=425-827-2205 t:city=Kirkland m:row_number.mwyh-gr8i=2

series e:mwyh-gr8i d:2011-07-06T15:26:50.000Z t:tags_available_=N t:agency="Cat Clinic at Canyon Park" t:suite="Ste 159" t:mail_in_forms_available_=Y t:telephone=425-489-1484 t:city=Bothell m:row_number.mwyh-gr8i=3
```

## Meta Commands

```ls
metric m:row_number.mwyh-gr8i p:long l:"Row Number"

entity e:mwyh-gr8i l:"Pet License Sales Locations" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/mwyh-gr8i

property e:mwyh-gr8i t:meta.view v:id=mwyh-gr8i v:category=Pets v:averageRating=0 v:name="Pet License Sales Locations" v:attribution="King County"

property e:mwyh-gr8i t:meta.view.license v:name="Public Domain"

property e:mwyh-gr8i t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:mwyh-gr8i t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| :updated_at | city      | agency                                    | suite   | telephone          | tags_available_ | mail_in_forms_available_ | notes | 
| =========== | ========= | ========================================= | ======= | ================== | =============== | ======================== | ===== | 
| 1309966007  | Auburn    | Parks, Arts and Recreation                |         | 253-931-3043       | Y               | Y                        |       | 
| 1309966008  | Kirkland  | QFC #809                                  |         | 425-827-2205       | Y               | Y                        |       | 
| 1309966010  | Bothell   | Cat Clinic at Canyon Park                 | Ste 159 | 425-489-1484       | N               | Y                        |       | 
| 1309966010  | Tukwila   | Tukwila City Hall                         |         | 206-433-1800       | Y               | Y                        |       | 
| 1309966010  | Carnation | Carnation City Hall                       |         | 425-333-4192       | Y               | Y                        |       | 
| 1309966011  | Kirkland  | Kirkland City Hall                        |         | 425-587-3100       | Y               | Y                        |       | 
| 1309966011  | Enumclaw  | Enumclaw City Hall                        |         | 360-825-3591 x5605 | Y               | Y                        |       | 
| 1309966012  | Kirkland  | Kirkland Animal Hospital                  |         | 425-822-8231       | N               | Y                        |       | 
| 1311956176  | Kent      | VCA Kent Animal Hospital                  |         | 253-852-8460       | N               | Y                        |       | 
| 1312991515  | Redmond   | King County Marymoor Park Business Office |         | 206-296-0673       | Y               | Y                        |       | 
```