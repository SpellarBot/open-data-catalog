# Nutrition, Physical Activity, and Obesity - Youth Risk Behavior Surveillance System

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nutrition-physical-activity-and-obesity-youth-risk-behavior-surveillance-system-bf946) |
| Metadata | [Link](https://data.cdc.gov/api/views/vba9-s8jp) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/vba9-s8jp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/vba9-s8jp/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | vba9-s8jp |
| Name | Nutrition, Physical Activity, and Obesity - Youth Risk Behavior Surveillance System |
| Attribution | Centers for Disease Control and Prevention (CDC), National Center for Chronic Disease Prevention and Health Promotion, Division of Nutrition, Physical Activity, and Obesity |
| Category | Nutrition, Physical Activity, and Obesity |
| Tags | adolescents, obesity, overweight, fruit, vegetables, physical activity, soda, tv, yrbss, dnpao |
| Created | 2016-07-22T10:37:39Z |
| Publication Date | 2016-12-19T13:56:22Z |

## Description

This dataset includes data on adolescent's diet, physical activity, and weight status from Youth Risk Behavior Surveillance System. This data is used for DNPAO's Data, Trends, and Maps database, which provides national and state specific data on obesity, nutrition, physical activity, and breastfeeding.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | yearstart                  | YearStart                  | number    | number      |
| No       |                | yearend                    | YearEnd                    | number    | number      |
| Yes      | series tag     | locationabbr               | LocationAbbr               | text      | text        |
| Yes      | series tag     | locationdesc               | LocationDesc               | text      | text        |
| Yes      | series tag     | datasource                 | Datasource                 | text      | text        |
| Yes      | series tag     | class                      | Class                      | text      | text        |
| Yes      | series tag     | topic                      | Topic                      | text      | text        |
| Yes      | series tag     | question                   | Question                   | text      | text        |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| No       |                | data_value_alt             | Data_Value_Alt             | number    | number      |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | numeric metric | low_confidence_limit       | Low_Confidence_Limit       | number    | number      |
| Yes      | numeric metric | high_confidence_limit      | High_Confidence_Limit      | number    | number      |
| Yes      | numeric metric | sample_size                | Sample_Size                | number    | number      |
| Yes      | series tag     | total                      | Total                      | text      | text        |
| Yes      | series tag     | gender                     | Gender                     | text      | text        |
| Yes      | series tag     | grade                      | Grade                      | text      | text        |
| Yes      | series tag     | race_ethnicity             | Race/Ethnicity             | text      | text        |
| Yes      | series tag     | classid                    | ClassID                    | text      | text        |
| Yes      | series tag     | topicid                    | TopicID                    | text      | text        |
| Yes      | series tag     | questionid                 | QuestionID                 | text      | text        |
| Yes      | series tag     | datavaluetypeid            | DataValueTypeID            | text      | text        |
| Yes      | series tag     | locationid                 | LocationID                 | text      | text        |
| Yes      | series tag     | stratificationcategory1    | StratificationCategory1    | text      | text        |
| Yes      | series tag     | stratification1            | Stratification1            | text      | text        |
| Yes      | series tag     | stratificationcategoryid1  | StratificationCategoryId1  | text      | text        |
| Yes      | series tag     | stratificationid1          | StratificationID1          | text      | text        |
```

## Time Field

```ls
Value = yearstart
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = yearend,data_value_unit,data_value_type,data_value_alt,data_value_footnote_symbol,data_value_footnote
```

## Data Commands

```ls
series e:vba9-s8jp d:2001-01-01T00:00:00.000Z t:total=Total t:topic="Obesity / Weight Status" t:locationabbr=AL t:locationdesc=Alabama t:topicid=OWS1 t:stratificationid1=OVERALL t:class="Obesity / Weight Status" t:questionid=Q038 t:locationid=01 t:stratificationcategoryid1=OVR t:stratification1=Total t:stratificationcategory1=Total t:question="Percent of students in grades 9-12 who are obese" t:datavaluetypeid=VALUE t:datasource="Youth Risk Behavior Surveillance System" t:classid=OWS m:high_confidence_limit=15.2 m:sample_size=1526 m:data_value=12.3 m:low_confidence_limit=9.8

series e:vba9-s8jp d:2001-01-01T00:00:00.000Z t:topic="Obesity / Weight Status" t:locationabbr=AL t:locationdesc=Alabama t:topicid=OWS1 t:stratificationid1=FEMALE t:class="Obesity / Weight Status" t:questionid=Q038 t:locationid=01 t:stratificationcategoryid1=GEN t:stratification1=Female t:stratificationcategory1=Gender t:gender=Female t:question="Percent of students in grades 9-12 who are obese" t:datavaluetypeid=VALUE t:datasource="Youth Risk Behavior Surveillance System" t:classid=OWS m:high_confidence_limit=10.4 m:sample_size=831 m:data_value=7.6 m:low_confidence_limit=5.4

series e:vba9-s8jp d:2001-01-01T00:00:00.000Z t:topic="Obesity / Weight Status" t:locationabbr=AL t:locationdesc=Alabama t:topicid=OWS1 t:stratificationid1=RACEWHT t:race_ethnicity="Non-Hispanic White" t:class="Obesity / Weight Status" t:questionid=Q038 t:locationid=01 t:stratificationcategoryid1=RACE t:stratification1="Non-Hispanic White" t:stratificationcategory1=Race/Ethnicity t:question="Percent of students in grades 9-12 who are obese" t:datavaluetypeid=VALUE t:datasource="Youth Risk Behavior Surveillance System" t:classid=OWS m:high_confidence_limit=14.4 m:sample_size=885 m:data_value=10.2 m:low_confidence_limit=7.2
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit t:dataTypeName=number

metric m:high_confidence_limit p:float l:High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

entity e:vba9-s8jp l:"Nutrition, Physical Activity, and Obesity - Youth Risk Behavior Surveillance System" t:attribution="Centers for Disease Control and Prevention (CDC), National Center for Chronic Disease Prevention and Health Promotion, Division of Nutrition, Physical Activity, and Obesity" t:url=https://data.cdc.gov/api/views/vba9-s8jp

property e:vba9-s8jp t:meta.view v:id=vba9-s8jp v:category="Nutrition, Physical Activity, and Obesity" v:attributionLink=http://www.cdc.gov/nccdphp/DNPAO/index.html v:averageRating=0 v:name="Nutrition, Physical Activity, and Obesity - Youth Risk Behavior Surveillance System" v:attribution="Centers for Disease Control and Prevention (CDC), National Center for Chronic Disease Prevention and Health Promotion, Division of Nutrition, Physical Activity, and Obesity"

property e:vba9-s8jp t:meta.view.license v:name="Public Domain"

property e:vba9-s8jp t:meta.view.owner v:id=cvya-y955 v:screenName="LV Moore" v:displayName="LV Moore"

property e:vba9-s8jp t:meta.view.tableauthor v:id=cvya-y955 v:screenName="LV Moore" v:roleName=publisher v:displayName="LV Moore"

property e:vba9-s8jp t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| yearstart | yearend | locationabbr | locationdesc | datasource                              | class                   | topic                   | question                                         | data_value_unit | data_value_type | data_value | data_value_alt | data_value_footnote_symbol | data_value_footnote                                     | low_confidence_limit | high_confidence_limit | sample_size | total | gender | grade | race_ethnicity                | classid | topicid | questionid | datavaluetypeid | locationid | stratificationcategory1 | stratification1               | stratificationcategoryid1 | stratificationid1 | 
| ========= | ======= | ============ | ============ | ======================================= | ======================= | ======================= | ================================================ | =============== | =============== | ========== | ============== | ========================== | ======================================================= | ==================== | ===================== | =========== | ===== | ====== | ===== | ============================= | ======= | ======= | ========== | =============== | ========== | ======================= | ============================= | ========================= | ================= | 
| 2001      | 2001    | AL           | Alabama      | Youth Risk Behavior Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of students in grades 9-12 who are obese |                 | Value           | 12.3       | 12.3           |                            |                                                         | 9.8                  | 15.2                  | 1526        | Total |        |       |                               | OWS     | OWS1    | Q038       | VALUE           | 01         | Total                   | Total                         | OVR                       | OVERALL           | 
| 2001      | 2001    | AL           | Alabama      | Youth Risk Behavior Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of students in grades 9-12 who are obese |                 | Value           | 7.6        | 7.6            |                            |                                                         | 5.4                  | 10.4                  | 831         |       | Female |       |                               | OWS     | OWS1    | Q038       | VALUE           | 01         | Gender                  | Female                        | GEN                       | FEMALE            | 
| 2001      | 2001    | AL           | Alabama      | Youth Risk Behavior Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of students in grades 9-12 who are obese |                 | Value           |            |                | ~                          | Data not available because sample size is insufficient. |                      |                       |             |       |        |       | 2 or more races               | OWS     | OWS1    | Q038       | VALUE           | 01         | Race/Ethnicity          | 2 or more races               | RACE                      | RACE2PLUS         | 
| 2001      | 2001    | AL           | Alabama      | Youth Risk Behavior Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of students in grades 9-12 who are obese |                 | Value           | 10.2       | 10.2           |                            |                                                         | 7.2                  | 14.4                  | 885         |       |        |       | Non-Hispanic White            | OWS     | OWS1    | Q038       | VALUE           | 01         | Race/Ethnicity          | Non-Hispanic White            | RACE                      | RACEWHT           | 
| 2001      | 2001    | AL           | Alabama      | Youth Risk Behavior Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of students in grades 9-12 who are obese |                 | Value           |            |                | ~                          | Data not available because sample size is insufficient. |                      |                       |             |       |        |       | Hawaiian/Pacific Islander     | OWS     | OWS1    | Q038       | VALUE           | 01         | Race/Ethnicity          | Hawaiian/Pacific Islander     | RACE                      | RACEHPI           | 
| 2001      | 2001    | AL           | Alabama      | Youth Risk Behavior Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of students in grades 9-12 who are obese |                 | Value           |            |                | ~                          | Data not available because sample size is insufficient. |                      |                       |             |       |        |       | Hispanic                      | OWS     | OWS1    | Q038       | VALUE           | 01         | Race/Ethnicity          | Hispanic                      | RACE                      | RACEHIS           | 
| 2001      | 2001    | AL           | Alabama      | Youth Risk Behavior Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of students in grades 9-12 who are obese |                 | Value           | 16.2       | 16.2           |                            |                                                         | 13.3                 | 19.5                  | 523         |       |        |       | Non-Hispanic Black            | OWS     | OWS1    | Q038       | VALUE           | 01         | Race/Ethnicity          | Non-Hispanic Black            | RACE                      | RACEBLK           | 
| 2001      | 2001    | AL           | Alabama      | Youth Risk Behavior Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of students in grades 9-12 who are obese |                 | Value           |            |                | ~                          | Data not available because sample size is insufficient. |                      |                       |             |       |        |       | Asian                         | OWS     | OWS1    | Q038       | VALUE           | 01         | Race/Ethnicity          | Asian                         | RACE                      | RACEASN           | 
| 2001      | 2001    | AL           | Alabama      | Youth Risk Behavior Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of students in grades 9-12 who are obese |                 | Value           |            |                | ~                          | Data not available because sample size is insufficient. |                      |                       |             |       |        |       | American Indian/Alaska Native | OWS     | OWS1    | Q038       | VALUE           | 01         | Race/Ethnicity          | American Indian/Alaska Native | RACE                      | RACENAA           | 
| 2001      | 2001    | AL           | Alabama      | Youth Risk Behavior Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of students in grades 9-12 who are obese |                 | Value           | 13.6       | 13.6           |                            |                                                         | 8.5                  | 21.1                  | 256         |       |        | 12th  |                               | OWS     | OWS1    | Q038       | VALUE           | 01         | Grade                   | 12th                          | GRADE                     | GRADE12           | 
```