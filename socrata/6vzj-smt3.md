# Plant Brokers (2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/plant-brokers-2013-b74ea) |
| Metadata | [Link](https://data.maryland.gov/api/views/6vzj-smt3) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/6vzj-smt3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/6vzj-smt3/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 6vzj-smt3 |
| Name | Plant Brokers (2013) |
| Attribution | MD Department of Agriculture |
| Category | Agriculture |
| Tags | plants, plant dealers, landscaping |
| Created | 2013-06-28T17:21:34Z |
| Publication Date | 2013-10-25T19:18:36Z |

## Description

Plant brokers in Maryland.

## Columns

```ls
| Included | Schema Type | Field Name | Name    | Data Type | Render Type |
| ======== | =========== | ========== | ======= | ========= | =========== |
| Yes      | series tag  | company    | COMPANY | text      | text        |
| Yes      | series tag  | county     | COUNTY  | text      | text        |
| Yes      | series tag  | phone1     | PHONE1  | phone     | phone       |
| Yes      | series tag  | phone2     | PHONE2  | phone     | phone       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6vzj-smt3 d:2013-01-01T00:00:00.000Z t:phone_number=4434580236 t:county="ANNE ARUNDEL" t:company="BUNTING'S TREE FARM, LLC" m:row_number.6vzj-smt3=1

series e:6vzj-smt3 d:2013-01-01T00:00:00.000Z t:county=BALTIMORE t:company="ANNA NICHOLS" m:row_number.6vzj-smt3=2

series e:6vzj-smt3 d:2013-01-01T00:00:00.000Z t:phone_number=4106022341 t:county=BALTIMORE t:company="GROUNDSCAPE, INC." m:row_number.6vzj-smt3=3
```

## Meta Commands

```ls
metric m:row_number.6vzj-smt3 p:long l:"Row Number"

entity e:6vzj-smt3 l:"Plant Brokers (2013)" t:attribution="MD Department of Agriculture" t:url=https://data.maryland.gov/api/views/6vzj-smt3

property e:6vzj-smt3 t:meta.view v:id=6vzj-smt3 v:category=Agriculture v:attributionLink=http://www.mda.maryland.gov v:averageRating=0 v:name="Plant Brokers (2013)" v:attribution="MD Department of Agriculture"

property e:6vzj-smt3 t:meta.view.owner v:id=tpc4-inqc v:screenName="Lisa Stollof" v:displayName="Lisa Stollof"

property e:6vzj-smt3 t:meta.view.tableauthor v:id=tpc4-inqc v:screenName="Lisa Stollof" v:roleName=editor v:displayName="Lisa Stollof"
```

## Top Records

```ls
| company                          | county       | phone1             | phone2             | 
| ================================ | ============ | ================== | ================== | 
| BUNTING'S TREE FARM, LLC         | ANNE ARUNDEL | [4434580922, null] | [4434580236, null] | 
| ANNA NICHOLS                     | BALTIMORE    | [null, null]       | [null, null]       | 
| GROUNDSCAPE, INC.                | BALTIMORE    | [4106022063, null] | [4106022341, null] | 
| ABORTRAGE PLANT BROKERAGE, LLC   | ANNE ARUNDEL | [null, null]       | [null, null]       | 
| HOLLY SPRING NURSERY, INC.       | BALTIMORE    | [4102396864, null] | [null, null]       | 
| PINE TREE DISTRIBUTORS, INC.     | QUEEN ANNE'S | [4107780964, null] | [null, null]       | 
| MARYLAND PLANTS & SUPPLIES, INC. | BALTIMORE    | [4106873885, null] | [null, null]       | 
| HORTUSALES                       | CARROLL      | [4104899280, null] | [4104899281, null] | 
| JGL DESIGN ASSOCIATES            | BALTIMORE    | [4103295208, null] | [null, null]       | 
| PLANTABBS PRODUCTS               | BALTIMORE    | [4107805494, null] | [4107805496, null] | 
```