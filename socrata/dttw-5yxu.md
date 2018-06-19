# Behavioral Risk Factor Surveillance System (BRFSS) Prevalence Data (2011 to present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/behavioral-risk-factor-surveillance-system-brfss-prevalence-data-2011-to-present-3dcd9) |
| Metadata | [Link](https://data.cdc.gov/api/views/dttw-5yxu) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/dttw-5yxu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/dttw-5yxu/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | dttw-5yxu |
| Name | Behavioral Risk Factor Surveillance System (BRFSS) Prevalence Data (2011 to present) |
| Category | Behavioral Risk Factors |
| Tags | survey, brfss, behavioral, risk, factor, ... |
| Created | 2015-06-04T13:43:05Z |
| Publication Date | 2016-12-23T17:51:01Z |

## Description

2011 to present. BRFSS combined land line and cell phone prevalence data. BRFSS is a continuous, state-based surveillance system that collects information about modifiable risk factors for chronic diseases and other leading causes of death. Data will be updated annually as it becomes available. Detailed information on sampling methodology and quality assurance can be found on the BRFSS website (http://www.cdc.gov/brfss). Methodology: http://www.cdc.gov/brfss/factsheets/pdf/DBS_BRFSS_survey.pdf Glossary: http://apps.nccd.cdc.gov/BRFSSQuest/index.asp

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | series tag     | locationabbr               | Locationabbr               | text      | text        |
| Yes      | series tag     | locationdesc               | Locationdesc               | text      | text        |
| Yes      | series tag     | class                      | Class                      | text      | text        |
| Yes      | series tag     | topic                      | Topic                      | text      | text        |
| Yes      | series tag     | question                   | Question                   | text      | text        |
| Yes      | series tag     | response                   | Response                   | text      | text        |
| Yes      | series tag     | break_out                  | Break_Out                  | text      | text        |
| Yes      | series tag     | break_out_category         | Break_Out_Category         | text      | text        |
| Yes      | numeric metric | sample_size                | Sample_Size                | number    | number      |
| Yes      | numeric metric | data_value                 | Data_value                 | number    | number      |
| Yes      | numeric metric | confidence_limit_low       | Confidence_limit_Low       | number    | number      |
| Yes      | numeric metric | confidence_limit_high      | Confidence_limit_High      | number    | number      |
| No       |                | display_order              | Display_order              | number    | number      |
| No       |                | data_value_unit            | Data_value_unit            | text      | text        |
| No       |                | data_value_type            | Data_value_type            | text      | text        |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | series tag     | datasource                 | DataSource                 | text      | text        |
| Yes      | series tag     | classid                    | ClassId                    | text      | text        |
| Yes      | series tag     | topicid                    | TopicId                    | text      | text        |
| Yes      | series tag     | locationid                 | LocationID                 | text      | text        |
| Yes      | series tag     | breakoutid                 | BreakoutID                 | text      | text        |
| Yes      | series tag     | breakoutcategoryid         | BreakOutCategoryID         | text      | text        |
| Yes      | series tag     | questionid                 | QuestionID                 | text      | text        |
| Yes      | series tag     | responseid                 | ResponseID                 | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = display_order,data_value_unit,data_value_type,data_value_footnote_symbol,data_value_footnote
```

## Data Commands

```ls
series e:dttw-5yxu d:2015-01-01T00:00:00.000Z t:topic="Alcohol Consumption" t:locationabbr=AL t:locationdesc=Alabama t:topicid=Topic03 t:class="Alcohol Consumption" t:break_out=18-24 t:questionid=DRNKANY5 t:response=Yes t:locationid=01 t:breakoutid=AGE01 t:responseid=RESP046 t:break_out_category="Age Group" t:question="Adults who have had at least one drink of alcohol within the past 30 days" t:breakoutcategoryid=CAT3 t:datasource=BRFSS t:classid=CLASS01 m:confidence_limit_low=39.6 m:sample_size=210 m:data_value=45.3 m:confidence_limit_high=50.9

series e:dttw-5yxu d:2015-01-01T00:00:00.000Z t:topic="Alcohol Consumption" t:locationabbr=AL t:locationdesc=Alabama t:topicid=Topic03 t:class="Alcohol Consumption" t:break_out=18-24 t:questionid=DRNKANY5 t:response=No t:locationid=01 t:breakoutid=AGE01 t:responseid=RESP054 t:break_out_category="Age Group" t:question="Adults who have had at least one drink of alcohol within the past 30 days" t:breakoutcategoryid=CAT3 t:datasource=BRFSS t:classid=CLASS01 m:confidence_limit_low=49.1 m:sample_size=253 m:data_value=54.7 m:confidence_limit_high=60.4

series e:dttw-5yxu d:2015-01-01T00:00:00.000Z t:topic="Alcohol Consumption" t:locationabbr=AL t:locationdesc=Alabama t:topicid=Topic03 t:class="Alcohol Consumption" t:break_out=25-34 t:questionid=DRNKANY5 t:response=Yes t:locationid=01 t:breakoutid=AGE02 t:responseid=RESP046 t:break_out_category="Age Group" t:question="Adults who have had at least one drink of alcohol within the past 30 days" t:breakoutcategoryid=CAT3 t:datasource=BRFSS t:classid=CLASS01 m:confidence_limit_low=49.1 m:sample_size=389 m:data_value=53.7 m:confidence_limit_high=58.4
```

## Meta Commands

```ls
metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

metric m:data_value p:float l:Data_value t:dataTypeName=number

metric m:confidence_limit_low p:float l:Confidence_limit_Low t:dataTypeName=number

metric m:confidence_limit_high p:float l:Confidence_limit_High t:dataTypeName=number

entity e:dttw-5yxu l:"Behavioral Risk Factor Surveillance System (BRFSS) Prevalence Data (2011 to present)" t:url=https://data.cdc.gov/api/views/dttw-5yxu

property e:dttw-5yxu t:meta.view v:id=dttw-5yxu v:category="Behavioral Risk Factors" v:averageRating=0 v:name="Behavioral Risk Factor Surveillance System (BRFSS) Prevalence Data (2011 to present)"

property e:dttw-5yxu t:meta.view.owner v:id=emuu-zcsq v:screenName=BRFSS v:displayName=BRFSS

property e:dttw-5yxu t:meta.view.tableauthor v:id=emuu-zcsq v:screenName=BRFSS v:roleName=publisher v:displayName=BRFSS

property e:dttw-5yxu t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | locationabbr | locationdesc | class               | topic               | question                                                                  | response | break_out | break_out_category | sample_size | data_value | confidence_limit_low | confidence_limit_high | display_order | data_value_unit | data_value_type  | data_value_footnote_symbol | data_value_footnote | datasource | classid | topicid | locationid | breakoutid | breakoutcategoryid | questionid | responseid | 
| ==== | ============ | ============ | =================== | =================== | ========================================================================= | ======== | ========= | ================== | =========== | ========== | ==================== | ===================== | ============= | =============== | ================ | ========================== | =================== | ========== | ======= | ======= | ========== | ========== | ================== | ========== | ========== | 
| 2015 | AL           | Alabama      | Alcohol Consumption | Alcohol Consumption | Adults who have had at least one drink of alcohol within the past 30 days | Yes      | 18-24     | Age Group          | 210         | 45.3       | 39.6                 | 50.9                  | 1             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS01 | Topic03 | 01         | AGE01      | CAT3               | DRNKANY5   | RESP046    | 
| 2015 | AL           | Alabama      | Alcohol Consumption | Alcohol Consumption | Adults who have had at least one drink of alcohol within the past 30 days | No       | 18-24     | Age Group          | 253         | 54.7       | 49.1                 | 60.4                  | 27            | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS01 | Topic03 | 01         | AGE01      | CAT3               | DRNKANY5   | RESP054    | 
| 2015 | AL           | Alabama      | Alcohol Consumption | Alcohol Consumption | Adults who have had at least one drink of alcohol within the past 30 days | Yes      | 25-34     | Age Group          | 389         | 53.7       | 49.1                 | 58.4                  | 2             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS01 | Topic03 | 01         | AGE02      | CAT3               | DRNKANY5   | RESP046    | 
| 2015 | AL           | Alabama      | Alcohol Consumption | Alcohol Consumption | Adults who have had at least one drink of alcohol within the past 30 days | No       | 25-34     | Age Group          | 330         | 46.3       | 41.6                 | 50.9                  | 28            | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS01 | Topic03 | 01         | AGE02      | CAT3               | DRNKANY5   | RESP054    | 
| 2015 | AL           | Alabama      | Alcohol Consumption | Alcohol Consumption | Adults who have had at least one drink of alcohol within the past 30 days | Yes      | 35-44     | Age Group          | 404         | 46.4       | 42.1                 | 50.8                  | 3             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS01 | Topic03 | 01         | AGE03      | CAT3               | DRNKANY5   | RESP046    | 
| 2015 | AL           | Alabama      | Alcohol Consumption | Alcohol Consumption | Adults who have had at least one drink of alcohol within the past 30 days | No       | 35-44     | Age Group          | 452         | 53.6       | 49.2                 | 57.9                  | 29            | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS01 | Topic03 | 01         | AGE03      | CAT3               | DRNKANY5   | RESP054    | 
| 2015 | AL           | Alabama      | Alcohol Consumption | Alcohol Consumption | Adults who have had at least one drink of alcohol within the past 30 days | Yes      | 45-54     | Age Group          | 549         | 43.5       | 40.1                 | 46.8                  | 4             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS01 | Topic03 | 01         | AGE04      | CAT3               | DRNKANY5   | RESP046    | 
| 2015 | AL           | Alabama      | Alcohol Consumption | Alcohol Consumption | Adults who have had at least one drink of alcohol within the past 30 days | No       | 45-54     | Age Group          | 734         | 56.5       | 53.2                 | 59.9                  | 30            | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS01 | Topic03 | 01         | AGE04      | CAT3               | DRNKANY5   | RESP054    | 
| 2015 | AL           | Alabama      | Alcohol Consumption | Alcohol Consumption | Adults who have had at least one drink of alcohol within the past 30 days | Yes      | 55-64     | Age Group          | 580         | 36.3       | 33.2                 | 39.4                  | 5             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS01 | Topic03 | 01         | AGE05      | CAT3               | DRNKANY5   | RESP046    | 
| 2015 | AL           | Alabama      | Alcohol Consumption | Alcohol Consumption | Adults who have had at least one drink of alcohol within the past 30 days | No       | 55-64     | Age Group          | 1147        | 63.7       | 60.6                 | 66.8                  | 31            | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS01 | Topic03 | 01         | AGE05      | CAT3               | DRNKANY5   | RESP054    | 
```