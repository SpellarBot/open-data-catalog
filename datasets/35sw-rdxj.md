# DYCD after-school programs: Beacon Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-beacon-programs-5100e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/35sw-rdxj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/35sw-rdxj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/35sw-rdxj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 35sw-rdxj |
| Name | DYCD after-school programs: Beacon Programs |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, school, child, children, beacon, lifelong learning |
| Created | 2011-08-31T19:20:58Z |
| Publication Date | 2011-08-31T19:20:58Z |

## Description

Facilities in New York City, by agency and site, that offer "Beacon Programs" after-school programs. Update Schedule: Annually

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
series e:35sw-rdxj d:2011-08-31T12:21:12.000Z t:contact_number=718.556.1565 t:program_type="After-School Programs" t:borough_community="Staten Island" t:program=Beacon t:agency="Jewish Community Center of Staten Island" t:grade_level_age_group="6 and up" t:site_name="IS 49" m:row_number.35sw-rdxj=1

series e:35sw-rdxj d:2011-08-31T12:21:13.000Z t:contact_number=718.590.0101 t:program_type="After-School Programs" t:borough_community=Bronx t:program=Beacon t:agency="Alianza Dominicana Inc." t:grade_level_age_group="6 and up" t:site_name="PS 11" m:row_number.35sw-rdxj=2

series e:35sw-rdxj d:2011-08-31T12:21:13.000Z t:contact_number=718.466.1806 t:program_type="After-School Programs" t:borough_community=Bronx t:program=Beacon t:agency="Community Association Progressive Dominicans" t:grade_level_age_group="6 and up" t:site_name="MS 117" m:row_number.35sw-rdxj=3
```

## Meta Commands

```ls
metric m:row_number.35sw-rdxj p:long l:"Row Number"

entity e:35sw-rdxj l:"DYCD after-school programs:  Beacon Programs" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/35sw-rdxj

property e:35sw-rdxj t:meta.view v:id=35sw-rdxj v:category=Education v:averageRating=0 v:name="DYCD after-school programs:  Beacon Programs" v:attribution="Department of Youth and Community Development (DYCD)"

property e:35sw-rdxj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:35sw-rdxj t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type          | program | site_name                               | borough_community | agency                                         | contact_number | grade_level_age_group | 
| =========== | ===================== | ======= | ======================================= | ================= | ============================================== | ============== | ===================== | 
| 1314793272  | After-School Programs | Beacon  | IS 49                                   | Staten Island     | Jewish Community Center of Staten Island       | 718.556.1565   | 6 and up              | 
| 1314793273  | After-School Programs | Beacon  | PS 11                                   | Bronx             | Alianza Dominicana Inc.                        | 718.590.0101   | 6 and up              | 
| 1314793273  | After-School Programs | Beacon  | MS 117                                  | Bronx             | Community Association Progressive Dominicans   | 718.466.1806   | 6 and up              | 
| 1314793273  | After-School Programs | Beacon  | JHS 349/345                             | Bronx             | Aspira of New York                             | 718.842.8289   | 6 and up              | 
| 1314793273  | After-School Programs | Beacon  | Dr. Charles R. Drew Educational Complex | Bronx             | Directions for Our Youth                       | 718.293.4344   | 6 and up              | 
| 1314793273  | After-School Programs | Beacon  | IS 323                                  | Brooklyn          | Research Foundation of CUNY                    | 718.498.8913   | 6 and up              | 
| 1314793273  | After-School Programs | Beacon  | IS 271                                  | Brooklyn          | Church Avenue Merchants Block Association Inc. | 718.345.5904   | 6 and up              | 
| 1314793273  | After-School Programs | Beacon  | JHS 45                                  | Manhattan         | Supportive Children's Advocacy Network (SCAN)  | 212.722.4090   | 6 and up              | 
| 1314793273  | After-School Programs | Beacon  | IS 218                                  | Brooklyn          | Police Athletic League (PAL)                   | 718.277.1928   | 6 and up              | 
| 1314793273  | After-School Programs | Beacon  | MS 210                                  | Queens            | YMCA Cross Island                              | 718.659.7710   | 6 and up              | 
```