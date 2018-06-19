# CCRB: Average Days for the CCRB to Close Substantiated Cases Measured from Date of Incident 2005 ? 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-average-days-for-the-ccrb-to-close-substantiated-cases-measured-from-date-of-inc-2005-66b78) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/7ub6-8ecn) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/7ub6-8ecn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/7ub6-8ecn/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 7ub6-8ecn |
| Name | CCRB: Average Days for the CCRB to Close Substantiated Cases Measured from Date of Incident 2005 ? 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-15T19:04:42Z |
| Publication Date | 2011-09-15T19:04:42Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009

## Columns

```ls
| Included | Schema Type    | Field Name                                             | Name                                                   | Data Type | Render Type |
| ======== | ============== | ====================================================== | ====================================================== | ========= | =========== |
| Yes      | series tag     | average_days_for_the_ccrb_to_close_substantiated_cases | Average Days for the CCRB to Close Substantiated Cases | text      | text        |
| Yes      | numeric metric | 2005                                                   | 2005                                                   | number    | number      |
| Yes      | numeric metric | 2006                                                   | 2006                                                   | number    | number      |
| Yes      | numeric metric | 2007                                                   | 2007                                                   | number    | number      |
| Yes      | numeric metric | 2008                                                   | 2008                                                   | number    | number      |
| Yes      | numeric metric | 2009                                                   | 2009                                                   | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7ub6-8ecn d:2005-01-01T00:00:00.000Z t:average_days_for_the_ccrb_to_close_substantiated_cases="Average Number of Days" m:2008=360 m:2009=401 m:2006=294 m:2007=311 m:2005=322
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

entity e:7ub6-8ecn l:"CCRB: Average Days for the CCRB to Close Substantiated Cases Measured from Date of Incident 2005 ? 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/7ub6-8ecn

property e:7ub6-8ecn t:meta.view v:id=7ub6-8ecn v:category="Public Safety" v:averageRating=0 v:name="CCRB: Average Days for the CCRB to Close Substantiated Cases Measured from Date of Incident 2005 ? 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:7ub6-8ecn t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:7ub6-8ecn t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| average_days_for_the_ccrb_to_close_substantiated_cases | 2005 | 2006 | 2007 | 2008 | 2009 | 
| ====================================================== | ==== | ==== | ==== | ==== | ==== | 
| Average Number of Days                                 | 322  | 294  | 311  | 360  | 401  | 
```