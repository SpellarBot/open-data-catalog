# New York State Registered Tax Return Preparers and Facilitators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-registered-tax-return-preparers-and-facilitators) |
| Metadata | [Link](https://data.ny.gov/api/views/b7jj-bh4g) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/b7jj-bh4g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/b7jj-bh4g/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | b7jj-bh4g |
| Name | New York State Registered Tax Return Preparers and Facilitators |
| Attribution | New York State Department of Taxation and Finance |
| Category | Government & Finance |
| Tags | preparer, registered, tax return |
| Created | 2014-07-03T16:14:32Z |
| Publication Date | 2017-04-20T22:24:42Z |

## Description

This Dataset contains tax return preparers and facilitators that have registered with the New York State Department of Taxation and Finance pursuant to Tax Law Section 32.

## Columns

```ls
| Included | Schema Type | Field Name                              | Name                                    | Data Type | Render Type |
| ======== | =========== | ======================================= | ======================================= | ========= | =========== |
| No       | time        | :updated_at                             | updated_at                              | meta_data | meta_data   |
| Yes      | series tag  | ny_registration_type                    | NY Registration Type                    | text      | text        |
| Yes      | series tag  | first_name                              | First Name                              | text      | text        |
| Yes      | series tag  | middle_initial                          | Middle Initial                          | text      | text        |
| Yes      | series tag  | last_name                               | Last Name                               | text      | text        |
| Yes      | series tag  | business_name_if_listed_on_registration | Business Name if Listed on Registration | text      | text        |
| Yes      | series tag  | city                                    | City                                    | text      | text        |
| Yes      | series tag  | state                                   | State                                   | text      | text        |
| Yes      | series tag  | country                                 | Country                                 | text      | text        |
| Yes      | series tag  | zip                                     | Zip                                     | text      | text        |
| Yes      | series tag  | zip_plus_four                           | Zip Plus Four                           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:b7jj-bh4g d:2017-04-20T22:18:12.000Z t:first_name=TERESA t:state=FL t:last_name=PETERSEN t:ny_registration_type=PREPARER/FACILITATOR t:city="CUTLER BAY" m:row_number.b7jj-bh4g=1

series e:b7jj-bh4g d:2017-04-20T22:18:12.000Z t:first_name=REYNALDO t:middle_initial=C t:state=NJ t:last_name=CADENILLA t:ny_registration_type=PREPARER t:city="JERSEY CITY" m:row_number.b7jj-bh4g=2

series e:b7jj-bh4g d:2017-04-20T22:18:12.000Z t:first_name=DENNIS t:middle_initial=C t:state=NY t:last_name=GENTILE t:ny_registration_type=PREPARER t:city="NEW ROCHELLE" m:row_number.b7jj-bh4g=3
```

## Meta Commands

```ls
metric m:row_number.b7jj-bh4g p:long l:"Row Number"

entity e:b7jj-bh4g l:"New York State Registered Tax Return Preparers and Facilitators" t:attribution="New York State Department of Taxation and Finance" t:url=https://data.ny.gov/api/views/b7jj-bh4g

property e:b7jj-bh4g t:meta.view v:id=b7jj-bh4g v:category="Government & Finance" v:attributionLink=http://www.tax.ny.gov/tp/ v:averageRating=0 v:name="New York State Registered Tax Return Preparers and Facilitators" v:attribution="New York State Department of Taxation and Finance"

property e:b7jj-bh4g t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:b7jj-bh4g t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:b7jj-bh4g t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | ny_registration_type | first_name | middle_initial | last_name      | business_name_if_listed_on_registration | city         | state | country | zip | zip_plus_four | 
| =========== | ==================== | ========== | ============== | ============== | ======================================= | ============ | ===== | ======= | === | ============= | 
| 1492726692  | PREPARER/FACILITATOR | TERESA     |                | PETERSEN       |                                         | CUTLER BAY   | FL    |         |     |               | 
| 1492726692  | PREPARER             | REYNALDO   | C              | CADENILLA      |                                         | JERSEY CITY  | NJ    |         |     |               | 
| 1492726692  | PREPARER             | DENNIS     | C              | GENTILE        |                                         | NEW ROCHELLE | NY    |         |     |               | 
| 1492726692  | PREPARER             | RANDY      | M              | LIGATOR        |                                         | E NORTHPORT  | NY    |         |     |               | 
| 1492726692  | PREPARER             | LLOYD      |                | PORTNOY        |                                         | EAST MEADOW  | NY    |         |     |               | 
| 1492726692  | PREPARER             | GEORGE     |                | HATZISTAVRIDIS |                                         | ASTORIA      | NY    |         |     |               | 
| 1492726692  | PREPARER             | AVE        |                | MORRIS         |                                         | MOUNT VERNON | NY    |         |     |               | 
| 1492726692  | PREPARER             | JIMMIE     | W              | BLAIR          |                                         | OCALA        | FL    |         |     |               | 
| 1492726692  | PREPARER             | MAHMOUD    | R              | SHOJAI         |                                         | SHERMAN      | TX    |         |     |               | 
| 1492726692  | PREPARER             | DEBORAH    |                | BENAVIDEZ      |                                         | SAN ANTONIO  | TX    |         |     |               | 
```