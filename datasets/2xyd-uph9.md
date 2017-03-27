# ARRA Grant Revenues As Of COB November 30, 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arra-grant-revenues-as-of-cob-november-30-2014-1007e) |
| Metadata | [Link](https://data.mo.gov/api/views/2xyd-uph9) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/2xyd-uph9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/2xyd-uph9/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 2xyd-uph9 |
| Name | ARRA Grant Revenues As Of COB November 30, 2014 |
| Category | Government Administration |
| Created | 2014-12-02T18:50:15Z |
| Publication Date | 2014-12-02T18:51:04Z |

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
series e:2xyd-uph9 d:2014-01-01T00:00:00.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE m:amount_received=111849.21

series e:2xyd-uph9 d:2014-01-01T00:00:00.000Z t:program_name="ENERGY EFFIC/RENEW ENERGY - CONS BLO" t:agency_name=AGRICULTURE m:amount_received=5000000

series e:2xyd-uph9 d:2014-01-01T00:00:00.000Z t:program_name="FISH AND WILDLIFE SERVICE" t:agency_name=CONSERVATION m:amount_received=144900
```

## Meta Commands

```ls
metric m:amount_received p:double l:"Amount Received" t:dataTypeName=money

entity e:2xyd-uph9 l:"ARRA Grant Revenues As Of COB November 30, 2014" t:url=https://data.mo.gov/api/views/2xyd-uph9

property e:2xyd-uph9 t:meta.view v:id=2xyd-uph9 v:category="Government Administration" v:averageRating=0 v:name="ARRA Grant Revenues As Of COB November 30, 2014"

property e:2xyd-uph9 t:meta.view.owner v:id=4cdh-4my4 v:screenName=Dwight v:displayName=Dwight

property e:2xyd-uph9 t:meta.view.tableauthor v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```