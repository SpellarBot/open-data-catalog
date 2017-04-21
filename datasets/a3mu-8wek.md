# Construction Contracts: ODOT: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/construction-contracts-odot-fiscal-year-2014-be67c) |
| Metadata | [Link](https://data.oregon.gov/api/views/a3mu-8wek) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/a3mu-8wek/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/a3mu-8wek/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | a3mu-8wek |
| Name | Construction Contracts: ODOT: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | odot, odot 2014, construction contracts, odot construction contracts, odot construction contracts 2014, 2014 |
| Created | 2014-12-30T15:44:17Z |
| Publication Date | 2014-12-30T15:51:14Z |

## Description

Summary of Oregon Department of Transportation construction contracts that are not in ORPIN for Fiscal Year 2014.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | series tag     | contract_id      | Contract_ID      | text          | number        |
| Yes      | series tag     | project_name     | Project_Name     | text          | text          |
| Yes      | series tag     | fed_state_number | Fed_State_Number | text          | text          |
| Yes      | time           | award_date       | Award_Date       | calendar_date | calendar_date |
| Yes      | series tag     | vendor_name      | Vendor_Name      | text          | text          |
| Yes      | numeric metric | contract_amount  | Contract_Amount  | money         | money         |
| Yes      | series tag     | addrtype         | ADDRTYPE         | text          | text          |
```

## Time Field

```ls
Value = award_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:a3mu-8wek d:2014-04-04T00:00:00.000Z t:project_name="ALBANY MULTIMODAL TRANSIT STATION PATH" t:fed_state_number=HPP-0100(029) t:contract_id=14666 t:vendor_name="HP CIVIL INC" m:contract_amount=383692

series e:a3mu-8wek d:2014-02-05T00:00:00.000Z t:addrtype=PREQ t:project_name="REGION 2 CURVE WARNING SIGN UPGRADES" t:fed_state_number=STP-S000(835) t:contract_id=14652 t:vendor_name="GAGE IT CONSTRUCTION LLC" m:contract_amount=166017

series e:a3mu-8wek d:2013-11-19T00:00:00.000Z t:addrtype=PREQ t:project_name="I-5: REGION 3 BARRIER AND GUARDRAIL UPGRADES" t:fed_state_number=NHPP-S001(448) t:contract_id=14625 t:vendor_name="WILDISH STANDARD PAVING CO" m:contract_amount=7869793
```

## Meta Commands

```ls
metric m:contract_amount p:integer l:Contract_Amount t:dataTypeName=money

entity e:a3mu-8wek l:"Construction Contracts: ODOT: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/a3mu-8wek

property e:a3mu-8wek t:meta.view v:id=a3mu-8wek v:category="Revenue & Expense" v:averageRating=0 v:name="Construction Contracts: ODOT: Fiscal Year 2014"

property e:a3mu-8wek t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:a3mu-8wek t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| contract_id | project_name                                   | fed_state_number | award_date          | vendor_name                                      | contract_amount | addrtype | 
| =========== | ============================================== | ================ | =================== | ================================================ | =============== | ======== | 
| 14666       | ALBANY MULTIMODAL TRANSIT STATION PATH         | HPP-0100(029)    | 2014-04-04T00:00:00 | HP CIVIL INC                                     | 383692          |          | 
| 14652       | REGION 2 CURVE WARNING SIGN UPGRADES           | STP-S000(835)    | 2014-02-05T00:00:00 | GAGE IT CONSTRUCTION LLC                         | 166017          | PREQ     | 
| 14625       | I-5: REGION 3 BARRIER AND GUARDRAIL UPGRADES   | NHPP-S001(448)   | 2013-11-19T00:00:00 | WILDISH STANDARD PAVING CO                       | 7869793         | PREQ     | 
| 14645       | BRIDGE OF THE GODS (CASCADE LOCKS)             | STP-C009(043)    | 2013-10-25T00:00:00 | WILDISH STANDARD PAVING CO                       | 581056          | PREQ     | 
| 14655       | MIM HUNTINGTON TO FAREWELL BEND                | NHPP-S002(148)   | 2014-02-10T00:00:00 | KERR CONTRACTORS OREGON INC DBA KERR CONTRACTORS | 625500          | PREQ     | 
| 14672       | US20 CHIP SEAL                                 | STP-S007(069)    | 2014-04-01T00:00:00 | KNIFE RIVER CORPORATION - NORTHWEST              | 2566865         | PREQ     | 
| 14614       | US101: CAPE CREEK BRIDGE RAIL RETROFIT         | STP-S009(404)    | 2013-10-03T00:00:00 | HAMILTON CONSTRUCTION CO                         | 2162582         | PREQ     | 
| 14679       | OR99W: SW DURHAM RD - SW FISCHER RD SEC        | HSIP-S091(069)   | 2014-04-15T00:00:00 | KERR CONTRACTORS OREGON INC DBA KERR CONTRACTORS | 1317537         | PREQ     | 
| 14631       | US101: HUNTER CREEK BRIDGE CATHODIC PROTECTION | STP-S009(397)    | 2013-11-18T00:00:00 | MOWAT CONSTRUCTION CO                            | 2930661         | PREQ     | 
| 14698       | YAQUINA RIVER (CHITWOOD) COVERED BRIDGE        | NHCBP-C041(023)  | 2014-06-05T00:00:00 | LEGACY CONTRACTING INC                           | 741345          | PREQ     | 
```