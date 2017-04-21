# ARRA Grant Revenues As Of COB June 30, 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arra-grant-revenues-as-of-cob-june-30-2014-6bfe5) |
| Metadata | [Link](https://data.mo.gov/api/views/ixe6-e4z3) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/ixe6-e4z3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/ixe6-e4z3/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | ixe6-e4z3 |
| Name | ARRA Grant Revenues As Of COB June 30, 2014 |
| Category | Government Administration |
| Created | 2014-07-02T18:39:03Z |
| Publication Date | 2014-07-02T18:39:56Z |

## Description

Data that shows every dollar received by the State of Missouri to date under the American Reinvestment and Recovery Act of 2009 including the receiving state agency and the federal funding source or program.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | agency_name     | Agency Name     | text      | text        |
| Yes      | series tag     | program_name    | Program Name    | text      | text        |
| Yes      | numeric metric | amount_received | Amount Received | money     | money       |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ixe6-e4z3 d:2014-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE m:amount_received=111849.21

series e:ixe6-e4z3 d:2014-01-01T00:00:00.000Z t:program_name="ENERGY EFFIC/RENEW ENERGY - CONS BLO" t:agency_name=AGRICULTURE m:amount_received=4995648.88

series e:ixe6-e4z3 d:2014-01-01T00:00:00.000Z t:program_name="FISH AND WILDLIFE SERVICE" t:agency_name=CONSERVATION m:amount_received=144900
```

## Meta Commands

```ls
metric m:amount_received p:double l:"Amount Received" t:dataTypeName=money

entity e:ixe6-e4z3 l:"ARRA Grant Revenues As Of COB June 30, 2014" t:url=https://data.mo.gov/api/views/ixe6-e4z3

property e:ixe6-e4z3 t:meta.view v:id=ixe6-e4z3 v:category="Government Administration" v:averageRating=0 v:name="ARRA Grant Revenues As Of COB June 30, 2014"

property e:ixe6-e4z3 t:meta.view.owner v:id=4cdh-4my4 v:screenName=Dwight v:displayName=Dwight

property e:ixe6-e4z3 t:meta.view.tableauthor v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```

## Top Records

```ls
| agency_name          | program_name                             | amount_received | 
| ==================== | ======================================== | =============== | 
| AGRICULTURE          | AQUACULTURE ASSISTANCE PROGRAM           | 111849.21       | 
| AGRICULTURE          | ENERGY EFFIC/RENEW ENERGY - CONS BLO     | 4995648.88      | 
| CONSERVATION         | FISH AND WILDLIFE SERVICE                | 144900.00       | 
| CONSERVATION         | WILDLAND FIRE MANAGEMENT                 | 6000000.00      | 
| ECONOMIC DEVELOPMENT | AMERICORPS                               | 823449.04       | 
| ECONOMIC DEVELOPMENT | COMMUNITY DEVELOPMENT BLOCK GRANT        | 6433629.00      | 
| ECONOMIC DEVELOPMENT | EMPLOYMENT SRVS WAGNER-PEYSER            | 7400054.18      | 
| ECONOMIC DEVELOPMENT | NATIONAL EMERG WIA GRANT                 | 3270587.36      | 
| ECONOMIC DEVELOPMENT | NATIONAL ENDOWMENT OF THE ARTS           | 320200.00       | 
| ECONOMIC DEVELOPMENT | STATE ENERGY REGULATORS ASSISTANCE GRANT | 60196.11        | 
```