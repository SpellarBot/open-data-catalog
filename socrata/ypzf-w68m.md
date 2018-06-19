# Possible Expansion Sites for LRF

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/possible-expansion-sites-for-lrf) |
| Metadata | [Link](https://data.lacity.org/api/views/ypzf-w68m) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/ypzf-w68m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/ypzf-w68m/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | ypzf-w68m |
| Name | Possible Expansion Sites for LRF |
| Attribution | juan.vasquez@lacity.org |
| Category | A Livable and Sustainable City |
| Tags | real estate |
| Created | 2017-02-10T23:53:36Z |
| Publication Date | 2017-02-10T23:55:46Z |

## Description

One time exploration for possible expansion sites.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                         | Data Type | Render Type |
| ======== | ============== | ========================== | ============================ | ========= | =========== |
| No       | time           | :updated_at                | updated_at                   | meta_data | meta_data   |
| Yes      | numeric metric | assessor_parcel_number_apn | Assessor Parcel Number (APN) | number    | text        |
| Yes      | series tag     | property_class             | Property Class               | text      | text        |
| Yes      | series tag     | property_status            | Property Status              | text      | text        |
| Yes      | series tag     | managing_city_agency       | Managing City Agency         | text      | text        |
| Yes      | series tag     | zoned_as                   | Zoned As                     | text      | text        |
| Yes      | series tag     | council_district           | Council District             | text      | number      |
| Yes      | numeric metric | square_footage             | Square Footage               | number    | number      |
| Yes      | series tag     | building_name              | Building Name                | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ypzf-w68m d:2017-02-10T23:53:39.000Z t:building_name="Lanzit Industrial" t:property_status=Owned t:property_class="Vacant Land" t:managing_city_agency=EWDD t:council_district=8 t:zoned_as=M1-1 m:assessor_parcel_number_apn=6071021915 m:square_footage=185911

series e:ypzf-w68m d:2017-02-10T23:53:39.000Z t:property_status=New t:property_class="Industrial Improved" t:managing_city_agency=DWP t:council_district=2 t:zoned_as=M2-1 m:assessor_parcel_number_apn=2328029900 m:square_footage=25667.1746

series e:ypzf-w68m d:2017-02-10T23:53:39.000Z t:property_status=New t:property_class="Industrial Improved" t:managing_city_agency=DWP t:council_district=6 t:zoned_as=M2-1-CUGU m:assessor_parcel_number_apn=2537023903 m:square_footage=47116.16155
```

## Meta Commands

```ls
metric m:assessor_parcel_number_apn p:long l:"Assessor Parcel Number (APN)" t:dataTypeName=number

metric m:square_footage p:double l:"Square Footage" t:dataTypeName=number

entity e:ypzf-w68m l:"Possible Expansion Sites for LRF" t:attribution=juan.vasquez@lacity.org t:url=https://data.lacity.org/api/views/ypzf-w68m

property e:ypzf-w68m t:meta.view v:id=ypzf-w68m v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Possible Expansion Sites for LRF" v:attribution=juan.vasquez@lacity.org

property e:ypzf-w68m t:meta.view.owner v:id=yv94-nsgm v:profileImageUrlMedium=/api/users/yv94-nsgm/profile_images/THUMB v:profileImageUrlLarge=/api/users/yv94-nsgm/profile_images/LARGE v:screenName=JuanSVas v:profileImageUrlSmall=/api/users/yv94-nsgm/profile_images/TINY v:displayName=JuanSVas

property e:ypzf-w68m t:meta.view.tableauthor v:id=yv94-nsgm v:profileImageUrlMedium=/api/users/yv94-nsgm/profile_images/THUMB v:profileImageUrlLarge=/api/users/yv94-nsgm/profile_images/LARGE v:screenName=JuanSVas v:profileImageUrlSmall=/api/users/yv94-nsgm/profile_images/TINY v:roleName=publisher v:displayName=JuanSVas
```

## Top Records

```ls
| :updated_at | assessor_parcel_number_apn | property_class      | property_status    | managing_city_agency | zoned_as  | council_district | square_footage | building_name                                         | 
| =========== | ========================== | =================== | ================== | ==================== | ========= | ================ | ============== | ===================================================== | 
| 1486770819  | 6071021915                 | Vacant Land         | Owned              | EWDD                 | M1-1      | 8                | 185911.0       | Lanzit Industrial                                     | 
| 1486770819  | 2328029900                 | Industrial Improved | New                | DWP                  | M2-1      | 2                | 25667.1746     |                                                       | 
| 1486770819  | 2537023903                 | Industrial Improved | New                | DWP                  | M2-1-CUGU | 6                | 47116.16155    |                                                       | 
| 1486770819  | 6049029900                 | Under Review        | New                | DWP                  | M1-1      | 8                | 1019534.724    |                                                       | 
| 1486770819  | 6071021908                 | Vacant Land         | Surplus-Undeclared | General Services     | M1-1      | 15               | 434409.548     | Vacant Land                                           | 
| 1486770819  | 4259020900                 | Public Facility     | Surplus-Undeclared | General Services     | M2-1      | 11               | 32629.34916    | Old West LA Animal Shelter                            | 
| 1486770819  | 5205004900                 | Open Space          | Surplus-Undeclared | General Services     | M1        | 1                | 38206.89721    | Open Space                                            | 
| 1486770819  | 6001014900                 | Vacant Land         | Surplus-Undeclared | General Services     | M2-1      | 8                | 121478.0       | Vacant Land                                           | 
| 1486770819  | 4204008901                 | Industrial Improved | Owned              | General Services     | M1-1VL    | 10               | 220043.5163    | Sanitation Transfer Station - Jefferson Transfer Yard | 
| 1486770819  | 2303024903                 | Under Review        | New                | TBD                  | M2-1      | 2                | 62401.7631     |                                                       | 
```