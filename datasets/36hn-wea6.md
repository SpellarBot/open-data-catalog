# DYCD after-school programs: OSY Out Of School Youth Employment Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-osy-out-of-school-youth-employment-programs-b0b82) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/36hn-wea6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/36hn-wea6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/36hn-wea6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 36hn-wea6 |
| Name | DYCD after-school programs: OSY Out Of School Youth Employment Programs |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, community development, school, child, children, after-school, after-school programs, programs, employment, internshi... |
| Created | 2011-09-01T20:39:32Z |
| Publication Date | 2011-09-01T20:39:32Z |

## Description

Facilities in New York City, by agency and site, that offer “Out-Of -School Youth Employment (OSY) Program” after-school  job and internship programs for young adults ages 16 to 21.
Update Frequency: Annually

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
series e:36hn-wea6 d:2011-09-01T13:39:35.000Z t:contact_number="212.478.5400 ext. 210" t:program_type="Jobs & Internships" t:borough_community="New York" t:program="Out-of-School Youth Employment (OSY)" t:agency="Henry Street Settlement" t:grade_level_age_group="16 to 21" t:site_name="Henry Street Settlement Workforce Development Center" m:row_number.36hn-wea6=1

series e:36hn-wea6 d:2011-09-01T13:39:35.000Z t:contact_number=212.571.1690 t:program_type="Jobs & Internships" t:borough_community="New York" t:program="Out-of-School Youth Employment (OSY)" t:agency="Chinatown Manpower Project, Inc." t:grade_level_age_group="16 to 21" t:site_name="Chinatown Manpower Project, Inc." m:row_number.36hn-wea6=2

series e:36hn-wea6 d:2011-09-01T13:39:35.000Z t:contact_number="212.691.7554 ext. 704" t:program_type="Jobs & Internships" t:borough_community=Queens t:program="Out-of-School Youth Employment (OSY)" t:agency="The Fortune Society, Inc." t:grade_level_age_group="16 to 21" t:site_name="The Fortune Society, Inc." m:row_number.36hn-wea6=3
```

## Meta Commands

```ls
metric m:row_number.36hn-wea6 p:long l:"Row Number"

entity e:36hn-wea6 l:"DYCD after-school programs: OSY Out Of School Youth Employment Programs" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/36hn-wea6

property e:36hn-wea6 t:meta.view v:id=36hn-wea6 v:category=Education v:averageRating=0 v:name="DYCD after-school programs: OSY Out Of School Youth Employment Programs" v:attribution="Department of Youth and Community Development (DYCD)"

property e:36hn-wea6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:36hn-wea6 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type       | program                              | site_name                                                      | borough_community | agency                                                        | contact_number        | grade_level_age_group | 
| =========== | ================== | ==================================== | ============================================================== | ================= | ============================================================= | ===================== | ===================== | 
| 1314884375  | Jobs & Internships | Out-of-School Youth Employment (OSY) | Henry Street Settlement Workforce Development Center           | New York          | Henry Street Settlement                                       | 212.478.5400 ext. 210 | 16 to 21              | 
| 1314884375  | Jobs & Internships | Out-of-School Youth Employment (OSY) | Chinatown Manpower Project, Inc.                               | New York          | Chinatown Manpower Project, Inc.                              | 212.571.1690          | 16 to 21              | 
| 1314884375  | Jobs & Internships | Out-of-School Youth Employment (OSY) | The Fortune Society, Inc.                                      | Queens            | The Fortune Society, Inc.                                     | 212.691.7554 ext. 704 | 16 to 21              | 
| 1314884377  | Jobs & Internships | Out-of-School Youth Employment (OSY) | The Door - A Center of Alternatives                            | New York          | The Door - A Center of Alternatives                           | 212.941.9090          | 16 to 21              | 
| 1314884377  | Jobs & Internships | Out-of-School Youth Employment (OSY) | Sunnyside Community Services, Inc.                             | Queens            | Sunnyside Community Service, Inc.                             | 718.784.6173 ext. 429 | 16 to 21              | 
| 1314884377  | Jobs & Internships | Out-of-School Youth Employment (OSY) | Brooklyn Job Corps Academy                                     | Brooklyn          | Arbor Employment and Training                                 | 718.623.4031          | 16 to 21              | 
| 1314884377  | Jobs & Internships | Out-of-School Youth Employment (OSY) | YWCA of Queens                                                 | Queens            | YWCA of Queens                                                | 718.353.4553          | 16 to 21              | 
| 1314884377  | Jobs & Internships | Out-of-School Youth Employment (OSY) | Medgar Evers College                                           | Brooklyn          | Research Foundation of CUNY on behalf of Medgar Evers College | 718.270.6474          | 16 to 21              | 
| 1314884377  | Jobs & Internships | Out-of-School Youth Employment (OSY) | International Sheet Metal Workers Local Union 28 (intake site) | New York          | International Sheet Metal Workers Local Union 28              | 212.732.7897          | 16 to 21              | 
| 1314884377  | Jobs & Internships | Out-of-School Youth Employment (OSY) | Mosholu Montefiore Community Center, Inc.                      | Bronx             | Mosholu Montefiore Community Center, Inc.                     | 718.652.0470          | 16 to 21              | 
```