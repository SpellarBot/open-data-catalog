# DYCD after-school programs: Health Stat

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-health-stat-83606) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9f5k-vxxv) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9f5k-vxxv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9f5k-vxxv/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9f5k-vxxv |
| Name | DYCD after-school programs: Health Stat |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Social Services |
| Tags | jobs and economic mobility, community, development, community development, school, child, children, after-school, after-school programs, programs, family, family support, nda, neighborhood, neighb... |
| Created | 2011-09-02T20:32:13Z |
| Publication Date | 2013-06-21T19:32:13Z |

## Description

Facilities in New York City, by agency and site, that offer Neighborhood Development Area (NDA) ?Health Stat? after-school Family Support Programs. - Department of Youth and Community Development (DYCD). 
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
series e:9f5k-vxxv d:2011-09-02T13:32:15.000Z t:contact_number="(718) 418-7690" t:program_type="Family Support,NDA Programs" t:borough_community=Brooklyn t:program="Health Stat" t:agency="Make the Road New York" t:grade_level_age_group="All Ages" t:site_name="Make the Road New York" m:row_number.9f5k-vxxv=1

series e:9f5k-vxxv d:2011-09-02T13:32:15.000Z t:contact_number=(718)961-0888 t:program_type="Family Support,NDA Programs" t:borough_community=Queens t:program="Health Stat" t:agency="Asian Americans for Equality" t:grade_level_age_group="All Ages" t:site_name="Asian Americans for Equality" m:row_number.9f5k-vxxv=2

series e:9f5k-vxxv d:2011-09-02T13:32:15.000Z t:contact_number="(212) 822-8344" t:program_type="Family Support,NDA Programs" t:borough_community="New York" t:program="Health Stat" t:agency="Northern Manhattan Improvement Corporation" t:grade_level_age_group="All Ages" t:site_name="Northern Manhattan Improvement Corporation" m:row_number.9f5k-vxxv=3
```

## Meta Commands

```ls
metric m:row_number.9f5k-vxxv p:long l:"Row Number"

entity e:9f5k-vxxv l:"DYCD after-school programs: Health Stat" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/9f5k-vxxv

property e:9f5k-vxxv t:meta.view v:id=9f5k-vxxv v:category="Social Services" v:averageRating=0 v:name="DYCD after-school programs: Health Stat" v:attribution="Department of Youth and Community Development (DYCD)"

property e:9f5k-vxxv t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9f5k-vxxv t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type                | program     | site_name                                  | borough_community | agency                                     | contact_number  | grade_level_age_group | 
| =========== | =========================== | =========== | ========================================== | ================= | ========================================== | =============== | ===================== | 
| 1314970335  | Family Support,NDA Programs | Health Stat | Make the Road New York                     | Brooklyn          | Make the Road New York                     | (718) 418-7690  | All Ages              | 
| 1314970335  | Family Support,NDA Programs | Health Stat | Asian Americans for Equality               | Queens            | Asian Americans for Equality               | (718)961-0888   | All Ages              | 
| 1314970335  | Family Support,NDA Programs | Health Stat | Northern Manhattan Improvement Corporation | New York          | Northern Manhattan Improvement Corporation | (212) 822-8344  | All Ages              | 
| 1314970335  | Family Support,NDA Programs | Health Stat | The East New York Learning Center, Inc     | Brooklyn          | The East New York Learning Center, Inc     | (718) 756- 7200 | All Ages              | 
| 1314970335  | Family Support,NDA Programs | Health Stat | The Children's Aid Society                 | New York          | The Children's Aid Society                 | 212-503-6820    | All Ages              | 
| 1314970335  | Family Support,NDA Programs | Health Stat | The Children's Aid Society                 | Bronx             | The Children's Aid Society                 | (718) 617-8595  | All Ages              | 
| 1314970335  | Family Support,NDA Programs | Health Stat | Asian Americans for Equality               | Queens            | Asian Americans for Equality               | (718)961-0888   | All Ages              | 
| 1314970335  | Family Support,NDA Programs | Health Stat | Make the Road New York                     | Staten Island     | Make the Road New York                     | (347) 547-5133  | All Ages              | 
```