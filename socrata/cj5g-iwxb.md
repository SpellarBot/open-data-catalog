# Race of Officers against whom Allegations were Substantiated

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/race-of-officers-against-whom-allegations-were-substantiated-37050) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/cj5g-iwxb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/cj5g-iwxb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/cj5g-iwxb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | cj5g-iwxb |
| Name | Race of Officers against whom Allegations were Substantiated |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | City Government |
| Tags | ccrb, officers, substantiated, race, allegation |
| Created | 2013-02-25T21:42:32Z |
| Publication Date | 2013-06-21T20:07:22Z |

## Description

This is the table representing the race of officers against whom allegations were substantiated

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type | Render Type |
| ======== | ============== | ========== | ======= | ========= | =========== |
| Yes      | time           | year       | Year    | number    | text        |
| Yes      | numeric metric | white      | White   | number    | text        |
| Yes      | numeric metric | black      | Black   | number    | text        |
| No       |                | latino     | Latino  | number    | text        |
| Yes      | numeric metric | asain      | Asain   | number    | text        |
| Yes      | numeric metric | other      | Other   | number    | text        |
| Yes      | numeric metric | unknown    | Unknown | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = latino
```

## Data Commands

```ls
series e:cj5g-iwxb d:2009-01-01T00:00:00.000Z m:other=1 m:white=118 m:unknown=1 m:asain=14 m:black=47

series e:cj5g-iwxb d:2010-01-01T00:00:00.000Z m:other=0 m:white=183 m:unknown=0 m:asain=11 m:black=62

series e:cj5g-iwxb d:2011-01-01T00:00:00.000Z m:other=0 m:white=114 m:unknown=0 m:asain=7 m:black=35
```

## Meta Commands

```ls
metric m:white p:integer l:White t:dataTypeName=number

metric m:black p:integer l:Black t:dataTypeName=number

metric m:asain p:integer l:Asain t:dataTypeName=number

metric m:other p:integer l:Other t:dataTypeName=number

metric m:unknown p:integer l:Unknown t:dataTypeName=number

entity e:cj5g-iwxb l:"Race of Officers against whom Allegations were Substantiated" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/cj5g-iwxb

property e:cj5g-iwxb t:meta.view v:id=cj5g-iwxb v:category="City Government" v:attributionLink=http://www.nyc.gov/html/ccrb/pdf/ccrbappendices2011.pdf v:averageRating=0 v:name="Race of Officers against whom Allegations were Substantiated" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:cj5g-iwxb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:cj5g-iwxb t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| year | white | black | latino | asain | other | unknown | 
| ==== | ===== | ===== | ====== | ===== | ===== | ======= | 
| 2009 | 118   | 47    | 96     | 14    | 1     | 1       | 
| 2010 | 183   | 62    | 119    | 11    | 0     | 0       | 
| 2011 | 114   | 35    | 57     | 7     | 0     | 0       | 
```