# Treasurer - 2011 Scavenger Sale No-bid PINs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/treasurer-2011-scavenger-sale-no-bid-pins-abb8c) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/z5gk-rh7u) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/z5gk-rh7u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/z5gk-rh7u/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | z5gk-rh7u |
| Name | Treasurer - 2011 Scavenger Sale No-bid PINs |
| Attribution | Cook County Treasurer's Office |
| Category | Property & Taxation |
| Created | 2012-03-16T15:18:33Z |
| Publication Date | 2014-10-09T23:17:02Z |

## Description

Scavenger Tax Sale: A sale held every two years by the Treasurer selling taxes on property with 2 or more years of delinquent taxes.

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
entity e:z5gk-rh7u l:"Treasurer - 2011 Scavenger Sale No-bid PINs" t:attribution="Cook County Treasurer's Office" t:url=https://datacatalog.cookcountyil.gov/api/views/z5gk-rh7u

property e:z5gk-rh7u t:meta.view v:id=z5gk-rh7u v:category="Property & Taxation" v:attributionLink=http://www.cookcountytreasurer.com/ v:averageRating=0 v:name="Treasurer - 2011 Scavenger Sale No-bid PINs" v:attribution="Cook County Treasurer's Office"

property e:z5gk-rh7u t:meta.view.license v:name="Public Domain"

property e:z5gk-rh7u t:meta.view.owner v:id=vtsd-afsj v:screenName=wlinder v:displayName=wlinder

property e:z5gk-rh7u t:meta.view.tableauthor v:id=vtsd-afsj v:screenName=wlinder v:roleName=publisher v:displayName=wlinder
```

## Top Records

```ls
| pin                | tax_type | tax_year | zip_code | 
| ================== | ======== | ======== | ======== | 
| 01-01-314-012-0000 | 0        | 2008     | 0        | 
| 01-01-314-012-0000 | 0        | 2009     | 0        | 
| 01-01-406-011-0000 | 0        | 1991     | 0        | 
| 01-01-406-011-0000 | 0        | 1992     | 0        | 
| 01-01-406-011-0000 | 0        | 1993     | 60010    | 
| 01-01-406-011-0000 | 0        | 1994     | 0        | 
| 01-01-406-011-0000 | 0        | 1995     | 0        | 
| 01-01-406-011-0000 | 0        | 1996     | 0        | 
| 13-15-302-016-0000 | 0        | 1997     | 0        | 
| 27-23-313-037-0000 | 0        | 1998     | 0        | 
```