# NNDSS - Table II. Ehrlichiosis/Anaplasmosis

## Dataset

* [Dataset URL](https://data.cdc.gov/api/views/keia-pvvn/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/nndss-table-ii-ehrlichiosis-anaplasmosis)
* [Metadata URL](https://data.cdc.gov/api/views/keia-pvvn)
* Id = keia-pvvn
* Name = NNDSS - Table II. Ehrlichiosis/Anaplasmosis
* Attribution = Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention
* Category = NNDSS
* Tags = [2016, mmwr, nndss, wonder, nedss, netss, ehrlichiosis/anaplasmosis, ehrlichia chaffeensis, anaplasma phagocytophilum, undetermined]
* Created = 2016-01-11T23:34:15Z
* Publication Date = 2017-01-05T16:55:40Z
* Rows Updated = 2017-01-05T14:39:08Z

## Description

NNDSS - Table II. Ehrlichiosis/Anaplasmosis - 2016.  In this Table, provisional* cases of selected? notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed. The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories. 

Note:
These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. 

Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. 

Footnotes:
C.N.M.I.: Commonwealth of Northern Mariana Islands. 
U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable.   NP:  Nationally notifiable but not published.   Cum: Cumulative year-to-date counts.    Med: Median.    Max: Maximum.
 
* Case counts for reporting year 2016 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. Data for TB are displayed in Table IV, which appears quarterly. 
? Three low incidence conditions, rubella, rubella congenital, and tetanus, are in Table II to facilitate case count verification with reporting jurisdictions. 
? Please refer to the MMWR publication for weekly updates to the footnote for this condition.

## Columns

```ls
| Name                                                                               | Field Name                                                                     | Data Type | Render Type | Schema Type    | Included | 
| ================================================================================== | ============================================================================== | ========= | =========== | ============== | ======== | 
| Reporting Area                                                                     | reporting_area                                                                 | text      | text        | series tag     | Yes      | 
| MMWR Year                                                                          | mmwr_year                                                                      | number    | number      |                | No       | 
| MMWR Week                                                                          | mmwr_week                                                                      | number    | number      |                | No       | 
| Ehrlichiosis/Anaplasmosis?, Ehrlichia chaffeensis, Current week                    | ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_current_week                   | number    | number      |                | No       | 
| Ehrlichiosis/Anaplasmosis?, Ehrlichia chaffeensis, Current week, flag              | ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_current_week_flag              | number    | text        | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Ehrlichia chaffeensis, Previous 52 weeks Med           | ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_previous_52_weeks_med          | number    | number      | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Ehrlichia chaffeensis, Previous 52 weeks Med, flag     | ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_previous_52_weeks_med_flag     | number    | text        | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Ehrlichia chaffeensis, Previous 52 weeks Max           | ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_previous_52_weeks_max          | number    | number      | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Ehrlichia chaffeensis, Previous 52 weeks Max, flag     | ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_previous_52_weeks_max_flag     | number    | text        | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Ehrlichia chaffeensis, Cum 2016                        | ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_cum_2016                       | number    | number      | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Ehrlichia chaffeensis, Cum 2016, flag                  | ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_cum_2016_flag                  | number    | text        | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Ehrlichia chaffeensis, Cum 2015                        | ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_cum_2015                       | number    | number      | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Ehrlichia chaffeensis, Cum 2015, flag                  | ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_cum_2015_flag                  | number    | text        | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Anaplasma phagocytophilum, Current week                | ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_current_week               | number    | number      |                | No       | 
| Ehrlichiosis/Anaplasmosis?, Anaplasma phagocytophilum, Current week, flag          | ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_current_week_flag          | number    | text        | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Anaplasma phagocytophilum, Previous 52 weeks Med       | ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_previous_52_weeks_med      | number    | number      | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Anaplasma phagocytophilum, Previous 52 weeks Med, flag | ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_previous_52_weeks_med_flag | number    | text        | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Anaplasma phagocytophilum, Previous 52 weeks Max       | ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_previous_52_weeks_max      | number    | number      | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Anaplasma phagocytophilum, Previous 52 weeks Max, flag | ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_previous_52_weeks_max_flag | number    | text        | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Anaplasma phagocytophilum, Cum 2016                    | ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_cum_2016                   | number    | number      | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Anaplasma phagocytophilum, Cum 2016, flag              | ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_cum_2016_flag              | number    | text        | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Anaplasma phagocytophilum, Cum 2015                    | ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_cum_2015                   | number    | number      | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Anaplasma phagocytophilum, Cum 2015, flag              | ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_cum_2015_flag              | number    | text        | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Undetermined, Current week                             | ehrlichiosis_anaplasmosis_undetermined_current_week                            | number    | number      |                | No       | 
| Ehrlichiosis/Anaplasmosis?, Undetermined, Current week, flag                       | ehrlichiosis_anaplasmosis_undetermined_current_week_flag                       | number    | text        | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Undetermined, Previous 52 weeks Med                    | ehrlichiosis_anaplasmosis_undetermined_previous_52_weeks_med                   | number    | number      | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Undetermined, Previous 52 weeks Med, flag              | ehrlichiosis_anaplasmosis_undetermined_previous_52_weeks_med_flag              | number    | text        | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Undetermined, Previous 52 weeks Max                    | ehrlichiosis_anaplasmosis_undetermined_previous_52_weeks_max                   | number    | number      | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Undetermined, Previous 52 weeks Max, flag              | ehrlichiosis_anaplasmosis_undetermined_previous_52_weeks_max_flag              | number    | text        | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Undetermined, Cum 2016                                 | ehrlichiosis_anaplasmosis_undetermined_cum_2016                                | number    | number      | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Undetermined, Cum 2016, flag                           | ehrlichiosis_anaplasmosis_undetermined_cum_2016_flag                           | number    | text        | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Undetermined, Cum 2015                                 | ehrlichiosis_anaplasmosis_undetermined_cum_2015                                | number    | number      | numeric metric | Yes      | 
| Ehrlichiosis/Anaplasmosis?, Undetermined, Cum 2015, flag                           | ehrlichiosis_anaplasmosis_undetermined_cum_2015_flag                           | number    | text        | numeric metric | Yes      | 
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
Excluded Fields = ehrlichiosis_anaplasmosis_undetermined_current_week,mmwr_year,ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_current_week,ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_current_week,mmwr_week
Annotation Fields = 
```

## Data Commands

```ls
series e:keia-pvvn d:2016-01-08T00:00:00.000Z t:ehrlichiosis_anaplasmosis_undetermined_cum_2016_flag=- t:ehrlichiosis_anaplasmosis_undetermined_current_week_flag=- t:ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_current_week_flag=- t:ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_cum_2016_flag=- t:reporting_area="UNITED STATES" m:ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_previous_52_weeks_med=39 m:ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_previous_52_weeks_med=13 m:ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_previous_52_weeks_max=70 m:ehrlichiosis_anaplasmosis_undetermined_cum_2015=1 m:ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_cum_2015=6 m:ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_cum_2016=1 m:ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_previous_52_weeks_max=194 m:ehrlichiosis_anaplasmosis_undetermined_previous_52_weeks_med=2 m:ehrlichiosis_anaplasmosis_undetermined_previous_52_weeks_max=9 m:ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_cum_2015=2

series e:keia-pvvn d:2016-01-08T00:00:00.000Z t:ehrlichiosis_anaplasmosis_undetermined_cum_2016_flag=- t:ehrlichiosis_anaplasmosis_undetermined_current_week_flag=- t:ehrlichiosis_anaplasmosis_undetermined_cum_2015_flag=- t:ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_current_week_flag=- t:ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_cum_2016_flag=- t:ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_cum_2015_flag=- t:reporting_area="NEW ENGLAND" m:ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_previous_52_weeks_med=15 m:ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_previous_52_weeks_med=1 m:ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_previous_52_weeks_max=6 m:ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_cum_2015=3 m:ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_cum_2016=1 m:ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_previous_52_weeks_max=98 m:ehrlichiosis_anaplasmosis_undetermined_previous_52_weeks_med=0 m:ehrlichiosis_anaplasmosis_undetermined_previous_52_weeks_max=2

series e:keia-pvvn d:2016-01-08T00:00:00.000Z t:ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_current_week_flag=- t:ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_cum_2016_flag=- t:ehrlichiosis_anaplasmosis_undetermined_cum_2016_flag=- t:ehrlichiosis_anaplasmosis_undetermined_current_week_flag=- t:ehrlichiosis_anaplasmosis_undetermined_cum_2015_flag=- t:ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_current_week_flag=- t:ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_cum_2016_flag=- t:reporting_area="MID. ATLANTIC" m:ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_previous_52_weeks_med=15 m:ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_previous_52_weeks_med=2 m:ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_previous_52_weeks_max=9 m:ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_cum_2015=1 m:ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_previous_52_weeks_max=61 m:ehrlichiosis_anaplasmosis_undetermined_previous_52_weeks_med=0 m:ehrlichiosis_anaplasmosis_undetermined_previous_52_weeks_max=2 m:ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_cum_2015=1
```

## Meta Commands

```ls
metric m:ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_previous_52_weeks_med p:integer l:"Ehrlichiosis/Anaplasmosis?, Ehrlichia chaffeensis, Previous 52 weeks Med" t:dataTypeName=number

metric m:ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_previous_52_weeks_max p:integer l:"Ehrlichiosis/Anaplasmosis?, Ehrlichia chaffeensis, Previous 52 weeks Max" t:dataTypeName=number

metric m:ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_cum_2016 p:integer l:"Ehrlichiosis/Anaplasmosis?, Ehrlichia chaffeensis, Cum 2016" t:dataTypeName=number

metric m:ehrlichiosis_anaplasmosis_ehrlichia_chaffeensis_cum_2015 p:integer l:"Ehrlichiosis/Anaplasmosis?, Ehrlichia chaffeensis, Cum 2015" t:dataTypeName=number

metric m:ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_previous_52_weeks_med p:integer l:"Ehrlichiosis/Anaplasmosis?, Anaplasma phagocytophilum, Previous 52 weeks Med" t:dataTypeName=number

metric m:ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_previous_52_weeks_max p:integer l:"Ehrlichiosis/Anaplasmosis?, Anaplasma phagocytophilum, Previous 52 weeks Max" t:dataTypeName=number

metric m:ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_cum_2016 p:integer l:"Ehrlichiosis/Anaplasmosis?, Anaplasma phagocytophilum, Cum 2016" t:dataTypeName=number

metric m:ehrlichiosis_anaplasmosis_anaplasma_phagocytophilum_cum_2015 p:integer l:"Ehrlichiosis/Anaplasmosis?, Anaplasma phagocytophilum, Cum 2015" t:dataTypeName=number

metric m:ehrlichiosis_anaplasmosis_undetermined_previous_52_weeks_med p:integer l:"Ehrlichiosis/Anaplasmosis?, Undetermined, Previous 52 weeks Med" t:dataTypeName=number

metric m:ehrlichiosis_anaplasmosis_undetermined_previous_52_weeks_max p:integer l:"Ehrlichiosis/Anaplasmosis?, Undetermined, Previous 52 weeks Max" t:dataTypeName=number

metric m:ehrlichiosis_anaplasmosis_undetermined_cum_2016 p:integer l:"Ehrlichiosis/Anaplasmosis?, Undetermined, Cum 2016" t:dataTypeName=number

metric m:ehrlichiosis_anaplasmosis_undetermined_cum_2015 p:integer l:"Ehrlichiosis/Anaplasmosis?, Undetermined, Cum 2015" t:dataTypeName=number

entity e:keia-pvvn l:"NNDSS - Table II. Ehrlichiosis/Anaplasmosis" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/keia-pvvn

property e:keia-pvvn t:meta.view d:2017-03-08T02:24:50.565Z v:id=keia-pvvn v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Ehrlichiosis/Anaplasmosis" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:keia-pvvn t:meta.view.owner d:2017-03-08T02:24:50.565Z v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:keia-pvvn t:meta.view.tableauthor d:2017-03-08T02:24:50.565Z v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:keia-pvvn t:meta.view.metadata.custom_fields.common_core d:2017-03-08T02:24:50.565Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```