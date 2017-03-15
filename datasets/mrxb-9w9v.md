# DYCD after-school programs: NDA Youth Employment Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-nda-youth-employment-programs-791a7) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mrxb-9w9v) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mrxb-9w9v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mrxb-9w9v/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mrxb-9w9v |
| Name | DYCD after-school programs: NDA Youth Employment Programs |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, community development, school, child, children, after-school, after-school programs, programs, employment, internshi... |
| Created | 2011-09-01T21:00:43Z |
| Publication Date | 2011-09-01T21:00:43Z |
| Rows Updated | 2011-09-01T21:00:49Z |

## Description

Facilities in New York City, by agency and site, that offer “NDA Neighborhood Development Area Youth Employment  Program” after-school  job and internship programs for children and young adults ages 14 to 21 in Middle School, in High School, or in all grades.
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
series e:mrxb-9w9v d:2011-09-01T14:00:46.000Z t:contact_number=718-599-2386 t:program_type="Jobs & Internships, Youth Employment" t:borough_community=Brooklyn t:program="Summer Youth Employment" t:agency="Asociaciones Dominicanas, Inc." t:grade_level_age_group="14 to 21" t:site_name="Asociaciones Dominicanas, Inc - Vulnerable Youth" m:row_number.mrxb-9w9v=1

series e:mrxb-9w9v d:2011-09-01T14:00:47.000Z t:contact_number=212.678.0037 t:program_type="Youth Employment, NDA Youth Employment" t:borough_community="New York" t:program="Youth Employment" t:agency="Ecumenical Community Development Organization" t:grade_level_age_group=HS t:site_name="ECDO Community Partnership Center" m:row_number.mrxb-9w9v=2

series e:mrxb-9w9v d:2011-09-01T14:00:47.000Z t:contact_number=212.427.2244 t:program_type="Youth Employment, NDA Youth Employment" t:borough_community="New York" t:program="Youth Employment" t:agency="Boys & Girls Harbor, Inc" t:site_name="Boys & Girls Harbor, Inc" m:row_number.mrxb-9w9v=3
```

## Meta Commands

```ls
metric m:row_number.mrxb-9w9v p:long l:"Row Number"

entity e:mrxb-9w9v l:"DYCD after-school programs: NDA Youth Employment Programs" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/mrxb-9w9v

property e:mrxb-9w9v t:meta.view v:id=mrxb-9w9v v:category=Education v:averageRating=0 v:name="DYCD after-school programs: NDA Youth Employment Programs" v:attribution="Department of Youth and Community Development (DYCD)"

property e:mrxb-9w9v t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:mrxb-9w9v t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```