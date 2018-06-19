# WEBSCommodities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/webscommodities) |
| Metadata | [Link](https://data.wa.gov/api/views/p3h4-ygqm) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/p3h4-ygqm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/p3h4-ygqm/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | p3h4-ygqm |
| Name | WEBSCommodities |
| Attribution | Department of Enterprise Services |
| Category | Procurements and Contracts |
| Tags | webs |
| Created | 2014-12-09T00:43:30Z |
| Publication Date | 2014-12-09T00:46:26Z |

## Description

Commodity codes used by Washington's E-business system.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | code        | Code       | text      | text        |
| Yes      | series tag  | title       | Title      | text      | text        |
| Yes      | series tag  | category    | Category   | text      | text        |
| Yes      | series tag  | keywords    | Keywords   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:p3h4-ygqm d:2014-12-08T16:43:33.000Z t:category=Abrasives t:title="Abrasive Equipment and Tools" t:keywords="5345, 5350," t:code=005-05 m:row_number.p3h4-ygqm=1

series e:p3h4-ygqm d:2014-12-08T16:43:33.000Z t:category=Abrasives t:title="Abrasives, Coated: Cloth, Fiber, Sandpaper, etc." t:keywords=5350, t:code=005-14 m:row_number.p3h4-ygqm=2

series e:p3h4-ygqm d:2014-12-08T16:43:33.000Z t:category=Abrasives t:title="Abrasives, Sandblasting, Metal" t:keywords=5350, t:code=005-21 m:row_number.p3h4-ygqm=3
```

## Meta Commands

```ls
metric m:row_number.p3h4-ygqm p:long l:"Row Number"

entity e:p3h4-ygqm l:WEBSCommodities t:attribution="Department of Enterprise Services" t:url=https://data.wa.gov/api/views/p3h4-ygqm

property e:p3h4-ygqm t:meta.view v:id=p3h4-ygqm v:category="Procurements and Contracts" v:attributionLink=http://www.des.wa.gov/SiteCollectionDocuments/ContractingPurchasing/WEBSCommodities.xls v:averageRating=0 v:name=WEBSCommodities v:attribution="Department of Enterprise Services"

property e:p3h4-ygqm t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:p3h4-ygqm t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| :updated_at | code   | title                                                                                                     | category  | keywords          | 
| =========== | ====== | ========================================================================================================= | ========= | ================= | 
| 1418057013  | 005-05 | Abrasive Equipment and Tools                                                                              | Abrasives | 5345, 5350,       | 
| 1418057013  | 005-14 | Abrasives, Coated: Cloth, Fiber, Sandpaper, etc.                                                          | Abrasives | 5350,             | 
| 1418057013  | 005-21 | Abrasives, Sandblasting, Metal                                                                            | Abrasives | 5350,             | 
| 1418057013  | 005-28 | Abrasives, Sandblasting (Other than Metal)                                                                | Abrasives | 5350,             | 
| 1418057013  | 005-42 | Abrasives, Solid: Wheels, Stones, etc.                                                                    | Abrasives | 3460, 5345, 5350, | 
| 1418057013  | 005-56 | Abrasives, Tumbling (Wheel)                                                                               | Abrasives | 3460, 5345, 5350, | 
| 1418057013  | 005-63 | Grinding and Polishing Compounds: Carborundum, Diamond, etc. (For Valve Grinding Compounds See Class 075) | Abrasives | 5350,             | 
| 1418057013  | 005-70 | Pumice Stone                                                                                              | Abrasives | 5350,             | 
| 1418057013  | 005-75 | Recycled Abrasives Products and Supplies                                                                  | Abrasives | 5350,             | 
| 1418057013  | 005-84 | Steel Wool, Aluminum Wool, Copper Wool, and Lead Wool                                                     | Abrasives | 5350,             | 
```