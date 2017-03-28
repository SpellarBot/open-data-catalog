# NNDSS - Table II. Invasive Pneumococcal Diseases, All Ages

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-invasive-pneumococcal-diseases-all-ages) |
| Metadata | [Link](https://data.cdc.gov/api/views/mbsb-z5f8) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/mbsb-z5f8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/mbsb-z5f8/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | mbsb-z5f8 |
| Name | NNDSS - Table II. Invasive Pneumococcal Diseases, All Ages |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2017, mmwr, nndss, wonder, nedss, netss, invasive pneumococcal diseases, all ages |
| Created | 2017-01-12T19:51:08Z |
| Publication Date | 2017-03-27T14:45:03Z |

## Description

NNDSS - Table II. Invasive Pneumococcal Diseases, All Ages - 2017. In this Table, provisional cases of selected notifiable diseases (≥1,000 cases reported during the preceding year), and selected low frequency diseases are displayed. The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories.

Note:
These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. 

Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. 

Footnotes:
 C.N.M.I.: Commonwealth of Northern Mariana Islands. 

 U: Unavailable. —: No reported cases. N: Not reportable. NN: Not Nationally Notifiable. NP: Nationally notifiable but not published. Cum: Cumulative year-to-date counts. Med: Median. Max: Maximum. 

*Three low incidence conditions, rubella, rubella congenital, and tetanus, are in Table II to facilitate case count verification with reporting jurisdictions. 

† Case counts for reporting years 2016 and 2017 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. Data for tuberculosis are displayed in Table IV, which appears quarterly.

§ Includes drug resistant and susceptible cases of Invasive Pneumococcal Disease. This condition was previously named Streptococcus pneumoniae invasive disease and cases were reported to CDC using different event codes to specify whether the cases were drug resistant or in a defined age group, such as <5 years.

NOTE:  These data may not reflect the case counts submitted by Oregon, Michigan, and Upstate New York due to changes in data processing.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                  | Name                                                                             | Data Type | Render Type |
| ======== | ============== | =========================================================================== | ================================================================================ | ========= | =========== |
| Yes      | series tag     | reporting_area                                                              | Reporting Area                                                                   | text      | text        |
| No       |                | mmwr_year                                                                   | MMWR Year                                                                        | number    | number      |
| No       |                | mmwr_week                                                                   | MMWR Week                                                                        | number    | number      |
| Yes      | numeric metric | invasive_pneumococcal_disease_all_ages_confirmed_current_week               | Invasive Pneumococcal Disease§, All ages, Confirmed, Current week                | number    | number      |
| No       |                | invasive_pneumococcal_disease_all_ages_confirmed_current_week_flag          | Invasive Pneumococcal Disease§, All ages, Confirmed, Current week, flag          | text      | text        |
| Yes      | numeric metric | invasive_pneumococcal_disease_all_ages_confirmed_previous_52_weeks_med      | Invasive Pneumococcal Disease§, All ages, Confirmed, Previous 52 weeks Med       | number    | number      |
| No       |                | invasive_pneumococcal_disease_all_ages_confirmed_previous_52_weeks_med_flag | Invasive Pneumococcal Disease§, All ages, Confirmed, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | invasive_pneumococcal_disease_all_ages_confirmed_previous_52_weeks_max      | Invasive Pneumococcal Disease§, All ages, Confirmed, Previous 52 weeks Max       | number    | number      |
| No       |                | invasive_pneumococcal_disease_all_ages_confirmed_previous_52_weeks_max_flag | Invasive Pneumococcal Disease§, All ages, Confirmed, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | invasive_pneumococcal_disease_all_ages_confirmed_cum_2017                   | Invasive Pneumococcal Disease§, All ages, Confirmed, Cum 2017                    | number    | number      |
| No       |                | invasive_pneumococcal_disease_all_ages_confirmed_cum_2017_flag              | Invasive Pneumococcal Disease§, All ages, Confirmed, Cum 2017, flag              | text      | text        |
| Yes      | numeric metric | invasive_pneumococcal_disease_all_ages_confirmed_cum_2016                   | Invasive Pneumococcal Disease§, All ages, Confirmed, Cum 2016                    | number    | number      |
| No       |                | invasive_pneumococcal_disease_all_ages_confirmed_cum_2016_flag              | Invasive Pneumococcal Disease§, All ages, Confirmed, Cum 2016, flag              | text      | text        |
| Yes      | numeric metric | invasive_pneumococcal_disease_all_ages_probable_current_week                | Invasive Pneumococcal Disease§, All ages, Probable, Current week                 | number    | number      |
| No       |                | invasive_pneumococcal_disease_all_ages_probable_current_week_flag           | Invasive Pneumococcal Disease§, All ages, Probable, Current week, flag           | text      | text        |
| Yes      | numeric metric | invasive_pneumococcal_disease_all_ages_probable_previous_52_weeks_med       | Invasive Pneumococcal Disease§, All ages, Probable, Previous 52 weeks Med        | number    | number      |
| No       |                | invasive_pneumococcal_disease_all_ages_probable_previous_52_weeks_med_flag  | Invasive Pneumococcal Disease§, All ages, Probable, Previous 52 weeks Med, flag  | text      | text        |
| Yes      | numeric metric | invasive_pneumococcal_disease_all_ages_probable_previous_52_weeks_max       | Invasive Pneumococcal Disease§, All ages, Probable, Previous 52 weeks Max        | number    | number      |
| No       |                | invasive_pneumococcal_disease_all_ages_probable_previous_52_weeks_max_flag  | Invasive Pneumococcal Disease§, All ages, Probable, Previous 52 weeks Max, flag  | text      | text        |
| Yes      | numeric metric | invasive_pneumococcal_disease_all_ages_probable_cum_2017                    | Invasive Pneumococcal Disease§, All ages, Probable, Cum 2017                     | number    | number      |
| No       |                | invasive_pneumococcal_disease_all_ages_probable_cum_2017_flag               | Invasive Pneumococcal Disease§, All ages, Probable, Cum 2017, flag               | text      | text        |
| Yes      | numeric metric | invasive_pneumococcal_disease_all_ages_probable_cum_2016                    | Invasive Pneumococcal Disease§, All ages, Probable, Cum 2016                     | number    | number      |
| No       |                | invasive_pneumococcal_disease_all_ages_probable_cum_2016_flag               | Invasive Pneumococcal Disease§, All ages, Probable, Cum 2016, flag               | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = invasive_pneumococcal_disease_all_ages_confirmed_current_week_flag,invasive_pneumococcal_disease_all_ages_confirmed_previous_52_weeks_med_flag,invasive_pneumococcal_disease_all_ages_confirmed_previous_52_weeks_max_flag,invasive_pneumococcal_disease_all_ages_confirmed_cum_2017_flag,invasive_pneumococcal_disease_all_ages_confirmed_cum_2016_flag,invasive_pneumococcal_disease_all_ages_probable_current_week_flag,invasive_pneumococcal_disease_all_ages_probable_previous_52_weeks_med_flag,invasive_pneumococcal_disease_all_ages_probable_previous_52_weeks_max_flag,invasive_pneumococcal_disease_all_ages_probable_cum_2017_flag,invasive_pneumococcal_disease_all_ages_probable_cum_2016_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:mbsb-z5f8 d:2017-01-01T00:00:00.000Z t:reporting_area="UNITED STATES" m:invasive_pneumococcal_disease_all_ages_confirmed_previous_52_weeks_med=270 m:invasive_pneumococcal_disease_all_ages_probable_cum_2016=2 m:invasive_pneumococcal_disease_all_ages_confirmed_cum_2016=487 m:invasive_pneumococcal_disease_all_ages_confirmed_cum_2017=264 m:invasive_pneumococcal_disease_all_ages_confirmed_current_week=264 m:invasive_pneumococcal_disease_all_ages_probable_previous_52_weeks_med=0 m:invasive_pneumococcal_disease_all_ages_probable_previous_52_weeks_max=2 m:invasive_pneumococcal_disease_all_ages_confirmed_previous_52_weeks_max=488

series e:mbsb-z5f8 d:2017-01-01T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:invasive_pneumococcal_disease_all_ages_confirmed_previous_52_weeks_med=20 m:invasive_pneumococcal_disease_all_ages_confirmed_cum_2016=31 m:invasive_pneumococcal_disease_all_ages_confirmed_cum_2017=5 m:invasive_pneumococcal_disease_all_ages_confirmed_current_week=5 m:invasive_pneumococcal_disease_all_ages_probable_previous_52_weeks_med=0 m:invasive_pneumococcal_disease_all_ages_probable_previous_52_weeks_max=0 m:invasive_pneumococcal_disease_all_ages_confirmed_previous_52_weeks_max=39

series e:mbsb-z5f8 d:2017-01-01T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:invasive_pneumococcal_disease_all_ages_confirmed_previous_52_weeks_med=41 m:invasive_pneumococcal_disease_all_ages_confirmed_cum_2016=45 m:invasive_pneumococcal_disease_all_ages_confirmed_cum_2017=50 m:invasive_pneumococcal_disease_all_ages_confirmed_current_week=50 m:invasive_pneumococcal_disease_all_ages_probable_previous_52_weeks_med=0 m:invasive_pneumococcal_disease_all_ages_probable_previous_52_weeks_max=0 m:invasive_pneumococcal_disease_all_ages_confirmed_previous_52_weeks_max=79
```

## Meta Commands

```ls
metric m:invasive_pneumococcal_disease_all_ages_confirmed_current_week p:integer l:"Invasive Pneumococcal Disease§, All ages, Confirmed, Current week" t:dataTypeName=number

metric m:invasive_pneumococcal_disease_all_ages_confirmed_previous_52_weeks_med p:integer l:"Invasive Pneumococcal Disease§, All ages, Confirmed, Previous 52 weeks Med" t:dataTypeName=number

metric m:invasive_pneumococcal_disease_all_ages_confirmed_previous_52_weeks_max p:integer l:"Invasive Pneumococcal Disease§, All ages, Confirmed, Previous 52 weeks Max" t:dataTypeName=number

metric m:invasive_pneumococcal_disease_all_ages_confirmed_cum_2017 p:integer l:"Invasive Pneumococcal Disease§, All ages, Confirmed, Cum 2017" t:dataTypeName=number

metric m:invasive_pneumococcal_disease_all_ages_confirmed_cum_2016 p:integer l:"Invasive Pneumococcal Disease§, All ages, Confirmed, Cum 2016" t:dataTypeName=number

metric m:invasive_pneumococcal_disease_all_ages_probable_current_week p:integer l:"Invasive Pneumococcal Disease§, All ages, Probable, Current week" t:dataTypeName=number

metric m:invasive_pneumococcal_disease_all_ages_probable_previous_52_weeks_med p:integer l:"Invasive Pneumococcal Disease§, All ages, Probable, Previous 52 weeks Med" t:dataTypeName=number

metric m:invasive_pneumococcal_disease_all_ages_probable_previous_52_weeks_max p:integer l:"Invasive Pneumococcal Disease§, All ages, Probable, Previous 52 weeks Max" t:dataTypeName=number

metric m:invasive_pneumococcal_disease_all_ages_probable_cum_2017 p:integer l:"Invasive Pneumococcal Disease§, All ages, Probable, Cum 2017" t:dataTypeName=number

metric m:invasive_pneumococcal_disease_all_ages_probable_cum_2016 p:integer l:"Invasive Pneumococcal Disease§, All ages, Probable, Cum 2016" t:dataTypeName=number

entity e:mbsb-z5f8 l:"NNDSS - Table II. Invasive Pneumococcal Diseases, All Ages" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/mbsb-z5f8

property e:mbsb-z5f8 t:meta.view v:id=mbsb-z5f8 v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Invasive Pneumococcal Diseases, All Ages" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:mbsb-z5f8 t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:mbsb-z5f8 t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:mbsb-z5f8 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```