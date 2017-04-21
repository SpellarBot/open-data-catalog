# Muni Driver Reported Transit Only Lane Violations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/muni-driver-reported-transit-only-lane-violations) |
| Metadata | [Link](https://data.sfgov.org/api/views/sd75-dps9) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/sd75-dps9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/sd75-dps9/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | sd75-dps9 |
| Name | Muni Driver Reported Transit Only Lane Violations |
| Category | Transportation |
| Tags | traffic, lanes, muni, violations |
| Created | 2016-02-27T01:33:31Z |
| Publication Date | 2016-04-15T18:23:11Z |

## Description

Location of Muni driver reported transit only lane violations from March 2008 to February 2015. These are geocoded from an Excel spreadsheet obtained from Enforcement). Currently in need of a regular update schedule. Dataset is now updated in ad hoc fashion.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | object_id            | Object ID            | text      | number      |
| Yes      | series tag     | ticket_number        | Ticket Number        | text      | number      |
| Yes      | time           | citation_issue_date  | Citation Issue Date  | date      | date        |
| Yes      | series tag     | citaton_issue_month  | Citaton Issue Month  | text      | text        |
| No       |                | citation_issue_time  | Citation Issue Time  | text      | text        |
| Yes      | series tag     | location             | Location             | text      | text        |
| Yes      | series tag     | violation_code       | Violation Code       | text      | text        |
| Yes      | series tag     | violation            | Violation            | text      | text        |
| Yes      | numeric metric | fine_amount          | Fine Amount          | number    | number      |
| Yes      | series tag     | citation_status      | Citation Status      | text      | text        |
| Yes      | series tag     | amount_paid          | Amount Paid          | text      | text        |
| Yes      | numeric metric | amount_due           | Amount Due           | number    | number      |
| Yes      | series tag     | suspend_code         | Suspend Code         | text      | text        |
| No       |                | suspend_process_date | Suspend Process Date | date      | date        |
| No       |                | suspend_until_date   | Suspend Until Date   | date      | date        |
| Yes      | series tag     | disposition_code     | Disposition Code     | text      | text        |
| No       |                | last_edited_date     | Last Edited Date     | date      | date        |
```

## Time Field

```ls
Value = citation_issue_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = citation_issue_time,suspend_process_date,suspend_until_date,last_edited_date
```

## Data Commands

```ls
series e:sd75-dps9 d:2008-07-10T00:00:00.000Z t:amount_paid="$                       -" t:suspend_code="731 731MP EXP" t:violation_code=V22500H t:location="643 O'FARRELL" t:violation="DBL PARK" t:object_id=1 t:ticket_number=100029164 t:citation_status=Closed m:fine_amount=65 m:amount_due=0

series e:sd75-dps9 d:2008-07-10T00:00:00.000Z t:amount_paid=$65.00 t:suspend_code="730 730TRNLN" t:violation_code=V22500H t:location="372 O'FARRELL" t:violation="DBL PARK" t:object_id=2 t:ticket_number=100029166 t:citation_status=Open m:fine_amount=65 m:amount_due=85

series e:sd75-dps9 d:2008-07-10T00:00:00.000Z t:amount_paid=$65.00 t:suspend_code="730 730TRNLN" t:violation_code=V22500H t:location="372 O'FARRELL" t:violation="DBL PARK" t:object_id=3 t:ticket_number=100029167 t:citation_status=Closed m:fine_amount=65 m:amount_due=0
```

## Meta Commands

```ls
metric m:fine_amount p:integer l:"Fine Amount" t:dataTypeName=number

metric m:amount_due p:integer l:"Amount Due" t:dataTypeName=number

entity e:sd75-dps9 l:"Muni Driver Reported Transit Only Lane Violations" t:url=https://data.sfgov.org/api/views/sd75-dps9

property e:sd75-dps9 t:meta.view v:id=sd75-dps9 v:category=Transportation v:averageRating=0 v:name="Muni Driver Reported Transit Only Lane Violations"

property e:sd75-dps9 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:sd75-dps9 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:sd75-dps9 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| object_id | ticket_number | citation_issue_date | citaton_issue_month | citation_issue_time | location      | violation_code | violation  | fine_amount | citation_status | amount_paid | amount_due | suspend_code  | suspend_process_date | suspend_until_date | disposition_code | last_edited_date | 
| ========= | ============= | =================== | =================== | =================== | ============= | ============== | ========== | =========== | =============== | =========== | ========== | ============= | ==================== | ================== | ================ | ================ | 
| 1         | 100029164     | 1215648000          |                     | 17:33               | 643 O'FARRELL | V22500H        | DBL PARK   | 65          | Closed          | $ -         | 0          | 731 731MP EXP | 1216684800           | 946512000          |                  |                  | 
| 2         | 100029166     | 1215648000          |                     | 15:27               | 372 O'FARRELL | V22500H        | DBL PARK   | 65          | Open            | $65.00      | 85         | 730 730TRNLN  | 1216425600           | 1218240000         |                  |                  | 
| 3         | 100029167     | 1215648000          |                     | 15:27               | 372 O'FARRELL | V22500H        | DBL PARK   | 65          | Closed          | $65.00      | 0          | 730 730TRNLN  | 1216425600           | 1218240000         |                  |                  | 
| 4         | 100000050     | 1215734400          |                     | 19:17               | 924 GEARY     | V22500I        | BUS ZONE   | 250         | Closed          | $ -         | 0          | 731 731MP EXP | 1216771200           | 946512000          |                  |                  | 
| 5         | 100029169     | 1215734400          |                     | 11:19               | 481 GEARY     | V22500H        | DBL PARK   | 65          | Closed          | $65.00      | 0          | 730 730TRNLN  | 1216425600           | 1218240000         |                  |                  | 
| 6         | 100029170     | 1215734400          |                     | 13:17               | 467 GEARY     | V22500H        | DBL PARK   | 65          | Closed          | $65.00      | 0          | 730 730TRNLN  | 1216425600           | 1218240000         |                  |                  | 
| 7         | 100029171     | 1215734400          |                     | 21:01               | 1008 GEARY    | V22500H        | DBL PARK   | 65          | Closed          | $ -         | 0          | 83 83 PEND HE | 1224374400           | 1239926400         | 201 HR UP NTPD   |                  | 
| 8         | 100029172     | 1215734400          |                     | 13:21               | 898 GEARY     | V22500I        | BUS ZONE   | 250         | Closed          | $250.00     | 0          | 91 P20 ENR    | 1217808000           | 1227571200         |                  |                  | 
| 9         | 100029173     | 1215734400          |                     | 18:50               | 1014 GEARY    | T32A.1         | TWAWY ZN#1 | 60          | Open            | $85.00      | 60         | 730 730TRNLN  | 1216425600           | 1218240000         |                  |                  | 
| 10        | 100029174     | 1215734400          |                     | 19:15               | 596 GEARY     | V22500I        | BUS ZONE   | 250         | Open            | $ -         | 275        |               |                      |                    |                  |                  | 
```