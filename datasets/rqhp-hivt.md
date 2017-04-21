# Scorecard Ratings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/scorecard-ratings-04f07) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rqhp-hivt) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rqhp-hivt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rqhp-hivt/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rqhp-hivt |
| Name | Scorecard Ratings |
| Attribution | Office of the Mayor (OTM) |
| Category | City Government |
| Tags | scorecard ratings, operations, street, sidewalk, clean, cleanliness, office of the mayor (otm) |
| Created | 2014-03-06T16:22:26Z |
| Publication Date | 2014-03-06T16:23:50Z |

## Description

Street and sidewalk cleanliness ratings.

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                    | Data Type | Render Type |
| ======== | ============== | ==================================== | ======================================= | ========= | =========== |
| No       | time           | :updated_at                          | updated_at                              | meta_data | meta_data   |
| Yes      | series tag     | borough                              | Borough                                 | text      | text        |
| Yes      | series tag     | zone                                 | Zone                                    | text      | text        |
| Yes      | series tag     | district                             | District                                | text      | text        |
| Yes      | series tag     | cleaning_section                     | Cleaning Section                        | text      | text        |
| Yes      | series tag     | acceptable_streets_feb_2014          | Acceptable Streets % (Feb. 2014)        | text      | number      |
| Yes      | numeric metric | previous_month_1                     | Previous Month                          | number    | number      |
| Yes      | numeric metric | same_month_prev_year_1               | Same Month Prev. Year                   | number    | number      |
| Yes      | series tag     | filthy_streets_feb_2014              | Filthy Streets % (Feb. 2014)            | text      | number      |
| Yes      | numeric metric | previous_month_2                     | Previous Month                          | number    | number      |
| Yes      | numeric metric | same_month_prev_year_2               | Same Month Prev. Year                   | number    | number      |
| Yes      | series tag     | avergage_street_cleanliness_feb_2014 | Avergage Street Cleanliness (Feb. 2014) | text      | number      |
| Yes      | numeric metric | previous_month_3                     | Previous Month                          | number    | number      |
| Yes      | numeric metric | same_month_prev_year_3               | Same Month Prev. Year                   | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rqhp-hivt d:2014-03-06T08:22:29.000Z t:avergage_street_cleanliness_feb_2014=1.21 t:acceptable_streets_feb_2014=100 t:cleaning_section=MN011 t:borough=Manhattan t:district=MN01 t:filthy_streets_feb_2014=0 t:zone=Manhattan m:same_month_prev_year_1=96.5 m:same_month_prev_year_2=0 m:same_month_prev_year_3=1.22 m:previous_month_3=1.26 m:previous_month_1=96.1 m:previous_month_2=2.6

series e:rqhp-hivt d:2014-03-06T08:22:29.000Z t:avergage_street_cleanliness_feb_2014=1.21 t:acceptable_streets_feb_2014=100 t:cleaning_section=MN013 t:borough=Manhattan t:district=MN01 t:filthy_streets_feb_2014=0 t:zone=Manhattan m:same_month_prev_year_1=87.8 m:same_month_prev_year_2=0 m:same_month_prev_year_3=1.26 m:previous_month_3=1.3 m:previous_month_1=86.7 m:previous_month_2=0

series e:rqhp-hivt d:2014-03-06T08:22:29.000Z t:avergage_street_cleanliness_feb_2014=1.2 t:acceptable_streets_feb_2014=100 t:cleaning_section=MN021 t:borough=Manhattan t:district=MN02 t:filthy_streets_feb_2014=0 t:zone=Manhattan m:same_month_prev_year_1=100 m:same_month_prev_year_2=0 m:same_month_prev_year_3=1.22 m:previous_month_3=1.31 m:previous_month_1=88.6 m:previous_month_2=0
```

## Meta Commands

```ls
metric m:previous_month_1 p:double l:"Previous Month" t:dataTypeName=number

metric m:same_month_prev_year_1 p:double l:"Same Month Prev. Year" t:dataTypeName=number

metric m:previous_month_2 p:double l:"Previous Month" t:dataTypeName=number

metric m:same_month_prev_year_2 p:float l:"Same Month Prev. Year" t:dataTypeName=number

metric m:previous_month_3 p:float l:"Previous Month" t:dataTypeName=number

metric m:same_month_prev_year_3 p:float l:"Same Month Prev. Year" t:dataTypeName=number

entity e:rqhp-hivt l:"Scorecard Ratings" t:attribution="Office of the Mayor (OTM)" t:url=https://data.cityofnewyork.us/api/views/rqhp-hivt

property e:rqhp-hivt t:meta.view v:id=rqhp-hivt v:category="City Government" v:averageRating=0 v:name="Scorecard Ratings" v:attribution="Office of the Mayor (OTM)"

property e:rqhp-hivt t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rqhp-hivt t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | borough   | zone      | district | cleaning_section | acceptable_streets_feb_2014 | previous_month_1 | same_month_prev_year_1 | filthy_streets_feb_2014 | previous_month_2 | same_month_prev_year_2 | avergage_street_cleanliness_feb_2014 | previous_month_3 | same_month_prev_year_3 | 
| =========== | ========= | ========= | ======== | ================ | =========================== | ================ | ====================== | ======================= | ================ | ====================== | ==================================== | ================ | ====================== | 
| 1394094149  | Manhattan | Manhattan | MN01     | MN011            | 100                         | 96.1             | 96.5                   | 0                       | 2.6              | 0                      | 1.21                                 | 1.26             | 1.22                   | 
| 1394094149  | Manhattan | Manhattan | MN01     | MN013            | 100                         | 86.7             | 87.8                   | 0                       | 0                | 0                      | 1.21                                 | 1.3              | 1.26                   | 
| 1394094149  | Manhattan | Manhattan | MN02     | MN021            | 100                         | 88.6             | 100                    | 0                       | 0                | 0                      | 1.2                                  | 1.31             | 1.22                   | 
| 1394094149  | Manhattan | Manhattan | MN02     | MN022            | 95.7                        | 86.7             | 98                     | 0                       | 0                | 0                      | 1.21                                 | 1.28             | 1.23                   | 
| 1394094149  | Manhattan | Manhattan | MN02     | MN023            | 100                         | 93.5             | 94                     | 0                       | 0                | 0                      | 1.22                                 | 1.26             | 1.24                   | 
| 1394094149  | Manhattan | Manhattan | MN03     | MN031            | 87.2                        | 91.4             | 90.9                   | 0                       | 0                | 0                      | 1.28                                 | 1.28             | 1.28                   | 
| 1394094149  | Manhattan | Manhattan | MN03     | MN032            | 90.9                        | 91.1             | 92                     | 0                       | 0                | 0                      | 1.28                                 | 1.28             | 1.25                   | 
| 1394094149  | Manhattan | Manhattan | MN03     | MN033            | 84.4                        | 88.9             | 88.6                   | 0                       | 0                | 0                      | 1.29                                 | 1.3              | 1.29                   | 
| 1394094149  | Manhattan | Manhattan | MN03     | MN034            | 80.5                        | 91.9             | 93.9                   | 2.4                     | 0                | 0                      | 1.33                                 | 1.28             | 1.26                   | 
| 1394094149  | Manhattan | Manhattan | MN04     | MN041            | 92                          | 95.8             | 100                    | 0                       | 0                | 0                      | 1.28                                 | 1.25             | 1.25                   | 
```