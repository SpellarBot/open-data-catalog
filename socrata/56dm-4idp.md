# Table 13: Wastewater Recycled

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-13-wastewater-recycled-8eb2a) |
| Metadata | [Link](https://data.hawaii.gov/api/views/56dm-4idp) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/56dm-4idp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/56dm-4idp/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 56dm-4idp |
| Name | Table 13: Wastewater Recycled |
| Attribution | DOH |
| Category | Health |
| Tags | wastewater, recycled |
| Created | 2012-08-01T00:08:01Z |
| Publication Date | 2012-08-01T00:08:59Z |

## Description

DOH Environmental Indicators

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                            | Data Type | Render Type |
| ======== | ============== | ============================ | =============================== | ========= | =========== |
| No       |                | _                            | #                               | number    | number      |
| Yes      | time           | calendar_year                | Calendar Year                   | number    | text        |
| Yes      | numeric metric | total_wastewater_treated_mgd | Total Wastewater Treated (MGD)* | number    | number      |
| Yes      | numeric metric | wastewater_reused_mgd        | Wastewater reused (MGD)         | number    | number      |
| Yes      | numeric metric | percentage_reused            | Percentage Reused               | percent   | percent     |
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
series e:56dm-4idp d:2006-01-01T00:00:00.000Z m:wastewater_reused_mgd=24.6 m:total_wastewater_treated_mgd=150 m:percentage_reused=16.4

series e:56dm-4idp d:2007-01-01T00:00:00.000Z m:wastewater_reused_mgd=24.4 m:total_wastewater_treated_mgd=150 m:percentage_reused=16.27

series e:56dm-4idp d:2008-01-01T00:00:00.000Z m:wastewater_reused_mgd=23.91 m:total_wastewater_treated_mgd=150 m:percentage_reused=15.94
```

## Meta Commands

```ls
metric m:total_wastewater_treated_mgd p:integer l:"Total Wastewater Treated (MGD)*" t:dataTypeName=number

metric m:wastewater_reused_mgd p:float l:"Wastewater reused (MGD)" t:dataTypeName=number

metric m:percentage_reused p:float l:"Percentage Reused" t:dataTypeName=percent

entity e:56dm-4idp l:"Table 13: Wastewater Recycled" t:attribution=DOH t:url=https://data.hawaii.gov/api/views/56dm-4idp

property e:56dm-4idp t:meta.view v:id=56dm-4idp v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="Table 13: Wastewater Recycled" v:attribution=DOH

property e:56dm-4idp t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:56dm-4idp t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:56dm-4idp t:meta.view.tableauthor v:id=8c9u-vteh v:screenName=lorrink v:roleName=editor v:displayName=lorrink
```

## Top Records

```ls
| _ | calendar_year | total_wastewater_treated_mgd | wastewater_reused_mgd | percentage_reused | 
| = | ============= | ============================ | ===================== | ================= | 
| 1 | 2006          | 150                          | 24.60                 | 16.40             | 
| 2 | 2007          | 150                          | 24.40                 | 16.27             | 
| 4 | 2008          | 150                          | 23.91                 | 15.94             | 
| 5 | 2009          | 150                          | 23.91                 | 15.94             | 
| 6 | 2010          | 145                          | 22.98                 | 15.85             | 
```