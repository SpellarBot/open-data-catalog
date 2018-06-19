# Stroke Mortality Data Among US Adults (35+) by State/Territory and County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/stroke-mortality-data-among-us-adults-35-by-state-territory-and-county-50ff2) |
| Metadata | [Link](https://data.cdc.gov/api/views/dhsy-4sea) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/dhsy-4sea/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/dhsy-4sea/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | dhsy-4sea |
| Name | Stroke Mortality Data Among US Adults (35+) by State/Territory and County |
| Attribution | CDC Division for Heart Disease and Stroke Prevention, Interactive Atlas of Heart Disease and Stroke |
| Category | Heart Disease & Stroke Prevention |
| Tags | stroke, cerebrovascular disease, cardiovascular disease, county |
| Created | 2016-09-20T20:29:19Z |
| Publication Date | 2016-09-26T17:17:40Z |

## Description

2012 to 2014, 3-year average. Rates are age-standardized. County rates are spatially smoothed. The data can be viewed by gender and race/ethnicity. Data source: National Vital Statistics System. Additional data, maps, and methodology can be viewed on the Interactive Atlas of Heart Disease and Stroke http://www.cdc.gov/dhdsp/maps/atlas

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | series tag     | locationabbr               | LocationAbbr               | text      | text        |
| Yes      | series tag     | locationdesc               | LocationDesc               | text      | text        |
| Yes      | series tag     | geographiclevel            | GeographicLevel            | text      | text        |
| Yes      | series tag     | datasource                 | DataSource                 | text      | text        |
| Yes      | series tag     | class                      | Class                      | text      | text        |
| Yes      | series tag     | topic                      | Topic                      | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | series tag     | stratificationcategory1    | StratificationCategory1    | text      | text        |
| Yes      | series tag     | stratification1            | Stratification1            | text      | text        |
| Yes      | series tag     | stratificationcategory2    | StratificationCategory2    | text      | text        |
| Yes      | series tag     | stratification2            | Stratification2            | text      | text        |
| Yes      | series tag     | topicid                    | TopicID                    | text      | text        |
| Yes      | series tag     | locationid                 | LocationID                 | text      | text        |
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
series e:dhsy-4sea d:2013-01-01T00:00:00.000Z t:geographiclevel=County t:topic="Stroke Mortality" t:locationabbr=AK t:locationdesc=Anchorage t:topicid=T6 t:locationid=02020 t:stratificationcategory2=Race/Ethnicity t:stratification1=Overall t:stratificationcategory1=Gender t:stratification2=Overall t:class="Cardiovascular Diseases" t:datasource=NVSS m:data_value=70.7

series e:dhsy-4sea d:2013-01-01T00:00:00.000Z t:geographiclevel=County t:topic="Stroke Mortality" t:locationabbr=AK t:locationdesc=Bethel t:topicid=T6 t:locationid=02050 t:stratificationcategory2=Race/Ethnicity t:stratification1=Overall t:stratificationcategory1=Gender t:stratification2=Overall t:class="Cardiovascular Diseases" t:datasource=NVSS m:data_value=95

series e:dhsy-4sea d:2013-01-01T00:00:00.000Z t:geographiclevel=County t:topic="Stroke Mortality" t:locationabbr=AK t:locationdesc=Denali t:topicid=T6 t:locationid=02068 t:stratificationcategory2=Race/Ethnicity t:stratification1=Overall t:stratificationcategory1=Gender t:stratification2=Overall t:class="Cardiovascular Diseases" t:datasource=NVSS m:data_value=77.2
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value t:dataTypeName=number

entity e:dhsy-4sea l:"Stroke Mortality Data Among US Adults (35+) by State/Territory and County" t:attribution="CDC Division for Heart Disease and Stroke Prevention, Interactive Atlas of Heart Disease and Stroke" t:url=https://data.cdc.gov/api/views/dhsy-4sea

property e:dhsy-4sea t:meta.view v:id=dhsy-4sea v:category="Heart Disease & Stroke Prevention" v:attributionLink=http://www.cdc.gov/dhdsp/maps/atlas v:averageRating=0 v:name="Stroke Mortality Data Among US Adults (35+) by State/Territory and County" v:attribution="CDC Division for Heart Disease and Stroke Prevention, Interactive Atlas of Heart Disease and Stroke"

property e:dhsy-4sea t:meta.view.owner v:id=a7ta-3b7u v:screenName=lschieb v:lastNotificationSeenAt=1492029398 v:displayName=lschieb

property e:dhsy-4sea t:meta.view.tableauthor v:id=a7ta-3b7u v:screenName=lschieb v:roleName=publisher v:lastNotificationSeenAt=1492029398 v:displayName=lschieb

property e:dhsy-4sea t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | locationabbr | locationdesc         | geographiclevel | datasource | class                   | topic            | data_value | data_value_unit        | data_value_type                                       | data_value_footnote_symbol | data_value_footnote | stratificationcategory1 | stratification1 | stratificationcategory2 | stratification2 | topicid | locationid | 
| ==== | ============ | ==================== | =============== | ========== | ======================= | ================ | ========== | ====================== | ===================================================== | ========================== | =================== | ======================= | =============== | ======================= | =============== | ======= | ========== | 
| 2013 | AK           | Aleutians East       | County          | NVSS       | Cardiovascular Diseases | Stroke Mortality |            | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate | ~                          | Insufficient Data   | Gender                  | Overall         | Race/Ethnicity          | Overall         | T6      | 02013      | 
| 2013 | AK           | Aleutians West       | County          | NVSS       | Cardiovascular Diseases | Stroke Mortality |            | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate | ~                          | Insufficient Data   | Gender                  | Overall         | Race/Ethnicity          | Overall         | T6      | 02016      | 
| 2013 | AK           | Anchorage            | County          | NVSS       | Cardiovascular Diseases | Stroke Mortality | 70.7       | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate |                            |                     | Gender                  | Overall         | Race/Ethnicity          | Overall         | T6      | 02020      | 
| 2013 | AK           | Bethel               | County          | NVSS       | Cardiovascular Diseases | Stroke Mortality | 95         | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate |                            |                     | Gender                  | Overall         | Race/Ethnicity          | Overall         | T6      | 02050      | 
| 2013 | AK           | Bristol Bay          | County          | NVSS       | Cardiovascular Diseases | Stroke Mortality |            | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate | ~                          | Insufficient Data   | Gender                  | Overall         | Race/Ethnicity          | Overall         | T6      | 02060      | 
| 2013 | AK           | Denali               | County          | NVSS       | Cardiovascular Diseases | Stroke Mortality | 77.2       | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate |                            |                     | Gender                  | Overall         | Race/Ethnicity          | Overall         | T6      | 02068      | 
| 2013 | AK           | Dillingham           | County          | NVSS       | Cardiovascular Diseases | Stroke Mortality | 113        | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate |                            |                     | Gender                  | Overall         | Race/Ethnicity          | Overall         | T6      | 02070      | 
| 2013 | AK           | Fairbanks North Star | County          | NVSS       | Cardiovascular Diseases | Stroke Mortality | 77.5       | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate |                            |                     | Gender                  | Overall         | Race/Ethnicity          | Overall         | T6      | 02090      | 
| 2013 | AK           | Haines               | County          | NVSS       | Cardiovascular Diseases | Stroke Mortality | 64.3       | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate |                            |                     | Gender                  | Overall         | Race/Ethnicity          | Overall         | T6      | 02100      | 
| 2013 | AK           | Juneau               | County          | NVSS       | Cardiovascular Diseases | Stroke Mortality | 65.7       | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate |                            |                     | Gender                  | Overall         | Race/Ethnicity          | Overall         | T6      | 02110      | 
```