# DWP - Percentage Of Water Purchased From MWD Each Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dwp-percentage-of-water-purchased-from-mwd-3-yr-avg-51db8) |
| Metadata | [Link](https://data.lacity.org/api/views/8yaq-2fpu) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/8yaq-2fpu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/8yaq-2fpu/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 8yaq-2fpu |
| Name | DWP - Percentage Of Water Purchased From MWD Each Fiscal Year |
| Category | A Livable and Sustainable City |
| Tags | dwp, water, mwd, local, in-basin, metropolitan water district, imported water |
| Created | 2014-05-30T22:10:37Z |
| Publication Date | 2017-03-13T18:40:37Z |

## Description

Los Angeles gets its water from several sources, including local water supplies, recycled water and the Owens Valley. When those sources do not provide enough to meet demand, the DWP must purchase water on the open market from the Metropolitan Water District. Water from the MWD costs more than the other sources, so keeping purchases from MWD low is important to ensuring stable and affordable rates for DWP customers.

## Columns

```ls
| Included | Schema Type    | Field Name                                             | Name                                          | Data Type | Render Type |
| ======== | ============== | ====================================================== | ============================================= | ========= | =========== |
| No       | time           | :updated_at                                            | updated_at                                    | meta_data | meta_data   |
| No       |                | date_name                                              | Fiscal Year                                   | text      | text        |
| Yes      | numeric metric | percentage_of_water_supply_purchased_from_mwd_3_yr_avg | Percentage of Water Supply Purchased from MWD | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date_name
```

## Data Commands

```ls
series e:8yaq-2fpu d:2017-03-13T18:38:16.000Z m:percentage_of_water_supply_purchased_from_mwd_3_yr_avg=25.1

series e:8yaq-2fpu d:2017-03-13T18:38:16.000Z m:percentage_of_water_supply_purchased_from_mwd_3_yr_avg=9

series e:8yaq-2fpu d:2017-03-13T18:38:16.000Z m:percentage_of_water_supply_purchased_from_mwd_3_yr_avg=9.9
```

## Meta Commands

```ls
metric m:percentage_of_water_supply_purchased_from_mwd_3_yr_avg p:double l:"Percentage of Water Supply Purchased from MWD" t:dataTypeName=percent

entity e:8yaq-2fpu l:"DWP - Percentage Of Water Purchased From MWD  Each Fiscal Year" t:url=https://data.lacity.org/api/views/8yaq-2fpu

property e:8yaq-2fpu t:meta.view v:id=8yaq-2fpu v:category="A Livable and Sustainable City" v:averageRating=0 v:name="DWP - Percentage Of Water Purchased From MWD  Each Fiscal Year"

property e:8yaq-2fpu t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:8yaq-2fpu t:meta.view.owner v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:displayName="LA DWP OpenData"

property e:8yaq-2fpu t:meta.view.tableauthor v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:roleName=publisher v:displayName="LA DWP OpenData"
```

## Top Records

```ls
| :updated_at | date_name | percentage_of_water_supply_purchased_from_mwd_3_yr_avg | 
| =========== | ========= | ====================================================== | 
| 1489430296  | 1969-70   | 25.1                                                   | 
| 1489430296  | 1970-71   | 9                                                      | 
| 1489430296  | 1971-72   | 9.9                                                    | 
| 1489430296  | 1972-73   | 5.7                                                    | 
| 1489430296  | 1973-74   | 4.5                                                    | 
| 1489430296  | 1974-75   | 5.7                                                    | 
| 1489430296  | 1975-76   | 4.1                                                    | 
| 1489430296  | 1976-77   | 18.9                                                   | 
| 1489430296  | 1977-78   | 9.2                                                    | 
| 1489430296  | 1978-79   | 3.2                                                    | 
```