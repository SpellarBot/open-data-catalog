# Nursery Growers and Greenhouse

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nursery-growers-and-greenhouse) |
| Metadata | [Link](https://data.ny.gov/api/views/qke7-n4w8) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/qke7-n4w8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/qke7-n4w8/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | qke7-n4w8 |
| Name | Nursery Growers and Greenhouse |
| Attribution | New York State Department of Agriculture and Markets |
| Category | Economic Development |
| Tags | nursery grower, greenhouse, license |
| Created | 2013-02-26T16:34:12Z |
| Publication Date | 2014-12-17T18:20:14Z |

## Description

A listing of all certified nursery growers and greenhouses which are licensed by the Department of Agriculture and Markets. Licensing of nursery growers and greenhouses is intended to prevent the introduction of injurious insects, noxious weeds, and plant diseases into the state.

## Columns

```ls
| Included | Schema Type | Field Name            | Name            | Data Type | Render Type |
| ======== | =========== | ===================== | =============== | ========= | =========== |
| No       | time        | :updated_at           | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | county                | County          | text      | text        |
| Yes      | series tag  | license_number        | License Number  | text      | text        |
| Yes      | series tag  | operation_type        | Operation Type  | text      | text        |
| Yes      | series tag  | nursery_size          | Nursery Size    | text      | text        |
| Yes      | series tag  | greenhouse_size       | Greenhouse Size | text      | text        |
| Yes      | series tag  | trade_name            | Trade Name      | text      | text        |
| Yes      | series tag  | owner_name            | Owner Name      | text      | text        |
| Yes      | series tag  | business_phone        | Business Phone  | text      | text        |
| Yes      | series tag  | street_address_number | Street Number   | text      | text        |
| Yes      | series tag  | street_name           | Street Name     | text      | text        |
| No       |             | address_line_2        | Address Line 2  | text      | text        |
| No       |             | address_line_3        | Address Line 3  | text      | text        |
| Yes      | series tag  | city                  | City            | text      | text        |
| Yes      | series tag  | state                 | State           | text      | text        |
| Yes      | series tag  | zip_code              | Zip Code        | text      | text        |
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
series e:qke7-n4w8 d:2014-10-02T08:16:42.000Z t:owner_name="HEILMAN ELAINE" t:zip_code=12067 t:license_number=14011 t:street_name="SUNSET VISTA LANE" t:state=NY t:operation_type="Combined Nursery and Greenhouse" t:nursery_size="11-100 Acres" t:city="FEURA BUSH" t:business_phone=518-768-2420 t:county=ALBANY t:trade_name="COUNTRY FLOWERS" t:street_address_number=9 t:greenhouse_size="2,001-20,000 SQFT OF GLASS" m:row_number.qke7-n4w8=1

series e:qke7-n4w8 d:2014-10-02T08:16:45.000Z t:business_phone=518-869-5626 t:zip_code=12309 t:owner_name="DEFORGE FRM&GREENHOUSES INC" t:county=ALBANY t:license_number=10542 t:street_name="VLY ROAD" t:state=NY t:trade_name="DEFORGE FARM & GREENHOUSE INC" t:street_address_number=216 t:operation_type="Greenhouse Stock Only" t:greenhouse_size="2,001-20,000 SQFT OF GLASS" t:city=SCHENECTADY m:row_number.qke7-n4w8=2

series e:qke7-n4w8 d:2014-10-02T08:16:45.000Z t:business_phone=518-5269101 t:zip_code=12186 t:owner_name="VANCLEVE ANDREW" t:county=ALBANY t:license_number=16402 t:street_name="PLEASANT STREET" t:state=NY t:trade_name="AZALEA HOUSE FLOWERING" t:street_address_number=2 t:operation_type="Nursery Stock Only" t:nursery_size="10 Acres or Less" t:city=VOORHEESVILLE m:row_number.qke7-n4w8=3
```

## Meta Commands

```ls
metric m:row_number.qke7-n4w8 p:long l:"Row Number"

entity e:qke7-n4w8 l:"Nursery Growers and Greenhouse" t:attribution="New York State Department of Agriculture and Markets" t:url=https://data.ny.gov/api/views/qke7-n4w8

property e:qke7-n4w8 t:meta.view v:id=qke7-n4w8 v:category="Economic Development" v:attributionLink=http://www.agriculture.ny.gov/PI/cover.htm v:averageRating=0 v:name="Nursery Growers and Greenhouse" v:attribution="New York State Department of Agriculture and Markets"

property e:qke7-n4w8 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:qke7-n4w8 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:qke7-n4w8 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | county | license_number | operation_type                  | nursery_size     | greenhouse_size             | trade_name                        | owner_name                  | business_phone | street_address_number | street_name          | address_line_2 | address_line_3 | city          | state | zip_code | 
| =========== | ====== | ============== | =============================== | ================ | =========================== | ================================= | =========================== | ============== | ===================== | ==================== | ============== | ============== | ============= | ===== | ======== | 
| 1412237802  | ALBANY | 14011          | Combined Nursery and Greenhouse | 11-100 Acres     | 2,001-20,000 SQFT OF GLASS  | COUNTRY FLOWERS                   | HEILMAN ELAINE              | 518-768-2420   | 9                     | SUNSET VISTA LANE    |                |                | FEURA BUSH    | NY    | 12067    | 
| 1412237805  | ALBANY | 10542          | Greenhouse Stock Only           |                  | 2,001-20,000 SQFT OF GLASS  | DEFORGE FARM & GREENHOUSE INC     | DEFORGE FRM&GREENHOUSES INC | 518-869-5626   | 216                   | VLY ROAD             |                |                | SCHENECTADY   | NY    | 12309    | 
| 1412237805  | ALBANY | 16402          | Nursery Stock Only              | 10 Acres or Less |                             | AZALEA HOUSE FLOWERING            | VANCLEVE ANDREW             | 518-5269101    | 2                     | PLEASANT STREET      | SHRUB FARM     |                | VOORHEESVILLE | NY    | 12186    | 
| 1412237808  | ALBANY | 11252          | Greenhouse Stock Only           |                  | 2,000 SqFt of Glass or Less | DIBACCO RICHARD                   | DIBACCO RICHARD             | 518-273-9321   | 14                    | GUY LANE             |                |                | WATERVLIET    | NY    | 12189    | 
| 1412237812  | ALBANY | 16362          | Greenhouse Stock Only           |                  | 2,000 SqFt of Glass or Less | BUTTERMILK FALLS ORGANIC FARM LLC | BRITT JANET                 | 518-677-2287   | 484                   | CENTRAL AVENUE       |                |                | ALBANY        | NY    | 12208    | 
| 1412237825  | ALBANY | 643795         |                                 |                  |                             | DIBACCO RICHARD                   | DIBACCO RICHARD             | 518-273-9321   | 14                    | GUY LANE             |                |                | WATERVLIET    | NY    | 12189    | 
| 1412237827  | ALBANY | 643609         |                                 |                  |                             | EIGHT MILE CREEK FARM VEHICLE     | MCSWEENEY PAMELA & JAMES    | 518-966-5468   | 40                    | JOHNNY CAKE HILL ROD |                |                | WESTERLO      | NY    | 12193    | 
| 1412237830  | ALBANY | 13164          | Greenhouse Stock Only           | 10 Acres or Less |                             | BRIZZELL'S FLOWERS                | BRIZZELL WILLIAM A SR       | 518-783-3131   | 562                   | LOUDON ROAD          | POB 33         |                | NEWTONVILLE   | NY    | 12128    | 
| 1412237833  | ALBANY | 16172          | Nursery Stock Only              | 10 Acres or Less |                             | AZALEA HOUSE FLOWERING            | VANCLEVE ANDREW             | 518-5269101    | 40                    | VOORHEESVILLE RD     | SHRUB FARM     |                | VOORHEESVILLE | NY    | 12186    | 
| 1412237836  | ALBANY | 10084          | Combined Nursery and Greenhouse | 10 Acres or Less | 2,001-20,000 SQFT OF GLASS  | ALTAMONT ORCHARDS INC             | ALTAMONT ORCHARDS INC       | 518-861-6515   | 6654                  | DUNNSVILLE ROAD      |                |                | ALTAMONT      | NY    | 12009    | 
```