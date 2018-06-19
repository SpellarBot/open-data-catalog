# CCRB: Attribution of Complaints to Other Bureaus 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-attribution-of-complaints-to-other-bureaus-2005-2009-221d6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/bexe-qnej) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/bexe-qnej/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/bexe-qnej/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | bexe-qnej |
| Name | CCRB: Attribution of Complaints to Other Bureaus 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-13T21:02:05Z |
| Publication Date | 2011-09-13T21:02:05Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009. Update Frequency: Annually

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | other_bureaus | Other Bureaus | text      | text        |
| Yes      | numeric metric | 2005          | 2005          | number    | number      |
| Yes      | numeric metric | 2006          | 2006          | number    | number      |
| Yes      | numeric metric | 2007          | 2007          | number    | number      |
| Yes      | numeric metric | 2008          | 2008          | number    | number      |
| Yes      | numeric metric | 2009          | 2009          | number    | number      |
| Yes      | numeric metric | total         | Total         | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bexe-qnej d:2005-01-01T00:00:00.000Z t:other_bureaus="Internal Affairs" m:2008=5 m:total=24 m:2009=2 m:2006=3 m:2007=4 m:2005=10

series e:bexe-qnej d:2005-01-01T00:00:00.000Z t:other_bureaus="Court Division" m:2008=44 m:total=230 m:2009=53 m:2006=53 m:2007=36 m:2005=44

series e:bexe-qnej d:2005-01-01T00:00:00.000Z t:other_bureaus="Criminal Justice HQ" m:2008=0 m:total=3 m:2009=2 m:2006=1 m:2007=0 m:2005=0
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:bexe-qnej l:"CCRB: Attribution of Complaints to Other Bureaus 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/bexe-qnej

property e:bexe-qnej t:meta.view v:id=bexe-qnej v:category="Public Safety" v:averageRating=0 v:name="CCRB: Attribution of Complaints to Other Bureaus 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:bexe-qnej t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:bexe-qnej t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| other_bureaus           | 2005 | 2006 | 2007 | 2008 | 2009 | total | 
| ======================= | ==== | ==== | ==== | ==== | ==== | ===== | 
| Internal Affairs Bureau |      |      |      |      |      |       | 
| Internal Affairs        | 10   | 3    | 4    | 5    | 2    | 24    | 
| Criminal Justice Bureau |      |      |      |      |      |       | 
| Court Division          | 44   | 53   | 36   | 44   | 53   | 230   | 
| Criminal Justice HQ     | 0    | 1    | 0    | 0    | 2    | 3     | 
| Support Services Bureau |      |      |      |      |      |       | 
| Property Clerk          | 1    | 3    | 2    | 2    | 0    | 8     | 
| Fleet Services          | 0    | 2    | 0    | 0    | 0    | 2     | 
| Central Record Division | 1    | 0    | 1    | 0    | 0    | 2     | 
| Personnel Bureau        |      |      |      |      |      |       | 
```