# Certified Plant Dealers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/certified-plant-dealers) |
| Metadata | [Link](https://data.ny.gov/api/views/2ssy-s6ns) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/2ssy-s6ns/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/2ssy-s6ns/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 2ssy-s6ns |
| Name | Certified Plant Dealers |
| Attribution | New York State Department of Agriculture and Markets |
| Category | Economic Development |
| Tags | plant dealer, plant disease, license |
| Created | 2013-02-26T17:10:49Z |
| Publication Date | 2016-02-05T23:23:50Z |

## Description

A listing of all certified plant dealers which are licensed by the Department of Agriculture and Markets. Licensing of plant dealers is intended to prevent the introduction of injurious insects, noxious weeds, and plant diseases into the state.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | county         | County         | text      | text        |
| Yes      | series tag  | license_number | License Number | text      | text        |
| Yes      | series tag  | operation_type | Operation Type | text      | text        |
| Yes      | series tag  | trade_name     | Trade Name     | text      | text        |
| Yes      | series tag  | owner_name     | Owner Name     | text      | text        |
| Yes      | series tag  | street_number  | Street Number  | text      | text        |
| Yes      | series tag  | street_name    | Street Name    | text      | text        |
| No       |             | address_line_2 | Address Line 2 | text      | text        |
| No       |             | address_line_3 | Address Line 3 | text      | text        |
| Yes      | series tag  | city           | City           | text      | text        |
| Yes      | series tag  | state          | State          | text      | text        |
| Yes      | series tag  | zip_code       | Zip Code       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_line_2,address_line_3
```

## Data Commands

```ls
series e:2ssy-s6ns d:2016-02-05T15:03:48.000Z t:zip_code=122042801 t:owner_name="RITE AID OF NEW YORK INC" t:county=ALBANY t:license_number=18952 t:street_name=BROADWAY t:state=NY t:trade_name="RITE AID #0162" t:street_number=444-A t:operation_type="Drug Store" t:city=ALBANY m:row_number.2ssy-s6ns=1

series e:2ssy-s6ns d:2016-02-05T15:03:48.000Z t:zip_code=121102106 t:owner_name="PRICE CHOPPER OPERATING CO INC" t:county=ALBANY t:license_number=10446 t:street_name="NEW LOUDON PLZ" t:state=NY t:trade_name="PRICE CHOPPER #0138" t:street_number=873 t:operation_type="Grocery Store" t:city=LATHAM m:row_number.2ssy-s6ns=2

series e:2ssy-s6ns d:2016-02-05T15:03:49.000Z t:zip_code=12206 t:owner_name="PRICE CHOPPER OPERATING CO INC" t:county=ALBANY t:license_number=10347 t:street_name="CENTRAL AVENUE-WESTGATE PLAZA" t:state=NY t:trade_name="PRICE CHOPPER #0133" t:street_number=911 t:operation_type="Grocery Store" t:city=ALBANY m:row_number.2ssy-s6ns=3
```

## Meta Commands

```ls
metric m:row_number.2ssy-s6ns p:long l:"Row Number"

entity e:2ssy-s6ns l:"Certified Plant Dealers" t:attribution="New York State Department of Agriculture and Markets" t:url=https://data.ny.gov/api/views/2ssy-s6ns

property e:2ssy-s6ns t:meta.view v:id=2ssy-s6ns v:category="Economic Development" v:attributionLink=http://www.agriculture.ny.gov/PI/cover.htm v:averageRating=0 v:name="Certified Plant Dealers" v:attribution="New York State Department of Agriculture and Markets"

property e:2ssy-s6ns t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:2ssy-s6ns t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:2ssy-s6ns t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | county | license_number | operation_type | trade_name             | owner_name                     | street_number | street_name                   | address_line_2 | address_line_3 | city           | state | zip_code  | 
| =========== | ====== | ============== | ============== | ====================== | ============================== | ============= | ============================= | ============== | ============== | ============== | ===== | ========= | 
| 1454684628  | ALBANY | 18952          | Drug Store     | RITE AID #0162         | RITE AID OF NEW YORK INC       | 444-A         | BROADWAY                      |                |                | ALBANY         | NY    | 122042801 | 
| 1454684628  | ALBANY | 10446          | Grocery Store  | PRICE CHOPPER #0138    | PRICE CHOPPER OPERATING CO INC | 873           | NEW LOUDON PLZ                |                |                | LATHAM         | NY    | 121102106 | 
| 1454684629  | ALBANY | 10347          | Grocery Store  | PRICE CHOPPER #0133    | PRICE CHOPPER OPERATING CO INC | 911           | CENTRAL AVENUE-WESTGATE PLAZA |                |                | ALBANY         | NY    | 12206     | 
| 1454684629  | ALBANY | 10486          | Drug Store     | WALGREENS #9154        | WALGREEN EASTERN COMPANY INC   | 1850          | CENTRAL AVENUE                |                |                | ALBANY         | NY    | 122054703 | 
| 1454684629  | ALBANY | 13917          | Other          | ROLLING MEADOWS FARM   | GLORIOSO JAMES A               | 232           | KNOWLES ROAD                  |                |                | PRESTON HOLLOW | NY    | 124691713 | 
| 1454684629  | ALBANY | 18986          | Drug Store     | RITE AID #4928         | RITE AID OF NEW YORK INC       | 1863          | CENTRAL AVENUE                |                |                | COLONIE        | NY    | 122054221 | 
| 1454684629  | ALBANY | 18985          | Drug Store     | RITE AID #4805         | RITE AID OF NEW YORK INC       | 2463          | US ROUTE 9W                   |                |                | RAVENA         | NY    | 121432610 | 
| 1454684629  | ALBANY | 18977          | Drug Store     | RITE AID #3334         | RITE AID OF NEW YORK INC       | 310           | SOUTH PEARL STREET            |                |                | ALBANY         | NY    | 122021940 | 
| 1454684629  | ALBANY | 18976          | Drug Store     | RITE AID #3331         | RITE AID OF NEW YORK INC       | 308           | ONTARIO STREET                |                |                | COHOES         | NY    | 120472847 | 
| 1454684629  | ALBANY | 12504          | Roadside Stand | DICAPRIO'S FARM MARKET | JOE DICAPRIO                   | 3651          | ALBANY CARMAN ROAD            |                |                | SCHENECTADY    | NY    | 12303     | 
```