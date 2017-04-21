# Building Complaint Disposition Codes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-complaint-disposition-codes-f81f1) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/6v9u-ndjg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/6v9u-ndjg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/6v9u-ndjg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 6v9u-ndjg |
| Name | Building Complaint Disposition Codes |
| Attribution | Department of Buildings (DOB) |
| Category | Housing & Development |
| Tags | building, buildings, complaint, complaints, disposition, lookup, reference, clean web |
| Created | 2012-03-24T13:52:49Z |
| Publication Date | 2017-02-08T18:30:38Z |

## Description

A reference table of disposition codes for building complaints

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | code        | Code        | text      | text        |
| Yes      | series tag  | disposition | Disposition | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:6v9u-ndjg d:2017-02-08T18:30:22.000Z t:code=A1 t:disposition="BUILDINGS VIOLATION(S) SERVED" m:row_number.6v9u-ndjg=1

series e:6v9u-ndjg d:2017-02-08T18:30:22.000Z t:code=A2 t:disposition="CRIMINAL COURT SUMMONS SERVED" m:row_number.6v9u-ndjg=2

series e:6v9u-ndjg d:2017-02-08T18:30:22.000Z t:code=A3 t:disposition="FULL STOP WORK ORDER SERVED F" m:row_number.6v9u-ndjg=3
```

## Meta Commands

```ls
metric m:row_number.6v9u-ndjg p:long l:"Row Number"

entity e:6v9u-ndjg l:"Building Complaint Disposition Codes" t:attribution="Department of Buildings (DOB)" t:url=https://data.cityofnewyork.us/api/views/6v9u-ndjg

property e:6v9u-ndjg t:meta.view v:id=6v9u-ndjg v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/dob/html/bis/faq.shtml#complaints v:averageRating=0 v:name="Building Complaint Disposition Codes" v:attribution="Department of Buildings (DOB)"

property e:6v9u-ndjg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:6v9u-ndjg t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | code | disposition                                                     | 
| =========== | ==== | =============================================================== | 
| 1486578622  | A1   | BUILDINGS VIOLATION(S) SERVED                                   | 
| 1486578622  | A2   | CRIMINAL COURT SUMMONS SERVED                                   | 
| 1486578622  | A3   | FULL STOP WORK ORDER SERVED F                                   | 
| 1486578622  | A4   | BUILDINGS VIOLATION(S) & CRIMINAL COURT SUMMONS SERVED          | 
| 1486578622  | A5   | BUILDINGS VIOLATION(S) & CRIMINAL COURT SUMMONS SERVED          | 
| 1486578622  | A6   | VACANT/OPEN/UNGUARDED STRUCTURE - VIOLATION(S) ISSUED           | 
| 1486578622  | A7   | COMPLAINT ACCEPTED BY PADLOCK UNIT                              | 
| 1486578622  | A8   | ECB VIOLATION SERVED                                            | 
| 1486578622  | A9   | ECB & BUILDINGS VIOLATIONS SERVED                               | 
| 1486578622  | B1   | BUILDINGS VIOLATION(S) PREPARED & ATTEMPT TO SERVE WILL BE MADE | 
```