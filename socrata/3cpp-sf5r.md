# ARRA Grant Revenues as of COB May 31, 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arra-grant-revenues-as-of-cob-may-31-2012-382aa) |
| Metadata | [Link](https://data.mo.gov/api/views/3cpp-sf5r) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/3cpp-sf5r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/3cpp-sf5r/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 3cpp-sf5r |
| Name | ARRA Grant Revenues as of COB May 31, 2012 |
| Category | Government |
| Created | 2012-06-01T18:06:11Z |
| Publication Date | 2012-06-01T18:08:48Z |

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
series e:3cpp-sf5r d:2012-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE m:amount_received=111849.21

series e:3cpp-sf5r d:2012-01-01T00:00:00.000Z t:program_name="ENERGY EFFIC/RENEW ENERGY - CONS BLO" t:agency_name=AGRICULTURE m:amount_received=2664597.53

series e:3cpp-sf5r d:2012-01-01T00:00:00.000Z t:program_name="FISH AND WILDLIFE SERVICE" t:agency_name=CONSERVATION m:amount_received=144900
```

## Meta Commands

```ls
metric m:amount_received p:double l:"Amount Received" t:dataTypeName=money

entity e:3cpp-sf5r l:"ARRA Grant Revenues as of COB May 31, 2012" t:url=https://data.mo.gov/api/views/3cpp-sf5r

property e:3cpp-sf5r t:meta.view v:id=3cpp-sf5r v:category=Government v:averageRating=0 v:name="ARRA Grant Revenues as of COB May 31, 2012"

property e:3cpp-sf5r t:meta.view.owner v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:displayName="Carolyn Aggeler"

property e:3cpp-sf5r t:meta.view.tableauthor v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:roleName=editor v:displayName="Carolyn Aggeler"
```

## Top Records

```ls
| agency_name          | program_name                         | amount_received | 
| ==================== | ==================================== | =============== | 
| AGRICULTURE          | AQUACULTURE ASSISTANCE PROGRAM       | 111849.21       | 
| AGRICULTURE          | ENERGY EFFIC/RENEW ENERGY - CONS BLO | 2664597.53      | 
| CONSERVATION         | FISH AND WILDLIFE SERVICE            | 144900.00       | 
| CONSERVATION         | WILDLAND FIRE MANAGEMENT             | 6000000.00      | 
| ECONOMIC DEVELOPMENT | AMERICORPS                           | 823449.04       | 
| ECONOMIC DEVELOPMENT | COMMUNITY DEVELOPMENT BLOCK GRANT    | 5019087.47      | 
| ECONOMIC DEVELOPMENT | EMPLOYMENT SRVS WAGNER-PEYSER        | 7400054.18      | 
| ECONOMIC DEVELOPMENT | NATIONAL EMERG WIA GRANT             | 3029920.89      | 
| ECONOMIC DEVELOPMENT | NATIONAL ENDOWMENT OF THE ARTS       | 320200.00       | 
| ECONOMIC DEVELOPMENT | TANF SUMMER YOUTH                    | 14675070.86     | 
```