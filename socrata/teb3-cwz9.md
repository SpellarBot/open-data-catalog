# Campaign Finance - Loans Dataset

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-loans-dataset) |
| Metadata | [Link](https://data.austintexas.gov/api/views/teb3-cwz9) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/teb3-cwz9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/teb3-cwz9/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | teb3-cwz9 |
| Name | Campaign Finance - Loans Dataset |
| Created | 2016-08-17T19:09:11Z |
| Publication Date | 2016-10-26T20:26:44Z |

## Description

This dataset lists all loans taken out by candidates, officeholders and political committees on data files submitted per City Code Chapter 2-2-26.
For a complete listing of each column heading, please see the field listing here: http://www.austintexas.gov/edims/document.cfm?id=262466

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag     | borrower                   | Borrower                   | text          | text          |
| Yes      | series tag     | lender                     | Lender                     | text          | text          |
| Yes      | numeric metric | loan_amount                | Loan_Amount                | money         | money         |
| Yes      | time           | loan_date                  | Loan_Date                  | calendar_date | calendar_date |
| Yes      | series tag     | lender_type                | Lender_Type                | text          | text          |
| Yes      | series tag     | financial_institution      | Financial_Institution      | text          | text          |
| No       |                | lender_address             | Lender_Address             | text          | text          |
| Yes      | series tag     | city_state_zip             | City_State_Zip             | text          | text          |
| No       |                | loan_year                  | Loan_Year                  | number        | text          |
| Yes      | series tag     | interest_rate              | Interest_Rate              | text          | text          |
| No       |                | maturity_date              | Maturity_Date              | calendar_date | calendar_date |
| Yes      | series tag     | collateral                 | Collateral                 | text          | text          |
| Yes      | series tag     | personal_funds             | Personal_Funds             | text          | text          |
| Yes      | series tag     | lender_reported_occupation | Lender_Reported_Occupation | text          | text          |
| Yes      | series tag     | lender_reported_employer   | Lender_Reported_Employer   | text          | text          |
| No       |                | date_reported              | Date_Reported              | calendar_date | calendar_date |
| Yes      | series tag     | report_filed               | Report_Filed               | text          | text          |
| Yes      | series tag     | guarantor                  | Guarantor                  | text          | text          |
| No       |                | guarantor_address          | Guarantor_Address          | text          | text          |
| Yes      | series tag     | guarantor_city_state_zip   | Guarantor_City_State_Zip   | text          | text          |
| Yes      | series tag     | guarantor_occupation       | Guarantor_Occupation       | text          | text          |
| Yes      | series tag     | guarantor_employer         | Guarantor_Employer         | text          | text          |
| Yes      | numeric metric | amount_guaranteed          | Amount_Guaranteed          | money         | money         |
| Yes      | series tag     | correction                 | Correction                 | text          | text          |
| Yes      | series tag     | view_report                | View_Report                | url           | url           |
| Yes      | series tag     | transaction_id             | TRANSACTION_ID             | text          | text          |
```

## Time Field

```ls
Value = loan_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = lender_address,maturity_date,date_reported,guarantor_address,loan_year
```

## Data Commands

```ls
series e:teb3-cwz9 d:2016-04-13T00:00:00.000Z t:city_state_zip="Austin, TX, 78753" t:lender_reported_employer="Pure Rain, LLC" t:borrower="Pressley, Laura" t:lender_reported_occupation=Owner t:guarantor="None reported" t:transaction_id=R20160726163007-E0005 t:personal_funds=Yes t:view_report="http://www.austintexas.gov/edims/document.cfm?id=258178" t:report_filed="C/OH: Candidate/Officeholder Campaign Finance Report" t:collateral="None reported" t:financial_institution=No t:lender_type=Individual t:lender="Pressley, Laura" t:interest_rate="Not reported" m:loan_amount=15000

series e:teb3-cwz9 d:2015-06-02T00:00:00.000Z t:city_state_zip="Austin, TX, 78753" t:lender_reported_employer="Pure Rain, LLC" t:borrower="Pressley, Laura" t:lender_reported_occupation=Owner t:guarantor="None reported" t:transaction_id=R20160726163007-E0006 t:personal_funds=Yes t:view_report="http://www.austintexas.gov/edims/document.cfm?id=258178" t:report_filed="C/OH: Candidate/Officeholder Campaign Finance Report" t:collateral="None reported" t:financial_institution=No t:lender_type=Individual t:lender="Pressley, Laura" t:interest_rate="Not reported" m:loan_amount=6000

series e:teb3-cwz9 d:2015-08-04T00:00:00.000Z t:report_filed="C/OH: Candidate/Officeholder Campaign Finance Report" t:city_state_zip="City Of Industry, CA, 91716" t:collateral="None reported" t:borrower="Pressley, Laura" t:financial_institution=Yes t:guarantor="None reported" t:lender_type=Entity t:lender="Capitol One" t:transaction_id=R20160726163007-E0007 t:interest_rate="Not reported" t:view_report="http://www.austintexas.gov/edims/document.cfm?id=258178" m:loan_amount=17724
```

## Meta Commands

```ls
metric m:loan_amount p:double l:Loan_Amount t:dataTypeName=money

metric m:amount_guaranteed p:integer l:Amount_Guaranteed t:dataTypeName=money

entity e:teb3-cwz9 l:"Campaign Finance - Loans Dataset" t:url=https://data.austintexas.gov/api/views/teb3-cwz9

property e:teb3-cwz9 t:meta.view v:id=teb3-cwz9 v:averageRating=0 v:name="Campaign Finance - Loans Dataset"

property e:teb3-cwz9 t:meta.view.owner v:id=fjfv-27ab v:screenName="Kathryn Darnall" v:displayName="Kathryn Darnall"

property e:teb3-cwz9 t:meta.view.tableauthor v:id=fjfv-27ab v:screenName="Kathryn Darnall" v:roleName=editor v:displayName="Kathryn Darnall"
```

## Top Records

```ls
| borrower                           | lender              | loan_amount | loan_date           | lender_type | financial_institution | lender_address            | city_state_zip              | loan_year | interest_rate | maturity_date       | collateral    | personal_funds | lender_reported_occupation | lender_reported_employer | date_reported       | report_filed                                             | guarantor     | guarantor_address | guarantor_city_state_zip | guarantor_occupation | guarantor_employer | amount_guaranteed | correction | view_report                                                            | transaction_id        | 
| ================================== | =================== | =========== | =================== | =========== | ===================== | ========================= | =========================== | ========= | ============= | =================== | ============= | ============== | ========================== | ======================== | =================== | ======================================================== | ============= | ================= | ======================== | ==================== | ================== | ================= | ========== | ====================================================================== | ===================== | 
| Pressley, Laura                    | Pressley, Laura     | 15000       | 2016-04-13T00:00:00 | Individual  | No                    | 10203 Woodglen Cove       | Austin, TX, 78753           | 2016      | Not reported  |                     | None reported | Yes            | Owner                      | Pure Rain, LLC           | 2016-07-26T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report     | None reported |                   |                          |                      |                    |                   |            | [http://www.austintexas.gov/edims/document.cfm?id=258178, View Report] | R20160726163007-E0005 | 
| Pressley, Laura                    | Pressley, Laura     | 6000        | 2015-06-02T00:00:00 | Individual  | No                    | 10203 Woodglen Cove       | Austin, TX, 78753           | 2015      | Not reported  |                     | None reported | Yes            | Owner                      | Pure Rain, LLC           | 2016-07-26T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report     | None reported |                   |                          |                      |                    |                   |            | [http://www.austintexas.gov/edims/document.cfm?id=258178, View Report] | R20160726163007-E0006 | 
| Pressley, Laura                    | Capitol One         | 17724       | 2015-08-04T00:00:00 | Entity      | Yes                   | P. O. Box 60599           | City Of Industry, CA, 91716 | 2015      | Not reported  |                     | None reported |                |                            |                          | 2016-07-26T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report     | None reported |                   |                          |                      |                    |                   |            | [http://www.austintexas.gov/edims/document.cfm?id=258178, View Report] | R20160726163007-E0007 | 
| Pressley, Laura                    | IEEE US Bank        | 7166        | 2015-08-09T00:00:00 | Entity      | Yes                   | P.O. Box 790408           | St. Louis, MO, 63179        | 2015      | Not reported  |                     | None reported |                |                            |                          | 2016-07-26T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report     | None reported |                   |                          |                      |                    |                   |            | [http://www.austintexas.gov/edims/document.cfm?id=258178, View Report] | R20160726163007-E0008 | 
| Pressley, Laura                    | Bank of America     | 2396        | 2016-03-02T00:00:00 | Entity      | Yes                   | P.O. Box 851001           | Dallas, TX, 75285           | 2016      | Not reported  |                     | None reported |                |                            |                          | 2016-07-26T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report     | None reported |                   |                          |                      |                    |                   |            | [http://www.austintexas.gov/edims/document.cfm?id=258178, View Report] | R20160726163007-E0009 | 
| Pressley, Laura                    | Chase               | 2986        | 2015-09-22T00:00:00 | Entity      | Yes                   | P.O. Box 15298            | Wilmington, DE, 19850       | 2015      | Not reported  |                     | None reported |                |                            |                          | 2016-07-26T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report     | None reported |                   |                          |                      |                    |                   |            | [http://www.austintexas.gov/edims/document.cfm?id=258178, View Report] | R20160726163007-E0010 | 
| Zimmerman, Donald S. "Don"         | Zimmerman, Donald   | 10000       | 2014-08-08T00:00:00 | Individual  | No                    | 10901 Enchanted Rock Cove | Austin, TX, 78726           | 2014      | Not reported  | 2014-12-31T00:00:00 | None reported |                | Engineer                   | Self                     | 2016-07-14T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report     | None reported |                   |                          |                      |                    |                   |            | [http://www.austintexas.gov/edims/document.cfm?id=258079, View Report] | R20160808101110-E0002 | 
| Garza, Delia                       | Garza, Delia        | 100         | 2016-05-09T00:00:00 | Individual  | No                    | 209 Sandra St.            | Austin, TX, 78745           | 2016      | Not reported  |                     | None reported | Yes            | Council Member             | City of Austin           | 2016-07-15T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report     | None reported |                   |                          |                      |                    |                   |            | [http://www.austintexas.gov/edims/document.cfm?id=258186, View Report] | R20160715173401-E0001 | 
| Flannigan, James T. "Jimmy"        | Flannigan, James T. | 200         | 2016-05-13T00:00:00 | Individual  | No                    | 12304 B Cahone Trl        | Austin, TX, 78729           | 2016      | Not reported  |                     | None reported | Yes            | Web developer              | McGinnis Lochridge       | 2016-07-15T00:00:00 | C/OH: Candidate/Officeholder Campaign Finance Report     | None reported |                   |                          |                      |                    |                   |            | [http://www.austintexas.gov/edims/document.cfm?id=258182, View Report] | R20160715180436-E0001 | 
| Our City Our Safety Our Choice PAC | Butts, David        | 10000       | 2016-04-28T00:00:00 | Individual  | No                    | 1914 Patton Ln            | Austin, TX, 78723           | 2016      | Not reported  |                     | None reported |                |                            |                          | 2016-07-18T00:00:00 | SPAC: Specific-Purpose Committee Campaign Finance Report | None reported |                   |                          |                      |                    |                   |            | [http://www.austintexas.gov/edims/document.cfm?id=258190, View Report] | R20160718160828-E0001 | 
```