# Austin Water - List of Active Liquid Waste Haulers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-water-list-of-active-liquid-waste-haulers) |
| Metadata | [Link](https://data.austintexas.gov/api/views/pbam-er2r) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/pbam-er2r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/pbam-er2r/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | pbam-er2r |
| Name | Austin Water - List of Active Liquid Waste Haulers |
| Attribution | Austin Water |
| Category | Utility |
| Tags | aw, water, waste haulers |
| Created | 2015-08-12T19:37:43Z |
| Publication Date | 2015-08-12T20:50:16Z |

## Description

List of active liquid waste haulers currently permitted by the City of Austin under the Liquid Waste Haulers Program.

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                                             | Data Type | Render Type |
| ======== | ============== | ================================================ | ================================================ | ========= | =========== |
| No       | time           | :updated_at                                      | updated_at                                       | meta_data | meta_data   |
| Yes      | series tag     | business_name                                    | BUSINESS_NAME                                    | text      | text        |
| No       |                | address_1                                        | ADDRESS_1                                        | text      | text        |
| No       |                | address_2                                        | ADDRESS_2                                        | text      | text        |
| Yes      | series tag     | city                                             | CITY                                             | text      | text        |
| Yes      | series tag     | zip                                              | ZIP                                              | text      | text        |
| Yes      | numeric metric | phone                                            | PHONE                                            | number    | text        |
| Yes      | series tag     | phone_ext                                        | PHONE_EXT                                        | text      | text        |
| Yes      | series tag     | austin_water_list_of_active_liquid_waste_haulers | Austin Water List of Active Liquid Waste Haulers | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_1,address_2
```

## Data Commands

```ls
series e:pbam-er2r d:2015-08-12T12:37:48.000Z t:business_name="ALL AMERICAN WASTEWATER SOLUTIONS, LLC (ALL AMERICAN SEPTIC SOLUTIONS, ALL SEPTIC CHECK)" t:zip=786523062 t:city=MANCHACA m:phone=5122823889

series e:pbam-er2r d:2015-08-12T12:37:48.000Z t:business_name="ALL CEN-TEX SEPTIC & DRAIN SERVICE, INC (CENTEX SEPTIC SERVICES, CEN-TEX PORTABLE TOILETS)" t:zip=786300545 t:city="CEDAR PARK" m:phone=5122584000

series e:pbam-er2r d:2015-08-12T12:37:48.000Z t:business_name="ALL POINTS INSPECTION SERVICES, INC." t:zip=78653 t:city=WEBBERVILLE m:phone=5122725056
```

## Meta Commands

```ls
metric m:phone p:long l:PHONE t:dataTypeName=number

entity e:pbam-er2r l:"Austin Water - List of Active Liquid Waste Haulers" t:attribution="Austin Water" t:url=https://data.austintexas.gov/api/views/pbam-er2r

property e:pbam-er2r t:meta.view v:id=pbam-er2r v:category=Utility v:attributionLink=http://www.austintexas.gov/department/water v:averageRating=0 v:name="Austin Water - List of Active Liquid Waste Haulers" v:attribution="Austin Water"

property e:pbam-er2r t:meta.view.license v:name="Public Domain"

property e:pbam-er2r t:meta.view.owner v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:displayName="Patricia Genty Andrade"

property e:pbam-er2r t:meta.view.tableauthor v:id=4786-56ku v:screenName="Patricia Genty Andrade" v:roleName=editor v:displayName="Patricia Genty Andrade"
```

## Top Records

```ls
| :updated_at | business_name                                                                              | address_1             | address_2 | city        | zip       | phone      | phone_ext | austin_water_list_of_active_liquid_waste_haulers | 
| =========== | ========================================================================================== | ===================== | ========= | =========== | ========= | ========== | ========= | ================================================ | 
| 1439383068  | ALL AMERICAN WASTEWATER SOLUTIONS, LLC (ALL AMERICAN SEPTIC SOLUTIONS, ALL SEPTIC CHECK)   | 3801 BLISS SPILLAR RD |           | MANCHACA    | 786523062 | 5122823889 |           |                                                  | 
| 1439383068  | ALL CEN-TEX SEPTIC & DRAIN SERVICE, INC (CENTEX SEPTIC SERVICES, CEN-TEX PORTABLE TOILETS) | P.O. BOX 545          |           | CEDAR PARK  | 786300545 | 5122584000 |           |                                                  | 
| 1439383068  | ALL POINTS INSPECTION SERVICES, INC.                                                       | 19139 FM 969          |           | WEBBERVILLE | 78653     | 5122725056 |           |                                                  | 
| 1439383068  | ANRIGE, INC. (A CLEAN PORTOCO)                                                             | P O BOX 531607        |           | HARLINGEN   | 785531607 | 9562301370 |           |                                                  | 
| 1439383068  | BARBARA J. THOMPSON (AFFORDABLE SEPTIC)                                                    | P O BOX 2535          |           | BASTROP     | 786028002 | 5123851600 |           |                                                  | 
| 1439383068  | C. SELLMAN ENTERPRISES, INC. (NATIONAL LIQUIDS, INC.)                                      | P.O. BOX 1377         |           | BUDA        | 786101377 | 5123120002 |           |                                                  | 
| 1439383068  | CEN-TEX WASTE WATER, INC.                                                                  | PO BOX 1139           |           | KINGSLAND   | 786391139 | 3253884044 |           |                                                  | 
| 1439383068  | CITY OF AUSTIN, AUSTIN RESOURCE RECOVERY (FM 812 TO TODD LANE)                             | PO BOX 1088           |           | AUSTIN      | 787671088 | 5122433325 |           |                                                  | 
| 1439383068  | CITY OF AUSTIN, AWU (REMOTE TREATMENT FACILITIES/LIFT STATIONS)                            |                       |           |             |           |            |           |                                                  | 
| 1439383068  | CTJ VACUUM SERVICES                                                                        | 5206 PENFIELD LN.     |           | HOUSTON     | 77021     | 2817013892 |           |                                                  | 
```