# Contracts: Treasury: Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-treasury-fiscal-year-2012-27f72) |
| Metadata | [Link](https://data.oregon.gov/api/views/vpzu-i3hc) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/vpzu-i3hc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/vpzu-i3hc/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | vpzu-i3hc |
| Name | Contracts: Treasury: Fiscal Year 2012 |
| Category | Revenue & Expense |
| Created | 2012-12-18T16:40:40Z |
| Publication Date | 2012-12-18T16:42:04Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | contract_description    | Contract Description    | text      | text        |
| Yes      | series tag     | contractor              | Contractor              | text      | text        |
| No       |                | contract_execution_date | Contract Execution Date | text      | text        |
| No       |                | contract_end_date       | Contract End Date       | text      | text        |
| Yes      | numeric metric | contract_value          | Contract Value          | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = contract_execution_date,contract_end_date
```

## Data Commands

```ls
series e:vpzu-i3hc d:2012-01-01T00:00:00.000Z t:contract_description="West Coast Infrastructure Project Strategic Planning (funded through a grant from the Rockefeller Foundation)" t:contractor="CH2M Hill" m:contract_value=90000

series e:vpzu-i3hc d:2012-01-01T00:00:00.000Z t:contract_description="Executive recruitment service for the position of Chief Investment Officer" t:contractor="EFL Associates" m:contract_value=180000

series e:vpzu-i3hc d:2012-01-01T00:00:00.000Z t:contract_description="Consulting services related to investment risk management activities" t:contractor="Hewit Ennisknupp" m:contract_value=65000
```

## Meta Commands

```ls
metric m:contract_value p:integer l:"Contract Value" t:dataTypeName=money

entity e:vpzu-i3hc l:"Contracts: Treasury: Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/vpzu-i3hc

property e:vpzu-i3hc t:meta.view v:id=vpzu-i3hc v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: Treasury: Fiscal Year 2012"

property e:vpzu-i3hc t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:vpzu-i3hc t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| contract_description                                                                                                                        | contractor                | contract_execution_date | contract_end_date | contract_value | 
| =========================================================================================================================================== | ========================= | ======================= | ================= | ============== | 
| West Coast Infrastructure Project Strategic Planning (funded through a grant from the Rockefeller Foundation)                               | CH2M Hill                 | 5/21/12                 | 12/31/12          | 90000          | 
| Executive recruitment service for the position of Chief Investment Officer                                                                  | EFL Associates            | 5/7/12                  | 12/31/12          | 180000         | 
| Consulting services related to investment risk management activities                                                                        | Hewit Ennisknupp          | 12/16/11                | 10/15/12          | 65000          | 
| Consulting services for capital projects - joint project of the Department of Administrative Services and Treasury Debt Management Division | Carol Ann Kirby           | 10/24/11                | 12/31/12          | 15000          | 
| Network penetration testing                                                                                                                 | Netragard                 | 6/6/12                  | 12/31/12          | 59007          | 
| Redesign of the Oregon State Treasury website                                                                                               | NicUSA                    | 3/7/12                  | 12/31/12          | 33500          | 
| Consulting services assessing Treasury's information security program policies and controls                                                 | SecuraStar                | 6/4/12                  | 12/31/12          | 20700          | 
| Retirement Governance Plan                                                                                                                  | Cortex Applied Research   | 10/7/11                 | 7/15/12           | 45000          | 
| Review OST operational risks processes & Controls                                                                                           | Cutter Associates         | 10/7/11                 | 4/15/12           | 90200          | 
| Operational and Governance Review of OST Investment Division                                                                                | Funston Advisory Services | 12/15/11                | 1/1/12            | 150000         | 
```