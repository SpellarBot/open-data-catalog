# IDPH Hospital Directory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-hospital-directory-e4ad3) |
| Metadata | [Link](https://data.illinois.gov/api/views/wsms-teqm) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/wsms-teqm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/wsms-teqm/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | wsms-teqm |
| Name | IDPH Hospital Directory |
| Attribution | Division of Health Care Facilities and Programs |
| Category | Public Health |
| Tags | hospital |
| Created | 2012-01-31T18:49:14Z |
| Publication Date | 2017-01-06T18:47:33Z |

## Description

Current as of January 2017

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type | Render Type |
| ======== | =========== | ======================= | ======================= | ========= | =========== |
| No       | time        | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag  | hospital_name           | Hospital Name           | text      | text        |
| Yes      | series tag  | type_of_hospital        | Type of Hospital        | text      | text        |
| No       |             | address                 | Address                 | text      | text        |
| Yes      | series tag  | city                    | City                    | text      | text        |
| Yes      | series tag  | county                  | County                  | text      | text        |
| Yes      | series tag  | zip                     | Zip                     | text      | number      |
| Yes      | series tag  | phone                   | Phone                   | phone     | phone       |
| Yes      | series tag  | license_                | License #               | text      | text        |
| Yes      | series tag  | license_expiration_date | License Expiration Date | html      | html        |
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
series e:wsms-teqm d:2017-01-06T18:42:21.000Z t:license_=0005728 t:zip=62656 t:hospital_name="Abraham Lincoln Hospital" t:license_expiration_date=06/30/17 t:phone_number="(217) 732-2161" t:county=Logan t:type_of_hospital="Critical Access Hospital" t:city=Lincoln m:row_number.wsms-teqm=1

series e:wsms-teqm d:2017-01-06T18:42:21.000Z t:license_=0005496 t:zip=60440 t:hospital_name="Adventist Bolingbrook Hospital" t:license_expiration_date=01/10/18 t:phone_number="(630) 312-5000" t:county=Will t:type_of_hospital="General Hospital" t:city=Bolingbrook m:row_number.wsms-teqm=2

series e:wsms-teqm d:2017-01-06T18:42:21.000Z t:license_=0003814 t:zip=60139 t:hospital_name="Adventist GlenOaks Hospital" t:license_expiration_date=06/30/17 t:phone_number="(630) 545-8000" t:county="Du Page" t:type_of_hospital="General Hospital" t:city="Glendale Heights" m:row_number.wsms-teqm=3
```

## Meta Commands

```ls
metric m:row_number.wsms-teqm p:long l:"Row Number"

entity e:wsms-teqm l:"IDPH Hospital Directory" t:attribution="Division of Health Care Facilities and Programs" t:url=https://data.illinois.gov/api/views/wsms-teqm

property e:wsms-teqm t:meta.view v:id=wsms-teqm v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/about/ohcr.htm v:averageRating=0 v:name="IDPH Hospital Directory" v:attribution="Division of Health Care Facilities and Programs"

property e:wsms-teqm t:meta.view.owner v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:displayName="IDPH Staff"

property e:wsms-teqm t:meta.view.tableauthor v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:roleName=publisher v:displayName="IDPH Staff"
```

## Top Records

```ls
| :updated_at | hospital_name                                                                   | type_of_hospital         | address                        | city             | county   | zip   | phone                  | license_ | license_expiration_date | 
| =========== | =============================================================================== | ======================== | ============================== | ================ | ======== | ===== | ====================== | ======== | ======================= | 
| 1483728141  | Abraham Lincoln Hospital                                                        | Critical Access Hospital | 200 Stahllhut Drive            | Lincoln          | Logan    | 62656 | [(217) 732-2161, null] | 0005728  | 06/30/17                | 
| 1483728141  | Adventist Bolingbrook Hospital                                                  | General Hospital         | 500 Remington Boulevard        | Bolingbrook      | Will     | 60440 | [(630) 312-5000, null] | 0005496  | 01/10/18                | 
| 1483728141  | Adventist GlenOaks Hospital                                                     | General Hospital         | 701 Winthrop Avenue            | Glendale Heights | Du Page  | 60139 | [(630) 545-8000, null] | 0003814  | 06/30/17                | 
| 1483728141  | Adventist Midwest Health - DBA Adventist LaGrange Memorial Hospital             | General Hospital         | 5101 South Willow Springs Road | LaGrange         | Cook     | 60525 | [(708) 245-9000, null] | 0005967  | 01/31/18                | 
| 1483728141  | Adventist Midwest Health - DBA Adventist Hinsdale Hospital                      | General Hospital         | 120 North Oak Street           | Hinsdale         | Du Page  | 60521 | [(630) 856-9000, null] | 0000976  | 12/31/17                | 
| 1483728141  | Advocate Christ Hospital & Medical Center                                       | General Hospital         | 4440 W. 95th Street            | Oak Lawn         | Cook     | 60453 | [(708) 684-8000, null] | 0000315  | 12/31/17                | 
| 1483728141  | Advocate Condell Medical Center                                                 | General Hospital         | 801 South Milwaukee Avenue     | Libertyville     | Lake     | 60048 | [(847) 362-2900, null] | 0005579  | 11/30/17                | 
| 1483728141  | Advocate Health and Hospitals Corporation - DBA Good Shepherd Hospital          | General Hospital         | 450 West Highway 22            | Barrington       | Lake     | 60010 | [(847) 381-9600, null] | 0003475  | 12/31/17                | 
| 1483728141  | Advocate Health and Hospitals Corporation - DBA Advocate Eureka Hospital        | Critical Access Hospital | 101 South Major Street         | Eureka           | Woodford | 61530 | [(309) 467-2371, null] | 0005652  | 01/05/18                | 
| 1483728141  | Advocate Health and Hospitals Corporation - DBA Advocate Bromenn Medical Center | General Hospital         | 1304 Franklin Avenue           | Normal           | Mc Lean  | 61761 | [(309) 454-1400, null] | 0005645  | 01/05/18                | 
```