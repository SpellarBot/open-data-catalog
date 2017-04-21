# DYCD after-school programs: Immigrant Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-immigrant-services-d29b6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/zmut-au2w) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/zmut-au2w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/zmut-au2w/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | zmut-au2w |
| Name | DYCD after-school programs: Immigrant Services |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Social Services |
| Tags | jobs and economic mobility, community, development, community development, school, child, children, after-school, after-school programs, programs, immigration, immigrant, nda, legal assistance, le... |
| Created | 2011-09-02T20:14:11Z |
| Publication Date | 2013-06-21T19:32:00Z |

## Description

Facilities in New York City, by agency and site, that offer after-school programs for immigration services and immigrant support services. These include programs for legal assistance, legal services, refugee assistance, immigrant youth services, immigrant family services, and domestic violence programs.- Department of Youth and Community Development (DYCD). 
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
series e:zmut-au2w d:2011-09-02T13:14:11.000Z t:contact_number="212.349.6009           ext. 264" t:program_type="Immigration Services,Immigrant Support Services" t:borough_community="Manhattan,Bronx,Queens,Staten Island, Brooklyn" t:program="Legal Services" t:agency="Sanctuary for Families, Inc." t:grade_level_age_group="All Ages" t:site_name="Sanctuary for Families, Inc. (Manhattan)" m:row_number.zmut-au2w=1

series e:zmut-au2w d:2011-09-02T13:14:11.000Z t:contact_number="212.349.6009           ext. 264" t:program_type="Immigration Services,Immigrant Support Services" t:borough_community="Manhattan,Bronx,Queens,Staten Island, Brooklyn" t:program="Legal Services" t:agency="Sanctuary for Families, Inc." t:grade_level_age_group="All Ages" t:site_name="Family Justice Centers in Queens and Brooklyn" m:row_number.zmut-au2w=2

series e:zmut-au2w d:2011-09-02T13:14:11.000Z t:program_type="Immigration Services,Immigrant Support Services" t:borough_community="Manhattan,Bronx,Queens,Staten Island, Brooklyn" t:program="Legal Assistance Program" t:agency="Safe Horizon, Inc." t:grade_level_age_group="All Ages" t:site_name="Safe Horizon - Immigration Law Project" m:row_number.zmut-au2w=3
```

## Meta Commands

```ls
metric m:row_number.zmut-au2w p:long l:"Row Number"

entity e:zmut-au2w l:"DYCD after-school programs: Immigrant Services" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/zmut-au2w

property e:zmut-au2w t:meta.view v:id=zmut-au2w v:category="Social Services" v:averageRating=0 v:name="DYCD after-school programs: Immigrant Services" v:attribution="Department of Youth and Community Development (DYCD)"

property e:zmut-au2w t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:zmut-au2w t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type                                    | program                       | site_name                                                                                  | borough_community                              | agency                                    | contact_number        | grade_level_age_group | 
| =========== | =============================================== | ============================= | ========================================================================================== | ============================================== | ========================================= | ===================== | ===================== | 
| 1314969251  | Immigration Services,Immigrant Support Services | Legal Services                | Sanctuary for Families, Inc. (Manhattan)                                                   | Manhattan,Bronx,Queens,Staten Island, Brooklyn | Sanctuary for Families, Inc.              | 212.349.6009 ext. 264 | All Ages              | 
| 1314969251  | Immigration Services,Immigrant Support Services | Legal Services                | Family Justice Centers in Queens and Brooklyn                                              | Manhattan,Bronx,Queens,Staten Island, Brooklyn | Sanctuary for Families, Inc.              | 212.349.6009 ext. 264 | All Ages              | 
| 1314969251  | Immigration Services,Immigrant Support Services | Legal Assistance Program      | Safe Horizon - Immigration Law Project                                                     | Manhattan,Bronx,Queens,Staten Island, Brooklyn | Safe Horizon, Inc.                        |                       | All Ages              | 
| 1314969252  | Immigration Services,Immigrant Support Services | Domestic Violence Program     | Jewish Board of Family and Children Services (JBFCS)-Genesis                               | Manhattan                                      | New York Legal Assistance Group (NYLAG)   | 212.613.5098          | Adult                 | 
| 1314969252  | Immigration Services,Immigrant Support Services | Domestic Violence Program     | Edith and Carl Marks Jewish Community House of Bensonhurst                                 | Brooklyn                                       | New York Legal Assistance Group (NYLAG)   | 212.613.5000          | All Ages              | 
| 1314969252  | Immigration Services,Immigrant Support Services | Domestic Violence Program     | Jewish Board of Family and Children Services - Domestic Violence Coordination and Training | Bronx                                          | New York Legal Assistance Group (NYLAG)   | 212.613.5098          | Adult                 | 
| 1314969252  | Immigration Services,Immigrant Support Services | Domestic Violence Program     | New York Legal Assistance Group (NYLAG)                                                    | Manhattan                                      | New York Legal Assistance Group (NYLAG)   | 212.613.5000          | All Ages              | 
| 1314969252  | Immigration Services,Immigrant Support Services | Domestic Violence Program     | Jewish Board of Family and Children Services - Horizons                                    | Brooklyn                                       | New York Legal Assistance Group (NYLAG)   | 212.613.5098          | Adult                 | 
| 1314969252  | Immigration Services,Immigrant Support Services | Domestic Violence Program     | Bronx Neighborhood Office, Legal Aid Society                                               | Bronx                                          | The Legal Aid Society                     | 718.991.4758          | Adult                 | 
| 1314969252  | Immigration Services,Immigrant Support Services | Services - Immigrant Families | Harbor Heights Middle School - Children's Arts & Science                                   | Manhattan                                      | Children's Arts & Science Workshops, Inc. | 212-923-7766          | All Ages              | 
```