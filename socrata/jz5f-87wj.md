# Water Main Breaks in the City of Los Angeles Each Month

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/water-leaks-in-the-city-of-los-angeles-cb80c) |
| Metadata | [Link](https://data.lacity.org/api/views/jz5f-87wj) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/jz5f-87wj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/jz5f-87wj/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | jz5f-87wj |
| Name | Water Main Breaks in the City of Los Angeles Each Month |
| Category | A Livable and Sustainable City |
| Tags | water leaks, broken pipe |
| Created | 2014-05-12T23:15:32Z |
| Publication Date | 2017-03-13T16:25:49Z |

## Description

Number of recorded water leaks by months in the City of Los Angeles

## Columns

```ls
| Included | Schema Type    | Field Name | Name  | Data Type | Render Type |
| ======== | ============== | ========== | ===== | ========= | =========== |
| Yes      | time           | month      | Month | text      | text        |
| Yes      | numeric metric | total      | Total | number    | number      |
```

## Time Field

```ls
Value = month
Format & Zone = MMM-yy
```

## Data Commands

```ls
series e:jz5f-87wj d:2003-07-01T00:00:00.000Z m:total=131

series e:jz5f-87wj d:2003-08-01T00:00:00.000Z m:total=97

series e:jz5f-87wj d:2003-09-01T00:00:00.000Z m:total=170
```

## Meta Commands

```ls
metric m:total p:integer l:Total t:dataTypeName=number

entity e:jz5f-87wj l:"Water Main Breaks in the City of Los Angeles Each Month" t:url=https://data.lacity.org/api/views/jz5f-87wj

property e:jz5f-87wj t:meta.view v:id=jz5f-87wj v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Water Main Breaks in the City of Los Angeles Each Month"

property e:jz5f-87wj t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:jz5f-87wj t:meta.view.owner v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:displayName="LA DWP OpenData"

property e:jz5f-87wj t:meta.view.tableauthor v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:roleName=publisher v:displayName="LA DWP OpenData"
```

## Top Records

```ls
| month  | total | 
| ====== | ===== | 
| Jul-03 | 131   | 
| Aug-03 | 97    | 
| Sep-03 | 170   | 
| Oct-03 | 153   | 
| Nov-03 | 151   | 
| Dec-03 | 279   | 
| Jan-04 | 219   | 
| Feb-04 | 120   | 
| Mar-04 | 155   | 
| Apr-04 | 125   | 
```