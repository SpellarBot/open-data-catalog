# Employee Overtime and Supplemental Earnings 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/employee-overtime-and-supplemental-earnings-2015) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/efd5-hyfi) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/efd5-hyfi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/efd5-hyfi/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | efd5-hyfi |
| Name | Employee Overtime and Supplemental Earnings 2015 |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | budget |
| Created | 2015-07-03T01:02:40Z |
| Publication Date | 2016-03-25T22:28:45Z |

## Description

Employee overtime and supplemental earnings by month and year-to-date.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | department_name | DEPARTMENT NAME | text      | text        |
| Yes      | series tag     | employee_name   | EMPLOYEE NAME   | text      | text        |
| Yes      | series tag     | title           | TITLE           | text      | text        |
| Yes      | numeric metric | january         | JANUARY         | money     | money       |
| Yes      | numeric metric | february        | FEBRUARY        | money     | money       |
| Yes      | numeric metric | march           | MARCH           | money     | money       |
| Yes      | numeric metric | april           | APRIL           | money     | money       |
| Yes      | numeric metric | may             | MAY             | money     | money       |
| Yes      | numeric metric | june            | JUNE            | money     | money       |
| Yes      | numeric metric | july            | JULY            | money     | money       |
| Yes      | numeric metric | august          | AUGUST          | money     | money       |
| Yes      | numeric metric | september       | SEPTEMBER       | money     | money       |
| Yes      | numeric metric | october         | OCTOBER         | money     | money       |
| Yes      | numeric metric | november        | NOVEMBER        | money     | money       |
| Yes      | numeric metric | december        | DECEMBER        | money     | money       |
| Yes      | numeric metric | total           | TOTAL           | money     | money       |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:efd5-hyfi d:2015-01-01T00:00:00.000Z t:title="Animal Care Aide I" t:department_name="Animal Care and Control" t:employee_name="Aguilar, Elma M" m:total=6670.1 m:december=388.59 m:november=388.59 m:february=997.63 m:june=439.68 m:january=1642.95 m:august=388.59 m:july=388.59 m:october=1147.27 m:september=888.21

series e:efd5-hyfi d:2015-01-01T00:00:00.000Z t:title="Animal Control Officer" t:department_name="Animal Care and Control" t:employee_name="Aguilar, Ricardo L" m:total=25432.49 m:december=2190.49 m:may=2186.62 m:november=2101.44 m:march=740.64 m:april=171.93 m:february=1190.3 m:june=1274.06 m:january=3012.89 m:august=5614.23 m:july=1313.39 m:october=2657.96 m:september=2978.54

series e:efd5-hyfi d:2015-01-01T00:00:00.000Z t:title="Animal Control Officer" t:department_name="Animal Care and Control" t:employee_name="Allen, Timothy M" m:total=1944.66 m:december=195.82 m:november=195.82 m:march=193.88 m:february=387.76 m:january=579.74 m:october=195.82 m:september=195.82
```

## Meta Commands

```ls
metric m:january p:double l:JANUARY t:dataTypeName=money

metric m:february p:double l:FEBRUARY t:dataTypeName=money

metric m:march p:double l:MARCH t:dataTypeName=money

metric m:april p:double l:APRIL t:dataTypeName=money

metric m:may p:double l:MAY t:dataTypeName=money

metric m:june p:double l:JUNE t:dataTypeName=money

metric m:july p:double l:JULY t:dataTypeName=money

metric m:august p:double l:AUGUST t:dataTypeName=money

metric m:september p:double l:SEPTEMBER t:dataTypeName=money

metric m:october p:double l:OCTOBER t:dataTypeName=money

metric m:november p:double l:NOVEMBER t:dataTypeName=money

metric m:december p:double l:DECEMBER t:dataTypeName=money

metric m:total p:double l:TOTAL t:dataTypeName=money

entity e:efd5-hyfi l:"Employee Overtime and Supplemental Earnings 2015" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/efd5-hyfi

property e:efd5-hyfi t:meta.view v:id=efd5-hyfi v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Employee Overtime and Supplemental Earnings 2015" v:attribution="City of Chicago"

property e:efd5-hyfi t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:efd5-hyfi t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| department_name         | employee_name           | title                    | january | february | march   | april  | may     | june    | july    | august  | september | october | november | december | total    | 
| ======================= | ======================= | ======================== | ======= | ======== | ======= | ====== | ======= | ======= | ======= | ======= | ========= | ======= | ======== | ======== | ======== | 
| Animal Care and Control | Aguilar, Elma M         | Animal Care Aide I       | 1642.95 | 997.63   |         |        |         | 439.68  | 388.59  | 388.59  | 888.21    | 1147.27 | 388.59   | 388.59   | 6670.10  | 
| Animal Care and Control | Aguilar, Ricardo L      | Animal Control Officer   | 3012.89 | 1190.30  | 740.64  | 171.93 | 2186.62 | 1274.06 | 1313.39 | 5614.23 | 2978.54   | 2657.96 | 2101.44  | 2190.49  | 25432.49 | 
| Animal Care and Control | Allen, Timothy M        | Animal Control Officer   | 579.74  | 387.76   | 193.88  |        |         |         |         |         | 195.82    | 195.82  | 195.82   | 195.82   | 1944.66  | 
| Animal Care and Control | Allison, John L         | Animal Control Officer   | 1129.37 | 337.36   | 168.68  | 156.63 |         | 168.68  | 304.24  | 795.09  | 2008.01   | 1419.80 | 1277.82  | 669.34   | 8435.02  | 
| Animal Care and Control | Ayala, Arthur           | Animal Control Officer   | 383.95  | 387.76   |         | 387.76 |         | 387.76  | 391.64  | 783.28  |           | 685.37  | 195.82   |          | 3603.34  | 
| Animal Care and Control | Batinich, Jaclyn M      | Veterinarian Assistant   | 918.87  | 577.57   | 420.06  | 420.06 | 210.03  | 787.60  | 1210.87 | 905.94  | 813.14    | 1202.04 | 1714.67  | 371.22   | 9552.07  | 
| Animal Care and Control | Bradford, Mona Michelle | Animal Care Aide II      | 476.07  | 494.54   | 590.71  |        | 2294.14 |         | 596.66  |         | 291.39    | 985.19  | 291.39   | 208.14   | 6228.23  | 
| Animal Care and Control | Brady, Dianne           | Animal Control Inspector | 2117.00 | 706.84   | 504.89  | 138.84 | 479.65  | 353.42  |         | 1189.85 | 1801.77   | 905.13  | 1121.86  | 896.63   | 10215.88 | 
| Animal Care and Control | Caballero, Jorge        | Animal Control Officer   | 234.21  | 384.77   | 895.01  | 724.92 | 1095.75 | 585.52  | 903.37  | 2141.34 | 677.46    | 481.80  | 306.60   | 1226.42  | 9657.17  | 
| Animal Care and Control | Calin, Michelle         | Animal Control Officer   | 2518.39 | 1253.05  | 2072.38 | 771.12 | 1325.35 | 1783.20 | 1709.94 | 4462.26 | 2287.92   | 389.43  | 2190.57  | 2774.73  | 23538.34 | 
```