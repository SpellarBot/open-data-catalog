# The Tax Burden on Tobacco Volume 51, 1970-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/the-tax-burden-on-tobacco-volume-49-1970-2014) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/7nwe-3aj9) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/7nwe-3aj9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/7nwe-3aj9/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | 7nwe-3aj9 |
| Name | The Tax Burden on Tobacco Volume 51, 1970-2016 |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Policy |
| Tags | osh, office on smoking and health, tax, tax burden on tobacco, cigarette sales, average cost per pack |
| Created | 2014-05-27T11:46:47Z |
| Publication Date | 2017-06-19T14:31:12Z |

## Description

1970-2016. Orzechowski and Walker. Tax Burden on Tobacco. Tax burden data was obtained from the annual compendium on tobacco revenue and industry statistics, The Tax Burden on Tobacco. Data are reported on an annual basis; Data include federal and state-level information regarding taxes applied to the price of a pack of cigarettes.

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
series e:7nwe-3aj9 d:1970-01-01T00:00:00.000Z t:measureid=450CGS t:measuredesc="Cigarette Sales" t:topicid=450POL t:submeasureid=455CGS t:datasource=OW t:topictypeid=POL t:locationabbr=AL t:locationdesc=Alabama t:source="Table 13- Orzechowski and Walker, Tax Burden on Tobacco" t:submeasuredesc="Average Cost per pack" t:topicdesc="The Tax Burden on Tobacco" m:data_value=0.427

series e:7nwe-3aj9 d:1970-01-01T00:00:00.000Z t:measureid=450CGS t:measuredesc="Cigarette Sales" t:topicid=450POL t:submeasureid=455CGS t:datasource=OW t:topictypeid=POL t:locationabbr=AK t:locationdesc=Alaska t:source="Table 13- Orzechowski and Walker, Tax Burden on Tobacco" t:submeasuredesc="Average Cost per pack" t:topicdesc="The Tax Burden on Tobacco" m:data_value=0.418

series e:7nwe-3aj9 d:1970-01-01T00:00:00.000Z t:measureid=450CGS t:measuredesc="Cigarette Sales" t:topicid=450POL t:submeasureid=455CGS t:datasource=OW t:topictypeid=POL t:locationabbr=AZ t:locationdesc=Arizona t:source="Table 13- Orzechowski and Walker, Tax Burden on Tobacco" t:submeasuredesc="Average Cost per pack" t:topicdesc="The Tax Burden on Tobacco" m:data_value=0.385
```

## Meta Commands

```ls
metric m:data_value p:double l:Data_Value d:"Value of the data" t:dataTypeName=number

entity e:7nwe-3aj9 l:"The Tax Burden on Tobacco Volume 51, 1970-2016" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://chronicdata.cdc.gov/api/views/7nwe-3aj9

property e:7nwe-3aj9 t:meta.view d:2017-09-25T07:29:59.839Z v:averageRating=0 v:name="The Tax Burden on Tobacco Volume 51, 1970-2016" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" v:attributionLink=http://www.cdc.gov/tobacco/STATESystem v:id=7nwe-3aj9 v:category=Policy

property e:7nwe-3aj9 t:meta.view.license d:2017-09-25T07:29:59.839Z v:name="Public Domain"

property e:7nwe-3aj9 t:meta.view.owner d:2017-09-25T07:29:59.839Z v:displayName=OSHData v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:id=p5wh-zttj v:screenName=OSHData v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB

property e:7nwe-3aj9 t:meta.view.tableauthor d:2017-09-25T07:29:59.839Z v:displayName=OSHData v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:id=p5wh-zttj v:screenName=OSHData v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB

property e:7nwe-3aj9 t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:29:59.839Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Program_Code=009:020 v:Publisher="Centers for Disease Control and Prevention" v:Bureau_Code=009:20 v:Public_Access_Level="Public Domain"
```

## Top Records

```ls
| locationabbr | locationdesc         | year | datasource | topicdesc                 | measuredesc     | submeasuredesc        | data_value | data_value_unit | data_value_type | source                                                  | topictypeid | topicid | measureid | submeasureid | submeasureiddisplayorder | 
| ============ | ==================== | ==== | ========== | ========================= | =============== | ===================== | ========== | =============== | =============== | ======================================================= | =========== | ======= | ========= | ============ | ======================== | 
| AL           | Alabama              | 1970 | OW         | The Tax Burden on Tobacco | Cigarette Sales | Average Cost per pack | 0.427      | $               | Dollars         | Table 13- Orzechowski and Walker, Tax Burden on Tobacco | POL         | 450POL  | 450CGS    | 455CGS       | 1                        | 
| AK           | Alaska               | 1970 | OW         | The Tax Burden on Tobacco | Cigarette Sales | Average Cost per pack | 0.418      | $               | Dollars         | Table 13- Orzechowski and Walker, Tax Burden on Tobacco | POL         | 450POL  | 450CGS    | 455CGS       | 1                        | 
| AZ           | Arizona              | 1970 | OW         | The Tax Burden on Tobacco | Cigarette Sales | Average Cost per pack | 0.385      | $               | Dollars         | Table 13- Orzechowski and Walker, Tax Burden on Tobacco | POL         | 450POL  | 450CGS    | 455CGS       | 1                        | 
| AR           | Arkansas             | 1970 | OW         | The Tax Burden on Tobacco | Cigarette Sales | Average Cost per pack | 0.388      | $               | Dollars         | Table 13- Orzechowski and Walker, Tax Burden on Tobacco | POL         | 450POL  | 450CGS    | 455CGS       | 1                        | 
| CA           | California           | 1970 | OW         | The Tax Burden on Tobacco | Cigarette Sales | Average Cost per pack | 0.397      | $               | Dollars         | Table 13- Orzechowski and Walker, Tax Burden on Tobacco | POL         | 450POL  | 450CGS    | 455CGS       | 1                        | 
| CO           | Colorado             | 1970 | OW         | The Tax Burden on Tobacco | Cigarette Sales | Average Cost per pack | 0.311      | $               | Dollars         | Table 13- Orzechowski and Walker, Tax Burden on Tobacco | POL         | 450POL  | 450CGS    | 455CGS       | 1                        | 
| CT           | Connecticut          | 1970 | OW         | The Tax Burden on Tobacco | Cigarette Sales | Average Cost per pack | 0.455      | $               | Dollars         | Table 13- Orzechowski and Walker, Tax Burden on Tobacco | POL         | 450POL  | 450CGS    | 455CGS       | 1                        | 
| DE           | Delaware             | 1970 | OW         | The Tax Burden on Tobacco | Cigarette Sales | Average Cost per pack | 0.413      | $               | Dollars         | Table 13- Orzechowski and Walker, Tax Burden on Tobacco | POL         | 450POL  | 450CGS    | 455CGS       | 1                        | 
| DC           | District of Columbia | 1970 | OW         | The Tax Burden on Tobacco | Cigarette Sales | Average Cost per pack | 0.326      | $               | Dollars         | Table 13- Orzechowski and Walker, Tax Burden on Tobacco | POL         | 450POL  | 450CGS    | 455CGS       | 1                        | 
| FL           | Florida              | 1970 | OW         | The Tax Burden on Tobacco | Cigarette Sales | Average Cost per pack | 0.438      | $               | Dollars         | Table 13- Orzechowski and Walker, Tax Burden on Tobacco | POL         | 450POL  | 450CGS    | 455CGS       | 1                        | 
```