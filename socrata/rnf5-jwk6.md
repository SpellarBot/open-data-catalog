# Disposition of Allegations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-allegations-7e359) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rnf5-jwk6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rnf5-jwk6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rnf5-jwk6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rnf5-jwk6 |
| Name | Disposition of Allegations |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | City Government |
| Tags | ccrb, investigations, dispositions, disciplinary, disposition, allegations |
| Created | 2013-02-25T21:47:06Z |
| Publication Date | 2013-06-21T20:04:58Z |

## Description

This table represents the disposition of allegations

## Columns

```ls
| Included | Schema Type    | Field Name                                                        | Name                                                                | Data Type | Render Type |
| ======== | ============== | ================================================================= | =================================================================== | ========= | =========== |
| Yes      | time           | year                                                              | Year                                                                | number    | text        |
| Yes      | numeric metric | full_investigations_dispositions_and_disciplinary_recommendations | Full Investigations - Dispositions and Disciplinary Recommendations | number    | text        |
| Yes      | numeric metric | alternative_dispute_resolution_closures                           | Alternative Dispute Resolution Closures                             | number    | text        |
| Yes      | numeric metric | truncated_investigations                                          | Truncated Investigations                                            | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rnf5-jwk6 d:2009-01-01T00:00:00.000Z m:full_investigations_dispositions_and_disciplinary_recommendations=10143 m:truncated_investigations=23990 m:alternative_dispute_resolution_closures=419

series e:rnf5-jwk6 d:2010-01-01T00:00:00.000Z m:full_investigations_dispositions_and_disciplinary_recommendations=8895 m:truncated_investigations=20389 m:alternative_dispute_resolution_closures=800

series e:rnf5-jwk6 d:2011-01-01T00:00:00.000Z m:full_investigations_dispositions_and_disciplinary_recommendations=6836 m:truncated_investigations=16886 m:alternative_dispute_resolution_closures=798
```

## Meta Commands

```ls
metric m:full_investigations_dispositions_and_disciplinary_recommendations p:integer l:"Full Investigations - Dispositions and Disciplinary Recommendations" t:dataTypeName=number

metric m:alternative_dispute_resolution_closures p:integer l:"Alternative Dispute Resolution Closures" t:dataTypeName=number

metric m:truncated_investigations p:integer l:"Truncated Investigations" t:dataTypeName=number

entity e:rnf5-jwk6 l:"Disposition of Allegations" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/rnf5-jwk6

property e:rnf5-jwk6 t:meta.view v:id=rnf5-jwk6 v:category="City Government" v:attributionLink=http://www.nyc.gov/html/ccrb/pdf/ccrbappendices2011.pdf v:averageRating=0 v:name="Disposition of Allegations" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:rnf5-jwk6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rnf5-jwk6 t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| year | full_investigations_dispositions_and_disciplinary_recommendations | alternative_dispute_resolution_closures | truncated_investigations | 
| ==== | ================================================================= | ======================================= | ======================== | 
| 2009 | 10143                                                             | 419                                     | 23990                    | 
| 2010 | 8895                                                              | 800                                     | 20389                    | 
| 2011 | 6836                                                              | 798                                     | 16886                    | 
```