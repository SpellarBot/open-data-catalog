# Med-QUEST Offices

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/med-quest-offices-1eb95) |
| Metadata | [Link](https://data.hawaii.gov/api/views/fek4-ym6q) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/fek4-ym6q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/fek4-ym6q/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | fek4-ym6q |
| Name | Med-QUEST Offices |
| Attribution | DHS |
| Created | 2013-09-11T00:10:00Z |
| Publication Date | 2015-09-11T17:51:52Z |

## Description

Locations

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | unit        | Unit       | text      | text        |
| Yes      | series tag  | room        | Room       | text      | text        |
| Yes      | series tag  | telephone1  | Telephone1 | text      | text        |
| Yes      | series tag  | telephone2  | Telephone2 | text      | text        |
| Yes      | series tag  | fax         | Fax        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fek4-ym6q d:2013-09-10T17:19:15.000Z t:telephone1=587-3521 t:unit="Oahu Section" t:fax=587-3543 t:telephone2=587-3540 t:room="3rd Floor" m:row_number.fek4-ym6q=1

series e:fek4-ym6q d:2013-09-10T17:26:03.000Z t:telephone1=692-7364 t:unit="Kapolei Unit" t:fax=692-7379 t:room="Room 415" m:row_number.fek4-ym6q=2

series e:fek4-ym6q d:2013-09-10T17:31:20.000Z t:telephone1=327-4970 t:unit="West Hawaii Section" t:fax=327-4975 t:room="Suite 3004" m:row_number.fek4-ym6q=3
```

## Meta Commands

```ls
metric m:row_number.fek4-ym6q p:long l:"Row Number"

entity e:fek4-ym6q l:"Med-QUEST Offices" t:attribution=DHS t:url=https://data.hawaii.gov/api/views/fek4-ym6q

property e:fek4-ym6q t:meta.view v:id=fek4-ym6q v:averageRating=0 v:name="Med-QUEST Offices" v:attribution=DHS

property e:fek4-ym6q t:meta.view.owner v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:displayName="Open Data Portal Administrator"

property e:fek4-ym6q t:meta.view.tableauthor v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"
```

## Top Records

```ls
| :updated_at | unit                | room       | telephone1 | telephone2 | fax      | 
| =========== | =================== | ========== | ========== | ========== | ======== | 
| 1378833555  | Oahu Section        | 3rd Floor  | 587-3521   | 587-3540   | 587-3543 | 
| 1378833963  | Kapolei Unit        | Room 415   | 692-7364   |            | 692-7379 | 
| 1378834280  | West Hawaii Section | Suite 3004 | 327-4970   |            | 327-4975 | 
| 1378834370  | Lanai Unit          |            | 565-7102   |            | 565-6460 | 
| 1378834458  | Maui Section        | Suite 101  | 243-5780   |            | 243-5788 | 
| 1378834458  | Molokai Unit        | Room 110   | 553-1758   |            | 553-3833 | 
| 1378834499  | Kauai Unit          | Suite A    | 241-3575   |            | 241-3583 | 
| 1441968695  | East Hawaii Section |            | 933-0339   |            | 933-0344 | 
```