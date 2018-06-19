# City-Owned Land Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-owned-land-inventory-b8efd) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/aksk-kvfp) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/aksk-kvfp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/aksk-kvfp/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | aksk-kvfp |
| Name | City-Owned Land Inventory |
| Attribution | Chicago Department of Planning and Development |
| Category | Community & Economic Development |
| Tags | city-owned vacant land |
| Created | 2013-01-07T17:03:42Z |
| Publication Date | 2015-08-19T18:26:46Z |

## Description

Vacant property owned and managed by the City of Chicago Department of Planning and Development. Information provided in the database, or on the City?s website generally, should not be used as a substitute for title research, title evidence, title insurance, real estate tax exemption or payment status, environmental or geotechnical due diligence, or as a substitute for legal, accounting, real estate, business, tax or other professional advice. The City assumes no liability for any damages or loss of any kind that might arise from the reliance upon, use of, misuse of, or the inability to use the LIS database or the City?s web site and the materials contained on the website. The City also assumes no liability for improper or incorrect use of materials or information contained on its website. All materials that appear in the LIS database or on the City?s web site are distributed and transmitted "as is," without warranties of any kind, either express or implied as to the accuracy, reliability or completeness of any information, and subject to the terms and conditions stated in this disclaimer.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| No       | time           | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag     | digit_pin             | 14-Digit PIN #        | text      | text        |
| Yes      | series tag     | street_number         | Street Number         | text      | text        |
| No       |                | d                     | Dir.                  | text      | text        |
| Yes      | series tag     | street_name           | Street Name           | text      | text        |
| Yes      | series tag     | type                  | Type                  | text      | text        |
| Yes      | numeric metric | sq_ft                 | Sq. Ft.               | number    | number      |
| Yes      | series tag     | ward                  | Ward                  | text      | number      |
| Yes      | series tag     | community_area        | Community Area        | text      | text        |
| Yes      | series tag     | zoning_classification | Zoning Classification | text      | text        |
| Yes      | series tag     | tif_name_area         | TIF District          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = d
```

## Data Commands

```ls
series e:aksk-kvfp d:2015-08-19T11:22:35.000Z t:ward=39 t:tif_name_area=Lawrence/Kedzie t:digit_pin=13-11-403-058-0000 t:community_area="NORTH PARK" t:zoning_classification=B1-2 m:sq_ft=3735

series e:aksk-kvfp d:2015-08-19T11:22:35.000Z t:ward=45 t:tif_name_area="Portage Park" t:digit_pin=13-16-428-037-0000 t:community_area="PORTAGE PARK" t:zoning_classification=B1-1 m:sq_ft=37601

series e:aksk-kvfp d:2015-08-19T11:22:35.000Z t:ward=30 t:tif_name_area="NOT IN TIF" t:street_name=AVALON t:digit_pin=13-23-303-010-0000 t:community_area=AVONDALE t:street_number=3546 t:type=AVE t:zoning_classification=RS-3 m:sq_ft=1386
```

## Meta Commands

```ls
metric m:sq_ft p:integer l:"Sq. Ft." d:"Parcel Square Footage" t:dataTypeName=number

entity e:aksk-kvfp l:"City-Owned Land Inventory" t:attribution="Chicago Department of Planning and Development" t:url=https://data.cityofchicago.org/api/views/aksk-kvfp

property e:aksk-kvfp t:meta.view v:id=aksk-kvfp v:category="Community & Economic Development" v:attributionLink=http://www.cityofchicago.org/city/en/depts/dcd/supp_info/city-owned_land_inventory.html v:averageRating=0 v:name="City-Owned Land Inventory" v:attribution="Chicago Department of Planning and Development"

property e:aksk-kvfp t:meta.view.owner v:id=6kkk-fbsp v:screenName=16458a v:displayName=16458a

property e:aksk-kvfp t:meta.view.tableauthor v:id=6kkk-fbsp v:screenName=16458a v:roleName=publisher v:displayName=16458a
```

## Top Records

```ls
| :updated_at | digit_pin          | street_number | d | street_name | type | sq_ft | ward | community_area | zoning_classification | tif_name_area               | 
| =========== | ================== | ============= | = | =========== | ==== | ===== | ==== | ============== | ===================== | =========================== | 
| 1439983355  | 13-11-403-058-0000 |               |   |             |      | 3735  | 39   | NORTH PARK     | B1-2                  | Lawrence/Kedzie             | 
| 1439983355  | 13-16-428-037-0000 |               |   |             |      | 37601 | 45   | PORTAGE PARK   | B1-1                  | Portage Park                | 
| 1439983355  | 13-23-303-010-0000 | 3546          | N | AVALON      | AVE  | 1386  | 30   | AVONDALE       | RS-3                  | NOT IN TIF                  | 
| 1439983355  | 14-31-502-008-0000 | 2481          | N | WOOD        | ST   | 17104 | 32   | LINCOLN PARK   | M3-3                  | NOT IN TIF                  | 
| 1439983355  | 14-31-502-009-0000 | 2481          | N | WOOD        | ST   | 15554 | 32   | LINCOLN PARK   | M3-3                  | NOT IN TIF                  | 
| 1439983355  | 16-01-318-009-0000 | 892           | N | SACRAMENTO  | AVE  | 3796  | 26   | HUMBOLDT PARK  | RS-3/M1-2             | Kinzie Industrial Corridor  | 
| 1439983355  | 16-02-100-001-0000 | 3939          | W | NORTH AV    | AVE  | 690   | 26   | HUMBOLDT PARK  | PD 1205               | Pulaski Industrial Corridor | 
| 1439983355  | 16-02-100-002-0000 | 3939          | W | NORTH AV    | AVE  | 11487 | 26   | HUMBOLDT PARK  | PD 1205               | Pulaski Industrial Corridor | 
| 1439983355  | 16-02-100-003-0000 | 3939          | W | NORTH AV    | AVE  | 6000  | 26   | HUMBOLDT PARK  | PD 1205               | Pulaski Industrial Corridor | 
| 1439983355  | 16-02-100-004-0000 | 3939          | W | NORTH AV    | AVE  | 5999  | 26   | HUMBOLDT PARK  | PD 1205               | Pulaski Industrial Corridor | 
```