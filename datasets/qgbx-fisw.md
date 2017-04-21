# Possible Assets for Polling Efforts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/possible-assets-for-polling-efforts) |
| Metadata | [Link](https://data.lacity.org/api/views/qgbx-fisw) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/qgbx-fisw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/qgbx-fisw/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | qgbx-fisw |
| Name | Possible Assets for Polling Efforts |
| Category | A Livable and Sustainable City |
| Created | 2016-09-07T23:48:45Z |
| Publication Date | 2016-09-07T23:51:20Z |

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| No       | time           | :updated_at                      | updated_at                       | meta_data | meta_data   |
| Yes      | series tag     | parcel_number                    | Parcel Number                    | text      | number      |
| Yes      | series tag     | type_of_asset                    | Type of Asset                    | text      | text        |
| Yes      | series tag     | agency_overseeing_asset          | Agency Overseeing Asset          | text      | text        |
| Yes      | series tag     | zoning                           | Zoning                           | text      | text        |
| Yes      | series tag     | neighborhood_council             | Neighborhood Council             | text      | text        |
| Yes      | series tag     | council_district                 | Council District                 | text      | number      |
| Yes      | series tag     | area_planning_commission         | Area Planning Commission         | text      | text        |
| Yes      | numeric metric | square_footage                   | Square Footage                   | number    | number      |
| Yes      | series tag     | business_improvement_district    | Business Improvement District    | text      | text        |
| Yes      | series tag     | community_plan_area              | Community Plan Area              | text      | text        |
| Yes      | series tag     | targeted_neighborhood_initiative | Targeted Neighborhood Initiative | text      | text        |
| Yes      | series tag     | class_c_estimate                 | Class C Estimate                 | text      | text        |
| Yes      | series tag     | building_name                    | Building Name                    | text      | text        |
| Yes      | series tag     | state_enterprise_zone            | State Enterprise Zone            | text      | text        |
| Yes      | series tag     | pin                              | PIN                              | text      | text        |
| Yes      | series tag     | building_book_number             | Building Book Number             | text      | text        |
| Yes      | numeric metric | la_county_apn                    | LA County APN                    | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qgbx-fisw d:2016-09-07T23:48:48.000Z t:building_name="City Hall South" t:targeted_neighborhood_initiative=None t:type_of_asset="Public Facility" t:agency_overseeing_asset="General Services" t:council_district=14 t:parcel_number=5161014902 t:area_planning_commission=Central t:neighborhood_council="Downtown Los Angeles" t:pin="130-5A213  17" t:building_book_number=01-011-00 t:business_improvement_district=None t:zoning=PF-2D t:community_plan_area="Central City" t:state_enterprise_zone="Los Angeles State Enterprise Zone" m:square_footage=62942.3 m:la_county_apn=5161014902

series e:qgbx-fisw d:2016-09-07T23:48:48.000Z t:building_name="Los Angeles City Hall" t:targeted_neighborhood_initiative=None t:type_of_asset="Public Facility" t:agency_overseeing_asset="General Services" t:council_district=14 t:parcel_number=5161005906 t:area_planning_commission=Central t:neighborhood_council="Downtown Los Angeles" t:pin="130-5A213 1" t:building_book_number=01-002-00 t:business_improvement_district=None t:zoning=OS-2D t:community_plan_area="Central City" t:state_enterprise_zone="Los Angeles State Enterprise Zone" m:square_footage=255338.8 m:la_county_apn=5161005906

series e:qgbx-fisw d:2016-09-07T23:48:48.000Z t:building_name="Los Angeles Mall" t:type_of_asset="Commercial Improved" t:neighborhood_council="Downtown Los Angeles" t:pin="130-5A213 3" t:agency_overseeing_asset="General Services" t:council_district=14 t:building_book_number=01-026-0 t:business_improvement_district=None t:parcel_number=5161010901 t:community_plan_area="Central City" t:area_planning_commission=Central m:square_footage=103593.5 m:la_county_apn=5161010901
```

## Meta Commands

```ls
metric m:square_footage p:float l:"Square Footage" t:dataTypeName=number

metric m:la_county_apn p:long l:"LA County APN" t:dataTypeName=number

entity e:qgbx-fisw l:"Possible Assets for Polling Efforts" t:url=https://data.lacity.org/api/views/qgbx-fisw

property e:qgbx-fisw t:meta.view v:id=qgbx-fisw v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Possible Assets for Polling Efforts"

property e:qgbx-fisw t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:qgbx-fisw t:meta.view.owner v:id=yv94-nsgm v:profileImageUrlMedium=/api/users/yv94-nsgm/profile_images/THUMB v:profileImageUrlLarge=/api/users/yv94-nsgm/profile_images/LARGE v:screenName=JuanSVas v:profileImageUrlSmall=/api/users/yv94-nsgm/profile_images/TINY v:displayName=JuanSVas

property e:qgbx-fisw t:meta.view.tableauthor v:id=yv94-nsgm v:profileImageUrlMedium=/api/users/yv94-nsgm/profile_images/THUMB v:profileImageUrlLarge=/api/users/yv94-nsgm/profile_images/LARGE v:screenName=JuanSVas v:profileImageUrlSmall=/api/users/yv94-nsgm/profile_images/TINY v:roleName=publisher v:displayName=JuanSVas
```

## Top Records

```ls
| :updated_at | parcel_number | type_of_asset       | agency_overseeing_asset | zoning         | neighborhood_council | council_district | area_planning_commission | square_footage | business_improvement_district | community_plan_area | targeted_neighborhood_initiative | class_c_estimate | building_name           | state_enterprise_zone             | pin           | building_book_number | la_county_apn | 
| =========== | ============= | =================== | ======================= | ============== | ==================== | ================ | ======================== | ============== | ============================= | =================== | ================================ | ================ | ======================= | ================================= | ============= | ==================== | ============= | 
| 1473292128  | 5161014902    | Public Facility     | General Services        | PF-2D          | Downtown Los Angeles | 14               | Central                  | 62942.3        | None                          | Central City        | None                             |                  | City Hall South         | Los Angeles State Enterprise Zone | 130-5A213 17  | 01-011-00            | 5161014902    | 
| 1473292128  | 5161005906    | Public Facility     | General Services        | OS-2D          | Downtown Los Angeles | 14               | Central                  | 255338.8       | None                          | Central City        | None                             |                  | Los Angeles City Hall   | Los Angeles State Enterprise Zone | 130-5A213 1   | 01-002-00            | 5161005906    | 
| 1473292128  | 5161010901    | Commercial Improved | General Services        |                | Downtown Los Angeles | 14               | Central                  | 103593.5       | None                          | Central City        |                                  |                  | Los Angeles Mall        |                                   | 130-5A213 3   | 01-026-0             | 5161010901    | 
| 1473292128  | 5161012904    | Commercial Improved | General Services        | [Q]C4-2D-CDO   | Historic Cultural    | 14               | Central                  | 83076.2        | Little Tokyo                  | Central City        | None                             |                  | TOKYO GIFT SHOP         | LOS ANGELES STATE ENTERPRISE ZONE | 130-5A215 384 | 60-525-00            | 5161012904    | 
| 1473292128  | 5161012908    | Commercial Improved | General Services        | [Q]C4-2D-CDO   | Historic Cultural    | 14               | Central                  | 5448.3         | Little Tokyo                  | Central City        | None                             |                  | Little Tokyo Substation | LOS ANGELES STATE ENTERPRISE ZONE | 130-5A215 287 | 33-001-0             | 5161012908    | 
| 1473292128  |               | Public Facility     | General Services        |                | Downtown Los Angeles | 14               | Central                  | 552481.0       | None                          | Central City        |                                  |                  | City Hall East          |                                   | 130-5A213 3   | 01-014-00            | 5161014901    | 
| 1473292128  | 5161017921    | Not Classified      | General Services        | [Q]C2-4D-O-CDO | Historic Cultural    | 14               | Central                  | 40.1           | Little Tokyo                  | Central City        | None                             |                  |                         | LOS ANGELES STATE ENTERPRISE ZONE | 129A215 60    |                      | 5161017921    | 
| 1473292128  | 5161019011    | Commercial Improved | General Services        | [Q]C2-3D-O-CDO | Historic Cultural    | 14               | Central                  | 68092.0        | Little Tokyo                  | Central City        | None                             |                  |                         | LOS ANGELES STATE ENTERPRISE ZONE | 129A215 190   | 05-422-00            | 5161019011    | 
| 1473292128  | 5161020018    | Commercial Improved | Private                 | [Q]C2-4D-O-CDO | Historic Cultural    | 14               | Central                  | 13349.0        | Little Tokyo                  | Central City        | None                             |                  |                         | LOS ANGELES STATE ENTERPRISE ZONE | 129A215 104   | 1-53-0               | 5161020018    | 
| 1473292128  | 5161020923    | Easement            | CRA                     | [Q]C2-4D-O-CDO | Historic Cultural    | 14               | Central                  | 10574.0        | Little Tokyo                  | Central City        | None                             |                  |                         | LOS ANGELES STATE ENTERPRISE ZONE | 129A213 157   |                      | 5161020923    | 
```