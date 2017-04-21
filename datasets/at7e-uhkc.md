# Behavioral Risk Factors: Selected Metropolitan Area Risk Trends (SMART) MMSA Age-adjusted Prevalence Data (2011 to Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/behavioral-risk-factors-selected-metropolitan-area-risk-trends-smart-mmsa-age-adjusted-pre) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/at7e-uhkc) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/at7e-uhkc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/at7e-uhkc/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | at7e-uhkc |
| Name | Behavioral Risk Factors: Selected Metropolitan Area Risk Trends (SMART) MMSA Age-adjusted Prevalence Data (2011 to Present) |
| Attribution | Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Population Health Population Health Surveillance Branch |
| Category | Behavioral Risk Factors |
| Tags | survey, brfss, behavioral, risk, factor, surveillance, age-adjusted |
| Created | 2016-06-24T16:56:36Z |
| Publication Date | 2016-12-23T17:31:43Z |

## Description

2011 to present. BRFSS SMART MMSA age-adjusted prevalence combined land line and cell phone data. The Selected Metropolitan Area Risk Trends (SMART) project uses the Behavioral Risk Factor Surveillance System (BRFSS) to analyze the data of selected metropolitan statistical areas (MMSAs) with 500 or more respondents. BRFSS data can be used to identify emerging health problems, establish and track health objectives, and develop and evaluate public health policies and programs. BRFSS is a continuous, state-based surveillance system that collects information about modifiable risk factors for chronic diseases and other leading causes of death. Data will be updated annually as it becomes available. Detailed information on sampling methodology and quality assurance can be found on the BRFSS website (http://www.cdc.gov/brfss). Methodology: http://www.cdc.gov/brfss/factsheets/pdf/DBS_BRFSS_survey.pdf Glossary: http://apps.nccd.cdc.gov/BRFSSQuest/index.asp

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
| Yes      | series tag     | responseid                 | RESPONSEID                 | text      | text        |
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
series e:at7e-uhkc d:2015-01-01T00:00:00.000Z t:topic="Overall Health" t:locationdesc="Aberdeen, SD Micropolitan Statistical Area" t:topicid=Topic41 t:class="Health Status" t:break_out=Overall t:questionid=GENHLTH t:response=Excellent t:locationid=10100 t:breakoutid=BO1 t:responseid=RESP056 t:break_out_category=Overall t:question="How is your general health?" t:breakoutcategoryid=CAT1 t:datasource=BRFSS t:classid=CLASS08 m:confidence_limit_low=12.7 m:locationabbr=10100 m:sample_size=91 m:data_value=17 m:confidence_limit_high=21.4

series e:at7e-uhkc d:2015-01-01T00:00:00.000Z t:topic="Overall Health" t:locationdesc="Aberdeen, SD Micropolitan Statistical Area" t:topicid=Topic41 t:class="Health Status" t:break_out=Overall t:questionid=GENHLTH t:response="Very good" t:locationid=10100 t:breakoutid=BO1 t:responseid=RESP057 t:break_out_category=Overall t:question="How is your general health?" t:breakoutcategoryid=CAT1 t:datasource=BRFSS t:classid=CLASS08 m:confidence_limit_low=34 m:locationabbr=10100 m:sample_size=224 m:data_value=39.8 m:confidence_limit_high=45.6

series e:at7e-uhkc d:2015-01-01T00:00:00.000Z t:topic="Overall Health" t:locationdesc="Aberdeen, SD Micropolitan Statistical Area" t:topicid=Topic41 t:class="Health Status" t:break_out=Overall t:questionid=GENHLTH t:response=Good t:locationid=10100 t:breakoutid=BO1 t:responseid=RESP058 t:break_out_category=Overall t:question="How is your general health?" t:breakoutcategoryid=CAT1 t:datasource=BRFSS t:classid=CLASS08 m:confidence_limit_low=27.6 m:locationabbr=10100 m:sample_size=191 m:data_value=33.3 m:confidence_limit_high=38.9
```

## Meta Commands

```ls
metric m:locationabbr p:integer l:Locationabbr t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

metric m:data_value p:float l:Data_value t:dataTypeName=number

metric m:confidence_limit_low p:float l:Confidence_limit_Low t:dataTypeName=number

metric m:confidence_limit_high p:float l:Confidence_limit_High t:dataTypeName=number

entity e:at7e-uhkc l:"Behavioral Risk Factors: Selected Metropolitan Area Risk Trends (SMART) MMSA Age-adjusted Prevalence Data (2011 to Present)" t:attribution="Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Population Health Population Health Surveillance Branch" t:url=https://chronicdata.cdc.gov/api/views/at7e-uhkc

property e:at7e-uhkc t:meta.view v:id=at7e-uhkc v:category="Behavioral Risk Factors" v:attributionLink=http://www.cdc.gov/BRFSS/ v:averageRating=0 v:name="Behavioral Risk Factors: Selected Metropolitan Area Risk Trends (SMART) MMSA Age-adjusted Prevalence Data (2011 to Present)" v:attribution="Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Population Health Population Health Surveillance Branch"

property e:at7e-uhkc t:meta.view.owner v:id=2dya-yixn v:profileImageUrlMedium=/api/users/2dya-yixn/profile_images/THUMB v:profileImageUrlLarge=/api/users/2dya-yixn/profile_images/LARGE v:screenName=Bill_Bartoli v:profileImageUrlSmall=/api/users/2dya-yixn/profile_images/TINY v:displayName=Bill_Bartoli

property e:at7e-uhkc t:meta.view.tableauthor v:id=2dya-yixn v:profileImageUrlMedium=/api/users/2dya-yixn/profile_images/THUMB v:profileImageUrlLarge=/api/users/2dya-yixn/profile_images/LARGE v:screenName=Bill_Bartoli v:profileImageUrlSmall=/api/users/2dya-yixn/profile_images/TINY v:roleName=publisher v:displayName=Bill_Bartoli

property e:at7e-uhkc t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name=CDCINFO
```

## Top Records

```ls
| year | locationabbr | locationdesc                               | class                       | topic                | question                                                                                                           | response              | break_out | break_out_category | sample_size | data_value | confidence_limit_low | confidence_limit_high | display_order | data_value_unit | data_value_type         | data_value_footnote_symbol | data_value_footnote | datasource | classid | topicid | locationid | breakoutid | breakoutcategoryid | questionid | responseid | 
| ==== | ============ | ========================================== | =========================== | ==================== | ================================================================================================================== | ===================== | ========= | ================== | =========== | ========== | ==================== | ===================== | ============= | =============== | ======================= | ========================== | =================== | ========== | ======= | ======= | ========== | ========== | ================== | ========== | ========== | 
| 2015 | 10100        | Aberdeen, SD Micropolitan Statistical Area | Health Status               | Overall Health       | How is your general health?                                                                                        | Excellent             | Overall   | Overall            | 91          | 17.0       | 12.7                 | 21.4                  | 1             | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 10100      | BO1        | CAT1               | GENHLTH    | RESP056    | 
| 2015 | 10100        | Aberdeen, SD Micropolitan Statistical Area | Health Status               | Overall Health       | How is your general health?                                                                                        | Very good             | Overall   | Overall            | 224         | 39.8       | 34.0                 | 45.6                  | 2             | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 10100      | BO1        | CAT1               | GENHLTH    | RESP057    | 
| 2015 | 10100        | Aberdeen, SD Micropolitan Statistical Area | Health Status               | Overall Health       | How is your general health?                                                                                        | Good                  | Overall   | Overall            | 191         | 33.3       | 27.6                 | 38.9                  | 3             | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 10100      | BO1        | CAT1               | GENHLTH    | RESP058    | 
| 2015 | 10100        | Aberdeen, SD Micropolitan Statistical Area | Health Status               | Overall Health       | How is your general health?                                                                                        | Fair                  | Overall   | Overall            | 47          | 6.2        | 4.2                  | 8.3                   | 4             | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 10100      | BO1        | CAT1               | GENHLTH    | RESP059    | 
| 2015 | 10100        | Aberdeen, SD Micropolitan Statistical Area | Health Status               | Overall Health       | How is your general health?                                                                                        | Poor                  | Overall   | Overall            | 24          | 3.7        | 1.7                  | 5.6                   | 5             | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS08 | Topic41 | 10100      | BO1        | CAT1               | GENHLTH    | RESP060    | 
| 2015 | 10100        | Aberdeen, SD Micropolitan Statistical Area | Health Status               | Fair or Poor Health  | Health Status (variable calculated from one or more BRFSS questions)                                               | Good or Better Health | Overall   | Overall            | 506         | 90.1       | 87.4                 | 92.8                  | 6             | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS08 | Topic24 | 10100      | BO1        | CAT1               | _RFHLTH    | RESP061    | 
| 2015 | 10100        | Aberdeen, SD Micropolitan Statistical Area | Health Status               | Fair or Poor Health  | Health Status (variable calculated from one or more BRFSS questions)                                               | Fair or Poor Health   | Overall   | Overall            | 71          | 9.9        | 7.2                  | 12.6                  | 7             | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS08 | Topic24 | 10100      | BO1        | CAT1               | _RFHLTH    | RESP062    | 
| 2015 | 10100        | Aberdeen, SD Micropolitan Statistical Area | Health Care Access/Coverage | Health Care Coverage | Do you have any kind of health care coverage?                                                                      | Yes                   | Overall   | Overall            | 547         | 90.3       | 86.6                 | 94.1                  | 8             | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS07 | Topic29 | 10100      | BO1        | CAT1               | HLTHPLN1   | RESP046    | 
| 2015 | 10100        | Aberdeen, SD Micropolitan Statistical Area | Health Care Access/Coverage | Health Care Coverage | Do you have any kind of health care coverage?                                                                      | No                    | Overall   | Overall            | 31          | 9.7        | 5.9                  | 13.4                  | 9             | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS07 | Topic29 | 10100      | BO1        | CAT1               | HLTHPLN1   | RESP054    | 
| 2015 | 10100        | Aberdeen, SD Micropolitan Statistical Area | Health Care Access/Coverage | Under 65 Coverage    | Adults aged 18-64 who have any kind of health care coverage (variable calculated from one or more BRFSS questions) | Yes                   | Overall   | Overall            | 303         | 89.2       | 84.7                 | 93.6                  | 10            | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS07 | Topic59 | 10100      | BO1        | CAT1               | _HCVU651   | RESP046    | 
```