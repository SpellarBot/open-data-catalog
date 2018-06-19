# Campaign Finance - Pre-Election Summary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-pre-election-summary) |
| Metadata | [Link](https://data.austintexas.gov/api/views/xbpn-n65g) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/xbpn-n65g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/xbpn-n65g/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | xbpn-n65g |
| Name | Campaign Finance - Pre-Election Summary |
| Category | Financial |
| Created | 2016-10-30T18:39:53Z |
| Publication Date | 2016-11-01T15:37:37Z |

## Description

A summary of data reported to the Clerk's office within the last 30 days, broken into transaction type and report type, with a transaction total for each type of record (expenditure, contribution, loan) reported.  The most recently reported items are at the top of the dataset.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | reported_by     | Reported By     | text          | text          |
| Yes      | series tag     | number_reported | Number Reported | text          | text          |
| Yes      | time           | date_reported   | Date Reported   | calendar_date | calendar_date |
| Yes      | numeric metric | total_amount    | Total Amount    | money         | money         |
| No       |                | date_from       | Date From       | date          | date          |
| No       |                | date_to         | Date To         | date          | date          |
| Yes      | series tag     | view_report     | View Report     | url           | url           |
| Yes      | series tag     | report_id       | Report_ID       | text          | text          |
```

## Time Field

```ls
Value = date_reported
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_from,date_to
```

## Data Commands

```ls
series e:xbpn-n65g d:2016-10-03T00:00:00.000Z t:reported_by="Austin Forward" t:report_id=R20161004101619-Contribution t:number_reported="28 contributions" t:view_report="http://www.austintexas.gov/edims/document.cfm?id=263980" m:total_amount=98500

series e:xbpn-n65g d:2016-10-03T00:00:00.000Z t:reported_by="Austin Forward" t:report_id=R20161004101619-Expenditure t:number_reported="25 expenditures" t:view_report="http://www.austintexas.gov/edims/document.cfm?id=263980" m:total_amount=128774.55

series e:xbpn-n65g d:2016-10-04T00:00:00.000Z t:reported_by="Texas Vote Environment PAC" t:report_id=R20161005124233-Contribution t:number_reported="1 contribution" t:view_report="http://www.austintexas.gov/edims/document.cfm?id=264034" m:total_amount=5100
```

## Meta Commands

```ls
metric m:total_amount p:double l:"Total Amount" t:dataTypeName=money

entity e:xbpn-n65g l:"Campaign Finance - Pre-Election Summary" t:url=https://data.austintexas.gov/api/views/xbpn-n65g

property e:xbpn-n65g t:meta.view v:id=xbpn-n65g v:category=Financial v:averageRating=0 v:name="Campaign Finance - Pre-Election Summary"

property e:xbpn-n65g t:meta.view.owner v:id=fjfv-27ab v:screenName="Kathryn Darnall" v:displayName="Kathryn Darnall"

property e:xbpn-n65g t:meta.view.tableauthor v:id=fjfv-27ab v:screenName="Kathryn Darnall" v:roleName=editor v:displayName="Kathryn Darnall"
```

## Top Records

```ls
| reported_by                                  | number_reported  | date_reported       | total_amount | date_from  | date_to    | view_report                                                            | report_id                    | 
| ============================================ | ================ | =================== | ============ | ========== | ========== | ====================================================================== | ============================ | 
| Austin Forward                               | 28 contributions | 2016-10-03T00:00:00 | 98500        | 1474934400 | 1475193600 | [http://www.austintexas.gov/edims/document.cfm?id=263980, View Report] | R20161004101619-Contribution | 
| Austin Forward                               | 25 expenditures  | 2016-10-03T00:00:00 | 128774.55    | 1474934400 | 1475280000 | [http://www.austintexas.gov/edims/document.cfm?id=263980, View Report] | R20161004101619-Expenditure  | 
| Texas Vote Environment PAC                   | 1 contribution   | 2016-10-04T00:00:00 | 5100         | 1475452800 | 1475452800 | [http://www.austintexas.gov/edims/document.cfm?id=264034, View Report] | R20161005124233-Contribution | 
| Texas Vote Environment PAC                   | 1 expenditure    | 2016-10-04T00:00:00 | 378.88       | 1475452800 | 1475452800 | [http://www.austintexas.gov/edims/document.cfm?id=264034, View Report] | R20161005124233-Expenditure  | 
| Texas Vote Environment PAC                   | 5 contributions  | 2016-10-04T00:00:00 | 1900         | 1474329600 | 1474675200 | [http://www.austintexas.gov/edims/document.cfm?id=264035, View Report] | R20161005124643-Contribution | 
| Texas Vote Environment PAC                   | 1 expenditure    | 2016-10-04T00:00:00 | 559.65       | 1453507200 | 1453507200 | [http://www.austintexas.gov/edims/document.cfm?id=264035, View Report] | R20161005124643-Expenditure  | 
| Austin Apartment Association PAC             | 10 contributions | 2016-10-05T00:00:00 | 2472         | 1472256000 | 1474329600 | [http://www.austintexas.gov/edims/document.cfm?id=264055, View Report] | R20161005125901-Contribution | 
| Austin Apartment Association PAC             | 3 expenditures   | 2016-10-05T00:00:00 | 15700        | 1473206400 | 1473292800 | [http://www.austintexas.gov/edims/document.cfm?id=264055, View Report] | R20161005125901-Expenditure  | 
| Sensible Transportation Solutions for Austin | 2 contributions  | 2016-10-05T00:00:00 | 19962.2      | 1474416000 | 1474416000 | [http://www.austintexas.gov/edims/document.cfm?id=264070, View Report] | R20161006084927-Contribution | 
| Austin Forward                               | 2 contributions  | 2016-10-05T00:00:00 | 7477.84      | 1475452800 | 1475452800 | [http://www.austintexas.gov/edims/document.cfm?id=264071, View Report] | R20161006090447-Contribution | 
```