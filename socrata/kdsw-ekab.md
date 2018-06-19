# SSMMA Village Of Midlothian Businesses For Sale Or Lease

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-village-of-midlothian-businesses-for-sale-or-lease-67116) |
| Metadata | [Link](https://data.illinois.gov/api/views/kdsw-ekab) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/kdsw-ekab/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/kdsw-ekab/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | kdsw-ekab |
| Name | SSMMA Village Of Midlothian Businesses For Sale Or Lease |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | midlothian, economic development, planning, business |
| Created | 2012-11-27T17:31:43Z |
| Publication Date | 2012-11-27T19:17:31Z |

## Description

This dataset details businesses for sale or lease in the Village of Midlothian, Illinois

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | business_type   | Business Type   | text      | text        |
| No       |             | businessaddress | BusinessAddress | text      | text        |
| Yes      | series tag  | units_for_lease | Units For Lease | text      | text        |
| Yes      | series tag  | zoned           | Zoned           | text      | text        |
| Yes      | series tag  | developed       | Developed       | text      | text        |
| Yes      | series tag  | width           | Width           | text      | text        |
| Yes      | series tag  | depth           | Depth           | text      | text        |
| Yes      | series tag  | unit_sq_ft      | Unit Sq. Ft.    | text      | text        |
| Yes      | series tag  | acreage         | Acreage         | text      | text        |
| Yes      | series tag  | owner_name      | Owner Name      | text      | text        |
| Yes      | series tag  | owner_contact   | Owner Contact # | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = businessaddress
```

## Data Commands

```ls
series e:kdsw-ekab d:2012-11-27T09:31:45.000Z t:owner_contact="(773) 221-7952" t:unit_sq_ft=2000 t:zoned=B-1 t:owner_name="Chester Borsuk" t:width=115ft t:developed="1 Story Bldg" t:units_for_lease=1 t:business_type=Retail/Office t:acreage=0.33 t:depth=125ft m:row_number.kdsw-ekab=1

series e:kdsw-ekab d:2012-11-27T09:31:45.000Z t:owner_contact="(773) 221-7952" t:unit_sq_ft=800 t:zoned=B-1 t:owner_name="Chester Borsuk" t:width=115ft t:developed="1 Story Bldg" t:units_for_lease=1 t:business_type=Restaurant t:acreage=0.330001 t:depth=125ft m:row_number.kdsw-ekab=2

series e:kdsw-ekab d:2012-11-27T09:31:45.000Z t:owner_contact="(708) 997-0615" t:unit_sq_ft=800 t:zoned=B-1 t:owner_name="George Pappas" t:width=90ft t:developed="1 Story Bldg" t:units_for_lease=1 t:business_type=Retail/Office t:acreage=0.2685 t:depth=130ft m:row_number.kdsw-ekab=3
```

## Meta Commands

```ls
metric m:row_number.kdsw-ekab p:long l:"Row Number"

entity e:kdsw-ekab l:"SSMMA Village Of Midlothian  Businesses For Sale Or Lease" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/kdsw-ekab

property e:kdsw-ekab t:meta.view v:id=kdsw-ekab v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Village Of Midlothian  Businesses For Sale Or Lease" v:attribution="South Suburban Mayors and Managers Association"

property e:kdsw-ekab t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:kdsw-ekab t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:kdsw-ekab t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| :updated_at | business_type | businessaddress | units_for_lease | zoned | developed    | width | depth | unit_sq_ft | acreage  | owner_name          | owner_contact  | 
| =========== | ============= | =============== | =============== | ===== | ============ | ===== | ===== | ========== | ======== | =================== | ============== | 
| 1354008705  | Retail/Office | 3202 W 147th St | 1               | B-1   | 1 Story Bldg | 115ft | 125ft | 2000       | 0.33     | Chester Borsuk      | (773) 221-7952 | 
| 1354008705  | Restaurant    | 3228 W 147th St | 1               | B-1   | 1 Story Bldg | 115ft | 125ft | 800        | 0.330001 | Chester Borsuk      | (773) 221-7952 | 
| 1354008705  | Retail/Office | 3300 W 147th St | 1               | B-1   | 1 Story Bldg | 90ft  | 130ft | 800        | 0.2685   | George Pappas       | (708) 997-0615 | 
| 1354008705  | Commercial    | 14475 Waverly   | Multiple        | OI    | 2 Story Bldg | 80    | 150   |            | 0.27548  | Kazimierz Kolbrecki | (630) 257-2208 | 
| 1354008705  | Retail/Office | 3433 W 147th St | Multiple        | R-2   |              |       |       |            |          | Carmen Adekola      | (708) 699-8387 | 
| 1354008705  | Retail/Office | 3642 W 147th St | Multiple        | B-2   | 1 Story Bldg | 30    | 130   | 500        | 0.0895   | Joseph J. Blaszak   | (708) 389-7740 | 
| 1354008705  | Retail/Office | 3824 W 147th St | Multiple        | B-2   | 2 Story Bldg |       |       | 1000       |          | Louie Dimis         | (708) 299-7211 | 
| 1354008705  | Retail/Office | 3836 W 147th St | 1               | B-2   | 1 Story Bldg |       |       | 750        |          | Chris Bartolini     | (708) 444-2171 | 
| 1354008705  | Retail/Office | 3912 W 147th St | 1               | B-2   | 1 Story Bldg |       |       |            |          | Robert Watson       | (815) 469-8900 | 
| 1354008705  | Retail/Office | 3934 W 147th St | 1               | B-2   | 1 Story Bldg | 130ft | 105ft | 6000       | 0.3133   | Robert Watson       | (815) 469-8900 | 
```