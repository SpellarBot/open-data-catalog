# National Health Interview Survey (NHIS) - National Cardiovascular Disease Surveillance Data

## Dataset

* [Dataset URL](https://chronicdata.cdc.gov/api/views/fwns-azgu/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/national-health-interview-survey-nhis-national-cardiovascular-disease-surveillance-data)
* [Metadata URL](https://chronicdata.cdc.gov/api/views/fwns-azgu)
* Id = fwns-azgu
* Name = National Health Interview Survey (NHIS) - National Cardiovascular Disease Surveillance Data
* Attribution = Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Health Disease and Stroke Prevention (DHDSP), National Cardiovascular Di...
* [Attribution Link](http://www.cdc.gov/dhdsp/ncvdss/index.htm)
* Category = Heart Disease & Stroke Prevention
* Tags = [cardiovascular disease, stroke, coronary heart disease, hypertension, risk factors]
* Created = 2016-06-24T14:17:25Z
* Publication Date = 2017-01-04T21:47:52Z
* Rows Updated = 2016-12-08T18:45:26Z

## Description

2001 to 2014. The National Health Interview Survey (NHIS) has monitored the health of the nation since 1957. NHIS data on a broad range of health topics are collected through personal household interviews.  Data for this dataset has been computed by personnel in CDC's Division for Heart Disease and Stroke Prevention (DHDSP).  This dataset is one of the datasets provided by National Cardiovascular Disease Surveillance System. The system is designed to integrate multiple indicators from many data sources to provide a comprehensive picture of the public health burden of CVDs and associated risk factors in the United States. The data are organized by location (national, state, county, and selected sites) and indicator, and they include CVDs (e.g., heart failure) and risk factors (e.g., hypertension). The data can be plotted as trends and stratified by age group, sex, and race/ethnicity.

## Columns

```ls
| Name                       | Field Name                 | Data Type | Render Type | Schema Type    | Included | 
| ========================== | ========================== | ========= | =========== | ============== | ======== | 
| Year                       | year                       | number    | number      | time           | Yes      | 
| LocationAbbr               | locationabbr               | text      | text        | series tag     | Yes      | 
| LocationDesc               | locationdesc               | text      | text        | series tag     | Yes      | 
| DataSource                 | datasource                 | text      | text        | series tag     | Yes      | 
| PriorityArea1              | priorityarea1              | text      | text        | series tag     | Yes      | 
| PriorityArea2              | priorityarea2              | text      | text        | series tag     | Yes      | 
| PriorityArea3              | priorityarea3              | text      | text        | series tag     | Yes      | 
| PriorityArea4              | priorityarea4              | number    | text        | numeric metric | Yes      | 
| Category                   | category                   | text      | text        | series tag     | Yes      | 
| Topic                      | topic                      | text      | text        | series tag     | Yes      | 
| Indicator                  | indicator                  | text      | text        | series tag     | Yes      | 
| Break_Out_Category         | break_out_category         | text      | text        | series tag     | Yes      | 
| Break_Out                  | break_out                  | text      | text        | series tag     | Yes      | 
| Data_Value_Type            | data_value_type            | text      | text        |                | No       | 
| Data_Value_Unit            | data_value_unit            | number    | text        |                | No       | 
| Data_Value                 | data_value                 | number    | number      | numeric metric | Yes      | 
| Data_Value_Footnote_Symbol | data_value_footnote_symbol | number    | text        | numeric metric | Yes      | 
| Data_Value_Footnote        | data_value_footnote        | text      | text        |                | No       | 
| Confidence_limit_Low       | confidence_limit_low       | number    | number      | numeric metric | Yes      | 
| Confidence_limit_High      | confidence_limit_high      | number    | number      | numeric metric | Yes      | 
| CategoryId                 | categoryid                 | text      | text        | series tag     | Yes      | 
| TopicId                    | topicid                    | text      | text        | series tag     | Yes      | 
| IndicatorID                | indicatorid                | text      | text        | series tag     | Yes      | 
| BreakOutCategoryId         | breakoutcategoryid         | text      | text        | series tag     | Yes      | 
| BreakOutId                 | breakoutid                 | text      | text        | series tag     | Yes      | 
| LocationID                 | locationid                 | text      | number      | series tag     | Yes      | 
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = data_value_footnote,data_value_unit,data_value_type
Annotation Fields = 
```

## Data Commands

```ls
series e:fwns-azgu d:2000-01-01T00:00:00.000Z t:topic="Coronary Heart Disease" t:indicator="Prevalence of coronary heart disease among US adults (18+) (Percentage); NHIS" t:locationdesc=Midwest t:locationabbr=MDW t:topicid=T4 t:priorityarea3=None t:priorityarea4=None t:priorityarea1="Million Hearts" t:priorityarea2=None t:break_out="Non-Hispanic White" t:categoryid=C1 t:category="Cardiovascular Diseases" t:locationid=103 t:indicatorid=NS001 t:breakoutid=RAC01 t:break_out_category=Race t:breakoutcategoryid=BOC04 t:datasource=NHIS m:confidence_limit_low=3.3 m:data_value=3.9 m:confidence_limit_high=4.5

series e:fwns-azgu d:2000-01-01T00:00:00.000Z t:topic="Coronary Heart Disease" t:indicator="Prevalence of coronary heart disease among US adults (18+) (Percentage); NHIS" t:locationdesc=Midwest t:locationabbr=MDW t:topicid=T4 t:priorityarea3=None t:priorityarea4=None t:priorityarea1="Million Hearts" t:priorityarea2=None t:break_out=Female t:categoryid=C1 t:category="Cardiovascular Diseases" t:locationid=103 t:indicatorid=NS001 t:breakoutid=GEN02 t:break_out_category=Gender t:breakoutcategoryid=BOC02 t:datasource=NHIS m:confidence_limit_low=2.2 m:data_value=2.7 m:confidence_limit_high=3.4

series e:fwns-azgu d:2000-01-01T00:00:00.000Z t:topic="Coronary Heart Disease" t:indicator="Prevalence of coronary heart disease among US adults (18+) (Percentage); NHIS" t:locationdesc=Midwest t:locationabbr=MDW t:topicid=T4 t:priorityarea3=None t:priorityarea4=None t:priorityarea1="Million Hearts" t:priorityarea2=None t:break_out=Hispanic t:categoryid=C1 t:category="Cardiovascular Diseases" t:locationid=103 t:indicatorid=NS001 t:breakoutid=RAC04 t:break_out_category=Race t:breakoutcategoryid=BOC04 t:datasource=NHIS m:confidence_limit_low=0.5 m:data_value=1.1 m:confidence_limit_high=2.8
```

## Meta Commands

```ls
metric m:data_value l:Data_Value d:"Data value (point estimate)" t:dataTypeName=number

metric m:confidence_limit_low p:integer l:Confidence_limit_Low d:"95% confidence interval lower bound" t:dataTypeName=number

metric m:confidence_limit_high l:Confidence_limit_High d:"95% confidence interval upper bound" t:dataTypeName=number

entity e:fwns-azgu l:"National Health Interview Survey (NHIS) - National Cardiovascular Disease Surveillance Data" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Health Disease and Stroke Prevention (DHDSP), National Cardiovascular Disease Surveillance System" t:url=https://chronicdata.cdc.gov/api/views/fwns-azgu

property e:fwns-azgu t:meta.view d:2017-03-08T02:30:13.977Z v:id=fwns-azgu v:category="Heart Disease & Stroke Prevention" v:attributionLink=http://www.cdc.gov/dhdsp/ncvdss/index.htm v:averageRating=0 v:name="National Health Interview Survey (NHIS) - National Cardiovascular Disease Surveillance Data" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Health Disease and Stroke Prevention (DHDSP), National Cardiovascular Disease Surveillance System"

property e:fwns-azgu t:meta.view.license d:2017-03-08T02:30:13.977Z v:name="Public Domain"

property e:fwns-azgu t:meta.view.owner d:2017-03-08T02:30:13.977Z v:id=6thr-55du v:screenName=Angelique v:roleName=publisher v:displayName=Angelique

property e:fwns-azgu t:meta.view.tableauthor d:2017-03-08T02:30:13.977Z v:id=6thr-55du v:screenName=Angelique v:roleName=publisher v:displayName=Angelique

property e:fwns-azgu t:meta.view.metadata.custom_fields.common_core d:2017-03-08T02:30:13.977Z v:Publisher="CDC Info" v:Contact_Email=cdcinfo@cdc.gov v:Public_Access_Level=Public v:Contact_Name="CDC Info" v:Bureau_Code=009:20 v:Program_Code=009:020
```