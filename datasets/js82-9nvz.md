# Complaints per Uniformed Officer

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/complaints-per-uniformed-officer-c234e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/js82-9nvz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/js82-9nvz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/js82-9nvz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | js82-9nvz |
| Name | Complaints per Uniformed Officer |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | City Government |
| Tags | ccrb, command, rankings, complaints |
| Created | 2013-02-25T21:42:04Z |
| Publication Date | 2013-06-21T20:06:15Z |

## Description

This table represents complaints per uniformed officer

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | text        |
| Yes      | numeric metric | ranking                    | Ranking                    | number    | text        |
| Yes      | series tag     | precinct_command           | Precinct / Command         | text      | text        |
| Yes      | numeric metric | complaints_count           | Complaints Count           | number    | text        |
| Yes      | numeric metric | number_of_subject_officers | Number Of Subject Officers | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:js82-9nvz d:2009-01-01T00:00:00.000Z t:precinct_command="Patrol Borough Bronx" m:number_of_subject_officers=3095 m:ranking=1 m:complaints_count=772

series e:js82-9nvz d:2009-01-01T00:00:00.000Z t:precinct_command="Patrol Borough Brooklyn North" m:number_of_subject_officers=2891 m:ranking=2 m:complaints_count=603

series e:js82-9nvz d:2009-01-01T00:00:00.000Z t:precinct_command="Patrol Borough Brooklyn South" m:number_of_subject_officers=2501 m:ranking=3 m:complaints_count=440
```

## Meta Commands

```ls
metric m:ranking p:integer l:Ranking t:dataTypeName=number

metric m:complaints_count p:integer l:"Complaints Count" t:dataTypeName=number

metric m:number_of_subject_officers p:integer l:"Number Of Subject Officers" t:dataTypeName=number

entity e:js82-9nvz l:"Complaints per Uniformed Officer" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/js82-9nvz

property e:js82-9nvz t:meta.view v:id=js82-9nvz v:category="City Government" v:attributionLink=http://www.nyc.gov/html/ccrb/pdf/ccrbappendices2011.pdf v:averageRating=0 v:name="Complaints per Uniformed Officer" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:js82-9nvz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:js82-9nvz t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| year | ranking | precinct_command               | complaints_count | number_of_subject_officers | 
| ==== | ======= | ============================== | ================ | ========================== | 
| 2009 | 1       | Patrol Borough Bronx           | 772              | 3095                       | 
| 2009 | 2       | Patrol Borough Brooklyn North  | 603              | 2891                       | 
| 2009 | 3       | Patrol Borough Brooklyn South  | 440              | 2501                       | 
| 2009 | 4       | Organized Crime Control Bureau | 294              | 1794                       | 
| 2009 | 5       | Patrol Borough Queens South    | 265              | 1748                       | 
| 2009 | 6       | Housing Bureau                 | 289              | 2002                       | 
| 2009 | 7       | Patrol Borough Manhattan North | 430              | 2604                       | 
| 2009 | 8       | Patrol Borough Staten Island   | 136              | 941                        | 
| 2009 | 9       | Patrol Borough Manhattan South | 264              | 2315                       | 
| 2009 | 10      | Patrol Borough Queens North    | 182              | 1830                       | 
```