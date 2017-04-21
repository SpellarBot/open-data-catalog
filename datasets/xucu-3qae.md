# Business License Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/business-license-data-91f63) |
| Metadata | [Link](https://data.illinois.gov/api/views/xucu-3qae) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/xucu-3qae/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/xucu-3qae/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | xucu-3qae |
| Name | Business License Data |
| Category | Municipality |
| Tags | business llcenses |
| Created | 2013-03-01T18:39:23Z |
| Publication Date | 2013-03-01T19:04:45Z |

## Description

City of Rockford Business License Data

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| No       | time        | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag  | cust_no       | CUST NO       | text      | number      |
| Yes      | series tag  | name          | NAME          | text      | text        |
| Yes      | series tag  | business_addr | BUSINESS ADDR | text      | text        |
| Yes      | series tag  | lic_code      | LIC CODE      | text      | number      |
| Yes      | series tag  | lic_descr     | LIC DESCR     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xucu-3qae d:2013-03-01T10:50:43.000Z t:business_addr="417 MAIN STREET PECATONICA" t:lic_code=101 t:name="HACKS AUCTION SERVICE" t:lic_descr=AUCTIONS t:cust_no=19 m:row_number.xucu-3qae=1

series e:xucu-3qae d:2013-03-01T10:50:43.000Z t:business_addr=NULL t:lic_code=23 t:name="DON CARTER LANES INC" t:lic_descr="BILLIARD TABLES" t:cust_no=25 m:row_number.xucu-3qae=2

series e:xucu-3qae d:2013-03-01T10:50:48.000Z t:business_addr=NULL t:lic_code=21 t:name="TEN PIN LANES" t:lic_descr="BOWLING ALLEY" t:cust_no=13 m:row_number.xucu-3qae=3
```

## Meta Commands

```ls
metric m:row_number.xucu-3qae p:long l:"Row Number"

entity e:xucu-3qae l:"Business License Data" t:url=https://data.illinois.gov/api/views/xucu-3qae

property e:xucu-3qae t:meta.view v:id=xucu-3qae v:category=Municipality v:averageRating=0 v:name="Business License Data"

property e:xucu-3qae t:meta.view.owner v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:displayName=Glenn

property e:xucu-3qae t:meta.view.tableauthor v:id=hdqp-matg v:profileImageUrlMedium=/api/users/hdqp-matg/profile_images/THUMB v:profileImageUrlLarge=/api/users/hdqp-matg/profile_images/LARGE v:screenName=Glenn v:profileImageUrlSmall=/api/users/hdqp-matg/profile_images/TINY v:roleName=publisher v:displayName=Glenn
```

## Top Records

```ls
| :updated_at | cust_no | name                          | business_addr              | lic_code | lic_descr                   | 
| =========== | ======= | ============================= | ========================== | ======== | =========================== | 
| 1362135043  | 19      | HACKS AUCTION SERVICE         | 417 MAIN STREET PECATONICA | 101      | AUCTIONS                    | 
| 1362135043  | 25      | DON CARTER LANES INC          | NULL                       | 23       | BILLIARD TABLES             | 
| 1362135048  | 13      | TEN PIN LANES                 | NULL                       | 21       | BOWLING ALLEY               | 
| 1362135051  | 33      | TAM COFFEE                    | NULL                       | 23       | BILLIARD TABLES             | 
| 1362135057  | 31      | STATE & MADISON BILLIARDS INC | NULL                       | 23       | BILLIARD TABLES             | 
| 1362135060  | 14      | STARLIGHT LANES               | NULL                       | 21       | BOWLING ALLEY               | 
| 1362135061  | 15      | WHITE EAGLE CLUB              | 10 LANES                   | 24       | BOWLING ALLEY               | 
| 1362135064  | 43      | FISCHER EXCAVATING            | CLASS A                    | 120      | BUILDING DEMOLITION CLASS A | 
| 1362135116  | 28      | ROCKFORD BILLIARD CAF?        | #460-475                   | 62       | AMUSEMENT DEVICES           | 
| 1362135219  | 42      | CASE CONSTRUCTION             | NULL                       | 120      | BUILDING DEMOLITION CLASS A | 
```