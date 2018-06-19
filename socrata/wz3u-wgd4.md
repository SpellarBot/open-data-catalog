# 2014 Elections - Expenditures by Authorized Use

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-elections-expenditures-by-authorized-use-d89cf) |
| Metadata | [Link](https://data.hawaii.gov/api/views/wz3u-wgd4) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/wz3u-wgd4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/wz3u-wgd4/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | wz3u-wgd4 |
| Name | 2014 Elections - Expenditures by Authorized Use |
| Category | Community |
| Tags | campaign spending commission |
| Created | 2015-01-13T18:03:59Z |
| Publication Date | 2015-01-13T18:45:12Z |

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| Yes      | series tag     | authorized_use                   | Authorized Use                   | text      | text        |
| Yes      | numeric metric | count                            | Count                            | number    | number      |
| Yes      | numeric metric | percentage_of_total_count        | Percentage of Total Count        | percent   | percent     |
| Yes      | numeric metric | total_expenditures               | Total Expenditures               | money     | money       |
| Yes      | numeric metric | percentage_of_total_expenditures | Percentage of Total Expenditures | percent   | percent     |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wz3u-wgd4 d:2014-01-01T00:00:00.000Z t:authorized_use="Charitable Donations" m:count=146 m:total_expenditures=27191.08 m:percentage_of_total_count=0.67 m:percentage_of_total_expenditures=0.17

series e:wz3u-wgd4 d:2014-01-01T00:00:00.000Z t:authorized_use="Directly Related to Candidate's Campaign" m:count=18578 m:total_expenditures=14201534 m:percentage_of_total_count=85.15 m:percentage_of_total_expenditures=90

series e:wz3u-wgd4 d:2014-01-01T00:00:00.000Z t:authorized_use="Full-Time Student Scholarship Awards" m:count=4 m:total_expenditures=3000 m:percentage_of_total_count=0.02 m:percentage_of_total_expenditures=0.02
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

metric m:percentage_of_total_count p:float l:"Percentage of Total Count" t:dataTypeName=percent

metric m:total_expenditures p:double l:"Total Expenditures" t:dataTypeName=money

metric m:percentage_of_total_expenditures p:double l:"Percentage of Total Expenditures" t:dataTypeName=percent

entity e:wz3u-wgd4 l:"2014 Elections - Expenditures by Authorized Use" t:url=https://data.hawaii.gov/api/views/wz3u-wgd4

property e:wz3u-wgd4 t:meta.view v:id=wz3u-wgd4 v:category=Community v:averageRating=0 v:name="2014 Elections - Expenditures by Authorized Use"

property e:wz3u-wgd4 t:meta.view.license v:name="Public Domain"

property e:wz3u-wgd4 t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:wz3u-wgd4 t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| authorized_use                                    | count | percentage_of_total_count | total_expenditures | percentage_of_total_expenditures | 
| ================================================= | ===== | ========================= | ================== | ================================ | 
| Charitable Donations                              | 146   | 0.67                      | 27191.08           | 0.17                             | 
| Directly Related to Candidate's Campaign          | 18578 | 85.15                     | 14201534           | 90                               | 
| Full-Time Student Scholarship Awards              | 4     | 0.02                      | 3000               | 0.02                             | 
| Mixed Benefit Expenses                            | 40    | 0.18                      | 6266.24            | 0.04                             | 
| Ordinary & Nec Expenses (*ELECTED OFFICIALS ONLY) | 440   | 2.02                      | 100849.98          | 0.64                             | 
| Political Party Contributions                     | 72    | 0.33                      | 73825.9            | 0.47                             | 
| Public School or Public Library Donations         | 58    | 0.27                      | 16832.62           | 0.11                             | 
| Two (2) Fundraiser Tickets                        | 197   | 0.9                       | 86172.98           | 0.55                             | 
| Blank (Authorized Use field added 7/3/14)         | 2284  | 10.47                     | 1246113.15         | 7.91                             | 
```