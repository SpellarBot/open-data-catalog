# DASH - Youth Risk Behavior Surveillance System (YRBSS): High School

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dash-youth-risk-behavior-surveillance-system-yrbss-high-school) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/svam-8dhg) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/svam-8dhg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/svam-8dhg/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | svam-8dhg |
| Name | DASH - Youth Risk Behavior Surveillance System (YRBSS): High School |
| Category | Youth Risk Behaviors |
| Created | 2016-08-29T14:00:36Z |
| Publication Date | 2017-03-30T15:04:10Z |

## Description

1991-2015. High School Dataset. The Youth Risk Behavior Surveillance System (YRBSS) monitors six categories of priority health behaviors 
among youth and young adults: 1) behaviors that contribute to unintentional injuries and violence; 2) tobacco use; 3) alcohol and 
other drug use; 4) sexual behaviors related to unintended pregnancy and sexually transmitted infections (STIs), including human 
immunodeficiency virus (HIV) infection; 5) unhealthy dietary behaviors; and 6) physical inactivity. In addition, YRBSS monitors 
the prevalence of obesity and asthma and other priority health behaviors.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                    | Data Type | Render Type |
| ======== | ============== | ======================================= | ======================================= | ========= | =========== |
| Yes      | time           | year                                    | YEAR                                    | number    | number      |
| Yes      | series tag     | locationabbr                            | LocationAbbr                            | text      | text        |
| Yes      | series tag     | locationdesc                            | LocationDesc                            | text      | text        |
| Yes      | series tag     | datasource                              | DataSource                              | text      | text        |
| Yes      | series tag     | topic                                   | Topic                                   | text      | text        |
| Yes      | series tag     | subtopic                                | Subtopic                                | text      | text        |
| Yes      | series tag     | shortquestiontext                       | ShortQuestionText                       | text      | text        |
| Yes      | series tag     | greater_risk_question                   | Greater_Risk_Question                   | text      | text        |
| Yes      | series tag     | description                             | Description                             | text      | text        |
| Yes      | series tag     | data_value_symbol                       | Data_Value_Symbol                       | text      | text        |
| No       |                | data_value_type                         | Data_Value_Type                         | text      | text        |
| Yes      | numeric metric | greater_risk_data_value                 | Greater_Risk_Data_Value                 | number    | number      |
| No       |                | greater_risk_data_value_footnote_symbol | Greater_Risk_Data_Value_Footnote_Symbol | text      | text        |
| No       |                | greater_risk_data_value_footnote        | Greater_Risk_Data_Value_Footnote        | text      | text        |
| Yes      | numeric metric | greater_risk_low_confidence_limit       | Greater_Risk_Low_Confidence_Limit       | number    | number      |
| Yes      | numeric metric | greater_risk_high_confidence_limit      | Greater_Risk_High_Confidence_Limit      | number    | number      |
| Yes      | series tag     | lesser_risk_question                    | Lesser_Risk_Question                    | text      | text        |
| Yes      | numeric metric | lesser_risk_data_value                  | Lesser_Risk_Data_Value                  | number    | number      |
| No       |                | lesser_risk_data_value_footnote_symbol  | Lesser_Risk_Data_Value_Footnote_Symbol  | text      | text        |
| No       |                | lesser_risk_data_value_footnote         | Lesser_Risk_Data_Value_Footnote         | text      | text        |
| Yes      | numeric metric | lesser_risk_low_confidence_limit        | Lesser_Risk_Low_Confidence_Limit        | number    | number      |
| Yes      | numeric metric | lesser_risk_high_confidence_limit       | Lesser_Risk_High_Confidence_Limit       | number    | number      |
| Yes      | numeric metric | sample_size                             | Sample_Size                             | number    | number      |
| Yes      | series tag     | sex                                     | Sex                                     | text      | text        |
| Yes      | series tag     | race                                    | Race                                    | text      | text        |
| Yes      | series tag     | grade                                   | Grade                                   | text      | text        |
| Yes      | series tag     | sexualidentity                          | SexualIdentity                          | text      | text        |
| Yes      | series tag     | sexofsexualcontacts                     | SexOfSexualContacts                     | text      | text        |
| Yes      | series tag     | topicid                                 | TopicId                                 | text      | text        |
| Yes      | series tag     | subtopicid                              | SubTopicID                              | text      | text        |
| Yes      | series tag     | questioncode                            | QuestionCode                            | text      | text        |
| Yes      | series tag     | locationid                              | LocationId                              | text      | text        |
| Yes      | series tag     | stratid1                                | StratID1                                | text      | text        |
| Yes      | series tag     | stratid2                                | StratID2                                | text      | text        |
| Yes      | series tag     | stratid3                                | StratID3                                | text      | text        |
| Yes      | series tag     | stratid4                                | StratID4                                | text      | text        |
| Yes      | series tag     | stratid5                                | StratID5                                | text      | text        |
| Yes      | series tag     | stratid6                                | StratID6                                | text      | text        |
| Yes      | series tag     | stratificationtype                      | StratificationType                      | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_type,greater_risk_data_value_footnote_symbol,greater_risk_data_value_footnote,lesser_risk_data_value_footnote_symbol,lesser_risk_data_value_footnote
```

## Data Commands

```ls
series e:svam-8dhg d:2009-01-01T00:00:00.000Z t:topic="Unintentional Injuries and Violence" t:stratid3=G2 t:locationdesc="Orange County, FL" t:locationabbr=OL t:subtopic="Behaviors that Contribute to Violence" t:sex=Female t:topicid=UIV01 t:stratid1=S7 t:stratid2=R1 t:stratificationtype=Local t:shortquestiontext="Gun carrying" t:greater_risk_question="Carried a gun" t:data_value_symbol=% t:race=Total t:subtopicid=VIO01 t:questioncode=H14 t:lesser_risk_question="Did not carry a gun" t:locationid=109 t:description="on at least 1 day during the 30 days before the survey" t:grade=9th t:datasource=YRBSS m:greater_risk_data_value=3.23 m:greater_risk_high_confidence_limit=6.9099 m:sample_size=195 m:greater_risk_low_confidence_limit=1.4787 m:lesser_risk_high_confidence_limit=98.5213 m:lesser_risk_low_confidence_limit=93.0901 m:lesser_risk_data_value=96.77

series e:svam-8dhg d:1999-01-01T00:00:00.000Z t:topic="Unintentional Injuries and Violence" t:stratid3=G2 t:locationdesc="Philadelphia, PA" t:locationabbr=PH t:subtopic="Behaviors that Contribute to Violence" t:sex=Female t:topicid=UIV01 t:stratid1=S7 t:stratid2=R1 t:stratificationtype=Local t:shortquestiontext="Gun carrying" t:greater_risk_question="Carried a gun" t:data_value_symbol=% t:race=Total t:subtopicid=VIO01 t:questioncode=H14 t:lesser_risk_question="Did not carry a gun" t:locationid=124 t:description="on at least 1 day during the 30 days before the survey" t:grade=9th t:datasource=YRBSS m:greater_risk_data_value=2.2589 m:greater_risk_high_confidence_limit=4.3819 m:sample_size=245 m:greater_risk_low_confidence_limit=1.1521 m:lesser_risk_high_confidence_limit=98.8479 m:lesser_risk_low_confidence_limit=95.6181 m:lesser_risk_data_value=97.7411

series e:svam-8dhg d:2003-01-01T00:00:00.000Z t:topic="Unintentional Injuries and Violence" t:stratid3=G2 t:locationdesc="Palm Beach County, FL" t:locationabbr=PB t:subtopic="Behaviors that Contribute to Violence" t:sex=Female t:topicid=UIV01 t:stratid1=S7 t:stratid2=R1 t:stratificationtype=Local t:shortquestiontext="Gun carrying" t:greater_risk_question="Carried a gun" t:data_value_symbol=% t:race=Total t:subtopicid=VIO01 t:questioncode=H14 t:lesser_risk_question="Did not carry a gun" t:locationid=110 t:description="on at least 1 day during the 30 days before the survey" t:grade=9th t:datasource=YRBSS m:greater_risk_data_value=2.7469 m:greater_risk_high_confidence_limit=7.6206 m:sample_size=237 m:greater_risk_low_confidence_limit=0.9578 m:lesser_risk_high_confidence_limit=99.0422 m:lesser_risk_low_confidence_limit=92.3794 m:lesser_risk_data_value=97.2531
```

## Meta Commands

```ls
metric m:greater_risk_data_value p:double l:Greater_Risk_Data_Value t:dataTypeName=number

metric m:greater_risk_low_confidence_limit p:double l:Greater_Risk_Low_Confidence_Limit t:dataTypeName=number

metric m:greater_risk_high_confidence_limit p:double l:Greater_Risk_High_Confidence_Limit t:dataTypeName=number

metric m:lesser_risk_data_value p:double l:Lesser_Risk_Data_Value t:dataTypeName=number

metric m:lesser_risk_low_confidence_limit p:double l:Lesser_Risk_Low_Confidence_Limit t:dataTypeName=number

metric m:lesser_risk_high_confidence_limit p:double l:Lesser_Risk_High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

entity e:svam-8dhg l:"DASH - Youth Risk Behavior Surveillance System (YRBSS): High School" t:url=https://chronicdata.cdc.gov/api/views/svam-8dhg

property e:svam-8dhg t:meta.view v:id=svam-8dhg v:category="Youth Risk Behaviors" v:averageRating=0 v:name="DASH - Youth Risk Behavior Surveillance System (YRBSS): High School"

property e:svam-8dhg t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:svam-8dhg t:meta.view.owner v:id=fjjr-gap9 v:screenName="The Su" v:lastNotificationSeenAt=1492539263 v:displayName="The Su"

property e:svam-8dhg t:meta.view.tableauthor v:id=fjjr-gap9 v:screenName="The Su" v:roleName=administrator v:lastNotificationSeenAt=1492539263 v:displayName="The Su"

property e:svam-8dhg t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC Info" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | locationabbr | locationdesc          | datasource | topic                               | subtopic                              | shortquestiontext | greater_risk_question | description                                            | data_value_symbol | data_value_type | greater_risk_data_value | greater_risk_data_value_footnote_symbol | greater_risk_data_value_footnote | greater_risk_low_confidence_limit | greater_risk_high_confidence_limit | lesser_risk_question | lesser_risk_data_value | lesser_risk_data_value_footnote_symbol | lesser_risk_data_value_footnote | lesser_risk_low_confidence_limit | lesser_risk_high_confidence_limit | sample_size | sex    | race  | grade | sexualidentity | sexofsexualcontacts | topicid | subtopicid | questioncode | locationid | stratid1 | stratid2 | stratid3 | stratid4 | stratid5 | stratid6 | stratificationtype | 
| ==== | ============ | ===================== | ========== | =================================== | ===================================== | ================= | ===================== | ====================================================== | ================= | =============== | ======================= | ======================================= | ================================ | ================================= | ================================== | ==================== | ====================== | ====================================== | =============================== | ================================ | ================================= | =========== | ====== | ===== | ===== | ============== | =================== | ======= | ========== | ============ | ========== | ======== | ======== | ======== | ======== | ======== | ======== | ================== | 
| 2009 | OL           | Orange County, FL     | YRBSS      | Unintentional Injuries and Violence | Behaviors that Contribute to Violence | Gun carrying      | Carried a gun         | on at least 1 day during the 30 days before the survey | %                 | Percentage      | 3.23                    |                                         |                                  | 1.4787                            | 6.9099                             | Did not carry a gun  | 96.77                  |                                        |                                 | 93.0901                          | 98.5213                           | 195         | Female | Total | 9th   |                |                     | UIV01   | VIO01      | H14          | 109        | S7       | R1       | G2       |          |          |          | Local              | 
| 1999 | PH           | Philadelphia, PA      | YRBSS      | Unintentional Injuries and Violence | Behaviors that Contribute to Violence | Gun carrying      | Carried a gun         | on at least 1 day during the 30 days before the survey | %                 | Percentage      | 2.2589                  |                                         |                                  | 1.1521                            | 4.3819                             | Did not carry a gun  | 97.7411                |                                        |                                 | 95.6181                          | 98.8479                           | 245         | Female | Total | 9th   |                |                     | UIV01   | VIO01      | H14          | 124        | S7       | R1       | G2       |          |          |          | Local              | 
| 2003 | PB           | Palm Beach County, FL | YRBSS      | Unintentional Injuries and Violence | Behaviors that Contribute to Violence | Gun carrying      | Carried a gun         | on at least 1 day during the 30 days before the survey | %                 | Percentage      | 2.7469                  |                                         |                                  | 0.9578                            | 7.6206                             | Did not carry a gun  | 97.2531                |                                        |                                 | 92.3794                          | 99.0422                           | 237         | Female | Total | 9th   |                |                     | UIV01   | VIO01      | H14          | 110        | S7       | R1       | G2       |          |          |          | Local              | 
| 2011 | PH           | Philadelphia, PA      | YRBSS      | Unintentional Injuries and Violence | Behaviors that Contribute to Violence | Gun carrying      | Carried a gun         | on at least 1 day during the 30 days before the survey | %                 | Percentage      | 1.869                   |                                         |                                  | 0.6164                            | 5.5255                             | Did not carry a gun  | 98.131                 |                                        |                                 | 94.4745                          | 99.3836                           | 206         | Female | Total | 9th   |                |                     | UIV01   | VIO01      | H14          | 124        | S7       | R1       | G2       |          |          |          | Local              | 
| 2013 | OL           | Orange County, FL     | YRBSS      | Unintentional Injuries and Violence | Behaviors that Contribute to Violence | Gun carrying      | Carried a gun         | on at least 1 day during the 30 days before the survey | %                 | Percentage      | 0.7331                  |                                         |                                  | 0.1696                            | 3.1107                             | Did not carry a gun  | 99.2669                |                                        |                                 | 96.8893                          | 99.8304                           | 259         | Female | Total | 9th   |                |                     | UIV01   | VIO01      | H14          | 109        | S7       | R1       | G2       |          |          |          | Local              | 
| 2015 | PH           | Philadelphia, PA      | YRBSS      | Unintentional Injuries and Violence | Behaviors that Contribute to Violence | Gun carrying      | Carried a gun         | on at least 1 day during the 30 days before the survey | %                 | Percentage      | 0.8453                  |                                         |                                  | 0.27                              | 2.6145                             | Did not carry a gun  | 99.1547                |                                        |                                 | 97.3855                          | 99.73                             | 277         | Female | Total | 9th   |                |                     | UIV01   | VIO01      | H14          | 124        | S7       | R1       | G2       |          |          |          | Local              | 
| 2011 | PR           | Puerto Rico           | YRBSS      | Unintentional Injuries and Violence | Behaviors that Contribute to Violence | Gun carrying      | Carried a gun         | on at least 1 day during the 30 days before the survey | %                 | Percentage      | 1.5111                  |                                         |                                  | 0.4463                            | 4.9894                             | Did not carry a gun  | 98.4889                |                                        |                                 | 95.0106                          | 99.5537                           | 270         | Female | Total | 9th   |                |                     | UIV01   | VIO01      | H14          | 72         | S7       | R1       | G2       |          |          |          | Territory          | 
| 1999 | PB           | Palm Beach County, FL | YRBSS      | Unintentional Injuries and Violence | Behaviors that Contribute to Violence | Gun carrying      | Carried a gun         | on at least 1 day during the 30 days before the survey | %                 | Percentage      | 2.5745                  |                                         |                                  | 1.2125                            | 5.3833                             | Did not carry a gun  | 97.4255                |                                        |                                 | 94.6167                          | 98.7875                           | 245         | Female | Total | 9th   |                |                     | UIV01   | VIO01      | H14          | 110        | S7       | R1       | G2       |          |          |          | Local              | 
| 2015 | PB           | Palm Beach County, FL | YRBSS      | Unintentional Injuries and Violence | Behaviors that Contribute to Violence | Gun carrying      | Carried a gun         | on at least 1 day during the 30 days before the survey | %                 | Percentage      | 1.6215                  |                                         |                                  | 0.54                              | 4.7653                             | Did not carry a gun  | 98.3785                |                                        |                                 | 95.2347                          | 99.46                             | 239         | Female | Total | 9th   |                |                     | UIV01   | VIO01      | H14          | 110        | S7       | R1       | G2       |          |          |          | Local              | 
| 2009 | PH           | Philadelphia, PA      | YRBSS      | Unintentional Injuries and Violence | Behaviors that Contribute to Violence | Gun carrying      | Carried a gun         | on at least 1 day during the 30 days before the survey | %                 | Percentage      | 1.8034                  |                                         |                                  | 0.29                              | 10.3898                            | Did not carry a gun  | 98.1966                |                                        |                                 | 89.6102                          | 99.71                             | 146         | Female | Total | 9th   |                |                     | UIV01   | VIO01      | H14          | 124        | S7       | R1       | G2       |          |          |          | Local              | 
```