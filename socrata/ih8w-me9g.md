# IDPH Licensed Campgrounds

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-licensed-campgrounds-6d04b) |
| Metadata | [Link](https://data.illinois.gov/api/views/ih8w-me9g) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/ih8w-me9g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/ih8w-me9g/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | ih8w-me9g |
| Name | IDPH Licensed Campgrounds |
| Attribution | Division of Environmental Health |
| Category | Public Health |
| Tags | licensed, campground |
| Created | 2012-08-01T21:41:22Z |
| Publication Date | 2015-05-26T18:10:19Z |

## Description

Updated May 2015.  
The Illinois Department of Public Health licenses facilities that meet the definition of a campground as defined in the Campground Licensing and Recreational Act in non-home rule units of government.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | campground_name | Campground Name | text      | text        |
| No       |             | address         | Address         | text      | text        |
| Yes      | series tag  | city            | City            | text      | text        |
| Yes      | series tag  | zip             | Zip             | text      | number      |
| Yes      | series tag  | state           | State           | text      | text        |
| Yes      | series tag  | phome           | Phone           | text      | text        |
| Yes      | series tag  | county          | County          | text      | text        |
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
series e:ih8w-me9g d:2015-05-26T06:36:02.000Z t:phome="(618) 458-6628" t:zip=62298 t:county=MONROE t:state=IL t:campground_name="FREEDOM LAKE" t:city=WATERLOO m:row_number.ih8w-me9g=1

series e:ih8w-me9g d:2015-05-26T06:36:02.000Z t:phome="(815) 547-5517" t:zip=61008 t:county=BOONE t:state=IL t:campground_name="PINE COUNTRY CAMPGROUND" t:city=BELVIDERE m:row_number.ih8w-me9g=2

series e:ih8w-me9g d:2015-05-26T06:36:02.000Z t:phome="(815) 547-7846" t:zip=61038 t:county=BOONE t:state=IL t:campground_name="HOLIDAY ACRES CAMPING RESORT" t:city="GARDEN PRAIRIE" m:row_number.ih8w-me9g=3
```

## Meta Commands

```ls
metric m:row_number.ih8w-me9g p:long l:"Row Number"

entity e:ih8w-me9g l:"IDPH Licensed Campgrounds" t:attribution="Division of Environmental Health" t:url=https://data.illinois.gov/api/views/ih8w-me9g

property e:ih8w-me9g t:meta.view v:id=ih8w-me9g v:category="Public Health" v:attributionLink=http://www.dph.illinois.gov/topics-services/environmental-health-protection/recreation/campgrounds-youth-camps v:averageRating=0 v:name="IDPH Licensed Campgrounds" v:attribution="Division of Environmental Health"

property e:ih8w-me9g t:meta.view.license v:name="Public Domain"

property e:ih8w-me9g t:meta.view.owner v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:displayName="IDPH Staff"

property e:ih8w-me9g t:meta.view.tableauthor v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:roleName=publisher v:displayName="IDPH Staff"
```

## Top Records

```ls
| :updated_at | campground_name              | address                   | city           | zip   | state | phome          | county  | 
| =========== | ============================ | ========================= | ============== | ===== | ===== | ============== | ======= | 
| 1432622162  | FREEDOM LAKE                 | 5329 SPORTSMAN RD         | WATERLOO       | 62298 | IL    | (618) 458-6628 | MONROE  | 
| 1432622162  | PINE COUNTRY CAMPGROUND      | 5710 SHATTUCK RD          | BELVIDERE      | 61008 | IL    | (815) 547-5517 | BOONE   | 
| 1432622162  | HOLIDAY ACRES CAMPING RESORT | 7050 EPWORTH RD           | GARDEN PRAIRIE | 61038 | IL    | (815) 547-7846 | BOONE   | 
| 1432622162  | LOWDEN STATE PARK            | 1411 N. RIVER ROAD        | OREGON         | 61061 | IL    | (815) 732-6828 | OGLE    | 
| 1432622162  | HANSEN'S HIDEWAY             | 2916 HARMONY ROAD         | OREGON         | 61061 | IL    | (815) 732-6489 | OGLE    | 
| 1432622162  | CAMPINGISLANDS.COM INC       | 8195 RT SOUTH             | DIXON          | 61021 | IL    | (815) 595-4255 | OGLE    | 
| 1432622162  | LINCOLN TRAIL ST PK          | 16985 E 1350TH ROAD       | MARSHALL       | 62441 | IL    | (217) 826-2222 | CLARK   | 
| 1432622162  | MORAINE VIEW STATE PARK      | RR 2 BOX 110              | LEROY          | 61752 | IL    | (309) 724-8032 | MC LEAN | 
| 1432622162  | MISSISSIPPI PALISADES ST PK  | 16327 IL RT 84            | SAVANNA        | 61074 | IL    | (815) 273-2731 | CARROLL | 
| 1432622162  | PERE MARQUETTE STATE PARK    | 13112 VISITOR CENTER LANE | GRAFTON        | 62037 | IL    | (618) 786-3323 | JERSEY  | 
```