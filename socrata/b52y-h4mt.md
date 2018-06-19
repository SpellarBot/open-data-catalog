# Contracts: State Treasurer: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-state-treasurer-fiscal-year-2013-1304c) |
| Metadata | [Link](https://data.oregon.gov/api/views/b52y-h4mt) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/b52y-h4mt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/b52y-h4mt/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | b52y-h4mt |
| Name | Contracts: State Treasurer: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | contracts, state treasurer, state treasurer contracts, state treasurer's office, treasury contracts, treasury |
| Created | 2013-12-19T23:21:22Z |
| Publication Date | 2013-12-19T23:25:25Z |

## Description

Contracts for the State Treasurer's office for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag     | type_of_contract          | Type of Contract          | text          | text          |
| Yes      | series tag     | contractor                | Contractor                | text          | text          |
| No       |                | st                        | ST                        | text          | text          |
| Yes      | time           | original_start_date       | Original Start Date       | calendar_date | calendar_date |
| No       |                | end_date                  | End Date                  | calendar_date | calendar_date |
| Yes      | numeric metric | original_contract_value   | Original Contract Value   | money         | money         |
| Yes      | series tag     | description               | Description               | text          | text          |
| Yes      | series tag     | amendment_no_renewal_data | Amendment No/Renewal Data | text          | text          |
```

## Time Field

```ls
Value = original_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = st,end_date
```

## Data Commands

```ls
series e:b52y-h4mt d:2012-11-09T00:00:00.000Z t:type_of_contract="Professional Services" t:contractor="Cutter Associates" t:description="Provide future state operating model" m:original_contract_value=139000

series e:b52y-h4mt d:2013-02-01T00:00:00.000Z t:type_of_contract="Professional Services" t:contractor=Tierpoint t:description="Electronic disaster recovery services" m:original_contract_value=50400

series e:b52y-h4mt d:2007-05-17T00:00:00.000Z t:amendment_no_renewal_data="Amendment 3" t:type_of_contract="Professional Services" t:contractor="TGF Productions" t:description="Advertising and marketing services for the 529 College Savings Program" m:original_contract_value=7000000
```

## Meta Commands

```ls
metric m:original_contract_value p:double l:"Original Contract Value" t:dataTypeName=money

entity e:b52y-h4mt l:"Contracts: State Treasurer: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/b52y-h4mt

property e:b52y-h4mt t:meta.view v:id=b52y-h4mt v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: State Treasurer: Fiscal Year 2013"

property e:b52y-h4mt t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:b52y-h4mt t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| type_of_contract      | contractor              | st | original_start_date | end_date            | original_contract_value | description                                                            | amendment_no_renewal_data | 
| ===================== | ======================= | == | =================== | =================== | ======================= | ====================================================================== | ========================= | 
| Professional Services | Cutter Associates       | MA | 2012-11-09T00:00:00 | 2013-06-30T00:00:00 | 139000.00               | Provide future state operating model                                   |                           | 
| Professional Services | Tierpoint               | WA | 2013-02-01T00:00:00 | 2016-01-31T00:00:00 | 50400.00                | Electronic disaster recovery services                                  |                           | 
| Professional Services | TGF Productions         | OR | 2007-05-17T00:00:00 | 2017-05-31T00:00:00 | 7000000.00              | Advertising and marketing services for the 529 College Savings Program | Amendment 3               | 
| Professional Services | Strategas Securities    | NY | 2013-10-14T00:00:00 | 2015-06-30T00:00:00 | 145000.00               | Investment & Sector Strategy/Research                                  | Amendment 1               | 
| Professional Services | Strategas Securities    | NY | 2012-09-05T00:00:00 | 2013-12-31T00:00:00 | 70000.00                | Investment & Sector Strategy/Research                                  |                           | 
| Professional Services | Cortex Applied Research | ON | 2013-04-10T00:00:00 | 2013-07-15T00:00:00 | 16500.00                | Facilitate OIC meeting                                                 |                           | 
| Professional Services | Funston Advisory        | MI | 2012-12-12T00:00:00 | 2013-03-31T00:00:00 | 22000.00                | Board member training best practices                                   |                           | 
| Professional Services | Coalfire Systems Inc    | CO | 2012-12-17T00:00:00 | 2013-12-31T00:00:00 | 110000.00               | Payment card industry data security standard                           | Amendment 1               | 
| Professional Services | OnLine Business         | OR | 2013-06-20T00:00:00 | 2015-06-30T00:00:00 | 150000.00               | Maintain host support Bond Tracker System                              |                           | 
| Professional Services | Advanced Reporting      | OR | 2010-06-24T00:00:00 | 2013-01-31T00:00:00 | 12000.00                | Background checks on potential employees and board appointments        |                           | 
```