# Historical - Department of Revenue - Businesses Subject to Home Rule Taxes - 2011 through September 8th

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-revenue-businesses-subject-to-home-rule-taxes-2011-through-september-8th-af385) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/cpgn-z9js) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/cpgn-z9js/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/cpgn-z9js/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | cpgn-z9js |
| Name | Historical - Department of Revenue - Businesses Subject to Home Rule Taxes - 2011 through September 8th |
| Attribution | Cook County Department of Revenue |
| Category | Finance & Administration |
| Created | 2011-09-08T19:32:23Z |
| Publication Date | 2014-10-09T21:13:36Z |

## Description

This dataset is no longer updated. For updated datasets please search for "Registered with the Cook County Department of Revenue." This dataset may be removed in the future. A listing of the businesses in unincorporated Cook County subject to Liquor, Gasoline, New Motor Vehicle, Dealer Use, Diesel, Amusement, and Parking Home Rule Taxes. Data last updated September 08, 2011

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| Yes      | series tag  | ret_type         | Ret Type         | text      | number      |
| Yes      | series tag  | return_type_desc | Return Type Desc | text      | text        |
| Yes      | series tag  | business_name    | Business Name    | text      | text        |
| No       |             | address_1        | Address 1        | text      | text        |
| No       |             | address_2        | Address 2        | text      | text        |
| Yes      | series tag  | state            | State            | text      | text        |
| Yes      | series tag  | zip              | Zip              | text      | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address_1,address_2
```

## Data Commands

```ls
series e:cpgn-z9js d:2011-01-01T00:00:00.000Z t:business_name="A.B. COMPANY OF WISCONSIN, INC." t:zip=60712 t:state=IL t:return_type_desc="Liquor Home Rule Tax" t:ret_type=1 m:row_number.cpgn-z9js=1

series e:cpgn-z9js d:2011-01-01T00:00:00.000Z t:business_name="ABRUZZI WINE CO." t:zip=60411 t:state=IL t:return_type_desc="Liquor Home Rule Tax" t:ret_type=1 m:row_number.cpgn-z9js=2

series e:cpgn-z9js d:2011-01-01T00:00:00.000Z t:business_name="AGAVES AGRICOLA CURIEL" t:zip=60505 t:state=IL t:return_type_desc="Liquor Home Rule Tax" t:ret_type=1 m:row_number.cpgn-z9js=3
```

## Meta Commands

```ls
metric m:row_number.cpgn-z9js p:long l:"Row Number"

entity e:cpgn-z9js l:"Historical - Department of Revenue - Businesses Subject to Home Rule Taxes - 2011 through September 8th" t:attribution="Cook County Department of Revenue" t:url=https://datacatalog.cookcountyil.gov/api/views/cpgn-z9js

property e:cpgn-z9js t:meta.view v:id=cpgn-z9js v:category="Finance & Administration" v:attributionLink=http://cookcountyil.gov/revenue v:averageRating=0 v:name="Historical - Department of Revenue - Businesses Subject to Home Rule Taxes - 2011 through September 8th" v:attribution="Cook County Department of Revenue"

property e:cpgn-z9js t:meta.view.license v:name="Public Domain"

property e:cpgn-z9js t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:cpgn-z9js t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| ret_type | return_type_desc     | business_name                   | address_1                      | address_2 | state | zip   | 
| ======== | ==================== | =============================== | ============================== | ========= | ===== | ===== | 
| 1        | Liquor Home Rule Tax | A.B. COMPANY OF WISCONSIN, INC. | 6525 PROESEL AVE.              |           | IL    | 60712 | 
| 1        | Liquor Home Rule Tax | ABRUZZI WINE CO.                | 15 W. 23RD STREET              |           | IL    | 60411 | 
| 1        | Liquor Home Rule Tax | AGAVES AGRICOLA CURIEL          | 523 S. RIVER STREET            |           | IL    | 60505 | 
| 1        | Liquor Home Rule Tax | AL CAPONE DIST., INC.           | 220 N. 4TH STREET              |           | IL    | 60174 | 
| 1        | Liquor Home Rule Tax | AMBERLAND LIQUOR DIST., INC.    | 3415 CHURCH ST                 |           | IL    | 60076 | 
| 1        | Liquor Home Rule Tax | AMERICAN WHOLSALER WINE & SPRT  | 4300 REGENCY DR                |           | IL    | 60025 | 
| 1        | Liquor Home Rule Tax | AMPED IGUANA LLC                | 4036 N. LINCOLN AVE            |           | IL    | 60618 | 
| 1        | Liquor Home Rule Tax | ARTISAN BEVERAGE CO.            | 2220 ARTHUR AVE.               |           | IL    | 60007 | 
| 1        | Liquor Home Rule Tax | ATOMIC BRANDS, INC.             | 500 W. SUPERIOR ST., STE. 1312 |           | IL    | 60654 | 
| 1        | Liquor Home Rule Tax | BALTIC FOOD DISTRIBUTING        | 1349 ENTERPRISE DR.            |           | IL    | 60446 | 
```