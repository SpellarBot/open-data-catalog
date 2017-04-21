# LADWP Water Mainline Replacement

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ladwp-water-mainline-replacement-f7e3a) |
| Metadata | [Link](https://data.lacity.org/api/views/pzs3-fue3) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/pzs3-fue3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/pzs3-fue3/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | pzs3-fue3 |
| Name | LADWP Water Mainline Replacement |
| Attribution | LADWP |
| Category | A Livable and Sustainable City |
| Created | 2014-05-12T23:22:02Z |
| Publication Date | 2017-03-13T17:00:36Z |

## Description

Water Pipe Mainline Replacement in feet by month.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                   | Data Type     | Render Type   |
| ======== | ============== | ==================== | ====================== | ============= | ============= |
| Yes      | series tag     | month                | Month                  | text          | text          |
| Yes      | time           | date_month           | Date (Month)           | calendar_date | calendar_date |
| Yes      | numeric metric | mainline_ft_replaced | Mainline (ft) replaced | number        | number        |
```

## Time Field

```ls
Value = date_month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:pzs3-fue3 d:2013-03-31T00:00:00.000Z t:month=March-13 m:mainline_ft_replaced=8615

series e:pzs3-fue3 d:2013-04-30T00:00:00.000Z t:month=April-13 m:mainline_ft_replaced=12629

series e:pzs3-fue3 d:2013-05-31T00:00:00.000Z t:month=May-13 m:mainline_ft_replaced=9527
```

## Meta Commands

```ls
metric m:mainline_ft_replaced p:integer l:"Mainline (ft) replaced" t:dataTypeName=number

entity e:pzs3-fue3 l:"LADWP Water Mainline Replacement" t:attribution=LADWP t:url=https://data.lacity.org/api/views/pzs3-fue3

property e:pzs3-fue3 t:meta.view v:id=pzs3-fue3 v:category="A Livable and Sustainable City" v:averageRating=0 v:name="LADWP Water Mainline Replacement" v:attribution=LADWP

property e:pzs3-fue3 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:pzs3-fue3 t:meta.view.owner v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:displayName="LA DWP OpenData"

property e:pzs3-fue3 t:meta.view.tableauthor v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:roleName=publisher v:displayName="LA DWP OpenData"
```

## Top Records

```ls
| month        | date_month          | mainline_ft_replaced | 
| ============ | =================== | ==================== | 
| March-13     | 2013-03-31T00:00:00 | 8615                 | 
| April-13     | 2013-04-30T00:00:00 | 12629                | 
| May-13       | 2013-05-31T00:00:00 | 9527                 | 
| June-13      | 2013-06-30T00:00:00 | 7770                 | 
| July-13      | 2013-07-31T00:00:00 | 11399                | 
| August-13    | 2013-08-31T00:00:00 | 8168                 | 
| September-13 | 2013-09-30T00:00:00 | 10837                | 
| October-13   | 2013-10-31T00:00:00 | 9590                 | 
| November-13  | 2013-11-30T00:00:00 | 6059                 | 
| December-13  | 2013-12-31T00:00:00 | 6210                 | 
```