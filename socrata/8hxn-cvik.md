# Nutrition, Physical Activity, and Obesity - National Immunization Survey (Breastfeeding)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nutrition-physical-activity-and-obesity-national-immunization-survey-breastfeeding-1553f) |
| Metadata | [Link](https://data.cdc.gov/api/views/8hxn-cvik) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/8hxn-cvik/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/8hxn-cvik/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 8hxn-cvik |
| Name | Nutrition, Physical Activity, and Obesity - National Immunization Survey (Breastfeeding) |
| Attribution | Centers for Disease Control and Prevention (CDC), National Center for Chronic Disease Prevention and Health Promotion, Division of Nutrition, Physical Activity, and Obesity |
| Category | Nutrition, Physical Activity, and Obesity |
| Tags | breastfeeding, breastfed, infants, child, national immunization survey, nis, nutrition, dnpao |
| Created | 2016-07-21T17:51:41Z |
| Publication Date | 2016-12-19T16:54:04Z |

## Description

This dataset includes breastfeeding data from the National Immunization Survey. This data is used for DNPAO's Data, Trends, and Maps database, which provides national and state specific data on obesity, nutrition, physical activity, and breastfeeding.

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
| Yes      | series tag     | povertylevel               | %PovertyLevel              | text      | text        |
| Yes      | series tag     | age_years                  | Age(years)                 | text      | text        |
| Yes      | series tag     | birthorder                 | BirthOrder                 | text      | text        |
| Yes      | series tag     | education                  | Education                  | text      | text        |
| Yes      | series tag     | gender                     | Gender                     | text      | text        |
| Yes      | series tag     | maritalstatus              | MaritalStatus              | text      | text        |
| Yes      | series tag     | metropolitan               | Metropolitan               | text      | text        |
| Yes      | series tag     | race_ethnicity             | Race/Ethnicity             | text      | text        |
| Yes      | series tag     | wicparticipation           | WICParticipation           | text      | text        |
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
series e:8hxn-cvik d:2004-01-01T00:00:00.000Z t:total=Total t:topic="Breastfeeding - Behavior" t:locationabbr=AL t:locationdesc=Alabama t:topicid=BF1 t:stratificationid1=OVERALL t:class=Breastfeeding t:questionid=Q001 t:locationid=01 t:stratificationcategoryid1=OVR t:stratification1=Total t:stratificationcategory1=Total t:question="Percent of breastfed infants who were supplemented with infant formula before 3 months" t:datavaluetypeid=VALUE t:datasource="National Immunization Survey" t:classid=BF m:high_confidence_limit=43.5 m:sample_size=151 m:data_value=33.8 m:low_confidence_limit=25.3

series e:8hxn-cvik d:2005-01-01T00:00:00.000Z t:total=Total t:topic="Breastfeeding - Behavior" t:locationabbr=AL t:locationdesc=Alabama t:topicid=BF1 t:stratificationid1=OVERALL t:class=Breastfeeding t:questionid=Q001 t:locationid=01 t:stratificationcategoryid1=OVR t:stratification1=Total t:stratificationcategory1=Total t:question="Percent of breastfed infants who were supplemented with infant formula before 3 months" t:datavaluetypeid=VALUE t:datasource="National Immunization Survey" t:classid=BF m:high_confidence_limit=49.7 m:sample_size=176 m:data_value=40.8 m:low_confidence_limit=32.5

series e:8hxn-cvik d:2006-01-01T00:00:00.000Z t:total=Total t:topic="Breastfeeding - Behavior" t:locationabbr=AL t:locationdesc=Alabama t:topicid=BF1 t:stratificationid1=OVERALL t:class=Breastfeeding t:questionid=Q001 t:locationid=01 t:stratificationcategoryid1=OVR t:stratification1=Total t:stratificationcategory1=Total t:question="Percent of breastfed infants who were supplemented with infant formula before 3 months" t:datavaluetypeid=VALUE t:datasource="National Immunization Survey" t:classid=BF m:high_confidence_limit=38.3 m:sample_size=212 m:data_value=30.8 m:low_confidence_limit=24.1
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit t:dataTypeName=number

metric m:high_confidence_limit p:float l:High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

entity e:8hxn-cvik l:"Nutrition, Physical Activity, and Obesity - National Immunization Survey (Breastfeeding)" t:attribution="Centers for Disease Control and Prevention (CDC), National Center for Chronic Disease Prevention and Health Promotion, Division of Nutrition, Physical Activity, and Obesity" t:url=https://data.cdc.gov/api/views/8hxn-cvik

property e:8hxn-cvik t:meta.view v:id=8hxn-cvik v:category="Nutrition, Physical Activity, and Obesity" v:attributionLink=http://www.cdc.gov/nccdphp/DNPAO/index.html v:averageRating=0 v:name="Nutrition, Physical Activity, and Obesity - National Immunization Survey (Breastfeeding)" v:attribution="Centers for Disease Control and Prevention (CDC), National Center for Chronic Disease Prevention and Health Promotion, Division of Nutrition, Physical Activity, and Obesity"

property e:8hxn-cvik t:meta.view.license v:name="Public Domain"

property e:8hxn-cvik t:meta.view.owner v:id=cvya-y955 v:screenName="LV Moore" v:displayName="LV Moore"

property e:8hxn-cvik t:meta.view.tableauthor v:id=cvya-y955 v:screenName="LV Moore" v:roleName=publisher v:displayName="LV Moore"

property e:8hxn-cvik t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| yearstart | yearend | locationabbr | locationdesc | datasource                   | class         | topic                    | question                                                                               | data_value_unit | data_value_type | data_value | data_value_alt | data_value_footnote_symbol | data_value_footnote | low_confidence_limit | high_confidence_limit | sample_size | total | povertylevel | age_years | birthorder | education | gender | maritalstatus | metropolitan | race_ethnicity     | wicparticipation | classid | topicid | questionid | datavaluetypeid | locationid | stratificationcategory1 | stratification1    | stratificationcategoryid1 | stratificationid1 | 
| ========= | ======= | ============ | ============ | ============================ | ============= | ======================== | ====================================================================================== | =============== | =============== | ========== | ============== | ========================== | =================== | ==================== | ===================== | =========== | ===== | ============ | ========= | ========== | ========= | ====== | ============= | ============ | ================== | ================ | ======= | ======= | ========== | =============== | ========== | ======================= | ================== | ========================= | ================= | 
| 2004      | 2004    | AL           | Alabama      | National Immunization Survey | Breastfeeding | Breastfeeding - Behavior | Percent of breastfed infants who were supplemented with infant formula before 3 months |                 | Value           | 33.8       | 33.8           |                            |                     | 25.3                 | 43.5                  | 151         | Total |              |           |            |           |        |               |              |                    |                  | BF      | BF1     | Q001       | VALUE           | 01         | Total                   | Total              | OVR                       | OVERALL           | 
| 2005      | 2005    | AL           | Alabama      | National Immunization Survey | Breastfeeding | Breastfeeding - Behavior | Percent of breastfed infants who were supplemented with infant formula before 3 months |                 | Value           | 40.8       | 40.8           |                            |                     | 32.5                 | 49.7                  | 176         | Total |              |           |            |           |        |               |              |                    |                  | BF      | BF1     | Q001       | VALUE           | 01         | Total                   | Total              | OVR                       | OVERALL           | 
| 2006      | 2006    | AL           | Alabama      | National Immunization Survey | Breastfeeding | Breastfeeding - Behavior | Percent of breastfed infants who were supplemented with infant formula before 3 months |                 | Value           | 30.8       | 30.8           |                            |                     | 24.1                 | 38.3                  | 212         | Total |              |           |            |           |        |               |              |                    |                  | BF      | BF1     | Q001       | VALUE           | 01         | Total                   | Total              | OVR                       | OVERALL           | 
| 2007      | 2007    | AL           | Alabama      | National Immunization Survey | Breastfeeding | Breastfeeding - Behavior | Percent of breastfed infants who were supplemented with infant formula before 3 months |                 | Value           | 44.2       | 44.2           |                            |                     | 35.8                 | 53                    | 194         | Total |              |           |            |           |        |               |              |                    |                  | BF      | BF1     | Q001       | VALUE           | 01         | Total                   | Total              | OVR                       | OVERALL           | 
| 2008      | 2008    | AL           | Alabama      | National Immunization Survey | Breastfeeding | Breastfeeding - Behavior | Percent of breastfed infants who were supplemented with infant formula before 3 months |                 | Value           | 35.4       | 35.4           |                            |                     | 27.9                 | 43.7                  | 195         | Total |              |           |            |           |        |               |              |                    |                  | BF      | BF1     | Q001       | VALUE           | 01         | Total                   | Total              | OVR                       | OVERALL           | 
| 2009      | 2009    | AL           | Alabama      | National Immunization Survey | Breastfeeding | Breastfeeding - Behavior | Percent of breastfed infants who were supplemented with infant formula before 3 months |                 | Value           | 30.6       | 30.6           |                            |                     | 23.5                 | 38.8                  | 209         | Total |              |           |            |           |        |               |              |                    |                  | BF      | BF1     | Q001       | VALUE           | 01         | Total                   | Total              | OVR                       | OVERALL           | 
| 2009      | 2011    | AL           | Alabama      | National Immunization Survey | Breastfeeding | Breastfeeding - Behavior | Percent of breastfed infants who were supplemented with infant formula before 3 months |                 | Value           | 34         | 34             |                            |                     | 28.7                 | 39.9                  | 438         | Total |              |           |            |           |        |               |              |                    |                  | BF      | BF1     | Q001       | VALUE           | 01         | Total                   | Total              | OVR                       | OVERALL           | 
| 2009      | 2011    | AL           | Alabama      | National Immunization Survey | Breastfeeding | Breastfeeding - Behavior | Percent of breastfed infants who were supplemented with infant formula before 3 months |                 | Value           | 34.9       | 34.9           |                            |                     | 27.4                 | 43.3                  | 221         |       |              |           |            |           | Male   |               |              |                    |                  | BF      | BF1     | Q001       | VALUE           | 01         | Gender                  | Male               | GEN                       | MALE              | 
| 2009      | 2011    | AL           | Alabama      | National Immunization Survey | Breastfeeding | Breastfeeding - Behavior | Percent of breastfed infants who were supplemented with infant formula before 3 months |                 | Value           | 33.1       | 33.1           |                            |                     | 26                   | 41.1                  | 217         |       |              |           |            |           | Female |               |              |                    |                  | BF      | BF1     | Q001       | VALUE           | 01         | Gender                  | Female             | GEN                       | FEMALE            | 
| 2009      | 2011    | AL           | Alabama      | National Immunization Survey | Breastfeeding | Breastfeeding - Behavior | Percent of breastfed infants who were supplemented with infant formula before 3 months |                 | Value           | 30.9       | 30.9           |                            |                     | 25                   | 37.5                  | 294         |       |              |           |            |           |        |               |              | Non-Hispanic White |                  | BF      | BF1     | Q001       | VALUE           | 01         | Race/Ethnicity          | Non-Hispanic White | RACE                      | RACEWHT           | 
```