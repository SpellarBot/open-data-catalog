# Snake Stream Miles Opened

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/snake-stream-miles-opened-bdc2a) |
| Metadata | [Link](https://data.wa.gov/api/views/uz8j-59zc) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/uz8j-59zc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/uz8j-59zc/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | uz8j-59zc |
| Name | Snake Stream Miles Opened |
| Created | 2012-12-05T07:17:44Z |
| Publication Date | 2012-12-07T12:38:32Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name         | Data Type | Render Type |
| ======== | =========== | =========== | ============ | ========= | =========== |
| No       | time        | :updated_at | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | region      | Region       | text      | text        |
| No       |             | _1          | Year         | number    | text        |
| No       |             | _2          | Miles Opened | number    | number      |
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
series e:uz8j-59zc d:2012-12-07T04:37:59.000Z t:region=Snake m:row_number.uz8j-59zc=1

series e:uz8j-59zc d:2012-12-07T04:37:59.000Z t:region=Snake m:row_number.uz8j-59zc=2

series e:uz8j-59zc d:2012-12-07T04:37:59.000Z t:region=Snake m:row_number.uz8j-59zc=3
```

## Meta Commands

```ls
metric m:row_number.uz8j-59zc p:long l:"Row Number"

entity e:uz8j-59zc l:"Snake Stream Miles Opened" t:url=https://data.wa.gov/api/views/uz8j-59zc

property e:uz8j-59zc t:meta.view d:2017-09-25T07:27:33.069Z v:averageRating=0 v:name="Snake Stream Miles Opened" v:id=uz8j-59zc

property e:uz8j-59zc t:meta.view.owner d:2017-09-25T07:27:33.069Z v:displayName="Jennifer Johnson" v:profileImageUrlLarge=/api/users/fuyk-waw8/profile_images/LARGE v:profileImageUrlSmall=/api/users/fuyk-waw8/profile_images/TINY v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:profileImageUrlMedium=/api/users/fuyk-waw8/profile_images/THUMB

property e:uz8j-59zc t:meta.view.tableauthor d:2017-09-25T07:27:33.069Z v:displayName="Jennifer Johnson" v:profileImageUrlLarge=/api/users/fuyk-waw8/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/fuyk-waw8/profile_images/TINY v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:profileImageUrlMedium=/api/users/fuyk-waw8/profile_images/THUMB
```

## Top Records

```ls
| :updated_at | region | _1   | _2 | 
| =========== | ====== | ==== | == | 
| 1354855079  | Snake  | 2005 | 37 | 
| 1354855079  | Snake  | 2006 | 70 | 
| 1354855079  | Snake  | 2007 | 23 | 
| 1354855079  | Snake  | 2008 | 69 | 
| 1354855079  | Snake  | 2009 | 3  | 
| 1354855079  | Snake  | 2010 | 4  | 
| 1354855079  | Snake  | 2011 | 23 | 
| 1354855079  | Snake  | 2012 | 0  | 
```