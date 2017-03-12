# DYCD after-school programs: Reading And Writing Literacy Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-reading-and-writing-literacy-programs-238fc) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/w9cy-nnma) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/w9cy-nnma/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/w9cy-nnma/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | w9cy-nnma |
| Name | DYCD after-school programs: Reading And Writing Literacy Programs |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, community development, school, child, children, after-school, after-school programs, programs, young adult, civics, ... |
| Created | 2011-09-02T18:40:22Z |
| Publication Date | 2011-09-02T18:40:22Z |
| Rows Updated | 2011-09-02T18:40:30Z |

## Description

Facilities in New York City, by agency and site, that offer after-school programs and resources for adult and adolescent literacy, family literacy, and English as a Second Language (ESOL) programs.
Update Schedule: Annually

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
entity e:w9cy-nnma l:"DYCD after-school programs: Reading And Writing Literacy Programs" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/w9cy-nnma

property e:w9cy-nnma t:meta.view v:id=w9cy-nnma v:category=Education v:averageRating=80 v:name="DYCD after-school programs: Reading And Writing Literacy Programs" v:attribution="Department of Youth and Community Development (DYCD)"

property e:w9cy-nnma t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:w9cy-nnma t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```