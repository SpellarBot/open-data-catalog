# CCRB: Attribution of Complaints to Special Operations Division 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-attribution-of-complaints-to-special-operations-division-2005-2009-23aac) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rfu3-4gsz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rfu3-4gsz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rfu3-4gsz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rfu3-4gsz |
| Name | CCRB: Attribution of Complaints to Special Operations Division 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-14T19:52:48Z |
| Publication Date | 2011-09-14T19:52:48Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009. Update Schedule: Annually

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | special_operations | Special Operations | text      | text        |
| Yes      | numeric metric | 2005               | 2005               | number    | number      |
| Yes      | numeric metric | 2006               | 2006               | number    | number      |
| Yes      | numeric metric | 2007               | 2007               | number    | number      |
| Yes      | numeric metric | 2008               | 2008               | number    | number      |
| Yes      | numeric metric | 2009               | 2009               | number    | number      |
| Yes      | numeric metric | total              | Total              | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rfu3-4gsz d:2005-01-01T00:00:00.000Z t:special_operations="Emergency Service" m:2008=17 m:total=126 m:2009=14 m:2006=36 m:2007=32 m:2005=27

series e:rfu3-4gsz d:2005-01-01T00:00:00.000Z t:special_operations="Harbor Unit" m:2008=0 m:total=3 m:2009=0 m:2006=2 m:2007=0 m:2005=1

series e:rfu3-4gsz d:2005-01-01T00:00:00.000Z t:special_operations="Aviation Unit" m:2008=0 m:total=2 m:2009=0 m:2006=1 m:2007=1 m:2005=0
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:rfu3-4gsz l:"CCRB: Attribution of Complaints to Special Operations Division 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/rfu3-4gsz

property e:rfu3-4gsz t:meta.view v:id=rfu3-4gsz v:category="Public Safety" v:averageRating=0 v:name="CCRB: Attribution of Complaints to Special Operations Division 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:rfu3-4gsz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rfu3-4gsz t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| special_operations                | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| ================================= | ==== | ==== | ==== | ==== | ==== | ===== | 
| Emergency Service                 | 27   | 36   | 32   | 17   | 14   | 126   | 
| Harbor Unit                       | 1    | 2    | 0    | 0    | 0    | 3     | 
| Aviation Unit                     | 0    | 1    | 1    | 0    | 0    | 2     | 
| Taxi Unit                         | 1    | 0    | 0    | 0    | 0    | 1     | 
| Canine Unit                       | 2    | 2    | 2    | 1    | 0    | 7     | 
| Mounted Unit                      | 7    | 4    | 5    | 3    | 1    | 20    | 
| Headquarters                      | 1    | 0    | 0    | 0    | 0    | 1     | 
| Special Operations Division Total | 39   | 45   | 40   | 21   | 15   | 160   | 
```