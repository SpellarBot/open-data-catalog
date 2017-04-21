# Pet License Sales Locations WITH TAGS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pet-license-sales-locations-with-tags-ad2a3) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/wzcu-fvew) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/wzcu-fvew/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/wzcu-fvew/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | wzcu-fvew |
| Name | Pet License Sales Locations WITH TAGS |
| Category | Pets |
| Created | 2012-09-26T21:09:04Z |
| Publication Date | 2017-01-05T22:35:08Z |

## Description

Locations that have license tags available for sale

## Columns

```ls
| Included | Schema Type | Field Name                | Name                       | Data Type | Render Type |
| ======== | =========== | ========================= | ========================== | ========= | =========== |
| No       | time        | :updated_at               | updated_at                 | meta_data | meta_data   |
| Yes      | series tag  | city                      | City                       | text      | text        |
| Yes      | series tag  | agency                    | Agency                     | text      | text        |
| Yes      | series tag  | suite                     | Suite                      | text      | text        |
| Yes      | series tag  | telephone                 | Telephone                  | text      | text        |
| Yes      | series tag  | license_tags_available    | License Tags Available?    | text      | text        |
| Yes      | series tag  | license_mailers_available | License Mailers Available? | text      | text        |
| Yes      | series tag  | notes                     | Notes                      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wzcu-fvew d:2013-02-12T12:15:29.000Z t:license_tags_available=Y t:license_mailers_available=N t:agency="Clyde Hill City Hall" t:telephone=425-453-7800 t:city="Clyde Hill" m:row_number.wzcu-fvew=1

series e:wzcu-fvew d:2013-02-12T12:15:29.000Z t:license_tags_available=Y t:license_mailers_available=N t:agency="Newcastle City Hall" t:suite="Ste 200" t:telephone=425-649-4444 t:city=Newcastle m:row_number.wzcu-fvew=2

series e:wzcu-fvew d:2013-02-12T12:15:29.000Z t:license_tags_available=Y t:license_mailers_available=N t:agency="Woodinville City Hall" t:telephone=425-489-2700 t:city=Woodinville m:row_number.wzcu-fvew=3
```

## Meta Commands

```ls
metric m:row_number.wzcu-fvew p:long l:"Row Number"

entity e:wzcu-fvew l:"Pet License Sales Locations WITH TAGS" t:url=https://data.kingcounty.gov/api/views/wzcu-fvew

property e:wzcu-fvew t:meta.view v:id=wzcu-fvew v:category=Pets v:averageRating=0 v:name="Pet License Sales Locations WITH TAGS"

property e:wzcu-fvew t:meta.view.license v:name="Public Domain"

property e:wzcu-fvew t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:wzcu-fvew t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| :updated_at | city          | agency                                    | suite   | telephone    | license_tags_available | license_mailers_available | notes | 
| =========== | ============= | ========================================= | ======= | ============ | ====================== | ========================= | ===== | 
| 1360671329  | Clyde Hill    | Clyde Hill City Hall                      |         | 425-453-7800 | Y                      | N                         |       | 
| 1360671329  | Newcastle     | Newcastle City Hall                       | Ste 200 | 425-649-4444 | Y                      | N                         |       | 
| 1360671329  | Woodinville   | Woodinville City Hall                     |         | 425-489-2700 | Y                      | N                         |       | 
| 1360671329  | Redmond       | QFC #820                                  |         | 425-885-2311 | Y                      | N                         |       | 
| 1360671329  | Redmond       | Old Redmond School House Community Center |         | 425-556-2300 | Y                      | N                         |       | 
| 1360671329  | Bothell       | Worthington Licensing Agency              |         | 425-481-1714 | Y                      | N                         |       | 
| 1360671329  | Issaquah      | QFC #821                                  |         | 425-392-4475 | Y                      | N                         |       | 
| 1360671329  | Mercer Island | QFC #806                                  |         | 206-232-0102 | Y                      | N                         |       | 
| 1360671329  | Covington     | Covington City Hall                       | Ste 100 | 253-638-1110 | Y                      | N                         |       | 
| 1360671329  | Bellevue      | QFC #826                                  |         | 425-865-0282 | Y                      | N                         |       | 
```