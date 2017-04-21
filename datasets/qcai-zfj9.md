# NOHSS Child Indicators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nohss-child-indicators-c8aa1) |
| Metadata | [Link](https://data.cdc.gov/api/views/qcai-zfj9) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/qcai-zfj9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/qcai-zfj9/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | qcai-zfj9 |
| Name | NOHSS Child Indicators |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Oral Health |
| Category | Oral Health |
| Tags | division of oral health, oral health, nohss, child, children, caries, tooth decay, untreated tooth decay, caries experience, dental sealants, bss, basic screening survey, prevalence, astdd |
| Created | 2015-04-22T00:32:41Z |
| Publication Date | 2016-08-08T17:44:34Z |

## Description

Data for School year-end 1994 through year-end 2016.  State oral health surveys are the data sources for these indicators. States periodically conduct independent screening surveys of a probability sample designed to be representative of all third grade students in the state. Some states also conduct surveys of students in other grades in school, or of Head Start program enrollees. This surveillance activity is voluntary. States submit their data to the Association of State and Territorial Dental Directors (ASTDD), where the survey design and data collected are reviewed for quality and against the criteria for inclusion in NOHSS, before being sent to CDC for inclusion in Oral Health Data. For more information, see: http://www.cdc.gov/oralhealthdata/overview/childIndicators/

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                         | Data Type | Render Type |
| ======== | ============== | ============================================ | ============================================ | ========= | =========== |
| No       | time           | :updated_at                                  | updated_at                                   | meta_data | meta_data   |
| Yes      | series tag     | latestdataforgrade                           | LatestDataforGrade                           | text      | text        |
| Yes      | numeric metric | schoolyearstart                              | SchoolYearStart                              | number    | text        |
| Yes      | numeric metric | schoolyearend                                | SchoolYearEnd                                | number    | text        |
| Yes      | series tag     | locationabbr                                 | LocationAbbr                                 | text      | text        |
| Yes      | series tag     | topic                                        | Topic                                        | text      | text        |
| Yes      | series tag     | grade                                        | Grade                                        | text      | text        |
| Yes      | series tag     | indicator                                    | Indicator                                    | text      | text        |
| Yes      | series tag     | datasource                                   | DataSource                                   | text      | text        |
| No       |                | data_value_unit                              | Data_Value_Unit                              | text      | text        |
| No       |                | data_value_type                              | Data_Value_Type                              | text      | text        |
| Yes      | numeric metric | data_value                                   | Data_Value                                   | number    | number      |
| No       |                | data_value_footnote_symbol                   | Data_Value_Footnote_Symbol                   | text      | text        |
| No       |                | data_value_footnote                          | Data_Value_Footnote                          | text      | text        |
| Yes      | numeric metric | low_confidence_interval                      | Low_Confidence_Interval                      | number    | number      |
| Yes      | numeric metric | high_confidence_interval                     | High_Confidence_Interval                     | number    | number      |
| No       |                | confidence_interval_footnote_symbol          | Confidence_Interval_Footnote_Symbol          | text      | text        |
| No       |                | confidence_interval_footnote                 | Confidence_Interval_Footnote                 | text      | text        |
| Yes      | numeric metric | sample_size                                  | Sample_Size                                  | number    | number      |
| Yes      | numeric metric | response_rate                                | Response_Rate                                | number    | number      |
| No       |                | response_rate_footnote_symbol                | Response_Rate_Footnote_Symbol                | text      | text        |
| No       |                | response_rate_footnote                       | Response_Rate_Footnote                       | text      | text        |
| Yes      | series tag     | adjusted_for_nonresponse                     | Adjusted_for_NonResponse                     | text      | text        |
| Yes      | numeric metric | percent_eligible_for_the_nslp_sampleschools  | Percent_eligible_for_the_NSLP_SampleSchools  | number    | number      |
| No       |                | nslp_sampleschools_footnote_symbol           | NSLP_SampleSchools_Footnote_Symbol           | text      | text        |
| No       |                | nslp_sampleschools_footnote                  | NSLP_SampleSchools_Footnote                  | text      | text        |
| Yes      | numeric metric | percent_eligible_for_the_nslp_samplestudents | Percent_eligible_for_the_NSLP_SampleStudents | number    | number      |
| No       |                | nslp_samplestudents_footnote_symbol          | NSLP_SampleStudents_Footnote_Symbol          | text      | text        |
| No       |                | nslp_samplestudents_footnote                 | NSLP_SampleStudents_Footnote                 | text      | text        |
| Yes      | numeric metric | percent_eligible_for_the_nslp_state          | Percent_eligible_for_the_NSLP_State          | number    | number      |
| No       |                | nslp_state_footnote_symbol                   | NSLP_State_Footnote_Symbol                   | text      | text        |
| No       |                | nslp_state_footnote                          | NSLP_State_Footnote                          | text      | text        |
| Yes      | series tag     | locationdesc                                 | LocationDesc                                 | text      | text        |
| Yes      | series tag     | locationid                                   | LocationID                                   | text      | text        |
| Yes      | series tag     | gradeid                                      | GradeID                                      | text      | text        |
| Yes      | series tag     | sortgradeid                                  | SortGradeID                                  | text      | text        |
| Yes      | series tag     | indicatorid                                  | IndicatorID                                  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = data_value_unit,data_value_type,data_value_footnote_symbol,data_value_footnote,confidence_interval_footnote_symbol,confidence_interval_footnote,response_rate_footnote_symbol,response_rate_footnote,nslp_sampleschools_footnote_symbol,nslp_sampleschools_footnote,nslp_samplestudents_footnote_symbol,nslp_samplestudents_footnote,nslp_state_footnote_symbol,nslp_state_footnote
```

## Data Commands

```ls
series e:qcai-zfj9 d:2016-07-28T19:04:39.000Z t:topic=Child t:locationdesc=Colorado t:locationabbr=CO t:indicator="Caries Experience: Percentage of students with caries experience (treated or untreated tooth decay)" t:locationid=08 t:latestdataforgrade=Yes t:indicatorid=CHD1_1 t:sortgradeid=01 t:grade="Head Start" t:adjusted_for_nonresponse=Yes t:gradeid=HGRADE t:datasource="State Oral Health Survey" m:schoolyearstart=2013 m:response_rate=53 m:sample_size=739 m:high_confidence_interval=46.3 m:data_value=41.7 m:low_confidence_interval=37 m:schoolyearend=2014

series e:qcai-zfj9 d:2016-07-28T19:04:39.000Z t:topic=Child t:locationdesc=Colorado t:locationabbr=CO t:indicator="Untreated Tooth Decay: Percentage of students with untreated tooth decay" t:locationid=08 t:latestdataforgrade=Yes t:indicatorid=CHD1_3 t:sortgradeid=01 t:grade="Head Start" t:adjusted_for_nonresponse=Yes t:gradeid=HGRADE t:datasource="State Oral Health Survey" m:schoolyearstart=2013 m:response_rate=53 m:sample_size=739 m:high_confidence_interval=21.3 m:data_value=15.3 m:low_confidence_interval=9.4 m:schoolyearend=2014

series e:qcai-zfj9 d:2016-07-28T19:04:39.000Z t:topic=Child t:locationdesc=Connecticut t:locationabbr=CT t:indicator="Caries Experience: Percentage of students with caries experience (treated or untreated tooth decay)" t:locationid=09 t:latestdataforgrade=Yes t:indicatorid=CHD1_1 t:sortgradeid=01 t:grade="Head Start" t:adjusted_for_nonresponse=No t:gradeid=HGRADE t:datasource="State Oral Health Survey" m:schoolyearstart=2010 m:response_rate=77 m:sample_size=774 m:high_confidence_interval=27.6 m:data_value=19.3 m:low_confidence_interval=10.9 m:schoolyearend=2011
```

## Meta Commands

```ls
metric m:schoolyearstart p:integer l:SchoolYearStart d:"Four-digit year in which State Oral Health Survey began data collection" t:dataTypeName=number

metric m:schoolyearend p:integer l:SchoolYearEnd d:"Four-digit year in which data collection for State Oral Health Survey ended." t:dataTypeName=number

metric m:data_value p:float l:Data_Value d:"Prevalence estimate for indicator" t:dataTypeName=number

metric m:low_confidence_interval p:float l:Low_Confidence_Interval d:"Lower 95 percent confidence limit" t:dataTypeName=number

metric m:high_confidence_interval p:float l:High_Confidence_Interval d:"Upper 95 percent confidence limit" t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size d:"Number of children participating in the state oral health survey" t:dataTypeName=number

metric m:response_rate p:integer l:Response_Rate d:"Percentage of selected children who participated in the state oral health survey" t:dataTypeName=number

metric m:percent_eligible_for_the_nslp_sampleschools p:float l:Percent_eligible_for_the_NSLP_SampleSchools d:"Percentage of students in participating schools who were eligible for the National School Lunch Program" t:dataTypeName=number

metric m:percent_eligible_for_the_nslp_samplestudents p:float l:Percent_eligible_for_the_NSLP_SampleStudents d:"Percentage of students participating in the State Oral Health Survey who were eligible for the National School Lunch Program" t:dataTypeName=number

metric m:percent_eligible_for_the_nslp_state p:float l:Percent_eligible_for_the_NSLP_State d:"Percentage of students in the state who were eligible for the National School Lunch Program" t:dataTypeName=number

entity e:qcai-zfj9 l:"NOHSS Child Indicators" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Oral Health" t:url=https://data.cdc.gov/api/views/qcai-zfj9

property e:qcai-zfj9 t:meta.view v:id=qcai-zfj9 v:category="Oral Health" v:attributionLink=http://www.cdc.gov/oralhealth v:averageRating=0 v:name="NOHSS Child Indicators" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Oral Health"

property e:qcai-zfj9 t:meta.view.owner v:id=5ehu-79qp v:screenName="Oral Health Data Administrator" v:displayName="Oral Health Data Administrator"

property e:qcai-zfj9 t:meta.view.tableauthor v:id=5ehu-79qp v:screenName="Oral Health Data Administrator" v:roleName=publisher v:displayName="Oral Health Data Administrator"

property e:qcai-zfj9 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| :updated_at | latestdataforgrade | schoolyearstart | schoolyearend | locationabbr | topic | grade      | indicator                                                                                           | datasource               | data_value_unit | data_value_type | data_value | data_value_footnote_symbol | data_value_footnote | low_confidence_interval | high_confidence_interval | confidence_interval_footnote_symbol | confidence_interval_footnote | sample_size | response_rate | response_rate_footnote_symbol | response_rate_footnote | adjusted_for_nonresponse | percent_eligible_for_the_nslp_sampleschools | nslp_sampleschools_footnote_symbol | nslp_sampleschools_footnote | percent_eligible_for_the_nslp_samplestudents | nslp_samplestudents_footnote_symbol | nslp_samplestudents_footnote | percent_eligible_for_the_nslp_state | nslp_state_footnote_symbol | nslp_state_footnote | locationdesc | locationid | gradeid | sortgradeid | indicatorid | 
| =========== | ================== | =============== | ============= | ============ | ===== | ========== | =================================================================================================== | ======================== | =============== | =============== | ========== | ========================== | =================== | ======================= | ======================== | =================================== | ============================ | =========== | ============= | ============================= | ====================== | ======================== | =========================================== | ================================== | =========================== | ============================================ | =================================== | ============================ | =================================== | ========================== | =================== | ============ | ========== | ======= | =========== | =========== | 
| 1469732679  | Yes                | 2013            | 2014          | CO           | Child | Head Start | Caries Experience: Percentage of students with caries experience (treated or untreated tooth decay) | State Oral Health Survey | %               | Percentage      | 41.7       |                            |                     | 37.0                    | 46.3                     |                                     |                              | 739         | 53            |                               |                        | Yes                      |                                             | NA                                 | Not Applicable              |                                              | NA                                  | Not Applicable               |                                     | NA                         | Not Applicable      | Colorado     | 08         | HGRADE  | 01          | CHD1_1      | 
| 1469732679  | Yes                | 2013            | 2014          | CO           | Child | Head Start | Untreated Tooth Decay: Percentage of students with untreated tooth decay                            | State Oral Health Survey | %               | Percentage      | 15.3       |                            |                     | 9.4                     | 21.3                     |                                     |                              | 739         | 53            |                               |                        | Yes                      |                                             | NA                                 | Not Applicable              |                                              | NA                                  | Not Applicable               |                                     | NA                         | Not Applicable      | Colorado     | 08         | HGRADE  | 01          | CHD1_3      | 
| 1469732679  | Yes                | 2010            | 2011          | CT           | Child | Head Start | Caries Experience: Percentage of students with caries experience (treated or untreated tooth decay) | State Oral Health Survey | %               | Percentage      | 19.3       |                            |                     | 10.9                    | 27.6                     |                                     |                              | 774         | 77            |                               |                        | No                       |                                             | NA                                 | Not Applicable              |                                              | NA                                  | Not Applicable               |                                     | NA                         | Not Applicable      | Connecticut  | 09         | HGRADE  | 01          | CHD1_1      | 
| 1469732679  | Yes                | 2010            | 2011          | CT           | Child | Head Start | Untreated Tooth Decay: Percentage of students with untreated tooth decay                            | State Oral Health Survey | %               | Percentage      | 9.6        |                            |                     | 4.6                     | 14.5                     |                                     |                              | 774         | 77            |                               |                        | No                       |                                             | NA                                 | Not Applicable              |                                              | NA                                  | Not Applicable               |                                     | NA                         | Not Applicable      | Connecticut  | 09         | HGRADE  | 01          | CHD1_3      | 
| 1469732679  | Yes                | 2014            | 2015          | FL           | Child | Head Start | Caries Experience: Percentage of students with caries experience (treated or untreated tooth decay) | State Oral Health Survey | %               | Percentage      | 32.1       |                            |                     | 26.2                    | 37.9                     |                                     |                              | 1433        | 93            |                               |                        | Yes                      |                                             | NA                                 | Not Applicable              |                                              | NA                                  | Not Applicable               |                                     | NA                         | Not Applicable      | Florida      | 12         | HGRADE  | 01          | CHD1_1      | 
| 1469732679  | Yes                | 2014            | 2015          | FL           | Child | Head Start | Untreated Tooth Decay: Percentage of students with untreated tooth decay                            | State Oral Health Survey | %               | Percentage      | 20.8       |                            |                     | 15.5                    | 26.1                     |                                     |                              | 1433        | 93            |                               |                        | Yes                      |                                             | NA                                 | Not Applicable              |                                              | NA                                  | Not Applicable               |                                     | NA                         | Not Applicable      | Florida      | 12         | HGRADE  | 01          | CHD1_3      | 
| 1469732679  | Yes                | 2014            | 2015          | IA           | Child | Head Start | Caries Experience: Percentage of students with caries experience (treated or untreated tooth decay) | State Oral Health Survey | %               | Percentage      | 43.3       |                            |                     | 38.3                    | 48.4                     |                                     |                              | 1090        | 76            |                               |                        | No                       |                                             | NA                                 | Not Applicable              |                                              | NA                                  | Not Applicable               |                                     | NA                         | Not Applicable      | Iowa         | 19         | HGRADE  | 01          | CHD1_1      | 
| 1469732679  | Yes                | 2014            | 2015          | IA           | Child | Head Start | Untreated Tooth Decay: Percentage of students with untreated tooth decay                            | State Oral Health Survey | %               | Percentage      | 17.2       |                            |                     | 13.5                    | 21.7                     |                                     |                              | 1090        | 76            |                               |                        | No                       |                                             | NA                                 | Not Applicable              |                                              | NA                                  | Not Applicable               |                                     | NA                         | Not Applicable      | Iowa         | 19         | HGRADE  | 01          | CHD1_3      | 
| 1469732679  | Yes                | 2011            | 2012          | NV           | Child | Head Start | Caries Experience: Percentage of students with caries experience (treated or untreated tooth decay) | State Oral Health Survey | %               | Percentage      | 47.1       |                            |                     | 43.7                    | 50.5                     |                                     |                              | 2257        | 81            |                               |                        | Yes                      |                                             | NA                                 | Not Applicable              |                                              | NA                                  | Not Applicable               |                                     | NA                         | Not Applicable      | Nevada       | 32         | HGRADE  | 01          | CHD1_1      | 
| 1469732679  | Yes                | 2011            | 2012          | NV           | Child | Head Start | Untreated Tooth Decay: Percentage of students with untreated tooth decay                            | State Oral Health Survey | %               | Percentage      | 12.3       |                            |                     | 10.6                    | 14.1                     |                                     |                              | 2257        | 81            |                               |                        | Yes                      |                                             | NA                                 | Not Applicable              |                                              | NA                                  | Not Applicable               |                                     | NA                         | Not Applicable      | Nevada       | 32         | HGRADE  | 01          | CHD1_3      | 
```