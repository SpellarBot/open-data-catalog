# Table 16: Solid Waste Generated Per Person (Pounds)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-16-solid-waste-generated-per-person-pounds-175f6) |
| Metadata | [Link](https://data.hawaii.gov/api/views/eex2-n8qt) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/eex2-n8qt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/eex2-n8qt/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | eex2-n8qt |
| Name | Table 16: Solid Waste Generated Per Person (Pounds) |
| Attribution | DOH |
| Category | Health |
| Tags | solid, waste, generated |
| Created | 2012-08-01T00:15:45Z |
| Publication Date | 2012-08-01T00:16:23Z |

## Description

DOH Environmental Indicators

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       |                | _             | #             | number    | number      |
| Yes      | time           | calendar_year | Calendar Year | number    | text        |
| Yes      | numeric metric | hawaii        | Hawaii        | number    | number      |
| Yes      | numeric metric | national      | National      | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _
```

## Data Commands

```ls
series e:eex2-n8qt d:2006-01-01T00:00:00.000Z m:national=4.6 m:hawaii=9.3

series e:eex2-n8qt d:2007-01-01T00:00:00.000Z m:national=4.6 m:hawaii=9.6

series e:eex2-n8qt d:2008-01-01T00:00:00.000Z m:national=4.5 m:hawaii=9.2
```

## Meta Commands

```ls
metric m:hawaii p:float l:Hawaii t:dataTypeName=number

metric m:national p:float l:National t:dataTypeName=number

entity e:eex2-n8qt l:"Table 16: Solid Waste Generated Per Person (Pounds)" t:attribution=DOH t:url=https://data.hawaii.gov/api/views/eex2-n8qt

property e:eex2-n8qt t:meta.view v:id=eex2-n8qt v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="Table 16: Solid Waste Generated Per Person (Pounds)" v:attribution=DOH

property e:eex2-n8qt t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:eex2-n8qt t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:eex2-n8qt t:meta.view.tableauthor v:id=8c9u-vteh v:screenName=lorrink v:roleName=editor v:displayName=lorrink
```

## Top Records

```ls
| _ | calendar_year | hawaii | national | 
| = | ============= | ====== | ======== | 
| 1 | 2006          | 9.3    | 4.6      | 
| 2 | 2007          | 9.6    | 4.6      | 
| 4 | 2008          | 9.2    | 4.5      | 
```