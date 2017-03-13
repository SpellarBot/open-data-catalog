# NOHSS Adult Indicators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nohss-adult-indicators-02260) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/jz6n-v26y) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/jz6n-v26y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/jz6n-v26y/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | jz6n-v26y |
| Name | NOHSS Adult Indicators |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Oral Health |
| Category | Oral Health |
| Tags | division of oral health, oral health, adult, adults, dentist, dental care, dental visits, dental cleaning, tooth loss, access to care, prevalence, surveillance, brfss, nohss |
| Created | 2015-04-22T01:28:29Z |
| Publication Date | 2016-11-17T11:18:40Z |
| Rows Updated | 2016-11-07T12:22:43Z |

## Description

2012-2014 (even years). Data from BRFSS for indicators of adult oral health for even years from 2012 through 2014. National estimates are represented by the median prevalence among 50 states and the District of Columbia data. Estimates are prepared from the BRFSS public use data sets. Estimates in this file are not age adjusted, and may differ slightly from estimates available from the BRFSS web site or Chronic Disease Indicators due to small differences in definition, age adjustment or rounding.  For more information, see: http://www.cdc.gov/oralhealthdata/overview/Adult_Indicators.html

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | series tag     | locationabbr               | LocationAbbr               | text      | text        |
| Yes      | series tag     | locationdesc               | LocationDesc               | text      | text        |
| Yes      | series tag     | category                   | Category                   | text      | text        |
| Yes      | series tag     | indicator                  | Indicator                  | text      | text        |
| Yes      | series tag     | response                   | Response                   | text      | text        |
| Yes      | series tag     | datasource                 | Datasource                 | text      | text        |
| No       |                | data_value_unit            | Data_Value_Unit            | number    | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| Yes      | numeric metric | data_value_footnote_symbol | Data_Value_Footnote_Symbol | number    | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | numeric metric | high_confidence_interval   | High_Confidence_Interval   | number    | number      |
| Yes      | numeric metric | low_confidence_interval    | Low_Confidence_Interval    | number    | number      |
| Yes      | numeric metric | samplesize                 | SampleSize                 | number    | number      |
| Yes      | series tag     | break_out                  | Break_Out                  | text      | text        |
| Yes      | series tag     | locationid                 | LocationID                 | text      | text        |
| Yes      | numeric metric | sortusfirst                | SortUSFirst                | number    | text        |
| Yes      | series tag     | break_out_category         | Break_Out_Category         | text      | text        |
| Yes      | series tag     | break_out_id               | Break_Out_ID               | text      | text        |
| Yes      | series tag     | sortbreakoutid             | SortBreakOutID             | text      | text        |
| Yes      | series tag     | indicatorid                | IndicatorID                | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_footnote,data_value_unit,data_value_type
```

## Data Commands

```ls
series e:jz6n-v26y d:2014-01-01T00:00:00.000Z t:response=Yes t:locationabbr=AL t:locationdesc=Alabama t:indicator="Adults aged 18+ who have visited a dentist or dental clinic in the past year" t:category=Adult t:locationid=1 t:indicatorid=ADT1_1 t:break_out_category=None t:sortbreakoutid=1 t:datasource=BRFSS m:sortusfirst=2 m:samplesize=5143 m:high_confidence_interval=61.5 m:data_value=60 m:low_confidence_interval=58.5

series e:jz6n-v26y d:2014-01-01T00:00:00.000Z t:response=Yes t:break_out_id=1GEN t:locationabbr=AL t:locationdesc=Alabama t:indicator="Adults aged 18+ who have visited a dentist or dental clinic in the past year" t:category=Adult t:locationid=1 t:indicatorid=ADT1_1 t:break_out_category=Gender t:sortbreakoutid=2 t:break_out=Female t:datasource=BRFSS m:sortusfirst=2 m:samplesize=3323 m:high_confidence_interval=62.9 m:data_value=61 m:low_confidence_interval=59.1

series e:jz6n-v26y d:2014-01-01T00:00:00.000Z t:response=Yes t:break_out_id=2GEN t:locationabbr=AL t:locationdesc=Alabama t:indicator="Adults aged 18+ who have visited a dentist or dental clinic in the past year" t:category=Adult t:locationid=1 t:indicatorid=ADT1_1 t:break_out_category=Gender t:sortbreakoutid=3 t:break_out=Male t:datasource=BRFSS m:sortusfirst=2 m:samplesize=1820 m:high_confidence_interval=61.3 m:data_value=58.9 m:low_confidence_interval=56.5
```

## Meta Commands

```ls
metric m:data_value l:Data_Value t:dataTypeName=number

metric m:high_confidence_interval l:High_Confidence_Interval t:dataTypeName=number

metric m:low_confidence_interval l:Low_Confidence_Interval t:dataTypeName=number

metric m:samplesize p:integer l:SampleSize t:dataTypeName=number

metric m:sortusfirst p:integer l:SortUSFirst t:dataTypeName=number

entity e:jz6n-v26y l:"NOHSS Adult Indicators" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Oral Health" t:url=https://chronicdata.cdc.gov/api/views/jz6n-v26y

property e:jz6n-v26y t:meta.view v:id=jz6n-v26y v:category="Oral Health" v:attributionLink=http://www.cdc.gov/oralhealth/ v:averageRating=0 v:name="NOHSS Adult Indicators" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Oral Health"

property e:jz6n-v26y t:meta.view.license v:name="Public Domain"

property e:jz6n-v26y t:meta.view.owner v:id=5ehu-79qp v:screenName="Oral Health Data Administrator" v:roleName=publisher v:displayName="Oral Health Data Administrator"

property e:jz6n-v26y t:meta.view.tableauthor v:id=5ehu-79qp v:screenName="Oral Health Data Administrator" v:roleName=publisher v:displayName="Oral Health Data Administrator"

property e:jz6n-v26y t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:10 v:Program_Code=009:020
```