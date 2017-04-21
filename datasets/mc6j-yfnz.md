# CSC Issaquah

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/csc-issaquah-6ebc0) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/mc6j-yfnz) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/mc6j-yfnz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/mc6j-yfnz/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | mc6j-yfnz |
| Name | CSC Issaquah |
| Category | Operations |
| Created | 2013-05-16T22:57:57Z |
| Publication Date | 2013-05-16T22:58:14Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | Name       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mc6j-yfnz d:2013-05-16T15:57:59.000Z t:name=Issaquah m:row_number.mc6j-yfnz=1
```

## Meta Commands

```ls
metric m:row_number.mc6j-yfnz p:long l:"Row Number"

entity e:mc6j-yfnz l:"CSC Issaquah" t:url=https://data.kingcounty.gov/api/views/mc6j-yfnz

property e:mc6j-yfnz t:meta.view v:id=mc6j-yfnz v:category=Operations v:averageRating=0 v:name="CSC Issaquah"

property e:mc6j-yfnz t:meta.view.license v:name="Public Domain"

property e:mc6j-yfnz t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:mc6j-yfnz t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| :updated_at | name     | 
| =========== | ======== | 
| 1368719879  | Issaquah | 
```