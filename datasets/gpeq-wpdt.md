# Stores Supplying Extra Trash Stickers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/stores-supplying-extra-trash-stickers) |
| Metadata | [Link](https://data.austintexas.gov/api/views/gpeq-wpdt) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/gpeq-wpdt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/gpeq-wpdt/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | gpeq-wpdt |
| Name | Stores Supplying Extra Trash Stickers |
| Tags | extra, garbage, trash, arr, sticker |
| Created | 2016-03-04T17:44:06Z |
| Publication Date | 2016-03-07T19:55:16Z |

## Description

Extra bags of trash that do not fit in your trash cart with the lid closed must be placed next to the trash cart and tagged with an Extra Trash Sticker, which can be purchased at H-E-B, Randall's and most local grocery stores for $4 + tax. Extra bags without a sticker will be charged a per-bag fee of $9.60 + tax. If you find that you often set out extra bagged garbage, consider switching to a larger cart for $15 (plus applicable monthly cart fee).

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | store       | Store      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:gpeq-wpdt d:2016-03-04T09:44:09.000Z t:store=Randall?s m:row_number.gpeq-wpdt=1

series e:gpeq-wpdt d:2017-03-07T00:56:49.000Z t:store=H.E.B. m:row_number.gpeq-wpdt=2

series e:gpeq-wpdt d:2017-03-07T00:57:31.000Z t:store=Randall?s m:row_number.gpeq-wpdt=3
```

## Meta Commands

```ls
metric m:row_number.gpeq-wpdt p:long l:"Row Number"

entity e:gpeq-wpdt l:"Stores Supplying Extra Trash Stickers" t:url=https://data.austintexas.gov/api/views/gpeq-wpdt

property e:gpeq-wpdt t:meta.view v:id=gpeq-wpdt v:averageRating=0 v:name="Stores Supplying Extra Trash Stickers"

property e:gpeq-wpdt t:meta.view.owner v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:displayName=erin.benoit@austintexas.gov

property e:gpeq-wpdt t:meta.view.tableauthor v:id=nnyu-u79i v:screenName=erin.benoit@austintexas.gov v:roleName=editor v:displayName=erin.benoit@austintexas.gov
```

## Top Records

```ls
| :updated_at | store     | 
| =========== | ========= | 
| 1457084649  | Randall?s | 
| 1488848209  | H.E.B.    | 
| 1488848251  | Randall?s | 
| 1488848270  | H.E.B.    | 
| 1488853902  | Randall?s | 
| 1488853902  | H.E.B.    | 
| 1488853902  | Randall?s | 
| 1488855653  | H.E.B.    | 
| 1488855691  | H.E.B.    | 
| 1488855702  | H.E.B.    | 
```