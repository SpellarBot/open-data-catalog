# Indoor Plumbing Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/indoor-plumbing-program-73792) |
| Metadata | [Link](https://data.maryland.gov/api/views/nn3z-6ak2) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/nn3z-6ak2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/nn3z-6ak2/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | nn3z-6ak2 |
| Name | Indoor Plumbing Program |
| Attribution | Maryland Department of Housing and Community Development |
| Category | Housing |
| Tags | department of housing & community development, dhc, ipp, indoor plumbing program, special loans, single family, rehab |
| Created | 2012-11-09T16:45:10Z |
| Publication Date | 2012-11-13T20:52:19Z |

## Description

The purpose of the Indoor Plumbing Program (IPP) is to provide indoor plumbing in residential properties. Loans may be made for single-family, owner-occupied houses and rental properties with one to four units, which do not have indoor plumbing. Properties must be structurally sound. Owner-occupants of single-family homes and all residents of assisted rental housing must have an income at or below 80 percent of the statewide or Washington, D.C. Metropolitan Statistical Area median income. Interest rates range from 0% to 6% and are based on the applicant's ability to pay. Deferred loans are available to some borrowers who require health, safety or accessability improvements. For rental units, the project's income determines requirements for loan deferment or repayment.

DISCLAIMER: Some of the information may be tied to the Department?s bond funded loan programs and should not be relied upon in making an investment decision. The Department provides comprehensive quarterly and annual financial information and operating data regarding its bonds and bond funded loan programs, all of which is posted on the publicly-accessible Electronic Municipal Market Access system website (commonly known as EMMA) that is maintained by the Municipal Securities Rulemaking Board, and on the Department?s website under Investor Information. 

More information accessible here: http://dhcd.maryland.gov/Investors/Pages/default.aspx

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                        | Data Type | Render Type |
| ======== | ============== | ========================= | =========================== | ========= | =========== |
| No       | time           | :updated_at               | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | month                     | Month                       | text      | text        |
| Yes      | numeric metric | ipp_committed             | $ IPP Committed             | money     | money       |
| Yes      | numeric metric | ipp_applications_received | # IPP Applications Received | number    | number      |
| Yes      | numeric metric | ipp_units_committed       | # IPP Units Committed       | number    | number      |
| Yes      | numeric metric | ipp_closed_loans          | $ IPP Closed Loans          | money     | money       |
| Yes      | numeric metric | ipp_units_closed          | # IPP Units Closed          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nn3z-6ak2 d:2012-11-09T08:45:12.000Z t:month=08/01/2009 m:ipp_closed_loans=0 m:ipp_applications_received=5 m:ipp_units_committed=5 m:ipp_units_closed=0 m:ipp_committed=56059

series e:nn3z-6ak2 d:2012-11-09T08:45:12.000Z t:month=09/01/2009 m:ipp_closed_loans=9612 m:ipp_applications_received=3 m:ipp_units_committed=2 m:ipp_units_closed=1 m:ipp_committed=20892

series e:nn3z-6ak2 d:2012-11-09T08:45:12.000Z t:month=10/01/2009 m:ipp_closed_loans=67472 m:ipp_applications_received=1 m:ipp_units_committed=2 m:ipp_units_closed=7 m:ipp_committed=16933
```

## Meta Commands

```ls
metric m:ipp_committed p:integer l:"$ IPP Committed" t:dataTypeName=money

metric m:ipp_applications_received p:integer l:"# IPP Applications Received" t:dataTypeName=number

metric m:ipp_units_committed p:integer l:"# IPP Units Committed" t:dataTypeName=number

metric m:ipp_closed_loans p:integer l:"$ IPP Closed Loans" t:dataTypeName=money

metric m:ipp_units_closed p:integer l:"# IPP Units Closed" t:dataTypeName=number

entity e:nn3z-6ak2 l:"Indoor Plumbing Program" t:attribution="Maryland Department of Housing and Community Development" t:url=https://data.maryland.gov/api/views/nn3z-6ak2

property e:nn3z-6ak2 t:meta.view v:id=nn3z-6ak2 v:category=Housing v:attributionLink=http://dhcd.maryland.gov/Pages/default.aspx v:averageRating=0 v:name="Indoor Plumbing Program" v:attribution="Maryland Department of Housing and Community Development"

property e:nn3z-6ak2 t:meta.view.owner v:id=pugw-9r35 v:screenName="Jessica Handy" v:lastNotificationSeenAt=1491917263 v:displayName="Jessica Handy"

property e:nn3z-6ak2 t:meta.view.tableauthor v:id=pugw-9r35 v:screenName="Jessica Handy" v:roleName=editor v:lastNotificationSeenAt=1491917263 v:displayName="Jessica Handy"
```

## Top Records

```ls
| :updated_at | month      | ipp_committed | ipp_applications_received | ipp_units_committed | ipp_closed_loans | ipp_units_closed | 
| =========== | ========== | ============= | ========================= | =================== | ================ | ================ | 
| 1352450712  | 08/01/2009 | 56059         | 5                         | 5                   | 0                | 0                | 
| 1352450712  | 09/01/2009 | 20892         | 3                         | 2                   | 9612             | 1                | 
| 1352450712  | 10/01/2009 | 16933         | 1                         | 2                   | 67472            | 7                | 
| 1352450712  | 11/01/2009 | 60393         | 2                         | 3                   | 77850            | 6                | 
| 1352450712  | 12/01/2009 | 8968          | 3                         | 1                   | 10422            | 1                | 
| 1352450712  | 01/01/2010 | 8335          | 1                         | 1                   | 0                | 0                | 
| 1352450712  | 02/01/2010 | 0             | 2                         | 0                   | 12280            | 1                | 
| 1352450712  | 03/01/2010 | 23869         | 1                         | 1                   | 82808            | 4                | 
| 1352450712  | 04/01/2010 | 35454         | 2                         | 1                   | 8335             | 1                | 
| 1352450712  | 05/01/2010 | 0             | 1                         | 0                   | 0                | 0                | 
```