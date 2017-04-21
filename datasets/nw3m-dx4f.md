# Possible City-Owned Sites in CD8 for Homeless Efforts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/possible-city-owned-sites-in-cd8-for-homeless-efforts) |
| Metadata | [Link](https://data.lacity.org/api/views/nw3m-dx4f) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/nw3m-dx4f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/nw3m-dx4f/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | nw3m-dx4f |
| Name | Possible City-Owned Sites in CD8 for Homeless Efforts |
| Attribution | Mayor's Operations Innovation Team |
| Category | A Livable and Sustainable City |
| Tags | homelessness |
| Created | 2016-11-14T22:39:58Z |
| Publication Date | 2016-11-14T22:42:32Z |

## Description

Possible City-Owned Sites in CD8 for Homeless Efforts. One-time effort across Mayor's Office teams.

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                           | Data Type | Render Type |
| ======== | ============== | ============================================ | ============================================== | ========= | =========== |
| No       | time           | :updated_at                                  | updated_at                                     | meta_data | meta_data   |
| Yes      | numeric metric | assessor_parcel_number_county_issued_apn     | Assessor Parcel Number (County-Issued APN)     | number    | number      |
| Yes      | series tag     | property_class                               | Property Class                                 | text      | text        |
| No       |                | address                                      | Address                                        | text      | text        |
| Yes      | series tag     | city_agency_responsible                      | City Agency Responsible                        | text      | text        |
| Yes      | series tag     | zoned_as                                     | Zoned As                                       | text      | text        |
| Yes      | series tag     | area_planning_commission                     | Area Planning Commission                       | text      | text        |
| Yes      | numeric metric | square_footage                               | Square Footage                                 | number    | number      |
| Yes      | series tag     | parcel_identification_number_city_issued_pin | Parcel Identification Number (City-Issued PIN) | text      | text        |
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
series e:nw3m-dx4f d:2016-11-14T22:40:00.000Z t:city_agency_responsible=DWP t:property_class="Under Review" m:square_footage=20811 m:assessor_parcel_number_county_issued_apn=6051029900

series e:nw3m-dx4f d:2016-11-14T22:40:00.000Z t:city_agency_responsible=HCID t:property_class="Residential Improved" m:square_footage=14513 m:assessor_parcel_number_county_issued_apn=6038001902

series e:nw3m-dx4f d:2016-11-14T22:40:00.000Z t:parcel_identification_number_city_issued_pin="093A201   322" t:city_agency_responsible=TBD t:property_class="Under Review" t:zoned_as=OS-1XL t:area_planning_commission="South Los Angeles" m:square_footage=13407 m:assessor_parcel_number_county_issued_apn=6054031900
```

## Meta Commands

```ls
metric m:assessor_parcel_number_county_issued_apn p:long l:"Assessor Parcel Number (County-Issued APN)" t:dataTypeName=number

metric m:square_footage p:integer l:"Square Footage" t:dataTypeName=number

entity e:nw3m-dx4f l:"Possible City-Owned Sites in CD8 for Homeless Efforts" t:attribution="Mayor's Operations Innovation Team" t:url=https://data.lacity.org/api/views/nw3m-dx4f

property e:nw3m-dx4f t:meta.view v:id=nw3m-dx4f v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Possible City-Owned Sites in CD8 for Homeless Efforts" v:attribution="Mayor's Operations Innovation Team"

property e:nw3m-dx4f t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:nw3m-dx4f t:meta.view.owner v:id=yv94-nsgm v:profileImageUrlMedium=/api/users/yv94-nsgm/profile_images/THUMB v:profileImageUrlLarge=/api/users/yv94-nsgm/profile_images/LARGE v:screenName=JuanSVas v:profileImageUrlSmall=/api/users/yv94-nsgm/profile_images/TINY v:displayName=JuanSVas

property e:nw3m-dx4f t:meta.view.tableauthor v:id=yv94-nsgm v:profileImageUrlMedium=/api/users/yv94-nsgm/profile_images/THUMB v:profileImageUrlLarge=/api/users/yv94-nsgm/profile_images/LARGE v:screenName=JuanSVas v:profileImageUrlSmall=/api/users/yv94-nsgm/profile_images/TINY v:roleName=publisher v:displayName=JuanSVas
```

## Top Records

```ls
| :updated_at | assessor_parcel_number_county_issued_apn | property_class       | address                    | city_agency_responsible | zoned_as | area_planning_commission | square_footage | parcel_identification_number_city_issued_pin | 
| =========== | ======================================== | ==================== | ========================== | ======================= | ======== | ======================== | ============== | ============================================ | 
| 1479163200  | 6051029900                               | Under Review         | 10631 STANFORD AVE         | DWP                     |          |                          | 20811          |                                              | 
| 1479163200  | 6038001902                               | Residential Improved | 461 W 87TH ST              | HCID                    |          |                          | 14513          |                                              | 
| 1479163200  | 6054031900                               | Under Review         | UNKNOWN                    | TBD                     | OS-1XL   | South Los Angeles        | 13407          | 093A201 322                                  | 
| 1479163200  | 6054025900                               | Under Review         | UNKNOWN                    | TBD                     | OS-1XL   | South Los Angeles        | 13337          | 093A201 325                                  | 
| 1479163200  | 6053013901                               | Under Review         | UNKNOWN                    | TBD                     | OS-1XL   | South Los Angeles        | 12712          | 093A203 303                                  | 
| 1479163200  | 4006004900                               | Residential Improved | 6108 South Victoria Avenue | HCID                    |          | South Los Angeles        | 11375          |                                              | 
| 1479163200  | 4006019901                               | Residential Improved | 3460 Hyde Park Boulevard   | HCID                    |          | South Los Angeles        | 11355          |                                              | 
```