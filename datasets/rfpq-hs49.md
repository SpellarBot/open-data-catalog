# School Attendance And Enrollment By District - 2010-11

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-attendance-and-enrollment-by-district-2010-11-d4281) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rfpq-hs49) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rfpq-hs49/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rfpq-hs49/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rfpq-hs49 |
| Name | School Attendance And Enrollment By District - 2010-11 |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | lifelong learning |
| Created | 2011-10-06T22:03:38Z |
| Publication Date | 2011-10-11T17:53:33Z |

## Description

2010- 11 Attendance & Enrollment (Unaudited) by District as of December 31, 2010

Charter Schools, Community-Based Organizations (Pre-K), Home Instruction, and Hospital Schools are not included.
Attendance averages based on each districts associated data.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                   | Data Type | Render Type |
| ======== | ============== | =================== | ====================== | ========= | =========== |
| Yes      | series tag     | district            | District               | text      | text        |
| Yes      | numeric metric | ytd_attendance_avg_ | YTD % Attendance (Avg) | percent   | percent     |
| Yes      | numeric metric | ytd_enrollment_avg_ | YTD Enrollment (Avg)   | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rfpq-hs49 d:2010-01-01T00:00:00.000Z t:district="DISTRICT 01" m:ytd_enrollment_avg_=12367 m:ytd_attendance_avg_=91.18

series e:rfpq-hs49 d:2010-01-01T00:00:00.000Z t:district="DISTRICT 02" m:ytd_enrollment_avg_=60823 m:ytd_attendance_avg_=89.01

series e:rfpq-hs49 d:2010-01-01T00:00:00.000Z t:district="DISTRICT 03" m:ytd_enrollment_avg_=21962 m:ytd_attendance_avg_=89.28
```

## Meta Commands

```ls
metric m:ytd_attendance_avg_ p:float l:"YTD % Attendance (Avg)" t:dataTypeName=percent

metric m:ytd_enrollment_avg_ p:integer l:"YTD Enrollment (Avg)" t:dataTypeName=number

entity e:rfpq-hs49 l:"School Attendance And Enrollment By District - 2010-11" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/rfpq-hs49

property e:rfpq-hs49 t:meta.view v:id=rfpq-hs49 v:category=Education v:averageRating=0 v:name="School Attendance And Enrollment By District - 2010-11" v:attribution="Department of Education (DOE)"

property e:rfpq-hs49 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rfpq-hs49 t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| district    | ytd_attendance_avg_ | ytd_enrollment_avg_ | 
| =========== | =================== | =================== | 
| DISTRICT 01 | 91.18               | 12367               | 
| DISTRICT 02 | 89.01               | 60823               | 
| DISTRICT 03 | 89.28               | 21962               | 
| DISTRICT 04 | 91.13               | 14252               | 
| DISTRICT 05 | 89.08               | 13170               | 
| DISTRICT 06 | 91.34               | 25733               | 
| DISTRICT 07 | 86.75               | 19717               | 
| DISTRICT 08 | 87.15               | 31625               | 
| DISTRICT 09 | 89.27               | 34518               | 
| DISTRICT 10 | 88.92               | 56757               | 
```