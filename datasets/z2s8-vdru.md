# Building and Zoning - Violations Issued - 2005 through part of 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-and-zoning-violations-issued-2005-through-part-of-2011-da8d1) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/z2s8-vdru) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/z2s8-vdru/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/z2s8-vdru/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | z2s8-vdru |
| Name | Building and Zoning - Violations Issued - 2005 through part of 2011 |
| Attribution | Cook County Department of Building and Zoning |
| Category | Economic Development |
| Created | 2011-09-27T16:11:44Z |
| Publication Date | 2014-10-09T23:06:48Z |
| Rows Updated | 2014-10-09T23:06:42Z |

## Description

Violations issued by Townships. Data from 2005 through part of 2011. Data last updated September 2011.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | fiscal_year   | Fiscal Year   | text      | text        |
| Yes      | series tag     | township_name | Township Name | text      | text        |
| Yes      | numeric metric | violation     | Violation     | number    | number      |
| Yes      | numeric metric | totals        | Totals        | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:z2s8-vdru d:2005-01-01T00:00:00.000Z t:fiscal_year=2005 t:township_name=Barrington m:violation=11 m:totals=11

series e:z2s8-vdru d:2005-01-01T00:00:00.000Z t:fiscal_year=2005 t:township_name=Berwyn m:violation=0 m:totals=0

series e:z2s8-vdru d:2005-01-01T00:00:00.000Z t:fiscal_year=2005 t:township_name=Bloom m:violation=46 m:totals=46
```

## Meta Commands

```ls
metric m:violation p:integer l:Violation t:dataTypeName=number

metric m:totals p:integer l:Totals t:dataTypeName=number

entity e:z2s8-vdru l:"Building and Zoning - Violations Issued - 2005 through part of 2011" t:attribution="Cook County Department of Building and Zoning" t:url=https://datacatalog.cookcountyil.gov/api/views/z2s8-vdru

property e:z2s8-vdru t:meta.view v:id=z2s8-vdru v:category="Economic Development" v:attributionLink=http://www.cookcountyil.gov/BuildingZoning v:averageRating=0 v:name="Building and Zoning - Violations Issued - 2005 through part of 2011" v:attribution="Cook County Department of Building and Zoning"

property e:z2s8-vdru t:meta.view.license v:name="Public Domain"

property e:z2s8-vdru t:meta.view.owner v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF

property e:z2s8-vdru t:meta.view.tableauthor v:id=8gct-yg9j v:screenName=HJF v:displayName=HJF
```