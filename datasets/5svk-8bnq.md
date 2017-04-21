# National Health and Nutrition Examination Survey (NHANES)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/national-health-and-nutrition-examination-survey-nhanes-ddd8a) |
| Metadata | [Link](https://data.cdc.gov/api/views/5svk-8bnq) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/5svk-8bnq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/5svk-8bnq/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 5svk-8bnq |
| Name | National Health and Nutrition Examination Survey (NHANES) |
| Attribution | Centers for Disease Control and Prevention National Center for Health Statistics |
| Category | Heart Disease & Stroke Prevention |
| Tags | cardiovascular disease, cvd risk factors, hypertension, cholesterol, blood pressure, sodium, cardiovascular health |
| Created | 2016-06-23T22:21:47Z |
| Publication Date | 2017-01-04T21:46:45Z |

## Description

1999 to 2014.  The National Health and Nutrition Examination Survey (NHANES) is a program of studies designed to assess the health and nutritional status of adults and children in the United States. The survey is unique in that it combines interviews and physical examinations. The NHANES program began in the early 1960s and has been conducted as a series of surveys focusing on different population groups or health topics. In 1999, the survey became a continuous program that has a changing focus on a variety of health and nutrition measurements to meet emerging needs. The survey examines a nationally representative sample of about 5,000 persons each year. These persons are located in counties across the country, 15 of which are visited each year. The NHANES interview includes demographic, socioeconomic, dietary, and health-related questions. The examination component consists of medical, dental, and physiological measurements, as well as laboratory tests administered by highly trained medical personnel. Indicators from this data source have been computed by personnel in CDC's Division for Heart Disease and Stroke Prevention (DHDSP). The data can be plotted as trends and stratified by age group, sex, and race/ethnicity.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| No       | time           | :updated_at                | updated_at                 | meta_data | meta_data   |
| Yes      | series tag     | year                       | Year                       | text      | text        |
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
| Yes      | series tag     | locationid                 | LocationID                 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = data_value_type,data_value_unit,data_value_footnote_symbol,data_value_footnote
```

## Data Commands

```ls
series e:5svk-8bnq d:2017-01-03T20:30:59.000Z t:topic="Aspirin use" t:indicator="Prevalence of aspirin use for secondary prevention of ischemic vascular disease among US adults (40+) (Percentage); NHANES" t:locationabbr=US t:locationdesc="United States" t:topicid=T8 t:priorityarea3=None t:priorityarea4=None t:priorityarea1=None t:priorityarea2=None t:break_out=45-64 t:category="Risk Factors" t:categoryid=C2 t:locationid=00 t:indicatorid=NH010 t:breakoutid=AGE05 t:break_out_category=Age t:year=2011-2012 t:breakoutcategoryid=BOC03 t:datasource=NHANES m:confidence_limit_low=55.9 m:data_value=72.3 m:confidence_limit_high=84.3

series e:5svk-8bnq d:2017-01-03T20:30:59.000Z t:topic="Aspirin use" t:indicator="Prevalence of aspirin use for secondary prevention of ischemic vascular disease among US adults (40+) (Percentage); NHANES" t:locationabbr=US t:locationdesc="United States" t:topicid=T8 t:priorityarea3=None t:priorityarea4=None t:priorityarea1=None t:priorityarea2=None t:break_out=65+ t:category="Risk Factors" t:categoryid=C2 t:locationid=00 t:indicatorid=NH010 t:breakoutid=AGE06 t:break_out_category=Age t:year=2011-2012 t:breakoutcategoryid=BOC03 t:datasource=NHANES m:confidence_limit_low=81.4 m:data_value=88.3 m:confidence_limit_high=92.8

series e:5svk-8bnq d:2017-01-03T20:30:59.000Z t:topic="Aspirin use" t:indicator="Prevalence of aspirin use for secondary prevention of ischemic vascular disease among US adults (40+) (Percentage); NHANES" t:locationabbr=US t:locationdesc="United States" t:topicid=T8 t:priorityarea3=None t:priorityarea4=None t:priorityarea1=None t:priorityarea2=None t:break_out=75+ t:category="Risk Factors" t:categoryid=C2 t:locationid=00 t:indicatorid=NH010 t:breakoutid=AGE08 t:break_out_category=Age t:year=2011-2012 t:breakoutcategoryid=BOC03 t:datasource=NHANES m:confidence_limit_low=81.2 m:data_value=87.8 m:confidence_limit_high=92.4
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value d:"Data value (point estimate)" t:dataTypeName=number

metric m:confidence_limit_low p:float l:Confidence_limit_Low d:"95% confidence interval lower bound" t:dataTypeName=number

metric m:confidence_limit_high p:float l:Confidence_limit_High d:"95% confidence interval upper bound" t:dataTypeName=number

entity e:5svk-8bnq l:"National Health and Nutrition Examination Survey (NHANES)" t:attribution="Centers for Disease Control and Prevention National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/5svk-8bnq

property e:5svk-8bnq t:meta.view v:id=5svk-8bnq v:category="Heart Disease & Stroke Prevention" v:attributionLink=http://www.cdc.gov/nchs/nhanes.htm v:averageRating=0 v:name="National Health and Nutrition Examination Survey (NHANES)" v:attribution="Centers for Disease Control and Prevention National Center for Health Statistics"

property e:5svk-8bnq t:meta.view.license v:name="Public Domain"

property e:5svk-8bnq t:meta.view.owner v:id=6thr-55du v:screenName=Angelique v:displayName=Angelique

property e:5svk-8bnq t:meta.view.tableauthor v:id=6thr-55du v:screenName=Angelique v:roleName=publisher v:displayName=Angelique

property e:5svk-8bnq t:meta.view.metadata.custom_fields.common_core v:Publisher="CDC INFO" v:Contact_Email=cdcinfo@cdc.gov v:Public_Access_Level="Public Domain" v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:029
```

## Top Records

```ls
| :updated_at | year      | locationabbr | locationdesc  | datasource | priorityarea1 | priorityarea2 | priorityarea3 | priorityarea4 | category     | topic       | indicator                                                                                                                  | break_out_category | break_out          | data_value_type | data_value_unit | data_value | data_value_footnote_symbol | data_value_footnote | confidence_limit_low | confidence_limit_high | categoryid | topicid | indicatorid | breakoutcategoryid | breakoutid | locationid | 
| =========== | ========= | ============ | ============= | ========== | ============= | ============= | ============= | ============= | ============ | =========== | ========================================================================================================================== | ================== | ================== | =============== | =============== | ========== | ========================== | =================== | ==================== | ===================== | ========== | ======= | =========== | ================== | ========== | ========== | 
| 1483475459  | 2011-2012 | US           | United States | NHANES     | None          | None          | None          | None          | Risk Factors | Aspirin use | Prevalence of aspirin use for secondary prevention of ischemic vascular disease among US adults (40+) (Percentage); NHANES | Age                | 45-64              | Percentage      | %               | 72.3       |                            |                     | 55.9                 | 84.3                  | C2         | T8      | NH010       | BOC03              | AGE05      | 00         | 
| 1483475459  | 2011-2012 | US           | United States | NHANES     | None          | None          | None          | None          | Risk Factors | Aspirin use | Prevalence of aspirin use for secondary prevention of ischemic vascular disease among US adults (40+) (Percentage); NHANES | Age                | 65+                | Percentage      | %               | 88.3       |                            |                     | 81.4                 | 92.8                  | C2         | T8      | NH010       | BOC03              | AGE06      | 00         | 
| 1483475459  | 2011-2012 | US           | United States | NHANES     | None          | None          | None          | None          | Risk Factors | Aspirin use | Prevalence of aspirin use for secondary prevention of ischemic vascular disease among US adults (40+) (Percentage); NHANES | Age                | 75+                | Percentage      | %               | 87.8       |                            |                     | 81.2                 | 92.4                  | C2         | T8      | NH010       | BOC03              | AGE08      | 00         | 
| 1483475459  | 2011-2012 | US           | United States | NHANES     | None          | None          | None          | None          | Risk Factors | Aspirin use | Prevalence of aspirin use for secondary prevention of ischemic vascular disease among US adults (40+) (Percentage); NHANES | Gender             | Male               | Percentage      | %               | 76.9       |                            |                     | 57.7                 | 89                    | C2         | T8      | NH010       | BOC02              | GEN01      | 00         | 
| 1483475459  | 2011-2012 | US           | United States | NHANES     | None          | None          | None          | None          | Risk Factors | Aspirin use | Prevalence of aspirin use for secondary prevention of ischemic vascular disease among US adults (40+) (Percentage); NHANES | Gender             | Female             | Percentage      | %               | 73.8       |                            |                     | 61.2                 | 83.4                  | C2         | T8      | NH010       | BOC02              | GEN02      | 00         | 
| 1483475459  | 2011-2012 | US           | United States | NHANES     | None          | None          | None          | None          | Risk Factors | Aspirin use | Prevalence of aspirin use for secondary prevention of ischemic vascular disease among US adults (40+) (Percentage); NHANES | Overall            | Overall            | Percentage      | %               | 75.7       |                            |                     | 62.5                 | 85.3                  | C2         | T8      | NH010       | BOC01              | OVR01      | 00         | 
| 1483475459  | 2011-2012 | US           | United States | NHANES     | None          | None          | None          | None          | Risk Factors | Aspirin use | Prevalence of aspirin use for secondary prevention of ischemic vascular disease among US adults (40+) (Percentage); NHANES | Race               | Non-Hispanic White | Percentage      | %               | 78.3       |                            |                     | 56.9                 | 90.8                  | C2         | T8      | NH010       | BOC04              | RAC01      | 00         | 
| 1483475459  | 2011-2012 | US           | United States | NHANES     | None          | None          | None          | None          | Risk Factors | Aspirin use | Prevalence of aspirin use for secondary prevention of ischemic vascular disease among US adults (40+) (Percentage); NHANES | Race               | Non-Hispanic Black | Percentage      | %               | 67.9       |                            |                     | 56.1                 | 77.8                  | C2         | T8      | NH010       | BOC04              | RAC02      | 00         | 
| 1483475459  | 2011-2012 | US           | United States | NHANES     | None          | None          | None          | None          | Risk Factors | Aspirin use | Prevalence of aspirin use for secondary prevention of ischemic vascular disease among US adults (40+) (Percentage); NHANES | Race               | Non-Hispanic Asian | Percentage      | %               | 71.4       |                            |                     | 29.8                 | 93.6                  | C2         | T8      | NH010       | BOC04              | RAC03      | 00         | 
| 1483475459  | 2011-2012 | US           | United States | NHANES     | None          | None          | None          | None          | Risk Factors | Aspirin use | Prevalence of aspirin use for secondary prevention of ischemic vascular disease among US adults (40+) (Percentage); NHANES | Race               | Hispanic           | Percentage      | %               | 54.8       |                            |                     | 38.6                 | 70.1                  | C2         | T8      | NH010       | BOC04              | RAC04      | 00         | 
```