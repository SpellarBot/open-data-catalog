# CSC Kent

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/csc-kent-ed461) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/bu7x-2xx6) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/bu7x-2xx6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/bu7x-2xx6/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | bu7x-2xx6 |
| Name | CSC Kent |
| Category | Operations |
| Created | 2011-12-16T19:47:30Z |
| Publication Date | 2011-12-16T20:07:06Z |

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
series e:bu7x-2xx6 d:2011-12-16T11:48:25.000Z t:hours="Mon-Fri: 9:30am-5pm" t:phone=206-205-7330 t:name="Maleng Regional Justice Center (Kent)" m:row_number.bu7x-2xx6=1
```

## Meta Commands

```ls
metric m:row_number.bu7x-2xx6 p:long l:"Row Number"

entity e:bu7x-2xx6 l:"CSC Kent" t:url=https://data.kingcounty.gov/api/views/bu7x-2xx6

property e:bu7x-2xx6 t:meta.view d:2017-09-25T07:23:53.440Z v:averageRating=0 v:name="CSC Kent" v:id=bu7x-2xx6 v:category=Operations

property e:bu7x-2xx6 t:meta.view.license d:2017-09-25T07:23:53.440Z v:name="Public Domain"

property e:bu7x-2xx6 t:meta.view.owner d:2017-09-25T07:23:53.440Z v:displayName=Cameron v:id=ph9f-eu4i v:screenName=Cameron

property e:bu7x-2xx6 t:meta.view.tableauthor d:2017-09-25T07:23:53.440Z v:displayName=Cameron v:roleName=publisher v:id=ph9f-eu4i v:screenName=Cameron
```

## Top Records

```ls
| :updated_at | name                                  | phone        | hours               | 
| =========== | ===================================== | ============ | =================== | 
| 1324036105  | Maleng Regional Justice Center (Kent) | 206-205-7330 | Mon-Fri: 9:30am-5pm | 
```