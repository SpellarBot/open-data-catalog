# 500 Cities: City-level Data (GIS Friendly Format)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/500-cities-city-level-data-gis-friendly-format) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/dxpw-cm5u) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/dxpw-cm5u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/dxpw-cm5u/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | dxpw-cm5u |
| Name | 500 Cities: City-level Data (GIS Friendly Format) |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Population Health |
| Category | 500 Cities |
| Tags | 500cities, cities, census, tract, gis, prevalence, unhealthy, behaviors, outcomes, prevention |
| Created | 2016-10-28T16:55:05Z |
| Publication Date | 2016-11-03T18:51:20Z |

## Description

2013, 2014. Data were provided by the Centers for Disease Control and Prevention (CDC), Division of Population Health, Epidemiology and Surveillance Branch. The project was funded by the Robert Wood Johnson Foundation (RWJF) in conjunction with the CDC Foundation. 500 cities project city-level data in GIS-friendly format. This dataset can be joined with city-level spatial data in a geographic information system (GIS) to produce maps of 27 measures at the city-level.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| No       | time           | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag     | stateabbr              | StateAbbr              | text      | text        |
| Yes      | series tag     | placename              | PlaceName              | text      | text        |
| Yes      | series tag     | placefips              | PlaceFIPS              | text      | text        |
| Yes      | numeric metric | population_count       | Population2010         | number    | number      |
| Yes      | numeric metric | access2_crudeprev      | ACCESS2_CrudePrev      | number    | number      |
| Yes      | series tag     | access2_crude95ci      | ACCESS2_Crude95CI      | text      | text        |
| Yes      | numeric metric | access2_adjprev        | ACCESS2_AdjPrev        | number    | number      |
| Yes      | series tag     | access2_adj95ci        | ACCESS2_Adj95CI        | text      | text        |
| Yes      | numeric metric | arthritis_crudeprev    | ARTHRITIS_CrudePrev    | number    | number      |
| Yes      | series tag     | arthritis_crude95ci    | ARTHRITIS_Crude95CI    | text      | text        |
| Yes      | numeric metric | arthritis_adjprev      | ARTHRITIS_AdjPrev      | number    | number      |
| Yes      | series tag     | arthritis_adj95ci      | ARTHRITIS_Adj95CI      | text      | text        |
| Yes      | numeric metric | binge_crudeprev        | BINGE_CrudePrev        | number    | number      |
| Yes      | series tag     | binge_crude95ci        | BINGE_Crude95CI        | text      | text        |
| Yes      | numeric metric | binge_adjprev          | BINGE_AdjPrev          | number    | number      |
| Yes      | series tag     | binge_adj95ci          | BINGE_Adj95CI          | text      | text        |
| Yes      | numeric metric | bphigh_crudeprev       | BPHIGH_CrudePrev       | number    | number      |
| Yes      | series tag     | bphigh_crude95ci       | BPHIGH_Crude95CI       | text      | text        |
| Yes      | numeric metric | bphigh_adjprev         | BPHIGH_AdjPrev         | number    | number      |
| Yes      | series tag     | bphigh_adj95ci         | BPHIGH_Adj95CI         | text      | text        |
| Yes      | numeric metric | bpmed_crudeprev        | BPMED_CrudePrev        | number    | number      |
| Yes      | series tag     | bpmed_crude95ci        | BPMED_Crude95CI        | text      | text        |
| Yes      | numeric metric | bpmed_adjprev          | BPMED_AdjPrev          | number    | number      |
| Yes      | series tag     | bpmed_adj95ci          | BPMED_Adj95CI          | text      | text        |
| Yes      | numeric metric | cancer_crudeprev       | CANCER_CrudePrev       | number    | number      |
| Yes      | series tag     | cancer_crude95ci       | CANCER_Crude95CI       | text      | text        |
| Yes      | numeric metric | cancer_adjprev         | CANCER_AdjPrev         | number    | number      |
| Yes      | series tag     | cancer_adj95ci         | CANCER_Adj95CI         | text      | text        |
| Yes      | numeric metric | casthma_crudeprev      | CASTHMA_CrudePrev      | number    | number      |
| Yes      | series tag     | casthma_crude95ci      | CASTHMA_Crude95CI      | text      | text        |
| Yes      | numeric metric | casthma_adjprev        | CASTHMA_AdjPrev        | number    | number      |
| Yes      | series tag     | casthma_adj95ci        | CASTHMA_Adj95CI        | text      | text        |
| Yes      | numeric metric | chd_crudeprev          | CHD_CrudePrev          | number    | number      |
| Yes      | series tag     | chd_crude95ci          | CHD_Crude95CI          | text      | text        |
| Yes      | numeric metric | chd_adjprev            | CHD_AdjPrev            | number    | number      |
| Yes      | series tag     | chd_adj95ci            | CHD_Adj95CI            | text      | text        |
| Yes      | numeric metric | checkup_crudeprev      | CHECKUP_CrudePrev      | number    | number      |
| Yes      | series tag     | checkup_crude95ci      | CHECKUP_Crude95CI      | text      | text        |
| Yes      | numeric metric | checkup_adjprev        | CHECKUP_AdjPrev        | number    | number      |
| Yes      | series tag     | checkup_adj95ci        | CHECKUP_Adj95CI        | text      | text        |
| Yes      | numeric metric | cholscreen_crudeprev   | CHOLSCREEN_CrudePrev   | number    | number      |
| Yes      | series tag     | cholscreen_crude95ci   | CHOLSCREEN_Crude95CI   | text      | text        |
| Yes      | numeric metric | cholscreen_adjprev     | CHOLSCREEN_AdjPrev     | number    | number      |
| Yes      | series tag     | cholscreen_adj95ci     | CHOLSCREEN_Adj95CI     | text      | text        |
| Yes      | numeric metric | colon_screen_crudeprev | COLON_SCREEN_CrudePrev | number    | number      |
| Yes      | series tag     | colon_screen_crude95ci | COLON_SCREEN_Crude95CI | text      | text        |
| Yes      | numeric metric | colon_screen_adjprev   | COLON_SCREEN_AdjPrev   | number    | number      |
| Yes      | series tag     | colon_screen_adj95ci   | COLON_SCREEN_Adj95CI   | text      | text        |
| Yes      | numeric metric | copd_crudeprev         | COPD_CrudePrev         | number    | number      |
| Yes      | series tag     | copd_crude95ci         | COPD_Crude95CI         | text      | text        |
| Yes      | numeric metric | copd_adjprev           | COPD_AdjPrev           | number    | number      |
| Yes      | series tag     | copd_adj95ci           | COPD_Adj95CI           | text      | text        |
| Yes      | numeric metric | corem_crudeprev        | COREM_CrudePrev        | number    | number      |
| Yes      | series tag     | corem_crude95ci        | COREM_Crude95CI        | text      | text        |
| Yes      | numeric metric | corem_adjprev          | COREM_AdjPrev          | number    | number      |
| Yes      | series tag     | corem_adj95ci          | COREM_Adj95CI          | text      | text        |
| Yes      | numeric metric | corew_crudeprev        | COREW_CrudePrev        | number    | number      |
| Yes      | series tag     | corew_crude95ci        | COREW_Crude95CI        | text      | text        |
| Yes      | numeric metric | corew_adjprev          | COREW_AdjPrev          | number    | number      |
| Yes      | series tag     | corew_adj95ci          | COREW_Adj95CI          | text      | text        |
| Yes      | numeric metric | csmoking_crudeprev     | CSMOKING_CrudePrev     | number    | number      |
| Yes      | series tag     | csmoking_crude95ci     | CSMOKING_Crude95CI     | text      | text        |
| Yes      | numeric metric | csmoking_adjprev       | CSMOKING_AdjPrev       | number    | number      |
| Yes      | series tag     | csmoking_adj95ci       | CSMOKING_Adj95CI       | text      | text        |
| Yes      | numeric metric | dental_crudeprev       | DENTAL_CrudePrev       | number    | number      |
| Yes      | series tag     | dental_crude95ci       | DENTAL_Crude95CI       | text      | text        |
| Yes      | numeric metric | dental_adjprev         | DENTAL_AdjPrev         | number    | number      |
| Yes      | series tag     | dental_adj95ci         | DENTAL_Adj95CI         | text      | text        |
| Yes      | numeric metric | diabetes_crudeprev     | DIABETES_CrudePrev     | number    | number      |
| Yes      | series tag     | diabetes_crude95ci     | DIABETES_Crude95CI     | text      | text        |
| Yes      | numeric metric | diabetes_adjprev       | DIABETES_AdjPrev       | number    | number      |
| Yes      | series tag     | diabetes_adj95ci       | DIABETES_Adj95CI       | text      | text        |
| Yes      | numeric metric | highchol_crudeprev     | HIGHCHOL_CrudePrev     | number    | number      |
| Yes      | series tag     | highchol_crude95ci     | HIGHCHOL_Crude95CI     | text      | text        |
| Yes      | numeric metric | highchol_adjprev       | HIGHCHOL_AdjPrev       | number    | number      |
| Yes      | series tag     | highchol_adj95ci       | HIGHCHOL_Adj95CI       | text      | text        |
| Yes      | numeric metric | kidney_crudeprev       | KIDNEY_CrudePrev       | number    | number      |
| Yes      | series tag     | kidney_crude95ci       | KIDNEY_Crude95CI       | text      | text        |
| Yes      | numeric metric | kidney_adjprev         | KIDNEY_AdjPrev         | number    | number      |
| Yes      | series tag     | kidney_adj95ci         | KIDNEY_Adj95CI         | text      | text        |
| Yes      | numeric metric | lpa_crudeprev          | LPA_CrudePrev          | number    | number      |
| Yes      | series tag     | lpa_crude95ci          | LPA_Crude95CI          | text      | text        |
| Yes      | numeric metric | lpa_adjprev            | LPA_AdjPrev            | number    | number      |
| Yes      | series tag     | lpa_adj95ci            | LPA_Adj95CI            | text      | text        |
| Yes      | numeric metric | mammouse_crudeprev     | MAMMOUSE_CrudePrev     | number    | number      |
| Yes      | series tag     | mammouse_crude95ci     | MAMMOUSE_Crude95CI     | text      | text        |
| Yes      | numeric metric | mammouse_adjprev       | MAMMOUSE_AdjPrev       | number    | number      |
| Yes      | series tag     | mammouse_adj95ci       | MAMMOUSE_Adj95CI       | text      | text        |
| Yes      | numeric metric | mhlth_crudeprev        | MHLTH_CrudePrev        | number    | number      |
| Yes      | series tag     | mhlth_crude95ci        | MHLTH_Crude95CI        | text      | text        |
| Yes      | numeric metric | mhlth_adjprev          | MHLTH_AdjPrev          | number    | number      |
| Yes      | series tag     | mhlth_adj95ci          | MHLTH_Adj95CI          | text      | text        |
| Yes      | numeric metric | obesity_crudeprev      | OBESITY_CrudePrev      | number    | number      |
| Yes      | series tag     | obesity_crude95ci      | OBESITY_Crude95CI      | text      | text        |
| Yes      | numeric metric | obesity_adjprev        | OBESITY_AdjPrev        | number    | number      |
| Yes      | series tag     | obesity_adj95ci        | OBESITY_Adj95CI        | text      | text        |
| Yes      | numeric metric | paptest_crudeprev      | PAPTEST_CrudePrev      | number    | number      |
| Yes      | series tag     | paptest_crude95ci      | PAPTEST_Crude95CI      | text      | text        |
| Yes      | numeric metric | paptest_adjprev        | PAPTEST_AdjPrev        | number    | number      |
| Yes      | series tag     | paptest_adj95ci        | PAPTEST_Adj95CI        | text      | text        |
| Yes      | numeric metric | phlth_crudeprev        | PHLTH_CrudePrev        | number    | number      |
| Yes      | series tag     | phlth_crude95ci        | PHLTH_Crude95CI        | text      | text        |
| Yes      | numeric metric | phlth_adjprev          | PHLTH_AdjPrev          | number    | number      |
| Yes      | series tag     | phlth_adj95ci          | PHLTH_Adj95CI          | text      | text        |
| Yes      | numeric metric | sleep_crudeprev        | SLEEP_CrudePrev        | number    | number      |
| Yes      | series tag     | sleep_crude95ci        | SLEEP_Crude95CI        | text      | text        |
| Yes      | numeric metric | sleep_adjprev          | SLEEP_AdjPrev          | number    | number      |
| Yes      | series tag     | sleep_adj95ci          | SLEEP_Adj95CI          | text      | text        |
| Yes      | numeric metric | stroke_crudeprev       | STROKE_CrudePrev       | number    | number      |
| Yes      | series tag     | stroke_crude95ci       | STROKE_Crude95CI       | text      | text        |
| Yes      | numeric metric | stroke_adjprev         | STROKE_AdjPrev         | number    | number      |
| Yes      | series tag     | stroke_adj95ci         | STROKE_Adj95CI         | text      | text        |
| Yes      | numeric metric | teethlost_crudeprev    | TEETHLOST_CrudePrev    | number    | number      |
| Yes      | series tag     | teethlost_crude95ci    | TEETHLOST_Crude95CI    | text      | text        |
| Yes      | numeric metric | teethlost_adjprev      | TEETHLOST_AdjPrev      | number    | number      |
| Yes      | series tag     | teethlost_adj95ci      | TEETHLOST_Adj95CI      | text      | text        |
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
series e:dxpw-cm5u d:2016-10-28T16:55:34.000Z t:phlth_crude95ci="(18.0, 18.5)" t:colon_screen_crude95ci="(60.6, 61.6)" t:kidney_crude95ci="( 3.3,  3.3)" t:mammouse_adj95ci="(79.3, 80.1)" t:bpmed_adj95ci="(70.3, 70.6)" t:corew_crude95ci="(26.7, 27.9)" t:obesity_adj95ci="(38.8, 39.1)" t:bphigh_crude95ci="(45.5, 45.8)" t:cholscreen_crude95ci="(73.0, 73.6)" t:corem_crude95ci="(29.2, 30.5)" t:sleep_adj95ci="(46.6, 47.0)" t:mhlth_adj95ci="(16.7, 17.2)" t:dental_adj95ci="(48.6, 49.6)" t:cancer_crude95ci="( 6.0,  6.1)" t:cholscreen_adj95ci="(74.1, 74.7)" t:highchol_crude95ci="(39.5, 39.9)" t:binge_adj95ci="(11.3, 11.4)" t:bphigh_adj95ci="(45.7, 46.1)" t:csmoking_adj95ci="(21.6, 22.3)" t:casthma_adj95ci="(11.3, 11.5)" t:highchol_adj95ci="(35.3, 35.6)" t:stroke_adj95ci="( 5.0,  5.1)" t:corem_adj95ci="(29.6, 30.9)" t:checkup_adj95ci="(77.2, 77.4)" t:stroke_crude95ci="( 5.0,  5.1)" t:bpmed_crude95ci="(81.3, 81.5)" t:access2_crude95ci="(22.1, 23.0)" t:placefips=0107000 t:copd_adj95ci="( 9.3,  9.6)" t:colon_screen_adj95ci="(62.2, 63.1)" t:diabetes_adj95ci="(16.0, 16.2)" t:access2_adj95ci="(21.0, 21.8)" t:obesity_crude95ci="(31.6, 31.7)" t:mammouse_crude95ci="(76.4, 77.2)" t:placename=Birmingham t:chd_adj95ci="( 7.6,  7.7)" t:checkup_crude95ci="(77.2, 77.4)" t:diabetes_crude95ci="(16.0, 16.3)" t:paptest_adj95ci="(79.7, 80.4)" t:casthma_crude95ci="(11.3, 11.5)" t:arthritis_adj95ci="(32.5, 32.8)" t:lpa_adj95ci="(31.3, 32.1)" t:teethlost_crude95ci="(25.1, 27.2)" t:sleep_crude95ci="(46.3, 46.7)" t:arthritis_crude95ci="(32.5, 32.8)" t:dental_crude95ci="(48.7, 49.8)" t:lpa_crude95ci="(31.2, 31.9)" t:paptest_crude95ci="(78.2, 78.9)" t:cancer_adj95ci="( 6.1,  6.1)" t:stateabbr=AL t:binge_crude95ci="(11.5, 11.6)" t:teethlost_adj95ci="(25.0, 26.9)" t:corew_adj95ci="(27.3, 28.4)" t:copd_crude95ci="( 9.3,  9.7)" t:kidney_adj95ci="( 3.3,  3.3)" t:chd_crude95ci="( 7.6,  7.8)" t:mhlth_crude95ci="(16.8, 17.2)" t:phlth_adj95ci="(18.0, 18.5)" t:csmoking_crude95ci="(21.5, 22.3)" m:kidney_crudeprev=3.3 m:casthma_adjprev=11.4 m:binge_crudeprev=11.5 m:corew_crudeprev=27.3 m:corew_adjprev=27.9 m:colon_screen_crudeprev=61.1 m:teethlost_adjprev=25.9 m:colon_screen_adjprev=62.7 m:stroke_adjprev=5 m:paptest_adjprev=80.1 m:bpmed_adjprev=70.5 m:mhlth_crudeprev=17 m:chd_adjprev=7.6 m:csmoking_adjprev=22 m:bpmed_crudeprev=81.4 m:diabetes_crudeprev=16.2 m:stroke_crudeprev=5 m:mhlth_adjprev=17 m:paptest_crudeprev=78.6 m:phlth_adjprev=18.3 m:cholscreen_crudeprev=73.3 m:population_count=212237 m:dental_crudeprev=49.3 m:cancer_adjprev=6.1 m:chd_crudeprev=7.7 m:casthma_crudeprev=11.4 m:csmoking_crudeprev=21.9 m:lpa_crudeprev=31.5 m:obesity_crudeprev=31.7 m:dental_adjprev=49.1 m:bphigh_crudeprev=45.6 m:diabetes_adjprev=16.1 m:corem_adjprev=30.3 m:copd_crudeprev=9.5 m:sleep_crudeprev=46.5 m:access2_adjprev=21.4 m:arthritis_crudeprev=32.6 m:checkup_adjprev=77.3 m:bphigh_adjprev=45.9 m:highchol_crudeprev=39.7 m:corem_crudeprev=29.9 m:copd_adjprev=9.4 m:cholscreen_adjprev=74.4 m:teethlost_crudeprev=26.1 m:arthritis_adjprev=32.6 m:cancer_crudeprev=6.1 m:highchol_adjprev=35.4 m:sleep_adjprev=46.9 m:kidney_adjprev=3.3 m:checkup_crudeprev=77.3 m:access2_crudeprev=22.6 m:lpa_adjprev=31.7 m:phlth_crudeprev=18.3 m:mammouse_crudeprev=76.8 m:obesity_adjprev=39 m:mammouse_adjprev=79.7 m:binge_adjprev=11.4

series e:dxpw-cm5u d:2016-10-28T16:55:34.000Z t:phlth_crude95ci="(10.0, 10.6)" t:colon_screen_crude95ci="(71.7, 73.1)" t:kidney_crude95ci="( 2.2,  2.3)" t:mammouse_adj95ci="(81.4, 82.9)" t:bpmed_adj95ci="(63.6, 64.1)" t:corew_crude95ci="(40.2, 42.7)" t:obesity_adj95ci="(24.4, 25.0)" t:bphigh_crude95ci="(32.6, 33.2)" t:cholscreen_crude95ci="(77.6, 78.5)" t:corem_crude95ci="(40.2, 43.1)" t:sleep_adj95ci="(34.2, 35.0)" t:mhlth_adj95ci="(10.5, 11.1)" t:dental_adj95ci="(71.9, 73.4)" t:cancer_crude95ci="( 7.0,  7.1)" t:cholscreen_adj95ci="(76.6, 77.5)" t:highchol_crude95ci="(39.2, 39.8)" t:binge_adj95ci="(15.5, 15.8)" t:bphigh_adj95ci="(31.6, 32.2)" t:csmoking_adj95ci="(12.6, 13.7)" t:casthma_adj95ci="( 8.0,  8.3)" t:highchol_adj95ci="(34.7, 35.2)" t:stroke_adj95ci="( 2.1,  2.3)" t:corem_adj95ci="(40.8, 43.7)" t:checkup_adj95ci="(73.7, 74.1)" t:stroke_crude95ci="( 2.2,  2.3)" t:bpmed_crude95ci="(77.8, 78.3)" t:access2_crude95ci="(10.2, 11.1)" t:placefips=0135896 t:copd_adj95ci="( 5.1,  5.5)" t:colon_screen_adj95ci="(72.9, 74.2)" t:diabetes_adj95ci="( 7.6,  7.8)" t:access2_adj95ci="( 9.7, 10.7)" t:obesity_crude95ci="(21.1, 21.3)" t:mammouse_crude95ci="(78.9, 80.4)" t:placename=Hoover t:chd_adj95ci="( 5.2,  5.5)" t:checkup_crude95ci="(73.9, 74.3)" t:diabetes_crude95ci="( 7.9,  8.2)" t:paptest_adj95ci="(85.8, 86.8)" t:casthma_crude95ci="( 8.0,  8.3)" t:arthritis_adj95ci="(25.0, 25.6)" t:lpa_adj95ci="(17.3, 18.3)" t:teethlost_crude95ci="( 8.6, 10.8)" t:sleep_crude95ci="(34.3, 35.0)" t:arthritis_crude95ci="(26.0, 26.6)" t:dental_crude95ci="(72.0, 73.4)" t:lpa_crude95ci="(17.5, 18.5)" t:paptest_crude95ci="(85.3, 86.2)" t:cancer_adj95ci="( 6.7,  6.9)" t:stateabbr=AL t:binge_crude95ci="(15.3, 15.5)" t:teethlost_adj95ci="( 8.5, 10.9)" t:corew_adj95ci="(40.9, 43.5)" t:copd_crude95ci="( 5.3,  5.7)" t:kidney_adj95ci="( 2.2,  2.3)" t:chd_crude95ci="( 5.4,  5.7)" t:mhlth_crude95ci="(10.5, 11.1)" t:phlth_adj95ci="( 9.7, 10.3)" t:csmoking_crude95ci="(12.7, 13.8)" m:kidney_crudeprev=2.3 m:casthma_adjprev=8.2 m:binge_crudeprev=15.4 m:corew_crudeprev=41.5 m:corew_adjprev=42.2 m:colon_screen_crudeprev=72.4 m:teethlost_adjprev=9.5 m:colon_screen_adjprev=73.6 m:stroke_adjprev=2.2 m:paptest_adjprev=86.3 m:bpmed_adjprev=63.8 m:mhlth_crudeprev=10.8 m:chd_adjprev=5.4 m:csmoking_adjprev=13.2 m:bpmed_crudeprev=78.1 m:diabetes_crudeprev=8 m:stroke_crudeprev=2.3 m:mhlth_adjprev=10.8 m:paptest_crudeprev=85.8 m:phlth_adjprev=10 m:cholscreen_crudeprev=78.1 m:population_count=81619 m:dental_crudeprev=72.7 m:cancer_adjprev=6.8 m:chd_crudeprev=5.5 m:casthma_crudeprev=8.2 m:csmoking_crudeprev=13.3 m:lpa_crudeprev=18 m:obesity_crudeprev=21.1 m:dental_adjprev=72.7 m:bphigh_crudeprev=32.9 m:diabetes_adjprev=7.7 m:corem_adjprev=42.3 m:copd_crudeprev=5.5 m:sleep_crudeprev=34.6 m:access2_adjprev=10.2 m:arthritis_crudeprev=26.3 m:checkup_adjprev=73.9 m:bphigh_adjprev=31.9 m:highchol_crudeprev=39.5 m:corem_crudeprev=41.7 m:copd_adjprev=5.3 m:cholscreen_adjprev=77 m:teethlost_crudeprev=9.6 m:arthritis_adjprev=25.3 m:cancer_crudeprev=7 m:highchol_adjprev=35 m:sleep_adjprev=34.6 m:kidney_adjprev=2.2 m:checkup_crudeprev=74.1 m:access2_crudeprev=10.6 m:lpa_adjprev=17.8 m:phlth_crudeprev=10.3 m:mammouse_crudeprev=79.7 m:obesity_adjprev=24.7 m:mammouse_adjprev=82.1 m:binge_adjprev=15.7

series e:dxpw-cm5u d:2016-10-28T16:55:34.000Z t:phlth_crude95ci="(13.8, 14.2)" t:colon_screen_crude95ci="(64.5, 65.5)" t:kidney_crude95ci="( 2.6,  2.7)" t:mammouse_adj95ci="(79.5, 80.5)" t:bpmed_adj95ci="(66.7, 67.1)" t:corew_crude95ci="(35.9, 37.5)" t:obesity_adj95ci="(31.8, 32.2)" t:bphigh_crude95ci="(37.1, 37.6)" t:cholscreen_crude95ci="(75.2, 75.9)" t:corem_crude95ci="(38.6, 40.4)" t:sleep_adj95ci="(39.4, 40.0)" t:mhlth_adj95ci="(13.8, 14.2)" t:dental_adj95ci="(60.0, 61.1)" t:cancer_crude95ci="( 6.8,  6.9)" t:cholscreen_adj95ci="(75.8, 76.5)" t:highchol_crude95ci="(40.1, 40.6)" t:binge_adj95ci="(12.2, 12.4)" t:bphigh_adj95ci="(36.5, 36.9)" t:csmoking_adj95ci="(20.8, 21.8)" t:casthma_adj95ci="( 9.5,  9.7)" t:highchol_adj95ci="(35.6, 35.9)" t:stroke_adj95ci="( 3.1,  3.2)" t:corem_adj95ci="(38.8, 40.6)" t:checkup_adj95ci="(70.6, 70.9)" t:stroke_crude95ci="( 3.3,  3.4)" t:bpmed_crude95ci="(78.9, 79.2)" t:access2_crude95ci="(16.9, 17.8)" t:placefips=0137000 t:copd_adj95ci="( 7.4,  7.7)" t:colon_screen_adj95ci="(65.3, 66.3)" t:diabetes_adj95ci="(10.5, 10.8)" t:access2_adj95ci="(15.9, 16.7)" t:obesity_crude95ci="(26.2, 26.4)" t:mammouse_crude95ci="(76.4, 77.4)" t:placename=Huntsville t:chd_adj95ci="( 6.6,  6.8)" t:checkup_crude95ci="(71.0, 71.4)" t:diabetes_crude95ci="(10.9, 11.1)" t:paptest_adj95ci="(83.1, 83.9)" t:casthma_crude95ci="( 9.6,  9.8)" t:arthritis_adj95ci="(29.2, 29.6)" t:lpa_adj95ci="(24.5, 25.3)" t:teethlost_crude95ci="(14.1, 15.7)" t:sleep_crude95ci="(38.9, 39.5)" t:arthritis_crude95ci="(29.8, 30.2)" t:dental_crude95ci="(60.1, 61.2)" t:lpa_crude95ci="(24.5, 25.4)" t:paptest_crude95ci="(82.0, 82.7)" t:cancer_adj95ci="( 6.5,  6.6)" t:stateabbr=AL t:binge_crude95ci="(12.1, 12.3)" t:teethlost_adj95ci="(13.8, 15.5)" t:corew_adj95ci="(36.1, 37.7)" t:copd_crude95ci="( 7.6,  7.9)" t:kidney_adj95ci="( 2.6,  2.6)" t:chd_crude95ci="( 6.9,  7.1)" t:mhlth_crude95ci="(13.7, 14.2)" t:phlth_adj95ci="(13.7, 14.2)" t:csmoking_crude95ci="(20.4, 21.4)" m:kidney_crudeprev=2.7 m:casthma_adjprev=9.6 m:binge_crudeprev=12.2 m:corew_crudeprev=36.6 m:corew_adjprev=36.9 m:colon_screen_crudeprev=65 m:teethlost_adjprev=14.7 m:colon_screen_adjprev=65.8 m:stroke_adjprev=3.2 m:paptest_adjprev=83.5 m:bpmed_adjprev=66.9 m:mhlth_crudeprev=14 m:chd_adjprev=6.7 m:csmoking_adjprev=21.3 m:bpmed_crudeprev=79.1 m:diabetes_crudeprev=11 m:stroke_crudeprev=3.3 m:mhlth_adjprev=14 m:paptest_crudeprev=82.4 m:phlth_adjprev=13.9 m:cholscreen_crudeprev=75.5 m:population_count=180105 m:dental_crudeprev=60.7 m:cancer_adjprev=6.5 m:chd_crudeprev=7 m:casthma_crudeprev=9.7 m:csmoking_crudeprev=20.9 m:lpa_crudeprev=25 m:obesity_crudeprev=26.4 m:dental_adjprev=60.5 m:bphigh_crudeprev=37.3 m:diabetes_adjprev=10.7 m:corem_adjprev=39.7 m:copd_crudeprev=7.7 m:sleep_crudeprev=39.2 m:access2_adjprev=16.3 m:arthritis_crudeprev=30 m:checkup_adjprev=70.8 m:bphigh_adjprev=36.7 m:highchol_crudeprev=40.3 m:corem_crudeprev=39.5 m:copd_adjprev=7.5 m:cholscreen_adjprev=76.2 m:teethlost_crudeprev=14.9 m:arthritis_adjprev=29.4 m:cancer_crudeprev=6.8 m:highchol_adjprev=35.8 m:sleep_adjprev=39.7 m:kidney_adjprev=2.6 m:checkup_crudeprev=71.2 m:access2_crudeprev=17.4 m:lpa_adjprev=24.9 m:phlth_crudeprev=14 m:mammouse_crudeprev=76.9 m:obesity_adjprev=32 m:mammouse_adjprev=80 m:binge_adjprev=12.3
```

## Meta Commands

```ls
metric m:population_count p:integer l:Population2010 d:"Population Count 2010" t:dataTypeName=number

metric m:access2_crudeprev p:float l:ACCESS2_CrudePrev d:"Model-based estimate for crude prevalence of current lack of health insurance among adults aged 18-64 years" t:dataTypeName=number

metric m:access2_adjprev p:double l:ACCESS2_AdjPrev d:"Age-adjusted prevalence estimate of current lack of health insurance among adults aged 18-64 years" t:dataTypeName=number

metric m:arthritis_crudeprev p:float l:ARTHRITIS_CrudePrev d:"Model-based estimate for crude prevalence of arthritis among adults aged >=18 years" t:dataTypeName=number

metric m:arthritis_adjprev p:float l:ARTHRITIS_AdjPrev d:"Model-based estimate for age-adjusted prevalence of arthritis among adults aged >=18 years" t:dataTypeName=number

metric m:binge_crudeprev p:float l:BINGE_CrudePrev d:"Model-based estimate for crude prevalence of binge drinking among adults aged >=18 years" t:dataTypeName=number

metric m:binge_adjprev p:float l:BINGE_AdjPrev d:"Model-based estimate for age-adjusted prevalence of binge drinking among adults aged >=18 years" t:dataTypeName=number

metric m:bphigh_crudeprev p:float l:BPHIGH_CrudePrev d:"Model-based estimate for crude prevalence of high blood pressure among adults aged >=18 years" t:dataTypeName=number

metric m:bphigh_adjprev p:float l:BPHIGH_AdjPrev d:"Model-based estimate for age-adjusted prevalence of high blood pressure among adults aged >=18 years" t:dataTypeName=number

metric m:bpmed_crudeprev p:float l:BPMED_CrudePrev d:"Model-based estimate for crude prevalence of taking medicine for high blood pressure control among adults aged >=18 years with high blood pressure" t:dataTypeName=number

metric m:bpmed_adjprev p:float l:BPMED_AdjPrev d:"Model-based estimate for age-adjusted prevalence of taking medicine for high blood pressure control among adults aged >=18 years with high blood pressure" t:dataTypeName=number

metric m:cancer_crudeprev p:float l:CANCER_CrudePrev d:"Model-based estimate for crude prevalence of cancer (excluding skin cancer) among adults aged >=18 years" t:dataTypeName=number

metric m:cancer_adjprev p:float l:CANCER_AdjPrev d:"Model-based estimate for age-adjusted prevalence of cancer (excluding skin cancer) among adults aged >=18 years" t:dataTypeName=number

metric m:casthma_crudeprev p:float l:CASTHMA_CrudePrev d:"Model-based estimate for crude prevalence of current asthma among adults aged >=18 years" t:dataTypeName=number

metric m:casthma_adjprev p:float l:CASTHMA_AdjPrev d:"Model-based estimate for age-adjusted prevalence of current asthma among adults aged >=18 years" t:dataTypeName=number

metric m:chd_crudeprev p:double l:CHD_CrudePrev d:"Model-based estimate for crude prevalence of coronary heart disease among adults aged >=18 years" t:dataTypeName=number

metric m:chd_adjprev p:float l:CHD_AdjPrev d:"Model-based estimate for age-adjusted prevalence of coronary heart disease among adults aged >=18 years" t:dataTypeName=number

metric m:checkup_crudeprev p:float l:CHECKUP_CrudePrev d:"Model-based estimate for crude prevalence of visits to doctor for routine checkup within the past year among adults aged >=18 years" t:dataTypeName=number

metric m:checkup_adjprev p:float l:CHECKUP_AdjPrev d:"Model-based estimate for age-adjusted prevalence of visits to doctor for routine checkup within the past year among adults aged >=18 years" t:dataTypeName=number

metric m:cholscreen_crudeprev p:float l:CHOLSCREEN_CrudePrev d:"Model-based estimate for crude prevalence of cholesterol screening among adults aged >=18 years" t:dataTypeName=number

metric m:cholscreen_adjprev p:float l:CHOLSCREEN_AdjPrev d:"Model-based estimate for age-adjusted prevalence of cholesterol screening among adults aged >=18 years" t:dataTypeName=number

metric m:colon_screen_crudeprev p:float l:COLON_SCREEN_CrudePrev d:"Model-based estimate for crude prevalence of fecal occult blood test, sigmoidoscopy, or colonoscopy among adults aged 50?75 years" t:dataTypeName=number

metric m:colon_screen_adjprev p:float l:COLON_SCREEN_AdjPrev d:"Model-based estimate for age-adjusted prevalence of fecal occult blood test, sigmoidoscopy, or colonoscopy among adults aged 50?75 years" t:dataTypeName=number

metric m:copd_crudeprev p:double l:COPD_CrudePrev d:"Model-based estimate for crude prevalence of chronic obstructive pulmonary disease among adults aged >=18 years" t:dataTypeName=number

metric m:copd_adjprev p:float l:COPD_AdjPrev d:"Model-based estimate for age-adjusted prevalence of chronic obstructive pulmonary disease among adults aged >=18 years" t:dataTypeName=number

metric m:corem_crudeprev p:float l:COREM_CrudePrev d:"Model-based estimate for crude prevalence of older adult men aged >=65 years who are up to date on a core set of clinical preventive services: Flu shot past year, PPV shot ever, Colorectal cancer screening" t:dataTypeName=number

metric m:corem_adjprev p:float l:COREM_AdjPrev d:"Model-based estimate for age-adjusted prevalence of older adult men aged >=65 years who are up to date on a core set of clinical preventive services: Flu shot past year, PPV shot ever, Colorectal cancer screening" t:dataTypeName=number

metric m:corew_crudeprev p:float l:COREW_CrudePrev d:"Model-based estimate for crude prevalence of older adult women aged >=65 years who are up to date on a core set of clinical preventive services: Flu shot past year, PPV shot ever, Colorectal cancer screening, and Mammogram past 2 years" t:dataTypeName=number

metric m:corew_adjprev p:float l:COREW_AdjPrev d:"Model-based estimate for age-adjusted prevalence of older adult women aged >=65 years who are up to date on a core set of clinical preventive services: Flu shot past year, PPV shot ever, Colorectal cancer screening, and Mammogram past 2 years" t:dataTypeName=number

metric m:csmoking_crudeprev p:float l:CSMOKING_CrudePrev d:"Model-based estimate for crude prevalence of current smoking among adults aged >=18 years" t:dataTypeName=number

metric m:csmoking_adjprev p:float l:CSMOKING_AdjPrev d:"Model-based estimate for age-adjusted prevalence of current smoking among adults aged >=18 years" t:dataTypeName=number

metric m:dental_crudeprev p:float l:DENTAL_CrudePrev d:"Model-based estimate for crude prevalence of visits to dentist or dental clinic among adults aged >=18 years" t:dataTypeName=number

metric m:dental_adjprev p:float l:DENTAL_AdjPrev d:"Model-based estimate for age-adjusted prevalence of visits to dentist or dental clinic among adults aged >=18 years" t:dataTypeName=number

metric m:diabetes_crudeprev p:float l:DIABETES_CrudePrev d:"Model-based estimate for crude prevalence of diagnosed diabetes among adults aged >=18 years" t:dataTypeName=number

metric m:diabetes_adjprev p:float l:DIABETES_AdjPrev d:"Model-based estimate for age-adjusted prevalence of diagnosed diabetes among adults aged >=18 years" t:dataTypeName=number

metric m:highchol_crudeprev p:float l:HIGHCHOL_CrudePrev d:"Model-based estimate for crude prevalence of high cholesterol among adults aged >=18 years who have been screened in the past 5 years" t:dataTypeName=number

metric m:highchol_adjprev p:float l:HIGHCHOL_AdjPrev d:"Model-based estimate for age-adjusted prevalence of high cholesterol among adults aged >=18 years who have been screened in the past 5 years" t:dataTypeName=number

metric m:kidney_crudeprev p:float l:KIDNEY_CrudePrev d:"Model-based estimate for crude prevalence of chronic kidney disease among adults aged >=18 years" t:dataTypeName=number

metric m:kidney_adjprev p:float l:KIDNEY_AdjPrev d:"Model-based estimate for age-adjusted prevalence of chronic kidney disease among adults aged >=18 years" t:dataTypeName=number

metric m:lpa_crudeprev p:float l:LPA_CrudePrev d:"Model-based estimate for crude prevalence of no leisure-time physical activity among adults aged >=18 years" t:dataTypeName=number

metric m:lpa_adjprev p:float l:LPA_AdjPrev d:"Model-based estimate for age-adjusted prevalence of no leisure-time physical activity among adults aged >=18 years" t:dataTypeName=number

metric m:mammouse_crudeprev p:float l:MAMMOUSE_CrudePrev d:"Model-based estimate for crude prevalence of mammography use among women aged 50?74 years" t:dataTypeName=number

metric m:mammouse_adjprev p:float l:MAMMOUSE_AdjPrev d:"Model-based estimate for age-adjusted prevalence of mammography use among women aged 50?74 years" t:dataTypeName=number

metric m:mhlth_crudeprev p:float l:MHLTH_CrudePrev d:"Model-based estimate for crude prevalence of mental health not good for >=14 days among adults aged >=18 years" t:dataTypeName=number

metric m:mhlth_adjprev p:float l:MHLTH_AdjPrev d:"Model-based estimate for age-adjusted prevalence of mental health not good for >=14 days among adults aged >=18 years" t:dataTypeName=number

metric m:obesity_crudeprev p:float l:OBESITY_CrudePrev d:"Model-based estimate for crude prevalence of obesity among adults aged >=18 years" t:dataTypeName=number

metric m:obesity_adjprev p:float l:OBESITY_AdjPrev d:"Model-based estimate for age-adjusted prevalence of obesity among adults aged >=18 years" t:dataTypeName=number

metric m:paptest_crudeprev p:float l:PAPTEST_CrudePrev d:"Model-based estimate for crude prevalence of papanicolaou smear use among adult women aged 21?65 years" t:dataTypeName=number

metric m:paptest_adjprev p:float l:PAPTEST_AdjPrev d:"Model-based estimate for age-adjusted prevalence of papanicolaou smear use among adult women aged 21?65 years" t:dataTypeName=number

metric m:phlth_crudeprev p:float l:PHLTH_CrudePrev d:"Model-based estimate for crude prevalence of physical health not good for >=14 days among adults aged >=18 years" t:dataTypeName=number

metric m:phlth_adjprev p:float l:PHLTH_AdjPrev d:"Model-based estimate for age-adjusted prevalence of physical health not good for >=14 days among adults aged >=18 years" t:dataTypeName=number

metric m:sleep_crudeprev p:float l:SLEEP_CrudePrev d:"Model-based estimate for crude prevalence of sleeping less than 7 hours among adults aged >=18 years" t:dataTypeName=number

metric m:sleep_adjprev p:double l:SLEEP_AdjPrev d:"Model-based estimate for age-adjusted prevalence of sleeping less than 7 hours among adults aged >=18 years" t:dataTypeName=number

metric m:stroke_crudeprev p:float l:STROKE_CrudePrev d:"Model-based estimate for crude prevalence of stroke among adults aged >=18 years" t:dataTypeName=number

metric m:stroke_adjprev p:float l:STROKE_AdjPrev d:"Model-based estimate for age-adjusted prevalence of stroke among adults aged >=18 years" t:dataTypeName=number

metric m:teethlost_crudeprev p:float l:TEETHLOST_CrudePrev d:"Model-based estimate for crude prevalence of all teeth lost among adults aged >=65 years" t:dataTypeName=number

metric m:teethlost_adjprev p:float l:TEETHLOST_AdjPrev d:"Model-based estimate for age-adjusted prevalence of all teeth lost among adults aged >=65 years" t:dataTypeName=number

entity e:dxpw-cm5u l:"500 Cities: City-level Data (GIS Friendly Format)" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Population Health" t:url=https://chronicdata.cdc.gov/api/views/dxpw-cm5u

property e:dxpw-cm5u t:meta.view v:id=dxpw-cm5u v:category="500 Cities" v:attributionLink=http://www.cdc.gov/nccdphp/dph/ v:averageRating=0 v:name="500 Cities: City-level Data (GIS Friendly Format)" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Division of Population Health"

property e:dxpw-cm5u t:meta.view.license v:name="Public Domain"

property e:dxpw-cm5u t:meta.view.owner v:id=fwb6-kmt3 v:screenName=hiz4@cdc.gov v:lastNotificationSeenAt=1492540125 v:displayName=hiz4@cdc.gov

property e:dxpw-cm5u t:meta.view.tableauthor v:id=fwb6-kmt3 v:screenName=hiz4@cdc.gov v:roleName=publisher v:lastNotificationSeenAt=1492540125 v:displayName=hiz4@cdc.gov

property e:dxpw-cm5u t:meta.view.metadata.custom_fields.common_core v:Publisher="CDC Info" v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC Info" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| :updated_at | stateabbr | placename  | placefips | population_count | access2_crudeprev | access2_crude95ci | access2_adjprev | access2_adj95ci | arthritis_crudeprev | arthritis_crude95ci | arthritis_adjprev | arthritis_adj95ci | binge_crudeprev | binge_crude95ci | binge_adjprev | binge_adj95ci | bphigh_crudeprev | bphigh_crude95ci | bphigh_adjprev | bphigh_adj95ci | bpmed_crudeprev | bpmed_crude95ci | bpmed_adjprev | bpmed_adj95ci | cancer_crudeprev | cancer_crude95ci | cancer_adjprev | cancer_adj95ci | casthma_crudeprev | casthma_crude95ci | casthma_adjprev | casthma_adj95ci | chd_crudeprev | chd_crude95ci | chd_adjprev | chd_adj95ci | checkup_crudeprev | checkup_crude95ci | checkup_adjprev | checkup_adj95ci | cholscreen_crudeprev | cholscreen_crude95ci | cholscreen_adjprev | cholscreen_adj95ci | colon_screen_crudeprev | colon_screen_crude95ci | colon_screen_adjprev | colon_screen_adj95ci | copd_crudeprev | copd_crude95ci | copd_adjprev | copd_adj95ci | corem_crudeprev | corem_crude95ci | corem_adjprev | corem_adj95ci | corew_crudeprev | corew_crude95ci | corew_adjprev | corew_adj95ci | csmoking_crudeprev | csmoking_crude95ci | csmoking_adjprev | csmoking_adj95ci | dental_crudeprev | dental_crude95ci | dental_adjprev | dental_adj95ci | diabetes_crudeprev | diabetes_crude95ci | diabetes_adjprev | diabetes_adj95ci | highchol_crudeprev | highchol_crude95ci | highchol_adjprev | highchol_adj95ci | kidney_crudeprev | kidney_crude95ci | kidney_adjprev | kidney_adj95ci | lpa_crudeprev | lpa_crude95ci | lpa_adjprev | lpa_adj95ci  | mammouse_crudeprev | mammouse_crude95ci | mammouse_adjprev | mammouse_adj95ci | mhlth_crudeprev | mhlth_crude95ci | mhlth_adjprev | mhlth_adj95ci | obesity_crudeprev | obesity_crude95ci | obesity_adjprev | obesity_adj95ci | paptest_crudeprev | paptest_crude95ci | paptest_adjprev | paptest_adj95ci | phlth_crudeprev | phlth_crude95ci | phlth_adjprev | phlth_adj95ci | sleep_crudeprev | sleep_crude95ci | sleep_adjprev | sleep_adj95ci | stroke_crudeprev | stroke_crude95ci | stroke_adjprev | stroke_adj95ci | teethlost_crudeprev | teethlost_crude95ci | teethlost_adjprev | teethlost_adj95ci | geolocation                      | 
| =========== | ========= | ========== | ========= | ================ | ================= | ================= | =============== | =============== | =================== | =================== | ================= | ================= | =============== | =============== | ============= | ============= | ================ | ================ | ============== | ============== | =============== | =============== | ============= | ============= | ================ | ================ | ============== | ============== | ================= | ================= | =============== | =============== | ============= | ============= | =========== | =========== | ================= | ================= | =============== | =============== | ==================== | ==================== | ================== | ================== | ====================== | ====================== | ==================== | ==================== | ============== | ============== | ============ | ============ | =============== | =============== | ============= | ============= | =============== | =============== | ============= | ============= | ================== | ================== | ================ | ================ | ================ | ================ | ============== | ============== | ================== | ================== | ================ | ================ | ================== | ================== | ================ | ================ | ================ | ================ | ============== | ============== | ============= | ============= | =========== | ============ | ================== | ================== | ================ | ================ | =============== | =============== | ============= | ============= | ================= | ================= | =============== | =============== | ================= | ================= | =============== | =============== | =============== | =============== | ============= | ============= | =============== | =============== | ============= | ============= | ================ | ================ | ============== | ============== | =================== | =================== | ================= | ================= | ================================ | 
| 1477673734  | AL        | Birmingham | 0107000   | 212237           | 22.6              | (22.1, 23.0)      | 21.4            | (21.0, 21.8)    | 32.6                | (32.5, 32.8)        | 32.6              | (32.5, 32.8)      | 11.5            | (11.5, 11.6)    | 11.4          | (11.3, 11.4)  | 45.6             | (45.5, 45.8)     | 45.9           | (45.7, 46.1)   | 81.4            | (81.3, 81.5)    | 70.5          | (70.3, 70.6)  | 6.1              | ( 6.0, 6.1)      | 6.1            | ( 6.1, 6.1)    | 11.4              | (11.3, 11.5)      | 11.4            | (11.3, 11.5)    | 7.7           | ( 7.6, 7.8)   | 7.6         | ( 7.6, 7.7) | 77.3              | (77.2, 77.4)      | 77.3            | (77.2, 77.4)    | 73.3                 | (73.0, 73.6)         | 74.4               | (74.1, 74.7)       | 61.1                   | (60.6, 61.6)           | 62.7                 | (62.2, 63.1)         | 9.5            | ( 9.3, 9.7)    | 9.4          | ( 9.3, 9.6)  | 29.9            | (29.2, 30.5)    | 30.3          | (29.6, 30.9)  | 27.3            | (26.7, 27.9)    | 27.9          | (27.3, 28.4)  | 21.9               | (21.5, 22.3)       | 22               | (21.6, 22.3)     | 49.3             | (48.7, 49.8)     | 49.1           | (48.6, 49.6)   | 16.2               | (16.0, 16.3)       | 16.1             | (16.0, 16.2)     | 39.7               | (39.5, 39.9)       | 35.4             | (35.3, 35.6)     | 3.3              | ( 3.3, 3.3)      | 3.3            | ( 3.3, 3.3)    | 31.5          | (31.2, 31.9)  | 31.7        | (31.3, 32.1) | 76.8               | (76.4, 77.2)       | 79.7             | (79.3, 80.1)     | 17              | (16.8, 17.2)    | 17            | (16.7, 17.2)  | 31.7              | (31.6, 31.7)      | 39              | (38.8, 39.1)    | 78.6              | (78.2, 78.9)      | 80.1            | (79.7, 80.4)    | 18.3            | (18.0, 18.5)    | 18.3          | (18.0, 18.5)  | 46.5            | (46.3, 46.7)    | 46.9          | (46.6, 47.0)  | 5                | ( 5.0, 5.1)      | 5              | ( 5.0, 5.1)    | 26.1                | (25.1, 27.2)        | 25.9              | (25.0, 26.9)      | (33.52756637730, -86.7988174678) | 
| 1477673734  | AL        | Hoover     | 0135896   | 81619            | 10.6              | (10.2, 11.1)      | 10.2            | ( 9.7, 10.7)    | 26.3                | (26.0, 26.6)        | 25.3              | (25.0, 25.6)      | 15.4            | (15.3, 15.5)    | 15.7          | (15.5, 15.8)  | 32.9             | (32.6, 33.2)     | 31.9           | (31.6, 32.2)   | 78.1            | (77.8, 78.3)    | 63.8          | (63.6, 64.1)  | 7                | ( 7.0, 7.1)      | 6.8            | ( 6.7, 6.9)    | 8.2               | ( 8.0, 8.3)       | 8.2             | ( 8.0, 8.3)     | 5.5           | ( 5.4, 5.7)   | 5.4         | ( 5.2, 5.5) | 74.1              | (73.9, 74.3)      | 73.9            | (73.7, 74.1)    | 78.1                 | (77.6, 78.5)         | 77                 | (76.6, 77.5)       | 72.4                   | (71.7, 73.1)           | 73.6                 | (72.9, 74.2)         | 5.5            | ( 5.3, 5.7)    | 5.3          | ( 5.1, 5.5)  | 41.7            | (40.2, 43.1)    | 42.3          | (40.8, 43.7)  | 41.5            | (40.2, 42.7)    | 42.2          | (40.9, 43.5)  | 13.3               | (12.7, 13.8)       | 13.2             | (12.6, 13.7)     | 72.7             | (72.0, 73.4)     | 72.7           | (71.9, 73.4)   | 8                  | ( 7.9, 8.2)        | 7.7              | ( 7.6, 7.8)      | 39.5               | (39.2, 39.8)       | 35               | (34.7, 35.2)     | 2.3              | ( 2.2, 2.3)      | 2.2            | ( 2.2, 2.3)    | 18            | (17.5, 18.5)  | 17.8        | (17.3, 18.3) | 79.7               | (78.9, 80.4)       | 82.1             | (81.4, 82.9)     | 10.8            | (10.5, 11.1)    | 10.8          | (10.5, 11.1)  | 21.1              | (21.1, 21.3)      | 24.7            | (24.4, 25.0)    | 85.8              | (85.3, 86.2)      | 86.3            | (85.8, 86.8)    | 10.3            | (10.0, 10.6)    | 10            | ( 9.7, 10.3)  | 34.6            | (34.3, 35.0)    | 34.6          | (34.2, 35.0)  | 2.3              | ( 2.2, 2.3)      | 2.2            | ( 2.1, 2.3)    | 9.6                 | ( 8.6, 10.8)        | 9.5               | ( 8.5, 10.9)      | (33.37676027290, -86.8051937568) | 
| 1477673734  | AL        | Huntsville | 0137000   | 180105           | 17.4              | (16.9, 17.8)      | 16.3            | (15.9, 16.7)    | 30                  | (29.8, 30.2)        | 29.4              | (29.2, 29.6)      | 12.2            | (12.1, 12.3)    | 12.3          | (12.2, 12.4)  | 37.3             | (37.1, 37.6)     | 36.7           | (36.5, 36.9)   | 79.1            | (78.9, 79.2)    | 66.9          | (66.7, 67.1)  | 6.8              | ( 6.8, 6.9)      | 6.5            | ( 6.5, 6.6)    | 9.7               | ( 9.6, 9.8)       | 9.6             | ( 9.5, 9.7)     | 7             | ( 6.9, 7.1)   | 6.7         | ( 6.6, 6.8) | 71.2              | (71.0, 71.4)      | 70.8            | (70.6, 70.9)    | 75.5                 | (75.2, 75.9)         | 76.2               | (75.8, 76.5)       | 65                     | (64.5, 65.5)           | 65.8                 | (65.3, 66.3)         | 7.7            | ( 7.6, 7.9)    | 7.5          | ( 7.4, 7.7)  | 39.5            | (38.6, 40.4)    | 39.7          | (38.8, 40.6)  | 36.6            | (35.9, 37.5)    | 36.9          | (36.1, 37.7)  | 20.9               | (20.4, 21.4)       | 21.3             | (20.8, 21.8)     | 60.7             | (60.1, 61.2)     | 60.5           | (60.0, 61.1)   | 11                 | (10.9, 11.1)       | 10.7             | (10.5, 10.8)     | 40.3               | (40.1, 40.6)       | 35.8             | (35.6, 35.9)     | 2.7              | ( 2.6, 2.7)      | 2.6            | ( 2.6, 2.6)    | 25            | (24.5, 25.4)  | 24.9        | (24.5, 25.3) | 76.9               | (76.4, 77.4)       | 80               | (79.5, 80.5)     | 14              | (13.7, 14.2)    | 14            | (13.8, 14.2)  | 26.4              | (26.2, 26.4)      | 32              | (31.8, 32.2)    | 82.4              | (82.0, 82.7)      | 83.5            | (83.1, 83.9)    | 14              | (13.8, 14.2)    | 13.9          | (13.7, 14.2)  | 39.2            | (38.9, 39.5)    | 39.7          | (39.4, 40.0)  | 3.3              | ( 3.3, 3.4)      | 3.2            | ( 3.1, 3.2)    | 14.9                | (14.1, 15.7)        | 14.7              | (13.8, 15.5)      | (34.69896926710, -86.6387042882) | 
| 1477673734  | AL        | Mobile     | 0150000   | 195111           | 20                | (19.6, 20.4)      | 19.1            | (18.7, 19.5)    | 33.1                | (32.9, 33.2)        | 31.8              | (31.7, 32.0)      | 12.5            | (12.4, 12.6)    | 12.8          | (12.7, 12.8)  | 44.1             | (43.9, 44.2)     | 43             | (42.8, 43.2)   | 81.1            | (81.0, 81.2)    | 69.3          | (69.1, 69.4)  | 6.9              | ( 6.8, 6.9)      | 6.5            | ( 6.4, 6.5)    | 10.7              | (10.6, 10.8)      | 10.7            | (10.6, 10.8)    | 8.2           | ( 8.1, 8.2)   | 7.6         | ( 7.5, 7.7) | 73                | (72.9, 73.1)      | 72.4            | (72.3, 72.5)    | 73.2                 | (72.9, 73.5)         | 73.2               | (72.9, 73.5)       | 61.6                   | (61.2, 62.1)           | 62.7                 | (62.3, 63.1)         | 9.1            | ( 8.9, 9.2)    | 8.7          | ( 8.5, 8.8)  | 33.9            | (33.2, 34.6)    | 34.3          | (33.6, 35.0)  | 31.6            | (31.0, 32.2)    | 32.2          | (31.6, 32.9)  | 21.5               | (21.2, 21.9)       | 22               | (21.6, 22.3)     | 52.9             | (52.4, 53.4)     | 52.6           | (52.1, 53.1)   | 14.5               | (14.3, 14.6)       | 13.8             | (13.7, 13.9)     | 43.1               | (42.9, 43.3)       | 37.6             | (37.5, 37.7)     | 3.2              | ( 3.1, 3.2)      | 3.1            | ( 3.0, 3.1)    | 27.6          | (27.3, 28.0)  | 27.4        | (27.1, 27.8) | 76                 | (75.6, 76.5)       | 80.1             | (79.7, 80.5)     | 15.7            | (15.5, 15.9)    | 15.8          | (15.6, 16.0)  | 30.8              | (30.7, 30.9)      | 37.6            | (37.4, 37.8)    | 80.8              | (80.5, 81.1)      | 81.9            | (81.6, 82.2)    | 16.6            | (16.4, 16.8)    | 16.3          | (16.1, 16.5)  | 41.6            | (41.4, 41.8)    | 42.2          | (42.0, 42.4)  | 4.3              | ( 4.3, 4.4)      | 4.1            | ( 4.0, 4.1)    | 24.3                | (23.4, 25.3)        | 24.1              | (23.1, 25.0)      | (30.67762486480, -88.1184482714) | 
| 1477673734  | AL        | Montgomery | 0151000   | 205764           | 19.7              | (19.2, 20.2)      | 18.5            | (18.1, 19.0)    | 31                  | (30.8, 31.2)        | 31.4              | (31.2, 31.6)      | 12.5            | (12.4, 12.5)    | 12.2          | (12.2, 12.3)  | 40.1             | (39.9, 40.3)     | 40.6           | (40.4, 40.8)   | 80.6            | (80.4, 80.7)    | 70.3          | (70.1, 70.5)  | 6.2              | ( 6.2, 6.3)      | 6.4            | ( 6.3, 6.4)    | 10.8              | (10.7, 11.0)      | 10.8            | (10.7, 10.9)    | 7.1           | ( 7.0, 7.2)   | 7.2         | ( 7.1, 7.3) | 75                | (74.9, 75.2)      | 75.2            | (75.0, 75.3)    | 74                   | (73.6, 74.3)         | 75.1               | (74.8, 75.4)       | 62.1                   | (61.6, 62.6)           | 63.3                 | (62.7, 63.9)         | 8.6            | ( 8.5, 8.8)    | 8.6          | ( 8.5, 8.8)  | 31.6            | (30.9, 32.4)    | 32.1          | (31.3, 32.9)  | 27.2            | (26.5, 27.9)    | 27.7          | (27.0, 28.3)  | 21.4               | (20.9, 21.8)       | 21.3             | (20.9, 21.8)     | 57.1             | (56.6, 57.7)     | 57.1           | (56.6, 57.7)   | 13.2               | (13.0, 13.3)       | 13.3             | (13.1, 13.4)     | 40.7               | (40.5, 40.9)       | 36.9             | (36.7, 37.0)     | 3                | ( 3.0, 3.0)      | 3.1            | ( 3.0, 3.1)    | 27.7          | (27.3, 28.1)  | 27.9        | (27.5, 28.3) | 77.1               | (76.5, 77.6)       | 80.2             | (79.6, 80.7)     | 15.6            | (15.3, 15.8)    | 15.5          | (15.2, 15.7)  | 30.2              | (30.0, 30.3)      | 36.8            | (36.6, 37.1)    | 81.7              | (81.3, 82.1)      | 83              | (82.7, 83.4)    | 16.1            | (15.9, 16.3)    | 16.2          | (16.0, 16.4)  | 41.1            | (40.8, 41.4)    | 41.3          | (41.0, 41.5)  | 4                | ( 3.9, 4.1)      | 4.1            | ( 4.0, 4.1)    | 21.2                | (20.3, 22.2)        | 21.2              | (20.1, 22.2)      | (32.34726453330, -86.2677059552) | 
| 1477673734  | AL        | Tuscaloosa | 0177256   | 90468            | 20.3              | (19.4, 21.4)      | 18.5            | (17.9, 19.2)    | 24.8                | (24.6, 25.0)        | 32.3              | (32.1, 32.6)      | 14.4            | (14.1, 14.6)    | 12.1          | (11.9, 12.2)  | 31.7             | (31.4, 32.1)     | 40             | (39.7, 40.3)   | 74.6            | (74.2, 75.0)    | 69            | (68.8, 69.3)  | 5                | ( 4.9, 5.0)      | 6.5            | ( 6.4, 6.6)    | 11.2              | (11.0, 11.5)      | 10.9            | (10.7, 11.1)    | 5.6           | ( 5.5, 5.7)   | 7.4         | ( 7.2, 7.5) | 71.2              | (70.7, 71.6)      | 74.3            | (74.1, 74.5)    | 63.4                 | (62.2, 64.4)         | 74.4               | (73.9, 74.9)       | 63.1                   | (62.3, 63.8)           | 64.2                 | (63.4, 64.9)         | 7.6            | ( 7.4, 7.8)    | 9.1          | ( 8.9, 9.4)  | 35.5            | (34.2, 36.8)    | 36            | (34.7, 37.3)  | 33.2            | (32.2, 34.2)    | 33.7          | (32.7, 34.8)  | 22.9               | (21.9, 23.9)       | 23.2             | (22.6, 23.9)     | 57.2             | (55.9, 58.3)     | 56.4           | (55.6, 57.2)   | 10.2               | (10.0, 10.3)       | 13.6             | (13.4, 13.8)     | 38                 | (37.5, 38.6)       | 38.7             | (38.5, 38.9)     | 2.3              | ( 2.3, 2.4)      | 2.9            | ( 2.9, 3.0)    | 25.8          | (25.1, 26.5)  | 28.6        | (28.0, 29.2) | 77.1               | (76.4, 77.8)       | 79.8             | (79.1, 80.5)     | 16.3            | (15.9, 16.8)    | 15.9          | (15.5, 16.2)  | 31.8              | (31.6, 31.9)      | 38.5            | (38.2, 38.8)    | 77.2              | (76.3, 78.0)      | 81              | (80.4, 81.5)    | 14.1            | (13.7, 14.5)    | 16.6          | (16.2, 16.9)  | 39.5            | (39.0, 40.0)    | 41.4          | (41.0, 41.8)  | 3.1              | ( 3.0, 3.2)      | 4.1            | ( 4.0, 4.2)    | 20.9                | (19.5, 22.4)        | 20.6              | (19.2, 21.9)      | (33.23360839510, -87.5268004073) | 
| 1477673734  | AK        | Anchorage  | 0203000   | 291826           | 15.5              | (15.2, 15.8)      | 14.5            | (14.3, 14.8)    | 19.3                | (19.2, 19.4)        | 21.3              | (21.2, 21.4)      | 21.6            | (21.5, 21.7)    | 20.2          | (20.1, 20.3)  | 27.8             | (27.6, 27.9)     | 30.2           | (30.1, 30.4)   | 62.1            | (62.0, 62.3)    | 49            | (48.8, 49.1)  | 5.3              | ( 5.2, 5.3)      | 6.2            | ( 6.1, 6.2)    | 8.7               | ( 8.6, 8.8)       | 8.6             | ( 8.5, 8.6)     | 4.2           | ( 4.1, 4.2)   | 5           | ( 4.9, 5.1) | 58.9              | (58.8, 59.1)      | 60.7            | (60.6, 60.8)    | 68                   | (67.7, 68.3)         | 70.2               | (69.9, 70.4)       | 57.5                   | (56.9, 58.0)           | 60.3                 | (59.9, 60.7)         | 4.7            | ( 4.6, 4.8)    | 5            | ( 5.0, 5.1)  | 32.4            | (31.7, 33.1)    | 33.4          | (32.8, 34.1)  | 28.8            | (28.2, 29.4)    | 29            | (28.4, 29.6)  | 19.2               | (18.9, 19.6)       | 18.3             | (18.0, 18.6)     | 65.8             | (65.3, 66.2)     | 66             | (65.5, 66.4)   | 7.4                | ( 7.3, 7.5)        | 8.2              | ( 8.1, 8.2)      | 35.9               | (35.7, 36.0)       | 32.9             | (32.8, 33.1)     | 2.1              | ( 2.0, 2.1)      | 2.3            | ( 2.3, 2.3)    | 18.5          | (18.2, 18.7)  | 19.2        | (19.0, 19.5) | 68.9               | (68.3, 69.4)       | 70.4             | (69.9, 70.9)     | 9.8             | ( 9.6, 9.9)     | 9.4           | ( 9.2, 9.5)   | 22.3              | (22.3, 22.4)      | 27.7            | (27.5, 27.9)    | 78.3              | (78.0, 78.7)      | 79.9            | (79.6, 80.2)    | 9.6             | ( 9.5, 9.8)     | 9.9           | ( 9.8, 10.1)  | 34              | (33.8, 34.2)    | 33.4          | (33.2, 33.6)  | 2.2              | ( 2.2, 2.2)      | 2.6            | ( 2.6, 2.6)    | 12.6                | (12.1, 13.2)        | 13                | (12.4, 13.7)      | (61.14986873100, -149.111113424) | 
| 1477673734  | AZ        | Avondale   | 0404720   | 76238            | 23.4              | (22.6, 24.1)      | 21.4            | (20.8, 22.1)    | 18.5                | (18.3, 18.6)        | 23                | (22.8, 23.2)      | 16.6            | (16.5, 16.8)    | 14.7          | (14.6, 14.8)  | 23.3             | (23.1, 23.5)     | 28.4           | (28.1, 28.6)   | 66.5            | (66.2, 66.8)    | 56            | (55.7, 56.2)  | 4.1              | ( 4.0, 4.1)      | 5.5            | ( 5.5, 5.6)    | 10                | ( 9.9, 10.2)      | 9.9             | ( 9.8, 10.0)    | 4.3           | ( 4.2, 4.3)   | 6.1         | ( 6.0, 6.2) | 61.8              | (61.5, 62.0)      | 64.8            | (64.6, 65.0)    | 66.1                 | (65.5, 66.6)         | 70.7               | (70.3, 71.2)       | 56.6                   | (55.8, 57.4)           | 59                   | (58.3, 59.8)         | 5.5            | ( 5.3, 5.6)    | 6.5          | ( 6.3, 6.7)  | 28.3            | (27.3, 29.3)    | 29.1          | (28.1, 30.1)  | 27.5            | (26.7, 28.4)    | 27.5          | (26.7, 28.4)  | 19.7               | (19.2, 20.3)       | 18.5             | (18.1, 19.0)     | 56.4             | (55.6, 57.2)     | 56.7           | (55.9, 57.4)   | 8.7                | ( 8.6, 8.8)        | 11               | (10.9, 11.2)     | 34.1               | (33.9, 34.4)       | 33.9             | (33.7, 34.1)     | 2.9              | ( 2.8, 2.9)      | 3.6            | ( 3.6, 3.7)    | 22.6          | (22.1, 23.1)  | 24.3        | (23.9, 24.8) | 75.9               | (75.3, 76.6)       | 77.2             | (76.6, 78.0)     | 13.1            | (12.8, 13.4)    | 12.6          | (12.3, 12.8)  | 23.4              | (23.2, 23.5)      | 30.1            | (29.9, 30.3)    | 79.7              | (79.2, 80.3)      | 80.3            | (79.9, 80.9)    | 12.1            | (11.9, 12.4)    | 13.5          | (13.2, 13.8)  | 37              | (36.8, 37.3)    | 36.2          | (35.9, 36.5)  | 2.3              | ( 2.2, 2.3)      | 3.1            | ( 3.0, 3.2)    | 15.3                | (14.2, 16.5)        | 16.1              | (14.9, 17.2)      | (33.38583674050, -112.323626619) | 
| 1477673734  | AZ        | Chandler   | 0412000   | 236123           | 13.1              | (12.8, 13.5)      | 12.3            | (12.0, 12.7)    | 19.4                | (19.3, 19.5)        | 21.2              | (21.1, 21.4)      | 17              | (16.9, 17.1)    | 16.2          | (16.1, 16.2)  | 24               | (23.8, 24.1)     | 26             | (25.9, 26.2)   | 69.1            | (68.9, 69.3)    | 54.8          | (54.6, 54.9)  | 5.2              | ( 5.2, 5.2)      | 6              | ( 6.0, 6.1)    | 9.2               | ( 9.2, 9.3)       | 9.1             | ( 9.1, 9.2)     | 4.2           | ( 4.1, 4.2)   | 5           | ( 4.9, 5.1) | 64.6              | (64.5, 64.7)      | 66.1            | (65.9, 66.2)    | 71.8                 | (71.5, 72.1)         | 72.8               | (72.5, 73.1)       | 64.8                   | (64.3, 65.2)           | 67                   | (66.5, 67.4)         | 4.9            | ( 4.8, 5.0)    | 5.3          | ( 5.2, 5.4)  | 33.8            | (32.9, 34.6)    | 34.5          | (33.6, 35.3)  | 34.8            | (34.0, 35.6)    | 35.2          | (34.3, 36.0)  | 16.1               | (15.7, 16.4)       | 15.3             | (15.0, 15.6)     | 67.7             | (67.2, 68.2)     | 68             | (67.5, 68.4)   | 7.1                | ( 7.0, 7.1)        | 7.7              | ( 7.7, 7.8)      | 35.5               | (35.3, 35.7)       | 33.1             | (32.9, 33.2)     | 2.8              | ( 2.8, 2.8)      | 3.1            | ( 3.1, 3.2)    | 17            | (16.7, 17.2)  | 17.4        | (17.1, 17.8) | 78.6               | (78.2, 79.0)       | 80.3             | (79.9, 80.7)     | 10.5            | (10.4, 10.7)    | 10.2          | (10.0, 10.3)  | 19.9              | (19.8, 20.0)      | 24.5            | (24.3, 24.6)    | 83                | (82.6, 83.3)      | 83.5            | (83.2, 83.8)    | 9.4             | ( 9.3, 9.6)     | 9.7           | ( 9.5, 9.8)   | 33.7            | (33.5, 33.9)    | 32.9          | (32.7, 33.1)  | 2                | ( 2.0, 2.1)      | 2.4            | ( 2.3, 2.4)    | 9.7                 | ( 9.1, 10.5)        | 9.9               | ( 9.2, 10.7)      | (33.28318981000, -111.852210033) | 
| 1477673734  | AZ        | Gilbert    | 0427400   | 208453           | 10.5              | (10.2, 10.8)      | 9.7             | ( 9.5, 10.0)    | 18.2                | (18.0, 18.3)        | 20.8              | (20.7, 21.0)      | 18.5            | (18.4, 18.6)    | 17.2          | (17.1, 17.2)  | 22.2             | (22.0, 22.4)     | 25.3           | (25.1, 25.5)   | 67.2            | (66.9, 67.4)    | 54.2          | (54.0, 54.3)  | 5                | ( 4.9, 5.0)      | 6.1            | ( 6.1, 6.2)    | 9.1               | ( 9.0, 9.2)       | 9               | ( 8.9, 9.0)     | 3.7           | ( 3.6, 3.7)   | 4.8         | ( 4.7, 4.9) | 64.2              | (64.1, 64.4)      | 66.3            | (66.2, 66.4)    | 72.3                 | (71.9, 72.7)         | 73.8               | (73.4, 74.1)       | 66.5                   | (66.0, 67.0)           | 69                   | (68.5, 69.4)         | 4.5            | ( 4.4, 4.6)    | 4.9          | ( 4.8, 5.1)  | 34.6            | (33.7, 35.5)    | 35.7          | (34.8, 36.5)  | 36.7            | (35.8, 37.6)    | 36.9          | (36.1, 37.7)  | 15.8               | (15.4, 16.2)       | 14.7             | (14.3, 15.1)     | 70.8             | (70.2, 71.3)     | 71.2           | (70.6, 71.7)   | 6.1                | ( 6.0, 6.2)        | 7.1              | ( 7.0, 7.1)      | 34.1               | (33.9, 34.2)       | 32.8             | (32.6, 32.9)     | 2.6              | ( 2.6, 2.6)      | 3              | ( 3.0, 3.1)    | 14.9          | (14.6, 15.2)  | 15.6        | (15.3, 15.9) | 79.6               | (79.1, 80.1)       | 81.2             | (80.7, 81.7)     | 10.1            | ( 9.9, 10.3)    | 9.6           | ( 9.5, 9.8)   | 19.2              | (19.1, 19.3)      | 23.5            | (23.3, 23.7)    | 84.7              | (84.4, 85.0)      | 85              | (84.6, 85.3)    | 8.4             | ( 8.3, 8.6)     | 8.8           | ( 8.6, 8.9)   | 33.2            | (32.9, 33.4)    | 32            | (31.8, 32.3)  | 1.8              | ( 1.7, 1.8)      | 2.2            | ( 2.1, 2.2)    | 7.9                 | ( 7.4, 8.5)         | 8.3               | ( 7.7, 9.0)       | (33.31014939200, -111.746237467) | 
```