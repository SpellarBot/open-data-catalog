# Paratransit Drivers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/paratransit-drivers-938ec) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/8bqd-u9ta) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/8bqd-u9ta/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/8bqd-u9ta/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 8bqd-u9ta |
| Name | Paratransit Drivers |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | transportation, taxi, limousine, vehicle, paratransit, transit, van, travel, drive, driver |
| Created | 2011-08-29T18:19:33Z |
| Publication Date | 2013-06-26T17:22:00Z |

## Description

Lists all TLC paratransit drivers

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag  | license_number          | License Number          | text          | number        |
| Yes      | series tag  | name_of_licensee        | Name of Licensee        | text          | text          |
| Yes      | series tag  | license_type            | License Type            | text          | text          |
| Yes      | time        | license_expiration_date | License Expiration Date | calendar_date | calendar_date |
```

## Time Field

```ls
Value = license_expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:8bqd-u9ta d:2012-07-21T00:00:00.000Z t:license_type="Paratransit Driver" t:license_number=5000717 t:name_of_licensee=YUSUPOV,BENSION m:row_number.8bqd-u9ta=1

series e:8bqd-u9ta d:2012-06-30T00:00:00.000Z t:license_type="Paratransit Driver" t:license_number=5001073 t:name_of_licensee=SANDLER,FELIX m:row_number.8bqd-u9ta=2

series e:8bqd-u9ta d:2012-06-03T00:00:00.000Z t:license_type="Paratransit Driver" t:license_number=5001551 t:name_of_licensee=MERCADO,RAYMOND,JR m:row_number.8bqd-u9ta=3
```

## Meta Commands

```ls
metric m:row_number.8bqd-u9ta p:long l:"Row Number"

entity e:8bqd-u9ta l:"Paratransit Drivers" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/8bqd-u9ta

property e:8bqd-u9ta t:meta.view v:id=8bqd-u9ta v:category=Transportation v:averageRating=0 v:name="Paratransit Drivers" v:attribution="Taxi and Limousine Commission (TLC)"

property e:8bqd-u9ta t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:8bqd-u9ta t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| license_number | name_of_licensee     | license_type       | license_expiration_date | 
| ============== | ==================== | ================== | ======================= | 
| 5000717        | YUSUPOV,BENSION      | Paratransit Driver | 2012-07-21T00:00:00     | 
| 5001073        | SANDLER,FELIX        | Paratransit Driver | 2012-06-30T00:00:00     | 
| 5001551        | MERCADO,RAYMOND,JR   | Paratransit Driver | 2012-06-03T00:00:00     | 
| 5002627        | FRIDMAN,YURIY        | Paratransit Driver | 2012-06-07T00:00:00     | 
| 5003366        | MOSESYAN,VITALIY     | Paratransit Driver | 2012-08-16T00:00:00     | 
| 5004815        | BEYGELMAN,MIKHAIL    | Paratransit Driver | 2012-06-23T00:00:00     | 
| 5005141        | DINGLE,HERBERT       | Paratransit Driver | 2012-06-17T00:00:00     | 
| 5006147        | KAZIUKONIS,ZBIGNEVAS | Paratransit Driver | 2012-06-09T00:00:00     | 
| 5008921        | ETIENNE,JEAN,M       | Paratransit Driver | 2013-07-26T00:00:00     | 
| 5011899        | LANDVIGER,INNA       | Paratransit Driver | 2013-08-16T00:00:00     | 
```