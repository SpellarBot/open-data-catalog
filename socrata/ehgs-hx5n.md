# CSC Seattle

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/csc-seattle-f5e57) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/ehgs-hx5n) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/ehgs-hx5n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/ehgs-hx5n/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | ehgs-hx5n |
| Name | CSC Seattle |
| Created | 2014-10-28T17:30:42Z |
| Publication Date | 2014-10-28T17:33:08Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | Name       | text      | text        |
| Yes      | series tag  | hours       | Hours      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ehgs-hx5n d:2014-10-28T10:33:02.000Z t:hours="Monday-Friday, 8:30am-4:30pm" t:name="King County Administration Building" m:row_number.ehgs-hx5n=1
```

## Meta Commands

```ls
metric m:row_number.ehgs-hx5n p:long l:"Row Number"

entity e:ehgs-hx5n l:"CSC Seattle" t:url=https://data.kingcounty.gov/api/views/ehgs-hx5n

property e:ehgs-hx5n t:meta.view v:id=ehgs-hx5n v:attributionLink=http://www.kingcounty.gov/csc v:averageRating=0 v:name="CSC Seattle"

property e:ehgs-hx5n t:meta.view.license v:name="Public Domain"

property e:ehgs-hx5n t:meta.view.owner v:id=ph9f-eu4i v:screenName=Cameron v:displayName=Cameron

property e:ehgs-hx5n t:meta.view.tableauthor v:id=ph9f-eu4i v:screenName=Cameron v:roleName=publisher v:displayName=Cameron
```

## Top Records

```ls
| :updated_at | name                                | hours                        | 
| =========== | =================================== | ============================ | 
| 1414492382  | King County Administration Building | Monday-Friday, 8:30am-4:30pm | 
```