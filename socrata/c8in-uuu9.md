# Maryland Department of Agriculture Dashboard Measures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-department-of-agriculture-dashboard-measures) |
| Metadata | [Link](https://data.maryland.gov/api/views/c8in-uuu9) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/c8in-uuu9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/c8in-uuu9/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | c8in-uuu9 |
| Name | Maryland Department of Agriculture Dashboard Measures |
| Category | Agriculture |
| Tags | agriculture, environment, quality of life, gopi |
| Created | 2016-06-30T20:24:01Z |
| Publication Date | 2017-01-11T03:23:19Z |

## Description

Annual metrics and progress for Governor's Office of Performance Improvement, FY11-FY15

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type     | Render Type   |
| ======== | ============== | ===================================== | ===================================== | ============= | ============= |
| Yes      | series tag     | performance_metric                    | Reporting Frequency                   | text          | text          |
| Yes      | time           | date                                  | Date                                  | calendar_date | calendar_date |
| No       |                | fiscal_year                           | Fiscal Year                           | number        | text          |
| Yes      | numeric metric | manure_transported_tons               | Tons of Manure Transported            | number        | number        |
| Yes      | numeric metric | goal_tons_of_manure                   | Goal:Tons of Manure Transported       | number        | number        |
| Yes      | numeric metric | acres_of_protected_land               | Acres of Protected Land               | number        | number        |
| Yes      | numeric metric | acres_of_cover_crop_planted           | Acres of Cover Crop Planted           | number        | number        |
| Yes      | numeric metric | goal_for_cover_crops_planted_in_acres | Goal for Cover Crops Planted in Acres | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_year
```

## Data Commands

```ls
series e:c8in-uuu9 d:2012-06-30T00:00:00.000Z t:performance_metric=Annual m:acres_of_cover_crop_planted=429818 m:goal_tons_of_manure=37000 m:manure_transported_tons=35380 m:goal_for_cover_crops_planted_in_acres=355000 m:acres_of_protected_land=284469

series e:c8in-uuu9 d:2013-06-30T00:00:00.000Z t:performance_metric=Annual m:acres_of_cover_crop_planted=415437 m:goal_tons_of_manure=37000 m:manure_transported_tons=52481 m:goal_for_cover_crops_planted_in_acres=355000 m:acres_of_protected_land=286239

series e:c8in-uuu9 d:2014-06-30T00:00:00.000Z t:performance_metric=Annual m:acres_of_cover_crop_planted=423212 m:goal_tons_of_manure=44000 m:manure_transported_tons=118995 m:goal_for_cover_crops_planted_in_acres=386700 m:acres_of_protected_land=292356
```

## Meta Commands

```ls
metric m:manure_transported_tons p:integer l:"Tons of Manure Transported" t:dataTypeName=number

metric m:goal_tons_of_manure p:integer l:"Goal:Tons of Manure Transported" t:dataTypeName=number

metric m:acres_of_protected_land p:integer l:"Acres of Protected Land" t:dataTypeName=number

metric m:acres_of_cover_crop_planted p:integer l:"Acres of Cover Crop Planted" t:dataTypeName=number

metric m:goal_for_cover_crops_planted_in_acres p:integer l:"Goal for Cover Crops Planted in Acres" t:dataTypeName=number

entity e:c8in-uuu9 l:"Maryland Department of Agriculture Dashboard Measures" t:url=https://data.maryland.gov/api/views/c8in-uuu9

property e:c8in-uuu9 t:meta.view v:id=c8in-uuu9 v:category=Agriculture v:averageRating=0 v:name="Maryland Department of Agriculture Dashboard Measures"

property e:c8in-uuu9 t:meta.view.owner v:id=hcsr-zg76 v:screenName="Alisha Mulkey" v:displayName="Alisha Mulkey"

property e:c8in-uuu9 t:meta.view.tableauthor v:id=hcsr-zg76 v:screenName="Alisha Mulkey" v:roleName=editor v:displayName="Alisha Mulkey"
```

## Top Records

```ls
| performance_metric | date                | fiscal_year | manure_transported_tons | goal_tons_of_manure | acres_of_protected_land | acres_of_cover_crop_planted | goal_for_cover_crops_planted_in_acres | 
| ================== | =================== | =========== | ======================= | =================== | ======================= | =========================== | ===================================== | 
| Annual             | 2012-06-30T00:00:00 | 2012        | 35380                   | 37000               | 284469                  | 429818                      | 355000                                | 
| Annual             | 2013-06-30T00:00:00 | 2013        | 52481                   | 37000               | 286239                  | 415437                      | 355000                                | 
| Annual             | 2014-06-30T00:00:00 | 2014        | 118995                  | 44000               | 292356                  | 423212                      | 386700                                | 
| Annual             | 2015-06-30T00:00:00 | 2015        | 167237                  | 44000               | 296682                  | 475560                      | 386700                                | 
| Annual             | 2016-06-30T00:00:00 | 2016        | 213151                  | 51000               |                         | 501204                      | 417014                                | 
| Annual             | 2011-06-30T00:00:00 | 2011        | 61150                   |                     | 279777                  | 400331                      | 325000                                | 
```