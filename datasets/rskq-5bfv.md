# DCLA Program Funding for FY11

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dcla-program-funding-for-fy11-7e426) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rskq-5bfv) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rskq-5bfv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rskq-5bfv/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rskq-5bfv |
| Name | DCLA Program Funding for FY11 |
| Attribution | Department of Cultural Affairs (DCLA) |
| Category | Recreation |
| Tags | cultural, culture, program, fund, funding, project, art, percent, percent for art, artist, dcla, cultural affairs |
| Created | 2012-02-07T23:37:10Z |
| Publication Date | 2013-06-21T19:41:01Z |

## Description

Department of Cultural Affairs (DCLA) This data set is the Programs funding award amount for FY11

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | application       | Application #     | text      | text        |
| Yes      | series tag     | organization      | Organization      | text      | text        |
| Yes      | numeric metric | total_final_award | Total Final Award | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rskq-5bfv d:2012-02-07T15:37:42.000Z t:organization="3 Graces Theater Co., Inc." t:application=FY11-AN-005416 m:total_final_award=4920

series e:rskq-5bfv d:2012-02-07T15:37:42.000Z t:organization="3 Legged Dog" t:application=FY11-MY-005357 m:total_final_award=13985

series e:rskq-5bfv d:2012-02-07T15:37:42.000Z t:organization="42nd Street Workshop, Inc." t:application=FY11-AN-005112 m:total_final_award=4920
```

## Meta Commands

```ls
metric m:total_final_award p:integer l:"Total Final Award" t:dataTypeName=money

entity e:rskq-5bfv l:"DCLA Program Funding for FY11" t:attribution="Department of Cultural Affairs (DCLA)" t:url=https://data.cityofnewyork.us/api/views/rskq-5bfv

property e:rskq-5bfv t:meta.view v:id=rskq-5bfv v:category=Recreation v:averageRating=0 v:name="DCLA Program Funding for FY11" v:attribution="Department of Cultural Affairs (DCLA)"

property e:rskq-5bfv t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rskq-5bfv t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | application    | organization               | total_final_award | 
| =========== | ============== | ========================== | ================= | 
| 1328629062  | FY11-AN-005416 | 3 Graces Theater Co., Inc. | 4920              | 
| 1328629062  | FY11-MY-005357 | 3 Legged Dog               | 13985             | 
| 1328629062  | FY11-AN-005112 | 42nd Street Workshop, Inc. | 4920              | 
| 1328629062  | FY11-RN-006138 | 52nd Street Project, Inc.  | 53740             | 
| 1328629062  | FY11-RN-005943 | 7 Loaves, Inc.             | 14040             | 
| 1328629062  | FY11-AN-005505 | A Gathering of the Tribes  | 7510              | 
| 1328629062  | FY11-RN-006204 | Aaron Davis Hall, Inc.     | 127005            | 
| 1328629062  | FY11-AN-005734 | ABC No Rio                 | 4920              | 
| 1328629062  | FY11-RN-006032 | Abingdon Theatre Company   | 18730             | 
| 1328629062  | FY11-RN-006264 | Academy of American Poets  | 13990             | 
```