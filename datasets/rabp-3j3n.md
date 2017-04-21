# Possible City-Owned Sites in CD8 for Homeless Efforts - No Square Footage

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/possible-city-owned-sites-in-cd8-for-homeless-efforts-no-square-footage) |
| Metadata | [Link](https://data.lacity.org/api/views/rabp-3j3n) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/rabp-3j3n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/rabp-3j3n/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | rabp-3j3n |
| Name | Possible City-Owned Sites in CD8 for Homeless Efforts - No Square Footage |
| Attribution | Mayor's Operations Innovation Team |
| Tags | homeslessnes |
| Created | 2016-11-14T22:50:56Z |
| Publication Date | 2016-11-14T22:53:22Z |

## Description

Possible City-Owned Sites in CD8 for Homeless Efforts. One-time effort across Mayor's Office teams. This is a second data set for properties currently lacking square footage information.

## Columns

```ls
| Included | Schema Type    | Field Name                                   | Name                                           | Data Type | Render Type |
| ======== | ============== | ============================================ | ============================================== | ========= | =========== |
| No       | time           | :updated_at                                  | updated_at                                     | meta_data | meta_data   |
| Yes      | numeric metric | assessor_parcel_number_county_issued_apn     | Assessor Parcel Number (County-Issued APN)     | number    | number      |
| Yes      | series tag     | property_class                               | Property Class                                 | text      | text        |
| No       |                | address                                      | Address                                        | text      | text        |
| Yes      | series tag     | inventory_type                               | Inventory Type                                 | text      | text        |
| Yes      | series tag     | zoned_as                                     | Zoned As                                       | text      | text        |
| Yes      | series tag     | area_planning_commission                     | Area Planning Commission                       | text      | text        |
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
series e:rabp-3j3n d:2016-11-14T22:50:58.000Z t:parcel_identification_number_city_issued_pin="117B189   466" t:inventory_type="General Services" t:property_class="Vacant Land" m:assessor_parcel_number_county_issued_apn=5042010900

series e:rabp-3j3n d:2016-11-14T22:50:58.000Z t:parcel_identification_number_city_issued_pin="105B189  1012" t:inventory_type=TBD t:property_class="Under Review" t:zoned_as=[Q]M1-1VL t:area_planning_commission="South Los Angeles" m:assessor_parcel_number_county_issued_apn=4007016900

series e:rabp-3j3n d:2016-11-14T22:50:58.000Z t:parcel_identification_number_city_issued_pin="105B189  1335" t:inventory_type=TBD t:property_class="Under Review" t:zoned_as=[Q]CM-1VL t:area_planning_commission="South Los Angeles" m:assessor_parcel_number_county_issued_apn=4007019900
```

## Meta Commands

```ls
metric m:assessor_parcel_number_county_issued_apn p:long l:"Assessor Parcel Number (County-Issued APN)" t:dataTypeName=number

entity e:rabp-3j3n l:"Possible City-Owned Sites in CD8 for Homeless Efforts - No Square Footage" t:attribution="Mayor's Operations Innovation Team" t:url=https://data.lacity.org/api/views/rabp-3j3n

property e:rabp-3j3n t:meta.view v:id=rabp-3j3n v:averageRating=0 v:name="Possible City-Owned Sites in CD8 for Homeless Efforts - No Square Footage" v:attribution="Mayor's Operations Innovation Team"

property e:rabp-3j3n t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:rabp-3j3n t:meta.view.owner v:id=yv94-nsgm v:profileImageUrlMedium=/api/users/yv94-nsgm/profile_images/THUMB v:profileImageUrlLarge=/api/users/yv94-nsgm/profile_images/LARGE v:screenName=JuanSVas v:profileImageUrlSmall=/api/users/yv94-nsgm/profile_images/TINY v:displayName=JuanSVas

property e:rabp-3j3n t:meta.view.tableauthor v:id=yv94-nsgm v:profileImageUrlMedium=/api/users/yv94-nsgm/profile_images/THUMB v:profileImageUrlLarge=/api/users/yv94-nsgm/profile_images/LARGE v:screenName=JuanSVas v:profileImageUrlSmall=/api/users/yv94-nsgm/profile_images/TINY v:roleName=publisher v:displayName=JuanSVas
```

## Top Records

```ls
| :updated_at | assessor_parcel_number_county_issued_apn | property_class | address        | inventory_type   | zoned_as  | area_planning_commission | parcel_identification_number_city_issued_pin | 
| =========== | ======================================== | ============== | ============== | ================ | ========= | ======================== | ============================================ | 
| 1479163858  | 5042010900                               | Vacant Land    | Rodeo/Cimarron | General Services |           |                          | 117B189 466                                  | 
| 1479163858  | 4007016900                               | Under Review   | UNKNOWN        | TBD              | [Q]M1-1VL | South Los Angeles        | 105B189 1012                                 | 
| 1479163858  | 4007019900                               | Under Review   | UNKNOWN        | TBD              | [Q]CM-1VL | South Los Angeles        | 105B189 1335                                 | 
| 1479163858  | 4007020900                               | Under Review   | UNKNOWN        | TBD              | [Q]CM-1VL | South Los Angeles        | 105B189 1942                                 | 
| 1479163858  | 6002001900                               | Under Review   | UNKNOWN        | TBD              | M1-1      | South Los Angeles        | 108B193 1351                                 | 
```