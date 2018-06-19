# LADWP Once Through Cooling (OTC)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ladwp-once-through-cooling-otc-7c223) |
| Metadata | [Link](https://data.lacity.org/api/views/hsmw-wwd6) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/hsmw-wwd6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/hsmw-wwd6/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | hsmw-wwd6 |
| Name | LADWP Once Through Cooling (OTC) |
| Attribution | LADWP |
| Category | A Livable and Sustainable City |
| Tags | otc, once through cooling, coastal power plants |
| Created | 2014-05-23T22:55:37Z |
| Publication Date | 2014-05-23T23:00:17Z |

## Description

Once-Through Cooling is the process of drawing ocean water and pumping it through a generating station's cooling system, then discharging it back into the ocean. LADWP is eliminating the use of ocean water for cooling in its 3 coastal power plants. MGD stands for Million Gallons per Day.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | time           | year       | Year      | number    | text        |
| Yes      | numeric metric | otc_mgd    | OTC (MGD) | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hsmw-wwd6 d:1990-01-01T00:00:00.000Z m:otc_mgd=1904

series e:hsmw-wwd6 d:1991-01-01T00:00:00.000Z m:otc_mgd=1904

series e:hsmw-wwd6 d:1992-01-01T00:00:00.000Z m:otc_mgd=1904
```

## Meta Commands

```ls
metric m:otc_mgd p:integer l:"OTC (MGD)" t:dataTypeName=number

entity e:hsmw-wwd6 l:"LADWP Once Through Cooling (OTC)" t:attribution=LADWP t:url=https://data.lacity.org/api/views/hsmw-wwd6

property e:hsmw-wwd6 t:meta.view v:id=hsmw-wwd6 v:category="A Livable and Sustainable City" v:averageRating=0 v:name="LADWP Once Through Cooling (OTC)" v:attribution=LADWP

property e:hsmw-wwd6 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:hsmw-wwd6 t:meta.view.owner v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:displayName="LA DWP OpenData"

property e:hsmw-wwd6 t:meta.view.tableauthor v:id=7q7s-tyf3 v:screenName="Steve Baule" v:roleName=publisher v:displayName="Steve Baule"
```

## Top Records

```ls
| year | otc_mgd | 
| ==== | ======= | 
| 1990 | 1904    | 
| 1991 | 1904    | 
| 1992 | 1904    | 
| 1993 | 1904    | 
| 1994 | 1904    | 
| 1995 | 1617    | 
| 1996 | 1617    | 
| 1997 | 1617    | 
| 1998 | 1617    | 
| 1999 | 1617    | 
```