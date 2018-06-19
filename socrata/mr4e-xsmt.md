# Contracts: State Agency: Oregon Judicial Department: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-state-agency-oregon-judicial-department-fiscal-year-2014-6dfa8) |
| Metadata | [Link](https://data.oregon.gov/api/views/mr4e-xsmt) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/mr4e-xsmt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/mr4e-xsmt/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | mr4e-xsmt |
| Name | Contracts: State Agency: Oregon Judicial Department: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | contracts, oregon judicial contracts, oregon judicial 2014, 2014 |
| Created | 2014-12-30T08:30:29Z |
| Publication Date | 2014-12-30T08:45:55Z |

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type     | Render Type   |
| ======== | ============== | ==================================== | ==================================== | ============= | ============= |
| Yes      | series tag     | award_number                         | Award Number                         | text          | text          |
| Yes      | series tag     | award_title                          | Award Title                          | text          | text          |
| Yes      | series tag     | award_type                           | Award Type                           | text          | text          |
| Yes      | series tag     | company_name                         | Company Name                         | text          | text          |
| No       |                | company_address                      | Company Address                      | text          | text          |
| Yes      | series tag     | zip_code                             | Zip Code                             | text          | number        |
| Yes      | series tag     | company_phone                        | Company Phone                        | text          | text          |
| Yes      | time           | contract_effective_date              | Contract Effective Date              | calendar_date | calendar_date |
| No       |                | contract_expiration_date             | Contract Expiration Date             | calendar_date | calendar_date |
| Yes      | numeric metric | original_contract_value              | Original Contract Value              | money         | money         |
| Yes      | numeric metric | total_amendment_value                | Total Amendment Value                | number        | number        |
| Yes      | numeric metric | total_contract_value_with_amendments | Total Contract Value With Amendments | money         | money         |
```

## Time Field

```ls
Value = contract_effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = company_address,contract_expiration_date
```

## Data Commands

```ls
series e:mr4e-xsmt d:2013-12-02T00:00:00.000Z t:award_number=5807 t:company_name="AVS Elevators" t:award_type=PO t:award_title="Misc - Repair large elevator" m:original_contract_value=14100

series e:mr4e-xsmt d:2014-02-19T00:00:00.000Z t:award_number=5932 t:zip_code=78682 t:company_name=Dell t:company_phone=800-274-0696 t:award_type=PO t:award_title="Hardware - (44) Optiplex 7010 SFF, no monitors, Ship to ETSD" m:original_contract_value=41040.12

series e:mr4e-xsmt d:2014-02-19T00:00:00.000Z t:award_number=5933 t:zip_code=78682 t:company_name=Dell t:company_phone=800-274-0696 t:award_type=PO t:award_title="Hardware - (111) Optiplex 7010 SFF, one 23"" monitor and one 19"" monitor each. Ship to MUL" m:original_contract_value=141770.31
```

## Meta Commands

```ls
metric m:original_contract_value p:double l:"Original Contract Value" t:dataTypeName=money

metric m:total_amendment_value p:float l:"Total Amendment Value" t:dataTypeName=number

metric m:total_contract_value_with_amendments p:double l:"Total Contract Value With Amendments" t:dataTypeName=money

entity e:mr4e-xsmt l:"Contracts: State Agency: Oregon Judicial Department: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/mr4e-xsmt

property e:mr4e-xsmt t:meta.view v:id=mr4e-xsmt v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: State Agency: Oregon Judicial Department: Fiscal Year 2014"

property e:mr4e-xsmt t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:mr4e-xsmt t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| award_number | award_title                                                                                   | award_type | company_name                        | company_address               | zip_code | company_phone | contract_effective_date | contract_expiration_date | original_contract_value | total_amendment_value | total_contract_value_with_amendments | 
| ============ | ============================================================================================= | ========== | =================================== | ============================= | ======== | ============= | ======================= | ======================== | ======================= | ===================== | ==================================== | 
| 5807         | Misc - Repair large elevator                                                                  | PO         | AVS Elevators                       |                               |          |               | 2013-12-02T00:00:00     | 2014-02-10T00:00:00      | 14100.00                |                       |                                      | 
| 5932         | Hardware - (44) Optiplex 7010 SFF, no monitors, Ship to ETSD                                  | PO         | Dell                                | One Dell Way                  | 78682    | 800-274-0696  | 2014-02-19T00:00:00     | 2014-04-11T00:00:00      | 41040.12                |                       |                                      | 
| 5933         | Hardware - (111) Optiplex 7010 SFF, one 23" monitor and one 19" monitor each. Ship to MUL     | PO         | Dell                                | One Dell Way                  | 78682    | 800-274-0696  | 2014-02-19T00:00:00     | 2014-03-03T00:00:00      | 141770.31               |                       |                                      | 
| 5950         | Maintenance - extended warranty on (4) servers                                                | PO         | Dell                                | One Dell Way                  | 78682    | 800-274-0696  | 2014-06-15T00:00:00     | 2018-06-14T00:00:00      | 10074.58                |                       |                                      | 
| 5953         | Hardware - (108) Limbo monitor stands                                                         | PO         | ErgoMart                            |                               |          |               | 2014-02-26T00:00:00     | 2014-03-06T00:00:00      | 8051.24                 |                       |                                      | 
| 6134         | Hardware - (18) 7010 USFF                                                                     | PO         | Dell                                | One Dell Way                  | 78682    | 800-274-0696  | 2014-05-08T00:00:00     | 2014-05-16T00:00:00      | 17065.44                |                       |                                      | 
| 5727D        | Maintenance - Extended Services for Power Edge R710 (3 Service Tags - See Comments) - JACKSON | PO         | Dell                                | One Dell Way                  | 78682    | 800-274-0696  | 2013-10-06T00:00:00     | 2016-10-06T00:00:00      | 9063.32                 |                       |                                      | 
| 140425       | Telecommunications Systems Management and Services                                            | IGA        | Lane Council of Governments         | 859 Willamette St., Suite 500 |          | 541-682-4283  | 2013-07-01T00:00:00     | 2014-06-30T00:00:00      | 16205.00                |                       |                                      | 
| 6232M        | Misc -14 Chairs                                                                               | PO         | RFM (Commercial Business Furniture) | 619 SW Wood St.               | 97123    |               | 2014-06-09T00:00:00     | 2014-06-27T00:00:00      | 7444.44                 |                       |                                      | 
| 5500D        | LEASE - Ricoh MPC5502 Copier - S/N: C86027666; MP6002 - S/N: C86025822 - JOSEPHINE            | PO         | Ricoh Americas Corp.                | P.O. Box 100345               | 91189    | 503-315-7627  | 2013-08-21T00:00:00     | 2017-08-30T00:00:00      | 23825.28                |                       |                                      | 
```