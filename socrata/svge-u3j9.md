# Fertilizer Program Stop Sales

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fertilizer-program-stop-sales-9e74d) |
| Metadata | [Link](https://data.oregon.gov/api/views/svge-u3j9) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/svge-u3j9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/svge-u3j9/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | svge-u3j9 |
| Name | Fertilizer Program Stop Sales |
| Category | Natural Resources |
| Tags | fertilizer |
| Created | 2014-04-16T18:42:16Z |
| Publication Date | 2017-03-29T22:41:51Z |

## Description

The products listed below are under a current stop sale, use, or removal order. They are not legal for sale or distribution in Oregon. For questions about these products, please call (503) 986-4635.

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type     | Render Type   |
| ======== | =========== | ============ | ============ | ============= | ============= |
| Yes      | series tag  | company      | Company      | text          | text          |
| Yes      | series tag  | brand_name   | Brand Name   | text          | text          |
| Yes      | series tag  | product_name | Product Name | text          | text          |
| Yes      | time        | date         | Date         | calendar_date | calendar_date |
| Yes      | series tag  | reason       | Reason       | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:svge-u3j9 d:2016-12-07T00:00:00.000Z t:reason=Unregistered Mislabeled t:product_name="0-7.2-5 Phosphorus Plus" t:company="9110-7144 Quebec Inc" t:brand_name=HESI m:row_number.svge-u3j9=1

series e:svge-u3j9 d:2016-12-07T00:00:00.000Z t:reason=Mislabeled Unregistered t:product_name="0-9.0-7.2 PK" t:company="9110-7144 Quebec Inc" t:brand_name=HESI m:row_number.svge-u3j9=2

series e:svge-u3j9 d:2016-12-07T00:00:00.000Z t:reason=Mislabeled Unregistered t:product_name="2.8-2.2-3.1 TNT Complex" t:company="9110-7144 Quebec Inc" t:brand_name=HESI m:row_number.svge-u3j9=3
```

## Meta Commands

```ls
metric m:row_number.svge-u3j9 p:long l:"Row Number"

entity e:svge-u3j9 l:"Fertilizer Program Stop Sales" t:url=https://data.oregon.gov/api/views/svge-u3j9

property e:svge-u3j9 t:meta.view v:id=svge-u3j9 v:category="Natural Resources" v:averageRating=0 v:name="Fertilizer Program Stop Sales"

property e:svge-u3j9 t:meta.view.owner v:id=xzpq-yk3z v:screenName="Andy Zimmerman" v:displayName="Andy Zimmerman"

property e:svge-u3j9 t:meta.view.tableauthor v:id=xzpq-yk3z v:screenName="Andy Zimmerman" v:roleName=editor v:displayName="Andy Zimmerman"
```

## Top Records

```ls
| company                   | brand_name                        | product_name                                                       | date                | reason                  | 
| ========================= | ================================= | ================================================================== | =================== | ======================= | 
| 9110-7144 Quebec Inc      | HESI                              | 0-7.2-5 Phosphorus Plus                                            | 2016-12-07T00:00:00 | Unregistered Mislabeled | 
| 9110-7144 Quebec Inc      | HESI                              | 0-9.0-7.2 PK                                                       | 2016-12-07T00:00:00 | Mislabeled Unregistered | 
| 9110-7144 Quebec Inc      | HESI                              | 2.8-2.2-3.1 TNT Complex                                            | 2016-12-07T00:00:00 | Mislabeled Unregistered | 
| 9110-7144 Quebec Inc      | HESI                              | 3-3.9-5.3 Hydro Bloom                                              | 2016-12-07T00:00:00 | Unregistered Mislabeled | 
| 9110-7144 Quebec Inc      | HESI                              | 3.4-2.6-3.4 Bloom Complex                                          | 2016-12-07T00:00:00 | Mislabeled Unregistered | 
| 9110-7144 Quebec Inc      | HESI                              | Root Complex Root Starter For Plant Growth in Soil, Hydro and Coco | 2016-12-07T00:00:00 | Unregistered Mislabeled | 
| 9110-7144 Quebec Inc      | HESI                              | Super Vit Plant Starter                                            | 2016-12-07T00:00:00 | Mislabeled Unregistered | 
| ABC ORGANICS INC          | ABC Organics Primordial Solutions | 0.3-4.0-4.0 Paleo Bloom                                            | 2016-12-07T00:00:00 | Unregistered            | 
| ABC ORGANICS INC          | ABC Organics Primordial Solutions | 1.0-0.5-4.0 Sea Green                                              | 2016-04-20T00:00:00 | Mislabeled Unregistered | 
| ACADIAN SEAPLANTS LIMITED | Acadian Sea Plants Limited        | 1-0.15-2 Kelp Meal Fertilizer                                      | 2016-12-08T00:00:00 | Unregistered Mislabeled | 
```