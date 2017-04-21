# Contracts: Treasury: As of June 30, 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-treasury-as-of-june-30-2010-e4c7b) |
| Metadata | [Link](https://data.oregon.gov/api/views/pxm3-5ksy) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/pxm3-5ksy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/pxm3-5ksy/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | pxm3-5ksy |
| Name | Contracts: Treasury: As of June 30, 2010 |
| Category | Revenue & Expense |
| Created | 2011-02-14T21:03:21Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag  | contract_description    | Contract Description    | text          | text          |
| Yes      | series tag  | contractor              | Contractor              | text          | text          |
| Yes      | time        | contract_execution_date | Contract Execution Date | calendar_date | calendar_date |
| No       |             | contract_end_date       | Contract End Date       | calendar_date | calendar_date |
| Yes      | series tag  | contract_value          | Contract Value          | text          | text          |
```

## Time Field

```ls
Value = contract_execution_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = contract_end_date
```

## Data Commands

```ls
series e:pxm3-5ksy d:2010-06-24T00:00:00.000Z t:contract_description="Background checks for prospective employees and board/commission members" t:contract_value=$12,000 t:contractor="Advanced Reporting" m:row_number.pxm3-5ksy=1

series e:pxm3-5ksy d:2009-08-30T00:00:00.000Z t:contract_description="Investment consulting services for the Oregon Growth Account (OGA)" t:contract_value=$195,000 t:contractor="Arnerich Massena & Associates Inc" m:row_number.pxm3-5ksy=2

series e:pxm3-5ksy d:2010-05-05T00:00:00.000Z t:contract_description="Hosting and maintenance for the Bond Tracker application" t:contract_value=$180,000 t:contractor="DevMecca LLC" m:row_number.pxm3-5ksy=3
```

## Meta Commands

```ls
metric m:row_number.pxm3-5ksy p:long l:"Row Number"

entity e:pxm3-5ksy l:"Contracts: Treasury: As of June 30, 2010" t:url=https://data.oregon.gov/api/views/pxm3-5ksy

property e:pxm3-5ksy t:meta.view v:id=pxm3-5ksy v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: Treasury: As of June 30, 2010"

property e:pxm3-5ksy t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:pxm3-5ksy t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| contract_description                                                                                               | contractor                               | contract_execution_date | contract_end_date   | contract_value        | 
| ================================================================================================================== | ======================================== | ======================= | =================== | ===================== | 
| Background checks for prospective employees and board/commission members                                           | Advanced Reporting                       | 2010-06-24T00:00:00     | 2013-01-31T00:00:00 | $12,000               | 
| Investment consulting services for the Oregon Growth Account (OGA)                                                 | Arnerich Massena & Associates Inc        | 2009-08-30T00:00:00     | 2012-08-31T00:00:00 | $195,000              | 
| Hosting and maintenance for the Bond Tracker application                                                           | DevMecca LLC                             | 2010-05-05T00:00:00     | 2013-06-30T00:00:00 | $180,000              | 
| Purchase and implementation support for the Infra application (an information services workflow management system) | EMC Corporation                          | 2009-07-08T00:00:00     | 2010-09-30T00:00:00 | $40,800               | 
| Access to Fitch security ratings through Bloomberg                                                                 | Fitch Solutions Inc                      | 2010-04-01T00:00:00     | 2011-03-31T00:00:00 | Annual fee of $7,500  | 
| Security review of OST's network and specific systems/ applications                                                | KPMG                                     | 2009-10-12T00:00:00     | 2010-01-15T00:00:00 | $54,560               | 
| Access to Moody's security ratings through Bloomberg                                                               | Moody's Analytics                        | 2010-06-01T00:00:00     | 2011-05-31T00:00:00 | Annual fee of $36,350 | 
| Access to Standard & Poor's (S&P) CUSIPs through Bloomberg                                                         | Standard & Poor's Financial Services LLC | 2010-05-01T00:00:00     | 2011-04-30T00:00:00 | Annual fee of $25,000 | 
```