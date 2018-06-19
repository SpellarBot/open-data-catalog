# CCR Annual Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccr-annual-report) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/vc9y-jf25) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/vc9y-jf25/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/vc9y-jf25/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | vc9y-jf25 |
| Name | CCR Annual Report |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Created | 2016-01-05T18:55:08Z |
| Publication Date | 2016-04-08T20:32:29Z |

## Description

The data tables published as part of the Annual NYC Drinking Water Supply and Quality Report.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                               | Data Type | Render Type |
| ======== | ============== | ================================ | ================================== | ========= | =========== |
| Yes      | time           | year                             | YEAR                               | number    | text        |
| Yes      | series tag     | parameters                       | PARAMETERS                         | text      | text        |
| Yes      | series tag     | nysdoh_mcl_highest_level_allowed | NYSDOH MCL (Highest Level Allowed) | text      | text        |
| Yes      | numeric metric | epa_mclg_ideal_goal              | EPA MCLG (Ideal Goal)              | number    | number      |
| Yes      | numeric metric | samples                          | # SAMPLES                          | number    | number      |
| Yes      | series tag     | range                            | RANGE                              | text      | text        |
| Yes      | series tag     | average                          | AVERAGE                            | text      | text        |
| Yes      | series tag     | mcl_violation                    | MCL VIOLATION                      | text      | text        |
| Yes      | series tag     | sources_in_drinking_water        | SOURCES IN DRINKING WATER          | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vc9y-jf25 d:2014-01-01T00:00:00.000Z t:sources_in_drinking_water="Erosion of natural deposits" t:mcl_violation=No t:range="13.5 - 18.1" t:nysdoh_mcl_highest_level_allowed=- t:parameters="Alkalinity (mg/L CaCO3)" t:average=15.7 m:samples=272

series e:vc9y-jf25 d:2014-01-01T00:00:00.000Z t:sources_in_drinking_water="Erosion of natural deposits" t:mcl_violation=No t:range="11 - 144" t:nysdoh_mcl_highest_level_allowed="50 - 200 (1)" t:parameters="Aluminum (?g/L)" t:average=23 m:samples=275

series e:vc9y-jf25 d:2014-01-01T00:00:00.000Z t:sources_in_drinking_water="Erosion of natural deposits" t:mcl_violation=No t:range="0.013 - 0.028" t:nysdoh_mcl_highest_level_allowed=2 t:parameters="Barium (mg/L)" t:average=0.017 m:epa_mclg_ideal_goal=2 m:samples=275
```

## Meta Commands

```ls
metric m:epa_mclg_ideal_goal p:double l:"EPA MCLG (Ideal Goal)" t:dataTypeName=number

metric m:samples p:integer l:"# SAMPLES" t:dataTypeName=number

entity e:vc9y-jf25 l:"CCR Annual Report" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/vc9y-jf25

property e:vc9y-jf25 t:meta.view v:id=vc9y-jf25 v:category=Environment v:averageRating=0 v:name="CCR Annual Report" v:attribution="Department of Environmental Protection (DEP)"

property e:vc9y-jf25 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:vc9y-jf25 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| year | parameters                                           | nysdoh_mcl_highest_level_allowed | epa_mclg_ideal_goal | samples | range         | average  | mcl_violation | sources_in_drinking_water                                           | 
| ==== | ==================================================== | ================================ | =================== | ======= | ============= | ======== | ============= | =================================================================== | 
| 2014 | Alkalinity (mg/L CaCO3)                              | -                                |                     | 272     | 13.5 - 18.1   | 15.7     | No            | Erosion of natural deposits                                         | 
| 2014 | Aluminum (?g/L)                                      | 50 - 200 (1)                     |                     | 275     | 11 - 144      | 23       | No            | Erosion of natural deposits                                         | 
| 2014 | Barium (mg/L)                                        | 2                                | 2                   | 275     | 0.013 - 0.028 | 0.017    | No            | Erosion of natural deposits                                         | 
| 2014 | Calcium (mg/L)                                       | -                                |                     | 272     | 5.2 - 6.9     | 5.9      | No            | Erosion of natural deposits                                         | 
| 2014 | Chlorate (mg/L)                                      | - (2)                            |                     | 18      | ND - 0.039    | 0.032    | No            | By-product of drinking water chlorination using sodium hypochlorite | 
| 2014 | Chloride (mg/L)                                      | 250                              |                     | 272     | 9 - 14        | 11       | No            | Naturally occurring; road salt                                      | 
| 2014 | Chlorine Residual, Free (mg/L)                       | 4 (3)                            |                     | 15023   | 0.00 - 1.51   | 0.63 (3) | No            | Water additive for disinfection                                     | 
| 2014 | Chromium (?g/L)                                      | 100                              |                     | 290     | ND - 0.31     | ND       | No            | Erosion of natural deposits                                         | 
| 2014 | Chromium VI (?g/L)                                   | - (2)                            |                     | 18      | 0.033 - 0.054 | 0.041    | No            | Erosion of natural deposits                                         | 
| 2014 | Color - distribution system (color units - apparent) | -                                |                     | 13929   | 3 - 40        | 6        | No            | Presence of iron, manganese, and organics in water                  | 
```