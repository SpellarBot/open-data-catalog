# ASTDD Synopses of State Oral Health Programs - Selected indicators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/astdd-synopses-of-state-oral-health-programs-2011-2015-selected-indicators) |
| Metadata | [Link](https://data.cdc.gov/api/views/vwmz-4ja3) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/vwmz-4ja3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/vwmz-4ja3/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | vwmz-4ja3 |
| Name | ASTDD Synopses of State Oral Health Programs - Selected indicators |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Oral Health |
| Category | Oral Health |
| Tags | oral health, state oral health program characteristics, school based sealant programs, state dental directors, programs, policy, workforce, infrastructure, cleft lip/cleft palate recording, cleft ... |
| Created | 2015-06-01T15:06:13Z |
| Publication Date | 2017-02-02T23:21:35Z |

## Description

2011-2015. The ASTDD Synopses of State Oral Health Programs contain information useful in tracking states? efforts to improve oral health and contributions to progress toward the national targets for Healthy People objectives for oral health. A subset of the information collected from the most recent five years is provided on the Oral Health Data website. For more information, see http://www.cdc.gov/oralhealthdata/overview/synopses/index.html

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | series tag     | locationabbr               | LocationAbbr               | text      | text        |
| Yes      | series tag     | locationdesc               | LocationDesc               | text      | text        |
| Yes      | series tag     | datasource                 | DataSource                 | text      | text        |
| Yes      | series tag     | class                      | Class                      | text      | text        |
| Yes      | series tag     | topic                      | Topic                      | text      | text        |
| Yes      | series tag     | question                   | Question                   | text      | text        |
| Yes      | series tag     | response                   | Response                   | text      | text        |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| Yes      | series tag     | data_value                 | Data_Value                 | text      | text        |
| No       |                | data_value_alt             | Data_Value_Alt             | number    | number      |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | numeric metric | low_confidence_limit       | Low_Confidence_Limit       | number    | number      |
| Yes      | numeric metric | high_confidence_limit      | High_Confidence_Limit      | number    | number      |
| Yes      | numeric metric | sample_size                | Sample_Size                | number    | number      |
| Yes      | series tag     | break_out                  | Break_Out                  | text      | text        |
| Yes      | series tag     | break_out_category         | Break_Out_Category         | text      | text        |
| Yes      | series tag     | classid                    | ClassID                    | text      | text        |
| Yes      | series tag     | topicid                    | TopicID                    | text      | text        |
| Yes      | series tag     | questionid                 | QuestionID                 | text      | text        |
| Yes      | series tag     | responseid                 | ResponseID                 | text      | text        |
| Yes      | series tag     | locationid                 | LocationID                 | text      | text        |
| Yes      | series tag     | breakoutid                 | BreakOutID                 | text      | text        |
| Yes      | series tag     | breakoutcategoryid         | BreakOutCategoryID         | text      | text        |
| Yes      | series tag     | data_value_category        | Data_Value_Category        | text      | text        |
| Yes      | series tag     | data_value_category_id     | Data_Value_Category_ID     | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_unit,data_value_type,data_value_alt,data_value_footnote_symbol,data_value_footnote
```

## Data Commands

```ls
```

## Meta Commands

```ls
metric m:low_confidence_limit p:long l:Low_Confidence_Limit t:dataTypeName=number

metric m:high_confidence_limit p:long l:High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:long l:Sample_Size t:dataTypeName=number

entity e:vwmz-4ja3 l:"ASTDD Synopses of State Oral Health Programs - Selected indicators" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Oral Health" t:url=https://data.cdc.gov/api/views/vwmz-4ja3

property e:vwmz-4ja3 t:meta.view v:id=vwmz-4ja3 v:category="Oral Health" v:attributionLink=http://www.cdc.gov/oralhealth/ v:averageRating=0 v:name="ASTDD Synopses of State Oral Health Programs - Selected indicators" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Oral Health"

property e:vwmz-4ja3 t:meta.view.license v:name="Public Domain"

property e:vwmz-4ja3 t:meta.view.owner v:id=5ehu-79qp v:screenName="Oral Health Data Administrator" v:displayName="Oral Health Data Administrator"

property e:vwmz-4ja3 t:meta.view.tableauthor v:id=5ehu-79qp v:screenName="Oral Health Data Administrator" v:roleName=publisher v:displayName="Oral Health Data Administrator"

property e:vwmz-4ja3 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | locationabbr | locationdesc         | datasource     | class    | topic      | question                      | response | data_value_unit | data_value_type | data_value | data_value_alt | data_value_footnote_symbol | data_value_footnote | low_confidence_limit | high_confidence_limit | sample_size | break_out | break_out_category | classid | topicid | questionid | responseid | locationid | breakoutid | breakoutcategoryid | data_value_category | data_value_category_id | 
| ==== | ============ | ==================== | ============== | ======== | ========== | ============================= | ======== | =============== | =============== | ========== | ============== | ========================== | =================== | ==================== | ===================== | =========== | ========= | ================== | ======= | ======= | ========== | ========== | ========== | ========== | ================== | =================== | ====================== | 
| 2015 | AK           | Alaska               | ASTDD Synopses | Synopses | Leadership | Current state dental director |          |                 | yes/no          | Yes        | 10001          |                            |                     |                      |                       |             |           |                    | SYNOP   | LEAD    | LEAD1_1    |            | 02         |            |                    | Yes                 | CAT10001               | 
| 2015 | AL           | Alabama              | ASTDD Synopses | Synopses | Leadership | Current state dental director |          |                 | yes/no          | Yes        | 10001          |                            |                     |                      |                       |             |           |                    | SYNOP   | LEAD    | LEAD1_1    |            | 01         |            |                    | Yes                 | CAT10001               | 
| 2015 | AR           | Arkansas             | ASTDD Synopses | Synopses | Leadership | Current state dental director |          |                 | yes/no          | Yes        | 10001          |                            |                     |                      |                       |             |           |                    | SYNOP   | LEAD    | LEAD1_1    |            | 05         |            |                    | Yes                 | CAT10001               | 
| 2015 | AZ           | Arizona              | ASTDD Synopses | Synopses | Leadership | Current state dental director |          |                 | yes/no          | Yes        | 10001          |                            |                     |                      |                       |             |           |                    | SYNOP   | LEAD    | LEAD1_1    |            | 04         |            |                    | Yes                 | CAT10001               | 
| 2015 | CA           | California           | ASTDD Synopses | Synopses | Leadership | Current state dental director |          |                 | yes/no          | Yes        | 10001          |                            |                     |                      |                       |             |           |                    | SYNOP   | LEAD    | LEAD1_1    |            | 06         |            |                    | Yes                 | CAT10001               | 
| 2015 | CO           | Colorado             | ASTDD Synopses | Synopses | Leadership | Current state dental director |          |                 | yes/no          | Yes        | 10001          |                            |                     |                      |                       |             |           |                    | SYNOP   | LEAD    | LEAD1_1    |            | 08         |            |                    | Yes                 | CAT10001               | 
| 2015 | CT           | Connecticut          | ASTDD Synopses | Synopses | Leadership | Current state dental director |          |                 | yes/no          | Yes        | 10001          |                            |                     |                      |                       |             |           |                    | SYNOP   | LEAD    | LEAD1_1    |            | 09         |            |                    | Yes                 | CAT10001               | 
| 2015 | DC           | District of Columbia | ASTDD Synopses | Synopses | Leadership | Current state dental director |          |                 | yes/no          | Yes        | 10001          |                            |                     |                      |                       |             |           |                    | SYNOP   | LEAD    | LEAD1_1    |            | 11         |            |                    | Yes                 | CAT10001               | 
| 2015 | DE           | Delaware             | ASTDD Synopses | Synopses | Leadership | Current state dental director |          |                 | yes/no          | Yes        | 10001          |                            |                     |                      |                       |             |           |                    | SYNOP   | LEAD    | LEAD1_1    |            | 10         |            |                    | Yes                 | CAT10001               | 
| 2015 | FL           | Florida              | ASTDD Synopses | Synopses | Leadership | Current state dental director |          |                 | yes/no          | Yes        | 10001          |                            |                     |                      |                       |             |           |                    | SYNOP   | LEAD    | LEAD1_1    |            | 12         |            |                    | Yes                 | CAT10001               | 
```