# Nutrition, Physical Activity, and Obesity - American Community Survey

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nutrition-physical-activity-and-obesity-american-community-survey-abe59) |
| Metadata | [Link](https://data.cdc.gov/api/views/8mrp-rmkw) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/8mrp-rmkw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/8mrp-rmkw/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 8mrp-rmkw |
| Name | Nutrition, Physical Activity, and Obesity - American Community Survey |
| Attribution | Centers for Disease Control and Prevention (CDC), National Center for Chronic Disease Prevention and Health Promotion, Division of Nutrition, Physical Activity, and Obesity |
| Category | Nutrition, Physical Activity, and Obesity |
| Tags | physical activity, walk, bike, work, american community survey, acs, dnpao |
| Created | 2016-07-22T10:17:37Z |
| Publication Date | 2016-12-19T13:59:21Z |
| Rows Updated | 2016-12-19T13:58:49Z |

## Description

This dataset includes select data from the U.S. Census Bureau's American Community Survey on the percent of adults who bike or walk to work. This data is used for DNPAO's Data, Trends, and Maps database, which provides national and state specific data on obesity, nutrition, physical activity, and breastfeeding.

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
| Yes      | series tag     | total                      | Total                      | text      | text        |
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
series e:8mrp-rmkw d:2009-01-01T00:00:00.000Z t:total=Total t:topic="Physical Activity - Behavior" t:locationabbr=DE t:locationdesc=Delaware t:topicid=PA1 t:stratificationid1=OVERALL t:class="Physical Activity" t:questionid=Q042 t:locationid=10 t:stratificationcategoryid1=OVR t:stratificationcategory1=Total t:stratification1=Total t:question="Percent of adults in the state who usually biked or walked to work in the last week" t:datavaluetypeid=VALUE t:datasource="American Community Survey" t:classid=PA m:high_confidence_limit=2.9 m:data_value=2.6 m:low_confidence_limit=2.3

series e:8mrp-rmkw d:2009-01-01T00:00:00.000Z t:total=Total t:topic="Physical Activity - Behavior" t:locationabbr=DC t:locationdesc="District of Columbia" t:topicid=PA1 t:stratificationid1=OVERALL t:class="Physical Activity" t:questionid=Q042 t:locationid=11 t:stratificationcategoryid1=OVR t:stratificationcategory1=Total t:stratification1=Total t:question="Percent of adults in the state who usually biked or walked to work in the last week" t:datavaluetypeid=VALUE t:datasource="American Community Survey" t:classid=PA m:high_confidence_limit=15.6 m:data_value=14.8 m:low_confidence_limit=13.9

series e:8mrp-rmkw d:2009-01-01T00:00:00.000Z t:total=Total t:topic="Physical Activity - Behavior" t:locationabbr=FL t:locationdesc=Florida t:topicid=PA1 t:stratificationid1=OVERALL t:class="Physical Activity" t:questionid=Q042 t:locationid=12 t:stratificationcategoryid1=OVR t:stratificationcategory1=Total t:stratification1=Total t:question="Percent of adults in the state who usually biked or walked to work in the last week" t:datavaluetypeid=VALUE t:datasource="American Community Survey" t:classid=PA m:high_confidence_limit=2.3 m:data_value=2.2 m:low_confidence_limit=2.1
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit t:dataTypeName=number

metric m:high_confidence_limit p:float l:High_Confidence_Limit t:dataTypeName=number

entity e:8mrp-rmkw l:"Nutrition, Physical Activity, and Obesity - American Community Survey" t:attribution="Centers for Disease Control and Prevention (CDC), National Center for Chronic Disease Prevention and Health Promotion, Division of Nutrition, Physical Activity, and Obesity" t:url=https://data.cdc.gov/api/views/8mrp-rmkw

property e:8mrp-rmkw t:meta.view v:id=8mrp-rmkw v:category="Nutrition, Physical Activity, and Obesity" v:attributionLink=http://www.cdc.gov/nccdphp/DNPAO/index.html v:averageRating=0 v:name="Nutrition, Physical Activity, and Obesity - American Community Survey" v:attribution="Centers for Disease Control and Prevention (CDC), National Center for Chronic Disease Prevention and Health Promotion, Division of Nutrition, Physical Activity, and Obesity"

property e:8mrp-rmkw t:meta.view.license v:name="Public Domain"

property e:8mrp-rmkw t:meta.view.owner v:id=fjjr-gap9 v:screenName="The Su" v:roleName=administrator v:displayName="The Su"

property e:8mrp-rmkw t:meta.view.tableauthor v:id=fjjr-gap9 v:screenName="The Su" v:roleName=administrator v:displayName="The Su"

property e:8mrp-rmkw t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```