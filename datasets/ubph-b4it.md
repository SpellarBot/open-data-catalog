# Mayor's ED No.5 GPCD Target Progress

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dwp-per-capita-water-1a275) |
| Metadata | [Link](https://data.lacity.org/api/views/ubph-b4it) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/ubph-b4it/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/ubph-b4it/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | ubph-b4it |
| Name | Mayor's ED No.5 GPCD Target Progress |
| Category | A Livable and Sustainable City |
| Tags | water, conservation, per capita, water use |
| Created | 2014-05-30T22:17:25Z |
| Publication Date | 2017-03-21T16:53:26Z |

## Description

This metric measures the average total daily water use in Los Angeles, divided by the total number of residents. As this figure includes commercial, industrial, and institutional water use, this figure does not represent the average personal daily use of an individual Angeleno.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                               | Data Type | Render Type |
| ======== | ============== | ==================================== | ================================== | ========= | =========== |
| No       | time           | :updated_at                          | updated_at                         | meta_data | meta_data   |
| No       |                | date                                 | Month-Year                         | text      | text        |
| Yes      | numeric metric | per_capita_water_use_gallons_per_day | GPCD-12 Month Rolling Conservation | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date
```

## Data Commands

```ls
series e:ubph-b4it d:2017-03-13T20:02:56.000Z m:per_capita_water_use_gallons_per_day=111

series e:ubph-b4it d:2017-03-13T20:02:56.000Z m:per_capita_water_use_gallons_per_day=110

series e:ubph-b4it d:2017-03-13T20:02:56.000Z m:per_capita_water_use_gallons_per_day=109
```

## Meta Commands

```ls
metric m:per_capita_water_use_gallons_per_day p:integer l:"GPCD-12 Month Rolling Conservation" d:"GPCD-12 Month Rolling Conservation" t:dataTypeName=number

entity e:ubph-b4it l:"Mayor's ED No.5 GPCD Target Progress" t:url=https://data.lacity.org/api/views/ubph-b4it

property e:ubph-b4it t:meta.view v:id=ubph-b4it v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Mayor's ED No.5 GPCD Target Progress"

property e:ubph-b4it t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:ubph-b4it t:meta.view.owner v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:displayName="LA DWP OpenData"

property e:ubph-b4it t:meta.view.tableauthor v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:roleName=publisher v:displayName="LA DWP OpenData"
```

## Top Records

```ls
| :updated_at | date   | per_capita_water_use_gallons_per_day | 
| =========== | ====== | ==================================== | 
| 1489435376  | Jul-15 | 111                                  | 
| 1489435376  | Aug-15 | 110                                  | 
| 1489435376  | Sep-15 | 109                                  | 
| 1489435376  | Oct-15 | 107                                  | 
| 1489435376  | Nov-15 | 107                                  | 
| 1489435376  | Dec-15 | 108                                  | 
| 1489435376  | Jan-16 | 106                                  | 
| 1489435376  | Feb-16 | 106                                  | 
| 1489435376  | Mar-16 | 105                                  | 
| 1489435376  | Apr-16 | 104                                  | 
```