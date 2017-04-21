# ACA Federal Upper Limits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aca-federal-upper-limits) |
| Metadata | [Link](https://data.medicaid.gov/api/views/yns6-zx8k) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/yns6-zx8k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/yns6-zx8k/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | yns6-zx8k |
| Name | ACA Federal Upper Limits |
| Attribution | Centers for Medicare and Medicaid Services |
| Category | Drug Pricing and Payment |
| Tags | federal upper limits, ful, amp |
| Created | 2016-10-31T01:15:11Z |
| Publication Date | 2017-03-29T14:53:52Z |

## Description

Affordable Care Act Federal Upper Limits (FUL) based on the weighted average of the most recently reported monthly average manufacturer price (AMP) for pharmaceutically and therapeutically equivalent multiple source drug products that are available for purchase by retail community pharmacies on a nationwide basis.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | product_group             | Product Group             | text      | number      |
| Yes      | series tag     | ingredient                | Ingredient                | text      | text        |
| Yes      | series tag     | strength                  | Strength                  | text      | text        |
| Yes      | series tag     | dosage                    | Dosage                    | text      | text        |
| Yes      | series tag     | route                     | Route                     | text      | text        |
| Yes      | series tag     | mdr_unit_type             | MDR Unit Type             | text      | text        |
| Yes      | numeric metric | weighted_average_amps     | Weighted Average AMPs     | number    | number      |
| Yes      | numeric metric | aca_ful                   | ACA FUL                   | number    | number      |
| Yes      | numeric metric | package_size              | Package Size              | number    | number      |
| Yes      | series tag     | ndc                       | NDC                       | text      | text        |
| Yes      | series tag     | a_rated                   | A-Rated                   | text      | text        |
| Yes      | series tag     | aca_ful_calculation_basis | ACA FUL Calculation Basis | text      | text        |
| No       |                | year                      | Year                      | number    | number      |
| No       |                | month                     | Month                     | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:yns6-zx8k d:2016-03-01T00:00:00.000Z t:ndc=00093005001 t:route=ORAL t:strength=300MG;15MG t:aca_ful_calculation_basis=Y t:a_rated=Yes t:mdr_unit_type=TAB t:dosage=TABLET t:ingredient="ACETAMINOPHEN; CODEINE PHOSPHATE" t:product_group=13 m:package_size=100 m:aca_ful=0.14994 m:weighted_average_amps=0.047949

series e:yns6-zx8k d:2016-03-01T00:00:00.000Z t:ndc=00406048301 t:route=ORAL t:strength=300MG;15MG t:aca_ful_calculation_basis=Y t:a_rated=Yes t:mdr_unit_type=TAB t:dosage=TABLET t:ingredient="ACETAMINOPHEN; CODEINE PHOSPHATE" t:product_group=13 m:package_size=100 m:aca_ful=0.14994 m:weighted_average_amps=0.047949

series e:yns6-zx8k d:2016-03-01T00:00:00.000Z t:ndc=00603233721 t:route=ORAL t:strength=300MG;15MG t:aca_ful_calculation_basis=Y t:a_rated=Yes t:mdr_unit_type=TAB t:dosage=TABLET t:ingredient="ACETAMINOPHEN; CODEINE PHOSPHATE" t:product_group=13 m:package_size=100 m:aca_ful=0.14994 m:weighted_average_amps=0.047949
```

## Meta Commands

```ls
metric m:weighted_average_amps p:double l:"Weighted Average AMPs" t:dataTypeName=number

metric m:aca_ful p:double l:"ACA FUL" t:dataTypeName=number

metric m:package_size p:integer l:"Package Size" t:dataTypeName=number

entity e:yns6-zx8k l:"ACA Federal Upper Limits" t:attribution="Centers for Medicare and Medicaid Services" t:url=https://data.medicaid.gov/api/views/yns6-zx8k

property e:yns6-zx8k t:meta.view v:id=yns6-zx8k v:category="Drug Pricing and Payment" v:attributionLink=https://www.medicaid.gov v:averageRating=0 v:name="ACA Federal Upper Limits" v:attribution="Centers for Medicare and Medicaid Services"

property e:yns6-zx8k t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:yns6-zx8k t:meta.view.owner v:id=nmzs-t286 v:profileImageUrlMedium=/api/users/nmzs-t286/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmzs-t286/profile_images/LARGE v:screenName="Jeff Chamblee" v:profileImageUrlSmall=/api/users/nmzs-t286/profile_images/TINY v:lastNotificationSeenAt=1491332351 v:displayName="Jeff Chamblee"

property e:yns6-zx8k t:meta.view.tableauthor v:id=nmzs-t286 v:profileImageUrlMedium=/api/users/nmzs-t286/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmzs-t286/profile_images/LARGE v:screenName="Jeff Chamblee" v:profileImageUrlSmall=/api/users/nmzs-t286/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491332351 v:displayName="Jeff Chamblee"

property e:yns6-zx8k t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| product_group | ingredient                       | strength   | dosage | route | mdr_unit_type | weighted_average_amps | aca_ful | package_size | ndc         | a_rated | aca_ful_calculation_basis | year | month | 
| ============= | ================================ | ========== | ====== | ===== | ============= | ===================== | ======= | ============ | =========== | ======= | ========================= | ==== | ===== | 
| 13            | ACETAMINOPHEN; CODEINE PHOSPHATE | 300MG;15MG | TABLET | ORAL  | TAB           | 0.047949              | 0.14994 | 100          | 00093005001 | Yes     | Y                         | 2016 | 3     | 
| 13            | ACETAMINOPHEN; CODEINE PHOSPHATE | 300MG;15MG | TABLET | ORAL  | TAB           | 0.047949              | 0.14994 | 100          | 00406048301 | Yes     | Y                         | 2016 | 3     | 
| 13            | ACETAMINOPHEN; CODEINE PHOSPHATE | 300MG;15MG | TABLET | ORAL  | TAB           | 0.047949              | 0.14994 | 100          | 00603233721 | Yes     | Y                         | 2016 | 3     | 
| 13            | ACETAMINOPHEN; CODEINE PHOSPHATE | 300MG;15MG | TABLET | ORAL  | TAB           | 0.047949              | 0.14994 | 100          | 13107005801 | Yes     | Y                         | 2016 | 3     | 
| 14            | ACETAMINOPHEN; CODEINE PHOSPHATE | 300MG;30MG | TABLET | ORAL  | TAB           | 0.069556              | 0.17    | 100          | 00093015001 | Yes     | Y                         | 2016 | 3     | 
| 14            | ACETAMINOPHEN; CODEINE PHOSPHATE | 300MG;30MG | TABLET | ORAL  | TAB           | 0.069556              | 0.17    | 1000         | 00093015010 | Yes     | Y                         | 2016 | 3     | 
| 14            | ACETAMINOPHEN; CODEINE PHOSPHATE | 300MG;30MG | TABLET | ORAL  | TAB           | 0.069556              | 0.17    | 100          | 00406048401 | Yes     | Y                         | 2016 | 3     | 
| 14            | ACETAMINOPHEN; CODEINE PHOSPHATE | 300MG;30MG | TABLET | ORAL  | TAB           | 0.069556              | 0.17    | 30           | 00406048403 | Yes     | Y                         | 2016 | 3     | 
| 14            | ACETAMINOPHEN; CODEINE PHOSPHATE | 300MG;30MG | TABLET | ORAL  | TAB           | 0.069556              | 0.17    | 1000         | 00406048410 | Yes     | Y                         | 2016 | 3     | 
| 14            | ACETAMINOPHEN; CODEINE PHOSPHATE | 300MG;30MG | TABLET | ORAL  | TAB           | 0.069556              | 0.17    | 20           | 00406048420 | Yes     | Y                         | 2016 | 3     | 
```