# Behavioral Risk Factors: Selected Metropolitan Area Risk Trends (SMART) County Prevalence Data (2010 and prior)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/behavioral-risk-factors-selected-metropolitan-area-risk-trends-smart-county-prevalence-dat-a0124) |
| Metadata | [Link](https://data.cdc.gov/api/views/acme-vg9e) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/acme-vg9e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/acme-vg9e/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | acme-vg9e |
| Name | Behavioral Risk Factors: Selected Metropolitan Area Risk Trends (SMART) County Prevalence Data (2010 and prior) |
| Category | Behavioral Risk Factors |
| Tags | smart, county, survey, brfss, behavioral, risk, ... |
| Created | 2015-06-04T14:45:44Z |
| Publication Date | 2016-03-11T15:58:38Z |

## Description

2002-2010. BRFSS SMART County Prevalence land line only data. The Selected Metropolitan Area Risk Trends (SMART) project uses the Behavioral Risk Factor Surveillance System (BRFSS) to analyze the data of selected counties with 500 or more respondents. BRFSS data can be used to identify emerging health problems, establish and track health objectives, and develop and evaluate public health policies and programs. BRFSS is a continuous, state-based surveillance system that collects information about modifiable risk factors for chronic diseases and other leading causes of death. Data will be updated annually as it becomes available. Detailed information on sampling methodology and quality assurance can be found on the BRFSS website (http://www.cdc.gov/brfss). Methodology: http://www.cdc.gov/brfss/factsheets/pdf/DBS_BRFSS_survey.pdf Glossary: http://apps.nccd.cdc.gov/BRFSSQuest/index.asp

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
| Yes      | series tag     | locationid                 | LocationID                 | text      | number      |
| Yes      | series tag     | questionid                 | QuestionID                 | text      | text        |
| Yes      | series tag     | respid                     | RESPID                     | text      | text        |
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
series e:acme-vg9e d:2010-01-01T00:00:00.000Z t:response=Excellent t:topic="Overall Health" t:locationabbr=AL t:locationdesc="AL - Jefferson County" t:topicid=Topic41 t:respid=RESP056 t:class="Health Status" t:question="How is your general health?" t:datasource=BRFSS t:questionid=GENHLTH t:classid=CLASS08 m:confidence_limit_low=14.1 m:sample_size=94 m:data_value=18.9 m:confidence_limit_high=23.6

series e:acme-vg9e d:2010-01-01T00:00:00.000Z t:response="Very good" t:topic="Overall Health" t:locationabbr=AL t:locationdesc="AL - Jefferson County" t:topicid=Topic41 t:respid=RESP057 t:class="Health Status" t:question="How is your general health?" t:datasource=BRFSS t:questionid=GENHLTH t:classid=CLASS08 m:confidence_limit_low=24.9 m:sample_size=148 m:data_value=30 m:confidence_limit_high=35

series e:acme-vg9e d:2010-01-01T00:00:00.000Z t:response=Good t:topic="Overall Health" t:locationabbr=AL t:locationdesc="AL - Jefferson County" t:topicid=Topic41 t:respid=RESP058 t:class="Health Status" t:question="How is your general health?" t:datasource=BRFSS t:questionid=GENHLTH t:classid=CLASS08 m:confidence_limit_low=28.2 m:sample_size=208 m:data_value=33.1 m:confidence_limit_high=38
```

## Meta Commands

```ls
metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

metric m:data_value p:float l:Data_value t:dataTypeName=number

metric m:confidence_limit_low p:float l:Confidence_limit_Low t:dataTypeName=number

metric m:confidence_limit_high p:double l:Confidence_limit_High t:dataTypeName=number

entity e:acme-vg9e l:"Behavioral Risk Factors: Selected Metropolitan Area Risk Trends (SMART) County Prevalence Data (2010 and prior)" t:url=https://data.cdc.gov/api/views/acme-vg9e

property e:acme-vg9e t:meta.view v:id=acme-vg9e v:category="Behavioral Risk Factors" v:averageRating=0 v:name="Behavioral Risk Factors: Selected Metropolitan Area Risk Trends (SMART) County Prevalence Data (2010 and prior)"

property e:acme-vg9e t:meta.view.owner v:id=emuu-zcsq v:screenName=BRFSS v:displayName=BRFSS

property e:acme-vg9e t:meta.view.tableauthor v:id=emuu-zcsq v:screenName=BRFSS v:roleName=publisher v:displayName=BRFSS

property e:acme-vg9e t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | locationabbr | locationdesc          | class                       | topic                | question                                                                                                           | response              | sample_size | data_value | confidence_limit_low | confidence_limit_high | display_order | data_value_unit | data_value_type  | data_value_footnote_symbol | data_value_footnote | datasource | classid | topicid | locationid | questionid | respid  | 
| ==== | ============ | ===================== | =========================== | ==================== | ================================================================================================================== | ===================== | =========== | ========== | ==================== | ===================== | ============= | =============== | ================ | ========================== | =================== | ========== | ======= | ======= | ========== | ========== | ======= | 
| 2010 | AL           | AL - Jefferson County | Health Status               | Overall Health       | How is your general health?                                                                                        | Excellent             | 94          | 18.9       | 14.1                 | 23.6                  | 1             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 |            | GENHLTH    | RESP056 | 
| 2010 | AL           | AL - Jefferson County | Health Status               | Overall Health       | How is your general health?                                                                                        | Very good             | 148         | 30         | 24.9                 | 35                    | 2             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 |            | GENHLTH    | RESP057 | 
| 2010 | AL           | AL - Jefferson County | Health Status               | Overall Health       | How is your general health?                                                                                        | Good                  | 208         | 33.1       | 28.2                 | 38                    | 3             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 |            | GENHLTH    | RESP058 | 
| 2010 | AL           | AL - Jefferson County | Health Status               | Overall Health       | How is your general health?                                                                                        | Fair                  | 107         | 12.5       | 9.5                  | 15.4                  | 4             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 |            | GENHLTH    | RESP059 | 
| 2010 | AL           | AL - Jefferson County | Health Status               | Overall Health       | How is your general health?                                                                                        | Poor                  | 45          | 5.5        | 3.5                  | 7.4                   | 5             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 |            | GENHLTH    | RESP060 | 
| 2010 | AL           | AL - Jefferson County | Health Status               | Fair or Poor Health  | Health Status (variable calculated from one or more BRFSS questions)                                               | Good or Better Health | 450         | 82         | 78.6                 | 85.3                  | 6             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic24 |            | _RFHLTH    | RESP061 | 
| 2010 | AL           | AL - Jefferson County | Health Status               | Fair or Poor Health  | Health Status (variable calculated from one or more BRFSS questions)                                               | Fair or Poor Health   | 152         | 18         | 14.6                 | 21.3                  | 7             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS08 | Topic24 |            | _RFHLTH    | RESP062 | 
| 2010 | AL           | AL - Jefferson County | Health Care Access/Coverage | Health Care Coverage | Do you have any kind of health care coverage?                                                                      | Yes                   | 524         | 79.3       | 74                   | 84.5                  | 8             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS07 | Topic29 |            | HLTHPLAN   | RESP046 | 
| 2010 | AL           | AL - Jefferson County | Health Care Access/Coverage | Health Care Coverage | Do you have any kind of health care coverage?                                                                      | No                    | 77          | 20.7       | 15.4                 | 25.9                  | 9             | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS07 | Topic29 |            | HLTHPLAN   | RESP054 | 
| 2010 | AL           | AL - Jefferson County | Health Care Access/Coverage | Under 65 Coverage    | Adults aged 18-64 who have any kind of health care coverage (variable calculated from one or more BRFSS questions) | Yes                   | 316         | 74.9       | 68.6                 | 81.1                  | 10            | %               | Crude Prevalence |                            |                     | BRFSS      | CLASS07 | Topic59 |            | _HCVU65    | RESP046 | 
```