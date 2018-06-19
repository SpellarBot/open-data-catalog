# DYCD after-school programs: Young Adult Internship Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-young-adult-internship-programs-1cfb4) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/73bd-vkmx) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/73bd-vkmx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/73bd-vkmx/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 73bd-vkmx |
| Name | DYCD after-school programs: Young Adult Internship Programs |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, community development, school, child, children, after-school, after-school programs, programs, employment, internshi... |
| Created | 2011-09-01T20:22:26Z |
| Publication Date | 2011-09-01T20:22:26Z |

## Description

Facilities in New York City, by agency and site, that offer ?Youth Adult Internship Program? after-school job and internship programs for young adults ages 16 to 24. Update Frequency: Annually

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
series e:73bd-vkmx d:2011-09-01T13:22:28.000Z t:contact_number=347.571.2441 t:program_type="Jobs & Internships" t:borough_community=Queens t:program="Young Adult Internship Program" t:agency="The Child Center of NY, Inc" t:grade_level_age_group="16 to 24" t:site_name="The Child Center of NY" m:row_number.73bd-vkmx=1

series e:73bd-vkmx d:2011-09-01T13:22:28.000Z t:contact_number=718.993.8880 t:program_type="Jobs & Internships" t:borough_community=Bronx t:program="Young Adult Internship Program" t:agency="The Citizens Advice Bureau" t:grade_level_age_group="16 to 24" t:site_name="Bronx Works Center" m:row_number.73bd-vkmx=2

series e:73bd-vkmx d:2011-09-01T13:22:28.000Z t:contact_number=718.623.4031 t:program_type="Jobs & Internships" t:borough_community=Brooklyn t:program="Young Adult Internship Program" t:agency="Arbor - NY" t:grade_level_age_group="16 to 24" t:site_name="Brooklyn Job Corps Academy" m:row_number.73bd-vkmx=3
```

## Meta Commands

```ls
metric m:row_number.73bd-vkmx p:long l:"Row Number"

entity e:73bd-vkmx l:"DYCD after-school programs: Young Adult Internship Programs" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/73bd-vkmx

property e:73bd-vkmx t:meta.view v:id=73bd-vkmx v:category=Education v:averageRating=0 v:name="DYCD after-school programs: Young Adult Internship Programs" v:attribution="Department of Youth and Community Development (DYCD)"

property e:73bd-vkmx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:73bd-vkmx t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type       | program                        | site_name                                      | borough_community | agency                                         | contact_number       | grade_level_age_group | 
| =========== | ================== | ============================== | ============================================== | ================= | ============================================== | ==================== | ===================== | 
| 1314883348  | Jobs & Internships | Young Adult Internship Program | The Child Center of NY                         | Queens            | The Child Center of NY, Inc                    | 347.571.2441         | 16 to 24              | 
| 1314883348  | Jobs & Internships | Young Adult Internship Program | Bronx Works Center                             | Bronx             | The Citizens Advice Bureau                     | 718.993.8880         | 16 to 24              | 
| 1314883348  | Jobs & Internships | Young Adult Internship Program | Brooklyn Job Corps Academy                     | Brooklyn          | Arbor - NY                                     | 718.623.4031         | 16 to 24              | 
| 1314883348  | Jobs & Internships | Young Adult Internship Program | Good Shepherd Services                         | Brooklyn          | Good Shepherd Services                         | 718.366.7240         | 16 to 24              | 
| 1314883348  | Jobs & Internships | Young Adult Internship Program | Federation Employment & Guidance Services, Inc | Bronx             | Federation Employment & Guidance Services, Inc | 718.742.3509         | 16 to 24              | 
| 1314883349  | Jobs & Internships | Young Adult Internship Program | Italian American Civil Rights League           | Brooklyn          | Italian American Civil Rights League           | 718.642.2180         | 16 to 24              | 
| 1314883349  | Jobs & Internships | Young Adult Internship Program | Southern Queens Park Association - NY          | Queens            | Southern Queens Park Association - NY          | 718.276.4630 ext.126 | 16 to 24              | 
| 1314883349  | Jobs & Internships | Young Adult Internship Program | Vannguard Computer Center                      | Brooklyn          | Vannguard Urban Improvement Assciation         | 718.735.4466         | 16 to 24              | 
| 1314883349  | Jobs & Internships | Young Adult Internship Program | NYSARC, Inc. NYC Chapter                       | Staten Island     | NYSARC, Inc. NYC Chapter                       | 718.246.1506         | 16 to 24              | 
| 1314883349  | Jobs & Internships | Young Adult Internship Program | Henry Street Settlement                        | Manhattan         | Henry Street Settlement                        | 212.473.1474         | 16 to 24              | 
```