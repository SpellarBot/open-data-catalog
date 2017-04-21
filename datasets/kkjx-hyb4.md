# Program ID Descriptions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/program-id-descriptions-04737) |
| Metadata | [Link](https://data.hawaii.gov/api/views/kkjx-hyb4) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/kkjx-hyb4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/kkjx-hyb4/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | kkjx-hyb4 |
| Name | Program ID Descriptions |
| Created | 2014-01-31T19:46:53Z |
| Publication Date | 2014-01-31T19:47:40Z |

## Description

for use with Expenditure data

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | pgm_id      | PGM ID      | text      | text        |
| Yes      | series tag  | description | DESCRIPTION | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kkjx-hyb4 d:2014-01-31T11:46:56.000Z t:description="FINANCIAL ASSISTANCE FOR AGRICULTURE" t:pgm_id=AGR101 m:row_number.kkjx-hyb4=1

series e:kkjx-hyb4 d:2014-01-31T11:46:56.000Z t:description="FINANCIAL ASSISTANCE FOR AQUACULTURE" t:pgm_id=AGR102 m:row_number.kkjx-hyb4=2

series e:kkjx-hyb4 d:2014-01-31T11:46:56.000Z t:description="PRICE & PRODUCTION CONTROLS FOR DAIRY PRDTS*" t:pgm_id=AGR103 m:row_number.kkjx-hyb4=3
```

## Meta Commands

```ls
metric m:row_number.kkjx-hyb4 p:long l:"Row Number"

entity e:kkjx-hyb4 l:"Program ID Descriptions" t:url=https://data.hawaii.gov/api/views/kkjx-hyb4

property e:kkjx-hyb4 t:meta.view v:id=kkjx-hyb4 v:averageRating=0 v:name="Program ID Descriptions"

property e:kkjx-hyb4 t:meta.view.owner v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:displayName="Open Data Portal Administrator"

property e:kkjx-hyb4 t:meta.view.tableauthor v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"
```

## Top Records

```ls
| :updated_at | pgm_id | description                                  | 
| =========== | ====== | ============================================ | 
| 1391168816  | AGR101 | FINANCIAL ASSISTANCE FOR AGRICULTURE         | 
| 1391168816  | AGR102 | FINANCIAL ASSISTANCE FOR AQUACULTURE         | 
| 1391168816  | AGR103 | PRICE & PRODUCTION CONTROLS FOR DAIRY PRDTS* | 
| 1391168816  | AGR121 | PLANT QUARANTINE*                            | 
| 1391168816  | AGR122 | PLANT PEST AND DISEASE CONTROL               | 
| 1391168816  | AGR131 | ANIMAL QUARANTINE                            | 
| 1391168816  | AGR132 | ANIMAL DISEASE CONTROL                       | 
| 1391168816  | AGR141 | AGRICULTURAL RESOURCE MANAGEMENT             | 
| 1391168816  | AGR151 | MKG INFO & DISTRIB SYSTEMS IMPROVEMT FOR AGR | 
| 1391168816  | AGR153 | AQUACULTURE DEVELOPMENT                      | 
```