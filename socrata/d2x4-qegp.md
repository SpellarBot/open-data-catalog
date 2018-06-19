# King County Community Service Center Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-community-service-center-locations-cf20a) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/d2x4-qegp) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/d2x4-qegp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/d2x4-qegp/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | d2x4-qegp |
| Name | King County Community Service Center Locations |
| Category | Operations |
| Tags | king, county, community, service, center, csc |
| Created | 2011-12-12T21:53:05Z |
| Publication Date | 2014-03-14T18:45:23Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | Name       | text      | text        |
| Yes      | series tag  | phone       | Phone      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:d2x4-qegp d:2011-12-12T15:28:52.000Z t:phone=206-205-7330 t:name="Maleng Regional Justice Center (Kent)" m:row_number.d2x4-qegp=1

series e:d2x4-qegp d:2011-12-12T15:28:54.000Z t:phone=206-296-9840 t:name="Northshore (Bothell)" m:row_number.d2x4-qegp=2

series e:d2x4-qegp d:2011-12-16T11:24:04.000Z t:phone=206-296-7810 t:name="Black River (Renton)" m:row_number.d2x4-qegp=3
```

## Meta Commands

```ls
metric m:row_number.d2x4-qegp p:long l:"Row Number"

entity e:d2x4-qegp l:"King County Community Service Center Locations" t:url=https://data.kingcounty.gov/api/views/d2x4-qegp

property e:d2x4-qegp t:meta.view v:id=d2x4-qegp v:category=Operations v:averageRating=0 v:name="King County Community Service Center Locations"

property e:d2x4-qegp t:meta.view.license v:name="Public Domain"

property e:d2x4-qegp t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:d2x4-qegp t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| :updated_at | name                                  | phone        | 
| =========== | ===================================== | ============ | 
| 1323703732  | Maleng Regional Justice Center (Kent) | 206-205-7330 | 
| 1323703734  | Northshore (Bothell)                  | 206-296-9840 | 
| 1324034644  | Black River (Renton)                  | 206-296-7810 | 
| 1368722302  | Shoreline                             |              | 
| 1368722394  | Issaquah                              |              | 
| 1372350769  |                                       |              | 
| 1393320514  | Vashon                                | 206-296-4510 | 
| 1394797512  | King County Administration Building   |              | 
```