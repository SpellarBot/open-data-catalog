# Attendance 4PM Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/attendance-4pm-report) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/madj-gkhr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/madj-gkhr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/madj-gkhr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | madj-gkhr |
| Name | Attendance 4PM Report |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | attendance, schools, doe, education |
| Created | 2015-12-31T18:03:16Z |
| Publication Date | 2017-04-20T21:10:47Z |

## Description

Statistical report that provides daily school wide attendance each day for all schools at 4:00pm. Attendance figures are "accurate" as of 4:00pm, but not final as schools continue to submit data after preliminary report is generated.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name            | Data Type | Render Type |
| ======== | ============== | ============= | =============== | ========= | =========== |
| Yes      | series tag     | school_year   | SCHOOL_YEAR     | text      | text        |
| Yes      | time           | date          | DATE            | text      | text        |
| Yes      | series tag     | school_dbn    | SCHOOL_DBN      | text      | text        |
| Yes      | numeric metric | register      | REGISTER        | number    | number      |
| Yes      | numeric metric | of_attd_taken | %_OF_ATTD_TAKEN | number    | number      |
```

## Time Field

```ls
Value = date
Format & Zone = MM-dd-yy
```

## Data Commands

```ls
series e:madj-gkhr d:2015-09-09T00:00:00.000Z t:school_dbn=10X024 t:school_year=2015-2016 m:register=999 m:of_attd_taken=96.6

series e:madj-gkhr d:2015-09-09T00:00:00.000Z t:school_dbn=10X032 t:school_year=2015-2016 m:register=810 m:of_attd_taken=88.4

series e:madj-gkhr d:2015-09-09T00:00:00.000Z t:school_dbn=10X033 t:school_year=2015-2016 m:register=991 m:of_attd_taken=86.7
```

## Meta Commands

```ls
metric m:register p:integer l:REGISTER t:dataTypeName=number

metric m:of_attd_taken p:float l:%_OF_ATTD_TAKEN t:dataTypeName=number

entity e:madj-gkhr l:"Attendance 4PM Report" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/madj-gkhr

property e:madj-gkhr t:meta.view v:id=madj-gkhr v:category=Education v:averageRating=0 v:name="Attendance 4PM Report" v:attribution="Department of Education (DOE)"

property e:madj-gkhr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:madj-gkhr t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| school_year | date     | school_dbn | register | of_attd_taken | 
| =========== | ======== | ========== | ======== | ============= | 
| 2015-2016   | 09-09-15 | 10X024     | 999      | 96.6          | 
| 2015-2016   | 09-09-15 | 10X032     | 810      | 88.4          | 
| 2015-2016   | 09-09-15 | 10X033     | 991      | 86.7          | 
| 2015-2016   | 09-09-15 | 10X045     | 702      | 91.3          | 
| 2015-2016   | 09-09-15 | 10X046     | 1075     | 84.2          | 
| 2015-2016   | 09-09-15 | 10X056     | 662      | 92.3          | 
| 2015-2016   | 09-09-15 | 10X080     | 595      | 86.4          | 
| 2015-2016   | 09-09-15 | 10X081     | 676      | 97.2          | 
| 2015-2016   | 09-09-15 | 10X086     | 1651     | 88.9          | 
| 2015-2016   | 09-09-15 | 10X094     | 1216     | 90.2          | 
```