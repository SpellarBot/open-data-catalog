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
series e:w9cy-nnma d:2011-09-02T11:40:24.000Z t:contact_number=718.282.5575 t:program_type="Reading & Writing" t:borough_community=Brooklyn t:program="Adolescent Literacy" t:agency="Church Ave. Merchants Block Assoc." t:grade_level_age_group="grades 6 to 8" t:site_name="School for Democracy and Leadership 600 Kingston Avenue" m:row_number.w9cy-nnma=1

series e:w9cy-nnma d:2011-09-02T11:40:25.000Z t:contact_number=212.652.2800 t:program_type="Reading & Writing" t:borough_community="New York" t:program="Adolescent Literacy" t:agency="Research Foundation of CUNY" t:grade_level_age_group="grades 6 to 8" t:site_name="Frederick Douglass Academy II (M860)" m:row_number.w9cy-nnma=2

series e:w9cy-nnma d:2011-09-02T11:40:25.000Z t:contact_number=212.652.2800 t:program_type="Reading & Writing" t:borough_community="New York" t:program="Adolescent Literacy" t:agency="Research Foundation of CUNY" t:grade_level_age_group="grades 6 to 8" t:site_name="CUNY/Creative Arts Team" m:row_number.w9cy-nnma=3
```

## Meta Commands

```ls
metric m:row_number.w9cy-nnma p:long l:"Row Number"

entity e:w9cy-nnma l:"DYCD after-school programs: Reading And Writing Literacy Programs" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/w9cy-nnma

property e:w9cy-nnma t:meta.view v:id=w9cy-nnma v:category=Education v:averageRating=80 v:name="DYCD after-school programs: Reading And Writing Literacy Programs" v:attribution="Department of Youth and Community Development (DYCD)"

property e:w9cy-nnma t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:displayName="NYC OpenData"

property e:w9cy-nnma t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type                                              | program             | site_name                                               | borough_community | agency                                       | contact_number | grade_level_age_group          | 
| =========== | ========================================================= | =================== | ======================================================= | ================= | ============================================ | ============== | ============================== | 
| 1314963624  | Reading & Writing                                         | Adolescent Literacy | School for Democracy and Leadership 600 Kingston Avenue | Brooklyn          | Church Ave. Merchants Block Assoc.           | 718.282.5575   | grades 6 to 8                  | 
| 1314963625  | Reading & Writing                                         | Adolescent Literacy | Frederick Douglass Academy II (M860)                    | New York          | Research Foundation of CUNY                  | 212.652.2800   | grades 6 to 8                  | 
| 1314963625  | Reading & Writing                                         | Adolescent Literacy | CUNY/Creative Arts Team                                 | New York          | Research Foundation of CUNY                  | 212.652.2800   | grades 6 to 8                  | 
| 1314963625  | Reading & Writing                                         | Adolescent Literacy | Environmental Science Sec School (M635)                 | New York          | Supportive Childrens Advocacy Network (SCAN) | 212.683.2522   | grades 6 to 8                  | 
| 1314963625  | Reading & Writing                                         | Adult Literacy      | Beacon Family Center at IS 8                            | Queens            | SQPA-NY Southern Queens Park Association NY  | 718.276.4630   | At least 16 Years Old or Older | 
| 1314963625  | Reading & Writing                                         | Adult Literacy      | Union Settlement Association                            | New York          | Union Settlement Association                 | 212.828.6016   | At least 16 Years Old or Older | 
| 1314963625  | Reading & Writing                                         | Adult Literacy      | SCO Family of Services                                  | Brooklyn          | SCO Family of Services                       | 718.455.1166   | At least 16 Years Old or Older | 
| 1314963625  | Reading & Writing                                         | Adult Literacy      | The Arab American Family Support Center                 | Brooklyn          | The Arab American Family Support Center      | 718.643.8000   | At least 16 Years Old or Older | 
| 1314963625  | Reading & Writing                                         | Adult Literacy      | Make the Road New York                                  | Staten Island     | Make the Road New York                       | 718.418.7690   | At least 16 Years Old or Older | 
| 1314963625  | Reading & Writing,English Language Program,Adult Literacy | ESOL                | Henry Street Settlement - Workforce Development Center  | New York          | Henry Street Settlement, Inc.                | 212.766.9200   | ESOL/Civics                    | 
```