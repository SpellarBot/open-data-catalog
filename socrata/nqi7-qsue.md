# License Statistical Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/license-statistical-report) |
| Metadata | [Link](https://data.ct.gov/api/views/nqi7-qsue) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/nqi7-qsue/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/nqi7-qsue/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | nqi7-qsue |
| Name | License Statistical Report |
| Attribution | Department of Motor Vehicles |
| Category | Transportation |
| Tags | dmv |
| Created | 2014-11-12T18:44:01Z |
| Publication Date | 2014-11-12T18:44:49Z |

## Description

Active ( Valid- Suspended)- Non- Expired Licenses as of Nov 2012, 2013, 2014

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | type_of_credentials | TYPE of CREDENTIALS | text      | text        |
| Yes      | numeric metric | nov_2012            | NOV-2012            | number    | number      |
| Yes      | numeric metric | nov_2013            | NOV-2013            | number    | number      |
| Yes      | numeric metric | nov_2014            | NOV-2014            | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nqi7-qsue d:2014-11-12T10:44:05.000Z t:type_of_credentials="Non Commercial DL" m:nov_2013=2461767 m:nov_2014=2460056 m:nov_2012=2458023

series e:nqi7-qsue d:2014-11-12T10:44:05.000Z t:type_of_credentials="Commercial DL" m:nov_2013=85787 m:nov_2014=85734 m:nov_2012=86423

series e:nqi7-qsue d:2014-11-12T10:44:05.000Z t:type_of_credentials="Non-Driver IDs" m:nov_2013=421096 m:nov_2014=428861 m:nov_2012=354309
```

## Meta Commands

```ls
metric m:nov_2012 p:integer l:NOV-2012 t:dataTypeName=number

metric m:nov_2013 p:integer l:NOV-2013 t:dataTypeName=number

metric m:nov_2014 p:integer l:NOV-2014 t:dataTypeName=number

entity e:nqi7-qsue l:"License Statistical Report" t:attribution="Department of Motor Vehicles" t:url=https://data.ct.gov/api/views/nqi7-qsue

property e:nqi7-qsue t:meta.view v:id=nqi7-qsue v:category=Transportation v:averageRating=0 v:name="License Statistical Report" v:attribution="Department of Motor Vehicles"

property e:nqi7-qsue t:meta.view.owner v:id=fd5k-6njr v:screenName=APatel v:displayName=APatel

property e:nqi7-qsue t:meta.view.tableauthor v:id=fd5k-6njr v:screenName=APatel v:roleName=editor v:displayName=APatel
```

## Top Records

```ls
| :updated_at | type_of_credentials | nov_2012 | nov_2013 | nov_2014 | 
| =========== | =================== | ======== | ======== | ======== | 
| 1415789045  | Non Commercial DL   | 2458023  | 2461767  | 2460056  | 
| 1415789045  | Commercial DL       | 86423    | 85787    | 85734    | 
| 1415789045  | Non-Driver IDs      | 354309   | 421096   | 428861   | 
| 1415789045  | Learner Permits     | 20217    | 21106    | 23392    | 
| 1415789045  | Motorcycle Permits  | 221      | 254      | 197      | 
```