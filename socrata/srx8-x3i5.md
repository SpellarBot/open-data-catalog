# Treasurer - 2009 Scavenger Sale No-bid PINS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/treasurer-2009-scavenger-sale-no-bid-pins-3dbb6) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/srx8-x3i5) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/srx8-x3i5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/srx8-x3i5/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | srx8-x3i5 |
| Name | Treasurer - 2009 Scavenger Sale No-bid PINS |
| Attribution | Cook County Treasurer's Office |
| Category | Property & Taxation |
| Tags | cook county treasurer, 2009 scavenger sale, tax sale, no bid pin |
| Created | 2011-10-25T22:13:12Z |
| Publication Date | 2011-10-25T22:20:17Z |

## Description

This file contains the 2009 Scavenger Sale No Bid PIN's.

## Columns

```ls
| Included | Schema Type | Field Name | Name     | Data Type | Render Type |
| ======== | =========== | ========== | ======== | ========= | =========== |
| Yes      | series tag  | pin        | PIN      | text      | text        |
| Yes      | series tag  | tax_type   | Tax Type | text      | number      |
| Yes      | time        | tax_year   | Tax Year | number    | text        |
| Yes      | series tag  | zip_code   | Zip Code | text      | text        |
```

## Time Field

```ls
Value = tax_year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:srx8-x3i5 l:"Treasurer - 2009 Scavenger Sale No-bid PINS" t:attribution="Cook County Treasurer's Office" t:url=https://datacatalog.cookcountyil.gov/api/views/srx8-x3i5

property e:srx8-x3i5 t:meta.view v:id=srx8-x3i5 v:category="Property & Taxation" v:attributionLink=http://www.cookcountytreasurer.com/ v:averageRating=0 v:name="Treasurer - 2009 Scavenger Sale No-bid PINS" v:attribution="Cook County Treasurer's Office"

property e:srx8-x3i5 t:meta.view.license v:name="Public Domain"

property e:srx8-x3i5 t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:srx8-x3i5 t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| pin                | tax_type | tax_year | zip_code | 
| ================== | ======== | ======== | ======== | 
| 01-01-406-011-0000 | 0        | 2003     | 00000    | 
| 01-01-406-011-0000 | 0        | 2004     | 00000    | 
| 01-01-406-011-0000 | 0        | 2005     | 00000    | 
| 01-01-406-011-0000 | 0        | 2006     | 00000    | 
| 01-01-406-011-0000 | 0        | 2007     | 00000    | 
| 01-01-406-011-0000 | 0        | 1989     | 60010    | 
| 01-01-406-011-0000 | 0        | 1990     | 60010    | 
| 01-01-406-011-0000 | 0        | 1991     | 60010    | 
| 01-01-406-011-0000 | 0        | 1992     | 60010    | 
| 01-01-406-011-0000 | 0        | 1993     | 60010    | 
```