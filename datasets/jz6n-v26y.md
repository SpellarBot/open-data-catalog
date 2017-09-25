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
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
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
Excluded Fields = data_value_unit,data_value_type,data_value_footnote_symbol,data_value_footnote
```

## Data Commands

```ls
series e:jz6n-v26y d:2014-01-01T00:00:00.000Z t:indicator="Adults aged 18+ who have visited a dentist or dental clinic in the past year" t:indicatorid=ADT1_1 t:break_out_category=None t:response=Yes t:datasource=BRFSS t:locationid=1 t:sortbreakoutid=1 t:locationabbr=AL t:locationdesc=Alabama t:category=Adult m:low_confidence_interval=58.5 m:data_value=60 m:samplesize=5143 m:high_confidence_interval=61.5 m:sortusfirst=2

series e:jz6n-v26y d:2014-01-01T00:00:00.000Z t:indicator="Adults aged 18+ who have visited a dentist or dental clinic in the past year" t:indicatorid=ADT1_1 t:break_out_id=1GEN t:break_out_category=Gender t:response=Yes t:datasource=BRFSS t:locationid=1 t:sortbreakoutid=2 t:locationabbr=AL t:break_out=Female t:locationdesc=Alabama t:category=Adult m:low_confidence_interval=59.1 m:data_value=61 m:samplesize=3323 m:high_confidence_interval=62.9 m:sortusfirst=2

series e:jz6n-v26y d:2014-01-01T00:00:00.000Z t:indicator="Adults aged 18+ who have visited a dentist or dental clinic in the past year" t:indicatorid=ADT1_1 t:break_out_id=2GEN t:break_out_category=Gender t:response=Yes t:datasource=BRFSS t:locationid=1 t:sortbreakoutid=3 t:locationabbr=AL t:break_out=Male t:locationdesc=Alabama t:category=Adult m:low_confidence_interval=56.5 m:data_value=58.9 m:samplesize=1820 m:high_confidence_interval=61.3 m:sortusfirst=2
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value t:dataTypeName=number

metric m:high_confidence_interval p:float l:High_Confidence_Interval t:dataTypeName=number

metric m:low_confidence_interval p:float l:Low_Confidence_Interval t:dataTypeName=number

metric m:samplesize p:integer l:SampleSize t:dataTypeName=number

metric m:sortusfirst p:integer l:SortUSFirst t:dataTypeName=number

entity e:jz6n-v26y l:"NOHSS Adult Indicators" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Oral Health" t:url=https://chronicdata.cdc.gov/api/views/jz6n-v26y

property e:jz6n-v26y t:meta.view d:2017-09-25T07:25:48.150Z v:averageRating=0 v:name="NOHSS Adult Indicators" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Oral Health" v:attributionLink=http://www.cdc.gov/oralhealth/ v:id=jz6n-v26y v:category="Oral Health"

property e:jz6n-v26y t:meta.view.license d:2017-09-25T07:25:48.150Z v:name="Public Domain"

property e:jz6n-v26y t:meta.view.owner d:2017-09-25T07:25:48.150Z v:displayName="Oral Health Data Administrator" v:id=5ehu-79qp v:screenName="Oral Health Data Administrator"

property e:jz6n-v26y t:meta.view.tableauthor d:2017-09-25T07:25:48.150Z v:displayName="Oral Health Data Administrator" v:roleName=publisher v:id=5ehu-79qp v:screenName="Oral Health Data Administrator"

property e:jz6n-v26y t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:25:48.150Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Program_Code=009:020 v:Publisher="Centers for Disease Control and Prevention" v:Bureau_Code=009:20 v:Public_Access_Level="Public Domain"
```

## Top Records

```ls
| year | locationabbr | locationdesc | category | indicator                                                                    | response | datasource | data_value_unit | data_value_type | data_value | data_value_footnote_symbol | data_value_footnote | high_confidence_interval | low_confidence_interval | samplesize | break_out | locationid | sortusfirst | break_out_category | break_out_id | sortbreakoutid | indicatorid | 
| ==== | ============ | ============ | ======== | ============================================================================ | ======== | ========== | =============== | =============== | ========== | ========================== | =================== | ======================== | ======================= | ========== | ========= | ========== | =========== | ================== | ============ | ============== | =========== | 
| 2014 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | Yes      | BRFSS      | %               | Percentage      | 60.0       |                            |                     | 61.5                     | 58.5                    | 5143       |           | 1          | 2           | None               |              | 1              | ADT1_1      | 
| 2014 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | Yes      | BRFSS      | %               | Percentage      | 61.0       |                            |                     | 62.9                     | 59.1                    | 3323       | Female    | 1          | 2           | Gender             | 1GEN         | 2              | ADT1_1      | 
| 2014 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | Yes      | BRFSS      | %               | Percentage      | 58.9       |                            |                     | 61.3                     | 56.5                    | 1820       | Male      | 1          | 2           | Gender             | 2GEN         | 3              | ADT1_1      | 
| 2014 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | Yes      | BRFSS      | %               | Percentage      | 66.0       |                            |                     | 71.3                     | 60.7                    | 280        | 18-24     | 1          | 2           | Age                | 1AGE         | 4              | ADT1_1      | 
| 2014 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | Yes      | BRFSS      | %               | Percentage      | 57.8       |                            |                     | 62.3                     | 53.3                    | 435        | 25-34     | 1          | 2           | Age                | 2AGE         | 5              | ADT1_1      | 
| 2014 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | Yes      | BRFSS      | %               | Percentage      | 61.4       |                            |                     | 65.4                     | 57.4                    | 558        | 35-44     | 1          | 2           | Age                | 3AGE         | 6              | ADT1_1      | 
| 2014 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | Yes      | BRFSS      | %               | Percentage      | 59.5       |                            |                     | 62.8                     | 56.2                    | 841        | 45-54     | 1          | 2           | Age                | 4AGE         | 7              | ADT1_1      | 
| 2014 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | Yes      | BRFSS      | %               | Percentage      | 59.4       |                            |                     | 62.4                     | 56.4                    | 1194       | 55-64     | 1          | 2           | Age                | 5AGE         | 8              | ADT1_1      | 
| 2014 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | Yes      | BRFSS      | %               | Percentage      | 57.9       |                            |                     | 60.3                     | 55.5                    | 1835       | 65+       | 1          | 2           | Age                | 6AGE         | 9              | ADT1_1      | 
| 2014 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | Yes      | BRFSS      | %               | Percentage      | 62.5       |                            |                     | 64.2                     | 60.8                    | 3852       | White     | 1          | 2           | Race               | 1RACE        | 10             | ADT1_1      | 
```