# FY17 PMMR Spending and Budget Information by Units of Appropriation

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy17-pmmr-spending-and-budget-information-by-units-of-appropriation) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jjvq-4t2v) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jjvq-4t2v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jjvq-4t2v/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jjvq-4t2v |
| Name | FY17 PMMR Spending and Budget Information by Units of Appropriation |
| Attribution | Mayor?s Office of Operations (OPS) |
| Category | City Government |
| Tags | fiscal 2017 preliminary mayor?s management report, pmmr additional tables, pmmr spending and budget information by units of appropriation, appropriation, units of appropriation, budget, adopted bu... |
| Created | 2017-02-06T22:42:51Z |
| Publication Date | 2017-02-06T22:47:12Z |

## Description

NYC agency spending and budget information by units of appropriation data from the Preliminary Mayor's Management Report (PMMR)

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
| Yes      | numeric metric | fy_16_exp     | FY 16 Exp     | number    | number      |
| Yes      | numeric metric | fy_17_adopted | FY 17 Adopted | number    | number      |
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
series e:jjvq-4t2v d:2017-02-06T22:42:54.000Z t:agy_name="BOARD OF ELECTIONS" t:agy=003 t:ps_otps_ind="Personal Services" t:ua_name="PERSONAL SERVICES" m:fy_17_adopted=52355676 m:fy_16_exp=54045441

series e:jjvq-4t2v d:2017-02-06T22:42:54.000Z t:agy_name="BOARD OF ELECTIONS" t:agy=003 t:ps_otps_ind="Other Than Personal Services" t:ua_name="OTHER THAN PERSONAL SERVICES" m:fy_17_adopted=71390634 m:fy_16_exp=62626677

series e:jjvq-4t2v d:2017-02-06T22:42:54.000Z t:agy_name="DEPARTMENT OF EMERGENCY MANAGEMENT" t:agy=017 t:ps_otps_ind="Personal Services" t:ua_name="PERSONAL SERVICES" m:fy_17_adopted=18282070 m:fy_16_exp=13919156
```

## Meta Commands

```ls
metric m:fy_16_exp p:long l:"FY 16 Exp" d:"Expenditures in dollars as reported in the City?s Fiscal 2016 Comprehensive Annual Financial Report; figures reflect all funds" t:dataTypeName=number

metric m:fy_17_adopted p:long l:"FY 17 Adopted" d:"Budgeted amounts in dollars for Fiscal 2017 as reported in the Fiscal 2017 adopted budget; figures reflect all funds" t:dataTypeName=number

entity e:jjvq-4t2v l:"FY17 PMMR Spending and Budget Information by Units of Appropriation" t:attribution="Mayor?s Office of Operations (OPS)" t:url=https://data.cityofnewyork.us/api/views/jjvq-4t2v

property e:jjvq-4t2v t:meta.view v:id=jjvq-4t2v v:category="City Government" v:averageRating=0 v:name="FY17 PMMR Spending and Budget Information by Units of Appropriation" v:attribution="Mayor?s Office of Operations (OPS)"

property e:jjvq-4t2v t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jjvq-4t2v t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agy | agy_name                           | ua  | ua_name                      | ps_otps_ind                  | fy_16_exp | fy_17_adopted | 
| =========== | === | ================================== | === | ============================ | ============================ | ========= | ============= | 
| 1486420974  | 003 | BOARD OF ELECTIONS                 | 001 | PERSONAL SERVICES            | Personal Services            | 54045441  | 52355676      | 
| 1486420974  | 003 | BOARD OF ELECTIONS                 | 002 | OTHER THAN PERSONAL SERVICES | Other Than Personal Services | 62626677  | 71390634      | 
| 1486420974  | 017 | DEPARTMENT OF EMERGENCY MANAGEMENT | 001 | PERSONAL SERVICES            | Personal Services            | 13919156  | 18282070      | 
| 1486420974  | 017 | DEPARTMENT OF EMERGENCY MANAGEMENT | 002 | OTHER THAN PERSONAL SERVICES | Other Than Personal Services | 21751991  | 41371688      | 
| 1486420974  | 025 | LAW DEPARTMENT                     | 001 | PERSONAL SERVICES            | Personal Services            | 118777294 | 146027908     | 
| 1486420974  | 025 | LAW DEPARTMENT                     | 002 | OTHER THAN PERSONAL SERVICES | Other Than Personal Services | 75573738  | 65484503      | 
| 1486420974  | 030 | DEPARTMENT OF CITY PLANNING        | 001 | PERSONAL SERVICES            | Personal Services            | 20447693  | 25694489      | 
| 1486420974  | 030 | DEPARTMENT OF CITY PLANNING        | 003 | GEOGRAPHIC SYSTEMS           | Personal Services            | 2126734   | 2278931       | 
| 1486420974  | 030 | DEPARTMENT OF CITY PLANNING        | 002 | OTHER THAN PERSONAL SERVICES | Other Than Personal Services | 8378980   | 18000272      | 
| 1486420974  | 030 | DEPARTMENT OF CITY PLANNING        | 004 | GEOGRAPHIC SYSTEMS           | Other Than Personal Services | 277570    | 297688        | 
```