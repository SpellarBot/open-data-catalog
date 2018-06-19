# DYCD after-school programs: Family Support Programs for Seniors

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-family-support-programs-for-seniors-7e0ce) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/dhs7-q59e) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/dhs7-q59e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/dhs7-q59e/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | dhs7-q59e |
| Name | DYCD after-school programs: Family Support Programs for Seniors |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Social Services |
| Tags | jobs and economic mobility, community, development, community development, school, after-school, after-school programs, programs, family, family support, seniors, older adults, lifelong learning |
| Created | 2011-09-06T20:19:52Z |
| Publication Date | 2013-06-21T19:32:19Z |

## Description

Facilities in New York City, by agency and site, that offer after-school Family Support Programs for seniors and older adults.Submitted by the Department of Youth and Community Development (DYCD).
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
series e:dhs7-q59e d:2011-09-06T13:19:55.000Z t:contact_number=800.624.8474 t:program_type="Family Support" t:borough_community=Bronx t:program=Seniors t:agency="Conscientious Musical Revues" t:grade_level_age_group=Seniors t:site_name="Pelham Parkway Senior Center" m:row_number.dhs7-q59e=1

series e:dhs7-q59e d:2011-09-06T13:19:56.000Z t:contact_number=718.627.5602 t:program_type="Family Support" t:borough_community=Flatbush t:program=Seniors t:agency="Council of Jewish Organizations of Flatbush" t:grade_level_age_group=Seniors t:site_name="COJO of Flatbush" m:row_number.dhs7-q59e=2

series e:dhs7-q59e d:2011-09-06T13:19:56.000Z t:contact_number=718.961.0888 t:program_type="Family Support" t:borough_community=Flushing t:program=Seniors t:agency="Asian Americans for Equality" t:grade_level_age_group=Seniors t:site_name="Asian Americans for Equality" m:row_number.dhs7-q59e=3
```

## Meta Commands

```ls
metric m:row_number.dhs7-q59e p:long l:"Row Number"

entity e:dhs7-q59e l:"DYCD after-school programs: Family Support  Programs for Seniors" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/dhs7-q59e

property e:dhs7-q59e t:meta.view v:id=dhs7-q59e v:category="Social Services" v:averageRating=0 v:name="DYCD after-school programs: Family Support  Programs for Seniors" v:attribution="Department of Youth and Community Development (DYCD)"

property e:dhs7-q59e t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:dhs7-q59e t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type   | program | site_name                     | borough_community | agency                                          | contact_number | grade_level_age_group | 
| =========== | ============== | ======= | ============================= | ================= | =============================================== | ============== | ===================== | 
| 1315315195  | Family Support | Seniors | Pelham Parkway Senior Center  | Bronx             | Conscientious Musical Revues                    | 800.624.8474   | Seniors               | 
| 1315315196  | Family Support | Seniors | COJO of Flatbush              | Flatbush          | Council of Jewish Organizations of Flatbush     | 718.627.5602   | Seniors               | 
| 1315315196  | Family Support | Seniors | Asian Americans for Equality  | Flushing          | Asian Americans for Equality                    | 718.961.0888   | Seniors               | 
| 1315315196  | Family Support | Seniors | U.J. C. of the East Side      | Lower East Side   | United Jewish Council of the East Side, Inc.    | 212.233.6037   | Seniors               | 
| 1315315196  | Family Support | Seniors | COJO of Flatbush              | Flatbush          | Council of Jewish Organizations of Flatbush     | 718.627.5602   | Seniors               | 
| 1315315196  | Family Support | Seniors | COJO of Flatbush              | Flatbush          | Council of Jewish Organizations of Flatbush     | 718.627.5602   | Seniors               | 
| 1315315196  | Family Support | Seniors | Greater Chinatown Comm. Assoc | Chinatown         | Greater Chinatown Community Association         | 212.374.1311   | Seniors               | 
| 1315315196  | Family Support | Seniors | Vladeck Cares N.O.R.C.        | New York          | Henry Street Settlement                         | 212.766.9200   | Seniors               | 
| 1315315196  | Family Support | Seniors | Riverdale YM-YWHA             | Bronx             | Riverdale YM-YWHA                               | 718.548.8200   | Seniors               | 
| 1315315196  | Family Support | Seniors | RAIN Inwood Senior Center     | New York          | Regional Aid For Interim Needs, Inc. (R.A.I.N.) | 718.892.5520   | Seniors               | 
```