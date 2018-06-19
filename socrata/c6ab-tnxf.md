# Department of Defense Hawaii Air National Guard

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-defense-hawaii-air-national-guard-2a63f) |
| Metadata | [Link](https://data.hawaii.gov/api/views/c6ab-tnxf) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/c6ab-tnxf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/c6ab-tnxf/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | c6ab-tnxf |
| Name | Department of Defense Hawaii Air National Guard |
| Attribution | Department of Defense |
| Category | Public Safety |
| Tags | hiang |
| Created | 2012-07-31T21:39:20Z |
| Publication Date | 2012-07-31T21:43:29Z |

## Description

Hawaii Air National Guard Facility Locations

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | component   | Component  | text      | text        |
| Yes      | series tag  | island      | Island     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:c6ab-tnxf d:2012-07-31T14:39:21.000Z t:component=Component t:island=Island m:row_number.c6ab-tnxf=1

series e:c6ab-tnxf d:2012-07-31T14:39:21.000Z t:component="Hawaii Air National Guard" t:island=Kauai m:row_number.c6ab-tnxf=2

series e:c6ab-tnxf d:2012-07-31T14:39:21.000Z t:component="Hawaii Air National Guard" t:island=Kauai m:row_number.c6ab-tnxf=3
```

## Meta Commands

```ls
metric m:row_number.c6ab-tnxf p:long l:"Row Number"

entity e:c6ab-tnxf l:"Department of Defense Hawaii Air National Guard" t:attribution="Department of Defense" t:url=https://data.hawaii.gov/api/views/c6ab-tnxf

property e:c6ab-tnxf t:meta.view v:id=c6ab-tnxf v:category="Public Safety" v:attributionLink=http://hawaii.gov/dod v:averageRating=0 v:name="Department of Defense Hawaii Air National Guard" v:attribution="Department of Defense"

property e:c6ab-tnxf t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:c6ab-tnxf t:meta.view.owner v:id=a7ka-qy6t v:screenName="Reynold Hioki" v:displayName="Reynold Hioki"

property e:c6ab-tnxf t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | component                 | island | 
| =========== | ========================= | ====== | 
| 1343745561  | Component                 | Island | 
| 1343745561  | Hawaii Air National Guard | Kauai  | 
| 1343745561  | Hawaii Air National Guard | Kauai  | 
| 1343745561  | Hawaii Air National Guard | Oahu   | 
| 1343745561  | Hawaii Air National Guard | Oahu   | 
| 1343745561  | Hawaii Air National Guard | Oahu   | 
| 1343745561  | Hawaii Air National Guard | Oahu   | 
| 1343745561  | Hawaii Air National Guard | Oahu   | 
| 1343745561  | Hawaii Air National Guard | Maui   | 
| 1343745561  | Hawaii Air National Guard | Hawaii | 
```