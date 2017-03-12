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
| Rows Updated | 2011-12-16T19:48:25Z |

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
```

## Meta Commands

```ls
entity e:bu7x-2xx6 l:"CSC Kent" t:url=https://data.kingcounty.gov/api/views/bu7x-2xx6

property e:bu7x-2xx6 t:meta.view v:id=bu7x-2xx6 v:category=Operations v:averageRating=0 v:name="CSC Kent"

property e:bu7x-2xx6 t:meta.view.license v:name="Public Domain"

property e:bu7x-2xx6 t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron

property e:bu7x-2xx6 t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```