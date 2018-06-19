# DYCD after-school-programs: Housing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-housing-fcb7b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/fqcv-e9sg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/fqcv-e9sg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/fqcv-e9sg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | fqcv-e9sg |
| Name | DYCD after-school-programs: Housing |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Social Services |
| Tags | jobs and economic mobility, community, development, community development, school, after-school, after-school programs, programs, family, family support, housing assistance and advocacy, housing a... |
| Created | 2011-09-06T20:28:38Z |
| Publication Date | 2013-06-21T19:32:07Z |

## Description

Facilities in New York City, by agency and site, that offer Family Support after-school ?Housing Assistance and Advocacy Programs? for adults and young adults ages 18 and up - Department of Youth and Community Development (DYCD).
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
series e:fqcv-e9sg d:2011-09-06T13:28:40.000Z t:contact_number=718.293.0727 t:program_type="Family Support" t:borough_community=Bronx t:program="Housing Assistance & Advocacy" t:agency="Citizens Advice Bureau, Inc." t:grade_level_age_group=Adults t:site_name="Bedford Park" m:row_number.fqcv-e9sg=1

series e:fqcv-e9sg d:2011-09-06T13:28:39.000Z t:contact_number=718.435.7585 t:program_type="Family Support" t:borough_community=Brooklyn t:program="Housing Assistance & Advocacy" t:agency="Brooklyn Housing and Family Services, Inc." t:grade_level_age_group=Adults t:site_name="Brooklyn Housing and Family Services, Inc." m:row_number.fqcv-e9sg=2

series e:fqcv-e9sg d:2011-09-06T13:28:39.000Z t:contact_number=718.859.4763 t:program_type="Family Support" t:borough_community=Brooklyn t:program="Housing Assistance & Advocacy" t:agency="Flatbush Development Corporation" t:grade_level_age_group=Adults t:site_name="Flatbush Development Corporation" m:row_number.fqcv-e9sg=3
```

## Meta Commands

```ls
metric m:row_number.fqcv-e9sg p:long l:"Row Number"

entity e:fqcv-e9sg l:"DYCD after-school-programs: Housing" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/fqcv-e9sg

property e:fqcv-e9sg t:meta.view v:id=fqcv-e9sg v:category="Social Services" v:averageRating=0 v:name="DYCD after-school-programs: Housing" v:attribution="Department of Youth and Community Development (DYCD)"

property e:fqcv-e9sg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:fqcv-e9sg t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type   | program                       | site_name                                                  | borough_community | agency                                                     | contact_number | grade_level_age_group | 
| =========== | ============== | ============================= | ========================================================== | ================= | ========================================================== | ============== | ===================== | 
| 1315315720  | Family Support | Housing Assistance & Advocacy | Bedford Park                                               | Bronx             | Citizens Advice Bureau, Inc.                               | 718.293.0727   | Adults                | 
| 1315315719  | Family Support | Housing Assistance & Advocacy | Brooklyn Housing and Family Services, Inc.                 | Brooklyn          | Brooklyn Housing and Family Services, Inc.                 | 718.435.7585   | Adults                | 
| 1315315719  | Family Support | Housing Assistance & Advocacy | Flatbush Development Corporation                           | Brooklyn          | Flatbush Development Corporation                           | 718.859.4763   | Adults                | 
| 1315315719  | Family Support | Housing Assistance & Advocacy | Cooper Square Community Development & Business Association | New York          | Cooper Square Community Development & Business Association | 212.228.8210   | Adults                | 
| 1315315719  | Family Support | Housing Assistance & Advocacy | Stryckers Bay Neighborhood Council, Inc.                   | New York          | Stryckers Bay Neighborhood Council, Inc.                   | 212.874.7272   | Adults                | 
| 1315315719  | Family Support | Housing Assistance & Advocacy | Catholic Charities Community Services-Washington Heights   | New York          | Catholic Charities Community Service, Archdiocese of N Y   | 212.371.1000   | Adults                | 
| 1315315719  | Family Support | Housing Assistance & Advocacy | AAFE Chinatown / Lower East Side                           | New York          | Asian Americans for Equality                               | 212.680.1374   | Adults                | 
| 1315315720  | Family Support | Housing Assistance & Advocacy | Flatbush Development Corporation                           | Brooklyn          | Flatbush Development Corporation                           | 718.859.3800   | Adults                | 
| 1315315719  | Family Support | Housing Assistance & Advocacy | Catholic Charities Community Service, Archdiocese of N Y   | New York          | Catholic Charities Community Service, Archdiocese of N Y   | 212.371.1000   | Adults                | 
| 1315315720  | Family Support | Housing Assistance & Advocacy | Northern Manhattan Improvement Corporation                 | New York          | Northern Manhattan Improvement Corporation                 | 212.822.8300   | Adults                | 
```