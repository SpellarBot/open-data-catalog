# Assignment of Officers against whom Allegations were Substantiated

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/assignment-of-officers-against-whom-allegations-were-substantiated-6a9a6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rbrz-iagc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rbrz-iagc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rbrz-iagc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rbrz-iagc |
| Name | Assignment of Officers against whom Allegations were Substantiated |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | City Government |
| Tags | ccrb, assignment, officer, substantiated, allegations |
| Created | 2013-02-25T21:25:06Z |
| Publication Date | 2013-06-21T20:06:53Z |

## Description

This table represents the assignment of officers against whom allegations were substantiated

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | time           | year                   | Year                   | number    | text        |
| Yes      | numeric metric | patrol_services_bureau | Patrol Services Bureau | number    | text        |
| Yes      | numeric metric | other_bureaus          | Other Bureaus          | number    | text        |
| Yes      | numeric metric | other_commands         | Other Commands         | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rbrz-iagc d:2009-01-01T00:00:00.000Z m:patrol_services_bureau=209 m:other_bureaus=64 m:other_commands=278

series e:rbrz-iagc d:2010-01-01T00:00:00.000Z m:patrol_services_bureau=264 m:other_bureaus=110 m:other_commands=376

series e:rbrz-iagc d:2011-01-01T00:00:00.000Z m:patrol_services_bureau=164 m:other_bureaus=53 m:other_commands=213
```

## Meta Commands

```ls
metric m:patrol_services_bureau p:integer l:"Patrol Services Bureau" t:dataTypeName=number

metric m:other_bureaus p:integer l:"Other Bureaus" t:dataTypeName=number

metric m:other_commands p:integer l:"Other Commands" t:dataTypeName=number

entity e:rbrz-iagc l:"Assignment of Officers against whom Allegations were Substantiated" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/rbrz-iagc

property e:rbrz-iagc t:meta.view v:id=rbrz-iagc v:category="City Government" v:attributionLink=http://www.nyc.gov/html/ccrb/pdf/ccrbappendices2011.pdf v:averageRating=0 v:name="Assignment of Officers against whom Allegations were Substantiated" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:rbrz-iagc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rbrz-iagc t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| year | patrol_services_bureau | other_bureaus | other_commands | 
| ==== | ====================== | ============= | ============== | 
| 2009 | 209                    | 64            | 278            | 
| 2010 | 264                    | 110           | 376            | 
| 2011 | 164                    | 53            | 213            | 
```