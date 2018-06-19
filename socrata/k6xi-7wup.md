# Percent with unmet medical need, 5-year differences by region

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percent-with-unmet-medical-need-5-year-differences-by-region-6387c) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/k6xi-7wup) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/k6xi-7wup/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/k6xi-7wup/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | k6xi-7wup |
| Name | Percent with unmet medical need, 5-year differences by region |
| Attribution | Seattle-King County Public Health |
| Category | Health |
| Tags | king county, community health, data, indicators |
| Created | 2013-03-13T00:13:12Z |
| Publication Date | 2013-03-14T20:21:19Z |

## Description

Did not seek medical care because of the cost, demographic differences, five year averages, 2006-2010

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| No       | time           | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag     | region                    | Region                    | text      | text        |
| Yes      | numeric metric | percent                   | Percent                   | percent   | percent     |
| Yes      | numeric metric | lower_confidence_interval | Lower Confidence Interval | number    | number      |
| Yes      | numeric metric | upper_confidence_interval | Upper Confidence Interval | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:k6xi-7wup d:2013-03-12T17:13:13.000Z t:region=East m:percent=6 m:upper_confidence_interval=7 m:lower_confidence_interval=5

series e:k6xi-7wup d:2013-03-12T17:13:13.000Z t:region=South m:percent=12 m:upper_confidence_interval=13 m:lower_confidence_interval=11

series e:k6xi-7wup d:2013-03-12T17:13:13.000Z t:region=Seattle m:percent=9 m:upper_confidence_interval=10 m:lower_confidence_interval=8
```

## Meta Commands

```ls
metric m:percent p:integer l:Percent t:dataTypeName=percent

metric m:lower_confidence_interval p:integer l:"Lower Confidence Interval" t:dataTypeName=number

metric m:upper_confidence_interval p:integer l:"Upper Confidence Interval" t:dataTypeName=number

entity e:k6xi-7wup l:"Percent with unmet medical need, 5-year differences by region" t:attribution="Seattle-King County Public Health" t:url=https://data.kingcounty.gov/api/views/k6xi-7wup

property e:k6xi-7wup t:meta.view v:id=k6xi-7wup v:category=Health v:attributionLink=http://www.kingcounty.gov/health v:averageRating=0 v:name="Percent with unmet medical need, 5-year differences by region" v:attribution="Seattle-King County Public Health"

property e:k6xi-7wup t:meta.view.license v:name="Public Domain"

property e:k6xi-7wup t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:k6xi-7wup t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| :updated_at | region  | percent | lower_confidence_interval | upper_confidence_interval | 
| =========== | ======= | ======= | ========================= | ========================= | 
| 1363108393  | East    | 6       | 5                         | 7                         | 
| 1363108393  | South   | 12      | 11                        | 13                        | 
| 1363108393  | Seattle | 9       | 8                         | 10                        | 
| 1363108393  | North   | 8       | 7                         | 10                        | 
```