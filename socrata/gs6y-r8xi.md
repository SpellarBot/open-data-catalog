# Libraries - 2015 Wi Fi Usage

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2015-wi-fi-usage) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/gs6y-r8xi) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/gs6y-r8xi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/gs6y-r8xi/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | gs6y-r8xi |
| Name | Libraries - 2015 Wi Fi Usage |
| Tags | libraries, wi fi |
| Created | 2015-02-11T23:17:28Z |
| Publication Date | 2016-01-11T18:25:40Z |

## Description

The Chicago Public Library offers free WiFi at all locations.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       |                | month              | MONTH              | text      | text        |
| No       |                | year               | YEAR               | number    | text        |
| Yes      | numeric metric | number_of_sessions | NUMBER OF SESSIONS | number    | number      |
| Yes      | numeric metric | ytd                | YTD                | number    | number      |
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
series e:gs6y-r8xi d:2015-01-01T00:00:00.000Z m:ytd=285540 m:number_of_sessions=285540

series e:gs6y-r8xi d:2015-02-01T00:00:00.000Z m:ytd=535261 m:number_of_sessions=249721

series e:gs6y-r8xi d:2015-03-01T00:00:00.000Z m:ytd=834528 m:number_of_sessions=299267
```

## Meta Commands

```ls
metric m:number_of_sessions p:integer l:"NUMBER OF SESSIONS" t:dataTypeName=number

metric m:ytd p:integer l:YTD t:dataTypeName=number

entity e:gs6y-r8xi l:"Libraries - 2015 Wi Fi Usage" t:url=https://data.cityofchicago.org/api/views/gs6y-r8xi

property e:gs6y-r8xi t:meta.view v:id=gs6y-r8xi v:averageRating=0 v:name="Libraries - 2015 Wi Fi Usage"

property e:gs6y-r8xi t:meta.view.owner v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:displayName="Marie E. Hardy"

property e:gs6y-r8xi t:meta.view.tableauthor v:id=vedk-n2zt v:profileImageUrlMedium=/api/users/vedk-n2zt/profile_images/THUMB v:profileImageUrlLarge=/api/users/vedk-n2zt/profile_images/LARGE v:screenName="Marie E. Hardy" v:profileImageUrlSmall=/api/users/vedk-n2zt/profile_images/TINY v:roleName=editor v:displayName="Marie E. Hardy"
```

## Top Records

```ls
| month     | year | number_of_sessions | ytd     | 
| ========= | ==== | ================== | ======= | 
| January   | 2015 | 285540             | 285540  | 
| February  | 2015 | 249721             | 535261  | 
| March     | 2015 | 299267             | 834528  | 
| April     | 2015 | 305097             | 1139625 | 
| May       | 2015 | 285416             | 1425041 | 
| June      | 2015 | 307731             | 1732772 | 
| July      | 2015 | 308945             | 2041717 | 
| August    | 2015 | 308774             | 2350491 | 
| September | 2015 | 337671             | 2688162 | 
| October   | 2015 | 351153             | 3039315 | 
```