# Contracts: State Treasurer: Fiscal Year 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-state-treasurer-fiscal-year-2014-55f46) |
| Metadata | [Link](https://data.oregon.gov/api/views/cfab-grzt) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/cfab-grzt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/cfab-grzt/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | cfab-grzt |
| Name | Contracts: State Treasurer: Fiscal Year 2014 |
| Category | Revenue & Expense |
| Tags | contracts, state treasurer, state treasurer contracts, state treasurer's office, treasury contracts, treasury 2014, 2014 |
| Created | 2014-12-30T08:18:52Z |
| Publication Date | 2014-12-30T08:25:49Z |

## Description

Contracts for the State Treasurer's office for Fiscal Year 2014

## Columns

```ls
| Included | Schema Type | Field Name                            | Name                                  | Data Type     | Render Type   |
| ======== | =========== | ===================================== | ===================================== | ============= | ============= |
| Yes      | series tag  | type_of_contract                      | Type of Contract                      | text          | text          |
| Yes      | series tag  | contractor                            | Contractor                            | text          | text          |
| Yes      | time        | original_start_date                   | Original Start Date                   | calendar_date | calendar_date |
| No       |             | end_date                              | End Date                              | calendar_date | calendar_date |
| Yes      | series tag  | contract_value                        | Contract Value                        | text          | text          |
| Yes      | series tag  | description_amendment_no_renewal_data | Description Amendment No/Renewal Data | text          | text          |
```

## Time Field

```ls
Value = original_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date
```

## Data Commands

```ls
series e:cfab-grzt d:2013-12-04T00:00:00.000Z t:type_of_contract="Professional Services" t:description_amendment_no_renewal_data="Management and Admin Survey, 2012 Public Fund Survey, Milliman 2013 Washington Public Employers Salary Survey" t:contract_value=$10,000.00 t:contractor="McLagan Partners" m:row_number.cfab-grzt=1

series e:cfab-grzt d:2013-03-30T00:00:00.000Z t:type_of_contract="Professional Services" t:description_amendment_no_renewal_data="Work with partner entities to advance stadardized business cases and other mechenisms that reduce risk and promote performance based publicinfrastructure" t:contract_value="27,777 mo." t:contractor="WCX Management, LLC" m:row_number.cfab-grzt=2

series e:cfab-grzt d:2013-05-31T00:00:00.000Z t:type_of_contract="Professional Services" t:description_amendment_no_renewal_data="Amendment 2 529 College Plan- Advertising, Media and promotional partnerships and material. Community based events" t:contract_value=$1,275,500.00 t:contractor="TGF Productions, Inc" m:row_number.cfab-grzt=3
```

## Meta Commands

```ls
metric m:row_number.cfab-grzt p:long l:"Row Number"

entity e:cfab-grzt l:"Contracts: State Treasurer: Fiscal Year 2014" t:url=https://data.oregon.gov/api/views/cfab-grzt

property e:cfab-grzt t:meta.view v:id=cfab-grzt v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: State Treasurer: Fiscal Year 2014"

property e:cfab-grzt t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:cfab-grzt t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| type_of_contract      | contractor                            | original_start_date | end_date            | contract_value | description_amendment_no_renewal_data                                                                                                                     | 
| ===================== | ===================================== | =================== | =================== | ============== | ========================================================================================================================================================= | 
| Professional Services | McLagan Partners                      | 2013-12-04T00:00:00 | 2014-01-31T00:00:00 | $10,000.00     | Management and Admin Survey, 2012 Public Fund Survey, Milliman 2013 Washington Public Employers Salary Survey                                             | 
| Professional Services | WCX Management, LLC                   | 2013-03-30T00:00:00 | 2014-06-30T00:00:00 | 27,777 mo.     | Work with partner entities to advance stadardized business cases and other mechenisms that reduce risk and promote performance based publicinfrastructure | 
| Professional Services | TGF Productions, Inc                  | 2013-05-31T00:00:00 | 2017-05-31T00:00:00 | $1,275,500.00  | Amendment 2 529 College Plan- Advertising, Media and promotional partnerships and material. Community based events                                        | 
| Professional Services | Online Business Systems               | 2013-06-20T00:00:00 | 2015-06-30T00:00:00 | $150,000.00    | Bond Tracking System                                                                                                                                      | 
| Professional Services | Callen Associates, Inc. by way of OIC | 2014-01-01T00:00:00 | 2018-01-01T00:00:00 | 550000 yr.     | Consulting Services for Investments (OIC)                                                                                                                 | 
| Professional Services | Pension Consulting Alliance, Inc.     | 2014-01-01T00:00:00 | 2016-12-31T00:00:00 | 135,000 yr.    | Consulting Services                                                                                                                                       | 
| Professional Services | KPMG                                  | 2013-11-15T00:00:00 |                     | $149,688.00    | Business Continuity Management                                                                                                                            | 
| Professional Services | Coalfire Systems Inc.                 | 2010-02-05T00:00:00 | 2014-12-31T00:00:00 | $110,000.00    | Amendment 2                                                                                                                                               | 
| Professional Services | Deloitte                              | 2013-07-11T00:00:00 |                     | $149,999.00    | Tax Service                                                                                                                                               | 
| Professional Services | Concur Technologies                   | 2013-09-23T00:00:00 |                     | $3,060.00      | New Travel System ( cost is for 3 sessions)                                                                                                               | 
```