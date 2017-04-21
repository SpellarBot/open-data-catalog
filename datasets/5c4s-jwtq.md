# Total SNAP Recipients

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/odra-snap-trends-878d6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/5c4s-jwtq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/5c4s-jwtq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/5c4s-jwtq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 5c4s-jwtq |
| Name | Total SNAP Recipients |
| Attribution | Human Resources Administration (HRA) |
| Category | Social Services |
| Tags | odra snap trends |
| Created | 2013-05-21T12:03:09Z |
| Publication Date | 2016-11-04T14:10:24Z |

## Description

Monthly trend statistics on SNAP supplemental nutrition assistance program recipients.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| No       | time           | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag     | month                 | Month                 | text      | text        |
| Yes      | numeric metric | total_snap_recipients | Total SNAP Recipients | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:5c4s-jwtq d:2016-11-04T14:10:16.000Z t:month=Jan-95 m:total_snap_recipients=1456024

series e:5c4s-jwtq d:2016-11-04T14:10:16.000Z t:month=Feb-95 m:total_snap_recipients=1454815

series e:5c4s-jwtq d:2016-11-04T14:10:16.000Z t:month=Mar-95 m:total_snap_recipients=1458300
```

## Meta Commands

```ls
metric m:total_snap_recipients p:integer l:"Total SNAP Recipients" t:dataTypeName=number

entity e:5c4s-jwtq l:"Total SNAP Recipients" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/5c4s-jwtq

property e:5c4s-jwtq t:meta.view v:id=5c4s-jwtq v:category="Social Services" v:averageRating=0 v:name="Total SNAP Recipients" v:attribution="Human Resources Administration (HRA)"

property e:5c4s-jwtq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:5c4s-jwtq t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | month  | total_snap_recipients | 
| =========== | ====== | ===================== | 
| 1478268616  | Jan-95 | 1456024               | 
| 1478268616  | Feb-95 | 1454815               | 
| 1478268616  | Mar-95 | 1458300               | 
| 1478268616  | Apr-95 | 1459683               | 
| 1478268616  | May-95 | 1451929               | 
| 1478268616  | Jun-95 | 1442051               | 
| 1478268616  | Jul-95 | 1435025               | 
| 1478268616  | Aug-95 | 1425147               | 
| 1478268616  | Sep-95 | 1416455               | 
| 1478268616  | Oct-95 | 1405342               | 
```