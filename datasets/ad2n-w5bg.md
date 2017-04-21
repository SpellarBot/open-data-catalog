# Marriage licenses, first Thursday in December

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/marriage-licenses-first-thursday-in-december-3af03) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/ad2n-w5bg) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/ad2n-w5bg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/ad2n-w5bg/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | ad2n-w5bg |
| Name | Marriage licenses, first Thursday in December |
| Attribution | King County Executive |
| Category | Operations |
| Tags | marriage |
| Created | 2012-12-09T02:40:47Z |
| Publication Date | 2012-12-09T02:43:13Z |

## Description

Numbers for marriage licenses issued on the first Thursday in December, 2009-2012

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| No       |                | date            | Date            | text      | text        |
| Yes      | numeric metric | licenses_issued | Licenses issued | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date
```

## Data Commands

```ls
series e:ad2n-w5bg d:2012-12-08T18:42:14.000Z m:licenses_issued=43

series e:ad2n-w5bg d:2012-12-08T18:42:31.000Z m:licenses_issued=39

series e:ad2n-w5bg d:2012-12-08T18:42:44.000Z m:licenses_issued=29
```

## Meta Commands

```ls
metric m:licenses_issued p:integer l:"Licenses issued" d:"Number of marriage licenses issued" t:dataTypeName=number

entity e:ad2n-w5bg l:"Marriage licenses, first Thursday in December" t:attribution="King County Executive" t:url=https://data.kingcounty.gov/api/views/ad2n-w5bg

property e:ad2n-w5bg t:meta.view v:id=ad2n-w5bg v:category=Operations v:attributionLink=http://www.kingcounty.gov/exec v:averageRating=0 v:name="Marriage licenses, first Thursday in December" v:attribution="King County Executive"

property e:ad2n-w5bg t:meta.view.license v:name="Public Domain"

property e:ad2n-w5bg t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:ad2n-w5bg t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| :updated_at | date         | licenses_issued | 
| =========== | ============ | =============== | 
| 1354992134  | Dec. 3, 2009 | 43              | 
| 1354992151  | Dec. 2, 2010 | 39              | 
| 1354992164  | Dec. 1, 2011 | 29              | 
| 1354992179  | Dec. 6, 2012 | 489             | 
```