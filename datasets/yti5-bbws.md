# Drought Regulation Penalty Schedule

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/drought-regulation-penalty-schedule-e28b6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yti5-bbws) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yti5-bbws/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yti5-bbws/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yti5-bbws |
| Name | Drought Regulation Penalty Schedule |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | dep, department of environmental protection, environment, drought, penalty, drought regulation penalty schedule, healthy living |
| Created | 2013-02-01T03:58:50Z |
| Publication Date | 2013-06-21T19:45:45Z |

## Description

Schedule of penalties for violating the Drought Regulations during the stages of a drought emergency.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                              | Data Type | Render Type |
| ======== | ============== | =============================== | ================================= | ========= | =========== |
| No       | time           | :updated_at                     | updated_at                        | meta_data | meta_data   |
| Yes      | series tag     | code                            | CODE                              | text      | text        |
| Yes      | series tag     | rcny                            | RCNY                              | text      | text        |
| Yes      | series tag     | section_subdivision_description | Section/Subdivision - DESCRIPTION | text      | text        |
| Yes      | numeric metric | penalty                         |  PENALTY                          | number    | number      |
| Yes      | numeric metric | default                         |  DEFAULT                          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:yti5-bbws d:2013-01-31T19:58:59.000Z t:rcny="AC 24-337" t:section_subdivision_description="WASTING OR NOT CONSERVING WATER FOR COMMERCIAL OR INDUSTRIAL USE; STAGE I" t:code=W01 m:default=1000 m:penalty=400

series e:yti5-bbws d:2013-01-31T19:58:59.000Z t:rcny="AC 24-337" t:section_subdivision_description="ILLEGAL WASTE OF WATER DURING DROUGHT; (RESIDENTIAL);  STAGE I" t:code=W02 m:default=1000 m:penalty=250

series e:yti5-bbws d:2013-01-31T19:58:59.000Z t:rcny="21-03 (a)" t:section_subdivision_description="ALLOWING LEAK OR WASTE OF WATER FROM FAUCETS, W.C.'S, ETC.;  STAGE I" t:code=W03 m:default=1000 m:penalty=250
```

## Meta Commands

```ls
metric m:penalty p:integer l:PENALTY t:dataTypeName=number

metric m:default p:integer l:DEFAULT t:dataTypeName=number

entity e:yti5-bbws l:"Drought Regulation Penalty Schedule" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/yti5-bbws

property e:yti5-bbws t:meta.view v:id=yti5-bbws v:category=Environment v:attributionLink=http://www.nyc.gov/html/dep/html/residents/droughtpenalty_wide.shtml v:averageRating=0 v:name="Drought Regulation Penalty Schedule" v:attribution="Department of Environmental Protection (DEP)"

property e:yti5-bbws t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yti5-bbws t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| :updated_at | code | rcny          | section_subdivision_description                                           | penalty | default | 
| =========== | ==== | ============= | ========================================================================= | ======= | ======= | 
| 1359662339  |  W01 | AC 24-337     | WASTING OR NOT CONSERVING WATER FOR COMMERCIAL OR INDUSTRIAL USE; STAGE I | 400     | 1000    | 
| 1359662339  |  W02 | AC 24-337     | ILLEGAL WASTE OF WATER DURING DROUGHT; (RESIDENTIAL);  STAGE I            | 250     | 1000    | 
| 1359662339  |  W03 | 21-03 (a)     | ALLOWING LEAK OR WASTE OF WATER FROM FAUCETS, W.C.'S, ETC.;  STAGE I      | 250     | 1000    | 
| 1359662339  |  W04 | 21-03 (b)     |  USING PUBLIC WATER TO WASH VEHICLES; STAGE I                             | 250     | 1000    | 
| 1359662339  |  W05 | 21-03 (c)     | USING WATER TO SPRAY OR WASH SIDEWALK, STREET;  STAGE I                   | 250     | 1000    | 
| 1359662339  |  W06 | 21-03 (d)     | USING ANY WATER FOR ORNAMENTAL PURPOSES; STAGE I                          | 250     | 1000    | 
| 1359662339  |  W07 | 21-03 (e)     | USING WATER FOR LAWNS, GOLF COURSE, PLANTS, TREES;  STAGE I               | 250     | 1000    | 
| 1359662339  |  W08 | 21-03 (e) (3) | FAILURE TO POST PROPER IRRIGATION SYSTEM SIGN; STAGE I                    | 100     | 1000    | 
| 1359662339  |  W09 | 21-03 (f)     | ILLEGAL USE OF FIRE HYDRANTS; STAGE I                                     | 750     | 1000    | 
| 1359662339  |  W10 |  21-03 (g)    | SERVING WATER WITHOUT REQUEST; STAGE I                                    | 250     | 1000    | 
```