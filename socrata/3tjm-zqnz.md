# TPW_StreetsMeasures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tpw-streetsmeasures) |
| Metadata | [Link](https://data.srcity.org/api/views/3tjm-zqnz) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/3tjm-zqnz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/3tjm-zqnz/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | 3tjm-zqnz |
| Name | TPW_StreetsMeasures |
| Category | Transportation |
| Created | 2017-02-08T15:35:36Z |
| Publication Date | 2017-02-08T19:37:19Z |

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type     | Render Type   |
| ======== | ============== | =================================== | =================================== | ============= | ============= |
| No       |                | year                                | Year                                | number        | number        |
| Yes      | series tag     | goaltype                            | GoalType                            | text          | text          |
| Yes      | series tag     | measure                             | Measure                             | text          | text          |
| Yes      | series tag     | submeasure                          | SubMeasure                          | text          | text          |
| Yes      | time           | date                                | Date                                | calendar_date | calendar_date |
| Yes      | series tag     | type                                | Type                                | text          | text          |
| Yes      | numeric metric | avgresponsehours                    | AvgResponseHours                    | number        | number        |
| Yes      | numeric metric | noofpotholeservicerequests          | NoOfPotholeServiceRequests          | number        | number        |
| Yes      | numeric metric | noofsidewalkservicerequests         | NoOfSidewalkServiceRequests         | number        | number        |
| Yes      | numeric metric | noofsignsservicerequests            | NoOfSignsServiceRequests            | number        | number        |
| Yes      | numeric metric | noofsignmaintenanceservicerequests  | NoOfSignMaintenanceServiceRequests  | number        | number        |
| Yes      | numeric metric | noofsigninstallationservicerequests | NoOfSignInstallationServiceRequests | number        | number        |
| Yes      | numeric metric | noofsignreplacementservicerequests  | NoOfSignReplacementServiceRequests  | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:3tjm-zqnz d:2016-12-31T00:00:00.000Z t:measure=Signs t:submeasure="Sign Replacement" t:type=annually t:goaltype=Streets m:avgresponsehours=1.5 m:noofsignreplacementservicerequests=2

series e:3tjm-zqnz d:2017-12-31T00:00:00.000Z t:measure=Signs t:submeasure="Sign Replacement" t:type=annually t:goaltype=Streets m:avgresponsehours=18 m:noofsignreplacementservicerequests=1

series e:3tjm-zqnz d:2016-09-01T00:00:00.000Z t:measure=Signs t:submeasure="Sign Replacement" t:type=monthly t:goaltype=Streets m:avgresponsehours=1.5 m:noofsignreplacementservicerequests=2
```

## Meta Commands

```ls
metric m:avgresponsehours p:double l:AvgResponseHours t:dataTypeName=number

metric m:noofpotholeservicerequests p:integer l:NoOfPotholeServiceRequests t:dataTypeName=number

metric m:noofsidewalkservicerequests p:integer l:NoOfSidewalkServiceRequests t:dataTypeName=number

metric m:noofsignsservicerequests p:integer l:NoOfSignsServiceRequests t:dataTypeName=number

metric m:noofsignmaintenanceservicerequests p:integer l:NoOfSignMaintenanceServiceRequests t:dataTypeName=number

metric m:noofsigninstallationservicerequests p:integer l:NoOfSignInstallationServiceRequests t:dataTypeName=number

metric m:noofsignreplacementservicerequests p:integer l:NoOfSignReplacementServiceRequests t:dataTypeName=number

entity e:3tjm-zqnz l:TPW_StreetsMeasures t:url=https://data.srcity.org/api/views/3tjm-zqnz

property e:3tjm-zqnz t:meta.view v:id=3tjm-zqnz v:category=Transportation v:averageRating=0 v:name=TPW_StreetsMeasures

property e:3tjm-zqnz t:meta.view.owner v:id=v4p4-re39 v:screenName="OpenData, RO" v:displayName="OpenData, RO"

property e:3tjm-zqnz t:meta.view.tableauthor v:id=v4p4-re39 v:screenName="OpenData, RO" v:roleName=administrator v:displayName="OpenData, RO"
```

## Top Records

```ls
| year | goaltype | measure | submeasure        | date                | type     | avgresponsehours | noofpotholeservicerequests | noofsidewalkservicerequests | noofsignsservicerequests | noofsignmaintenanceservicerequests | noofsigninstallationservicerequests | noofsignreplacementservicerequests | 
| ==== | ======== | ======= | ================= | =================== | ======== | ================ | ========================== | =========================== | ======================== | ================================== | =================================== | ================================== | 
| 2016 | Streets  | Signs   | Sign Replacement  | 2016-12-31T00:00:00 | annually | 1.5              |                            |                             |                          |                                    |                                     | 2                                  | 
| 2017 | Streets  | Signs   | Sign Replacement  | 2017-12-31T00:00:00 | annually | 18               |                            |                             |                          |                                    |                                     | 1                                  | 
| 2016 | Streets  | Signs   | Sign Replacement  | 2016-09-01T00:00:00 | monthly  | 1.5              |                            |                             |                          |                                    |                                     | 2                                  | 
| 2017 | Streets  | Signs   | Sign Replacement  | 2017-01-01T00:00:00 | monthly  | 18               |                            |                             |                          |                                    |                                     | 1                                  | 
| 2016 | Streets  | Signs   | Sign Installation | 2016-09-01T00:00:00 | monthly  | 87.1428571428571 |                            |                             |                          |                                    | 7                                   |                                    | 
| 2016 | Streets  | Signs   | Sign Installation | 2016-11-01T00:00:00 | monthly  | 247.888888888889 |                            |                             |                          |                                    | 18                                  |                                    | 
| 2016 | Streets  | Signs   | Sign Installation | 2016-07-01T00:00:00 | monthly  | 90.25            |                            |                             |                          |                                    | 8                                   |                                    | 
| 2016 | Streets  | Signs   | Sign Installation | 2016-05-01T00:00:00 | monthly  | 24.1818181818182 |                            |                             |                          |                                    | 11                                  |                                    | 
| 2016 | Streets  | Signs   | Sign Installation | 2016-04-01T00:00:00 | monthly  | 24.8571428571429 |                            |                             |                          |                                    | 7                                   |                                    | 
| 2016 | Streets  | Signs   | Sign Installation | 2016-06-01T00:00:00 | monthly  | 94.625           |                            |                             |                          |                                    | 8                                   |                                    | 
```