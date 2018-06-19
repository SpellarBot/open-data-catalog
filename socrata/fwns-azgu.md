# National Health Interview Survey (NHIS) - National Cardiovascular Disease Surveillance Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/national-health-interview-survey-nhis-national-cardiovascular-disease-surveillance-data-55805) |
| Metadata | [Link](https://data.cdc.gov/api/views/fwns-azgu) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/fwns-azgu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/fwns-azgu/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | fwns-azgu |
| Name | National Health Interview Survey (NHIS) - National Cardiovascular Disease Surveillance Data |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Health Disease and Stroke Prevention (DHDSP), National Cardiovascular Di... |
| Category | Heart Disease & Stroke Prevention |
| Tags | cardiovascular disease, stroke, coronary heart disease, hypertension, risk factors |
| Created | 2016-06-24T14:17:25Z |
| Publication Date | 2017-06-27T20:27:17Z |

## Description

2001 forward. The National Health Interview Survey (NHIS) has monitored the health of the nation since 1957. NHIS data on a broad range of health topics are collected through personal household interviews.  Indicators for this dataset has been computed by personnel in CDC's Division for Heart Disease and Stroke Prevention (DHDSP).  This is one of the datasets provided by the National Cardiovascular Disease Surveillance System. The system is designed to integrate multiple indicators from many data sources to provide a comprehensive picture of the public health burden of CVDs and associated risk factors in the United States. The data are organized by location (region) and indicator, and they include CVDs (e.g., heart failure) and risk factors (e.g., hypertension). The data can be plotted as trends and stratified by age group, sex, and race/ethnicity.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | series tag     | locationabbr               | LocationAbbr               | text      | text        |
| Yes      | series tag     | locationdesc               | LocationDesc               | text      | text        |
| Yes      | series tag     | datasource                 | DataSource                 | text      | text        |
| Yes      | series tag     | priorityarea1              | PriorityArea1              | text      | text        |
| Yes      | series tag     | priorityarea2              | PriorityArea2              | text      | text        |
| Yes      | series tag     | priorityarea3              | PriorityArea3              | text      | text        |
| Yes      | series tag     | priorityarea4              | PriorityArea4              | text      | text        |
| Yes      | series tag     | category                   | Category                   | text      | text        |
| Yes      | series tag     | topic                      | Topic                      | text      | text        |
| Yes      | series tag     | indicator                  | Indicator                  | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| No       |                | data_value_alt             | Data_Value_Alt             | number    | number      |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | numeric metric | confidence_limit_low       | Confidence_limit_Low       | number    | number      |
| Yes      | numeric metric | confidence_limit_high      | Confidence_limit_High      | number    | number      |
| Yes      | series tag     | break_out_category         | Break_Out_Category         | text      | text        |
| Yes      | series tag     | break_out                  | Break_Out                  | text      | text        |
| Yes      | series tag     | categoryid                 | CategoryId                 | text      | text        |
| Yes      | series tag     | topicid                    | TopicId                    | text      | text        |
| Yes      | series tag     | indicatorid                | IndicatorID                | text      | text        |
| Yes      | series tag     | data_value_typeid          | Data_Value_TypeID          | text      | text        |
| Yes      | series tag     | breakoutcategoryid         | BreakOutCategoryId         | text      | text        |
| Yes      | series tag     | breakoutid                 | BreakOutId                 | text      | text        |
| Yes      | series tag     | locationid                 | LocationID                 | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_type,data_value_unit,data_value_alt,data_value_footnote_symbol,data_value_footnote
```

## Data Commands

```ls
series e:fwns-azgu d:2000-01-01T00:00:00.000Z t:indicator="Prevalence of major cardiovascular disease among US adults (18+); NHIS" t:priorityarea3=None t:breakoutcategoryid=BOC01 t:priorityarea4=None t:priorityarea1=None t:priorityarea2=None t:locationabbr=US t:break_out=Overall t:locationdesc="United States" t:data_value_typeid=AgeStdz t:topicid=T1 t:indicatorid=NS001 t:break_out_category=Overall t:datasource=NHIS t:locationid=59 t:breakoutid=OVR01 t:topic="Major Cardiovascular Disease" t:category="Cardiovascular Diseases" t:categoryid=C1 m:data_value=7.1 m:confidence_limit_low=6.8 m:confidence_limit_high=7.4

series e:fwns-azgu d:2000-01-01T00:00:00.000Z t:indicator="Prevalence of major cardiovascular disease among US adults (18+); NHIS" t:priorityarea3=None t:breakoutcategoryid=BOC01 t:priorityarea4=None t:priorityarea1=None t:priorityarea2=None t:locationabbr=US t:break_out=Overall t:locationdesc="United States" t:data_value_typeid=Crude t:topicid=T1 t:indicatorid=NS001 t:break_out_category=Overall t:datasource=NHIS t:locationid=59 t:breakoutid=OVR01 t:topic="Major Cardiovascular Disease" t:category="Cardiovascular Diseases" t:categoryid=C1 m:data_value=6.9 m:confidence_limit_low=6.6 m:confidence_limit_high=7.2

series e:fwns-azgu d:2000-01-01T00:00:00.000Z t:indicator="Prevalence of major cardiovascular disease among US adults (18+); NHIS" t:priorityarea3=None t:breakoutcategoryid=BOC02 t:priorityarea4=None t:priorityarea1=None t:priorityarea2=None t:locationabbr=US t:break_out=Male t:locationdesc="United States" t:data_value_typeid=Crude t:topicid=T1 t:indicatorid=NS001 t:break_out_category=Gender t:datasource=NHIS t:locationid=59 t:breakoutid=GEN01 t:topic="Major Cardiovascular Disease" t:category="Cardiovascular Diseases" t:categoryid=C1 m:data_value=7.9 m:confidence_limit_low=7.5 m:confidence_limit_high=8.5
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value d:"Data value (point estimate)" t:dataTypeName=number

metric m:confidence_limit_low p:float l:Confidence_limit_Low d:"95% confidence interval lower bound" t:dataTypeName=number

metric m:confidence_limit_high p:float l:Confidence_limit_High d:"95% confidence interval upper bound" t:dataTypeName=number

entity e:fwns-azgu l:"National Health Interview Survey (NHIS) - National Cardiovascular Disease Surveillance Data" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Health Disease and Stroke Prevention (DHDSP), National Cardiovascular Disease Surveillance System" t:url=https://data.cdc.gov/api/views/fwns-azgu

property e:fwns-azgu t:meta.view d:2017-09-25T07:22:29.527Z v:averageRating=0 v:name="National Health Interview Survey (NHIS) - National Cardiovascular Disease Surveillance Data" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Health Disease and Stroke Prevention (DHDSP), National Cardiovascular Disease Surveillance System" v:attributionLink=http://www.cdc.gov/dhdsp/ncvdss/index.htm v:id=fwns-azgu v:category="Heart Disease & Stroke Prevention"

property e:fwns-azgu t:meta.view.license d:2017-09-25T07:22:29.527Z v:name="Public Domain"

property e:fwns-azgu t:meta.view.owner d:2017-09-25T07:22:29.527Z v:displayName=VHC6@cdc.gov v:id=6thr-55du v:screenName=VHC6@cdc.gov

property e:fwns-azgu t:meta.view.tableauthor d:2017-09-25T07:22:29.527Z v:displayName=VHC6@cdc.gov v:roleName=publisher v:id=6thr-55du v:screenName=VHC6@cdc.gov

property e:fwns-azgu t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:22:29.527Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC Info" v:Program_Code=009:020 v:Publisher="Centers for Disease Control and Prevention" v:Bureau_Code=009:20 v:Public_Access_Level="Public Domain"
```

## Top Records

```ls
| year | locationabbr | locationdesc  | datasource | priorityarea1 | priorityarea2 | priorityarea3 | priorityarea4 | category                | topic                        | indicator                                                              | data_value_type  | data_value_unit | data_value | data_value_alt | data_value_footnote_symbol | data_value_footnote                                                                                         | confidence_limit_low | confidence_limit_high | break_out_category | break_out | categoryid | topicid | indicatorid | data_value_typeid | breakoutcategoryid | breakoutid | locationid | 
| ==== | ============ | ============= | ========== | ============= | ============= | ============= | ============= | ======================= | ============================ | ====================================================================== | ================ | =============== | ========== | ============== | ========================== | =========================================================================================================== | ==================== | ===================== | ================== | ========= | ========== | ======= | =========== | ================= | ================== | ========== | ========== | 
| 2000 | US           | United States | NHIS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease among US adults (18+); NHIS | Age-Standardized | Percent (%)     | 7.1        | 7.1            |                            |                                                                                                             | 6.8                  | 7.4                   | Overall            | Overall   | C1         | T1      | NS001       | AgeStdz           | BOC01              | OVR01      | 59         | 
| 2000 | US           | United States | NHIS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease among US adults (18+); NHIS | Crude            | Percent (%)     | 6.9        | 6.9            |                            |                                                                                                             | 6.6                  | 7.2                   | Overall            | Overall   | C1         | T1      | NS001       | Crude             | BOC01              | OVR01      | 59         | 
| 2000 | US           | United States | NHIS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease among US adults (18+); NHIS | Crude            | Percent (%)     | 7.9        | 7.9            |                            |                                                                                                             | 7.5                  | 8.5                   | Gender             | Male      | C1         | T1      | NS001       | Crude             | BOC02              | GEN01      | 59         | 
| 2000 | US           | United States | NHIS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease among US adults (18+); NHIS | Age-Standardized | Percent (%)     | 8.6        | 8.6            |                            |                                                                                                             | 8.1                  | 9                     | Gender             | Male      | C1         | T1      | NS001       | AgeStdz           | BOC02              | GEN01      | 59         | 
| 2000 | US           | United States | NHIS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease among US adults (18+); NHIS | Age-Standardized | Percent (%)     | 5.8        | 5.8            |                            |                                                                                                             | 5.5                  | 6.2                   | Gender             | Female    | C1         | T1      | NS001       | AgeStdz           | BOC02              | GEN02      | 59         | 
| 2000 | US           | United States | NHIS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease among US adults (18+); NHIS | Crude            | Percent (%)     | 5.9        | 5.9            |                            |                                                                                                             | 5.6                  | 6.3                   | Gender             | Female    | C1         | T1      | NS001       | Crude             | BOC02              | GEN02      | 59         | 
| 2000 | US           | United States | NHIS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease among US adults (18+); NHIS | Crude            | Percent (%)     |            | -2             | ~                          | Statistically unstable estimates not presented [unstable by NCHS standards: (standard error/estimate>0.30)] |                      |                       | Age                | 18-24     | C1         | T1      | NS001       | Crude             | BOC03              | AGE01      | 59         | 
| 2000 | US           | United States | NHIS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease among US adults (18+); NHIS | Crude            | Percent (%)     | 1.2        | 1.2            |                            |                                                                                                             | 1                    | 1.5                   | Age                | 25-44     | C1         | T1      | NS001       | Crude             | BOC03              | AGE04      | 59         | 
| 2000 | US           | United States | NHIS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease among US adults (18+); NHIS | Crude            | Percent (%)     | 8          | 8              |                            |                                                                                                             | 7.4                  | 8.7                   | Age                | 45-64     | C1         | T1      | NS001       | Crude             | BOC03              | AGE05      | 59         | 
| 2000 | US           | United States | NHIS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease among US adults (18+); NHIS | Crude            | Percent (%)     | 24.5       | 24.5           |                            |                                                                                                             | 23.3                 | 25.6                  | Age                | 65+       | C1         | T1      | NS001       | Crude             | BOC03              | AGE06      | 59         | 
```