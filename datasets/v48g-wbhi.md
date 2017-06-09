# Table 17: Solid Waste Recycled (in tons)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-17-solid-waste-recycled-in-tons-851c9) |
| Metadata | [Link](https://data.hawaii.gov/api/views/v48g-wbhi) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/v48g-wbhi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/v48g-wbhi/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | v48g-wbhi |
| Name | Table 17: Solid Waste Recycled (in tons) |
| Attribution | DOH |
| Category | Health |
| Tags | solid, waste, recycled |
| Created | 2012-08-01T00:21:17Z |
| Publication Date | 2012-08-01T00:22:15Z |

## Description

DOH Environmental Indicators

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       |                | _                  | #                  | number    | number      |
| Yes      | time           | calendar_year      | Calendar Year      | number    | text        |
| Yes      | numeric metric | produced_statewide | Produced Statewide | number    | number      |
| Yes      | numeric metric | disposed_statewide | Disposed Statewide | number    | number      |
| Yes      | numeric metric | diverted_statewide | Diverted Statewide | number    | number      |
| Yes      | numeric metric | percent_diverted   | Percent Diverted   | percent   | percent     |
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
series e:v48g-wbhi d:2004-01-01T00:00:00.000Z m:percent_diverted=32.5 m:disposed_statewide=1427904 m:diverted_statewide=688820 m:produced_statewide=2116724

series e:v48g-wbhi d:2005-01-01T00:00:00.000Z m:percent_diverted=36 m:disposed_statewide=1425752 m:diverted_statewide=801373 m:produced_statewide=2227124

series e:v48g-wbhi d:2006-01-01T00:00:00.000Z m:percent_diverted=31.4 m:disposed_statewide=1733889 m:diverted_statewide=792245 m:produced_statewide=2526134
```

## Meta Commands

```ls
metric m:produced_statewide p:integer l:"Produced Statewide" t:dataTypeName=number

metric m:disposed_statewide p:integer l:"Disposed Statewide" t:dataTypeName=number

metric m:diverted_statewide p:integer l:"Diverted Statewide" t:dataTypeName=number

metric m:percent_diverted p:float l:"Percent Diverted" t:dataTypeName=percent

entity e:v48g-wbhi l:"Table 17: Solid Waste Recycled (in tons)" t:attribution=DOH t:url=https://data.hawaii.gov/api/views/v48g-wbhi

property e:v48g-wbhi t:meta.view d:2017-06-09T13:52:27.132Z v:id=v48g-wbhi v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="Table 17: Solid Waste Recycled (in tons)" v:attribution=DOH

property e:v48g-wbhi t:meta.view.license d:2017-06-09T13:52:27.132Z v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:v48g-wbhi t:meta.view.owner d:2017-06-09T13:52:27.132Z v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:v48g-wbhi t:meta.view.tableauthor d:2017-06-09T13:52:27.132Z v:id=8c9u-vteh v:screenName=lorrink v:roleName=editor v:displayName=lorrink
```

## Top Records

```ls
| _ | calendar_year | produced_statewide | disposed_statewide | diverted_statewide | percent_diverted | 
| = | ============= | ================== | ================== | ================== | ================ | 
| 1 | 2004          | 2116724            | 1427904            | 688820             | 32.5             | 
| 2 | 2005          | 2227124            | 1425752            | 801373             | 36.0             | 
| 3 | 2006          | 2526134            | 1733889            | 792245             | 31.4             | 
| 4 | 2007          | 2617350            | 1778009            | 839341             | 32.1             | 
| 5 | 2008          | 2532370            | 1629397            | 902973             | 35.7             | 
```