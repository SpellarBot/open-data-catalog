# Contracts: ESD: Douglas: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-esd-douglas-fiscal-year-2014-7e103) |
| Metadata | [Link](https://data.oregon.gov/api/views/f7yf-xpvy) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/f7yf-xpvy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/f7yf-xpvy/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | f7yf-xpvy |
| Name | Contracts: ESD: Douglas: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | contracts, esd, douglas, fiscal year 2014 |
| Created | 2014-12-11T21:57:23Z |
| Publication Date | 2014-12-29T05:48:37Z |

## Description

Contracts for Douglas ESD for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | numeric metric | esd                            | ESD #                          | number        | number        |
| Yes      | series tag     | esd_name                       | ESD NAME                       | text          | text          |
| Yes      | series tag     | award_number_w_amendments      | Award Number w/Amendments      | text          | text          |
| Yes      | series tag     | award_title                    | Award Title                    | text          | text          |
| Yes      | series tag     | award_type                     | Award Type                     | text          | text          |
| Yes      | series tag     | contractor_information         | Contractor Information         | text          | text          |
| Yes      | time           | original_start                 | Original Start                 | calendar_date | calendar_date |
| No       |                | amendment_date                 | Amendment Date                 | calendar_date | calendar_date |
| No       |                | expiration_date                | Expiration Date                | calendar_date | calendar_date |
| Yes      | numeric metric | original_award_value           | Original Award Value           | money         | money         |
| Yes      | series tag     | amendment_value                | Amendment Value                | text          | text          |
| Yes      | numeric metric | total_award_value_w_amendments | Total Award Value w/Amendments | money         | money         |
```

## Time Field

```ls
Value = original_start
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = amendment_date,expiration_date
```

## Data Commands

```ls
series e:f7yf-xpvy d:2013-07-01T00:00:00.000Z t:esd_name="Douglas ESD" t:award_type=CONTRACT t:award_title=SERVICES t:contractor_information="Always Clean Carpet & Tile Solutions" m:total_award_value_w_amendments=356.21 m:esd=1980 m:original_award_value=356.21

series e:f7yf-xpvy d:2013-07-01T00:00:00.000Z t:esd_name="Douglas ESD" t:award_type=CONTRACT t:award_title="SLP SERVICES" t:contractor_information="Ardor Health Solutions" m:total_award_value_w_amendments=82680 m:esd=1980 m:original_award_value=82680

series e:f7yf-xpvy d:2013-07-01T00:00:00.000Z t:esd_name="Douglas ESD" t:award_type=CONTRACT t:award_title="ANNUAL SUBSCRIPTION" t:contractor_information="Aspex Solutions" m:total_award_value_w_amendments=1095 m:esd=1980 m:original_award_value=1095
```

## Meta Commands

```ls
metric m:esd p:integer l:"ESD #" t:dataTypeName=number

metric m:original_award_value p:double l:"Original Award Value" t:dataTypeName=money

metric m:total_award_value_w_amendments p:double l:"Total Award Value w/Amendments" t:dataTypeName=money

entity e:f7yf-xpvy l:"Contracts: ESD: Douglas: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/f7yf-xpvy

property e:f7yf-xpvy t:meta.view v:id=f7yf-xpvy v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ESD: Douglas: Fiscal Year 2014"

property e:f7yf-xpvy t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:f7yf-xpvy t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd  | esd_name    | award_number_w_amendments | award_title         | award_type             | contractor_information                  | original_start      | amendment_date      | expiration_date     | original_award_value | amendment_value | total_award_value_w_amendments | 
| ==== | =========== | ========================= | =================== | ====================== | ======================================= | =================== | =================== | =================== | ==================== | =============== | ============================== | 
| 1980 | Douglas ESD |                           | SERVICES            | CONTRACT               | Always Clean Carpet & Tile Solutions    | 2013-07-01T00:00:00 |                     | 2014-06-30T00:00:00 | 356.21               |                 | 356.21                         | 
| 1980 | Douglas ESD |                           | SLP SERVICES        | CONTRACT               | Ardor Health Solutions                  | 2013-07-01T00:00:00 |                     | 2014-06-30T00:00:00 | 82680.00             |                 | 82680.00                       | 
| 1980 | Douglas ESD |                           | ANNUAL SUBSCRIPTION | CONTRACT               | Aspex Solutions                         | 2013-07-01T00:00:00 |                     | 2014-06-30T00:00:00 | 1095.00              |                 | 1095.00                        | 
| 1980 | Douglas ESD |                           | SPEAKER             | INDEPENDENT CONTRACTOR | Assistive Technology for Education, LLC | 2013-07-01T00:00:00 |                     | 2014-06-30T00:00:00 | 550.00               |                 | 550.00                         | 
| 1980 | Douglas ESD |                           | RENTAL              | ANNUAL AGREEMENT       | Berry's Oak Grove Storage               | 2012-08-24T00:00:00 |                     |                     | 2160.00              |                 | 2160.00                        | 
| 1980 | Douglas ESD |                           | SPEAKER             | INDEPENDENT CONTRACTOR | Beth Poss                               | 2014-02-27T00:00:00 | 2014-02-27T00:00:00 | 2014-02-27T00:00:00 | 731.69               |                 | 731.69                         | 
| 1980 | Douglas ESD |                           | SPEAKER             | INDEPENDENT CONTRACTOR | Bowser, Mary                            | 2013-09-27T00:00:00 |                     | 2014-06-30T00:00:00 | 10200.00             |                 | 10200.00                       | 
| 1980 | Douglas ESD |                           | TRAINING            | INDEPENDENT CONTRACTOR | BURTON, RICK                            | 2013-11-14T00:00:00 |                     | 2013-11-15T00:00:00 | 780.00               |                 | 780.00                         | 
| 1980 | Douglas ESD |                           | PRESCHOOL           | CONTRACT               | Butterfly House Early Learning Center   | 2013-07-01T00:00:00 |                     | 2014-06-30T00:00:00 | 16622.00             |                 | 16622.00                       | 
| 1980 | Douglas ESD |                           | TRAINING            | INDEPENDENT CONTRACTOR | Cady, Karen                             | 2013-07-01T00:00:00 |                     | 2014-06-30T00:00:00 | 1000.00              |                 | 1000.00                        | 
```