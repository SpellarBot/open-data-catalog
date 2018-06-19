# Percent with unmet medical need, 5-year differences by age

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percent-with-unmet-medical-need-5-year-differences-by-age-09bac) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/fupa-q885) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/fupa-q885/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/fupa-q885/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | fupa-q885 |
| Name | Percent with unmet medical need, 5-year differences by age |
| Attribution | King County |
| Category | Health |
| Tags | king county, community health, data, indicators |
| Created | 2013-03-12T22:58:42Z |
| Publication Date | 2013-03-14T20:23:48Z |

## Description

Did not seek medical care because of the cost, demographic differences, five year averages, 2006-2010

## Columns

```ls
| Included | Schema Type    | Field Name  | Name                      | Data Type | Render Type |
| ======== | ============== | =========== | ========================= | ========= | =========== |
| No       | time           | :updated_at | updated_at                | meta_data | meta_data   |
| Yes      | series tag     | age         | Age                       | text      | text        |
| Yes      | numeric metric | percent     | Percent                   | percent   | percent     |
| Yes      | numeric metric | lower_ci    | Lower Confidence Interval | number    | number      |
| Yes      | numeric metric | upper_ci    | Upper Confidence Interval | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fupa-q885 d:2013-03-12T15:58:44.000Z t:age=18-24 m:upper_ci=19 m:percent=16 m:lower_ci=13

series e:fupa-q885 d:2013-03-12T15:58:44.000Z t:age=25-44 m:upper_ci=13 m:percent=12 m:lower_ci=11

series e:fupa-q885 d:2013-03-12T15:58:44.000Z t:age=45-64 m:upper_ci=9 m:percent=9 m:lower_ci=8
```

## Meta Commands

```ls
metric m:percent p:integer l:Percent t:dataTypeName=percent

metric m:lower_ci p:integer l:"Lower Confidence Interval" t:dataTypeName=number

metric m:upper_ci p:integer l:"Upper Confidence Interval" t:dataTypeName=number

entity e:fupa-q885 l:"Percent with unmet medical need, 5-year differences by age" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/fupa-q885

property e:fupa-q885 t:meta.view v:id=fupa-q885 v:category=Health v:attributionLink=http://www.kingcounty.gov/health v:averageRating=0 v:name="Percent with unmet medical need, 5-year differences by age" v:attribution="King County"

property e:fupa-q885 t:meta.view.license v:name="Public Domain"

property e:fupa-q885 t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:fupa-q885 t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| :updated_at | age   | percent | lower_ci | upper_ci | 
| =========== | ===== | ======= | ======== | ======== | 
| 1363103924  | 18-24 | 16      | 13       | 19       | 
| 1363103924  | 25-44 | 12      | 11       | 13       | 
| 1363103924  | 45-64 | 9       | 8        | 9        | 
| 1363103924  | 65+   | 3       | 2        | 3        | 
```