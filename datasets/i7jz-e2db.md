# Summary Table Of Funding Sources

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/summary-table-of-funding-sources-fcd54) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/i7jz-e2db) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/i7jz-e2db/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/i7jz-e2db/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | i7jz-e2db |
| Name | Summary Table Of Funding Sources |
| Attribution | Department of City Planning (DCP) |
| Category | Housing & Development |
| Tags | dcp, city, planning, funding, source, housing |
| Created | 2013-02-20T14:49:34Z |
| Publication Date | 2013-06-21T20:45:48Z |

## Description

Details of Funding Sources for Housing Projects

## Columns

```ls
| Included | Schema Type    | Field Name                                           | Name                                                 | Data Type | Render Type |
| ======== | ============== | ==================================================== | ==================================================== | ========= | =========== |
| Yes      | time           | year                                                 | Year                                                 | number    | text        |
| Yes      | series tag     | project_code                                         | Project Code                                         | text      | text        |
| Yes      | series tag     | program_type                                         | Program Type                                         | text      | text        |
| Yes      | series tag     | program_name                                         | Program Name                                         | text      | text        |
| Yes      | numeric metric | amount                                               | Amount                                               | money     | money       |
| Yes      | numeric metric | amount_city_expects_to_receive                       | Amount City Expects to Receive                       | money     | money       |
| Yes      | numeric metric | amount_city_expects_to_be_received_by_other_entities | Amount City Expects to be Received by Other Entities | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:i7jz-e2db d:2012-01-01T00:00:00.000Z t:program_type="HUD Formula/Entitlement Program" t:program_name="Community Development Block Grant (CDBG)" t:project_code=C-OMB-0000 m:amount_city_expects_to_receive=231486000

series e:i7jz-e2db d:2012-01-01T00:00:00.000Z t:program_type="HUD Formula/Entitlement Program" t:program_name="7A Program" t:project_code=C-HPD-0085 m:amount=1377000

series e:i7jz-e2db d:2012-01-01T00:00:00.000Z t:program_type="HUD Formula/Entitlement Program" t:program_name="Adult Literacy Program" t:project_code=C-VARIOUS-0204 m:amount=2043000
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=money

metric m:amount_city_expects_to_receive p:integer l:"Amount City Expects to Receive" t:dataTypeName=money

metric m:amount_city_expects_to_be_received_by_other_entities p:integer l:"Amount City Expects to be Received by Other Entities" t:dataTypeName=money

entity e:i7jz-e2db l:"Summary Table Of Funding Sources" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/i7jz-e2db

property e:i7jz-e2db t:meta.view v:id=i7jz-e2db v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/dcp/pdf/pub/conplan12_amended_vol1.pdf v:averageRating=0 v:name="Summary Table Of Funding Sources" v:attribution="Department of City Planning (DCP)"

property e:i7jz-e2db t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:i7jz-e2db t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| year | project_code   | program_type                    | program_name                                       | amount  | amount_city_expects_to_receive | amount_city_expects_to_be_received_by_other_entities | 
| ==== | ============== | =============================== | ================================================== | ======= | ============================== | ==================================================== | 
| 2012 | C-OMB-0000     | HUD Formula/Entitlement Program | Community Development Block Grant (CDBG)           |         | 231486000                      |                                                      | 
| 2012 | C-HPD-0085     | HUD Formula/Entitlement Program | 7A Program                                         | 1377000 |                                |                                                      | 
| 2012 | C-VARIOUS-0204 | HUD Formula/Entitlement Program | Adult Literacy Program                             | 2043000 |                                |                                                      | 
| 2012 | C-HPD-0206     | HUD Formula/Entitlement Program | Alternative Enforcement Program                    | 8236000 |                                |                                                      | 
| 2012 | C-SBS-0026     | HUD Formula/Entitlement Program | Avenue NYC                                         | 2035000 |                                |                                                      | 
| 2012 | C-DYCD-0142    | HUD Formula/Entitlement Program | Beacon School Program                              | 5949000 |                                |                                                      | 
| 2012 | C-DPR-0055     | HUD Formula/Entitlement Program | Bronx River Project                                | 198000  |                                |                                                      | 
| 2012 | C-VARIOUS-0063 | HUD Formula/Entitlement Program | CDBG Administration                                | 2326000 |                                |                                                      | 
| 2012 | C-DOEd-0165    | HUD Formula/Entitlement Program | Code Violation Removal in Schools                  | 4750000 |                                |                                                      | 
| 2012 | C-CHR-0040     | HUD Formula/Entitlement Program | Commission on Human Rights Law Enforcement Program | 1665000 |                                |                                                      | 
```