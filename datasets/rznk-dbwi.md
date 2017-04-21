# TESTING_INSURANCE_COMPLAINTS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/testing-insurance-complaints) |
| Metadata | [Link](https://data.ct.gov/api/views/rznk-dbwi) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/rznk-dbwi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/rznk-dbwi/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | rznk-dbwi |
| Name | TESTING_INSURANCE_COMPLAINTS |
| Created | 2016-12-08T14:43:04Z |
| Publication Date | 2016-12-08T14:51:27Z |

## Description

Testing dataset for automated uploads

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type     | Render Type   |
| ======== | ============== | =========== | =========== | ============= | ============= |
| Yes      | series tag     | company     | Company     | text          | text          |
| Yes      | series tag     | file_no     | File No.    | text          | number        |
| Yes      | time           | opened      | Opened      | calendar_date | calendar_date |
| No       |                | closed      | Closed      | calendar_date | calendar_date |
| Yes      | series tag     | coverage    | Coverage    | text          | text          |
| Yes      | series tag     | reason      | Reason      | text          | text          |
| Yes      | series tag     | subreason   | SubReason   | text          | text          |
| Yes      | series tag     | disposition | Disposition | text          | text          |
| Yes      | series tag     | conclusion  | Conclusion  | text          | text          |
| Yes      | numeric metric | recovery    | Recovery    | money         | money         |
| Yes      | series tag     | status      | Status      | text          | text          |
```

## Time Field

```ls
Value = opened
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = closed
```

## Data Commands

```ls
series e:rznk-dbwi d:2016-09-27T00:00:00.000Z t:file_no=604491 t:status=Open t:reason="Unfair Claims Practice" t:coverage="Group Health" t:subreason="CPT Code Issue" t:company="Anthem Health Plans, Inc" t:conclusion=Justified t:disposition="Claim Settled" m:recovery=24442.29

series e:rznk-dbwi d:2016-09-30T00:00:00.000Z t:file_no=604547 t:status=Closed t:reason="Unfair Claims Practice" t:coverage="Auto Liability" t:subreason="Claim Delays" t:company="Allstate Insurance Company" t:conclusion=Justified t:disposition="Corrective Action" m:recovery=0

series e:rznk-dbwi d:2016-12-07T00:00:00.000Z t:file_no=605589 t:status=Closed t:reason=Marketing/Sales t:coverage=Auto t:subreason=Mis-Quote t:company="IDS Property Casualty Insurance Company" t:conclusion=Justified t:disposition="Corrective Action" m:recovery=0
```

## Meta Commands

```ls
metric m:recovery p:double l:Recovery t:dataTypeName=money

entity e:rznk-dbwi l:TESTING_INSURANCE_COMPLAINTS t:url=https://data.ct.gov/api/views/rznk-dbwi

property e:rznk-dbwi t:meta.view v:id=rznk-dbwi v:averageRating=0 v:name=TESTING_INSURANCE_COMPLAINTS

property e:rznk-dbwi t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:rznk-dbwi t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| company                                 | file_no | opened              | closed              | coverage                   | reason                 | subreason                 | disposition             | conclusion            | recovery | status | 
| ======================================= | ======= | =================== | =================== | ========================== | ====================== | ========================= | ======================= | ===================== | ======== | ====== | 
| Anthem Health Plans, Inc                | 604491  | 2016-09-27T00:00:00 |                     | Group Health               | Unfair Claims Practice | CPT Code Issue            | Claim Settled           | Justified             | 24442.29 | Open   | 
| Allstate Insurance Company              | 604547  | 2016-09-30T00:00:00 | 2016-12-28T00:00:00 | Auto Liability             | Unfair Claims Practice | Claim Delays              | Corrective Action       | Justified             | 0        | Closed | 
| IDS Property Casualty Insurance Company | 605589  | 2016-12-07T00:00:00 | 2016-12-28T00:00:00 | Auto                       | Marketing/Sales        | Mis-Quote                 | Corrective Action       | Justified             | 0        | Closed | 
| Commerce Insurance Company (The)        | 605084  | 2016-11-07T00:00:00 | 2016-12-07T00:00:00 | Auto Liability             | Unfair Claims Practice | Claim Delays              | Corrective Action       | Justified             | 585.18   | Closed | 
| Liberty Mutual Fire Insurance Company   | 601644  | 2016-04-07T00:00:00 | 2016-12-08T00:00:00 | Homeowners                 | Unfair Claims Practice | Unsatisfactory Settlement | Refer To Appraisal      | Questionable          | 0        | Closed | 
| Commerce Insurance Company (The)        | 605084  | 2016-11-07T00:00:00 | 2016-12-07T00:00:00 | Auto Liability             | Unfair Claims Practice | Diminished Value          | Enter Arbitration       | Unjustified           | 0        | Closed | 
| Anthem Health Plans, Inc                | 605573  | 2016-12-07T00:00:00 | 2016-12-07T00:00:00 | Exchange-Individual Health | Premium and Rating     | Premium/Rate Increase     | Rate Increase Explained | Furnished Information | 0        | Closed | 
| Anthem Health Plans, Inc                | 605334  | 2016-11-21T00:00:00 | 2016-12-07T00:00:00 | A & H                      | Unfair Claims Practice | Provider Contract Issue   | Provider Issue          | Furnished Information | 0        | Closed | 
| Progressive Direct Insurance Company    | 605219  | 2016-11-14T00:00:00 | 2016-12-05T00:00:00 | Auto                       | Unfair Claims Practice | Denial of Claim           | Coverage Denied         | Unjustified           | 0        | Closed | 
| Aetna Health Inc                        | 304468  | 2013-10-11T00:00:00 | 2013-11-27T00:00:00 | Group Health               | Unfair Claims Practice | Unsatisfactory Settlement | Record Only             | No Action Necessary   | 0        | Closed | 
```