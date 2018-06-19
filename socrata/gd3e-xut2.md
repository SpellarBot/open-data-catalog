# Campaign Finance - Expenditures Dataset

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-expenditures-dataset) |
| Metadata | [Link](https://data.austintexas.gov/api/views/gd3e-xut2) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/gd3e-xut2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/gd3e-xut2/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | gd3e-xut2 |
| Name | Campaign Finance - Expenditures Dataset |
| Created | 2016-08-17T19:04:03Z |
| Publication Date | 2016-09-19T14:21:59Z |

## Description

This dataset lists all expenditures and incurred obligations reported by candidates, officeholders and political committees on data files submitted per City Code Chapter 2-2-26.

For a complete listing of each column heading, please see the field listing here: http://www.austintexas.gov/edims/document.cfm?id=262465

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag     | payee                  | Payee                  | text          | text          |
| Yes      | series tag     | paid_by                | Paid_By                | text          | text          |
| Yes      | numeric metric | payment_amount         | Payment_Amount         | money         | money         |
| Yes      | time           | payment_date           | Payment_Date           | calendar_date | calendar_date |
| Yes      | series tag     | payee_type             | Payee_Type             | text          | text          |
| No       |                | payee_address          | Payee_Address          | text          | text          |
| Yes      | series tag     | city_state_zip         | City_State_Zip         | text          | text          |
| No       |                | payment_year           | Payment_Year           | number        | text          |
| Yes      | series tag     | expenditure_type       | Expenditure_Type       | text          | text          |
| No       |                | date_reported          | Date_Reported          | calendar_date | calendar_date |
| Yes      | series tag     | report_filed           | Report_Filed           | text          | text          |
| Yes      | series tag     | expense_description    | Expense_Description    | text          | text          |
| Yes      | series tag     | travel_outside_texas   | Travel_Outside_Texas   | text          | text          |
| Yes      | series tag     | political_obligation   | Political_Obligation   | text          | text          |
| Yes      | series tag     | reimbursement_intended | Reimbursement_Intended | text          | text          |
| Yes      | series tag     | correction             | Correction             | text          | text          |
| Yes      | series tag     | view_report            | View_Report            | url           | url           |
| Yes      | series tag     | transaction_id         | TRANSACTION_ID         | text          | text          |
```

## Time Field

```ls
Value = payment_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = payee_address,date_reported,payment_year
```

## Data Commands

```ls
series e:gd3e-xut2 d:2016-05-06T00:00:00.000Z t:report_filed="C/OH: Candidate/Officeholder Campaign Finance Report" t:payee_type=Entity t:city_state_zip="Austin, TX, 78701" t:expenditure_type="Political Expenditure from Political Contributions" t:paid_by="Troxclair, Ellen" t:payee=Taverna t:expense_description="Food/Beverage Expense | Staff lunch" t:transaction_id=R20160715175704-F0001 t:view_report="http://www.austintexas.gov/edims/document.cfm?id=258144" m:payment_amount=106.12

series e:gd3e-xut2 d:2016-05-09T00:00:00.000Z t:report_filed="SPAC: Specific-Purpose Committee Campaign Finance Report" t:payee_type=Entity t:city_state_zip="San Francisco, CA, 94110" t:expenditure_type="Political Expenditure from Political Contributions" t:paid_by="Austin Unites" t:political_obligation=Yes t:payee=Stripe t:expense_description="Fees | Processing Fees" t:transaction_id=R20160718161156-F0002 t:view_report="http://www.austintexas.gov/edims/document.cfm?id=258188" m:payment_amount=43.7

series e:gd3e-xut2 d:2016-09-08T00:00:00.000Z t:report_filed="ATX_1: Independent Expenditures not by a Candidate" t:payee_type=Entity t:city_state_zip="Austin, TX, 78701" t:paid_by="Austin Forward" t:payee="GNI Consulting" t:expense_description="Salaries/Wages/Contract Labor | Outreach Consulting" t:transaction_id=R20160916091836-F0001 t:view_report="http://www.austintexas.gov/edims/document.cfm?id=262904" m:payment_amount=2250
```

## Meta Commands

```ls
metric m:payment_amount p:double l:Payment_Amount t:dataTypeName=money

entity e:gd3e-xut2 l:"Campaign Finance - Expenditures Dataset" t:url=https://data.austintexas.gov/api/views/gd3e-xut2

property e:gd3e-xut2 t:meta.view v:id=gd3e-xut2 v:averageRating=0 v:name="Campaign Finance - Expenditures Dataset"

property e:gd3e-xut2 t:meta.view.owner v:id=fjfv-27ab v:screenName="Kathryn Darnall" v:displayName="Kathryn Darnall"

property e:gd3e-xut2 t:meta.view.tableauthor v:id=fjfv-27ab v:screenName="Kathryn Darnall" v:roleName=editor v:displayName="Kathryn Darnall"
```

## Top Records

```ls
| payee               | paid_by                          | payment_amount | payment_date        | payee_type | payee_address                 | city_state_zip           | payment_year | expenditure_type                                   | date_reported       | report_filed                                                           | expense_description                                             | travel_outside_texas | political_obligation | reimbursement_intended | correction | view_report                                                            | transaction_id        | 
| =================== | ================================ | ============== | =================== | ========== | ============================= | ======================== | ============ | ================================================== | =================== | ====================================================================== | =============================================================== | ==================== | ==================== | ====================== | ========== | ====================================================================== | ===================== | 
| Taverna             | Troxclair, Ellen                 | 106.12         | 2016-05-06T00:00:00 | Entity     | 258 W 2nd St                  | Austin, TX, 78701        | 2016         | Political Expenditure from Political Contributions | 2016-07-15T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report                   | Food/Beverage Expense | Staff lunch                             |                      |                      |                        |            | [http://www.austintexas.gov/edims/document.cfm?id=258144, View Report] | R20160715175704-F0001 | 
| Stripe              | Austin Unites                    | 43.7           | 2016-05-09T00:00:00 | Entity     | 3180 18th St                  | San Francisco, CA, 94110 | 2016         | Political Expenditure from Political Contributions | 2016-07-18T00:00:00 | SPAC: Specific-Purpose Committee Campaign Finance Report               | Fees | Processing Fees                                          |                      | Yes                  |                        |            | [http://www.austintexas.gov/edims/document.cfm?id=258188, View Report] | R20160718161156-F0002 | 
| GNI Consulting      | Austin Forward                   | 2250           | 2016-09-08T00:00:00 | Entity     | P.O. Box 3685008              | Austin, TX, 78701        | 2016         |                                                    | 2016-09-14T00:00:00 | ATX_1: Independent Expenditures not by a Candidate                     | Salaries/Wages/Contract Labor | Outreach Consulting             |                      |                      |                        |            | [http://www.austintexas.gov/edims/document.cfm?id=262904, View Report] | R20160916091836-F0001 | 
| Papa John's Pizza   | Austin Forward                   | 58.96          | 2016-09-29T00:00:00 | Entity     | 8106 Brodie Ln                | Austin, TX, 78745        | 2016         |                                                    | 2016-10-03T00:00:00 | ATX_1: Independent Expenditures not by a Candidate                     | Food/Beverage Expense                                           |                      |                      |                        |            | [http://www.austintexas.gov/edims/document.cfm?id=263980, View Report] | R20161004101619-F0023 | 
| Austin PAC Forward  | Austin Apartment Association PAC | 15000          | 2016-09-08T00:00:00 | Entity     | 2121 S. Lamar Blvd, Suite 100 | Austin, TX, 78704        | 2016         | Political Expenditure from Political Contributions | 2016-10-05T00:00:00 | MPAC: Monthly Filing General-Purpose Committee Campaign Finance Report | Contribution                                                    |                      | Yes                  |                        |            | [http://www.austintexas.gov/edims/document.cfm?id=264055, View Report] | R20161005125901-F0003 | 
| UPS Store           | Pool, Leslie                     | 118.5          | 2016-05-18T00:00:00 | Entity     | 1101 W 34th Street            | Austin, TX, 78705        | 2016         | Political Expenditure from Political Contributions | 2016-07-01T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report                   | mailbox rental                                                  |                      |                      |                        |            | [http://www.austintexas.gov/edims/document.cfm?id=258080, View Report] | R20160705153524-F0005 | 
| Rein Consulting LLP | Gauldin, Natalie B.              | 115            | 2016-08-04T00:00:00 | Entity     | 201 Tanglebriar A             | San Antonio, TX, 78209   | 2016         | Political Expenditure from Political Contributions | 2016-10-11T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report                   | Consulting Expense | Campaign Consulting                        |                      | Yes                  |                        |            | [http://www.austintexas.gov/edims/document.cfm?id=264522, View Report] | R20161012171606-F0046 | 
| Davies, William     | Travis County Democratic Party   | 127.86         | 2016-10-15T00:00:00 | Individual | 2211 Lawnmont                 | Austin, TX, 78702        | 2016         |                                                    | 2016-10-19T00:00:00 | ATX_1: Independent Expenditures not by a Candidate                     | Salaries/Wages/Contract Labor                                   |                      |                      |                        |            | [http://www.austintexas.gov/edims/document.cfm?id=264958, View Report] | R20161020153116-F0011 | 
| Austin Crossing LTD | Zimmerman, Donald S. "Don"       | 230.13         | 2016-10-04T00:00:00 | Entity     | 405 N. Lamar, Suite 200       | Austin, TX, 78703        | 2016         | Political Expenditure from Political Contributions | 2016-10-31T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report                   | Office Overhead/Rental Expense | Office Overhead/Rental Expense |                      | Yes                  |                        |            | [http://www.austintexas.gov/edims/document.cfm?id=265598, View Report] | R20161031143039-F0008 | 
| Lassus, Nick        | Workers Defense in Action PAC    | 78.72          | 2016-09-21T00:00:00 | Individual | 6043B Chimney Creek Circle    | Austin, TX, 78723        | 2016         |                                                    | 2016-09-23T00:00:00 | ATX_1: Independent Expenditures not by a Candidate                     | Salaries/Wages/Contract Labor                                   |                      |                      |                        |            | [http://www.austintexas.gov/edims/document.cfm?id=263644, View Report] | R20161028164911-F0006 | 
```