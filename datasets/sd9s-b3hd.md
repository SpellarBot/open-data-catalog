# Average days for the CCRB to close case

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/average-days-for-the-ccrb-to-close-case-9f584) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/sd9s-b3hd) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/sd9s-b3hd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/sd9s-b3hd/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | sd9s-b3hd |
| Name | Average days for the CCRB to close case |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | City Government |
| Tags | ccrb, average, days, investigations |
| Created | 2013-02-25T21:42:13Z |
| Publication Date | 2013-06-21T20:07:28Z |
| Rows Updated | 2013-06-21T20:07:25Z |

## Description

This table represents average days for the CCRB to close a case measured from the date of report

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | time           | year                     | Year                     | number    | text        |
| Yes      | numeric metric | full_investigations      | Full Investigations      | number    | text        |
| Yes      | numeric metric | truncated_investigations | Truncated Investigations | number    | text        |
| Yes      | numeric metric | mediations               | Mediations               | number    | text        |
| Yes      | numeric metric | mediation_attempted      | Mediation Attempted      | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:sd9s-b3hd d:2009-01-01T00:00:00.000Z m:truncated_investigations=113 m:mediations=162 m:full_investigations=349 m:mediation_attempted=227

series e:sd9s-b3hd d:2010-01-01T00:00:00.000Z m:truncated_investigations=96 m:mediations=177 m:full_investigations=299 m:mediation_attempted=264

series e:sd9s-b3hd d:2011-01-01T00:00:00.000Z m:truncated_investigations=97 m:mediations=178 m:full_investigations=284 m:mediation_attempted=267
```

## Meta Commands

```ls
metric m:full_investigations p:integer l:"Full Investigations" t:dataTypeName=number

metric m:truncated_investigations p:integer l:"Truncated Investigations" t:dataTypeName=number

metric m:mediations p:integer l:Mediations t:dataTypeName=number

metric m:mediation_attempted p:integer l:"Mediation Attempted" t:dataTypeName=number

entity e:sd9s-b3hd l:"Average days for the CCRB to close case" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/sd9s-b3hd

property e:sd9s-b3hd t:meta.view v:id=sd9s-b3hd v:category="City Government" v:attributionLink=http://www.nyc.gov/html/ccrb/pdf/ccrbappendices2011.pdf v:averageRating=0 v:name="Average days for the CCRB to close case" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:sd9s-b3hd t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:sd9s-b3hd t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```