# NNDSS - Table II. Rabies, animal to Rubella, congenital syndrome

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-rabies-animal-to-rubella-congenital-syndrome) |
| Metadata | [Link](https://data.cdc.gov/api/views/scxv-4u4u) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/scxv-4u4u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/scxv-4u4u/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | scxv-4u4u |
| Name | NNDSS - Table II. Rabies, animal to Rubella, congenital syndrome |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2017, mmwr, nndss, wonder, nedss, netss, rabies, animal, rubella, congenital syndrome |
| Created | 2017-01-12T20:23:18Z |
| Publication Date | 2017-03-16T16:13:12Z |
| Rows Updated | 2017-03-16T14:57:39Z |

## Description

NNDSS - Table II. Rabies, animal to Rubella, congenital syndrome - 2017.  In this Table, provisional cases of selected notifiable diseases (≥1,000 cases reported during the preceding year), and selected low frequency diseases are displayed.  The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories.

Note:
These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. 

Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. 

Footnotes:
 C.N.M.I.: Commonwealth of Northern Mariana Islands. 

 U: Unavailable. —: No reported cases. N: Not reportable. NN: Not Nationally Notifiable. NP: Nationally notifiable but not published. Cum: Cumulative year-to-date counts. Med: Median. Max: Maximum. 

*Three low incidence conditions, rubella, rubella congenital, and tetanus, are in Table II to facilitate case count verification with reporting jurisdictions. 

† Case counts for reporting years 2016 and 2017 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. Data for tuberculosis are displayed in Table IV, which appears quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name                                             | Name                                                      | Data Type | Render Type |
| ======== | ============== | ====================================================== | ========================================================= | ========= | =========== |
| Yes      | series tag     | reporting_area                                         | Reporting Area                                            | text      | text        |
| No       |                | mmwr_year                                              | MMWR Year                                                 | number    | number      |
| No       |                | mmwr_week                                              | MMWR Week                                                 | number    | number      |
| Yes      | numeric metric | rabies_animal_current_week                             | Rabies, animal, Current week                              | number    | number      |
| No       |                | rabies_animal_current_week_flag                        | Rabies, animal, Current week, flag                        | text      | text        |
| Yes      | numeric metric | rabies_animal_previous_52_weeks_med                    | Rabies, animal, Previous 52 weeks Med                     | number    | number      |
| No       |                | rabies_animal_previous_52_weeks_med_flag               | Rabies, animal, Previous 52 weeks Med, flag               | text      | text        |
| Yes      | numeric metric | rabies_animal_previous_52_weeks_max                    | Rabies, animal, Previous 52 weeks Max                     | number    | number      |
| No       |                | rabies_animal_previous_52_weeks_max_flag               | Rabies, animal, Previous 52 weeks Max, flag               | text      | text        |
| Yes      | numeric metric | rabies_animal_cum_2017                                 | Rabies, animal, Cum 2017                                  | number    | number      |
| No       |                | rabies_animal_cum_2017_flag                            | Rabies, animal, Cum 2017, flag                            | text      | text        |
| Yes      | numeric metric | rabies_animal_cum_2016                                 | Rabies, animal, Cum 2016                                  | number    | number      |
| No       |                | rabies_animal_cum_2016_flag                            | Rabies, animal, Cum 2016, flag                            | text      | text        |
| Yes      | numeric metric | rubella_current_week                                   | Rubella, Current week                                     | number    | number      |
| No       |                | rubella_current_week_flag                              | Rubella, Current week, flag                               | text      | text        |
| Yes      | numeric metric | rubella_previous_52_weeks_med                          | Rubella, Previous 52 weeks Med                            | number    | number      |
| No       |                | rubella_previous_52_weeks_med_flag                     | Rubella, Previous 52 weeks Med, flag                      | text      | text        |
| Yes      | numeric metric | rubella_previous_52_weeks_max                          | Rubella, Previous 52 weeks Max                            | number    | number      |
| No       |                | rubella_previous_52_weeks_max_flag                     | Rubella, Previous 52 weeks Max, flag                      | text      | text        |
| Yes      | numeric metric | rubella_cum_2017                                       | Rubella, Cum 2017                                         | number    | number      |
| No       |                | rubella_cum_2017_flag                                  | Rubella, Cum 2017, flag                                   | text      | text        |
| Yes      | numeric metric | rubella_cum_2016                                       | Rubella, Cum 2016                                         | number    | number      |
| No       |                | rubella_cum_2016_flag                                  | Rubella, Cum 2016, flag                                   | text      | text        |
| Yes      | numeric metric | rubella_congenital_syndrome_current_week               | Rubella, congenital syndrome, Current week                | number    | number      |
| No       |                | rubella_congenital_syndrome_current_week_flag          | Rubella, congenital syndrome, Current week, flag          | text      | text        |
| Yes      | numeric metric | rubella_congenital_syndrome_previous_52_weeks_med      | Rubella, congenital syndrome, Previous 52 weeks Med       | number    | number      |
| No       |                | rubella_congenital_syndrome_previous_52_weeks_med_flag | Rubella, congenital syndrome, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | rubella_congenital_syndrome_previous_52_weeks_max      | Rubella, congenital syndrome, Previous 52 weeks Max       | number    | number      |
| No       |                | rubella_congenital_syndrome_previous_52_weeks_max_flag | Rubella, congenital syndrome, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | rubella_congenital_syndrome_cum_2017                   | Rubella, congenital syndrome, Cum 2017                    | number    | number      |
| No       |                | rubella_congenital_syndrome_cum_2017_flag              | Rubella, congenital syndrome, Cum 2017, flag              | text      | text        |
| Yes      | numeric metric | rubella_congenital_syndrome_cum_2016                   | Rubella, congenital syndrome, Cum 2016                    | number    | number      |
| No       |                | rubella_congenital_syndrome_cum_2016_flag              | Rubella, congenital syndrome, Cum 2016, flag              | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = rabies_animal_current_week_flag,rabies_animal_previous_52_weeks_med_flag,rabies_animal_previous_52_weeks_max_flag,rabies_animal_cum_2017_flag,rabies_animal_cum_2016_flag,rubella_current_week_flag,rubella_previous_52_weeks_med_flag,rubella_previous_52_weeks_max_flag,rubella_cum_2017_flag,rubella_cum_2016_flag,rubella_congenital_syndrome_current_week_flag,rubella_congenital_syndrome_previous_52_weeks_med_flag,rubella_congenital_syndrome_previous_52_weeks_max_flag,rubella_congenital_syndrome_cum_2017_flag,rubella_congenital_syndrome_cum_2016_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:scxv-4u4u d:2017-01-01T00:00:00.000Z t:reporting_area="UNITED STATES" m:rubella_congenital_syndrome_previous_52_weeks_med=0 m:rabies_animal_cum_2017=11 m:rabies_animal_previous_52_weeks_max=112 m:rubella_congenital_syndrome_previous_52_weeks_max=1 m:rubella_previous_52_weeks_med=0 m:rabies_animal_cum_2016=34 m:rubella_previous_52_weeks_max=2 m:rabies_animal_current_week=11 m:rabies_animal_previous_52_weeks_med=52

series e:scxv-4u4u d:2017-01-01T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:rubella_congenital_syndrome_previous_52_weeks_med=0 m:rabies_animal_previous_52_weeks_max=13 m:rubella_congenital_syndrome_previous_52_weeks_max=0 m:rubella_previous_52_weeks_med=0 m:rubella_previous_52_weeks_max=0 m:rabies_animal_previous_52_weeks_med=4

series e:scxv-4u4u d:2017-01-01T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:rubella_congenital_syndrome_previous_52_weeks_med=0 m:rabies_animal_cum_2017=7 m:rabies_animal_previous_52_weeks_max=33 m:rubella_congenital_syndrome_previous_52_weeks_max=0 m:rubella_previous_52_weeks_med=0 m:rabies_animal_cum_2016=5 m:rubella_previous_52_weeks_max=0 m:rabies_animal_current_week=7 m:rabies_animal_previous_52_weeks_med=8
```

## Meta Commands

```ls
metric m:rabies_animal_current_week p:integer l:"Rabies, animal, Current week" t:dataTypeName=number

metric m:rabies_animal_previous_52_weeks_med p:integer l:"Rabies, animal, Previous 52 weeks Med" t:dataTypeName=number

metric m:rabies_animal_previous_52_weeks_max p:integer l:"Rabies, animal, Previous 52 weeks Max" t:dataTypeName=number

metric m:rabies_animal_cum_2017 p:integer l:"Rabies, animal, Cum 2017" t:dataTypeName=number

metric m:rabies_animal_cum_2016 p:integer l:"Rabies, animal, Cum 2016" t:dataTypeName=number

metric m:rubella_current_week p:long l:"Rubella, Current week" t:dataTypeName=number

metric m:rubella_previous_52_weeks_med p:integer l:"Rubella, Previous 52 weeks Med" t:dataTypeName=number

metric m:rubella_previous_52_weeks_max p:integer l:"Rubella, Previous 52 weeks Max" t:dataTypeName=number

metric m:rubella_cum_2017 p:integer l:"Rubella, Cum 2017" t:dataTypeName=number

metric m:rubella_cum_2016 p:integer l:"Rubella, Cum 2016" t:dataTypeName=number

metric m:rubella_congenital_syndrome_current_week p:long l:"Rubella, congenital syndrome, Current week" t:dataTypeName=number

metric m:rubella_congenital_syndrome_previous_52_weeks_med p:integer l:"Rubella, congenital syndrome, Previous 52 weeks Med" t:dataTypeName=number

metric m:rubella_congenital_syndrome_previous_52_weeks_max p:integer l:"Rubella, congenital syndrome, Previous 52 weeks Max" t:dataTypeName=number

metric m:rubella_congenital_syndrome_cum_2017 p:integer l:"Rubella, congenital syndrome, Cum 2017" t:dataTypeName=number

metric m:rubella_congenital_syndrome_cum_2016 p:long l:"Rubella, congenital syndrome, Cum 2016" t:dataTypeName=number

entity e:scxv-4u4u l:"NNDSS - Table II. Rabies, animal to Rubella, congenital syndrome" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/scxv-4u4u

property e:scxv-4u4u t:meta.view v:id=scxv-4u4u v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Rabies, animal to Rubella, congenital syndrome" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:scxv-4u4u t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:scxv-4u4u t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:scxv-4u4u t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```