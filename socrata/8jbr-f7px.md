# IDPH Birthing Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-birthing-centers) |
| Metadata | [Link](https://data.illinois.gov/api/views/8jbr-f7px) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/8jbr-f7px/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/8jbr-f7px/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 8jbr-f7px |
| Name | IDPH Birthing Centers |
| Attribution | IDPH |
| Category | Health |
| Created | 2016-07-12T14:31:54Z |
| Publication Date | 2016-10-05T18:14:40Z |

## Description

Birthing centers provide the location of birthing center in Illinois as of January 2017

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| Yes      | series tag  | birthing_centers | Birthing Centers | text      | text        |
| Yes      | series tag  | county           | County           | text      | text        |
| Yes      | series tag  | phone            | Phone            | text      | text        |
| Yes      | series tag  | licence_number   | Licence Number   | text      | text        |
| Yes      | time        | expiry_date      | Expiry Date      | text      | text        |
```

## Time Field

```ls
Value = expiry_date
Format & Zone = MM/dd/yy
```

## Data Commands

```ls
series e:8jbr-f7px d:2017-09-23T00:00:00.000Z t:phone="(309) 722-4020" t:county="Mc Lean" t:birthing_centers="Bloomington-Normal Birthing Center" t:licence_number=4000031 m:row_number.8jbr-f7px=1

series e:8jbr-f7px d:2017-10-08T00:00:00.000Z t:phone="(708) 386-0845" t:county=Cook t:birthing_centers="PCC South Family Health Center" t:licence_number=4000029 m:row_number.8jbr-f7px=2
```

## Meta Commands

```ls
metric m:row_number.8jbr-f7px p:long l:"Row Number"

entity e:8jbr-f7px l:"IDPH Birthing Centers" t:attribution=IDPH t:url=https://data.illinois.gov/api/views/8jbr-f7px

property e:8jbr-f7px t:meta.view v:id=8jbr-f7px v:category=Health v:averageRating=0 v:name="IDPH Birthing Centers" v:attribution=IDPH

property e:8jbr-f7px t:meta.view.owner v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:displayName="IDPH Staff"

property e:8jbr-f7px t:meta.view.tableauthor v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:roleName=publisher v:displayName="IDPH Staff"
```

## Top Records

```ls
| birthing_centers                   | county  | phone          | licence_number | expiry_date | 
| ================================== | ======= | ============== | ============== | =========== | 
| Bloomington-Normal Birthing Center | Mc Lean | (309) 722-4020 | 4000031        | 09/23/17    | 
| PCC South Family Health Center     | Cook    | (708) 386-0845 | 4000029        | 10/08/17    | 
```