# CIP DataSet for Budget Montgomery

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cip-dataset-for-budget-montgomery) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/ww4d-tnet) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/ww4d-tnet/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/ww4d-tnet/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | ww4d-tnet |
| Name | CIP DataSet for Budget Montgomery |
| Created | 2016-04-21T16:59:37Z |
| Publication Date | 2016-07-25T22:15:40Z |

## Description

CIP DataSet for Budget Montgomery

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | time           | fiscal_year  | fiscal_year  | number    | number      |
| Yes      | series tag     | service      | Service      | text      | text        |
| Yes      | series tag     | category     | Category     | text      | text        |
| Yes      | series tag     | project      | Project      | text      | text        |
| Yes      | series tag     | project_id   | project_id   | text      | text        |
| Yes      | series tag     | fund         | Fund         | text      | text        |
| Yes      | series tag     | fund_type    | fund_type    | text      | text        |
| Yes      | numeric metric | recommended  | Recommended  | number    | number      |
| Yes      | numeric metric | approved_amt | approved_amt | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ww4d-tnet d:2015-01-01T00:00:00.000Z t:fund_type=Local t:project="Burtonsville Community Revitalization (P760900)" t:category="Community Development" t:project_id=P760900 t:service="Community Development and Housing" t:fund="Current Revenue: General" m:approved_amt=460000 m:recommended=460000

series e:ww4d-tnet d:2015-01-01T00:00:00.000Z t:fund_type=Local t:project="Burtonsville Community Revitalization (P760900)" t:category="Community Development" t:project_id=P760900 t:service="Community Development and Housing" t:fund="G.O. Bonds" m:approved_amt=0 m:recommended=0

series e:ww4d-tnet d:2015-01-01T00:00:00.000Z t:fund_type=Local t:project="Burtonsville Community Revitalization (P760900)" t:category="Community Development" t:project_id=P760900 t:service="Community Development and Housing" t:fund=PAYGO m:approved_amt=1210000 m:recommended=1210000
```

## Meta Commands

```ls
metric m:recommended p:integer l:Recommended t:dataTypeName=number

metric m:approved_amt p:integer l:approved_amt t:dataTypeName=number

entity e:ww4d-tnet l:"CIP DataSet for Budget Montgomery" t:url=https://data.montgomerycountymd.gov/api/views/ww4d-tnet

property e:ww4d-tnet t:meta.view v:id=ww4d-tnet v:averageRating=0 v:name="CIP DataSet for Budget Montgomery"

property e:ww4d-tnet t:meta.view.owner v:id=y8as-9hmt v:screenName=Rekha v:displayName=Rekha

property e:ww4d-tnet t:meta.view.tableauthor v:id=y8as-9hmt v:screenName=Rekha v:roleName=editor v:displayName=Rekha
```

## Top Records

```ls
| fiscal_year | service                           | category              | project                                                            | project_id | fund                                       | fund_type | recommended | approved_amt | 
| =========== | ================================= | ===================== | ================================================================== | ========== | ========================================== | ========= | =========== | ============ | 
| 2015        | Community Development and Housing | Community Development | Burtonsville Community Revitalization (P760900)                    | P760900    | Current Revenue: General                   | Local     | 460000      | 460000       | 
| 2015        | Community Development and Housing | Community Development | Burtonsville Community Revitalization (P760900)                    | P760900    | G.O. Bonds                                 | Local     | 0           | 0            | 
| 2015        | Community Development and Housing | Community Development | Burtonsville Community Revitalization (P760900)                    | P760900    | PAYGO                                      | Local     | 1210000     | 1210000      | 
| 2015        | Community Development and Housing | Community Development | Colesville/New Hampshire Avenue Community Revitalization (P761501) | P761501    | Current Revenue: General                   | Local     | 0           | 0            | 
| 2015        | Community Development and Housing | Community Development | Facility Planning: HCD (P769375)                                   | P769375    | Community Development Block Grant          | External  | 334000      | 334000       | 
| 2015        | Community Development and Housing | Community Development | Facility Planning: HCD (P769375)                                   | P769375    | Current Revenue: General                   | Local     | 2031000     | 2031000      | 
| 2015        | Community Development and Housing | Community Development | Facility Planning: HCD (P769375)                                   | P769375    | Current Revenue: Parking - Montgomery Hill | Local     | 100000      | 100000       | 
| 2015        | Community Development and Housing | Community Development | Facility Planning: HCD (P769375)                                   | P769375    | Federal Aid                                | External  | 200000      | 200000       | 
| 2015        | Community Development and Housing | Community Development | Fenton Street Village Pedestrian Linkages (P760500)                | P760500    | Community Development Block Grant          | External  | 1830000     | 1830000      | 
| 2015        | Community Development and Housing | Community Development | Fenton Street Village Pedestrian Linkages (P760500)                | P760500    | Federal Aid                                | External  | 198000      | 198000       | 
```