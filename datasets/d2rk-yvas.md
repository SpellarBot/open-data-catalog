# Behavioral Risk Factor Surveillance System (BRFSS) Age-Adjusted Prevalence Data (2011 to present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/behavioral-risk-factor-surveillance-system-brfss-age-adjusted-prevalence-data-2011-to-pres) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/d2rk-yvas) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/d2rk-yvas/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/d2rk-yvas/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | d2rk-yvas |
| Name | Behavioral Risk Factor Surveillance System (BRFSS) Age-Adjusted Prevalence Data (2011 to present) |
| Attribution | Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Population Health Population Health Surveillance Branch |
| Category | Behavioral Risk Factors |
| Tags | survey, brfss, behavioral, risk, factor, surveillance, age-adjusted |
| Created | 2016-06-24T16:32:20Z |
| Publication Date | 2016-12-23T17:28:02Z |
| Rows Updated | 2016-12-22T21:46:43Z |

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
series e:d2rk-yvas d:2015-01-01T00:00:00.000Z t:topic="Alcohol Consumption" t:locationabbr=AL t:locationdesc=Alabama t:topicid=Topic03 t:class="Alcohol Consumption" t:break_out=Overall t:questionid=DRNKANY5 t:response=Yes t:locationid=01 t:breakoutid=BO1 t:responseid=RESP046 t:break_out_category=Overall t:question="Adults who have had at least one drink of alcohol within the past 30 days" t:breakoutcategoryid=CAT1 t:datasource=BRFSS t:classid=CLASS01 m:confidence_limit_low=40.2 m:sample_size=2767 m:data_value=41.9 m:confidence_limit_high=43.6

series e:d2rk-yvas d:2015-01-01T00:00:00.000Z t:topic="Alcohol Consumption" t:locationabbr=AL t:locationdesc=Alabama t:topicid=Topic03 t:class="Alcohol Consumption" t:break_out=Overall t:questionid=DRNKANY5 t:response=No t:locationid=01 t:breakoutid=BO1 t:responseid=RESP054 t:break_out_category=Overall t:question="Adults who have had at least one drink of alcohol within the past 30 days" t:breakoutcategoryid=CAT1 t:datasource=BRFSS t:classid=CLASS01 m:confidence_limit_low=56.4 m:sample_size=4805 m:data_value=58.1 m:confidence_limit_high=59.8

series e:d2rk-yvas d:2015-01-01T00:00:00.000Z t:topic="Binge Drinking" t:locationabbr=AL t:locationdesc=Alabama t:topicid=Topic07 t:class="Alcohol Consumption" t:break_out=Overall t:questionid=_RFBING5 t:response=Yes t:locationid=01 t:breakoutid=BO1 t:responseid=RESP046 t:break_out_category=Overall t:question="Binge drinkers (males having five or more drinks on one occasion, females having four or more drinks on one occasion) (variable calculated from one or more BRFSS questions)" t:breakoutcategoryid=CAT1 t:datasource=BRFSS t:classid=CLASS01 m:confidence_limit_low=11.2 m:sample_size=665 m:data_value=12.3 m:confidence_limit_high=13.5
```

## Meta Commands

```ls
metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

metric m:data_value p:float l:Data_value t:dataTypeName=number

metric m:confidence_limit_low p:float l:Confidence_limit_Low t:dataTypeName=number

metric m:confidence_limit_high p:float l:Confidence_limit_High t:dataTypeName=number

entity e:d2rk-yvas l:"Behavioral Risk Factor Surveillance System (BRFSS) Age-Adjusted Prevalence Data (2011 to present)" t:attribution="Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Population Health Population Health Surveillance Branch" t:url=https://chronicdata.cdc.gov/api/views/d2rk-yvas

property e:d2rk-yvas t:meta.view v:id=d2rk-yvas v:category="Behavioral Risk Factors" v:attributionLink=http://www.cdc.gov/BRFSS/ v:averageRating=0 v:name="Behavioral Risk Factor Surveillance System (BRFSS) Age-Adjusted Prevalence Data (2011 to present)" v:attribution="Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Population Health Population Health Surveillance Branch"

property e:d2rk-yvas t:meta.view.owner v:id=2dya-yixn v:profileImageUrlMedium=/api/users/2dya-yixn/profile_images/THUMB v:profileImageUrlLarge=/api/users/2dya-yixn/profile_images/LARGE v:screenName=Bill_Bartoli v:profileImageUrlSmall=/api/users/2dya-yixn/profile_images/TINY v:roleName=publisher v:displayName=Bill_Bartoli

property e:d2rk-yvas t:meta.view.tableauthor v:id=2dya-yixn v:profileImageUrlMedium=/api/users/2dya-yixn/profile_images/THUMB v:profileImageUrlLarge=/api/users/2dya-yixn/profile_images/LARGE v:screenName=Bill_Bartoli v:profileImageUrlSmall=/api/users/2dya-yixn/profile_images/TINY v:roleName=publisher v:displayName=Bill_Bartoli

property e:d2rk-yvas t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name=CDCINFO
```