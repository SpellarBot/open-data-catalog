# 2013 Proposed Budget, Budgets By Services and Sources

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-proposed-budget-budgets-by-services-and-sources-a4047) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/irnq-vig3) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/irnq-vig3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/irnq-vig3/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | irnq-vig3 |
| Name | 2013 Proposed Budget, Budgets By Services and Sources |
| Attribution | King County Executive |
| Category | Budget |
| Tags | budget, 2013, budget2013 |
| Created | 2012-09-14T17:19:44Z |
| Publication Date | 2012-09-23T01:32:23Z |

## Description

King County budget proposed September 2012 by Executive for 2013, broken down by service and source. See http://www.kingcounty.gov/budget for more.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | fund                   | Fund                   | text      | text        |
| Yes      | series tag     | services_by_fund       | Services by fund       | text      | text        |
| Yes      | numeric metric | revenues_fy13          | Revenues FY13          | money     | money       |
| Yes      | numeric metric | revenues_fy14          | Revenues FY14          | money     | money       |
| Yes      | numeric metric | revenues_fy13_fy14     | Revenues FY13/FY14     | money     | money       |
| Yes      | numeric metric | budget_1               | Expenditures FY13      | money     | money       |
| Yes      | numeric metric | budget_2               | Expenditures FY14      | money     | money       |
| Yes      | numeric metric | expenditures_fy13_fy14 | Expenditures FY13/FY14 | money     | money       |
| Yes      | numeric metric | variance               | Variance               | money     | money       |
| Yes      | numeric metric | percent_variance       | Percent variance       | percent   | percent     |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:irnq-vig3 d:2013-01-01T00:00:00.000Z t:services_by_fund="General Fund" t:fund=000000010 m:budget_1=682426119 m:revenues_fy13_fy14=675635747 m:budget_2=0 m:variance=-6790373 m:percent_variance=-1 m:revenues_fy13=675635747 m:revenues_fy14=0 m:expenditures_fy13_fy14=682426119

series e:irnq-vig3 d:2013-01-01T00:00:00.000Z t:services_by_fund="Inmate Welfare Fund" t:fund=000000016 m:budget_1=1559308 m:revenues_fy13_fy14=1019266 m:budget_2=0 m:variance=-540042 m:percent_variance=-53 m:revenues_fy13=1019266 m:revenues_fy14=0 m:expenditures_fy13_fy14=1559308

series e:irnq-vig3 d:2013-01-01T00:00:00.000Z t:services_by_fund="County Road Fund" t:fund=000001030 m:budget_1=97946669 m:revenues_fy13_fy14=189040965 m:budget_2=90987829 m:variance=106468 m:percent_variance=0 m:revenues_fy13=96444540 m:revenues_fy14=92596425 m:expenditures_fy13_fy14=188934497
```

## Meta Commands

```ls
metric m:revenues_fy13 p:integer l:"Revenues FY13" t:dataTypeName=money

metric m:revenues_fy14 p:integer l:"Revenues FY14" t:dataTypeName=money

metric m:revenues_fy13_fy14 p:integer l:"Revenues FY13/FY14" t:dataTypeName=money

metric m:budget_1 p:integer l:"Expenditures FY13" t:dataTypeName=money

metric m:budget_2 p:integer l:"Expenditures FY14" t:dataTypeName=money

metric m:expenditures_fy13_fy14 p:integer l:"Expenditures FY13/FY14" t:dataTypeName=money

metric m:variance p:integer l:Variance t:dataTypeName=money

metric m:percent_variance p:integer l:"Percent variance" t:dataTypeName=percent

entity e:irnq-vig3 l:"2013 Proposed Budget, Budgets By Services and Sources" t:attribution="King County Executive" t:url=https://data.kingcounty.gov/api/views/irnq-vig3

property e:irnq-vig3 t:meta.view v:id=irnq-vig3 v:category=Budget v:attributionLink=http://www.kingcounty.gov/budget v:averageRating=0 v:name="2013 Proposed Budget, Budgets By Services and Sources" v:attribution="King County Executive"

property e:irnq-vig3 t:meta.view.license v:name="Public Domain"

property e:irnq-vig3 t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:irnq-vig3 t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| fund      | services_by_fund               | revenues_fy13 | revenues_fy14 | revenues_fy13_fy14 | budget_1  | budget_2  | expenditures_fy13_fy14 | variance  | percent_variance | 
| ========= | ============================== | ============= | ============= | ================== | ========= | ========= | ====================== | ========= | ================ | 
| 000000010 | General Fund                   | 675635747     | 0             | 675635747          | 682426119 | 0         | 682426119              | -6790373  | -1               | 
| 000000016 | Inmate Welfare Fund            | 1019266       | 0             | 1019266            | 1559308   | 0         | 1559308                | -540042   | -53              | 
| 000001030 | County Road Fund               | 96444540      | 92596425      | 189040965          | 97946669  | 90987829  | 188934497              | 106468    | 0                | 
| 000001040 | Sw Post Closure Lf Maint       | 47614         | 10899         | 58513              | 2025668   | 2039766   | 4065434                | -4006921  | -6848            | 
| 000001060 | Veterans Relief                | 2847477       | 2895258       | 5742735            | 3309139   | 3389810   | 6698949                | -956214   | -17              | 
| 000001070 | Developmental Disability       | 30221681      | 30311969      | 60533650           | 31037603  | 30876679  | 61914282               | -1380632  | -2               | 
| 000001090 | Recorder'S O & M Fund          | 1502891       | 1496474       | 2999365            | 1720771   | 1797544   | 3518315                | -518950   | -17              | 
| 000001110 | Emergency Telephone E911       | 24760378      | 25455294      | 50215672           | 28165719  | 25709170  | 53874889               | -3659217  | -7               | 
| 000001120 | Mental Health                  | 170556898     | 170530468     | 341087366          | 170601086 | 171246954 | 341848040              | -760674   | 0                | 
| 000001190 | Mental Illness Drug Dependency | 46166827      | 55875828      | 102042655          | 57504628  | 57948282  | 115452910              | -13410255 | -13              | 
```