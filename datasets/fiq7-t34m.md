# Package Store Permit Availability

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/package-store-permit-availability) |
| Metadata | [Link](https://data.ct.gov/api/views/fiq7-t34m) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/fiq7-t34m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/fiq7-t34m/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | fiq7-t34m |
| Name | Package Store Permit Availability |
| Attribution | Department of Consumer Protection |
| Category | Business |
| Tags | package store |
| Created | 2016-03-07T18:16:26Z |
| Publication Date | 2016-06-21T17:46:20Z |

## Description

Package Store Permit Availability by town. Updated nightly.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | town               | town               | text      | text        |
| Yes      | numeric metric | max_stores_allowed | max-stores-allowed | number    | number      |
| Yes      | series tag     | stores_available   | stores-available   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fiq7-t34m d:2017-04-12T11:10:03.000Z t:stores_available=1 t:town=AVON m:max_stores_allowed=7

series e:fiq7-t34m d:2017-04-12T11:10:03.000Z t:stores_available="None Available" t:town=CANAAN m:max_stores_allowed=0

series e:fiq7-t34m d:2017-04-12T11:10:03.000Z t:stores_available="None Available" t:town=CHESTER m:max_stores_allowed=1
```

## Meta Commands

```ls
metric m:max_stores_allowed p:integer l:max-stores-allowed t:dataTypeName=number

entity e:fiq7-t34m l:"Package Store Permit Availability" t:attribution="Department of Consumer Protection" t:url=https://data.ct.gov/api/views/fiq7-t34m

property e:fiq7-t34m t:meta.view v:id=fiq7-t34m v:category=Business v:averageRating=0 v:name="Package Store Permit Availability" v:attribution="Department of Consumer Protection"

property e:fiq7-t34m t:meta.view.license v:name="Public Domain"

property e:fiq7-t34m t:meta.view.owner v:id=ksrh-ut6b v:screenName="Open Data Hub" v:displayName="Open Data Hub"

property e:fiq7-t34m t:meta.view.tableauthor v:id=ksrh-ut6b v:screenName="Open Data Hub" v:roleName=publisher v:displayName="Open Data Hub"
```

## Top Records

```ls
| :updated_at | town        | max_stores_allowed | stores_available | 
| =========== | =========== | ================== | ================ | 
| 1491995403  | AVON        | 7                  | 1                | 
| 1491995403  | CANAAN      | 0                  | None Available   | 
| 1491995403  | CHESTER     | 1                  | None Available   | 
| 1491995403  | HEBRON      | 3                  | None Available   | 
| 1491995403  | KENT        | 1                  | None Available   | 
| 1491995403  | MANCHESTER  | 23                 | None Available   | 
| 1491995403  | MERIDEN     | 24                 | 1                | 
| 1491995403  | NORTH HAVEN | 9                  | None Available   | 
| 1491995403  | NORWALK     | 34                 | 2                | 
| 1491995403  | SALEM       | 1                  | None Available   | 
```