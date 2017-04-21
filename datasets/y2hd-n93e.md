# Ownership

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ownership-1ab1b) |
| Metadata | [Link](https://data.medicare.gov/api/views/y2hd-n93e) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/y2hd-n93e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/y2hd-n93e/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | y2hd-n93e |
| Name | Ownership |
| Category | Nursing Home Compare |
| Tags | nursing home, nhc, general information |
| Created | 2013-07-11T15:01:31Z |
| Publication Date | 2017-03-22T01:54:50Z |

## Description

A list of ownership information for currently active nursing homes.

## Columns

```ls
| Included | Schema Type | Field Name              | Name                                        | Data Type     | Render Type   |
| ======== | =========== | ======================= | =========================================== | ============= | ============= |
| Yes      | series tag  | federal_provider_number | Federal Provider Number                     | text          | text          |
| Yes      | series tag  | provider_name           | Provider Name                               | text          | text          |
| No       |             | provider_address        | Provider Address                            | text          | text          |
| Yes      | series tag  | provider_city           | Provider City                               | text          | text          |
| Yes      | series tag  | provider_state          | Provider State                              | text          | text          |
| Yes      | series tag  | provider_zip_code       | Provider Zip Code                           | text          | text          |
| Yes      | series tag  | role_description        | Role played by Owner or Manager in Facility | text          | text          |
| Yes      | series tag  | owner_type              | Owner Type                                  | text          | text          |
| Yes      | series tag  | owner_name              | Owner Name                                  | text          | text          |
| Yes      | series tag  | ownership_percentage    | Ownership Percentage                        | text          | text          |
| No       |             | association_date        | Association Date                            | text          | text          |
| Yes      | time        | processing_date         | Processing Date                             | calendar_date | calendar_date |
```

## Time Field

```ls
Value = processing_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = provider_address,association_date
```

## Data Commands

```ls
series e:y2hd-n93e d:2017-03-01T00:00:00.000Z t:role_description="5% OR GREATER DIRECT OWNERSHIP INTEREST" t:owner_type=Organization t:ownership_percentage=100% t:owner_name="GENESIS HOLDINGS LLC" t:federal_provider_number=015019 t:provider_zip_code=36025 t:provider_state=AL t:provider_name="MERRY WOOD LODGE CARE AND REHABILITATION CENTER" t:provider_city=ELMORE m:row_number.y2hd-n93e=1

series e:y2hd-n93e d:2017-03-01T00:00:00.000Z t:role_description="5% OR GREATER INDIRECT OWNERSHIP INTEREST" t:owner_type=Organization t:ownership_percentage="NO PERCENTAGE PROVIDED" t:owner_name="DONNA REIS 1995 FAM TR" t:federal_provider_number=015019 t:provider_zip_code=36025 t:provider_state=AL t:provider_name="MERRY WOOD LODGE CARE AND REHABILITATION CENTER" t:provider_city=ELMORE m:row_number.y2hd-n93e=2

series e:y2hd-n93e d:2017-03-01T00:00:00.000Z t:role_description="5% OR GREATER INDIRECT OWNERSHIP INTEREST" t:owner_type=Organization t:ownership_percentage="NO PERCENTAGE PROVIDED" t:owner_name="FC-GEN OPERATIONS INVESTMENT LLC" t:federal_provider_number=015019 t:provider_zip_code=36025 t:provider_state=AL t:provider_name="MERRY WOOD LODGE CARE AND REHABILITATION CENTER" t:provider_city=ELMORE m:row_number.y2hd-n93e=3
```

## Meta Commands

```ls
metric m:row_number.y2hd-n93e p:long l:"Row Number"

entity e:y2hd-n93e l:Ownership t:url=https://data.medicare.gov/api/views/y2hd-n93e

property e:y2hd-n93e t:meta.view v:id=y2hd-n93e v:category="Nursing Home Compare" v:averageRating=0 v:name=Ownership

property e:y2hd-n93e t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:y2hd-n93e t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:y2hd-n93e t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=Edward.Mortimore@cms.hhs.gov v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| federal_provider_number | provider_name                                   | provider_address | provider_city | provider_state | provider_zip_code | role_description                          | owner_type   | owner_name                       | ownership_percentage   | association_date | processing_date     | 
| ======================= | =============================================== | ================ | ============= | ============== | ================= | ========================================= | ============ | ================================ | ====================== | ================ | =================== | 
| 015019                  | MERRY WOOD LODGE CARE AND REHABILITATION CENTER | P O BOX 130      | ELMORE        | AL             | 36025             | 5% OR GREATER DIRECT OWNERSHIP INTEREST   | Organization | GENESIS HOLDINGS LLC             | 100%                   | since 02/02/2015 | 2017-03-01T00:00:00 | 
| 015019                  | MERRY WOOD LODGE CARE AND REHABILITATION CENTER | P O BOX 130      | ELMORE        | AL             | 36025             | 5% OR GREATER INDIRECT OWNERSHIP INTEREST | Organization | DONNA REIS 1995 FAM TR           | NO PERCENTAGE PROVIDED | since 02/02/2015 | 2017-03-01T00:00:00 | 
| 015019                  | MERRY WOOD LODGE CARE AND REHABILITATION CENTER | P O BOX 130      | ELMORE        | AL             | 36025             | 5% OR GREATER INDIRECT OWNERSHIP INTEREST | Organization | FC-GEN OPERATIONS INVESTMENT LLC | NO PERCENTAGE PROVIDED | since 02/02/2015 | 2017-03-01T00:00:00 | 
| 015019                  | MERRY WOOD LODGE CARE AND REHABILITATION CENTER | P O BOX 130      | ELMORE        | AL             | 36025             | 5% OR GREATER INDIRECT OWNERSHIP INTEREST | Organization | GEN OPERATIONS I LLC             | NO PERCENTAGE PROVIDED | since 02/02/2015 | 2017-03-01T00:00:00 | 
| 015019                  | MERRY WOOD LODGE CARE AND REHABILITATION CENTER | P O BOX 130      | ELMORE        | AL             | 36025             | 5% OR GREATER INDIRECT OWNERSHIP INTEREST | Organization | GEN OPERATIONS II, LLC           | NO PERCENTAGE PROVIDED | since 02/02/2015 | 2017-03-01T00:00:00 | 
| 015019                  | MERRY WOOD LODGE CARE AND REHABILITATION CENTER | P O BOX 130      | ELMORE        | AL             | 36025             | 5% OR GREATER INDIRECT OWNERSHIP INTEREST | Organization | GENESIS HEALTHCARE INC           | NO PERCENTAGE PROVIDED | since 02/02/2015 | 2017-03-01T00:00:00 | 
| 015019                  | MERRY WOOD LODGE CARE AND REHABILITATION CENTER | P O BOX 130      | ELMORE        | AL             | 36025             | 5% OR GREATER INDIRECT OWNERSHIP INTEREST | Organization | GENESIS HEALTHCARE LLC           | NO PERCENTAGE PROVIDED | since 02/02/2015 | 2017-03-01T00:00:00 | 
| 015019                  | MERRY WOOD LODGE CARE AND REHABILITATION CENTER | P O BOX 130      | ELMORE        | AL             | 36025             | 5% OR GREATER INDIRECT OWNERSHIP INTEREST | Organization | HCCF MANAGEMENT GROUP XI LLC     | NO PERCENTAGE PROVIDED | since 02/02/2015 | 2017-03-01T00:00:00 | 
| 015019                  | MERRY WOOD LODGE CARE AND REHABILITATION CENTER | P O BOX 130      | ELMORE        | AL             | 36025             | 5% OR GREATER INDIRECT OWNERSHIP INTEREST | Organization | ONEX PARTNERS LP                 | NO PERCENTAGE PROVIDED | since 02/02/2015 | 2017-03-01T00:00:00 | 
| 015019                  | MERRY WOOD LODGE CARE AND REHABILITATION CENTER | P O BOX 130      | ELMORE        | AL             | 36025             | 5% OR GREATER INDIRECT OWNERSHIP INTEREST | Organization | SENIOR CARE GENESIS LLC          | NO PERCENTAGE PROVIDED | since 02/02/2015 | 2017-03-01T00:00:00 | 
```