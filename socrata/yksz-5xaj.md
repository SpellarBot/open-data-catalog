# TLC Commuter Van Authorizations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tlc-commuter-van-authorizations-f0d30) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yksz-5xaj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yksz-5xaj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yksz-5xaj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yksz-5xaj |
| Name | TLC Commuter Van Authorizations |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | transportation, taxi, limousine, commuter, van, authorize, authorization |
| Created | 2011-08-26T19:59:10Z |
| Publication Date | 2011-08-26T19:59:10Z |

## Description

Spreadsheet of all TLC commuter van authorizations

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
series e:yksz-5xaj d:2011-08-26T12:59:12.000Z t:license_type="License Type" t:license_number="License Number" t:street_address=Street_Address t:name_of_licensee="Name of Licensee" t:telephone=Telephone t:alternative_name_of_licensee="Alternative Name of Licensee" m:row_number.yksz-5xaj=1

series e:yksz-5xaj d:2011-08-26T12:59:12.000Z t:license_type="TLC-licensed base (FHV, Commuter Van, or Para)" t:zip_code=11436 t:license_number=B80008 t:street_address="142-40 130 AVENUE" t:name_of_licensee="JAMZONE VAN SERVICE INC." t:telephone=718-323-2374 m:row_number.yksz-5xaj=2

series e:yksz-5xaj d:2011-08-26T12:59:12.000Z t:license_type="TLC-licensed base (FHV, Commuter Van, or Para)" t:zip_code=11422 t:license_number=B80012 t:street_address="258-27 147 AVENUE" t:name_of_licensee="MONTEGO VAN SERVICE INC." t:telephone=718-481-7715 m:row_number.yksz-5xaj=3
```

## Meta Commands

```ls
metric m:row_number.yksz-5xaj p:long l:"Row Number"

entity e:yksz-5xaj l:"TLC Commuter Van Authorizations" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/yksz-5xaj

property e:yksz-5xaj t:meta.view v:id=yksz-5xaj v:category=Transportation v:averageRating=0 v:name="TLC Commuter Van Authorizations" v:attribution="Taxi and Limousine Commission (TLC)"

property e:yksz-5xaj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yksz-5xaj t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | license_number | name_of_licensee              | alternative_name_of_licensee | street_address            | zip_code | telephone    | license_type                                   | 
| =========== | ============== | ============================= | ============================ | ========================= | ======== | ============ | ============================================== | 
| 1314363552  | License Number | Name of Licensee              | Alternative Name of Licensee | Street_Address            |          | Telephone    | License Type                                   | 
| 1314363552  | B80008         | JAMZONE VAN SERVICE INC.      |                              | 142-40 130 AVENUE         | 11436    | 718-323-2374 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314363552  | B80012         | MONTEGO VAN SERVICE INC.      |                              | 258-27 147 AVENUE         | 11422    | 718-481-7715 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314363552  | B80025         | DESTA TRANSPORTATION          |                              | 333 BEACH 32 STREET #15K  | 11691    | 718-471-3180 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314363552  | B80028         | CITY EXPRESS CORP             |                              | 391 ADELPHI STREET #E     | 11238    | 347-539-9482 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314363552  | B80039         | MARIO'S TRANSPORTATION INC.   |                              | 685 DEGRAW STREET APT. #1 | 11217    | 718-789-0113 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314363552  | B80054         | BROOKLYN VAN LINES INC        |                              | 1799 BEDFORD AVENUE 1D    | 11225    | 718-484-3681 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314363552  | B80061         | OZONE COMMUTER VAN SERVICE    |                              | 137-08 132 AVENUE         | 11436    | 718-529-6356 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314363552  | B80070         | EARLY BIRD TRANSPORTATION INC |                              | 750 MIDWOOD STREET        | 11553    | 718-217-2308 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314363552  | B80080         | PEBBLES TRANSPORTATION INC.   |                              | 3712 FLATLANDS AVENUE 2F  | 11234    | 516-354-3337 | TLC-licensed base (FHV, Commuter Van, or Para) | 
```