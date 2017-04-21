# DYCD after-school programs: Adolescent Literacy

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-adolescent-literacy-d8013) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/a8rp-fpnn) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/a8rp-fpnn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/a8rp-fpnn/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | a8rp-fpnn |
| Name | DYCD after-school programs: Adolescent Literacy |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, community development, school, child, children, after-school, after-school programs, programs, young adult, civics, ... |
| Created | 2011-09-02T18:59:21Z |
| Publication Date | 2011-09-02T18:59:21Z |

## Description

Facilities in New York City, by agency and site, that offer after-school programs and learning resources for adolescent literacy. Update Schedule: Annually

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
series e:a8rp-fpnn d:2011-09-02T11:59:22.000Z t:contact_number=718.282.5575 t:program_type="Reading & Writing" t:borough_community=Brooklyn t:program="Adolescent Literacy" t:agency=CAMBA t:grade_level_age_group="grades 6 to 8" t:site_name="K 533- School for Democracy and Leadership 600 Kingston Avenue" m:row_number.a8rp-fpnn=1

series e:a8rp-fpnn d:2011-09-02T11:59:23.000Z t:contact_number=212.740.8655 t:program_type="Reading & Writing" t:borough_community="New York" t:program="Adolescent Literacy" t:agency="The Children's Aid Society" t:grade_level_age_group="grades 6 to 8" t:site_name="MS 324 - Patria Mirabal School" m:row_number.a8rp-fpnn=2

series e:a8rp-fpnn d:2011-09-02T11:59:23.000Z t:contact_number=212.683.2522 t:program_type="Reading & Writing" t:borough_community=Bronx t:program="Adolescent Literacy" t:agency="Supportive Childrens Advocacy Network (SCAN)" t:grade_level_age_group="grades 6 to 8" t:site_name="JHS 22- Jordan L Mott School" m:row_number.a8rp-fpnn=3
```

## Meta Commands

```ls
metric m:row_number.a8rp-fpnn p:long l:"Row Number"

entity e:a8rp-fpnn l:"DYCD after-school programs: Adolescent Literacy" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/a8rp-fpnn

property e:a8rp-fpnn t:meta.view v:id=a8rp-fpnn v:category=Education v:averageRating=0 v:name="DYCD after-school programs: Adolescent Literacy" v:attribution="Department of Youth and Community Development (DYCD)"

property e:a8rp-fpnn t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:a8rp-fpnn t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type      | program             | site_name                                                      | borough_community | agency                                       | contact_number        | grade_level_age_group | 
| =========== | ================= | =================== | ============================================================== | ================= | ============================================ | ===================== | ===================== | 
| 1314964762  | Reading & Writing | Adolescent Literacy | K 533- School for Democracy and Leadership 600 Kingston Avenue | Brooklyn          | CAMBA                                        | 718.282.5575          | grades 6 to 8         | 
| 1314964763  | Reading & Writing | Adolescent Literacy | MS 324 - Patria Mirabal School                                 | New York          | The Children's Aid Society                   | 212.740.8655          | grades 6 to 8         | 
| 1314964763  | Reading & Writing | Adolescent Literacy | JHS 22- Jordan L Mott School                                   | Bronx             | Supportive Childrens Advocacy Network (SCAN) | 212.683.2522          | grades 6 to 8         | 
| 1314964763  | Reading & Writing | Adolescent Literacy | M.S. 860 Frederick Douglass Academy II                         | New York          | Creative Arts Team/CUNY                      | 212.652.2800          | grades 6 to 8         | 
| 1314964763  | Reading & Writing | Adolescent Literacy | M.S. 635- Academy for Enviornmental Sciences                   | New York          | Supportive Childrens Advocacy Network (SCAN) | 212.683.2522          | grades 6 to 8         | 
| 1314964763  | Reading & Writing | Adolescent Literacy | M.S. 368- IN-Tech Academy                                      | Bronx             | Creative Arts Team/CUNY                      | 212.652.2800          | grades 6 to 8         | 
| 1314964763  | Reading & Writing | Adolescent Literacy | I.S.168 - Parsons School                                       | Queens            | The Child Center of NY                       | 718.458.4243 ext. 205 | grades 6 to 8         | 
| 1314964763  | Reading & Writing | Adolescent Literacy | MS 35- Decatur Clearpool School                                | Brooklyn          | Stanton Heiskell Center                      | 212.817.2106          | grades 6 to 8         | 
| 1314964763  | Reading & Writing | Adolescent Literacy | Q 705- The Renaissance Charter School                          | Queens            | Creative Arts Team/CUNY                      | 212.652.2800          | grades 6 to 8         | 
| 1314964763  | Reading & Writing | Adolescent Literacy | I.S. 126- Astoria Intermediate School                          | Queens            | Jacob Riis Neighborhood Settlement           | 718.204.6797          | grades 6 to 8         | 
```