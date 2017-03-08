# CDC PRAMStat Data for 2004

## Dataset

* [Dataset URL](https://chronicdata.cdc.gov/api/views/xyxp-dxa9/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/cdc-pramstat-data-for-2004)
* [Metadata URL](https://chronicdata.cdc.gov/api/views/xyxp-dxa9)
* Id = xyxp-dxa9
* Name = CDC PRAMStat Data for 2004
* Attribution = Centers for Disease Control and Prevention Division of Reproductive Health Pregnancy Risk Assessment Monitoring System (PRAMS)
* [Attribution Link](http://www.cdc.gov/prams/index)
* Category = Maternal & Child Health
* Tags = [abuse, alcohol use, contraception, breastfeeding, mental health, morbidity, obesity, pregnancy history, prenatal care, sleep behavior, smoke exposure, stress, tobacco use, wic, medicaid, reproduct...
* Created = 2015-03-17T18:37:35Z
* Publication Date = 2015-03-17T19:50:37Z
* Rows Updated = 2015-03-17T18:51:01Z

## Description

2004. Centers for Disease Control and Prevention (CDC). PRAMS, the Pregnancy Risk Assessment Monitoring System, is a surveillance system collecting state-specific, population-based data on maternal attitudes and experiences before, during, and shortly after pregnancy. It is a collaborative project of the Centers for Disease Control and Prevention (CDC) and state health departments. PRAMS provides data for state health officials to use to improve the health of mothers and infants. PRAMS topics include abuse, alcohol use, contraception, breastfeeding, mental health, morbidity, obesity, preconception health, pregnancy history, prenatal-care, sleep behavior, smoke exposure, stress, tobacco use, WIC, Medicaid, infant health, and unintended pregnancy. Data will be updated annually as it becomes available.

## Columns

```ls
| Name                       | Field Name                 | Data Type | Render Type | Schema Type    | Included | 
| ========================== | ========================== | ========= | =========== | ============== | ======== | 
| Year                       | year                       | number    | number      | time           | Yes      | 
| LocationAbbr               | locationabbr               | text      | text        | series tag     | Yes      | 
| LocationDesc               | locationdesc               | text      | text        | series tag     | Yes      | 
| Class                      | class                      | text      | text        | series tag     | Yes      | 
| Topic                      | topic                      | text      | text        | series tag     | Yes      | 
| Question                   | question                   | text      | text        | series tag     | Yes      | 
| DataSource                 | datasource                 | text      | text        | series tag     | Yes      | 
| Response                   | response                   | text      | text        | series tag     | Yes      | 
| Data_Value_Unit            | data_value_unit            | number    | text        |                | No       | 
| Data_Value_Type            | data_value_type            | text      | text        |                | No       | 
| Data_Value                 | data_value                 | number    | number      | numeric metric | Yes      | 
| Data_Value_Footnote_Symbol | data_value_footnote_symbol | number    | number      | numeric metric | Yes      | 
| Data_Value_Footnote        | data_value_footnote        | text      | text        |                | No       | 
| Data_Value_Std_Err         | data_value_std_err         | text      | text        | series tag     | Yes      | 
| Low_Confidence_Limit       | low_confidence_limit       | number    | number      | numeric metric | Yes      | 
| High_Confidence_Limit      | high_confidence_limit      | number    | number      | numeric metric | Yes      | 
| Sample_Size                | sample_size                | number    | number      | numeric metric | Yes      | 
| Break_Out                  | break_out                  | text      | text        | series tag     | Yes      | 
| Break_Out_Category         | break_out_category         | text      | text        | series tag     | Yes      | 
| ClassId                    | classid                    | text      | text        | series tag     | Yes      | 
| TopicId                    | topicid                    | text      | text        | series tag     | Yes      | 
| QuestionId                 | questionid                 | text      | text        | series tag     | Yes      | 
| LocationId                 | locationid                 | text      | number      | series tag     | Yes      | 
| BreakOutId                 | breakoutid                 | text      | text        | series tag     | Yes      | 
| BreakOutCategoryid         | breakoutcategoryid         | text      | text        | series tag     | Yes      | 
| ResponseId                 | responseid                 | text      | text        | series tag     | Yes      | 
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
series e:xyxp-dxa9 d:2004-01-01T00:00:00.000Z t:topic="Prenatal Care - Visits" t:locationabbr=AK t:locationdesc=Alaska t:topicid=TOP44 t:class="Control Variable" t:break_out="Age 18 - 44" t:questionid=QUO171 t:response=NO t:locationid=2 t:breakoutid=AGE1844ALL t:responseid=RES23 t:break_out_category="Maternal Age - 18 to 44 years only" t:question="Indicator of no prenatal care" t:breakoutcategoryid=BOC16 t:datasource=PRAMS t:classid=CLA1 m:data_value=99.1

series e:xyxp-dxa9 d:2004-01-01T00:00:00.000Z t:topic=Medicaid t:locationabbr=AK t:locationdesc=Alaska t:topicid=TOP12 t:class=Insurance/Medicaid/Services t:questionid=QUO17 t:locationid=2 t:breakoutid=BOC1 t:break_out_category="Birth Weight" t:question="Just before you got pregnant  were you on Medicaid? (years 2000 - 2008)" t:breakoutcategoryid=BOC1 t:datasource=PRAMS t:classid=CLA10 m:data_value_footnote_symbol=1 m:data_value=18

series e:xyxp-dxa9 d:2004-01-01T00:00:00.000Z t:topic=Medicaid t:locationabbr=AK t:locationdesc=Alaska t:topicid=TOP12 t:class=Insurance/Medicaid/Services t:break_out="LBW (<=2500g)" t:questionid=QUO17 t:response=NO t:locationid=2 t:breakoutid=BWT1 t:responseid=RES23 t:break_out_category="Birth Weight" t:question="Just before you got pregnant  were you on Medicaid? (years 2000 - 2008)" t:breakoutcategoryid=BOC1 t:datasource=PRAMS t:classid=CLA10 m:high_confidence_limit=86 m:sample_size=335 m:data_value=84.2 m:low_confidence_limit=82.1
```

## Meta Commands

```ls
metric m:data_value l:Data_Value t:dataTypeName=number

metric m:data_value_footnote_symbol p:integer l:Data_Value_Footnote_Symbol t:dataTypeName=number

metric m:low_confidence_limit l:Low_Confidence_Limit t:dataTypeName=number

metric m:high_confidence_limit l:High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

entity e:xyxp-dxa9 l:"CDC PRAMStat Data for 2004" t:attribution="Centers for Disease Control and Prevention Division of Reproductive Health Pregnancy Risk Assessment Monitoring System (PRAMS)" t:url=https://chronicdata.cdc.gov/api/views/xyxp-dxa9

property e:xyxp-dxa9 t:meta.view d:2017-03-07T23:57:45.827Z v:id=xyxp-dxa9 v:category="Maternal & Child Health" v:attributionLink=http://www.cdc.gov/prams/index v:averageRating=0 v:name="CDC PRAMStat Data for 2004" v:attribution="Centers for Disease Control and Prevention Division of Reproductive Health Pregnancy Risk Assessment Monitoring System (PRAMS)"

property e:xyxp-dxa9 t:meta.view.license d:2017-03-07T23:57:45.827Z v:name="Public Domain"

property e:xyxp-dxa9 t:meta.view.owner d:2017-03-07T23:57:45.827Z v:id=7gh3-3zr5 v:screenName="PRAMStat Administrator" v:roleName=publisher v:displayName="PRAMStat Administrator"

property e:xyxp-dxa9 t:meta.view.tableauthor d:2017-03-07T23:57:45.827Z v:id=7gh3-3zr5 v:screenName="PRAMStat Administrator" v:roleName=publisher v:displayName="PRAMStat Administrator"

property e:xyxp-dxa9 t:meta.view.metadata.custom_fields.common_core d:2017-03-07T23:57:45.827Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```