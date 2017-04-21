# Business Owners

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/business-owners-fe8d3) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ezma-pppn) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ezma-pppn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ezma-pppn/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ezma-pppn |
| Name | Business Owners |
| Attribution | City of Chicago |
| Category | Community & Economic Development |
| Tags | business, licenses |
| Created | 2011-09-26T18:17:38Z |
| Publication Date | 2014-09-08T10:42:22Z |

## Description

This dataset contains the owner information for all the accounts listed in the Business License Dataset, and is sorted by Account Number. To identify the owner of a business, you will need the account number or legal name, which may be obtained from theBusiness Licenses dataset: https://data.cityofchicago.org/dataset/Business-Licenses/r5kz-chrr. Data Owner: Business Affairs & Consumer Protection. Time Period: 2002 to present. Frequency: Data is updated daily.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                 | Data Type | Render Type |
| ======== | =========== | ====================== | ==================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | account_number         | Account Number       | text      | number      |
| Yes      | series tag  | doing_business_as_name | Legal Name           | text      | text        |
| Yes      | series tag  | owner_first_name       | Owner First Name     | text      | text        |
| Yes      | series tag  | owner_middle_initial   | Owner Middle Initial | text      | text        |
| Yes      | series tag  | owner_last_name        | Owner Last Name      | text      | text        |
| Yes      | series tag  | owner_name_suffix      | Suffix               | text      | text        |
| Yes      | series tag  | owner_name             | Legal Entity Owner   | text      | text        |
| Yes      | series tag  | owner_title            | Title                | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ezma-pppn d:2017-01-05T23:57:13.000Z t:doing_business_as_name="TOPLINE GROUP LLC" t:account_number=412598 t:owner_middle_initial=S t:owner_last_name=WU t:owner_first_name=ANDREW t:owner_title=MEMBER m:row_number.ezma-pppn=1

series e:ezma-pppn d:2014-09-08T03:40:10.000Z t:doing_business_as_name="JOHN SCHALLER" t:account_number=6 t:owner_middle_initial=J. t:owner_last_name=SCHALLER t:owner_first_name=JOHN t:owner_title="SOLE PROPRIETOR" m:row_number.ezma-pppn=2

series e:ezma-pppn d:2017-01-06T10:57:29.000Z t:doing_business_as_name="Roberto Casta?eda" t:account_number=402097 t:owner_last_name=Casta?eda t:owner_first_name=Roberto t:owner_title="SOLE PROPRIETOR" m:row_number.ezma-pppn=3
```

## Meta Commands

```ls
metric m:row_number.ezma-pppn p:long l:"Row Number"

entity e:ezma-pppn l:"Business Owners" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/ezma-pppn

property e:ezma-pppn t:meta.view v:id=ezma-pppn v:category="Community & Economic Development" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Business Owners" v:attribution="City of Chicago"

property e:ezma-pppn t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:ezma-pppn t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | account_number | doing_business_as_name         | owner_first_name | owner_middle_initial | owner_last_name | owner_name_suffix | owner_name             | owner_title     | 
| =========== | ============== | ============================== | ================ | ==================== | =============== | ================= | ====================== | =============== | 
| 1483660633  | 412598         | TOPLINE GROUP LLC              | ANDREW           | S                    | WU              |                   |                        | MEMBER          | 
| 1410147610  | 6              | JOHN SCHALLER                  | JOHN             | J.                   | SCHALLER        |                   |                        | SOLE PROPRIETOR | 
| 1483700249  | 402097         | Roberto Casta?eda              | Roberto          |                      | Casta?eda       |                   |                        | SOLE PROPRIETOR | 
| 1483700249  | 370531         | L?cole Fran?aise, Inc.        | Erwan            | A                    | Sorel           |                   |                        | SECRETARY       | 
| 1483700249  | 370531         | L?cole Fran?aise, Inc.        | Erwan            | A                    | Sorel           |                   |                        | PRESIDENT       | 
| 1483700249  | 370531         | L?cole Fran?aise, Inc.        | Erwan            | A                    | Sorel           |                   |                        | SHAREHOLDER     | 
| 1483786618  | 56082          | HELLENIC FOUNDATION            | JAMES            |                      | SOUKOULIS       |                   |                        | TREASURER       | 
| 1483786618  | 400979         | ON TOUR BREWING COMPANY LLC    | MARK             | WALTER               | LEGENZA         |                   |                        | MANAGING MEMBER | 
| 1483786618  | 412581         | H & M GENERAL REMODELING CORP. | HARLEY           | A                    | PINZON          |                   |                        | PRESIDENT       | 
| 1483786618  | 407312         | RED FOX RESTAURANT I LLC       |                  |                      |                 |                   | RED FOX MANAGEMENT LLC | MANAGING MEMBER | 
```