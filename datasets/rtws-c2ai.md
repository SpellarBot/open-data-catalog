# NYC DOE 2015-2016 Final Class Size Report Pupil-to-Teacher Ratio (PTR)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-doe-2015-2016-final-class-size-report-pupil-to-teacher-ratio-ptr) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rtws-c2ai) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rtws-c2ai/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rtws-c2ai/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rtws-c2ai |
| Name | NYC DOE 2015-2016 Final Class Size Report Pupil-to-Teacher Ratio (PTR) |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Created | 2016-03-11T20:30:05Z |
| Publication Date | 2016-03-11T20:44:35Z |

## Description

New York City Department of Education 2015-16 Final Class Size Report School Pupil-to-Teacher Ratio (PTR) General Education (Gen Ed) and Integrated Co-Teaching (ICT)

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | dbn                        | DBN                        | text      | text        |
| Yes      | series tag     | school_name                | School Name                | text      | text        |
| Yes      | numeric metric | school_pupil_teacher_ratio | School Pupil-Teacher Ratio | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rtws-c2ai d:2015-01-01T00:00:00.000Z t:school_name="P.S. 001 THE BERGEN" t:dbn=15K001 m:school_pupil_teacher_ratio=13.4

series e:rtws-c2ai d:2015-01-01T00:00:00.000Z t:school_name="BRONX LITTLE SCHOOL" t:dbn=12X691 m:school_pupil_teacher_ratio=12

series e:rtws-c2ai d:2015-01-01T00:00:00.000Z t:school_name="LINDEN TREE ELEMENTARY SCHOOL" t:dbn=11X567 m:school_pupil_teacher_ratio=16.9
```

## Meta Commands

```ls
metric m:school_pupil_teacher_ratio p:float l:"School Pupil-Teacher Ratio" t:dataTypeName=number

entity e:rtws-c2ai l:"NYC DOE 2015-2016 Final Class Size Report Pupil-to-Teacher Ratio (PTR)" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/rtws-c2ai

property e:rtws-c2ai t:meta.view v:id=rtws-c2ai v:category=Education v:averageRating=0 v:name="NYC DOE 2015-2016 Final Class Size Report Pupil-to-Teacher Ratio (PTR)" v:attribution="Department of Education (DOE)"

property e:rtws-c2ai t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rtws-c2ai t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| dbn    | school_name                     | school_pupil_teacher_ratio | 
| ====== | =============================== | ========================== | 
| 15K001 | P.S. 001 THE BERGEN             | 13.4                       | 
| 12X691 | BRONX LITTLE SCHOOL             | 12                         | 
| 11X567 | LINDEN TREE ELEMENTARY SCHOOL   | 16.9                       | 
| 09X555 | MOUNT EDEN CHILDREN'S ACADEMY   | 18.1                       | 
| 12X536 | PS 536                          | 14.8                       | 
| 12X531 | ARCHER ELEMENTARY SCHOOL        | 13.7                       | 
| 11X483 | P.S. 483                        | 14.3                       | 
| 11X481 | P.S. 481                        | 14.1                       | 
| 12X463 | URBAN SCHOLARS COMMUNITY SCHOOL | 13.8                       | 
| 12X458 | SAMARA COMMUNITY SCHOOL         | 19                         | 
```