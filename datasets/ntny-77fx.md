# Healthcare Cost and Utilization Project (HCUP) - National Inpatient Sample

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/healthcare-cost-and-utilization-project-hcup-national-inpatient-sample) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/ntny-77fx) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/ntny-77fx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/ntny-77fx/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | ntny-77fx |
| Name | Healthcare Cost and Utilization Project (HCUP) - National Inpatient Sample |
| Attribution | Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Heart Disease and Stroke Prevention (DHDSP), National Cardiovascular Disea... |
| Category | Heart Disease & Stroke Prevention |
| Tags | cardiovascular, stroke, coronary heart disease, myocardial infarction, hospitalizations |
| Created | 2016-06-23T23:26:57Z |
| Publication Date | 2017-01-04T21:44:43Z |
| Rows Updated | 2017-01-03T20:29:35Z |

## Description

2001 to 2013.  The National (Nationwide) Inpatient Sample (NIS) is part of a family of databases and software tools developed for the Healthcare Cost and Utilization Project (HCUP). The NIS is the largest publicly available all-payer inpatient health care database in the United States, yielding national estimates of hospital inpatient stays. Unweighted, it contains data from more than 7 million hospital stays each year. Weighted, it estimates more than 35 million hospitalizations nationally. Indicators from this data source have been computed by personnel in CDC's Division for Heart Disease and Stroke Prevention (DHDSP). This dataset is one of the datasets provided by National Cardiovascular Disease Surveillance System. The system is designed to integrate multiple indicators from many data sources to provide a comprehensive picture of the public health burden of CVDs and associated risk factors in the United States. The data are organized by location (national, state, county, and selected sites) and indicator, and they include CVDs (e.g., heart failure). The data can be plotted as trends and stratified by age group, sex, and race/ethnicity.

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
series e:ntny-77fx d:2004-01-01T00:00:00.000Z t:topic="Major Cardiovascular Disease" t:indicator="Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US adults (18+) (Percentage); HCUP-NIS" t:locationdesc="United States" t:locationabbr=US t:topicid=T1 t:priorityarea3=None t:priorityarea4=None t:priorityarea1=None t:priorityarea2=None t:break_out=Male t:categoryid=C1 t:category="Cardiovascular Diseases" t:locationid=00 t:indicatorid=HC101 t:breakoutid=GEN01 t:break_out_category=Gender t:breakoutcategoryid=BOC02 t:datasource=HCUP m:confidence_limit_low=22.4 m:data_value=23.1 m:confidence_limit_high=23.9

series e:ntny-77fx d:2004-01-01T00:00:00.000Z t:topic="Major Cardiovascular Disease" t:indicator="Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US adults (18+) (Percentage); HCUP-NIS" t:locationdesc="United States" t:locationabbr=US t:topicid=T1 t:priorityarea3=None t:priorityarea4=None t:priorityarea1=None t:priorityarea2=None t:break_out=35+ t:categoryid=C1 t:category="Cardiovascular Diseases" t:locationid=00 t:indicatorid=HC101 t:breakoutid=AGE07 t:break_out_category=Age t:breakoutcategoryid=BOC03 t:datasource=HCUP m:confidence_limit_low=20.5 m:data_value=21.1 m:confidence_limit_high=21.6

series e:ntny-77fx d:2004-01-01T00:00:00.000Z t:topic="Major Cardiovascular Disease" t:indicator="Prevalence of major cardiovascular disease hospitalizations among all hospitalizations, US adults (18+) (Percentage); HCUP-NIS" t:locationdesc="United States" t:locationabbr=US t:topicid=T1 t:priorityarea3=None t:priorityarea4=None t:priorityarea1=None t:priorityarea2=None t:break_out=Female t:categoryid=C1 t:category="Cardiovascular Diseases" t:locationid=00 t:indicatorid=HC101 t:breakoutid=GEN02 t:break_out_category=Gender t:breakoutcategoryid=BOC02 t:datasource=HCUP m:confidence_limit_low=12.8 m:data_value=13.2 m:confidence_limit_high=13.6
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value d:"Data value (point estimate)" t:dataTypeName=number

metric m:confidence_limit_low p:float l:Confidence_limit_Low d:"95% confidence interval lower bound" t:dataTypeName=number

metric m:confidence_limit_high p:float l:Confidence_limit_High d:"95% confidence interval upper bound" t:dataTypeName=number

entity e:ntny-77fx l:"Healthcare Cost and Utilization Project (HCUP) - National Inpatient Sample" t:attribution="Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Heart Disease and Stroke Prevention (DHDSP), National Cardiovascular Disease Surveillance System" t:url=https://chronicdata.cdc.gov/api/views/ntny-77fx

property e:ntny-77fx t:meta.view v:id=ntny-77fx v:category="Heart Disease & Stroke Prevention" v:attributionLink=http://www.cdc.gov/dhdsp/ncvdss/index.htm v:averageRating=0 v:name="Healthcare Cost and Utilization Project (HCUP) - National Inpatient Sample" v:attribution="Centers for Disease Control and Prevention National Center for Chronic Disease Prevention and Health Promotion Division of Heart Disease and Stroke Prevention (DHDSP), National Cardiovascular Disease Surveillance System"

property e:ntny-77fx t:meta.view.license v:name="Public Domain"

property e:ntny-77fx t:meta.view.owner v:id=6thr-55du v:screenName=Angelique v:displayName=Angelique

property e:ntny-77fx t:meta.view.tableauthor v:id=6thr-55du v:screenName=Angelique v:roleName=publisher v:displayName=Angelique

property e:ntny-77fx t:meta.view.metadata.custom_fields.common_core v:Publisher="CDC INFO" v:Contact_Email=cdcinfo@cdc.gov v:Public_Access_Level="Public Domain" v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:029
```