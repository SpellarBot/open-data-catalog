# DOP Adult Probationers Rearrested As A Percentage Of NYPD Arrest Report (Monthly Average)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adult-probationers-rearrested-as-a-percentage-of-nypd-arrest-report-monthly-average) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/arhf-esqb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/arhf-esqb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/arhf-esqb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | arhf-esqb |
| Name | DOP Adult Probationers Rearrested As A Percentage Of NYPD Arrest Report (Monthly Average) |
| Attribution | Department of Probation (DOP) |
| Category | Public Safety |
| Tags | dop |
| Created | 2016-08-02T17:51:58Z |
| Publication Date | 2017-03-31T20:56:13Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type | Render Type |
| ======== | ============== | ========== | ====== | ========= | =========== |
| Yes      | series tag     | borough    | Region | text      | text        |
| No       |                | month      | Month  | text      | text        |
| No       |                | year       | Year   | number    | number      |
| Yes      | numeric metric | rate       | Rate   | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:arhf-esqb d:2016-03-01T00:00:00.000Z t:borough=Citywide m:rate=3.3

series e:arhf-esqb d:2016-04-01T00:00:00.000Z t:borough=Citywide m:rate=3.3

series e:arhf-esqb d:2016-05-01T00:00:00.000Z t:borough=Citywide m:rate=3.3
```

## Meta Commands

```ls
metric m:rate p:float l:Rate d:"The percentage of adult probationer arrests relative to all arrests recorded by the Police Department during the reporting period." t:dataTypeName=number

entity e:arhf-esqb l:"DOP Adult Probationers Rearrested As A Percentage Of NYPD Arrest Report (Monthly Average)" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/arhf-esqb

property e:arhf-esqb t:meta.view v:id=arhf-esqb v:category="Public Safety" v:averageRating=0 v:name="DOP Adult Probationers Rearrested As A Percentage Of NYPD Arrest Report (Monthly Average)" v:attribution="Department of Probation (DOP)"

property e:arhf-esqb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:arhf-esqb t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough  | month     | year | rate | 
| ======== | ========= | ==== | ==== | 
| Citywide | March     | 2016 | 3.3  | 
| Citywide | April     | 2016 | 3.3  | 
| Citywide | May       | 2016 | 3.3  | 
| Citywide | June      | 2016 | 3.3  | 
| Citywide | July      | 2016 | 3.6  | 
| Citywide | August    | 2016 | 3.5  | 
| Citywide | September | 2016 | 3.6  | 
| Citywide | October   | 2016 | 3.6  | 
| Citywide | November  | 2016 | 3.5  | 
| Citywide | December  | 2016 | 3.5  | 
```