# CDC PRAMStat Data for 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-pramstat-data-for-2000-45a95) |
| Metadata | [Link](https://data.cdc.gov/api/views/3hwj-hqmh) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/3hwj-hqmh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/3hwj-hqmh/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 3hwj-hqmh |
| Name | CDC PRAMStat Data for 2000 |
| Attribution | Centers for Disease Control and Prevention Division of Reproductive Health Pregnancy Risk Assessment Monitoring System (PRAMS) |
| Category | Maternal & Child Health |
| Tags | abuse, alcohol use, contraception, breastfeeding, mental health, morbidity, obesity, pregnancy history, prenatal care, sleep behavior, smoke exposure, stress, tobacco use, wic, medicaid, reproduct... |
| Created | 2015-03-17T21:32:01Z |
| Publication Date | 2015-03-17T21:52:34Z |

## Description

2000. Centers for Disease Control and Prevention (CDC). PRAMS, the Pregnancy Risk Assessment Monitoring System, is a surveillance system collecting state-specific, population-based data on maternal attitudes and experiences before, during, and shortly after pregnancy. It is a collaborative project of the Centers for Disease Control and Prevention (CDC) and state health departments. PRAMS provides data for state health officials to use to improve the health of mothers and infants. PRAMS topics include abuse, alcohol use, contraception, breastfeeding, mental health, morbidity, obesity, preconception health, pregnancy history, prenatal-care, sleep behavior, smoke exposure, stress, tobacco use, WIC, Medicaid, infant health, and unintended pregnancy. Data will be updated annually as it becomes available.

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
series e:3hwj-hqmh d:2000-01-01T00:00:00.000Z t:topic="Prenatal Care - Visits" t:locationabbr=AK t:locationdesc=Alaska t:topicid=TOP44 t:class="Control Variable" t:break_out="Age 18 - 44" t:questionid=QUO171 t:response=NO t:locationid=2 t:breakoutid=AGE1844ALL t:responseid=RES23 t:break_out_category="Maternal Age - 18 to 44 years only" t:question="Indicator of no prenatal care" t:breakoutcategoryid=BOC16 t:datasource=PRAMS t:classid=CLA1 m:data_value=99.5

series e:3hwj-hqmh d:2000-01-01T00:00:00.000Z t:topic=Medicaid t:locationabbr=AK t:locationdesc=Alaska t:topicid=TOP12 t:class=Insurance/Medicaid/Services t:questionid=QUO17 t:locationid=2 t:breakoutid=BOC1 t:break_out_category="Birth Weight" t:question="Just before you got pregnant  were you on Medicaid? (years 2000 - 2008)" t:breakoutcategoryid=BOC1 t:datasource=PRAMS t:classid=CLA10 m:data_value=22

series e:3hwj-hqmh d:2000-01-01T00:00:00.000Z t:topic=Medicaid t:locationabbr=AK t:locationdesc=Alaska t:topicid=TOP12 t:class=Insurance/Medicaid/Services t:break_out="LBW (<=2500g)" t:questionid=QUO17 t:response=NO t:locationid=2 t:breakoutid=BWT1 t:responseid=RES23 t:break_out_category="Birth Weight" t:question="Just before you got pregnant  were you on Medicaid? (years 2000 - 2008)" t:breakoutcategoryid=BOC1 t:datasource=PRAMS t:classid=CLA10 m:high_confidence_limit=83.4 m:sample_size=229 m:data_value=80.6 m:low_confidence_limit=77.5
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit t:dataTypeName=number

metric m:high_confidence_limit p:float l:High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

entity e:3hwj-hqmh l:"CDC PRAMStat Data for 2000" t:attribution="Centers for Disease Control and Prevention Division of Reproductive Health Pregnancy Risk Assessment Monitoring System (PRAMS)" t:url=https://data.cdc.gov/api/views/3hwj-hqmh

property e:3hwj-hqmh t:meta.view v:id=3hwj-hqmh v:category="Maternal & Child Health" v:attributionLink=http://www.cdc.gov/prams/index v:averageRating=0 v:name="CDC PRAMStat Data for 2000" v:attribution="Centers for Disease Control and Prevention Division of Reproductive Health Pregnancy Risk Assessment Monitoring System (PRAMS)"

property e:3hwj-hqmh t:meta.view.license v:name="Public Domain"

property e:3hwj-hqmh t:meta.view.owner v:id=7gh3-3zr5 v:screenName="PRAMStat Administrator" v:displayName="PRAMStat Administrator"

property e:3hwj-hqmh t:meta.view.tableauthor v:id=7gh3-3zr5 v:screenName="PRAMStat Administrator" v:roleName=publisher v:displayName="PRAMStat Administrator"

property e:3hwj-hqmh t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | locationabbr | locationdesc | class                       | topic                  | question                                                               | datasource | response | data_value_unit | data_value_type | data_value | data_value_footnote_symbol | data_value_footnote                                                                           | data_value_std_err | low_confidence_limit | high_confidence_limit | sample_size | break_out     | break_out_category                 | classid | topicid | questionid | locationid | breakoutid | breakoutcategoryid | responseid | 
| ==== | ============ | ============ | =========================== | ====================== | ====================================================================== | ========== | ======== | =============== | =============== | ========== | ========================== | ============================================================================================= | ================== | ==================== | ===================== | =========== | ============= | ================================== | ======= | ======= | ========== | ========== | ========== | ================== | ========== | 
| 2000 | AK           | Alaska       | Control Variable            | Prenatal Care - Visits | Indicator of no prenatal care                                          | PRAMS      | NO       | %               | Percentage      | 99.5000    |                            |                                                                                               |                    |                      |                       |             | Age 18 - 44   | Maternal Age - 18 to 44 years only | CLA1    | TOP44   | QUO171     | 2          | AGE1844ALL | BOC16              | RES23      | 
| 2000 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      |          | %               | Percentage      | 22.0000    | 1                          | Missing includes not applicable, don't know, not recorded, no responses, and legitimate skips |                    |                      |                       |             |               | Birth Weight                       | CLA10   | TOP12   | QUO17      | 2          | BOC1       | BOC1               |            | 
| 2000 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | NO       | %               | Percentage      | 80.6000    |                            |                                                                                               |                    | 77.5000              | 83.4000               | 229         | LBW (<=2500g) | Birth Weight                       | CLA10   | TOP12   | QUO17      | 2          | BWT1       | BOC1               | RES23      | 
| 2000 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | YES      | %               | Percentage      | 19.4000    |                            |                                                                                               |                    | 16.6000              | 22.5000               | 54          | LBW (<=2500g) | Birth Weight                       | CLA10   | TOP12   | QUO17      | 2          | BWT1       | BOC1               | RES40      | 
| 2000 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | NO       | %               | Percentage      | 88.4000    |                            |                                                                                               |                    | 86.4000              | 90.1000               | 1001        | NBW (>2500g)  | Birth Weight                       | CLA10   | TOP12   | QUO17      | 2          | BWT2       | BOC1               | RES23      | 
| 2000 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | YES      | %               | Percentage      | 11.6000    |                            |                                                                                               |                    | 9.9000               | 13.6000               | 174         | NBW (>2500g)  | Birth Weight                       | CLA10   | TOP12   | QUO17      | 2          | BWT2       | BOC1               | RES40      | 
| 2000 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      |          | %               | Percentage      | 13.0000    | 1                          | Missing includes not applicable, don't know, not recorded, no responses, and legitimate skips |                    |                      |                       |             |               | On WIC during Pregnancy            | CLA10   | TOP12   | QUO17      | 2          | BOC10      | BOC10              |            | 
| 2000 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | NO       | %               | Percentage      | 96.6000    |                            |                                                                                               |                    | 95.3000              | 97.5000               | 634         | Non-WIC       | On WIC during Pregnancy            | CLA10   | TOP12   | QUO17      | 2          | WIC1       | BOC10              | RES23      | 
| 2000 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | YES      | %               | Percentage      | 3.4000     |                            |                                                                                               |                    | 2.5000               | 4.7000                | 46          | Non-WIC       | On WIC during Pregnancy            | CLA10   | TOP12   | QUO17      | 2          | WIC1       | BOC10              | RES40      | 
| 2000 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | NO       | %               | Percentage      | 78.8000    |                            |                                                                                               |                    | 75.4000              | 81.8000               | 601         | WIC           | On WIC during Pregnancy            | CLA10   | TOP12   | QUO17      | 2          | WIC2       | BOC10              | RES23      | 
```