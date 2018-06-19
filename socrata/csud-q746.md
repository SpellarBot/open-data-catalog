# Campaign Finance - Summary Financial Data for Committees Controlled by Candidates for Mayor - November 8, 2011 Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-summary-financial-data-for-committees-controlled-by-candidates-for-mayor--d5990) |
| Metadata | [Link](https://data.sfgov.org/api/views/csud-q746) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/csud-q746/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/csud-q746/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | csud-q746 |
| Name | Campaign Finance - Summary Financial Data for Committees Controlled by Candidates for Mayor - November 8, 2011 Election |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | mayor, election, 2011, campaign, finance, contributions, expenditures, loans, cash |
| Created | 2012-03-16T18:22:47Z |
| Publication Date | 2012-03-19T23:23:28Z |

## Description

This dataset contains the financial summary information reported on Fair Political Practices Commission Form 460 by committees controlled by candidates running for Mayor in the November 8, 2011 election.  The data covers the period of 2009-2011 and is current as of 3/8/2012.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | ============== | =========================== | =========================== | ============= | ============= |
| Yes      | series tag     | fppc_filer_id               | FPPC Filer ID               | text          | number        |
| Yes      | series tag     | committee_name              | Committee Name              | text          | text          |
| Yes      | series tag     | candidate_name              | Candidate Name              | text          | text          |
| Yes      | series tag     | report_version_number       | Report Version Number       | text          | number        |
| Yes      | time           | report_date                 | Report Date                 | calendar_date | calendar_date |
| No       |                | period_start_date           | Period Start Date           | calendar_date | calendar_date |
| No       |                | period_end_date             | Period End Date             | calendar_date | calendar_date |
| Yes      | series tag     | schedule                    | Schedule                    | text          | text          |
| Yes      | series tag     | line_item                   | Line Item                   | text          | text          |
| Yes      | numeric metric | total_this_period           | Total This Period           | money         | money         |
| No       |                | calendar_year_total_to_date | Calendar Year Total to Date | text          | money         |
```

## Time Field

```ls
Value = report_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = period_start_date,period_end_date,calendar_year_total_to_date
```

## Data Commands

```ls
series e:csud-q746 d:2012-02-10T00:00:00.000Z t:schedule="Summary for Period" t:committee_name="David Chiu for Mayor 2011" t:candidate_name="Chiu, David" t:line_item="Monetary Contributions" t:report_version_number=1 t:fppc_filer_id=1337108 m:total_this_period=47878

series e:csud-q746 d:2012-02-10T00:00:00.000Z t:schedule="Summary for Period" t:committee_name="David Chiu for Mayor 2011" t:candidate_name="Chiu, David" t:line_item="Loans Received" t:report_version_number=1 t:fppc_filer_id=1337108 m:total_this_period=0

series e:csud-q746 d:2012-02-10T00:00:00.000Z t:schedule="Summary for Period" t:committee_name="David Chiu for Mayor 2011" t:candidate_name="Chiu, David" t:line_item="Subtotal Cash Contributions (Monetary Contributions + Loans Received)" t:report_version_number=1 t:fppc_filer_id=1337108 m:total_this_period=47878
```

## Meta Commands

```ls
metric m:total_this_period p:double l:"Total This Period" t:dataTypeName=money

entity e:csud-q746 l:"Campaign Finance - Summary Financial Data for Committees Controlled by Candidates for Mayor - November 8, 2011 Election" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/csud-q746

property e:csud-q746 t:meta.view v:id=csud-q746 v:category="City Management and Ethics" v:averageRating=0 v:name="Campaign Finance - Summary Financial Data for Committees Controlled by Candidates for Mayor - November 8, 2011 Election" v:attribution="San Francisco Ethics Commission"

property e:csud-q746 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:csud-q746 t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:csud-q746 t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| fppc_filer_id | committee_name            | candidate_name | report_version_number | report_date         | period_start_date   | period_end_date     | schedule           | line_item                                                                              | total_this_period | calendar_year_total_to_date | 
| ============= | ========================= | ============== | ===================== | =================== | =================== | =================== | ================== | ====================================================================================== | ================= | =========================== | 
| 1337108       | David Chiu for Mayor 2011 | Chiu, David    | 1                     | 2012-02-10T00:00:00 | 2011-10-23T00:00:00 | 2011-12-31T00:00:00 | Summary for Period | Monetary Contributions                                                                 | 47878             | 666791.99                   | 
| 1337108       | David Chiu for Mayor 2011 | Chiu, David    | 1                     | 2012-02-10T00:00:00 | 2011-10-23T00:00:00 | 2011-12-31T00:00:00 | Summary for Period | Loans Received                                                                         | 0                 | 0                           | 
| 1337108       | David Chiu for Mayor 2011 | Chiu, David    | 1                     | 2012-02-10T00:00:00 | 2011-10-23T00:00:00 | 2011-12-31T00:00:00 | Summary for Period | Subtotal Cash Contributions (Monetary Contributions + Loans Received)                  | 47878             | 666791.99                   | 
| 1337108       | David Chiu for Mayor 2011 | Chiu, David    | 1                     | 2012-02-10T00:00:00 | 2011-10-23T00:00:00 | 2011-12-31T00:00:00 | Summary for Period | Nonmonetary Contributions                                                              | 0                 | 3032.01                     | 
| 1337108       | David Chiu for Mayor 2011 | Chiu, David    | 1                     | 2012-02-10T00:00:00 | 2011-10-23T00:00:00 | 2011-12-31T00:00:00 | Summary for Period | Total Contributions Received (Subtotal Cash Contributions + Nonmonetary Contributions) | 47878             | 669824                      | 
| 1337108       | David Chiu for Mayor 2011 | Chiu, David    | 1                     | 2012-02-10T00:00:00 | 2011-10-23T00:00:00 | 2011-12-31T00:00:00 | Summary for Period | Payments Made                                                                          | 372320.44         | 1237887.43                  | 
| 1337108       | David Chiu for Mayor 2011 | Chiu, David    | 1                     | 2012-02-10T00:00:00 | 2011-10-23T00:00:00 | 2011-12-31T00:00:00 | Summary for Period | Loans Made                                                                             | 0                 | 0                           | 
| 1337108       | David Chiu for Mayor 2011 | Chiu, David    | 1                     | 2012-02-10T00:00:00 | 2011-10-23T00:00:00 | 2011-12-31T00:00:00 | Summary for Period | Subtotal Cash Payments (Payments Made + Loans Made)                                    | 372320.44         | 1237887.43                  | 
| 1337108       | David Chiu for Mayor 2011 | Chiu, David    | 1                     | 2012-02-10T00:00:00 | 2011-10-23T00:00:00 | 2011-12-31T00:00:00 | Summary for Period | Accrued Expenses (Unpaid Bills)                                                        | 0                 | 0                           | 
| 1337108       | David Chiu for Mayor 2011 | Chiu, David    | 1                     | 2012-02-10T00:00:00 | 2011-10-23T00:00:00 | 2011-12-31T00:00:00 | Summary for Period | Nonmonetary Adjustment                                                                 | 0                 | 3032.01                     | 
```