# Treasurer - 2009 Scavenger Sale Sold PINS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/treasurer-2009-scavenger-sale-sold-pins-8fac5) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/wsmt-5pai) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/wsmt-5pai/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/wsmt-5pai/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | wsmt-5pai |
| Name | Treasurer - 2009 Scavenger Sale Sold PINS |
| Attribution | Cook County Treasurer's Office |
| Category | Property & Taxation |
| Created | 2011-10-25T21:40:56Z |
| Publication Date | 2014-10-09T22:57:05Z |

## Description

This is a File that contains Scavenger Sale Sold PIN's

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
entity e:wsmt-5pai l:"Treasurer - 2009 Scavenger Sale Sold PINS" t:attribution="Cook County Treasurer's Office" t:url=https://datacatalog.cookcountyil.gov/api/views/wsmt-5pai

property e:wsmt-5pai t:meta.view v:id=wsmt-5pai v:category="Property & Taxation" v:attributionLink=http://www.cookcountytreasurer.com/ v:averageRating=0 v:name="Treasurer - 2009 Scavenger Sale Sold PINS" v:attribution="Cook County Treasurer's Office"

property e:wsmt-5pai t:meta.view.license v:name="Public Domain"

property e:wsmt-5pai t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:wsmt-5pai t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| pin                | tax_type | tax_year | zip_code | 
| ================== | ======== | ======== | ======== | 
| 01-12-107-008-0000 | 0        | 2004     | 60010    | 
| 01-12-107-008-0000 | 0        | 2005     | 60010    | 
| 02-15-407-049-1113 | 0        | 1999     | 60067    | 
| 02-15-407-049-1113 | 0        | 2005     | 60067    | 
| 02-22-102-010-0000 | 0        | 2004     | 60067    | 
| 02-22-102-010-0000 | 0        | 2006     | 60067    | 
| 02-22-102-010-0000 | 0        | 2007     | 60067    | 
| 03-02-203-006-0000 | 0        | 2006     | 60090    | 
| 03-02-203-006-0000 | 0        | 2007     | 60090    | 
| 03-02-410-083-1129 | 0        | 2006     | 60090    | 
```