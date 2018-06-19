# Contracts: Treasury: Fiscal Year 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-treasury-fiscal-year-2011-4deb4) |
| Metadata | [Link](https://data.oregon.gov/api/views/6h93-vmtc) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/6h93-vmtc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/6h93-vmtc/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 6h93-vmtc |
| Name | Contracts: Treasury: Fiscal Year 2011 |
| Category | Revenue & Expense |
| Created | 2011-12-18T22:59:09Z |
| Publication Date | 2011-12-18T23:00:08Z |

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type | Render Type |
| ======== | =========== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag  | contract_description    | Contract Description    | text      | text        |
| Yes      | series tag  | contractor              | Contractor              | text      | text        |
| Yes      | time        | contract_execution_date | Contract Execution Date | date      | date        |
| No       |             | contract_end_date       | Contract End Date       | text      | text        |
| Yes      | series tag  | contract_value          | Contract Value          | text      | text        |
```

## Time Field

```ls
Value = contract_execution_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = contract_end_date
```

## Data Commands

```ls
series e:6h93-vmtc d:2011-04-01T07:00:00.000Z t:contract_description="Access to Fitch security ratings through Bloomberg" t:contract_value="Annual fee of $7,500" t:contractor="Fitch Solutions Inc" m:row_number.6h93-vmtc=1

series e:6h93-vmtc d:2011-06-01T07:00:00.000Z t:contract_description="Access to Moody's security ratings through Bloomberg" t:contract_value="Annual fee of $36,350" t:contractor="Moody's Analytics" m:row_number.6h93-vmtc=2

series e:6h93-vmtc d:2011-05-01T07:00:00.000Z t:contract_description="Access to Standard & Poor's (S&P) CUSIPs through Bloomberg" t:contract_value="Annual fee of $25,000" t:contractor="Standard & Poor's Financial Services LLC" m:row_number.6h93-vmtc=3
```

## Meta Commands

```ls
metric m:row_number.6h93-vmtc p:long l:"Row Number"

entity e:6h93-vmtc l:"Contracts: Treasury: Fiscal Year 2011" t:url=https://data.oregon.gov/api/views/6h93-vmtc

property e:6h93-vmtc t:meta.view v:id=6h93-vmtc v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: Treasury: Fiscal Year 2011"

property e:6h93-vmtc t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:6h93-vmtc t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| contract_description                                                                                                                       | contractor                               | contract_execution_date | contract_end_date | contract_value                                                     | 
| ========================================================================================================================================== | ======================================== | ======================= | ================= | ================================================================== | 
| Access to Fitch security ratings through Bloomberg                                                                                         | Fitch Solutions Inc                      | 1301641200              | 3/31/12           | Annual fee of $7,500                                               | 
| Access to Moody's security ratings through Bloomberg                                                                                       | Moody's Analytics                        | 1306911600              | 5/31/12           | Annual fee of $36,350                                              | 
| Access to Standard & Poor's (S&P) CUSIPs through Bloomberg                                                                                 | Standard & Poor's Financial Services LLC | 1304233200              | 4/30/12           | Annual fee of $25,000                                              | 
| Consulting services supporting the financial review of the Columbia River Crossing project                                                 | C&M Associates                           | 1305788400              | None specified    | $68,000                                                            | 
| Legal services regarding supplemental retirement plan                                                                                      | Hershner Hunter, LLP                     | 1279177200              | 6/30/11           | $18,000                                                            | 
| Strategic planning and management consulting services                                                                                      | John Kreft                               | 1293696000              | 6/30/11           | $31,500                                                            | 
| Professional services - Bond servicing                                                                                                     | Bank of NY Mellon                        | 1302850800              | 6/30/13           | $1,000/yr for each varible rate bond, $700/yr for fixed rate bonds | 
| Rapid SAQ, PCI-DSS compliance (payment card compliance) and optional consulting hours - this contract was transferred from DAS to Treasury | Coalfire Systems, Inc.                   | 1265961600              | 12/31/12          | $110,000                                                           | 
| Cash management application assessment                                                                                                     | On-line Business Systems                 | 1306220400              | 7/31/11           | $25,000                                                            | 
| Consulting services associated with a Request for Proposal for a new investment custodian                                                  | Corte and Associates Consulting, LLC     | 1306998000              | None specified    | $26,000                                                            | 
```