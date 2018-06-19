# L.A. Zoo Attendance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/l-a-zoo-attendance-46503) |
| Metadata | [Link](https://data.lacity.org/api/views/3gwn-arjr) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/3gwn-arjr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/3gwn-arjr/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 3gwn-arjr |
| Name | L.A. Zoo Attendance |
| Category | A Livable and Sustainable City |
| Tags | zoo, attendance, recreation, attraction, park, animals, visitor, school, camp, membership, ticket |
| Created | 2014-05-30T16:53:22Z |
| Publication Date | 2014-05-30T20:48:35Z |

## Description

L.A. Zoo attendance for the last 5 years.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | fiscal_year | Fiscal Year | text      | text        |
| Yes      | numeric metric | attendance  | Attendance  | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy-MM
```

## Data Commands

```ls
series e:3gwn-arjr d:2013-01-01T00:00:00.000Z m:attendance=1506274

series e:3gwn-arjr d:2011-12-01T00:00:00.000Z m:attendance=1660450

series e:3gwn-arjr d:2010-11-01T00:00:00.000Z m:attendance=1543232
```

## Meta Commands

```ls
metric m:attendance p:integer l:Attendance t:dataTypeName=number

entity e:3gwn-arjr l:"L.A. Zoo Attendance" t:url=https://data.lacity.org/api/views/3gwn-arjr

property e:3gwn-arjr t:meta.view v:id=3gwn-arjr v:category="A Livable and Sustainable City" v:averageRating=0 v:name="L.A. Zoo Attendance"

property e:3gwn-arjr t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:3gwn-arjr t:meta.view.owner v:id=uypn-9feh v:profileImageUrlMedium=/api/users/uypn-9feh/profile_images/THUMB v:profileImageUrlLarge=/api/users/uypn-9feh/profile_images/LARGE v:screenName="LA Zoo OpenData" v:profileImageUrlSmall=/api/users/uypn-9feh/profile_images/TINY v:displayName="LA Zoo OpenData"

property e:3gwn-arjr t:meta.view.tableauthor v:id=uypn-9feh v:profileImageUrlMedium=/api/users/uypn-9feh/profile_images/THUMB v:profileImageUrlLarge=/api/users/uypn-9feh/profile_images/LARGE v:screenName="LA Zoo OpenData" v:profileImageUrlSmall=/api/users/uypn-9feh/profile_images/TINY v:roleName=editor v:displayName="LA Zoo OpenData"
```

## Top Records

```ls
| fiscal_year | attendance | 
| =========== | ========== | 
| 2012-13     | 1506274    | 
| 2011-12     | 1660450    | 
| 2010-11     | 1543232    | 
| 2009-10     | 1459080    | 
| 2008-09     | 1556162    | 
```