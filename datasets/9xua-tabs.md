# Employee Overtime and Supplemental Earnings 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/employee-overtime-and-supplemental-earnings-2014-706fa) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/9xua-tabs) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/9xua-tabs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/9xua-tabs/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 9xua-tabs |
| Name | Employee Overtime and Supplemental Earnings 2014 |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | budget, overtime, supplemental earnings |
| Created | 2014-07-04T04:33:56Z |
| Publication Date | 2015-12-04T17:57:17Z |

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
| Yes      | numeric metric | febrary         | FEBRARY         | money     | money       |
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
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9xua-tabs d:2014-01-01T00:00:00.000Z t:title="ADMINISTRATIVE ASST III" t:department_name="Administrative Hearings" t:employee_name="JACKSON, ALLADDIN D" m:total=78.45 m:december=0 m:may=0 m:november=0 m:march=0 m:april=0 m:june=0 m:january=78.45 m:febrary=0 m:august=0 m:july=0 m:october=0 m:september=0

series e:9xua-tabs d:2014-01-01T00:00:00.000Z t:title="ANIMAL CARE AIDE II" t:department_name="Animal Care and Control" t:employee_name="HOLLOWAY, EFREM J" m:total=1661.14 m:december=0 m:may=0 m:november=316.58 m:march=574.48 m:april=0 m:june=0 m:january=287.24 m:febrary=287.24 m:august=0 m:july=0 m:october=195.6 m:september=0

series e:9xua-tabs d:2014-01-01T00:00:00.000Z t:title="ANIMAL CONTROL INSPECTOR" t:department_name="Animal Care and Control" t:employee_name="EDGECOMBE, CHERYL K" m:total=8610.25 m:december=954.29 m:may=967.73 m:november=443.54 m:march=849.43 m:april=352.82 m:june=614.91 m:january=461.43 m:febrary=461.43 m:august=863.56 m:july=927.42 m:october=514.11 m:september=1199.58
```

## Meta Commands

```ls
metric m:january p:double l:JANUARY t:dataTypeName=money

metric m:febrary p:double l:FEBRARY t:dataTypeName=money

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

entity e:9xua-tabs l:"Employee Overtime and Supplemental Earnings 2014" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/9xua-tabs

property e:9xua-tabs t:meta.view v:id=9xua-tabs v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Employee Overtime and Supplemental Earnings 2014" v:attribution="City of Chicago"

property e:9xua-tabs t:meta.view.license v:name="Public Domain"

property e:9xua-tabs t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:9xua-tabs t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| department_name         | employee_name              | title                       | january | febrary | march  | april  | may    | june   | july    | august  | september | october | november | december | total   | 
| ======================= | ========================== | =========================== | ======= | ======= | ====== | ====== | ====== | ====== | ======= | ======= | ========= | ======= | ======== | ======== | ======= | 
| Administrative Hearings | JACKSON, ALLADDIN D        | ADMINISTRATIVE ASST III     | 78.45   | 0       | 0      | 0      | 0      | 0      | 0       | 0       | 0         | 0       | 0        | 0        | 78.45   | 
| Animal Care and Control | HOLLOWAY, EFREM J          | ANIMAL CARE AIDE II         | 287.24  | 287.24  | 574.48 | 0      | 0      | 0      | 0       | 0       | 0         | 195.6   | 316.58   | 0        | 1661.14 | 
| Animal Care and Control | EDGECOMBE, CHERYL K        | ANIMAL CONTROL INSPECTOR    | 461.43  | 461.43  | 849.43 | 352.82 | 967.73 | 614.91 | 927.42  | 863.56  | 1199.58   | 514.11  | 443.54   | 954.29   | 8610.25 | 
| Animal Care and Control | WASHINGTON, MONTESE DAJUAN | VETERINARY ASST             | 473.24  | 301.14  | 602.29 | 172.09 | 172.09 | 150.58 | 172.09  | 659.67  | 358.52    | 591.56  | 492.5    | 664.13   | 4809.92 | 
| Animal Care and Control | ZAVALA, VICTOR             | ANIMAL CONTROL OFFICER      | 0       | 0       | 0      | 0      | 912.17 | 881.57 | 477.52  | 404.05  | 700.84    | 0       | 0        | 0        | 3376.15 | 
| Animal Care and Control | KELLER, AUDREY ANN         | VETERINARIAN                | 1712.59 | 0       | 0      | 0      | 778.45 | 569.22 | 1138.43 | 0       | 0         | 365.92  | 0        | 0        | 4564.61 | 
| Animal Care and Control | HAMILTON, ARTHUR           | ANIMAL CARE AIDE II         | 523.52  | 0       | 523.52 | 0      | 679.71 | 0      | 0       | 0       | 0         | 0       | 0        | 0        | 1726.75 | 
| Animal Care and Control | HAMILTON, ARTHUR           | SUPVSR OF ANIMAL CARE AIDES | 0       | 0       | 0      | 0      | 0      | 274.5  | 1509.49 | 2865.03 | 1227.86   | 180.24  | 328.22   | 328.22   | 6713.57 | 
| Animal Care and Control | MCDONALD, KOLLEEN DENISE   | SUPVSR OF ANIMAL CARE AIDES | 0       | 0       | 0      | 0      | 0      | 0      | 0       | 0       | 0         | 0       | 1260.10  | 343.66   | 1603.76 | 
| Animal Care and Control | SAUNDERS, JASMINE M        | ANIMAL CARE AIDE II         | 0       | 0       | 645.04 | 551.55 | 383.3  | 640.66 | 1748.29 | 862.71  | 895.39    | 1372.49 | 272.04   | 523.68   | 7895.17 | 
```