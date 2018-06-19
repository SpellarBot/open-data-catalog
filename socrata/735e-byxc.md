# Nutrition, Physical Activity, and Obesity - Women, Infant, and Child

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nutrition-physical-activity-and-obesity-women-infant-and-child) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/735e-byxc) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/735e-byxc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/735e-byxc/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | 735e-byxc |
| Name | Nutrition, Physical Activity, and Obesity - Women, Infant, and Child |
| Attribution | Centers for Disease Control and Prevention (CDC), National Center for Chronic Disease Prevention and Health Promotion, Division of Nutrition, Physical Activity, and Obesity |
| Category | Nutrition, Physical Activity, and Obesity |
| Tags | wic, wic-pc, overweight, obese, low income, children, obesity, dnpao |
| Created | 2016-07-22T10:34:17Z |
| Publication Date | 2016-12-19T13:19:50Z |

## Description

This dataset includes data on weight status for 2-4 year olds from Women, Infant, and Children Participant and Program Characteristics. This data is used for DNPAO's Data, Trends, and Maps database, which provides national and state specific data on obesity, nutrition, physical activity, and breastfeeding.

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
| Yes      | series tag     | age_months                 | Age(months)                | text      | text        |
| Yes      | series tag     | gender                     | Gender                     | text      | text        |
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
series e:735e-byxc d:2008-01-01T00:00:00.000Z t:total=Total t:topic="Obesity / Weight Status" t:locationabbr=AL t:locationdesc=Alabama t:topicid=OWS1 t:stratificationid1=OVERALL t:class="Obesity / Weight Status" t:questionid=Q040 t:locationid=01 t:stratificationcategoryid1=OVR t:stratification1=Total t:stratificationcategory1=Total t:question="Percent of WIC children aged 2 to 4 years who have an overweight classification" t:datavaluetypeid=VALUE t:datasource="Women, Infants, and Children Participant and Program Characteristics" t:classid=OWS m:high_confidence_limit=15.8 m:sample_size=43287 m:data_value=15.4 m:low_confidence_limit=15.1

series e:735e-byxc d:2008-01-01T00:00:00.000Z t:topic="Obesity / Weight Status" t:locationabbr=AL t:locationdesc=Alabama t:topicid=OWS1 t:stratificationid1=MALE t:class="Obesity / Weight Status" t:questionid=Q040 t:locationid=01 t:stratificationcategoryid1=GEN t:stratification1=Male t:stratificationcategory1=Gender t:gender=Male t:question="Percent of WIC children aged 2 to 4 years who have an overweight classification" t:datavaluetypeid=VALUE t:datasource="Women, Infants, and Children Participant and Program Characteristics" t:classid=OWS m:high_confidence_limit=16 m:sample_size=21912 m:data_value=15.5 m:low_confidence_limit=15

series e:735e-byxc d:2008-01-01T00:00:00.000Z t:topic="Obesity / Weight Status" t:locationabbr=AL t:locationdesc=Alabama t:topicid=OWS1 t:stratificationid1=FEMALE t:class="Obesity / Weight Status" t:questionid=Q040 t:locationid=01 t:stratificationcategoryid1=GEN t:stratification1=Female t:stratificationcategory1=Gender t:gender=Female t:question="Percent of WIC children aged 2 to 4 years who have an overweight classification" t:datavaluetypeid=VALUE t:datasource="Women, Infants, and Children Participant and Program Characteristics" t:classid=OWS m:high_confidence_limit=15.8 m:sample_size=21375 m:data_value=15.3 m:low_confidence_limit=14.9
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit t:dataTypeName=number

metric m:high_confidence_limit p:float l:High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

entity e:735e-byxc l:"Nutrition, Physical Activity, and Obesity - Women, Infant, and Child" t:attribution="Centers for Disease Control and Prevention (CDC), National Center for Chronic Disease Prevention and Health Promotion, Division of Nutrition, Physical Activity, and Obesity" t:url=https://chronicdata.cdc.gov/api/views/735e-byxc

property e:735e-byxc t:meta.view v:id=735e-byxc v:category="Nutrition, Physical Activity, and Obesity" v:attributionLink=http://www.cdc.gov/nccdphp/DNPAO/index.html v:averageRating=0 v:name="Nutrition, Physical Activity, and Obesity - Women, Infant, and Child" v:attribution="Centers for Disease Control and Prevention (CDC), National Center for Chronic Disease Prevention and Health Promotion, Division of Nutrition, Physical Activity, and Obesity"

property e:735e-byxc t:meta.view.license v:name="Public Domain"

property e:735e-byxc t:meta.view.owner v:id=cvya-y955 v:screenName="LV Moore" v:displayName="LV Moore"

property e:735e-byxc t:meta.view.tableauthor v:id=cvya-y955 v:screenName="LV Moore" v:roleName=publisher v:displayName="LV Moore"

property e:735e-byxc t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| yearstart | yearend | locationabbr | locationdesc | datasource                                                           | class                   | topic                   | question                                                                        | data_value_unit | data_value_type | data_value | data_value_alt | data_value_footnote_symbol | data_value_footnote | low_confidence_limit | high_confidence_limit | sample_size | total | age_months | gender | race_ethnicity                | classid | topicid | questionid | datavaluetypeid | locationid | stratificationcategory1 | stratification1               | stratificationcategoryid1 | stratificationid1 | 
| ========= | ======= | ============ | ============ | ==================================================================== | ======================= | ======================= | =============================================================================== | =============== | =============== | ========== | ============== | ========================== | =================== | ==================== | ===================== | =========== | ===== | ========== | ====== | ============================= | ======= | ======= | ========== | =============== | ========== | ======================= | ============================= | ========================= | ================= | 
| 2008      | 2008    | AL           | Alabama      | Women, Infants, and Children Participant and Program Characteristics | Obesity / Weight Status | Obesity / Weight Status | Percent of WIC children aged 2 to 4 years who have an overweight classification |                 | Value           | 15.4       | 15.4           |                            |                     | 15.1                 | 15.8                  | 43287       | Total |            |        |                               | OWS     | OWS1    | Q040       | VALUE           | 01         | Total                   | Total                         | OVR                       | OVERALL           | 
| 2008      | 2008    | AL           | Alabama      | Women, Infants, and Children Participant and Program Characteristics | Obesity / Weight Status | Obesity / Weight Status | Percent of WIC children aged 2 to 4 years who have an overweight classification |                 | Value           | 15.5       | 15.5           |                            |                     | 15                   | 16                    | 21912       |       |            | Male   |                               | OWS     | OWS1    | Q040       | VALUE           | 01         | Gender                  | Male                          | GEN                       | MALE              | 
| 2008      | 2008    | AL           | Alabama      | Women, Infants, and Children Participant and Program Characteristics | Obesity / Weight Status | Obesity / Weight Status | Percent of WIC children aged 2 to 4 years who have an overweight classification |                 | Value           | 15.3       | 15.3           |                            |                     | 14.9                 | 15.8                  | 21375       |       |            | Female |                               | OWS     | OWS1    | Q040       | VALUE           | 01         | Gender                  | Female                        | GEN                       | FEMALE            | 
| 2008      | 2008    | AL           | Alabama      | Women, Infants, and Children Participant and Program Characteristics | Obesity / Weight Status | Obesity / Weight Status | Percent of WIC children aged 2 to 4 years who have an overweight classification |                 | Value           | 15.3       | 15.3           |                            |                     | 14.7                 | 15.8                  | 18219       |       | 24 - 35    |        |                               | OWS     | OWS1    | Q040       | VALUE           | 01         | Age (months)            | 24 - 35                       | AGEMO                     | AGEMO2435         | 
| 2008      | 2008    | AL           | Alabama      | Women, Infants, and Children Participant and Program Characteristics | Obesity / Weight Status | Obesity / Weight Status | Percent of WIC children aged 2 to 4 years who have an overweight classification |                 | Value           | 14.9       | 14.9           |                            |                     | 14.4                 | 15.5                  | 14796       |       | 36 - 47    |        |                               | OWS     | OWS1    | Q040       | VALUE           | 01         | Age (months)            | 36 - 47                       | AGEMO                     | AGEMO3647         | 
| 2008      | 2008    | AL           | Alabama      | Women, Infants, and Children Participant and Program Characteristics | Obesity / Weight Status | Obesity / Weight Status | Percent of WIC children aged 2 to 4 years who have an overweight classification |                 | Value           | 16.4       | 16.4           |                            |                     | 15.6                 | 17.1                  | 10272       |       | 48 - 59    |        |                               | OWS     | OWS1    | Q040       | VALUE           | 01         | Age (months)            | 48 - 59                       | AGEMO                     | AGEMO4859         | 
| 2008      | 2008    | AL           | Alabama      | Women, Infants, and Children Participant and Program Characteristics | Obesity / Weight Status | Obesity / Weight Status | Percent of WIC children aged 2 to 4 years who have an overweight classification |                 | Value           | 15.8       | 15.8           |                            |                     | 15.2                 | 16.3                  | 17833       |       |            |        | Non-Hispanic White            | OWS     | OWS1    | Q040       | VALUE           | 01         | Race/Ethnicity          | Non-Hispanic White            | RACE                      | RACEWHT           | 
| 2008      | 2008    | AL           | Alabama      | Women, Infants, and Children Participant and Program Characteristics | Obesity / Weight Status | Obesity / Weight Status | Percent of WIC children aged 2 to 4 years who have an overweight classification |                 | Value           | 13.9       | 13.9           |                            |                     | 13.4                 | 14.4                  | 19170       |       |            |        | Non-Hispanic Black            | OWS     | OWS1    | Q040       | VALUE           | 01         | Race/Ethnicity          | Non-Hispanic Black            | RACE                      | RACEBLK           | 
| 2008      | 2008    | AL           | Alabama      | Women, Infants, and Children Participant and Program Characteristics | Obesity / Weight Status | Obesity / Weight Status | Percent of WIC children aged 2 to 4 years who have an overweight classification |                 | Value           | 19.3       | 19.3           |                            |                     | 18.3                 | 20.3                  | 5731        |       |            |        | Hispanic                      | OWS     | OWS1    | Q040       | VALUE           | 01         | Race/Ethnicity          | Hispanic                      | RACE                      | RACEHIS           | 
| 2008      | 2008    | AL           | Alabama      | Women, Infants, and Children Participant and Program Characteristics | Obesity / Weight Status | Obesity / Weight Status | Percent of WIC children aged 2 to 4 years who have an overweight classification |                 | Value           | 25         | 25             |                            |                     | 19.3                 | 30.7                  | 228         |       |            |        | American Indian/Alaska Native | OWS     | OWS1    | Q040       | VALUE           | 01         | Race/Ethnicity          | American Indian/Alaska Native | RACE                      | RACENAA           | 
```