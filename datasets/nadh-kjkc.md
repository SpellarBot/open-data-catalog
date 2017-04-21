# TLC Community Car Service Bases

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tlc-community-car-service-bases-1958d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/nadh-kjkc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/nadh-kjkc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/nadh-kjkc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | nadh-kjkc |
| Name | TLC Community Car Service Bases |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | jobs and economic mobility, transportation, taxi, limousine, community, car, vehicle, service, base |
| Created | 2011-08-26T20:04:57Z |
| Publication Date | 2011-08-26T20:04:57Z |

## Description

Spreadsheet of all TLC community car service bases

## Columns

```ls
| Included | Schema Type | Field Name                   | Name                         | Data Type | Render Type |
| ======== | =========== | ============================ | ============================ | ========= | =========== |
| No       | time        | :updated_at                  | updated_at                   | meta_data | meta_data   |
| Yes      | series tag  | license_number               | License Number               | text      | text        |
| Yes      | series tag  | name_of_licensee             | Name of Licensee             | text      | text        |
| Yes      | series tag  | alternative_name_of_licensee | Alternative Name of Licensee | text      | text        |
| Yes      | series tag  | street_address               | Street_Address               | text      | text        |
| Yes      | series tag  | zip_code                     | Zip_Code                     | text      | number      |
| Yes      | series tag  | telephone                    | Telephone                    | text      | text        |
| Yes      | series tag  | license_type                 | License Type                 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nadh-kjkc d:2011-08-26T13:04:59.000Z t:license_type="License Type" t:license_number="License Number" t:street_address=Street_Address t:name_of_licensee="Name of Licensee" t:telephone=Telephone t:alternative_name_of_licensee="Alternative Name of Licensee" m:row_number.nadh-kjkc=1

series e:nadh-kjkc d:2011-08-26T13:04:59.000Z t:license_type="TLC-licensed base (FHV, Commuter Van, or Para)" t:zip_code=11379 t:license_number=B00008 t:street_address="69-90 73 PLACE" t:name_of_licensee="T-D MAINTENANCE CORP" t:telephone=718-456-1111 t:alternative_name_of_licensee="FOUR ONES CAR SERVICE" m:row_number.nadh-kjkc=2

series e:nadh-kjkc d:2011-08-26T13:04:59.000Z t:license_type="TLC-licensed base (FHV, Commuter Van, or Para)" t:zip_code=11379 t:license_number=B00009 t:street_address="69-90 73 PLACE" t:name_of_licensee="T-D MAINTENANCE" t:telephone=718-456-1111 t:alternative_name_of_licensee="FOUR ONES CAR SERVICE" m:row_number.nadh-kjkc=3
```

## Meta Commands

```ls
metric m:row_number.nadh-kjkc p:long l:"Row Number"

entity e:nadh-kjkc l:"TLC Community Car Service Bases" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/nadh-kjkc

property e:nadh-kjkc t:meta.view v:id=nadh-kjkc v:category=Transportation v:averageRating=0 v:name="TLC Community Car Service Bases" v:attribution="Taxi and Limousine Commission (TLC)"

property e:nadh-kjkc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:nadh-kjkc t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| :updated_at | license_number | name_of_licensee                      | alternative_name_of_licensee | street_address              | zip_code | telephone    | license_type                                   | 
| =========== | ============== | ===================================== | ============================ | =========================== | ======== | ============ | ============================================== | 
| 1314363899  | License Number | Name of Licensee                      | Alternative Name of Licensee | Street_Address              |          | Telephone    | License Type                                   | 
| 1314363899  | B00008         | T-D MAINTENANCE CORP                  | FOUR ONES CAR SERVICE        | 69-90 73 PLACE              | 11379    | 718-456-1111 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314363899  | B00009         | T-D MAINTENANCE                       | FOUR ONES CAR SERVICE        | 69-90 73 PLACE              | 11379    | 718-456-1111 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314363899  | B00021         | MEXICANA HIGH CLASS INC.              | CAPITAL CAR SERVICE          | 52-02 103 STREET            | 11368    | 718-592-1200 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314363899  | B00023         | F.J.A. LIVERY CORP                    | VILLAGE CAR SERVICE          | 3747A VICTORY BOULEVARD     | 10314    | 718-698-4493 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314363899  | B00029         | COMMUNITY CAR SVC CORP                |                              | 1322 EAST GUN HILL ROAD     | 10469    | 718-881-0708 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314363899  | B00030         | TREMONT DISPATCHING CORP              |                              | 3552 EAST TREMONT AVENUE    | 10465    | 718-822-7777 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314363899  | B00031         | QUEENS VILLAGE INC.                   |                              | 96-23 SPRINGFIELD BOULEVARD | 11429    | 718-776-8787 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314363899  | B00037         | TRANSP UNLIMITED C/S                  |                              | 1226 NOSTRAND AVENUE        | 11225    | 718-363-1000 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314363899  | B00041         | COMMUNITY CAR SERVICE PRISCILLA CORP. |                              | 9-17 WYCKOFF AVENUE         | 11385    | 718-366-8800 | TLC-licensed base (FHV, Commuter Van, or Para) | 
```