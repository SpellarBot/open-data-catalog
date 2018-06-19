# Monthly HELP (Highway Emergency Local Patrol) Assists: Beginning 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-help-highway-emergency-local-patrol-assists-beginning-2010) |
| Metadata | [Link](https://data.ny.gov/api/views/f923-iscf) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/f923-iscf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/f923-iscf/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | f923-iscf |
| Name | Monthly HELP (Highway Emergency Local Patrol) Assists: Beginning 2010 |
| Attribution | New York State Department of Transportation |
| Category | Transportation |
| Tags | help, assist, highway, road, vehicle |
| Created | 2013-05-14T19:24:36Z |
| Publication Date | 2016-05-11T22:00:44Z |

## Description

The HELP (Highway Emergency Local Patrol) file provides the number of motorists assisted by month, by region, in vehicles traveling on over 1,450 miles of limited access interstate roadways, parkways, and expressways on Long Island, in New York City, the Lower Hudson Valley, Buffalo, Rochester, and the Albany Capital District.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       |                | year                    | Year                    | number    | number      |
| No       |                | month                   | Month                   | text      | text        |
| Yes      | series tag     | albany_capital_district | Albany Capital District | text      | number      |
| Yes      | numeric metric | rochester               | Rochester               | number    | number      |
| Yes      | numeric metric | buffalo                 | Buffalo                 | number    | number      |
| Yes      | numeric metric | lower_hudson_valley     | Lower Hudson Valley     | number    | number      |
| Yes      | numeric metric | long_island             | Long Island             | number    | number      |
| Yes      | numeric metric | new_york_city           | New York City           | number    | number      |
| Yes      | numeric metric | total_assists           | Total Assists           | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:f923-iscf d:2014-01-01T00:00:00.000Z t:albany_capital_district=307 m:new_york_city=296 m:buffalo=102 m:long_island=1791 m:lower_hudson_valley=2407 m:total_assists=5345 m:rochester=442

series e:f923-iscf d:2014-02-01T00:00:00.000Z t:albany_capital_district=295 m:new_york_city=342 m:buffalo=80 m:long_island=1468 m:lower_hudson_valley=2435 m:total_assists=4927 m:rochester=307

series e:f923-iscf d:2014-03-01T00:00:00.000Z t:albany_capital_district=258 m:new_york_city=349 m:buffalo=72 m:long_island=1651 m:lower_hudson_valley=2404 m:total_assists=5016 m:rochester=282
```

## Meta Commands

```ls
metric m:rochester p:integer l:Rochester t:dataTypeName=number

metric m:buffalo p:integer l:Buffalo t:dataTypeName=number

metric m:lower_hudson_valley p:integer l:"Lower Hudson Valley" t:dataTypeName=number

metric m:long_island p:integer l:"Long Island" t:dataTypeName=number

metric m:new_york_city p:integer l:"New York City" t:dataTypeName=number

metric m:total_assists p:integer l:"Total Assists" t:dataTypeName=number

entity e:f923-iscf l:"Monthly HELP (Highway Emergency Local Patrol) Assists: Beginning 2010" t:attribution="New York State Department of Transportation" t:url=https://data.ny.gov/api/views/f923-iscf

property e:f923-iscf t:meta.view v:id=f923-iscf v:category=Transportation v:attributionLink=https://www.dot.ny.gov/helpprogram v:averageRating=0 v:name="Monthly HELP (Highway Emergency Local Patrol) Assists: Beginning 2010" v:attribution="New York State Department of Transportation"

property e:f923-iscf t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:f923-iscf t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:f923-iscf t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | month | albany_capital_district | rochester | buffalo | lower_hudson_valley | long_island | new_york_city | total_assists | 
| ==== | ===== | ======================= | ========= | ======= | =================== | =========== | ============= | ============= | 
| 2014 | Jan   | 307                     | 442       | 102     | 2407                | 1791        | 296           | 5345          | 
| 2014 | Feb   | 295                     | 307       | 80      | 2435                | 1468        | 342           | 4927          | 
| 2014 | Mar   | 258                     | 282       | 72      | 2404                | 1651        | 349           | 5016          | 
| 2014 | Apr   | 258                     | 288       | 117     | 2816                | 1800        | 395           | 5674          | 
| 2014 | May   | 317                     | 323       | 92      | 2773                | 1728        | 380           | 5613          | 
| 2014 | Jun   | 327                     | 320       | 112     | 2812                | 1799        | 365           | 5735          | 
| 2014 | Jul   | 334                     | 301       | 113     | 2935                | 1873        | 380           | 5936          | 
| 2014 | Aug   | 319                     | 260       | 128     | 2573                | 1666        | 352           | 5298          | 
| 2014 | Sep   | 329                     | 332       | 126     | 2425                | 1667        | 344           | 5223          | 
| 2014 | Oct   | 306                     | 322       | 124     | 2410                | 1660        | 342           | 5164          | 
```