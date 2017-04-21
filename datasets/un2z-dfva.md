# Scheduled vs Unscheduled Maintenance

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/scheduled-vs-unscheduled-maintenance) |
| Metadata | [Link](https://data.austintexas.gov/api/views/un2z-dfva) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/un2z-dfva/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/un2z-dfva/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | un2z-dfva |
| Name | Scheduled vs Unscheduled Maintenance |
| Attribution | City of Austin - Building Services Department |
| Category | Business |
| Tags | building services, bsd |
| Created | 2015-08-03T19:23:19Z |
| Publication Date | 2015-08-04T18:59:20Z |

## Description

Ratio of Scheduled vs Unscheduled Maintenance by Labor Hours (completed work orders) on the Building Services Department's core properties for FY2015 (Q1, Q2, and Q3).

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                               | Data Type | Render Type |
| ======== | ============== | ============================ | ================================== | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                         | meta_data | meta_data   |
| Yes      | series tag     | fy15_q1_q2_q3_core_buildings | FY15 - Q1, Q2, Q3 | Core Buildings | text      | text        |
| Yes      | numeric metric | scheduled                    | Scheduled                          | number    | number      |
| Yes      | numeric metric | unscheduled                  | Unscheduled                        | number    | number      |
| Yes      | numeric metric | total                        | Total                              | number    | number      |
| Yes      | numeric metric | ratio                        | Ratio                              | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:un2z-dfva d:2015-08-03T12:23:24.000Z t:fy15_q1_q2_q3_core_buildings="Building Services Headquarters (411 Chicon St)" m:total=257 m:scheduled=64.5 m:ratio=25.1 m:unscheduled=192.5

series e:un2z-dfva d:2015-08-03T12:23:24.000Z t:fy15_q1_q2_q3_core_buildings="City Hall (301 W 2nd St)" m:total=1799.05 m:scheduled=513.5 m:ratio=28.5 m:unscheduled=1285.55

series e:un2z-dfva d:2015-08-03T12:23:24.000Z t:fy15_q1_q2_q3_core_buildings="Municipal Building (124 W 8th St)" m:total=645.75 m:scheduled=305 m:ratio=47.2 m:unscheduled=340.75
```

## Meta Commands

```ls
metric m:scheduled p:float l:Scheduled t:dataTypeName=number

metric m:unscheduled p:float l:Unscheduled t:dataTypeName=number

metric m:total p:float l:Total t:dataTypeName=number

metric m:ratio p:float l:Ratio t:dataTypeName=percent

entity e:un2z-dfva l:"Scheduled vs Unscheduled Maintenance" t:attribution="City of Austin - Building Services Department" t:url=https://data.austintexas.gov/api/views/un2z-dfva

property e:un2z-dfva t:meta.view v:id=un2z-dfva v:category=Business v:averageRating=0 v:name="Scheduled vs Unscheduled Maintenance" v:attribution="City of Austin - Building Services Department"

property e:un2z-dfva t:meta.view.license v:name="Public Domain"

property e:un2z-dfva t:meta.view.owner v:id=vn3d-c3t8 v:screenName="Korrie Melia" v:displayName="Korrie Melia"

property e:un2z-dfva t:meta.view.tableauthor v:id=vn3d-c3t8 v:screenName="Korrie Melia" v:roleName=editor v:displayName="Korrie Melia"
```

## Top Records

```ls
| :updated_at | fy15_q1_q2_q3_core_buildings                      | scheduled | unscheduled        | total              | ratio | 
| =========== | ================================================= | ========= | ================== | ================== | ===== | 
| 1438604604  | Building Services Headquarters (411 Chicon St)    | 64.5      | 192.5              | 257                | 25.1  | 
| 1438604604  | City Hall (301 W 2nd St)                          | 513.5     | 1285.55            | 1799.05            | 28.5  | 
| 1438604604  | Municipal Building (124 W 8th St)                 | 305       | 340.75             | 645.75             | 47.2  | 
| 1438604604  | One Texas Center (505 Barton Springs Rd)          | 25.25     | 491.05             | 516.29999999999995 | 4.9   | 
| 1438604604  | Public Safety Training Campus (4800 Shaw Ln)      | 75        | 596.75             | 671.75             | 11.2  | 
| 1438604604  | Rutherford Lane Campus - RLC (1520 Rutherford Ln) | 432.5     | 1722.5             | 2155               | 20.1  | 
| 1438604604  | Technicenter (4201 Ed Bluestein Blvd)             | 96        | 357.75             | 453.75             | 21.2  | 
| 1438604604  | Total                                             | 1511.75   | 4986.8500000000004 | 6498.6             | 23.3  | 
```