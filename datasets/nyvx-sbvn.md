# ARRA Grant Revenue as of COB June 30, 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arra-grant-revenue-as-of-cob-june-30-2015) |
| Metadata | [Link](https://data.mo.gov/api/views/nyvx-sbvn) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/nyvx-sbvn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/nyvx-sbvn/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | nyvx-sbvn |
| Name | ARRA Grant Revenue as of COB June 30, 2015 |
| Category | Government Administration |
| Created | 2015-07-02T14:58:56Z |
| Publication Date | 2015-07-02T14:59:49Z |

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
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nyvx-sbvn d:2015-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE m:amount_received=111849.21

series e:nyvx-sbvn d:2015-01-01T00:00:00.000Z t:program_name="ENERGY EFFIC/RENEW ENERGY - CONS BLO" t:agency_name=AGRICULTURE m:amount_received=5000000

series e:nyvx-sbvn d:2015-01-01T00:00:00.000Z t:program_name="FISH AND WILDLIFE SERVICE" t:agency_name=CONSERVATION m:amount_received=144900
```

## Meta Commands

```ls
metric m:amount_received p:double l:"Amount Received" t:dataTypeName=money

entity e:nyvx-sbvn l:"ARRA Grant Revenue as of COB June 30, 2015" t:url=https://data.mo.gov/api/views/nyvx-sbvn

property e:nyvx-sbvn t:meta.view v:id=nyvx-sbvn v:category="Government Administration" v:averageRating=0 v:name="ARRA Grant Revenue as of COB June 30, 2015"

property e:nyvx-sbvn t:meta.view.license v:name="Public Domain"

property e:nyvx-sbvn t:meta.view.owner v:id=4cdh-4my4 v:screenName=Dwight v:displayName=Dwight

property e:nyvx-sbvn t:meta.view.tableauthor v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```

## Top Records

```ls
| agency_name          | program_name                             | amount_received | 
| ==================== | ======================================== | =============== | 
| AGRICULTURE          | AQUACULTURE ASSISTANCE PROGRAM           | 111849.21       | 
| AGRICULTURE          | ENERGY EFFIC/RENEW ENERGY - CONS BLO     | 5000000.00      | 
| CONSERVATION         | FISH AND WILDLIFE SERVICE                | 144900.00       | 
| CONSERVATION         | WILDLAND FIRE MANAGEMENT                 | 6000000.00      | 
| ECONOMIC DEVELOPMENT | AMERICORPS                               | 823449.04       | 
| ECONOMIC DEVELOPMENT | COMMUNITY DEVELOPMENT BLOCK GRANT        | 6433629.00      | 
| ECONOMIC DEVELOPMENT | EMPLOYMENT SRVS WAGNER-PEYSER            | 7400054.18      | 
| ECONOMIC DEVELOPMENT | NATIONAL EMERG WIA GRANT                 | 3270587.36      | 
| ECONOMIC DEVELOPMENT | NATIONAL ENDOWMENT OF THE ARTS           | 320200.00       | 
| ECONOMIC DEVELOPMENT | STATE ENERGY REGULATORS ASSISTANCE GRANT | 125520.67       | 
```