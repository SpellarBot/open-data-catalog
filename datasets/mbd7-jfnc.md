# DYCD after-school programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-6dc9b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mbd7-jfnc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mbd7-jfnc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mbd7-jfnc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mbd7-jfnc |
| Name | DYCD after-school programs |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, school, child, children, lifelong learning |
| Created | 2011-08-31T18:20:25Z |
| Publication Date | 2011-08-31T18:20:25Z |

## Description

After-school programs in New York City, organized by various categories and for various audiences. Update Frequency: Annually

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
series e:mbd7-jfnc d:2011-08-31T11:20:30.000Z t:contact_number="Contact Number" t:program_type="PROGRAM TYPE" t:borough_community="BOROUGH / COMMUNITY" t:program=PROGRAM t:agency=AGENCY t:grade_level_age_group="Grade Level / Age Group" t:site_name="SITE NAME" m:row_number.mbd7-jfnc=1

series e:mbd7-jfnc d:2011-08-31T11:20:30.000Z t:contact_number=718.556.1565 t:program_type="After-School Programs" t:borough_community="Staten Island" t:program=Beacon t:agency="Jewish Community Center of Staten Island" t:grade_level_age_group="6 and up" t:site_name="IS 49" m:row_number.mbd7-jfnc=2

series e:mbd7-jfnc d:2011-08-31T11:20:30.000Z t:contact_number=718.589.1510 t:program_type="After-School Programs,Jobs & Internships,Youth Employment" t:borough_community=Bronx t:program="In-School Youth Employment (ISY)" t:agency="Simpson Street Development Association, Inc." t:grade_level_age_group="High School" t:site_name="Intermediate School 217 - Rafael Hernandez School" m:row_number.mbd7-jfnc=3
```

## Meta Commands

```ls
metric m:row_number.mbd7-jfnc p:long l:"Row Number"

entity e:mbd7-jfnc l:"DYCD after-school programs" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/mbd7-jfnc

property e:mbd7-jfnc t:meta.view v:id=mbd7-jfnc v:category=Education v:averageRating=80 v:name="DYCD after-school programs" v:attribution="Department of Youth and Community Development (DYCD)"

property e:mbd7-jfnc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:mbd7-jfnc t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type                                                 | program                          | site_name                                                      | borough_community   | agency                                            | contact_number | grade_level_age_group   | 
| =========== | ============================================================ | ================================ | ============================================================== | =================== | ================================================= | ============== | ======================= | 
| 1314789630  | PROGRAM TYPE                                                 | PROGRAM                          | SITE NAME                                                      | BOROUGH / COMMUNITY | AGENCY                                            | Contact Number | Grade Level / Age Group | 
| 1314789630  | After-School Programs                                        | Beacon                           | IS 49                                                          | Staten Island       | Jewish Community Center of Staten Island          | 718.556.1565   | 6 and up                | 
| 1314789630  | After-School Programs,Jobs & Internships,Youth Employment    | In-School Youth Employment (ISY) | Intermediate School 217 - Rafael Hernandez School              | Bronx               | Simpson Street Development Association, Inc.      | 718.589.1510   | High School             | 
| 1314789631  | After-School Programs                                        | Out of School Time               | Building T 149                                                 | Queens              | Rockaway Artist Alliance, Inc.                    | (718) 474-0861 | Elem/MS                 | 
| 1314789632  | Reading & Writing,NDA Programs,Family Literacy               | Adolescent Literacy              | K 533- School for Democracy and Leadership 600 Kingston Avenue | Brooklyn            | CAMBA                                             | 718.282.5575   | grades 6 to 8           | 
| 1314789632  | After-School Programs,NDA Programs,Youth Educational Support | High-School Aged Youth           | Voyagees Prepatory High School                                 | Queens              | Central Brooklyn Economic Development Corporation | (718) 592-5757 | High School             | 
| 1314789632  | Family Support,NDA Programs                                  | Housing                          | AIDS Center of Queens County Jamaica Site                      | Queens              | St. Luke A.M.E Church                             | (718) 896-2500 | Adults                  | 
| 1314789632  | Immigration Services,Immigrant Support Services              | Domestic Violence Program        | Jewish Board of Family and Children Services (JBFCS)-Genesis   | Manhattan           | New York Legal Assistance Group (NYLAG)           | 212.613.5098   | Adult                   | 
| 1314789638  | Family Support,NDA Programs                                  | Fatherhood Initiative            | Nursing Family Partnership                                     | Bronx               | Visiting Nurse Service of New York                | 718.402.3900   | 16 to 24                | 
| 1314789632  | Immigration Services,Immigrant Support Services              | Domestic Violence Program        | Jewish Board of Family and Children Services - Horizons        | Brooklyn            | New York Legal Assistance Group (NYLAG)           | 212.613.5098   | Adult                   | 
```