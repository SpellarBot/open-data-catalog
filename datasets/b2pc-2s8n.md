# Campaign Finance Data - Report Detail Dataset

## Dataset

* [Dataset URL](https://data.austintexas.gov/api/views/b2pc-2s8n/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/campaign-finance-data-report-detail-dataset)
* Id = b2pc-2s8n
* Name = Campaign Finance Data - Report Detail Dataset
* Category = Government
* Tags = [election, financial, campaign finance, contributions, expenditures, city clerk]
* Created = 2016-01-14T17:17:15Z
* Publication Date = 2016-10-28T21:03:32Z
* Rows Updated = 2017-01-23T15:48:17Z

## Description

This dataset contains data about the Campaign Finance Report received by a filer.  The Reports table contains information about the type of report filed, the due date, original filing date, and transaction totals.  To access the Transactions table, where individual transactions are listed, please go to: https://data.austintexas.gov/Government/Campaign-Finance-Data-Transaction-Detail-Dataset/g4yx-aw9r

A data dictionary for this dataset is available at http://www.austintexas.gov/edims/document.cfm?id=247730

## Columns

```ls
| Name                       | Field Name                 | Data Type     | Render Type   | Schema Type    | Included | 
| ========================== | ========================== | ============= | ============= | ============== | ======== | 
| Filer_Name                 | filer_name                 | text          | text          | series tag     | Yes      | 
| Form                       | form_type                  | text          | text          | series tag     | Yes      | 
| Report_Type                | report_type                | text          | text          | series tag     | Yes      | 
| Report_Type2               | report_type2               | text          | text          | series tag     | Yes      | 
| View_Report                | link_to_report             | url           | url           | series tag     | Yes      | 
| Date_Filed                 | date_filed                 | calendar_date | calendar_date | time           | Yes      | 
| Filer_Address              | filer_address_2            | text          | text          | series tag     | Yes      | 
| Filer_City_State_Zip       | filer_city                 | text          | text          | series tag     | Yes      | 
| Report_ID                  | report_id                  | text          | text          | series tag     | Yes      | 
| Treasurer_Name             | treasurer_name             | text          | text          | series tag     | Yes      | 
| Treasurer_Address          | treasurer_address_2        | text          | text          | series tag     | Yes      | 
| Treasurer_City_State_Zip   | treasurer_city             | text          | text          | series tag     | Yes      | 
| Date_Due                   | date_due                   | calendar_date | calendar_date |                | No       | 
| Name_as_Reported           | name_as_reported           | text          | text          | series tag     | Yes      | 
| Filer_Phone                | filer_phone                | text          | text          | series tag     | Yes      | 
| Treasurer_State            | treasurer_state            | text          | text          | series tag     | Yes      | 
| Treasurer_Zip_Code         | treasurer_zip_code         | text          | text          | series tag     | Yes      | 
| Treasurer_Phone            | treasurer_phone            | text          | text          | series tag     | Yes      | 
| Period_From                | period_from                | calendar_date | calendar_date |                | No       | 
| Period_To                  | period_to                  | calendar_date | calendar_date |                | No       | 
| Election_Date              | election_date              | calendar_date | calendar_date |                | No       | 
| Election_Type              | election_type              | text          | text          | series tag     | Yes      | 
| Office_Held                | office_held                | text          | text          | series tag     | Yes      | 
| Office_Sought              | office_sought              | text          | text          | series tag     | Yes      | 
| Unitemized_Contrib_Total   | unitemized_contrib_total   | money         | money         | numeric metric | Yes      | 
| Contrib_Total              | contrib_total              | money         | money         | numeric metric | Yes      | 
| Unitemized_Expend_Total    | unitemized_expend_total    | money         | money         | numeric metric | Yes      | 
| Expend_Total               | expend_total               | money         | money         | numeric metric | Yes      | 
| Contrib_Balance            | contrib_balance            | money         | money         | numeric metric | Yes      | 
| Outstand_Loan              | outstand_loan              | money         | money         | numeric metric | Yes      | 
| Unitemized_InKind_Total    | unitemized_inkind_total    | money         | money         | numeric metric | Yes      | 
| Unitemized_Pledge_Total    | unitemized_pledge_total    | money         | money         | numeric metric | Yes      | 
| Unitemized_Loan_Total      | unitemized_loan_total      | money         | money         | numeric metric | Yes      | 
| Unitemized_Unpaid_Total    | unitemized_unpaid_total    | money         | money         | numeric metric | Yes      | 
| Unitemized_Cred_Card_Total | unitemized_cred_card_total | money         | money         | numeric metric | Yes      | 
```

## Time Field

```ls
Value = date_filed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = election_date,date_due,period_from,period_to
Annotation Fields = 
```

## Data Commands

```ls
series e:b2pc-2s8n d:2016-07-15T00:00:00.000Z t:filer_city="Austin, TX, 78729" t:filer_name="Flannigan, James T. ""Jimmy""" t:treasurer_name="Landuyt, Noel" t:office_sought="District 6" t:election_type=General t:report_type="July 15 Seminannual Report" t:treasurer_phone=5127738437 t:treasurer_city="Austin, TX, 78717" t:treasurer_address_2="10100 Lachlan Dr." t:form_type="C/OH - Candidate/Officeholder Campaign Finance Report" t:name_as_reported="James, Flannigan, T., ""Jimmy""" t:filer_address_2="12304 B Cahone Trl" t:report_id=R20160715180436 t:filer_phone=5129178428 m:unitemized_inkind_total=0 m:unitemized_unpaid_total=0 m:expend_total=12209.9 m:unitemized_contrib_total=0 m:unitemized_expend_total=0 m:unitemized_pledge_total=0 m:contrib_balance=20487.21 m:unitemized_loan_total=0 m:contrib_total=46951.54 m:outstand_loan=0 m:unitemized_cred_card_total=0

series e:b2pc-2s8n d:2016-07-14T00:00:00.000Z t:filer_city="Austin, TX, 78755" t:filer_name="Gallo, Sheri P." t:treasurer_name="Little, Lew, Jr." t:office_sought="District 10" t:election_type=General t:report_type="July 15 Seminannual Report" t:treasurer_phone=512-480-9702 t:treasurer_city="Austin, TX, 78746" t:treasurer_address_2="2806 Stratford Drive" t:form_type="C/OH - Candidate/Officeholder Campaign Finance Report" t:name_as_reported="Gallo, Sheri" t:filer_address_2="PO Box 26550" t:report_id=R20160715181229 t:filer_phone=512-978-2110 t:office_held="District 10" m:unitemized_inkind_total=0 m:unitemized_unpaid_total=0 m:expend_total=0 m:unitemized_contrib_total=0 m:unitemized_expend_total=0 m:unitemized_pledge_total=0 m:contrib_balance=0 m:unitemized_loan_total=0 m:contrib_total=0 m:outstand_loan=0 m:unitemized_cred_card_total=0

series e:b2pc-2s8n d:2016-07-15T00:00:00.000Z t:filer_city="Austin, TX, 78756" t:filer_name="Gauldin, Natalie B." t:treasurer_name="Baxter, Audrey" t:office_sought="District 7" t:election_type=General t:report_type="July 15 Seminannual Report" t:treasurer_phone=5124180239 t:treasurer_city="Austin, TX, 78731" t:treasurer_address_2="7304 Valburn Dr." t:form_type="C/OH - Candidate/Officeholder Campaign Finance Report" t:name_as_reported="Gauldin, Natalie" t:filer_address_2="5015 Shoal Creek Blvd" t:report_id=R20160715173219 t:filer_phone=5126562759 m:unitemized_inkind_total=0 m:unitemized_unpaid_total=0 m:expend_total=1748.11 m:unitemized_contrib_total=0 m:unitemized_expend_total=0 m:unitemized_pledge_total=0 m:contrib_balance=18711.89 m:unitemized_loan_total=0 m:contrib_total=20460 m:outstand_loan=0 m:unitemized_cred_card_total=0
```

## Meta Commands

```ls
entity e:b2pc-2s8n l:"Campaign Finance Data - Report Detail Dataset" t:url=https://data.austintexas.gov/api/views/b2pc-2s8n

property e:b2pc-2s8n t:meta.view d:2017-03-03T14:39:20.383Z v:id=b2pc-2s8n v:category=Government v:averageRating=0 v:name="Campaign Finance Data - Report Detail Dataset"

property e:b2pc-2s8n t:meta.view.owner d:2017-03-03T14:39:20.383Z v:id=fjfv-27ab v:screenName="Kathryn Darnall" v:roleName=editor v:displayName="Kathryn Darnall"

property e:b2pc-2s8n t:meta.view.tableauthor d:2017-03-03T14:39:20.383Z v:id=fjfv-27ab v:screenName="Kathryn Darnall" v:roleName=editor v:displayName="Kathryn Darnall"
```