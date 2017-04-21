# Current Commuter Van Drivers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/current-commuter-van-drivers-fdd64) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mf6v-bdzr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mf6v-bdzr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mf6v-bdzr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mf6v-bdzr |
| Name | Current Commuter Van Drivers |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | transportation, taxi, limousine, commuter, van, driver |
| Created | 2011-08-26T20:44:51Z |
| Publication Date | 2011-08-26T20:44:51Z |

## Description

Spreadsheet of all TLC commuter van drivers

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type | Render Type |
| ======== | =========== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag  | license_number          | License Number          | text      | number      |
| Yes      | series tag  | name_of_licensee        | Name of Licensee        | text      | text        |
| Yes      | series tag  | license_type            | License Type            | text      | text        |
| Yes      | time        | license_expiration_date | License Expiration Date | date      | date        |
```

## Time Field

```ls
Value = license_expiration_date
Format & Zone = seconds
```

## Data Commands

```ls
series e:mf6v-bdzr d:2011-08-26T13:44:55.000Z t:license_type="License Type" t:name_of_licensee="Name of Licensee" m:row_number.mf6v-bdzr=1

series e:mf6v-bdzr d:2011-12-08T08:00:00.000Z t:license_type="Commuter Van Driver" t:license_number=5019397 t:name_of_licensee=OBI,DENNIS,A m:row_number.mf6v-bdzr=2

series e:mf6v-bdzr d:2012-12-30T08:00:00.000Z t:license_type="Commuter Van Driver" t:license_number=5024314 t:name_of_licensee=NG,WAH m:row_number.mf6v-bdzr=3
```

## Meta Commands

```ls
metric m:row_number.mf6v-bdzr p:long l:"Row Number"

entity e:mf6v-bdzr l:"Current Commuter Van Drivers" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/mf6v-bdzr

property e:mf6v-bdzr t:meta.view v:id=mf6v-bdzr v:category=Transportation v:averageRating=0 v:name="Current Commuter Van Drivers" v:attribution="Taxi and Limousine Commission (TLC)"

property e:mf6v-bdzr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:mf6v-bdzr t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| license_number | name_of_licensee   | license_type        | license_expiration_date | 
| ============== | ================== | =================== | ======================= | 
|                | Name of Licensee   | License Type        |                         | 
| 5019397        | OBI,DENNIS,A       | Commuter Van Driver | 1323331200              | 
| 5024314        | NG,WAH             | Commuter Van Driver | 1356854400              | 
| 5026408        | WATSON,DENNIS,R    | Commuter Van Driver | 1330156800              | 
| 5026791        | NG,CHUNG,K         | Commuter Van Driver | 1327737600              | 
| 5027067        | WEST,DESMOND,A     | Commuter Van Driver | 1327737600              | 
| 5027174        | PARCHMENT,KERT     | Commuter Van Driver | 1327046400              | 
| 5027731        | SMITH,RADCLIFFE,S  | Commuter Van Driver | 1327737600              | 
| 5028614        | OGOEGBUNAM,ATTAMOH | Commuter Van Driver | 1330416000              | 
| 5031906        | ROWE,GLASFORD      | Commuter Van Driver | 1335510000              | 
```