# Block Watch

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/block-watch-a313f) |
| Metadata | [Link](https://data.seattle.gov/api/views/n3gw-htbc) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/n3gw-htbc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/n3gw-htbc/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | n3gw-htbc |
| Name | Block Watch |
| Attribution | City Groups |
| Category | Public Safety |
| Tags | block watch, police, public safety, neighborhood watch |
| Created | 2011-10-11T22:08:35Z |
| Publication Date | 2012-04-23T18:10:47Z |

## Description

from City groups

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | name           | Name           | text      | text        |
| Yes      | series tag  | categories     | Categories     | text      | text        |
| Yes      | series tag  | type_of_group  | Type of Group  | text      | text        |
| Yes      | series tag  | audience_size  | Audience Size  | text      | text        |
| Yes      | series tag  | activity_level | Activity Level | text      | text        |
| Yes      | series tag  | contact        | Contact        | text      | text        |
| Yes      | series tag  | url            | Url            | url       | url         |
| Yes      | series tag  | description    | Description    | text      | text        |
| Yes      | series tag  | email          | Email          | text      | text        |
| Yes      | series tag  | source         | Source         | text      | text        |
| Yes      | series tag  | neighborhood   | Neighborhood   | text      | text        |
| Yes      | series tag  | city           | City           | text      | text        |
| Yes      | series tag  | zipcode        | zipcode        | text      | text        |
| Yes      | series tag  | county         | County         | text      | text        |
| Yes      | series tag  | state          | State          | text      | text        |
| No       |             | latitude       | latitude       | number    | number      |
| No       |             | longitude      | longitude      | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:n3gw-htbc d:2012-04-23T11:10:44.000Z t:audience_size="10-25 People" t:type_of_group="E-mail list" t:name="10400 block of 34th Ave. S.W." t:activity_level="Every Few Months" t:zipcode=98146 t:state=WA t:neighborhood="West Seattle" t:categories="Block Watch, Crime Prevention, National Night Out" t:city=Seattle m:row_number.n3gw-htbc=1

series e:n3gw-htbc d:2012-04-23T11:10:45.000Z t:type_of_group=Blog t:name="4700-4800 23rd Ave SW/Puget Blvd SW Block Watch" t:categories="Block Watch, Crime Prevention, Pedestrian Improvements, Beautification" t:contact="Chat to someone on the street, they will direct you to the contact person." m:row_number.n3gw-htbc=2

series e:n3gw-htbc d:2012-04-23T11:10:45.000Z t:audience_size="50-100 People" t:type_of_group="E-mail list" t:name="8400 Block 8th Ave SW" t:activity_level=Occasionally t:categories="Block Watch, Crime Prevention" m:row_number.n3gw-htbc=3
```

## Meta Commands

```ls
metric m:row_number.n3gw-htbc p:long l:"Row Number"

entity e:n3gw-htbc l:"Block Watch" t:attribution="City Groups" t:url=https://data.seattle.gov/api/views/n3gw-htbc

property e:n3gw-htbc t:meta.view v:id=n3gw-htbc v:category="Public Safety" v:attributionLink=http://seattle.citygroups.org/taxonomy/term/721 v:averageRating=0 v:name="Block Watch" v:attribution="City Groups"

property e:n3gw-htbc t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:n3gw-htbc t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | name                                            | categories                                                             | type_of_group | audience_size | activity_level   | contact                                                                    | url          | description | email | source             | neighborhood    | city    | zipcode | county | state | latitude | longitude | 
| =========== | =============================================== | ====================================================================== | ============= | ============= | ================ | ========================================================================== | ============ | =========== | ===== | ================== | =============== | ======= | ======= | ====== | ===== | ======== | ========= | 
| 1335179444  | 10400 block of 34th Ave. S.W.                   | Block Watch, Crime Prevention, National Night Out                      | E-mail list   | 10-25 People  | Every Few Months |                                                                            | [null, null] |             |       |                    | West Seattle    | Seattle | 98146   |        | WA    | 47.5084  | -122.375  | 
| 1335179445  | 4700-4800 23rd Ave SW/Puget Blvd SW Block Watch | Block Watch, Crime Prevention, Pedestrian Improvements, Beautification | Blog          |               |                  | Chat to someone on the street, they will direct you to the contact person. | [null, null] |             |       |                    |                 |         |         |        |       |          |           | 
| 1335179445  | 8400 Block 8th Ave SW                           | Block Watch, Crime Prevention                                          | E-mail list   | 50-100 People | Occasionally     |                                                                            | [null, null] |             |       |                    |                 |         |         |        |       |          |           | 
| 1335179445  | 7900 & 7800 Block 34th Ave SW                   | Block Watch, Crime Prevention                                          | E-mail list   | 50-100 People | Occasionally     | 7900.34thavesw@gmail.com                                                   | [null, null] |             |       |                    | West Seattle    | Seattle | 98126   |        | WA    | -47.5302 | 122.376   | 
| 1335179445  | 2600 Block SW Nevada Street                     | Block Watch, Crime Prevention                                          | E-mail list   | 50-100 People | Occasionally     | Email                                                                      | [null, null] |             |       | Blockwatch Captain |                 |         |         |        |       |          |           | 
| 1335179445  | 3200 Block of 56th Ave SW                       | Block Watch, Crime Prevention                                          | E-mail list   | 50-100 People | Occasionally     |                                                                            | [null, null] |             |       |                    | Genesee-Schmitz | Seattle | 98116   |        | WA    | 47.5746  | -122.405  | 
| 1335179445  | West of Schmitz Park                            | Block Watch, Crime Prevention                                          | E-mail list   | 50-100 People | Occasionally     |                                                                            | [null, null] |             |       |                    | Genesee-Schmitz | Seattle | 98116   |        | WA    |          |           | 
| 1335179445  | West of Schmitz Park                            | Block Watch, Crime Prevention                                          | E-mail list   | 50-100 People | Occasionally     |                                                                            | [null, null] |             |       |                    |                 |         |         |        |       |          |           | 
| 1335179445  | 4700 45th Ave SW Block Watch                    | Block Watch, Crime Prevention                                          | E-mail list   | 50-100 People | Occasionally     |                                                                            | [null, null] |             |       |                    |                 |         |         |        |       |          |           | 
| 1335179445  | 7100 Block 34th Ave SW                          | Block Watch, Crime Prevention                                          | E-mail list   | 50-100 People | Occasionally     |                                                                            | [null, null] |             |       |                    |                 |         |         |        |       |          |           | 
```