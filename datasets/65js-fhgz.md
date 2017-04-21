# DOP Juvenile Cases Snapshot by Calendar Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dop-juvenile-cases-snapshot-by-calendar-year-63a0c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/65js-fhgz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/65js-fhgz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/65js-fhgz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 65js-fhgz |
| Name | DOP Juvenile Cases Snapshot by Calendar Year |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, probation, juvenile cases, snapshot, calendar year |
| Created | 2014-06-17T16:46:42Z |
| Publication Date | 2017-03-08T21:00:00Z |

## Description

The number of active juvenile probation supervision cases on the last day of the reporting period (December 31)

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | borough                    | Borough                    | text      | text        |
| Yes      | time           | calendar_year              | Calendar Year              | number    | number      |
| Yes      | numeric metric | supervision_caseload_count | Supervision Caseload Count | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:65js-fhgz d:2006-01-01T00:00:00.000Z t:borough=Bronx m:supervision_caseload_count=822

series e:65js-fhgz d:2007-01-01T00:00:00.000Z t:borough=Bronx m:supervision_caseload_count=752

series e:65js-fhgz d:2008-01-01T00:00:00.000Z t:borough=Bronx m:supervision_caseload_count=675
```

## Meta Commands

```ls
metric m:supervision_caseload_count p:integer l:"Supervision Caseload Count" d:"The number of active juvenile probation supervision cases on the last day of the reporting period (December 31)." t:dataTypeName=number

entity e:65js-fhgz l:"DOP Juvenile Cases Snapshot by Calendar Year" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/65js-fhgz

property e:65js-fhgz t:meta.view v:id=65js-fhgz v:category="City Government" v:averageRating=0 v:name="DOP Juvenile Cases Snapshot by Calendar Year" v:attribution="Department of Probation (DOP)"

property e:65js-fhgz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:65js-fhgz t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough  | calendar_year | supervision_caseload_count | 
| ======== | ============= | ========================== | 
| Bronx    | 2006          | 822                        | 
| Bronx    | 2007          | 752                        | 
| Bronx    | 2008          | 675                        | 
| Bronx    | 2009          | 891                        | 
| Bronx    | 2010          | 713                        | 
| Bronx    | 2011          | 657                        | 
| Bronx    | 2012          | 626                        | 
| Bronx    | 2013          | 457                        | 
| Brooklyn | 2006          | 942                        | 
| Brooklyn | 2007          | 778                        | 
```