# DYCD after-school-programs: SYEP Summer Youth Employment Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-syep-summer-youth-employment-programs-229fc) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/q5x3-7piv) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/q5x3-7piv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/q5x3-7piv/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | q5x3-7piv |
| Name | DYCD after-school-programs: SYEP Summer Youth Employment Programs |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, community development, school, child, children, after-school, summer youth employment, summer, employment, internshi... |
| Created | 2011-09-01T20:13:45Z |
| Publication Date | 2011-09-01T20:13:45Z |

## Description

Facilities in New York City, by agency and site, that offer ?Summer Youth Employment (SYEP) Program? after-school  job and internship programs for children ages 14 to 24 - the Department of Youth and Community Development (DYCD).
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
series e:q5x3-7piv d:2011-09-01T13:13:47.000Z t:contact_number=718-599-2386 t:program_type="Jobs & Internships, Youth Employment" t:borough_community=Brooklyn t:program="Summer Youth Employment" t:agency="Asociaciones Dominicanas, Inc - Vulnerable Youth" t:grade_level_age_group="14 to 24" t:site_name="Asociaciones Dominicanas, Inc - Vulnerable Youth" m:row_number.q5x3-7piv=1

series e:q5x3-7piv d:2011-09-01T13:13:49.000Z t:contact_number=718-716-4021 t:program_type="Jobs & Internships, Youth Employment" t:borough_community=Bronx t:program="Summer Youth Employment" t:agency="Community Association of Progressive Dominicans - Bronx" t:grade_level_age_group="14 to 24" t:site_name="CIS 117" m:row_number.q5x3-7piv=2

series e:q5x3-7piv d:2011-09-01T13:13:49.000Z t:contact_number="212-860-6820 x5211" t:program_type="Jobs & Internships, Youth Employment" t:borough_community=Manhattan t:program="Summer Youth Employment" t:agency="East Harlem Council For Community Improvement" t:grade_level_age_group="14 to 24" t:site_name="East Harlem Council For Community Improvement" m:row_number.q5x3-7piv=3
```

## Meta Commands

```ls
metric m:row_number.q5x3-7piv p:long l:"Row Number"

entity e:q5x3-7piv l:"DYCD after-school-programs: SYEP Summer Youth Employment Programs" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/q5x3-7piv

property e:q5x3-7piv t:meta.view v:id=q5x3-7piv v:category=Education v:averageRating=0 v:name="DYCD after-school-programs: SYEP Summer Youth Employment Programs" v:attribution="Department of Youth and Community Development (DYCD)"

property e:q5x3-7piv t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:q5x3-7piv t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type                         | program                 | site_name                                        | borough_community | agency                                                  | contact_number     | grade_level_age_group | 
| =========== | ==================================== | ======================= | ================================================ | ================= | ======================================================= | ================== | ===================== | 
| 1314882827  | Jobs & Internships, Youth Employment | Summer Youth Employment | Asociaciones Dominicanas, Inc - Vulnerable Youth | Brooklyn          | Asociaciones Dominicanas, Inc - Vulnerable Youth        | 718-599-2386       | 14 to 24              | 
| 1314882829  | Jobs & Internships, Youth Employment | Summer Youth Employment | CIS 117                                          | Bronx             | Community Association of Progressive Dominicans - Bronx | 718-716-4021       | 14 to 24              | 
| 1314882829  | Jobs & Internships, Youth Employment | Summer Youth Employment | East Harlem Council For Community Improvement    | Manhattan         | East Harlem Council For Community Improvement           | 212-860-6820 x5211 | 14 to 24              | 
| 1314882829  | Jobs & Internships, Youth Employment | Summer Youth Employment | Betances Community Center                        | Bronx             | Aspira of New York, Inc.                                | 212-585-5040       | 14 to 24              | 
| 1314882829  | Jobs & Internships, Youth Employment | Summer Youth Employment | The Children's Aid Society                       | Manhattan         | The Children's Aid Society                              | 917-286-1535       | 14 to 24              | 
| 1314882829  | Jobs & Internships, Youth Employment | Summer Youth Employment | Chinese American Planning Council - Queens       | Queens            | Chinese American Planning Council - Queens              | 718-358-8899 x132  | 14 to 24              | 
| 1314882829  | Jobs & Internships, Youth Employment | Summer Youth Employment | Catholic Charities Neighborhood Services, Inc.   | Brooklyn          | Catholic Charities Neighborhood Services, Inc.          | 718-875-8801       | 14 to 24              | 
| 1314882829  | Jobs & Internships, Youth Employment | Summer Youth Employment | CAB Community Center                             | Bronx             | Citizens Advice Bureau, Inc.                            | 718-508-3193       | 14 to 24              | 
| 1314882829  | Jobs & Internships, Youth Employment | Summer Youth Employment | Childrens Arts & Science Workshops, Inc. -Man    | Manhattan         | Childrens Arts & Science Workshops, Inc. -Man           | 212-740-8170       | 14 to 24              | 
| 1314882829  | Jobs & Internships, Youth Employment | Summer Youth Employment | Childrens Arts & Science Workshops, Inc. -Bx     | Bronx             | Childrens Arts & Science Workshops, Inc. -Bx            | 718-220-4444       | 14 to 24              | 
```