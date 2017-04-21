# Total Work Orders Requested and Completed by Trade

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-work-orders-requested-and-completed-by-trade) |
| Metadata | [Link](https://data.austintexas.gov/api/views/btjx-7fri) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/btjx-7fri/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/btjx-7fri/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | btjx-7fri |
| Name | Total Work Orders Requested and Completed by Trade |
| Attribution | City of Austin - Building Services Department |
| Category | Business |
| Tags | building services, bsd, work orders, trade |
| Created | 2015-08-03T20:54:24Z |
| Publication Date | 2015-08-04T18:59:58Z |

## Description

Work orders managed by the Building Services Department. Includes work orders requested as well as work orders completed segmented by trade for FY2015 (Q1, Q2, and Q3).

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | trade_craft   | Trade/Craft   | text      | text        |
| Yes      | numeric metric | requested_wos | Requested WOs | number    | number      |
| Yes      | numeric metric | completed_wos | Completed WOs | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:btjx-7fri d:2015-08-03T13:55:02.000Z t:trade_craft=Carpentry m:requested_wos=125 m:completed_wos=113

series e:btjx-7fri d:2015-08-03T13:55:02.000Z t:trade_craft="Contract Administration" m:requested_wos=535 m:completed_wos=372

series e:btjx-7fri d:2015-08-03T13:55:02.000Z t:trade_craft=Electrical m:requested_wos=979 m:completed_wos=916
```

## Meta Commands

```ls
metric m:requested_wos p:integer l:"Requested WOs" t:dataTypeName=number

metric m:completed_wos p:integer l:"Completed WOs" t:dataTypeName=number

entity e:btjx-7fri l:"Total Work Orders Requested and Completed by Trade" t:attribution="City of Austin - Building Services Department" t:url=https://data.austintexas.gov/api/views/btjx-7fri

property e:btjx-7fri t:meta.view v:id=btjx-7fri v:category=Business v:averageRating=0 v:name="Total Work Orders Requested and Completed by Trade" v:attribution="City of Austin - Building Services Department"

property e:btjx-7fri t:meta.view.license v:name="Public Domain"

property e:btjx-7fri t:meta.view.owner v:id=vn3d-c3t8 v:screenName="Korrie Melia" v:displayName="Korrie Melia"

property e:btjx-7fri t:meta.view.tableauthor v:id=vn3d-c3t8 v:screenName="Korrie Melia" v:roleName=editor v:displayName="Korrie Melia"
```

## Top Records

```ls
| :updated_at | trade_craft                           | requested_wos | completed_wos | 
| =========== | ===================================== | ============= | ============= | 
| 1438610102  | Carpentry                             | 125           | 113           | 
| 1438610102  | Contract Administration               | 535           | 372           | 
| 1438610102  | Electrical                            | 979           | 916           | 
| 1438610102  | Elevators                             | 199           | 202           | 
| 1438610102  | Fire Alarm System                     | 110           | 74            | 
| 1438610102  | General Maintenance                   | 2428          | 2025          | 
| 1438610102  | Generators                            | 95            | 82            | 
| 1438610102  | Graffiti                              | 56            | 61            | 
| 1438610102  | Health/Safety                         | 31            | 34            | 
| 1438610102  | Heating/Ventilation /Air Conditioning | 2593          | 1753          | 
```