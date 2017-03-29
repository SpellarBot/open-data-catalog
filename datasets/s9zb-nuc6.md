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

## Description

Employee overtime and supplemental earnings by month and year-to-date. Data Owner: Budget & Management. Time Period: January 2013 to present. Frequency: Data is updated monthly

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
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
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:s9zb-nuc6 d:2013-01-01T00:00:00.000Z t:title="ANIMAL CARE AIDE I" t:department_name="Animal Care and Control" t:employee_name="AGUILAR, ELMA M" m:jul_2013=864.58 m:jan_2013=887.34 m:nov_2013=500.55 m:may_2013=182.02 m:dec_2013=333.62 m:apr_2013=500.55 m:aug_2013=1274.13 m:feb_2013=-22.75 m:oct_2013=0 m:mar_2013=318.53 m:grand_total=5763.83 m:sep_2013=743.24 m:jun_2013=182.02

series e:s9zb-nuc6 d:2013-01-01T00:00:00.000Z t:title="ANIMAL CONTROL OFFICER" t:department_name="Animal Care and Control" t:employee_name="AGUILAR, RICARDO L" m:jul_2013=1612.71 m:jan_2013=1531.96 m:nov_2013=2724.77 m:may_2013=0 m:dec_2013=1887.64 m:apr_2013=960.23 m:aug_2013=2220.03 m:feb_2013=1780.95 m:oct_2013=2043.57 m:mar_2013=590.91 m:grand_total=17535.87 m:sep_2013=1493.7 m:jun_2013=689.4

series e:s9zb-nuc6 d:2013-01-01T00:00:00.000Z t:title="ANIMAL CONTROL OFFICER" t:department_name="Animal Care and Control" t:employee_name="ALLEN, TIMOTHY M" m:jul_2013=189.14 m:jan_2013=0 m:nov_2013=189.14 m:may_2013=0 m:dec_2013=189.14 m:apr_2013=0 m:aug_2013=0 m:feb_2013=189.14 m:oct_2013=0 m:mar_2013=378.27 m:grand_total=1323.97 m:sep_2013=189.14 m:jun_2013=0
```

## Meta Commands

```ls
metric m:jan_2013 p:double l:"JAN 2013" t:dataTypeName=money

metric m:feb_2013 p:double l:"FEB 2013" t:dataTypeName=money

metric m:mar_2013 p:double l:"MAR 2013" t:dataTypeName=money

metric m:apr_2013 p:double l:"APR 2013" t:dataTypeName=money

metric m:may_2013 p:double l:"MAY 2013" t:dataTypeName=money

metric m:jun_2013 p:double l:"JUN 2013" t:dataTypeName=money

metric m:jul_2013 p:double l:"JUL 2013" t:dataTypeName=money

metric m:aug_2013 p:double l:"AUG 2013" t:dataTypeName=money

metric m:sep_2013 p:double l:"SEP 2013" t:dataTypeName=money

metric m:oct_2013 p:double l:"OCT 2013" t:dataTypeName=money

metric m:nov_2013 p:double l:"NOV 2013" t:dataTypeName=money

metric m:dec_2013 p:double l:"DEC 2013" t:dataTypeName=money

metric m:grand_total p:double l:"2013 TOTAL" t:dataTypeName=money

entity e:s9zb-nuc6 l:"Employee Overtime and Supplemental Earnings 2013" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/s9zb-nuc6

property e:s9zb-nuc6 t:meta.view v:id=s9zb-nuc6 v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Employee Overtime and Supplemental Earnings 2013" v:attribution="City of Chicago"

property e:s9zb-nuc6 t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:displayName="Tom Schenk Jr"

property e:s9zb-nuc6 t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| department_name         | employee_name           | title                             | jan_2013 | feb_2013 | mar_2013 | apr_2013 | may_2013 | jun_2013 | jul_2013 | aug_2013 | sep_2013 | oct_2013 | nov_2013 | dec_2013 | grand_total | 
| ======================= | ======================= | ================================= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | =========== | 
| Animal Care and Control | AGUILAR, ELMA M         | ANIMAL CARE AIDE I                | 887.34   | -22.75   | 318.53   | 500.55   | 182.02   | 182.02   | 864.58   | 1274.13  | 743.24   | 0        | 500.55   | 333.62   | 5763.83     | 
| Animal Care and Control | AGUILAR, RICARDO L      | ANIMAL CONTROL OFFICER            | 1531.96  | 1780.95  | 590.91   | 960.23   | 0        | 689.4    | 1612.71  | 2220.03  | 1493.7   | 2043.57  | 2724.77  | 1887.64  | 17535.87    | 
| Animal Care and Control | ALLEN, TIMOTHY M        | ANIMAL CONTROL OFFICER            | 0        | 189.14   | 378.27   | 0        | 0        | 0        | 189.14   | 0        | 189.14   | 0        | 189.14   | 189.14   | 1323.97     | 
| Animal Care and Control | AYALA, ARTHUR           | ANIMAL CONTROL OFFICER            | 375.47   | 0        | 189.13   | 0        | 0        | 0        | 189.14   | 972.71   | 0        | 0        | 0        | 999.73   | 2726.18     | 
| Animal Care and Control | BATINICH, JACLYN M      | VETERINARY ASST                   | 849.94   | 0        | 0        | 333.62   | 190.63   | 1139.87  | 190.64   | 285.96   | 190.64   | 0        | 381.28   | 873.77   | 4436.35     | 
| Animal Care and Control | BRADFORD, MONA MICHELLE | ANIMAL CARE AIDE II               | 1166.31  | 178.52   | 374.88   | 0        | 142.81   | 839.02   | 598.02   | 0        | 0        | 1262.07  | 0        | 0        | 4561.63     | 
| Animal Care and Control | BRADY, DIANNE           | ANIMAL CONTROL INSPECTOR          | 1392.26  | 837.42   | 628.06   | 280.38   | 0        | 0        | 314.03   | 426.18   | 179.45   | 2138.41  | 2534.68  | 1516.89  | 10247.76    | 
| Animal Care and Control | CALIN, MICHELLE         | ANIMAL CONTROL OFFICER            | 3756.27  | 0        | 1065.46  | 493.48   | 897.24   | 3566.51  | 1555.21  | 2684.22  | 2489.81  | 1749.61  | 1136.5   | 360.47   | 19754.78    | 
| Animal Care and Control | CHRISTENSEN, ALTHEA     | ANIMAL CARE AIDE II               | 0        | 0        | 0        | 375.01   | 0        | 0        | 124.96   | 365.96   | 214.22   | 321.33   | 565.31   | 529.59   | 2496.38     | 
| Animal Care and Control | CRAYTON, MARSTINE L     | SUPVSR OF ANIMAL CONTROL OFFICERS | 3983.97  | 1621.4   | 1204.47  | 548.18   | 324.28   | 872.46   | 980.55   | 741.21   | 1335.71  | 2293.11  | 1814.41  | 324.28   | 16044.03    | 
```