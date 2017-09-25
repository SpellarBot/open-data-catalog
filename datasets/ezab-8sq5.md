# Smoking-Attributable Mortality, Morbidity, and Economic Costs (SAMMEC) - Smoking-Attributable Expenditures (SAE)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/smoking-attributable-mortality-morbidity-and-economic-costs-sammec-smoking-attributable-ex-d39cf) |
| Metadata | [Link](https://data.cdc.gov/api/views/ezab-8sq5) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/ezab-8sq5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/ezab-8sq5/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | ezab-8sq5 |
| Name | Smoking-Attributable Mortality, Morbidity, and Economic Costs (SAMMEC) - Smoking-Attributable Expenditures (SAE) |
| Category | Health Consequences and Costs |
| Tags | osh, tobacco, sammec, sae |
| Created | 2015-01-20T20:23:17Z |
| Publication Date | 2017-02-06T16:35:05Z |

## Description

2005-2009. SAMMEC - Smoking-Attributable Mortality, Morbidity, and Economic Costs. Smoking-attributable expenditures (SAEs) are excess health care expenditures attributable to cigarette smoking, by type of service, among adults ages 19 years of age and older.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | text        |
| Yes      | series tag     | locationabbr               | LocationAbbr               | text      | text        |
| Yes      | series tag     | locationdesc               | LocationDesc               | text      | text        |
| Yes      | series tag     | datasource                 | DataSource                 | text      | text        |
| Yes      | series tag     | topictype                  | TopicType                  | text      | text        |
| Yes      | series tag     | topicdesc                  | TopicDesc                  | text      | text        |
| Yes      | series tag     | measuredesc                | MeasureDesc                | text      | text        |
| Yes      | series tag     | variable                   | Variable                   | text      | text        |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | series tag     | topic_type_id              | Topic Type ID              | text      | text        |
| Yes      | series tag     | topic_id                   | Topic ID                   | text      | text        |
| Yes      | series tag     | measure_id                 | Measure ID                 | text      | text        |
| Yes      | series tag     | submeasureid               | SubMeasureID               | text      | text        |
| No       |                | displayorder               | DisplayOrder               | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_unit,data_value_type,data_value_footnote_symbol,data_value_footnote,displayorder
```

## Data Commands

```ls
series e:ezab-8sq5 d:2005-01-01T00:00:00.000Z t:topic_type_id=HLT t:measuredesc="Type of Expense" t:submeasureid=SAE002 t:datasource=SAMMEC t:variable=Ambulatory t:locationabbr=AL t:locationdesc=Alabama t:topic_id=501HLT t:topictype="Health Consequences and Costs" t:measure_id=520SAE t:topicdesc="Smoking-Attributable Expenditures (SAEs)" m:data_value=265.7

series e:ezab-8sq5 d:2005-01-01T00:00:00.000Z t:topic_type_id=HLT t:measuredesc="Type of Expense" t:submeasureid=SAE002 t:datasource=SAMMEC t:variable=Ambulatory t:locationabbr=AK t:locationdesc=Alaska t:topic_id=501HLT t:topictype="Health Consequences and Costs" t:measure_id=520SAE t:topicdesc="Smoking-Attributable Expenditures (SAEs)" m:data_value=60.5

series e:ezab-8sq5 d:2005-01-01T00:00:00.000Z t:topic_type_id=HLT t:measuredesc="Type of Expense" t:submeasureid=SAE002 t:datasource=SAMMEC t:variable=Ambulatory t:locationabbr=AZ t:locationdesc=Arizona t:topic_id=501HLT t:topictype="Health Consequences and Costs" t:measure_id=520SAE t:topicdesc="Smoking-Attributable Expenditures (SAEs)" m:data_value=315.4
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value d:"Value of the data" t:dataTypeName=number

entity e:ezab-8sq5 l:"Smoking-Attributable Mortality, Morbidity, and Economic Costs (SAMMEC) - Smoking-Attributable Expenditures (SAE)" t:url=https://data.cdc.gov/api/views/ezab-8sq5

property e:ezab-8sq5 t:meta.view d:2017-09-25T07:23:46.042Z v:averageRating=0 v:name="Smoking-Attributable Mortality, Morbidity, and Economic Costs (SAMMEC) - Smoking-Attributable Expenditures (SAE)" v:id=ezab-8sq5 v:category="Health Consequences and Costs"

property e:ezab-8sq5 t:meta.view.license d:2017-09-25T07:23:46.042Z v:name="Public Domain"

property e:ezab-8sq5 t:meta.view.owner d:2017-09-25T07:23:46.042Z v:displayName=OSHData v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:id=p5wh-zttj v:screenName=OSHData v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB

property e:ezab-8sq5 t:meta.view.tableauthor d:2017-09-25T07:23:46.042Z v:displayName=OSHData v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:id=p5wh-zttj v:screenName=OSHData v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB

property e:ezab-8sq5 t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:23:46.042Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Program_Code=009:020 v:Publisher="Centers for Disease Control and Prevention" v:Bureau_Code=009:20 v:Public_Access_Level="Public Domain"
```

## Top Records

```ls
| year | locationabbr | locationdesc         | datasource | topictype                     | topicdesc                                | measuredesc     | variable   | data_value_unit | data_value_type     | data_value | data_value_footnote_symbol | data_value_footnote | topic_type_id | topic_id | measure_id | submeasureid | displayorder | 
| ==== | ============ | ==================== | ========== | ============================= | ======================================== | =============== | ========== | =============== | =================== | ========== | ========================== | =================== | ============= | ======== | ========== | ============ | ============ | 
| 2005 | AL           | Alabama              | SAMMEC     | Health Consequences and Costs | Smoking-Attributable Expenditures (SAEs) | Type of Expense | Ambulatory | $               | Millions of Dollars | 265.7      |                            |                     | HLT           | 501HLT   | 520SAE     | SAE002       | 02           | 
| 2005 | AK           | Alaska               | SAMMEC     | Health Consequences and Costs | Smoking-Attributable Expenditures (SAEs) | Type of Expense | Ambulatory | $               | Millions of Dollars | 60.5       |                            |                     | HLT           | 501HLT   | 520SAE     | SAE002       | 02           | 
| 2005 | AZ           | Arizona              | SAMMEC     | Health Consequences and Costs | Smoking-Attributable Expenditures (SAEs) | Type of Expense | Ambulatory | $               | Millions of Dollars | 315.4      |                            |                     | HLT           | 501HLT   | 520SAE     | SAE002       | 02           | 
| 2005 | AR           | Arkansas             | SAMMEC     | Health Consequences and Costs | Smoking-Attributable Expenditures (SAEs) | Type of Expense | Ambulatory | $               | Millions of Dollars | 156.2      |                            |                     | HLT           | 501HLT   | 520SAE     | SAE002       | 02           | 
| 2005 | CA           | California           | SAMMEC     | Health Consequences and Costs | Smoking-Attributable Expenditures (SAEs) | Type of Expense | Ambulatory | $               | Millions of Dollars | 2056.6     |                            |                     | HLT           | 501HLT   | 520SAE     | SAE002       | 02           | 
| 2005 | CO           | Colorado             | SAMMEC     | Health Consequences and Costs | Smoking-Attributable Expenditures (SAEs) | Type of Expense | Ambulatory | $               | Millions of Dollars | 255.7      |                            |                     | HLT           | 501HLT   | 520SAE     | SAE002       | 02           | 
| 2005 | CT           | Connecticut          | SAMMEC     | Health Consequences and Costs | Smoking-Attributable Expenditures (SAEs) | Type of Expense | Ambulatory | $               | Millions of Dollars | 243.9      |                            |                     | HLT           | 501HLT   | 520SAE     | SAE002       | 02           | 
| 2005 | DE           | Delaware             | SAMMEC     | Health Consequences and Costs | Smoking-Attributable Expenditures (SAEs) | Type of Expense | Ambulatory | $               | Millions of Dollars | 65.6       |                            |                     | HLT           | 501HLT   | 520SAE     | SAE002       | 02           | 
| 2005 | DC           | District of Columbia | SAMMEC     | Health Consequences and Costs | Smoking-Attributable Expenditures (SAEs) | Type of Expense | Ambulatory | $               | Millions of Dollars | 35.1       |                            |                     | HLT           | 501HLT   | 520SAE     | SAE002       | 02           | 
| 2005 | FL           | Florida              | SAMMEC     | Health Consequences and Costs | Smoking-Attributable Expenditures (SAEs) | Type of Expense | Ambulatory | $               | Millions of Dollars | 1281.4     |                            |                     | HLT           | 501HLT   | 520SAE     | SAE002       | 02           | 
```