# NOHSS Adult Indicators

## Dataset

* [Dataset URL](https://data.cdc.gov/api/views/jz6n-v26y/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/nohss-adult-indicators)
* Id = jz6n-v26y
* Name = NOHSS Adult Indicators
* Attribution = Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Oral Health
* Attribution Link = http://www.cdc.gov/oralhealth/
* Category = Oral Health
* Tags = [division of oral health, oral health, adult, adults, dentist, dental care, dental visits, dental cleaning, tooth loss, access to care, prevalence, surveillance, brfss, nohss]
* Created = 2015-04-22T01:28:29Z
* Publication Date = 2016-11-17T11:18:40Z
* Rows Updated = 2016-11-07T12:22:43Z

## Description

2012-2014 (even years). Data from BRFSS for indicators of adult oral health for even years from 2012 through 2014. National estimates are represented by the median prevalence among 50 states and the District of Columbia data. Estimates are prepared from the BRFSS public use data sets. Estimates in this file are not age adjusted, and may differ slightly from estimates available from the BRFSS web site or Chronic Disease Indicators due to small differences in definition, age adjustment or rounding.  For more information, see: http://www.cdc.gov/oralhealthdata/overview/Adult_Indicators.html

## Columns

```ls
| Name                       | Field Name                 | Data Type | Render Type | Schema Type    | Included | 
| ========================== | ========================== | ========= | =========== | ============== | ======== | 
| Year                       | year                       | number    | number      | time           | Yes      | 
| LocationAbbr               | locationabbr               | text      | text        | series tag     | Yes      | 
| LocationDesc               | locationdesc               | text      | text        | series tag     | Yes      | 
| Category                   | category                   | text      | text        | series tag     | Yes      | 
| Indicator                  | indicator                  | text      | text        | series tag     | Yes      | 
| Response                   | response                   | text      | text        | series tag     | Yes      | 
| Datasource                 | datasource                 | text      | text        | series tag     | Yes      | 
| Data_Value_Unit            | data_value_unit            | number    | text        |                | No       | 
| Data_Value_Type            | data_value_type            | text      | text        |                | No       | 
| Data_Value                 | data_value                 | number    | number      | numeric metric | Yes      | 
| Data_Value_Footnote_Symbol | data_value_footnote_symbol | number    | text        | numeric metric | Yes      | 
| Data_Value_Footnote        | data_value_footnote        | text      | text        |                | No       | 
| High_Confidence_Interval   | high_confidence_interval   | number    | number      | numeric metric | Yes      | 
| Low_Confidence_Interval    | low_confidence_interval    | number    | number      | numeric metric | Yes      | 
| SampleSize                 | samplesize                 | number    | number      | numeric metric | Yes      | 
| Break_Out                  | break_out                  | text      | text        | series tag     | Yes      | 
| LocationID                 | locationid                 | text      | text        | series tag     | Yes      | 
| SortUSFirst                | sortusfirst                | number    | text        | numeric metric | Yes      | 
| Break_Out_Category         | break_out_category         | text      | text        | series tag     | Yes      | 
| Break_Out_ID               | break_out_id               | text      | text        | series tag     | Yes      | 
| SortBreakOutID             | sortbreakoutid             | text      | text        | series tag     | Yes      | 
| IndicatorID                | indicatorid                | text      | text        | series tag     | Yes      | 
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

entity e:jz6n-v26y l:"NOHSS Adult Indicators" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Oral Health" t:url=https://data.cdc.gov/api/views/jz6n-v26y

property e:jz6n-v26y t:meta.view d:2017-03-03T14:15:38.682Z v:id=jz6n-v26y v:category="Oral Health" v:attributionLink=http://www.cdc.gov/oralhealth/ v:averageRating=0 v:name="NOHSS Adult Indicators" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Oral Health"

property e:jz6n-v26y t:meta.view.license d:2017-03-03T14:15:38.682Z v:name="Public Domain"

property e:jz6n-v26y t:meta.view.owner d:2017-03-03T14:15:38.682Z v:id=5ehu-79qp v:screenName="Oral Health Data Administrator" v:roleName=publisher v:displayName="Oral Health Data Administrator"

property e:jz6n-v26y t:meta.view.tableauthor d:2017-03-03T14:15:38.682Z v:id=5ehu-79qp v:screenName="Oral Health Data Administrator" v:roleName=publisher v:displayName="Oral Health Data Administrator"

property e:jz6n-v26y t:meta.view.metadata.custom_fields.common_core d:2017-03-03T14:15:38.682Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:10 v:Program_Code=009:020
```