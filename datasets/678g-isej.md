# Organ Procurement facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/organ-procurement-facilities-2e0b1) |
| Metadata | [Link](https://data.hawaii.gov/api/views/678g-isej) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/678g-isej/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/678g-isej/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 678g-isej |
| Name | Organ Procurement facilities |
| Attribution | Department of Health |
| Category | Health |
| Tags | organ, organs |
| Created | 2012-08-26T21:47:41Z |
| Publication Date | 2012-08-26T21:51:49Z |

## Description

Department of Health Organ Procurement facilities

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | name        | Name       | text      | text        |
| Yes      | series tag     | services    | Services   | text      | text        |
| Yes      | numeric metric | house       | House      | number    | text        |
| Yes      | series tag     | zip_code    | Zip code   | text      | text        |
| Yes      | series tag     | island      | Island     | text      | text        |
| Yes      | series tag     | phone       | PHONE      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:678g-isej d:2012-08-26T14:47:46.000Z t:phone=599-7630 t:services="Organ Procurement Organization" t:zip_code=96817 t:name="LEGACY OF LIFE HAWAII" t:island=Oahu m:house=405
```

## Meta Commands

```ls
metric m:house p:integer l:House t:dataTypeName=number

entity e:678g-isej l:"Organ Procurement facilities" t:attribution="Department of Health" t:url=https://data.hawaii.gov/api/views/678g-isej

property e:678g-isej t:meta.view v:id=678g-isej v:category=Health v:attributionLink=http://hawaii.gov/health v:averageRating=0 v:name="Organ Procurement facilities" v:attribution="Department of Health"

property e:678g-isej t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:678g-isej t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:678g-isej t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | name                  | services                       | house | zip_code | island | phone    | 
| =========== | ===================== | ============================== | ===== | ======== | ====== | ======== | 
| 1345992466  | LEGACY OF LIFE HAWAII | Organ Procurement Organization | 405   | 96817    | Oahu   | 599-7630 | 
```