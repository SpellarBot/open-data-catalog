# LADWP Power Outages

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ladwp-power-outages) |
| Metadata | [Link](https://data.lacity.org/api/views/r95y-gwez) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/r95y-gwez/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/r95y-gwez/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | r95y-gwez |
| Name | LADWP Power Outages |
| Attribution | LADWP |
| Category | A Livable and Sustainable City |
| Tags | outages |
| Created | 2014-05-15T01:36:49Z |
| Publication Date | 2016-11-02T22:16:12Z |

## Description

Annual recorded number of Power Outages at LADWP

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | time           | year              | Year              | calendar_date | calendar_date |
| Yes      | numeric metric | number_of_outages | Number of Outages | number        | number        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:r95y-gwez d:2000-01-01T00:00:00.000Z m:number_of_outages=3404

series e:r95y-gwez d:2001-01-01T00:00:00.000Z m:number_of_outages=3452

series e:r95y-gwez d:2002-01-01T00:00:00.000Z m:number_of_outages=3494
```

## Meta Commands

```ls
metric m:number_of_outages p:integer l:"Number of Outages" t:dataTypeName=number

entity e:r95y-gwez l:"LADWP Power Outages" t:attribution=LADWP t:url=https://data.lacity.org/api/views/r95y-gwez

property e:r95y-gwez t:meta.view v:id=r95y-gwez v:category="A Livable and Sustainable City" v:averageRating=0 v:name="LADWP Power Outages" v:attribution=LADWP

property e:r95y-gwez t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:r95y-gwez t:meta.view.owner v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:displayName="LA DWP OpenData"

property e:r95y-gwez t:meta.view.tableauthor v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:roleName=publisher v:displayName="LA DWP OpenData"
```

## Top Records

```ls
| year                | number_of_outages | 
| =================== | ================= | 
| 2000-01-01T00:00:00 | 3404              | 
| 2001-01-01T00:00:00 | 3452              | 
| 2002-01-01T00:00:00 | 3494              | 
| 2003-01-01T00:00:00 | 4193              | 
| 2004-01-01T00:00:00 | 4508              | 
| 2005-01-01T00:00:00 | 5317              | 
| 2006-01-01T00:00:00 | 5915              | 
| 2007-01-01T00:00:00 | 5713              | 
| 2008-01-01T00:00:00 | 4628              | 
| 2009-01-01T00:00:00 | 4296              | 
```