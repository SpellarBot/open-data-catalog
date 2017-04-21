# DYCD after-school programs: Fatherhood

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-fatherhood-26bba) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/esw6-z4id) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/esw6-z4id/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/esw6-z4id/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | esw6-z4id |
| Name | DYCD after-school programs: Fatherhood |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Social Services |
| Tags | jobs and economic mobility, community, development, community development, school, after-school, after-school programs, programs, family, family support, fatherhood, initiative, fatherhood initiat... |
| Created | 2011-09-06T20:36:34Z |
| Publication Date | 2013-06-21T19:32:32Z |

## Description

Facilities in New York City, by agency and site, that offer Family Support after-school ?Fatherhood Initiative Programs? for young adults ages 16 to 24. Submitted by the Department of Youth and Community Development (DYCD).
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
series e:esw6-z4id d:2011-09-06T13:36:36.000Z t:contact_number=347.510.3619 t:program_type="Family Support" t:borough_community=Queens t:program="Fatherhood Initiative" t:agency="The Fortune Society, Inc." t:grade_level_age_group="16 to 24" t:site_name="Fortune Society" m:row_number.esw6-z4id=1

series e:esw6-z4id d:2011-09-06T13:36:36.000Z t:contact_number="646.613.9633 ext. 202" t:program_type="Family Support" t:borough_community="New York" t:program="Fatherhood Initiative" t:agency="Legal Information for Families Today (LIFT)" t:grade_level_age_group="16 to 24" t:site_name="The Fathers Center" m:row_number.esw6-z4id=2

series e:esw6-z4id d:2011-09-06T13:36:36.000Z t:contact_number=646.264.1329 t:program_type="Family Support" t:borough_community="New York" t:program="Fatherhood Initiative" t:agency="Fund for the City of New York/Center for Court Innovation" t:grade_level_age_group="16 to 24" t:site_name="Midtown Community Court" m:row_number.esw6-z4id=3
```

## Meta Commands

```ls
metric m:row_number.esw6-z4id p:long l:"Row Number"

entity e:esw6-z4id l:"DYCD after-school programs: Fatherhood" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/esw6-z4id

property e:esw6-z4id t:meta.view v:id=esw6-z4id v:category="Social Services" v:averageRating=0 v:name="DYCD after-school programs: Fatherhood" v:attribution="Department of Youth and Community Development (DYCD)"

property e:esw6-z4id t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:esw6-z4id t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type   | program               | site_name                                   | borough_community | agency                                                    | contact_number        | grade_level_age_group | 
| =========== | ============== | ===================== | =========================================== | ================= | ========================================================= | ===================== | ===================== | 
| 1315316196  | Family Support | Fatherhood Initiative | Fortune Society                             | Queens            | The Fortune Society, Inc.                                 | 347.510.3619          | 16 to 24              | 
| 1315316196  | Family Support | Fatherhood Initiative | The Fathers Center                          | New York          | Legal Information for Families Today (LIFT)               | 646.613.9633 ext. 202 | 16 to 24              | 
| 1315316196  | Family Support | Fatherhood Initiative | Midtown Community Court                     | New York          | Fund for the City of New York/Center for Court Innovation | 646.264.1329          | 16 to 24              | 
| 1315316196  | Family Support | Fatherhood Initiative | Oberia Dempsey Center                       | New York          | The Northern Manhattan Perinatal Partnership Inc.         | 212.665.2600          | 16 to 24              | 
| 1315316196  | Family Support | Fatherhood Initiative | Friends of the Island Academy               | New York          | Friends of Island Academy                                 | 212.760.0755          | 16 to 24              | 
| 1315316196  | Family Support | Fatherhood Initiative | Neighborhood Defender Service of Harlem     | New York          | Neighborhood Defender Service of Harlem                   | 212.876.5500          | 16 to 24              | 
| 1315316196  | Family Support | Fatherhood Initiative | Strive/East Harlem Employment Service, Inc. | New York          | East Harlem Employment Services, Inc.                     | 212.360.1100          | 16 to 24              | 
| 1315316196  | Family Support | Fatherhood Initiative | FRIENDS Program                             | Bronx             | Visiting Nurse Service of New York                        | 212.794.9200          | 16 to 24              | 
| 1315316196  | Family Support | Fatherhood Initiative | Family and Community Support Services       | Brooklyn          | Family and Community Support Services                     | 347.879.3367          | 16 to 24              | 
| 1315316196  | Family Support | Fatherhood Initiative | Parkside Houses                             | Bronx             | Friends of Island Academy                                 | 718.653.5301          | 16 to 24              | 
```