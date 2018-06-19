# Missouri Beer, Wine and Liquor Solicitor List with Zip Code

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-beer-wine-and-liquor-solicitor-list-with-zip-code-c91b4) |
| Metadata | [Link](https://data.mo.gov/api/views/mmn5-wy78) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/mmn5-wy78/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/mmn5-wy78/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | mmn5-wy78 |
| Name | Missouri Beer, Wine and Liquor Solicitor List with Zip Code |
| Attribution | Missouri Division of Alcohol and Tobacco Control |
| Category | Regulatory |
| Tags | missouri, beer, wholesaler, solicitor, listing, zip code |
| Created | 2012-08-07T14:31:25Z |
| Publication Date | 2017-04-20T13:15:11Z |

## Description

Listing of all current beer, wine and liquor solicitors and their associated zip code. This is updated daily

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | business_name  | Business Name  | text      | text        |
| Yes      | series tag  | zip_code       | Zip Code       | text      | text        |
| Yes      | series tag  | license_number | License Number | text      | text        |
| Yes      | series tag  | license_type   | License Type   | text      | text        |
| Yes      | series tag  | city           | City           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mmn5-wy78 d:2017-04-20T13:15:04.000Z t:business_name="A & M IMPORTS LLC" t:license_type=22S t:zip_code=212245749 t:license_number=235768 t:city=BALTIMORE m:row_number.mmn5-wy78=1

series e:mmn5-wy78 d:2017-04-20T13:15:04.000Z t:business_name="A TO Z WINEWORKS LLC" t:license_type=22S t:zip_code=971326966 t:license_number=158858 t:city=NEWBERG m:row_number.mmn5-wy78=2

series e:mmn5-wy78 d:2017-04-20T13:15:04.000Z t:business_name="A W DIRECT LLC" t:license_type=22S t:zip_code=954090000 t:license_number=239546 t:city="SANTA ROSA" m:row_number.mmn5-wy78=3
```

## Meta Commands

```ls
metric m:row_number.mmn5-wy78 p:long l:"Row Number"

entity e:mmn5-wy78 l:"Missouri Beer, Wine and Liquor Solicitor List with Zip Code" t:attribution="Missouri Division of Alcohol and Tobacco Control" t:url=https://data.mo.gov/api/views/mmn5-wy78

property e:mmn5-wy78 t:meta.view v:id=mmn5-wy78 v:category=Regulatory v:attributionLink=http://www.atc.dps.mo.gov v:averageRating=0 v:name="Missouri Beer, Wine and Liquor Solicitor List with Zip Code" v:attribution="Missouri Division of Alcohol and Tobacco Control"

property e:mmn5-wy78 t:meta.view.owner v:id=gytm-8bsj v:screenName="Rob Gourley" v:displayName="Rob Gourley"

property e:mmn5-wy78 t:meta.view.tableauthor v:id=gytm-8bsj v:screenName="Rob Gourley" v:roleName=editor v:displayName="Rob Gourley"
```

## Top Records

```ls
| :updated_at | business_name             | zip_code  | license_number | license_type | city          | 
| =========== | ========================= | ========= | ============== | ============ | ============= | 
| 1492694104  | A & M IMPORTS LLC         | 212245749 | 235768         | 22S          | BALTIMORE     | 
| 1492694104  | A TO Z WINEWORKS LLC      | 971326966 | 158858         | 22S          | NEWBERG       | 
| 1492694104  | A W DIRECT LLC            | 954090000 | 239546         | 22S          | SANTA ROSA    | 
| 1492694104  | A. BOMMARITO WINES INC.   | 631442711 | 96573          | LS           | BRENTWOOD     | 
| 1492694104  | A. HARDY USA LTD.         | 600183338 | 95054          | LS           | DES PLAINES   | 
| 1492694104  | A.V. BRANDS INC.          | 21093     | 169341         | LS           | LUTHERVILLE   | 
| 1492694104  | A.V.V. WINERY COMPANY LLC | 954489642 | 147198         | 22S          | HEALDSBURG    | 
| 1492694104  | A-BLONDES INC.            | 630051025 | 227448         | LS           | CHESTERFIELD  | 
| 1492694104  | ABIGAIL ADAMS WINE CO.    | 945991369 | 242846         | 22S          | YOUNTVILLE    | 
| 1492694104  | ABITA BREWING COMPANY LLC | 704200000 | 231298         | 22S          | ABITA SPRINGS | 
```