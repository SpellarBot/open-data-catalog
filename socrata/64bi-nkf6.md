# IDVA - Grant Payout Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idva-grant-payout-data-c8485) |
| Metadata | [Link](https://data.illinois.gov/api/views/64bi-nkf6) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/64bi-nkf6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/64bi-nkf6/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 64bi-nkf6 |
| Name | IDVA - Grant Payout Data |
| Attribution | Illinois Department of Veterans Affairs |
| Category | Reference |
| Tags | idva, veteran, vet, veterans cash, veterans grant |
| Created | 2012-01-31T21:12:34Z |
| Publication Date | 2012-01-31T21:46:57Z |

## Description

This is data that shows where the grants have been paid out to. These funds are appropriations collected through the Veterans Cash lottery program sponsored by the Illinois Department of Veterans Affairs.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | organization   | Organization   | text      | text        |
| Yes      | numeric metric | grant_amount   | Grant Amount   | money     | money       |
| Yes      | series tag     | grant_category | Grant Category | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:64bi-nkf6 d:2012-01-31T13:12:47.000Z t:grant_category="Veteran Disability Benefits - VSO Funding" t:organization="African American PTSD Association" m:grant_amount=100000

series e:64bi-nkf6 d:2012-01-31T13:12:47.000Z t:grant_category="Post-Traumatic Stress Disorder" t:organization="Alexian Brothers Hospital Network" m:grant_amount=97500

series e:64bi-nkf6 d:2012-01-31T13:12:47.000Z t:grant_category="Veteran Disability Benefits - VSO Funding" t:organization="American Legion Dept. of IL" m:grant_amount=100000
```

## Meta Commands

```ls
metric m:grant_amount p:double l:"Grant Amount" t:dataTypeName=money

entity e:64bi-nkf6 l:"IDVA - Grant Payout Data" t:attribution="Illinois Department of Veterans Affairs" t:url=https://data.illinois.gov/api/views/64bi-nkf6

property e:64bi-nkf6 t:meta.view v:id=64bi-nkf6 v:category=Reference v:averageRating=0 v:name="IDVA - Grant Payout Data" v:attribution="Illinois Department of Veterans Affairs"

property e:64bi-nkf6 t:meta.view.owner v:id=ajuq-3qfp v:screenName="Chris Pence" v:displayName="Chris Pence"

property e:64bi-nkf6 t:meta.view.tableauthor v:id=ajuq-3qfp v:screenName="Chris Pence" v:displayName="Chris Pence"
```

## Top Records

```ls
| :updated_at | organization                          | grant_amount | grant_category                            | 
| =========== | ===================================== | ============ | ========================================= | 
| 1328015567  | African American PTSD Association     | 100000.00    | Veteran Disability Benefits - VSO Funding | 
| 1328015567  | Alexian Brothers Hospital Network     | 97500.00     | Post-Traumatic Stress Disorder            | 
| 1328015567  | American Legion Dept. of IL           | 100000.00    | Veteran Disability Benefits - VSO Funding | 
| 1328015567  | American Legion of Illinois           | 100000.00    | Veteran Disability Benefits - VSO Funding | 
| 1328015567  | American Legion Post 615              | 45000.00     | Veteran Disability Benefits - VSO Funding | 
| 1328015567  | American Veterans Post #260 Woodstock | 35000.00     | Veteran Long-Term Care                    | 
| 1328015567  | AMVETS 104                            | 5720.00      | Veteran Long-Term Care                    | 
| 1328015567  | AMVETS Post # 32 of IL                | 34900.00     | Veteran Long-Term Care                    | 
| 1328015567  | AMVETS Post 104                       | 90000.00     | Veteran Long-Term Care                    | 
| 1328015567  | AMVETS POST 104                       | 1257.00      | Veteran Long-Term Care                    | 
```