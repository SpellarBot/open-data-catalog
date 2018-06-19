# Snake Barriers Removed

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/snake-barriers-removed-37692) |
| Metadata | [Link](https://data.wa.gov/api/views/m3jx-45hn) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/m3jx-45hn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/m3jx-45hn/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | m3jx-45hn |
| Name | Snake Barriers Removed |
| Created | 2012-12-05T07:19:34Z |
| Publication Date | 2012-12-07T12:42:18Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name             | Data Type | Render Type |
| ======== | =========== | =========== | ================ | ========= | =========== |
| No       | time        | :updated_at | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | region      | Region           | text      | text        |
| No       |             | _1          | Year             | number    | text        |
| No       |             | _2          | Barriers Removed | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = _1,_2
```

## Data Commands

```ls
series e:m3jx-45hn d:2012-12-07T04:41:46.000Z t:region=Snake m:row_number.m3jx-45hn=1

series e:m3jx-45hn d:2012-12-07T04:41:46.000Z t:region=Snake m:row_number.m3jx-45hn=2

series e:m3jx-45hn d:2012-12-07T04:41:46.000Z t:region=Snake m:row_number.m3jx-45hn=3
```

## Meta Commands

```ls
metric m:row_number.m3jx-45hn p:long l:"Row Number"

entity e:m3jx-45hn l:"Snake Barriers Removed" t:url=https://data.wa.gov/api/views/m3jx-45hn

property e:m3jx-45hn t:meta.view v:id=m3jx-45hn v:averageRating=0 v:name="Snake Barriers Removed"

property e:m3jx-45hn t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:m3jx-45hn t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| :updated_at | region | _1   | _2 | 
| =========== | ====== | ==== | == | 
| 1354855306  | Snake  | 2005 | 6  | 
| 1354855306  | Snake  | 2006 | 3  | 
| 1354855306  | Snake  | 2007 | 4  | 
| 1354855306  | Snake  | 2008 | 10 | 
| 1354855306  | Snake  | 2009 | 1  | 
| 1354855306  | Snake  | 2010 | 9  | 
| 1354855306  | Snake  | 2011 | 3  | 
| 1354855306  | Snake  | 2012 | 0  | 
```