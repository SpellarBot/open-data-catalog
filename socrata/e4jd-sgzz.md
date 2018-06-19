# ARRA Grant Revenues as of COB June 30, 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arra-grant-revenues-as-of-cob-june-30-2012-afe5b) |
| Metadata | [Link](https://data.mo.gov/api/views/e4jd-sgzz) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/e4jd-sgzz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/e4jd-sgzz/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | e4jd-sgzz |
| Name | ARRA Grant Revenues as of COB June 30, 2012 |
| Category | Government |
| Created | 2012-07-02T19:46:25Z |
| Publication Date | 2012-07-02T19:49:53Z |

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
series e:e4jd-sgzz d:2012-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE m:amount_received=111849.21

series e:e4jd-sgzz d:2012-01-01T00:00:00.000Z t:program_name="ENERGY EFFIC/RENEW ENERGY - CONS BLO" t:agency_name=AGRICULTURE m:amount_received=2941408.08

series e:e4jd-sgzz d:2012-01-01T00:00:00.000Z t:program_name="FISH AND WILDLIFE SERVICE" t:agency_name=CONSERVATION m:amount_received=144900
```

## Meta Commands

```ls
metric m:amount_received p:double l:"Amount Received" t:dataTypeName=money

entity e:e4jd-sgzz l:"ARRA Grant Revenues as of COB June 30, 2012" t:url=https://data.mo.gov/api/views/e4jd-sgzz

property e:e4jd-sgzz t:meta.view v:id=e4jd-sgzz v:category=Government v:averageRating=0 v:name="ARRA Grant Revenues as of COB June 30, 2012"

property e:e4jd-sgzz t:meta.view.owner v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:displayName="Carolyn Aggeler"

property e:e4jd-sgzz t:meta.view.tableauthor v:id=29n3-s86h v:screenName="Carolyn Aggeler" v:roleName=editor v:displayName="Carolyn Aggeler"
```

## Top Records

```ls
| agency_name          | program_name                         | amount_received | 
| ==================== | ==================================== | =============== | 
| AGRICULTURE          | AQUACULTURE ASSISTANCE PROGRAM       | 111849.21       | 
| AGRICULTURE          | ENERGY EFFIC/RENEW ENERGY - CONS BLO | 2941408.08      | 
| CONSERVATION         | FISH AND WILDLIFE SERVICE            | 144900          | 
| CONSERVATION         | WILDLAND FIRE MANAGEMENT             | 6000000         | 
| ECONOMIC DEVELOPMENT | AMERICORPS                           | 823449.04       | 
| ECONOMIC DEVELOPMENT | COMMUNITY DEVELOPMENT BLOCK GRANT    | 5573005.36      | 
| ECONOMIC DEVELOPMENT | EMPLOYMENT SRVS WAGNER-PEYSER        | 7400054.18      | 
| ECONOMIC DEVELOPMENT | NATIONAL EMERG WIA GRANT             | 3035299.91      | 
| ECONOMIC DEVELOPMENT | NATIONAL ENDOWMENT OF THE ARTS       | 320200          | 
| ECONOMIC DEVELOPMENT | TANF SUMMER YOUTH                    | 14675070.86     | 
```