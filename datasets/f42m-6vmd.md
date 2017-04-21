# Fund Codes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fund-codes-924fc) |
| Metadata | [Link](https://data.illinois.gov/api/views/f42m-6vmd) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/f42m-6vmd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/f42m-6vmd/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | f42m-6vmd |
| Name | Fund Codes |
| Category | Municipality |
| Created | 2013-03-21T16:09:44Z |
| Publication Date | 2013-03-21T16:11:49Z |

## Description

City of Rockford Finance Fund Codes

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | numeric metric | fund        | Fund        | number    | number      |
| Yes      | series tag     | description | Description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:f42m-6vmd d:2013-03-21T09:09:46.000Z t:description="GENERAL FUND" m:fund=1010

series e:f42m-6vmd d:2013-03-21T09:09:46.000Z t:description=TOURISM m:fund=1040

series e:f42m-6vmd d:2013-03-21T09:09:46.000Z t:description="LIBR-LSTA LATINO OUTREACH PROG" m:fund=1100
```

## Meta Commands

```ls
metric m:fund p:integer l:Fund t:dataTypeName=number

entity e:f42m-6vmd l:"Fund Codes" t:url=https://data.illinois.gov/api/views/f42m-6vmd

property e:f42m-6vmd t:meta.view v:id=f42m-6vmd v:category=Municipality v:averageRating=0 v:name="Fund Codes"

property e:f42m-6vmd t:meta.view.owner v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:displayName=Glenn

property e:f42m-6vmd t:meta.view.tableauthor v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:roleName=publisher v:displayName=Glenn
```

## Top Records

```ls
| :updated_at | fund | description                    | 
| =========== | ==== | ============================== | 
| 1363856986  | 1010 | GENERAL FUND                   | 
| 1363856986  | 1040 | TOURISM                        | 
| 1363856986  | 1100 | LIBR-LSTA LATINO OUTREACH PROG | 
| 1363856986  | 1110 | PUBLIC LIBRARY                 | 
| 1363856986  | 1120 | TB CARE CENTER                 | 
| 1363856986  | 1130 | MOTOR FUEL TAX                 | 
| 1363856986  | 1140 | PUBLIC BENEFIT                 | 
| 1363856986  | 1150 | GARBAGE AND REFUSE             | 
| 1363856986  | 1160 | REFUSE RESEARCH                | 
| 1363856986  | 1170 | LIBR-LSTA UNITING SHARED HIST  | 
```