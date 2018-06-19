# Behavioral Risk Factors: Selected Metropolitan Area Risk Trends (SMART) MMSA Prevalence Data (2010 and Prior)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/behavioral-risk-factors-selected-metropolitan-area-risk-trends-smart-mmsa-prevalence-data--ad5d8) |
| Metadata | [Link](https://data.cdc.gov/api/views/waxm-p5qv) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/waxm-p5qv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/waxm-p5qv/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | waxm-p5qv |
| Name | Behavioral Risk Factors: Selected Metropolitan Area Risk Trends (SMART) MMSA Prevalence Data (2010 and Prior) |
| Category | Behavioral Risk Factors |
| Tags | smart, mmsa, survey, brfss, behavioral, risk, ... |
| Created | 2015-06-04T15:50:01Z |
| Publication Date | 2016-08-19T20:59:34Z |

## Description

2002-2010. BRFSS SMART MMSA Prevalence land line only data. The Selected Metropolitan Area Risk Trends (SMART) project uses the Behavioral Risk Factor Surveillance System (BRFSS) to analyze the data of selected metropolitan statistical areas (MMSAs) with 500 or more respondents. BRFSS data can be used to identify emerging health problems, establish and track health objectives, and develop and evaluate public health policies and programs. BRFSS is a continuous, state-based surveillance system that collects information about modifiable risk factors for chronic diseases and other leading causes of death. Data will be updated annually as it becomes available. Detailed information on sampling methodology and quality assurance can be found on the BRFSS website (http://www.cdc.gov/brfss). Methodology: http://www.cdc.gov/brfss/factsheets/pdf/DBS_BRFSS_survey.pdf Glossary: http://apps.nccd.cdc.gov/BRFSSQuest/index.asp

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | numeric metric | locationabbr               | Locationabbr               | number    | text        |
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
series e:waxm-p5qv d:2010-01-01T00:00:00.000Z t:topic="Overall Health" t:locationdesc="Akron, OH Metropolitan Statistical Area" t:topicid=Topic41 t:class="Health Status" t:break_out=Overall t:questionid=GENHLTH t:response=Excellent t:locationid=10420 t:breakoutid=BO1 t:responseid=RESP056 t:break_out_category=Overall t:question="How is your general health?" t:breakoutcategoryid=CAT1 t:datasource=BRFSS t:classid=CLASS08 m:confidence_limit_low=13.1 m:locationabbr=10420 m:sample_size=118 m:data_value=17.9 m:confidence_limit_high=22.6

series e:waxm-p5qv d:2010-01-01T00:00:00.000Z t:topic="Overall Health" t:locationdesc="Akron, OH Metropolitan Statistical Area" t:topicid=Topic41 t:class="Health Status" t:break_out=Overall t:questionid=GENHLTH t:response="Very good" t:locationid=10420 t:breakoutid=BO1 t:responseid=RESP057 t:break_out_category=Overall t:question="How is your general health?" t:breakoutcategoryid=CAT1 t:datasource=BRFSS t:classid=CLASS08 m:confidence_limit_low=32 m:locationabbr=10420 m:sample_size=272 m:data_value=37.9 m:confidence_limit_high=43.7

series e:waxm-p5qv d:2010-01-01T00:00:00.000Z t:topic="Overall Health" t:locationdesc="Akron, OH Metropolitan Statistical Area" t:topicid=Topic41 t:class="Health Status" t:break_out=Overall t:questionid=GENHLTH t:response=Good t:locationid=10420 t:breakoutid=BO1 t:responseid=RESP058 t:break_out_category=Overall t:question="How is your general health?" t:breakoutcategoryid=CAT1 t:datasource=BRFSS t:classid=CLASS08 m:confidence_limit_low=24.8 m:locationabbr=10420 m:sample_size=259 m:data_value=29.6 m:confidence_limit_high=34.3
```

## Meta Commands

```ls
metric m:locationabbr p:integer l:Locationabbr t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

metric m:data_value p:float l:Data_value t:dataTypeName=number

metric m:confidence_limit_low p:float l:Confidence_limit_Low t:dataTypeName=number

metric m:confidence_limit_high p:double l:Confidence_limit_High t:dataTypeName=number

entity e:waxm-p5qv l:"Behavioral Risk Factors: Selected Metropolitan Area Risk Trends (SMART) MMSA Prevalence Data (2010 and Prior)" t:url=https://data.cdc.gov/api/views/waxm-p5qv

property e:waxm-p5qv t:meta.view v:id=waxm-p5qv v:category="Behavioral Risk Factors" v:averageRating=0 v:name="Behavioral Risk Factors: Selected Metropolitan Area Risk Trends (SMART) MMSA Prevalence Data (2010 and Prior)"

property e:waxm-p5qv t:meta.view.owner v:id=emuu-zcsq v:screenName=BRFSS v:displayName=BRFSS

property e:waxm-p5qv t:meta.view.tableauthor v:id=emuu-zcsq v:screenName=BRFSS v:roleName=publisher v:displayName=BRFSS

property e:waxm-p5qv t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | locationabbr | locationdesc                            | class                       | topic                | question                                                                                                           | response              | break_out | break_out_category | sample_size | data_value | confidence_limit_low | confidence_limit_high | display_order | data_value_unit | data_value_type  | data_value_footnote_symbol | data_value_footnote | datasource | classid | topicid | locationid | breakoutid | breakoutcategoryid | questionid | responseid | 
| ==== | ============ | ======================================= | =========================== | ==================== | ================================================================================================================== | ===================== | ========= | ================== | =========== | ========== | ==================== | ===================== | ============= | =============== | ================ | ========================== | =================== | ========== | ======= | ======= | ========== | ========== | ================== | ========== | ========== | 
| 2010 | 10420        | Akron, OH Metropolitan Statistical Area | Health Status               | Overall Health       | How is your general health?                                                                                        | Excellent             | Overall   | Overall            | 118         | 17.9       | 13.1                 | 22.6                  | 1             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 10420      | BO1        | CAT1               | GENHLTH    | RESP056    | 
| 2010 | 10420        | Akron, OH Metropolitan Statistical Area | Health Status               | Overall Health       | How is your general health?                                                                                        | Very good             | Overall   | Overall            | 272         | 37.9       | 32                   | 43.7                  | 2             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 10420      | BO1        | CAT1               | GENHLTH    | RESP057    | 
| 2010 | 10420        | Akron, OH Metropolitan Statistical Area | Health Status               | Overall Health       | How is your general health?                                                                                        | Good                  | Overall   | Overall            | 259         | 29.6       | 24.8                 | 34.3                  | 3             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 10420      | BO1        | CAT1               | GENHLTH    | RESP058    | 
| 2010 | 10420        | Akron, OH Metropolitan Statistical Area | Health Status               | Overall Health       | How is your general health?                                                                                        | Fair                  | Overall   | Overall            | 115         | 11.1       | 8.3                  | 13.8                  | 4             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 10420      | BO1        | CAT1               | GENHLTH    | RESP059    | 
| 2010 | 10420        | Akron, OH Metropolitan Statistical Area | Health Status               | Overall Health       | How is your general health?                                                                                        | Poor                  | Overall   | Overall            | 44          | 3.5        | 2.1                  | 4.8                   | 5             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 10420      | BO1        | CAT1               | GENHLTH    | RESP060    | 
| 2010 | 10420        | Akron, OH Metropolitan Statistical Area | Health Status               | Fair or Poor Health  | Health Status (variable calculated from one or more BRFSS questions)                                               | Good or Better Health | Overall   | Overall            | 649         | 85.5       | 82.3                 | 88.6                  | 6             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic24 | 10420      | BO1        | CAT1               | _RFHLTH    | RESP061    | 
| 2010 | 10420        | Akron, OH Metropolitan Statistical Area | Health Status               | Fair or Poor Health  | Health Status (variable calculated from one or more BRFSS questions)                                               | Fair or Poor Health   | Overall   | Overall            | 159         | 14.5       | 11.3                 | 17.6                  | 7             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic24 | 10420      | BO1        | CAT1               | _RFHLTH    | RESP062    | 
| 2010 | 10420        | Akron, OH Metropolitan Statistical Area | Health Care Access/Coverage | Health Care Coverage | Do you have any kind of health care coverage?                                                                      | Yes                   | Overall   | Overall            | 724         | 85         | 81                   | 88.9                  | 8             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS07 | Topic29 | 10420      | BO1        | CAT1               | HLTHPLAN   | RESP046    | 
| 2010 | 10420        | Akron, OH Metropolitan Statistical Area | Health Care Access/Coverage | Health Care Coverage | Do you have any kind of health care coverage?                                                                      | No                    | Overall   | Overall            | 86          | 15         | 11                   | 18.9                  | 9             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS07 | Topic29 | 10420      | BO1        | CAT1               | HLTHPLAN   | RESP054    | 
| 2010 | 10420        | Akron, OH Metropolitan Statistical Area | Health Care Access/Coverage | Under 65 Coverage    | Adults aged 18-64 who have any kind of health care coverage (variable calculated from one or more BRFSS questions) | Yes                   | Overall   | Overall            | 447         | 82.2       | 77.4                 | 86.9                  | 10            | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS07 | Topic59 | 10420      | BO1        | CAT1               | _HCVU65    | RESP046    | 
```