# how do i typeahead data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/how-do-i-typeahead-data-84bbf) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/fyug-m7sc) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/fyug-m7sc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/fyug-m7sc/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | fyug-m7sc |
| Name | how do i typeahead data |
| Attribution | King County |
| Category | Website content |
| Tags | typeahead webteam |
| Created | 2013-09-03T19:34:10Z |
| Publication Date | 2013-10-18T20:01:48Z |

## Description

Data to populate how do i type ahead data

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type      | Render Type    |
| ======== | =========== | =========== | ========== | ============== | ============== |
| No       | time        | :updated_at | updated_at | meta_data      | meta_data      |
| Yes      | series tag  | task        | Task       | text           | text           |
| Yes      | series tag  | link        | Link       | text           | text           |
| Yes      | series tag  | category2   | Category   | drop_down_list | drop_down_list |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fyug-m7sc d:2013-10-18T12:29:56.000Z t:task=Permits t:link=/property/permits/info t:category2=7cth-4f8a m:row_number.fyug-m7sc=1

series e:fyug-m7sc d:2013-10-18T12:29:59.000Z t:task="Jobs at King County" t:link=/jobs t:category2=7cth-4f8a m:row_number.fyug-m7sc=2

series e:fyug-m7sc d:2013-10-18T12:30:06.000Z t:task="Pet License" t:link=/safety/regionalAnimalServices/License t:category2=7cth-4f8a m:row_number.fyug-m7sc=3
```

## Meta Commands

```ls
metric m:row_number.fyug-m7sc p:long l:"Row Number"

entity e:fyug-m7sc l:"how do i typeahead data" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/fyug-m7sc

property e:fyug-m7sc t:meta.view v:id=fyug-m7sc v:category="Website content" v:averageRating=0 v:name="how do i typeahead data" v:attribution="King County"

property e:fyug-m7sc t:meta.view.license v:name="Public Domain"

property e:fyug-m7sc t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:fyug-m7sc t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| :updated_at | task                                     | link                                                                                                      | category2 | 
| =========== | ======================================== | ========================================================================================================= | ========= | 
| 1382099396  | Permits                                  | /property/permits/info                                                                                    | 7cth-4f8a | 
| 1382099399  | Jobs at King County                      | /jobs                                                                                                     | 7cth-4f8a | 
| 1382099406  | Pet License                              | /safety/regionalAnimalServices/License                                                                    | 7cth-4f8a | 
| 1382099408  | Business license                         | /business/licenses                                                                                        | 7cth-4f8a | 
| 1382099412  | Marriage license                         | /courts/marriage                                                                                          | 7cth-4f8a | 
| 1382099418  | Jury duty                                | /how-do-i/jury-duty                                                                                       | th57-wapf | 
| 1382099425  | Register as a vendor                     | https://procurement.kingcounty.gov/procurement_ovr/login.aspx?ReturnUrl=%2fprocurement_ovr%2fdefault.aspx | w5yi-xsg9 | 
| 1382099430  | View bid & contract opportunities        | /operations/procurement                                                                                   | w5yi-xsg9 | 
| 1382099441  | Find certified contractors and suppliers | https://info.kingcounty.gov/EXEC/contractreporting/Public/SCS/default.aspx                                | w5yi-xsg9 | 
| 1382099466  | District Court documents                 | /courts/DistrictCourt/SmallClaims                                                                         | mapg-yztp | 
```