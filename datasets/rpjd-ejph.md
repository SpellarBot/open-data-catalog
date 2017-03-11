# TABLE III. Deaths in 122 U.S. cities

## Dataset

* [Dataset URL](https://data.cdc.gov/api/views/rpjd-ejph/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/table-iii-deaths-in-122-u-s-cities)
* Id = rpjd-ejph
* Name = TABLE III. Deaths in 122 U.S. cities
* Attribution = National Center for Immunization and Respiratory Diseases (NCIRD)
* Category = NNDSS
* Tags = [2016, 122 cities, mortality, death, pneumonia, influenza]
* Created = 2016-01-12T14:32:29Z
* Publication Date = 2016-10-06T16:10:10Z
* Rows Updated = 2016-10-06T02:20:55Z

## Description

TABLE III. Deaths in 122 U.S. cities ? 2016.  122 Cities Mortality Reporting System ? Each week, the vital statistics offices of 122 cities across the United States report the total number of death certificates processed and the number of those for which pneumonia or influenza was listed as the underlying or contributing cause of death by age group (Under 28 days, 28 days ?1 year, 1-14 years, 15-24 years, 25-44 years, 45-64 years, 65-74 years, 75-84 years, and ? 85 years).

FOOTNOTE:
U: Unavailable. ?: No reported cases.
* Mortality data in this table are voluntarily reported from 122 cities in the United States, most of which have populations of 100,000 or more. A death is reported by the place of its occurrence and by the week that the death certificate was filed. Fetal deaths are not included. 

? Pneumonia and influenza. 

? Total includes unknown ages.

## Columns

```ls
| Name                                         | Field Name                            | Data Type | Render Type | Schema Type    | Included | 
| ============================================ | ===================================== | ========= | =========== | ============== | ======== | 
| Reporting Area                               | reporting_area                        | text      | text        | series tag     | Yes      | 
| MMWR YEAR                                    | mmwr_year                             | number    | number      |                | No       | 
| MMWR WEEK                                    | mmwr_week                             | number    | number      |                | No       | 
| All causes, by age (years), All Ages**       | all_causes_by_age_years_all_ages      | number    | number      | numeric metric | Yes      | 
| All causes, by age (years), All Ages**, flag | all_causes_by_age_years_all_ages_flag | number    | text        | numeric metric | Yes      | 
| All causes, by age (years), ?65              | all_causes_by_age_years_65            | number    | number      | numeric metric | Yes      | 
| All causes, by age (years), ?65, flag        | all_causes_by_age_years_65_flag       | number    | text        | numeric metric | Yes      | 
| All causes, by age (years), 45?64            | all_causes_by_age_years_45_64         | number    | number      | numeric metric | Yes      | 
| All causes, by age (years), 45?64, flag      | all_causes_by_age_years_45_64_flag    | number    | text        | numeric metric | Yes      | 
| All causes, by age (years), 25?44            | all_causes_by_age_years_25_44         | number    | number      | numeric metric | Yes      | 
| All causes, by age (years), 25?44, flag      | all_causes_by_age_years_25_44_flag    | number    | text        | numeric metric | Yes      | 
| All causes, by age (years), 1?24             | all_causes_by_age_years_1_24          | number    | number      | numeric metric | Yes      | 
| All causes, by age (years), 1?24, flag       | all_causes_by_age_years_1_24_flag     | number    | text        | numeric metric | Yes      | 
| All causes, by age (years), LT 1             | all_causes_by_age_years_lt_1          | number    | number      | numeric metric | Yes      | 
| All causes, by age (years), LT 1, flag       | all_causes_by_age_years_lt_1_flag     | number    | text        | numeric metric | Yes      | 
| P&I? Total                                   | p_i_total                             | number    | number      | numeric metric | Yes      | 
| P&I? Total, flag                             | p_i_total_flag                        | number    | text        | numeric metric | Yes      | 
```

## Time Field

```ls
Value = mmwr_year+mmwr_week
Format & Zone = yyyy+w
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = mmwr_year,mmwr_week
Annotation Fields = 
```

## Data Commands

```ls
series e:rpjd-ejph d:2016-01-08T00:00:00.000Z t:reporting_area="New England" m:all_causes_by_age_years_all_ages=600 m:p_i_total=47 m:all_causes_by_age_years_65=426 m:all_causes_by_age_years_1_24=12 m:all_causes_by_age_years_45_64=125 m:all_causes_by_age_years_lt_1=9 m:all_causes_by_age_years_25_44=28

series e:rpjd-ejph d:2016-01-08T00:00:00.000Z t:reporting_area="Mid. Atlantic" m:all_causes_by_age_years_all_ages=807 m:p_i_total=32 m:all_causes_by_age_years_65=563 m:all_causes_by_age_years_1_24=13 m:all_causes_by_age_years_45_64=181 m:all_causes_by_age_years_lt_1=18 m:all_causes_by_age_years_25_44=32

series e:rpjd-ejph d:2016-01-08T00:00:00.000Z t:reporting_area="E.N. Central" m:all_causes_by_age_years_all_ages=2468 m:p_i_total=159 m:all_causes_by_age_years_65=1611 m:all_causes_by_age_years_1_24=62 m:all_causes_by_age_years_45_64=594 m:all_causes_by_age_years_lt_1=34 m:all_causes_by_age_years_25_44=167
```

## Meta Commands

```ls
metric m:all_causes_by_age_years_all_ages p:integer l:"All causes, by age (years), All Ages**" t:dataTypeName=number

metric m:all_causes_by_age_years_65 p:integer l:"All causes, by age (years), ?65" t:dataTypeName=number

metric m:all_causes_by_age_years_45_64 p:integer l:"All causes, by age (years), 45?64" t:dataTypeName=number

metric m:all_causes_by_age_years_25_44 p:integer l:"All causes, by age (years), 25?44" t:dataTypeName=number

metric m:all_causes_by_age_years_1_24 p:integer l:"All causes, by age (years), 1?24" t:dataTypeName=number

metric m:all_causes_by_age_years_lt_1 p:integer l:"All causes, by age (years), LT 1" t:dataTypeName=number

metric m:p_i_total p:integer l:"P&I? Total" t:dataTypeName=number

entity e:rpjd-ejph l:"TABLE III. Deaths in 122 U.S. cities" t:attribution="National Center for Immunization and Respiratory Diseases (NCIRD)" t:url=https://data.cdc.gov/api/views/rpjd-ejph

property e:rpjd-ejph t:meta.view d:2017-03-03T14:28:08.664Z v:id=rpjd-ejph v:category=NNDSS v:averageRating=0 v:name="TABLE III. Deaths in 122 U.S. cities" v:attribution="National Center for Immunization and Respiratory Diseases (NCIRD)"

property e:rpjd-ejph t:meta.view.owner d:2017-03-03T14:28:08.664Z v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:rpjd-ejph t:meta.view.tableauthor d:2017-03-03T14:28:08.664Z v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:rpjd-ejph t:meta.view.metadata.custom_fields.common_core d:2017-03-03T14:28:08.664Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```