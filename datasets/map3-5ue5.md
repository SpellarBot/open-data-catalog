# Rural Health Clinics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rural-health-clinics-c972f) |
| Metadata | [Link](https://data.hawaii.gov/api/views/map3-5ue5) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/map3-5ue5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/map3-5ue5/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | map3-5ue5 |
| Name | Rural Health Clinics |
| Attribution | Department of Health |
| Category | Health |
| Tags | rural, health |
| Created | 2012-08-26T22:01:27Z |
| Publication Date | 2012-10-10T00:57:24Z |

## Description

Department of Health Rural Health Clinic

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
| Yes      | series tag     | phone       | PHONE      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:map3-5ue5 d:2012-08-26T15:01:33.000Z t:phone=553-5331 t:services="Rural Health Clinic" t:zip_code=96748 t:name="Molokai General Hospital Rural Health Clinic" t:island=Hawaii m:house=280

series e:map3-5ue5 d:2012-08-26T15:01:33.000Z t:phone=928-8331 t:services="Rural Health Clinic" t:zip_code=96777 t:name="Ka-u Hospital Rural Health Clinic" t:island=Hawaii m:house=1
```

## Meta Commands

```ls
metric m:house p:integer l:House t:dataTypeName=number

entity e:map3-5ue5 l:"Rural Health Clinics" t:attribution="Department of Health" t:url=https://data.hawaii.gov/api/views/map3-5ue5

property e:map3-5ue5 t:meta.view v:id=map3-5ue5 v:category=Health v:attributionLink=http://hawaii.gov/health v:averageRating=0 v:name="Rural Health Clinics" v:attribution="Department of Health"

property e:map3-5ue5 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:map3-5ue5 t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:map3-5ue5 t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | name                                         | services            | house | zip_code | island | phone    | 
| =========== | ============================================ | =================== | ===== | ======== | ====== | ======== | 
| 1345993293  | Molokai General Hospital Rural Health Clinic | Rural Health Clinic | 280   | 96748    | Hawaii | 553-5331 | 
| 1345993293  | Ka-u Hospital Rural Health Clinic            | Rural Health Clinic | 1     | 96777    | Hawaii | 928-8331 | 
```