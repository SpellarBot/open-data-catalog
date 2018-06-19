# CD8 Around Imperial Highway - Potential Sites for Homeless Service Deployment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cd8-around-imperial-highway-potential-sites-for-homeless-service-deployment) |
| Metadata | [Link](https://data.lacity.org/api/views/vh95-edpt) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/vh95-edpt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/vh95-edpt/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | vh95-edpt |
| Name | CD8 Around Imperial Highway - Potential Sites for Homeless Service Deployment |
| Attribution | Mayor's Operations Innovation Team |
| Category | A Livable and Sustainable City |
| Tags | real estate |
| Created | 2016-10-24T19:45:02Z |
| Publication Date | 2016-10-24T19:48:44Z |

## Description

CD8 Around Imperial Highway - Potential Sites for Homeless Service Deployment

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                       | Data Type | Render Type |
| ======== | ============== | ======================================== | ========================================== | ========= | =========== |
| No       | time           | :updated_at                              | updated_at                                 | meta_data | meta_data   |
| No       |                | address                                  | Address                                    | text      | text        |
| Yes      | numeric metric | assessor_parcel_number_county_issued     | Assessor Parcel Number (County-Issued)     | number    | text        |
| Yes      | series tag     | parcel_identification_number_city_issued | Parcel Identification Number (City Issued) | text      | text        |
| Yes      | series tag     | property_class                           | Property Class                             | text      | text        |
| Yes      | series tag     | agency_who_oversees_it                   | Agency Who Oversees It                     | text      | text        |
| Yes      | series tag     | zoning                                   | Zoning                                     | text      | text        |
| Yes      | series tag     | council_district                         | Council District                           | text      | number      |
| Yes      | series tag     | area_planning_commission                 | Area Planning Commission                   | text      | text        |
| Yes      | numeric metric | square_footage                           | Square Footage                             | number    | number      |
| Yes      | series tag     | community_plan_area                      | Community Plan Area                        | text      | text        |
| Yes      | series tag     | county_assessor_owner                    | County Assessor Owner                      | text      | text        |
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
series e:vh95-edpt d:2016-10-24T19:45:05.000Z t:property_class="Commercial Vacant Land" t:council_district=8 t:agency_who_oversees_it=CRA m:square_footage=8032.6 m:assessor_parcel_number_county_issued=6032013905

series e:vh95-edpt d:2016-10-24T19:45:05.000Z t:property_class="Commercial Vacant Land" t:council_district=8 t:agency_who_oversees_it="General Services" t:parcel_identification_number_city_issued="097-5A201 327" m:square_footage=4079.5 m:assessor_parcel_number_county_issued=6032035900

series e:vh95-edpt d:2016-10-24T19:45:05.000Z t:property_class="Vacant Land" t:council_district=8 t:agency_who_oversees_it=EWDD t:zoning=M1-1 m:square_footage=185911
```

## Meta Commands

```ls
metric m:assessor_parcel_number_county_issued p:long l:"Assessor Parcel Number (County-Issued)" t:dataTypeName=number

metric m:square_footage p:float l:"Square Footage" t:dataTypeName=number

entity e:vh95-edpt l:"CD8 Around Imperial Highway - Potential Sites for Homeless Service Deployment" t:attribution="Mayor's Operations Innovation Team" t:url=https://data.lacity.org/api/views/vh95-edpt

property e:vh95-edpt t:meta.view v:id=vh95-edpt v:category="A Livable and Sustainable City" v:averageRating=0 v:name="CD8 Around Imperial Highway - Potential Sites for Homeless Service Deployment" v:attribution="Mayor's Operations Innovation Team"

property e:vh95-edpt t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:vh95-edpt t:meta.view.owner v:id=yv94-nsgm v:profileImageUrlMedium=/api/users/yv94-nsgm/profile_images/THUMB v:profileImageUrlLarge=/api/users/yv94-nsgm/profile_images/LARGE v:screenName=JuanSVas v:profileImageUrlSmall=/api/users/yv94-nsgm/profile_images/TINY v:displayName=JuanSVas

property e:vh95-edpt t:meta.view.tableauthor v:id=yv94-nsgm v:profileImageUrlMedium=/api/users/yv94-nsgm/profile_images/THUMB v:profileImageUrlLarge=/api/users/yv94-nsgm/profile_images/LARGE v:screenName=JuanSVas v:profileImageUrlSmall=/api/users/yv94-nsgm/profile_images/TINY v:roleName=publisher v:displayName=JuanSVas
```

## Top Records

```ls
| :updated_at | address                  | assessor_parcel_number_county_issued | parcel_identification_number_city_issued | property_class         | agency_who_oversees_it | zoning    | council_district | area_planning_commission | square_footage | community_plan_area   | county_assessor_owner            | 
| =========== | ======================== | ==================================== | ======================================== | ====================== | ====================== | ========= | ================ | ======================== | ============== | ===================== | ================================ | 
| 1477338305  | 8500 S VERMONT AVE       | 6032013905                           |                                          | Commercial Vacant Land | CRA                    |           | 8                |                          | 8032.6         |                       |                                  | 
| 1477338305  | 8531 South Flower Street | 6032035900                           | 097-5A201 327                            | Commercial Vacant Land | General Services       |           | 8                |                          | 4079.5         |                       |                                  | 
| 1477338305  | 10931 South Clovis Ave   |                                      |                                          | Vacant Land            | EWDD                   | M1-1      | 8                |                          | 185911.0       |                       |                                  | 
| 1477338305  | UNKNOWN                  | 6039003900                           | 094-5A201 203                            | Under Review           | DWP                    | [Q]C2-1VL | 8                | South Los Angeles        |                | Southeast Los Angeles | L A CITY DEPT OF WATER AND POWER | 
| 1477338305  | UNKNOWN                  | 6049029900                           | 093A209 61                               | Under Review           | DWP                    | M1-1      | 8                | South Los Angeles        |                | Southeast Los Angeles | L A CITY DEPT OF WATER AND POWER | 
| 1477338305  | UNKNOWN                  | 6053012901                           | 093A203 305                              | Under Review           | DWP                    | C2-1VL    | 8                | South Los Angeles        |                | Southeast Los Angeles | L A CITY DEPT OF WATER AND POWER | 
| 1477338305  | UNKNOWN                  | 6057010902                           | 093A193 251                              | Under Review           | DWP                    | OS-1XL    | 8                | South Los Angeles        |                | South Los Angeles     | L A CITY DEPT OF WATER AND POWER | 
| 1477338305  | 10631 STANFORD AVE       | 6051029900                           |                                          | Under Review           | DWP                    |           | 8                |                          |                |                       | L A CITY DEPT OF WATER AND POWER | 
| 1477338305  | UNKNOWN                  | 6020013901                           | 099B197 442                              | Under Review           | TBD                    | C2-1VL    | 8                | South Los Angeles        |                | South Los Angeles     | L A CITY                         | 
| 1477338305  | UNKNOWN                  | 6020016900                           | 099B201 432                              | Under Review           | DWP                    | R3-1      | 8                | South Los Angeles        |                | South Los Angeles     | L A CITY DEPT OF WATER AND POWER | 
```