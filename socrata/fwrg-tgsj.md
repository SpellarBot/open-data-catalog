# OMB Approved and Recommended Capital Funding

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/omb-approved-and-recommended-capital-funding-2b30a) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/fwrg-tgsj) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/fwrg-tgsj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/fwrg-tgsj/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | fwrg-tgsj |
| Name | OMB Approved and Recommended Capital Funding |
| Category | Government |
| Tags | approved, recommended, capital expenditures, funding |
| Created | 2014-07-15T16:37:14Z |
| Publication Date | 2016-07-20T13:26:21Z |

## Description

This dataset includes the County Executive?s Recommended and Approved Capital funding for the recent fiscal years.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | fiscal_year             | Fiscal Year             | number    | number      |
| Yes      | series tag     | service                 | Service                 | text      | text        |
| Yes      | series tag     | category                | Category                | text      | text        |
| Yes      | series tag     | project                 | Project                 | text      | text        |
| Yes      | series tag     | project_id              | Project ID              | text      | text        |
| Yes      | series tag     | fund                    | Fund                    | text      | text        |
| Yes      | series tag     | fund_type               | Fund Type               | text      | text        |
| Yes      | numeric metric | thru_fy_recommended     | Thru FY Recommended     | number    | number      |
| Yes      | numeric metric | thru_fy_actuals         | Thru FY Actuals         | number    | number      |
| Yes      | numeric metric | fy_recommended          | FY Recommended          | number    | number      |
| Yes      | numeric metric | approved_amount         | Approved Amount         | number    | number      |
| Yes      | numeric metric | fy_plus_1_recommended   | FY+1 Recommended        | number    | number      |
| Yes      | numeric metric | fy_plus_1_approved      | FY+1 Approved           | number    | number      |
| Yes      | numeric metric | fy_plus_2_recommended   | FY+2 Recommended        | number    | number      |
| Yes      | numeric metric | fy_plus_2_approved      | FY+2 Approved           | number    | number      |
| Yes      | numeric metric | fy_plus_3_recommended   | FY+3 Recommended        | number    | number      |
| Yes      | numeric metric | fy_plus_3_approved      | FY+3 Approved           | number    | number      |
| Yes      | numeric metric | fy_plus_4_recommended   | FY+4 Recommended        | number    | number      |
| Yes      | numeric metric | fy_plus_4_approved      | FY+4 Approved           | number    | number      |
| Yes      | numeric metric | fy_plus_5_recommended   | FY+5 Recommended        | number    | number      |
| Yes      | numeric metric | fy_plus_5_approved      | FY+5 Approved           | number    | number      |
| Yes      | numeric metric | fy_beyond_5_recommended | Beyond FY+5 Recommended | number    | number      |
| Yes      | numeric metric | fy_beyond_5_approved    | Beyond FY+5 Approved    | number    | number      |
| Yes      | numeric metric | fy_plus_6_recommended   | FY+6 Recommended        | number    | number      |
| Yes      | numeric metric | fy_plus_6_approved      | FY+6 Approved           | number    | number      |
| Yes      | numeric metric | fy_approved             | fy_approved             | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fwrg-tgsj d:2015-01-01T00:00:00.000Z t:project="Ag Land Pres Easements (P788911)" t:fund_type=External t:category="Ag Land Preservation" t:project_id=P788911 t:service="Conservation of Natural Resources" t:fund="Federal Aid" m:fy_plus_5_approved=0 m:approved_amount=0 m:fy_plus_6_approved=0 m:fy_plus_3_approved=0 m:fy_beyond_5_approved=0 m:fy_plus_2_approved=0 m:fy_beyond_5_recommended=0 m:fy_approved=0 m:fy_plus_1_approved=0 m:fy_plus_6_recommended=0 m:fy_plus_5_recommended=0 m:fy_plus_1_recommended=0 m:fy_plus_4_approved=0 m:thru_fy_actuals=522000 m:fy_plus_3_recommended=0 m:fy_plus_4_recommended=0 m:fy_plus_2_recommended=0 m:thru_fy_recommended=522000 m:fy_recommended=0

series e:fwrg-tgsj d:2015-01-01T00:00:00.000Z t:project="Mid-County Community Recreation Center (P720103)" t:fund_type=Local t:category=Recreation t:project_id=P720103 t:service="Culture and Recreation" t:fund=PAYGO m:fy_plus_5_approved=0 m:approved_amount=0 m:fy_plus_6_approved=0 m:fy_plus_3_approved=0 m:fy_beyond_5_approved=0 m:fy_plus_2_approved=0 m:fy_beyond_5_recommended=0 m:fy_approved=0 m:fy_plus_1_approved=0 m:fy_plus_6_recommended=0 m:fy_plus_5_recommended=0 m:fy_plus_1_recommended=0 m:fy_plus_4_approved=0 m:thru_fy_actuals=325000 m:fy_plus_3_recommended=0 m:fy_plus_4_recommended=0 m:fy_plus_2_recommended=0 m:thru_fy_recommended=325000 m:fy_recommended=0

series e:fwrg-tgsj d:2015-01-01T00:00:00.000Z t:project="Mid-County Community Recreation Center (P720103)" t:fund_type=Local t:category=Recreation t:project_id=P720103 t:service="Culture and Recreation" t:fund="G.O. Bonds" m:fy_plus_5_approved=0 m:approved_amount=280000 m:fy_plus_6_approved=0 m:fy_plus_3_approved=0 m:fy_beyond_5_approved=0 m:fy_plus_2_approved=0 m:fy_beyond_5_recommended=0 m:fy_approved=280000 m:fy_plus_1_approved=0 m:fy_plus_6_recommended=0 m:fy_plus_5_recommended=0 m:fy_plus_1_recommended=0 m:fy_plus_4_approved=0 m:thru_fy_actuals=11145000 m:fy_plus_3_recommended=0 m:fy_plus_4_recommended=0 m:fy_plus_2_recommended=0 m:thru_fy_recommended=11145000 m:fy_recommended=280000
```

## Meta Commands

```ls
metric m:thru_fy_recommended p:integer l:"Thru FY Recommended" d:"The summed recommended allocation on this project from inception up to the budget fiscal year specified in the ?Fiscal Year? field" t:dataTypeName=number

metric m:thru_fy_actuals p:integer l:"Thru FY Actuals" d:"The actuals on this project from inception up to the budget fiscal year specified in the ?Fiscal Year? field" t:dataTypeName=number

metric m:fy_recommended p:integer l:"FY Recommended" d:"The amount recommended for this project for the FY15 budget year" t:dataTypeName=number

metric m:approved_amount p:integer l:"Approved Amount" d:"The amount approved for this project for the budget year" t:dataTypeName=number

metric m:fy_plus_1_recommended p:integer l:"FY+1 Recommended" d:"The amount recommended for this project for the FY16 budget year" t:dataTypeName=number

metric m:fy_plus_1_approved p:integer l:"FY+1 Approved" d:"The amount approved for this project for the FY16 budget year" t:dataTypeName=number

metric m:fy_plus_2_recommended p:integer l:"FY+2 Recommended" d:"The amount recommended for this project for the FY17budget year" t:dataTypeName=number

metric m:fy_plus_2_approved p:integer l:"FY+2 Approved" d:"The amount approved for this project for the FY17budget year" t:dataTypeName=number

metric m:fy_plus_3_recommended p:integer l:"FY+3 Recommended" d:"The amount recommended for this project for the FY18 budget year" t:dataTypeName=number

metric m:fy_plus_3_approved p:integer l:"FY+3 Approved" d:"The amount approved for this project for the FY18 budget year" t:dataTypeName=number

metric m:fy_plus_4_recommended p:integer l:"FY+4 Recommended" d:"The amount recommended for this project for the FY19 budget year" t:dataTypeName=number

metric m:fy_plus_4_approved p:integer l:"FY+4 Approved" d:"The amount approved for this project for the FY19 budget year" t:dataTypeName=number

metric m:fy_plus_5_recommended p:integer l:"FY+5 Recommended" d:"The amount recommended for this project for the FY20 budget year" t:dataTypeName=number

metric m:fy_plus_5_approved p:integer l:"FY+5 Approved" d:"The amount approved for this project for the FY20 budget year" t:dataTypeName=number

metric m:fy_beyond_5_recommended p:integer l:"Beyond FY+5 Recommended" d:"The amount recommended for this project for the FY21 budget year and beyond" t:dataTypeName=number

metric m:fy_beyond_5_approved p:integer l:"Beyond FY+5 Approved" d:"The amount approved for this project for the FY21 budget year and beyond" t:dataTypeName=number

metric m:fy_plus_6_recommended p:integer l:"FY+6 Recommended" t:dataTypeName=number

metric m:fy_plus_6_approved p:integer l:"FY+6 Approved" t:dataTypeName=number

metric m:fy_approved p:integer l:fy_approved t:dataTypeName=number

entity e:fwrg-tgsj l:"OMB Approved and Recommended Capital Funding" t:url=https://data.montgomerycountymd.gov/api/views/fwrg-tgsj

property e:fwrg-tgsj t:meta.view v:id=fwrg-tgsj v:category=Government v:averageRating=0 v:name="OMB Approved and Recommended Capital Funding"

property e:fwrg-tgsj t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:fwrg-tgsj t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| fiscal_year | service                           | category             | project                                                   | project_id | fund                     | fund_type | thru_fy_recommended | thru_fy_actuals | fy_recommended | approved_amount | fy_plus_1_recommended | fy_plus_1_approved | fy_plus_2_recommended | fy_plus_2_approved | fy_plus_3_recommended | fy_plus_3_approved | fy_plus_4_recommended | fy_plus_4_approved | fy_plus_5_recommended | fy_plus_5_approved | fy_beyond_5_recommended | fy_beyond_5_approved | fy_plus_6_recommended | fy_plus_6_approved | fy_approved | 
| =========== | ================================= | ==================== | ========================================================= | ========== | ======================== | ========= | =================== | =============== | ============== | =============== | ===================== | ================== | ===================== | ================== | ===================== | ================== | ===================== | ================== | ===================== | ================== | ======================= | ==================== | ===================== | ================== | =========== | 
| 2015        | Conservation of Natural Resources | Ag Land Preservation | Ag Land Pres Easements (P788911)                          | P788911    | Federal Aid              | External  | 522000              | 522000          | 0              | 0               | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                       | 0                    | 0                     | 0                  | 0           | 
| 2015        | Culture and Recreation            | Recreation           | Mid-County Community Recreation Center (P720103)          | P720103    | PAYGO                    | Local     | 325000              | 325000          | 0              | 0               | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                       | 0                    | 0                     | 0                  | 0           | 
| 2015        | Culture and Recreation            | Recreation           | Mid-County Community Recreation Center (P720103)          | P720103    | G.O. Bonds               | Local     | 11145000            | 11145000        | 280000         | 280000          | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                       | 0                    | 0                     | 0                  | 280000      | 
| 2015        | General Government                | Economic Development | Silver Spring Civic Building (P159921)                    | P159921    | G.O. Bonds               | Local     | 0                   | 0               | 119000         | 119000          | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                       | 0                    | 0                     | 0                  | 119000      | 
| 2015        | M-NCPPC                           | Development          | Broadacres Local Park Renovation (P058702)                | P058702    | Land Sale                | Local     | 561000              | 561000          | 0              | 0               | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                       | 0                    | 0                     | 0                  | 0           | 
| 2015        | M-NCPPC                           | Development          | Broadacres Local Park Renovation (P058702)                | P058702    | Park and Planning Bonds  | Local     | 382000              | 382000          | 20000          | 20000           | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                       | 0                    | 0                     | 0                  | 20000       | 
| 2015        | M-NCPPC                           | Development          | Rock Creek Sewer System Improvements (P098701)            | P098701    | G.O. Bonds               | Local     | 1319000             | 1319000         | 139000         | 139000          | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                       | 0                    | 0                     | 0                  | 139000      | 
| 2015        | M-NCPPC                           | Development          | M-NCPPC Headquarters Project (P138707)                    | P138707    | Current Revenue: General | Local     | 50000               | 50000           | 50000          | 50000           | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                       | 0                    | 0                     | 0                  | 50000       | 
| 2015        | M-NCPPC                           | Development          | S. Germantown Recreational Park: Non Soccer Fac (P998729) | P998729    | Current Revenue: General | Local     | 633000              | 633000          | 0              | 0               | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                       | 0                    | 0                     | 0                  | 0           | 
| 2015        | M-NCPPC                           | Development          | S. Germantown Recreational Park: Non Soccer Fac (P998729) | P998729    | PAYGO                    | Local     | 5863000             | 5863000         | 0              | 0               | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                     | 0                  | 0                       | 0                    | 0                     | 0                  | 0           | 
```