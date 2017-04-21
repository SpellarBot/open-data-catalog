# Street Hail Livery (SHL) Drivers ? Status Change Log 09/18/2014 - present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-hail-livery-drivers-status-change-log-09-18-2014-present-aafad) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/v3mc-68jm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/v3mc-68jm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/v3mc-68jm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | v3mc-68jm |
| Name | Street Hail Livery (SHL) Drivers ? Status Change Log 09/18/2014 - present |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | shl, boro taxi, green cabs, green taxi, street hail livery, drivers authorized, drivers active |
| Created | 2014-09-25T15:22:49Z |
| Publication Date | 2014-10-07T15:00:21Z |

## Description

This list contains information on changes in status to Street Hail Livery Drivers and their corresponding record history starting from 09/18/2014 (inclusive). The most recently published active Street Hail Livery Drivers list can be found at https://data.cityofnewyork.us/Transportation/Street-Hail-Livery-Drivers-Active/5tub-eh45

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | license_number     | License Number     | text          | text          |
| Yes      | series tag     | name               | Name               | text          | text          |
| Yes      | series tag     | status_code        | Status Code        | text          | number        |
| Yes      | series tag     | status_description | Status Description | text          | text          |
| Yes      | time           | expiration_date    | Expiration Date    | calendar_date | calendar_date |
| No       |                | last_update_date   | Last Update Date   | calendar_date | calendar_date |
| No       |                | last_update_time   | Last Update Time   | text          | text          |
| Yes      | series tag     | active_flag        | Active Flag        | text          | text          |
| Yes      | numeric metric | row_wid            | Row Wid            | number        | number        |
```

## Time Field

```ls
Value = expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = last_update_date,last_update_time
```

## Data Commands

```ls
series e:v3mc-68jm d:2015-12-06T00:00:00.000Z t:status_code=2 t:status_description="SHL NON-WAV ONLY" t:license_number=502653 t:name=AROUNA,FADE t:active_flag=Y m:row_wid=674

series e:v3mc-68jm d:2015-06-22T00:00:00.000Z t:status_code=1 t:status_description="SHL UNRESTRICTED" t:license_number=874136 t:name=IQBAL,QUAID t:active_flag=N m:row_wid=17926

series e:v3mc-68jm d:2015-09-23T00:00:00.000Z t:status_code=2 t:status_description="SHL NON-WAV ONLY" t:license_number=495457 t:name=MANTE,NII,AMU t:active_flag=N m:row_wid=2051
```

## Meta Commands

```ls
metric m:row_wid p:integer l:"Row Wid" t:dataTypeName=number

entity e:v3mc-68jm l:"Street Hail Livery (SHL) Drivers ? Status Change Log 09/18/2014 - present" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/v3mc-68jm

property e:v3mc-68jm t:meta.view v:id=v3mc-68jm v:category=Transportation v:averageRating=0 v:name="Street Hail Livery (SHL) Drivers ? Status Change Log 09/18/2014 - present" v:attribution="Taxi and Limousine Commission (TLC)"

property e:v3mc-68jm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:v3mc-68jm t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| license_number | name                 | status_code | status_description | expiration_date     | last_update_date    | last_update_time | active_flag | row_wid | 
| ============== | ==================== | =========== | ================== | =================== | =================== | ================ | =========== | ======= | 
| 502653         | AROUNA,FADE          | 2           | SHL NON-WAV ONLY   | 2015-12-06T00:00:00 | 2015-02-04T00:00:00 | 13:20            | Y           | 674     | 
| 874136         | IQBAL,QUAID          | 1           | SHL UNRESTRICTED   | 2015-06-22T00:00:00 | 2015-06-22T00:00:00 | 13:20            | N           | 17926   | 
| 495457         | MANTE,NII,AMU        | 2           | SHL NON-WAV ONLY   | 2015-09-23T00:00:00 | 2015-09-23T00:00:00 | 13:20            | N           | 2051    | 
| 686963         | HAGIGAT,YAGOUB       | 1           | SHL UNRESTRICTED   | 2015-08-12T00:00:00 | 2015-08-12T00:00:00 | 13:20            | N           | 2512    | 
| 675205         | FRIEDMAN,BRUCE,H     | 1           | SHL UNRESTRICTED   | 2015-12-09T00:00:00 | 2015-12-09T00:00:00 | 13:20            | N           | 644     | 
| 879465         | CONCEPCION,JOHNNY,JR | 1           | SHL UNRESTRICTED   | 2016-04-27T00:00:00 | 2016-04-27T00:00:00 | 13:20            | N           | 21799   | 
| 422081         | SINGH,LAKHVINDER     | 2           | SHL NON-WAV ONLY   | 2015-09-13T00:00:00 | 2014-08-20T00:00:00 | 13:20            | N           | 11087   | 
| 664245         | CORNIEL,PEDRO,A      | 1           | SHL UNRESTRICTED   | 2016-04-10T00:00:00 | 2016-03-09T00:00:00 | 13:20            | N           | 9       | 
| 5403616        | AIZIKOWICH,GERSHON   | 3           | SHL WAV ONLY       | 2015-07-01T00:00:00 | 2015-07-01T00:00:00 | 13:20            | Y           | 73662   | 
| 5336817        | TINUADE,ADEYINKA,O   | 1           | SHL UNRESTRICTED   | 2016-06-26T00:00:00 | 2016-06-25T00:00:00 | 13:20            | N           | 60729   | 
```