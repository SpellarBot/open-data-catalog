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
| Rows Updated | 2011-09-01T18:33:06Z |

## Description

Facilities in New York City, by agency and site, that offer ?Beacon Satellite at NYCHA Programs? after-school programs. Update Schedule: Annually

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
```

## Meta Commands

```ls
entity e:pyif-r8qe l:"DYCD after-school programs: Beacon Satellite At NYCHA Programs" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/pyif-r8qe

property e:pyif-r8qe t:meta.view d:2017-03-10T16:02:33.824Z v:id=pyif-r8qe v:category=Education v:averageRating=0 v:name="DYCD after-school programs: Beacon Satellite At NYCHA Programs" v:attribution="Department of Youth and Community Development (DYCD)"

property e:pyif-r8qe t:meta.view.owner d:2017-03-10T16:02:33.824Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:pyif-r8qe t:meta.view.tableauthor d:2017-03-10T16:02:33.824Z v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```