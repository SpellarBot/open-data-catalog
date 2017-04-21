# Facilities Management - Find it Fast - Cook County Facilities and Services Locator

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/facilities-management-find-it-fast-cook-county-facilities-and-services-locator-8e414) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/5kra-pjk3) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/5kra-pjk3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/5kra-pjk3/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 5kra-pjk3 |
| Name | Facilities Management - Find it Fast - Cook County Facilities and Services Locator |
| Attribution | Cook County Department of Facilities Management |
| Category | Economic Development |
| Created | 2011-09-19T20:29:47Z |
| Publication Date | 2014-10-09T23:16:34Z |

## Description

County facilities by location and type of services provided at that location.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| No       | time        | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag  | building_         | Building          | text      | text        |
| Yes      | series tag  | building_code     | Building Code     | text      | text        |
| Yes      | series tag  | type_of_service   | Type of Service   | text      | text        |
| Yes      | series tag  | room_or_suite     | Room or Suite     | text      | text        |
| Yes      | series tag  | main_phone_number | Main Phone Number | phone     | phone       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:5kra-pjk3 d:2011-09-19T13:29:51.000Z t:phone_number=773-801-2000 t:type_of_service=Administrative t:building_="Hawthorne Warehouse" t:building_code=Administrative m:row_number.5kra-pjk3=1

series e:5kra-pjk3 d:2011-09-19T13:29:51.000Z t:phone_number=773-843-6090 t:type_of_service=Administrative t:building_="County Warehouse" t:building_code=Administrative m:row_number.5kra-pjk3=2

series e:5kra-pjk3 d:2011-09-19T13:29:51.000Z t:type_of_service="Economic Development" t:building_="Cook County Works" t:building_code=Administrative m:row_number.5kra-pjk3=3
```

## Meta Commands

```ls
metric m:row_number.5kra-pjk3 p:long l:"Row Number"

entity e:5kra-pjk3 l:"Facilities Management - Find it Fast - Cook County Facilities and Services Locator" t:attribution="Cook County Department of Facilities Management" t:url=https://datacatalog.cookcountyil.gov/api/views/5kra-pjk3

property e:5kra-pjk3 t:meta.view v:id=5kra-pjk3 v:category="Economic Development" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/facilities_management/294/facilities_management v:averageRating=0 v:name="Facilities Management - Find it Fast - Cook County Facilities and Services Locator" v:attribution="Cook County Department of Facilities Management"

property e:5kra-pjk3 t:meta.view.license v:name="Public Domain"

property e:5kra-pjk3 t:meta.view.owner v:id=eudm-snef v:profileImageUrlMedium=/api/users/eudm-snef/profile_images/THUMB v:profileImageUrlLarge=/api/users/eudm-snef/profile_images/LARGE v:screenName="Saf Rabah" v:profileImageUrlSmall=/api/users/eudm-snef/profile_images/TINY v:lastNotificationSeenAt=1491972744 v:displayName="Saf Rabah"

property e:5kra-pjk3 t:meta.view.tableauthor v:id=eudm-snef v:profileImageUrlMedium=/api/users/eudm-snef/profile_images/THUMB v:profileImageUrlLarge=/api/users/eudm-snef/profile_images/LARGE v:screenName="Saf Rabah" v:profileImageUrlSmall=/api/users/eudm-snef/profile_images/TINY v:lastNotificationSeenAt=1491972744 v:displayName="Saf Rabah"
```

## Top Records

```ls
| :updated_at | building_               | building_code  | type_of_service      | room_or_suite | main_phone_number    | 
| =========== | ======================= | ============== | ==================== | ============= | ==================== | 
| 1316438991  | Hawthorne Warehouse     | Administrative | Administrative       |               | [773-801-2000, null] | 
| 1316438991  | County Warehouse        | Administrative | Administrative       |               | [773-843-6090, null] | 
| 1316438991  | Cook County Works       | Administrative | Economic Development |               | [null, null]         | 
| 1316438991  | Cook County Works       | Administrative | Economic Development |               | [null, null]         | 
| 1316438991  | Pension & Annuity Board | Administrative | Finance              |               | [312-603-1200, null] | 
| 1316438991  | Cook County Building    | Administrative | Administrative       |               | [312-443-5500, null] | 
| 1316438991  | Employee Assistance     | Administrative | Finance              |               | [312-603-1290, null] | 
| 1316438991  | Cook County Works       | Administrative | Economic Development |               | [null, null]         | 
| 1316438991  | County Admin Offices    | Administrative | Administrative       |               | [312-443-5500, null] | 
| 1316438991  | Cook County Works       | Administrative | Economic Development |               | [null, null]         | 
```