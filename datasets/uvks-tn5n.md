# DYCD after-school programs: Out Of School Time

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-out-of-school-time-19e03) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/uvks-tn5n) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/uvks-tn5n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/uvks-tn5n/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | uvks-tn5n |
| Name | DYCD after-school programs: Out Of School Time |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, school, child, children, time, lifelong learning |
| Created | 2011-08-31T19:04:43Z |
| Publication Date | 2011-08-31T19:04:43Z |

## Description

Facilities in New York City that offer "Out of School Time" after-school programs. Managed by the Department of Youth and Community Development (DYCD). Update Frequency: Annually

## Columns

```ls
| Included | Schema Type | Field Name            | Name                    | Data Type | Render Type |
| ======== | =========== | ===================== | ======================= | ========= | =========== |
| No       | time        | :updated_at           | updated_at              | meta_data | meta_data   |
| Yes      | series tag  | program_type          | PROGRAM TYPE            | text      | text        |
| Yes      | series tag  | program               | PROGRAM                 | text      | text        |
| Yes      | series tag  | site_name             | SITE NAME               | text      | text        |
| Yes      | series tag  | borough_community     | BOROUGH / COMMUNITY     | text      | text        |
| Yes      | series tag  | agency                | AGENCY                  | text      | text        |
| Yes      | series tag  | contact_number        | Contact Number          | text      | text        |
| Yes      | series tag  | grade_level_age_group | Grade Level / Age Group | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:uvks-tn5n d:2011-08-31T12:04:53.000Z t:contact_number="(718) 474-0861" t:program_type="After-School Programs" t:borough_community=Queens t:program="Out of School Time" t:agency="Rockaway Artist Alliance, Inc." t:grade_level_age_group=Elem/MS t:site_name="Building T 149" m:row_number.uvks-tn5n=1

series e:uvks-tn5n d:2011-08-31T12:04:54.000Z t:contact_number="(718) 402-8481" t:program_type="After-School Programs" t:borough_community=Bronx t:program="Out of School Time" t:agency="Citizens Advice Bureau, Inc." t:grade_level_age_group="High School" t:site_name="H.S. 427 COMMUNITY SCHOOL FOR" m:row_number.uvks-tn5n=2

series e:uvks-tn5n d:2011-08-31T12:04:54.000Z t:contact_number="(718) 589-2230" t:program_type="After-School Programs" t:borough_community=Bronx t:program="Out of School Time" t:agency="Casita Maria, Inc." t:grade_level_age_group=Elementary t:site_name="C.S. 50 CLARA BARTON SCHOOL" m:row_number.uvks-tn5n=3
```

## Meta Commands

```ls
metric m:row_number.uvks-tn5n p:long l:"Row Number"

entity e:uvks-tn5n l:"DYCD  after-school programs: Out Of School Time" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/uvks-tn5n

property e:uvks-tn5n t:meta.view v:id=uvks-tn5n v:category=Education v:averageRating=80 v:name="DYCD  after-school programs: Out Of School Time" v:attribution="Department of Youth and Community Development (DYCD)"

property e:uvks-tn5n t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:uvks-tn5n t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type          | program            | site_name                     | borough_community | agency                                   | contact_number | grade_level_age_group | 
| =========== | ===================== | ================== | ============================= | ================= | ======================================== | ============== | ===================== | 
| 1314792293  | After-School Programs | Out of School Time | Building T 149                | Queens            | Rockaway Artist Alliance, Inc.           | (718) 474-0861 | Elem/MS               | 
| 1314792294  | After-School Programs | Out of School Time | H.S. 427 COMMUNITY SCHOOL FOR | Bronx             | Citizens Advice Bureau, Inc.             | (718) 402-8481 | High School           | 
| 1314792294  | After-School Programs | Out of School Time | C.S. 50 CLARA BARTON SCHOOL   | Bronx             | Casita Maria, Inc.                       | (718) 589-2230 | Elementary            | 
| 1314792294  | After-School Programs | Out of School Time | Avenue St. John               | Bronx             | Citizens Advice Bureau, Inc.             | (718) 401-1227 | Elementary            | 
| 1314792294  | After-School Programs | Out of School Time | CAB-Elem                      | Bronx             | Citizens Advice Bureau, Inc.             | (718) 508-3178 | Elementary            | 
| 1314792294  | After-School Programs | Out of School Time | Marble Hill                   | Bronx             | Childrens Arts & Science Workshops, Inc. | (718) 562-8560 | Elementary            | 
| 1314792294  | After-School Programs | Out of School Time | Baychester Center- MS         | Bronx             | Baychester Youth Council                 | (718) 325-9484 | Middle School         | 
| 1314792294  | After-School Programs | Out of School Time | Baychester Center-HS          | Bronx             | Baychester Youth Council                 | (718) 325-9484 | High School           | 
| 1314792294  | After-School Programs | Out of School Time | Girls Club-HS                 | Bronx             | Citizens Advice Bureau, Inc.             | (718) 508-3044 | High School           | 
| 1314792294  | After-School Programs | Out of School Time | C.E.S. 109 SEDGWICK SCHOOL    | Bronx             | Bronx Arts Ensemble                      | (718) 601-7399 | Elementary            | 
```