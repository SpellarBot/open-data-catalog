# CDC PRAMStat Data for 2004

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-pramstat-data-for-2004) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/xyxp-dxa9) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/xyxp-dxa9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/xyxp-dxa9/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | xyxp-dxa9 |
| Name | CDC PRAMStat Data for 2004 |
| Attribution | Centers for Disease Control and Prevention Division of Reproductive Health Pregnancy Risk Assessment Monitoring System (PRAMS) |
| Category | Maternal & Child Health |
| Tags | abuse, alcohol use, contraception, breastfeeding, mental health, morbidity, obesity, pregnancy history, prenatal care, sleep behavior, smoke exposure, stress, tobacco use, wic, medicaid, reproduct... |
| Created | 2015-03-17T18:37:35Z |
| Publication Date | 2015-03-17T19:50:37Z |

## Description

2004. Centers for Disease Control and Prevention (CDC). PRAMS, the Pregnancy Risk Assessment Monitoring System, is a surveillance system collecting state-specific, population-based data on maternal attitudes and experiences before, during, and shortly after pregnancy. It is a collaborative project of the Centers for Disease Control and Prevention (CDC) and state health departments. PRAMS provides data for state health officials to use to improve the health of mothers and infants. PRAMS topics include abuse, alcohol use, contraception, breastfeeding, mental health, morbidity, obesity, preconception health, pregnancy history, prenatal-care, sleep behavior, smoke exposure, stress, tobacco use, WIC, Medicaid, infant health, and unintended pregnancy. Data will be updated annually as it becomes available.

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
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | number    | number      |
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
series e:xyxp-dxa9 d:2004-01-01T00:00:00.000Z t:topic="Prenatal Care - Visits" t:locationabbr=AK t:locationdesc=Alaska t:topicid=TOP44 t:class="Control Variable" t:break_out="Age 18 - 44" t:questionid=QUO171 t:response=NO t:locationid=2 t:breakoutid=AGE1844ALL t:responseid=RES23 t:break_out_category="Maternal Age - 18 to 44 years only" t:question="Indicator of no prenatal care" t:breakoutcategoryid=BOC16 t:datasource=PRAMS t:classid=CLA1 m:data_value=99.1

series e:xyxp-dxa9 d:2004-01-01T00:00:00.000Z t:topic=Medicaid t:locationabbr=AK t:locationdesc=Alaska t:topicid=TOP12 t:class=Insurance/Medicaid/Services t:questionid=QUO17 t:locationid=2 t:breakoutid=BOC1 t:break_out_category="Birth Weight" t:question="Just before you got pregnant  were you on Medicaid? (years 2000 - 2008)" t:breakoutcategoryid=BOC1 t:datasource=PRAMS t:classid=CLA10 m:data_value=18

series e:xyxp-dxa9 d:2004-01-01T00:00:00.000Z t:topic=Medicaid t:locationabbr=AK t:locationdesc=Alaska t:topicid=TOP12 t:class=Insurance/Medicaid/Services t:break_out="LBW (<=2500g)" t:questionid=QUO17 t:response=NO t:locationid=2 t:breakoutid=BWT1 t:responseid=RES23 t:break_out_category="Birth Weight" t:question="Just before you got pregnant  were you on Medicaid? (years 2000 - 2008)" t:breakoutcategoryid=BOC1 t:datasource=PRAMS t:classid=CLA10 m:high_confidence_limit=86 m:sample_size=335 m:data_value=84.2 m:low_confidence_limit=82.1
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit t:dataTypeName=number

metric m:high_confidence_limit p:float l:High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

entity e:xyxp-dxa9 l:"CDC PRAMStat Data for 2004" t:attribution="Centers for Disease Control and Prevention Division of Reproductive Health Pregnancy Risk Assessment Monitoring System (PRAMS)" t:url=https://chronicdata.cdc.gov/api/views/xyxp-dxa9

property e:xyxp-dxa9 t:meta.view v:id=xyxp-dxa9 v:category="Maternal & Child Health" v:attributionLink=http://www.cdc.gov/prams/index v:averageRating=0 v:name="CDC PRAMStat Data for 2004" v:attribution="Centers for Disease Control and Prevention Division of Reproductive Health Pregnancy Risk Assessment Monitoring System (PRAMS)"

property e:xyxp-dxa9 t:meta.view.license v:name="Public Domain"

property e:xyxp-dxa9 t:meta.view.owner v:id=7gh3-3zr5 v:screenName="PRAMStat Administrator" v:displayName="PRAMStat Administrator"

property e:xyxp-dxa9 t:meta.view.tableauthor v:id=7gh3-3zr5 v:screenName="PRAMStat Administrator" v:roleName=publisher v:displayName="PRAMStat Administrator"

property e:xyxp-dxa9 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | locationabbr | locationdesc | class                       | topic                  | question                                                               | datasource | response | data_value_unit | data_value_type | data_value | data_value_footnote_symbol | data_value_footnote                                                                           | data_value_std_err | low_confidence_limit | high_confidence_limit | sample_size | break_out     | break_out_category                 | classid | topicid | questionid | locationid | breakoutid | breakoutcategoryid | responseid | 
| ==== | ============ | ============ | =========================== | ====================== | ====================================================================== | ========== | ======== | =============== | =============== | ========== | ========================== | ============================================================================================= | ================== | ==================== | ===================== | =========== | ============= | ================================== | ======= | ======= | ========== | ========== | ========== | ================== | ========== | 
| 2004 | AK           | Alaska       | Control Variable            | Prenatal Care - Visits | Indicator of no prenatal care                                          | PRAMS      | NO       | %               | Percentage      | 99.1000    |                            |                                                                                               |                    |                      |                       |             | Age 18 - 44   | Maternal Age - 18 to 44 years only | CLA1    | TOP44   | QUO171     | 2          | AGE1844ALL | BOC16              | RES23      | 
| 2004 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      |          | %               | Percentage      | 18.0000    | 1                          | Missing includes not applicable, don't know, not recorded, no responses, and legitimate skips |                    |                      |                       |             |               | Birth Weight                       | CLA10   | TOP12   | QUO17      | 2          | BOC1       | BOC1               |            | 
| 2004 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | NO       | %               | Percentage      | 84.2000    |                            |                                                                                               |                    | 82.1000              | 86.0000               | 335         | LBW (<=2500g) | Birth Weight                       | CLA10   | TOP12   | QUO17      | 2          | BWT1       | BOC1               | RES23      | 
| 2004 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | YES      | %               | Percentage      | 15.8000    |                            |                                                                                               |                    | 14.0000              | 17.9000               | 58          | LBW (<=2500g) | Birth Weight                       | CLA10   | TOP12   | QUO17      | 2          | BWT1       | BOC1               | RES40      | 
| 2004 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | NO       | %               | Percentage      | 88.6000    |                            |                                                                                               |                    | 86.4000              | 90.5000               | 794         | NBW (>2500g)  | Birth Weight                       | CLA10   | TOP12   | QUO17      | 2          | BWT2       | BOC1               | RES23      | 
| 2004 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | YES      | %               | Percentage      | 11.4000    |                            |                                                                                               |                    | 9.5000               | 13.6000               | 135         | NBW (>2500g)  | Birth Weight                       | CLA10   | TOP12   | QUO17      | 2          | BWT2       | BOC1               | RES40      | 
| 2004 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      |          | %               | Percentage      | 19.0000    | 1                          | Missing includes not applicable, don't know, not recorded, no responses, and legitimate skips |                    |                      |                       |             |               | On WIC during Pregnancy            | CLA10   | TOP12   | QUO17      | 2          | BOC10      | BOC10              |            | 
| 2004 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | NO       | %               | Percentage      | 96.6000    |                            |                                                                                               |                    | 94.9000              | 97.7000               | 575         | Non-WIC       | On WIC during Pregnancy            | CLA10   | TOP12   | QUO17      | 2          | WIC1       | BOC10              | RES23      | 
| 2004 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | YES      | %               | Percentage      | 3.4000     |                            |                                                                                               |                    | 2.3000               | 5.1000                | 31          | Non-WIC       | On WIC during Pregnancy            | CLA10   | TOP12   | QUO17      | 2          | WIC1       | BOC10              | RES40      | 
| 2004 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | NO       | %               | Percentage      | 80.3000    |                            |                                                                                               |                    | 76.6000              | 83.5000               | 555         | WIC           | On WIC during Pregnancy            | CLA10   | TOP12   | QUO17      | 2          | WIC2       | BOC10              | RES23      | 
```