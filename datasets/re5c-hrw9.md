# Property Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/property-information) |
| Metadata | [Link](https://data.brla.gov/api/views/re5c-hrw9) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/re5c-hrw9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/re5c-hrw9/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | re5c-hrw9 |
| Name | Property Information |
| Attribution | City Parish Planning Commission |
| Category | Housing and Development |
| Tags | lot, address, property |
| Created | 2014-12-01T01:37:32Z |
| Publication Date | 2016-08-26T19:04:42Z |

## Description

This dataset is a combination of attribute information from the master address table that is associated with the center point of building footprints.  If there is no building, then the point is the center of the lot.  The address information comes from a variety of sources including Public Works building permits, E-911 telephone database, Polk City Directory, and field data collection.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                          | Data Type | Render Type |
| ======== | ============== | ====================== | ============================= | ========= | =========== |
| No       | time           | :updated_at            | updated_at                    | meta_data | meta_data   |
| No       |                | address_point_id       | ADDRESS POINT ID              | text      | number      |
| Yes      | series tag     | lot_id                 | LOT ID                        | text      | number      |
| No       |                | address_id             | ADDRESS ID                    | text      | number      |
| No       |                | address_no_complete    | ADDRESS NO COMPLETE           | text      | text        |
| Yes      | series tag     | st_prefix_dir          | STREET PREFIX DIRECTION       | text      | text        |
| Yes      | series tag     | st_name                | STREET NAME                   | text      | text        |
| Yes      | series tag     | st_suffix_type         | STREET SUFFIX TYPE            | text      | text        |
| Yes      | series tag     | st_suffix_dir          | STREET SUFFIX DIRECTION       | text      | text        |
| Yes      | series tag     | st_ext                 | STREET EXTENSION              | text      | text        |
| Yes      | series tag     | city                   | CITY                          | text      | text        |
| Yes      | series tag     | zip                    | ZIP                           | text      | number      |
| Yes      | series tag     | subd_id                | SUBDIVISION ID                | text      | number      |
| Yes      | series tag     | subdivision            | SUBDIVISION                   | text      | text        |
| Yes      | series tag     | property_info          | PROPERTY NAME                 | text      | text        |
| Yes      | series tag     | business_id            | BUSINESS ID                   | text      | number      |
| Yes      | series tag     | business_name          | BUSINESS NAME                 | text      | text        |
| Yes      | series tag     | business_naics_code    | BUSINESS NAICS CODE           | text      | number      |
| Yes      | numeric metric | pla_dist               | PLANNING DISTRICT NO          | number    | number      |
| Yes      | numeric metric | sub_area               | SUBAREA NO                    | number    | number      |
| Yes      | numeric metric | lb_map                 | LOT BLOCK MAP NO              | number    | number      |
| Yes      | series tag     | lot_num                | LOT NO                        | text      | text        |
| Yes      | series tag     | block_num              | CITY BLOCK SQUARE NO          | text      | text        |
| Yes      | series tag     | lot_location           | LOT JURISDICTION              | text      | text        |
| Yes      | series tag     | ward_number            | WARD NO                       | text      | text        |
| Yes      | numeric metric | tax_section            | TAX SECTION                   | number    | text        |
| Yes      | series tag     | plss                   | PUBLIC LAND SURVEY SYSTEM     | text      | text        |
| Yes      | numeric metric | census_tract           | CENSUS TRACT                  | number    | number      |
| Yes      | series tag     | block_group            | CENSUS BLOCK GROUP            | text      | number      |
| Yes      | numeric metric | dotd_map               | TRAFFIC ANALYSIS ZONE         | number    | number      |
| Yes      | series tag     | police_district        | POLICE DISTRICT               | text      | text        |
| Yes      | series tag     | fire_district          | FIRE DISTRICT                 | text      | text        |
| Yes      | series tag     | school_district        | SCHOOL DISTRICT               | text      | text        |
| Yes      | series tag     | voting_district        | VOTING PRECINCT               | text      | text        |
| Yes      | series tag     | council_dist_no        | COUNCIL DISTRICT NO           | text      | number      |
| Yes      | series tag     | enterprise_zone        | ENTERPRISE ZONE               | text      | text        |
| Yes      | series tag     | economic_dev_zone      | ECONOMIC DEVELOPMENT ZONE     | text      | text        |
| Yes      | series tag     | redevelopment_district | REDEVELOPMENT DISTRICT        | text      | text        |
| Yes      | series tag     | historic_district      | HISTORIC DISTRICT             | text      | text        |
| Yes      | series tag     | historic_landmark      | HISTORIC LANDMARK             | text      | text        |
| Yes      | series tag     | udd_name               | URBAN DESIGN DISTRICT         | text      | text        |
| Yes      | series tag     | udod_name              | URBAN DESIGN OVERLAY DISTRICT | text      | text        |
| Yes      | series tag     | industrial_area        | INDUSTRIAL AREA               | text      | text        |
| Yes      | series tag     | existing_land_use      | EXISTING LAND USE             | text      | text        |
| Yes      | series tag     | future_land_use        | FUTURE LAND USE               | text      | text        |
| Yes      | series tag     | zoning_type            | ZONING TYPE                   | text      | text        |
| Yes      | numeric metric | area_meas_acres        | LOT AREA MEASUREMENT          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_point_id,address_id,address_no_complete
```

## Data Commands

```ls
series e:re5c-hrw9 d:2015-10-06T10:11:33.000Z t:industrial_area="Yes, 1" t:zip=70807 t:lot_num="TR. ECO-1" t:st_name=HARDING t:future_land_use=I t:council_dist_no=10 t:plss="T6S R1W Sect 50" t:existing_land_use=UND t:subd_id=2849 t:enterprise_zone=YES t:city="BATON ROUGE" t:property_info="SHADA PLANTATION & RIVERVIEW FARMS PLANTATION" t:lot_location=Parish t:economic_dev_zone=NO t:lot_id=710080046 t:st_suffix_type=BLVD t:block_group=3 t:school_district=EBR-3 t:voting_district=1-100 m:pla_dist=7 m:sub_area=1 m:area_meas_acres=52.39 m:dotd_map=235 m:census_tract=30 m:lb_map=8

series e:re5c-hrw9 d:2015-10-06T10:11:41.000Z t:industrial_area="Yes, 1" t:zip=70805 t:lot_num="TR. R-4" t:st_name=SCENIC t:future_land_use=I t:council_dist_no=10 t:plss="T6S R1W Sect 44" t:existing_land_use=I t:subd_id=2849 t:enterprise_zone=YES t:city="BATON ROUGE" t:business_name="EXXON MOBIL ELASTOMERS PRODUCT WAREHOUSE" t:lot_location=Parish t:economic_dev_zone=NO t:lot_id=710270274 t:st_suffix_type=HWY t:business_id=28575 t:business_naics_code=324000 t:block_group=3 t:school_district=EBR-3 t:voting_district=1-17 m:pla_dist=7 m:sub_area=1 m:area_meas_acres=315.06 m:dotd_map=232 m:census_tract=30 m:lb_map=27

series e:re5c-hrw9 d:2015-10-06T10:11:46.000Z t:industrial_area="Yes, 1" t:subdivision="MONTE SANO HIGHLAND FARMS" t:zip=70805 t:lot_num=UND t:st_name=SCENIC t:future_land_use=I t:council_dist_no=5 t:plss="T6S R1W Sect 37" t:existing_land_use=I t:subd_id=2695 t:enterprise_zone=YES t:city="BATON ROUGE" t:business_name="EAST WEST COPOLYMER" t:lot_location=Parish t:economic_dev_zone=NO t:lot_id=710120045 t:st_suffix_type=HWY t:business_id=2594 t:business_naics_code=325212 t:block_group=3 t:school_district=EBR-3 t:voting_district=1-23 m:pla_dist=7 m:sub_area=1 m:area_meas_acres=0.28 m:dotd_map=238 m:census_tract=30 m:lb_map=12
```

## Meta Commands

```ls
metric m:pla_dist p:integer l:"PLANNING DISTRICT NO" d:"The Planning Commission district number (1-16)" t:dataTypeName=number

metric m:sub_area p:integer l:"SUBAREA NO" d:"Planning Districts are divided into 3-5 subareas" t:dataTypeName=number

metric m:lb_map p:integer l:"LOT BLOCK MAP NO" d:"The retired City-Parish lot and block map number (1-267)" t:dataTypeName=number

metric m:tax_section p:integer l:"TAX SECTION" d:"Division of the Parish wards for property recordation purposes" t:dataTypeName=number

metric m:census_tract p:double l:"CENSUS TRACT" t:dataTypeName=number

metric m:dotd_map p:integer l:"TRAFFIC ANALYSIS ZONE" d:"An area number designated by the Louisiana Department of Transportation and Development" t:dataTypeName=number

metric m:area_meas_acres p:float l:"LOT AREA MEASUREMENT" d:"Area of the lot measured in acres" t:dataTypeName=number

entity e:re5c-hrw9 l:"Property Information" t:attribution="City Parish Planning Commission" t:url=https://data.brla.gov/api/views/re5c-hrw9

property e:re5c-hrw9 t:meta.view v:id=re5c-hrw9 v:category="Housing and Development" v:attributionLink=http://brgov.com/dept/planning v:averageRating=0 v:name="Property Information" v:attribution="City Parish Planning Commission"

property e:re5c-hrw9 t:meta.view.license v:name="Public Domain"

property e:re5c-hrw9 t:meta.view.owner v:id=srd7-p95j v:profileImageUrlMedium=/api/users/srd7-p95j/profile_images/THUMB v:profileImageUrlLarge=/api/users/srd7-p95j/profile_images/LARGE v:screenName="Warren Kron" v:profileImageUrlSmall=/api/users/srd7-p95j/profile_images/TINY v:displayName="Warren Kron"

property e:re5c-hrw9 t:meta.view.tableauthor v:id=srd7-p95j v:profileImageUrlMedium=/api/users/srd7-p95j/profile_images/THUMB v:profileImageUrlLarge=/api/users/srd7-p95j/profile_images/LARGE v:screenName="Warren Kron" v:profileImageUrlSmall=/api/users/srd7-p95j/profile_images/TINY v:roleName=administrator v:displayName="Warren Kron"
```

## Top Records

```ls
| :updated_at | address_point_id | lot_id    | address_id | address_no_complete | st_prefix_dir | st_name               | st_suffix_type | st_suffix_dir | st_ext | city        | zip   | subd_id | subdivision               | property_info                                 | business_id | business_name                            | business_naics_code | pla_dist | sub_area | lb_map | lot_num   | block_num | lot_location | ward_number | tax_section | plss            | census_tract | block_group | dotd_map | police_district | fire_district | school_district | voting_district | council_dist_no | enterprise_zone | economic_dev_zone | redevelopment_district | historic_district | historic_landmark | udd_name | udod_name | industrial_area | existing_land_use | future_land_use | zoning_type | area_meas_acres | 
| =========== | ================ | ========= | ========== | =================== | ============= | ===================== | ============== | ============= | ====== | =========== | ===== | ======= | ========================= | ============================================= | =========== | ======================================== | =================== | ======== | ======== | ====== | ========= | ========= | ============ | =========== | =========== | =============== | ============ | =========== | ======== | =============== | ============= | =============== | =============== | =============== | =============== | ================= | ====================== | ================= | ================= | ======== | ========= | =============== | ================= | =============== | =========== | =============== | 
| 1444126293  | 14629            | 710080046 | 169654     | 500                 |               | HARDING               | BLVD           |               |        | BATON ROUGE | 70807 | 2849    |                           | SHADA PLANTATION & RIVERVIEW FARMS PLANTATION |             |                                          |                     | 7        | 1        | 8      | TR. ECO-1 |           | Parish       |             |             | T6S R1W Sect 50 | 30           | 3           | 235      |                 |               | EBR-3           | 1-100           | 10              | YES             | NO                |                        |                   |                   |          |           | Yes, 1          | UND               | I               |             | 52.39           | 
| 1444126301  | 180309           | 710270274 | 180932     | 3301                |               | SCENIC                | HWY            |               |        | BATON ROUGE | 70805 | 2849    |                           |                                               | 28575       | EXXON MOBIL ELASTOMERS PRODUCT WAREHOUSE | 324000              | 7        | 1        | 27     | TR. R-4   |           | Parish       |             |             | T6S R1W Sect 44 | 30           | 3           | 232      |                 |               | EBR-3           | 1-17            | 10              | YES             | NO                |                        |                   |                   |          |           | Yes, 1          | I                 | I               |             | 315.06          | 
| 1444126306  | 14889            | 710120045 | 99020      | 5955                |               | SCENIC                | HWY            |               |        | BATON ROUGE | 70805 | 2695    | MONTE SANO HIGHLAND FARMS |                                               | 2594        | EAST WEST COPOLYMER                      | 325212              | 7        | 1        | 12     | UND       |           | Parish       |             |             | T6S R1W Sect 37 | 30           | 3           | 238      |                 |               | EBR-3           | 1-23            | 5               | YES             | NO                |                        |                   |                   |          |           | Yes, 1          | I                 | I               |             | 0.28            | 
| 1444126308  | 45728            | 710270273 | 142777     | 2400                | N             | 3RD                   | ST             |               |        | BATON ROUGE | 70805 | 2849    |                           |                                               | 34878       | RESCAR COMPANIES                         | 811000              | 7        | 1        | 27     | C.N.R.R.  |           | Parish       |             |             | T6S R1W Sect 45 | 30           | 3           | 232      |                 |               | EBR-3           | 1-17            | 10              | YES             | NO                |                        |                   |                   |          |           | Yes, 1          | I                 | I               |             | 89.3            | 
| 1444126328  | 45948            | 712530010 | 79616      | 4045                |               | SCENIC                | HWY            |               |        | BATON ROUGE | 70805 | 2849    |                           |                                               | 37897       | EXXON MOBIL CHEMICAL COMPANY             | 211112              | 7        | 1        | 253    | TR. R-3   |           | Parish       |             |             | T6S R1W Sect 44 | 30           | 3           | 232      |                 |               | EBR-3           | 1-17            | 10              | YES             | NO                |                        |                   |                   |          |           | Yes, 1          | I                 | I               |             | 518.13          | 
| 1444126339  | 14711            | 710270293 | 122542     | 913                 |               | CHIPPEWA              | ST             |               |        | BATON ROUGE | 70805 | 2134    | STANDARD HEIGHTS          |                                               | 7008        | RENTAL SERVICE CORP                      | 532412              | 7        | 1        | 27     | 19        | 51        | Parish       |             |             | T6S R1W Sect 45 | 30           | 3           | 232      |                 |               | EBR-3           | 1-17            | 10              | YES             | NO                |                        |                   |                   |          |           | Yes, 1          | I                 | I               |             | 0.14            | 
| 1444126350  | 215614           | 710120190 | 219283     | 1325 STE 4C         |               | AIRLINE               | HWY            |               |        | BATON ROUGE | 70805 | 2849    |                           | KAISER ALUMINUM AND CHEMICAL CORPORATION      | 42004       | CLUB TRUTH                               | 722000              | 7        | 1        | 12     | UND       |           | Parish       |             |             | T6S R1W Sect 37 | 30           | 3           | 233      |                 |               | EBR-3           | 1-100           | 10              | YES             | NO                |                        |                   |                   |          |           | Yes, 1          | C                 | I               |             | 8.27            | 
| 1444126351  | 215136           | 710120190 | 218617     | 1325 STE 4B         |               | AIRLINE               | HWY            |               |        | BATON ROUGE | 70805 | 2849    |                           | KAISER ALUMINUM AND CHEMICAL CORPORATION      | 41470       | RIVERFRONT SOUTHERN STYLE CAFE           | 722000              | 7        | 1        | 12     | UND       |           | Parish       |             |             | T6S R1W Sect 37 | 30           | 3           | 233      |                 |               | EBR-3           | 1-100           | 10              | YES             | NO                |                        |                   |                   |          |           | Yes, 1          | C                 | I               |             | 8.27            | 
| 1444126354  | 46775            | 712530011 | 156703     | 300                 |               | GULF STATES UTILITIES | RD             |               |        | BATON ROUGE | 70805 | 2849    |                           |                                               | 19777       | ENTERGY POWER PLANT                      | 221112              | 7        | 1        | 27     | GSU CO.   |           | Parish       |             |             | T6S R1W Sect 43 | 30           | 3           | 232      |                 |               | EBR-3           | 1-17            | 10              | YES             | NO                |                        |                   |                   |          |           | Yes, 1          | U                 | I               |             | 75.38           | 
| 1444126362  | 45948            | 712530010 | 79616      | 4045                |               | SCENIC                | HWY            |               |        | BATON ROUGE | 70805 | 2849    |                           |                                               | 37897       | EXXON MOBILE PIPELINE CO                 | 454000              | 7        | 1        | 253    | TR. R-3   |           | Parish       |             |             | T6S R1W Sect 44 | 30           | 3           | 232      |                 |               | EBR-3           | 1-17            | 10              | YES             | NO                |                        |                   |                   |          |           | Yes, 1          | I                 | I               |             | 518.13          | 
```