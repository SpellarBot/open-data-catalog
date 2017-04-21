# Contracts: Lottery: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-lottery-fiscal-year-2014-93fac) |
| Metadata | [Link](https://data.oregon.gov/api/views/7jv5-pfn5) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/7jv5-pfn5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/7jv5-pfn5/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 7jv5-pfn5 |
| Name | Contracts: Lottery: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | lottery contracts, lottery, oregon state lottery contracts 2014, 2014 |
| Created | 2014-12-30T06:13:58Z |
| Publication Date | 2014-12-30T06:21:04Z |

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                       | Data Type     | Render Type   |
| ======== | ============== | ========================================== | ========================================== | ============= | ============= |
| Yes      | series tag     | contract_no                                | Contract No.                               | text          | number        |
| Yes      | series tag     | amendment_no                               | Amendment No.                              | text          | text          |
| Yes      | series tag     | contract_or_amendment_description          | Contract or Amendment Description          | text          | text          |
| Yes      | series tag     | contract_type                              | Contract Type                              | text          | text          |
| Yes      | series tag     | contractorname                             | ContractorName                             | text          | text          |
| Yes      | series tag     | contractorstreet                           | ContractorStreet                           | text          | text          |
| Yes      | series tag     | contractorcity                             | ContractorCity                             | text          | text          |
| Yes      | series tag     | contractorstate                            | ContractorState                            | text          | text          |
| Yes      | series tag     | contractor_zipcode                         | Contractor Zipcode                         | text          | number        |
| Yes      | time           | contract_executed_date                     | Contract Executed Date                     | calendar_date | calendar_date |
| No       |                | contract_end_date                          | Contract End Date                          | calendar_date | calendar_date |
| Yes      | numeric metric | original_contract_amount_or_previous_value | Original Contract amount or previous value | money         | money         |
| Yes      | numeric metric | amendment_amount                           | Amendment Amount                           | money         | money         |
| Yes      | numeric metric | total_contract_amount                      | Total Contract Amount                      | money         | money         |
```

## Time Field

```ls
Value = contract_executed_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = contract_end_date
```

## Data Commands

```ls
series e:7jv5-pfn5 d:2013-08-12T00:00:00.000Z t:contract_or_amendment_description="Compressor check liebert unit" t:contract_type=SERVICES t:contractorstreet="3552 SILVERTON RD NE" t:contract_no=2864 t:contractorstate=OR t:contractorcity=SALEM t:contractorname="C J HANSEN" t:contractor_zipcode=97305 m:total_contract_amount=8000 m:original_contract_amount_or_previous_value=8000

series e:7jv5-pfn5 d:2013-08-12T00:00:00.000Z t:contract_or_amendment_description="Jackpot Games How To Play (rev 2013)" t:contract_type=GOODS t:contractorstreet="3403 W 7TH AVE" t:contract_no=2869 t:contractorstate=OR t:contractorcity=EUGENE t:contractorname="SHELTON TURNBULL PRINTERS" t:contractor_zipcode=97402 m:total_contract_amount=31000 m:original_contract_amount_or_previous_value=31000

series e:7jv5-pfn5 d:2014-04-15T00:00:00.000Z t:contract_or_amendment_description="Dispenser parts for inventory" t:contract_type=GOODS t:contractorstreet="130 NE MONTGOMERY" t:contract_no=3997 t:contractorstate=OR t:contractorcity=ALBANY t:contractorname=TAKE-A-TICKET t:contractor_zipcode=97321 m:total_contract_amount=27325 m:original_contract_amount_or_previous_value=27325
```

## Meta Commands

```ls
metric m:original_contract_amount_or_previous_value p:double l:"Original Contract amount or previous value" t:dataTypeName=money

metric m:amendment_amount p:double l:"Amendment Amount" t:dataTypeName=money

metric m:total_contract_amount p:double l:"Total Contract Amount" t:dataTypeName=money

entity e:7jv5-pfn5 l:"Contracts: Lottery: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/7jv5-pfn5

property e:7jv5-pfn5 t:meta.view v:id=7jv5-pfn5 v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: Lottery: Fiscal Year 2014"

property e:7jv5-pfn5 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:7jv5-pfn5 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| contract_no | amendment_no | contract_or_amendment_description                                                                     | contract_type | contractorname                         | contractorstreet                | contractorcity | contractorstate | contractor_zipcode | contract_executed_date | contract_end_date   | original_contract_amount_or_previous_value | amendment_amount | total_contract_amount | 
| =========== | ============ | ===================================================================================================== | ============= | ====================================== | =============================== | ============== | =============== | ================== | ====================== | =================== | ========================================== | ================ | ===================== | 
| 2864        |              | Compressor check liebert unit                                                                         | SERVICES      | C J HANSEN                             | 3552 SILVERTON RD NE            | SALEM          | OR              | 97305              | 2013-08-12T00:00:00    |                     | 8000.00                                    |                  | 8000.00               | 
| 2869        |              | Jackpot Games How To Play (rev 2013)                                                                  | GOODS         | SHELTON TURNBULL PRINTERS              | 3403 W 7TH AVE                  | EUGENE         | OR              | 97402              | 2013-08-12T00:00:00    |                     | 31000.00                                   |                  | 31000.00              | 
| 3997        |              | Dispenser parts for inventory                                                                         | GOODS         | TAKE-A-TICKET                          | 130 NE MONTGOMERY               | ALBANY         | OR              | 97321              | 2014-04-15T00:00:00    |                     | 27325.00                                   |                  | 27325.00              | 
| 111         |              | Video Central System (Addendum 22 to move b/up data center)                                           | SERVICES      | GTECH CORPORATION                      | 3925 FAIRVIEW IND DR SE, STE 10 | SALEM          | OR              | 97302              | 2014-05-08T00:00:00    | 2015-09-01T00:00:00 | 101220.00                                  |                  | 101220.00             | 
| 488         |              | Blue Tooth & Phone Holders for Vehicles                                                               | SERVICES      | CAR TOYS                               | 448 LANCASTER DR NE             | SALEM          | OR              | 97301              | 2014-01-13T00:00:00    | 2015-01-12T00:00:00 | 9600.00                                    |                  | 9600.00               | 
| 543         |              | RFSmart Software Maint Renew, MS Dynamics                                                             | SERVICES      | INFORMATION AND COMPUTING SERVICES INC | 1650 PRUDENTIAL DR STE 300      | JACKSONVILLE   | FL              | 32207              | 2014-03-25T00:00:00    | 2014-06-30T00:00:00 | 39999.00                                   |                  | 60199.00              | 
| 543         | 000543(7)    | Amendment for consulting services for quarantine workflows, RFSmart Software Maint Renew, MS Dynamics | SERVICES      | INFORMATION AND COMPUTING SERVICES INC | 1650 PRUDENTIAL DR STE 300      | JACKSONVILLE   | FL              | 32207              | 2013-10-31T00:00:00    | 2014-02-06T00:00:00 |                                            | 20200.00         |                       | 
| 591         |              | Custom Imprinted Beverage Napkins, Keno and Video Lottery (PA 591)                                    | GOODS         | SIERRA GROUP LLC                       | 1021 N. GIBSON RD               | Hayden         | ID              | 83835              | 2013-09-20T00:00:00    |                     | 118200.00                                  |                  | 118200.00             | 
| 1068        |              | Repairs to Powerball & Megabucks LEDs - add dollars for FY15                                          | SERVICES      | DAKTRONICS INC                         | 201 DAKTRONICS DR               | BROOKINGS      | SD              | 57006              | 2013-10-25T00:00:00    | 2014-10-24T00:00:00 | 10000.00                                   | 15000.00         | 25000.00              | 
| 1157        |              | Blanket PO for Printer Maintenance & Repairs                                                          | SERVICES      | DEPENDABLE PRINTER SUPPORT , INC       | PO BOX 17795                    | SALEM          | OR              | 97305              | 2013-07-01T00:00:00    | 2014-06-30T00:00:00 | 5000.00                                    | 4500.00          | 9500.00               | 
```