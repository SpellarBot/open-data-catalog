# Electronics Stores

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/electronics-stores-92826) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xszr-btpb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xszr-btpb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xszr-btpb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xszr-btpb |
| Name | Electronics Stores |
| Attribution | Department of Consumer Affairs (DCA) |
| Category | Business |
| Tags | retail, sale, sell, license, store, electronics, consumer affairs, dca |
| Created | 2010-11-03T17:15:45Z |
| Publication Date | 2013-06-27T19:55:56Z |

## Description

A list of electronics stores that have a current DCA license as of the run date.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | entity_type         | Entity Type         | text      | text        |
| Yes      | series tag  | license_number      | License Number      | text      | number      |
| Yes      | series tag  | entity_name         | Entity Name         | text      | text        |
| Yes      | series tag  | camis_trade_name    | Camis Trade Name    | text      | text        |
| No       |             | address_bldg        | Address Bldg        | text      | text        |
| Yes      | series tag  | address_street_name | Address Street Name | text      | text        |
| No       |             | address_location    | Address Location    | text      | text        |
| No       |             | address_city        | Address City        | text      | text        |
| No       |             | address_state       | Address State       | text      | text        |
| No       |             | address_zip_code    | Address Zip Code    | text      | number      |
| Yes      | series tag  | telephone_number    | Telephone Number    | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_bldg,address_location,address_city,address_state,address_zip_code
```

## Data Commands

```ls
series e:xszr-btpb d:2010-11-04T09:08:52.000Z t:entity_name="J P CELLULAR INC" t:telephone_number=7185322588 t:address_street_name="8 AVENUE" t:license_number=1314948 t:entity_type="ELECTRONICS STORE" m:row_number.xszr-btpb=1

series e:xszr-btpb d:2010-11-04T09:09:36.000Z t:entity_name="ROZKOS, INC" t:telephone_number=7188363200 t:address_street_name="5 AVENUE" t:license_number=1354421 t:entity_type="ELECTRONICS STORE" m:row_number.xszr-btpb=2

series e:xszr-btpb d:2010-11-03T10:17:42.000Z t:entity_name="A A RELIABLE TV SERVICE INC" t:telephone_number=7189871133 t:address_street_name="NEW DORP LANE" t:license_number=900885 t:entity_type="ELECTRONICS STORE" t:camis_trade_name="A A RELIABLE TV" m:row_number.xszr-btpb=3
```

## Meta Commands

```ls
metric m:row_number.xszr-btpb p:long l:"Row Number"

entity e:xszr-btpb l:"Electronics Stores" t:attribution="Department of Consumer Affairs (DCA)" t:url=https://data.cityofnewyork.us/api/views/xszr-btpb

property e:xszr-btpb t:meta.view v:id=xszr-btpb v:category=Business v:averageRating=0 v:name="Electronics Stores" v:attribution="Department of Consumer Affairs (DCA)"

property e:xszr-btpb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xszr-btpb t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | entity_type       | license_number | entity_name                   | camis_trade_name     | address_bldg | address_street_name   | address_location | address_city  | address_state | address_zip_code | telephone_number | 
| =========== | ================= | ============== | ============================= | ==================== | ============ | ===================== | ================ | ============= | ============= | ================ | ================ | 
| 1288861732  | ELECTRONICS STORE | 1314948        | J P CELLULAR INC              |                      | 5222         | 8 AVENUE              |                  | BROOKLYN      | NY            | 11220            | 7185322588       | 
| 1288861776  | ELECTRONICS STORE | 1354421        | ROZKOS, INC                   |                      | 8325         | 5 AVENUE              |                  | BROOKLYN      | NY            | 11209            | 7188363200       | 
| 1288779462  | ELECTRONICS STORE | 900885         | A A RELIABLE TV SERVICE INC   | A A RELIABLE TV      | 286          | NEW DORP LANE         |                  | STATEN ISLAND | NY            | 10306            | 7189871133       | 
| 1288779463  | ELECTRONICS STORE | 905045         | WARREN PROCESSING LABS LTD    | WARREN WORLD         | 2655         | NOSTRAND AVENUE       |                  | BROOKLYN      | NY            | 11210            | 7182580004       | 
| 1288779463  | ELECTRONICS STORE | 907700         | MARQUIS GIFT SHOP INC         |                      | 302          | BRIGHTON BEACH AVENUE |                  | BROOKLYN      | NY            | 11235            | 7189342010       | 
| 1288779464  | ELECTRONICS STORE | 926369         | TOP CONCOURSE ELECTRONICS INC |                      | 2486         | GRAND CONCOURSE       |                  | BRONX         | NY            | 10458            | 7182951836       | 
| 1288779464  | ELECTRONICS STORE | 934695         | M B N ELECTRONICS INC         |                      | 2271         | 65 STREET             |                  | BROOKLYN      | NY            | 11204            | 7182565221       | 
| 1288779464  | ELECTRONICS STORE | 941593         | YOO, SEUNG CHUL               | YOO SUNG ELECTRONICS | 56-10        | MARATHON PARKWAY      |                  | LITTLE NECK   | NY            | 11362            | 7182812893       | 
| 1288779465  | ELECTRONICS STORE | 950257         | ENG APPLIANCES CORP           |                      | 9            | BOWERY                |                  | NEW YORK      | NY            | 10002            | 2129255578       | 
| 1288779465  | ELECTRONICS STORE | 965538         | ROSS PHOTO & ELECTRONICS INC  |                      | 169A         | ROSS STREET           |                  | BROOKLYN      | NY            | 11211            | 7187821212       | 
```