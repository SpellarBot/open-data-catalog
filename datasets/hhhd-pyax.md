# Building and Zoning - Zoning Applications Applied For - Fiscal Years 2005 through 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-and-zoning-zoning-applications-applied-for-fiscal-years-2005-through-2011-dfe25) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/hhhd-pyax) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/hhhd-pyax/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/hhhd-pyax/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | hhhd-pyax |
| Name | Building and Zoning - Zoning Applications Applied For - Fiscal Years 2005 through 2011 |
| Attribution | Cook County Department of Building and Zoning |
| Category | Economic Development |
| Created | 2011-09-27T17:23:48Z |
| Publication Date | 2014-10-09T22:59:31Z |

## Description

Zoning applications applied for by Township in Fiscal Years 2005 through part of 2011. Data last updated September 2011.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | time           | fiscal_year    | Fiscal Year    | text      | text        |
| Yes      | series tag     | township_name  | Township Name  | text      | text        |
| Yes      | numeric metric | map_amendments | Map Amendments | number    | number      |
| Yes      | numeric metric | special_uses   | Special Uses   | number    | number      |
| Yes      | numeric metric | variances      | Variances      | number    | number      |
| Yes      | numeric metric | totals         | Totals         | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hhhd-pyax d:2005-01-01T00:00:00.000Z t:township_name=Barrington m:variances=0 m:special_uses=1 m:totals=1 m:map_amendments=0

series e:hhhd-pyax d:2005-01-01T00:00:00.000Z t:township_name=Berwyn m:variances=0 m:special_uses=0 m:totals=0 m:map_amendments=0

series e:hhhd-pyax d:2005-01-01T00:00:00.000Z t:township_name=Bloom m:variances=5 m:special_uses=1 m:totals=6 m:map_amendments=0
```

## Meta Commands

```ls
metric m:map_amendments p:integer l:"Map Amendments" t:dataTypeName=number

metric m:special_uses p:integer l:"Special Uses" t:dataTypeName=number

metric m:variances p:integer l:Variances t:dataTypeName=number

metric m:totals p:integer l:Totals t:dataTypeName=number

entity e:hhhd-pyax l:"Building and Zoning - Zoning Applications Applied For - Fiscal Years 2005 through 2011" t:attribution="Cook County Department of Building and Zoning" t:url=https://datacatalog.cookcountyil.gov/api/views/hhhd-pyax

property e:hhhd-pyax t:meta.view v:id=hhhd-pyax v:category="Economic Development" v:attributionLink=http://www.cookcountyil.gov/BuildingZoning v:averageRating=0 v:name="Building and Zoning - Zoning Applications Applied For - Fiscal Years 2005 through 2011" v:attribution="Cook County Department of Building and Zoning"

property e:hhhd-pyax t:meta.view.license v:name="Public Domain"

property e:hhhd-pyax t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:hhhd-pyax t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```

## Top Records

```ls
| fiscal_year | township_name | map_amendments | special_uses | variances | totals | 
| =========== | ============= | ============== | ============ | ========= | ====== | 
| 2005        | Barrington    | 0              | 1            | 0         | 1      | 
| 2005        | Berwyn        | 0              | 0            | 0         | 0      | 
| 2005        | Bloom         | 0              | 1            | 5         | 6      | 
| 2005        | Bremen        | 0              | 1            | 2         | 3      | 
| 2005        | Calumet       | 0              | 0            | 0         | 0      | 
| 2005        | Cicero        | 0              | 0            | 0         | 0      | 
| 2005        | Elk Grove     | 0              | 1            | 5         | 6      | 
| 2005        | Evanston      | 0              | 0            | 0         | 0      | 
| 2005        | Hanover       | 1              | 0            | 5         | 6      | 
| 2005        | Lemont        | 0              | 0            | 2         | 2      | 
```