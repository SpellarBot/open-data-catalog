# Behavioral Risk Factor Surveillance System (BRFSS) Prevalence Data (2010 and prior)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/behavioral-risk-factor-surveillance-system-brfss-prevalence-data-2010-and-prior) |
| Metadata | [Link](https://data.cdc.gov/api/views/y4ft-s73h) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/y4ft-s73h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/y4ft-s73h/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | y4ft-s73h |
| Name | Behavioral Risk Factor Surveillance System (BRFSS) Prevalence Data (2010 and prior) |
| Category | Behavioral Risk Factors |
| Tags | survey, brfss, behavioral, risk, factor, ... |
| Created | 2015-06-04T17:33:13Z |
| Publication Date | 2016-03-11T15:04:09Z |
| Rows Updated | 2016-03-11T15:01:49Z |

## Description

1995-2010. BRFSS land line only prevalence data. BRFSS is a continuous, state-based surveillance system that collects information about modifiable risk factors for chronic diseases and other leading causes of death. Data will be updated annually as it becomes available. Detailed information on sampling methodology and quality assurance can be found on the BRFSS website (http://www.cdc.gov/brfss). Methodology: http://www.cdc.gov/brfss/factsheets/pdf/DBS_BRFSS_survey.pdf Glossary: http://apps.nccd.cdc.gov/BRFSSQuest/index.asp

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
| No       |                | data_value_unit            | Data_value_unit            | number    | text        |
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
| Yes      | series tag     | responseid                 | ResponseID                 | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_footnote,data_value_footnote_symbol,data_value_unit,data_value_type,display_order
```

## Data Commands

```ls
series e:y4ft-s73h d:2010-01-01T00:00:00.000Z t:topic="Overall Health" t:locationabbr=AL t:locationdesc=Alabama t:topicid=Topic41 t:class="Health Status" t:break_out=Overall t:questionid=GENHLTH t:response=Excellent t:locationid=01 t:breakoutid=BO1 t:responseid=RESP056 t:break_out_category=Overall t:question="How is your general health?" t:breakoutcategoryid=CAT1 t:datasource=BRFSS t:classid=CLASS08 m:confidence_limit_low=15 m:sample_size=996 m:data_value=16.4 m:confidence_limit_high=17.7

series e:y4ft-s73h d:2010-01-01T00:00:00.000Z t:topic="Overall Health" t:locationabbr=AL t:locationdesc=Alabama t:topicid=Topic41 t:class="Health Status" t:break_out=Overall t:questionid=GENHLTH t:response="Very good" t:locationid=01 t:breakoutid=BO1 t:responseid=RESP057 t:break_out_category=Overall t:question="How is your general health?" t:breakoutcategoryid=CAT1 t:datasource=BRFSS t:classid=CLASS08 m:confidence_limit_low=27.6 m:sample_size=1923 m:data_value=29.2 m:confidence_limit_high=30.8

series e:y4ft-s73h d:2010-01-01T00:00:00.000Z t:topic="Overall Health" t:locationabbr=AL t:locationdesc=Alabama t:topicid=Topic41 t:class="Health Status" t:break_out=Overall t:questionid=GENHLTH t:response=Good t:locationid=01 t:breakoutid=BO1 t:responseid=RESP058 t:break_out_category=Overall t:question="How is your general health?" t:breakoutcategoryid=CAT1 t:datasource=BRFSS t:classid=CLASS08 m:confidence_limit_low=31.6 m:sample_size=2524 m:data_value=33.2 m:confidence_limit_high=34.8
```

## Meta Commands

```ls
metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

metric m:data_value l:Data_value t:dataTypeName=number

metric m:confidence_limit_low l:Confidence_limit_Low t:dataTypeName=number

metric m:confidence_limit_high l:Confidence_limit_High t:dataTypeName=number

entity e:y4ft-s73h l:"Behavioral Risk Factor Surveillance System (BRFSS) Prevalence Data (2010 and prior)" t:url=https://data.cdc.gov/api/views/y4ft-s73h

property e:y4ft-s73h t:meta.view v:id=y4ft-s73h v:category="Behavioral Risk Factors" v:averageRating=0 v:name="Behavioral Risk Factor Surveillance System (BRFSS) Prevalence Data (2010 and prior)"

property e:y4ft-s73h t:meta.view.owner v:id=emuu-zcsq v:screenName=BRFSS v:roleName=publisher v:displayName=BRFSS

property e:y4ft-s73h t:meta.view.tableauthor v:id=emuu-zcsq v:screenName=BRFSS v:roleName=publisher v:displayName=BRFSS

property e:y4ft-s73h t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```