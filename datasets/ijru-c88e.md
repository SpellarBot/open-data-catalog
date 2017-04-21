# Hose Nozzle And Sprayer Survey

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hose-nozzle-and-sprayer-survey-f9c07) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ijru-c88e) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ijru-c88e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ijru-c88e/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ijru-c88e |
| Name | Hose Nozzle And Sprayer Survey |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | dep, department of environmental protection, environment, hose nozzle, sprayer, drought, emergency, hose nozzle and sprayer survey, healthy living |
| Created | 2013-02-01T14:29:16Z |
| Publication Date | 2013-06-21T19:45:36Z |

## Description

List of hose nozzles and sprayers that meet the requirements during a drought emergency.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | manufacturer             | Manufacturer             | text      | text        |
| Yes      | series tag     | model                    | Model                    | text      | text        |
| Yes      | numeric metric | cost                     | Cost                     | money     | money       |
| Yes      | numeric metric | minimum_flow_rate_gpm    | Minimum Flow Rate (gpm)  | number    | number      |
| Yes      | numeric metric | minimum_flow_p_s_i       | Minimum Flow P.S.I.      | number    | number      |
| Yes      | numeric metric | maximum_flow_rate_gpm    | Maximum Flow Rate (gpm)  | number    | number      |
| Yes      | numeric metric | maximum_flow_p_s_i       | Maximum Flow P.S.I.      | number    | number      |
| Yes      | series tag     | spray_patterns_available | Spray Patterns Available | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ijru-c88e d:2013-02-01T06:29:18.000Z t:model="E-Z Squeeze" t:manufacturer=Nelson t:spray_patterns_available="Adjustable Flow Control" m:minimum_flow_rate_gpm=1 m:maximum_flow_p_s_i=52 m:cost=7.96 m:maximum_flow_rate_gpm=3.25 m:minimum_flow_p_s_i=52

series e:ijru-c88e d:2013-02-01T06:29:18.000Z t:model="Metal Sprayer" t:manufacturer=Nelson t:spray_patterns_available="Four Patterns" m:minimum_flow_rate_gpm=0.4 m:maximum_flow_p_s_i=52 m:cost=5.97 m:maximum_flow_rate_gpm=5 m:minimum_flow_p_s_i=52

series e:ijru-c88e d:2013-02-01T06:29:18.000Z t:model="Plastic - Flow Control Pistol Nozzle" t:manufacturer=Nelson t:spray_patterns_available="Adjustable Spray Pattern" m:minimum_flow_rate_gpm=1.5 m:maximum_flow_p_s_i=52 m:cost=5.99 m:maximum_flow_rate_gpm=3.5 m:minimum_flow_p_s_i=52
```

## Meta Commands

```ls
metric m:cost p:double l:Cost t:dataTypeName=money

metric m:minimum_flow_rate_gpm p:float l:"Minimum Flow Rate (gpm)" t:dataTypeName=number

metric m:minimum_flow_p_s_i p:integer l:"Minimum Flow P.S.I." t:dataTypeName=number

metric m:maximum_flow_rate_gpm p:float l:"Maximum Flow Rate (gpm)" t:dataTypeName=number

metric m:maximum_flow_p_s_i p:integer l:"Maximum Flow P.S.I." t:dataTypeName=number

entity e:ijru-c88e l:"Hose Nozzle And Sprayer Survey" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/ijru-c88e

property e:ijru-c88e t:meta.view v:id=ijru-c88e v:category=Environment v:attributionLink=http://www.nyc.gov/html/dep/html/ways_to_save_water/nozzles_wide.shtm v:averageRating=0 v:name="Hose Nozzle And Sprayer Survey" v:attribution="Department of Environmental Protection (DEP)"

property e:ijru-c88e t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ijru-c88e t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| :updated_at | manufacturer | model                                    | cost | minimum_flow_rate_gpm | minimum_flow_p_s_i | maximum_flow_rate_gpm | maximum_flow_p_s_i | spray_patterns_available   | 
| =========== | ============ | ======================================== | ==== | ===================== | ================== | ===================== | ================== | ========================== | 
| 1359700158  | Nelson       | E-Z Squeeze                              | 7.96 | 1.00                  | 52                 | 3.25                  | 52                 | Adjustable Flow Control    | 
| 1359700158  | Nelson       | Metal Sprayer                            | 5.97 | 0.40                  | 52                 | 5.00                  | 52                 | Four  Patterns             | 
| 1359700158  | Nelson       | Plastic - Flow Control Pistol Nozzle     | 5.99 | 1.50                  | 52                 | 3.50                  | 52                 | Adjustable Spray Pattern   | 
| 1359700158  | Niagara      | Plastic Spray Nozzle                     | 6.00 | 0.28                  | 52                 | 3.00                  | 52                 | Six  settings              | 
| 1359700158  | Orbit        | Metal - 7 Pattern Turret  Pistol Nozzle  | 6.97 | 0.18                  | 52                 | 4.50                  | 52                 | Seven Patterns             | 
| 1359700158  | Orbit        | Pistol Grip Metal                        | 3.29 | 0.40                  | 52                 | 5.00                  | 52                 | Fine Mist to Heavy Stream  | 
| 1359700158  | Orbit        | Zinc -Sprayer w/ Grip                    | 4.97 | 1.00                  | 52                 | 5.00                  | 52                 | Fine Mist to Heavy Stream  | 
| 1359700158  | Rain Bird    | Set & Forget                             | 5.99 | 1.00                  | 52                 | 4.00                  | 52                 | Three Patterns             | 
```