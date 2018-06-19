# Agricultural and Conservation Easement Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/agricultural-and-conservation-easement-inventory) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/jh6m-rvdj) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/jh6m-rvdj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/jh6m-rvdj/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | jh6m-rvdj |
| Name | Agricultural and Conservation Easement Inventory |
| Attribution | Office of Agriculture |
| Category | Community/Recreation |
| Tags | agriculture, easement |
| Created | 2016-07-20T13:11:52Z |
| Publication Date | 2017-03-22T15:10:39Z |

## Description

Inventory of Agricultural preservation and conservation land easements located in the County.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name              | Data Type | Render Type |
| ======== | ============== | ============== | ================= | ========= | =========== |
| No       | time           | :updated_at    | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | program        | Program           | text      | text        |
| Yes      | numeric metric | elec_dist      | Election District | number    | text        |
| Yes      | series tag     | primary_tax_id | Primary Tax ID    | text      | text        |
| No       |                | date_aquired   | Date Aquired      | text      | text        |
| Yes      | series tag     | grantor        | Grantor           | text      | text        |
| Yes      | series tag     | owner          | Property Owner    | text      | text        |
| Yes      | series tag     | easement_acres | Easement Acres    | text      | text        |
| Yes      | series tag     | number         | Street Number     | text      | text        |
| Yes      | series tag     | street         | Street            | text      | text        |
| Yes      | series tag     | city           | City              | text      | text        |
| Yes      | series tag     | state          | State             | text      | text        |
| Yes      | series tag     | zipcode        | Zipcode           | text      | text        |
| Yes      | numeric metric | tax_id_1       | Tax ID -1         | number    | text        |
| Yes      | numeric metric | tax_id_2       | Tax ID - 2        | number    | text        |
| Yes      | numeric metric | tax_id_3       | Tax ID - 3        | number    | text        |
| Yes      | numeric metric | tax_id_4       | Tax ID -4         | number    | text        |
| Yes      | numeric metric | tax_id_5       | Tax ID - 5        | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date_aquired
```

## Data Commands

```ls
series e:jh6m-rvdj d:2016-07-20T06:11:58.000Z t:easement_acres=57 t:program=AEP t:zipcode=20842-8915 t:street="BIG WOODS RD" t:owner="THOMS, RICHARD W ET AL TR" t:state=MD t:number=21700 t:grantor=Thoms t:primary_tax_id=1679436 t:city=DICKERSON m:elec_dist=11

series e:jh6m-rvdj d:2016-07-20T06:11:58.000Z t:easement_acres=25 t:program=AEP t:zipcode=20841 t:street="BUCKLODGE RD" t:owner="WARE, THOMAS L & E J" t:state=MD t:number=19310 t:grantor=Ware t:primary_tax_id=2168372 t:city=BOYDS m:elec_dist=11

series e:jh6m-rvdj d:2016-07-20T06:11:58.000Z t:easement_acres=65.97 t:program=AEP t:zipcode=20871 t:street="BURNT HILL RD" t:owner="HANEY, MARY E ET AL" t:state=MD t:number=24801 t:grantor=Woodfield t:primary_tax_id=23262 t:city=CLARKSBURG m:elec_dist=2 m:tax_id_2=23273 m:tax_id_1=23251
```

## Meta Commands

```ls
metric m:elec_dist p:integer l:"Election District" d:"Election District" t:dataTypeName=number

metric m:tax_id_1 p:integer l:"Tax ID -1" d:"Tax ID property 1" t:dataTypeName=number

metric m:tax_id_2 p:integer l:"Tax ID - 2" d:"Tax ID property 2" t:dataTypeName=number

metric m:tax_id_3 p:integer l:"Tax ID - 3" d:"Tax ID property 3" t:dataTypeName=number

metric m:tax_id_4 p:integer l:"Tax ID -4" d:"Tax ID property 4" t:dataTypeName=number

metric m:tax_id_5 p:integer l:"Tax ID - 5" d:"Tax ID property 5" t:dataTypeName=number

entity e:jh6m-rvdj l:"Agricultural and Conservation Easement Inventory" t:attribution="Office of Agriculture" t:url=https://data.montgomerycountymd.gov/api/views/jh6m-rvdj

property e:jh6m-rvdj t:meta.view v:id=jh6m-rvdj v:category=Community/Recreation v:attributionLink=https://www.montgomerycountymd.gov/agservices/ v:averageRating=0 v:name="Agricultural and Conservation Easement Inventory" v:attribution="Office of Agriculture"

property e:jh6m-rvdj t:meta.view.owner v:id=rykt-6e5x v:profileImageUrlMedium=/api/users/rykt-6e5x/profile_images/THUMB v:profileImageUrlLarge=/api/users/rykt-6e5x/profile_images/LARGE v:screenName=Brian v:profileImageUrlSmall=/api/users/rykt-6e5x/profile_images/TINY v:displayName=Brian

property e:jh6m-rvdj t:meta.view.tableauthor v:id=rykt-6e5x v:profileImageUrlMedium=/api/users/rykt-6e5x/profile_images/THUMB v:profileImageUrlLarge=/api/users/rykt-6e5x/profile_images/LARGE v:screenName=Brian v:profileImageUrlSmall=/api/users/rykt-6e5x/profile_images/TINY v:roleName=editor v:displayName=Brian
```

## Top Records

```ls
| :updated_at | program      | elec_dist | primary_tax_id | date_aquired | grantor            | owner                     | easement_acres     | number | street        | city         | state | zipcode    | tax_id_1 | tax_id_2 | tax_id_3 | tax_id_4 | tax_id_5 | 
| =========== | ============ | ========= | ============== | ============ | ================== | ========================= | ================== | ====== | ============= | ============ | ===== | ========== | ======== | ======== | ======== | ======== | ======== | 
| 1468995118  | AEP          | 11        | 1679436        | 12/89        | Thoms              | THOMS, RICHARD W ET AL TR | 57                 | 21700  | BIG WOODS RD  | DICKERSON    | MD    | 20842-8915 |          |          |          |          |          | 
| 1468995118  | AEP          | 11        | 2168372        | 1/1/93       | Ware               | WARE, THOMAS L & E J      | 25                 | 19310  | BUCKLODGE RD  | BOYDS        | MD    | 20841      |          |          |          |          |          | 
| 1468995118  | AEP          | 2         | 23262          | 12/1998      | Woodfield          | HANEY, MARY E ET AL       | 65.97              | 24801  | BURNT HILL RD | CLARKSBURG   | MD    | 20871      | 23251    | 23273    |          |          |          | 
| 1468995118  | AEP          | 11        | 913695         | 12/1991      | Checkley           | CHECKLEY, NORMA ET AL TR  | 157.06             | 17110  | COMUS RD      | DICKERSON    | MD    | 20842      |          |          |          |          |          | 
| 1468995118  | AEP          | 11        | 3129401        | 11/1995      | Seligson           | SWEETWATER FARM LLC       | 95.72              | 12165  | DARNESTOWN RD | GAITHERSBURG | MD    | 20878-2205 |          |          |          |          |          | 
| 1468995118  | AEP          | 11        | 3129241        | 11/1995      | Seligson           | SWEETWATER FARM LLC       | 99.3               | 12165  | DARNESTOWN RD | GAITHERSBURG | MD    | 20878-2205 |          |          |          |          |          | 
| 1468995118  | Private -BLT | 2         | 1573625        |              | A.S. McGaughan, Jr | A.S. McGaughan, Jr        | 5                  | 26315  | HAINES RD     | CLARKSBURG   | MD    | 20871      |          |          |          |          |          | 
| 1468995118  | Private -BLT | 2         | 1607958        |              | A.S. McGaughan, Jr | A.S. McGaughan, Jr        | 5                  | 26405  | HAINES RD     | CLARKSBURG   | MD    | 20871      |          |          |          |          |          | 
| 1468995118  | Private -BLT | 2         | 1607947        |              | A.S. McGaughan, Jr | A.S. McGaughan, Jr        | 5                  | 26355  | HAINES RD     | CLARKSBURG   | MD    | 20871      |          |          |          |          |          | 
| 1468995118  | RLP          | 3         | 41523          | 9/01         | Patricia Vajda     | J A K E ENTERPRISES LC    | 212.00800000000001 | 9936   | MAIN ST       | FAIRFAX      | VA    | 22031-3901 |          |          |          |          |          | 
```