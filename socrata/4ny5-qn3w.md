# Behavioral Risk Factor Data: Heart Disease & Stroke Prevention

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/behavioral-risk-factor-data-heart-disease-amp-stroke-prevention-67c1f) |
| Metadata | [Link](https://data.cdc.gov/api/views/4ny5-qn3w) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/4ny5-qn3w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/4ny5-qn3w/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 4ny5-qn3w |
| Name | Behavioral Risk Factor Data: Heart Disease & Stroke Prevention |
| Attribution | Centers for Disease Control and Prevention |
| Category | Heart Disease & Stroke Prevention |
| Tags | brfss, cardiovascular disease, stroke, coronary heart disease, hypertension, risk factors |
| Created | 2016-06-23T21:16:19Z |
| Publication Date | 2017-01-04T21:43:29Z |

## Description

2011 to present.  BRFSS is a continuous, state-based surveillance system that collects information about modifiable risk factors for chronic diseases and other leading causes of death.  Indicators from this data source have been computed by personnel in CDC's Division for Heart Disease and Stroke Prevention (DHDSP). This dataset is one of the datasets provided by National Cardiovascular Disease Surveillance System. The system is designed to integrate multiple indicators from many data sources to provide a comprehensive picture of the public health burden of CVDs and associated risk factors in the United States. The data are organized by location (national, state, county, and selected sites) and indicator, and they include CVDs (e.g., heart failure) and risk factors (e.g., hypertension). The data can be plotted as trends and stratified by age group, sex, and race/ethnicity.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | series tag     | locationabbr               | LocationAbbr               | text      | text        |
| Yes      | series tag     | locationdesc               | LocationDesc               | text      | text        |
| Yes      | series tag     | datasource                 | Datasource                 | text      | text        |
| Yes      | series tag     | priorityarea1              | PriorityArea1              | text      | text        |
| Yes      | series tag     | priorityarea2              | PriorityArea2              | text      | text        |
| Yes      | series tag     | priorityarea3              | PriorityArea3              | text      | text        |
| Yes      | series tag     | priorityarea4              | PriorityArea4              | text      | text        |
| Yes      | series tag     | category                   | Category                   | text      | text        |
| Yes      | series tag     | topic                      | Topic                      | text      | text        |
| Yes      | series tag     | indicator                  | Indicator                  | text      | text        |
| Yes      | series tag     | break_out_category         | Break_Out_Category         | text      | text        |
| Yes      | series tag     | break_out                  | Break_out                  | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | numeric metric | confidence_limit_low       | Confidence_Limit_Low       | number    | number      |
| Yes      | numeric metric | confidence_limit_high      | Confidence_Limit_High      | number    | number      |
| Yes      | series tag     | categoryid                 | CategoryID                 | text      | text        |
| Yes      | series tag     | topicid                    | TopicID                    | text      | text        |
| Yes      | series tag     | indicatorid                | IndicatorID                | text      | text        |
| Yes      | series tag     | breakoutcategoryid         | BreakoutCategoryID         | text      | text        |
| Yes      | series tag     | breakoutid                 | BreakOutID                 | text      | text        |
| Yes      | series tag     | locationid                 | LocationID                 | text      | text        |
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
```

## Meta Commands

```ls
metric m:data_value p:double l:Data_Value d:"Data value (point estimate)" t:dataTypeName=number

metric m:confidence_limit_low p:float l:Confidence_Limit_Low d:"95% confidence interval lower bound" t:dataTypeName=number

metric m:confidence_limit_high p:float l:Confidence_Limit_High d:"95% confidence interval upper bound" t:dataTypeName=number

entity e:4ny5-qn3w l:"Behavioral Risk Factor Data: Heart Disease & Stroke Prevention" t:attribution="Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/4ny5-qn3w

property e:4ny5-qn3w t:meta.view v:id=4ny5-qn3w v:category="Heart Disease & Stroke Prevention" v:attributionLink=http://www.cdc.gov/brfss/ v:averageRating=0 v:name="Behavioral Risk Factor Data: Heart Disease & Stroke Prevention" v:attribution="Centers for Disease Control and Prevention"

property e:4ny5-qn3w t:meta.view.license v:name="Public Domain"

property e:4ny5-qn3w t:meta.view.owner v:id=6thr-55du v:screenName=Angelique v:displayName=Angelique

property e:4ny5-qn3w t:meta.view.tableauthor v:id=6thr-55du v:screenName=Angelique v:roleName=publisher v:displayName=Angelique

property e:4ny5-qn3w t:meta.view.metadata.custom_fields.common_core v:Publisher="CDC INFO" v:Contact_Email=cdcinfo@cdc.gov v:Public_Access_Level="Public Domain" v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:029
```

## Top Records

```ls
| year | locationabbr | locationdesc | datasource | priorityarea1 | priorityarea2 | priorityarea3 | priorityarea4 | category                | topic                  | indicator                                                                      | break_out_category | break_out          | data_value_type | data_value_unit | data_value | data_value_footnote_symbol | data_value_footnote                                                                                        | confidence_limit_low | confidence_limit_high | categoryid | topicid | indicatorid | breakoutcategoryid | breakoutid | locationid | 
| ==== | ============ | ============ | ========== | ============= | ============= | ============= | ============= | ======================= | ====================== | ============================================================================== | ================== | ================== | =============== | =============== | ========== | ========================== | ========================================================================================================== | ==================== | ===================== | ========== | ======= | =========== | ================== | ========== | ========== | 
| 2011 | NV           | Nevada       | BRFSS      | None          | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); BRFSS | Age                | 25-44              | Percentage      | %               |            | ~                          | Statistically unstable estimates not presented [unstable by CDC standards: (standard error/estimate>0.30)] |                      |                       | C1         | T4      | BR001       | BOC03              | AGE04      | 32         | 
| 2011 | NV           | Nevada       | BRFSS      | None          | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); BRFSS | Race               | Non-Hispanic Black | Percentage      | %               |            | ~                          | Statistically unstable estimates not presented [unstable by CDC standards: (standard error/estimate>0.30)] |                      |                       | C1         | T4      | BR001       | BOC04              | RAC02      | 32         | 
| 2011 | NV           | Nevada       | BRFSS      | None          | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); BRFSS | Age                | 18-24              | Percentage      | %               |            | ~                          | Statistically unstable estimates not presented [unstable by CDC standards: (standard error/estimate>0.30)] |                      |                       | C1         | T4      | BR001       | BOC03              | AGE01      | 32         | 
| 2011 | NV           | Nevada       | BRFSS      | None          | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); BRFSS | Race               | Other              | Percentage      | %               |            | ~                          | Statistically unstable estimates not presented [unstable by CDC standards: (standard error/estimate>0.30)] |                      |                       | C1         | T4      | BR001       | BOC04              | RAC07      | 32         | 
| 2011 | NV           | Nevada       | BRFSS      | None          | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); BRFSS | Race               | Hispanic           | Percentage      | %               |            | ~                          | Statistically unstable estimates not presented [unstable by CDC standards: (standard error/estimate>0.30)] |                      |                       | C1         | T4      | BR001       | BOC04              | RAC04      | 32         | 
| 2011 | NY           | New York     | BRFSS      | None          | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); BRFSS | Age                | 25-44              | Percentage      | %               |            | ~                          | Statistically unstable estimates not presented [unstable by CDC standards: (standard error/estimate>0.30)] |                      |                       | C1         | T4      | BR001       | BOC03              | AGE04      | 36         | 
| 2011 | NY           | New York     | BRFSS      | None          | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); BRFSS | Age                | 18-24              | Percentage      | %               |            | ~                          | Statistically unstable estimates not presented [unstable by CDC standards: (standard error/estimate>0.30)] |                      |                       | C1         | T4      | BR001       | BOC03              | AGE01      | 36         | 
| 2011 | OH           | Ohio         | BRFSS      | None          | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); BRFSS | Race               | Hispanic           | Percentage      | %               |            | ~                          | Statistically unstable estimates not presented [unstable by CDC standards: (standard error/estimate>0.30)] |                      |                       | C1         | T4      | BR001       | BOC04              | RAC04      | 39         | 
| 2011 | OH           | Ohio         | BRFSS      | None          | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); BRFSS | Race               | Other              | Percentage      | %               |            | ~                          | Statistically unstable estimates not presented [unstable by CDC standards: (standard error/estimate>0.30)] |                      |                       | C1         | T4      | BR001       | BOC04              | RAC07      | 39         | 
| 2011 | OH           | Ohio         | BRFSS      | None          | None          | None          | None          | Cardiovascular Diseases | Coronary Heart Disease | Prevalence of coronary heart disease among US adults (18+) (Percentage); BRFSS | Age                | 18-24              | Percentage      | %               |            | ~                          | Statistically unstable estimates not presented [unstable by CDC standards: (standard error/estimate>0.30)] |                      |                       | C1         | T4      | BR001       | BOC03              | AGE01      | 39         | 
```