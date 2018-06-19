# Nutrition, Physical Activity, and Obesity - Behavioral Risk Factor Surveillance System

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nutrition-physical-activity-and-obesity-behavioral-risk-factor-surveillance-system-f645f) |
| Metadata | [Link](https://data.cdc.gov/api/views/hn4x-zwk7) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/hn4x-zwk7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/hn4x-zwk7/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | hn4x-zwk7 |
| Name | Nutrition, Physical Activity, and Obesity - Behavioral Risk Factor Surveillance System |
| Attribution | Centers for Disease Control and Prevention (CDC), National Center for Chronic Disease Prevention and Health Promotion, Division of Nutrition, Physical Activity, and Obesity |
| Category | Nutrition, Physical Activity, and Obesity |
| Tags | adults, obesity, overweight, fruit, vegetables, walking, physical activity, nutrition, dnpao, brfss |
| Created | 2016-07-21T17:53:38Z |
| Publication Date | 2016-12-19T17:04:27Z |

## Description

This dataset includes data on adult's diet, physical activity, and weight status from Behavioral Risk Factor Surveillance System. This data is used for DNPAO's Data, Trends, and Maps database, which provides national and state specific data on obesity, nutrition, physical activity, and breastfeeding.

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
| Yes      | series tag     | age_years                  | Age(years)                 | text      | text        |
| Yes      | series tag     | education                  | Education                  | text      | text        |
| Yes      | series tag     | gender                     | Gender                     | text      | text        |
| Yes      | series tag     | income                     | Income                     | text      | text        |
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
series e:hn4x-zwk7 d:2011-01-01T00:00:00.000Z t:total=Total t:topic="Obesity / Weight Status" t:locationabbr=AL t:locationdesc=Alabama t:topicid=OWS1 t:stratificationid1=OVERALL t:class="Obesity / Weight Status" t:questionid=Q036 t:locationid=01 t:stratificationcategoryid1=OVR t:stratification1=Total t:stratificationcategory1=Total t:question="Percent of adults aged 18 years and older who are obese" t:datavaluetypeid=VALUE t:datasource="Behavioral Risk Factor Surveillance System" t:classid=OWS m:high_confidence_limit=33.5 m:sample_size=7304 m:data_value=32 m:low_confidence_limit=30.5

series e:hn4x-zwk7 d:2011-01-01T00:00:00.000Z t:topic="Obesity / Weight Status" t:locationabbr=AL t:locationdesc=Alabama t:topicid=OWS1 t:stratificationid1=MALE t:class="Obesity / Weight Status" t:questionid=Q036 t:locationid=01 t:stratificationcategoryid1=GEN t:stratification1=Male t:stratificationcategory1=Gender t:gender=Male t:question="Percent of adults aged 18 years and older who are obese" t:datavaluetypeid=VALUE t:datasource="Behavioral Risk Factor Surveillance System" t:classid=OWS m:high_confidence_limit=34.7 m:sample_size=2581 m:data_value=32.3 m:low_confidence_limit=29.9

series e:hn4x-zwk7 d:2011-01-01T00:00:00.000Z t:topic="Obesity / Weight Status" t:locationabbr=AL t:locationdesc=Alabama t:topicid=OWS1 t:stratificationid1=FEMALE t:class="Obesity / Weight Status" t:questionid=Q036 t:locationid=01 t:stratificationcategoryid1=GEN t:stratification1=Female t:stratificationcategory1=Gender t:gender=Female t:question="Percent of adults aged 18 years and older who are obese" t:datavaluetypeid=VALUE t:datasource="Behavioral Risk Factor Surveillance System" t:classid=OWS m:high_confidence_limit=33.6 m:sample_size=4723 m:data_value=31.8 m:low_confidence_limit=30
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit t:dataTypeName=number

metric m:high_confidence_limit p:float l:High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

entity e:hn4x-zwk7 l:"Nutrition, Physical Activity, and Obesity - Behavioral Risk Factor Surveillance System" t:attribution="Centers for Disease Control and Prevention (CDC), National Center for Chronic Disease Prevention and Health Promotion, Division of Nutrition, Physical Activity, and Obesity" t:url=https://data.cdc.gov/api/views/hn4x-zwk7

property e:hn4x-zwk7 t:meta.view v:id=hn4x-zwk7 v:category="Nutrition, Physical Activity, and Obesity" v:attributionLink=http://www.cdc.gov/nccdphp/DNPAO/index.html v:averageRating=0 v:name="Nutrition, Physical Activity, and Obesity - Behavioral Risk Factor Surveillance System" v:attribution="Centers for Disease Control and Prevention (CDC), National Center for Chronic Disease Prevention and Health Promotion, Division of Nutrition, Physical Activity, and Obesity"

property e:hn4x-zwk7 t:meta.view.license v:name="Public Domain"

property e:hn4x-zwk7 t:meta.view.owner v:id=cvya-y955 v:screenName="LV Moore" v:displayName="LV Moore"

property e:hn4x-zwk7 t:meta.view.tableauthor v:id=cvya-y955 v:screenName="LV Moore" v:roleName=publisher v:displayName="LV Moore"

property e:hn4x-zwk7 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| yearstart | yearend | locationabbr | locationdesc | datasource                                 | class                   | topic                   | question                                                | data_value_unit | data_value_type | data_value | data_value_alt | data_value_footnote_symbol | data_value_footnote | low_confidence_limit | high_confidence_limit | sample_size | total | age_years | education                        | gender | income | race_ethnicity | classid | topicid | questionid | datavaluetypeid | locationid | stratificationcategory1 | stratification1                  | stratificationcategoryid1 | stratificationid1 | 
| ========= | ======= | ============ | ============ | ========================================== | ======================= | ======================= | ======================================================= | =============== | =============== | ========== | ============== | ========================== | =================== | ==================== | ===================== | =========== | ===== | ========= | ================================ | ====== | ====== | ============== | ======= | ======= | ========== | =============== | ========== | ======================= | ================================ | ========================= | ================= | 
| 2011      | 2011    | AL           | Alabama      | Behavioral Risk Factor Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of adults aged 18 years and older who are obese |                 | Value           | 32         | 32             |                            |                     | 30.5                 | 33.5                  | 7304        | Total |           |                                  |        |        |                | OWS     | OWS1    | Q036       | VALUE           | 01         | Total                   | Total                            | OVR                       | OVERALL           | 
| 2011      | 2011    | AL           | Alabama      | Behavioral Risk Factor Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of adults aged 18 years and older who are obese |                 | Value           | 32.3       | 32.3           |                            |                     | 29.9                 | 34.7                  | 2581        |       |           |                                  | Male   |        |                | OWS     | OWS1    | Q036       | VALUE           | 01         | Gender                  | Male                             | GEN                       | MALE              | 
| 2011      | 2011    | AL           | Alabama      | Behavioral Risk Factor Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of adults aged 18 years and older who are obese |                 | Value           | 31.8       | 31.8           |                            |                     | 30                   | 33.6                  | 4723        |       |           |                                  | Female |        |                | OWS     | OWS1    | Q036       | VALUE           | 01         | Gender                  | Female                           | GEN                       | FEMALE            | 
| 2011      | 2011    | AL           | Alabama      | Behavioral Risk Factor Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of adults aged 18 years and older who are obese |                 | Value           | 33.6       | 33.6           |                            |                     | 29.9                 | 37.6                  | 1153        |       |           | Less than high school            |        |        |                | OWS     | OWS1    | Q036       | VALUE           | 01         | Education               | Less than high school            | EDU                       | EDUHS             | 
| 2011      | 2011    | AL           | Alabama      | Behavioral Risk Factor Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of adults aged 18 years and older who are obese |                 | Value           | 32.8       | 32.8           |                            |                     | 30.2                 | 35.6                  | 2402        |       |           | High school graduate             |        |        |                | OWS     | OWS1    | Q036       | VALUE           | 01         | Education               | High school graduate             | EDU                       | EDUHSGRAD         | 
| 2011      | 2011    | AL           | Alabama      | Behavioral Risk Factor Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of adults aged 18 years and older who are obese |                 | Value           | 33.8       | 33.8           |                            |                     | 31                   | 36.8                  | 1925        |       |           | Some college or technical school |        |        |                | OWS     | OWS1    | Q036       | VALUE           | 01         | Education               | Some college or technical school | EDU                       | EDUCOTEC          | 
| 2011      | 2011    | AL           | Alabama      | Behavioral Risk Factor Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of adults aged 18 years and older who are obese |                 | Value           | 26.4       | 26.4           |                            |                     | 23.7                 | 29.3                  | 1812        |       |           | College graduate                 |        |        |                | OWS     | OWS1    | Q036       | VALUE           | 01         | Education               | College graduate                 | EDU                       | EDUCOGRAD         | 
| 2011      | 2011    | AL           | Alabama      | Behavioral Risk Factor Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of adults aged 18 years and older who are obese |                 | Value           | 16.3       | 16.3           |                            |                     | 12.6                 | 20.9                  | 356         |       | 18 - 24   |                                  |        |        |                | OWS     | OWS1    | Q036       | VALUE           | 01         | Age (years)             | 18 - 24                          | AGEYR                     | AGEYR1824         | 
| 2011      | 2011    | AL           | Alabama      | Behavioral Risk Factor Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of adults aged 18 years and older who are obese |                 | Value           | 35.2       | 35.2           |                            |                     | 30.7                 | 40                    | 598         |       | 25 - 34   |                                  |        |        |                | OWS     | OWS1    | Q036       | VALUE           | 01         | Age (years)             | 25 - 34                          | AGEYR                     | AGEYR2534         | 
| 2011      | 2011    | AL           | Alabama      | Behavioral Risk Factor Surveillance System | Obesity / Weight Status | Obesity / Weight Status | Percent of adults aged 18 years and older who are obese |                 | Value           | 35.5       | 35.5           |                            |                     | 31.6                 | 39.6                  | 865         |       | 35 - 44   |                                  |        |        |                | OWS     | OWS1    | Q036       | VALUE           | 01         | Age (years)             | 35 - 44                          | AGEYR                     | AGEYR3544         | 
```