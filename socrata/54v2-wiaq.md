# Cook County Municipalities, Number of Vacant Commercial Addresses, 3/2009 ACS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-municipalities-number-of-vacant-commercial-addresses-3-2009-acs-bdc9c) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/54v2-wiaq) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/54v2-wiaq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/54v2-wiaq/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 54v2-wiaq |
| Name | Cook County Municipalities, Number of Vacant Commercial Addresses, 3/2009 ACS |
| Attribution | Chicago Metropolitan Agency for Planning MetroPulse |
| Category | Economic Development |
| Created | 2012-08-30T20:49:33Z |
| Publication Date | 2014-10-09T22:08:06Z |

## Description

Courtesy MetroPulse

## Columns

```ls
| Included | Schema Type | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | =========== | ===================================== | ===================================== | ========= | =========== |
| Yes      | series tag  | municipality                          | Municipality                          | text      | text        |
| No       |             | number_of_vacant_commercial_addresses | Number of Vacant Commercial Addresses | number    | number      |
| Yes      | series tag  | city                                  | City                                  | text      | text        |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = number_of_vacant_commercial_addresses
```

## Data Commands

```ls
series e:54v2-wiaq d:2009-01-01T00:00:00.000Z t:municipality="Mount Prospect" m:row_number.54v2-wiaq=1

series e:54v2-wiaq d:2009-01-01T00:00:00.000Z m:row_number.54v2-wiaq=2

series e:54v2-wiaq d:2009-01-01T00:00:00.000Z t:municipality=Countryside m:row_number.54v2-wiaq=3
```

## Meta Commands

```ls
metric m:row_number.54v2-wiaq p:long l:"Row Number"

entity e:54v2-wiaq l:"Cook County Municipalities, Number of Vacant Commercial Addresses, 3/2009 ACS" t:attribution="Chicago Metropolitan Agency for Planning MetroPulse" t:url=https://datacatalog.cookcountyil.gov/api/views/54v2-wiaq

property e:54v2-wiaq t:meta.view v:id=54v2-wiaq v:category="Economic Development" v:attributionLink=https://www.cmap.illinois.gov/ v:averageRating=0 v:name="Cook County Municipalities, Number of Vacant Commercial Addresses, 3/2009 ACS" v:attribution="Chicago Metropolitan Agency for Planning MetroPulse"

property e:54v2-wiaq t:meta.view.license v:name="Public Domain"

property e:54v2-wiaq t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:54v2-wiaq t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| municipality    | number_of_vacant_commercial_addresses | city | 
| =============== | ===================================== | ==== | 
| Mount Prospect  | 415                                   |      | 
|                 |                                       |      | 
| Countryside     | 45                                    |      | 
| Riverdale       | 40                                    |      | 
| North Riverside | 58                                    |      | 
| Oak Lawn        | 163                                   |      | 
| Winnetka        | 62                                    |      | 
| Richton Park    | 25                                    |      | 
| River Grove     | 47                                    |      | 
| Palos Hills     | 45                                    |      | 
```