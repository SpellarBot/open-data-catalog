# Behavioral Risk Factor Surveillance System (BRFSS) Age-Adjusted Prevalence Data (2011 to present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/behavioral-risk-factor-surveillance-system-brfss-age-adjusted-prevalence-data-2011-to-pres-e2415) |
| Metadata | [Link](https://data.cdc.gov/api/views/d2rk-yvas) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/d2rk-yvas/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/d2rk-yvas/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | d2rk-yvas |
| Name | Behavioral Risk Factor Surveillance System (BRFSS) Age-Adjusted Prevalence Data (2011 to present) |
| Attribution | Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Population Health Population Health Surveillance Branch |
| Category | Behavioral Risk Factors |
| Tags | survey, brfss, behavioral, risk, factor, surveillance, age-adjusted |
| Created | 2016-06-24T16:32:20Z |
| Publication Date | 2017-09-11T12:33:39Z |

## Description

2011 to present. BRFSS combined land line and cell phone age-adjusted prevalence data. The BRFSS is a continuous, state-based surveillance system that collects information about modifiable risk factors for chronic diseases and other leading causes of death. 
Data will be updated annually as it becomes available.

Detailed information on sampling methodology and quality assurance can be found on the BRFSS website (http://www.cdc.gov/brfss). 
Methodology: http://www.cdc.gov/brfss/factsheets/pdf/DBS_BRFSS_survey.pdf 
Glossary: http://apps.nccd.cdc.gov/BRFSSQuest/index.asp

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
series e:d2rk-yvas d:2015-01-01T00:00:00.000Z t:breakoutcategoryid=CAT1 t:questionid=DRNKANY5 t:question="Adults who have had at least one drink of alcohol within the past 30 days" t:locationabbr=AL t:break_out=Overall t:locationdesc=Alabama t:topicid=Topic03 t:classid=CLASS01 t:break_out_category=Overall t:response=Yes t:datasource=BRFSS t:locationid=01 t:breakoutid=BO1 t:topic="Alcohol Consumption" t:class="Alcohol Consumption" t:responseid=RESP046 m:sample_size=2767 m:data_value=41.9 m:confidence_limit_low=40.2 m:confidence_limit_high=43.6

series e:d2rk-yvas d:2015-01-01T00:00:00.000Z t:breakoutcategoryid=CAT1 t:questionid=DRNKANY5 t:question="Adults who have had at least one drink of alcohol within the past 30 days" t:locationabbr=AL t:break_out=Overall t:locationdesc=Alabama t:topicid=Topic03 t:classid=CLASS01 t:break_out_category=Overall t:response=No t:datasource=BRFSS t:locationid=01 t:breakoutid=BO1 t:topic="Alcohol Consumption" t:class="Alcohol Consumption" t:responseid=RESP054 m:sample_size=4805 m:data_value=58.1 m:confidence_limit_low=56.4 m:confidence_limit_high=59.8

series e:d2rk-yvas d:2015-01-01T00:00:00.000Z t:breakoutcategoryid=CAT1 t:questionid=_RFBING5 t:question="Binge drinkers (males having five or more drinks on one occasion, females having four or more drinks on one occasion) (variable calculated from one or more BRFSS questions)" t:locationabbr=AL t:break_out=Overall t:locationdesc=Alabama t:topicid=Topic07 t:classid=CLASS01 t:break_out_category=Overall t:response=Yes t:datasource=BRFSS t:locationid=01 t:breakoutid=BO1 t:topic="Binge Drinking" t:class="Alcohol Consumption" t:responseid=RESP046 m:sample_size=665 m:data_value=12.3 m:confidence_limit_low=11.2 m:confidence_limit_high=13.5
```

## Meta Commands

```ls
metric m:sample_size p:integer l:Sample_Size d:"Sample size used to calculate the data value" t:dataTypeName=number

metric m:data_value p:float l:Data_value d:"Data Value, such as 14.7 or no value if footnote symbol is present" t:dataTypeName=number

metric m:confidence_limit_low p:float l:Confidence_limit_Low d:"Low Confidence Limit" t:dataTypeName=number

metric m:confidence_limit_high p:float l:Confidence_limit_High d:"High Confidence Limit" t:dataTypeName=number

entity e:d2rk-yvas l:"Behavioral Risk Factor Surveillance System (BRFSS) Age-Adjusted Prevalence Data (2011 to present)" t:attribution="Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Population Health Population Health Surveillance Branch" t:url=https://data.cdc.gov/api/views/d2rk-yvas

property e:d2rk-yvas t:meta.view d:2017-09-25T07:27:27.373Z v:averageRating=0 v:name="Behavioral Risk Factor Surveillance System (BRFSS) Age-Adjusted Prevalence Data (2011 to present)" v:attribution="Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Population Health Population Health Surveillance Branch" v:attributionLink=http://www.cdc.gov/BRFSS/ v:id=d2rk-yvas v:category="Behavioral Risk Factors"

property e:d2rk-yvas t:meta.view.owner d:2017-09-25T07:27:27.373Z v:displayName=WKB8@cdc.gov v:profileImageUrlLarge=/api/users/2dya-yixn/profile_images/LARGE v:profileImageUrlSmall=/api/users/2dya-yixn/profile_images/TINY v:id=2dya-yixn v:screenName=WKB8@cdc.gov v:profileImageUrlMedium=/api/users/2dya-yixn/profile_images/THUMB

property e:d2rk-yvas t:meta.view.tableauthor d:2017-09-25T07:27:27.373Z v:displayName=WKB8@cdc.gov v:profileImageUrlLarge=/api/users/2dya-yixn/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/2dya-yixn/profile_images/TINY v:id=2dya-yixn v:screenName=WKB8@cdc.gov v:profileImageUrlMedium=/api/users/2dya-yixn/profile_images/THUMB

property e:d2rk-yvas t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:27:27.373Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name=CDCINFO
```

## Top Records

```ls
| year | locationabbr | locationdesc | class                 | topic               | question                                                                                                                                                                     | response                                | break_out | break_out_category | sample_size | data_value | confidence_limit_low | confidence_limit_high | display_order | data_value_unit | data_value_type         | data_value_footnote_symbol | data_value_footnote | datasource | classid | topicid | locationid | breakoutid | breakoutcategoryid | questionid | responseid | 
| ==== | ============ | ============ | ===================== | =================== | ============================================================================================================================================================================ | ======================================= | ========= | ================== | =========== | ========== | ==================== | ===================== | ============= | =============== | ======================= | ========================== | =================== | ========== | ======= | ======= | ========== | ========== | ================== | ========== | ========== | 
| 2015 | AL           | Alabama      | Alcohol Consumption   | Alcohol Consumption | Adults who have had at least one drink of alcohol within the past 30 days                                                                                                    | Yes                                     | Overall   | Overall            | 2767        | 41.9       | 40.2                 | 43.6                  | 7             | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS01 | Topic03 | 01         | BO1        | CAT1               | DRNKANY5   | RESP046    | 
| 2015 | AL           | Alabama      | Alcohol Consumption   | Alcohol Consumption | Adults who have had at least one drink of alcohol within the past 30 days                                                                                                    | No                                      | Overall   | Overall            | 4805        | 58.1       | 56.4                 | 59.8                  | 33            | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS01 | Topic03 | 01         | BO1        | CAT1               | DRNKANY5   | RESP054    | 
| 2015 | AL           | Alabama      | Alcohol Consumption   | Binge Drinking      | Binge drinkers (males having five or more drinks on one occasion, females having four or more drinks on one occasion) (variable calculated from one or more BRFSS questions) | Yes                                     | Overall   | Overall            | 665         | 12.3       | 11.2                 | 13.5                  | 59            | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS01 | Topic07 | 01         | BO1        | CAT1               | _RFBING5   | RESP046    | 
| 2015 | AL           | Alabama      | Alcohol Consumption   | Binge Drinking      | Binge drinkers (males having five or more drinks on one occasion, females having four or more drinks on one occasion) (variable calculated from one or more BRFSS questions) | No                                      | Overall   | Overall            | 6822        | 87.7       | 86.5                 | 88.8                  | 85            | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS01 | Topic07 | 01         | BO1        | CAT1               | _RFBING5   | RESP054    | 
| 2015 | AL           | Alabama      | Alcohol Consumption   | Heavy Drinking      | Heavy drinkers (adult men having more than 14 drinks per week and adult women having more than 7 drinks per week) (variable calculated from one or more BRFSS questions)     | Do not meet criteria for heavy drinking | Overall   | Overall            | 7180        | 95.0       | 94.2                 | 95.8                  | 111           | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS01 | Topic30 | 01         | BO1        | CAT1               | _RFDRHV5   | RESP205    | 
| 2015 | AL           | Alabama      | Alcohol Consumption   | Heavy Drinking      | Heavy drinkers (adult men having more than 14 drinks per week and adult women having more than 7 drinks per week) (variable calculated from one or more BRFSS questions)     | Meet criteria for heavy drinking        | Overall   | Overall            | 317         | 5.0        | 4.2                  | 5.8                   | 137           | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS01 | Topic30 | 01         | BO1        | CAT1               | _RFDRHV5   | RESP206    | 
| 2015 | AL           | Alabama      | Cholesterol Awareness | Cholesterol Checked | Adults who have ever had their blood cholesterol checked                                                                                                                     | Yes                                     | Overall   | Overall            | 6883        | 80.5       | 79.0                 | 82.0                  | 163           | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS02 | Topic11 | 01         | BO1        | CAT1               | BLOODCHO   | RESP046    | 
| 2015 | AL           | Alabama      | Cholesterol Awareness | Cholesterol Checked | Adults who have ever had their blood cholesterol checked                                                                                                                     | No                                      | Overall   | Overall            | 830         | 19.5       | 18.0                 | 21.0                  | 189           | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS02 | Topic11 | 01         | BO1        | CAT1               | BLOODCHO   | RESP054    | 
| 2015 | AL           | Alabama      | Cholesterol Awareness | Cholesterol Checked | Adults who have had their blood cholesterol checked within the last five years (variable calculated from one or more BRFSS questions)                                        | Checked in past 5 years                 | Overall   | Overall            | 6578        | 77.4       | 75.9                 | 78.9                  | 215           | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS02 | Topic11 | 01         | BO1        | CAT1               | _CHOLCHK   | RESP072    | 
| 2015 | AL           | Alabama      | Cholesterol Awareness | Cholesterol Checked | Adults who have had their blood cholesterol checked within the last five years (variable calculated from one or more BRFSS questions)                                        | Not Checked in past 5 years             | Overall   | Overall            | 189         | 2.9        | 2.3                  | 3.4                   | 241           | %               | Age-adjusted Prevalence |                            |                     | BRFSS      | CLASS02 | Topic11 | 01         | BO1        | CAT1               | _CHOLCHK   | RESP073    | 
```