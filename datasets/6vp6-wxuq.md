# 500 Cities: Local Data for Better Health

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/500-cities-local-data-for-better-health-fc759) |
| Metadata | [Link](https://data.cdc.gov/api/views/6vp6-wxuq) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/6vp6-wxuq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/6vp6-wxuq/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 6vp6-wxuq |
| Name | 500 Cities: Local Data for Better Health |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Population Health |
| Category | 500 Cities |
| Tags | 500cities, cities, census, tracts, brfss, prevalence, unhealthy, behaviors, outcomes, prevention |
| Created | 2016-10-28T15:57:26Z |
| Publication Date | 2017-02-15T18:21:02Z |

## Description

This is the complete dataset for the 500 Cities project. This dataset includes 2013, 2014 model-based small area estimates for 27 measures of chronic disease related to unhealthy behaviors (5), health outcomes (13), and use of preventive services (9). Data were provided by the Centers for Disease Control and Prevention (CDC), Division of Population Health, Epidemiology and Surveillance Branch. The project was funded by the Robert Wood Johnson Foundation (RWJF) in conjunction with the CDC Foundation. It represents a first-of-its kind effort to release information on a large scale for cities and for small areas within those cities. It includes estimates for the 500 largest US cities and approximately 28,000 census tracts within these cities. These estimates can be used to identify emerging health problems and to inform development and implementation of effective, targeted public health prevention activities. Because the small area model cannot detect effects due to local interventions, users are cautioned against using these estimates for program or policy evaluations. Data sources used to generate these measures include Behavioral Risk Factor Surveillance System (BRFSS) data (2013, 2014), Census Bureau 2010 census population data, and American Community Survey (ACS) 2009-2013, 2010-2014 estimates. More information about the methodology can be found at www.cdc.gov/500cities.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | series tag     | stateabbr                  | StateAbbr                  | text      | text        |
| Yes      | series tag     | statedesc                  | StateDesc                  | text      | text        |
| Yes      | series tag     | cityname                   | CityName                   | text      | text        |
| Yes      | series tag     | geographiclevel            | GeographicLevel            | text      | text        |
| Yes      | series tag     | datasource                 | DataSource                 | text      | text        |
| Yes      | series tag     | category                   | Category                   | text      | text        |
| Yes      | series tag     | uniqueid                   | UniqueID                   | text      | text        |
| Yes      | series tag     | measure                    | Measure                    | text      | text        |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| Yes      | series tag     | datavaluetypeid            | DataValueTypeID            | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| Yes      | numeric metric | low_confidence_limit       | Low_Confidence_Limit       | number    | number      |
| Yes      | numeric metric | high_confidence_limit      | High_Confidence_Limit      | number    | number      |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | numeric metric | populationcount            | PopulationCount            | number    | number      |
| Yes      | series tag     | categoryid                 | CategoryID                 | text      | text        |
| Yes      | series tag     | measureid                  | MeasureId                  | text      | text        |
| Yes      | series tag     | cityfips                   | CityFIPS                   | text      | text        |
| Yes      | series tag     | tractfips                  | TractFIPS                  | text      | text        |
| Yes      | series tag     | short_question_text        | Short_Question_Text        | text      | text        |
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
series e:6vp6-wxuq d:2014-01-01T00:00:00.000Z t:geographiclevel=US t:statedesc="United States" t:uniqueid=59 t:categoryid=PREVENT t:category=Prevention t:stateabbr=US t:measure="Current lack of health insurance among adults aged 18?64 Years" t:short_question_text="Health Insurance" t:measureid=ACCESS2 t:datasource=BRFSS t:datavaluetypeid=AgeAdjPrv m:high_confidence_limit=15.2 m:populationcount=308745538 m:data_value=14.9 m:low_confidence_limit=14.6

series e:6vp6-wxuq d:2014-01-01T00:00:00.000Z t:geographiclevel=US t:statedesc="United States" t:uniqueid=59 t:categoryid=PREVENT t:category=Prevention t:stateabbr=US t:measure="Current lack of health insurance among adults aged 18?64 Years" t:short_question_text="Health Insurance" t:measureid=ACCESS2 t:datasource=BRFSS t:datavaluetypeid=CrdPrv m:high_confidence_limit=14.3 m:populationcount=308745538 m:data_value=14.1 m:low_confidence_limit=13.8

series e:6vp6-wxuq d:2014-01-01T00:00:00.000Z t:geographiclevel=US t:statedesc="United States" t:uniqueid=59 t:categoryid=HLTHOUT t:category="Health Outcomes" t:stateabbr=US t:measure="Arthritis among adults aged >=18 Years" t:short_question_text=Arthritis t:measureid=ARTHRITIS t:datasource=BRFSS t:datavaluetypeid=AgeAdjPrv m:high_confidence_limit=23.7 m:populationcount=308745538 m:data_value=23.5 m:low_confidence_limit=23.3
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value d:"Data Value, such as 14.7" t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit d:"Low confidence limit" t:dataTypeName=number

metric m:high_confidence_limit p:float l:High_Confidence_Limit d:"High confidence limit" t:dataTypeName=number

metric m:populationcount p:integer l:PopulationCount d:"Population count from census 2010" t:dataTypeName=number

entity e:6vp6-wxuq l:"500 Cities: Local Data for Better Health" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Population Health" t:url=https://data.cdc.gov/api/views/6vp6-wxuq

property e:6vp6-wxuq t:meta.view v:id=6vp6-wxuq v:category="500 Cities" v:attributionLink=http://www.cdc.gov/nccdphp/dph/ v:averageRating=0 v:name="500 Cities: Local Data for Better Health" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Population Health"

property e:6vp6-wxuq t:meta.view.license v:name="Public Domain"

property e:6vp6-wxuq t:meta.view.owner v:id=fwb6-kmt3 v:screenName=hiz4@cdc.gov v:lastNotificationSeenAt=1492540125 v:displayName=hiz4@cdc.gov

property e:6vp6-wxuq t:meta.view.tableauthor v:id=fwb6-kmt3 v:screenName=hiz4@cdc.gov v:roleName=publisher v:lastNotificationSeenAt=1492540125 v:displayName=hiz4@cdc.gov

property e:6vp6-wxuq t:meta.view.metadata.custom_fields.common_core v:Publisher="CDC Info" v:Contact_Email=cdcinfo@cdc.gov v:Public_Access_Level="Public Domain" v:Contact_Name="CDC Info" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | stateabbr | statedesc     | cityname | geographiclevel | datasource | category            | uniqueid | measure                                                                                               | data_value_unit | datavaluetypeid | data_value_type         | data_value | low_confidence_limit | high_confidence_limit | data_value_footnote_symbol | data_value_footnote | populationcount | categoryid | measureid | cityfips | tractfips | short_question_text  | 
| ==== | ========= | ============= | ======== | =============== | ========== | =================== | ======== | ===================================================================================================== | =============== | =============== | ======================= | ========== | ==================== | ===================== | ========================== | =================== | =============== | ========== | ========= | ======== | ========= | ==================== | 
| 2014 | US        | United States |          | US              | BRFSS      | Prevention          | 59       | Current lack of health insurance among adults aged 18?64 Years                                        | %               | AgeAdjPrv       | Age-adjusted prevalence | 14.9       | 14.6                 | 15.2                  |                            |                     | 308745538       | PREVENT    | ACCESS2   |          |           | Health Insurance     | 
| 2014 | US        | United States |          | US              | BRFSS      | Prevention          | 59       | Current lack of health insurance among adults aged 18?64 Years                                        | %               | CrdPrv          | Crude prevalence        | 14.1       | 13.8                 | 14.3                  |                            |                     | 308745538       | PREVENT    | ACCESS2   |          |           | Health Insurance     | 
| 2014 | US        | United States |          | US              | BRFSS      | Health Outcomes     | 59       | Arthritis among adults aged >=18 Years                                                                | %               | AgeAdjPrv       | Age-adjusted prevalence | 23.5       | 23.3                 | 23.7                  |                            |                     | 308745538       | HLTHOUT    | ARTHRITIS |          |           | Arthritis            | 
| 2014 | US        | United States |          | US              | BRFSS      | Health Outcomes     | 59       | Arthritis among adults aged >=18 Years                                                                | %               | CrdPrv          | Crude prevalence        | 25.6       | 25.4                 | 25.9                  |                            |                     | 308745538       | HLTHOUT    | ARTHRITIS |          |           | Arthritis            | 
| 2014 | US        | United States |          | US              | BRFSS      | Unhealthy Behaviors | 59       | Binge drinking among adults aged >=18 Years                                                           | %               | AgeAdjPrv       | Age-adjusted prevalence | 16.8       | 16.6                 | 17.1                  |                            |                     | 308745538       | UNHBEH     | BINGE     |          |           | Binge Drinking       | 
| 2014 | US        | United States |          | US              | BRFSS      | Unhealthy Behaviors | 59       | Binge drinking among adults aged >=18 Years                                                           | %               | CrdPrv          | Crude prevalence        | 16.0       | 15.8                 | 16.2                  |                            |                     | 308745538       | UNHBEH     | BINGE     |          |           | Binge Drinking       | 
| 2013 | US        | United States |          | US              | BRFSS      | Health Outcomes     | 59       | High blood pressure among adults aged >=18 Years                                                      | %               | AgeAdjPrv       | Age-adjusted prevalence | 30.2       | 30.0                 | 30.5                  |                            |                     | 308745538       | HLTHOUT    | BPHIGH    |          |           | High Blood Pressure  | 
| 2013 | US        | United States |          | US              | BRFSS      | Health Outcomes     | 59       | High blood pressure among adults aged >=18 Years                                                      | %               | CrdPrv          | Crude prevalence        | 32.4       | 32.1                 | 32.7                  |                            |                     | 308745538       | HLTHOUT    | BPHIGH    |          |           | High Blood Pressure  | 
| 2013 | US        | United States |          | US              | BRFSS      | Prevention          | 59       | Taking medicine for high blood pressure control among adults aged >=18 Years with high blood pressure | %               | AgeAdjPrv       | Age-adjusted prevalence | 58.2       | 57.5                 | 58.8                  |                            |                     | 308745538       | PREVENT    | BPMED     |          |           | Taking BP Medication | 
| 2013 | US        | United States |          | US              | BRFSS      | Prevention          | 59       | Taking medicine for high blood pressure control among adults aged >=18 Years with high blood pressure | %               | CrdPrv          | Crude prevalence        | 77.1       | 76.6                 | 77.5                  |                            |                     | 308745538       | PREVENT    | BPMED     |          |           | Taking BP Medication | 
```