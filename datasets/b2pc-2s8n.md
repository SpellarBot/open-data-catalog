# Campaign Finance Data - Report Detail Dataset

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-data-report-detail-dataset) |
| Metadata | [Link](https://data.austintexas.gov/api/views/b2pc-2s8n) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/b2pc-2s8n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/b2pc-2s8n/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | b2pc-2s8n |
| Name | Campaign Finance Data - Report Detail Dataset |
| Category | Government |
| Tags | election, financial, campaign finance, contributions, expenditures, city clerk |
| Created | 2016-01-14T17:17:15Z |
| Publication Date | 2016-10-28T21:03:32Z |
| Rows Updated | 2017-01-23T15:48:17Z |

## Description

This dataset contains data about the Campaign Finance Report received by a filer.  The Reports table contains information about the type of report filed, the due date, original filing date, and transaction totals.  To access the Transactions table, where individual transactions are listed, please go to: https://data.austintexas.gov/Government/Campaign-Finance-Data-Transaction-Detail-Dataset/g4yx-aw9r

A data dictionary for this dataset is available at http://www.austintexas.gov/edims/document.cfm?id=247730

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag     | filer_name                 | Filer_Name                 | text          | text          |
| Yes      | series tag     | form_type                  | Form                       | text          | text          |
| Yes      | series tag     | report_type                | Report_Type                | text          | text          |
| Yes      | series tag     | report_type2               | Report_Type2               | text          | text          |
| Yes      | series tag     | link_to_report             | View_Report                | url           | url           |
| Yes      | time           | date_filed                 | Date_Filed                 | calendar_date | calendar_date |
| No       |                | filer_address_2            | Filer_Address              | text          | text          |
| Yes      | series tag     | filer_city                 | Filer_City_State_Zip       | text          | text          |
| Yes      | series tag     | report_id                  | Report_ID                  | text          | text          |
| Yes      | series tag     | treasurer_name             | Treasurer_Name             | text          | text          |
| No       |                | treasurer_address_2        | Treasurer_Address          | text          | text          |
| Yes      | series tag     | treasurer_city             | Treasurer_City_State_Zip   | text          | text          |
| No       |                | date_due                   | Date_Due                   | calendar_date | calendar_date |
| Yes      | series tag     | name_as_reported           | Name_as_Reported           | text          | text          |
| Yes      | series tag     | filer_phone                | Filer_Phone                | text          | text          |
| Yes      | series tag     | treasurer_state            | Treasurer_State            | text          | text          |
| Yes      | series tag     | treasurer_zip_code         | Treasurer_Zip_Code         | text          | text          |
| Yes      | series tag     | treasurer_phone            | Treasurer_Phone            | text          | text          |
| No       |                | period_from                | Period_From                | calendar_date | calendar_date |
| No       |                | period_to                  | Period_To                  | calendar_date | calendar_date |
| No       |                | election_date              | Election_Date              | text          | calendar_date |
| Yes      | series tag     | election_type              | Election_Type              | text          | text          |
| Yes      | series tag     | office_held                | Office_Held                | text          | text          |
| Yes      | series tag     | office_sought              | Office_Sought              | text          | text          |
| Yes      | numeric metric | unitemized_contrib_total   | Unitemized_Contrib_Total   | money         | money         |
| Yes      | numeric metric | contrib_total              | Contrib_Total              | money         | money         |
| Yes      | numeric metric | unitemized_expend_total    | Unitemized_Expend_Total    | money         | money         |
| Yes      | numeric metric | expend_total               | Expend_Total               | money         | money         |
| Yes      | numeric metric | contrib_balance            | Contrib_Balance            | money         | money         |
| Yes      | numeric metric | outstand_loan              | Outstand_Loan              | money         | money         |
| Yes      | numeric metric | unitemized_inkind_total    | Unitemized_InKind_Total    | money         | money         |
| Yes      | numeric metric | unitemized_pledge_total    | Unitemized_Pledge_Total    | money         | money         |
| Yes      | numeric metric | unitemized_loan_total      | Unitemized_Loan_Total      | money         | money         |
| Yes      | numeric metric | unitemized_unpaid_total    | Unitemized_Unpaid_Total    | money         | money         |
| Yes      | numeric metric | unitemized_cred_card_total | Unitemized_Cred_Card_Total | money         | money         |
```

## Time Field

```ls
Value = date_filed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = filer_address_2,treasurer_address_2,date_due,period_from,period_to,election_date
```

## Data Commands

```ls
series e:b2pc-2s8n d:2016-07-15T00:00:00.000Z t:filer_city="Austin, TX, 78729" t:filer_name="Flannigan, James T. ""Jimmy""" t:link_to_report="http://www.austintexas.gov/edims/document.cfm?id=258182" t:treasurer_name="Landuyt, Noel" t:office_sought="District 6" t:election_type=General t:report_type="July 15 Seminannual Report" t:treasurer_phone=5127738437 t:treasurer_city="Austin, TX, 78717" t:form_type="C/OH - Candidate/Officeholder Campaign Finance Report" t:name_as_reported="James, Flannigan, T., ""Jimmy""" t:report_id=R20160715180436 t:filer_phone=5129178428 m:unitemized_inkind_total=0 m:unitemized_unpaid_total=0 m:expend_total=12209.9 m:unitemized_contrib_total=0 m:unitemized_expend_total=0 m:unitemized_pledge_total=0 m:contrib_balance=20487.21 m:unitemized_loan_total=0 m:contrib_total=46951.54 m:outstand_loan=0 m:unitemized_cred_card_total=0

series e:b2pc-2s8n d:2016-07-14T00:00:00.000Z t:filer_city="Austin, TX, 78755" t:filer_name="Gallo, Sheri P." t:link_to_report="http://www.austintexas.gov/edims/document.cfm?id=258109" t:treasurer_name="Little, Lew, Jr." t:office_sought="District 10" t:election_type=General t:report_type="July 15 Seminannual Report" t:treasurer_phone=512-480-9702 t:treasurer_city="Austin, TX, 78746" t:form_type="C/OH - Candidate/Officeholder Campaign Finance Report" t:name_as_reported="Gallo, Sheri" t:report_id=R20160715181229 t:filer_phone=512-978-2110 t:office_held="District 10" m:unitemized_inkind_total=0 m:unitemized_unpaid_total=0 m:expend_total=0 m:unitemized_contrib_total=0 m:unitemized_expend_total=0 m:unitemized_pledge_total=0 m:contrib_balance=0 m:unitemized_loan_total=0 m:contrib_total=0 m:outstand_loan=0 m:unitemized_cred_card_total=0

series e:b2pc-2s8n d:2016-07-15T00:00:00.000Z t:filer_city="Austin, TX, 78756" t:filer_name="Gauldin, Natalie B." t:link_to_report="http://www.austintexas.gov/edims/document.cfm?id=258191" t:treasurer_name="Baxter, Audrey" t:office_sought="District 7" t:election_type=General t:report_type="July 15 Seminannual Report" t:treasurer_phone=5124180239 t:treasurer_city="Austin, TX, 78731" t:form_type="C/OH - Candidate/Officeholder Campaign Finance Report" t:name_as_reported="Gauldin, Natalie" t:report_id=R20160715173219 t:filer_phone=5126562759 m:unitemized_inkind_total=0 m:unitemized_unpaid_total=0 m:expend_total=1748.11 m:unitemized_contrib_total=0 m:unitemized_expend_total=0 m:unitemized_pledge_total=0 m:contrib_balance=18711.89 m:unitemized_loan_total=0 m:contrib_total=20460 m:outstand_loan=0 m:unitemized_cred_card_total=0
```

## Meta Commands

```ls
metric m:unitemized_contrib_total p:double l:Unitemized_Contrib_Total d:"The total of all unitemized contributions received by the filer during the reporting period" t:dataTypeName=money

metric m:contrib_total p:double l:Contrib_Total d:"The total of all contributions received by the filer during the reporting period (itemized and unitemized)" t:dataTypeName=money

metric m:unitemized_expend_total p:double l:Unitemized_Expend_Total d:"The total of all unitemized expenditures made by the filer during the reporting period" t:dataTypeName=money

metric m:expend_total p:double l:Expend_Total d:"The total of all expenditures made by the filer during the reporting period (itemized and unitemized)" t:dataTypeName=money

metric m:contrib_balance p:double l:Contrib_Balance d:"The total of all political contributions, including interest and additional income, as of the last day of the reporting period" t:dataTypeName=money

metric m:outstand_loan p:double l:Outstand_Loan d:"Outstanding principal of all loans maintained as of the last day of the reporting period" t:dataTypeName=money

metric m:unitemized_inkind_total p:double l:Unitemized_InKind_Total d:"The total of all unitemized in-kind contributions received by the filer during the reporting period" t:dataTypeName=money

metric m:unitemized_pledge_total p:integer l:Unitemized_Pledge_Total d:"The total of all unitemized pledges received by the filer during the reporting period" t:dataTypeName=money

metric m:unitemized_loan_total p:integer l:Unitemized_Loan_Total d:"The total of all unitemized loans maintained by the filer during the reporting period" t:dataTypeName=money

metric m:unitemized_unpaid_total p:double l:Unitemized_Unpaid_Total d:"The total of all unitemized unpaid obligations incurred by the filer during the reporting period" t:dataTypeName=money

metric m:unitemized_cred_card_total p:integer l:Unitemized_Cred_Card_Total d:"The total of all unitemized credit card expenditures made by the filer during the reporting period" t:dataTypeName=money

entity e:b2pc-2s8n l:"Campaign Finance Data - Report Detail Dataset" t:url=https://data.austintexas.gov/api/views/b2pc-2s8n

property e:b2pc-2s8n t:meta.view v:id=b2pc-2s8n v:category=Government v:averageRating=0 v:name="Campaign Finance Data - Report Detail Dataset"

property e:b2pc-2s8n t:meta.view.owner v:id=fjfv-27ab v:screenName="Kathryn Darnall" v:displayName="Kathryn Darnall"

property e:b2pc-2s8n t:meta.view.tableauthor v:id=fjfv-27ab v:screenName="Kathryn Darnall" v:roleName=editor v:displayName="Kathryn Darnall"
```