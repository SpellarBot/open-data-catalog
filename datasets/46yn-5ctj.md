# School Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-location) |
| Metadata | [Link](https://data.brla.gov/api/views/46yn-5ctj) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/46yn-5ctj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/46yn-5ctj/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | 46yn-5ctj |
| Name | School Location |
| Attribution | City-Parish Department of Information Services |
| Category | Government |
| Tags | school, charter, montessori, education, learning, basemap |
| Created | 2016-09-02T15:15:30Z |
| Publication Date | 2016-09-02T17:47:47Z |

## Description

This dataset displays the location, address, and contact information for public and private schools in East Baton Rouge Parish.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name            | Data Type | Render Type |
| ======== | ============== | ============== | =============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | name           | NAME            | text      | text        |
| Yes      | series tag     | type           | TYPE            | text      | text        |
| Yes      | series tag     | gradelevels    | GRADE LEVELS    | text      | text        |
| Yes      | series tag     | public_private | PUBLIC/ PRIVATE | text      | text        |
| Yes      | series tag     | schoolsystem   | SCHOOL DISTRICT | text      | text        |
| Yes      | series tag     | open_closed    | OPEN/CLOSED     | text      | text        |
| Yes      | series tag     | name_former    | FORMER NAMES    | text      | text        |
| No       |                | full_address   | ADDRESS         | text      | text        |
| Yes      | series tag     | city           | CITY            | text      | text        |
| Yes      | series tag     | state          | STATE           | text      | text        |
| Yes      | series tag     | zip            | ZIP             | text      | text        |
| Yes      | series tag     | phone_number   | PHONE NUMBER    | text      | text        |
| Yes      | series tag     | website        | WEBSITE         | url       | url         |
| Yes      | numeric metric | recno          | RECNO           | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = full_address
```

## Data Commands

```ls
series e:46yn-5ctj d:2016-09-02T17:49:27.000Z t:zip=70810 t:public_private=Private t:gradelevels="PK to K" t:phone_number=225-767-2500 t:name="Baton Rouge Montessori KIds" t:state=LOUISIANA t:open_closed=O t:type="All Grades" t:schoolsystem=Private t:city="BATON ROUGE" m:recno=752

series e:46yn-5ctj d:2016-09-02T17:49:27.000Z t:zip=70807 t:public_private=Public t:gradelevels="6 to 8" t:phone_number=225-775-4285 t:name_former="Beechwood Elementary School" t:website=http://ebr.oncoursesystems.com/websites/12700516 t:name="Greenville Alternative at Beechwood" t:state=LOUISIANA t:open_closed=O t:type=Middle t:schoolsystem="East Baton Rouge Parish" t:city="BATON ROUGE" m:recno=516

series e:46yn-5ctj d:2016-09-02T17:49:27.000Z t:zip=70806 t:public_private=Private t:gradelevels="K to 12" t:phone_number=225-932-2357 t:name="Jehovah-Jireh Christian Academy" t:state=LOUISIANA t:open_closed=O t:type="All Grades" t:schoolsystem=Private t:city="BATON ROUGE" m:recno=582
```

## Meta Commands

```ls
metric m:recno p:integer l:RECNO d:"Unique record identifier" t:dataTypeName=number

entity e:46yn-5ctj l:"School Location" t:attribution="City-Parish Department of Information Services" t:url=https://data.brla.gov/api/views/46yn-5ctj

property e:46yn-5ctj t:meta.view v:id=46yn-5ctj v:category=Government v:averageRating=0 v:name="School Location" v:attribution="City-Parish Department of Information Services"

property e:46yn-5ctj t:meta.view.license v:name="Public Domain"

property e:46yn-5ctj t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:displayName="Open Data BR"

property e:46yn-5ctj t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```

## Top Records

```ls
| :updated_at | name                                | type       | gradelevels | public_private | schoolsystem            | open_closed | name_former                 | full_address              | city        | state     | zip   | phone_number | website                                                  | recno | 
| =========== | =================================== | ========== | =========== | ============== | ======================= | =========== | =========================== | ========================= | =========== | ========= | ===== | ============ | ======================================================== | ===== | 
| 1472838567  | Baton Rouge Montessori KIds         | All Grades | PK to K     | Private        | Private                 | O           |                             | 12663 PERKINS RD          | BATON ROUGE | LOUISIANA | 70810 | 225-767-2500 | [null, null]                                             | 752   | 
| 1472838567  | Greenville Alternative at Beechwood | Middle     | 6 to 8      | Public         | East Baton Rouge Parish | O           | Beechwood Elementary School | 2555 DESOTO DR            | BATON ROUGE | LOUISIANA | 70807 | 225-775-4285 | [http://ebr.oncoursesystems.com/websites/12700516, null] | 516   | 
| 1472838567  | Jehovah-Jireh Christian Academy     | All Grades | K to 12     | Private        | Private                 | O           |                             | 1771 LOBDELL BLVD         | BATON ROUGE | LOUISIANA | 70806 | 225-932-2357 | [null, null]                                             | 582   | 
| 1472838567  | McKinley Middle Magnet School       | Middle     | 6 to 8      | Public         | East Baton Rouge Parish | O           |                             | 1550 EDDIE ROBINSON SR DR | BATON ROUGE | LOUISIANA | 70802 | 225-388-0089 | [http://ebr.oncoursesystems.com/websites/12787832, null] | 495   | 
| 1472838567  | Montessori School of Baton Rouge    | Elementary | PK to K     | Private        | Private                 | O           |                             | 8227 WIMBLEDON AVE        | BATON ROUGE | LOUISIANA | 70810 | 225-766-9942 | [http://montessorischoolofbatonrouge.org/, null]         | 759   | 
| 1472838567  | Istrouma School                     | Elementary |             | Public         |                         | C           |                             |                           |             |           |       |              | [null, null]                                             | 486   | 
| 1472838567  | Episcopal High School               | High       | Pre-K to 12 | Private        | Private                 | O           |                             | 3200 WOODLAND RIDGE BLVD  | BATON ROUGE | LOUISIANA | 70816 | 225-753-3180 | [http://www.ehsbr.org/, null]                            | 423   | 
| 1472838567  | AMIKids Baton Rouge                 | All Grades | 4 to 12     | Private        | Private                 | O           |                             | 5555 BEECHWOOD DR         | BATON ROUGE | LOUISIANA | 70805 | 225-356-3461 | [http://www.amikidsbatonrouge.org, null]                 | 729   | 
| 1472838567  | Arlington Preparatory Academy       | High       | 8 to 12     | Public         | East Baton Rouge Parish | O           |                             | 931 DEAN LEE DR           | BATON ROUGE | LOUISIANA | 70820 | 225-766-8188 | [http://ebr.oncoursesystems.com/websites/12783282, null] | 439   | 
| 1472838567  | Tara High School                    | High       | 9 to 12     | Public         | East Baton Rouge Parish | O           |                             | 9002 WHITEHALL AVE        | BATON ROUGE | LOUISIANA | 70806 | 225-927-6100 | [http://ebr.oncoursesystems.com/websites/12783373, null] | 416   | 
```