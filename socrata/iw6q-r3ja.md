# Center for Medicare & Medicaid Services (CMS) , Medicare Claims data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/center-for-medicare-amp-medicaid-services-cms-medicare-claims-data) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/iw6q-r3ja) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/iw6q-r3ja/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/iw6q-r3ja/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | iw6q-r3ja |
| Name | Center for Medicare & Medicaid Services (CMS) , Medicare Claims data |
| Attribution | Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Heart Disease and Stroke Prevention (DHDSP), National Cardiovascular Disea... |
| Category | Heart Disease & Stroke Prevention |
| Tags | cardiovascular disease, stroke, heart disease, claims data |
| Created | 2016-06-23T23:17:36Z |
| Publication Date | 2017-01-04T21:48:34Z |

## Description

2003 to 2013.  CMS compiles claims data for Medicare and Medicaid patients across a variety of categories and years. This includes Inpatient and Outpatient claims, Master Beneficiary Summary Files, and many other files. Indicators from this data source have been computed by personnel in CDC's Division for Heart Disease and Stroke Prevention (DHDSP).  This dataset is one of the datasets provided by National Cardiovascular Disease Surveillance System. The system is designed to integrate multiple indicators from many data sources to provide a comprehensive picture of the public health burden of CVDs and associated risk factors in the United States. The data are organized by location (national, state, county, and selected sites) and indicator. The data can be plotted as trends and stratified by sex and race/ethnicity.

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
| Yes      | series tag     | locationid                 | LocationID                 | html      | html        |
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
series e:iw6q-r3ja d:2004-01-01T00:00:00.000Z t:topic="Major Cardiovascular Disease" t:indicator="Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US Medicare FFS beneficiaries (65+) (Percentage)" t:locationdesc="United States" t:locationabbr=US t:topicid=T1 t:priorityarea3=None t:priorityarea4=None t:priorityarea1=None t:priorityarea2=None t:break_out=65+ t:categoryid=C1 t:category="Cardiovascular Diseases" t:locationid=00 t:indicatorid=MD101 t:breakoutid=AGE06 t:break_out_category=Age t:breakoutcategoryid=BOC03 t:datasource=Medicare m:confidence_limit_low=26.6 m:data_value=26.7 m:confidence_limit_high=26.7

series e:iw6q-r3ja d:2004-01-01T00:00:00.000Z t:topic="Major Cardiovascular Disease" t:indicator="Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US Medicare FFS beneficiaries (65+) (Percentage)" t:locationdesc="United States" t:locationabbr=US t:topicid=T1 t:priorityarea3=None t:priorityarea4=None t:priorityarea1=None t:priorityarea2=None t:break_out=Male t:categoryid=C1 t:category="Cardiovascular Diseases" t:locationid=00 t:indicatorid=MD101 t:breakoutid=GEN01 t:break_out_category=Gender t:breakoutcategoryid=BOC02 t:datasource=Medicare m:confidence_limit_low=30.1 m:data_value=30.2 m:confidence_limit_high=30.2

series e:iw6q-r3ja d:2004-01-01T00:00:00.000Z t:topic="Major Cardiovascular Disease" t:indicator="Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US Medicare FFS beneficiaries (65+) (Percentage)" t:locationdesc="United States" t:locationabbr=US t:topicid=T1 t:priorityarea3=None t:priorityarea4=None t:priorityarea1=None t:priorityarea2=None t:break_out=Hispanic t:categoryid=C1 t:category="Cardiovascular Diseases" t:locationid=00 t:indicatorid=MD101 t:breakoutid=RAC04 t:break_out_category=Race t:breakoutcategoryid=BOC04 t:datasource=Medicare m:confidence_limit_low=25.9 m:data_value=26.1 m:confidence_limit_high=26.3
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value d:"Data value (point estimate)" t:dataTypeName=number

metric m:confidence_limit_low p:float l:Confidence_limit_Low d:"95% confidence interval lower bound" t:dataTypeName=number

metric m:confidence_limit_high p:float l:Confidence_limit_High d:"95% confidence interval upper bound" t:dataTypeName=number

entity e:iw6q-r3ja l:"Center for Medicare & Medicaid Services (CMS) , Medicare Claims data" t:attribution="Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Heart Disease and Stroke Prevention (DHDSP), National Cardiovascular Disease Surveillance System" t:url=https://chronicdata.cdc.gov/api/views/iw6q-r3ja

property e:iw6q-r3ja t:meta.view v:id=iw6q-r3ja v:category="Heart Disease & Stroke Prevention" v:attributionLink=http://www.cdc.gov/dhdsp/ncvdss/index.htm v:averageRating=0 v:name="Center for Medicare & Medicaid Services (CMS) , Medicare Claims data" v:attribution="Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Heart Disease and Stroke Prevention (DHDSP), National Cardiovascular Disease Surveillance System"

property e:iw6q-r3ja t:meta.view.license v:name="Public Domain"

property e:iw6q-r3ja t:meta.view.owner v:id=6thr-55du v:screenName=Angelique v:displayName=Angelique

property e:iw6q-r3ja t:meta.view.tableauthor v:id=6thr-55du v:screenName=Angelique v:roleName=publisher v:displayName=Angelique

property e:iw6q-r3ja t:meta.view.metadata.custom_fields.common_core v:Publisher="CDC INFO" v:Contact_Email=cdcinfo@cdc.gov v:Public_Access_Level="Public Domain" v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:029
```

## Top Records

```ls
| year | locationabbr | locationdesc  | datasource | priorityarea1 | priorityarea2 | priorityarea3 | priorityarea4 | category                | topic                        | indicator                                                                                                                                | break_out_category | break_out | data_value_type | data_value_unit | data_value | data_value_footnote_symbol | data_value_footnote | confidence_limit_low | confidence_limit_high | categoryid | topicid | indicatorid | breakoutcategoryid | breakoutid | locationid | 
| ==== | ============ | ============= | ========== | ============= | ============= | ============= | ============= | ======================= | ============================ | ======================================================================================================================================== | ================== | ========= | =============== | =============== | ========== | ========================== | =================== | ==================== | ===================== | ========== | ======= | =========== | ================== | ========== | ========== | 
| 2004 | US           | United States | Medicare   | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US Medicare FFS beneficiaries (65+) (Percentage) | Age                | 65+       | Percentage      | %               | 26.7       |                            |                     | 26.6                 | 26.7                  | C1         | T1      | MD101       | BOC03              | AGE06      | 00         | 
| 2004 | US           | United States | Medicare   | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US Medicare FFS beneficiaries (65+) (Percentage) | Gender             | Male      | Percentage      | %               | 30.2       |                            |                     | 30.1                 | 30.2                  | C1         | T1      | MD101       | BOC02              | GEN01      | 00         | 
| 2004 | US           | United States | Medicare   | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US Medicare FFS beneficiaries (65+) (Percentage) | Race               | Hispanic  | Percentage      | %               | 26.1       |                            |                     | 25.9                 | 26.3                  | C1         | T1      | MD101       | BOC04              | RAC04      | 00         | 
| 2004 | US           | United States | Medicare   | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US Medicare FFS beneficiaries (65+) (Percentage) | Gender             | Female    | Percentage      | %               | 24.0       |                            |                     | 24.0                 | 24.1                  | C1         | T1      | MD101       | BOC02              | GEN02      | 00         | 
| 2004 | US           | United States | Medicare   | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US Medicare FFS beneficiaries (65+) (Percentage) | Race               | White     | Percentage      | %               | 26.6       |                            |                     | 26.6                 | 26.7                  | C1         | T1      | MD101       | BOC04              | RAC05      | 00         | 
| 2004 | US           | United States | Medicare   | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US Medicare FFS beneficiaries (65+) (Percentage) | Race               | Black     | Percentage      | %               | 26.7       |                            |                     | 26.7                 | 26.8                  | C1         | T1      | MD101       | BOC04              | RAC06      | 00         | 
| 2004 | US           | United States | Medicare   | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US Medicare FFS beneficiaries (65+) (Percentage) | Age                | 75+       | Percentage      | %               | 26.6       |                            |                     | 26.5                 | 26.6                  | C1         | T1      | MD101       | BOC03              | AGE08      | 00         | 
| 2004 | US           | United States | Medicare   | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US Medicare FFS beneficiaries (65+) (Percentage) | Race               | Other     | Percentage      | %               | 25.5       |                            |                     | 25.4                 | 25.7                  | C1         | T1      | MD101       | BOC04              | RAC07      | 00         | 
| 2004 | US           | United States | Medicare   | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US Medicare FFS beneficiaries (65+) (Percentage) | Overall            | Overall   | Percentage      | %               | 26.6       |                            |                     | 26.6                 | 26.6                  | C1         | T1      | MD101       | BOC01              | OVR01      | 00         | 
| 2004 | AL           | Alabama       | Medicare   | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US Medicare FFS beneficiaries (65+) (Percentage) | Race               | Black     | Percentage      | %               | 28.2       |                            |                     | 27.7                 | 28.6                  | C1         | T1      | MD101       | BOC04              | RAC06      | 01         | 
```