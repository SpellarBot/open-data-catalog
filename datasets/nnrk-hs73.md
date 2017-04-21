# ARRA Grant Revenues As Of COB July 31, 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arra-grant-revenues-as-of-cob-july-31-2012-9a4c3) |
| Metadata | [Link](https://data.mo.gov/api/views/nnrk-hs73) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/nnrk-hs73/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/nnrk-hs73/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | nnrk-hs73 |
| Name | ARRA Grant Revenues As Of COB July 31, 2012 |
| Attribution | Office of Administration |
| Category | Government Administration |
| Created | 2012-08-07T17:34:30Z |
| Publication Date | 2012-08-07T17:35:12Z |

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
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nnrk-hs73 d:2012-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE m:amount_received=111849.21

series e:nnrk-hs73 d:2012-01-01T00:00:00.000Z t:program_name="ENERGY EFFIC/RENEW ENERGY - CONS BLO" t:agency_name=AGRICULTURE m:amount_received=3067501.91

series e:nnrk-hs73 d:2012-01-01T00:00:00.000Z t:program_name="FISH AND WILDLIFE SERVICE" t:agency_name=CONSERVATION m:amount_received=144900
```

## Meta Commands

```ls
metric m:amount_received p:double l:"Amount Received" t:dataTypeName=money

entity e:nnrk-hs73 l:"ARRA Grant Revenues As Of COB July 31, 2012" t:attribution="Office of Administration" t:url=https://data.mo.gov/api/views/nnrk-hs73

property e:nnrk-hs73 t:meta.view v:id=nnrk-hs73 v:category="Government Administration" v:averageRating=0 v:name="ARRA Grant Revenues As Of COB July 31, 2012" v:attribution="Office of Administration"

property e:nnrk-hs73 t:meta.view.owner v:id=wzcj-jrcg v:screenName=John v:displayName=John

property e:nnrk-hs73 t:meta.view.tableauthor v:id=wzcj-jrcg v:screenName=John v:roleName=editor v:displayName=John
```

## Top Records

```ls
| agency_name          | program_name                         | amount_received | 
| ==================== | ==================================== | =============== | 
| AGRICULTURE          | AQUACULTURE ASSISTANCE PROGRAM       | 111849.21       | 
| AGRICULTURE          | ENERGY EFFIC/RENEW ENERGY - CONS BLO | 3067501.91      | 
| CONSERVATION         | FISH AND WILDLIFE SERVICE            | 144900          | 
| CONSERVATION         | WILDLAND FIRE MANAGEMENT             | 6000000         | 
| ECONOMIC DEVELOPMENT | AMERICORPS                           | 823449.04       | 
| ECONOMIC DEVELOPMENT | COMMUNITY DEVELOPMENT BLOCK GRANT    | 5724189.08      | 
| ECONOMIC DEVELOPMENT | EMPLOYMENT SRVS WAGNER-PEYSER        | 7400054.17      | 
| ECONOMIC DEVELOPMENT | NATIONAL EMERG WIA GRANT             | 3063550.73      | 
| ECONOMIC DEVELOPMENT | NATIONAL ENDOWMENT OF THE ARTS       | 320200          | 
| ECONOMIC DEVELOPMENT | TANF SUMMER YOUTH                    | 14675070.85     | 
```