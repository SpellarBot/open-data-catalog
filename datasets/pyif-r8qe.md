# DYCD after-school programs: Beacon Satellite At NYCHA Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-beacon-satellite-at-nycha-programs-e7307) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pyif-r8qe) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pyif-r8qe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pyif-r8qe/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pyif-r8qe |
| Name | DYCD after-school programs: Beacon Satellite At NYCHA Programs |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, school, child, children, nycha, new york city housing authority, beacon satellite, beacon, lifelong learning |
| Created | 2011-09-01T16:20:02Z |
| Publication Date | 2011-09-01T16:20:02Z |

## Description

Facilities in New York City, by agency and site, that offer “Beacon Satellite at NYCHA Programs” after-school programs. Update Schedule: Annually

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
series e:pyif-r8qe d:2011-09-01T11:33:05.000Z t:contact_number="(718) 652-0246" t:program_type="After-School Programs,Beacon,NYCHA Centers" t:borough_community=Bronx t:program="Beacon Satellite" t:agency="Mosholu Montefiore  @Edenwald Community Center" t:grade_level_age_group="6 and up" t:site_name="NYCHA EDENWALD HOUSES" m:row_number.pyif-r8qe=1

series e:pyif-r8qe d:2011-09-01T11:33:05.000Z t:contact_number="(718) 471-0360" t:program_type="After-School Programs,Beacon,NYCHA Centers" t:borough_community=Queens t:program="Beacon Satellite" t:agency="Police Athletic League @Redfern Community Center" t:grade_level_age_group="6 and up" t:site_name="NYCHA REDFERN HOUSES" m:row_number.pyif-r8qe=2

series e:pyif-r8qe d:2011-09-01T11:33:05.000Z t:contact_number="(718) 353-0385" t:program_type="After-School Programs,Beacon,NYCHA Centers" t:borough_community=Queens t:program="Beacon Satellite" t:agency="Child Center of New York @Lewis H. Latimer Gardens Community Center" t:grade_level_age_group="6 and up" t:site_name="NYCHA LATIMER GARDENS" m:row_number.pyif-r8qe=3
```

## Meta Commands

```ls
metric m:row_number.pyif-r8qe p:long l:"Row Number"

entity e:pyif-r8qe l:"DYCD after-school programs: Beacon Satellite At NYCHA Programs" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/pyif-r8qe

property e:pyif-r8qe t:meta.view v:id=pyif-r8qe v:category=Education v:averageRating=0 v:name="DYCD after-school programs: Beacon Satellite At NYCHA Programs" v:attribution="Department of Youth and Community Development (DYCD)"

property e:pyif-r8qe t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:pyif-r8qe t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type                               | program          | site_name                        | borough_community | agency                                                                 | contact_number | grade_level_age_group | 
| =========== | ========================================== | ================ | ================================ | ================= | ====================================================================== | ============== | ===================== | 
| 1314876785  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA EDENWALD HOUSES            | Bronx             | Mosholu Montefiore @Edenwald Community Center                          | (718) 652-0246 | 6 and up              | 
| 1314876785  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA REDFERN HOUSES             | Queens            | Police Athletic League @Redfern Community Center                       | (718) 471-0360 | 6 and up              | 
| 1314876785  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA LATIMER GARDENS            | Queens            | Child Center of New York @Lewis H. Latimer Gardens Community Center    | (718) 353-0385 | 6 and up              | 
| 1314876785  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA MARLBORO HOUSES            | Brooklyn          | Federation of Italian American Organization @Marlboro Community Center | (718) 449-1444 | 6 and up              | 
| 1314876785  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA BUSHWICK/HYLAN HOUSES      | Brooklyn          | YMCA-Eastern District @ Bushwick/Hylan Community Center                | (718) 453-8116 | 6 and up              | 
| 1314876785  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA DYCKMAN HOUSES             | Manhattan         | Alianza Dominicana, Inc. @Dyckman Community Center                     | (212) 567-8782 | 6 and up              | 
| 1314876785  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA TAYLOR-WYTHE AVENUE HOUSES | Brooklyn          | El Puente De Williamsburg @Taylor-Wythe Community Center               | (718) 333-0575 | 6 and up              | 
| 1314876785  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA PINK HOUSES                | Brooklyn          | East New York Development Corporation @ Louis H. Pink Community Center | (718) 964-9043 | 6 and up              | 
| 1314876785  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA SUMNER HOUSES              | Brooklyn          | YMCA-Eastern District @Sumner Community Center                         | (718) 919-4756 | 6 and up              | 
| 1314876785  | After-School Programs,Beacon,NYCHA Centers | Beacon Satellite | NYCHA JOHNSON HOUSES             | Manhattan         | SCAN @James Weldon Johnson Community Center                            | (212) 289-8819 | 6 and up              | 
```