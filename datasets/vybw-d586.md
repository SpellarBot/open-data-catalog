# IDPH Public and Private Beaches

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-public-and-private-beaches-ad028) |
| Metadata | [Link](https://data.illinois.gov/api/views/vybw-d586) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/vybw-d586/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/vybw-d586/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | vybw-d586 |
| Name | IDPH Public and Private Beaches |
| Attribution | Illinois Department of Public Health |
| Category | Environment |
| Tags | beach |
| Created | 2011-06-17T15:15:15Z |
| Publication Date | 2011-06-17T15:15:15Z |

## Description

Data extracted from IDPH Beach Monitoring site

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | beach_name         | beach_name         | text      | text        |
| Yes      | series tag  | waterbody_name     | waterbody_name     | text      | text        |
| Yes      | series tag  | waterbody_type     | waterbody_type     | text      | text        |
| Yes      | series tag  | county             | county             | text      | text        |
| Yes      | series tag  | site_type          | site_type          | text      | text        |
| Yes      | series tag  | ownership_type     | ownership_type     | text      | text        |
| Yes      | series tag  | site_url           | site_url           | text      | text        |
| Yes      | series tag  | epa_prawn_beach_id | epa_prawn_beach_id | text      | text        |
| Yes      | series tag  | epa_storet_number  | epa_storet_number  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vybw-d586 d:2011-06-17T08:15:19.000Z t:ownership_type=Individual t:county=STARK t:waterbody_type="Inland Lake" t:site_type="Public Beach" t:beach_name="Allendale Conservation Club" m:row_number.vybw-d586=1

series e:vybw-d586 d:2011-06-17T08:15:19.000Z t:ownership_type=Individual t:county="ST CLAIR" t:waterbody_type="Inland Lake" t:site_type="Public Beach" t:beach_name="American Legion Freedom Farm" m:row_number.vybw-d586=2

series e:vybw-d586 d:2011-06-17T08:15:19.000Z t:ownership_type=Individual t:county=EFFINGHAM t:waterbody_type="Inland Lake" t:site_type="Public Beach" t:beach_name="Anthony Acres Resort Inc" m:row_number.vybw-d586=3
```

## Meta Commands

```ls
metric m:row_number.vybw-d586 p:long l:"Row Number"

entity e:vybw-d586 l:"IDPH Public and Private Beaches" t:attribution="Illinois Department of Public Health" t:url=https://data.illinois.gov/api/views/vybw-d586

property e:vybw-d586 t:meta.view v:id=vybw-d586 v:category=Environment v:attributionLink=http://app.idph.state.il.us/envhealth/ilbeaches/public/default.aspx v:averageRating=0 v:name="IDPH Public and Private Beaches" v:attribution="Illinois Department of Public Health"

property e:vybw-d586 t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:vybw-d586 t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| :updated_at | beach_name                   | waterbody_name | waterbody_type | county     | site_type     | ownership_type | site_url | epa_prawn_beach_id | epa_storet_number | 
| =========== | ============================ | ============== | ============== | ========== | ============= | ============== | ======== | ================== | ================= | 
| 1308298519  | Allendale Conservation Club  |                | Inland Lake    | STARK      | Public Beach  | Individual     |          |                    |                   | 
| 1308298519  | American Legion Freedom Farm |                | Inland Lake    | ST CLAIR   | Public Beach  | Individual     |          |                    |                   | 
| 1308298519  | Anthony Acres Resort Inc     |                | Inland Lake    | EFFINGHAM  | Public Beach  | Individual     |          |                    |                   | 
| 1308298519  | Apple Canyon Lake - Nixon    |                | Inland Lake    | JO DAVIESS | Public Beach  | Individual     |          |                    |                   | 
| 1308298519  | Area No 1 Outdoor Club       |                | Inland Lake    | WILL       | Private Beach | Organization   |          |                    |                   | 
| 1308298519  | Avondale Lake                |                | Inland Lake    | FULTON     | Public Beach  | Individual     |          |                    |                   | 
| 1308298519  | Batavia Quarry Beach         |                | Inland Lake    | KANE       | Private Beach | Organization   |          |                    |                   | 
| 1308298519  | Blue Lake Resort             |                | Inland Lake    | WHITESIDE  | Private Beach | Organization   |          |                    |                   | 
| 1308298519  | Blue Ridge Club              |                | Inland Lake    | SANGAMON   | Public Beach  | Individual     |          |                    |                   | 
| 1308298519  | Bur Oaks Resort Inc          |                | Inland Lake    | MADISON    | Public Beach  | Individual     |          |                    |                   | 
```