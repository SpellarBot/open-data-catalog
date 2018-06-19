# Total Bills Vs Estimated Bill at LADWP

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-bills-vs-estimated-bill-at-ladwp-7fdce) |
| Metadata | [Link](https://data.lacity.org/api/views/svt7-r3ww) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/svt7-r3ww/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/svt7-r3ww/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | svt7-r3ww |
| Name | Total Bills Vs Estimated Bill at LADWP |
| Attribution | LADWP |
| Category | A Well Run City |
| Tags | customer bills |
| Created | 2014-05-23T23:31:59Z |
| Publication Date | 2014-05-23T23:36:37Z |

## Description

Number of bills LADWP estimates versus total bills issued

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | month       | Month      | text      | text        |
| Yes      | numeric metric | sep_13      | Sep-13     | number    | number      |
| Yes      | numeric metric | oct_13      | Oct-13     | number    | number      |
| Yes      | numeric metric | nov_13      | Nov-13     | number    | number      |
| Yes      | numeric metric | dec_13      | Dec-13     | number    | number      |
| Yes      | numeric metric | jan_14      | Jan-14     | number    | number      |
| Yes      | numeric metric | feb_14      | Feb-14     | number    | number      |
| Yes      | numeric metric | mar_14      | Mar-14     | number    | number      |
| Yes      | numeric metric | apr_14      | Apr-14     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:svt7-r3ww d:2014-05-23T16:32:02.000Z t:month="No. of Estimated Bills" m:oct_13=188487 m:nov_13=160337 m:feb_14=125734 m:mar_14=83717 m:sep_13=137516 m:apr_14=65502 m:dec_13=221014 m:jan_14=184280

series e:svt7-r3ww d:2014-05-23T16:32:02.000Z t:month="Total Bills (including Est. Bills)" m:oct_13=969680 m:nov_13=750037 m:feb_14=820897 m:mar_14=856093 m:sep_13=896157 m:apr_14=936881 m:dec_13=858932 m:jan_14=914146

series e:svt7-r3ww d:2014-05-23T16:36:34.000Z t:month="Estimated Bill Percentage" m:oct_13=0.194 m:nov_13=0.213 m:feb_14=0.153 m:mar_14=0.097 m:sep_13=0.153 m:apr_14=0.069 m:dec_13=0.257 m:jan_14=0.201
```

## Meta Commands

```ls
metric m:sep_13 p:double l:Sep-13 t:dataTypeName=number

metric m:oct_13 p:double l:Oct-13 t:dataTypeName=number

metric m:nov_13 p:double l:Nov-13 t:dataTypeName=number

metric m:dec_13 p:double l:Dec-13 t:dataTypeName=number

metric m:jan_14 p:double l:Jan-14 t:dataTypeName=number

metric m:feb_14 p:double l:Feb-14 t:dataTypeName=number

metric m:mar_14 p:double l:Mar-14 t:dataTypeName=number

metric m:apr_14 p:double l:Apr-14 t:dataTypeName=number

entity e:svt7-r3ww l:"Total Bills Vs Estimated Bill at LADWP" t:attribution=LADWP t:url=https://data.lacity.org/api/views/svt7-r3ww

property e:svt7-r3ww t:meta.view v:id=svt7-r3ww v:category="A Well Run City" v:averageRating=0 v:name="Total Bills Vs Estimated Bill at LADWP" v:attribution=LADWP

property e:svt7-r3ww t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:svt7-r3ww t:meta.view.owner v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:displayName="LA DWP OpenData"

property e:svt7-r3ww t:meta.view.tableauthor v:id=7q7s-tyf3 v:screenName="Steve Baule" v:roleName=publisher v:displayName="Steve Baule"
```

## Top Records

```ls
| :updated_at | month                              | sep_13 | oct_13 | nov_13 | dec_13 | jan_14 | feb_14 | mar_14 | apr_14 | 
| =========== | ================================== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | 
| 1400862722  | No. of Estimated Bills             | 137516 | 188487 | 160337 | 221014 | 184280 | 125734 | 83717  | 65502  | 
| 1400862722  | Total Bills (including Est. Bills) | 896157 | 969680 | 750037 | 858932 | 914146 | 820897 | 856093 | 936881 | 
| 1400862994  | Estimated Bill Percentage          | 0.153  | 0.194  | 0.213  | 0.257  | 0.201  | 0.153  | 0.097  | 0.069  | 
```