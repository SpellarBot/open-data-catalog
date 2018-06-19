# DCLA Programs Funding

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dcla-programs-funding-b2c87) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/y6fv-k6p7) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/y6fv-k6p7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/y6fv-k6p7/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | y6fv-k6p7 |
| Name | DCLA Programs Funding |
| Attribution | Department of Cultural Affairs (DCLA) |
| Category | Recreation |
| Tags | dcla, cultural, culture, program, fund, funding, project, art, percent, percent for art, artist, cultural affairs |
| Created | 2013-03-01T20:17:27Z |
| Publication Date | 2017-04-06T21:56:17Z |

## Description

This data set is the Programs funding award amount by fiscal year

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | application       | Application #     | text      | text        |
| Yes      | series tag     | organization      | Organization      | text      | text        |
| Yes      | numeric metric | total_final_award | Total Final Award | money     | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:y6fv-k6p7 d:2013-03-07T12:35:54.000Z t:organization="3 Graces Theater Co., Inc." t:application=FY12-AN-009139 m:total_final_award=5325

series e:y6fv-k6p7 d:2013-03-07T12:35:54.000Z t:organization="3 Legged Dog" t:application=FY12-RN-009814 m:total_final_award=15975

series e:y6fv-k6p7 d:2013-03-07T12:35:54.000Z t:organization="52nd Street Project, Inc." t:application=FY12-RN-009843 m:total_final_award=60750
```

## Meta Commands

```ls
metric m:total_final_award p:long l:"Total Final Award" d:"Total CDF Award Amount" t:dataTypeName=money

entity e:y6fv-k6p7 l:"DCLA Programs Funding" t:attribution="Department of Cultural Affairs (DCLA)" t:url=https://data.cityofnewyork.us/api/views/y6fv-k6p7

property e:y6fv-k6p7 t:meta.view v:id=y6fv-k6p7 v:category=Recreation v:averageRating=0 v:name="DCLA Programs Funding" v:attribution="Department of Cultural Affairs (DCLA)"

property e:y6fv-k6p7 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:y6fv-k6p7 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | application    | organization               | total_final_award | 
| =========== | ============== | ========================== | ================= | 
| 1362659754  | FY12-AN-009139 | 3 Graces Theater Co., Inc. | 5,325             | 
| 1362659754  | FY12-RN-009814 | 3 Legged Dog               | 15,975            | 
| 1362659754  | FY12-RN-009843 | 52nd Street Project, Inc.  | 60,750            | 
| 1362659754  | FY12-MY-006965 | 7 Loaves, Inc.             | 18,975            | 
| 1362659754  | FY12-RN-009783 | Aaron Davis Hall, Inc.     | 145,625           | 
| 1362659754  | FY12-MY-007865 | ABC No Rio                 | 5,325             | 
| 1362659754  | FY12-MY-006656 | Abingdon Theatre Company   | 20,975            | 
| 1362659754  | FY12-MY-008120 | Academy of American Poets  | 15,975            | 
| 1362659754  | FY12-MY-007322 | Actors Company Theatre     | 15,975            | 
| 1362659754  | FY12-RN-009866 | Actors' Fund of America    | 15,975            | 
```