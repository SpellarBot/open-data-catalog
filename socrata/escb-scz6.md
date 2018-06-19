# SAMHSA Synar Reports: Youth Tobacco Sales

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/samhsa-synar-reports-youth-tobacco-sales-e80ac) |
| Metadata | [Link](https://data.cdc.gov/api/views/escb-scz6) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/escb-scz6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/escb-scz6/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | escb-scz6 |
| Name | SAMHSA Synar Reports: Youth Tobacco Sales |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Policy |
| Tags | cdc, osh, office on smoking and health, tobacco, youth tobacco sales |
| Created | 2014-05-27T11:38:57Z |
| Publication Date | 2016-12-12T17:53:32Z |

## Description

1997-2014. Substance Abuse and Mental Health Services Administration (SAMHSA). Synar Reports: Youth Tobacco Sales. Policy ? Youth Tobacco Sales. SAMHSA?s Synar Report on Youth Tobacco Sales presents findings on compliance of the Synar Amendment aimed at decreasing youth access to tobacco, and reviews progress in enforcing State youth tobacco access laws and in reducing the percentage of retailers selling tobacco products to minors.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | locationabbr               | LocationAbbr               | text      | text        |
| Yes      | series tag     | locationdesc               | LocationDesc               | text      | text        |
| Yes      | time           | ffy_year                   | FFY Year                   | number    | number      |
| Yes      | series tag     | topicdesc                  | TopicDesc                  | text      | text        |
| Yes      | series tag     | measuredesc                | MeasureDesc                | text      | text        |
| Yes      | series tag     | submeasure                 | SubMeasure                 | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | series tag     | source                     | Source                     | text      | text        |
| Yes      | series tag     | topictypeid                | TopicTypeId                | text      | text        |
| Yes      | series tag     | topicid                    | TopicId                    | text      | text        |
| Yes      | series tag     | measureid                  | MeasureId                  | text      | text        |
| Yes      | series tag     | submeasureid               | SubMeasureID               | text      | text        |
| No       |                | displayorder               | DisplayOrder               | number    | text        |
```

## Time Field

```ls
Value = ffy_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_unit,data_value_type,data_value_footnote_symbol,data_value_footnote,displayorder
```

## Data Commands

```ls
series e:escb-scz6 d:2013-01-01T00:00:00.000Z t:locationabbr=AL t:locationdesc=Alabama t:topicid=360POL t:source="Substance Abuse and Mental Health Services Administration (SAMHSA). Synar Reports: Tobacco Sales to Youth." t:submeasure="Youth Tobacco Sales - SAMHSA" t:measureid=150STM t:measuredesc="Sales to Minors" t:topicdesc="Synar Report" t:submeasureid=155YTS t:topictypeid=POL m:data_value=8.2

series e:escb-scz6 d:2013-01-01T00:00:00.000Z t:locationabbr=AK t:locationdesc=Alaska t:topicid=360POL t:source="Substance Abuse and Mental Health Services Administration (SAMHSA). Synar Reports: Tobacco Sales to Youth." t:submeasure="Youth Tobacco Sales - SAMHSA" t:measureid=150STM t:measuredesc="Sales to Minors" t:topicdesc="Synar Report" t:submeasureid=155YTS t:topictypeid=POL m:data_value=7.3

series e:escb-scz6 d:2013-01-01T00:00:00.000Z t:locationabbr=AZ t:locationdesc=Arizona t:topicid=360POL t:source="Substance Abuse and Mental Health Services Administration (SAMHSA). Synar Reports: Tobacco Sales to Youth." t:submeasure="Youth Tobacco Sales - SAMHSA" t:measureid=150STM t:measuredesc="Sales to Minors" t:topicdesc="Synar Report" t:submeasureid=155YTS t:topictypeid=POL m:data_value=5.8
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value d:"Value of the data" t:dataTypeName=number

entity e:escb-scz6 l:"SAMHSA Synar Reports: Youth Tobacco Sales" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://data.cdc.gov/api/views/escb-scz6

property e:escb-scz6 t:meta.view v:id=escb-scz6 v:category=Policy v:attributionLink=http://www.samhsa.gov/synar v:averageRating=0 v:name="SAMHSA Synar Reports: Youth Tobacco Sales" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:escb-scz6 t:meta.view.license v:name="Public Domain"

property e:escb-scz6 t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:escb-scz6 t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:escb-scz6 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| locationabbr | locationdesc         | ffy_year | topicdesc    | measuredesc     | submeasure                   | data_value | data_value_unit | data_value_type | data_value_footnote_symbol | data_value_footnote | source                                                                                                     | topictypeid | topicid | measureid | submeasureid | displayorder | 
| ============ | ==================== | ======== | ============ | =============== | ============================ | ========== | =============== | =============== | ========================== | =================== | ========================================================================================================== | =========== | ======= | ========= | ============ | ============ | 
| AL           | Alabama              | 2013     | Synar Report | Sales to Minors | Youth Tobacco Sales - SAMHSA | 8.2        | %               | Percent         |                            |                     | Substance Abuse and Mental Health Services Administration (SAMHSA). Synar Reports: Tobacco Sales to Youth. | POL         | 360POL  | 150STM    | 155YTS       | 1            | 
| AK           | Alaska               | 2013     | Synar Report | Sales to Minors | Youth Tobacco Sales - SAMHSA | 7.3        | %               | Percent         |                            |                     | Substance Abuse and Mental Health Services Administration (SAMHSA). Synar Reports: Tobacco Sales to Youth. | POL         | 360POL  | 150STM    | 155YTS       | 1            | 
| AZ           | Arizona              | 2013     | Synar Report | Sales to Minors | Youth Tobacco Sales - SAMHSA | 5.8        | %               | Percent         |                            |                     | Substance Abuse and Mental Health Services Administration (SAMHSA). Synar Reports: Tobacco Sales to Youth. | POL         | 360POL  | 150STM    | 155YTS       | 1            | 
| AR           | Arkansas             | 2013     | Synar Report | Sales to Minors | Youth Tobacco Sales - SAMHSA | 3.3        | %               | Percent         |                            |                     | Substance Abuse and Mental Health Services Administration (SAMHSA). Synar Reports: Tobacco Sales to Youth. | POL         | 360POL  | 150STM    | 155YTS       | 1            | 
| CA           | California           | 2013     | Synar Report | Sales to Minors | Youth Tobacco Sales - SAMHSA | 8.7        | %               | Percent         |                            |                     | Substance Abuse and Mental Health Services Administration (SAMHSA). Synar Reports: Tobacco Sales to Youth. | POL         | 360POL  | 150STM    | 155YTS       | 1            | 
| CO           | Colorado             | 2013     | Synar Report | Sales to Minors | Youth Tobacco Sales - SAMHSA | 9.1        | %               | Percent         |                            |                     | Substance Abuse and Mental Health Services Administration (SAMHSA). Synar Reports: Tobacco Sales to Youth. | POL         | 360POL  | 150STM    | 155YTS       | 1            | 
| CT           | Connecticut          | 2013     | Synar Report | Sales to Minors | Youth Tobacco Sales - SAMHSA | 12.1       | %               | Percent         |                            |                     | Substance Abuse and Mental Health Services Administration (SAMHSA). Synar Reports: Tobacco Sales to Youth. | POL         | 360POL  | 150STM    | 155YTS       | 1            | 
| DE           | Delaware             | 2013     | Synar Report | Sales to Minors | Youth Tobacco Sales - SAMHSA | 9.5        | %               | Percent         |                            |                     | Substance Abuse and Mental Health Services Administration (SAMHSA). Synar Reports: Tobacco Sales to Youth. | POL         | 360POL  | 150STM    | 155YTS       | 1            | 
| DC           | District of Columbia | 2013     | Synar Report | Sales to Minors | Youth Tobacco Sales - SAMHSA | 8.6        | %               | Percent         |                            |                     | Substance Abuse and Mental Health Services Administration (SAMHSA). Synar Reports: Tobacco Sales to Youth. | POL         | 360POL  | 150STM    | 155YTS       | 1            | 
| FL           | Florida              | 2013     | Synar Report | Sales to Minors | Youth Tobacco Sales - SAMHSA | 13.8       | %               | Percent         |                            |                     | Substance Abuse and Mental Health Services Administration (SAMHSA). Synar Reports: Tobacco Sales to Youth. | POL         | 360POL  | 150STM    | 155YTS       | 1            | 
```