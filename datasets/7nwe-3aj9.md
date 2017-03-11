# The Tax Burden on Tobacco Volume 49, 1970-2014

## Dataset

* [Dataset URL](https://chronicdata.cdc.gov/api/views/7nwe-3aj9/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/the-tax-burden-on-tobacco-volume-49-1970-2014)
* Id = 7nwe-3aj9
* Name = The Tax Burden on Tobacco Volume 49, 1970-2014
* Attribution = Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health
* Attribution Link = http://www.cdc.gov/tobacco/STATESystem
* Category = Policy
* Tags = [osh, office on smoking and health, tax, tax burden on tobacco, cigarette sales, average cost per pack]
* Created = 2014-05-27T11:46:47Z
* Publication Date = 2017-02-07T12:20:46Z
* Rows Updated = 2017-02-06T18:22:12Z

## Description

1970-2014. Orzechowski and Walker. Tax Burden on Tobacco. Tax burden data was obtained from the annual compendium on tobacco revenue and industry statistics, The Tax Burden on Tobacco. Data are reported on an annual basis; Data include federal and state-level information regarding taxes applied to the price of a pack of cigarettes.

## Columns

```ls
| Name                     | Field Name               | Data Type | Render Type | Schema Type    | Included | 
| ======================== | ======================== | ========= | =========== | ============== | ======== | 
| LocationAbbr             | locationabbr             | text      | text        | series tag     | Yes      | 
| LocationDesc             | locationdesc             | text      | text        | series tag     | Yes      | 
| Year                     | year                     | number    | number      | time           | Yes      | 
| Datasource               | datasource               | text      | text        | series tag     | Yes      | 
| TopicDesc                | topicdesc                | text      | text        | series tag     | Yes      | 
| MeasureDesc              | measuredesc              | text      | text        | series tag     | Yes      | 
| SubMeasureDesc           | submeasuredesc           | text      | text        | series tag     | Yes      | 
| Data_Value               | data_value               | number    | number      | numeric metric | Yes      | 
| Data_Value_Unit          | data_value_unit          | number    | text        |                | No       | 
| Data_Value_Type          | data_value_type          | text      | text        |                | No       | 
| Source                   | source                   | text      | text        | series tag     | Yes      | 
| TopicTypeId              | topictypeid              | text      | text        | series tag     | Yes      | 
| TopicId                  | topicid                  | text      | text        | series tag     | Yes      | 
| MeasureId                | measureid                | text      | text        | series tag     | Yes      | 
| SubMeasureID             | submeasureid             | text      | text        | series tag     | Yes      | 
| SubMeasureIdDisplayOrder | submeasureiddisplayorder | number    | text        | numeric metric | Yes      | 
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
Excluded Fields = data_value_unit,data_value_type
Annotation Fields = 
```

## Data Commands

```ls
series e:7nwe-3aj9 d:2014-01-01T00:00:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:topicid=450POL t:source="Table 13- Orzechowski and Walker, Tax Burden on Tobacco" t:measureid=450CGS t:measuredesc="Cigarette Sales" t:submeasuredesc="Average Cost per pack" t:topicdesc="The Tax Burden on Tobacco" t:submeasureid=455CGS t:datasource=OW t:topictypeid=POL m:submeasureiddisplayorder=1 m:data_value=5.102

series e:7nwe-3aj9 d:2014-01-01T00:00:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:topicid=450POL t:source="Table 11- Orzechowski and Walker, Tax Burden on Tobacco" t:measureid=450CGS t:measuredesc="Cigarette Sales" t:submeasuredesc="Cigarette Consumption (Pack Sales Per Capita)" t:topicdesc="The Tax Burden on Tobacco" t:submeasureid=453CGS t:datasource=OW t:topictypeid=POL m:submeasureiddisplayorder=2 m:data_value=61.7

series e:7nwe-3aj9 d:2014-01-01T00:00:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:topicid=450POL t:source="Table 13- Orzechowski and Walker, Tax Burden on Tobacco" t:measureid=450CGS t:measuredesc="Cigarette Sales" t:submeasuredesc="Federal and State tax as a Percentage of Retail Price" t:topicdesc="The Tax Burden on Tobacco" t:submeasureid=454CGS t:datasource=OW t:topictypeid=POL m:submeasureiddisplayorder=3 m:data_value=28.1
```

## Meta Commands

```ls
metric m:data_value l:Data_Value d:"Value of the data" t:dataTypeName=number

metric m:submeasureiddisplayorder p:integer l:SubMeasureIdDisplayOrder d:"For programming purposes" t:dataTypeName=number

entity e:7nwe-3aj9 l:"The Tax Burden on Tobacco Volume 49, 1970-2014" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://chronicdata.cdc.gov/api/views/7nwe-3aj9

property e:7nwe-3aj9 t:meta.view d:2017-03-03T14:02:56.450Z v:id=7nwe-3aj9 v:category=Policy v:attributionLink=http://www.cdc.gov/tobacco/STATESystem v:averageRating=0 v:name="The Tax Burden on Tobacco Volume 49, 1970-2014" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:7nwe-3aj9 t:meta.view.owner d:2017-03-03T14:02:56.450Z v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:7nwe-3aj9 t:meta.view.tableauthor d:2017-03-03T14:02:56.450Z v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:7nwe-3aj9 t:meta.view.metadata.custom_fields.common_core d:2017-03-03T14:02:56.450Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```