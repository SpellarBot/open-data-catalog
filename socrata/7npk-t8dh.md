# 2015 - ODOT - Construction Contracts - Fiscal Year 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-odot-construction-contracts-fiscal-year-2015) |
| Metadata | [Link](https://data.oregon.gov/api/views/7npk-t8dh) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/7npk-t8dh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/7npk-t8dh/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 7npk-t8dh |
| Name | 2015 - ODOT - Construction Contracts - Fiscal Year 2015 |
| Category | Revenue & Expense |
| Tags | 2015; odot, odot 2015, construction contracts, odot construction contracts, odot construction contracts 2015 |
| Created | 2016-01-01T06:06:18Z |
| Publication Date | 2016-01-01T06:12:07Z |

## Description

Summary of Oregon Department of Transportation construction contracts that are not in ORPIN for Fiscal Year 2015. For more information go to: http://www.oregon.gov/transparency/Pages/contracts.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| No       |                | fiscal_year      | Fiscal Year      | number        | number        |
| Yes      | series tag     | contract_id      | Contract_ID      | text          | number        |
| Yes      | series tag     | project_name     | Project_Name     | text          | text          |
| Yes      | series tag     | fed_state_number | Fed_State_Number | text          | text          |
| Yes      | time           | award_date       | Award_Date       | calendar_date | calendar_date |
| Yes      | numeric metric | contract_amount  | Contract_Amount  | money         | money         |
| Yes      | series tag     | vendor_name      | Vendor_Name      | text          | text          |
| Yes      | series tag     | addrtype         | ADDRTYPE         | text          | text          |
```

## Time Field

```ls
Value = award_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_year
```

## Data Commands

```ls
series e:7npk-t8dh d:2014-09-24T00:00:00.000Z t:addrtype=PREQ t:project_name="2014 REGION 1 CURVE WARNING SIGN PROJECT" t:fed_state_number=AC-STP-S000(873) t:contract_id=14726 t:vendor_name="CARTELLO CONSTRUCTION INC" m:contract_amount=117470

series e:7npk-t8dh d:2014-11-13T00:00:00.000Z t:addrtype=PREQ t:project_name="WYSS RD: TRASK SLOUGH BRIDGE #57C33" t:fed_state_number=STP-C057(063) t:contract_id=14748 t:vendor_name="CONCRETE ENTERPRISES INC" m:contract_amount=857922

series e:7npk-t8dh d:2015-03-11T00:00:00.000Z t:addrtype=PREQ t:project_name="OR126: CHICKAHOMINY CREEK TO POTERF CREEK" t:fed_state_number=STP-S062(039) t:contract_id=14781 t:vendor_name="EUGENE SAND CONSTRUCTION INC" m:contract_amount=1666420
```

## Meta Commands

```ls
metric m:contract_amount p:integer l:Contract_Amount t:dataTypeName=money

entity e:7npk-t8dh l:"2015 - ODOT - Construction Contracts - Fiscal Year 2015" t:url=https://data.oregon.gov/api/views/7npk-t8dh

property e:7npk-t8dh t:meta.view v:id=7npk-t8dh v:category="Revenue & Expense" v:averageRating=0 v:name="2015 - ODOT - Construction Contracts - Fiscal Year 2015"

property e:7npk-t8dh t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:7npk-t8dh t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| fiscal_year | contract_id | project_name                                      | fed_state_number | award_date          | contract_amount | vendor_name                                          | addrtype | 
| =========== | =========== | ================================================= | ================ | =================== | =============== | ==================================================== | ======== | 
| 2015        | 14726       | 2014 REGION 1 CURVE WARNING SIGN PROJECT          | AC-STP-S000(873) | 2014-09-24T00:00:00 | 117470          | CARTELLO CONSTRUCTION INC                            | PREQ     | 
| 2015        | 14748       | WYSS RD: TRASK SLOUGH BRIDGE #57C33               | STP-C057(063)    | 2014-11-13T00:00:00 | 857922          | CONCRETE ENTERPRISES INC                             | PREQ     | 
| 2015        | 14781       | OR126: CHICKAHOMINY CREEK TO POTERF CREEK         | STP-S062(039)    | 2015-03-11T00:00:00 | 1666420         | EUGENE SAND CONSTRUCTION INC                         | PREQ     | 
| 2015        | 14752       | US101: WHEELER - WILSON RIVER PROJECT             | STP-S009(413)    | 2014-11-13T00:00:00 | 5885393         | OREGON MAINLINE PAVING LLC                           | PREQ     | 
| 2015        | 14744       | REGION 1 SIGNAL UPGRADES                          | STP-S000(786)    | 2014-10-31T00:00:00 | 985484          | NORTHSTAR ELEC CONTRACTORS INCDBA NORTHSTAR ELECTRIC | PREQ     | 
| 2015        | 14793       | US97: MORO - MADRAS                               | NHPP-S004(195)   | 2015-04-23T00:00:00 | 9902700         | KERR CONTRACTORS OREGON INC DBA KERR CONTRACTORS     | PREQ     | 
| 2015        | 14798       | BROADWAY ST: WILLAMETTE R (BROADWAY) BR PAINTING  | STP-C051(101)    | 2015-03-25T00:00:00 | 6903048         | FD THOMAS INC                                        | PREQ     | 
| 2015        | 14728       | 2014 INTERSTATE SIGN REPLACEMENT PROJECT          | NHPP-S000(857)   | 2014-09-29T00:00:00 | 4952613         | WILDISH STANDARD PAVING CO                           | PREQ     | 
| 2015        | 14717       | MCKEE BR RD: APPLEGATE R (MCKEE COVERED BR) REHAB | NHCBP-C029(082)  | 2014-09-02T00:00:00 | 343434          | MOWAT CONSTRUCTION CO                                | PREQ     | 
| 2015        | 14758       | OR99W: GAARDE/MCDONALD INTERSECTION IMPRVMTS      | STP-7365(013)    | 2014-12-23T00:00:00 | 4414058         | KERR CONTRACTORS OREGON INC DBA KERR CONTRACTORS     | PREQ     | 
```