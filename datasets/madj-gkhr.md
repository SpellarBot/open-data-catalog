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
| Publication Date | 2017-03-10T23:56:48Z |
| Rows Updated | 2017-03-10T23:56:41Z |

## Description

Statistical report that provides daily school wide attendance each day for all schools at 4:00pm. Attendance figures are "accurate" as of 4:00pm, but not final as schools continue to submit data after preliminary report is generated.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name            | Data Type | Render Type |
| ======== | ============== | ============= | =============== | ========= | =========== |
| No       | time           | :updated_at   | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | school_year   | SCHOOL_YEAR     | text      | text        |
| Yes      | series tag     | date          | DATE            | text      | text        |
| Yes      | series tag     | school_dbn    | SCHOOL_DBN      | text      | text        |
| Yes      | numeric metric | register      | REGISTER        | number    | number      |
| Yes      | numeric metric | of_attd_taken | %_OF_ATTD_TAKEN | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:madj-gkhr d:2015-12-31T10:03:25.000Z t:school_dbn=10X024 t:date=09-09-15 t:school_year=2015-2016 m:register=999 m:of_attd_taken=96.6

series e:madj-gkhr d:2015-12-31T10:03:25.000Z t:school_dbn=10X032 t:date=09-09-15 t:school_year=2015-2016 m:register=810 m:of_attd_taken=88.4

series e:madj-gkhr d:2015-12-31T10:03:25.000Z t:school_dbn=10X033 t:date=09-09-15 t:school_year=2015-2016 m:register=991 m:of_attd_taken=86.7
```

## Meta Commands

```ls
metric m:register p:long l:REGISTER t:dataTypeName=number

metric m:of_attd_taken p:long l:%_OF_ATTD_TAKEN t:dataTypeName=number

entity e:madj-gkhr l:"Attendance 4PM Report" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/madj-gkhr

property e:madj-gkhr t:meta.view v:id=madj-gkhr v:category=Education v:averageRating=0 v:name="Attendance 4PM Report" v:attribution="Department of Education (DOE)"

property e:madj-gkhr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:madj-gkhr t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"
```