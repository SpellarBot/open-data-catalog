# 2015-16 Total Available Revenue By Agency

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-16-total-available-revenue-by-agency) |
| Metadata | [Link](https://data.oregon.gov/api/views/7fjf-a4ya) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/7fjf-a4ya/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/7fjf-a4ya/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 7fjf-a4ya |
| Name | 2015-16 Total Available Revenue By Agency |
| Category | Revenue & Expense |
| Tags | 2016, 2015-17, 2015-17 revenue, adopted budget, budget |
| Created | 2016-12-10T04:33:02Z |
| Publication Date | 2016-12-10T04:37:41Z |

## Description

Legislatively Adopted Budget: 2015-17 Biennium: Total Available Revenues by Agency (Sept. 2016). For more information go to: http://www.oregon.gov/transparency/Pages/revenue.aspx#Money_Coming_In:__Revenue. This report provides Revenue information for Oregon state agencies, organized by agency # and by fund type (e.g. General Fund, Lottery Funds, Other Funds, and Federal Funds). Note: This report includes data from the Oregon Legislature and the Oregon Judicial Department, but does not include data from the Oregon State Lottery or Semi-independent boards and commissions. (Source: DAS Budget and Management ? Oregon Budget Information Tracking System ? ORBITS)

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | dept_no          | Dept No          | text      | text        |
| Yes      | series tag     | dept_description | Dept Description | text      | text        |
| Yes      | numeric metric | federal_funds    | Federal Funds    | number    | number      |
| Yes      | numeric metric | general_fund     | General Fund     | number    | number      |
| Yes      | numeric metric | lottery_fund     | Lottery Fund     | number    | number      |
| Yes      | numeric metric | other_funds      | Other Funds      | number    | number      |
| Yes      | numeric metric | grand_total      | Grand Total      | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7fjf-a4ya d:2015-01-01T00:00:00.000Z t:dept_no=10000 t:dept_description="Human Services, Dept. of" m:lottery_fund=0 m:general_fund=2700922689 m:other_funds=502628844 m:federal_funds=7002589591 m:grand_total=10206141124

series e:7fjf-a4ya d:2015-01-01T00:00:00.000Z t:dept_no=10700 t:dept_description="Administrative Svcs, Dept of" m:lottery_fund=485685124 m:general_fund=12468238 m:other_funds=1334434361 m:federal_funds=0 m:grand_total=1832587723

series e:7fjf-a4ya d:2015-01-01T00:00:00.000Z t:dept_no=10800 t:dept_description="Licensed Prof Counselors and Therapists, Board of" m:other_funds=1791826 m:grand_total=1791826
```

## Meta Commands

```ls
metric m:federal_funds p:long l:"Federal Funds" t:dataTypeName=number

metric m:general_fund p:long l:"General Fund" t:dataTypeName=number

metric m:lottery_fund p:integer l:"Lottery Fund" t:dataTypeName=number

metric m:other_funds p:long l:"Other Funds" t:dataTypeName=number

metric m:grand_total p:long l:"Grand Total" t:dataTypeName=number

entity e:7fjf-a4ya l:"2015-16 Total Available Revenue By Agency" t:url=https://data.oregon.gov/api/views/7fjf-a4ya

property e:7fjf-a4ya t:meta.view v:id=7fjf-a4ya v:category="Revenue & Expense" v:averageRating=0 v:name="2015-16 Total Available Revenue By Agency"

property e:7fjf-a4ya t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:7fjf-a4ya t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| dept_no | dept_description                                  | federal_funds | general_fund | lottery_fund | other_funds | grand_total | 
| ======= | ================================================= | ============= | ============ | ============ | =========== | =========== | 
| 10000   | Human Services, Dept. of                          | 7002589591    | 2700922689   | 0            | 502628844   | 10206141124 | 
| 10700   | Administrative Svcs, Dept of                      | 0             | 12468238     | 485685124    | 1334434361  | 1832587723  | 
| 10800   | Licensed Prof Counselors and Therapists, Board of |               |              |              | 1791826     | 1791826     | 
| 10900   | Aviation, Dept of                                 | 8504014       |              |              | 13378085    | 21882099    | 
| 11400   | Long Term Care Ombudsman                          |               | 6172203      |              | 753334      | 6925537     | 
| 11500   | Employment Relations Board                        |               | 2393033      |              | 2283585     | 4676618     | 
| 11900   | Tax Practitioners, State Board of                 |               |              |              | 1510830     | 1510830     | 
| 12000   | Accountancy, Board of                             |               |              |              | 3362953     | 3362953     | 
| 12100   | Governor, Office of the                           | 0             | 12448211     | 4143320      | 3664536     | 20256067    | 
| 12200   | Oregon Board of Psychologist Examiners            |               |              |              | 1430550     | 1430550     | 
```