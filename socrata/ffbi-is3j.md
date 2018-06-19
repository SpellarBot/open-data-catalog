# NAAG Tobacco Settlement Payments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/naag-tobacco-settlement-payments-66b4b) |
| Metadata | [Link](https://data.cdc.gov/api/views/ffbi-is3j) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/ffbi-is3j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/ffbi-is3j/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | ffbi-is3j |
| Name | NAAG Tobacco Settlement Payments |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Policy |
| Tags | osh, office on smoking and health, policy, state system, tobacco, tobacco settlement payments |
| Created | 2014-05-27T12:26:12Z |
| Publication Date | 2017-03-02T14:44:27Z |

## Description

1999-2016. National Association of Attorneys General (NAAG). Policy?Tobacco Settlement Payments. The National Association of Attorneys General (NAAG) provides Tobacco Settlement Revenue data for 46 states participating in the Master Settlement Agreement (MSA) with the four largest tobacco companies in the United States.  Data are reported on an annual basis.  Four states (Florida, Minnesota, Mississippi and Texas) provide the STATE System their Tobacco Settlement Revenue data independently.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | locationabbr               | LocationAbbr               | text      | text        |
| Yes      | series tag     | locationdesc               | LocationDesc               | text      | text        |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | series tag     | topic                      | Topic                      | text      | text        |
| Yes      | series tag     | indicator                  | Indicator                  | text      | text        |
| Yes      | series tag     | submeasure                 | SubMeasure                 | text      | text        |
| Yes      | numeric metric | amount                     | Amount                     | number    | number      |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | series tag     | topictypeid                | TopicTypeId                | text      | text        |
| Yes      | series tag     | topicid                    | TopicId                    | text      | text        |
| Yes      | series tag     | measureid                  | MeasureId                  | text      | text        |
| Yes      | series tag     | source                     | Source                     | text      | text        |
| Yes      | series tag     | submeasureid               | SubMeasureID               | text      | text        |
| No       |                | displayorder               | DisplayOrder               | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_unit,data_value_footnote_symbol,data_value_footnote,displayorder
```

## Data Commands

```ls
series e:ffbi-is3j d:2016-01-01T00:00:00.000Z t:topic="Tobacco Settlement" t:locationabbr=AL t:locationdesc=Alabama t:indicator="Tobacco Settlement Payment" t:topicid=300POL t:source="National Association of Attorneys General" t:submeasure="Tobacco Settlement Revenue - NAAG" t:measureid=325TSR t:submeasureid=330TSR t:topictypeid=POL m:amount=91152731.38

series e:ffbi-is3j d:2016-01-01T00:00:00.000Z t:topic="Tobacco Settlement" t:locationabbr=AK t:locationdesc=Alaska t:indicator="Tobacco Settlement Payment" t:topicid=300POL t:source="National Association of Attorneys General" t:submeasure="Tobacco Settlement Revenue - NAAG" t:measureid=325TSR t:submeasureid=330TSR t:topictypeid=POL m:amount=30394217.63

series e:ffbi-is3j d:2016-01-01T00:00:00.000Z t:topic="Tobacco Settlement" t:locationabbr=AZ t:locationdesc=Arizona t:indicator="Tobacco Settlement Payment" t:topicid=300POL t:source="National Association of Attorneys General" t:submeasure="Tobacco Settlement Revenue - NAAG" t:measureid=325TSR t:submeasureid=330TSR t:topictypeid=POL m:amount=98906897.48
```

## Meta Commands

```ls
metric m:amount p:double l:Amount d:Amount t:dataTypeName=number

entity e:ffbi-is3j l:"NAAG Tobacco Settlement Payments" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://data.cdc.gov/api/views/ffbi-is3j

property e:ffbi-is3j t:meta.view v:id=ffbi-is3j v:category=Policy v:attributionLink=http://www.naag.org/tobacco.php v:averageRating=0 v:name="NAAG Tobacco Settlement Payments" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:ffbi-is3j t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:ffbi-is3j t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:ffbi-is3j t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| locationabbr | locationdesc         | year | topic              | indicator                  | submeasure                        | amount       | data_value_unit | data_value_footnote_symbol | data_value_footnote | topictypeid | topicid | measureid | source                                    | submeasureid | displayorder | 
| ============ | ==================== | ==== | ================== | ========================== | ================================= | ============ | =============== | ========================== | =================== | =========== | ======= | ========= | ========================================= | ============ | ============ | 
| AL           | Alabama              | 2016 | Tobacco Settlement | Tobacco Settlement Payment | Tobacco Settlement Revenue - NAAG | 91152731.38  | $               |                            |                     | POL         | 300POL  | 325TSR    | National Association of Attorneys General | 330TSR       | 1            | 
| AK           | Alaska               | 2016 | Tobacco Settlement | Tobacco Settlement Payment | Tobacco Settlement Revenue - NAAG | 30394217.63  | $               |                            |                     | POL         | 300POL  | 325TSR    | National Association of Attorneys General | 330TSR       | 1            | 
| AZ           | Arizona              | 2016 | Tobacco Settlement | Tobacco Settlement Payment | Tobacco Settlement Revenue - NAAG | 98906897.48  | $               |                            |                     | POL         | 300POL  | 325TSR    | National Association of Attorneys General | 330TSR       | 1            | 
| AR           | Arkansas             | 2016 | Tobacco Settlement | Tobacco Settlement Payment | Tobacco Settlement Revenue - NAAG | 49158346.98  | $               |                            |                     | POL         | 300POL  | 325TSR    | National Association of Attorneys General | 330TSR       | 1            | 
| CA           | California           | 2016 | Tobacco Settlement | Tobacco Settlement Payment | Tobacco Settlement Revenue - NAAG | 713588532.35 | $               |                            |                     | POL         | 300POL  | 325TSR    | National Association of Attorneys General | 330TSR       | 1            | 
| CO           | Colorado             | 2016 | Tobacco Settlement | Tobacco Settlement Payment | Tobacco Settlement Revenue - NAAG | 92200153.16  | $               |                            |                     | POL         | 300POL  | 325TSR    | National Association of Attorneys General | 330TSR       | 1            | 
| CT           | Connecticut          | 2016 | Tobacco Settlement | Tobacco Settlement Payment | Tobacco Settlement Revenue - NAAG | 120448144.58 | $               |                            |                     | POL         | 300POL  | 325TSR    | National Association of Attorneys General | 330TSR       | 1            | 
| DE           | Delaware             | 2016 | Tobacco Settlement | Tobacco Settlement Payment | Tobacco Settlement Revenue - NAAG | 27098153.42  | $               |                            |                     | POL         | 300POL  | 325TSR    | National Association of Attorneys General | 330TSR       | 1            | 
| DC           | District of Columbia | 2016 | Tobacco Settlement | Tobacco Settlement Payment | Tobacco Settlement Revenue - NAAG | 37384422.76  | $               |                            |                     | POL         | 300POL  | 325TSR    | National Association of Attorneys General | 330TSR       | 1            | 
| GA           | Georgia              | 2016 | Tobacco Settlement | Tobacco Settlement Payment | Tobacco Settlement Revenue - NAAG | 137034756.76 | $               |                            |                     | POL         | 300POL  | 325TSR    | National Association of Attorneys General | 330TSR       | 1            | 
```