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

## Description

Violations issued by Townships. Data from 2005 through part of 2011. Data last updated September 2011.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | time           | fiscal_year   | Fiscal Year   | text      | text        |
| Yes      | series tag     | township_name | Township Name | text      | text        |
| Yes      | numeric metric | violation     | Violation     | number    | number      |
| Yes      | numeric metric | totals        | Totals        | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:z2s8-vdru d:2005-01-01T00:00:00.000Z t:township_name=Barrington m:violation=11 m:totals=11

series e:z2s8-vdru d:2005-01-01T00:00:00.000Z t:township_name=Berwyn m:violation=0 m:totals=0

series e:z2s8-vdru d:2005-01-01T00:00:00.000Z t:township_name=Bloom m:violation=46 m:totals=46
```

## Meta Commands

```ls
metric m:violation p:integer l:Violation t:dataTypeName=number

metric m:totals p:integer l:Totals t:dataTypeName=number

entity e:z2s8-vdru l:"Building and Zoning - Violations Issued - 2005 through part of 2011" t:attribution="Cook County Department of Building and Zoning" t:url=https://datacatalog.cookcountyil.gov/api/views/z2s8-vdru

property e:z2s8-vdru t:meta.view d:2017-09-25T07:27:46.172Z v:averageRating=0 v:name="Building and Zoning - Violations Issued - 2005 through part of 2011" v:attribution="Cook County Department of Building and Zoning" v:attributionLink=http://www.cookcountyil.gov/BuildingZoning v:id=z2s8-vdru v:category="Economic Development"

property e:z2s8-vdru t:meta.view.license d:2017-09-25T07:27:46.172Z v:name="Public Domain"

property e:z2s8-vdru t:meta.view.owner d:2017-09-25T07:27:46.172Z v:displayName=HJF v:id=8gct-yg9j v:screenName=HJF

property e:z2s8-vdru t:meta.view.tableauthor d:2017-09-25T07:27:46.172Z v:displayName=HJF v:id=8gct-yg9j v:screenName=HJF
```

## Top Records

```ls
| fiscal_year | township_name | violation | totals | 
| =========== | ============= | ========= | ====== | 
| 2005        | Barrington    | 11        | 11     | 
| 2005        | Berwyn        | 0         | 0      | 
| 2005        | Bloom         | 46        | 46     | 
| 2005        | Bremen        | 67        | 67     | 
| 2005        | Calumet       | 0         | 0      | 
| 2005        | Cicero        | 0         | 0      | 
| 2005        | Elk Grove     | 57        | 57     | 
| 2005        | Evanston      | 0         | 0      | 
| 2005        | Hanover       | 70        | 70     | 
| 2005        | Lemont        | 111       | 111    | 
```