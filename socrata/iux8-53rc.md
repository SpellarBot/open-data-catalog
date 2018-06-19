# Medallion Drivers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medallion-drivers-bdca3) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/iux8-53rc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/iux8-53rc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/iux8-53rc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | iux8-53rc |
| Name | Medallion Drivers |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | transportation, taxi, limousine, medallion, drive, driver |
| Created | 2011-08-29T18:27:10Z |
| Publication Date | 2011-10-11T15:24:46Z |

## Description

List of all TLC medallion drivers

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
series e:iux8-53rc d:2012-01-31T08:00:00.000Z t:license_type="Medallion Taxi Driver" t:license_number=4511 t:name_of_licensee=MCKENNA,BERNARD m:row_number.iux8-53rc=1

series e:iux8-53rc d:2013-02-28T08:00:00.000Z t:license_type="Medallion Taxi Driver" t:license_number=4832 t:name_of_licensee=MERMELSTEIN,JOSEF m:row_number.iux8-53rc=2

series e:iux8-53rc d:2013-02-13T08:00:00.000Z t:license_type="Medallion Taxi Driver" t:license_number=7022 t:name_of_licensee=LOCASCIO,SALVATORE,D m:row_number.iux8-53rc=3
```

## Meta Commands

```ls
metric m:row_number.iux8-53rc p:long l:"Row Number"

entity e:iux8-53rc l:"Medallion Drivers" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/iux8-53rc

property e:iux8-53rc t:meta.view v:id=iux8-53rc v:category=Transportation v:averageRating=0 v:name="Medallion Drivers" v:attribution="Taxi and Limousine Commission (TLC)"

property e:iux8-53rc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:iux8-53rc t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| license_number | name_of_licensee     | license_type          | license_expiration_date | 
| ============== | ==================== | ===================== | ======================= | 
| 4511           | MCKENNA,BERNARD      | Medallion Taxi Driver | 1327996800              | 
| 4832           | MERMELSTEIN,JOSEF    | Medallion Taxi Driver | 1362038400              | 
| 7022           | LOCASCIO,SALVATORE,D | Medallion Taxi Driver | 1360742400              | 
| 9193           | NUNEZ,ROLANDO        | Medallion Taxi Driver | 1329811200              | 
| 9909           | GIKAS,NICKOLAS       | Medallion Taxi Driver | 1330070400              | 
| 11327          | BERMAN,DONALD,A      | Medallion Taxi Driver | 1327996800              | 
| 11979          | WEISSMAN,ABRAHAM,K   | Medallion Taxi Driver | 1327996800              | 
| 13662          | RODRIGUEZ,DAVID      | Medallion Taxi Driver | 1360137600              | 
| 13684          | DAVIS,JAMES,JR       | Medallion Taxi Driver | 1360224000              | 
| 15795          | APONTE,RAFAEL        | Medallion Taxi Driver | 1328083200              | 
```