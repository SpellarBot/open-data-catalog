# Police Department Disciplinary Penalties

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/police-department-disciplinary-penalties-01eda) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ns22-2dcm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ns22-2dcm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ns22-2dcm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ns22-2dcm |
| Name | Police Department Disciplinary Penalties |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | City Government |
| Tags | ccrb, police, penalties, department, terminated |
| Created | 2013-02-26T20:08:34Z |
| Publication Date | 2013-06-21T20:05:40Z |

## Description

This data set represents police department disciplinary penalties imposed by NYPD

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | time           | year          | Year          | number    | number      |
| Yes      | series tag     | penalties     | Penalties     | text      | text        |
| Yes      | numeric metric | officer_count | Officer Count | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ns22-2dcm d:2009-01-01T00:00:00.000Z t:penalties=Terminated m:officer_count=0

series e:ns22-2dcm d:2009-01-01T00:00:00.000Z t:penalties="Suspension or loss of vacation time of 31 or more days and / or 1 year probation" m:officer_count=1

series e:ns22-2dcm d:2009-01-01T00:00:00.000Z t:penalties="Suspension or loss of vacation time of 21 to 30 more days and / or 1 year probation" m:officer_count=3
```

## Meta Commands

```ls
metric m:officer_count p:integer l:"Officer Count" t:dataTypeName=number

entity e:ns22-2dcm l:"Police Department Disciplinary Penalties" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/ns22-2dcm

property e:ns22-2dcm t:meta.view v:id=ns22-2dcm v:category="City Government" v:attributionLink=http://www.nyc.gov/html/ccrb/pdf/ccrbappendices2011.pdf v:averageRating=0 v:name="Police Department Disciplinary Penalties" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:ns22-2dcm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ns22-2dcm t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| year | penalties                                                                           | officer_count | 
| ==== | =================================================================================== | ============= | 
| 2009 | Terminated                                                                          | 0             | 
| 2009 | Suspension or loss of vacation time of 31 or more days and / or 1 year probation    | 1             | 
| 2009 | Suspension or loss of vacation time of 21 to 30 more days and / or 1 year probation | 3             | 
| 2009 | Suspension or loss of vacation time of 11 to 20 days                                | 4             | 
| 2009 | Suspension or loss of vacation time of 1 to 10 days                                 | 11            | 
| 2009 | Command discipline A                                                                | 14            | 
| 2009 | Command discipline B                                                                | 58            | 
| 2009 | Instructions                                                                        | 70            | 
| 2009 | Warned and admonished                                                               | 0             | 
| 2010 | Terminated                                                                          | 0             | 
```