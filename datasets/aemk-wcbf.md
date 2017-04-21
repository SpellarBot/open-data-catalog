# NOHSS Adult Indicators - 2010 And Prior BRFSS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nohss-adult-indicators-2010-and-prior-brfss-eb247) |
| Metadata | [Link](https://data.cdc.gov/api/views/aemk-wcbf) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/aemk-wcbf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/aemk-wcbf/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | aemk-wcbf |
| Name | NOHSS Adult Indicators - 2010 And Prior BRFSS |
| Category | Oral Health |
| Tags | adults, dental visits, dental cleaning, tooth loss, access to care |
| Created | 2016-11-07T12:27:04Z |
| Publication Date | 2016-11-07T12:34:11Z |

## Description

Data from BRFSS for indicators of adult oral health for 1999 and even years from 2002 through 2010. National estimates are represented by the median prevalence among 50 states and the District of Columbia data. Estimates are prepared from the BRFSS public use data sets. Estimates in this file are not age adjusted, and may differ slightly from estimates available from the BRFSS web site or Chronic Disease Indicators due to small differences in definition, age adjustment or rounding. For more information, see: http://www.cdc.gov/oralhealthdata/overview/Adult_Indicators.html

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
| Yes      | series tag     | locationid                 | LocationID                 | text      | number      |
| Yes      | numeric metric | sortusfirst                | SortUSFirst                | number    | number      |
| Yes      | series tag     | break_out_category         | Break_Out_Category         | text      | text        |
| Yes      | series tag     | break_out_id               | Break_Out_ID               | text      | text        |
| Yes      | series tag     | sortbreakoutid             | SortBreakOutID             | text      | number      |
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
series e:aemk-wcbf d:2010-01-01T00:00:00.000Z t:response=Yes t:locationabbr=AL t:locationdesc=Alabama t:indicator="Adults aged 18+ who have visited a dentist or dental clinic in the past year" t:category=Adult t:locationid=1 t:indicatorid=ADT1_1 t:break_out_category=None t:sortbreakoutid=1 t:datasource=BRFSS m:sortusfirst=2 m:samplesize=4606 m:high_confidence_interval=64.7 m:data_value=63 m:low_confidence_interval=61.3

series e:aemk-wcbf d:2010-01-01T00:00:00.000Z t:response=No t:locationabbr=AL t:locationdesc=Alabama t:indicator="Adults aged 18+ who have visited a dentist or dental clinic in the past year" t:category=Adult t:locationid=1 t:indicatorid=ADT1_1 t:break_out_category=None t:sortbreakoutid=1 t:datasource=BRFSS m:sortusfirst=2 m:samplesize=2904 m:high_confidence_interval=38.7 m:data_value=37 m:low_confidence_interval=35.3

series e:aemk-wcbf d:2010-01-01T00:00:00.000Z t:response=Yes t:break_out_id=1GEN t:locationabbr=AL t:locationdesc=Alabama t:indicator="Adults aged 18+ who have visited a dentist or dental clinic in the past year" t:category=Adult t:locationid=1 t:indicatorid=ADT1_1 t:break_out_category=Gender t:sortbreakoutid=2 t:break_out=Female t:datasource=BRFSS m:sortusfirst=2 m:samplesize=3190 m:high_confidence_interval=66.1 m:data_value=64.2 m:low_confidence_interval=62.3
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value t:dataTypeName=number

metric m:high_confidence_interval p:double l:High_Confidence_Interval t:dataTypeName=number

metric m:low_confidence_interval p:float l:Low_Confidence_Interval t:dataTypeName=number

metric m:samplesize p:integer l:SampleSize t:dataTypeName=number

metric m:sortusfirst p:integer l:SortUSFirst t:dataTypeName=number

entity e:aemk-wcbf l:"NOHSS Adult Indicators - 2010 And Prior BRFSS" t:url=https://data.cdc.gov/api/views/aemk-wcbf

property e:aemk-wcbf t:meta.view v:id=aemk-wcbf v:category="Oral Health" v:averageRating=0 v:name="NOHSS Adult Indicators - 2010 And Prior BRFSS"

property e:aemk-wcbf t:meta.view.license v:name="Public Domain"

property e:aemk-wcbf t:meta.view.owner v:id=fjjr-gap9 v:screenName="The Su" v:lastNotificationSeenAt=1492539263 v:displayName="The Su"

property e:aemk-wcbf t:meta.view.tableauthor v:id=fjjr-gap9 v:screenName="The Su" v:roleName=administrator v:lastNotificationSeenAt=1492539263 v:displayName="The Su"

property e:aemk-wcbf t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | locationabbr | locationdesc | category | indicator                                                                    | response | datasource | data_value_unit | data_value_type | data_value | data_value_footnote_symbol | data_value_footnote | high_confidence_interval | low_confidence_interval | samplesize | break_out | locationid | sortusfirst | break_out_category | break_out_id | sortbreakoutid | indicatorid | 
| ==== | ============ | ============ | ======== | ============================================================================ | ======== | ========== | =============== | =============== | ========== | ========================== | =================== | ======================== | ======================= | ========== | ========= | ========== | =========== | ================== | ============ | ============== | =========== | 
| 2010 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | Yes      | BRFSS      | %               | Percentage      | 63         |                            |                     | 64.7                     | 61.3                    | 4606       |           | 1          | 2           | None               |              | 1              | ADT1_1      | 
| 2010 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | No       | BRFSS      | %               | Percentage      | 37         |                            |                     | 38.7                     | 35.3                    | 2904       |           | 1          | 2           | None               |              | 1              | ADT1_1      | 
| 2010 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | Yes      | BRFSS      | %               | Percentage      | 64.2       |                            |                     | 66.1                     | 62.3                    | 3190       | Female    | 1          | 2           | Gender             | 1GEN         | 2              | ADT1_1      | 
| 2010 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | No       | BRFSS      | %               | Percentage      | 35.8       |                            |                     | 37.7                     | 33.9                    | 1962       | Female    | 1          | 2           | Gender             | 1GEN         | 2              | ADT1_1      | 
| 2010 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | Yes      | BRFSS      | %               | Percentage      | 61.6       |                            |                     | 64.4                     | 58.8                    | 1416       | Male      | 1          | 2           | Gender             | 2GEN         | 3              | ADT1_1      | 
| 2010 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | No       | BRFSS      | %               | Percentage      | 38.4       |                            |                     | 41.2                     | 35.6                    | 942        | Male      | 1          | 2           | Gender             | 2GEN         | 3              | ADT1_1      | 
| 2010 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | Yes      | BRFSS      | %               | Percentage      | 75.4       |                            |                     | 83.5                     | 67.3                    | 144        | 18?24     | 1          | 2           | Age                | 1AGE         | 4              | ADT1_1      | 
| 2010 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | No       | BRFSS      | %               | Percentage      | 24.6       |                            |                     | 32.7                     | 16.5                    | 61         | 18?24     | 1          | 2           | Age                | 1AGE         | 4              | ADT1_1      | 
| 2010 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | Yes      | BRFSS      | %               | Percentage      | 53.7       |                            |                     | 59.3                     | 48.1                    | 349        | 25?34     | 1          | 2           | Age                | 2AGE         | 5              | ADT1_1      | 
| 2010 | AL           | Alabama      | Adult    | Adults aged 18+ who have visited a dentist or dental clinic in the past year | No       | BRFSS      | %               | Percentage      | 46.3       |                            |                     | 51.9                     | 40.7                    | 253        | 25?34     | 1          | 2           | Age                | 2AGE         | 5              | ADT1_1      | 
```