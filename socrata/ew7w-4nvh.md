# Indoor Plumbing Program FY13

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/indoor-plumbing-program-fy13-68233) |
| Metadata | [Link](https://data.maryland.gov/api/views/ew7w-4nvh) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/ew7w-4nvh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/ew7w-4nvh/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | ew7w-4nvh |
| Name | Indoor Plumbing Program FY13 |
| Attribution | Maryland Department of Housing and Community Developement |
| Category | Housing |
| Tags | dhcd, housing, indoor, plumbing |
| Created | 2014-06-02T15:28:34Z |
| Publication Date | 2014-06-03T19:01:07Z |

## Description

The Indoor Plumbing Program is a sub-set of the Maryland Rehabilitation Loan Program. Numbers are tracked individually, when the rehabilitation	work involves strictly plumbing, sewer and water related improvements. Often times IPP improvements/rehabilitation is done as part of a larger project and the funding does not reflect in these numbers.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                        | Data Type     | Render Type   |
| ======== | ============== | ========================= | =========================== | ============= | ============= |
| Yes      | time           | month                     | Month                       | calendar_date | calendar_date |
| Yes      | numeric metric | ipp_applications_received | # IPP Applications Received | number        | number        |
| Yes      | numeric metric | ipp_committed             | $ IPP Committed             | money         | money         |
| Yes      | numeric metric | ipp_units_committed       | # IPP Units Committed       | number        | number        |
| Yes      | numeric metric | ipp_closed_loans          | $ IPP Closed Loans          | money         | money         |
| Yes      | numeric metric | ipp_units_closed          | # IPP Units Closed          | number        | number        |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ew7w-4nvh d:2012-07-01T00:00:00.000Z m:ipp_closed_loans=23260 m:ipp_applications_received=1 m:ipp_units_committed=1 m:ipp_units_closed=3 m:ipp_committed=7059

series e:ew7w-4nvh d:2012-08-01T00:00:00.000Z m:ipp_closed_loans=21428 m:ipp_applications_received=1 m:ipp_units_committed=2 m:ipp_units_closed=2 m:ipp_committed=23350

series e:ew7w-4nvh d:2012-09-01T00:00:00.000Z m:ipp_closed_loans=28129 m:ipp_applications_received=1 m:ipp_units_committed=0 m:ipp_units_closed=2 m:ipp_committed=0
```

## Meta Commands

```ls
metric m:ipp_applications_received p:integer l:"# IPP Applications Received" t:dataTypeName=number

metric m:ipp_committed p:double l:"$ IPP Committed" t:dataTypeName=money

metric m:ipp_units_committed p:integer l:"# IPP Units Committed" t:dataTypeName=number

metric m:ipp_closed_loans p:double l:"$ IPP Closed Loans" t:dataTypeName=money

metric m:ipp_units_closed p:integer l:"# IPP Units Closed" t:dataTypeName=number

entity e:ew7w-4nvh l:"Indoor Plumbing Program FY13" t:attribution="Maryland Department of Housing and Community Developement" t:url=https://data.maryland.gov/api/views/ew7w-4nvh

property e:ew7w-4nvh t:meta.view v:id=ew7w-4nvh v:category=Housing v:attributionLink=http://www.dhcd.state.md.us/Website v:averageRating=0 v:name="Indoor Plumbing Program FY13" v:attribution="Maryland Department of Housing and Community Developement"

property e:ew7w-4nvh t:meta.view.license v:name="Public Domain"

property e:ew7w-4nvh t:meta.view.owner v:id=3bma-cuk6 v:screenName="Linda DeLuca" v:displayName="Linda DeLuca"

property e:ew7w-4nvh t:meta.view.tableauthor v:id=3bma-cuk6 v:screenName="Linda DeLuca" v:roleName=editor v:displayName="Linda DeLuca"
```

## Top Records

```ls
| month               | ipp_applications_received | ipp_committed | ipp_units_committed | ipp_closed_loans | ipp_units_closed | 
| =================== | ========================= | ============= | =================== | ================ | ================ | 
| 2012-07-01T00:00:00 | 1                         | 7059.00       | 1                   | 23260.00         | 3                | 
| 2012-08-01T00:00:00 | 1                         | 23350.00      | 2                   | 21428.00         | 2                | 
| 2012-09-01T00:00:00 | 1                         | 0.00          | 0                   | 28129.00         | 2                | 
| 2012-10-01T00:00:00 | 1                         | 20196.00      | 1                   | 31956.00         | 2                | 
| 2012-11-01T00:00:00 | 0                         | 0.00          | 0                   | 0.00             | 0                | 
| 2012-12-01T00:00:00 | 0                         | 0.00          | 0                   | 0.00             | 0                | 
| 2013-01-01T00:00:00 | 0                         | 10253.00      | 1                   | 0.00             | 0                | 
| 2013-02-01T00:00:00 | 3                         | 0.00          | 0                   | 0.00             | 0                | 
| 2013-03-01T00:00:00 | 1                         | 16800.00      | 1                   | 0.00             | 0                | 
| 2013-04-01T00:00:00 | 0                         | 0.00          | 0                   | 10253.00         | 1                | 
```