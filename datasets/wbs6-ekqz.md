# Environmental Control - Project List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/environmental-control-project-list-e2f9b) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/wbs6-ekqz) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/wbs6-ekqz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/wbs6-ekqz/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | wbs6-ekqz |
| Name | Environmental Control - Project List |
| Attribution | Cook County Bureau of Environmental Control |
| Category | Finance & Administration |
| Created | 2012-04-12T07:18:43Z |
| Publication Date | 2014-10-09T22:33:23Z |

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | name           | Name           | text      | text        |
| Yes      | series tag  | street_address | Street Address | text      | text        |
| Yes      | series tag  | zip_code       | Zip Code       | text      | text        |
| Yes      | series tag  | project_type   | Project Type   | text      | text        |
| Yes      | series tag  | link           | Link           | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wbs6-ekqz d:2012-04-12T19:39:23.000Z t:zip_code=Hillside t:name="Aspire Childrens Services-Hillside" t:street_address="1815 South Wolf Road" t:project_type=Illinois m:row_number.wbs6-ekqz=1

series e:wbs6-ekqz d:2012-04-12T19:39:23.000Z t:zip_code=Bellwood t:name="Aspire Childrens Services-Bellwood" t:street_address="5010 St. Charles Road" t:project_type=Illinois m:row_number.wbs6-ekqz=2

series e:wbs6-ekqz d:2012-04-12T19:39:23.000Z t:zip_code=Westchester t:name="Aspire Childrens Services-Westchester" t:street_address="9901 Derby Lane" t:project_type=Illinois m:row_number.wbs6-ekqz=3
```

## Meta Commands

```ls
metric m:row_number.wbs6-ekqz p:long l:"Row Number"

entity e:wbs6-ekqz l:"Environmental Control - Project List" t:attribution="Cook County Bureau of Environmental Control" t:url=https://datacatalog.cookcountyil.gov/api/views/wbs6-ekqz

property e:wbs6-ekqz t:meta.view v:id=wbs6-ekqz v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/environmental_control/291 v:averageRating=0 v:name="Environmental Control - Project List" v:attribution="Cook County Bureau of Environmental Control"

property e:wbs6-ekqz t:meta.view.license v:name="Public Domain"

property e:wbs6-ekqz t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:wbs6-ekqz t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| :updated_at | name                                            | street_address              | zip_code          | project_type | link         | 
| =========== | =============================================== | =========================== | ================= | ============ | ============ | 
| 1334259563  | Aspire Childrens Services-Hillside              | 1815 South Wolf Road        | Hillside          | Illinois     | [null, null] | 
| 1334259563  | Aspire Childrens Services-Bellwood              | 5010 St. Charles Road       | Bellwood          | Illinois     | [null, null] | 
| 1334259563  | Aspire Childrens Services-Westchester           | 9901 Derby Lane             | Westchester       | Illinois     | [null, null] | 
| 1334259563  | Blue Cap                                        | 2155 Broadway Street        | Blue Island       | Illinois     | [null, null] | 
| 1334259563  | Harvey City Hall                                | 15320 Broadway Avenue       | Harvey            | Illinois     | [null, null] | 
| 1334259563  | Clearbrook                                      | 1835 West Central Road      | Arlington Heights | Illinois     | [null, null] | 
| 1334259563  | Elk Grove Park District Administration Building | 225 East Elk Grove Bolevard | Elk Grove         | Illinois     | [null, null] | 
| 1334259563  | Hanover Township Senior Center                  | 240 South Illinois Route 59 | Bartlett          | Illinois     | [null, null] | 
| 1334259563  | Little City Foundation                          | 1760 West Algonquin Road    | Palatine          | Illinois     | [null, null] | 
| 1334259563  | Rolling Meadows Community Center                | 3705 Pheasant Dr            | Rolling Meadows   | Illinois     | [null, null] | 
```