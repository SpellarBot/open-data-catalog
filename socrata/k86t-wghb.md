# 500 Cities: Census Tract-level Data (GIS Friendly Format)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/500-cities-census-tract-level-data-gis-friendly-format) |
| Metadata | [Link](https://data.cdc.gov/api/views/k86t-wghb) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/k86t-wghb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/k86t-wghb/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | k86t-wghb |
| Name | 500 Cities: Census Tract-level Data (GIS Friendly Format) |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Population Health |
| Category | 500 Cities |
| Tags | 500cities, cities, census, tract, gis, prevalence, unhealthy, behaviors, outcomes, prevention |
| Created | 2016-11-02T20:01:28Z |
| Publication Date | 2016-11-04T18:32:13Z |

## Description

2013, 2014. Data were provided by the Centers for Disease Control and Prevention (CDC), Division of Population Health, Epidemiology and Surveillance Branch. The project was funded by the Robert Wood Johnson Foundation (RWJF) in conjunction with the CDC Foundation. 500 cities project census tract-level data in GIS-friendly format. This dataset can be joined with census tract spatial data in a geographic information system (GIS) to produce maps of 27 measures at the census tract level.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| No       | time           | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag     | stateabbr              | StateAbbr              | text      | text        |
| Yes      | series tag     | placename              | PlaceName              | text      | text        |
| Yes      | series tag     | placefips              | PlaceFIPS              | text      | text        |
| Yes      | series tag     | tractfips              | TractFIPS              | text      | text        |
| Yes      | series tag     | place_tractid          | Place_TractID          | text      | text        |
| Yes      | numeric metric | population2010         | population2010         | number    | number      |
| Yes      | numeric metric | access2_crudeprev      | ACCESS2_CrudePrev      | number    | number      |
| Yes      | series tag     | access2_crude95ci      | ACCESS2_Crude95CI      | text      | text        |
| Yes      | numeric metric | arthritis_crudeprev    | ARTHRITIS_CrudePrev    | number    | number      |
| Yes      | series tag     | arthritis_crude95ci    | ARTHRITIS_Crude95CI    | text      | text        |
| Yes      | numeric metric | binge_crudeprev        | BINGE_CrudePrev        | number    | number      |
| Yes      | series tag     | binge_crude95ci        | BINGE_Crude95CI        | text      | text        |
| Yes      | numeric metric | bphigh_crudeprev       | BPHIGH_CrudePrev       | number    | number      |
| Yes      | series tag     | bphigh_crude95ci       | BPHIGH_Crude95CI       | text      | text        |
| Yes      | numeric metric | bpmed_crudeprev        | BPMED_CrudePrev        | number    | number      |
| Yes      | series tag     | bpmed_crude95ci        | BPMED_Crude95CI        | text      | text        |
| Yes      | numeric metric | cancer_crudeprev       | CANCER_CrudePrev       | number    | number      |
| Yes      | series tag     | cancer_crude95ci       | CANCER_Crude95CI       | text      | text        |
| Yes      | numeric metric | casthma_crudeprev      | CASTHMA_CrudePrev      | number    | number      |
| Yes      | series tag     | casthma_crude95ci      | CASTHMA_Crude95CI      | text      | text        |
| Yes      | numeric metric | chd_crudeprev          | CHD_CrudePrev          | number    | number      |
| Yes      | series tag     | chd_crude95ci          | CHD_Crude95CI          | text      | text        |
| Yes      | numeric metric | checkup_crudeprev      | CHECKUP_CrudePrev      | number    | number      |
| Yes      | series tag     | checkup_crude95ci      | CHECKUP_Crude95CI      | text      | text        |
| Yes      | numeric metric | cholscreen_crudeprev   | CHOLSCREEN_CrudePrev   | number    | number      |
| Yes      | series tag     | cholscreen_crude95ci   | CHOLSCREEN_Crude95CI   | text      | text        |
| Yes      | numeric metric | colon_screen_crudeprev | COLON_SCREEN_CrudePrev | number    | number      |
| Yes      | series tag     | colon_screen_crude95ci | COLON_SCREEN_Crude95CI | text      | text        |
| Yes      | numeric metric | copd_crudeprev         | COPD_CrudePrev         | number    | number      |
| Yes      | series tag     | copd_crude95ci         | COPD_Crude95CI         | text      | text        |
| Yes      | numeric metric | corem_crudeprev        | COREM_CrudePrev        | number    | number      |
| Yes      | series tag     | corem_crude95ci        | COREM_Crude95CI        | text      | text        |
| Yes      | numeric metric | corew_crudeprev        | COREW_CrudePrev        | number    | number      |
| Yes      | series tag     | corew_crude95ci        | COREW_Crude95CI        | text      | text        |
| Yes      | numeric metric | csmoking_crudeprev     | CSMOKING_CrudePrev     | number    | number      |
| Yes      | series tag     | csmoking_crude95ci     | CSMOKING_Crude95CI     | text      | text        |
| Yes      | numeric metric | dental_crudeprev       | DENTAL_CrudePrev       | number    | number      |
| Yes      | series tag     | dental_crude95ci       | DENTAL_Crude95CI       | text      | text        |
| Yes      | numeric metric | diabetes_crudeprev     | DIABETES_CrudePrev     | number    | number      |
| Yes      | series tag     | diabetes_crude95ci     | DIABETES_Crude95CI     | text      | text        |
| Yes      | numeric metric | highchol_crudeprev     | HIGHCHOL_CrudePrev     | number    | number      |
| Yes      | series tag     | highchol_crude95ci     | HIGHCHOL_Crude95CI     | text      | text        |
| Yes      | numeric metric | kidney_crudeprev       | KIDNEY_CrudePrev       | number    | number      |
| Yes      | series tag     | kidney_crude95ci       | KIDNEY_Crude95CI       | text      | text        |
| Yes      | numeric metric | lpa_crudeprev          | LPA_CrudePrev          | number    | number      |
| Yes      | series tag     | lpa_crude95ci          | LPA_Crude95CI          | text      | text        |
| Yes      | numeric metric | mammouse_crudeprev     | MAMMOUSE_CrudePrev     | number    | number      |
| Yes      | series tag     | mammouse_crude95ci     | MAMMOUSE_Crude95CI     | text      | text        |
| Yes      | numeric metric | mhlth_crudeprev        | MHLTH_CrudePrev        | number    | number      |
| Yes      | series tag     | mhlth_crude95ci        | MHLTH_Crude95CI        | text      | text        |
| Yes      | numeric metric | obesity_crudeprev      | OBESITY_CrudePrev      | number    | number      |
| Yes      | series tag     | obesity_crude95ci      | OBESITY_Crude95CI      | text      | text        |
| Yes      | numeric metric | paptest_crudeprev      | PAPTEST_CrudePrev      | number    | number      |
| Yes      | series tag     | paptest_crude95ci      | PAPTEST_Crude95CI      | text      | text        |
| Yes      | numeric metric | phlth_crudeprev        | PHLTH_CrudePrev        | number    | number      |
| Yes      | series tag     | phlth_crude95ci        | PHLTH_Crude95CI        | text      | text        |
| Yes      | numeric metric | sleep_crudeprev        | SLEEP_CrudePrev        | number    | number      |
| Yes      | series tag     | sleep_crude95ci        | SLEEP_Crude95CI        | text      | text        |
| Yes      | numeric metric | stroke_crudeprev       | STROKE_CrudePrev       | number    | number      |
| Yes      | series tag     | stroke_crude95ci       | STROKE_Crude95CI       | text      | text        |
| Yes      | numeric metric | teethlost_crudeprev    | TEETHLOST_CrudePrev    | number    | number      |
| Yes      | series tag     | teethlost_crude95ci    | TEETHLOST_Crude95CI    | text      | text        |
| No       |                | geolocation            | Geolocation            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = geolocation
```

## Data Commands

```ls
series e:k86t-wghb d:2016-11-02T20:01:58.000Z t:phlth_crude95ci="(19.8, 23.4)" t:colon_screen_crude95ci="(50.7, 57.4)" t:obesity_crude95ci="(41.4, 43.7)" t:kidney_crude95ci="( 3.1,  3.5)" t:mammouse_crude95ci="(70.6, 77.0)" t:placename=Birmingham t:checkup_crude95ci="(75.8, 77.4)" t:diabetes_crude95ci="(15.9, 17.6)" t:corew_crude95ci="(21.9, 28.2)" t:casthma_crude95ci="(12.0, 13.7)" t:bphigh_crude95ci="(45.3, 48.2)" t:cholscreen_crude95ci="(70.5, 75.0)" t:corem_crude95ci="(24.1, 32.1)" t:teethlost_crude95ci="(24.1, 36.3)" t:sleep_crude95ci="(49.1, 51.6)" t:arthritis_crude95ci="(32.9, 35.0)" t:dental_crude95ci="(37.5, 44.3)" t:lpa_crude95ci="(33.7, 39.1)" t:cancer_crude95ci="( 5.3,  5.8)" t:paptest_crude95ci="(73.1, 78.6)" t:highchol_crude95ci="(38.3, 40.8)" t:binge_crude95ci="( 9.8, 10.7)" t:stateabbr=AL t:tractfips=01073000100 t:copd_crude95ci="(10.2, 12.4)" t:stroke_crude95ci="( 4.7,  5.6)" t:access2_crude95ci="(24.2, 31.0)" t:bpmed_crude95ci="(79.4, 81.1)" t:placefips=0107000 t:chd_crude95ci="( 7.3,  8.4)" t:place_tractid=0107000-01073000100 t:mhlth_crude95ci="(18.9, 22.3)" t:csmoking_crude95ci="(24.7, 30.1)" m:kidney_crudeprev=3.3 m:casthma_crudeprev=12.8 m:csmoking_crudeprev=27.3 m:lpa_crudeprev=36.4 m:binge_crudeprev=10.3 m:obesity_crudeprev=42.6 m:bphigh_crudeprev=46.8 m:corew_crudeprev=25.2 m:colon_screen_crudeprev=54.2 m:copd_crudeprev=11.2 m:sleep_crudeprev=50.4 m:arthritis_crudeprev=34 m:mhlth_crudeprev=20.5 m:bpmed_crudeprev=80.3 m:highchol_crudeprev=39.5 m:corem_crudeprev=28.2 m:diabetes_crudeprev=16.8 m:stroke_crudeprev=5.1 m:teethlost_crudeprev=30.2 m:cancer_crudeprev=5.5 m:paptest_crudeprev=76 m:checkup_crudeprev=76.6 m:access2_crudeprev=27.6 m:population2010=3042 m:cholscreen_crudeprev=72.8 m:phlth_crudeprev=21.6 m:mammouse_crudeprev=74.2 m:dental_crudeprev=40.9 m:chd_crudeprev=7.8

series e:k86t-wghb d:2016-11-02T20:01:58.000Z t:phlth_crude95ci="(20.3, 24.4)" t:colon_screen_crude95ci="(46.7, 55.6)" t:obesity_crude95ci="(41.6, 44.3)" t:kidney_crude95ci="( 3.1,  3.7)" t:mammouse_crude95ci="(69.6, 77.5)" t:placename=Birmingham t:checkup_crude95ci="(73.1, 74.8)" t:diabetes_crude95ci="(17.0, 19.1)" t:corew_crude95ci="(19.1, 26.6)" t:casthma_crude95ci="(11.1, 12.8)" t:bphigh_crude95ci="(44.9, 47.5)" t:cholscreen_crude95ci="(68.0, 72.1)" t:corem_crude95ci="(21.5, 29.9)" t:teethlost_crude95ci="(25.6, 41.0)" t:sleep_crude95ci="(47.8, 50.8)" t:arthritis_crude95ci="(31.5, 34.0)" t:dental_crude95ci="(35.0, 42.8)" t:lpa_crude95ci="(34.9, 40.9)" t:cancer_crude95ci="( 4.7,  5.2)" t:paptest_crude95ci="(70.0, 76.4)" t:highchol_crude95ci="(39.2, 41.8)" t:binge_crude95ci="(10.5, 11.5)" t:stateabbr=AL t:tractfips=01073000300 t:copd_crude95ci="( 9.9, 12.4)" t:stroke_crude95ci="( 4.8,  5.9)" t:access2_crude95ci="(28.5, 36.0)" t:bpmed_crude95ci="(79.6, 81.5)" t:placefips=0107000 t:chd_crude95ci="( 7.4,  8.6)" t:place_tractid=0107000-01073000300 t:mhlth_crude95ci="(18.3, 22.0)" t:csmoking_crude95ci="(23.5, 29.8)" m:kidney_crudeprev=3.4 m:casthma_crudeprev=11.9 m:csmoking_crudeprev=26.7 m:lpa_crudeprev=37.9 m:binge_crudeprev=11 m:obesity_crudeprev=43 m:bphigh_crudeprev=46.2 m:corew_crudeprev=22.7 m:colon_screen_crudeprev=51.3 m:copd_crudeprev=11.1 m:sleep_crudeprev=49.4 m:arthritis_crudeprev=32.8 m:mhlth_crudeprev=20.2 m:bpmed_crudeprev=80.6 m:highchol_crudeprev=40.6 m:corem_crudeprev=25.7 m:diabetes_crudeprev=18.1 m:stroke_crudeprev=5.3 m:teethlost_crudeprev=33.3 m:cancer_crudeprev=5 m:paptest_crudeprev=73.2 m:checkup_crudeprev=74 m:access2_crudeprev=32.2 m:population2010=2735 m:cholscreen_crudeprev=70.2 m:phlth_crudeprev=22.3 m:mammouse_crudeprev=74 m:dental_crudeprev=39 m:chd_crudeprev=8

series e:k86t-wghb d:2016-11-02T20:01:58.000Z t:phlth_crude95ci="(22.5, 27.0)" t:colon_screen_crude95ci="(48.0, 56.3)" t:obesity_crude95ci="(45.3, 47.8)" t:kidney_crude95ci="( 3.4,  4.1)" t:mammouse_crude95ci="(69.6, 77.1)" t:placename=Birmingham t:checkup_crude95ci="(76.5, 78.4)" t:diabetes_crude95ci="(19.9, 21.9)" t:corew_crude95ci="(18.3, 25.3)" t:casthma_crude95ci="(12.4, 14.6)" t:bphigh_crude95ci="(50.0, 53.4)" t:cholscreen_crude95ci="(69.4, 74.8)" t:corem_crude95ci="(20.3, 28.6)" t:teethlost_crude95ci="(28.9, 43.5)" t:sleep_crude95ci="(51.2, 53.7)" t:arthritis_crude95ci="(36.0, 38.5)" t:dental_crude95ci="(31.4, 38.8)" t:lpa_crude95ci="(38.3, 44.4)" t:cancer_crude95ci="( 5.3,  5.9)" t:paptest_crude95ci="(69.4, 76.2)" t:highchol_crude95ci="(40.2, 43.5)" t:binge_crude95ci="( 8.7,  9.8)" t:stateabbr=AL t:tractfips=01073000400 t:copd_crude95ci="(11.6, 14.6)" t:stroke_crude95ci="( 5.9,  7.3)" t:access2_crude95ci="(28.0, 35.8)" t:bpmed_crude95ci="(81.5, 83.5)" t:placefips=0107000 t:chd_crude95ci="( 8.4,  9.9)" t:place_tractid=0107000-01073000400 t:mhlth_crude95ci="(20.1, 24.1)" t:csmoking_crude95ci="(26.5, 32.4)" m:kidney_crudeprev=3.8 m:casthma_crudeprev=13.4 m:csmoking_crudeprev=29.3 m:lpa_crudeprev=41.3 m:binge_crudeprev=9.3 m:obesity_crudeprev=46.6 m:bphigh_crudeprev=51.8 m:corew_crudeprev=21.6 m:colon_screen_crudeprev=52.1 m:copd_crudeprev=12.9 m:sleep_crudeprev=52.5 m:arthritis_crudeprev=37.2 m:mhlth_crudeprev=21.9 m:bpmed_crudeprev=82.5 m:highchol_crudeprev=41.8 m:corem_crudeprev=24.3 m:diabetes_crudeprev=20.8 m:stroke_crudeprev=6.5 m:teethlost_crudeprev=36 m:cancer_crudeprev=5.6 m:paptest_crudeprev=72.8 m:checkup_crudeprev=77.5 m:access2_crudeprev=31.8 m:population2010=3338 m:cholscreen_crudeprev=72.2 m:phlth_crudeprev=24.6 m:mammouse_crudeprev=73.6 m:dental_crudeprev=35.1 m:chd_crudeprev=9.1
```

## Meta Commands

```ls
metric m:population2010 p:integer l:population2010 d:"2010 Census population count" t:dataTypeName=number

metric m:access2_crudeprev p:float l:ACCESS2_CrudePrev d:"Model-based estimate for crude prevalence of current lack of health insurance among adults aged 18-64 years" t:dataTypeName=number

metric m:arthritis_crudeprev p:float l:ARTHRITIS_CrudePrev d:"Model-based estimate for crude prevalence of arthritis among adults aged >=18 years" t:dataTypeName=number

metric m:binge_crudeprev p:float l:BINGE_CrudePrev d:"Model-based estimate for crude prevalence of binge drinking among adults aged >=18 years" t:dataTypeName=number

metric m:bphigh_crudeprev p:float l:BPHIGH_CrudePrev d:"Model-based estimate for crude prevalence of high blood pressure among adults aged >=18 years" t:dataTypeName=number

metric m:bpmed_crudeprev p:float l:BPMED_CrudePrev d:"Model-based estimate for crude prevalence of taking medicine for high blood pressure control among adults aged >=18 years with high blood pressure" t:dataTypeName=number

metric m:cancer_crudeprev p:float l:CANCER_CrudePrev d:"Model-based estimate for crude prevalence of cancer (excluding skin cancer) among adults aged >=18 years" t:dataTypeName=number

metric m:casthma_crudeprev p:float l:CASTHMA_CrudePrev d:"Model-based estimate for crude prevalence of current asthma among adults aged >=18 years" t:dataTypeName=number

metric m:chd_crudeprev p:float l:CHD_CrudePrev d:"Model-based estimate for crude prevalence of coronary heart disease among adults aged >=18 years" t:dataTypeName=number

metric m:checkup_crudeprev p:double l:CHECKUP_CrudePrev d:"Model-based estimate for crude prevalence of visits to doctor for routine checkup within the past year among adults aged >=18 years" t:dataTypeName=number

metric m:cholscreen_crudeprev p:float l:CHOLSCREEN_CrudePrev d:"Model-based estimate for crude prevalence of cholesterol screening among adults aged >=18 years" t:dataTypeName=number

metric m:colon_screen_crudeprev p:float l:COLON_SCREEN_CrudePrev d:"Model-based estimate for crude prevalence of fecal occult blood test, sigmoidoscopy, or colonoscopy among adults aged 50?75 years" t:dataTypeName=number

metric m:copd_crudeprev p:float l:COPD_CrudePrev d:"Model-based estimate for crude prevalence of chronic obstructive pulmonary disease among adults aged >=18 years" t:dataTypeName=number

metric m:corem_crudeprev p:float l:COREM_CrudePrev d:"Model-based estimate for crude prevalence of older adult men aged >=65 years who are up to date on a core set of clinical preventive services: Flu shot past year, PPV shot ever, Colorectal cancer screening" t:dataTypeName=number

metric m:corew_crudeprev p:float l:COREW_CrudePrev d:"Model-based estimate for crude prevalence of older adult women aged >=65 years who are up to date on a core set of clinical preventive services: Flu shot past year, PPV shot ever, Colorectal cancer screening, and Mammogram past 2 years" t:dataTypeName=number

metric m:csmoking_crudeprev p:float l:CSMOKING_CrudePrev d:"Model-based estimate for crude prevalence of current smoking among adults aged >=18 years" t:dataTypeName=number

metric m:dental_crudeprev p:float l:DENTAL_CrudePrev d:"Model-based estimate for crude prevalence of visits to dentist or dental clinic among adults aged >=18 years" t:dataTypeName=number

metric m:diabetes_crudeprev p:double l:DIABETES_CrudePrev d:"Model-based estimate for crude prevalence of diagnosed diabetes among adults aged >=18 years" t:dataTypeName=number

metric m:highchol_crudeprev p:float l:HIGHCHOL_CrudePrev d:"Model-based estimate for crude prevalence of high cholesterol among adults aged >=18 years who have been screened in the past 5 years" t:dataTypeName=number

metric m:kidney_crudeprev p:float l:KIDNEY_CrudePrev d:"Model-based estimate for crude prevalence of chronic kidney disease among adults aged >=18 years" t:dataTypeName=number

metric m:lpa_crudeprev p:float l:LPA_CrudePrev d:"Model-based estimate for crude prevalence of no leisure-time physical activity among adults aged >=18 years" t:dataTypeName=number

metric m:mammouse_crudeprev p:float l:MAMMOUSE_CrudePrev d:"Model-based estimate for crude prevalence of mammography use among women aged 50?74 years" t:dataTypeName=number

metric m:mhlth_crudeprev p:float l:MHLTH_CrudePrev d:"Model-based estimate for crude prevalence of mental health not good for >=14 days among adults aged >=18 years" t:dataTypeName=number

metric m:obesity_crudeprev p:float l:OBESITY_CrudePrev d:"Model-based estimate for crude prevalence of obesity among adults aged >=18 years" t:dataTypeName=number

metric m:paptest_crudeprev p:float l:PAPTEST_CrudePrev d:"Model-based estimate for crude prevalence of papanicolaou smear use among adult women aged 21?65 years" t:dataTypeName=number

metric m:phlth_crudeprev p:float l:PHLTH_CrudePrev d:"Model-based estimate for crude prevalence of physical health not good for >=14 days among adults aged >=18 years" t:dataTypeName=number

metric m:sleep_crudeprev p:float l:SLEEP_CrudePrev d:"Model-based estimate for crude prevalence of sleeping less than 7 hours among adults aged >=18 years" t:dataTypeName=number

metric m:stroke_crudeprev p:float l:STROKE_CrudePrev d:"Model-based estimate for crude prevalence of stroke among adults aged >=18 years" t:dataTypeName=number

metric m:teethlost_crudeprev p:double l:TEETHLOST_CrudePrev d:"Model-based estimate for crude prevalence of all teeth lost among adults aged >=65 years" t:dataTypeName=number

entity e:k86t-wghb l:"500 Cities: Census Tract-level Data (GIS Friendly Format)" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Population Health" t:url=https://data.cdc.gov/api/views/k86t-wghb

property e:k86t-wghb t:meta.view v:id=k86t-wghb v:category="500 Cities" v:attributionLink=http://www.cdc.gov/nccdphp/dph/ v:averageRating=0 v:name="500 Cities: Census Tract-level Data (GIS Friendly Format)" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Population Health"

property e:k86t-wghb t:meta.view.license v:name="Public Domain"

property e:k86t-wghb t:meta.view.owner v:id=fwb6-kmt3 v:screenName=hiz4@cdc.gov v:lastNotificationSeenAt=1492540125 v:displayName=hiz4@cdc.gov

property e:k86t-wghb t:meta.view.tableauthor v:id=fwb6-kmt3 v:screenName=hiz4@cdc.gov v:roleName=publisher v:lastNotificationSeenAt=1492540125 v:displayName=hiz4@cdc.gov

property e:k86t-wghb t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC Info" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| :updated_at | stateabbr | placename  | placefips | tractfips   | place_tractid       | population2010 | access2_crudeprev | access2_crude95ci | arthritis_crudeprev | arthritis_crude95ci | binge_crudeprev | binge_crude95ci | bphigh_crudeprev | bphigh_crude95ci | bpmed_crudeprev | bpmed_crude95ci | cancer_crudeprev | cancer_crude95ci | casthma_crudeprev | casthma_crude95ci | chd_crudeprev | chd_crude95ci | checkup_crudeprev | checkup_crude95ci | cholscreen_crudeprev | cholscreen_crude95ci | colon_screen_crudeprev | colon_screen_crude95ci | copd_crudeprev | copd_crude95ci | corem_crudeprev | corem_crude95ci | corew_crudeprev | corew_crude95ci | csmoking_crudeprev | csmoking_crude95ci | dental_crudeprev | dental_crude95ci | diabetes_crudeprev | diabetes_crude95ci | highchol_crudeprev | highchol_crude95ci | kidney_crudeprev | kidney_crude95ci | lpa_crudeprev | lpa_crude95ci | mammouse_crudeprev | mammouse_crude95ci | mhlth_crudeprev | mhlth_crude95ci | obesity_crudeprev | obesity_crude95ci | paptest_crudeprev | paptest_crude95ci | phlth_crudeprev | phlth_crude95ci | sleep_crudeprev | sleep_crude95ci | stroke_crudeprev | stroke_crude95ci | teethlost_crudeprev | teethlost_crude95ci | geolocation                      | 
| =========== | ========= | ========== | ========= | =========== | =================== | ============== | ================= | ================= | =================== | =================== | =============== | =============== | ================ | ================ | =============== | =============== | ================ | ================ | ================= | ================= | ============= | ============= | ================= | ================= | ==================== | ==================== | ====================== | ====================== | ============== | ============== | =============== | =============== | =============== | =============== | ================== | ================== | ================ | ================ | ================== | ================== | ================== | ================== | ================ | ================ | ============= | ============= | ================== | ================== | =============== | =============== | ================= | ================= | ================= | ================= | =============== | =============== | =============== | =============== | ================ | ================ | =================== | =================== | ================================ | 
| 1478116918  | AL        | Birmingham | 0107000   | 01073000100 | 0107000-01073000100 | 3042           | 27.6              | (24.2, 31.0)      | 34                  | (32.9, 35.0)        | 10.3            | ( 9.8, 10.7)    | 46.8             | (45.3, 48.2)     | 80.3            | (79.4, 81.1)    | 5.5              | ( 5.3, 5.8)      | 12.8              | (12.0, 13.7)      | 7.8           | ( 7.3, 8.4)   | 76.6              | (75.8, 77.4)      | 72.8                 | (70.5, 75.0)         | 54.2                   | (50.7, 57.4)           | 11.2           | (10.2, 12.4)   | 28.2            | (24.1, 32.1)    | 25.2            | (21.9, 28.2)    | 27.3               | (24.7, 30.1)       | 40.9             | (37.5, 44.3)     | 16.8               | (15.9, 17.6)       | 39.5               | (38.3, 40.8)       | 3.3              | ( 3.1, 3.5)      | 36.4          | (33.7, 39.1)  | 74.2               | (70.6, 77.0)       | 20.5            | (18.9, 22.3)    | 42.6              | (41.4, 43.7)      | 76                | (73.1, 78.6)      | 21.6            | (19.8, 23.4)    | 50.4            | (49.1, 51.6)    | 5.1              | ( 4.7, 5.6)      | 30.2                | (24.1, 36.3)        | (33.57943283260, -86.7228323926) | 
| 1478116918  | AL        | Birmingham | 0107000   | 01073000300 | 0107000-01073000300 | 2735           | 32.2              | (28.5, 36.0)      | 32.8                | (31.5, 34.0)        | 11              | (10.5, 11.5)    | 46.2             | (44.9, 47.5)     | 80.6            | (79.6, 81.5)    | 5                | ( 4.7, 5.2)      | 11.9              | (11.1, 12.8)      | 8             | ( 7.4, 8.6)   | 74                | (73.1, 74.8)      | 70.2                 | (68.0, 72.1)         | 51.3                   | (46.7, 55.6)           | 11.1           | ( 9.9, 12.4)   | 25.7            | (21.5, 29.9)    | 22.7            | (19.1, 26.6)    | 26.7               | (23.5, 29.8)       | 39               | (35.0, 42.8)     | 18.1               | (17.0, 19.1)       | 40.6               | (39.2, 41.8)       | 3.4              | ( 3.1, 3.7)      | 37.9          | (34.9, 40.9)  | 74                 | (69.6, 77.5)       | 20.2            | (18.3, 22.0)    | 43                | (41.6, 44.3)      | 73.2              | (70.0, 76.4)      | 22.3            | (20.3, 24.4)    | 49.4            | (47.8, 50.8)    | 5.3              | ( 4.8, 5.9)      | 33.3                | (25.6, 41.0)        | (33.54282086860, -86.7524339780) | 
| 1478116918  | AL        | Birmingham | 0107000   | 01073000400 | 0107000-01073000400 | 3338           | 31.8              | (28.0, 35.8)      | 37.2                | (36.0, 38.5)        | 9.3             | ( 8.7, 9.8)     | 51.8             | (50.0, 53.4)     | 82.5            | (81.5, 83.5)    | 5.6              | ( 5.3, 5.9)      | 13.4              | (12.4, 14.6)      | 9.1           | ( 8.4, 9.9)   | 77.5              | (76.5, 78.4)      | 72.2                 | (69.4, 74.8)         | 52.1                   | (48.0, 56.3)           | 12.9           | (11.6, 14.6)   | 24.3            | (20.3, 28.6)    | 21.6            | (18.3, 25.3)    | 29.3               | (26.5, 32.4)       | 35.1             | (31.4, 38.8)     | 20.8               | (19.9, 21.9)       | 41.8               | (40.2, 43.5)       | 3.8              | ( 3.4, 4.1)      | 41.3          | (38.3, 44.4)  | 73.6               | (69.6, 77.1)       | 21.9            | (20.1, 24.1)    | 46.6              | (45.3, 47.8)      | 72.8              | (69.4, 76.2)      | 24.6            | (22.5, 27.0)    | 52.5            | (51.2, 53.7)    | 6.5              | ( 5.9, 7.3)      | 36                  | (28.9, 43.5)        | (33.56324496330, -86.7640474064) | 
| 1478116918  | AL        | Birmingham | 0107000   | 01073000500 | 0107000-01073000500 | 2864           | 33.7              | (29.3, 37.9)      | 40.1                | (38.6, 41.5)        | 8.4             | ( 8.0, 8.9)     | 56.7             | (55.1, 58.3)     | 84.5            | (83.6, 85.5)    | 6.1              | ( 5.8, 6.5)      | 13.6              | (12.6, 14.7)      | 10.8          | ( 9.8, 11.8)  | 78.7              | (77.8, 79.6)      | 72.1                 | (69.5, 74.5)         | 52                     | (47.9, 56.1)           | 14.4           | (12.7, 16.2)   | 22.2            | (17.5, 27.6)    | 19.5            | (16.0, 23.2)    | 29.4               | (26.3, 32.4)       | 32.7             | (28.9, 36.5)     | 23.9               | (22.6, 25.3)       | 44.5               | (42.9, 46.2)       | 4.5              | ( 4.1, 5.0)      | 44            | (40.8, 47.0)  | 73.2               | (68.8, 76.8)       | 22              | (20.1, 24.0)    | 47.3              | (46.0, 48.6)      | 70.8              | (67.0, 74.5)      | 26.4            | (24.1, 28.7)    | 52.6            | (51.1, 54.0)    | 8                | ( 7.2, 8.9)      | 40.2                | (31.1, 48.9)        | (33.54424045940, -86.7749130719) | 
| 1478116918  | AL        | Birmingham | 0107000   | 01073000700 | 0107000-01073000700 | 2577           | 38.4              | (33.0, 43.7)      | 40.2                | (38.7, 41.5)        | 7.4             | ( 6.9, 8.0)     | 56.7             | (54.9, 58.3)     | 83.8            | (82.7, 84.8)    | 6                | ( 5.5, 6.4)      | 14.7              | (13.4, 16.1)      | 11.2          | (10.2, 12.1)  | 78.4              | (77.3, 79.6)      | 69.6                 | (66.5, 72.5)         | 48.4                   | (44.0, 52.8)           | 15.6           | (13.7, 17.3)   | 21.9            | (17.1, 27.1)    | 17.6            | (13.8, 21.5)    | 31.6               | (27.6, 35.3)       | 28.3             | (24.5, 32.9)     | 24.4               | (22.9, 25.6)       | 43.5               | (41.6, 45.4)       | 4.5              | ( 4.1, 5.0)      | 47.1          | (43.3, 50.7)  | 70.5               | (65.0, 75.4)       | 24.1            | (21.6, 26.6)    | 49.6              | (48.0, 51.0)      | 67.6              | (62.9, 71.9)      | 28.6            | (25.9, 31.1)    | 54.1            | (52.3, 55.6)    | 8.8              | ( 7.8, 9.9)      | 45.8                | (35.2, 56.1)        | (33.55254061390, -86.8016893706) | 
| 1478116918  | AL        | Birmingham | 0107000   | 01073000800 | 0107000-01073000800 | 3859           | 26.5              | (22.6, 30.2)      | 40.7                | (39.3, 42.1)        | 8.8             | ( 8.4, 9.2)     | 56.6             | (55.1, 58.0)     | 85.8            | (85.1, 86.6)    | 7                | ( 6.6, 7.4)      | 12.6              | (11.7, 13.5)      | 10.8          | ( 9.9, 11.7)  | 81.1              | (80.4, 81.9)      | 78.3                 | (76.3, 80.2)         | 59.9                   | (56.0, 64.0)           | 12.5           | (10.9, 14.1)   | 24.9            | (20.2, 29.8)    | 23.6            | (19.3, 28.0)    | 24.6               | (21.7, 27.4)       | 40.8             | (36.8, 45.2)     | 23.5               | (22.0, 25.0)       | 44                 | (42.8, 45.4)       | 4.4              | ( 4.1, 4.9)      | 38.7          | (35.3, 41.6)  | 76.5               | (72.6, 80.0)       | 18.7            | (16.8, 20.4)    | 44.3              | (43.0, 45.5)      | 77.3              | (74.2, 80.4)      | 23              | (20.8, 25.2)    | 50.8            | (49.3, 52.1)    | 7.5              | ( 6.7, 8.4)      | 32.8                | (24.7, 42.0)        | (33.54969778900, -86.8330944744) | 
| 1478116918  | AL        | Birmingham | 0107000   | 01073001100 | 0107000-01073001100 | 5354           | 19.7              | (15.8, 23.8)      | 36.3                | (34.6, 38.0)        | 9.8             | ( 9.3, 10.4)    | 51.2             | (49.6, 52.7)     | 84.4            | (83.5, 85.2)    | 6.9              | ( 6.5, 7.3)      | 11.7              | (10.7, 12.8)      | 8.3           | ( 7.5, 9.3)   | 81.9              | (80.9, 82.7)      | 79                   | (76.5, 81.3)         | 66.6                   | (61.8, 71.0)           | 9.3            | ( 7.8, 10.9)   | 28.3            | (22.5, 34.3)    | 28.1            | (23.5, 32.7)    | 20.1               | (16.7, 23.5)       | 51               | (45.4, 56.4)     | 18.7               | (17.3, 20.2)       | 41                 | (39.5, 42.5)       | 3.8              | ( 3.4, 4.1)      | 31.5          | (27.8, 35.3)  | 80                 | (76.0, 83.3)       | 16              | (13.9, 18.1)    | 39.7              | (38.0, 41.4)      | 82.3              | (78.8, 85.3)      | 17.8            | (15.6, 20.2)    | 48.4            | (46.4, 50.4)    | 5.6              | ( 4.9, 6.3)      | 23.8                | (16.5, 32.2)        | (33.54291433250, -86.8756782852) | 
| 1478116918  | AL        | Birmingham | 0107000   | 01073001200 | 0107000-01073001200 | 2876           | 28.9              | (26.1, 31.9)      | 39                  | (37.9, 40.1)        | 9.3             | ( 9.0, 9.6)     | 54.3             | (53.1, 55.3)     | 84.9            | (84.3, 85.6)    | 6.8              | ( 6.4, 7.1)      | 12                | (11.4, 12.7)      | 10.3          | ( 9.6, 11.1)  | 79.4              | (78.8, 80.0)      | 76                   | (74.5, 77.4)         | 58.2                   | (54.8, 61.3)           | 12             | (10.8, 13.3)   | 24.7            | (21.0, 28.7)    | 22.2            | (18.9, 25.6)    | 24.1               | (22.0, 26.2)       | 39.9             | (36.9, 42.9)     | 22.3               | (21.3, 23.4)       | 43.1               | (42.1, 44.2)       | 4.2              | ( 3.9, 4.5)      | 39.3          | (36.7, 41.8)  | 76                 | (72.9, 78.8)       | 18.5            | (17.2, 19.9)    | 44.1              | (43.0, 45.1)      | 76.2              | (73.5, 78.7)      | 22.9            | (21.2, 24.7)    | 50.2            | (49.1, 51.3)    | 7.3              | ( 6.6, 8.0)      | 33.6                | (26.4, 41.2)        | (33.52787677060, -86.8604161686) | 
| 1478116918  | AL        | Birmingham | 0107000   | 01073001400 | 0107000-01073001400 | 2181           | 26.6              | (22.3, 30.5)      | 40                  | (38.4, 41.6)        | 8.7             | ( 8.3, 9.1)     | 55.8             | (54.2, 57.3)     | 85.9            | (85.1, 86.7)    | 7.3              | ( 6.8, 7.8)      | 11.8              | (10.9, 12.8)      | 10.9          | ( 9.8, 12.2)  | 80.6              | (79.8, 81.4)      | 77.4                 | (75.5, 79.2)         | 60.3                   | (55.5, 64.7)           | 11.6           | ( 9.9, 13.7)   | 25.7            | (20.0, 31.8)    | 23.2            | (18.6, 28.0)    | 21.7               | (18.4, 24.9)       | 42.5             | (37.9, 47.4)     | 22.8               | (21.2, 24.4)       | 43.7               | (42.2, 45.2)       | 4.4              | ( 4.0, 5.0)      | 37.9          | (33.9, 41.8)  | 76.9               | (72.3, 80.8)       | 17.4            | (15.4, 19.4)    | 43.1              | (41.4, 44.6)      | 77.4              | (73.6, 80.9)      | 22.1            | (19.7, 25.0)    | 49.1            | (47.2, 50.8)    | 7.6              | ( 6.7, 8.8)      | 31.7                | (21.3, 42.7)        | (33.52614972580, -86.8351466060) | 
| 1478116918  | AL        | Birmingham | 0107000   | 01073001500 | 0107000-01073001500 | 3189           | 31.8              | (28.4, 34.9)      | 37.7                | (36.6, 38.8)        | 9.3             | ( 8.9, 9.7)     | 54.8             | (53.6, 55.9)     | 83.5            | (82.7, 84.2)    | 5.8              | ( 5.6, 6.1)      | 13                | (12.2, 13.8)      | 10            | ( 9.3, 10.8)  | 77.9              | (77.2, 78.6)      | 72.6                 | (70.5, 74.3)         | 52.6                   | (49.3, 55.9)           | 13             | (11.8, 14.3)   | 23.6            | (19.8, 27.5)    | 20.9            | (18.0, 24.3)    | 28.8               | (26.3, 31.4)       | 34.9             | (31.7, 37.9)     | 22.3               | (21.1, 23.3)       | 43.1               | (41.9, 44.3)       | 4.2              | ( 3.9, 4.5)      | 41.3          | (38.8, 43.8)  | 74.2               | (70.8, 77.5)       | 21.1            | (19.6, 22.8)    | 46.6              | (45.4, 47.6)      | 72.9              | (70.0, 75.7)      | 24.7            | (23.0, 26.6)    | 52.5            | (51.3, 53.6)    | 7.2              | ( 6.6, 7.9)      | 38.2                | (31.0, 45.3)        | (33.52987273420, -86.8197191685) | 
```