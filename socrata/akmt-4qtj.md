# CDC PRAMStat Data for 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-pramstat-data-for-2006) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/akmt-4qtj) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/akmt-4qtj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/akmt-4qtj/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | akmt-4qtj |
| Name | CDC PRAMStat Data for 2006 |
| Attribution | Centers for Disease Control and Prevention Division of Reproductive Health Pregnancy Risk Assessment Monitoring System (PRAMS) |
| Category | Maternal & Child Health |
| Tags | abuse, alcohol use, contraception, breastfeeding, mental health, morbidity, obesity, pregnancy history, prenatal care, sleep behavior, smoke exposure, stress, tobacco use, wic, medicaid, reproduct... |
| Created | 2015-03-16T21:18:40Z |
| Publication Date | 2015-03-16T21:56:29Z |

## Description

2006. Centers for Disease Control and Prevention (CDC). PRAMS, the Pregnancy Risk Assessment Monitoring System, is a surveillance system collecting state-specific, population-based data on maternal attitudes and experiences before, during, and shortly after pregnancy. It is a collaborative project of the Centers for Disease Control and Prevention (CDC) and state health departments. PRAMS provides data for state health officials to use to improve the health of mothers and infants. PRAMS topics include abuse, alcohol use, contraception, breastfeeding, mental health, morbidity, obesity, preconception health, pregnancy history, prenatal-care, sleep behavior, smoke exposure, stress, tobacco use, WIC, Medicaid, infant health, and unintended pregnancy. Data will be updated annually as it becomes available.

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
series e:akmt-4qtj d:2006-01-01T00:00:00.000Z t:breakoutcategoryid=BOC16 t:questionid=QUO171 t:question="Indicator of no prenatal care" t:locationabbr=AK t:break_out="Age 18 - 44" t:locationdesc=Alaska t:topicid=TOP44 t:classid=CLA1 t:break_out_category="Maternal Age - 18 to 44 years only" t:datasource=PRAMS t:response=NO t:locationid=2 t:breakoutid=AGE1844ALL t:topic="Prenatal Care - Visits" t:class="Control Variable" t:responseid=RES23 m:data_value=99.1

series e:akmt-4qtj d:2006-01-01T00:00:00.000Z t:breakoutcategoryid=BOC1 t:questionid=QUO17 t:question="Just before you got pregnant  were you on Medicaid? (years 2000 - 2008)" t:locationabbr=AK t:locationdesc=Alaska t:topicid=TOP12 t:classid=CLA10 t:break_out_category="Birth Weight" t:datasource=PRAMS t:locationid=2 t:breakoutid=BOC1 t:topic=Medicaid t:class=Insurance/Medicaid/Services m:data_value=35

series e:akmt-4qtj d:2006-01-01T00:00:00.000Z t:breakoutcategoryid=BOC1 t:questionid=QUO17 t:question="Just before you got pregnant  were you on Medicaid? (years 2000 - 2008)" t:locationabbr=AK t:break_out="LBW (<=2500g)" t:locationdesc=Alaska t:topicid=TOP12 t:classid=CLA10 t:break_out_category="Birth Weight" t:datasource=PRAMS t:response=NO t:locationid=2 t:breakoutid=BWT1 t:topic=Medicaid t:class=Insurance/Medicaid/Services t:responseid=RES23 m:sample_size=324 m:data_value=85.1 m:high_confidence_limit=87.1 m:low_confidence_limit=82.8
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit t:dataTypeName=number

metric m:high_confidence_limit p:float l:High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size t:dataTypeName=number

entity e:akmt-4qtj l:"CDC PRAMStat Data for 2006" t:attribution="Centers for Disease Control and Prevention Division of Reproductive Health Pregnancy Risk Assessment Monitoring System (PRAMS)" t:url=https://chronicdata.cdc.gov/api/views/akmt-4qtj

property e:akmt-4qtj t:meta.view d:2017-09-25T07:23:14.791Z v:averageRating=0 v:name="CDC PRAMStat Data for 2006" v:attribution="Centers for Disease Control and Prevention Division of Reproductive Health Pregnancy Risk Assessment Monitoring System (PRAMS)" v:attributionLink=http://www.cdc.gov/prams/Index v:id=akmt-4qtj v:category="Maternal & Child Health"

property e:akmt-4qtj t:meta.view.license d:2017-09-25T07:23:14.791Z v:name="Public Domain"

property e:akmt-4qtj t:meta.view.owner d:2017-09-25T07:23:14.791Z v:displayName="PRAMStat Administrator" v:id=7gh3-3zr5 v:screenName="PRAMStat Administrator"

property e:akmt-4qtj t:meta.view.tableauthor d:2017-09-25T07:23:14.791Z v:displayName="PRAMStat Administrator" v:roleName=publisher v:id=7gh3-3zr5 v:screenName="PRAMStat Administrator"

property e:akmt-4qtj t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:23:14.791Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Program_Code=009:020 v:Publisher="Centers for Disease Control and Prevention" v:Bureau_Code=009:20 v:Public_Access_Level="Public Domain"
```

## Top Records

```ls
| year | locationabbr | locationdesc | class                       | topic                  | question                                                               | datasource | response | data_value_unit | data_value_type | data_value | data_value_footnote_symbol | data_value_footnote                                                                           | data_value_std_err | low_confidence_limit | high_confidence_limit | sample_size | break_out     | break_out_category                 | classid | topicid | questionid | locationid | breakoutid | breakoutcategoryid | responseid | 
| ==== | ============ | ============ | =========================== | ====================== | ====================================================================== | ========== | ======== | =============== | =============== | ========== | ========================== | ============================================================================================= | ================== | ==================== | ===================== | =========== | ============= | ================================== | ======= | ======= | ========== | ========== | ========== | ================== | ========== | 
| 2006 | AK           | Alaska       | Control Variable            | Prenatal Care - Visits | Indicator of no prenatal care                                          | PRAMS      | NO       | %               | Percentage      | 99.1000    |                            |                                                                                               |                    |                      |                       |             | Age 18 - 44   | Maternal Age - 18 to 44 years only | CLA1    | TOP44   | QUO171     | 2          | AGE1844ALL | BOC16              | RES23      | 
| 2006 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      |          | %               | Percentage      | 35.0000    | 1                          | Missing includes not applicable, don't know, not recorded, no responses, and legitimate skips |                    |                      |                       |             |               | Birth Weight                       | CLA10   | TOP12   | QUO17      | 2          | BOC1       | BOC1               |            | 
| 2006 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | NO       | %               | Percentage      | 85.1000    |                            |                                                                                               |                    | 82.8000              | 87.1000               | 324         | LBW (<=2500g) | Birth Weight                       | CLA10   | TOP12   | QUO17      | 2          | BWT1       | BOC1               | RES23      | 
| 2006 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | YES      | %               | Percentage      | 14.9000    |                            |                                                                                               |                    | 12.9000              | 17.2000               | 52          | LBW (<=2500g) | Birth Weight                       | CLA10   | TOP12   | QUO17      | 2          | BWT1       | BOC1               | RES40      | 
| 2006 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | NO       | %               | Percentage      | 88.5000    |                            |                                                                                               |                    | 86.4000              | 90.3000               | 857         | NBW (>2500g)  | Birth Weight                       | CLA10   | TOP12   | QUO17      | 2          | BWT2       | BOC1               | RES23      | 
| 2006 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | YES      | %               | Percentage      | 11.5000    |                            |                                                                                               |                    | 9.7000               | 13.6000               | 142         | NBW (>2500g)  | Birth Weight                       | CLA10   | TOP12   | QUO17      | 2          | BWT2       | BOC1               | RES40      | 
| 2006 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      |          | %               | Percentage      | 31.0000    | 1                          | Missing includes not applicable, don't know, not recorded, no responses, and legitimate skips |                    |                      |                       |             |               | On WIC during Pregnancy            | CLA10   | TOP12   | QUO17      | 2          | BOC10      | BOC10              |            | 
| 2006 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | NO       | %               | Percentage      | 95.8000    |                            |                                                                                               |                    | 93.8000              | 97.1000               | 629         | Non-WIC       | On WIC during Pregnancy            | CLA10   | TOP12   | QUO17      | 2          | WIC1       | BOC10              | RES23      | 
| 2006 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | YES      | %               | Percentage      | 4.2000     |                            |                                                                                               |                    | 2.9000               | 6.2000                | 37          | Non-WIC       | On WIC during Pregnancy            | CLA10   | TOP12   | QUO17      | 2          | WIC1       | BOC10              | RES40      | 
| 2006 | AK           | Alaska       | Insurance/Medicaid/Services | Medicaid               | Just before you got pregnant were you on Medicaid? (years 2000 - 2008) | PRAMS      | NO       | %               | Percentage      | 81.3000    |                            |                                                                                               |                    | 77.8000              | 84.4000               | 557         | WIC           | On WIC during Pregnancy            | CLA10   | TOP12   | QUO17      | 2          | WIC2       | BOC10              | RES23      | 
```