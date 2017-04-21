# Treasurer - 2009 Annual Tax Sale Sold PINS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/treasurer-2009-annual-tax-sale-sold-pins-bb005) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/ae8r-hsd6) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ae8r-hsd6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ae8r-hsd6/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | ae8r-hsd6 |
| Name | Treasurer - 2009 Annual Tax Sale Sold PINS |
| Attribution | Cook County Treasurer's Office |
| Category | Property & Taxation |
| Tags | cook county treasurer, scavenger sale, 2009 tax sale, sold pin |
| Created | 2011-10-25T22:46:10Z |
| Publication Date | 2011-10-25T22:55:33Z |

## Description

Annual Tax Sale: A yearly auction of delinquent taxes where a tax buyer (purchaser) pays the delinquent taxes due on a parcel. This results in a lien on the property. The property owner must repay the tax buyer with interest for the amount of the sale ? this is known as ?redemption.? If redemption does not occur within a set time period, the tax buyer can obtain legal title to the property ? this is referred to as a ?tax deed.?

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
entity e:ae8r-hsd6 l:"Treasurer - 2009 Annual Tax Sale Sold PINS" t:attribution="Cook County Treasurer's Office" t:url=https://datacatalog.cookcountyil.gov/api/views/ae8r-hsd6

property e:ae8r-hsd6 t:meta.view v:id=ae8r-hsd6 v:category="Property & Taxation" v:attributionLink=http://www.cookcountytreasurer.com/ v:averageRating=0 v:name="Treasurer - 2009 Annual Tax Sale Sold PINS" v:attribution="Cook County Treasurer's Office"

property e:ae8r-hsd6 t:meta.view.license v:name="Public Domain"

property e:ae8r-hsd6 t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:ae8r-hsd6 t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| pin                | tax_type | tax_year | zip_code | 
| ================== | ======== | ======== | ======== | 
| 01-01-101-029-0000 | 0        | 2009     | 60010    | 
| 01-01-204-019-0000 | 0        | 2009     | 60010    | 
| 01-01-211-009-0000 | 0        | 2009     | 60010    | 
| 01-01-307-017-0000 | 0        | 2009     | 60010    | 
| 01-01-307-018-0000 | 0        | 2009     | 60010    | 
| 01-01-405-002-0000 | 0        | 2009     | 60010    | 
| 01-01-406-017-0000 | 0        | 2009     | 00000    | 
| 01-01-407-008-0000 | 0        | 2009     | 00000    | 
| 01-03-200-029-0000 | 0        | 2009     | 60010    | 
| 01-04-100-008-0000 | 0        | 2009     | 60010    | 
```