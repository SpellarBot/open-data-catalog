# 2013 Proposed Budget, General Fund Expenditures By Appropriation Unit

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-proposed-budget-general-fund-expenditures-by-appropriation-unit-26b97) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/yj3s-xdaz) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/yj3s-xdaz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/yj3s-xdaz/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | yj3s-xdaz |
| Name | 2013 Proposed Budget, General Fund Expenditures By Appropriation Unit |
| Attribution | King County Executive |
| Category | Budget |
| Tags | budget, 2013, budget2013 |
| Created | 2012-09-18T20:12:50Z |
| Publication Date | 2012-09-23T05:58:04Z |

## Description

King County budget proposed September 2012 by Executive for 2013, General Fund Expenditures By Appropriation Unit. The General Fund is an annual budget for the 2013/2014 Biennium. See http://www.kingcounty.gov/budget for more.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name               | Data Type | Render Type |
| ======== | ============== | ============== | ================== | ========= | =========== |
| Yes      | series tag     | section        | Strategic Area     | text      | text        |
| Yes      | series tag     | strategic_plan | Appropriation Unit | text      | text        |
| No       |                | _1             | 2012 Adopted       | money     | money       |
| No       |                | _2             | 2013 Proposed      | money     | money       |
| No       |                | _3             | Amount of change   | money     | money       |
| Yes      | numeric metric | percent_change | Percent Change     | percent   | percent     |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _1,_2,_3
```

## Data Commands

```ls
series e:yj3s-xdaz d:2013-01-01T00:00:00.000Z t:strategic_plan="Adult And Juvenile Detention" t:section="Justice And Safety" m:percent_change=-2

series e:yj3s-xdaz d:2013-01-01T00:00:00.000Z t:strategic_plan="District Court" t:section="Justice And Safety" m:percent_change=9

series e:yj3s-xdaz d:2013-01-01T00:00:00.000Z t:strategic_plan="Drug Enforcement Forfeits" t:section="Justice And Safety" m:percent_change=-1
```

## Meta Commands

```ls
metric m:percent_change p:integer l:"Percent Change" t:dataTypeName=percent

entity e:yj3s-xdaz l:"2013 Proposed Budget, General Fund Expenditures By Appropriation Unit" t:attribution="King County Executive" t:url=https://data.kingcounty.gov/api/views/yj3s-xdaz

property e:yj3s-xdaz t:meta.view v:id=yj3s-xdaz v:category=Budget v:attributionLink=http://www.kingcounty.gov/budget v:averageRating=0 v:name="2013 Proposed Budget, General Fund Expenditures By Appropriation Unit" v:attribution="King County Executive"

property e:yj3s-xdaz t:meta.view.license v:name="Public Domain"

property e:yj3s-xdaz t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:yj3s-xdaz t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| section            | strategic_plan                 | _1        | _2          | _3          | percent_change | 
| ================== | ============================== | ========= | =========== | =========== | ============== | 
| Justice And Safety | Adult And Juvenile Detention   | 130212329 | 128214175.5 | -1998153.52 | -2             | 
| Justice And Safety | District Court                 | 27461186  | 29930274.63 | 2469088.62  | 9              | 
| Justice And Safety | Drug Enforcement Forfeits      | 1138037   | 1132194.45  | -5842.54    | -1             | 
| Justice And Safety | Inmate Welfare Admin           | 1168877   | 1551808.14  | 382931.14   | 33             | 
| Justice And Safety | Jail Health Services           | 25409575  | 25147640.7  | -261934.30  | -1             | 
| Justice And Safety | Judicial Administration        | 19061595  | 19750105.45 | 688510.44   | 4              | 
| Justice And Safety | Juvenile Inmate Welfare        | 0         | 7500        | 7500        |                | 
| Justice And Safety | Office Of Emergency Management | 1933695   | 2306342.28  | 372647.28   | 19             | 
| Justice And Safety | Pao Antiprofiteering           | 119897    | 119897      | 0           | 0              | 
| Justice And Safety | Prosecuting Attorney           | 58718143  | 61088578.87 | 2370435.87  | 4              | 
```