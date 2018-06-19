# 2015-17 Total Available Revenue By Agency

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-17-total-available-revenue-by-agency) |
| Metadata | [Link](https://data.oregon.gov/api/views/ffkm-k25b) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ffkm-k25b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ffkm-k25b/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ffkm-k25b |
| Name | 2015-17 Total Available Revenue By Agency |
| Category | Revenue & Expense |
| Tags | 2015; 2015-17; 2015-17 revenue; adopted budget; 2015 budget |
| Created | 2015-12-25T07:12:43Z |
| Publication Date | 2015-12-25T21:44:26Z |

## Description

Legislatively Adopted Budget: 2015-17 Biennium: Total Available Revenues by Agency. For more information go to: http://www.oregon.gov/transparency/Pages/revenue.aspx#Money_Coming_In:__Revenue.  This report provides Revenue information for Oregon state agencies, organized by agency # and by fund type (e.g. General Fund, Lottery Funds, Other Funds, and Federal Funds). Note: This report includes data from the Oregon Legislature and the Oregon Judicial Department, but does not include data from the Oregon State Lottery or Semi-independent boards and commissions. (Source: DAS Budget and Management ? Oregon Budget Information Tracking System ? ORBITS)

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | series tag     | id_no                         | ID. No.                       | text      | number      |
| Yes      | series tag     | agency_department_description | Agency\Department Description | text      | text        |
| Yes      | numeric metric | federal_funds                 | Federal Funds                 | money     | money       |
| Yes      | numeric metric | general_fund                  | General Fund                  | money     | money       |
| Yes      | numeric metric | lottery_funds                 | Lottery Funds                 | money     | money       |
| Yes      | numeric metric | other_funds                   | Other Funds                   | money     | money       |
| Yes      | numeric metric | total_funds                   | Total Funds                   | money     | money       |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ffkm-k25b d:2015-01-01T00:00:00.000Z t:agency_department_description="Administrative Svcs, Dept of" t:id_no=10700 m:general_fund=12468238 m:other_funds=1334434361 m:total_funds=1832587723 m:lottery_funds=485685124

series e:ffkm-k25b d:2015-01-01T00:00:00.000Z t:agency_department_description="Licensed Prof Counselors and Therapists, Board of" t:id_no=10800 m:other_funds=1791826 m:total_funds=1791826

series e:ffkm-k25b d:2015-01-01T00:00:00.000Z t:agency_department_description="Aviation, Dept of" t:id_no=10900 m:other_funds=13378085 m:total_funds=21882099 m:federal_funds=8504014
```

## Meta Commands

```ls
metric m:federal_funds p:long l:"Federal Funds" t:dataTypeName=money

metric m:general_fund p:double l:"General Fund" t:dataTypeName=money

metric m:lottery_funds p:double l:"Lottery Funds" t:dataTypeName=money

metric m:other_funds p:long l:"Other Funds" t:dataTypeName=money

metric m:total_funds p:long l:"Total Funds" t:dataTypeName=money

entity e:ffkm-k25b l:"2015-17 Total Available Revenue By Agency" t:url=https://data.oregon.gov/api/views/ffkm-k25b

property e:ffkm-k25b t:meta.view v:id=ffkm-k25b v:category="Revenue & Expense" v:averageRating=0 v:name="2015-17 Total Available Revenue By Agency"

property e:ffkm-k25b t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:ffkm-k25b t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| id_no | agency_department_description                     | federal_funds | general_fund | lottery_funds | other_funds | total_funds | 
| ===== | ================================================= | ============= | ============ | ============= | =========== | =========== | 
| 10700 | Administrative Svcs, Dept of                      |               | 12468238     | 485685124     | 1334434361  | 1832587723  | 
| 10800 | Licensed Prof Counselors and Therapists, Board of |               |              |               | 1791826     | 1791826     | 
| 10900 | Aviation, Dept of                                 | 8504014       |              |               | 13378085    | 21882099    | 
| 11400 | Long Term Care Ombudsman                          |               | 6172203      |               | 753334      | 6925537     | 
| 11500 | Employment Relations Board                        |               | 2393033      |               | 2283585     | 4676618     | 
| 11900 | Tax Practitioners, State Board of                 |               |              |               | 1510830     | 1510830     | 
| 12000 | Accountancy, Board of                             |               |              |               | 3362953     | 3362953     | 
| 12100 | Governor, Office of the                           |               | 12448211     | 4143320       | 3664536     | 20256067    | 
| 12200 | Oregon Board of Psychologist Examiners            |               |              |               | 1430550     | 1430550     | 
| 12300 | Oregon Business Development Department            | 45172199      | 16845486     | 111789423     | 574302504   | 748109612   | 
```