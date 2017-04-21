# Manufactured Home Park Registrations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/manufactured-home-park-registrations) |
| Metadata | [Link](https://data.ny.gov/api/views/sxi2-m23m) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/sxi2-m23m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/sxi2-m23m/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | sxi2-m23m |
| Name | Manufactured Home Park Registrations |
| Attribution | New York State Division of Housing and Community Renewal |
| Category | Economic Development |
| Tags | manufactured homes, mobile homes, manufactured home parks |
| Created | 2014-04-07T12:44:22Z |
| Publication Date | 2017-02-17T17:50:47Z |

## Description

This dataset captures the park name, address, and county in which a maufactured home park is located; the number of site capacity and number of occupied sites; and the name and contact number for the park owner/operator. New York State Homes and Community Renewal?s (HCR) Division of Housing and Community Renewal (DHCR) oversees the registration of these parks in accordance with NYS Real Property Law Section 233 sub-section (v.) which requires owners of manufactured home parks with three or more homes register their park with DHCR.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | park_registration_year     | Park Registration Year     | number    | number      |
| Yes      | series tag     | county                     | County                     | text      | text        |
| Yes      | series tag     | facility_id_number         | Facility ID Number         | text      | number      |
| Yes      | series tag     | facility_name              | Facility Name              | text      | text        |
| No       |                | facility_address           | Facility Address           | text      | text        |
| Yes      | series tag     | facility_municipality      | Facility Municipality      | text      | text        |
| Yes      | numeric metric | site_capacity              | Site Capacity              | number    | number      |
| Yes      | numeric metric | sites_occupancy            | Sites Occupancy            | number    | number      |
| Yes      | series tag     | park_owner_1               | Park Owner 1               | text      | text        |
| Yes      | series tag     | park_owner_2               | Park Owner 2               | text      | text        |
| Yes      | series tag     | park_owner_3               | Park Owner 3               | text      | text        |
| Yes      | series tag     | park_owner_4               | Park Owner 4               | text      | text        |
| Yes      | series tag     | park_owner_5               | Park Owner 5               | text      | text        |
| Yes      | series tag     | park_owner_6               | Park Owner 6               | text      | text        |
| Yes      | series tag     | park_owner_7               | Park Owner 7               | text      | text        |
| Yes      | series tag     | owner_or_operator_name     | Owner or Operator Name     | text      | text        |
| No       |                | owner_or_operator_address  | Owner or Operator Address  | text      | text        |
| Yes      | series tag     | owner_or_operator_city     | Owner or Operator City     | text      | text        |
| Yes      | series tag     | owner_or_operator_state    | Owner or Operator State    | text      | text        |
| Yes      | series tag     | owner_or_operator_zip_code | Owner or Operator ZIP Code | text      | text        |
| Yes      | series tag     | owner_or_operator_phone    | Owner or Operator Phone    | text      | number      |
| Yes      | series tag     | home_setup                 | Home Setup                 | text      | text        |
| Yes      | series tag     | tiedown                    | Tiedown                    | text      | text        |
| Yes      | series tag     | home_sales                 | Home Sales                 | text      | text        |
| Yes      | series tag     | home_maintenance           | Home Maintenance           | text      | text        |
| Yes      | series tag     | ground_maintenance         | Ground Maintenance         | text      | text        |
| Yes      | series tag     | road_maintenance           | Road Maintenance           | text      | text        |
| Yes      | series tag     | storage                    | Storage                    | text      | text        |
| Yes      | series tag     | playground                 | Playground                 | text      | text        |
| Yes      | series tag     | parking_space              | Parking Space              | text      | text        |
| Yes      | series tag     | water                      | Water                      | text      | text        |
| Yes      | series tag     | sewage                     | Sewage                     | text      | text        |
| Yes      | series tag     | beach                      | Beach                      | text      | text        |
| Yes      | series tag     | pool                       | Pool                       | text      | text        |
| Yes      | series tag     | garbage_trash              | Garbage/Trash              | text      | text        |
| Yes      | series tag     | security_guard             | Security Guard             | text      | text        |
| Yes      | series tag     | food_store                 | Food/Store                 | text      | text        |
| Yes      | series tag     | clubhouse                  | Clubhouse                  | text      | text        |
| Yes      | series tag     | laundry_room               | Laundry Room               | text      | text        |
| Yes      | series tag     | electrical                 | Electrical                 | text      | text        |
| Yes      | series tag     | natural_gas                | Natural Gas                | text      | text        |
| Yes      | series tag     | propane_gas                | Propane Gas                | text      | text        |
| Yes      | series tag     | tv_cable_hookup            | TV/Cable Hookup            | text      | text        |
| Yes      | series tag     | other_park_amenity_1       | Other Park Amenity 1       | text      | text        |
| Yes      | series tag     | other_park_amenity_2       | Other Park Amenity 2       | text      | text        |
| Yes      | series tag     | other_park_amenity_3       | Other Park Amenity 3       | text      | text        |
| Yes      | series tag     | other_park_amenity_4       | Other Park Amenity 4       | text      | text        |
| Yes      | series tag     | other_park_amenity_5       | Other Park Amenity 5       | text      | text        |
```

## Time Field

```ls
Value = park_registration_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = facility_address,owner_or_operator_address
```

## Data Commands

```ls
series e:sxi2-m23m d:2016-01-01T00:00:00.000Z t:other_park_amenity_2=N t:other_park_amenity_3=N t:food_store=N t:other_park_amenity_1=N t:owner_or_operator_phone=5183554461 t:clubhouse=N t:beach=N t:other_park_amenity_4=N t:home_setup=N t:other_park_amenity_5=N t:facility_name="GREEN ACRES" t:pool=N t:owner_or_operator_name="RAYMOND M. FLOWER" t:tiedown=N t:ground_maintenance=N t:facility_municipality=KNOX t:owner_or_operator_state=NY t:home_sales=N t:water=Y t:playground=N t:owner_or_operator_zip_code=12306 t:parking_space=Y t:sewage=Y t:home_maintenance=N t:road_maintenance=Y t:propane_gas=Y t:security_guard=N t:natural_gas=N t:garbage_trash=Y t:electrical=Y t:county=ALBANY t:owner_or_operator_city=SCHENECTADY t:laundry_room=N t:tv_cable_hookup=Y t:facility_id_number=1 t:storage=N m:sites_occupancy=25 m:site_capacity=25

series e:sxi2-m23m d:2015-01-01T00:00:00.000Z t:other_park_amenity_2=N t:other_park_amenity_3=N t:food_store=N t:other_park_amenity_1=N t:owner_or_operator_phone=5183554461 t:clubhouse=N t:beach=N t:other_park_amenity_4=N t:home_setup=N t:other_park_amenity_5=N t:facility_name="GREEN ACRES" t:pool=N t:owner_or_operator_name="RAYMOND M. FLOWER" t:tiedown=N t:ground_maintenance=N t:facility_municipality=KNOX t:owner_or_operator_state=NY t:home_sales=N t:water=Y t:playground=N t:owner_or_operator_zip_code=12306 t:parking_space=Y t:sewage=Y t:home_maintenance=N t:road_maintenance=Y t:propane_gas=Y t:security_guard=N t:natural_gas=N t:garbage_trash=Y t:electrical=Y t:county=ALBANY t:owner_or_operator_city=SCHENECTADY t:laundry_room=N t:tv_cable_hookup=Y t:facility_id_number=1 t:storage=N m:sites_occupancy=25 m:site_capacity=25

series e:sxi2-m23m d:2014-01-01T00:00:00.000Z t:other_park_amenity_2=N t:other_park_amenity_3=N t:food_store=N t:other_park_amenity_1=N t:owner_or_operator_phone=5183554461 t:clubhouse=N t:beach=N t:other_park_amenity_4=N t:home_setup=N t:other_park_amenity_5=N t:facility_name="GREEN ACRES" t:pool=N t:owner_or_operator_name="RAYMOND M. FLOWER" t:tiedown=N t:ground_maintenance=N t:facility_municipality=KNOX t:owner_or_operator_state=NY t:home_sales=N t:water=Y t:playground=N t:owner_or_operator_zip_code=12306 t:parking_space=Y t:sewage=Y t:home_maintenance=N t:road_maintenance=Y t:propane_gas=Y t:security_guard=N t:natural_gas=N t:garbage_trash=Y t:electrical=Y t:county=ALBANY t:owner_or_operator_city=SCHENECTADY t:laundry_room=N t:tv_cable_hookup=Y t:facility_id_number=1 t:storage=N m:sites_occupancy=25 m:site_capacity=25
```

## Meta Commands

```ls
metric m:site_capacity p:integer l:"Site Capacity" d:"The maximum number of sites at the manufactured home park" t:dataTypeName=number

metric m:sites_occupancy p:integer l:"Sites Occupancy" d:"The number of occupied or filled sites" t:dataTypeName=number

entity e:sxi2-m23m l:"Manufactured Home Park Registrations" t:attribution="New York State Division of Housing and Community Renewal" t:url=https://data.ny.gov/api/views/sxi2-m23m

property e:sxi2-m23m t:meta.view v:id=sxi2-m23m v:category="Economic Development" v:attributionLink=http://www.nyshcr.org v:averageRating=0 v:name="Manufactured Home Park Registrations" v:attribution="New York State Division of Housing and Community Renewal"

property e:sxi2-m23m t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:sxi2-m23m t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:sxi2-m23m t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| park_registration_year | county | facility_id_number | facility_name | facility_address | facility_municipality | site_capacity | sites_occupancy | park_owner_1 | park_owner_2 | park_owner_3 | park_owner_4 | park_owner_5 | park_owner_6 | park_owner_7 | owner_or_operator_name | owner_or_operator_address | owner_or_operator_city | owner_or_operator_state | owner_or_operator_zip_code | owner_or_operator_phone | home_setup | tiedown | home_sales | home_maintenance | ground_maintenance | road_maintenance | storage | playground | parking_space | water | sewage | beach | pool | garbage_trash | security_guard | food_store | clubhouse | laundry_room | electrical | natural_gas | propane_gas | tv_cable_hookup | other_park_amenity_1 | other_park_amenity_2 | other_park_amenity_3 | other_park_amenity_4 | other_park_amenity_5 | 
| ====================== | ====== | ================== | ============= | ================ | ===================== | ============= | =============== | ============ | ============ | ============ | ============ | ============ | ============ | ============ | ====================== | ========================= | ====================== | ======================= | ========================== | ======================= | ========== | ======= | ========== | ================ | ================== | ================ | ======= | ========== | ============= | ===== | ====== | ===== | ==== | ============= | ============== | ========== | ========= | ============ | ========== | =========== | =========== | =============== | ==================== | ==================== | ==================== | ==================== | ==================== | 
| 2016                   | ALBANY | 1                  | GREEN ACRES   | NOT PROVIDED     | KNOX                  | 25            | 25              |              |              |              |              |              |              |              | RAYMOND M. FLOWER      | 223 CURRYBUSH RD          | SCHENECTADY            | NY                      | 12306                      | 5183554461              | N          | N       | N          | N                | N                  | Y                | N       | N          | Y             | Y     | Y      | N     | N    | Y             | N              | N          | N         | N            | Y          | N           | Y           | Y               | N                    | N                    | N                    | N                    | N                    | 
| 2015                   | ALBANY | 1                  | GREEN ACRES   | NOT PROVIDED     | KNOX                  | 25            | 25              |              |              |              |              |              |              |              | RAYMOND M. FLOWER      | 223 CURRYBUSH RD          | SCHENECTADY            | NY                      | 12306                      | 5183554461              | N          | N       | N          | N                | N                  | Y                | N       | N          | Y             | Y     | Y      | N     | N    | Y             | N              | N          | N         | N            | Y          | N           | Y           | Y               | N                    | N                    | N                    | N                    | N                    | 
| 2014                   | ALBANY | 1                  | GREEN ACRES   | NOT PROVIDED     | KNOX                  | 25            | 25              |              |              |              |              |              |              |              | RAYMOND M. FLOWER      | 223 CURRYBUSH RD          | SCHENECTADY            | NY                      | 12306                      | 5183554461              | N          | N       | N          | N                | N                  | Y                | N       | N          | Y             | Y     | Y      | N     | N    | Y             | N              | N          | N         | N            | Y          | N           | Y           | Y               | N                    | N                    | N                    | N                    | N                    | 
| 2013                   | ALBANY | 1                  | GREEN ACRES   | NOT PROVIDED     | KNOX                  | 25            | 25              |              |              |              |              |              |              |              | RAYMOND M. FLOWER      | 223 CURRYBUSH RD          | SCHENECTADY            | NY                      | 12306                      | 5183554461              | N          | N       | N          | N                | N                  | Y                | N       | N          | Y             | Y     | Y      | N     | N    | Y             | N              | N          | N         | N            | Y          | N           | Y           | Y               | N                    | N                    | N                    | N                    | N                    | 
| 2012                   | ALBANY | 1                  | GREEN ACRES   | NOT PROVIDED     | KNOX                  | 25            | 25              |              |              |              |              |              |              |              | RAYMOND M. FLOWER      | 223 CURRYBUSH RD          | SCHENECTADY            | NY                      | 12306                      | 5183554461              | N          | N       | N          | N                | N                  | Y                | N       | N          | Y             | Y     | Y      | N     | N    | Y             | N              | N          | N         | N            | Y          | N           | Y           | Y               | N                    | N                    | N                    | N                    | N                    | 
| 2011                   | ALBANY | 1                  | GREEN ACRES   | NOT PROVIDED     | KNOX                  | 25            | 25              |              |              |              |              |              |              |              | RAYMOND M. FLOWER      | 223 CURRYBUSH RD          | SCHENECTADY            | NY                      | 12306                      | 5183554461              | N          | N       | N          | N                | N                  | Y                | N       | N          | Y             | Y     | Y      | N     | N    | Y             | N              | N          | N         | N            | Y          | N           | Y           | Y               | N                    | N                    | N                    | N                    | N                    | 
| 2010                   | ALBANY | 1                  | GREEN ACRES   | NOT PROVIDED     | KNOX                  | 25            | 25              |              |              |              |              |              |              |              | RAYMOND M. FLOWER      | 223 CURRYBUSH RD          | SCHENECTADY            | NY                      | 12306                      | 5183554461              | N          | N       | N          | N                | N                  | Y                | N       | N          | Y             | Y     | Y      | N     | N    | Y             | N              | N          | N         | N            | Y          | N           | Y           | Y               | N                    | N                    | N                    | N                    | N                    | 
| 2009                   | ALBANY | 1                  | GREEN ACRES   | NOT PROVIDED     | KNOX                  | 25            | 25              |              |              |              |              |              |              |              | RAYMOND M. FLOWER      | 223 CURRYBUSH RD          | SCHENECTADY            | NY                      | 12306                      | 5183554461              | N          | N       | N          | N                | N                  | Y                | N       | N          | Y             | Y     | Y      | N     | N    | Y             | N              | N          | N         | N            | Y          | N           | Y           | Y               | N                    | N                    | N                    | N                    | N                    | 
| 2008                   | ALBANY | 1                  | GREEN ACRES   | NOT PROVIDED     | KNOX                  | 25            | 25              |              |              |              |              |              |              |              | RAYMOND M. FLOWER      | 223 CURRYBUSH RD          | SCHENECTADY            | NY                      | 12306                      | 5183554461              | N          | N       | N          | N                | N                  | Y                | N       | N          | Y             | Y     | Y      | N     | N    | Y             | N              | N          | N         | N            | Y          | N           | Y           | Y               | N                    | N                    | N                    | N                    | N                    | 
| 2007                   | ALBANY | 1                  | GREEN ACRES   | NOT PROVIDED     | KNOX                  | 25            | 25              |              |              |              |              |              |              |              | RAYMOND M. FLOWER      | 223 CURRYBUSH RD          | SCHENECTADY            | NY                      | 12306                      | 5183554461              | N          | N       | N          | N                | N                  | Y                | N       | N          | Y             | Y     | Y      | N     | N    | Y             | N              | N          | N         | N            | Y          | N           | Y           | Y               | N                    | N                    | N                    | N                    | N                    | 
```