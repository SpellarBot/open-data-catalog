# NNDSS - Table II. Shiga toxin to Shigellosis

## Dataset

* [Dataset URL](https://data.cdc.gov/api/views/xv7k-8e7s/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/nndss-table-ii-shiga-toxin-to-shigellosis)
* [Metadata URL](https://data.cdc.gov/api/views/xv7k-8e7s)
* Id = xv7k-8e7s
* Name = NNDSS - Table II. Shiga toxin to Shigellosis
* Attribution = Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention
* Category = NNDSS
* Tags = [2016, mmwr, nndss, wonder, nedss, netss, shiga toxin-producing e. coli, stec, shigellosis]
* Created = 2016-01-12T13:20:18Z
* Publication Date = 2017-01-05T17:34:30Z
* Rows Updated = 2017-01-05T14:58:06Z

## Description

NNDSS - Table II. Shiga toxin to Shigellosis - 2016.  In this Table, provisional* cases of selected? notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed. The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories.
Note:
These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. 

Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. 

Footnotes:
C.N.M.I.: Commonwealth of Northern Mariana Islands. 
U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable.   NP:  Nationally notifiable but not published.   Cum: Cumulative year-to-date counts.    Med: Median.    Max: Maximum.
 
* Case counts for reporting year 2016 are provisional and subject to change.   For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf.   Data for TB are displayed in Table IV, which appears quarterly.  
? Three low incidence conditions, rubella, rubella congenital, and tetanus, have been moved to Table II to facilitate case count verification with reporting jurisdictions.
? Includes E. coli O157:H7; Shiga toxin-positive, serogroup non-O157; and Shiga toxin-positive, not serogrouped.

## Columns

```ls
| Name                                                               | Field Name                                                   | Data Type | Render Type | Schema Type    | Included | 
| ================================================================== | ============================================================ | ========= | =========== | ============== | ======== | 
| Reporting Area                                                     | reporting_area                                               | text      | text        | series tag     | Yes      | 
| MMWR Year                                                          | mmwr_year                                                    | number    | number      |                | No       | 
| MMWR Week                                                          | mmwr_week                                                    | number    | number      |                | No       | 
| Shiga toxin-producing E. coli (STEC)?, Current week                | shiga_toxin_producing_e_coli_stec_current_week               | number    | number      |                | No       | 
| Shiga toxin-producing E. coli (STEC)?, Current week, flag          | shiga_toxin_producing_e_coli_stec_current_week_flag          | number    | text        | numeric metric | Yes      | 
| Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Med       | shiga_toxin_producing_e_coli_stec_previous_52_weeks_med      | number    | number      | numeric metric | Yes      | 
| Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Med, flag | shiga_toxin_producing_e_coli_stec_previous_52_weeks_med_flag | number    | text        | numeric metric | Yes      | 
| Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Max       | shiga_toxin_producing_e_coli_stec_previous_52_weeks_max      | number    | number      | numeric metric | Yes      | 
| Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Max, flag | shiga_toxin_producing_e_coli_stec_previous_52_weeks_max_flag | number    | text        | numeric metric | Yes      | 
| Shiga toxin-producing E. coli (STEC)?, Cum 2016                    | shiga_toxin_producing_e_coli_stec_cum_2016                   | number    | number      | numeric metric | Yes      | 
| Shiga toxin-producing E. coli (STEC)?, Cum 2016, flag              | shiga_toxin_producing_e_coli_stec_cum_2016_flag              | number    | text        | numeric metric | Yes      | 
| Shiga toxin-producing E. coli (STEC)?, Cum 2015                    | shiga_toxin_producing_e_coli_stec_cum_2015                   | number    | number      | numeric metric | Yes      | 
| Shiga toxin-producing E. coli (STEC)?, Cum 2015, flag              | shiga_toxin_producing_e_coli_stec_cum_2015_flag              | number    | text        | numeric metric | Yes      | 
| Shigellosis, Current week                                          | shigellosis_current_week                                     | number    | number      |                | No       | 
| Shigellosis, Current week, flag                                    | shigellosis_current_week_flag                                | number    | text        | numeric metric | Yes      | 
| Shigellosis, Previous 52 weeks Med                                 | shigellosis_previous_52_weeks_med                            | number    | number      | numeric metric | Yes      | 
| Shigellosis, Previous 52 weeks Med, flag                           | shigellosis_previous_52_weeks_med_flag                       | number    | text        | numeric metric | Yes      | 
| Shigellosis, Previous 52 weeks Max                                 | shigellosis_previous_52_weeks_max                            | number    | number      | numeric metric | Yes      | 
| Shigellosis, Previous 52 weeks Max, flag                           | shigellosis_previous_52_weeks_max_flag                       | number    | text        | numeric metric | Yes      | 
| Shigellosis, Cum 2016                                              | shigellosis_cum_2016                                         | number    | number      | numeric metric | Yes      | 
| Shigellosis, Cum 2016, flag                                        | shigellosis_cum_2016_flag                                    | number    | text        | numeric metric | Yes      | 
| Shigellosis, Cum 2015                                              | shigellosis_cum_2015                                         | number    | number      | numeric metric | Yes      | 
| Shigellosis, Cum 2015, flag                                        | shigellosis_cum_2015_flag                                    | number    | text        | numeric metric | Yes      | 
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
Excluded Fields = shiga_toxin_producing_e_coli_stec_current_week,shigellosis_current_week,mmwr_year,mmwr_week
Annotation Fields = 
```

## Data Commands

```ls
series e:xv7k-8e7s d:2016-01-08T00:00:00.000Z t:reporting_area="UNITED STATES" m:shiga_toxin_producing_e_coli_stec_cum_2015=56 m:shiga_toxin_producing_e_coli_stec_cum_2016=16 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max=194 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med=111 m:shigellosis_previous_52_weeks_med=408 m:shigellosis_previous_52_weeks_max=610 m:shigellosis_cum_2015=332 m:shigellosis_cum_2016=166

series e:xv7k-8e7s d:2016-01-08T00:00:00.000Z t:shiga_toxin_producing_e_coli_stec_current_week_flag=- t:shiga_toxin_producing_e_coli_stec_cum_2016_flag=- t:reporting_area="NEW ENGLAND" m:shiga_toxin_producing_e_coli_stec_cum_2015=3 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max=17 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med=3 m:shigellosis_previous_52_weeks_med=5 m:shigellosis_previous_52_weeks_max=17 m:shigellosis_cum_2015=2 m:shigellosis_cum_2016=1

series e:xv7k-8e7s d:2016-01-08T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:shiga_toxin_producing_e_coli_stec_cum_2015=4 m:shiga_toxin_producing_e_coli_stec_cum_2016=2 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max=23 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med=12 m:shigellosis_previous_52_weeks_med=28 m:shigellosis_previous_52_weeks_max=82 m:shigellosis_cum_2015=49 m:shigellosis_cum_2016=12
```

## Meta Commands

```ls
metric m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med p:integer l:"Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Med" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max p:integer l:"Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Max" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_cum_2016 p:integer l:"Shiga toxin-producing E. coli (STEC)?, Cum 2016" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_cum_2015 p:integer l:"Shiga toxin-producing E. coli (STEC)?, Cum 2015" t:dataTypeName=number

metric m:shigellosis_previous_52_weeks_med p:integer l:"Shigellosis, Previous 52 weeks Med" t:dataTypeName=number

metric m:shigellosis_previous_52_weeks_max p:integer l:"Shigellosis, Previous 52 weeks Max" t:dataTypeName=number

metric m:shigellosis_cum_2016 p:integer l:"Shigellosis, Cum 2016" t:dataTypeName=number

metric m:shigellosis_cum_2015 p:integer l:"Shigellosis, Cum 2015" t:dataTypeName=number

entity e:xv7k-8e7s l:"NNDSS - Table II. Shiga toxin to Shigellosis" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/xv7k-8e7s

property e:xv7k-8e7s t:meta.view d:2017-03-08T01:40:15.709Z v:id=xv7k-8e7s v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Shiga toxin to Shigellosis" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:xv7k-8e7s t:meta.view.owner d:2017-03-08T01:40:15.709Z v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:xv7k-8e7s t:meta.view.tableauthor d:2017-03-08T01:40:15.709Z v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:xv7k-8e7s t:meta.view.metadata.custom_fields.common_core d:2017-03-08T01:40:15.709Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```