# DYCD after-school programs: Neighborhood Development Area (NDA) Family Support

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-neighborhood-development-area-nda-family-support-461c6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/chv4-k4fa) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/chv4-k4fa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/chv4-k4fa/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | chv4-k4fa |
| Name | DYCD after-school programs: Neighborhood Development Area (NDA) Family Support |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, community development, school, child, children, after-school, after-school programs, programs, employment, internshi... |
| Created | 2011-09-06T20:51:41Z |
| Publication Date | 2011-09-06T20:51:41Z |

## Description

A database of facilities in New York City, by agency and site, that offer NDA (Neighborhood Development Area) after-school ?Family Support Programs,? including immigrant services, legal assistance, domestic violence, health, housing and literacy programs for adults, seniors, young adults and children of all ages

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
series e:chv4-k4fa d:2011-09-06T13:51:44.000Z t:contact_number=718.282.5575 t:program_type="Reading & Writing,NDA Programs,Family Literacy" t:borough_community=Brooklyn t:program="Adolescent Literacy" t:agency=CAMBA t:grade_level_age_group="grades 6 to 8" t:site_name="K 533- School for Democracy and Leadership 600 Kingston Avenue" m:row_number.chv4-k4fa=1

series e:chv4-k4fa d:2011-09-06T13:51:44.000Z t:contact_number="(718) 592-5757" t:program_type="After-School Programs,NDA Programs,Youth Educational Support" t:borough_community=Queens t:program="High-School Aged Youth" t:agency="Central Brooklyn Economic Development Corporation" t:grade_level_age_group="High School" t:site_name="Voyagees Prepatory High School" m:row_number.chv4-k4fa=2

series e:chv4-k4fa d:2011-09-06T13:51:44.000Z t:contact_number="(718) 896-2500" t:program_type="Family Support,NDA Programs" t:borough_community=Queens t:program=Housing t:agency="St. Luke A.M.E Church" t:grade_level_age_group=Adults t:site_name="AIDS Center of Queens County Jamaica Site" m:row_number.chv4-k4fa=3
```

## Meta Commands

```ls
metric m:row_number.chv4-k4fa p:long l:"Row Number"

entity e:chv4-k4fa l:"DYCD after-school programs: Neighborhood Development Area (NDA) Family Support" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/chv4-k4fa

property e:chv4-k4fa t:meta.view v:id=chv4-k4fa v:category=Education v:averageRating=80 v:name="DYCD after-school programs: Neighborhood Development Area (NDA) Family Support" v:attribution="Department of Youth and Community Development (DYCD)"

property e:chv4-k4fa t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:chv4-k4fa t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type                                                 | program                  | site_name                                                      | borough_community                              | agency                                            | contact_number        | grade_level_age_group          | 
| =========== | ============================================================ | ======================== | ============================================================== | ============================================== | ================================================= | ===================== | ============================== | 
| 1315317104  | Reading & Writing,NDA Programs,Family Literacy               | Adolescent Literacy      | K 533- School for Democracy and Leadership 600 Kingston Avenue | Brooklyn                                       | CAMBA                                             | 718.282.5575          | grades 6 to 8                  | 
| 1315317104  | After-School Programs,NDA Programs,Youth Educational Support | High-School Aged Youth   | Voyagees Prepatory High School                                 | Queens                                         | Central Brooklyn Economic Development Corporation | (718) 592-5757        | High School                    | 
| 1315317104  | Family Support,NDA Programs                                  | Housing                  | AIDS Center of Queens County Jamaica Site                      | Queens                                         | St. Luke A.M.E Church                             | (718) 896-2500        | Adults                         | 
| 1315317116  | Family Support,NDA Programs                                  | Housing                  | Project Home                                                   | New York                                       | Refugee and Immigrant Services                    | (212) 674-9120        | Adults                         | 
| 1315317121  | Family Support,NDA Programs                                  | Healthy Families         | SSAW                                                           | Queens                                         | Bushwick Campus                                   | (212) 714-9153        |                                | 
| 1315317104  | Immigration Services,Immigrant Support Services              | Legal Services           | Sanctuary for Families, Inc. (Manhattan)                       | Manhattan,Bronx,Queens,Staten Island, Brooklyn | Sanctuary for Families, Inc.                      | 212.349.6009 ext. 264 | All Ages                       | 
| 1315317104  | Immigration Services,Immigrant Support Services              | Legal Services           | Family Justice Centers in Queens and Brooklyn                  | Manhattan,Bronx,Queens,Staten Island, Brooklyn | Sanctuary for Families, Inc.                      | 212.349.6009 ext. 264 | All Ages                       | 
| 1315317104  | Immigration Services,Immigrant Support Services              | Legal Assistance Program | Safe Horizon - Immigration Law Project                         | Manhattan,Bronx,Queens,Staten Island, Brooklyn | Safe Horizon, Inc.                                |                       | All Ages                       | 
| 1315317106  | Reading & Writing,NDA Programs,Family Literacy               | Family Literacy          | Public School 105 - Blythebourne School                        | Brooklyn                                       | Brooklyn Chinese American Association             | 718-438-0008          | A parent 16 Years Old or Older | 
| 1315317106  | Reading & Writing,NDA Programs,Family Literacy               | Family Literacy          | Public School 249 - The Caton School                           | Brooklyn                                       | CAMBA, Inc.                                       | 718-282-5575          | A parent 16 Years Old or Older | 
```