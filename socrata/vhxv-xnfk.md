# MNM Feature Types

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mnm-feature-types) |
| Metadata | [Link](https://data.seattle.gov/api/views/vhxv-xnfk) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/vhxv-xnfk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/vhxv-xnfk/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | vhxv-xnfk |
| Name | MNM Feature Types |
| Category | City Business |
| Created | 2015-07-01T20:39:50Z |
| Publication Date | 2015-07-01T20:41:33Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| No       |                | id          | ID         | text      | number      |
| Yes      | series tag     | category    | category   | text      | text        |
| Yes      | series tag     | name        | NAME       | text      | text        |
| Yes      | series tag     | imagepath   | IMAGEPATH  | text      | text        |
| Yes      | numeric metric | sortorder   | SORTORDER  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:vhxv-xnfk d:2015-07-01T13:39:56.000Z t:category="ARTS AND RECREATION" t:imagepath=generalattraction.gif t:name="General Attractions" m:sortorder=1

series e:vhxv-xnfk d:2015-07-01T13:39:56.000Z t:category="ARTS AND RECREATION" t:imagepath=museums.gif t:name="Museums and Galleries" m:sortorder=2

series e:vhxv-xnfk d:2015-07-01T13:39:56.000Z t:category="ARTS AND RECREATION" t:imagepath=public_art.gif t:name="Public Art" m:sortorder=3
```

## Meta Commands

```ls
metric m:sortorder p:integer l:SORTORDER t:dataTypeName=number

entity e:vhxv-xnfk l:"MNM Feature Types" t:url=https://data.seattle.gov/api/views/vhxv-xnfk

property e:vhxv-xnfk t:meta.view v:id=vhxv-xnfk v:category="City Business" v:averageRating=0 v:name="MNM Feature Types"

property e:vhxv-xnfk t:meta.view.license v:name="Public Domain"

property e:vhxv-xnfk t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:vhxv-xnfk t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | id | category            | name                              | imagepath             | sortorder | 
| =========== | == | =================== | ================================= | ===================== | ========= | 
| 1435757996  | 23 | ARTS AND RECREATION | General Attractions               | generalattraction.gif | 1         | 
| 1435757996  | 24 | ARTS AND RECREATION | Museums and Galleries             | museums.gif           | 2         | 
| 1435757996  | 51 | ARTS AND RECREATION | Public Art                        | public_art.gif        | 3         | 
| 1435757996  | 46 | ARTS AND RECREATION | Seattle Center                    | seattle_center.gif    | 4         | 
| 1435757996  | 19 | COMMUNITY           | Cemeteries                        | cemeterry.gif         | 1         | 
| 1435757996  | 70 | COMMUNITY           | Community Volunteer Organizations | unitedway.gif         | 2         | 
| 1435757996  | 54 | COMMUNITY           | Computer/Media Center             | commTechnology.gif    | 3         | 
| 1435757996  | 61 | COMMUNITY           | Family Support Center             | familysupport.gif     | 4         | 
| 1435757996  | 45 | COMMUNITY           | Farmers Markets                   | farmers_market.gif    | 5         | 
| 1435757996  | 53 | COMMUNITY           | Food Banks                        | food_banks.gif        | 6         | 
```