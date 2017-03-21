# CDC PRAMStat Data for 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-pramstat-data-for-2011) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/ese6-rqpq) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/ese6-rqpq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/ese6-rqpq/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | ese6-rqpq |
| Name | CDC PRAMStat Data for 2011 |
| Attribution | Centers for Disease Control and Prevention Division of Reproductive Health Pregnancy Risk Assessment Monitoring System (PRAMS) |
| Category | Maternal & Child Health |
| Tags | abuse, alcohol use, contraception, breastfeeding, mental health, morbidity, obesity, pregnancy history, prenatal care, sleep behavior, smoke exposure, stress, tobacco use, wic, medicaid, reproduct... |
| Created | 2015-03-16T13:46:10Z |
| Publication Date | 2015-03-16T14:03:18Z |
| Rows Updated | 2015-03-16T13:58:43Z |

## Description

2011.  Centers for Disease Control and Prevention (CDC).  PRAMS, the Pregnancy Risk Assessment Monitoring System, is a surveillance system collecting state-specific, population-based data on maternal attitudes and experiences before, during, and shortly after pregnancy. It is a collaborative project of the Centers for Disease Control and Prevention (CDC) and state health departments.  PRAMS provides data for state health officials to use to improve the health of mothers and infants. PRAMS topics include abuse, alcohol use, contraception, breastfeeding, mental health, morbidity, obesity, preconception health, pregnancy history, prenatal-care, sleep behavior, smoke exposure, stress, tobacco use, WIC, Medicaid, infant health, and unintended pregnancy.
Data will be updated annually as it becomes available.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | series tag     | locationabbr               | LocationAbbr               | text      | text        |
| Yes      | series tag     | locationdesc               | LocationDesc               | text      | text        |
| Yes      | series tag     | class                      | Class                      | text      | text        |
| Yes      | series tag     | topic                      | Topic                      | text      | text        |
| Yes      | series tag     | question                   | Question                   | text      | text        |
| Yes      | series tag     | datasource                 | DataSource                 | text      | text        |
| Yes      | series tag     | response                   | Response                   | text      | text        |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | number    | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | series tag     | data_value_std_err         | Data_Value_Std_Err         | text      | text        |
| Yes      | numeric metric | low_confidence_limit       | Low_Confidence_Limit       | number    | number      |
| Yes      | numeric metric | high_confidence_limit      | High_Confidence_Limit      | number    | number      |
| Yes      | numeric metric | sample_size                | Sample_Size                | number    | number      |
| Yes      | series tag     | break_out                  | Break_Out                  | text      | text        |
| Yes      | series tag     | break_out_category         | Break_Out_Category         | text      | text        |
| Yes      | series tag     | classid                    | ClassId                    | text      | text        |
| Yes      | series tag     | topicid                    | TopicId                    | text      | text        |
| Yes      | series tag     | questionid                 | QuestionId                 | text      | text        |
| Yes      | series tag     | locationid                 | LocationId                 | text      | number      |
| Yes      | series tag     | breakoutid                 | BreakOutId                 | text      | text        |
| Yes      | series tag     | breakoutcategoryid         | BreakOutCategoryid         | text      | text        |
| Yes      | series tag     | responseid                 | ResponseId                 | text      | text        |
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
series e:ese6-rqpq d:2011-01-01T00:00:00.000Z t:topic="Prenatal Care - Visits" t:locationabbr=AR t:locationdesc=Arkansas t:topicid=TOP44 t:class="Control Variable" t:break_out="Age 18 - 44" t:questionid=QUO171 t:response=NO t:locationid=5 t:breakoutid=AGE1844ALL t:responseid=RES23 t:break_out_category="Maternal Age - 18 to 44 years only" t:question="Indicator of no prenatal care" t:breakoutcategoryid=BOC16 t:datasource=PRAMS t:classid=CLA1 m:data_value=99.1

series e:ese6-rqpq d:2011-01-01T00:00:00.000Z t:topic=Medicaid t:locationabbr=AR t:locationdesc=Arkansas t:topicid=TOP12 t:class=Insurance/Medicaid/Services t:questionid=QUO25 t:locationid=5 t:breakoutid=BOC1 t:break_out_category="Birth Weight" t:question="Indicator of whether mother received Medicaid coverage for prenatal care." t:breakoutcategoryid=BOC1 t:datasource=PRAMS t:classid=CLA10 m:data_value=25

series e:ese6-rqpq d:2011-01-01T00:00:00.000Z t:topic=Medicaid t:locationabbr=AR t:locationdesc=Arkansas t:topicid=TOP12 t:class=Insurance/Medicaid/Services t:break_out="LBW (<=2500g)" t:questionid=QUO25 t:response="NO (UNCHECKED)" t:locationid=5 t:breakoutid=BWT1 t:responseid=RES24 t:break_out_category="Birth Weight" t:question="Indicator of whether mother received Medicaid coverage for prenatal care." t:breakoutcategoryid=BOC1 t:datasource=PRAMS t:classid=CLA10 m:high_confidence_limit=37.5 m:sample_size=143 m:data_value=33 m:low_confidence_limit=28.8
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit t:dataTypeName=number

metric m:high_confidence_limit p:float l:High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

entity e:ese6-rqpq l:"CDC PRAMStat Data for 2011" t:attribution="Centers for Disease Control and Prevention Division of Reproductive Health Pregnancy Risk Assessment Monitoring System (PRAMS)" t:url=https://chronicdata.cdc.gov/api/views/ese6-rqpq

property e:ese6-rqpq t:meta.view v:id=ese6-rqpq v:category="Maternal & Child Health" v:attributionLink=http://www.cdc.gov/prams/index.htm v:averageRating=0 v:name="CDC PRAMStat Data for 2011" v:attribution="Centers for Disease Control and Prevention Division of Reproductive Health Pregnancy Risk Assessment Monitoring System (PRAMS)"

property e:ese6-rqpq t:meta.view.license v:name="Public Domain"

property e:ese6-rqpq t:meta.view.owner v:id=7gh3-3zr5 v:screenName="PRAMStat Administrator" v:displayName="PRAMStat Administrator"

property e:ese6-rqpq t:meta.view.tableauthor v:id=uj8q-r4hw v:profileImageUrlMedium=/api/users/uj8q-r4hw/profile_images/THUMB v:profileImageUrlLarge=/api/users/uj8q-r4hw/profile_images/LARGE v:screenName=jbraith v:profileImageUrlSmall=/api/users/uj8q-r4hw/profile_images/TINY v:roleName=administrator v:displayName=jbraith

property e:ese6-rqpq t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```