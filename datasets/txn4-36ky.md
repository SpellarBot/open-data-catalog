# Active Conservation in the City of Los Angeles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/active-conservation-in-the-city-of-los-angeles) |
| Metadata | [Link](https://data.lacity.org/api/views/txn4-36ky) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/txn4-36ky/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/txn4-36ky/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | txn4-36ky |
| Name | Active Conservation in the City of Los Angeles |
| Attribution | LADWP |
| Category | A Livable and Sustainable City |
| Tags | water, conservation |
| Created | 2014-05-12T23:04:15Z |
| Publication Date | 2015-12-07T20:14:34Z |

## Description

Active Water Conservation by Acre Feet in the City of Los Angeles. An Acre Foot is a unit of volume equal to one foot water in depth spread across one Acre (325,853.38 gallons).

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                         | Data Type | Render Type |
| ======== | ============== | =========================================== | ============================================ | ========= | =========== |
| Yes      | time           | month                                       | Month                                        | text      | text        |
| Yes      | numeric metric | monthly_active_water_conservation_acre_feet | Monthly Active Water Conservation(Acre-Feet) | number    | number      |
```

## Time Field

```ls
Value = month
Format & Zone = MMM-yy
```

## Data Commands

```ls
series e:txn4-36ky d:2011-07-01T00:00:00.000Z m:monthly_active_water_conservation_acre_feet=288

series e:txn4-36ky d:2011-08-01T00:00:00.000Z m:monthly_active_water_conservation_acre_feet=141

series e:txn4-36ky d:2011-09-01T00:00:00.000Z m:monthly_active_water_conservation_acre_feet=101
```

## Meta Commands

```ls
metric m:monthly_active_water_conservation_acre_feet p:integer l:"Monthly Active Water Conservation(Acre-Feet)" t:dataTypeName=number

entity e:txn4-36ky l:"Active Conservation in the City of Los Angeles" t:attribution=LADWP t:url=https://data.lacity.org/api/views/txn4-36ky

property e:txn4-36ky t:meta.view v:id=txn4-36ky v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Active Conservation in the City of Los Angeles" v:attribution=LADWP

property e:txn4-36ky t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:txn4-36ky t:meta.view.owner v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:displayName="LA DWP OpenData"

property e:txn4-36ky t:meta.view.tableauthor v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:roleName=publisher v:displayName="LA DWP OpenData"
```

## Top Records

```ls
| month  | monthly_active_water_conservation_acre_feet | 
| ====== | =========================================== | 
| Jul-11 | 288                                         | 
| Aug-11 | 141                                         | 
| Sep-11 | 101                                         | 
| Oct-11 | 103                                         | 
| Nov-11 | 180                                         | 
| Dec-11 | 175                                         | 
| Jan-12 | 126                                         | 
| Feb-12 | 174                                         | 
| Mar-12 | 184                                         | 
| Apr-12 | 173                                         | 
```