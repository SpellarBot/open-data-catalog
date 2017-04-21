# TPW_PerformanceMeasures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tpw-performancemeasures) |
| Metadata | [Link](https://data.srcity.org/api/views/jwpb-rhnm) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/jwpb-rhnm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/jwpb-rhnm/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | jwpb-rhnm |
| Name | TPW_PerformanceMeasures |
| Category | Transportation |
| Created | 2017-02-03T22:57:57Z |
| Publication Date | 2017-02-03T22:59:17Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type     | Render Type   |
| ======== | ============== | =========== | =========== | ============= | ============= |
| No       |                | year        | year        | number        | number        |
| Yes      | time           | date        | date        | calendar_date | calendar_date |
| Yes      | series tag     | division    | division    | text          | text          |
| Yes      | series tag     | measure     | measure     | text          | text          |
| Yes      | series tag     | type        | type        | text          | text          |
| Yes      | numeric metric | number      | number      | number        | number        |
| Yes      | numeric metric | percent     | percent     | number        | number        |
| Yes      | numeric metric | dollar      | dollar      | number        | number        |
| Yes      | series tag     | time        | time        | text          | text          |
| Yes      | numeric metric | decimaltime | decimaltime | number        | number        |
| Yes      | series tag     | goal        | goal        | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:jwpb-rhnm d:2009-12-31T00:00:00.000Z t:division="Pavement Condition Index" t:measure="Average PCI" m:number=64

series e:jwpb-rhnm d:2012-12-31T00:00:00.000Z t:division="Pavement Condition Index" t:measure="Average PCI" m:number=62

series e:jwpb-rhnm d:2014-06-30T00:00:00.000Z t:time=000429 t:division="Time and Delay" t:measure="Mendocino Ave: College Ave to Steele Lane" m:decimaltime=4.48333333333333
```

## Meta Commands

```ls
metric m:number p:integer l:number t:dataTypeName=number

metric m:percent p:long l:percent t:dataTypeName=number

metric m:dollar p:long l:dollar t:dataTypeName=number

metric m:decimaltime p:double l:decimaltime t:dataTypeName=number

entity e:jwpb-rhnm l:TPW_PerformanceMeasures t:url=https://data.srcity.org/api/views/jwpb-rhnm

property e:jwpb-rhnm t:meta.view v:id=jwpb-rhnm v:category=Transportation v:averageRating=0 v:name=TPW_PerformanceMeasures

property e:jwpb-rhnm t:meta.view.owner v:id=4jau-mr7g v:profileImageUrlMedium=/api/users/4jau-mr7g/profile_images/THUMB v:profileImageUrlLarge=/api/users/4jau-mr7g/profile_images/LARGE v:screenName="Tickner, Brian" v:profileImageUrlSmall=/api/users/4jau-mr7g/profile_images/TINY v:lastNotificationSeenAt=1492537611 v:displayName="Tickner, Brian"

property e:jwpb-rhnm t:meta.view.tableauthor v:id=4jau-mr7g v:profileImageUrlMedium=/api/users/4jau-mr7g/profile_images/THUMB v:profileImageUrlLarge=/api/users/4jau-mr7g/profile_images/LARGE v:screenName="Tickner, Brian" v:profileImageUrlSmall=/api/users/4jau-mr7g/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492537611 v:displayName="Tickner, Brian"
```

## Top Records

```ls
| year | date                | division                 | measure                                              | type | number | percent | dollar | time   | decimaltime      | goal | 
| ==== | =================== | ======================== | ==================================================== | ==== | ====== | ======= | ====== | ====== | ================ | ==== | 
| 2009 | 2009-12-31T00:00:00 | Pavement Condition Index | Average PCI                                          |      | 64     |         |        |        |                  |      | 
| 2012 | 2012-12-31T00:00:00 | Pavement Condition Index | Average PCI                                          |      | 62     |         |        |        |                  |      | 
| 2014 | 2014-06-30T00:00:00 | Time and Delay           | Mendocino Ave: College Ave to Steele Lane            |      |        |         |        | 000429 | 4.48333333333333 |      | 
| 2015 | 2015-06-30T00:00:00 | Time and Delay           | Stony Point Road: West College Avenue to Hearn Ave   |      |        |         |        | 000634 | 6.56666666666667 |      | 
| 2015 | 2015-12-31T00:00:00 | Pavement Condition Index | Average PCI                                          |      | 60     |         |        |        |                  |      | 
| 2011 | 2011-12-31T00:00:00 | Pavement Condition Index | Average PCI                                          |      | 63     |         |        |        |                  |      | 
| 2008 | 2008-12-31T00:00:00 | Pavement Condition Index | Average PCI                                          |      | 65     |         |        |        |                  |      | 
| 2015 | 2015-06-30T00:00:00 | Time and Delay           | College/West College: Cleveland Avenue to 4th Street |      |        |         |        | 000313 | 3.21666666666667 |      | 
| 2014 | 2014-12-31T00:00:00 | Pavement Condition Index | Average PCI                                          |      | 61     |         |        |        |                  |      | 
| 2016 | 2016-06-30T00:00:00 | Time and Delay           | Mendocino Ave: College Ave to Steele Lane            |      |        |         |        | 000340 | 3.66666666666667 |      | 
```