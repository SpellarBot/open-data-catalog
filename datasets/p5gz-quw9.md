# DEPRACTATED King County Elections, Canvassing Board Schedule

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-elections-canvassing-board-schedule-92152) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/p5gz-quw9) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/p5gz-quw9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/p5gz-quw9/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | p5gz-quw9 |
| Name | DEPRACTATED King County Elections, Canvassing Board Schedule |
| Attribution | King County Elections |
| Category | Election operations |
| Tags | king county, elections, canvassing board |
| Created | 2012-02-27T22:05:58Z |
| Publication Date | 2015-12-02T17:23:38Z |

## Description

Schedule for meetings of the King County Elections Canvassing Board:

## Columns

```ls
| Included | Schema Type | Field Name | Name     | Data Type     | Render Type   |
| ======== | =========== | ========== | ======== | ============= | ============= |
| Yes      | time        | date       | Date     | calendar_date | calendar_date |
| Yes      | series tag  | time       | Time     | text          | text          |
| Yes      | series tag  | event_id   | Event ID | text          | text          |
| Yes      | series tag  | event      | Event    | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:p5gz-quw9 d:2015-10-16T00:00:00.000Z t:time="10:00 a.m." t:event="Convening Meeting: Review canvassing procedures as necessary, provide instructions regarding mail ballots.  Commence processing mail ballots received." t:event_id=CB m:row_number.p5gz-quw9=1

series e:p5gz-quw9 d:2015-10-20T00:00:00.000Z t:time="1:00 p.m." t:event="Logic and accuracy tests for vote counting equipment" t:event_id=CB m:row_number.p5gz-quw9=2

series e:p5gz-quw9 d:2015-11-12T00:00:00.000Z t:time="1:30 p.m.." t:event="First Post-Election Meeting: Review provisional ballots and any special-case mail ballots received subsequent to the election.  Make determination regarding issues of voter intent." t:event_id=CB m:row_number.p5gz-quw9=3
```

## Meta Commands

```ls
metric m:row_number.p5gz-quw9 p:long l:"Row Number"

entity e:p5gz-quw9 l:"DEPRACTATED King County Elections, Canvassing Board Schedule" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/p5gz-quw9

property e:p5gz-quw9 t:meta.view v:id=p5gz-quw9 v:category="Election operations" v:attributionLink=http://kingcounty.gov/elections/currentelections/canvassingboard.aspx v:averageRating=0 v:name="DEPRACTATED King County Elections, Canvassing Board Schedule" v:attribution="King County Elections"

property e:p5gz-quw9 t:meta.view.license v:name="Public Domain"

property e:p5gz-quw9 t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:p5gz-quw9 t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| date                | time       | event_id | event                                                                                                                                                                                | 
| =================== | ========== | ======== | ==================================================================================================================================================================================== | 
| 2015-10-16T00:00:00 | 10:00 a.m. | CB       | Convening Meeting: Review canvassing procedures as necessary, provide instructions regarding mail ballots. Commence processing mail ballots received.                                | 
| 2015-10-20T00:00:00 | 1:00 p.m.  | CB       | Logic and accuracy tests for vote counting equipment                                                                                                                                 | 
| 2015-11-12T00:00:00 | 1:30 p.m.. | CB       | First Post-Election Meeting: Review provisional ballots and any special-case mail ballots received subsequent to the election. Make determination regarding issues of voter intent.  | 
| 2015-11-19T00:00:00 | 1:30 p.m.. | CB       | Second Post-Election Meeting: Review provisional ballots and any special-case mail ballots received subsequent to the election. Make determination regarding issues of voter intent. | 
| 2015-11-24T00:00:00 | 3:00 p.m.  | CB       | Certification Meeting: Approve corrective action for discrepancies or errors resulting from abstract review, if any. Sign the certificate.                                           | 
| 2015-11-23T00:00:00 | 3:30 p.m.  | CB       | Final Post-Election Meeting: Complete the canvassing process and direct preparation of election certification documents.                                                             | 
| 2015-10-29T00:00:00 | 1:30 p.m.  | CB       | Canceled.                                                                                                                                                                            | 
| 2015-12-07T00:00:00 | 1:00 p.m.  | CB       | Certification Meeting: Reconciliation and create final reports; King County Canvassing Board meets to certify recount at 1:00. PM.                                                   | 
```