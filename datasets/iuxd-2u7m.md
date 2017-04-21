# Contracts: Judicial: Fiscal Year 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-judicial-fiscal-year-2011-c7353) |
| Metadata | [Link](https://data.oregon.gov/api/views/iuxd-2u7m) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/iuxd-2u7m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/iuxd-2u7m/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | iuxd-2u7m |
| Name | Contracts: Judicial: Fiscal Year 2011 |
| Category | Revenue & Expense |
| Created | 2011-12-18T22:55:11Z |
| Publication Date | 2011-12-18T22:57:32Z |

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type     | Render Type   |
| ======== | ============== | ==================================== | ==================================== | ============= | ============= |
| Yes      | series tag     | award_number                         | Award Number                         | text          | text          |
| Yes      | series tag     | award_title                          | Award Title                          | text          | text          |
| Yes      | series tag     | award_type                           | *Award Type                          | text          | text          |
| Yes      | series tag     | company_name                         | Company Name                         | text          | text          |
| No       |                | company_address                      | Company Address                      | text          | text          |
| Yes      | series tag     | company_phone                        | Company Phone                        | text          | text          |
| Yes      | time           | contract_effective_date_             | Contract Effective Date              | calendar_date | calendar_date |
| No       |                | contract_expiration_date_            | Contract Expiration Date             | calendar_date | calendar_date |
| Yes      | numeric metric | original_contract_value              | Original Contract Value              | money         | money         |
| Yes      | numeric metric | total_amendment_value                | Total Amendment Value                | money         | money         |
| Yes      | numeric metric | total_contract_value_with_amendments | Total Contract Value with amendments | money         | money         |
```

## Time Field

```ls
Value = contract_effective_date_
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = company_address,contract_expiration_date_
```

## Data Commands

```ls
series e:iuxd-2u7m d:2010-10-01T00:00:00.000Z t:award_number=100140 t:company_name="DAS Facilities" t:company_phone=503-373-2317 t:award_type=IAA t:award_title="IAA - Supreme Court Building - Misc Services" m:total_contract_value_with_amendments=165269 m:total_amendment_value=0 m:original_contract_value=165269

series e:iuxd-2u7m d:2010-07-08T00:00:00.000Z t:award_number=100160 t:company_name="Josephine County" t:company_phone=541-474-5474 t:award_type=IGA t:award_title="Josephine Parking Space" m:total_contract_value_with_amendments=19458 m:total_amendment_value=0 m:original_contract_value=19458

series e:iuxd-2u7m d:2010-07-01T00:00:00.000Z t:award_number=110171 t:company_name="Lane Council of Governments" t:company_phone=541-682-4548 t:award_type=IGA t:award_title="Telecommunications Systems Management and Services" m:total_contract_value_with_amendments=15115 m:total_amendment_value=0 m:original_contract_value=15115
```

## Meta Commands

```ls
metric m:original_contract_value p:double l:"Original Contract Value" t:dataTypeName=money

metric m:total_amendment_value p:double l:"Total Amendment Value" t:dataTypeName=money

metric m:total_contract_value_with_amendments p:double l:"Total Contract Value with amendments" t:dataTypeName=money

entity e:iuxd-2u7m l:"Contracts: Judicial: Fiscal Year 2011" t:url=https://data.oregon.gov/api/views/iuxd-2u7m

property e:iuxd-2u7m t:meta.view v:id=iuxd-2u7m v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: Judicial: Fiscal Year 2011"

property e:iuxd-2u7m t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:iuxd-2u7m t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| award_number | award_title                                                                                               | award_type | company_name                          | company_address                                  | company_phone | contract_effective_date_ | contract_expiration_date_ | original_contract_value | total_amendment_value | total_contract_value_with_amendments | 
| ============ | ========================================================================================================= | ========== | ===================================== | ================================================ | ============= | ======================== | ========================= | ======================= | ===================== | ==================================== | 
| 100140       | IAA - Supreme Court Building - Misc Services                                                              | IAA        | DAS Facilities                        | 1225 Ferry Street SE U100 Salem, OR 97301-4281   | 503-373-2317  | 2010-10-01T00:00:00      | 2011-06-30T00:00:00       | 165269.00               | 0.00                  | 165269.00                            | 
| 100160       | Josephine Parking Space                                                                                   | IGA        | Josephine County                      | 500 NW 6th Grants Pass, OR 97526                 | 541-474-5474  | 2010-07-08T00:00:00      | 2013-12-31T00:00:00       | 19458.00                | 0.00                  | 19458.00                             | 
| 110171       | Telecommunications Systems Management and Services                                                        | IGA        | Lane Council of Governments           | 99 East Broadway Suite 400 Eugene, OR 97401-3111 | 541-682-4548  | 2010-07-01T00:00:00      | 2011-06-30T00:00:00       | 15115.00                | 0.00                  | 15115.00                             | 
| 110180       | Statewide (Re) Assessment of Juvenile Dependency Courts                                                   | PSK        | Travis Consulting Co.                 | 1746 NE 51st Ave Portland, OR 97213              | 503-703-6686  | 2010-10-20T00:00:00      | 2011-08-19T00:00:00       | 55020.00                | 0.00                  | 55020.00                             | 
| 110183       | GRANT - Partial Funding of Drug Court Coordinator - Deschutes County                                      | IGA        | Deschutes County                      | 1100 NW Bond St Bend, OR 97701                   | 541-388-5300  | 2010-07-01T00:00:00      | 2011-06-30T00:00:00       | 66211.00                | 9935.00               | 76146.00                             | 
| 110184       | GRANT - .5 VAWA Staff Counsel Position                                                                    | IAA        | Oregon Judicial Department            | 1163 State St Salem, OR 97301                    | 503-986-5942  | 2010-07-29T00:00:00      | 2011-06-30T00:00:00       | 55256.21                | 0.00                  | 55256.21                             | 
| 110185       | OEA to develop and maintain revenue forecasting models for OJD                                            | IAA        | DAS Office of Economic Analysis       | 155 Cottage St. NE, U20 Salem, OR 97301-3966     | 503-378-3405  | 2010-07-01T00:00:00      | 2011-06-30T00:00:00       | 10000.00                | 0.00                  | 10000.00                             | 
| 110200       | GRANT - Funding For Intensive Drug Court For High Risk Offenders Measure 57 Provide 1.5 Support Positions | IGA        | Jackson County Circuit Court          | 10 S. Oakdale Rm 214 Medford, OR 97501           | 541-776-7171  | 2010-10-06T00:00:00      | 2011-09-30T00:00:00       | 118301.00               | 0.00                  | 118301.00                            | 
| 110201       | GRANT - Subgrant to Fund Drug Court                                                                       | IGA        | Lutheran Community Services Northwest | 206 N Court Prineville, OR 97754                 | 541-416-1095  | 2010-07-01T00:00:00      | 2011-06-30T00:00:00       | 94032.00                | 0.00                  | 94032.00                             | 
| 110204       | GRANT - .5 FTE Drug Court Coordinator                                                                     | IGA        | Linn County Circuit Court             | PO Box 100 Albany, OR 97321                      | 541-967-3802  | 2010-10-01T00:00:00      | 2011-06-30T00:00:00       | 31995.00                | 0.00                  | 31995.00                             | 
```