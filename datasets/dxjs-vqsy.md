# Addresses with Units - Enterprise Addressing System (EAS)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/addresses-with-units-enterprise-addressing-system-eas-4a920) |
| Metadata | [Link](https://data.sfgov.org/api/views/dxjs-vqsy) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/dxjs-vqsy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/dxjs-vqsy/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | dxjs-vqsy |
| Name | Addresses with Units - Enterprise Addressing System (EAS) |
| Attribution | City and County of San Francisco |
| Category | Geographic Locations and Boundaries |
| Tags | eas, addresses, dbi, enterprise addressing system |
| Created | 2016-08-12T17:57:17Z |
| Publication Date | 2016-08-26T19:42:37Z |

## Description

All active addresses from the City's Enterprise Addressing System, including sub-addresses, such as units. Includes references to parcel and street centerline data. Updated nightly.See EAS Base Addresses for base addresses not including units.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                  | Data Type | Render Type |
| ======== | ============== | ==================== | ===================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at            | meta_data | meta_data   |
| Yes      | series tag     | eas_baseid           | EAS BaseID            | text      | number      |
| Yes      | series tag     | eas_subid            | EAS SubID             | text      | number      |
| Yes      | numeric metric | cnn                  | CNN                   | number    | text        |
| No       |                | address              | Address               | text      | text        |
| No       |                | address_number       | Address Number        | text      | text        |
| No       |                | address_number_suffx | Address Number Suffix | text      | text        |
| Yes      | series tag     | street_name          | Street Name           | text      | text        |
| Yes      | series tag     | street_type          | Street Type           | text      | text        |
| Yes      | series tag     | unit_number          | Unit Number           | text      | text        |
| Yes      | series tag     | zipcode              | Zipcode               | text      | text        |
| Yes      | series tag     | blk_lot              | Block Lot             | text      | text        |
| No       |                | longitude            | Longitude             | number    | number      |
| No       |                | latitude             | Latitude              | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,address_number,address_number_suffx,longitude,latitude
```

## Data Commands

```ls
series e:dxjs-vqsy d:2016-08-26T19:45:51.000Z t:eas_baseid=407758 t:blk_lot=6795C004 t:zipcode=94112 t:street_name="SANTA ROSA" t:street_type=AVE m:cnn=11590000

series e:dxjs-vqsy d:2016-08-26T19:45:51.000Z t:eas_baseid=285166 t:blk_lot=0557002 t:zipcode=94123 t:street_name=WEBSTER t:street_type=ST m:cnn=13553000

series e:dxjs-vqsy d:2016-08-26T19:45:51.000Z t:eas_baseid=275907 t:blk_lot=0026T892A t:zipcode=94109 t:street_name=HYDE t:street_type=ST m:cnn=7150000
```

## Meta Commands

```ls
metric m:cnn p:integer l:CNN t:dataTypeName=number

entity e:dxjs-vqsy l:"Addresses with Units - Enterprise Addressing System (EAS)" t:attribution="City and County of San Francisco" t:url=https://data.sfgov.org/api/views/dxjs-vqsy

property e:dxjs-vqsy t:meta.view v:id=dxjs-vqsy v:category="Geographic Locations and Boundaries" v:attributionLink=http://www.sfgov.org v:averageRating=0 v:name="Addresses with Units - Enterprise Addressing System (EAS)" v:attribution="City and County of San Francisco"

property e:dxjs-vqsy t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:dxjs-vqsy t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | eas_baseid | eas_subid | cnn      | address            | address_number | address_number_suffx | street_name | street_type | unit_number | zipcode | blk_lot   | longitude     | latitude    | 
| =========== | ========== | ========= | ======== | ================== | ============== | ==================== | =========== | =========== | =========== | ======= | ========= | ============= | =========== | 
| 1472240751  | 407758     |           | 11590000 | 136 SANTA ROSA AVE | 136            |                      | SANTA ROSA  | AVE         |             | 94112   | 6795C004  | -122.43642397 | 37.72722832 | 
| 1472240751  | 285166     |           | 13553000 | 2735 WEBSTER ST    | 2735           |                      | WEBSTER     | ST          |             | 94123   | 0557002   | -122.4338704  | 37.79590342 | 
| 1472240751  | 275907     |           | 7150000  | 2655 HYDE ST       | 2655           |                      | HYDE        | ST          |             | 94109   | 0026T892A | -122.42059646 | 37.80547351 | 
| 1472240751  | 436811     |           | 3318000  | 13 BUCARELI DR     | 13             |                      | BUCARELI    | DR          |             | 94132   | 7342001   | -122.47904176 | 37.71712903 | 
| 1472240751  | 366869     |           | 11353000 | 454 SAN BRUNO AVE  | 454            |                      | SAN BRUNO   | AVE         |             | 94110   | 3975001H  | -122.40570342 | 37.76384499 | 
| 1472240751  | 453203     |           | 4638000  | 1262 DE HARO ST    | 1262           |                      | DE HARO     | ST          |             | 94107   | 4217008   | -122.40085787 | 37.75379848 | 
| 1472240751  | 476995     |           | 6404000  | 1431 GRANT AVE     | 1431           |                      | GRANT       | AVE         | RESDL 2/F   | 94133   | 0116008   | -122.40764567 | 37.80006678 | 
| 1472240751  | 274996     |           | 8766101  | 2213 MARKET ST     | 2213           |                      | MARKET      | ST          |             | 94114   | 3559002   | -122.43140943 | 37.76508439 | 
| 1472240751  | 452276     |           | 731000   | 3080 16TH ST       | 3080           |                      | 16TH        | ST          |             | 94103   | 3554016   | -122.42159592 | 37.76517593 | 
| 1472240751  | 336045     |           | 1921000  | 2330 41ST AVE      | 2330           |                      | 41ST        | AVE         |             | 94116   | 2369024   | -122.49902133 | 37.74326787 | 
```