# Behavioral Risk Factor Surveillance System (BRFSS) Historical Questions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/behavioral-risk-factor-surveillance-system-brfss-historical-questions) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/iuq5-y9ct) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/iuq5-y9ct/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/iuq5-y9ct/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | iuq5-y9ct |
| Name | Behavioral Risk Factor Surveillance System (BRFSS) Historical Questions |
| Attribution | Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Population Health Population Health Surveillance Branch |
| Category | Behavioral Risk Factors |
| Tags | questions, survey, brfss, behavioral, risk, factor, surveillance, system |
| Created | 2015-03-03T23:43:41Z |
| Publication Date | 2017-04-12T15:36:49Z |

## Description

1984-2016.  Centers for Disease Control and Prevention (CDC). BRFSS Survey Data.  The BRFSS is a continuous, state-based surveillance system that collects information about modifiable risk factors for chronic diseases and other leading causes of death.
Detailed information on sampling methodology and quality assurance can be found on the BRFSS website (http://www.cdc.gov/brfss).

http://apps.nccd.cdc.gov/BRFSSQuest/index.asp

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| Yes      | series tag  | topic        | Topic        | text      | text        |
| Yes      | series tag  | question     | Question     | text      | text        |
| Yes      | series tag  | variablename | VariableName | text      | text        |
| Yes      | series tag  | responses    | Responses    | text      | text        |
| Yes      | time        | year         | Year         | number    | number      |
| Yes      | series tag  | type         | Type         | text      | text        |
| No       |             | displayorder | DisplayOrder | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = displayorder
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:iuq5-y9ct l:"Behavioral Risk Factor Surveillance System (BRFSS) Historical Questions" t:attribution="Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Population Health Population Health Surveillance Branch" t:url=https://chronicdata.cdc.gov/api/views/iuq5-y9ct

property e:iuq5-y9ct t:meta.view v:id=iuq5-y9ct v:category="Behavioral Risk Factors" v:attributionLink=http://www.cdc.gov/BRFSS/ v:averageRating=0 v:name="Behavioral Risk Factor Surveillance System (BRFSS) Historical Questions" v:attribution="Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Population Health Population Health Surveillance Branch"

property e:iuq5-y9ct t:meta.view.license v:name="Public Domain"

property e:iuq5-y9ct t:meta.view.owner v:id=emuu-zcsq v:screenName=BRFSS v:displayName=BRFSS

property e:iuq5-y9ct t:meta.view.tableauthor v:id=emuu-zcsq v:screenName=BRFSS v:roleName=publisher v:displayName=BRFSS

property e:iuq5-y9ct t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| topic                       | question                                                                                                                                                                                                         | variablename | responses                                                                                                                                                                                                               | year | type          | displayorder | 
| =========================== | ================================================================================================================================================================================================================ | ============ | ======================================================================================================================================================================================================================= | ==== | ============= | ============ | 
| Health Status/Healthy Days  | Would you say that in general your health is---                                                                                                                                                                  | GENHLTH      | 1=Excellent 2=Very good 3=Good 4=Fair 5=Poor 7=DK/NS 9=Refused                                                                                                                                                          | 2013 | Core Question | 1            | 
| Health Status/Healthy Days  | Now thinking about your physical health, which includes physical illness and injury, for how many days during the past 30 days was your physical health not good? (Moved to Healthy Days in 2004)                | PHYSHLTH     | __ __=Number of days 88=None 77=DK/NS 99=Refused                                                                                                                                                                        | 2013 | Core Question | 2            | 
| Health Status/Healthy Days  | Now thinking about your mental health, which includes stress, depression, and problems with emotions, for how many days during the past 30 days was your mental health not good? (Moved to Healthy Days in 2004) | MENTHLTH     | __ __=Number of days 88=None 77=DK/NS 99=Refused                                                                                                                                                                        | 2013 | Core Question | 3            | 
| Health Status/Healthy Days  | During the past 30 days, for about how many days did poor physical or mental health keep you from doing your usual activities, such as self-care, work, or recreation? (Moved to Healthy Days in 2004)           | POORHLTH     | __ __=Number of days 88=None 77=DK/NS 99=Refused                                                                                                                                                                        | 2013 | Core Question | 4            | 
| Health Care Access          | Do you have any kind of health care coverage, including health insurance, prepaid plans such as HMOs, or government plans such as Medicare, or Indian Health Service?                                            | HLTHPLN1     | 1=Yes 2=No 7=DK/NS 9=Refused                                                                                                                                                                                            | 2013 | Core Question | 5            | 
| Health Care Coverage/Access | Do you have one person you think of as your personal doctor or health care provider? (If "No" ask "Is there more than one or is there no person who you think of?").                                             | PERSDOC2     | 1=Yes, only one 2=More than one 3=No 7=DK/NS 9=Refused                                                                                                                                                                  | 2013 | Core Question | 6            | 
| Health Care Coverage/Access | Was there a time during the past 12 months when you needed to see a doctor, but could not because of the cost?                                                                                                   | MEDCOST      | 1=Yes 2=No 7=DK/NS 9=Refused                                                                                                                                                                                            | 2013 | Core Question | 7            | 
| Health Care Coverage/Access | About how long has it been since you last visited a doctor for a routine checkup? A routine checkup is a general physical exam, not an exam for a specific injury, illness, or condition. (Variable name change) | CHECKUP1     | 1=Within past year (anytime less than 12 months ago) 2=Within past 2 years (1 year but less than 2 years ago) 3=Within past 5 years (2 years but less than 5 years ago) 4=5 or more years ago 7=DK/NS 8=Never 9=Refused | 2013 | Core Question | 8            | 
| Inadequate Sleep            | On average, how many hours of sleep do you get in a 24-hour period?                                                                                                                                              | SLEPTIM1     | 1-24=Number of hours [1-24] 77=DK/NS 99=Refused                                                                                                                                                                         | 2013 | Core Question | 9            | 
| Hypertension (Awareness)    | Have you ever been told by a doctor, nurse, or other health professional that you have high blood pressure? (If "Yes" and respondent is female, ask "Was this only when you were pregnant?").                    | BPHIGH4      | 1=Yes 2=Yes, but female told only during pregnancy 3=No 4=Told borderline high or pre-hypertensive 7=DK/NS 9=Refused                                                                                                    | 2013 | Core Question | 10           | 
```