# Healthcare Cost and Utilization Project (HCUP) - National Inpatient Sample

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/healthcare-cost-and-utilization-project-hcup-national-inpatient-sample) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/ntny-77fx) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/ntny-77fx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/ntny-77fx/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | ntny-77fx |
| Name | Healthcare Cost and Utilization Project (HCUP) - National Inpatient Sample |
| Attribution | Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Heart Disease and Stroke Prevention (DHDSP), National Cardiovascular Disea... |
| Category | Heart Disease & Stroke Prevention |
| Tags | cardiovascular, stroke, coronary heart disease, myocardial infarction, hospitalizations |
| Created | 2016-06-23T23:26:57Z |
| Publication Date | 2017-06-27T20:27:54Z |

## Description

2001 forward.  The National (Nationwide) Inpatient Sample (NIS) is part of a family of databases and software tools developed for the Healthcare Cost and Utilization Project (HCUP). The NIS is the largest publicly available all-payer inpatient health care database in the United States, yielding national estimates of hospital inpatient stays. Unweighted, it contains data from more than 7 million hospital stays each year. Weighted, it estimates more than 35 million hospitalizations nationally. Indicators from this data source have been computed by personnel in CDC's Division for Heart Disease and Stroke Prevention (DHDSP). This is one of the datasets provided by the National Cardiovascular Disease Surveillance System. The system is designed to integrate multiple indicators from many data sources to provide a comprehensive picture of the public health burden of CVDs and associated risk factors in the United States. The data are organized by indicator, and they include CVDs (e.g., heart failure). The data can be plotted as trends and stratified by age group, sex, and race/ethnicity.

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
series e:ntny-77fx d:2004-01-01T00:00:00.000Z t:indicator="Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US adults (18+); HCUP-NIS" t:priorityarea3=None t:breakoutcategoryid=BOC01 t:priorityarea4=None t:priorityarea1=None t:priorityarea2=None t:locationabbr=US t:break_out=Overall t:locationdesc="United States" t:data_value_typeid=Crude t:topicid=T1 t:indicatorid=HC101 t:break_out_category=Overall t:datasource=HCUP t:locationid=59 t:breakoutid=OVR01 t:topic="Major Cardiovascular Disease" t:category="Cardiovascular Diseases" t:categoryid=C1 m:data_value=17 m:confidence_limit_low=16.5 m:confidence_limit_high=17.5

series e:ntny-77fx d:2004-01-01T00:00:00.000Z t:indicator="Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US adults (18+); HCUP-NIS" t:priorityarea3=None t:breakoutcategoryid=BOC02 t:priorityarea4=None t:priorityarea1=None t:priorityarea2=None t:locationabbr=US t:break_out=Male t:locationdesc="United States" t:data_value_typeid=Crude t:topicid=T1 t:indicatorid=HC101 t:break_out_category=Gender t:datasource=HCUP t:locationid=59 t:breakoutid=GEN01 t:topic="Major Cardiovascular Disease" t:category="Cardiovascular Diseases" t:categoryid=C1 m:data_value=23.1 m:confidence_limit_low=22.4 m:confidence_limit_high=23.9

series e:ntny-77fx d:2004-01-01T00:00:00.000Z t:indicator="Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US adults (18+); HCUP-NIS" t:priorityarea3=None t:breakoutcategoryid=BOC02 t:priorityarea4=None t:priorityarea1=None t:priorityarea2=None t:locationabbr=US t:break_out=Female t:locationdesc="United States" t:data_value_typeid=Crude t:topicid=T1 t:indicatorid=HC101 t:break_out_category=Gender t:datasource=HCUP t:locationid=59 t:breakoutid=GEN02 t:topic="Major Cardiovascular Disease" t:category="Cardiovascular Diseases" t:categoryid=C1 m:data_value=13.2 m:confidence_limit_low=12.8 m:confidence_limit_high=13.6
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value d:"Data value (point estimate)" t:dataTypeName=number

metric m:confidence_limit_low p:double l:Confidence_limit_Low d:"95% confidence interval lower bound" t:dataTypeName=number

metric m:confidence_limit_high p:float l:Confidence_limit_High d:"95% confidence interval upper bound" t:dataTypeName=number

entity e:ntny-77fx l:"Healthcare Cost and Utilization Project (HCUP) - National Inpatient Sample" t:attribution="Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Heart Disease and Stroke Prevention (DHDSP), National Cardiovascular Disease Surveillance System" t:url=https://chronicdata.cdc.gov/api/views/ntny-77fx

property e:ntny-77fx t:meta.view d:2017-09-25T07:25:13.690Z v:averageRating=0 v:name="Healthcare Cost and Utilization Project (HCUP) - National Inpatient Sample" v:attribution="Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Heart Disease and Stroke Prevention (DHDSP), National Cardiovascular Disease Surveillance System" v:attributionLink=http://www.cdc.gov/dhdsp/ncvdss/index.htm v:id=ntny-77fx v:category="Heart Disease & Stroke Prevention"

property e:ntny-77fx t:meta.view.license d:2017-09-25T07:25:13.690Z v:name="Public Domain"

property e:ntny-77fx t:meta.view.owner d:2017-09-25T07:25:13.690Z v:displayName=VHC6@cdc.gov v:id=6thr-55du v:screenName=VHC6@cdc.gov

property e:ntny-77fx t:meta.view.tableauthor d:2017-09-25T07:25:13.690Z v:displayName=VHC6@cdc.gov v:roleName=publisher v:id=6thr-55du v:screenName=VHC6@cdc.gov

property e:ntny-77fx t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:25:13.690Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Program_Code=009:020 v:Publisher="Centers for Disease Control and Prevention" v:Bureau_Code=009:20 v:Public_Access_Level="Public Domain"
```

## Top Records

```ls
| year | locationabbr | locationdesc  | datasource | priorityarea1 | priorityarea2 | priorityarea3 | priorityarea4 | category                | topic                        | indicator                                                                                                         | data_value_type | data_value_unit | data_value | data_value_alt | data_value_footnote_symbol | data_value_footnote | confidence_limit_low | confidence_limit_high | break_out_category | break_out | categoryid | topicid | indicatorid | data_value_typeid | breakoutcategoryid | breakoutid | locationid | 
| ==== | ============ | ============= | ========== | ============= | ============= | ============= | ============= | ======================= | ============================ | ================================================================================================================= | =============== | =============== | ========== | ============== | ========================== | =================== | ==================== | ===================== | ================== | ========= | ========== | ======= | =========== | ================= | ================== | ========== | ========== | 
| 2004 | US           | United States | HCUP       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US adults (18+); HCUP-NIS | Crude           | Percent (%)     | 17         | 17             |                            |                     | 16.5                 | 17.5                  | Overall            | Overall   | C1         | T1      | HC101       | Crude             | BOC01              | OVR01      | 59         | 
| 2004 | US           | United States | HCUP       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US adults (18+); HCUP-NIS | Crude           | Percent (%)     | 23.1       | 23.1           |                            |                     | 22.4                 | 23.9                  | Gender             | Male      | C1         | T1      | HC101       | Crude             | BOC02              | GEN01      | 59         | 
| 2004 | US           | United States | HCUP       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US adults (18+); HCUP-NIS | Crude           | Percent (%)     | 13.2       | 13.2           |                            |                     | 12.8                 | 13.6                  | Gender             | Female    | C1         | T1      | HC101       | Crude             | BOC02              | GEN02      | 59         | 
| 2004 | US           | United States | HCUP       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US adults (18+); HCUP-NIS | Crude           | Percent (%)     | 0.8        | 0.8            |                            |                     | 0.8                  | 0.9                   | Age                | 18-24     | C1         | T1      | HC101       | Crude             | BOC03              | AGE01      | 59         | 
| 2004 | US           | United States | HCUP       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US adults (18+); HCUP-NIS | Crude           | Percent (%)     | 3.9        | 3.9            |                            |                     | 3.8                  | 4.2                   | Age                | 25-44     | C1         | T1      | HC101       | Crude             | BOC03              | AGE04      | 59         | 
| 2004 | US           | United States | HCUP       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US adults (18+); HCUP-NIS | Crude           | Percent (%)     | 19.2       | 19.2           |                            |                     | 18.6                 | 19.8                  | Age                | 45-64     | C1         | T1      | HC101       | Crude             | BOC03              | AGE05      | 59         | 
| 2004 | US           | United States | HCUP       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US adults (18+); HCUP-NIS | Crude           | Percent (%)     | 26.5       | 26.5           |                            |                     | 25.9                 | 27.1                  | Age                | 65+       | C1         | T1      | HC101       | Crude             | BOC03              | AGE06      | 59         | 
| 2004 | US           | United States | HCUP       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US adults (18+); HCUP-NIS | Crude           | Percent (%)     | 21.1       | 21.1           |                            |                     | 20.5                 | 21.6                  | Age                | 35+       | C1         | T1      | HC101       | Crude             | BOC03              | AGE07      | 59         | 
| 2004 | US           | United States | HCUP       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US adults (18+); HCUP-NIS | Crude           | Percent (%)     | 26.5       | 26.5           |                            |                     | 26                   | 27                    | Age                | 75+       | C1         | T1      | HC101       | Crude             | BOC03              | AGE08      | 59         | 
| 2005 | US           | United States | HCUP       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US adults (18+); HCUP-NIS | Crude           | Percent (%)     | 16.5       | 16.5           |                            |                     | 15.9                 | 17                    | Overall            | Overall   | C1         | T1      | HC101       | Crude             | BOC01              | OVR01      | 59         | 
```