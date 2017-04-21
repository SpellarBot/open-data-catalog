# Casa Tienda Possible Properties

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/casa-tienda-possible-properties) |
| Metadata | [Link](https://data.lacity.org/api/views/y7m5-sde4) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/y7m5-sde4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/y7m5-sde4/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | y7m5-sde4 |
| Name | Casa Tienda Possible Properties |
| Attribution | Mayor's OTeam |
| Category | A Safe City |
| Tags | real estate |
| Created | 2016-10-21T23:09:20Z |
| Publication Date | 2016-10-21T23:11:33Z |

## Description

Possible assets identified by the Mayor's OTeam for Casa Tienda initiative.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| No       | time           | :updated_at                        | updated_at                         | meta_data | meta_data   |
| Yes      | series tag     | type_of_property                   | Type of Property                   | text      | text        |
| Yes      | series tag     | status                             | Status                             | text      | text        |
| Yes      | series tag     | agency_overseeing_asset            | Agency Overseeing Asset            | text      | text        |
| Yes      | series tag     | zoned_as                           | Zoned As                           | text      | text        |
| Yes      | series tag     | council_district                   | Council District                   | text      | number      |
| Yes      | series tag     | area_planning_commission           | Area Planning Commission           | text      | text        |
| Yes      | numeric metric | square_footage                     | Square Footage                     | number    | number      |
| Yes      | series tag     | business_improvement_district      | Business Improvement District      | text      | text        |
| Yes      | series tag     | community_plan_area                | Community Plan Area                | text      | text        |
| No       |                | address                            | Address                            | text      | text        |
| Yes      | numeric metric | la_county_apn                      | LA County APN                      | number    | number      |
| Yes      | series tag     | owner_according_to_county_assessor | Owner According to County Assessor | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:y7m5-sde4 d:2016-10-21T23:09:23.000Z t:status=Owned t:agency_overseeing_asset=CRA t:council_district=8 t:business_improvement_district=None t:type_of_property="Commercial Vacant Land" m:square_footage=8032.6 m:la_county_apn=6032013905

series e:y7m5-sde4 d:2016-10-21T23:09:23.000Z t:status=Owned t:agency_overseeing_asset="General Services" t:council_district=8 t:business_improvement_district=None t:type_of_property="Commercial Vacant Land" m:square_footage=4079.5 m:la_county_apn=6032035900

series e:y7m5-sde4 d:2016-10-21T23:09:23.000Z t:status=Owned t:agency_overseeing_asset=DOT t:council_district=8 t:business_improvement_district=None t:type_of_property="Parking Facility" m:square_footage=4400.3 m:la_county_apn=6033025900
```

## Meta Commands

```ls
metric m:square_footage p:double l:"Square Footage" t:dataTypeName=number

metric m:la_county_apn p:long l:"LA County APN" t:dataTypeName=number

entity e:y7m5-sde4 l:"Casa Tienda Possible Properties" t:attribution="Mayor's OTeam" t:url=https://data.lacity.org/api/views/y7m5-sde4

property e:y7m5-sde4 t:meta.view v:id=y7m5-sde4 v:category="A Safe City" v:averageRating=0 v:name="Casa Tienda Possible Properties" v:attribution="Mayor's OTeam"

property e:y7m5-sde4 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:y7m5-sde4 t:meta.view.owner v:id=yv94-nsgm v:profileImageUrlMedium=/api/users/yv94-nsgm/profile_images/THUMB v:profileImageUrlLarge=/api/users/yv94-nsgm/profile_images/LARGE v:screenName=JuanSVas v:profileImageUrlSmall=/api/users/yv94-nsgm/profile_images/TINY v:displayName=JuanSVas

property e:y7m5-sde4 t:meta.view.tableauthor v:id=yv94-nsgm v:profileImageUrlMedium=/api/users/yv94-nsgm/profile_images/THUMB v:profileImageUrlLarge=/api/users/yv94-nsgm/profile_images/LARGE v:screenName=JuanSVas v:profileImageUrlSmall=/api/users/yv94-nsgm/profile_images/TINY v:roleName=publisher v:displayName=JuanSVas
```

## Top Records

```ls
| :updated_at | type_of_property       | status             | agency_overseeing_asset | zoned_as | council_district | area_planning_commission | square_footage    | business_improvement_district | community_plan_area | address                     | la_county_apn | owner_according_to_county_assessor | 
| =========== | ====================== | ================== | ======================= | ======== | ================ | ======================== | ================= | ============================= | =================== | =========================== | ============= | ================================== | 
| 1477091363  | Commercial Vacant Land | Owned              | CRA                     |          | 8                |                          | 8032.6            | None                          |                     | 8500 S VERMONT AVE          | 6032013905    |                                    | 
| 1477091363  | Commercial Vacant Land | Owned              | General Services        |          | 8                |                          | 4079.5            | None                          |                     | 8531 South Flower Street    | 6032035900    |                                    | 
| 1477091363  | Parking Facility       | Owned              | DOT                     |          | 8                |                          | 4400.3            | None                          |                     | 8463 S Vermont Ave          | 6033025900    |                                    | 
| 1477091363  | Residential Improved   | Owned              | HCID                    |          | 8                |                          | 14512.2           | None                          |                     | 461 W 87TH ST               | 6038001902    |                                    | 
| 1477091363  | Park                   | Owned              | RAP                     |          | 8                | South Los Angeles        | 9147.6            | None                          | South Los Angeles   | 8742 & 8750 S. VERMONT AVE. | 6038010904    |                                    | 
| 1477091363  | Park                   | Owned              | RAP                     |          | 8                | South Los Angeles        | 5662.8            | None                          | South Los Angeles   | 554 West 97th Street        | 6054025902    |                                    | 
| 1477091363  | Public Safety Facility | Surplus-Undeclared | General Services        | PF-1     | 8                |                          | 6593.0            |                               |                     | 729 W MANCHESTER            | 6032015901    |                                    | 
| 1477091363  | Public Facility        | Owned              | General Services        | [Q]C2-1  | 8                | South Los Angeles        | 10193.5           | NONE                          | South Los Angeles   | 8475 South Vermont Avenue   | 6033025902    |                                    | 
| 1477091363  | Public Facility        | Owned              | LAPL                    |          | 8                |                          |                   |                               |                     | 9621 South Figueroa Street  | 6054028900    |                                    | 
| 1477091363  | Public Facility        | Owned              | RAP                     |          | 8                | South Los Angeles        | 716997.6000000001 |                               | South Los Angeles   | 8800 South Hoover Street    | 6038013900    |                                    | 
```