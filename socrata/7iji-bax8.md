# Contracts: Lottery: As of June 30, 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-lottery-as-of-june-30-2010-40efe) |
| Metadata | [Link](https://data.oregon.gov/api/views/7iji-bax8) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/7iji-bax8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/7iji-bax8/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 7iji-bax8 |
| Name | Contracts: Lottery: As of June 30, 2010 |
| Category | Revenue & Expense |
| Created | 2011-02-11T20:40:00Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag     | agency_number        | Agency Number        | text          | text          |
| Yes      | series tag     | agency_name          | Agency Name          | text          | text          |
| Yes      | series tag     | contract_description | Contract Description | text          | text          |
| Yes      | series tag     | contractor           | Contractor           | text          | text          |
| Yes      | time           | date_executed        | Date Executed        | calendar_date | calendar_date |
| Yes      | numeric metric | contract_value       | Contract Value       | money         | money         |
```

## Time Field

```ls
Value = date_executed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:7iji-bax8 d:2009-07-16T00:00:00.000Z t:contract_description="Three-year Contract for Lottery's interior identification signage located at retailer establishments throughout the State." t:contractor="Carmanah              Signs" t:agency_number=177000 t:agency_name="Oregon State Lottery" m:contract_value=70000

series e:7iji-bax8 d:2009-10-15T00:00:00.000Z t:contract_description="Contract renewal for Powerball Jackpot outdoor bulletin space located at I-84 & Halsey for a 5-year period." t:contractor="Meadow               Outdoor" t:agency_number=177000 t:agency_name="Oregon State Lottery" m:contract_value=549960

series e:7iji-bax8 d:2009-07-01T00:00:00.000Z t:contract_description="One year Contract for the purchase of Lottery's Keno napkins." t:contractor="Sierra Group" t:agency_number=177000 t:agency_name="Oregon State Lottery" m:contract_value=97000
```

## Meta Commands

```ls
metric m:contract_value p:integer l:"Contract Value" t:dataTypeName=money

entity e:7iji-bax8 l:"Contracts: Lottery: As of June 30, 2010" t:url=https://data.oregon.gov/api/views/7iji-bax8

property e:7iji-bax8 t:meta.view v:id=7iji-bax8 v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: Lottery: As of June 30, 2010"

property e:7iji-bax8 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:7iji-bax8 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_number | agency_name          | contract_description                                                                                                                         | contractor          | date_executed       | contract_value | 
| ============= | ==================== | ============================================================================================================================================ | =================== | =================== | ============== | 
| 177000        | Oregon State Lottery | Three-year Contract for Lottery's interior identification signage located at retailer establishments throughout the State.                   | Carmanah Signs      | 2009-07-16T00:00:00 | 70000          | 
| 177000        | Oregon State Lottery | Contract renewal for Powerball Jackpot outdoor bulletin space located at I-84 & Halsey for a 5-year period.                                  | Meadow Outdoor      | 2009-10-15T00:00:00 | 549960         | 
| 177000        | Oregon State Lottery | One year Contract for the purchase of Lottery's Keno napkins.                                                                                | Sierra Group        | 2009-07-01T00:00:00 | 97000          | 
| 177000        | Oregon State Lottery | Amendment to current Contract to add Anti-Fraud module license, including 1 year maintenance and support.                                    | ESI Integrity       | 2009-07-09T00:00:00 | 58000          | 
| 177000        | Oregon State Lottery | Purchase of additional TeamSite software licenses including 1 year maintenance and support.                                                  | Autonomy Interwoven | 2009-07-09T00:00:00 | 65844          | 
| 177000        | Oregon State Lottery | Contract renewal for monthly co-location charges for Lottery network equipment space and connectivity at Qwest Bend Central office for FY10. | Qwest               | 2009-07-27T00:00:00 | 26152          | 
| 177000        | Oregon State Lottery | Use of a State of Oregon Price Agreement for renewal of annual Novell software maintenance and support.                                      | Nova Coast          | 2009-07-28T00:00:00 | 40556          | 
| 177000        | Oregon State Lottery | Amendment to extend current Contract for sign and dispenser installation, removal and repair services throughout the State.                  | Peterson Electric   | 2009-07-28T00:00:00 | 100000         | 
| 177000        | Oregon State Lottery | Use of State Price Agreement for renewal of Cisco Smartnet hardware, software annual maintenance and support for Lottery network equipment.  | Qwest               | 2009-08-05T00:00:00 | 168728         | 
| 177000        | Oregon State Lottery | Purchase of Holiday 2009 display boxes and pillow envelopes to support Scratch-itsm ticket gift giving.                                      | Dynagraphics        | 2009-08-05T00:00:00 | 40171          | 
```