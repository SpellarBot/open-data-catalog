# CTA - Ridership - Annual Boarding Totals

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cta-ridership-annual-boarding-totals-fb1a0) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/w8km-9pzd) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/w8km-9pzd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/w8km-9pzd/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | w8km-9pzd |
| Name | CTA - Ridership - Annual Boarding Totals |
| Attribution | Chicago Transit Authority |
| Category | Transportation |
| Tags | cta, public transit, ridership, sustainability |
| Created | 2011-08-11T21:15:40Z |
| Publication Date | 2016-02-26T23:14:54Z |

## Description

This dataset gives annual ridership totals dating to the mid-1980s. Numbers are presented in boardings (see attached readme file for information on how these numbers are calculated).

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | year        | year        | number    | number      |
| Yes      | numeric metric | bus         | bus         | number    | number      |
| Yes      | numeric metric | paratransit | paratransit | number    | number      |
| Yes      | numeric metric | rail        | rail        | number    | number      |
| Yes      | numeric metric | total       | total       | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:w8km-9pzd d:1988-01-01T00:00:00.000Z m:total=604960900 m:bus=430089500 m:rail=174436000 m:paratransit=435400

series e:w8km-9pzd d:1989-01-01T00:00:00.000Z m:total=590156300 m:bus=420572700 m:rail=168658800 m:paratransit=924800

series e:w8km-9pzd d:1990-01-01T00:00:00.000Z m:total=587847111 m:bus=421183734 m:rail=165732575 m:paratransit=930802
```

## Meta Commands

```ls
metric m:bus p:integer l:bus t:dataTypeName=number

metric m:paratransit p:integer l:paratransit t:dataTypeName=number

metric m:rail p:integer l:rail t:dataTypeName=number

metric m:total p:integer l:total t:dataTypeName=number

entity e:w8km-9pzd l:"CTA - Ridership - Annual Boarding Totals" t:attribution="Chicago Transit Authority" t:url=https://data.cityofchicago.org/api/views/w8km-9pzd

property e:w8km-9pzd t:meta.view v:id=w8km-9pzd v:category=Transportation v:attributionLink=http://www.transitchicago.com v:averageRating=0 v:name="CTA - Ridership - Annual Boarding Totals" v:attribution="Chicago Transit Authority"

property e:w8km-9pzd t:meta.view.owner v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:displayName="cta web"

property e:w8km-9pzd t:meta.view.tableauthor v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:roleName=designer v:displayName="cta web"
```

## Top Records

```ls
| year | bus       | paratransit | rail      | total     | 
| ==== | ========= | =========== | ========= | ========= | 
| 1988 | 430089500 | 435400      | 174436000 | 604960900 | 
| 1989 | 420572700 | 924800      | 168658800 | 590156300 | 
| 1990 | 421183734 | 930802      | 165732575 | 587847111 | 
| 1991 | 392088602 | 949460      | 147608116 | 540646178 | 
| 1992 | 370335119 | 1011669     | 137372830 | 508719618 | 
| 1993 | 326655953 | 1167904     | 135369734 | 463193591 | 
| 1994 | 331520700 | 1209900     | 143579100 | 476309700 | 
| 1995 | 306075585 | 1270274     | 135461619 | 442807478 | 
| 1996 | 302115116 | 1244209     | 142040486 | 445399811 | 
| 1997 | 287628293 | 1235085     | 151010374 | 439873752 | 
```