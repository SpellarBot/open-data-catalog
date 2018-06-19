# Lost Property Contact Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lost-property-contact-information-f4502) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/dg7a-jiz2) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/dg7a-jiz2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/dg7a-jiz2/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | dg7a-jiz2 |
| Name | Lost Property Contact Information |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | taxi, yellow cab, shl, boro taxi, medallion, green cabs, green taxi |
| Created | 2014-01-09T20:43:07Z |
| Publication Date | 2017-04-20T18:50:39Z |

## Description

This list contains lost item contact information on  bases that are affiliated with TLC SHL/Boro and Yellow Medallion Taxicabs. For inquiries about the contents of this dataset, please email licensinginquiries@tlc.nyc.gov.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type     | Render Type   |
| ======== | =========== | =================== | =================== | ============= | ============= |
| Yes      | series tag  | license_number      | License Number      | text          | text          |
| Yes      | series tag  | name                | Name                | text          | text          |
| Yes      | series tag  | type                | Type                | text          | text          |
| Yes      | series tag  | dmv_plate_number    | DMV Plate Number    | text          | text          |
| Yes      | series tag  | base_name           | Base Name           | text          | text          |
| Yes      | series tag  | base_license_number | Base License Number | text          | text          |
| Yes      | series tag  | base_phone_number   | Base Phone Number   | text          | text          |
| No       |             | base_address        | Base Address        | text          | text          |
| Yes      | series tag  | base_website        | Base Website        | text          | text          |
| Yes      | time        | last_updated_date   | Last Updated Date   | calendar_date | calendar_date |
| No       |             | last_updated_time   | Last Updated Time   | text          | text          |
```

## Time Field

```ls
Value = last_updated_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = base_address,last_updated_time
```

## Data Commands

```ls
series e:dg7a-jiz2 d:2017-04-20T00:00:00.000Z t:license_number=6A66 t:name="TAN, TOMMY" t:dmv_plate_number=6A66B t:type=MEDALLION m:row_number.dg7a-jiz2=1

series e:dg7a-jiz2 d:2017-04-20T00:00:00.000Z t:license_number=6A67 t:base_phone_number=(718)361-0055 t:name="HAVERLIN, WILLIAM J." t:dmv_plate_number=6A67A t:type=MEDALLION t:base_license_number=202 t:base_name="ALL TAXI MANAGEMENT INC" m:row_number.dg7a-jiz2=2

series e:dg7a-jiz2 d:2017-04-20T00:00:00.000Z t:license_number=6A68 t:base_phone_number=(917)578-1803 t:name="CANDIA, ROLANDO" t:dmv_plate_number=6A68J t:type=MEDALLION t:base_license_number=307 t:base_name="TAXIFLEET MANAGEMENT LLC" m:row_number.dg7a-jiz2=3
```

## Meta Commands

```ls
metric m:row_number.dg7a-jiz2 p:long l:"Row Number"

entity e:dg7a-jiz2 l:"Lost Property Contact Information" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/dg7a-jiz2

property e:dg7a-jiz2 t:meta.view v:id=dg7a-jiz2 v:category=Transportation v:averageRating=0 v:name="Lost Property Contact Information" v:attribution="Taxi and Limousine Commission (TLC)"

property e:dg7a-jiz2 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:dg7a-jiz2 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| license_number | name                 | type      | dmv_plate_number | base_name                   | base_license_number | base_phone_number | base_address                             | base_website | last_updated_date   | last_updated_time | 
| ============== | ==================== | ========= | ================ | =========================== | =================== | ================= | ======================================== | ============ | =================== | ================= | 
| 6A66           | TAN, TOMMY           | MEDALLION | 6A66B            |                             |                     |                   |                                          |              | 2017-04-20T00:00:00 | 13:25             | 
| 6A67           | HAVERLIN, WILLIAM J. | MEDALLION | 6A67A            | ALL TAXI MANAGEMENT INC     | 202                 | (718)361-0055     | 41-25 36 STREET LIC NY 11101             |              | 2017-04-20T00:00:00 | 13:25             | 
| 6A68           | CANDIA, ROLANDO      | MEDALLION | 6A68J            | TAXIFLEET MANAGEMENT LLC    | 307                 | (917)578-1803     | 54-11 QUEENS BOULEVARD WOODSIDE NY 11377 |              | 2017-04-20T00:00:00 | 13:25             | 
| 6A73           | CHANG, MICHAEL       | MEDALLION | 6A73H            | J T L MANAGEMENT INC        | 213                 | (718)392-7000     | 36-16 SKILLMAN AVENUE LIC NY 11101       |              | 2017-04-20T00:00:00 | 13:25             | 
| 6A76           | EDOUARD,JOSEPH,C     | MEDALLION | 6A76B            | MEDALLION MAINTENANCE INC.  | 217                 | (718)472-9000     | 11-38 44 ROAD LIC NY 11101               |              | 2017-04-20T00:00:00 | 13:25             | 
| 6A77           | CHEONG,HI,KAI        | MEDALLION | 6A77A            | MC GUINNESS MANAGEMENT CORP | 259                 | (718)389-4483     | 330 MC GUINNESS BOULEVARD BKLYN NY 11222 |              | 2017-04-20T00:00:00 | 13:25             | 
| 6A78           | SIU, WAI-MAN         | MEDALLION | 6A78A            |                             |                     |                   |                                          |              | 2017-04-20T00:00:00 | 13:25             | 
| 6A79           | LUCIEN,PAUL          | MEDALLION | 6A79A            |                             |                     |                   |                                          |              | 2017-04-20T00:00:00 | 13:25             | 
| 6A80           | MAN KAMLOI           | MEDALLION | 6A80A            | MC GUINNESS MANAGEMENT CORP | 259                 | (718)389-4483     | 330 MC GUINNESS BOULEVARD BKLYN NY 11222 |              | 2017-04-20T00:00:00 | 13:25             | 
| 6A81           | CHENG,RUEY-JONG      | MEDALLION | 6A81H            | L.I.C. TAXI MANAGEMENT INC. | 314                 | (718)470-0063     | 37-26 34 STREET LIC NY 11101             |              | 2017-04-20T00:00:00 | 13:25             | 
```