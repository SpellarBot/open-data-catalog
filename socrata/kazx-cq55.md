# Food Supplement Program (FSP) And Women Infants & Children (WIC) Programs, Participation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/food-supplement-program-fsp-and-women-infants-children-wic-programs-participation-2b465) |
| Metadata | [Link](https://data.maryland.gov/api/views/kazx-cq55) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/kazx-cq55/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/kazx-cq55/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | kazx-cq55 |
| Name | Food Supplement Program (FSP) And Women Infants & Children (WIC) Programs, Participation |
| Attribution | Department of Human Resources (DHR) |
| Category | Health and Human Services |
| Tags | dhr, hunger, childhood hunger, fsp, wic, food stamps, women, children, food |
| Created | 2013-02-09T01:41:59Z |
| Publication Date | 2015-08-31T14:35:27Z |

## Description

This dataset tracks participation in the food supplement program (formerly Food Stamps) as well as participation in the Women, Infants, & Children program.

## Columns

```ls
| Included | Schema Type    | Field Name                                     | Name                                                           | Data Type | Render Type |
| ======== | ============== | ============================================== | ============================================================== | ========= | =========== |
| Yes      | time           | month                                          | Month                                                          | text      | text        |
| Yes      | numeric metric | fsp_recipients_age_18_or_less                  | FSP Recipients (Age 18 or Younger)                             | number    | number      |
| Yes      | numeric metric | eligible_for_fsp_but_unreached_age_18_or_less  | Eligible for FSP but Unreached (Age 18 or Younger)             | number    | number      |
| Yes      | numeric metric | fsp_participation_rate_age_18_or_younger       | FSP Participation Rate (Age 18 or Younger)                     | percent   | percent     |
| Yes      | numeric metric | fsp_households_w_child_recipients              | FSP Households w/Child Recipients                              | number    | number      |
| Yes      | numeric metric | unreached_fsp_households_w_child               | Unreached FSP Households w/ Child                              | number    | number      |
| Yes      | numeric metric | fsp_participation_rate                         | FSP Households Participation Rate (for Children 18 or Younger) | percent   | percent     |
| Yes      | numeric metric | fsp_2015_participation_goal                    | FSP 2015 Participation Goal (for Children 18 or Younger)       | percent   | percent     |
| Yes      | numeric metric | wic_program_total_participation_children       | WIC Program: Total Participation (Children)                    | number    | number      |
| Yes      | numeric metric | wic_program_total_eligible                     | WIC Program: Total Eligible                                    | number    | number      |
| Yes      | numeric metric | wic_program_participation_rate                 | WIC Program: Participation Rate                                | percent   | percent     |
| Yes      | numeric metric | wic_program_percentage_of_usda_caseload_served | WIC Program: Percentage of USDA Caseload Served                | percent   | percent     |
```

## Time Field

```ls
Value = month
Format & Zone = MMM-yy
```

## Data Commands

```ls
series e:kazx-cq55 d:2009-12-01T00:00:00.000Z m:wic_program_participation_rate=80.5 m:fsp_participation_rate=51.8 m:fsp_recipients_age_18_or_less=242328 m:unreached_fsp_households_w_child=38304 m:fsp_2015_participation_goal=100 m:wic_program_total_participation_children=112746 m:eligible_for_fsp_but_unreached_age_18_or_less=115672 m:wic_program_total_eligible=139971 m:wic_program_percentage_of_usda_caseload_served=101.1 m:fsp_participation_rate_age_18_or_younger=72.6 m:fsp_households_w_child_recipients=120696

series e:kazx-cq55 d:2010-06-01T00:00:00.000Z m:wic_program_participation_rate=79.5 m:fsp_participation_rate=77.9 m:fsp_recipients_age_18_or_less=260100 m:unreached_fsp_households_w_child=28582 m:fsp_2015_participation_goal=100 m:wic_program_total_participation_children=111300 m:eligible_for_fsp_but_unreached_age_18_or_less=97900 m:wic_program_total_eligible=139971 m:wic_program_percentage_of_usda_caseload_served=100.3 m:fsp_participation_rate_age_18_or_younger=72.7 m:fsp_households_w_child_recipients=130529

series e:kazx-cq55 d:2010-12-01T00:00:00.000Z m:wic_program_participation_rate=79.2 m:fsp_participation_rate=86 m:fsp_recipients_age_18_or_less=285283 m:unreached_fsp_households_w_child=14545 m:fsp_2015_participation_goal=100 m:wic_program_total_participation_children=110866 m:eligible_for_fsp_but_unreached_age_18_or_less=72717 m:wic_program_total_eligible=139971 m:wic_program_percentage_of_usda_caseload_served=103.8 m:fsp_participation_rate_age_18_or_younger=79.7 m:fsp_households_w_child_recipients=144566
```

## Meta Commands

```ls
metric m:fsp_recipients_age_18_or_less p:integer l:"FSP Recipients (Age 18 or Younger)" d:"Children 18 or under who are Food Supplement Program (FSP) Recipients" t:dataTypeName=number

metric m:eligible_for_fsp_but_unreached_age_18_or_less p:integer l:"Eligible for FSP but Unreached (Age 18 or Younger)" d:"Children 18 or under who are eligible for the Food Supplement Program (FSP) but not participating." t:dataTypeName=number

metric m:fsp_participation_rate_age_18_or_younger p:float l:"FSP Participation Rate (Age 18 or Younger)" t:dataTypeName=percent

metric m:fsp_households_w_child_recipients p:integer l:"FSP Households w/Child Recipients" t:dataTypeName=number

metric m:unreached_fsp_households_w_child p:integer l:"Unreached FSP Households w/ Child" t:dataTypeName=number

metric m:fsp_participation_rate p:float l:"FSP Households Participation Rate (for Children 18 or Younger)" t:dataTypeName=percent

metric m:fsp_2015_participation_goal p:integer l:"FSP 2015 Participation Goal (for Children 18 or Younger)" d:"This goal covers both FSP-eligible households and FSP-eligible individuals." t:dataTypeName=percent

metric m:wic_program_total_participation_children p:integer l:"WIC Program: Total Participation (Children)" t:dataTypeName=number

metric m:wic_program_total_eligible p:integer l:"WIC Program: Total Eligible" t:dataTypeName=number

metric m:wic_program_participation_rate p:float l:"WIC Program: Participation Rate" t:dataTypeName=percent

metric m:wic_program_percentage_of_usda_caseload_served p:float l:"WIC Program: Percentage of USDA Caseload Served" t:dataTypeName=percent

entity e:kazx-cq55 l:"Food Supplement Program (FSP) And Women Infants & Children (WIC) Programs, Participation" t:attribution="Department of Human Resources (DHR)" t:url=https://data.maryland.gov/api/views/kazx-cq55

property e:kazx-cq55 t:meta.view v:id=kazx-cq55 v:category="Health and Human Services" v:attributionLink=http://dhr.state.md.us v:averageRating=0 v:name="Food Supplement Program (FSP) And Women Infants & Children (WIC) Programs, Participation" v:attribution="Department of Human Resources (DHR)"

property e:kazx-cq55 t:meta.view.license v:name="Public Domain"

property e:kazx-cq55 t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:kazx-cq55 t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| month  | fsp_recipients_age_18_or_less | eligible_for_fsp_but_unreached_age_18_or_less | fsp_participation_rate_age_18_or_younger | fsp_households_w_child_recipients | unreached_fsp_households_w_child | fsp_participation_rate | fsp_2015_participation_goal | wic_program_total_participation_children | wic_program_total_eligible | wic_program_participation_rate | wic_program_percentage_of_usda_caseload_served | 
| ====== | ============================= | ============================================= | ======================================== | ================================= | ================================ | ====================== | =========================== | ======================================== | ========================== | ============================== | ============================================== | 
| Dec-09 | 242328                        | 115672                                        | 72.6                                     | 120696                            | 38304                            | 51.8                   | 100                         | 112746                                   | 139971                     | 80.5                           | 101.1                                          | 
| Jun-10 | 260100                        | 97900                                         | 72.7                                     | 130529                            | 28582                            | 77.9                   | 100                         | 111300                                   | 139971                     | 79.5                           | 100.3                                          | 
| Dec-10 | 285283                        | 72717                                         | 79.7                                     | 144566                            | 14545                            | 86                     | 100                         | 110866                                   | 139971                     | 79.2                           | 103.8                                          | 
| Jun-11 | 291200                        | 85800                                         | 77.2                                     | 149509                            | 18046                            | 88.5                   | 100                         | 112203                                   | 165683                     | 67.7                           | 105.4                                          | 
| Dec-11 | 299821                        | 77179                                         | 79.5                                     | 153292                            | 14263                            | 91.5                   | 100                         | 110313                                   | 165683                     | 66.6                           | 101.7                                          | 
| Jun-12 | 300962                        | 76038                                         | 79.8                                     | 154006                            | 13549                            | 91.9                   | 100                         | 110925                                   | 165683                     | 67                             | 102.3                                          | 
| Dec-12 | 315405                        | 61565                                         | 83.7                                     | 161700                            | 5855                             | 94.3                   | 100                         | 108234                                   | 165683                     | 65.3                           | 105.9                                          | 
| Jun-09 | 218566                        | 139434                                        | 65.4                                     | 107325                            | 51675                            | 46.1                   | 100                         | 111939                                   | 139971                     | 80                             | 107                                            | 
| Jun-13 | 324564                        | 28436                                         | 91.9                                     | 166895                            | 9605                             | 94.6                   | 100                         | 110242                                   | 165683                     |                                | 107.7                                          | 
| Dec-13 | 327404                        | 25696                                         | 92.7                                     | 168583                            | 7917                             | 95.5                   | 100                         | 105316                                   |                            |                                | 102.4                                          | 
```