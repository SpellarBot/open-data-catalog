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
| Publication Date | 2017-01-04T21:47:52Z |

## Description

2001 to 2014. The National Health Interview Survey (NHIS) has monitored the health of the nation since 1957. NHIS data on a broad range of health topics are collected through personal household interviews.  Data for this dataset has been computed by personnel in CDC's Division for Heart Disease and Stroke Prevention (DHDSP).  This dataset is one of the datasets provided by National Cardiovascular Disease Surveillance System. The system is designed to integrate multiple indicators from many data sources to provide a comprehensive picture of the public health burden of CVDs and associated risk factors in the United States. The data are organized by location (national, state, county, and selected sites) and indicator, and they include CVDs (e.g., heart failure) and risk factors (e.g., hypertension). The data can be plotted as trends and stratified by age group, sex, and race/ethnicity.

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
| Yes      | series tag     | break_out_category         | Break_Out_Category         | text      | text        |
| Yes      | series tag     | break_out                  | Break_Out                  | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | numeric metric | confidence_limit_low       | Confidence_limit_Low       | number    | number      |
| Yes      | numeric metric | confidence_limit_high      | Confidence_limit_High      | number    | number      |
| Yes      | series tag     | categoryid                 | CategoryId                 | text      | text        |
| Yes      | series tag     | topicid                    | TopicId                    | text      | text        |
| Yes      | series tag     | indicatorid                | IndicatorID                | text      | text        |
| Yes      | series tag     | breakoutcategoryid         | BreakOutCategoryId         | text      | text        |
| Yes      | series tag     | breakoutid                 | BreakOutId                 | text      | text        |
| Yes      | series tag     | locationid                 | LocationID                 | text      | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_type,data_value_unit,data_value_footnote_symbol,data_value_footnote
```

## Data Commands

```ls
series e:fwns-azgu d:2000-01-01T00:00:00.000Z t:topic="Coronary Heart Disease" t:indicator="Prevalence of coronary heart disease among US adults (18+) (Percentage); NHIS" t:locationdesc=Midwest t:locationabbr=MDW t:topicid=T4 t:priorityarea3=None t:priorityarea4=None t:priorityarea1="Million Hearts" t:priorityarea2=None t:break_out="Non-Hispanic White" t:categoryid=C1 t:category="Cardiovascular Diseases" t:locationid=103 t:indicatorid=NS001 t:breakoutid=RAC01 t:break_out_category=Race t:breakoutcategoryid=BOC04 t:datasource=NHIS m:confidence_limit_low=3.3 m:data_value=3.9 m:confidence_limit_high=4.5

series e:fwns-azgu d:2000-01-01T00:00:00.000Z t:topic="Coronary Heart Disease" t:indicator="Prevalence of coronary heart disease among US adults (18+) (Percentage); NHIS" t:locationdesc=Midwest t:locationabbr=MDW t:topicid=T4 t:priorityarea3=None t:priorityarea4=None t:priorityarea1="Million Hearts" t:priorityarea2=None t:break_out=Female t:categoryid=C1 t:category="Cardiovascular Diseases" t:locationid=103 t:indicatorid=NS001 t:breakoutid=GEN02 t:break_out_category=Gender t:breakoutcategoryid=BOC02 t:datasource=NHIS m:confidence_limit_low=2.2 m:data_value=2.7 m:confidence_limit_high=3.4

series e:fwns-azgu d:2000-01-01T00:00:00.000Z t:topic="Coronary Heart Disease" t:indicator="Prevalence of coronary heart disease among US adults (18+) (Percentage); NHIS" t:locationdesc=Midwest t:locationabbr=MDW t:topicid=T4 t:priorityarea3=None t:priorityarea4=None t:priorityarea1="Million Hearts" t:priorityarea2=None t:break_out=Hispanic t:categoryid=C1 t:category="Cardiovascular Diseases" t:locationid=103 t:indicatorid=NS001 t:breakoutid=RAC04 t:break_out_category=Race t:breakoutcategoryid=BOC04 t:datasource=NHIS m:confidence_limit_low=0.5 m:data_value=1.1 m:confidence_limit_high=2.8
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value d:"Data value (point estimate)" t:dataTypeName=number

metric m:confidence_limit_low p:double l:Confidence_limit_Low d:"95% confidence interval lower bound" t:dataTypeName=number

metric m:confidence_limit_high p:float l:Confidence_limit_High d:"95% confidence interval upper bound" t:dataTypeName=number

entity e:fwns-azgu l:"National Health Interview Survey (NHIS) - National Cardiovascular Disease Surveillance Data" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Health Disease and Stroke Prevention (DHDSP), National Cardiovascular Disease Surveillance System" t:url=https://data.cdc.gov/api/views/fwns-azgu

property e:fwns-azgu t:meta.view v:id=fwns-azgu v:category="Heart Disease & Stroke Prevention" v:attributionLink=http://www.cdc.gov/dhdsp/ncvdss/index.htm v:averageRating=0 v:name="National Health Interview Survey (NHIS) - National Cardiovascular Disease Surveillance Data" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Health Disease and Stroke Prevention (DHDSP), National Cardiovascular Disease Surveillance System"

property e:fwns-azgu t:meta.view.license v:name="Public Domain"

property e:fwns-azgu t:meta.view.owner v:id=6thr-55du v:screenName=Angelique v:displayName=Angelique

property e:fwns-azgu t:meta.view.tableauthor v:id=6thr-55du v:screenName=Angelique v:roleName=publisher v:displayName=Angelique

property e:fwns-azgu t:meta.view.metadata.custom_fields.common_core v:Publisher="CDC Info" v:Contact_Email=cdcinfo@cdc.gov v:Public_Access_Level=Public v:Contact_Name="CDC Info" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | locationabbr | locationdesc | datasource | priorityarea1  | priorityarea2 | priorityarea3 | priorityarea4 | category                | topic                  | indicator                                                                     | break_out_category | break_out          | data_value_type | data_value_unit | data_value | data_value_footnote_symbol | data_value_footnote                                                                                         | confidence_limit_low | confidence_limit_high | categoryid | topicid | indicatorid | breakoutcategoryid | breakoutid | locationid | 
| ==== | ============ | ============ | ========== | ============== | ============= | ============= | ============= | ======================= | ====================== | ============================================================================= | ================== | ================== | =============== | =============== | ========== | ========================== | =========================================================================================================== | ==================== | ===================== | ========== | ======= | =========== | ================== | ========== | ========== | 
| 2000 | MDW          | Midwest      | NHIS       | Million Hearts | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); NHIS | Race               | Non-Hispanic White | Percentage      | %               | 3.9        |                            |                                                                                                             | 3.3                  | 4.5                   | C1         | T4      | NS001       | BOC04              | RAC01      | 103        | 
| 2000 | MDW          | Midwest      | NHIS       | Million Hearts | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); NHIS | Gender             | Female             | Percentage      | %               | 2.7        |                            |                                                                                                             | 2.2                  | 3.4                   | C1         | T4      | NS001       | BOC02              | GEN02      | 103        | 
| 2000 | MDW          | Midwest      | NHIS       | Million Hearts | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); NHIS | Race               | Hispanic           | Percentage      | %               | 1.1        |                            |                                                                                                             | 0.5                  | 2.8                   | C1         | T4      | NS001       | BOC04              | RAC04      | 103        | 
| 2000 | MDW          | Midwest      | NHIS       | Million Hearts | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); NHIS | Age                | 45-64              | Percentage      | %               | 4.1        |                            |                                                                                                             | 3.2                  | 5.2                   | C1         | T4      | NS001       | BOC03              | AGE05      | 103        | 
| 2000 | MDW          | Midwest      | NHIS       | Million Hearts | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); NHIS | Overall            | Overall            | Percentage      | %               | 3.8        |                            |                                                                                                             | 3.3                  | 4.4                   | C1         | T4      | NS001       | BOC01              | OVR01      | 103        | 
| 2000 | MDW          | Midwest      | NHIS       | Million Hearts | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); NHIS | Race               | Non-Hispanic Black | Percentage      | %               | 3.1        |                            |                                                                                                             | 2.1                  | 4.5                   | C1         | T4      | NS001       | BOC04              | RAC02      | 103        | 
| 2000 | MDW          | Midwest      | NHIS       | Million Hearts | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); NHIS | Age                | 25-44              | Percentage      | %               | 0.6        |                            |                                                                                                             | 0.3                  | 1.2                   | C1         | T4      | NS001       | BOC03              | AGE04      | 103        | 
| 2000 | MDW          | Midwest      | NHIS       | Million Hearts | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); NHIS | Age                | 65+                | Percentage      | %               | 12.7       |                            |                                                                                                             | 10.9                 | 14.7                  | C1         | T4      | NS001       | BOC03              | AGE06      | 103        | 
| 2000 | MDW          | Midwest      | NHIS       | Million Hearts | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); NHIS | Gender             | Male               | Percentage      | %               | 5.2        |                            |                                                                                                             | 4.3                  | 6.3                   | C1         | T4      | NS001       | BOC02              | GEN01      | 103        | 
| 2000 | MDW          | Midwest      | NHIS       | Million Hearts | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); NHIS | Age                | 18-24              | Percentage      | %               |            | ~                          | Statistically unstable estimates not presented [unstable by NCHS standards: (standard error/estimate>0.30)] |                      |                       | C1         | T4      | NS001       | BOC03              | AGE01      | 103        | 
```