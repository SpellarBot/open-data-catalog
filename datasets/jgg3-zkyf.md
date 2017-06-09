# Percent with unmet medical need, 5-year differences by ethnicity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percent-with-unmet-medical-need-5-year-differences-by-ethnicity-aa173) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/jgg3-zkyf) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/jgg3-zkyf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/jgg3-zkyf/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | jgg3-zkyf |
| Name | Percent with unmet medical need, 5-year differences by ethnicity |
| Attribution | King County Public Health |
| Category | Health |
| Tags | king county, community health, data, indicators |
| Created | 2013-03-12T23:47:05Z |
| Publication Date | 2013-03-14T20:22:05Z |

## Description

Did not seek medical care because of the cost, demographic differences, five year averages, 2006-2010

## Columns

```ls
| Included | Schema Type    | Field Name  | Name                      | Data Type | Render Type |
| ======== | ============== | =========== | ========================= | ========= | =========== |
| No       | time           | :updated_at | updated_at                | meta_data | meta_data   |
| Yes      | series tag     | ethnicity   | Ethnicity                 | text      | text        |
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
series e:jgg3-zkyf d:2013-03-12T16:47:07.000Z t:ethnicity="African American" m:upper_ci=26 m:lower_ci=17 m:percent=21

series e:jgg3-zkyf d:2013-03-12T16:47:07.000Z t:ethnicity="American Indian/AN" m:upper_ci=27 m:lower_ci=11 m:percent=18

series e:jgg3-zkyf d:2013-03-12T16:47:07.000Z t:ethnicity=Asian/PI m:upper_ci=10 m:lower_ci=6 m:percent=8
```

## Meta Commands

```ls
metric m:percent p:integer l:Percent t:dataTypeName=percent

metric m:lower_ci p:integer l:"Lower Confidence Interval" t:dataTypeName=number

metric m:upper_ci p:integer l:"Upper Confidence Interval" t:dataTypeName=number

entity e:jgg3-zkyf l:"Percent with unmet medical need, 5-year differences by ethnicity" t:attribution="King County Public Health" t:url=https://data.kingcounty.gov/api/views/jgg3-zkyf

property e:jgg3-zkyf t:meta.view d:2017-06-09T13:56:49.317Z v:id=jgg3-zkyf v:category=Health v:attributionLink=http://www.kingcounty.gov/health v:averageRating=0 v:name="Percent with unmet medical need, 5-year differences by ethnicity" v:attribution="King County Public Health"

property e:jgg3-zkyf t:meta.view.license d:2017-06-09T13:56:49.317Z v:name="Public Domain"

property e:jgg3-zkyf t:meta.view.owner d:2017-06-09T13:56:49.317Z v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:jgg3-zkyf t:meta.view.tableauthor d:2017-06-09T13:56:49.317Z v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| :updated_at | ethnicity          | percent | lower_ci | upper_ci | 
| =========== | ================== | ======= | ======== | ======== | 
| 1363106827  | African American   | 21      | 17       | 26       | 
| 1363106827  | American Indian/AN | 18      | 11       | 27       | 
| 1363106827  | Asian/PI           | 8       | 6        | 10       | 
| 1363106827  | Hispanic/Latino    | 23      | 19       | 26       | 
| 1363106827  | White              | 9       | 8        | 9        | 
```