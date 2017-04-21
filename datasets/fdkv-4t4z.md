# NYC Zoning Tax Lot Database

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-zoning-tax-lot-database-1e7ec) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/fdkv-4t4z) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/fdkv-4t4z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/fdkv-4t4z/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | fdkv-4t4z |
| Name | NYC Zoning Tax Lot Database |
| Attribution | Department of City Planning (DCP) |
| Category | City Government |
| Tags | dcp, city planning, property, zoning, nyc zoning tax lot database |
| Created | 2013-07-29T17:55:31Z |
| Publication Date | 2017-03-09T14:31:06Z |

## Description

The Zoning Tax Lot Database is a comma?separated values (CSV) file format that contains up-to-date zoning by parcel. The Database includes the zoning designations and zoning map associated with a specific tax block and lot. The Database is updated on a monthly basis to reflect rezoning and corrections to the file.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | borough_code            | Borough Code            | text      | number      |
| Yes      | numeric metric | tax_block               | Tax Block               | number    | number      |
| Yes      | numeric metric | tax_lot                 | Tax Lot                 | number    | number      |
| Yes      | series tag     | zoning_district_1       | Zoning District 1       | text      | text        |
| Yes      | series tag     | zoning_district_2       | Zoning District 2       | text      | text        |
| Yes      | series tag     | zoning_district_3       | Zoning District 3       | text      | text        |
| Yes      | series tag     | zoning_district_4       | Zoning District 4       | text      | text        |
| Yes      | series tag     | commercial_overlay_1    | Commercial Overlay 1    | text      | text        |
| Yes      | series tag     | commercial_overlay_2    | Commercial Overlay 2    | text      | text        |
| Yes      | series tag     | special_district_1      | Special District 1      | text      | text        |
| Yes      | series tag     | special_district_2      | Special District 2      | text      | text        |
| Yes      | series tag     | special_district_3      | Special District 3      | text      | text        |
| Yes      | series tag     | limited_height_district | Limited Height District | text      | text        |
| Yes      | series tag     | zoning_map_number       | Zoning Map Number       | text      | text        |
| Yes      | series tag     | zoning_map_code         | Zoning Map Code         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fdkv-4t4z d:2017-03-09T14:26:48.000Z t:special_district_1=GI t:zoning_map_number=16A t:borough_code=1 t:zoning_district_1=R3-2 t:zoning_map_code=Y m:tax_block=1 m:tax_lot=10

series e:fdkv-4t4z d:2017-03-09T14:26:48.000Z t:zoning_map_number=16A t:borough_code=1 t:zoning_district_1=R3-2 t:zoning_map_code=Y m:tax_block=1 m:tax_lot=101

series e:fdkv-4t4z d:2017-03-09T14:26:48.000Z t:zoning_map_number=12B t:borough_code=1 t:zoning_district_1=R3-2 m:tax_block=1 m:tax_lot=201
```

## Meta Commands

```ls
metric m:tax_block p:integer l:"Tax Block" d:"The tax block that the tax lot is located in. This field contains a one to five digit tax block number which is preceded with leading blanks when the tax block is less than five digits. Each tax block is unique within a borough (see BOROUGH)." t:dataTypeName=number

metric m:tax_lot p:integer l:"Tax Lot" d:"The number of the tax lot. This field contains a one to four digit tax lot number which is preceded with leading blanks when the tax lot is less than four digits. Each tax lot is unique within a tax block (see TAX BLOCK)." t:dataTypeName=number

entity e:fdkv-4t4z l:"NYC Zoning Tax Lot Database" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/fdkv-4t4z

property e:fdkv-4t4z t:meta.view v:id=fdkv-4t4z v:category="City Government" v:averageRating=0 v:name="NYC Zoning Tax Lot Database" v:attribution="Department of City Planning (DCP)"

property e:fdkv-4t4z t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:fdkv-4t4z t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | borough_code | tax_block | tax_lot | zoning_district_1 | zoning_district_2 | zoning_district_3 | zoning_district_4 | commercial_overlay_1 | commercial_overlay_2 | special_district_1 | special_district_2 | special_district_3 | limited_height_district | zoning_map_number | zoning_map_code | 
| =========== | ============ | ========= | ======= | ================= | ================= | ================= | ================= | ==================== | ==================== | ================== | ================== | ================== | ======================= | ================= | =============== | 
| 1489069608  | 1            | 1         | 10      | R3-2              |                   |                   |                   |                      |                      | GI                 |                    |                    |                         | 16A               | Y               | 
| 1489069608  | 1            | 1         | 101     | R3-2              |                   |                   |                   |                      |                      |                    |                    |                    |                         | 16A               | Y               | 
| 1489069608  | 1            | 1         | 201     | R3-2              |                   |                   |                   |                      |                      |                    |                    |                    |                         | 12B               |                 | 
| 1489069608  | 1            | 1         | 301     | ZNA               |                   |                   |                   |                      |                      |                    |                    |                    |                         | 12B               |                 | 
| 1489069608  | 1            | 1         | 401     | ZNA               |                   |                   |                   |                      |                      |                    |                    |                    |                         | 12B               |                 | 
| 1489069608  | 1            | 2         | 1       | M1-4              |                   |                   |                   |                      |                      | LM                 |                    |                    |                         | 12B               |                 | 
| 1489069608  | 1            | 2         | 2       | C4-6              |                   |                   |                   |                      |                      | LM                 |                    |                    |                         | 12B               |                 | 
| 1489069608  | 1            | 2         | 3       | C4-6              |                   |                   |                   |                      |                      | LM                 |                    |                    |                         | 12B               |                 | 
| 1489069608  | 1            | 2         | 23      | C4-6              |                   |                   |                   |                      |                      | LM                 |                    |                    |                         | 12B               |                 | 
| 1489069608  | 1            | 3         | 1       | PARK              |                   |                   |                   |                      |                      |                    |                    |                    |                         | 12B               |                 | 
```