# Hawaii Capital Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaii-capital-budget) |
| Metadata | [Link](https://data.hawaii.gov/api/views/8t8p-2mku) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/8t8p-2mku/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/8t8p-2mku/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 8t8p-2mku |
| Name | Hawaii Capital Budget |
| Created | 2015-04-14T19:53:45Z |
| Publication Date | 2016-02-04T00:05:04Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | time           | fiscal_year          | Fiscal Year          | number    | number      |
| Yes      | series tag     | service              | Service              | text      | text        |
| Yes      | series tag     | department           | Department           | text      | text        |
| Yes      | series tag     | project              | Project              | text      | text        |
| Yes      | series tag     | project_id           | Project ID           | text      | text        |
| Yes      | series tag     | fund                 | Fund                 | text      | text        |
| Yes      | series tag     | fund_type            | Fund Type            | text      | text        |
| Yes      | numeric metric | thru_fy_actuals      | Thru FY Actuals      | number    | number      |
| Yes      | numeric metric | fy_approved          | FY Approved          | number    | number      |
| Yes      | numeric metric | fy_plus_1_approved   | FY Plus 1 Approved   | number    | number      |
| Yes      | numeric metric | fy_plus_2_approved   | FY Plus 2 Approved   | number    | number      |
| Yes      | numeric metric | fy_plus_3_approved   | FY Plus 3 Approved   | number    | number      |
| Yes      | numeric metric | fy_plus_4_approved   | FY Plus 4 Approved   | number    | number      |
| Yes      | numeric metric | fy_plus_5_approved   | FY Plus 5 Approved   | number    | number      |
| Yes      | numeric metric | fy_plus_6_approved   | FY Plus 6 Approved   | number    | number      |
| Yes      | numeric metric | fy_beyond_6_approved | FY Beyond 6 Approved | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8t8p-2mku d:2016-01-01T00:00:00.000Z t:project="MOLOKAI IRRIGATION SYSTEM IMPROVEMENTS, MOLOKAI" t:department="Agricultural Resource Management" t:project_id=200402 t:service="Department of Agriculture" t:fund="General Obligation (G.O.) Bonds" m:thru_fy_actuals=0 m:fy_approved=1200

series e:8t8p-2mku d:2016-01-01T00:00:00.000Z t:project="KOHALA DITCH IRRIGATION SYSTEM IMPROVEMENTS, HAWAII" t:department="Agricultural Resource Management" t:project_id=P16002 t:service="Department of Agriculture" t:fund="General Obligation (G.O.) Bonds" m:thru_fy_actuals=0 m:fy_approved=1500

series e:8t8p-2mku d:2016-01-01T00:00:00.000Z t:project="KAMUELA VACUUM COOLING PLANT, HAWAII" t:department="Agricultural Resource Management" t:project_id=P16003 t:service="Department of Agriculture" t:fund="General Obligation (G.O.) Bonds" m:thru_fy_actuals=0 m:fy_approved=1000
```

## Meta Commands

```ls
metric m:thru_fy_actuals p:integer l:"Thru FY Actuals" t:dataTypeName=number

metric m:fy_approved p:integer l:"FY Approved" t:dataTypeName=number

metric m:fy_plus_1_approved p:long l:"FY Plus 1 Approved" t:dataTypeName=number

metric m:fy_plus_2_approved p:long l:"FY Plus 2 Approved" t:dataTypeName=number

metric m:fy_plus_3_approved p:long l:"FY Plus 3 Approved" t:dataTypeName=number

metric m:fy_plus_4_approved p:long l:"FY Plus 4 Approved" t:dataTypeName=number

metric m:fy_plus_5_approved p:long l:"FY Plus 5 Approved" t:dataTypeName=number

metric m:fy_plus_6_approved p:long l:"FY Plus 6 Approved" t:dataTypeName=number

metric m:fy_beyond_6_approved p:long l:"FY Beyond 6 Approved" t:dataTypeName=number

entity e:8t8p-2mku l:"Hawaii Capital Budget" t:url=https://data.hawaii.gov/api/views/8t8p-2mku

property e:8t8p-2mku t:meta.view v:id=8t8p-2mku v:averageRating=0 v:name="Hawaii Capital Budget"

property e:8t8p-2mku t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:8t8p-2mku t:meta.view.tableauthor v:id=wktp-67q4 v:screenName=karen v:roleName=administrator v:displayName=karen
```

## Top Records

```ls
| fiscal_year | service                                       | department                                      | project                                                                       | project_id | fund                            | fund_type | thru_fy_actuals | fy_approved | fy_plus_1_approved | fy_plus_2_approved | fy_plus_3_approved | fy_plus_4_approved | fy_plus_5_approved | fy_plus_6_approved | fy_beyond_6_approved | 
| =========== | ============================================= | =============================================== | ============================================================================= | ========== | =============================== | ========= | =============== | =========== | ================== | ================== | ================== | ================== | ================== | ================== | ==================== | 
| 2016        | Department of Agriculture                     | Agricultural Resource Management                | MOLOKAI IRRIGATION SYSTEM IMPROVEMENTS, MOLOKAI                               | 200402     | General Obligation (G.O.) Bonds |           | 0               | 1200        |                    |                    |                    |                    |                    |                    |                      | 
| 2016        | Department of Agriculture                     | Agricultural Resource Management                | KOHALA DITCH IRRIGATION SYSTEM IMPROVEMENTS, HAWAII                           | P16002     | General Obligation (G.O.) Bonds |           | 0               | 1500        |                    |                    |                    |                    |                    |                    |                      | 
| 2016        | Department of Agriculture                     | Agricultural Resource Management                | KAMUELA VACUUM COOLING PLANT, HAWAII                                          | P16003     | General Obligation (G.O.) Bonds |           | 0               | 1000        |                    |                    |                    |                    |                    |                    |                      | 
| 2016        | Department of Agriculture                     | Agribusiness Development and Research           | AGRICULTURAL LAND, OAHU                                                       | P16004     | General Obligation (G.O.) Bonds |           | 0               | 10000       |                    |                    |                    |                    |                    |                    |                      | 
| 2016        | Department of Agriculture                     | General Administration for Agriculture          | MISCELLANEOUS HEALTH, SAFETY, CODE, AND OTHER REQUIREMENTS, STATEWIDE         | 981921     | General Obligation (G.O.) Bonds |           | 0               | 1400        |                    |                    |                    |                    |                    |                    |                      | 
| 2017        | Department of Agriculture                     | General Administration for Agriculture          | MISCELLANEOUS HEALTH, SAFETY, CODE, AND OTHER REQUIREMENTS, STATEWIDE         | 981921     | General Obligation (G.O.) Bonds |           | 0               | 500         |                    |                    |                    |                    |                    |                    |                      | 
| 2016        | Department of Accounting and General Services | Public Works - Planning, Design, & Construction | LUMP SUM MAINTENANCE OF EXISTING FACILITIES, PUBLIC WORKS DIVISION, STATEWIDE | E109       | General Obligation (G.O.) Bonds |           | 0               | 12000       |                    |                    |                    |                    |                    |                    |                      | 
| 2017        | Department of Accounting and General Services | Public Works - Planning, Design, & Construction | LUMP SUM MAINTENANCE OF EXISTING FACILITIES, PUBLIC WORKS DIVISION, STATEWIDE | E109       | General Obligation (G.O.) Bonds |           | 0               | 12000       |                    |                    |                    |                    |                    |                    |                      | 
| 2016        | Department of Accounting and General Services | Public Works - Planning, Design, & Construction | HONOLULU ACADEMY OF ARTS, OAHU                                                | P16123     | General Obligation (G.O.) Bonds |           | 0               | 1500        |                    |                    |                    |                    |                    |                    |                      | 
| 2016        | Department of Accounting and General Services | Public Works - Planning, Design, & Construction | DIAMOND HEAD THEATRE, OAHU                                                    | P16124     | General Obligation (G.O.) Bonds |           | 0               | 450         |                    |                    |                    |                    |                    |                    |                      | 
```