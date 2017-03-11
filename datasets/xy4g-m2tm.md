# Board of Ethics - Summary of Activity, by Month - Fiscal Year 2011 Incomplete

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/board-of-ethics-summary-of-activity-by-month-fiscal-year-2011-incomplete-30bb3) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/xy4g-m2tm) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/xy4g-m2tm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/xy4g-m2tm/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | xy4g-m2tm |
| Name | Board of Ethics - Summary of Activity, by Month - Fiscal Year 2011 Incomplete |
| Attribution | Cook County Board of Ethics |
| Category | Finance & Administration |
| Created | 2011-09-07T16:37:25Z |
| Publication Date | 2014-10-09T20:56:31Z |
| Rows Updated | 2014-10-09T20:56:20Z |

## Description

Data covers December 2010 through June 2011.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                              | Data Type | Render Type |
| ======== | ============== | =============================== | ================================= | ========= | =========== |
| No       | time           | :updated_at                     | updated_at                        | meta_data | meta_data   |
| Yes      | series tag     | month                           | Month                             | text      | text        |
| Yes      | numeric metric | training_seminars               | Training Seminars                 | number    | number      |
| Yes      | numeric metric | employees_trained               | Employees Trained                 | number    | number      |
| Yes      | numeric metric | inquiries_pre_bid_mtgs_included | Inquiries (Pre-Bid Mtgs included) | number    | number      |
| Yes      | numeric metric | new_investigations_opened       | New Investigations Opened         | number    | number      |
| Yes      | numeric metric | advisory_opinions_issued        | Advisory Opinions Issued          | number    | number      |
| Yes      | numeric metric | vendor_compliance_audit         | Vendor Compliance Audit           | number    | number      |
| Yes      | numeric metric | lobbyist_expense_audit          | Lobbyist Expense Audit            | number    | number      |
| Yes      | numeric metric | political_contributions_audit   | Political Contributions Audit     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xy4g-m2tm d:2011-09-07T09:37:28.000Z t:month=DEC m:vendor_compliance_audit=20 m:training_seminars=3 m:advisory_opinions_issued=1 m:political_contributions_audit=0 m:inquiries_pre_bid_mtgs_included=24 m:lobbyist_expense_audit=0 m:employees_trained=29 m:new_investigations_opened=6

series e:xy4g-m2tm d:2011-09-07T09:37:28.000Z t:month=JAN m:vendor_compliance_audit=10 m:training_seminars=2 m:advisory_opinions_issued=1 m:political_contributions_audit=0 m:inquiries_pre_bid_mtgs_included=22 m:lobbyist_expense_audit=0 m:employees_trained=29 m:new_investigations_opened=1

series e:xy4g-m2tm d:2011-09-07T09:37:28.000Z t:month=FEB m:vendor_compliance_audit=23 m:training_seminars=2 m:advisory_opinions_issued=2 m:political_contributions_audit=0 m:inquiries_pre_bid_mtgs_included=10 m:lobbyist_expense_audit=0 m:employees_trained=26 m:new_investigations_opened=0
```

## Meta Commands

```ls
metric m:training_seminars p:integer l:"Training Seminars" t:dataTypeName=number

metric m:employees_trained p:integer l:"Employees Trained" t:dataTypeName=number

metric m:inquiries_pre_bid_mtgs_included p:integer l:"Inquiries (Pre-Bid Mtgs included)" t:dataTypeName=number

metric m:new_investigations_opened p:integer l:"New Investigations Opened" t:dataTypeName=number

metric m:advisory_opinions_issued p:integer l:"Advisory Opinions Issued" t:dataTypeName=number

metric m:vendor_compliance_audit p:integer l:"Vendor Compliance Audit" t:dataTypeName=number

metric m:lobbyist_expense_audit p:integer l:"Lobbyist Expense Audit" t:dataTypeName=number

metric m:political_contributions_audit p:integer l:"Political Contributions Audit" t:dataTypeName=number

entity e:xy4g-m2tm l:"Board of Ethics - Summary of Activity, by Month - Fiscal Year 2011 Incomplete" t:attribution="Cook County Board of Ethics" t:url=https://datacatalog.cookcountyil.gov/api/views/xy4g-m2tm

property e:xy4g-m2tm t:meta.view d:2017-03-10T14:19:08.358Z v:id=xy4g-m2tm v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/board_of_ethics/293 v:averageRating=0 v:name="Board of Ethics - Summary of Activity, by Month - Fiscal Year 2011 Incomplete" v:attribution="Cook County Board of Ethics"

property e:xy4g-m2tm t:meta.view.license d:2017-03-10T14:19:08.358Z v:name="Public Domain"

property e:xy4g-m2tm t:meta.view.owner d:2017-03-10T14:19:08.358Z v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:xy4g-m2tm t:meta.view.tableauthor d:2017-03-10T14:19:08.358Z v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```