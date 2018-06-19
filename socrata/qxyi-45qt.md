# Sales Tax Registration

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sales-tax-registration) |
| Metadata | [Link](https://data.iowa.gov/api/views/qxyi-45qt) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/qxyi-45qt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/qxyi-45qt/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | qxyi-45qt |
| Name | Sales Tax Registration |
| Attribution | Iowa Department of Revenue, Sales Tax Registration |
| Category | Economy |
| Tags | sales tax, taxes, business, retail, sales, revenue |
| Created | 2014-12-04T19:02:18Z |
| Publication Date | 2017-04-20T20:35:54Z |

## Description

This dataset is a record of active Iowa businesses that are registered to collect and remit retail sales tax in the State of Iowa.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type | Render Type |
| ======== | =========== | ========================= | ========================= | ========= | =========== |
| No       | time        | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag  | permit                    | Permit                    | text      | text        |
| Yes      | series tag  | business_name             | Business Name             | text      | text        |
| No       |             | business_address          | Business Address          | text      | text        |
| Yes      | series tag  | city                      | City                      | text      | text        |
| Yes      | series tag  | zip_code                  | Zip Code                  | text      | text        |
| Yes      | series tag  | county_number             | County Number             | text      | text        |
| Yes      | series tag  | county                    | County                    | text      | text        |
| Yes      | series tag  | business_code             | Business Code             | text      | number      |
| Yes      | series tag  | business_code_description | Business Code Description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = business_address
```

## Data Commands

```ls
series e:qxyi-45qt d:2017-04-20T19:09:15.000Z t:business_name="Wilson Marketing" t:county_number=63 t:zip_code=50138 t:county=Marion t:permit=163009563 t:business_code=4422 t:business_code_description="Home Furnishings Stores" t:city=Knoxville m:row_number.qxyi-45qt=1

series e:qxyi-45qt d:2017-04-20T19:09:15.000Z t:business_name="Angove Construction" t:county_number=63 t:zip_code=50138 t:county=Marion t:permit=163005693 t:business_code=2331 t:business_code_description="General Contractors" t:city=Knoxville m:row_number.qxyi-45qt=2

series e:qxyi-45qt d:2017-04-20T19:09:15.000Z t:business_name="Ancell Dental Pllc" t:county_number=63 t:zip_code=50138 t:county=Marion t:permit=163011364 t:business_code=6212 t:business_code_description="Offices Of Dentist" t:city=Knoxville m:row_number.qxyi-45qt=3
```

## Meta Commands

```ls
metric m:row_number.qxyi-45qt p:long l:"Row Number"

entity e:qxyi-45qt l:"Sales Tax Registration" t:attribution="Iowa Department of Revenue, Sales Tax Registration" t:url=https://data.iowa.gov/api/views/qxyi-45qt

property e:qxyi-45qt t:meta.view v:id=qxyi-45qt v:category=Economy v:averageRating=0 v:name="Sales Tax Registration" v:attribution="Iowa Department of Revenue, Sales Tax Registration"

property e:qxyi-45qt t:meta.view.license v:name="Public Domain"

property e:qxyi-45qt t:meta.view.owner v:id=y22p-i8y2 v:profileImageUrlMedium=/api/users/y22p-i8y2/profile_images/THUMB v:profileImageUrlLarge=/api/users/y22p-i8y2/profile_images/LARGE v:screenName="Revenue, Research and Analysis" v:profileImageUrlSmall=/api/users/y22p-i8y2/profile_images/TINY v:displayName="Revenue, Research and Analysis"

property e:qxyi-45qt t:meta.view.tableauthor v:id=y22p-i8y2 v:profileImageUrlMedium=/api/users/y22p-i8y2/profile_images/THUMB v:profileImageUrlLarge=/api/users/y22p-i8y2/profile_images/LARGE v:screenName="Revenue, Research and Analysis" v:profileImageUrlSmall=/api/users/y22p-i8y2/profile_images/TINY v:roleName=editor v:displayName="Revenue, Research and Analysis"
```

## Top Records

```ls
| :updated_at | permit    | business_name                 | business_address  | city           | zip_code | county_number | county | business_code | business_code_description                                               | 
| =========== | ========= | ============================= | ================= | ============== | ======== | ============= | ====== | ============= | ======================================================================= | 
| 1492715355  | 163009563 | Wilson Marketing              | 222 E Robinson St | Knoxville      | 50138    | 63            | Marion | 4422          | Home Furnishings Stores                                                 | 
| 1492715355  | 163005693 | Angove Construction           | 1001 W Ash St     | Knoxville      | 50138    | 63            | Marion | 2331          | General Contractors                                                     | 
| 1492715355  | 163011364 | Ancell Dental Pllc            | 112 S 1st St      | Knoxville      | 50138    | 63            | Marion | 6212          | Offices Of Dentist                                                      | 
| 1492715355  | 163010529 | Van Sant Distributing Inc     | 75 Truman Rd      | Pella          | 50219    | 63            | Marion | 4841          | Truck, General Freight Local, and General Freight Long Distance Haulers | 
| 1492715355  | 163010121 | From Heart And Hands          | 102 Park Ridge Dr | Rural          | 50214    | 63            | Marion | 4487          | Hobby and Toy Stores                                                    | 
| 1492715355  | 163011441 | Maxim Trucking Inc            | 1608 Fifield Rd   | Pella          | 50219    | 63            | Marion | 4841          | Truck, General Freight Local, and General Freight Long Distance Haulers | 
| 1492715355  | 163011118 | Iowa Home Air Audit           | 101 S Polk St     | Pleasantville  | 50225    | 63            | Marion | 5419          | Services (NEC-Not Elsewhere Classified)                                 | 
| 1492715355  | 163006418 | Ben Shinn Trucking Inc        | 1501 E Main St    | Knoxville      | 50138    | 63            | Marion | 4841          | Truck, General Freight Local, and General Freight Long Distance Haulers | 
| 1492715355  | 163010456 | Silver Lining Enterprises Llc | 733 Franklin St   | Pella          | 50219    | 63            | Marion | 4421          | Furniture Stores                                                        | 
| 1492715355  | 163011275 | Land Of Ahhhs                 | 1879 40th Pl      | Melcher-Dallas | 50062    | 63            | Marion | 4487          | Hobby and Toy Stores                                                    | 
```