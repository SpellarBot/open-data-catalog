# CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Special Operations Division 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-assignment-of-officers-against-whom-allegations-were-substantiated-special-operation--25e95) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/zcqs-4wtn) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/zcqs-4wtn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/zcqs-4wtn/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | zcqs-4wtn |
| Name | CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Special Operations Division 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-13T20:47:02Z |
| Publication Date | 2011-09-13T20:47:02Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | special_operations | Special Operations | text      | text        |
| Yes      | numeric metric | 2005               | 2005               | percent   | percent     |
| Yes      | numeric metric | 2006               | 2006               | percent   | percent     |
| Yes      | numeric metric | 2007               | 2007               | percent   | percent     |
| Yes      | numeric metric | 2008               | 2008               | percent   | percent     |
| Yes      | numeric metric | 2009               | 2009               | percent   | percent     |
| Yes      | numeric metric | total              | Total              | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:zcqs-4wtn d:2005-01-01T00:00:00.000Z t:special_operations="Emergency Service" m:2008=1 m:total=2 m:2009=0 m:2006=0 m:2007=1 m:2005=0

series e:zcqs-4wtn d:2005-01-01T00:00:00.000Z t:special_operations="Harbor Unit" m:2008=0 m:total=0 m:2009=0 m:2006=0 m:2007=0 m:2005=0

series e:zcqs-4wtn d:2005-01-01T00:00:00.000Z t:special_operations="Aviation Unit" m:2008=0 m:total=0 m:2009=0 m:2006=0 m:2007=0 m:2005=0
```

## Meta Commands

```ls
metric m:2005 p:double l:2005 t:dataTypeName=percent

metric m:2006 p:double l:2006 t:dataTypeName=percent

metric m:2007 p:double l:2007 t:dataTypeName=percent

metric m:2008 p:double l:2008 t:dataTypeName=percent

metric m:2009 p:double l:2009 t:dataTypeName=percent

metric m:total p:double l:Total t:dataTypeName=percent

entity e:zcqs-4wtn l:"CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Special Operations Division 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/zcqs-4wtn

property e:zcqs-4wtn t:meta.view v:id=zcqs-4wtn v:category="Public Safety" v:averageRating=0 v:name="CCRB: Assignment of Officers against Whom Allegations Were Substantiated - Special Operations Division 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:zcqs-4wtn t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:zcqs-4wtn t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| special_operations                                                          | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| =========================================================================== | ==== | ==== | ==== | ==== | ==== | ===== | 
| Emergency Service                                                           | 0    | 0    | 1    | 1    | 0    | 2     | 
| Harbor Unit                                                                 | 0    | 0    | 0    | 0    | 0    | 0     | 
| Aviation Unit                                                               | 0    | 0    | 0    | 0    | 0    | 0     | 
| Taxi Unit                                                                   | 0    | 0    | 0    | 0    | 0    | 0     | 
| Canine Unit                                                                 | 0    | 0    | 0    | 0    | 0    | 0     | 
| Mounted Unit                                                                | 0    | 0    | 0    | 0    | 0    | 0     | 
| Headquarters                                                                | 0    | 0    | 0    | 0    | 0    | 0     | 
| Special Operations Division Total                                           | 0    | 0    | 1    | 1    | 0    | 2     | 
| Percent of All Subject Officers Against Whom Allegations were Substantiated | 0.00 | 0.00 | 0.20 | 0.30 | 0.00 | 0.10  | 
```