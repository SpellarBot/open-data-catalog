# DYCD after-school programs: Teen ACTION Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-teen-action-programs-ca868) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/fijd-wye8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/fijd-wye8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/fijd-wye8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | fijd-wye8 |
| Name | DYCD after-school programs: Teen ACTION Programs |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, school, child, children, nycha, new york city housing authority, beacon satellite, teen action, after school, lifelo... |
| Created | 2011-09-01T16:33:52Z |
| Publication Date | 2011-09-01T16:33:52Z |

## Description

Facilities in New York City, by agency and site, that offer ?Teen ACTION Programs? after-school programs for children ages 13 to 21. Update Schedule: Annually

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
series e:fijd-wye8 d:2011-09-01T11:33:10.000Z t:contact_number="718.293.0727 ext.204" t:program_type="After-School Programs" t:borough_community=Bronx t:program="Teen Action Program" t:agency="Citizens Advice Bureau, Inc." t:grade_level_age_group="13 to 21" t:site_name="COMMUNITY SCHOOL FOR SOCIAL JUSTICE (X427)" m:row_number.fijd-wye8=1

series e:fijd-wye8 d:2011-09-01T11:33:10.000Z t:contact_number="212.360.7625 ext.10" t:program_type="After-School Programs" t:borough_community="New York" t:program="Teen Action Program" t:agency="Stanley M. Isaacs Neighborhood Center, Inc." t:grade_level_age_group="13 to 21" t:site_name="PS 198 Isador E Ida Straus" m:row_number.fijd-wye8=2

series e:fijd-wye8 d:2011-09-01T11:33:10.000Z t:contact_number=212.912.2557 t:program_type="After-School Programs" t:borough_community="New York" t:program="Teen Action Program" t:agency="YMCA of Greater New York/Vanderbilt" t:grade_level_age_group="13 to 21" t:site_name="Vanderbilt YMCA of Greater  New York" m:row_number.fijd-wye8=3
```

## Meta Commands

```ls
metric m:row_number.fijd-wye8 p:long l:"Row Number"

entity e:fijd-wye8 l:"DYCD after-school programs: Teen ACTION Programs" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/fijd-wye8

property e:fijd-wye8 t:meta.view v:id=fijd-wye8 v:category=Education v:averageRating=0 v:name="DYCD after-school programs: Teen ACTION Programs" v:attribution="Department of Youth and Community Development (DYCD)"

property e:fijd-wye8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:fijd-wye8 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type          | program             | site_name                                    | borough_community | agency                                      | contact_number                       | grade_level_age_group | 
| =========== | ===================== | =================== | ============================================ | ================= | =========================================== | ==================================== | ===================== | 
| 1314876790  | After-School Programs | Teen Action Program | COMMUNITY SCHOOL FOR SOCIAL JUSTICE (X427)   | Bronx             | Citizens Advice Bureau, Inc.                | 718.293.0727 ext.204                 | 13 to 21              | 
| 1314876790  | After-School Programs | Teen Action Program | PS 198 Isador E Ida Straus                   | New York          | Stanley M. Isaacs Neighborhood Center, Inc. | 212.360.7625 ext.10                  | 13 to 21              | 
| 1314876790  | After-School Programs | Teen Action Program | Vanderbilt YMCA of Greater New York          | New York          | YMCA of Greater New York/Vanderbilt         | 212.912.2557                         | 13 to 21              | 
| 1314876790  | After-School Programs | Teen Action Program | Manhattan Center For Science and Mathematics | New York          | The Children's Aid Society                  | 212.949.4921                         | 13 to 21              | 
| 1314876790  | After-School Programs | Teen Action Program | I S 218 SALOME UKENA (M218)                  | New York          | The Children's Aid Society                  | 212.949.4921                         | 13 to 21              | 
| 1314876790  | After-School Programs | Teen Action Program | I S 061 WILLIAM A MORRIS (R061)              | Staten Island     | The Children's Aid Society                  | 718.727.8481                         | 13 to 21              | 
| 1314876790  | After-School Programs | Teen Action Program | I S 051 EDWIN MARKHAM (R051)                 | Staten Island     | Sports and Arts In Schools Foundation, Inc. | 347.417.8161                         | 13 to 21              | 
| 1314876790  | After-School Programs | Teen Action Program | I S 238 SUSAN B ANTHONY (Q238)               | Queens            | Sports and Arts In Schools Foundation, Inc. | 347.417.8161                         | 13 to 21              | 
| 1314876790  | After-School Programs | Teen Action Program | IS 285 Meyer Levin                           | Brooklyn          | Sports and Arts in Schools Foundation       | 718.451.2200 ext.107 or 973.896.1246 | 13 to 21              | 
| 1314876790  | After-School Programs | Teen Action Program | Canarsie High School                         | Brooklyn          | Hospital Audiences, Inc.                    | 212.575.7670 ext.246                 | 13 to 21              | 
```