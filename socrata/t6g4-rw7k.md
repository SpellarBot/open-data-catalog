# Rate at which the CCRB made findings on the merits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rate-at-which-the-ccrb-made-findings-on-the-merits-799d7) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/t6g4-rw7k) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/t6g4-rw7k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/t6g4-rw7k/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | t6g4-rw7k |
| Name | Rate at which the CCRB made findings on the merits |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | City Government |
| Tags | ccrb, merits, allegations |
| Created | 2013-02-25T21:46:54Z |
| Publication Date | 2013-06-21T20:07:05Z |

## Description

This table represents the rate at which CCRB made findings on the merits

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | time           | year                      | Year                      | number    | text        |
| Yes      | numeric metric | findings_on_the_merits    | Findings on the Merits    | number    | text        |
| Yes      | numeric metric | no_findings_on_the_merits | No Findings on the Merits | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:t6g4-rw7k d:2009-01-01T00:00:00.000Z m:no_findings_on_the_merits=4786 m:findings_on_the_merits=5356

series e:t6g4-rw7k d:2010-01-01T00:00:00.000Z m:no_findings_on_the_merits=4245 m:findings_on_the_merits=4643

series e:t6g4-rw7k d:2011-01-01T00:00:00.000Z m:no_findings_on_the_merits=3549 m:findings_on_the_merits=3287
```

## Meta Commands

```ls
metric m:findings_on_the_merits p:integer l:"Findings on the Merits" t:dataTypeName=number

metric m:no_findings_on_the_merits p:integer l:"No Findings on the Merits" t:dataTypeName=number

entity e:t6g4-rw7k l:"Rate at which the CCRB made findings on the merits" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/t6g4-rw7k

property e:t6g4-rw7k t:meta.view v:id=t6g4-rw7k v:category="City Government" v:attributionLink=http://www.nyc.gov/html/ccrb/pdf/ccrbappendices2011.pdf v:averageRating=0 v:name="Rate at which the CCRB made findings on the merits" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:t6g4-rw7k t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:t6g4-rw7k t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| year | findings_on_the_merits | no_findings_on_the_merits | 
| ==== | ====================== | ========================= | 
| 2009 | 5356                   | 4786                      | 
| 2010 | 4643                   | 4245                      | 
| 2011 | 3287                   | 3549                      | 
```