# NNDSS - Table II. Rabies, animal to Rubella, congenital syndrome

## Dataset

* [Dataset URL](https://data.cdc.gov/api/views/scxv-4u4u/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/nndss-table-ii-rabies-animal-to-rubella-congenital-syndrome)
* Id = scxv-4u4u
* Name = NNDSS - Table II. Rabies, animal to Rubella, congenital syndrome
* Attribution = Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention
* Category = NNDSS
* Tags = [2017, mmwr, nndss, wonder, nedss, netss, rabies, animal, rubella, congenital syndrome]
* Created = 2017-01-12T20:23:18Z
* Publication Date = 2017-03-02T18:35:14Z
* Rows Updated = 2017-03-02T16:52:38Z

## Description

NNDSS - Table II. Rabies, animal to Rubella, congenital syndrome - 2017.  In this Table, provisional cases of selected notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed.  The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories.

Note:
These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. 

Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. 

Footnotes:
 C.N.M.I.: Commonwealth of Northern Mariana Islands. 

 U: Unavailable. ?: No reported cases. N: Not reportable. NN: Not Nationally Notifiable. NP: Nationally notifiable but not published. Cum: Cumulative year-to-date counts. Med: Median. Max: Maximum. 

*Three low incidence conditions, rubella, rubella congenital, and tetanus, are in Table II to facilitate case count verification with reporting jurisdictions. 

? Case counts for reporting years 2016 and 2017 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. Data for tuberculosis are displayed in Table IV, which appears quarterly.

## Columns

```ls
| Name                                                      | Field Name                                             | Data Type | Render Type | Schema Type    | Included | 
| ========================================================= | ====================================================== | ========= | =========== | ============== | ======== | 
| Reporting Area                                            | reporting_area                                         | text      | text        | series tag     | Yes      | 
| MMWR Year                                                 | mmwr_year                                              | number    | number      |                | No       | 
| MMWR Week                                                 | mmwr_week                                              | number    | number      |                | No       | 
| Rabies, animal, Current week                              | rabies_animal_current_week                             | number    | number      |                | No       | 
| Rabies, animal, Current week, flag                        | rabies_animal_current_week_flag                        | text      | text        |                | No       | 
| Rabies, animal, Previous 52 weeks Med                     | rabies_animal_previous_52_weeks_med                    | number    | number      | numeric metric | Yes      | 
| Rabies, animal, Previous 52 weeks Med, flag               | rabies_animal_previous_52_weeks_med_flag               | text      | text        |                | No       | 
| Rabies, animal, Previous 52 weeks Max                     | rabies_animal_previous_52_weeks_max                    | number    | number      | numeric metric | Yes      | 
| Rabies, animal, Previous 52 weeks Max, flag               | rabies_animal_previous_52_weeks_max_flag               | text      | text        |                | No       | 
| Rabies, animal, Cum 2017                                  | rabies_animal_cum_2017                                 | number    | number      | numeric metric | Yes      | 
| Rabies, animal, Cum 2017, flag                            | rabies_animal_cum_2017_flag                            | text      | text        |                | No       | 
| Rabies, animal, Cum 2016                                  | rabies_animal_cum_2016                                 | number    | number      | numeric metric | Yes      | 
| Rabies, animal, Cum 2016, flag                            | rabies_animal_cum_2016_flag                            | text      | text        |                | No       | 
| Rubella, Current week                                     | rubella_current_week                                   | number    | number      |                | No       | 
| Rubella, Current week, flag                               | rubella_current_week_flag                              | text      | text        |                | No       | 
| Rubella, Previous 52 weeks Med                            | rubella_previous_52_weeks_med                          | number    | number      | numeric metric | Yes      | 
| Rubella, Previous 52 weeks Med, flag                      | rubella_previous_52_weeks_med_flag                     | text      | text        |                | No       | 
| Rubella, Previous 52 weeks Max                            | rubella_previous_52_weeks_max                          | number    | number      | numeric metric | Yes      | 
| Rubella, Previous 52 weeks Max, flag                      | rubella_previous_52_weeks_max_flag                     | text      | text        |                | No       | 
| Rubella, Cum 2017                                         | rubella_cum_2017                                       | number    | number      | numeric metric | Yes      | 
| Rubella, Cum 2017, flag                                   | rubella_cum_2017_flag                                  | text      | text        |                | No       | 
| Rubella, Cum 2016                                         | rubella_cum_2016                                       | number    | number      | numeric metric | Yes      | 
| Rubella, Cum 2016, flag                                   | rubella_cum_2016_flag                                  | text      | text        |                | No       | 
| Rubella, congenital syndrome, Current week                | rubella_congenital_syndrome_current_week               | number    | number      |                | No       | 
| Rubella, congenital syndrome, Current week, flag          | rubella_congenital_syndrome_current_week_flag          | text      | text        |                | No       | 
| Rubella, congenital syndrome, Previous 52 weeks Med       | rubella_congenital_syndrome_previous_52_weeks_med      | number    | number      | numeric metric | Yes      | 
| Rubella, congenital syndrome, Previous 52 weeks Med, flag | rubella_congenital_syndrome_previous_52_weeks_med_flag | text      | text        |                | No       | 
| Rubella, congenital syndrome, Previous 52 weeks Max       | rubella_congenital_syndrome_previous_52_weeks_max      | number    | number      | numeric metric | Yes      | 
| Rubella, congenital syndrome, Previous 52 weeks Max, flag | rubella_congenital_syndrome_previous_52_weeks_max_flag | text      | text        |                | No       | 
| Rubella, congenital syndrome, Cum 2017                    | rubella_congenital_syndrome_cum_2017                   | number    | number      | numeric metric | Yes      | 
| Rubella, congenital syndrome, Cum 2017, flag              | rubella_congenital_syndrome_cum_2017_flag              | text      | text        |                | No       | 
| Rubella, congenital syndrome, Cum 2016                    | rubella_congenital_syndrome_cum_2016                   | number    | number      | numeric metric | Yes      | 
| Rubella, congenital syndrome, Cum 2016, flag              | rubella_congenital_syndrome_cum_2016_flag              | text      | text        |                | No       | 
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
Excluded Fields = rabies_animal_cum_2016_flag,rubella_cum_2017_flag,mmwr_year,rubella_congenital_syndrome_cum_2016_flag,rubella_previous_52_weeks_max_flag,rubella_congenital_syndrome_previous_52_weeks_med_flag,rubella_cum_2016_flag,rabies_animal_previous_52_weeks_med_flag,rabies_animal_current_week_flag,rubella_congenital_syndrome_cum_2017_flag,rubella_congenital_syndrome_current_week,rabies_animal_previous_52_weeks_max_flag,rubella_current_week_flag,rubella_congenital_syndrome_previous_52_weeks_max_flag,rubella_current_week,rabies_animal_cum_2017_flag,rabies_animal_current_week,rubella_previous_52_weeks_med_flag,mmwr_week,rubella_congenital_syndrome_current_week_flag
Annotation Fields = 
```

## Data Commands

```ls
series e:scxv-4u4u d:2017-01-08T00:00:00.000Z t:reporting_area="UNITED STATES" m:rubella_congenital_syndrome_previous_52_weeks_med=0 m:rabies_animal_cum_2017=11 m:rabies_animal_previous_52_weeks_max=112 m:rubella_congenital_syndrome_previous_52_weeks_max=1 m:rubella_previous_52_weeks_med=0 m:rabies_animal_cum_2016=34 m:rubella_previous_52_weeks_max=2 m:rabies_animal_previous_52_weeks_med=52

series e:scxv-4u4u d:2017-01-08T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:rubella_congenital_syndrome_previous_52_weeks_med=0 m:rabies_animal_previous_52_weeks_max=13 m:rubella_congenital_syndrome_previous_52_weeks_max=0 m:rubella_previous_52_weeks_med=0 m:rubella_previous_52_weeks_max=0 m:rabies_animal_previous_52_weeks_med=4

series e:scxv-4u4u d:2017-01-08T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:rubella_congenital_syndrome_previous_52_weeks_med=0 m:rabies_animal_cum_2017=7 m:rabies_animal_previous_52_weeks_max=33 m:rubella_congenital_syndrome_previous_52_weeks_max=0 m:rubella_previous_52_weeks_med=0 m:rabies_animal_cum_2016=5 m:rubella_previous_52_weeks_max=0 m:rabies_animal_previous_52_weeks_med=8
```

## Meta Commands

```ls
metric m:rabies_animal_previous_52_weeks_med l:"Rabies, animal, Previous 52 weeks Med" t:dataTypeName=number

metric m:rabies_animal_previous_52_weeks_max l:"Rabies, animal, Previous 52 weeks Max" t:dataTypeName=number

metric m:rabies_animal_cum_2017 l:"Rabies, animal, Cum 2017" t:dataTypeName=number

metric m:rabies_animal_cum_2016 l:"Rabies, animal, Cum 2016" t:dataTypeName=number

metric m:rubella_previous_52_weeks_med l:"Rubella, Previous 52 weeks Med" t:dataTypeName=number

metric m:rubella_previous_52_weeks_max l:"Rubella, Previous 52 weeks Max" t:dataTypeName=number

metric m:rubella_cum_2017 l:"Rubella, Cum 2017" t:dataTypeName=number

metric m:rubella_cum_2016 l:"Rubella, Cum 2016" t:dataTypeName=number

metric m:rubella_congenital_syndrome_previous_52_weeks_med l:"Rubella, congenital syndrome, Previous 52 weeks Med" t:dataTypeName=number

metric m:rubella_congenital_syndrome_previous_52_weeks_max l:"Rubella, congenital syndrome, Previous 52 weeks Max" t:dataTypeName=number

metric m:rubella_congenital_syndrome_cum_2017 l:"Rubella, congenital syndrome, Cum 2017" t:dataTypeName=number

metric m:rubella_congenital_syndrome_cum_2016 l:"Rubella, congenital syndrome, Cum 2016" t:dataTypeName=number

entity e:scxv-4u4u l:"NNDSS - Table II. Rabies, animal to Rubella, congenital syndrome" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/scxv-4u4u

property e:scxv-4u4u t:meta.view d:2017-03-03T14:21:29.199Z v:id=scxv-4u4u v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Rabies, animal to Rubella, congenital syndrome" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:scxv-4u4u t:meta.view.owner d:2017-03-03T14:21:29.199Z v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:scxv-4u4u t:meta.view.tableauthor d:2017-03-03T14:21:29.199Z v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:scxv-4u4u t:meta.view.metadata.custom_fields.common_core d:2017-03-03T14:21:29.199Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```