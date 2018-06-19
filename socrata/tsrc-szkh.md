# ITA- Monthly Downloads My LA 311 App

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ita-monthly-downloads-my-la-311-app-8e18b) |
| Metadata | [Link](https://data.lacity.org/api/views/tsrc-szkh) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/tsrc-szkh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/tsrc-szkh/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | tsrc-szkh |
| Name | ITA- Monthly Downloads My LA 311 App |
| Created | 2014-05-30T22:22:47Z |
| Publication Date | 2014-05-30T22:24:06Z |

## Columns

```ls
| Included | Schema Type    | Field Name               | Name           | Data Type     | Render Type   |
| ======== | ============== | ======================== | ============== | ============= | ============= |
| Yes      | time           | date                     | Date           | calendar_date | calendar_date |
| No       |                | date_name                | Date Name      | text          | text          |
| Yes      | numeric metric | of_myla311_app_downloads | # of Downloads | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_name
```

## Data Commands

```ls
series e:tsrc-szkh d:2013-01-01T00:00:00.000Z m:of_myla311_app_downloads=0

series e:tsrc-szkh d:2013-02-01T00:00:00.000Z m:of_myla311_app_downloads=0

series e:tsrc-szkh d:2013-03-01T00:00:00.000Z m:of_myla311_app_downloads=898
```

## Meta Commands

```ls
metric m:of_myla311_app_downloads p:integer l:"# of Downloads" t:dataTypeName=number

entity e:tsrc-szkh l:"ITA- Monthly Downloads My LA 311 App" t:url=https://data.lacity.org/api/views/tsrc-szkh

property e:tsrc-szkh t:meta.view v:id=tsrc-szkh v:averageRating=0 v:name="ITA- Monthly Downloads My LA 311 App"

property e:tsrc-szkh t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:tsrc-szkh t:meta.view.owner v:id=yb4r-dcys v:profileImageUrlMedium=/api/users/yb4r-dcys/profile_images/THUMB v:profileImageUrlLarge=/api/users/yb4r-dcys/profile_images/LARGE v:screenName="ITA OpenData" v:profileImageUrlSmall=/api/users/yb4r-dcys/profile_images/TINY v:displayName="ITA OpenData"

property e:tsrc-szkh t:meta.view.tableauthor v:id=yb4r-dcys v:profileImageUrlMedium=/api/users/yb4r-dcys/profile_images/THUMB v:profileImageUrlLarge=/api/users/yb4r-dcys/profile_images/LARGE v:screenName="ITA OpenData" v:profileImageUrlSmall=/api/users/yb4r-dcys/profile_images/TINY v:roleName=publisher v:displayName="ITA OpenData"
```

## Top Records

```ls
| date                | date_name | of_myla311_app_downloads | 
| =================== | ========= | ======================== | 
| 2013-01-01T00:00:00 | Jan-13    | 0                        | 
| 2013-02-01T00:00:00 | Feb-13    | 0                        | 
| 2013-03-01T00:00:00 | Mar-13    | 898                      | 
| 2013-04-01T00:00:00 | Apr-13    | 9592                     | 
| 2013-05-01T00:00:00 | May-13    | 820                      | 
| 2013-06-01T00:00:00 | Jun-13    | 1138                     | 
| 2013-07-01T00:00:00 | Jul-13    | 1933                     | 
| 2013-08-01T00:00:00 | Aug-13    | 1169                     | 
| 2013-09-01T00:00:00 | Sep-13    | 961                      | 
| 2013-10-01T00:00:00 | Oct-13    | 877                      | 
```