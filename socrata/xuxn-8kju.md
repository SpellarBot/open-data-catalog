# Behavioral Risk Factor Data: Health-Related Quality of Life (HRQOL)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/behavioral-risk-factor-data-health-related-quality-of-life-hrqol-76ea6) |
| Metadata | [Link](https://data.cdc.gov/api/views/xuxn-8kju) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/xuxn-8kju/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/xuxn-8kju/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | xuxn-8kju |
| Name | Behavioral Risk Factor Data: Health-Related Quality of Life (HRQOL) |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion Division of Population Health, Health-Related Quality of Life Annual trend data |
| Category | Health-Related Quality of Life |
| Tags | healthy, unhealthy, physical, mental, health, brfss |
| Created | 2015-06-03T17:04:36Z |
| Publication Date | 2015-06-04T14:24:57Z |

## Description

1993 - 2010. Centers for Disease Control and Prevention (CDC). Data are from the Behavioral Risk Factor Surveillance System (BRFSS). All respondents to the BRFSS are non-institutionalized adults, 18 years old or older. HRQOL surveillance is used to identify unmet population health needs including recognizing trends, disparities, and determinants of health in the population. HRQOL surveillance data can be used to inform decision making, and program and policy development. To assure that the population is benefiting from public health programs, HRQOL surveillance data can be used for program evaluation. A compact set of HRQOL measures including a summary measure of unhealthy days have been developed and validated for population health surveillance and have been widely used since 1993.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | series tag     | locationabbr               | LocationAbbr               | text      | text        |
| Yes      | series tag     | locationdesc               | LocationDesc               | text      | text        |
| Yes      | series tag     | category                   | Category                   | text      | text        |
| Yes      | series tag     | topic                      | Topic                      | text      | text        |
| Yes      | series tag     | question                   | Question                   | text      | text        |
| Yes      | series tag     | datasource                 | DataSource                 | text      | text        |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | series tag     | data_value_std_err         | Data_Value_Std_Err         | text      | text        |
| Yes      | numeric metric | low_confidence_limit       | Low_Confidence_Limit       | number    | number      |
| Yes      | numeric metric | high_confidence_limit      | High_Confidence_Limit      | number    | number      |
| Yes      | numeric metric | sample_size                | Sample_Size                | number    | number      |
| Yes      | series tag     | break_out                  | Break_Out                  | text      | text        |
| Yes      | series tag     | break_out_category         | Break_Out_Category         | text      | text        |
| Yes      | series tag     | categoryid                 | CategoryId                 | text      | text        |
| Yes      | series tag     | topicid                    | TopicId                    | text      | text        |
| Yes      | series tag     | questionid                 | QuestionId                 | text      | text        |
| Yes      | series tag     | locationid                 | LocationId                 | text      | number      |
| Yes      | series tag     | breakoutid                 | BreakOutId                 | text      | text        |
| Yes      | series tag     | breakoutcategoryid         | BreakOutCategoryid         | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_unit,data_value_type,data_value_footnote_symbol,data_value_footnote
```

## Data Commands

```ls
series e:xuxn-8kju d:2010-01-01T00:00:00.000Z t:topic="Activity Limitation" t:locationdesc=Alabama t:locationabbr=AL t:topicid=POORHLTH t:break_out="18-24 years old" t:questionid=AL002 t:category="Health Status/Healthy Days" t:categoryid=HLT001 t:locationid=1 t:breakoutid=Age1 t:break_out_category="Age Group" t:question="Mean days of activity limitation" t:breakoutcategoryid=GPAGE t:datasource=HRQOL m:high_confidence_limit=1.5 m:sample_size=202 m:data_value=0.9 m:low_confidence_limit=0.3

series e:xuxn-8kju d:2010-01-01T00:00:00.000Z t:topic="Activity Limitation" t:locationdesc=Alabama t:locationabbr=AL t:topicid=POORHLTH t:break_out="25-34 years old" t:questionid=AL002 t:category="Health Status/Healthy Days" t:categoryid=HLT001 t:locationid=1 t:breakoutid=Age2 t:break_out_category="Age Group" t:question="Mean days of activity limitation" t:breakoutcategoryid=GPAGE t:datasource=HRQOL m:high_confidence_limit=2.7 m:sample_size=597 m:data_value=2 m:low_confidence_limit=1.3

series e:xuxn-8kju d:2010-01-01T00:00:00.000Z t:topic="Activity Limitation" t:locationdesc=Alabama t:locationabbr=AL t:topicid=POORHLTH t:break_out="35-44 years old" t:questionid=AL002 t:category="Health Status/Healthy Days" t:categoryid=HLT001 t:locationid=1 t:breakoutid=Age3 t:break_out_category="Age Group" t:question="Mean days of activity limitation" t:breakoutcategoryid=GPAGE t:datasource=HRQOL m:high_confidence_limit=2.9 m:sample_size=892 m:data_value=2.3 m:low_confidence_limit=1.8
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit t:dataTypeName=number

metric m:high_confidence_limit p:double l:High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

entity e:xuxn-8kju l:"Behavioral Risk Factor Data: Health-Related Quality of Life (HRQOL)" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion Division of Population Health, Health-Related Quality of Life Annual trend data" t:url=https://data.cdc.gov/api/views/xuxn-8kju

property e:xuxn-8kju t:meta.view v:id=xuxn-8kju v:category="Health-Related Quality of Life" v:attributionLink=http://www.cdc.gov/hrqol/surveillance.htm v:averageRating=0 v:name="Behavioral Risk Factor Data: Health-Related Quality of Life (HRQOL)" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion Division of Population Health, Health-Related Quality of Life Annual trend data"

property e:xuxn-8kju t:meta.view.license v:name="Public Domain"

property e:xuxn-8kju t:meta.view.owner v:id=xw2h-mnvs v:screenName="HRQOL Administrator" v:displayName="HRQOL Administrator"

property e:xuxn-8kju t:meta.view.tableauthor v:id=xw2h-mnvs v:screenName="HRQOL Administrator" v:roleName=publisher v:displayName="HRQOL Administrator"

property e:xuxn-8kju t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | locationabbr | locationdesc | category                   | topic               | question                         | datasource | data_value_unit | data_value_type        | data_value         | data_value_footnote_symbol | data_value_footnote | data_value_std_err | low_confidence_limit | high_confidence_limit | sample_size | break_out       | break_out_category | categoryid | topicid  | questionid | locationid | breakoutid | breakoutcategoryid | 
| ==== | ============ | ============ | ========================== | =================== | ================================ | ========== | =============== | ====================== | ================== | ========================== | =================== | ================== | ==================== | ===================== | =========== | =============== | ================== | ========== | ======== | ========== | ========== | ========== | ================== | 
| 2010 | AL           | Alabama      | Health Status/Healthy Days | Activity Limitation | Mean days of activity limitation | HRQOL      |                 | Average number of days | 0.9                |                            |                     |                    | 0.3                  | 1.5                   | 202         | 18-24 years old | Age Group          | HLT001     | POORHLTH | AL002      | 1          | Age1       | GPAGE              | 
| 2010 | AL           | Alabama      | Health Status/Healthy Days | Activity Limitation | Mean days of activity limitation | HRQOL      |                 | Average number of days | 2                  |                            |                     |                    | 1.3                  | 2.7                   | 597         | 25-34 years old | Age Group          | HLT001     | POORHLTH | AL002      | 1          | Age2       | GPAGE              | 
| 2010 | AL           | Alabama      | Health Status/Healthy Days | Activity Limitation | Mean days of activity limitation | HRQOL      |                 | Average number of days | 2.2999999999999998 |                            |                     |                    | 1.8                  | 2.9                   | 892         | 35-44 years old | Age Group          | HLT001     | POORHLTH | AL002      | 1          | Age3       | GPAGE              | 
| 2010 | AL           | Alabama      | Health Status/Healthy Days | Activity Limitation | Mean days of activity limitation | HRQOL      |                 | Average number of days | 4.2                |                            |                     |                    | 3.6                  | 4.9000000000000004    | 1352        | 45-54 years old | Age Group          | HLT001     | POORHLTH | AL002      | 1          | Age4       | GPAGE              | 
| 2010 | AL           | Alabama      | Health Status/Healthy Days | Activity Limitation | Mean days of activity limitation | HRQOL      |                 | Average number of days | 4                  |                            |                     |                    | 3.4                  | 4.5999999999999996    | 1621        | 55-64 years old | Age Group          | HLT001     | POORHLTH | AL002      | 1          | Age5       | GPAGE              | 
| 2010 | AL           | Alabama      | Health Status/Healthy Days | Activity Limitation | Mean days of activity limitation | HRQOL      |                 | Average number of days | 3.4                |                            |                     |                    | 2.7                  | 4                     | 1477        | 65-74 years old | Age Group          | HLT001     | POORHLTH | AL002      | 1          | Age6       | GPAGE              | 
| 2010 | AL           | Alabama      | Health Status/Healthy Days | Activity Limitation | Mean days of activity limitation | HRQOL      |                 | Average number of days | 2.7                |                            |                     |                    | 2.1                  | 3.4                   | 1008        | 75+             | Age Group          | HLT001     | POORHLTH | AL002      | 1          | Age7       | GPAGE              | 
| 2010 | AL           | Alabama      | Health Status/Healthy Days | Activity Limitation | Mean days of activity limitation | HRQOL      |                 | Average number of days | 3.6                |                            |                     |                    | 3.2                  | 3.9                   | 4868        | Female          | Gender             | HLT001     | POORHLTH | AL002      | 1          | GEN3       | GPSEX              | 
| 2010 | AL           | Alabama      | Health Status/Healthy Days | Activity Limitation | Mean days of activity limitation | HRQOL      |                 | Average number of days | 2.5                |                            |                     |                    | 2.1                  | 2.9                   | 2281        | Male            | Gender             | HLT001     | POORHLTH | AL002      | 1          | GEN2       | GPSEX              | 
| 2010 | AL           | Alabama      | Health Status/Healthy Days | Activity Limitation | Mean days of activity limitation | HRQOL      |                 | Average number of days | 3.1                |                            |                     |                    | 2.8                  | 3.4                   | 7149        | Overall         | Overall            | HLT001     | POORHLTH | AL002      | 1          | GEN1       | GPOVER             | 
```