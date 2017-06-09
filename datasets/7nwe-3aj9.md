# The Tax Burden on Tobacco Volume 49, 1970-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/the-tax-burden-on-tobacco-volume-49-1970-2014) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/7nwe-3aj9) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/7nwe-3aj9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/7nwe-3aj9/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | 7nwe-3aj9 |
| Name | The Tax Burden on Tobacco Volume 49, 1970-2014 |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Policy |
| Tags | osh, office on smoking and health, tax, tax burden on tobacco, cigarette sales, average cost per pack |
| Created | 2014-05-27T11:46:47Z |
| Publication Date | 2017-02-07T12:20:46Z |

## Description

1970-2014. Orzechowski and Walker. Tax Burden on Tobacco. Tax burden data was obtained from the annual compendium on tobacco revenue and industry statistics, The Tax Burden on Tobacco. Data are reported on an annual basis; Data include federal and state-level information regarding taxes applied to the price of a pack of cigarettes.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | locationabbr             | LocationAbbr             | text      | text        |
| Yes      | series tag     | locationdesc             | LocationDesc             | text      | text        |
| Yes      | time           | year                     | Year                     | number    | number      |
| Yes      | series tag     | datasource               | Datasource               | text      | text        |
| Yes      | series tag     | topicdesc                | TopicDesc                | text      | text        |
| Yes      | series tag     | measuredesc              | MeasureDesc              | text      | text        |
| Yes      | series tag     | submeasuredesc           | SubMeasureDesc           | text      | text        |
| Yes      | numeric metric | data_value               | Data_Value               | number    | number      |
| No       |                | data_value_unit          | Data_Value_Unit          | text      | text        |
| No       |                | data_value_type          | Data_Value_Type          | text      | text        |
| Yes      | series tag     | source                   | Source                   | text      | text        |
| Yes      | series tag     | topictypeid              | TopicTypeId              | text      | text        |
| Yes      | series tag     | topicid                  | TopicId                  | text      | text        |
| Yes      | series tag     | measureid                | MeasureId                | text      | text        |
| Yes      | series tag     | submeasureid             | SubMeasureID             | text      | text        |
| No       |                | submeasureiddisplayorder | SubMeasureIdDisplayOrder | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_unit,data_value_type,submeasureiddisplayorder
```

## Data Commands

```ls
series e:7nwe-3aj9 d:2014-01-01T00:00:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:topicid=450POL t:source="Table 13- Orzechowski and Walker, Tax Burden on Tobacco" t:measureid=450CGS t:measuredesc="Cigarette Sales" t:submeasuredesc="Average Cost per pack" t:topicdesc="The Tax Burden on Tobacco" t:submeasureid=455CGS t:datasource=OW t:topictypeid=POL m:data_value=5.102

series e:7nwe-3aj9 d:2014-01-01T00:00:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:topicid=450POL t:source="Table 11- Orzechowski and Walker, Tax Burden on Tobacco" t:measureid=450CGS t:measuredesc="Cigarette Sales" t:submeasuredesc="Cigarette Consumption (Pack Sales Per Capita)" t:topicdesc="The Tax Burden on Tobacco" t:submeasureid=453CGS t:datasource=OW t:topictypeid=POL m:data_value=61.7

series e:7nwe-3aj9 d:2014-01-01T00:00:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:topicid=450POL t:source="Table 13- Orzechowski and Walker, Tax Burden on Tobacco" t:measureid=450CGS t:measuredesc="Cigarette Sales" t:submeasuredesc="Federal and State tax as a Percentage of Retail Price" t:topicdesc="The Tax Burden on Tobacco" t:submeasureid=454CGS t:datasource=OW t:topictypeid=POL m:data_value=28.1
```

## Meta Commands

```ls
metric m:data_value p:double l:Data_Value d:"Value of the data" t:dataTypeName=number

entity e:7nwe-3aj9 l:"The Tax Burden on Tobacco Volume 49, 1970-2014" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://chronicdata.cdc.gov/api/views/7nwe-3aj9

property e:7nwe-3aj9 t:meta.view d:2017-06-09T13:58:41.277Z v:id=7nwe-3aj9 v:category=Policy v:attributionLink=http://www.cdc.gov/tobacco/STATESystem v:averageRating=0 v:name="The Tax Burden on Tobacco Volume 49, 1970-2014" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:7nwe-3aj9 t:meta.view.owner d:2017-06-09T13:58:41.277Z v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:7nwe-3aj9 t:meta.view.tableauthor d:2017-06-09T13:58:41.277Z v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:7nwe-3aj9 t:meta.view.metadata.custom_fields.common_core d:2017-06-09T13:58:41.277Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| locationabbr | locationdesc | year | datasource | topicdesc                 | measuredesc     | submeasuredesc                                        | data_value | data_value_unit | data_value_type | source                                                  | topictypeid | topicid | measureid | submeasureid | submeasureiddisplayorder | 
| ============ | ============ | ==== | ========== | ========================= | =============== | ===================================================== | ========== | =============== | =============== | ======================================================= | =========== | ======= | ========= | ============ | ======================== | 
| AL           | Alabama      | 2014 | OW         | The Tax Burden on Tobacco | Cigarette Sales | Average Cost per pack                                 | 5.102      | $               | Dollars         | Table 13- Orzechowski and Walker, Tax Burden on Tobacco | POL         | 450POL  | 450CGS    | 455CGS       | 1                        | 
| AL           | Alabama      | 2014 | OW         | The Tax Burden on Tobacco | Cigarette Sales | Cigarette Consumption (Pack Sales Per Capita)         | 61.7       |                 | Pack            | Table 11- Orzechowski and Walker, Tax Burden on Tobacco | POL         | 450POL  | 450CGS    | 453CGS       | 2                        | 
| AL           | Alabama      | 2014 | OW         | The Tax Burden on Tobacco | Cigarette Sales | Federal and State tax as a Percentage of Retail Price | 28.1       | %               | Percentage      | Table 13- Orzechowski and Walker, Tax Burden on Tobacco | POL         | 450POL  | 450CGS    | 454CGS       | 3                        | 
| AL           | Alabama      | 2014 | OW         | The Tax Burden on Tobacco | Cigarette Sales | Federal and State Tax per pack                        | 1.435      | $               | Dollars         | Table 13- Orzechowski and Walker, Tax Burden on Tobacco | POL         | 450POL  | 450CGS    | 452CGS       | 4                        | 
| AL           | Alabama      | 2014 | OW         | The Tax Burden on Tobacco | Cigarette Sales | Gross Cigarette Tax Revenue                           | 126853195  | $               | Dollars         | Table 12- Orzechowski and Walker, Tax Burden on Tobacco | POL         | 450POL  | 450CGS    | 456CGS       | 5                        | 
| AL           | Alabama      | 2014 | OW         | The Tax Burden on Tobacco | Cigarette Sales | State Tax per pack                                    | 0.425      | $               | Dollars         | Table 7- Orzechowski and Walker, Tax Burden on Tobacco  | POL         | 450POL  | 450CGS    | 451CGS       | 6                        | 
| AK           | Alaska       | 2014 | OW         | The Tax Burden on Tobacco | Cigarette Sales | Average Cost per pack                                 | 8.901      | $               | Dollars         | Table 13- Orzechowski and Walker, Tax Burden on Tobacco | POL         | 450POL  | 450CGS    | 455CGS       | 1                        | 
| AK           | Alaska       | 2014 | OW         | The Tax Burden on Tobacco | Cigarette Sales | Cigarette Consumption (Pack Sales Per Capita)         | 37.2       |                 | Pack            | Table 11- Orzechowski and Walker, Tax Burden on Tobacco | POL         | 450POL  | 450CGS    | 453CGS       | 2                        | 
| AK           | Alaska       | 2014 | OW         | The Tax Burden on Tobacco | Cigarette Sales | Federal and State tax as a Percentage of Retail Price | 33.8       | %               | Percentage      | Table 13- Orzechowski and Walker, Tax Burden on Tobacco | POL         | 450POL  | 450CGS    | 454CGS       | 3                        | 
| AK           | Alaska       | 2014 | OW         | The Tax Burden on Tobacco | Cigarette Sales | Federal and State Tax per pack                        | 3.01       | $               | Dollars         | Table 13- Orzechowski and Walker, Tax Burden on Tobacco | POL         | 450POL  | 450CGS    | 452CGS       | 4                        | 
```