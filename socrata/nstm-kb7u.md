# 60 Month Converted to Safety Net (SN) recipients

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/60-month-converted-to-safety-net-sn-recipients-1e4f4) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/nstm-kb7u) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/nstm-kb7u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/nstm-kb7u/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | nstm-kb7u |
| Name | 60 Month Converted to Safety Net (SN) recipients |
| Attribution | Human Resources Administration (HRA) |
| Category | Social Services |
| Tags | 60 month converted to safety net (sn) recipients, hra, trend, human resource |
| Created | 2013-05-20T21:45:01Z |
| Publication Date | 2016-11-04T14:06:34Z |

## Description

Trend chart showing 60 Month Converted to Safety Net (SN) recipients

## Columns

```ls
| Included | Schema Type    | Field Name  | Name                                        | Data Type | Render Type |
| ======== | ============== | =========== | =========================================== | ========= | =========== |
| No       | time           | :updated_at | updated_at                                  | meta_data | meta_data   |
| Yes      | series tag     | month       | Month                                       | text      | text        |
| Yes      | numeric metric | recipients  | 60-Month Converted to Safety Net Recipients | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nstm-kb7u d:2016-11-04T14:06:15.000Z t:month=Jan-96 m:recipients=0

series e:nstm-kb7u d:2016-11-04T14:06:15.000Z t:month=Feb-96 m:recipients=0

series e:nstm-kb7u d:2016-11-04T14:06:15.000Z t:month=Mar-96 m:recipients=0
```

## Meta Commands

```ls
metric m:recipients p:integer l:"60-Month Converted to Safety Net Recipients" t:dataTypeName=number

entity e:nstm-kb7u l:"60 Month Converted to Safety Net (SN) recipients" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/nstm-kb7u

property e:nstm-kb7u t:meta.view v:id=nstm-kb7u v:category="Social Services" v:averageRating=0 v:name="60 Month Converted to Safety Net (SN) recipients" v:attribution="Human Resources Administration (HRA)"

property e:nstm-kb7u t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:nstm-kb7u t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | month  | recipients | 
| =========== | ====== | ========== | 
| 1478268375  | Jan-96 | 0          | 
| 1478268375  | Feb-96 | 0          | 
| 1478268375  | Mar-96 | 0          | 
| 1478268375  | Apr-96 | 0          | 
| 1478268375  | May-96 | 0          | 
| 1478268375  | Jun-96 | 0          | 
| 1478268375  | Jul-96 | 0          | 
| 1478268375  | Aug-96 | 0          | 
| 1478268375  | Sep-96 | 0          | 
| 1478268375  | Oct-96 | 0          | 
```