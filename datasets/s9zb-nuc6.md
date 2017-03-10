# Employee Overtime and Supplemental Earnings 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/employee-overtime-and-supplemental-earnings-2013-449d3) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/s9zb-nuc6) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/s9zb-nuc6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/s9zb-nuc6/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | s9zb-nuc6 |
| Name | Employee Overtime and Supplemental Earnings 2013 |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | budget, overtime, supplemental earnings |
| Created | 2013-07-15T04:44:33Z |
| Publication Date | 2014-02-04T00:10:56Z |
| Rows Updated | 2014-02-04T00:10:00Z |

## Description

Employee overtime and supplemental earnings by month and year-to-date. Data Owner: Budget & Management. Time Period: January 2013 to present. Frequency: Data is updated monthly

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | department_name | DEPARTMENT NAME | text      | text        |
| Yes      | series tag     | employee_name   | EMPLOYEE NAME   | text      | text        |
| Yes      | series tag     | title           | TITLE           | text      | text        |
| Yes      | numeric metric | jan_2013        | JAN 2013        | money     | money       |
| Yes      | numeric metric | feb_2013        | FEB 2013        | money     | money       |
| Yes      | numeric metric | mar_2013        | MAR 2013        | money     | money       |
| Yes      | numeric metric | apr_2013        | APR 2013        | money     | money       |
| Yes      | numeric metric | may_2013        | MAY 2013        | money     | money       |
| Yes      | numeric metric | jun_2013        | JUN 2013        | money     | money       |
| Yes      | numeric metric | jul_2013        | JUL 2013        | money     | money       |
| Yes      | numeric metric | aug_2013        | AUG 2013        | money     | money       |
| Yes      | numeric metric | sep_2013        | SEP 2013        | money     | money       |
| Yes      | numeric metric | oct_2013        | OCT 2013        | money     | money       |
| Yes      | numeric metric | nov_2013        | NOV 2013        | money     | money       |
| Yes      | numeric metric | dec_2013        | DEC 2013        | money     | money       |
| Yes      | numeric metric | grand_total     | 2013 TOTAL      | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:s9zb-nuc6 d:2014-02-03T16:08:25.000Z t:title="ANIMAL CARE AIDE I" t:department_name="Animal Care and Control" t:employee_name="AGUILAR, ELMA M" m:jul_2013=864.58 m:jan_2013=887.34 m:nov_2013=500.55 m:may_2013=182.02 m:dec_2013=333.62 m:apr_2013=500.55 m:aug_2013=1274.13 m:feb_2013=-22.75 m:oct_2013=0 m:mar_2013=318.53 m:grand_total=5763.83 m:jun_2013=182.02 m:sep_2013=743.24

series e:s9zb-nuc6 d:2014-02-03T16:08:25.000Z t:title="ANIMAL CONTROL OFFICER" t:department_name="Animal Care and Control" t:employee_name="AGUILAR, RICARDO L" m:jul_2013=1612.71 m:jan_2013=1531.96 m:nov_2013=2724.77 m:may_2013=0 m:dec_2013=1887.64 m:apr_2013=960.23 m:aug_2013=2220.03 m:feb_2013=1780.95 m:oct_2013=2043.57 m:mar_2013=590.91 m:grand_total=17535.87 m:jun_2013=689.4 m:sep_2013=1493.7

series e:s9zb-nuc6 d:2014-02-03T16:08:25.000Z t:title="ANIMAL CONTROL OFFICER" t:department_name="Animal Care and Control" t:employee_name="ALLEN, TIMOTHY M" m:jul_2013=189.14 m:jan_2013=0 m:nov_2013=189.14 m:may_2013=0 m:dec_2013=189.14 m:apr_2013=0 m:aug_2013=0 m:feb_2013=189.14 m:oct_2013=0 m:mar_2013=378.27 m:grand_total=1323.97 m:jun_2013=0 m:sep_2013=189.14
```

## Meta Commands

```ls
entity e:s9zb-nuc6 l:"Employee Overtime and Supplemental Earnings 2013" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/s9zb-nuc6

property e:s9zb-nuc6 t:meta.view d:2017-03-10T14:39:36.945Z v:id=s9zb-nuc6 v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Employee Overtime and Supplemental Earnings 2013" v:attribution="City of Chicago"

property e:s9zb-nuc6 t:meta.view.owner d:2017-03-10T14:39:36.945Z v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:displayName="Tom Schenk Jr"

property e:s9zb-nuc6 t:meta.view.tableauthor d:2017-03-10T14:39:36.945Z v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:displayName="Tom Schenk Jr"
```