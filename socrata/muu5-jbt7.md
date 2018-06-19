# spendingMontgomery Glossary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/spendingmontgomery-glossary-48fa5) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/muu5-jbt7) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/muu5-jbt7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/muu5-jbt7/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | muu5-jbt7 |
| Name | spendingMontgomery Glossary |
| Category | Finance/Tax/Property |
| Tags | spendingmontgomery, hover |
| Created | 2014-09-24T12:48:59Z |
| Publication Date | 2014-12-11T13:49:58Z |

## Description

County spending glossary (definitions of financial terms) on dataMontgomery. These definitions appear when a user hovers over this term in spendingMontgomery.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | term        | Term        | text      | text        |
| Yes      | series tag  | type        | Term Type   | text      | text        |
| Yes      | series tag  | description | Description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:muu5-jbt7 d:2014-11-07T12:52:22.000Z t:term=Advertising t:description="Payments for advertising  jobs, contracts, marketing and sales, and sponsorships" t:type=expense_category m:row_number.muu5-jbt7=1

series e:muu5-jbt7 d:2014-11-07T12:52:22.000Z t:term="Amortization Exp - Non Approp - Acct Use" t:description="An accounting term indicating that a non-budget cost is spread over time." t:type=expense_category m:row_number.muu5-jbt7=2

series e:muu5-jbt7 d:2014-11-07T12:52:22.000Z t:term="Annuities Paid" t:description="A payment made by the County at specified intervals  (e.g. monthly pension income received by a retiree)" t:type=expense_category m:row_number.muu5-jbt7=3
```

## Meta Commands

```ls
metric m:row_number.muu5-jbt7 p:long l:"Row Number"

entity e:muu5-jbt7 l:"spendingMontgomery Glossary" t:url=https://data.montgomerycountymd.gov/api/views/muu5-jbt7

property e:muu5-jbt7 t:meta.view v:id=muu5-jbt7 v:category=Finance/Tax/Property v:averageRating=0 v:name="spendingMontgomery Glossary"

property e:muu5-jbt7 t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:muu5-jbt7 t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| :updated_at | term                                     | type             | description                                                                                                                                         | 
| =========== | ======================================== | ================ | =================================================================================================================================================== | 
| 1415364742  | Advertising                              | expense_category | Payments for advertising jobs, contracts, marketing and sales, and sponsorships                                                                     | 
| 1415364742  | Amortization Exp - Non Approp - Acct Use | expense_category | An accounting term indicating that a non-budget cost is spread over time.                                                                           | 
| 1415364742  | Annuities Paid                           | expense_category | A payment made by the County at specified intervals (e.g. monthly pension income received by a retiree)                                             | 
| 1415364742  | Automation Equipment (Over $10,000)      | expense_category | Purchase of an electronic or mechanical device with a cost over $10,000 (e.g. computer software)                                                    | 
| 1415364742  | Autos and Other Vehicles (Over $10,000)  | expense_category | Purchase of automobiles and other vehicles with a cost over $10,000 (e.g. fire engine)                                                              | 
| 1415364742  | Boards/Committees/Commissions            | expense_category | Necessary expenses to conduct official County business (e.g. meeting room rentals and travel reimbursement)                                         | 
| 1415364742  | Books/Videos/Subscriptions               | expense_category | Costs for books, videos, and subscriptions to magazines, periodicals, newspapers, and professional journals                                         | 
| 1415364742  | Buildings                                | expense_category | Building Acquisition/Construction Costs--e.g., Purchase, Improvements, survey and assessments, etc                                                  | 
| 1415364742  | Charges from Others                      | expense_category | Payments made by County departments for services provided by other departments or agencies (e.g. maintenance by the Department of General Services) | 
| 1415364742  | Charges to Others                        | expense_category | Charges from other departments for services, such as the Department of Technology charges the various departments for software cost.                | 
```