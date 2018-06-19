# IDOR FY 2011 Lottery Sales by Zip Code

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idor-fy-2011-lottery-sales-by-zip-code-a8768) |
| Metadata | [Link](https://data.illinois.gov/api/views/r9kx-zjnk) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/r9kx-zjnk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/r9kx-zjnk/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | r9kx-zjnk |
| Name | IDOR FY 2011 Lottery Sales by Zip Code |
| Attribution | Illinois Department of Revenue |
| Category | Economics |
| Tags | revenue, lottery |
| Created | 2011-06-15T16:38:45Z |
| Publication Date | 2011-06-15T16:38:45Z |

## Description

Sales report SLS989-01 reflects all Lottery sales for fiscal year 2011 (current). The games are Instant, Pic 3, Pic 4, Subscription, Mega, Lotto, Little Lotto, Powerball, Pick-n-Play and Raffle.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | numeric metric | sales_amount | SALES AMOUNT | money     | money       |
| Yes      | series tag     | zip_code     | ZIP CODE     | text      | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:r9kx-zjnk d:2011-01-01T00:00:00.000Z t:zip_code=60619 m:sales_amount=26805228

series e:r9kx-zjnk d:2011-01-01T00:00:00.000Z t:zip_code=60628 m:sales_amount=20964145.5

series e:r9kx-zjnk d:2011-01-01T00:00:00.000Z t:zip_code=60651 m:sales_amount=20036299.5
```

## Meta Commands

```ls
metric m:sales_amount p:double l:"SALES AMOUNT" t:dataTypeName=money

entity e:r9kx-zjnk l:"IDOR FY 2011 Lottery Sales by Zip Code" t:attribution="Illinois Department of Revenue" t:url=https://data.illinois.gov/api/views/r9kx-zjnk

property e:r9kx-zjnk t:meta.view v:id=r9kx-zjnk v:category=Economics v:averageRating=0 v:name="IDOR FY 2011 Lottery Sales by Zip Code" v:attribution="Illinois Department of Revenue"

property e:r9kx-zjnk t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:r9kx-zjnk t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| sales_amount | zip_code | 
| ============ | ======== | 
| 26805228.00  | 60619    | 
| 20964145.50  | 60628    | 
| 20036299.50  | 60651    | 
| 19844371.50  | 60639    | 
| 19333370.00  | 60634    | 
| 19043721.50  | 60618    | 
| 19019133.50  | 60647    | 
| 18733402.50  | 60617    | 
| 18703401.50  | 60620    | 
| 18154487.00  | 60453    | 
```