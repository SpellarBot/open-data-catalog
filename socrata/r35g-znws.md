# Heart Disease Mortality Data Among US Adults (35+) by State/Territory and County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/heart-disease-mortality-data-among-us-adults-35-by-state-territory-and-county) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/r35g-znws) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/r35g-znws/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/r35g-znws/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | r35g-znws |
| Name | Heart Disease Mortality Data Among US Adults (35+) by State/Territory and County |
| Attribution | CDC Division for Heart Disease and Stroke Prevention, Interactive Atlas of Heart Disease and Stroke |
| Category | Heart Disease & Stroke Prevention |
| Tags | heart disease, cardiovascular disease, county |
| Created | 2016-09-20T19:55:48Z |
| Publication Date | 2016-09-26T17:17:55Z |

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
series e:r35g-znws d:2013-01-01T00:00:00.000Z t:geographiclevel=County t:topic="Heart Disease Mortality" t:locationabbr=AK t:locationdesc="Aleutians East" t:topicid=T2 t:locationid=02013 t:stratificationcategory2=Race/Ethnicity t:stratification1=Overall t:stratificationcategory1=Gender t:stratification2=Overall t:class="Cardiovascular Diseases" t:datasource=NVSS m:data_value=147.4

series e:r35g-znws d:2013-01-01T00:00:00.000Z t:geographiclevel=County t:topic="Heart Disease Mortality" t:locationabbr=AK t:locationdesc="Aleutians West" t:topicid=T2 t:locationid=02016 t:stratificationcategory2=Race/Ethnicity t:stratification1=Overall t:stratificationcategory1=Gender t:stratification2=Overall t:class="Cardiovascular Diseases" t:datasource=NVSS m:data_value=229.4

series e:r35g-znws d:2013-01-01T00:00:00.000Z t:geographiclevel=County t:topic="Heart Disease Mortality" t:locationabbr=AK t:locationdesc=Anchorage t:topicid=T2 t:locationid=02020 t:stratificationcategory2=Race/Ethnicity t:stratification1=Overall t:stratificationcategory1=Gender t:stratification2=Overall t:class="Cardiovascular Diseases" t:datasource=NVSS m:data_value=255.5
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value t:dataTypeName=number

entity e:r35g-znws l:"Heart Disease Mortality Data Among US Adults (35+) by State/Territory and County" t:attribution="CDC Division for Heart Disease and Stroke Prevention, Interactive Atlas of Heart Disease and Stroke" t:url=https://chronicdata.cdc.gov/api/views/r35g-znws

property e:r35g-znws t:meta.view v:id=r35g-znws v:category="Heart Disease & Stroke Prevention" v:attributionLink=http://www.cdc.gov/dhdsp/maps/atlas v:averageRating=0 v:name="Heart Disease Mortality Data Among US Adults (35+) by State/Territory and County" v:attribution="CDC Division for Heart Disease and Stroke Prevention, Interactive Atlas of Heart Disease and Stroke"

property e:r35g-znws t:meta.view.owner v:id=a7ta-3b7u v:screenName=lschieb v:lastNotificationSeenAt=1492029398 v:displayName=lschieb

property e:r35g-znws t:meta.view.tableauthor v:id=a7ta-3b7u v:screenName=lschieb v:roleName=publisher v:lastNotificationSeenAt=1492029398 v:displayName=lschieb

property e:r35g-znws t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | locationabbr | locationdesc         | geographiclevel | datasource | class                   | topic                   | data_value | data_value_unit        | data_value_type                                       | data_value_footnote_symbol | data_value_footnote | stratificationcategory1 | stratification1 | stratificationcategory2 | stratification2 | topicid | locationid | 
| ==== | ============ | ==================== | =============== | ========== | ======================= | ======================= | ========== | ====================== | ===================================================== | ========================== | =================== | ======================= | =============== | ======================= | =============== | ======= | ========== | 
| 2013 | AK           | Aleutians East       | County          | NVSS       | Cardiovascular Diseases | Heart Disease Mortality | 147.4      | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate |                            |                     | Gender                  | Overall         | Race/Ethnicity          | Overall         | T2      | 02013      | 
| 2013 | AK           | Aleutians West       | County          | NVSS       | Cardiovascular Diseases | Heart Disease Mortality | 229.4      | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate |                            |                     | Gender                  | Overall         | Race/Ethnicity          | Overall         | T2      | 02016      | 
| 2013 | AK           | Anchorage            | County          | NVSS       | Cardiovascular Diseases | Heart Disease Mortality | 255.5      | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate |                            |                     | Gender                  | Overall         | Race/Ethnicity          | Overall         | T2      | 02020      | 
| 2013 | AK           | Bethel               | County          | NVSS       | Cardiovascular Diseases | Heart Disease Mortality | 305.5      | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate |                            |                     | Gender                  | Overall         | Race/Ethnicity          | Overall         | T2      | 02050      | 
| 2013 | AK           | Bristol Bay          | County          | NVSS       | Cardiovascular Diseases | Heart Disease Mortality |            | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate | ~                          | Insufficient Data   | Gender                  | Overall         | Race/Ethnicity          | Overall         | T2      | 02060      | 
| 2013 | AK           | Denali               | County          | NVSS       | Cardiovascular Diseases | Heart Disease Mortality | 281.7      | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate |                            |                     | Gender                  | Overall         | Race/Ethnicity          | Overall         | T2      | 02068      | 
| 2013 | AK           | Dillingham           | County          | NVSS       | Cardiovascular Diseases | Heart Disease Mortality | 340        | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate |                            |                     | Gender                  | Overall         | Race/Ethnicity          | Overall         | T2      | 02070      | 
| 2013 | AK           | Fairbanks North Star | County          | NVSS       | Cardiovascular Diseases | Heart Disease Mortality | 285.7      | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate |                            |                     | Gender                  | Overall         | Race/Ethnicity          | Overall         | T2      | 02090      | 
| 2013 | AK           | Haines               | County          | NVSS       | Cardiovascular Diseases | Heart Disease Mortality | 288.4      | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate |                            |                     | Gender                  | Overall         | Race/Ethnicity          | Overall         | T2      | 02100      | 
| 2013 | AK           | Juneau               | County          | NVSS       | Cardiovascular Diseases | Heart Disease Mortality | 288.4      | per 100,000 population | Age-adjusted, Spatially Smoothed, 3-year Average Rate |                            |                     | Gender                  | Overall         | Race/Ethnicity          | Overall         | T2      | 02110      | 
```