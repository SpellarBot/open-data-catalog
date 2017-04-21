# FY16 MMR Spending and Budget Information by Units of Appropriation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy16-mmr-spending-and-budget-information-by-units-of-appropriation-data-for-opendata) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/gepv-dxc2) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/gepv-dxc2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/gepv-dxc2/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | gepv-dxc2 |
| Name | FY16 MMR Spending and Budget Information by Units of Appropriation |
| Attribution | Mayor?s Office of Operations (OPS) |
| Category | City Government |
| Tags | fiscal 2016 mayor?s management report, mmr additional tables, mmr spending and budget information by units of appropriation, appropriation, units of appropriation, budget, adopted budget, cafr, co... |
| Created | 2016-09-26T13:40:08Z |
| Publication Date | 2016-09-27T15:10:41Z |

## Description

NYC agency spending and budget information by units of appropriation data from the Mayor's Management Report (MMR).

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | agy           | Agy           | text      | text        |
| Yes      | series tag     | agy_name      | Agy_Name      | text      | text        |
| No       |                | ua            | UA            | text      | text        |
| Yes      | series tag     | ua_name       | UA_Name       | text      | text        |
| Yes      | series tag     | ps_otps_ind   | PS_OTPS_Ind   | text      | text        |
| Yes      | numeric metric | fy_15_exp     | FY_15_Exp     | number    | number      |
| Yes      | numeric metric | fy_16_adopted | FY_16_Adopted | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = ua
```

## Data Commands

```ls
series e:gepv-dxc2 d:2016-09-27T15:08:57.000Z t:agy_name="BOARD OF ELECTIONS" t:agy=003 t:ps_otps_ind="Personal Services" t:ua_name="PERSONAL SERVICES" m:fy_16_adopted=61723539 m:fy_15_exp=51391433

series e:gepv-dxc2 d:2016-09-27T15:08:57.000Z t:agy_name="BOARD OF ELECTIONS" t:agy=003 t:ps_otps_ind="Other Than Personal Services" t:ua_name="OTHER THAN PERSONAL SERVICES" m:fy_16_adopted=78528690 m:fy_15_exp=55363698

series e:gepv-dxc2 d:2016-09-27T15:08:57.000Z t:agy_name="DEPARTMENT OF EMERGENCY MANAGEMENT" t:agy=017 t:ps_otps_ind="Personal Services" t:ua_name="PERSONAL SERVICES" m:fy_16_adopted=6246590 m:fy_15_exp=11601381
```

## Meta Commands

```ls
metric m:fy_15_exp p:long l:FY_15_Exp t:dataTypeName=number

metric m:fy_16_adopted p:long l:FY_16_Adopted t:dataTypeName=number

entity e:gepv-dxc2 l:"FY16 MMR Spending and Budget Information by Units of Appropriation" t:attribution="Mayor?s Office of Operations (OPS)" t:url=https://data.cityofnewyork.us/api/views/gepv-dxc2

property e:gepv-dxc2 t:meta.view v:id=gepv-dxc2 v:category="City Government" v:averageRating=0 v:name="FY16 MMR Spending and Budget Information by Units of Appropriation" v:attribution="Mayor?s Office of Operations (OPS)"

property e:gepv-dxc2 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:gepv-dxc2 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agy | agy_name                           | ua  | ua_name                      | ps_otps_ind                  | fy_15_exp | fy_16_adopted | 
| =========== | === | ================================== | === | ============================ | ============================ | ========= | ============= | 
| 1474988937  | 003 | BOARD OF ELECTIONS                 | 001 | PERSONAL SERVICES            | Personal Services            | 51391433  | 61723539      | 
| 1474988937  | 003 | BOARD OF ELECTIONS                 | 002 | OTHER THAN PERSONAL SERVICES | Other Than Personal Services | 55363698  | 78528690      | 
| 1474988937  | 017 | DEPARTMENT OF EMERGENCY MANAGEMENT | 001 | PERSONAL SERVICES            | Personal Services            | 11601381  | 6246590       | 
| 1474988937  | 017 | DEPARTMENT OF EMERGENCY MANAGEMENT | 002 | OTHER THAN PERSONAL SERVICES | Other Than Personal Services | 23436956  | 9780548       | 
| 1474988937  | 025 | LAW DEPARTMENT                     | 001 | PERSONAL SERVICES            | Personal Services            | 111055572 | 125701262     | 
| 1474988937  | 025 | LAW DEPARTMENT                     | 002 | OTHER THAN PERSONAL SERVICES | Other Than Personal Services | 64534069  | 60879415      | 
| 1474988937  | 030 | DEPARTMENT OF CITY PLANNING        | 001 | PERSONAL SERVICES            | Personal Services            | 19223316  | 22966676      | 
| 1474988937  | 030 | DEPARTMENT OF CITY PLANNING        | 003 | GEOGRAPHIC SYSTEMS           | Personal Services            | 1956106   | 2229653       | 
| 1474988937  | 030 | DEPARTMENT OF CITY PLANNING        | 002 | OTHER THAN PERSONAL SERVICES | Other Than Personal Services | 3255798   | 12617720      | 
| 1474988937  | 030 | DEPARTMENT OF CITY PLANNING        | 004 | GEOGRAPHIC SYSTEMS           | Other Than Personal Services | 282241    | 297688        | 
```