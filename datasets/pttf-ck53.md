# Behavioral Risk Factors - Vision & Eye Health

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/behavioral-risk-factors-vision-amp-eye-health-c8237) |
| Metadata | [Link](https://data.cdc.gov/api/views/pttf-ck53) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/pttf-ck53/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/pttf-ck53/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | pttf-ck53 |
| Name | Behavioral Risk Factors - Vision & Eye Health |
| Attribution | Centers for Disease Control and Prevention's Division of Diabetes Translation |
| Category | Vision & Eye Health |
| Tags | vision impairment, eye diseases, diabetes, state, hypertension, stroke, heart diseases, smoking, physical activity, vhi |
| Created | 2015-06-15T16:14:22Z |
| Publication Date | 2016-02-02T15:37:43Z |

## Description

2005-2014.  In 2013 and subsequently, one question in the core of BRFSS asks about vision: Are you blind or do you have serious difficulty seeing, even when wearing glasses?  From 2005-2011 the BRFSS employed a ten question vision module regarding vision impairment, access and utilization of eye care, and self-reported eye diseases.  The Vision and Eye Health Surveillance System is intended   to provide population estimates of vision loss function, eye diseases, health disparities, as well as barriers and facilitators to access to vision and eye care.  This information can be used for designing, implementing, and evaluating vision and eye health prevention programs.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | text        |
| Yes      | series tag     | locationabbr               | LocationAbbr               | text      | text        |
| Yes      | series tag     | locationdesc               | LocationDesc               | text      | text        |
| Yes      | series tag     | topic                      | Topic                      | text      | text        |
| Yes      | series tag     | question                   | Question                   | text      | text        |
| Yes      | series tag     | datasource                 | DataSource                 | text      | text        |
| Yes      | series tag     | response                   | Response                   | text      | text        |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | numeric metric | low_confidence_limit       | Low_Confidence_limit       | number    | number      |
| Yes      | numeric metric | high_confidence_limit      | High_Confidence_Limit      | number    | number      |
| Yes      | numeric metric | sample_size                | Sample_Size                | number    | number      |
| Yes      | series tag     | break_out                  | Break_Out                  | text      | text        |
| Yes      | series tag     | break_out_category         | Break_Out_Category         | text      | text        |
| Yes      | series tag     | topicid                    | TopicId                    | text      | text        |
| Yes      | series tag     | questionid                 | QuestionId                 | text      | text        |
| Yes      | series tag     | locationid                 | LocationId                 | text      | text        |
| Yes      | series tag     | breakoutid                 | BreakOutId                 | text      | text        |
| Yes      | series tag     | breakoutcategoryid         | BreakOutCategoryId         | text      | text        |
| Yes      | series tag     | responseid                 | ResponseId                 | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_unit,data_value_type,data_value_footnote_symbol,data_value_footnote
```

## Data Commands

```ls
series e:pttf-ck53 d:2005-01-01T00:00:00.000Z t:topic="Visual Impairment" t:locationabbr=IA t:locationdesc=Iowa t:topicid=T01 t:locationid=19 t:breakoutid=BO99 t:break_out_category=Total t:question="Percentage of Adults 50 Years and Older Who Reported Any Distance Visual Impairment" t:break_out=Total t:breakoutcategoryid=BOC99 t:datasource=BRFSS t:questionid=Q41_2005 m:high_confidence_limit=13.6 m:data_value=12.1 m:low_confidence_limit=10.9

series e:pttf-ck53 d:2005-01-01T00:00:00.000Z t:topic="Visual Impairment" t:locationabbr=LA t:locationdesc=Louisiana t:topicid=T01 t:locationid=22 t:breakoutid=BO99 t:break_out_category=Total t:question="Percentage of Adults 50 Years and Older Who Reported Any Distance Visual Impairment" t:break_out=Total t:breakoutcategoryid=BOC99 t:datasource=BRFSS t:questionid=Q41_2005 m:high_confidence_limit=16.2 m:data_value=14 m:low_confidence_limit=12

series e:pttf-ck53 d:2005-01-01T00:00:00.000Z t:topic="Visual Impairment" t:locationabbr=OH t:locationdesc=Ohio t:topicid=T01 t:locationid=39 t:breakoutid=BO99 t:break_out_category=Total t:question="Percentage of Adults 50 Years and Older Who Reported Any Distance Visual Impairment" t:break_out=Total t:breakoutcategoryid=BOC99 t:datasource=BRFSS t:questionid=Q41_2005 m:high_confidence_limit=18.7 m:data_value=16.8 m:low_confidence_limit=15.1
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_limit t:dataTypeName=number

metric m:high_confidence_limit p:float l:High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

entity e:pttf-ck53 l:"Behavioral Risk Factors - Vision & Eye Health" t:attribution="Centers for Disease Control and Prevention's Division of Diabetes Translation" t:url=https://data.cdc.gov/api/views/pttf-ck53

property e:pttf-ck53 t:meta.view v:id=pttf-ck53 v:category="Vision & Eye Health" v:averageRating=0 v:name="Behavioral Risk Factors - Vision & Eye Health" v:attribution="Centers for Disease Control and Prevention's Division of Diabetes Translation"

property e:pttf-ck53 t:meta.view.license v:name="Public Domain"

property e:pttf-ck53 t:meta.view.owner v:id=emuu-zcsq v:screenName=BRFSS v:displayName=BRFSS

property e:pttf-ck53 t:meta.view.tableauthor v:id=emuu-zcsq v:screenName=BRFSS v:roleName=publisher v:displayName=BRFSS

property e:pttf-ck53 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:029
```

## Top Records

```ls
| year | locationabbr | locationdesc | topic             | question                                                                            | datasource | response | data_value_unit | data_value_type  | data_value | data_value_footnote_symbol | data_value_footnote | low_confidence_limit | high_confidence_limit | sample_size | break_out | break_out_category | topicid | questionid | locationid | breakoutid | breakoutcategoryid | responseid | 
| ==== | ============ | ============ | ================= | =================================================================================== | ========== | ======== | =============== | ================ | ========== | ========================== | =================== | ==================== | ===================== | =========== | ========= | ================== | ======= | ========== | ========== | ========== | ================== | ========== | 
| 2005 | IA           | Iowa         | Visual Impairment | Percentage of Adults 50 Years and Older Who Reported Any Distance Visual Impairment | BRFSS      |          | %               | Crude Prevalence | 12.1       |                            |                     | 10.9                 | 13.6                  |             | Total     | Total              | T01     | Q41_2005   | 19         | BO99       | BOC99              |            | 
| 2005 | LA           | Louisiana    | Visual Impairment | Percentage of Adults 50 Years and Older Who Reported Any Distance Visual Impairment | BRFSS      |          | %               | Crude Prevalence | 14         |                            |                     | 12                   | 16.2                  |             | Total     | Total              | T01     | Q41_2005   | 22         | BO99       | BOC99              |            | 
| 2005 | OH           | Ohio         | Visual Impairment | Percentage of Adults 50 Years and Older Who Reported Any Distance Visual Impairment | BRFSS      |          | %               | Crude Prevalence | 16.8       |                            |                     | 15.1                 | 18.7                  |             | Total     | Total              | T01     | Q41_2005   | 39         | BO99       | BOC99              |            | 
| 2005 | TN           | Tennessee    | Visual Impairment | Percentage of Adults 50 Years and Older Who Reported Any Distance Visual Impairment | BRFSS      |          | %               | Crude Prevalence | 14         |                            |                     | 12.4                 | 15.8                  |             | Total     | Total              | T01     | Q41_2005   | 47         | BO99       | BOC99              |            | 
| 2005 | TX           | Texas        | Visual Impairment | Percentage of Adults 50 Years and Older Who Reported Any Distance Visual Impairment | BRFSS      |          | %               | Crude Prevalence | 15.9       |                            |                     | 14.4                 | 17.5                  |             | Total     | Total              | T01     | Q41_2005   | 48         | BO99       | BOC99              |            | 
| 2005 | IA           | Iowa         | Visual Impairment | Percentage of Adults 50 Years and Older Who Reported Any Near Visual Impairment     | BRFSS      |          | %               | Crude Prevalence | 24.2       |                            |                     | 22.5                 | 26.1                  |             | Total     | Total              | T01     | Q42_2005   | 19         | BO99       | BOC99              |            | 
| 2005 | LA           | Louisiana    | Visual Impairment | Percentage of Adults 50 Years and Older Who Reported Any Near Visual Impairment     | BRFSS      |          | %               | Crude Prevalence | 27.3       |                            |                     | 24.7                 | 30.1                  |             | Total     | Total              | T01     | Q42_2005   | 22         | BO99       | BOC99              |            | 
| 2005 | OH           | Ohio         | Visual Impairment | Percentage of Adults 50 Years and Older Who Reported Any Near Visual Impairment     | BRFSS      |          | %               | Crude Prevalence | 31.8       |                            |                     | 29.6                 | 34.1                  |             | Total     | Total              | T01     | Q42_2005   | 39         | BO99       | BOC99              |            | 
| 2005 | TN           | Tennessee    | Visual Impairment | Percentage of Adults 50 Years and Older Who Reported Any Near Visual Impairment     | BRFSS      |          | %               | Crude Prevalence | 26.1       |                            |                     | 24                   | 28.3                  |             | Total     | Total              | T01     | Q42_2005   | 47         | BO99       | BOC99              |            | 
| 2005 | TX           | Texas        | Visual Impairment | Percentage of Adults 50 Years and Older Who Reported Any Near Visual Impairment     | BRFSS      |          | %               | Crude Prevalence | 32.6       |                            |                     | 30.6                 | 34.7                  |             | Total     | Total              | T01     | Q42_2005   | 48         | BO99       | BOC99              |            | 
```