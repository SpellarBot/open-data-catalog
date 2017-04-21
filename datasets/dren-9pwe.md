# Treasurer - 2011 Scavenger Sale Registered Buyers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/treasurer-2011-scavenger-sale-registered-buyers-4e732) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/dren-9pwe) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/dren-9pwe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/dren-9pwe/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | dren-9pwe |
| Name | Treasurer - 2011 Scavenger Sale Registered Buyers |
| Attribution | Cook County Treasurer's Office |
| Category | Property & Taxation |
| Created | 2012-03-16T15:35:12Z |
| Publication Date | 2014-10-09T23:17:33Z |

## Description

2011 Scavenger Sale Registered Buyers. They are registered to purchase taxes on property that have not been paid for 2 years

## Columns

```ls
| Included | Schema Type | Field Name | Name       | Data Type | Render Type |
| ======== | =========== | ========== | ========== | ========= | =========== |
| Yes      | series tag  | buyer_id   | Buyer ID   | text      | text        |
| Yes      | series tag  | buyer_name | Buyer Name | text      | text        |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dren-9pwe d:2011-01-01T00:00:00.000Z t:buyer_id=1100000 t:buyer_name="COUNTY OF COOK" m:row_number.dren-9pwe=1

series e:dren-9pwe d:2011-01-01T00:00:00.000Z t:buyer_id=1100001 t:buyer_name="HUBERTS JR    DENNIS    L" m:row_number.dren-9pwe=2

series e:dren-9pwe d:2011-01-01T00:00:00.000Z t:buyer_id=1100002 t:buyer_name="VARDA         TONY" m:row_number.dren-9pwe=3
```

## Meta Commands

```ls
metric m:row_number.dren-9pwe p:long l:"Row Number"

entity e:dren-9pwe l:"Treasurer - 2011 Scavenger Sale Registered Buyers" t:attribution="Cook County Treasurer's Office" t:url=https://datacatalog.cookcountyil.gov/api/views/dren-9pwe

property e:dren-9pwe t:meta.view v:id=dren-9pwe v:category="Property & Taxation" v:attributionLink=http://www.cookcountytreasurer.com/ v:averageRating=0 v:name="Treasurer - 2011 Scavenger Sale Registered Buyers" v:attribution="Cook County Treasurer's Office"

property e:dren-9pwe t:meta.view.license v:name="Public Domain"

property e:dren-9pwe t:meta.view.owner v:id=vtsd-afsj v:screenName=wlinder v:displayName=wlinder

property e:dren-9pwe t:meta.view.tableauthor v:id=vtsd-afsj v:screenName=wlinder v:roleName=publisher v:displayName=wlinder
```

## Top Records

```ls
| buyer_id | buyer_name          | 
| ======== | =================== | 
| 1100000  | COUNTY OF COOK      | 
| 1100001  | HUBERTS JR DENNIS L | 
| 1100002  | VARDA TONY          | 
| 1100003  | PATTERSON VICTORIA  | 
| 1100004  | WILLIAMS JOHNNY     | 
| 1100005  | FRANKLIN ROBERT S   | 
| 1100006  | DEMIR ORHAN         | 
| 1100007  | CALDWELL HAROLD     | 
| 1100008  | MCCASTER WENDELL    | 
| 1100009  | TAIYM DANIAL        | 
```