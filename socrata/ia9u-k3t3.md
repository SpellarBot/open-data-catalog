# DYCD after-school programs: NDA Adult Literacy Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-nda-adult-literacy-programs-7f0f0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ia9u-k3t3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ia9u-k3t3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ia9u-k3t3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ia9u-k3t3 |
| Name | DYCD after-school programs: NDA Adult Literacy Programs |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, community development, school, child, children, after-school, after-school programs, programs, young adult, civics, ... |
| Created | 2011-09-02T19:06:10Z |
| Publication Date | 2011-09-02T19:06:10Z |

## Description

Facilities in New York City, by agency and site, that offer ?Neighborhood Development Area (NDA) Reading and Writing Program? after-school adult literacy programs - the Department of Youth and Community Development (DYCD).
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
series e:ia9u-k3t3 d:2011-09-02T12:06:12.000Z t:contact_number="(212) 809-5935 x 104" t:program_type="Reading & Writing,NDA Programs,English Language Program,ESOL,Family Literacy" t:borough_community=Brooklyn t:program="Adult Literacy" t:agency="Agudath Israel of America Community Services, Inc." t:grade_level_age_group=16+ t:site_name="Project COPE / Adult Education" m:row_number.ia9u-k3t3=1

series e:ia9u-k3t3 d:2011-09-02T12:06:12.000Z t:contact_number="(718) 438-0008" t:program_type="Reading & Writing,NDA Programs,English Language Program,ESOL,Family Literacy" t:borough_community=Brooklyn t:program="Adult Literacy" t:agency="Brooklyn Chinese-American Association" t:grade_level_age_group=16+ t:site_name="Brooklyn Chinese-American Association" m:row_number.ia9u-k3t3=2

series e:ia9u-k3t3 d:2011-09-02T12:06:12.000Z t:contact_number="(718) 940-1737 x 424" t:program_type="Reading & Writing,NDA Programs,English Language Program,ESOL,Family Literacy,Adult Basic Education,ABE/GED" t:borough_community=Brooklyn t:program="Adult Literacy" t:agency=CAMBA t:grade_level_age_group=16+ t:site_name="PS 25 - Eubie Blake School" m:row_number.ia9u-k3t3=3
```

## Meta Commands

```ls
metric m:row_number.ia9u-k3t3 p:long l:"Row Number"

entity e:ia9u-k3t3 l:"DYCD after-school programs: NDA Adult Literacy Programs" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/ia9u-k3t3

property e:ia9u-k3t3 t:meta.view v:id=ia9u-k3t3 v:category=Education v:averageRating=0 v:name="DYCD after-school programs: NDA Adult Literacy Programs" v:attribution="Department of Youth and Community Development (DYCD)"

property e:ia9u-k3t3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ia9u-k3t3 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type                                                                                               | program        | site_name                                              | borough_community | agency                                                 | contact_number        | grade_level_age_group | 
| =========== | ========================================================================================================== | ============== | ====================================================== | ================= | ====================================================== | ===================== | ===================== | 
| 1314965172  | Reading & Writing,NDA Programs,English Language Program,ESOL,Family Literacy                               | Adult Literacy | Project COPE / Adult Education                         | Brooklyn          | Agudath Israel of America Community Services, Inc.     | (212) 809-5935 x 104  | 16+                   | 
| 1314965172  | Reading & Writing,NDA Programs,English Language Program,ESOL,Family Literacy                               | Adult Literacy | Brooklyn Chinese-American Association                  | Brooklyn          | Brooklyn Chinese-American Association                  | (718) 438-0008        | 16+                   | 
| 1314965172  | Reading & Writing,NDA Programs,English Language Program,ESOL,Family Literacy,Adult Basic Education,ABE/GED | Adult Literacy | PS 25 - Eubie Blake School                             | Brooklyn          | CAMBA                                                  | (718) 940-1737 x 424  | 16+                   | 
| 1314965172  | Reading & Writing,NDA Programs,English Language Program,ESOL,Family Literacy                               | Adult Literacy | Agudath Israel of America Community Services, Inc.     | New York          | Agudath Israel of America Community Services, Inc.     | (212) 809-5935 x 104  | 16+                   | 
| 1314965172  | Reading & Writing,NDA Programs,English Language Program,ESOL,Family Literacy                               | Adult Literacy | African Services Committee, Inc.                       | New York          | African Services Committee, Inc.                       | (212) 222-3882        | 16+                   | 
| 1314965172  | Reading & Writing,NDA Programs,English Language Program,ESOL,Family Literacy                               | Adult Literacy | Brooklyn Chinese-American Association                  | Brooklyn          | Brooklyn Chinese-American Association                  | (718) 438-0008        | 16+                   | 
| 1314965173  | Reading & Writing,NDA Programs,English Language Program,ESOL,Family Literacy                               | Adult Literacy | Opportunities for a Better Tomorrow                    | Brooklyn          | Opportunities for a Better Tomorrow                    | (718) 369-0303        | 16+                   | 
| 1314965173  | Reading & Writing,NDA Programs,English Language Program,ESOL,Family Literacy                               | Adult Literacy | Catholic Charities Neighborhood Services               | Astoria           | Catholic Charities Neighborhood Services               | (718) 726-9790 x 128  | 16+                   | 
| 1314965173  | Reading & Writing,NDA Programs,English Language Program,ESOL,Family Literacy                               | Adult Literacy | YMCA of Greater New York / ELESAIR                     | New York          | YMCA of Greater New York / ELESAIR                     | (212) 875-4336        | 16+                   | 
| 1314965173  | Reading & Writing,NDA Programs,English Language Program,ESOL,Family Literacy                               | Adult Literacy | Jewish Community Council of Greater Coney Island, Inc. | Brooklyn          | Jewish Community Council of Greater Coney Island, Inc. | (718) 449-5000 x 2237 | 16+                   | 
```