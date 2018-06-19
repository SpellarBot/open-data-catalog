# CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Transit Bureau 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-assignment-of-officers-against-whom-allegations-were-substantiated-transit-bureau-20--a3fd6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rv3z-jq34) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rv3z-jq34/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rv3z-jq34/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rv3z-jq34 |
| Name | CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Transit Bureau 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-13T20:53:38Z |
| Publication Date | 2011-09-13T20:53:38Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009 Update Schedule: Annually

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | series tag     | transit_bureau | Transit Bureau | text      | text        |
| Yes      | numeric metric | 2005           | 2005           | percent   | percent     |
| Yes      | numeric metric | 2006           | 2006           | percent   | percent     |
| Yes      | numeric metric | 2007           | 2007           | percent   | percent     |
| Yes      | numeric metric | 2008           | 2008           | percent   | percent     |
| Yes      | numeric metric | 2009           | 2009           | percent   | percent     |
| Yes      | numeric metric | total          | Total          | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rv3z-jq34 d:2005-01-01T00:00:00.000Z t:transit_bureau="Transit Bureau Headquarters" m:2008=1 m:total=3 m:2009=2 m:2006=0 m:2007=0 m:2005=0

series e:rv3z-jq34 d:2005-01-01T00:00:00.000Z t:transit_bureau="TB Liaison" m:2008=0 m:total=0 m:2009=0 m:2006=0 m:2007=0 m:2005=0

series e:rv3z-jq34 d:2005-01-01T00:00:00.000Z t:transit_bureau="TB Inspections" m:2008=0 m:total=0 m:2009=0 m:2006=0 m:2007=0 m:2005=0
```

## Meta Commands

```ls
metric m:2005 p:double l:2005 t:dataTypeName=percent

metric m:2006 p:double l:2006 t:dataTypeName=percent

metric m:2007 p:double l:2007 t:dataTypeName=percent

metric m:2008 p:double l:2008 t:dataTypeName=percent

metric m:2009 p:double l:2009 t:dataTypeName=percent

metric m:total p:double l:Total t:dataTypeName=percent

entity e:rv3z-jq34 l:"CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Transit Bureau 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/rv3z-jq34

property e:rv3z-jq34 t:meta.view v:id=rv3z-jq34 v:category="Public Safety" v:averageRating=0 v:name="CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Transit Bureau 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:rv3z-jq34 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rv3z-jq34 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| transit_bureau              | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| =========================== | ==== | ==== | ==== | ==== | ==== | ===== | 
| Transit Bureau Headquarters | 0    | 0    | 0    | 1    | 2    | 3     | 
| TB Liaison                  | 0    | 0    | 0    | 0    | 0    | 0     | 
| TB Inspections              | 0    | 0    | 0    | 0    | 0    | 0     | 
| TB Special Investigations   | 0    | 0    | 0    | 0    | 0    | 0     | 
| TB Crime Analysis           | 0    | 0    | 0    | 0    | 0    | 0     | 
| TB Operations               | 0    | 0    | 0    | 0    | 0    | 0     | 
| TB Manhattan                | 0    | 0    | 0    | 0    | 0    | 0     | 
| TB Bronx                    | 0    | 0    | 0    | 0    | 0    | 0     | 
| TB Queens                   | 0    | 0    | 0    | 0    | 0    | 0     | 
| TB Brooklyn                 | 0    | 0    | 0    | 0    | 0    | 0     | 
```