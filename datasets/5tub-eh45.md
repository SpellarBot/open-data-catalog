# Street Hail Livery (SHL) Drivers - Active

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-hail-livery-drivers-active-81bf5) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/5tub-eh45) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/5tub-eh45/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/5tub-eh45/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 5tub-eh45 |
| Name | Street Hail Livery (SHL) Drivers - Active |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | shl, boro taxi, green cabs, green taxi, street hail livery, drivers authorized, drivers active |
| Created | 2014-08-18T18:33:15Z |
| Publication Date | 2017-04-19T19:18:32Z |

## Description

NYC TLC licensed drivers that are currently active, in good standing and authorized to operate Street Hail Livery (SHL) vehicles. This list is accurate to the date and time represented in the Last Date Updated and Last Time Updated fields. For inquiries about the contents of this dataset, please email licensinginquiries@tlc.nyc.gov.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | series tag  | license_number     | License Number     | text          | text          |
| Yes      | series tag  | name               | Name               | text          | text          |
| Yes      | series tag  | status_code        | Status Code        | text          | number        |
| Yes      | series tag  | status_description | Status Description | text          | text          |
| Yes      | time        | expiration_date    | Expiration Date    | calendar_date | calendar_date |
| No       |             | last_update_date   | Last Date Updated  | calendar_date | calendar_date |
| No       |             | last_update_time   | Last Time Updated  | text          | text          |
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
series e:5tub-eh45 d:2019-11-24T00:00:00.000Z t:status_code=1 t:status_description="SHL UNRESTRICTED" t:license_number=493092 t:name=MAIGA,BOUNAFOU m:row_number.5tub-eh45=1

series e:5tub-eh45 d:2020-04-03T00:00:00.000Z t:status_code=1 t:status_description="SHL UNRESTRICTED" t:license_number=681774 t:name=GNANARAJ,SINNA m:row_number.5tub-eh45=2

series e:5tub-eh45 d:2020-01-30T00:00:00.000Z t:status_code=1 t:status_description="SHL UNRESTRICTED" t:license_number=497742 t:name=LACY,SAM,J m:row_number.5tub-eh45=3
```

## Meta Commands

```ls
metric m:row_number.5tub-eh45 p:long l:"Row Number"

entity e:5tub-eh45 l:"Street Hail Livery (SHL) Drivers - Active" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/5tub-eh45

property e:5tub-eh45 t:meta.view v:id=5tub-eh45 v:category=Transportation v:averageRating=0 v:name="Street Hail Livery (SHL) Drivers - Active" v:attribution="Taxi and Limousine Commission (TLC)"

property e:5tub-eh45 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:5tub-eh45 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| license_number | name                | status_code | status_description | expiration_date     | last_update_date    | last_update_time | 
| ============== | =================== | =========== | ================== | =================== | =================== | ================ | 
| 493092         | MAIGA,BOUNAFOU      | 1           | SHL UNRESTRICTED   | 2019-11-24T00:00:00 | 2017-04-19T00:00:00 | 13:20            | 
| 681774         | GNANARAJ,SINNA      | 1           | SHL UNRESTRICTED   | 2020-04-03T00:00:00 | 2017-04-19T00:00:00 | 13:20            | 
| 497742         | LACY,SAM,J          | 1           | SHL UNRESTRICTED   | 2020-01-30T00:00:00 | 2017-04-19T00:00:00 | 13:20            | 
| 498143         | KAREEM,LUKMAN,ABDUL | 1           | SHL UNRESTRICTED   | 2018-01-03T00:00:00 | 2017-04-19T00:00:00 | 13:20            | 
| 688826         | SANTANA,JUAN        | 1           | SHL UNRESTRICTED   | 2019-08-24T00:00:00 | 2017-04-19T00:00:00 | 13:20            | 
| 686178         | TAVERAS,OLGA        | 1           | SHL UNRESTRICTED   | 2019-08-21T00:00:00 | 2017-04-19T00:00:00 | 13:20            | 
| 664245         | CORNIEL,PEDRO,A     | 1           | SHL UNRESTRICTED   | 2019-04-10T00:00:00 | 2017-04-19T00:00:00 | 13:20            | 
| 498190         | JAMILU,MOHAMMED,Y   | 1           | SHL UNRESTRICTED   | 2020-02-19T00:00:00 | 2017-04-19T00:00:00 | 13:20            | 
| 689626         | BRODIE,ALFRED,A,JR  | 1           | SHL UNRESTRICTED   | 2019-11-14T00:00:00 | 2017-04-19T00:00:00 | 13:20            | 
| 695067         | ORTIZ,ANGEL         | 1           | SHL UNRESTRICTED   | 2019-04-19T00:00:00 | 2017-04-19T00:00:00 | 13:20            | 
```