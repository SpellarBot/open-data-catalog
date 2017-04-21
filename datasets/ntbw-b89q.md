# Current & Expired Product List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/current-expired-product-list-8ab19) |
| Metadata | [Link](https://data.hawaii.gov/api/views/ntbw-b89q) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/ntbw-b89q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/ntbw-b89q/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | ntbw-b89q |
| Name | Current & Expired Product List |
| Attribution | Hawaii Department of Agriculture |
| Category | Health |
| Created | 2014-06-13T00:56:38Z |
| Publication Date | 2017-03-10T20:45:27Z |

## Description

List of pesticide products licensed for distribution and sale in the state of Hawaii, including currently licensed and expired.  This list is provided for informational purposes only.  Restricted use pesticides are indicated by an asterisk (*).  Restricted use pesticides can only be distributed and sold by a licensed dealer and only to certified applicators.  It is a violation of state and federal laws to use these restricted use pesticides unless the person is a certified pesticide applicator or under the direct supervision of a certified pesticide applicator.  Product names followed by a number in parenthesis, for example (1) or (2), indicate that the product will be discontinued and will only be renewed for one or two additional years after the current license period expires.

## Columns

```ls
| Included | Schema Type | Field Name | Name       | Data Type | Render Type |
| ======== | =========== | ========== | ========== | ========= | =========== |
| Yes      | series tag  | prod_name  | PROD_NAME  | text      | text        |
| Yes      | series tag  | eparegisno | EPAREGISNO | text      | text        |
| Yes      | series tag  | classific  | CLASSIFIC  | text      | text        |
| Yes      | time        | exp_year   | EXP_YEAR   | number    | number      |
| Yes      | series tag  | name       | NAME       | text      | text        |
| Yes      | series tag  | company_no | COMPANY_NO | text      | number      |
| Yes      | series tag  | product_no | PRODUCT_NO | text      | number      |
| Yes      | series tag  | labels     | LABELS     | url       | url         |
```

## Time Field

```ls
Value = exp_year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:ntbw-b89q l:"Current & Expired Product List" t:attribution="Hawaii Department of Agriculture" t:url=https://data.hawaii.gov/api/views/ntbw-b89q

property e:ntbw-b89q t:meta.view v:id=ntbw-b89q v:category=Health v:averageRating=0 v:name="Current & Expired Product List" v:attribution="Hawaii Department of Agriculture"

property e:ntbw-b89q t:meta.view.owner v:id=dnu6-bvze v:profileImageUrlMedium=/api/users/dnu6-bvze/profile_images/THUMB v:profileImageUrlLarge=/api/users/dnu6-bvze/profile_images/LARGE v:screenName="HDOA Pesticides Branch" v:profileImageUrlSmall=/api/users/dnu6-bvze/profile_images/TINY v:displayName="HDOA Pesticides Branch"

property e:ntbw-b89q t:meta.view.tableauthor v:id=dnu6-bvze v:profileImageUrlMedium=/api/users/dnu6-bvze/profile_images/THUMB v:profileImageUrlLarge=/api/users/dnu6-bvze/profile_images/LARGE v:screenName="HDOA Pesticides Branch" v:profileImageUrlSmall=/api/users/dnu6-bvze/profile_images/TINY v:roleName=editor v:displayName="HDOA Pesticides Branch"
```

## Top Records

```ls
| prod_name                                                       | eparegisno | classific   | exp_year | name                     | company_no | product_no | labels                                                  | 
| =============================================================== | ========== | =========== | ======== | ======================== | ========== | ========== | ======================================================= | 
| "POW!" Roach Killer                                             | 44405-1    | General Use | 1990     | Nu-Way Products, Inc.    | 9397       | 1          | [null, null]                                            | 
| "Schultz-Instant" House Plant & Garden Insecticide Spray        | 39609-1    | General Use | 2000     | Schultz Company          | 9395       | 1          | [null, null]                                            | 
| "Schultz-Instant" Insect Spray for Fruits & Vegetable           | 39609-1    | General Use | 1997     | Schultz Company          | 9395       | 3          | [null, null]                                            | 
| "Schultz-Instant" Insect Spray for House Plants & Gardens       | 39609-1    | General Use | 1997     | Schultz Company          | 9395       | 2          | [null, null]                                            | 
| "Schultz-Instant" Insect Spray for Roses & Flowers              | 39609-1    | General Use | 1997     | Schultz Company          | 9395       | 4          | [null, null]                                            | 
| #118 Marvin Brand Creosote                                      | 11092-1    | General Use | 1987     | The Marvin Corp.         | 9522       | 1          | [null, null]                                            | 
| #271 Raid Roach & Ant Killer and Treatment (Assorted Scents)    | 4822-271   | General Use | 2015     | S.C. Johnson & Son, Inc. | 9274       | 432        | [http://hawaii.gov/hdoa/labels/9274.432_2015.pdf, null] | 
| #271 Raid Roach & Ant Killer and Treatment (Garden Center Size) | 4822-271   | General Use | 2006     | S.C. Johnson & Son, Inc. | 9274       | 433        | [null, null]                                            | 
| #271 Raid Roach & Ant Killer and Treatment (House & Yard Line)  | 4822-271   | General Use | 2006     | S.C. Johnson & Son, Inc. | 9274       | 434        | [null, null]                                            | 
| #271 Raid Roach & Ant Killer and Treatment (Institutional Size) | 4822-271   | General Use | 2006     | S.C. Johnson & Son, Inc. | 9274       | 435        | [null, null]                                            | 
```