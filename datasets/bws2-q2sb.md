# CCRB: Average Days for the CCRB to Close Substantiated Cases Measured from Date of Report 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-average-days-for-the-ccrb-to-close-substantiated-cases-measured-from-date-of-report-2-5aa1b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/bws2-q2sb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/bws2-q2sb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/bws2-q2sb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | bws2-q2sb |
| Name | CCRB: Average Days for the CCRB to Close Substantiated Cases Measured from Date of Report 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-15T19:09:33Z |
| Publication Date | 2011-09-15T19:09:33Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009 Update Schedule: Annually

## Columns

```ls
| Included | Schema Type    | Field Name                                                     | Name                                                           | Data Type | Render Type |
| ======== | ============== | ============================================================== | ============================================================== | ========= | =========== |
| No       |                | ccrb_to_close_substantiated_cases_measured_from_date_of_report | CCRB to Close Substantiated Cases Measured from Date of Report | text      | text        |
| Yes      | numeric metric | 2005                                                           | 2005                                                           | number    | number      |
| Yes      | numeric metric | 2006                                                           | 2006                                                           | number    | number      |
| Yes      | numeric metric | 2007                                                           | 2007                                                           | number    | number      |
| Yes      | numeric metric | 2008                                                           | 2008                                                           | number    | number      |
| Yes      | numeric metric | 2009                                                           | 2009                                                           | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = ccrb_to_close_substantiated_cases_measured_from_date_of_report
```

## Data Commands

```ls
series e:bws2-q2sb d:2005-01-01T00:00:00.000Z m:2008=350 m:2009=394 m:2006=285 m:2007=301 m:2005=314
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

entity e:bws2-q2sb l:"CCRB: Average Days for the CCRB to Close Substantiated Cases Measured from Date of Report 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/bws2-q2sb

property e:bws2-q2sb t:meta.view v:id=bws2-q2sb v:category="Public Safety" v:averageRating=0 v:name="CCRB: Average Days for the CCRB to Close Substantiated Cases Measured from Date of Report 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:bws2-q2sb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:bws2-q2sb t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| ccrb_to_close_substantiated_cases_measured_from_date_of_report | 2005 | 2006 | 2007 | 2008 | 2009 | 
| ============================================================== | ==== | ==== | ==== | ==== | ==== | 
| Average Number of Days                                         | 314  | 285  | 301  | 350  | 394  | 
```