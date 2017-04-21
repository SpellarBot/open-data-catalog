# El Pueblo Tours

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/el-pueblo-tours) |
| Metadata | [Link](https://data.lacity.org/api/views/diev-46hg) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/diev-46hg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/diev-46hg/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | diev-46hg |
| Name | El Pueblo Tours |
| Attribution | El Pueblo Historical Monument |
| Category | A Livable and Sustainable City |
| Tags | tours |
| Created | 2014-05-29T21:15:24Z |
| Publication Date | 2017-03-20T22:49:24Z |

## Description

The number of tours provided by the Angelitas del Pueblo of the historic monument.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | time           | month          | Month          | calendar_date | calendar_date |
| Yes      | numeric metric | tours_provided | Tours Provided | number        | number        |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:diev-46hg d:2014-01-01T00:00:00.000Z m:tours_provided=754

series e:diev-46hg d:2014-02-01T00:00:00.000Z m:tours_provided=856

series e:diev-46hg d:2014-03-01T00:00:00.000Z m:tours_provided=928
```

## Meta Commands

```ls
metric m:tours_provided p:integer l:"Tours Provided" t:dataTypeName=number

entity e:diev-46hg l:"El Pueblo Tours" t:attribution="El Pueblo Historical Monument" t:url=https://data.lacity.org/api/views/diev-46hg

property e:diev-46hg t:meta.view v:id=diev-46hg v:category="A Livable and Sustainable City" v:attributionLink=http://elpueblo.lacity.org/index.htm v:averageRating=0 v:name="El Pueblo Tours" v:attribution="El Pueblo Historical Monument"

property e:diev-46hg t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:diev-46hg t:meta.view.owner v:id=rz8e-rup2 v:profileImageUrlMedium=/api/users/rz8e-rup2/profile_images/THUMB v:profileImageUrlLarge=/api/users/rz8e-rup2/profile_images/LARGE v:screenName="El Pueblo OpenData" v:profileImageUrlSmall=/api/users/rz8e-rup2/profile_images/TINY v:displayName="El Pueblo OpenData"

property e:diev-46hg t:meta.view.tableauthor v:id=rz8e-rup2 v:profileImageUrlMedium=/api/users/rz8e-rup2/profile_images/THUMB v:profileImageUrlLarge=/api/users/rz8e-rup2/profile_images/LARGE v:screenName="El Pueblo OpenData" v:profileImageUrlSmall=/api/users/rz8e-rup2/profile_images/TINY v:roleName=publisher v:displayName="El Pueblo OpenData"
```

## Top Records

```ls
| month               | tours_provided | 
| =================== | ============== | 
| 2014-01-01T00:00:00 | 754            | 
| 2014-02-01T00:00:00 | 856            | 
| 2014-03-01T00:00:00 | 928            | 
| 2014-04-01T00:00:00 | 982            | 
| 2014-05-01T00:00:00 | 2129           | 
| 2014-06-01T00:00:00 | 1181           | 
| 2014-07-01T00:00:00 | 1185           | 
| 2014-08-01T00:00:00 | 557            | 
| 2014-09-01T00:00:00 | 338            | 
| 2014-10-01T00:00:00 | 1259           | 
```