# LADWP Stormwater Capture by Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ladwp-stormwater-capture-by-fiscal-year-4f912) |
| Metadata | [Link](https://data.lacity.org/api/views/p8nc-6hdi) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/p8nc-6hdi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/p8nc-6hdi/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | p8nc-6hdi |
| Name | LADWP Stormwater Capture by Fiscal Year |
| Attribution | LADWP |
| Category | A Livable and Sustainable City |
| Tags | stormwater, local water |
| Created | 2014-05-23T23:21:43Z |
| Publication Date | 2017-03-21T17:30:10Z |

## Description

LADWP's capacity for stormwater and actual stormwater collected

## Columns

```ls
| Included | Schema Type    | Field Name  | Name                  | Data Type | Render Type |
| ======== | ============== | =========== | ===================== | ========= | =========== |
| No       | time           | :updated_at | updated_at            | meta_data | meta_data   |
| No       |                | fy          | FY                    | text      | text        |
| Yes      | numeric metric | capture_af  | Capacity in Acre Feet | number    | number      |
| Yes      | numeric metric | recharge_af | Recharge in Acre Feet | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = fy
```

## Data Commands

```ls
series e:p8nc-6hdi d:2014-05-23T16:28:21.000Z m:capture_af=108116

series e:p8nc-6hdi d:2014-05-23T16:28:38.000Z m:capture_af=105100

series e:p8nc-6hdi d:2014-05-23T16:28:44.000Z m:capture_af=105100
```

## Meta Commands

```ls
metric m:capture_af p:integer l:"Capacity in Acre Feet" d:"Total stormwater Capacity in Acre Feet" t:dataTypeName=number

metric m:recharge_af p:long l:"Recharge in Acre Feet" d:"Actual stormwater captured" t:dataTypeName=number

entity e:p8nc-6hdi l:"LADWP Stormwater Capture by Fiscal Year" t:attribution=LADWP t:url=https://data.lacity.org/api/views/p8nc-6hdi

property e:p8nc-6hdi t:meta.view v:id=p8nc-6hdi v:category="A Livable and Sustainable City" v:averageRating=0 v:name="LADWP Stormwater Capture by Fiscal Year" v:attribution=LADWP

property e:p8nc-6hdi t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:p8nc-6hdi t:meta.view.owner v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:displayName="LA DWP OpenData"

property e:p8nc-6hdi t:meta.view.tableauthor v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:roleName=publisher v:displayName="LA DWP OpenData"
```

## Top Records

```ls
| :updated_at | fy      | capture_af | recharge_af | 
| =========== | ======= | ========== | =========== | 
| 1400862501  | 2010-11 | 108116     |             | 
| 1400862518  | 2008-09 | 105100     |             | 
| 1400862524  | 2009-10 | 105100     |             | 
| 1400862536  | 2011-12 | 108145     |             | 
| 1400862556  | 2012-13 | 108199     |             | 
| 1489427016  | 2013-14 | 108199     |             | 
| 1489427019  | 2014-15 | 108199     |             | 
| 1490117401  | 2015-16 | 64000      |             | 
```