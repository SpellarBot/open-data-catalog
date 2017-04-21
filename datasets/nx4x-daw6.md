# Foreclosure parcels

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/trf140-12-13-16) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/nx4x-daw6) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/nx4x-daw6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/nx4x-daw6/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | nx4x-daw6 |
| Name | Foreclosure parcels |
| Attribution | kingcountytreasurer@kingcounty.gov |
| Category | Property |
| Created | 2016-12-13T23:35:00Z |
| Publication Date | 2017-03-31T22:51:23Z |

## Description

Parcels currently in foreclosure status with King County.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | parcels     | Parcels    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nx4x-daw6 d:2017-03-31T22:50:56.000Z t:parcels=0011000038 m:row_number.nx4x-daw6=1

series e:nx4x-daw6 d:2017-03-31T22:50:56.000Z t:parcels=0119069015 m:row_number.nx4x-daw6=2

series e:nx4x-daw6 d:2017-03-31T22:50:56.000Z t:parcels=0122029006 m:row_number.nx4x-daw6=3
```

## Meta Commands

```ls
metric m:row_number.nx4x-daw6 p:long l:"Row Number"

entity e:nx4x-daw6 l:"Foreclosure parcels" t:attribution=kingcountytreasurer@kingcounty.gov t:url=https://data.kingcounty.gov/api/views/nx4x-daw6

property e:nx4x-daw6 t:meta.view v:id=nx4x-daw6 v:category=Property v:attributionLink=http://www.kingcounty.gov/depts/finance-business-operations/treasury/foreclosure/current-foreclosure-action/foreclosure-properties.aspx v:averageRating=0 v:name="Foreclosure parcels" v:attribution=kingcountytreasurer@kingcounty.gov

property e:nx4x-daw6 t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:nx4x-daw6 t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| :updated_at | parcels    | 
| =========== | ========== | 
| 1491000656  | 0011000038 | 
| 1491000656  | 0119069015 | 
| 1491000656  | 0122029006 | 
| 1491000656  | 0123039325 | 
| 1491000656  | 0125079012 | 
| 1491000656  | 0156000520 | 
| 1491000656  | 0156000550 | 
| 1491000656  | 0221029074 | 
| 1491000656  | 0221059009 | 
| 1491000656  | 0222069133 | 
```