# CCRB: Average Days for the Police Department to Close Substantiated CCRB Cases 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-average-days-for-the-police-department-to-close-substantiated-ccrb-cases-2005-2009-e2cae) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/niyd-ckq3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/niyd-ckq3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/niyd-ckq3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | niyd-ckq3 |
| Name | CCRB: Average Days for the Police Department to Close Substantiated CCRB Cases 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics |
| Created | 2011-09-15T19:23:17Z |
| Publication Date | 2011-09-15T19:23:17Z |

## Description

Civilian Complaint Review Board (CCRB)complaint activity data, 2005-2009.  The time it takes the NYPD to resolve substantiated cases is measured from the date that the CCRB physically transferred the case file to the department until the last day of the month in which the department closed the case. The department does not inform the CCRB of its actual disposition date ?just the month in which it closed the case. In addition, when the Department Advocate's Office refers a case to a commanding officer for the imposition of a command discipline, the NYPD considers the case closed and reports that closure to the CCRB. It is subsequent to this closure date that the commanding officer decides upon a penalty consistent with the level of command discipline proscribed by the Department Advocate's Office. For cases that proceeded to administrative hearings, the time it takes for judges to render written decisions is included in calculating the department's closure time.
Update Schedule: Annually

## Columns

```ls
| Included | Schema Type    | Field Name                                              | Name                                                     | Data Type | Render Type |
| ======== | ============== | ======================================================= | ======================================================== | ========= | =========== |
| Yes      | series tag     | ccrb_substantiated_cases_average_days_for_nypd_to_close | CCRB Substantiated Cases, Average Days for NYPD to close | text      | text        |
| Yes      | numeric metric | 2005_cases                                              | 2005 Cases                                               | number    | text        |
| Yes      | numeric metric | 2005_average_days_to_close                              | 2005 Average Days to Close                               | number    | text        |
| Yes      | numeric metric | 2006_cases                                              | 2006 Cases                                               | number    | text        |
| Yes      | numeric metric | 2006_average_days_to_close                              | 2006 Average Days to Close                               | number    | text        |
| Yes      | numeric metric | 2007_cases                                              | 2007 Cases                                               | number    | text        |
| Yes      | numeric metric | 2007_average_days_to_close                              | 2007 Average Days to Close                               | number    | text        |
| Yes      | numeric metric | 2008_cases                                              | 2008 Cases                                               | number    | text        |
| Yes      | numeric metric | 2008_average_days_to_close                              | 2008 Average Days to Close                               | number    | text        |
| Yes      | numeric metric | 2009_cases                                              | 2009 Cases                                               | number    | text        |
| Yes      | numeric metric | 2009_average_days_to_close                              | 2009 Average Days to Close                               | number    | text        |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:niyd-ckq3 d:2005-01-01T00:00:00.000Z t:ccrb_substantiated_cases_average_days_for_nypd_to_close=Total m:2006_cases=366 m:2008_cases=282 m:2005_average_days_to_close=255 m:2009_average_days_to_close=269 m:2009_cases=266 m:2006_average_days_to_close=289 m:2007_average_days_to_close=272 m:2005_cases=481 m:2008_average_days_to_close=304 m:2007_cases=314
```

## Meta Commands

```ls
metric m:2005_cases p:integer l:"2005 Cases" t:dataTypeName=number

metric m:2005_average_days_to_close p:integer l:"2005 Average Days to Close" t:dataTypeName=number

metric m:2006_cases p:integer l:"2006 Cases" t:dataTypeName=number

metric m:2006_average_days_to_close p:integer l:"2006 Average Days to Close" t:dataTypeName=number

metric m:2007_cases p:integer l:"2007 Cases" t:dataTypeName=number

metric m:2007_average_days_to_close p:integer l:"2007 Average Days to Close" t:dataTypeName=number

metric m:2008_cases p:integer l:"2008 Cases" t:dataTypeName=number

metric m:2008_average_days_to_close p:integer l:"2008 Average Days to Close" t:dataTypeName=number

metric m:2009_cases p:integer l:"2009 Cases" t:dataTypeName=number

metric m:2009_average_days_to_close p:integer l:"2009 Average Days to Close" t:dataTypeName=number

entity e:niyd-ckq3 l:"CCRB: Average Days for the Police Department to Close Substantiated CCRB Cases  2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/niyd-ckq3

property e:niyd-ckq3 t:meta.view v:id=niyd-ckq3 v:category="Public Safety" v:averageRating=0 v:name="CCRB: Average Days for the Police Department to Close Substantiated CCRB Cases  2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:niyd-ckq3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:niyd-ckq3 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| ccrb_substantiated_cases_average_days_for_nypd_to_close                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 2005_cases | 2005_average_days_to_close | 2006_cases | 2006_average_days_to_close | 2007_cases | 2007_average_days_to_close | 2008_cases | 2008_average_days_to_close | 2009_cases | 2009_average_days_to_close | 
| ====================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ========== | ========================== | ========== | ========================== | ========== | ========================== | ========== | ========================== | ========== | ========================== | 
| Total                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 481        | 255                        | 366        | 289                        | 314        | 272                        | 282        | 304                        | 266        | 269                        | 
| * The time it takes the NYPD to resolve substantiated cases is measured from the date that the CCRB physically transferred the case file to the department until the last day of the month in which the department closed the case. The department does not inform the CCRB of its actual disposition date ?just the month in which it closed the case. In addition, when the Department Advocate's Office refers a case to a commanding officer for the imposition of a command discipline, the NYPD considers the case closed and reports that closure to the CCRB. It is subsequent to this closure date that the commanding officer decides upon a penalty consistent with the level of command discipline proscribed by the Department Advocate's Office. For cases that proceeded to administrative hearings, the time it takes for judges to render written decisions is included in calculating the department's closure time. |            |                            |            |                            |            |                            |            |                            |            |                            | 
```