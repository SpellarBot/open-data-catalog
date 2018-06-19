# Department Codes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-codes-57967) |
| Metadata | [Link](https://data.illinois.gov/api/views/wyic-g7r7) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/wyic-g7r7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/wyic-g7r7/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | wyic-g7r7 |
| Name | Department Codes |
| Category | Municipality |
| Created | 2013-03-21T16:07:45Z |
| Publication Date | 2013-03-21T16:09:20Z |

## Description

City of Rockford Finance Department Codes

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | seg_no      | Seg No      | text      | number      |
| Yes      | series tag  | seg_desc    | Seg Desc    | text      | text        |
| Yes      | series tag  | code        | Code        | text      | number      |
| Yes      | series tag  | description | Description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wyic-g7r7 d:2013-03-21T09:07:46.000Z t:description="NO DEPARTMENT" t:seg_no=3 t:seg_desc=Department t:code=0 m:row_number.wyic-g7r7=1

series e:wyic-g7r7 d:2013-03-21T09:07:46.000Z t:description="NO DEPARTMENT" t:seg_no=3 t:seg_desc=Department t:code=0 m:row_number.wyic-g7r7=2

series e:wyic-g7r7 d:2013-03-21T09:07:46.000Z t:description="MAYOR'S OFFICE" t:seg_no=3 t:seg_desc=Department t:code=11 m:row_number.wyic-g7r7=3
```

## Meta Commands

```ls
metric m:row_number.wyic-g7r7 p:long l:"Row Number"

entity e:wyic-g7r7 l:"Department Codes" t:url=https://data.illinois.gov/api/views/wyic-g7r7

property e:wyic-g7r7 t:meta.view v:id=wyic-g7r7 v:category=Municipality v:averageRating=0 v:name="Department Codes"

property e:wyic-g7r7 t:meta.view.owner v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:displayName=Glenn

property e:wyic-g7r7 t:meta.view.tableauthor v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:roleName=publisher v:displayName=Glenn
```

## Top Records

```ls
| :updated_at | seg_no | seg_desc   | code | description         | 
| =========== | ====== | ========== | ==== | =================== | 
| 1363856866  | 3      | Department | 0    | NO DEPARTMENT       | 
| 1363856866  | 3      | Department | 0    | NO DEPARTMENT       | 
| 1363856866  | 3      | Department | 11   | MAYOR'S OFFICE      | 
| 1363856866  | 3      | Department | 12   | CITY COUNCIL        | 
| 1363856866  | 3      | Department | 15   | LEGAL DEPARTMENT    | 
| 1363856866  | 3      | Department | 17   | FINANCE DEPARTMENT  | 
| 1363856866  | 3      | Department | 18   | INFORMATION SYSTEMS | 
| 1363856866  | 3      | Department | 19   | WIB                 | 
| 1363856866  | 3      | Department | 21   | POLICE DEPARTMENT   | 
| 1363856866  | 3      | Department | 22   | FIRE DEPARTMENT     | 
```