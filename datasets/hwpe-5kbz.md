# DJS Performance Metrics - Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percentage-of-youth-diverted-to-alternate-programs-treatments-prior-to-adjudication) |
| Metadata | [Link](https://data.maryland.gov/api/views/hwpe-5kbz) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/hwpe-5kbz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/hwpe-5kbz/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | hwpe-5kbz |
| Name | DJS Performance Metrics - Fiscal Year |
| Attribution | Department of Juvenile Services, Office of Research and Evaluation |
| Category | Public Safety |
| Tags | djs, diversion, gopi, intake, juvenile |
| Created | 2016-06-01T18:37:26Z |
| Publication Date | 2017-01-12T19:43:54Z |

## Description

The percent of cases referred to The Department of Juvenile Services Intake that are diverted to pre-court supervision, as well as the percent of DJS Committed youth successfully released without a new delinquent adjudication or conviction within a year of release.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | time           | date                | Date                | calendar_date | calendar_date |
| Yes      | series tag     | fiscal_year         | Fiscal year         | text          | text          |
| Yes      | numeric metric | complaints_referred | Complaints Referred | number        | number        |
| Yes      | numeric metric | percent_diverted    | Percent Diverted    | percent       | percent       |
| Yes      | numeric metric | released_youth      | Released Youth      | number        | number        |
| Yes      | numeric metric | success_rate        | Success Rate        | percent       | percent       |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:hwpe-5kbz d:2001-06-30T00:00:00.000Z t:fiscal_year=FY2001 m:percent_diverted=56 m:complaints_referred=51271

series e:hwpe-5kbz d:2002-06-30T00:00:00.000Z t:fiscal_year=FY2002 m:percent_diverted=57.3 m:complaints_referred=53197

series e:hwpe-5kbz d:2003-06-30T00:00:00.000Z t:fiscal_year=FY2003 m:percent_diverted=58.3 m:complaints_referred=52662
```

## Meta Commands

```ls
metric m:complaints_referred p:integer l:"Complaints Referred" d:"Count of all complaints referred to DJS Intake, a portion of which are diverted from court." t:dataTypeName=number

metric m:percent_diverted p:float l:"Percent Diverted" d:"Percentage of youth diverted to alternate programs/treatments prior to adjudication. These are cases referred to DJS Intake, where the decision is made to divert from court, and place under an informal pre-court supervision program." t:dataTypeName=percent

metric m:released_youth p:integer l:"Released Youth" d:"Number of youth released from DJS committed programs in the prior fiscal year." t:dataTypeName=number

metric m:success_rate p:float l:"Success Rate" d:"Youth released from DJS committed programs in the prior Fiscal Year with no new offense resulting in an adjudication or conviction within a year." t:dataTypeName=percent

entity e:hwpe-5kbz l:"DJS Performance Metrics - Fiscal Year" t:attribution="Department of Juvenile Services, Office of Research and Evaluation" t:url=https://data.maryland.gov/api/views/hwpe-5kbz

property e:hwpe-5kbz t:meta.view v:id=hwpe-5kbz v:category="Public Safety" v:attributionLink=http://www.djs.state.md.us/data-resource-guides.asp v:averageRating=0 v:name="DJS Performance Metrics - Fiscal Year" v:attribution="Department of Juvenile Services, Office of Research and Evaluation"

property e:hwpe-5kbz t:meta.view.owner v:id=89ms-xkes v:screenName="John Irvine" v:displayName="John Irvine"

property e:hwpe-5kbz t:meta.view.tableauthor v:id=89ms-xkes v:screenName="John Irvine" v:roleName=editor v:displayName="John Irvine"
```

## Top Records

```ls
| date                | fiscal_year | complaints_referred | percent_diverted | released_youth | success_rate | 
| =================== | =========== | =================== | ================ | ============== | ============ | 
| 2001-06-30T00:00:00 | FY2001      | 51271               | 56               |                |              | 
| 2002-06-30T00:00:00 | FY2002      | 53197               | 57.3             |                |              | 
| 2003-06-30T00:00:00 | FY2003      | 52662               | 58.3             |                |              | 
| 2004-06-30T00:00:00 | FY2004      | 53081               | 58               |                |              | 
| 2005-06-30T00:00:00 | FY2005      | 51384               | 57.4             |                |              | 
| 2006-06-30T00:00:00 | FY2006      | 53475               | 56               |                |              | 
| 2007-06-30T00:00:00 | FY2007      | 51137               | 57.7             |                |              | 
| 2008-06-30T00:00:00 | FY2008      | 51127               | 56.8             |                |              | 
| 2009-06-30T00:00:00 | FY2009      | 48387               | 58.2             |                |              | 
| 2013-06-30T00:00:00 | FY2013      | 27550               | 48.2             | 1570           | 79           | 
```