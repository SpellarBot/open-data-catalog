# CCRB: Average Days for the CCRB to Close Cases Measured from Date of Report 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-average-days-for-the-ccrb-to-close-cases-measured-from-date-of-report-2005-2009-8994e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rgqc-ddc4) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rgqc-ddc4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rgqc-ddc4/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rgqc-ddc4 |
| Name | CCRB: Average Days for the CCRB to Close Cases Measured from Date of Report 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-15T18:58:52Z |
| Publication Date | 2011-09-15T18:58:52Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009. Update Frequency: Annually

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | case_type         | Case Type         | text      | text        |
| Yes      | numeric metric | 2005              | 2005              | number    | number      |
| Yes      | numeric metric | 2006              | 2006              | number    | number      |
| Yes      | numeric metric | 2007              | 2007              | number    | number      |
| Yes      | numeric metric | 2008              | 2008              | number    | number      |
| Yes      | numeric metric | 2009              | 2009              | number    | number      |
| Yes      | numeric metric | five_year_average | Five-year Average | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rgqc-ddc4 d:2005-01-01T00:00:00.000Z t:case_type="Full Investigations" m:2008=316 m:2009=349 m:five_year_average=308 m:2006=281 m:2007=303 m:2005=294

series e:rgqc-ddc4 d:2005-01-01T00:00:00.000Z t:case_type="Truncated Investigations" m:2008=98 m:2009=113 m:five_year_average=110 m:2006=106 m:2007=112 m:2005=121

series e:rgqc-ddc4 d:2005-01-01T00:00:00.000Z t:case_type=Mediations m:2008=167 m:2009=162 m:five_year_average=163 m:2006=155 m:2007=148 m:2005=185
```

## Meta Commands

```ls
metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:five_year_average p:integer l:"Five-year Average" t:dataTypeName=number

entity e:rgqc-ddc4 l:"CCRB:  Average Days for the CCRB to Close Cases Measured from Date of Report 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/rgqc-ddc4

property e:rgqc-ddc4 t:meta.view v:id=rgqc-ddc4 v:category="Public Safety" v:averageRating=0 v:name="CCRB:  Average Days for the CCRB to Close Cases Measured from Date of Report 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:rgqc-ddc4 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rgqc-ddc4 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| case_type                | 2005 | 2006 | 2007 | 2008 | 2009 | five_year_average | 
| ======================== | ==== | ==== | ==== | ==== | ==== | ================= | 
| Full Investigations      | 294  | 281  | 303  | 316  | 349  | 308               | 
| Truncated Investigations | 121  | 106  | 112  | 98   | 113  | 110               | 
| Mediations               | 185  | 155  | 148  | 167  | 162  | 163               | 
| Mediation Attempted      | 254  | 198  | 200  | 228  | 227  | 219               | 
| All Cases                | 195  | 172  | 181  | 170  | 193  | 182               | 
```