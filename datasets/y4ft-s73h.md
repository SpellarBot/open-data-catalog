# Behavioral Risk Factor Surveillance System (BRFSS) Prevalence Data (2010 and prior)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/behavioral-risk-factor-surveillance-system-brfss-prevalence-data-2010-and-prior) |
| Metadata | [Link](https://data.cdc.gov/api/views/y4ft-s73h) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/y4ft-s73h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/y4ft-s73h/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | y4ft-s73h |
| Name | Behavioral Risk Factor Surveillance System (BRFSS) Prevalence Data (2010 and prior) |
| Category | Behavioral Risk Factors |
| Tags | survey, brfss, behavioral, risk, factor, ... |
| Created | 2015-06-04T17:33:13Z |
| Publication Date | 2016-03-11T15:04:09Z |

## Description

1995-2010. BRFSS land line only prevalence data. BRFSS is a continuous, state-based surveillance system that collects information about modifiable risk factors for chronic diseases and other leading causes of death. Data will be updated annually as it becomes available. Detailed information on sampling methodology and quality assurance can be found on the BRFSS website (http://www.cdc.gov/brfss). Methodology: http://www.cdc.gov/brfss/factsheets/pdf/DBS_BRFSS_survey.pdf Glossary: https://chronicdata.cdc.gov/Behavioral-Risk-Factors/Behavioral-Risk-Factor-Surveillance-System-BRFSS-H/iuq5-y9ct

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
series e:y4ft-s73h d:2010-01-01T00:00:00.000Z t:breakoutcategoryid=CAT1 t:questionid=GENHLTH t:question="How is your general health?" t:locationabbr=AL t:break_out=Overall t:locationdesc=Alabama t:topicid=Topic41 t:classid=CLASS08 t:break_out_category=Overall t:response=Excellent t:datasource=BRFSS t:locationid=01 t:breakoutid=BO1 t:topic="Overall Health" t:class="Health Status" t:responseid=RESP056 m:sample_size=996 m:data_value=16.4 m:confidence_limit_low=15 m:confidence_limit_high=17.7

series e:y4ft-s73h d:2010-01-01T00:00:00.000Z t:breakoutcategoryid=CAT1 t:questionid=GENHLTH t:question="How is your general health?" t:locationabbr=AL t:break_out=Overall t:locationdesc=Alabama t:topicid=Topic41 t:classid=CLASS08 t:break_out_category=Overall t:response="Very good" t:datasource=BRFSS t:locationid=01 t:breakoutid=BO1 t:topic="Overall Health" t:class="Health Status" t:responseid=RESP057 m:sample_size=1923 m:data_value=29.2 m:confidence_limit_low=27.6 m:confidence_limit_high=30.8

series e:y4ft-s73h d:2010-01-01T00:00:00.000Z t:breakoutcategoryid=CAT1 t:questionid=GENHLTH t:question="How is your general health?" t:locationabbr=AL t:break_out=Overall t:locationdesc=Alabama t:topicid=Topic41 t:classid=CLASS08 t:break_out_category=Overall t:response=Good t:datasource=BRFSS t:locationid=01 t:breakoutid=BO1 t:topic="Overall Health" t:class="Health Status" t:responseid=RESP058 m:sample_size=2524 m:data_value=33.2 m:confidence_limit_low=31.6 m:confidence_limit_high=34.8
```

## Meta Commands

```ls
metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

metric m:data_value p:float l:Data_value t:dataTypeName=number

metric m:confidence_limit_low p:float l:Confidence_limit_Low t:dataTypeName=number

metric m:confidence_limit_high p:float l:Confidence_limit_High t:dataTypeName=number

entity e:y4ft-s73h l:"Behavioral Risk Factor Surveillance System (BRFSS) Prevalence Data (2010 and prior)" t:url=https://data.cdc.gov/api/views/y4ft-s73h

property e:y4ft-s73h t:meta.view d:2017-09-25T07:22:29.810Z v:averageRating=0 v:name="Behavioral Risk Factor Surveillance System (BRFSS) Prevalence Data (2010 and prior)" v:id=y4ft-s73h v:category="Behavioral Risk Factors"

property e:y4ft-s73h t:meta.view.license d:2017-09-25T07:22:29.810Z v:name="Public Domain"

property e:y4ft-s73h t:meta.view.owner d:2017-09-25T07:22:29.810Z v:displayName=BRFSS v:id=emuu-zcsq v:screenName=BRFSS

property e:y4ft-s73h t:meta.view.tableauthor d:2017-09-25T07:22:29.810Z v:displayName=BRFSS v:roleName=publisher v:id=emuu-zcsq v:screenName=BRFSS

property e:y4ft-s73h t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:22:29.810Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Program_Code=009:020 v:Publisher="Centers for Disease Control and Prevention" v:Bureau_Code=009:20 v:Public_Access_Level="Public Domain"
```

## Top Records

```ls
| year | locationabbr | locationdesc | class         | topic          | question                    | response  | break_out | break_out_category | sample_size | data_value | confidence_limit_low | confidence_limit_high | display_order | data_value_unit | data_value_type  | data_value_footnote_symbol | data_value_footnote | datasource | classid | topicid | locationid | breakoutid | breakoutcategoryid | questionid | responseid | 
| ==== | ============ | ============ | ============= | ============== | =========================== | ========= | ========= | ================== | =========== | ========== | ==================== | ===================== | ============= | =============== | ================ | ========================== | =================== | ========== | ======= | ======= | ========== | ========== | ================== | ========== | ========== | 
| 2010 | AL           | Alabama      | Health Status | Overall Health | How is your general health? | Excellent | Overall   | Overall            | 996         | 16.4       | 15.0                 | 17.7                  | 1             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 01         | BO1        | CAT1               | GENHLTH    | RESP056    | 
| 2010 | AL           | Alabama      | Health Status | Overall Health | How is your general health? | Very good | Overall   | Overall            | 1923        | 29.2       | 27.6                 | 30.8                  | 2             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 01         | BO1        | CAT1               | GENHLTH    | RESP057    | 
| 2010 | AL           | Alabama      | Health Status | Overall Health | How is your general health? | Good      | Overall   | Overall            | 2524        | 33.2       | 31.6                 | 34.8                  | 3             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 01         | BO1        | CAT1               | GENHLTH    | RESP058    | 
| 2010 | AL           | Alabama      | Health Status | Overall Health | How is your general health? | Fair      | Overall   | Overall            | 1415        | 14.0       | 13.0                 | 15.0                  | 4             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 01         | BO1        | CAT1               | GENHLTH    | RESP059    | 
| 2010 | AL           | Alabama      | Health Status | Overall Health | How is your general health? | Poor      | Overall   | Overall            | 787         | 7.2        | 6.5                  | 7.9                   | 5             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 01         | BO1        | CAT1               | GENHLTH    | RESP060    | 
| 2010 | AL           | Alabama      | Health Status | Overall Health | How is your general health? | Excellent | Male      | Gender             | 350         | 17.7       | 15.4                 | 20.1                  | 6             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 01         | SEX1       | CAT2               | GENHLTH    | RESP056    | 
| 2010 | AL           | Alabama      | Health Status | Overall Health | How is your general health? | Excellent | Female    | Gender             | 646         | 15.2       | 13.7                 | 16.6                  | 7             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 01         | SEX2       | CAT2               | GENHLTH    | RESP056    | 
| 2010 | AL           | Alabama      | Health Status | Overall Health | How is your general health? | Very good | Male      | Gender             | 603         | 30.2       | 27.4                 | 32.9                  | 8             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 01         | SEX1       | CAT2               | GENHLTH    | RESP057    | 
| 2010 | AL           | Alabama      | Health Status | Overall Health | How is your general health? | Very good | Female    | Gender             | 1320        | 28.4       | 26.6                 | 30.1                  | 9             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 01         | SEX2       | CAT2               | GENHLTH    | RESP057    | 
| 2010 | AL           | Alabama      | Health Status | Overall Health | How is your general health? | Good      | Male      | Gender             | 804         | 34.1       | 31.4                 | 36.9                  | 10            | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 01         | SEX1       | CAT2               | GENHLTH    | RESP058    | 
```