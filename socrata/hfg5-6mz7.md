# Treasurer - 2009 Annual Tax Sale Registered Buyers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/treasurer-2009-annual-tax-sale-registered-buyers-44c41) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/hfg5-6mz7) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/hfg5-6mz7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/hfg5-6mz7/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | hfg5-6mz7 |
| Name | Treasurer - 2009 Annual Tax Sale Registered Buyers |
| Attribution | Cook County Treasurer's Office |
| Category | Property & Taxation |
| Created | 2011-10-24T18:01:40Z |
| Publication Date | 2014-10-09T22:57:16Z |

## Description

2009 Tax Sale Registered Buyers. They are registered to purchase taxes on property that have not been paid for 2 years

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | numeric metric | buyer_id_  | Buyer ID   | number    | text        |
| Yes      | series tag     | buyer_name | Buyer Name | text      | text        |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hfg5-6mz7 d:2009-01-01T00:00:00.000Z t:buyer_name="WESTERN SITES LLC" m:buyer_id_=900001

series e:hfg5-6mz7 d:2009-01-01T00:00:00.000Z t:buyer_name="SABRE INVE STMENTS, LLC" m:buyer_id_=900002

series e:hfg5-6mz7 d:2009-01-01T00:00:00.000Z t:buyer_name="GOLDNER HELEN M" m:buyer_id_=900003
```

## Meta Commands

```ls
metric m:buyer_id_ p:integer l:"Buyer ID" t:dataTypeName=number

entity e:hfg5-6mz7 l:"Treasurer - 2009 Annual Tax Sale Registered Buyers" t:attribution="Cook County Treasurer's Office" t:url=https://datacatalog.cookcountyil.gov/api/views/hfg5-6mz7

property e:hfg5-6mz7 t:meta.view v:id=hfg5-6mz7 v:category="Property & Taxation" v:attributionLink=http://www.cookcountytreasurer.com/ v:averageRating=0 v:name="Treasurer - 2009 Annual Tax Sale Registered Buyers" v:attribution="Cook County Treasurer's Office"

property e:hfg5-6mz7 t:meta.view.license v:name="Public Domain"

property e:hfg5-6mz7 t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:hfg5-6mz7 t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| buyer_id_ | buyer_name              | 
| ========= | ======================= | 
| 900001    | WESTERN SITES LLC       | 
| 900002    | SABRE INVE STMENTS, LLC | 
| 900003    | GOLDNER HELEN M         | 
| 900004    | INTERSTATE FUNDING      | 
| 900005    | OAK PARK INVESTMENTS    | 
| 900006    | BELMONT REALTY COP      | 
| 900007    | OKOTETE PATRICIA L      | 
| 900008    | MUNICIPAL POINT FUNDING | 
| 900009    | ANTONOW CHRIS S         | 
| 900010    | PUNJABI ANOOP           | 
```