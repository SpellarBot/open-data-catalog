# Hawaii Agricultural Good Neighbor Program RUP Use Reporting

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/kauai-agricultural-good-neighbor-program-rup-use-reporting-b10bb) |
| Metadata | [Link](https://data.hawaii.gov/api/views/9pud-c8q5) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/9pud-c8q5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/9pud-c8q5/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 9pud-c8q5 |
| Name | Hawaii Agricultural Good Neighbor Program RUP Use Reporting |
| Attribution | Hawaii Department of Agriculture |
| Category | Health |
| Created | 2013-12-27T20:23:40Z |
| Publication Date | 2017-03-30T00:01:33Z |

## Description

Aggregate usage of Restricted Use Pesticides as reported through the Hawaii Agricultural Good Neighbor Program.

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                  | Data Type     | Render Type   |
| ======== | ============== | ========================================================== | ===================== | ============= | ============= |
| Yes      | time           | month_year                                                 | Month-Year            | calendar_date | calendar_date |
| Yes      | series tag     | farm_operator                                              | Farm Operator         | text          | text          |
| Yes      | series tag     | product_name                                               | Product Name          | text          | text          |
| Yes      | series tag     | epa_reg_no                                                 | EPA Reg. No.          | text          | text          |
| Yes      | numeric metric | total_used_gallons                                         | Total Used (Gallons)  | number        | text          |
| Yes      | numeric metric | total_used_pounds                                          | Total Used (Pounds)   | number        | text          |
| Yes      | series tag     | a_i_1_name                                                 | A.I. (1) Name         | text          | text          |
| Yes      | numeric metric | a_i_1_pounds                                               | A.I. (1) Pounds       | number        | text          |
| Yes      | series tag     | a_i_2_name                                                 | A.I. (2) Name         | text          | text          |
| Yes      | numeric metric | a_i_2_pounds                                               | A.I. (2) Pounds       | number        | text          |
| Yes      | series tag     | a_i_3_name                                                 | A.I. (3) Name         | text          | text          |
| Yes      | numeric metric | a_i_3_pounds                                               | A.I. (3) Pounds       | number        | text          |
| Yes      | numeric metric | total_area_applied_to_acres_includes_multiple_applications | Total area applied to | number        | text          |
| Yes      | numeric metric | field_area_applied_to_acres                                | Field area applied to | number        | text          |
```

## Time Field

```ls
Value = month_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:9pud-c8q5 d:2013-12-01T00:00:00.000Z t:farm_operator="Kaua'i Coffee Co. LLC" t:product_name="No RUP's used" m:total_used_gallons=0 m:total_used_pounds=0 m:field_area_applied_to_acres=0 m:total_area_applied_to_acres_includes_multiple_applications=0

series e:9pud-c8q5 d:2013-12-01T00:00:00.000Z t:a_i_1_name=Atrazine t:farm_operator="Syngenta (Kauai)" t:product_name="Aatrex Nine-O" t:epa_reg_no=100-585 m:a_i_1_pounds=146.74 m:total_used_pounds=166.75 m:field_area_applied_to_acres=166.75 m:total_area_applied_to_acres_includes_multiple_applications=166.75

series e:9pud-c8q5 d:2013-12-01T00:00:00.000Z t:a_i_1_name=Esfenvalerate t:farm_operator="Syngenta (Kauai)" t:product_name="Asana XL" t:epa_reg_no=352-515 m:a_i_1_pounds=1.09 m:total_used_gallons=1.65 m:field_area_applied_to_acres=23.43 m:total_area_applied_to_acres_includes_multiple_applications=23.43
```

## Meta Commands

```ls
metric m:total_used_gallons p:float l:"Total Used (Gallons)" d:"Total RUP used in gallons (if liquid) for reported month/year" t:dataTypeName=number

metric m:total_used_pounds p:long l:"Total Used (Pounds)" d:"Total RUP used in pounds(if applicable) for reported month/year" t:dataTypeName=number

metric m:a_i_1_pounds p:float l:"A.I. (1) Pounds" d:"Total active ingredient used for reported month (pounds)." t:dataTypeName=number

metric m:a_i_2_pounds p:float l:"A.I. (2) Pounds" d:"Total active ingredient used for reported month (pounds)." t:dataTypeName=number

metric m:a_i_3_pounds p:float l:"A.I. (3) Pounds" d:"Total active ingredient used for reported month (pounds)." t:dataTypeName=number

metric m:total_area_applied_to_acres_includes_multiple_applications p:float l:"Total area applied to" d:"Total area applied to in acres, including repeat applications." t:dataTypeName=number

metric m:field_area_applied_to_acres p:float l:"Field area applied to" d:"Field area applied to in acres. Does not include repeat applications." t:dataTypeName=number

entity e:9pud-c8q5 l:"Hawaii Agricultural Good Neighbor Program RUP Use Reporting" t:attribution="Hawaii Department of Agriculture" t:url=https://data.hawaii.gov/api/views/9pud-c8q5

property e:9pud-c8q5 t:meta.view v:id=9pud-c8q5 v:category=Health v:averageRating=0 v:name="Hawaii Agricultural Good Neighbor Program RUP Use Reporting" v:attribution="Hawaii Department of Agriculture"

property e:9pud-c8q5 t:meta.view.owner v:id=dnu6-bvze v:profileImageUrlMedium=/api/users/dnu6-bvze/profile_images/THUMB v:profileImageUrlLarge=/api/users/dnu6-bvze/profile_images/LARGE v:screenName="HDOA Pesticides Branch" v:profileImageUrlSmall=/api/users/dnu6-bvze/profile_images/TINY v:displayName="HDOA Pesticides Branch"

property e:9pud-c8q5 t:meta.view.tableauthor v:id=dnu6-bvze v:profileImageUrlMedium=/api/users/dnu6-bvze/profile_images/THUMB v:profileImageUrlLarge=/api/users/dnu6-bvze/profile_images/LARGE v:screenName="HDOA Pesticides Branch" v:profileImageUrlSmall=/api/users/dnu6-bvze/profile_images/TINY v:roleName=editor v:displayName="HDOA Pesticides Branch"
```

## Top Records

```ls
| month_year          | farm_operator         | product_name   | epa_reg_no  | total_used_gallons | total_used_pounds | a_i_1_name        | a_i_1_pounds | a_i_2_name | a_i_2_pounds | a_i_3_name | a_i_3_pounds | total_area_applied_to_acres_includes_multiple_applications | field_area_applied_to_acres | 
| =================== | ===================== | ============== | =========== | ================== | ================= | ================= | ============ | ========== | ============ | ========== | ============ | ========================================================== | =========================== | 
| 2013-12-01T00:00:00 | Kaua'i Coffee Co. LLC | No RUP's used  |             | 0.00000            | 0.00000           |                   |              |            |              |            |              | 0.00                                                       | 0.00                        | 
| 2013-12-01T00:00:00 | Syngenta (Kauai)      | Aatrex Nine-O  | 100-585     |                    | 166.75000         | Atrazine          | 146.74000    |            |              |            |              | 166.75                                                     | 166.75                      | 
| 2013-12-01T00:00:00 | Syngenta (Kauai)      | Asana XL       | 352-515     | 1.65000            |                   | Esfenvalerate     | 1.09000      |            |              |            |              | 23.43                                                      | 23.43                       | 
| 2013-12-01T00:00:00 | Syngenta (Kauai)      | Callisto EUP   | 100-EUP-114 | 0.27300            |                   | Mesotrione        | 1.09000      |            |              |            |              | 3.82                                                       | 3.82                        | 
| 2013-12-01T00:00:00 | Syngenta (Kauai)      | Dual II Magnum | 100-818     | 1.73000            |                   | S-metolachlor     | 13.20000     |            |              |            |              | 11.10                                                      | 11.10                       | 
| 2013-12-01T00:00:00 | Syngenta (Kauai)      | Force 3G       | 100-1075    |                    | 199.80000         | Tefluthrin        | 5.99000      |            |              |            |              | 39.96                                                      | 39.96                       | 
| 2013-12-01T00:00:00 | Syngenta (Kauai)      | Lannate        | 352-384     | 4.44000            |                   | Methomyl          | 10.66000     |            |              |            |              | 23.70                                                      | 23.70                       | 
| 2013-12-01T00:00:00 | Syngenta (Kauai)      | Lorsban        | 62719-591   | 81.69000           |                   | Chlorpyrifos      | 306.75000    |            |              |            |              | 326.76                                                     | 326.76                      | 
| 2013-12-01T00:00:00 | Syngenta (Kauai)      | Lumax EZ       | 100-1442    | 104.82000          |                   | S-metolachlor     | 261.00000    | Mesotrione | 26.10000     | Atrazine   | 98.01000     | 139.76                                                     | 139.76                      | 
| 2013-12-01T00:00:00 | Syngenta (Kauai)      | Mustang        | 279-3126    | 3.91000            |                   | Zeta-Cypermethrin | 5.87000      |            |              |            |              | 166.84                                                     | 166.84                      | 
```