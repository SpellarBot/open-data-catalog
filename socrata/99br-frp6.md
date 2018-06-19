# DYCD after-school programs: Jobs and Internships

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-jobs-and-internships-c73a0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/99br-frp6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/99br-frp6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/99br-frp6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 99br-frp6 |
| Name | DYCD after-school programs: Jobs and Internships |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, community development, school, child, children, after-school, summer youth employment, summer, employment, internshi... |
| Created | 2011-09-01T17:11:12Z |
| Publication Date | 2011-09-01T17:11:12Z |

## Description

Facilities in New York City, by agency and site, that offer the following after-school  job and internship programs: Summer Youth Employment, In-School Youth Employment (ISY), Out-of-School Youth Employment (OSY), Youth Employment, and Adult Employment Programs for children in age groups 14 to 24, 16 to 21, children in all grades, and adults.    Update Schedule: Annually

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
series e:99br-frp6 d:2011-09-01T10:11:13.000Z t:contact_number=718.589.1510 t:program_type="Jobs & Internships" t:borough_community=Bronx t:program="In-School Youth Employment (ISY)" t:agency="Simpson Street Development Association, Inc." t:site_name="Intermediate School 217 - Rafael Hernandez School" m:row_number.99br-frp6=1

series e:99br-frp6 d:2011-09-01T10:11:14.000Z t:contact_number="718 585.2600" t:program_type="Jobs & Internships" t:borough_community=Bronx t:program="Adult Employment" t:agency="South Bronx Overall Economic Development Corp." t:site_name="NDA Center" m:row_number.99br-frp6=2

series e:99br-frp6 d:2011-09-01T11:33:30.000Z t:contact_number=718.859.3800 t:program_type="Jobs & Internships" t:borough_community=Brooklyn t:program="Youth Employment" t:agency="Flatbush Development Corporation" t:grade_level_age_group=MS/HS t:site_name="Public School 217 - Col. David Marcus Elementary School" m:row_number.99br-frp6=3
```

## Meta Commands

```ls
metric m:row_number.99br-frp6 p:long l:"Row Number"

entity e:99br-frp6 l:"DYCD after-school programs: Jobs and Internships" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/99br-frp6

property e:99br-frp6 t:meta.view v:id=99br-frp6 v:category=Education v:averageRating=0 v:name="DYCD after-school programs: Jobs and Internships" v:attribution="Department of Youth and Community Development (DYCD)"

property e:99br-frp6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:99br-frp6 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type                         | program                          | site_name                                               | borough_community | agency                                         | contact_number    | grade_level_age_group | 
| =========== | ==================================== | ================================ | ======================================================= | ================= | ============================================== | ================= | ===================== | 
| 1314871873  | Jobs & Internships                   | In-School Youth Employment (ISY) | Intermediate School 217 - Rafael Hernandez School       | Bronx             | Simpson Street Development Association, Inc.   | 718.589.1510      |                       | 
| 1314871874  | Jobs & Internships                   | Adult Employment                 | NDA Center                                              | Bronx             | South Bronx Overall Economic Development Corp. | 718 585.2600      |                       | 
| 1314876810  | Jobs & Internships                   | Youth Employment                 | Public School 217 - Col. David Marcus Elementary School | Brooklyn          | Flatbush Development Corporation               | 718.859.3800      | MS/HS                 | 
| 1314876810  | Jobs & Internships, Youth Employment | Summer Youth Employment          | All City Leadership School                              | Brooklyn          | Ridgewood Bushwick Senior Citizens Council     | 718-381-9653      | 14 to 24              | 
| 1314876810  | Jobs & Internships                   | In-School Youth Employment (ISY) | East Harlem Council For Community Improvement           | New York          | East Harlem Council For Community Improvement  | 212.410.7707      |                       | 
| 1314876810  | Jobs & Internships, Youth Employment | Summer Youth Employment          | PAL-Foster Laurie Center                                | Queens            | Police Athletic League, Inc. - Queens          | 718-389-5309      | 14 to 24              | 
| 1314876810  | Jobs & Internships, Youth Employment | Summer Youth Employment          | Chinese American Planning Council - Queens              | Queens            | Chinese American Planning Council - Queens     | 718-358-8899 x132 | 14 to 24              | 
| 1314876810  | Jobs & Internships                   | Adult Employment                 | The Annex                                               | New York          | Community Impact/Columbia University           | 212.854.2617      |                       | 
| 1314876810  | Jobs & Internships                   | Youth Employment                 | Bnos Yakov Educational Center                           | Brooklyn          | Bnos Yakov Educational Center                  | 718.963.1212      | MS/HS                 | 
| 1314876810  | Jobs & Internships                   | In-School Youth Employment (ISY) | Intermediate School 93 - Ridgewood Intermediate School  | Queens            | Greater Ridgewood Youth Council, Inc.          | 718.456.5437      |                       | 
```