# Treasurer - 2009 Scavenger Sale Registered Buyers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/treasurer-2009-scavenger-sale-registered-buyers-ab427) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/6tn4-u7fq) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/6tn4-u7fq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/6tn4-u7fq/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 6tn4-u7fq |
| Name | Treasurer - 2009 Scavenger Sale Registered Buyers |
| Attribution | Cook County Treasurer's Office |
| Category | Property & Taxation |
| Created | 2011-09-26T19:41:21Z |
| Publication Date | 2014-10-09T23:17:12Z |

## Description

2009 Scavenger Sale Registered Buyers. They are registered to purchase taxes on property that have not been paid for 2 years

## Columns

```ls
| Included | Schema Type | Field Name | Name       | Data Type | Render Type |
| ======== | =========== | ========== | ========== | ========= | =========== |
| Yes      | series tag  | buyer_id   | Buyer Id   | text      | text        |
| Yes      | series tag  | buyer_name | Buyer Name | text      | text        |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6tn4-u7fq d:2009-01-01T00:00:00.000Z t:buyer_id=900001 t:buyer_name="WILSON        JEFFREY" m:row_number.6tn4-u7fq=1

series e:6tn4-u7fq d:2009-01-01T00:00:00.000Z t:buyer_id=900002 t:buyer_name="BONFIGLIO     SALLY" m:row_number.6tn4-u7fq=2

series e:6tn4-u7fq d:2009-01-01T00:00:00.000Z t:buyer_id=900003 t:buyer_name="SHABAN        IBRAHIM" m:row_number.6tn4-u7fq=3
```

## Meta Commands

```ls
metric m:row_number.6tn4-u7fq p:long l:"Row Number"

entity e:6tn4-u7fq l:"Treasurer - 2009 Scavenger Sale Registered Buyers" t:attribution="Cook County Treasurer's Office" t:url=https://datacatalog.cookcountyil.gov/api/views/6tn4-u7fq

property e:6tn4-u7fq t:meta.view v:id=6tn4-u7fq v:category="Property & Taxation" v:attributionLink=http://www.cookcountytreasurer.com/ v:averageRating=0 v:name="Treasurer - 2009 Scavenger Sale Registered Buyers" v:attribution="Cook County Treasurer's Office"

property e:6tn4-u7fq t:meta.view.license v:name="Public Domain"

property e:6tn4-u7fq t:meta.view.owner v:id=vtsd-afsj v:screenName=wlinder v:displayName=wlinder

property e:6tn4-u7fq t:meta.view.tableauthor v:id=vtsd-afsj v:screenName=wlinder v:roleName=publisher v:displayName=wlinder
```

## Top Records

```ls
| buyer_id | buyer_name               | 
| ======== | ======================== | 
| 900001   | WILSON JEFFREY           | 
| 900002   | BONFIGLIO SALLY          | 
| 900003   | SHABAN IBRAHIM           | 
| 900004   | LEONARD THOMAS           | 
| 900005   | MEHOVIC DAVID 304        | 
| 900006   | WHEELER DEALER LTD       | 
| 900007   | MATHIS ANDREW            | 
| 900008   | HENRY VANESSA            | 
| 900009   | FORD REALTY ENT INC      | 
| 900010   | MICHAEL J WILSON ASSO PC | 
```