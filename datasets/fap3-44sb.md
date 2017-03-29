# ARRA Grant Revenue as of COB January 31, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arra-grant-revenue-as-of-cob-january-31-2016) |
| Metadata | [Link](https://data.mo.gov/api/views/fap3-44sb) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/fap3-44sb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/fap3-44sb/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | fap3-44sb |
| Name | ARRA Grant Revenue as of COB January 31, 2016 |
| Category | Government Administration |
| Created | 2016-02-04T16:26:02Z |
| Publication Date | 2016-02-04T16:27:17Z |

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
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fap3-44sb d:2016-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE m:amount_received=111849.21

series e:fap3-44sb d:2016-01-01T00:00:00.000Z t:program_name="ENERGY EFFIC/RENEW ENERGY - CONS BLO" t:agency_name=AGRICULTURE m:amount_received=5000000

series e:fap3-44sb d:2016-01-01T00:00:00.000Z t:program_name="FISH AND WILDLIFE SERVICE" t:agency_name=CONSERVATION m:amount_received=144900
```

## Meta Commands

```ls
metric m:amount_received p:double l:"Amount Received" t:dataTypeName=money

entity e:fap3-44sb l:"ARRA Grant Revenue as of COB January 31, 2016" t:url=https://data.mo.gov/api/views/fap3-44sb

property e:fap3-44sb t:meta.view v:id=fap3-44sb v:category="Government Administration" v:averageRating=0 v:name="ARRA Grant Revenue as of COB January 31, 2016"

property e:fap3-44sb t:meta.view.owner v:id=4cdh-4my4 v:screenName=Dwight v:displayName=Dwight

property e:fap3-44sb t:meta.view.tableauthor v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
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