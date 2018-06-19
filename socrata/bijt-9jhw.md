# Contracts: State Agency: Oregon Judicial Department: Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-state-agency-oregon-judicial-department-fiscal-year-2012-eedaa) |
| Metadata | [Link](https://data.oregon.gov/api/views/bijt-9jhw) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/bijt-9jhw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/bijt-9jhw/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | bijt-9jhw |
| Name | Contracts: State Agency: Oregon Judicial Department: Fiscal Year 2012 |
| Category | Revenue & Expense |
| Created | 2012-12-06T00:42:59Z |
| Publication Date | 2012-12-18T16:12:05Z |

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type | Render Type |
| ======== | ============== | ==================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | agency_number                        | Agency Number                        | text      | text        |
| Yes      | series tag     | agency_name                          | Agency Name                          | text      | text        |
| Yes      | series tag     | award_number                         | Award Number                         | text      | text        |
| Yes      | series tag     | award_title                          | Award Title                          | text      | text        |
| Yes      | series tag     | award_type                           | *Award Type                          | text      | text        |
| Yes      | series tag     | company_name                         | Company Name                         | text      | text        |
| No       |                | company_address                      | Company Address                      | text      | text        |
| Yes      | series tag     | company_phone                        | Company Phone                        | text      | text        |
| Yes      | time           | contract_effective_date              | Contract Effective Date              | text      | text        |
| No       |                | contract_expiration_date             | Contract Expiration Date             | text      | text        |
| Yes      | numeric metric | original_contract_value              | Original Contract Value              | money     | money       |
| Yes      | numeric metric | total_amendment_value                | Total Amendment Value                | money     | money       |
| Yes      | numeric metric | total_contract_value_with_amendments | Total Contract Value with amendments | money     | money       |
```

## Time Field

```ls
Value = contract_effective_date
Format & Zone = MM/dd/yy
```

## Series Fields

```ls
Excluded Fields = company_address,contract_expiration_date
```

## Data Commands

```ls
series e:bijt-9jhw d:2011-07-01T00:00:00.000Z t:award_number=110240 t:company_name="Oregon State Police" t:company_phone=503-986-1122 t:award_type=IAA t:award_title="Provide Security for Supreme Court & Justice Buildings" t:agency_number=19800 t:agency_name="Oregon Judicial Department" m:total_contract_value_with_amendments=294302.52 m:total_amendment_value=0 m:original_contract_value=294302.52

series e:bijt-9jhw d:2011-07-01T00:00:00.000Z t:award_number=110241 t:company_name="Oregon State Police" t:company_phone=503-378-4217 t:award_type=IAA t:award_title="Dignitary Protection Services for the Chief Justice" t:agency_number=19800 t:agency_name="Oregon Judicial Department" m:total_contract_value_with_amendments=216876 m:total_amendment_value=0 m:original_contract_value=216876

series e:bijt-9jhw d:2011-07-01T00:00:00.000Z t:award_number=110245 t:company_name="Lane Council of Governments (LCOG)" t:company_phone=541-682-4283 t:award_type=IGA t:award_title="Telecommunications Systems Management and Services" t:agency_number=19800 t:agency_name="Oregon Judicial Department" m:total_contract_value_with_amendments=15115 m:total_amendment_value=0 m:original_contract_value=15115
```

## Meta Commands

```ls
metric m:original_contract_value p:double l:"Original Contract Value" t:dataTypeName=money

metric m:total_amendment_value p:double l:"Total Amendment Value" t:dataTypeName=money

metric m:total_contract_value_with_amendments p:double l:"Total Contract Value with amendments" t:dataTypeName=money

entity e:bijt-9jhw l:"Contracts: State Agency: Oregon Judicial Department: Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/bijt-9jhw

property e:bijt-9jhw t:meta.view v:id=bijt-9jhw v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: State Agency: Oregon Judicial Department: Fiscal Year 2012"

property e:bijt-9jhw t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:bijt-9jhw t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_number | agency_name                | award_number | award_title                                            | award_type  | company_name                          | company_address                                   | company_phone | contract_effective_date | contract_expiration_date | original_contract_value | total_amendment_value | total_contract_value_with_amendments | 
| ============= | ========================== | ============ | ====================================================== | =========== | ===================================== | ================================================= | ============= | ======================= | ======================== | ======================= | ===================== | ==================================== | 
| 19800         | Oregon Judicial Department | 110240       | Provide Security for Supreme Court & Justice Buildings | IAA         | Oregon State Police                   | 900 Court St NE, Rm. 60C, Salem, OR 97301         | 503-986-1122  | 7/1/11                  | 06/30/13                 | 294302.52               | 0.00                  | 294302.52                            | 
| 19800         | Oregon Judicial Department | 110241       | Dignitary Protection Services for the Chief Justice    | IAA         | Oregon State Police                   | 3784 Portland Rd NE, Salem, OR 97301              | 503-378-4217  | 7/1/11                  | 06/30/13                 | 216876.00               | 0.00                  | 216876.00                            | 
| 19800         | Oregon Judicial Department | 110245       | Telecommunications Systems Management and Services     | IGA         | Lane Council of Governments (LCOG)    | 99 E. Broadway, Suite 400 Eugene, OR 97402        | 541-682-4283  | 7/1/11                  | 06/30/12                 | 15115.00                | 0.00                  | 15115.00                             | 
| 19800         | Oregon Judicial Department | 110248       | Subscription Plan Amendment Patron Access - Larson's   | SUB         | LexisNexis                            | 6601 Park of Commerce Blvd., Boca Raton, FL 33487 | 888-285-3947  | 7/1/11                  | 06/30/14                 | 7092.00                 | 0.00                  | 7092.00                              | 
| 19800         | Oregon Judicial Department | 110249       | Subscription Plan Amendment Patron Access - Tax Center | SUB         | LexisNexis                            | 6601 Park of Commerce Blvd., Boca Raton, FL 33487 | 888-285-3947  | 7/1/11                  | 06/30/14                 | 79200.00                | 0.00                  | 79200.00                             | 
| 19800         | Oregon Judicial Department | 110250       | Develop and Maintain OJD Revenue Forecasting Models    | IAA         | DAS Office of Economic Analysis (OEA) | 155 Cottage St. NE, U20, Salem, OR 97301          | 503-378-3405  | 7/1/11                  | 06/30/13                 | 20000.00                | 0.00                  | 20000.00                             | 
| 19800         | Oregon Judicial Department | 110253       | DOJ Share of Costs for Security Services               | IAA         | Department of Justice                 | 1162 Court St NE, Salem, OR 97301                 | 503-373-1323  | 7/1/11                  | 06/30/13                 | 73575.63                | 0.00                  | 73575.63                             | 
| 19800         | Oregon Judicial Department | 110254       | MS Project and MS Project Server Consulting Services   | PSK         | Advisicon, Inc.                       | 5411 NE 107th Ave., #200, Vancouver, WA 98662     | 866-632-3847  | 7/1/11                  | 09/30/11                 | 5000.00                 | 0.00                  | 5000.00                              | 
| 19800         | Oregon Judicial Department | 120263       | Region 5 Statewide Court Security Systems Upgrades     | Public Imp. | Huser integrated Technologies         | 1313 NW 17th Ave., Portland, OR 97209             | 503-227-6688  | 8/30/11                 | 01/31/12                 | 333632.79               | 52619.87              | 386252.76                            | 
| 19800         | Oregon Judicial Department | 120264       | Grant funds .5 FTE Adult Drug Court Coordinator        | SGA         | Linn County                           | P.O .Box 100, Albany, OR 97321                    | 541-967-3819  | 7/1/11                  | 09/30/11                 | 10699.00                | 0.00                  |                                      | 
```