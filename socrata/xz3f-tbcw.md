# Comment Test

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/comment-test) |
| Metadata | [Link](https://data.oregon.gov/api/views/xz3f-tbcw) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/xz3f-tbcw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/xz3f-tbcw/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | xz3f-tbcw |
| Name | Comment Test |
| Created | 2016-05-04T15:45:59Z |
| Publication Date | 2016-05-04T17:59:11Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | Name       | text      | text        |
| Yes      | series tag  | comment     | Comment    | html      | html        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xz3f-tbcw d:2016-05-04T09:16:43.000Z t:name=yrdy t:comment=sdfgd m:row_number.xz3f-tbcw=1

series e:xz3f-tbcw d:2016-05-04T09:50:06.000Z t:name=2222 t:comment=sdgsdfgsdfg m:row_number.xz3f-tbcw=2

series e:xz3f-tbcw d:2016-05-04T09:56:18.000Z t:name=1111 t:comment=111aaaaa m:row_number.xz3f-tbcw=3
```

## Meta Commands

```ls
metric m:row_number.xz3f-tbcw p:long l:"Row Number"

entity e:xz3f-tbcw l:"Comment Test" t:url=https://data.oregon.gov/api/views/xz3f-tbcw

property e:xz3f-tbcw t:meta.view v:id=xz3f-tbcw v:averageRating=0 v:name="Comment Test"

property e:xz3f-tbcw t:meta.view.owner v:id=ynpd-i4b5 v:screenName="Jesse Toews" v:displayName="Jesse Toews"

property e:xz3f-tbcw t:meta.view.tableauthor v:id=ynpd-i4b5 v:screenName="Jesse Toews" v:roleName=editor v:displayName="Jesse Toews"
```

## Top Records

```ls
| :updated_at | name | comment     | 
| =========== | ==== | =========== | 
| 1462353403  | yrdy | sdfgd       | 
| 1462355406  | 2222 | sdgsdfgsdfg | 
| 1462355778  | 1111 | 111aaaaa    | 
| 1462355883  | 222  | 222bbb      | 
| 1462356507  | 333  | 333ccc      | 
| 1462358651  | 444  | 444ddd      | 
```