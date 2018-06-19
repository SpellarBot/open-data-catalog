# Free Standing X-Ray Facility

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/free-standing-x-ray-facility-2425f) |
| Metadata | [Link](https://data.hawaii.gov/api/views/xpu9-ny5u) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/xpu9-ny5u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/xpu9-ny5u/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | xpu9-ny5u |
| Name | Free Standing X-Ray Facility |
| Attribution | Department of Health |
| Category | Health |
| Tags | xray |
| Created | 2012-08-25T01:56:58Z |
| Publication Date | 2012-08-25T01:59:43Z |

## Description

Free standing X-RAY Facility

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | name        | Name       | text      | text        |
| Yes      | series tag     | services    | Services   | text      | text        |
| Yes      | numeric metric | house       | House      | number    | text        |
| Yes      | series tag     | zip_code    | Zip code   | text      | number      |
| Yes      | series tag     | island      | Island     | text      | text        |
| Yes      | series tag     | phone       | Phone      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xpu9-ny5u d:2012-08-24T18:57:04.000Z t:phone=271-5691 t:services="Free-standing X-Ray Facility" t:zip_code=96822 t:name="ALOHA MOBILE IMAGING" t:island=Oahu m:house=1502

series e:xpu9-ny5u d:2012-08-24T18:57:04.000Z t:phone=599-4471 t:services="Free-standing X-Ray Facility" t:zip_code=96813 t:name="PACIFIC MOBILE IMAGING, LLC" t:island=Oahu m:house=1380
```

## Meta Commands

```ls
metric m:house p:integer l:House t:dataTypeName=number

entity e:xpu9-ny5u l:"Free Standing X-Ray Facility" t:attribution="Department of Health" t:url=https://data.hawaii.gov/api/views/xpu9-ny5u

property e:xpu9-ny5u t:meta.view v:id=xpu9-ny5u v:category=Health v:attributionLink=http://hawaii.gov/health v:averageRating=0 v:name="Free Standing X-Ray Facility" v:attribution="Department of Health"

property e:xpu9-ny5u t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:xpu9-ny5u t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:xpu9-ny5u t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | name                        | services                     | house | zip_code | island | phone    | 
| =========== | =========================== | ============================ | ===== | ======== | ====== | ======== | 
| 1345834624  | ALOHA MOBILE IMAGING        | Free-standing X-Ray Facility | 1502  | 96822    | Oahu   | 271-5691 | 
| 1345834624  | PACIFIC MOBILE IMAGING, LLC | Free-standing X-Ray Facility | 1380  | 96813    | Oahu   | 599-4471 | 
```