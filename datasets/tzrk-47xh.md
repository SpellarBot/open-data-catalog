# Licensed Insurance Companies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/licensed-insurance-companies) |
| Metadata | [Link](https://data.iowa.gov/api/views/tzrk-47xh) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/tzrk-47xh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/tzrk-47xh/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | tzrk-47xh |
| Name | Licensed Insurance Companies |
| Attribution | Iowa Insurance Division |
| Category | Economy |
| Tags | life, health, property, casualty, insurance, insurer, company |
| Created | 2015-09-11T15:29:22Z |
| Publication Date | 2016-06-30T13:45:36Z |

## Description

Insurance companies licensed in Iowa

## Columns

```ls
| Included | Schema Type | Field Name            | Name                       | Data Type | Render Type |
| ======== | =========== | ===================== | ========================== | ========= | =========== |
| No       | time        | :updated_at           | updated_at                 | meta_data | meta_data   |
| Yes      | series tag  | company_name          | Company Name               | text      | text        |
| Yes      | series tag  | company_type          | Company Type               | text      | text        |
| Yes      | series tag  | naic_number           | NAIC Number                | text      | text        |
| Yes      | series tag  | iowa_license_number   | Iowa License Number        | text      | text        |
| Yes      | series tag  | iowa_domiciled        | Iowa Domiciled             | checkbox  | checkbox    |
| No       |             | address1              | Company Address 1          | text      | text        |
| No       |             | address2              | Company Address 2          | text      | text        |
| Yes      | series tag  | company_city          | Company City               | text      | text        |
| Yes      | series tag  | company_state         | Company State              | text      | text        |
| Yes      | series tag  | company_zip           | Company Zip                | text      | text        |
| Yes      | series tag  | telephone             | Telephone                  | text      | text        |
| No       |             | alternate_address1    | Alternate Address 1        | text      | text        |
| No       |             | alternate_address2    | Alternate Address 2        | text      | text        |
| Yes      | series tag  | alternate_city        | Alternate City             | text      | text        |
| Yes      | series tag  | alternate_state       | Alternate State            | text      | text        |
| Yes      | series tag  | alternate_zip         | Alternate Zip              | text      | text        |
| Yes      | series tag  | alternate_telephone   | Alternate Phone            | text      | text        |
| Yes      | series tag  | business_license_type | Business License Type      | text      | text        |
| Yes      | series tag  | ownership_type        | Ownership Type             | text      | text        |
| Yes      | series tag  | fdba                  | Formerly Doing Business As | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address1,address2,alternate_address1,alternate_address2
```

## Data Commands

```ls
series e:tzrk-47xh d:2017-02-22T23:00:39.000Z t:iowa_domiciled=true t:company_state=IA t:ownership_type=Mutual t:company_name="Home Mutual Insurance Association of Carroll County Iowa" t:company_type="County Mutual" t:business_license_type="County Mutual" t:iowa_license_number=0026 t:telephone=712-655-3076 t:naic_number=14263 t:fdba="German Mutual Fire, Lightning, Tornado, Wind, & Cyclone Association" t:company_zip=51455 t:company_city=Manning m:row_number.tzrk-47xh=1

series e:tzrk-47xh d:2017-02-22T23:00:39.000Z t:iowa_domiciled=true t:company_state=IA t:ownership_type=Mutual t:company_name="Svea Mutual Insurance Association" t:company_type="County Mutual" t:business_license_type="County Mutual" t:iowa_license_number=0075 t:telephone=319-254-2288 t:naic_number=15430 t:fdba="Svea Mutual Fire Insurance Association" t:company_zip=52652 t:company_city=Swedesburg m:row_number.tzrk-47xh=2

series e:tzrk-47xh d:2017-02-22T23:00:39.000Z t:iowa_domiciled=true t:company_state=IA t:ownership_type=Mutual t:company_name="Howard County Mutual Insurance Association" t:company_type="County Mutual" t:business_license_type="County Mutual" t:iowa_license_number=0076 t:telephone=563-547-2450 t:naic_number=15412 t:fdba="Farmers Mutual Insurance Association of Cresco" t:company_zip=52136 t:company_city=Cresco m:row_number.tzrk-47xh=3
```

## Meta Commands

```ls
metric m:row_number.tzrk-47xh p:long l:"Row Number"

entity e:tzrk-47xh l:"Licensed Insurance Companies" t:attribution="Iowa Insurance Division" t:url=https://data.iowa.gov/api/views/tzrk-47xh

property e:tzrk-47xh t:meta.view v:id=tzrk-47xh v:category=Economy v:averageRating=0 v:name="Licensed Insurance Companies" v:attribution="Iowa Insurance Division"

property e:tzrk-47xh t:meta.view.owner v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:displayName="Iowa Insurance Division (Commerce)"

property e:tzrk-47xh t:meta.view.tableauthor v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:roleName=publisher v:displayName="Iowa Insurance Division (Commerce)"
```

## Top Records

```ls
| :updated_at | company_name                                             | company_type  | naic_number | iowa_license_number | iowa_domiciled | address1           | address2          | company_city | company_state | company_zip | telephone    | alternate_address1 | alternate_address2 | alternate_city | alternate_state | alternate_zip | alternate_telephone | business_license_type | ownership_type | fdba                                                                | 
| =========== | ======================================================== | ============= | =========== | =================== | ============== | ================== | ================= | ============ | ============= | =========== | ============ | ================== | ================== | ============== | =============== | ============= | =================== | ===================== | ============== | =================================================================== | 
| 1487804439  | Home Mutual Insurance Association of Carroll County Iowa | County Mutual | 14263       | 0026                | true           | P. O. Box 367      |                   | Manning      | IA            | 51455       | 712-655-3076 |                    |                    |                |                 |               |                     | County Mutual         | Mutual         | German Mutual Fire, Lightning, Tornado, Wind, & Cyclone Association | 
| 1487804439  | Svea Mutual Insurance Association                        | County Mutual | 15430       | 0075                | true           | P.O. Box 35        | 1903 140th Street | Swedesburg   | IA            | 52652       | 319-254-2288 |                    |                    |                |                 |               |                     | County Mutual         | Mutual         | Svea Mutual Fire Insurance Association                              | 
| 1487804439  | Howard County Mutual Insurance Association               | County Mutual | 15412       | 0076                | true           | P. O. Box 87       |                   | Cresco       | IA            | 52136       | 563-547-2450 |                    |                    |                |                 |               |                     | County Mutual         | Mutual         | Farmers Mutual Insurance Association of Cresco                      | 
| 1487804439  | Farmers Mutual Insurance Association                     | County Mutual | 15399       | 0141                | true           | P.O. Box 59        |                   | Traer        | IA            | 50675-0059  | 319-478-2585 |                    |                    |                |                 |               |                     | County Mutual         | Mutual         | Mutual Fire Insurance Association of German Farmers of Tama County  | 
| 1487804440  | Family Benefit Society Inc.                              | Benevolent    |             | 1525                | true           | PO Box 7734        |                   | Urbandale    | IA            | 50323       | 515-276-5387 |                    |                    |                |                 |               |                     | Benevolent            | Stock          |                                                                     | 
| 1487804440  | United Benefit Society Inc.                              | Benevolent    |             | 1543                | true           | PO Box 7734        |                   | Urbandale    | IA            | 50323       | 515-276-5387 |                    |                    |                |                 |               |                     | Benevolent            | Stock          |                                                                     | 
| 1492470229  | German Mutual Insurance Association                      | County Mutual | 15406       | 0022                | true           | Highway 4 & 7      | Box 160           | Pomeroy      | IA            | 50575       | 712-468-2215 |                    |                    |                |                 |               |                     | County Mutual         | Mutual         |                                                                     | 
| 1487804439  | Sherrill Mutual Fire Insurance Association               | County Mutual | 15428       | 0058                | true           | P. O. Box 19       |                   | Sherrill     | IA            | 52073       | 563-552-1715 |                    |                    |                |                 |               |                     | County Mutual         | Mutual         |                                                                     | 
| 1487804439  | Farmers Mutual Insurance Association                     | County Mutual | 15397       | 0062                | true           | Box 246            |                   | Fayette      | IA            | 52142       | 563-425-4176 |                    |                    |                |                 |               |                     | County Mutual         | Mutual         | Farmer Mutual Fire Insurance Association                            | 
| 1487804439  | Farmers Mutual Insurance Association                     | County Mutual | 15398       | 0067                | true           | 108 North Vine St. | PO Box 390        | Jefferson    | IA            | 50129       | 515-386-2178 |                    |                    |                |                 |               |                     | County Mutual         | Mutual         | Farmers Mutual Fire and Lightning Insurance Association             | 
```