# Nutrition, Physical Activity, and Obesity - American Community Survey

## Dataset

* [Dataset URL](https://data.cdc.gov/api/views/8mrp-rmkw/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/nutrition-physical-activity-and-obesity-american-community-survey-abe59)
* [Metadata URL](https://data.cdc.gov/api/views/8mrp-rmkw)
* Id = 8mrp-rmkw
* Name = Nutrition, Physical Activity, and Obesity - American Community Survey
* Attribution = Centers for Disease Control and Prevention (CDC), National Center for Chronic Disease Prevention and Health Promotion, Division of Nutrition, Physical Activity, and Obesity
* [Attribution Link](http://www.cdc.gov/nccdphp/DNPAO/index.html)
* Category = Nutrition, Physical Activity, and Obesity
* Tags = [physical activity, walk, bike, work, american community survey, acs, dnpao]
* Created = 2016-07-22T10:17:37Z
* Publication Date = 2016-12-19T13:59:21Z
* Rows Updated = 2016-12-19T13:58:49Z

## Description

This dataset includes select data from the U.S. Census Bureau's American Community Survey on the percent of adults who bike or walk to work. This data is used for DNPAO's Data, Trends, and Maps database, which provides national and state specific data on obesity, nutrition, physical activity, and breastfeeding.

## Columns

```ls
| Name                       | Field Name                 | Data Type | Render Type | Schema Type    | Included | 
| ========================== | ========================== | ========= | =========== | ============== | ======== | 
| YearStart                  | yearstart                  | number    | number      | time           | Yes      | 
| YearEnd                    | yearend                    | number    | number      |                | No       | 
| LocationAbbr               | locationabbr               | text      | text        | series tag     | Yes      | 
| LocationDesc               | locationdesc               | text      | text        | series tag     | Yes      | 
| Datasource                 | datasource                 | text      | text        | series tag     | Yes      | 
| Class                      | class                      | text      | text        | series tag     | Yes      | 
| Topic                      | topic                      | text      | text        | series tag     | Yes      | 
| Question                   | question                   | text      | text        | series tag     | Yes      | 
| Data_Value_Unit            | data_value_unit            | text      | text        |                | No       | 
| Data_Value_Type            | data_value_type            | text      | text        |                | No       | 
| Data_Value                 | data_value                 | number    | number      | numeric metric | Yes      | 
| Data_Value_Alt             | data_value_alt             | number    | number      |                | No       | 
| Data_Value_Footnote_Symbol | data_value_footnote_symbol | text      | text        |                | No       | 
| Data_Value_Footnote        | data_value_footnote        | text      | text        |                | No       | 
| Low_Confidence_Limit       | low_confidence_limit       | number    | number      | numeric metric | Yes      | 
| High_Confidence_Limit      | high_confidence_limit      | number    | number      | numeric metric | Yes      | 
| Total                      | total                      | text      | text        | series tag     | Yes      | 
| ClassID                    | classid                    | text      | text        | series tag     | Yes      | 
| TopicID                    | topicid                    | text      | text        | series tag     | Yes      | 
| QuestionID                 | questionid                 | text      | text        | series tag     | Yes      | 
| DataValueTypeID            | datavaluetypeid            | text      | text        | series tag     | Yes      | 
| LocationID                 | locationid                 | text      | text        | series tag     | Yes      | 
| StratificationCategory1    | stratificationcategory1    | text      | text        | series tag     | Yes      | 
| Stratification1            | stratification1            | text      | text        | series tag     | Yes      | 
| StratificationCategoryId1  | stratificationcategoryid1  | text      | text        | series tag     | Yes      | 
| StratificationID1          | stratificationid1          | text      | text        | series tag     | Yes      | 
```

## Time Field

```ls
Value = yearstart
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = data_value_footnote,data_value_footnote_symbol,data_value_unit,data_value_alt,data_value_type,yearend
Annotation Fields = 
```

## Data Commands

```ls
series e:8mrp-rmkw d:2009-01-01T00:00:00.000Z t:total=Total t:topic="Physical Activity - Behavior" t:locationabbr=DE t:locationdesc=Delaware t:topicid=PA1 t:stratificationid1=OVERALL t:class="Physical Activity" t:questionid=Q042 t:locationid=10 t:stratificationcategoryid1=OVR t:stratificationcategory1=Total t:stratification1=Total t:question="Percent of adults in the state who usually biked or walked to work in the last week" t:datavaluetypeid=VALUE t:datasource="American Community Survey" t:classid=PA m:high_confidence_limit=2.9 m:data_value=2.6 m:low_confidence_limit=2.3

series e:8mrp-rmkw d:2009-01-01T00:00:00.000Z t:total=Total t:topic="Physical Activity - Behavior" t:locationabbr=DC t:locationdesc="District of Columbia" t:topicid=PA1 t:stratificationid1=OVERALL t:class="Physical Activity" t:questionid=Q042 t:locationid=11 t:stratificationcategoryid1=OVR t:stratificationcategory1=Total t:stratification1=Total t:question="Percent of adults in the state who usually biked or walked to work in the last week" t:datavaluetypeid=VALUE t:datasource="American Community Survey" t:classid=PA m:high_confidence_limit=15.6 m:data_value=14.8 m:low_confidence_limit=13.9

series e:8mrp-rmkw d:2009-01-01T00:00:00.000Z t:total=Total t:topic="Physical Activity - Behavior" t:locationabbr=FL t:locationdesc=Florida t:topicid=PA1 t:stratificationid1=OVERALL t:class="Physical Activity" t:questionid=Q042 t:locationid=12 t:stratificationcategoryid1=OVR t:stratificationcategory1=Total t:stratification1=Total t:question="Percent of adults in the state who usually biked or walked to work in the last week" t:datavaluetypeid=VALUE t:datasource="American Community Survey" t:classid=PA m:high_confidence_limit=2.3 m:data_value=2.2 m:low_confidence_limit=2.1
```

## Meta Commands

```ls
metric m:data_value l:Data_Value t:dataTypeName=number

metric m:low_confidence_limit l:Low_Confidence_Limit t:dataTypeName=number

metric m:high_confidence_limit l:High_Confidence_Limit t:dataTypeName=number

entity e:8mrp-rmkw l:"Nutrition, Physical Activity, and Obesity - American Community Survey" t:attribution="Centers for Disease Control and Prevention (CDC), National Center for Chronic Disease Prevention and Health Promotion, Division of Nutrition, Physical Activity, and Obesity" t:url=https://data.cdc.gov/api/views/8mrp-rmkw

property e:8mrp-rmkw t:meta.view d:2017-03-07T16:50:54.184Z v:id=8mrp-rmkw v:category="Nutrition, Physical Activity, and Obesity" v:attributionLink=http://www.cdc.gov/nccdphp/DNPAO/index.html v:averageRating=0 v:name="Nutrition, Physical Activity, and Obesity - American Community Survey" v:attribution="Centers for Disease Control and Prevention (CDC), National Center for Chronic Disease Prevention and Health Promotion, Division of Nutrition, Physical Activity, and Obesity"

property e:8mrp-rmkw t:meta.view.license d:2017-03-07T16:50:54.184Z v:name="Public Domain"

property e:8mrp-rmkw t:meta.view.owner d:2017-03-07T16:50:54.184Z v:id=fjjr-gap9 v:screenName="The Su" v:roleName=administrator v:displayName="The Su"

property e:8mrp-rmkw t:meta.view.tableauthor d:2017-03-07T16:50:54.184Z v:id=fjjr-gap9 v:screenName="The Su" v:roleName=administrator v:displayName="The Su"

property e:8mrp-rmkw t:meta.view.metadata.custom_fields.common_core d:2017-03-07T16:50:54.184Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```