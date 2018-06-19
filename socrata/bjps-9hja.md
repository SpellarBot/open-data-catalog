# Municipality Connection Status To The Nutmeg Network

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/municipality-connection-status-to-the-nutmeg-network) |
| Metadata | [Link](https://data.ct.gov/api/views/bjps-9hja) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/bjps-9hja/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/bjps-9hja/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | bjps-9hja |
| Name | Municipality Connection Status To The Nutmeg Network |
| Category | Government |
| Tags | btop, mrra, cen, psdn, fiber |
| Created | 2014-03-10T12:09:03Z |
| Publication Date | 2014-03-10T12:09:51Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | town        | Town       | text      | text        |
| Yes      | series tag  | status      | Status     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:bjps-9hja d:2014-03-10T05:09:14.000Z t:status="CEN in process" t:town="West Hartford" m:row_number.bjps-9hja=1

series e:bjps-9hja d:2014-03-10T05:09:14.000Z t:status="No news" t:town=Bozrah m:row_number.bjps-9hja=2

series e:bjps-9hja d:2014-03-10T05:09:14.000Z t:status="CEN in process" t:town=Putnam m:row_number.bjps-9hja=3
```

## Meta Commands

```ls
metric m:row_number.bjps-9hja p:long l:"Row Number"

entity e:bjps-9hja l:"Municipality Connection Status To The Nutmeg Network" t:url=https://data.ct.gov/api/views/bjps-9hja

property e:bjps-9hja t:meta.view v:id=bjps-9hja v:category=Government v:averageRating=0 v:name="Municipality Connection Status To The Nutmeg Network"

property e:bjps-9hja t:meta.view.license v:name="Public Domain"

property e:bjps-9hja t:meta.view.owner v:id=cttg-mwt7 v:profileImageUrlMedium=/api/users/cttg-mwt7/profile_images/THUMB v:profileImageUrlLarge=/api/users/cttg-mwt7/profile_images/LARGE v:screenName="John Vittner" v:profileImageUrlSmall=/api/users/cttg-mwt7/profile_images/TINY v:displayName="John Vittner"

property e:bjps-9hja t:meta.view.tableauthor v:id=cttg-mwt7 v:profileImageUrlMedium=/api/users/cttg-mwt7/profile_images/THUMB v:profileImageUrlLarge=/api/users/cttg-mwt7/profile_images/LARGE v:screenName="John Vittner" v:profileImageUrlSmall=/api/users/cttg-mwt7/profile_images/TINY v:roleName=publisher v:displayName="John Vittner"
```

## Top Records

```ls
| :updated_at | town          | status          | 
| =========== | ============= | =============== | 
| 1394428154  | West Hartford | CEN in process  | 
| 1394428154  | Bozrah        | No news         | 
| 1394428154  | Putnam        | CEN in process  | 
| 1394428154  | Woodbridge    | CEN in process  | 
| 1394428154  | Ledyard       | Deferred        | 
| 1394428154  | Groton        | CEN in process  | 
| 1394428154  | Windham       | CEN in process  | 
| 1394428154  | New Britain   | PSDN in process | 
| 1394428154  | Brooklyn      | No news         | 
| 1394428154  | Simsbury      | PSDN in process | 
```