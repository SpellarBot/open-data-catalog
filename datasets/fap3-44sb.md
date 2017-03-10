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
| Rows Updated | 2016-02-04T16:26:42Z |

## Description

Data that shows every dollar received by the State of Missouri to date under the American Reinvestment and Recovery Act of 2009 including the receiving state agency and the federal funding source or program.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | agency_name     | Agency Name     | text      | text        |
| Yes      | series tag     | program_name    | Program Name    | text      | text        |
| Yes      | numeric metric | amount_received | Amount Received | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fap3-44sb d:2016-02-04T08:26:35.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE m:amount_received=111849.21

series e:fap3-44sb d:2016-02-04T08:26:35.000Z t:program_name="ENERGY EFFIC/RENEW ENERGY - CONS BLO" t:agency_name=AGRICULTURE m:amount_received=5000000

series e:fap3-44sb d:2016-02-04T08:26:35.000Z t:program_name="FISH AND WILDLIFE SERVICE" t:agency_name=CONSERVATION m:amount_received=144900
```

## Meta Commands

```ls
entity e:fap3-44sb l:"ARRA Grant Revenue as of COB January 31, 2016" t:url=https://data.mo.gov/api/views/fap3-44sb

property e:fap3-44sb t:meta.view d:2017-03-10T16:03:15.948Z v:id=fap3-44sb v:category="Government Administration" v:averageRating=0 v:name="ARRA Grant Revenue as of COB January 31, 2016"

property e:fap3-44sb t:meta.view.owner d:2017-03-10T16:03:15.948Z v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight

property e:fap3-44sb t:meta.view.tableauthor d:2017-03-10T16:03:15.948Z v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```