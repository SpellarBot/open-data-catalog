# King County Worksites

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-worksites-5d14c) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/65fu-sm5s) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/65fu-sm5s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/65fu-sm5s/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 65fu-sm5s |
| Name | King County Worksites |
| Attribution | King County |
| Category | Operations |
| Tags | buildings maps locations worksites |
| Created | 2011-06-30T23:40:27Z |
| Publication Date | 2011-06-30T23:40:27Z |

## Description

A list of all the buildings King County currently uses for staff worksites.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| No       | time        | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag  | department    | Department    | text      | text        |
| Yes      | series tag  | division      | Division      | text      | text        |
| Yes      | series tag  | building      | Building      | text      | text        |
| No       |             | address       | Address       | text      | text        |
| Yes      | series tag  | city          | City          | text      | text        |
| Yes      | series tag  | state         | State         | text      | text        |
| Yes      | series tag  | zip_code      | Zip Code      | text      | text        |
| Yes      | series tag  | building_type | Building Type | text      | text        |
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
series e:65fu-sm5s d:2011-06-30T16:40:29.000Z t:building="DUTCH SISLER" t:division="MHCADS - Dutch Sisler" t:department=DCHS t:state=WA t:building_type=clinic m:row_number.65fu-sm5s=1

series e:65fu-sm5s d:2011-06-30T16:40:29.000Z t:department=TOTAL m:row_number.65fu-sm5s=2

series e:65fu-sm5s d:2011-06-30T16:40:29.000Z t:building="SOUTH SEATTLE COMMUNITY COLLEGE" t:division="CSD - DWP" t:department=DCHS t:state=98108 t:building_type=worktraining t:city=Seattle m:row_number.65fu-sm5s=3
```

## Meta Commands

```ls
metric m:row_number.65fu-sm5s p:long l:"Row Number"

entity e:65fu-sm5s l:"King County Worksites" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/65fu-sm5s

property e:65fu-sm5s t:meta.view v:id=65fu-sm5s v:category=Operations v:attributionLink=http://www.kingcounty.gov v:averageRating=0 v:name="King County Worksites" v:attribution="King County"

property e:65fu-sm5s t:meta.view.license v:name="Public Domain"

property e:65fu-sm5s t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:65fu-sm5s t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| :updated_at | department | division                         | building                           | address                 | city    | state | zip_code | building_type  | 
| =========== | ========== | ================================ | ================================== | ======================= | ======= | ===== | ======== | ============== | 
| 1309452029  | DCHS       | MHCADS - Dutch Sisler            | DUTCH SISLER                       | 1930 BOREN AVE          |         | WA    |          | clinic         | 
| 1309452029  | TOTAL      |                                  |                                    |                         |         |       |          |                | 
| 1309452029  | DCHS       | CSD - DWP                        | SOUTH SEATTLE COMMUNITY COLLEGE    | 6737 corson Ave S       | Seattle | 98108 |          | worktraining   | 
| 1309452029  | DES        | REALS - Community Service Center | FALL CITY COMMUNITY SERVICE CENTER | ???                     |         | WA    |          | service center | 
| 1309452029  | SO         |                                  | SNOQUALMIE PASS FPD #51            | SNOQ. PASS COMM. CENTER |         | WA    |          | OFFICE         | 
| 1309452029  | DNRP/PARKS |                                  | STATE OF WA                        | ADJ TO AURURN NARR0WS   |         | WA    |          | PARK           | 
| 1309452029  | DNRP/PARKS |                                  | SHORELINE SCHOOL DIST              | CORDELL HULL SCHOOL     |         | WA    |          | PARK           | 
| 1309452029  | DNRP/PARKS |                                  | US ARMY CORPS OF ENGRS.            | COUGAR MOUNTAIN PARK    |         | WA    |          | PARK           | 
| 1309452029  | DNRP/PARKS |                                  | STATE OF WA                        | DOCKTON PARK            |         | WA    |          | PARK           | 
| 1309452029  | DNRP/PARKS |                                  | PUGET POWER                        | INTERURBAN TRAIL        |         | WA    |          | PARK           | 
```