# CSC Vashon

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/csc-vashon-97f54) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/yc2w-rs5z) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/yc2w-rs5z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/yc2w-rs5z/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | yc2w-rs5z |
| Name | CSC Vashon |
| Category | Operations |
| Created | 2011-12-16T20:18:36Z |
| Publication Date | 2014-02-25T17:07:45Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | Name       | text      | text        |
| Yes      | series tag  | phone       | Phone      | text      | text        |
| Yes      | series tag  | hours       | Hours      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:yc2w-rs5z d:2014-02-25T09:07:40.000Z t:phone=206-296-4510 t:hours="Tue: noon-7pm" t:name=Vashon m:row_number.yc2w-rs5z=1
```

## Meta Commands

```ls
metric m:row_number.yc2w-rs5z p:long l:"Row Number"

entity e:yc2w-rs5z l:"CSC Vashon" t:url=https://data.kingcounty.gov/api/views/yc2w-rs5z

property e:yc2w-rs5z t:meta.view v:id=yc2w-rs5z v:category=Operations v:averageRating=0 v:name="CSC Vashon"

property e:yc2w-rs5z t:meta.view.license v:name="Public Domain"

property e:yc2w-rs5z t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:yc2w-rs5z t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| :updated_at | name   | phone        | hours         | 
| =========== | ====== | ============ | ============= | 
| 1393319260  | Vashon | 206-296-4510 | Tue: noon-7pm | 
```