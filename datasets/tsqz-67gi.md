# Employee Overtime and Supplemental Earnings 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/employee-overtime-and-supplemental-earnings-2016) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/tsqz-67gi) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/tsqz-67gi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/tsqz-67gi/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | tsqz-67gi |
| Name | Employee Overtime and Supplemental Earnings 2016 |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | budget |
| Created | 2016-07-02T02:25:41Z |
| Publication Date | 2017-03-18T02:26:31Z |

## Description

Employee overtime and supplemental earnings by month and year-to-date

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | department_name | DEPARTMENT NAME | text      | text        |
| Yes      | series tag     | name            | NAME            | text      | text        |
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
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tsqz-67gi d:2016-01-01T00:00:00.000Z t:title="Animal Control Officer" t:name="Loza, Ernesto" t:department_name="Animal Care and Control" m:total=16364.37 m:december=1291.2 m:may=633.4 m:november=2669.2 m:march=234.59 m:april=1008.75 m:february=1391.92 m:june=1345 m:january=2406.4 m:august=1333.28 m:july=1548.31 m:october=1298.08 m:september=1204.24

series e:tsqz-67gi d:2016-01-01T00:00:00.000Z t:title="Animal Care Aide I" t:name="Aguilar, Elma M" t:department_name="Animal Care and Control" m:total=3629.67 m:december=396.42 m:may=186.89 m:november=226.52 m:march=616.74 m:april=560.67 m:february=532.63 m:june=0 m:january=392.47 m:august=141.58 m:july=0 m:october=198.21 m:september=377.54

series e:tsqz-67gi d:2016-01-01T00:00:00.000Z t:title="Animal Control Officer" t:name="Williams Jr, Eli" t:department_name="Animal Care and Control" m:total=1293.28 m:december=519.36 m:may=0 m:november=259.68 m:march=0 m:april=0 m:february=257.12 m:june=0 m:january=257.12 m:august=0 m:july=0 m:october=0 m:september=0
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

entity e:tsqz-67gi l:"Employee Overtime and Supplemental Earnings 2016" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/tsqz-67gi

property e:tsqz-67gi t:meta.view v:id=tsqz-67gi v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Employee Overtime and Supplemental Earnings 2016" v:attribution="City of Chicago"

property e:tsqz-67gi t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:tsqz-67gi t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| department_name         | name                | title                    | january | february | march  | april   | may     | june    | july    | august  | september | october | november | december | total    | 
| ======================= | =================== | ======================== | ======= | ======== | ====== | ======= | ======= | ======= | ======= | ======= | ========= | ======= | ======== | ======== | ======== | 
| Animal Care and Control | Loza, Ernesto       | Animal Control Officer   | 2406.40 | 1391.92  | 234.59 | 1008.75 | 633.40  | 1345    | 1548.31 | 1333.28 | 1204.24   | 1298.08 | 2669.20  | 1291.20  | 16364.37 | 
| Animal Care and Control | Aguilar, Elma M     | Animal Care Aide I       | 392.47  | 532.63   | 616.74 | 560.67  | 186.89  | 0       | 0       | 141.58  | 377.54    | 198.21  | 226.52   | 396.42   | 3629.67  | 
| Animal Care and Control | Williams Jr, Eli    | Animal Control Officer   | 257.12  | 257.12   | 0      | 0       | 0       | 0       | 0       | 0       | 0         | 0       | 259.68   | 519.36   | 1293.28  | 
| Animal Care and Control | Howard, Maryann J   | Animal Control Inspector | 340.75  | 729.26   | 0      | 0       | 0       | 0       | 0       | 0       | 0         | 0       | 0        | 208.09   | 1278.10  | 
| Animal Care and Control | Eldridge, Michael E | Animal Control Officer   | 0       | 0        | 0      | 0       | 0       | 0       | 0       | 0       | 0         | 0       | 0        | 1342.53  | 1342.53  | 
| Animal Care and Control | Allison, John L     | Animal Control Officer   | 0       | 344.15   | 344.15 | 344.15  | 1765.79 | 704.69  | 1857.32 | 0       | 1549.52   | 884.21  | 861.80   | 2106.89  | 10762.67 | 
| Animal Care and Control | Allen, Timothy M    | Animal Control Officer   | 197.79  | 197.79   | 197.79 | 0       | 0       | 197.79  | 197.79  | 0       | 197.79    | 197.79  | 0        | 199.77   | 1584.30  | 
| Animal Care and Control | Tuider, Colleen T   | Dispatch Clerk           | 307.94  | 307.94   | 307.94 | 0       | 571.89  | 351.93  | 819.06  | 925.56  | 310.98    | 1362.41 | 488.69   | 1451.26  | 7205.60  | 
| Animal Care and Control | Hernandez, Miguel   | Animal Control Officer   | 653.61  | 328.43   | 0      | 0       | 437.91  | 0       | 0       | 0       | 0         | 0       | 247.67   | 173.80   | 1841.42  | 
| Animal Care and Control | Brady, Dianne       | Animal Control Inspector | 360.55  | 502.19   | 360.55 | 373.43  | 965.77  | 1068.78 | 746.86  | 824.13  | 862.75    | 476.44  | 1218.18  | 572.24   | 8331.87  | 
```