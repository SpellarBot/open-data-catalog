# Percent of Connecticut Adults, High School Students, and Middle School Students Currently Smoking Cigarettes by Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percent-of-connecticut-adults-high-school-students-and-middle-school-students-currently-sm) |
| Metadata | [Link](https://data.ct.gov/api/views/9veb-bt9u) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/9veb-bt9u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/9veb-bt9u/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 9veb-bt9u |
| Name | Percent of Connecticut Adults, High School Students, and Middle School Students Currently Smoking Cigarettes by Year |
| Attribution | CT DPH: Community Health and Prevention Section |
| Category | Health and Human Services |
| Tags | smoking, cigarette, behavioral risk factor surveillance system, connecticut school health survey, youth tobacco survey |
| Created | 2014-04-08T15:13:14Z |
| Publication Date | 2014-04-08T15:16:38Z |

## Description

This tables provides the prevalence rates for currently smoking cigarettes among Connecticut adults (18+y), high school students, and middle school students by year.

## Columns

```ls
| Included | Schema Type    | Field Name                                                     | Name                                                           | Data Type | Render Type |
| ======== | ============== | ============================================================== | ============================================================== | ========= | =========== |
| Yes      | time           | year                                                           | Year                                                           | number    | text        |
| Yes      | numeric metric | percent_of_high_school_students_currently_smoking_cigarettes   | Percent of High School Students Currently Smoking Cigarettes   | percent   | percent     |
| Yes      | numeric metric | percent_of_adults_currently_smoking_cigarettes                 | Percent of Adults Currently Smoking Cigarettes                 | percent   | percent     |
| Yes      | numeric metric | percent_of_middle_school_students_currently_smoking_cigarettes | Percent of Middle School Students Currently Smoking Cigarettes | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9veb-bt9u d:1990-01-01T00:00:00.000Z m:percent_of_adults_currently_smoking_cigarettes=22.1

series e:9veb-bt9u d:1991-01-01T00:00:00.000Z m:percent_of_adults_currently_smoking_cigarettes=22.4

series e:9veb-bt9u d:1992-01-01T00:00:00.000Z m:percent_of_adults_currently_smoking_cigarettes=22.2
```

## Meta Commands

```ls
metric m:percent_of_high_school_students_currently_smoking_cigarettes p:float l:"Percent of High School Students Currently Smoking Cigarettes" t:dataTypeName=percent

metric m:percent_of_adults_currently_smoking_cigarettes p:float l:"Percent of Adults Currently Smoking Cigarettes" t:dataTypeName=percent

metric m:percent_of_middle_school_students_currently_smoking_cigarettes p:float l:"Percent of Middle School Students Currently Smoking Cigarettes" t:dataTypeName=percent

entity e:9veb-bt9u l:"Percent of Connecticut Adults, High School Students, and Middle School Students Currently Smoking Cigarettes by Year" t:attribution="CT DPH: Community Health and Prevention Section" t:url=https://data.ct.gov/api/views/9veb-bt9u

property e:9veb-bt9u t:meta.view d:2017-09-25T07:27:46.611Z v:averageRating=0 v:name="Percent of Connecticut Adults, High School Students, and Middle School Students Currently Smoking Cigarettes by Year" v:attribution="CT DPH: Community Health and Prevention Section" v:attributionLink=http://www.ct.gov/dph/tobacco v:id=9veb-bt9u v:category="Health and Human Services"

property e:9veb-bt9u t:meta.view.license d:2017-09-25T07:27:46.611Z v:name="Public Domain"

property e:9veb-bt9u t:meta.view.owner d:2017-09-25T07:27:46.611Z v:displayName="Gary Archambault" v:lastNotificationSeenAt=1496862788 v:profileImageUrlLarge=/api/users/dby8-627v/profile_images/LARGE v:profileImageUrlSmall=/api/users/dby8-627v/profile_images/TINY v:id=dby8-627v v:screenName="Gary Archambault" v:profileImageUrlMedium=/api/users/dby8-627v/profile_images/THUMB

property e:9veb-bt9u t:meta.view.tableauthor d:2017-09-25T07:27:46.611Z v:displayName="Gary Archambault" v:lastNotificationSeenAt=1496862788 v:profileImageUrlLarge=/api/users/dby8-627v/profile_images/LARGE v:roleName=editor v:profileImageUrlSmall=/api/users/dby8-627v/profile_images/TINY v:id=dby8-627v v:screenName="Gary Archambault" v:profileImageUrlMedium=/api/users/dby8-627v/profile_images/THUMB
```

## Top Records

```ls
| year | percent_of_high_school_students_currently_smoking_cigarettes | percent_of_adults_currently_smoking_cigarettes | percent_of_middle_school_students_currently_smoking_cigarettes | 
| ==== | ============================================================ | ============================================== | ============================================================== | 
| 1990 |                                                              | 22.1                                           |                                                                | 
| 1991 |                                                              | 22.4                                           |                                                                | 
| 1992 |                                                              | 22.2                                           |                                                                | 
| 1993 |                                                              | 20.7                                           |                                                                | 
| 1994 |                                                              | 19.9                                           |                                                                | 
| 1995 |                                                              | 20.8                                           |                                                                | 
| 1996 |                                                              | 21.8                                           |                                                                | 
| 1997 |                                                              | 21.6                                           |                                                                | 
| 1998 |                                                              | 20.9                                           |                                                                | 
| 1999 |                                                              | 22.8                                           |                                                                | 
```