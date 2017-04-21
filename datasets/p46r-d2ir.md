# Category Stories

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/category-stories-6ccf2) |
| Metadata | [Link](https://data.hawaii.gov/api/views/p46r-d2ir) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/p46r-d2ir/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/p46r-d2ir/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | p46r-d2ir |
| Name | Category Stories |
| Created | 2012-07-07T05:38:35Z |
| Publication Date | 2012-09-24T20:12:51Z |

## Description

Dataset of information for Category Detail pages

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | category    | category   | text      | text        |
| Yes      | series tag  | link        | link       | text      | text        |
| Yes      | series tag  | title       | title      | text      | text        |
| Yes      | series tag  | source      | source     | text      | text        |
| Yes      | series tag  | text        | text       | text      | text        |
| Yes      | series tag  | photo       | Photo      | photo     | photo       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:p46r-d2ir d:2012-07-16T17:11:58.000Z t:text="Additional maps of other school types can be created" t:title="Location of High Schools" t:category="Formal Education" t:source=https://data.hawaii.gov/d/6r5m-ppsj t:link=formal_education t:photo=9kn-ksrv9ILdcpkH548XFpHZb9Mnu8FwH5xtH99FGhs m:row_number.p46r-d2ir=1

series e:p46r-d2ir d:2012-07-16T17:13:04.000Z t:text="To explore more data about Libaries search on Libraries" t:title="Location of State Public Libraries" t:category="Formal Education" t:source=https://data.hawaii.gov/d/jx86-2vch t:link=formal_education t:photo=T61UUfDxJZmxT1DxgTWzuDw3vGQ-TUtSR5p6GmVmGKQ m:row_number.p46r-d2ir=2

series e:p46r-d2ir d:2012-07-16T18:55:52.000Z t:text="Let the Department of Agriculture know if we are missing any" t:title="Map of Farmers Markets across the State" t:category="Culture and Recreation" t:source=https://data.hawaii.gov/d/nqfm-3etr t:link=culture_and_recreation t:photo=5vn8kFrJuTr_vgQnmAinsAiPpAZOtkpMf-UHKRVBaII m:row_number.p46r-d2ir=3
```

## Meta Commands

```ls
metric m:row_number.p46r-d2ir p:long l:"Row Number"

entity e:p46r-d2ir l:"Category Stories" t:url=https://data.hawaii.gov/api/views/p46r-d2ir

property e:p46r-d2ir t:meta.view v:id=p46r-d2ir v:averageRating=0 v:name="Category Stories"

property e:p46r-d2ir t:meta.view.owner v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"

property e:p46r-d2ir t:meta.view.tableauthor v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"
```

## Top Records

```ls
| :updated_at | category                  | link                      | title                                                                 | source                              | text                                                                                                                                                                                   | photo                                       | 
| =========== | ========================= | ========================= | ===================================================================== | =================================== | ====================================================================================================================================================================================== | =========================================== | 
| 1342458718  | Formal Education          | formal_education          | Location of High Schools                                              | https://data.hawaii.gov/d/6r5m-ppsj | Additional maps of other school types can be created                                                                                                                                   | 9kn-ksrv9ILdcpkH548XFpHZb9Mnu8FwH5xtH99FGhs | 
| 1342458784  | Formal Education          | formal_education          | Location of State Public Libraries                                    | https://data.hawaii.gov/d/jx86-2vch | To explore more data about Libaries search on Libraries                                                                                                                                | T61UUfDxJZmxT1DxgTWzuDw3vGQ-TUtSR5p6GmVmGKQ | 
| 1342464952  | Culture and Recreation    | culture_and_recreation    | Map of Farmers Markets across the State                               | https://data.hawaii.gov/d/nqfm-3etr | Let the Department of Agriculture know if we are missing any                                                                                                                           | 5vn8kFrJuTr_vgQnmAinsAiPpAZOtkpMf-UHKRVBaII | 
| 1342628316  | Individual Rights         | individual_rights         | Top Ten Lobbyist Organization by Expenditure for Lobby period 2011-03 | https://data.hawaii.gov/d/6uwv-4qkz | Explore the full data set for other lobby periods                                                                                                                                      | OCDl67-FCFqAXn7_x6QNkaYP3krjNXKx61W_Fh-MZRY | 
| 1343141462  | Transportation Facilities | transportation_facilities | Retail car registrations by make of vehicle                           | https://data.hawaii.gov/d/a7f5-6vg6 | Mouse over the chart view or see data set for all types                                                                                                                                | znK-VeZxeLIX6FuB3ssDGks3UxbnzHiG87Xeg2Hby3c | 
| 1343151380  | Transportation Facilities | transportation_facilities | Price of a gallon of regular gas in Honolulu from 2006-2012           | https://data.hawaii.gov/d/dqp6-3idi | Explore the State Energy Office data for more details                                                                                                                                  | xHk4nRPcpK8gqD0FgnRXiYDEwkJdxNxHUTgA9vu05rA | 
| 1345747880  | Tourism                   | Tourism                   | Map of Hawaii tourism Authority inventory list                        | https://data.hawaii.gov/d/r8i7-xd8t | The Visitor Plant Inventory presents the results of the Hawaii Tourism Authority's enumeration of visitor accommodations in Hawaii. Existing visitor accommodations as of May 1, 2011. | m92tOeaXtXhjJXLKtxYW9k0T-rwYjX81xuw4YS3tqes | 
| 1345820127  | Tourism                   | Tourism                   | Line graph of Hawaii visitors by month and year                       | https://data.hawaii.gov/d/28kv-pay3 | See busiest month and year at a glance                                                                                                                                                 | J7pcTg_ulAnxwNcIts2ZuW-bR-tV3kTspZcMC5za30k | 
| 1347041977  | Health                    | health                    | Map of Hospitals in Hawaii                                            | https://data.hawaii.gov/d/bnu5-w695 | Find the closest hospital                                                                                                                                                              | iWbJMaLxPjFDMivJEm8rbv9B1obi2onY7gcQqFUtgPg | 
| 1347042929  | Health                    | health                    | Map of Public Health Nursing                                          | https://data.hawaii.gov/d/vg6h-w5vn | Facilities that provide Public health nursing                                                                                                                                          | vjaKUNENJWQnzejQgfa0ABtuHHLFL5b5hAxx_SYiirA | 
```