# Alerts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/test-1234) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/sn5i-xuny) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/sn5i-xuny/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/sn5i-xuny/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | sn5i-xuny |
| Name | Alerts |
| Attribution | Department of Information Technology and Telecommunications |
| Category | City Government |
| Created | 2016-12-22T20:51:56Z |
| Publication Date | 2017-04-13T14:43:11Z |

## Description

This dataset contains alerts related to NYC OpenData datasets that have been reported and verified.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | time        | alert_date      | Alert Date      | calendar_date | calendar_date |
| Yes      | series tag  | dataset_url     | Dataset         | url           | url           |
| Yes      | series tag  | dataset_name    | Dataset Name    | text          | text          |
| Yes      | series tag  | status          | Status          | text          | text          |
| Yes      | series tag  | details         | Details         | text          | text          |
| No       |             | resolution_date | Resolution Date | calendar_date | calendar_date |
| Yes      | series tag  | resolution      | Resolution      | text          | text          |
```

## Time Field

```ls
Value = alert_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = resolution_date
```

## Data Commands

```ls
series e:sn5i-xuny d:2016-11-01T00:00:00.000Z t:dataset_url=https://data.cityofnewyork.us/City-Government/ACRIS-Personal-Property-Parties/gq4f-jwz9 t:details="Several records in the dataset are corrupt." t:status=Resolved t:resolution="Datasets were recreated and reloaded." t:dataset_name="ACRIS Personal Property Parties" m:row_number.sn5i-xuny=1

series e:sn5i-xuny d:2016-11-01T00:00:00.000Z t:dataset_url=https://data.cityofnewyork.us/City-Government/ACRIS-Real-Property-Parties/nf4v-htvt t:details="Several records in the dataset are corrupt." t:status=Resolved t:resolution="Datasets were recreated and reloaded." t:dataset_name="ACRIS Real Property Parties" m:row_number.sn5i-xuny=2

series e:sn5i-xuny d:2016-11-01T00:00:00.000Z t:dataset_url=https://data.cityofnewyork.us/City-Government/ACRIS-Real-Property-References/qpy9-5hqe t:details="Several records in the dataset are corrupt." t:status=Resolved t:resolution="Datasets were recreated and reloaded." t:dataset_name="ACRIS Real Property References" m:row_number.sn5i-xuny=3
```

## Meta Commands

```ls
metric m:row_number.sn5i-xuny p:long l:"Row Number"

entity e:sn5i-xuny l:Alerts t:attribution="Department of Information Technology and Telecommunications" t:url=https://data.cityofnewyork.us/api/views/sn5i-xuny

property e:sn5i-xuny t:meta.view v:id=sn5i-xuny v:category="City Government" v:averageRating=0 v:name=Alerts v:attribution="Department of Information Technology and Telecommunications"

property e:sn5i-xuny t:meta.view.owner v:id=txun-eb7e v:screenName="Albert Webber" v:displayName="Albert Webber"

property e:sn5i-xuny t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| alert_date          | dataset_url                                                                                     | dataset_name                    | status   | details                                                                             | resolution_date     | resolution                            | 
| =================== | =============================================================================================== | =============================== | ======== | =================================================================================== | =================== | ===================================== | 
| 2016-11-01T00:00:00 | [https://data.cityofnewyork.us/City-Government/ACRIS-Personal-Property-Parties/gq4f-jwz9, null] | ACRIS Personal Property Parties | Resolved | Several records in the dataset are corrupt.                                         | 2017-02-16T00:00:00 | Datasets were recreated and reloaded. | 
| 2016-11-01T00:00:00 | [https://data.cityofnewyork.us/City-Government/ACRIS-Real-Property-Parties/nf4v-htvt, null]     | ACRIS Real Property Parties     | Resolved | Several records in the dataset are corrupt.                                         | 2017-02-16T00:00:00 | Datasets were recreated and reloaded. | 
| 2016-11-01T00:00:00 | [https://data.cityofnewyork.us/City-Government/ACRIS-Real-Property-References/qpy9-5hqe, null]  | ACRIS Real Property References  | Resolved | Several records in the dataset are corrupt.                                         | 2017-02-16T00:00:00 | Datasets were recreated and reloaded. | 
| 2017-02-01T00:00:00 | [https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions/h9gi-nx95, null]     | NYPD Motor Vehicle Collision    | Open     | Data issues have been confirmed and a fix is being investigated.                    |                     |                                       | 
| 2017-01-20T00:00:00 | [https://data.cityofnewyork.us/City-Government/Evictions/6z8x-wfk4, null]                       | Evictions                       | Open     | This dataset has been taken down while reported data issues are being investigated. |                     |                                       | 
| 2017-04-13T00:00:00 | [https://data.cityofnewyork.us/City-Government/OATH-ECB-Hearings-Case-Status/y6h5-jvss, null]   | OATH ECB Hearings Case Status   | Open     | A small number of records are not reflecting the latest information.                |                     |                                       | 
```