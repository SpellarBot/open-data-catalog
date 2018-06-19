# Onondaga County Public Facilities and Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/onondaga-county-public-facilities-and-services) |
| Metadata | [Link](https://data.ny.gov/api/views/bybh-67nt) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/bybh-67nt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/bybh-67nt/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | bybh-67nt |
| Name | Onondaga County Public Facilities and Services |
| Attribution | Onondaga County |
| Category | Government & Finance |
| Tags | onondaga county parks, hospitals in onondaga county, urgent care facilities in onondaga county |
| Created | 2013-03-03T23:48:05Z |
| Publication Date | 2013-03-03T23:51:50Z |

## Description

Onondaga County has created an interactive facilities locator that allows residents to find public locations such as parks, hospitals, and urgent care facilities.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | building_name      | Building Name      | text      | text        |
| Yes      | series tag  | building_code      | Building Code      | text      | text        |
| Yes      | series tag  | type_of_service    | Type of Service    | text      | text        |
| Yes      | series tag  | room_or_suite      | Room or Suite      | text      | text        |
| Yes      | series tag  | main_phone_number  | Main Phone Number  | text      | text        |
| Yes      | series tag  | street_address     | Street Address     | text      | text        |
| Yes      | series tag  | city_state_zip     | City State Zip     | text      | text        |
| Yes      | series tag  | hours_of_operation | Hours of Operation | text      | text        |
| No       |             | latitude           | Latitude           | number    | text        |
| No       |             | longitude          | Longitude          | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:bybh-67nt d:2013-03-03T15:48:07.000Z t:building_name="North Medical Urgent Care" t:city_state_zip="Liverpool, NY 13090" t:hours_of_operation="7 days a week - 7:00 a.m - 11:00 p.m." t:main_phone_number="(315) 452-2333" t:type_of_service="Urgent Care" t:street_address="5100 W. Taft Road" t:building_code="Health and Hospitals System" m:row_number.bybh-67nt=1

series e:bybh-67nt d:2013-03-03T15:48:07.000Z t:building_name="Northeast Medical Urgent Care" t:city_state_zip="Fayetteville, NY 13066" t:hours_of_operation="7 days a week - 7:00 a.m - 11:00 p.m." t:room_or_suite=#4103 t:main_phone_number="(315) 637-7800" t:type_of_service="Urgent Care" t:street_address="4000 Medical Center Dr." t:building_code="Health and Hospitals System" m:row_number.bybh-67nt=2

series e:bybh-67nt d:2013-03-03T15:48:07.000Z t:building_name="Crouse Prompt Care" t:city_state_zip="Syracuse, NY 13210" t:hours_of_operation="7 days a week - 7:00 a.m - 11:00 p.m." t:main_phone_number="(315) 470-2951" t:type_of_service="Urgent Care" t:street_address="739 Irving Avenue" t:building_code="Health and Hospitals System" m:row_number.bybh-67nt=3
```

## Meta Commands

```ls
metric m:row_number.bybh-67nt p:long l:"Row Number"

entity e:bybh-67nt l:"Onondaga County Public Facilities and Services" t:attribution="Onondaga County" t:url=https://data.ny.gov/api/views/bybh-67nt

property e:bybh-67nt t:meta.view v:id=bybh-67nt v:category="Government & Finance" v:attributionLink=http://www.onondagacountyparks.com/ v:averageRating=0 v:name="Onondaga County Public Facilities and Services" v:attribution="Onondaga County"

property e:bybh-67nt t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:bybh-67nt t:meta.view.tableauthor v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:bybh-67nt t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | building_name                                           | building_code               | type_of_service | room_or_suite | main_phone_number | street_address           | city_state_zip         | hours_of_operation                                                 | latitude           | longitude           | 
| =========== | ======================================================= | =========================== | =============== | ============= | ================= | ======================== | ====================== | ================================================================== | ================== | =================== | 
| 1362325687  | North Medical Urgent Care                               | Health and Hospitals System | Urgent Care     |               | (315) 452-2333    | 5100 W. Taft Road        | Liverpool, NY 13090    | 7 days a week - 7:00 a.m - 11:00 p.m.                              | 43.121529199999998 | -76.162762799999996 | 
| 1362325687  | Northeast Medical Urgent Care                           | Health and Hospitals System | Urgent Care     | #4103         | (315) 637-7800    | 4000 Medical Center Dr.  | Fayetteville, NY 13066 | 7 days a week - 7:00 a.m - 11:00 p.m.                              | 43.039611000000001 | -76.022749000000005 | 
| 1362325687  | Crouse Prompt Care                                      | Health and Hospitals System | Urgent Care     |               | (315) 470-2951    | 739 Irving Avenue        | Syracuse, NY 13210     | 7 days a week - 7:00 a.m - 11:00 p.m.                              | 43.041176999999998 | -76.137507999999997 | 
| 1362325687  | Immediate Medical Care Assoc.                           | Health and Hospitals System | Urgent Care     |               | (315) 488-6393    | 5700 West Genesee St.    | Camillus, NY 13031     | M-F - 9:00 a.m. - 6:00 p.m./ S-S 8:00 a.m. - 2:00 p.m.             | 43.041204999999998 | -76.294185999999996 | 
| 1362325687  | Finger Lakes Medical Care Center-Skaneateles            | Health and Hospitals System | Urgent Care     | Route 20      | (315) 685-9355    | 803 Genesee Street       | Skaneateles, NY 13152  | M-F 9:00-12:00 p.m. and 1:00 -6:00 p.m. / S-S 8:00 a.m.- 1:00 p.m. | 42.944116999999999 | -76.446226899999999 | 
| 1362325687  | Finger Lakes Medical Care Center - Auburn               | Health and Hospitals System | Urgent Care     |               | (315) 258-7100    | 303 Grant Avenue         | Auburn, NY 13021       | M-F 9:00-12:00 p.m. and 1:00-6:00 p.m./S-S 8:00 a.m. - 1:00 p.m.   | 42.95487           | -76.549785          | 
| 1362325687  | Cayuga Medical Center Convenient Care Center - Cortland | Health and Hospitals System | Urgent Care     |               | (607) 756-7200    | Rte. 281 at Commons Ave. | Cortland, NY 13045     | 7 days a week - 7:00 a.m - 10:00 p.m.                              | 42.604925999999999 | -76.199833100000006 | 
| 1362325687  | Cortland Regional Medical Center Prompt Care            | Health and Hospitals System | Urgent Care     |               | (607) 756-3500    | 134 Homer Avenue         | Cortland, NY 13045     | M-F 1:00 p.m.-10:00 p.m./S-S 10:00 a.m. - 10:00 p.m.               | 42.608842000000003 | -76.187635          | 
| 1362325687  | Crouse Hospital                                         | Health and Hospitals System | Hospital        |               | (315) 470-7111    | 736 Irving Avenue        | Syracuse, NY 13210     |                                                                    | 43.041413900000002 | -76.1378749         | 
| 1362325687  | St. Joseph's Hospital Health Center                     | Health and Hospitals System | Hospital        |               | (315)448-5111     | 301 Prospect Avenue      | Syracuse, NY 13202     |                                                                    | 43.055706999999998 | -76.149806999999996 | 
```