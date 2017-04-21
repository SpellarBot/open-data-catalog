# Contracts: State Agency: Oregon Judicial Department: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-state-agency-oregon-judicial-department-fiscal-year-2013-fad6a) |
| Metadata | [Link](https://data.oregon.gov/api/views/dntw-yh5t) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/dntw-yh5t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/dntw-yh5t/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | dntw-yh5t |
| Name | Contracts: State Agency: Oregon Judicial Department: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | contracts, oregon judicial contracts, oregon judicial |
| Created | 2013-11-06T21:49:35Z |
| Publication Date | 2013-11-06T21:53:23Z |

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type     | Render Type   |
| ======== | ============== | ==================================== | ==================================== | ============= | ============= |
| Yes      | series tag     | award_number                         | Award Number                         | text          | text          |
| Yes      | series tag     | award_title                          | Award Title                          | text          | text          |
| Yes      | series tag     | award_type                           | *Award Type                          | text          | text          |
| Yes      | series tag     | company_name                         | Company Name                         | text          | text          |
| No       |                | company_address                      | Company Address                      | text          | text          |
| Yes      | series tag     | zip_code                             | Zip Code                             | text          | number        |
| Yes      | series tag     | company_phone                        | Company Phone                        | text          | text          |
| Yes      | time           | contract_effective_date              | Contract Effective Date              | calendar_date | calendar_date |
| No       |                | contract_expiration_date             | Contract Expiration Date             | calendar_date | calendar_date |
| Yes      | numeric metric | original_contract_value              | Original Contract Value              | number        | number        |
| Yes      | numeric metric | total_amendment_value                | Total Amendment Value                | number        | number        |
| Yes      | numeric metric | total_contract_value_with_amendments | Total Contract Value With Amendments | number        | number        |
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
series e:dntw-yh5t d:2013-04-25T00:00:00.000Z t:award_number=5279M t:zip_code=78682 t:company_name=Dell t:company_phone=512-725-0190 t:award_type=PO t:award_title="Hardware - 23 x Optiplex 7010 SFF" m:total_contract_value_with_amendments=21804 m:original_contract_value=21804

series e:dntw-yh5t d:2013-06-20T00:00:00.000Z t:award_number=5546 t:zip_code=8873 t:company_name="Software House International (SHI)" t:company_phone=800-477-6479 t:award_type=PO t:award_title="Maintenance - SPSS Collaboration and Deployment" m:total_contract_value_with_amendments=13601.85 m:original_contract_value=13601.85

series e:dntw-yh5t d:2012-12-18T00:00:00.000Z t:award_number=4940M t:zip_code=7006 t:company_name="Ricoh Americas Corporation" t:company_phone=503-315-7627 t:award_type=PO t:award_title="Lease - Aficio MP5002SP copier 48 mos.@ $219.85" m:total_contract_value_with_amendments=10552.8 m:original_contract_value=10552.8
```

## Meta Commands

```ls
metric m:original_contract_value p:double l:"Original Contract Value" t:dataTypeName=number

metric m:total_amendment_value p:float l:"Total Amendment Value" t:dataTypeName=number

metric m:total_contract_value_with_amendments p:double l:"Total Contract Value With Amendments" t:dataTypeName=number

entity e:dntw-yh5t l:"Contracts: State Agency: Oregon Judicial Department: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/dntw-yh5t

property e:dntw-yh5t t:meta.view v:id=dntw-yh5t v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: State Agency: Oregon Judicial Department: Fiscal Year 2013"

property e:dntw-yh5t t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:dntw-yh5t t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| award_number | award_title                                          | award_type | company_name                       | company_address                 | zip_code | company_phone | contract_effective_date | contract_expiration_date | original_contract_value | total_amendment_value | total_contract_value_with_amendments | 
| ============ | ==================================================== | ========== | ================================== | =============================== | ======== | ============= | ======================= | ======================== | ======================= | ===================== | ==================================== | 
| 5279M        | Hardware - 23 x Optiplex 7010 SFF                    | PO         | Dell                               | One Dell Way                    | 78682    | 512-725-0190  | 2013-04-25T00:00:00     | 2013-05-14T00:00:00      | 21804.00                |                       | 21804.00                             | 
| 5546         | Maintenance - SPSS Collaboration and Deployment      | PO         | Software House International (SHI) | 290 Davidson Ave.               | 8873     | 800-477-6479  | 2013-06-20T00:00:00     | 2013-06-26T00:00:00      | 13601.85                |                       | 13601.85                             | 
| 4940M        | Lease - Aficio MP5002SP copier 48 mos.@ $219.85      | PO         | Ricoh Americas Corporation         | #5 Dedrick Place                | 7006     | 503-315-7627  | 2012-12-18T00:00:00     | 2013-01-10T00:00:00      | 10552.80                |                       | 10552.80                             | 
| 5108         | Lease - Richoh MP5002SP - $219.85/mo.                | PO         | Ricoh Americas Corporation         | #5 Dedrick Place                | 7006     | 503-315-7627  | 2013-03-04T00:00:00     | 2013-03-22T00:00:00      | 10552.80                |                       | 10552.80                             | 
| 120356       | Court Interpreter Exam Rating Services               | PSK        | National Center for State Courts   | 707 Seventeenth St., Suite 2900 | 80202    | 303-293-3063  | 2012-11-01T00:00:00     | 2015-10-31T00:00:00      | 65500.00                |                       | 65500.00                             | 
| 4843         | Hardware - Cisco 48 Port 10/100/1000                 | PO         | CDWG                               | 230 N. Milwaukee Ave.           | 60061    | 800-594-4239  | 2012-10-25T00:00:00     | 2012-11-01T00:00:00      | 6180.50                 |                       | 6180.50                              | 
| 5306         | Maintenance - renew McAfee, coterming for Ent.       | PO         | Dell||ASAP                         | 850 Asbury Drive                | 60089    | 800-883-7213  | 2013-05-02T00:00:00     | 2013-05-08T00:00:00      | 150547.57               |                       | 150547.57                            | 
| 4884         | Hardware - equipment for courtroom audio upgrade     | PO         | Compview                           | 10035 SW Artic Dr.              | 97005    | 877-297-2079  | 2012-11-16T00:00:00     | 2012-12-11T00:00:00      | 12869.57                |                       | 12869.57                             | 
| 4957         | Misc - install audio upgrades for courtroom 303 &404 | PO         | TruEdge Communications             | 1224 NE Walnut St., PMB 249     | 97470    | 541-580-2445  | 2013-01-08T00:00:00     | 2013-03-01T00:00:00      | 9974.92                 |                       | 9974.92                              | 
| 4977         | Hardware - (90) P1913S monitors w/stands             | PO         | Dell                               | One Dell Way                    | 78682    | 512-725-0190  | 2013-01-14T00:00:00     | 2013-01-23T00:00:00      | 12537.00                |                       | 12537.00                             | 
```