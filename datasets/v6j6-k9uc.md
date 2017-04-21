# Derelict Vehicles Dispositions - Rentals

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/derelict-vehicles-dispositions-rentals) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/v6j6-k9uc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/v6j6-k9uc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/v6j6-k9uc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | v6j6-k9uc |
| Name | Derelict Vehicles Dispositions - Rentals |
| Attribution | Department of Sanitation (DSNY) |
| Category | City Government |
| Created | 2015-05-22T20:18:45Z |
| Publication Date | 2017-04-08T20:01:33Z |

## Description

Data for removing derelict vehicle operations from city streets, Gives disposition (rentals) of derelict vehicles reported to DSNY from 311.

https://data.cityofnewyork.us/City-Government/Derelict-Vehicle-Dispositions-Tow/vr8p-8shw
https://data.cityofnewyork.us/City-Government/Derelict-Vehicle-Dispositions-Vehicles/bjuu-44hx
https://data.cityofnewyork.us/City-Government/Derelict-Vehicles-Dispositions-Complaints/pq5i-thsu

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | numeric metric | dvr_load_timestmp   | DVR_LOAD_TIMESTMP   | number    | number      |
| Yes      | series tag     | dvr_fill_1          | DVR_FILL_1          | text      | text        |
| Yes      | series tag     | dvr_fill_2          | DVR_FILL_2          | text      | text        |
| Yes      | series tag     | dvr_delete_indic    | DVR_DELETE_INDIC    | text      | text        |
| Yes      | time           | dvr_delete_timestmp | DVR_DELETE_TIMESTMP | number    | number      |
```

## Time Field

```ls
Value = dvr_delete_timestmp
Format & Zone = yyyyMMddHHmmss
```

## Data Commands

```ls
series e:v6j6-k9uc d:2017-04-08T19:54:23.000Z m:dvr_load_timestmp=441823

series e:v6j6-k9uc d:2011-03-26T14:59:45.000Z t:dvr_delete_indic=Y m:dvr_load_timestmp=441824

series e:v6j6-k9uc d:2017-04-08T19:54:23.000Z m:dvr_load_timestmp=441825
```

## Meta Commands

```ls
metric m:dvr_load_timestmp p:integer l:DVR_LOAD_TIMESTMP t:dataTypeName=number

entity e:v6j6-k9uc l:"Derelict Vehicles Dispositions - Rentals" t:attribution="Department of Sanitation (DSNY)" t:url=https://data.cityofnewyork.us/api/views/v6j6-k9uc

property e:v6j6-k9uc t:meta.view v:id=v6j6-k9uc v:category="City Government" v:averageRating=0 v:name="Derelict Vehicles Dispositions - Rentals" v:attribution="Department of Sanitation (DSNY)"

property e:v6j6-k9uc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:v6j6-k9uc t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| dvr_load_timestmp | dvr_fill_1 | dvr_fill_2 | dvr_delete_indic | dvr_delete_timestmp | 
| ================= | ========== | ========== | ================ | =================== | 
| 441823            |            |            |                  |                     | 
| 441824            |            |            | Y                | 20110326145945      | 
| 441825            |            |            |                  |                     | 
| 441826            |            |            | Y                | 20101030150021      | 
| 441827            |            |            | Y                | 20101016150024      | 
| 441828            |            |            | Y                | 20100731145941      | 
| 441829            |            |            | Y                | 20100731145941      | 
| 441830            |            |            | Y                | 20100717145939      | 
| 441831            |            |            | Y                | 20101016150014      | 
| 441832            |            |            | Y                | 20100731145941      | 
```