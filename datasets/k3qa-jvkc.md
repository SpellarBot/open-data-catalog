# DYCD after-school programs: NDA Family Literacy

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-nda-family-literacy-01f3f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/k3qa-jvkc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/k3qa-jvkc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/k3qa-jvkc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | k3qa-jvkc |
| Name | DYCD after-school programs: NDA Family Literacy |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, community development, school, child, children, after-school, after-school programs, programs, young adult, civics, ... |
| Created | 2011-09-02T19:12:58Z |
| Publication Date | 2011-09-02T19:12:58Z |

## Description

Facilities in New York City, by agency and site, that offer ?NDA (Neighborhood Development Area) Reading and Writing Program? after-school  family literacy programs.  - Department of Youth and Community Development (DYCD).

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
series e:k3qa-jvkc d:2011-09-02T12:13:01.000Z t:contact_number=718-438-0008 t:program_type="Reading & Writing,NDA Programs,Family Literacy" t:borough_community=Brooklyn t:program="Family Literacy" t:agency="Brooklyn Chinese American Association" t:grade_level_age_group="A parent 16 Years Old or Older" t:site_name="Brooklyn Chinese American Association" m:row_number.k3qa-jvkc=1

series e:k3qa-jvkc d:2011-09-02T12:13:01.000Z t:contact_number=718-438-0008 t:program_type="Reading & Writing,NDA Programs,Family Literacy" t:borough_community=Brooklyn t:program="Family Literacy" t:agency="Brooklyn Chinese American Association" t:grade_level_age_group="A parent 16 Years Old or Older" t:site_name="Public School 105 - Blythebourne School" m:row_number.k3qa-jvkc=2

series e:k3qa-jvkc d:2011-09-02T12:13:01.000Z t:contact_number=212-949-4917 t:program_type="Reading & Writing,NDA Programs,Family Literacy" t:borough_community="New York" t:program="Family Literacy" t:agency="The Children's Aid Society" t:grade_level_age_group="A parent 16 Years Old or Older" t:site_name="Public School 8 - Luis Belliard School" m:row_number.k3qa-jvkc=3
```

## Meta Commands

```ls
metric m:row_number.k3qa-jvkc p:long l:"Row Number"

entity e:k3qa-jvkc l:"DYCD after-school programs: NDA Family Literacy" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/k3qa-jvkc

property e:k3qa-jvkc t:meta.view v:id=k3qa-jvkc v:category=Education v:averageRating=0 v:name="DYCD after-school programs: NDA Family Literacy" v:attribution="Department of Youth and Community Development (DYCD)"

property e:k3qa-jvkc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:k3qa-jvkc t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type                                   | program         | site_name                                         | borough_community | agency                                            | contact_number | grade_level_age_group          | 
| =========== | ============================================== | =============== | ================================================= | ================= | ================================================= | ============== | ============================== | 
| 1314965581  | Reading & Writing,NDA Programs,Family Literacy | Family Literacy | Brooklyn Chinese American Association             | Brooklyn          | Brooklyn Chinese American Association             | 718-438-0008   | A parent 16 Years Old or Older | 
| 1314965581  | Reading & Writing,NDA Programs,Family Literacy | Family Literacy | Public School 105 - Blythebourne School           | Brooklyn          | Brooklyn Chinese American Association             | 718-438-0008   | A parent 16 Years Old or Older | 
| 1314965581  | Reading & Writing,NDA Programs,Family Literacy | Family Literacy | Public School 8 - Luis Belliard School            | New York          | The Children's Aid Society                        | 212-949-4917   | A parent 16 Years Old or Older | 
| 1314965581  | Reading & Writing,NDA Programs,Family Literacy | Family Literacy | Public School 249 - The Caton School              | Brooklyn          | CAMBA, Inc.                                       | 718-282-5575   | A parent 16 Years Old or Older | 
| 1314965582  | Reading & Writing,NDA Programs,Family Literacy | Family Literacy | Public School 92 - Harry T Stewart Senior         | Queens            | Coalition for Hispanic Family Services            | 718-497-6090   | A parent 16 Years Old or Older | 
| 1314965582  | Reading & Writing,NDA Programs,Family Literacy | Family Literacy | Southeast Bronx Neighborhood Centers, Inc.        | Bronx             | Southeast Bronx Neighborhood Center, Inc. (SEBNC) | 718-542-2727   | A parent 16 Years Old or Older | 
| 1314965582  | Reading & Writing,NDA Programs,Family Literacy | Family Literacy | Public School 19 - Curtis School                  | Staten Island     | Jewish Community Center of Staten Island, Inc.    | 718-508-3883   | A parent 16 Years Old or Older | 
| 1314965582  | Reading & Writing,NDA Programs,Family Literacy | Family Literacy | Public School 73 - The Bronx School               | Bronx             | Highbridge Community Life Center (HCLC)           | 718-681-2222   | A parent 16 Years Old or Older | 
| 1314965582  | Reading & Writing,NDA Programs,Family Literacy | Family Literacy | Public School 199Q - Maurice Fitzgerald           | Queens            | Sunnyside Community Service, Inc.                 | 718-784-6173   | A parent 16 Years Old or Older | 
| 1314965582  | Reading & Writing,NDA Programs,Family Literacy | Family Literacy | Public School 198/77 - Isador & Ida Straus School | New York          | Stanley M. Isaacs Neighborhood Center, Inc.       | 212-360-7625   | A parent 16 Years Old or Older | 
```