# Libraries - Locations, Hours and Contact Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-locations-hours-and-contact-information-f3c61) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/x8fc-8rcq) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/x8fc-8rcq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/x8fc-8rcq/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | x8fc-8rcq |
| Name | Libraries - Locations, Hours and Contact Information |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, facilities, gis |
| Created | 2010-12-22T20:49:56Z |
| Publication Date | 2015-09-10T21:02:18Z |

## Description

Chicago Public Library locations, contact information, and hours of operation.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | name_                  | NAME                   | text      | text        |
| Yes      | series tag  | hours_of_operation     | HOURS OF OPERATION     | text      | text        |
| Yes      | series tag  | cybernavigator         | CYBERNAVIGATOR         | text      | text        |
| Yes      | series tag  | teacher_in_the_library | TEACHER IN THE LIBRARY | text      | text        |
| No       |             | address                | ADDRESS                | text      | text        |
| Yes      | series tag  | city                   | CITY                   | text      | text        |
| Yes      | series tag  | state                  | STATE                  | text      | text        |
| Yes      | series tag  | zip                    | ZIP                    | text      | text        |
| Yes      | series tag  | phone                  | PHONE                  | text      | text        |
| Yes      | series tag  | website                | WEBSITE                | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:x8fc-8rcq d:2015-09-10T14:01:20.000Z t:zip=60625 t:phone="(773) 539-5450" t:teacher_in_the_library=Yes t:website=http://www.chipublib.org/locations/1/ t:hours_of_operation="M, W: 10AM-6PM;  TU, TH: 12PM-8PM; F, SA: 9AM-5PM; SU: Closed" t:state=IL t:cybernavigator=Yes t:name_="Albany Park" t:city=CHICAGO m:row_number.x8fc-8rcq=1

series e:x8fc-8rcq d:2015-09-10T14:01:20.000Z t:zip=60827 t:phone="(312) 747-3270" t:teacher_in_the_library=Yes t:website=http://www.chipublib.org/locations/3/ t:hours_of_operation="M, W: 12PM-8PM; TU, TH: 10AM-6PM; F, SA: 9AM-5PM; SU: Closed" t:state=IL t:cybernavigator=Yes t:name_=Altgeld t:city=CHICAGO m:row_number.x8fc-8rcq=2

series e:x8fc-8rcq d:2015-09-10T14:01:20.000Z t:zip=60632 t:phone="(312) 747-9241" t:teacher_in_the_library=Yes t:website=http://www.chipublib.org/locations/4/ t:hours_of_operation="M, W: 12PM-8PM; TU, TH: 10AM-6PM; F, SA: 9AM-5PM; SU: Closed" t:state=IL t:cybernavigator=No t:name_="Archer Heights" t:city=CHICAGO m:row_number.x8fc-8rcq=3
```

## Meta Commands

```ls
metric m:row_number.x8fc-8rcq p:long l:"Row Number"

entity e:x8fc-8rcq l:"Libraries - Locations, Hours and Contact Information" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/x8fc-8rcq

property e:x8fc-8rcq t:meta.view v:id=x8fc-8rcq v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - Locations, Hours and Contact Information" v:attribution="Chicago Public Library"

property e:x8fc-8rcq t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:x8fc-8rcq t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | name_             | hours_of_operation                                           | cybernavigator | teacher_in_the_library | address                     | city    | state | zip   | phone          | website                                        | 
| =========== | ================= | ============================================================ | ============== | ====================== | =========================== | ======= | ===== | ===== | ============== | ============================================== | 
| 1441893680  | Albany Park       | M, W: 10AM-6PM; TU, TH: 12PM-8PM; F, SA: 9AM-5PM; SU: Closed | Yes            | Yes                    | 3401 W. Foster Avenue       | CHICAGO | IL    | 60625 | (773) 539-5450 | [http://www.chipublib.org/locations/1/, null]  | 
| 1441893680  | Altgeld           | M, W: 12PM-8PM; TU, TH: 10AM-6PM; F, SA: 9AM-5PM; SU: Closed | Yes            | Yes                    | 13281 S. Corliss Avenue     | CHICAGO | IL    | 60827 | (312) 747-3270 | [http://www.chipublib.org/locations/3/, null]  | 
| 1441893680  | Archer Heights    | M, W: 12PM-8PM; TU, TH: 10AM-6PM; F, SA: 9AM-5PM; SU: Closed | No             | Yes                    | 5055 S. Archer Avenue       | CHICAGO | IL    | 60632 | (312) 747-9241 | [http://www.chipublib.org/locations/4/, null]  | 
| 1441893680  | Austin            | M, W: 12PM-8PM; TU, TH: 10AM-6PM; F, SA: 9AM-5PM; SU: Closed | Yes            | Yes                    | 5615 W. Race Avenue         | CHICAGO | IL    | 60644 | (312) 746-5038 | [http://www.chipublib.org/locations/6/, null]  | 
| 1441893680  | Austin-Irving     | M, W: 12PM-8PM; TU, TH: 10AM-6PM; F, SA: 9AM-5PM; SU: Closed | No             | Yes                    | 6100 W. Irving Park Road    | CHICAGO | IL    | 60634 | (312) 744-6222 | [http://www.chipublib.org/locations/7/, null]  | 
| 1441893680  | Avalon            | M, W: 12PM-8PM; TU, TH: 10AM-6PM; F, SA: 9AM-5PM; SU: Closed | Yes            | Yes                    | 8148 S. Stony Island Avenue | CHICAGO | IL    | 60617 | (312) 747-5234 | [http://www.chipublib.org/locations/8/, null]  | 
| 1441893680  | Back of the Yards | M, W: 10AM-6PM; TU, TH: 12PM-8PM; F, SA: 9AM-5PM; SU: Closed | No             | Yes                    | 2111 W. 47th Street         | CHICAGO | IL    | 60609 | (312) 747-9595 | [http://www.chipublib.org/locations/9/, null]  | 
| 1441893680  | Beverly           | M, W: 12PM-8PM; TU, TH: 10AM-6PM; F, SA: 9AM-5PM; SU: Closed | No             | Yes                    | 1962 W. 95th Street         | CHICAGO | IL    | 60643 | (312) 747-9673 | [http://www.chipublib.org/locations/10/, null] | 
| 1441893680  | Bezazian          | M, W: 12PM-8PM; TU, TH: 10AM-6PM; F, SA: 9AM-5PM; SU: Closed | No             | Yes                    | 1226 W. Ainslie Street      | CHICAGO | IL    | 60640 | (312) 744-0019 | [http://www.chipublib.org/locations/11/, null] | 
| 1441893680  | Blackstone        | M, W: 12PM-8PM; TU, TH: 10AM-6PM; F, SA: 9AM-5PM; SU: Closed | Yes            | Yes                    | 4904 S. Lake Park Avenue    | CHICAGO | IL    | 60615 | (312) 747-0511 | [http://www.chipublib.org/locations/12/, null] | 
```