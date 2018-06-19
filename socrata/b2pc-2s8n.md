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
| Category | City Government |
| Tags | election, financial, campaign finance, contributions, expenditures, city clerk |
| Created | 2016-01-14T17:17:15Z |
| Publication Date | 2016-10-28T21:03:32Z |

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
| No       |                | election_date              | Election_Date              | calendar_date | calendar_date |
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
series e:b2pc-2s8n d:2016-07-15T00:00:00.000Z t:treasurer_city="Austin, TX, 78717" t:form_type="C/OH - Candidate/Officeholder Campaign Finance Report" t:treasurer_name="Landuyt, Noel" t:filer_name="Flannigan, James T. ""Jimmy""" t:report_type="July 15 Seminannual Report" t:filer_city="Austin, TX, 78729" t:link_to_report="http://www.austintexas.gov/edims/document.cfm?id=258182" t:report_id=R20160715180436 t:filer_phone=5129178428 t:name_as_reported="James, Flannigan, T., ""Jimmy""" t:office_sought="District 6" t:election_type=General t:treasurer_phone=5127738437 m:unitemized_cred_card_total=0 m:unitemized_unpaid_total=0 m:outstand_loan=0 m:unitemized_inkind_total=0 m:unitemized_loan_total=0 m:contrib_balance=20487.21 m:contrib_total=46951.54 m:unitemized_pledge_total=0 m:unitemized_expend_total=0 m:unitemized_contrib_total=0 m:expend_total=12209.9

series e:b2pc-2s8n d:2016-07-14T00:00:00.000Z t:treasurer_city="Austin, TX, 78746" t:office_held="District 10" t:form_type="C/OH - Candidate/Officeholder Campaign Finance Report" t:treasurer_name="Little, Lew, Jr." t:filer_name="Gallo, Sheri P." t:report_type="July 15 Seminannual Report" t:filer_city="Austin, TX, 78755" t:link_to_report="http://www.austintexas.gov/edims/document.cfm?id=258109" t:report_id=R20160715181229 t:filer_phone=512-978-2110 t:name_as_reported="Gallo, Sheri" t:office_sought="District 10" t:election_type=General t:treasurer_phone=512-480-9702 m:unitemized_cred_card_total=0 m:unitemized_unpaid_total=0 m:outstand_loan=0 m:unitemized_inkind_total=0 m:unitemized_loan_total=0 m:contrib_balance=0 m:contrib_total=0 m:unitemized_pledge_total=0 m:unitemized_expend_total=0 m:unitemized_contrib_total=0 m:expend_total=0

series e:b2pc-2s8n d:2016-07-15T00:00:00.000Z t:treasurer_city="Austin, TX, 78731" t:form_type="C/OH - Candidate/Officeholder Campaign Finance Report" t:treasurer_name="Baxter, Audrey" t:filer_name="Gauldin, Natalie B." t:report_type="July 15 Seminannual Report" t:filer_city="Austin, TX, 78756" t:link_to_report="http://www.austintexas.gov/edims/document.cfm?id=258191" t:report_id=R20160715173219 t:filer_phone=5126562759 t:name_as_reported="Gauldin, Natalie" t:office_sought="District 7" t:election_type=General t:treasurer_phone=5124180239 m:unitemized_cred_card_total=0 m:unitemized_unpaid_total=0 m:outstand_loan=0 m:unitemized_inkind_total=0 m:unitemized_loan_total=0 m:contrib_balance=18711.89 m:contrib_total=20460 m:unitemized_pledge_total=0 m:unitemized_expend_total=0 m:unitemized_contrib_total=0 m:expend_total=1748.11
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

property e:b2pc-2s8n t:meta.view d:2017-09-25T07:30:02.765Z v:averageRating=0 v:name="Campaign Finance Data - Report Detail Dataset" v:id=b2pc-2s8n v:category="City Government"

property e:b2pc-2s8n t:meta.view.owner d:2017-09-25T07:30:02.765Z v:displayName="Kathryn Darnall" v:lastNotificationSeenAt=1501527806 v:id=fjfv-27ab v:screenName="Kathryn Darnall"

property e:b2pc-2s8n t:meta.view.tableauthor d:2017-09-25T07:30:02.765Z v:displayName="Kathryn Darnall" v:lastNotificationSeenAt=1501527806 v:roleName=editor v:id=fjfv-27ab v:screenName="Kathryn Darnall"
```

## Top Records

```ls
| filer_name                                   | form_type                                                 | report_type                   | report_type2 | link_to_report                                                         | date_filed          | filer_address_2               | filer_city        | report_id       | treasurer_name                       | treasurer_address_2      | treasurer_city        | date_due            | name_as_reported                             | filer_phone  | treasurer_state | treasurer_zip_code | treasurer_phone | period_from         | period_to           | election_date       | election_type | office_held | office_sought | unitemized_contrib_total | contrib_total | unitemized_expend_total | expend_total | contrib_balance | outstand_loan | unitemized_inkind_total | unitemized_pledge_total | unitemized_loan_total | unitemized_unpaid_total | unitemized_cred_card_total | 
| ============================================ | ========================================================= | ============================= | ============ | ====================================================================== | =================== | ============================= | ================= | =============== | ==================================== | ======================== | ===================== | =================== | ============================================ | ============ | =============== | ================== | =============== | =================== | =================== | =================== | ============= | =========== | ============= | ======================== | ============= | ======================= | ============ | =============== | ============= | ======================= | ======================= | ===================== | ======================= | ========================== | 
| Flannigan, James T. "Jimmy"                  | C/OH - Candidate/Officeholder Campaign Finance Report     | July 15 Seminannual Report    |              | [http://www.austintexas.gov/edims/document.cfm?id=258182, View Report] | 2016-07-15T00:00:00 | 12304 B Cahone Trl            | Austin, TX, 78729 | R20160715180436 | Landuyt, Noel                        | 10100 Lachlan Dr.        | Austin, TX, 78717     | 2016-07-15T00:00:00 | James, Flannigan, T., "Jimmy"                | 5129178428   |                 |                    | 5127738437      | 2016-05-03T00:00:00 | 2016-06-30T00:00:00 | 2016-11-08T00:00:00 | General       |             | District 6    | 0                        | 46951.54      | 0                       | 12209.9      | 20487.21        | 0             | 0                       | 0                       | 0                     | 0                       | 0                          | 
| Austin Forward                               | ATX_1 - Independent Expenditures not by a Candidate       |                               |              | [http://www.austintexas.gov/edims/document.cfm?id=263528, View Report] | 2016-09-21T00:00:00 | P.O. Box 302854               | Austin, TX, 78703 | R20160922165921 | Hernandez, Laura, Ms.                | 710 Colorado Street, #6C | Austin, TX, 78701     |                     | Austin Forward PAC (aka Move Austin Forward) |              |                 |                    |                 |                     | 2016-09-20T00:00:00 |                     |               |             |               |                          |               |                         |              |                 |               |                         |                         |                       |                         |                            | 
| Gallo, Sheri P.                              | C/OH - Candidate/Officeholder Campaign Finance Report     | July 15 Seminannual Report    |              | [http://www.austintexas.gov/edims/document.cfm?id=258109, View Report] | 2016-07-14T00:00:00 | PO Box 26550                  | Austin, TX, 78755 | R20160715181229 | Little, Lew, Jr.                     | 2806 Stratford Drive     | Austin, TX, 78746     | 2016-07-15T00:00:00 | Gallo, Sheri                                 | 512-978-2110 |                 |                    | 512-480-9702    | 2016-01-01T00:00:00 | 2016-06-30T00:00:00 | 2016-11-08T00:00:00 | General       | District 10 | District 10   | 0                        | 0             | 0                       | 0            | 0               | 0             | 0                       | 0                       | 0                     | 0                       | 0                          | 
| Gauldin, Natalie B.                          | C/OH - Candidate/Officeholder Campaign Finance Report     | July 15 Seminannual Report    |              | [http://www.austintexas.gov/edims/document.cfm?id=258191, View Report] | 2016-07-15T00:00:00 | 5015 Shoal Creek Blvd         | Austin, TX, 78756 | R20160715173219 | Baxter, Audrey                       | 7304 Valburn Dr.         | Austin, TX, 78731     | 2016-07-15T00:00:00 | Gauldin, Natalie                             | 5126562759   |                 |                    | 5124180239      | 2016-06-22T00:00:00 | 2016-06-30T00:00:00 | 2016-11-08T00:00:00 | General       |             | District 7    | 0                        | 20460         | 0                       | 1748.11      | 18711.89        | 0             | 0                       | 0                       | 0                     | 0                       | 0                          | 
| Pressley, Laura                              | C/OH - Candidate/Officeholder Campaign Finance Report     | July 15 Seminannual Report    |              | [http://www.austintexas.gov/edims/document.cfm?id=258178, View Report] | 2016-07-26T00:00:00 | 10203 Woodglen                | Austin, TX, 78753 | R20160726163007 | Acevedo, Fidel                       | 3807 Prairie             | Austin, TX, 78728     | 2016-07-15T00:00:00 | Pressley, Laura, A                           | 512-762-3825 |                 |                    | 512-775-7276    | 2016-01-01T00:00:00 | 2016-06-30T00:00:00 | 2014-12-16T00:00:00 | Runoff        |             | District 4    | 7641                     | 41484.3       | 1020.44                 | 61791.69     | 6213.73         | 76972.2       | 0                       | 0                       | 0                     | 0                       | 0                          | 
| Renteria, Sabino "Pio"                       | C/OH - Candidate/Officeholder Campaign Finance Report     | July 15 Seminannual Report    |              | [http://www.austintexas.gov/edims/document.cfm?id=258044, View Report] | 2016-07-14T00:00:00 | 1511 Haskell St.              | Austin, TX, 78702 | R20160715181117 | Valdez, Cristina                     | 902 E. 2nd St.           | Austin, TX, 78702     | 2016-07-15T00:00:00 | Renteria, Sabino, "Pio"                      | 5124786770   |                 |                    | 5127890309      | 2016-01-01T00:00:00 | 2016-06-30T00:00:00 | 2018-11-06T00:00:00 | General       | District 3  |               | 0                        | 0             | 382.27                  | 1733.27      | 5737.9          | 0             | 0                       | 0                       | 0                     | 0                       | 0                          | 
| Zimmerman, Donald S. "Don"                   | C/OH - Candidate/Officeholder Campaign Finance Report     | July 15 Seminannual Report    |              | [http://www.austintexas.gov/edims/document.cfm?id=258082, View Report] | 2016-07-15T00:00:00 | 10901 Enchanted Rock Cove     | Austin, TX, 78726 | R20160715174406 | Kelly, Timothy, Mr.                  | 1727 Warwick Way         | Cedar Park, TX, 78613 | 2016-07-15T00:00:00 | Zimmerman, Donald, Mr., S, "Don"             | 512-577-8842 |                 |                    | 512-919-9772    | 2016-01-01T00:00:00 | 2016-07-15T00:00:00 | 2016-11-08T00:00:00 | General       | District 6  | District 6    | 0                        | 5625          | 0                       | 8018.22      | 9061.91         | 0             | 0                       | 0                       | 0                     | 0                       | 0                          | 
| Zimmerman, Donald S. "Don"                   | C/OH - Candidate/Officeholder Campaign Finance Report     | January 15 Seminannual Report |              | [http://www.austintexas.gov/edims/document.cfm?id=246415, View Report] | 2016-01-11T00:00:00 | 13492 Research Blvd, #120-141 | Austin, TX, 78750 | R20160125164624 | Zimmerman, Jennifer, Ms., L, "Jenny" | 10901 Enchanted Rock Cv. | Austin, TX, 78726     | 2016-01-15T00:00:00 | Zimmerman, Donald, Mr., S, "Don"             | 512-577-8842 |                 |                    | 512-250-3015    | 2015-07-01T00:00:00 | 2015-12-31T00:00:00 | 2016-11-08T00:00:00 | General       | District 6  | District 6    | 40                       | 19842.75      | 0                       | 132.33       | 14998.32        | 18000         | 0                       | 0                       | 0                     | 0                       | 0                          | 
| Sensible Transportation Solutions for Austin | SPAC - Specific-Purpose Committee Campaign Finance Report | July 15 Seminannual Report    |              | [http://www.austintexas.gov/edims/document.cfm?id=258014, View Report] | 2016-07-14T00:00:00 | PO Box 146                    | Austin, TX, 78767 | R20160715112740 | Levy, Michael, R.                    | 515 Congress, Suite 2375 | Austin, TX, 78701     | 2016-07-15T00:00:00 | Sensible Transportation Solutions for Austin |              |                 |                    | 512-450-5100    | 2016-01-01T00:00:00 | 2016-06-30T00:00:00 |                     |               |             |               | 0                        | 0             | 0                       | 0            | 0               | 0             | 0                       | 0                       | 0                     | 0                       | 0                          | 
| Zimmerman, Donald S. "Don"                   | C/OH - Candidate/Officeholder Campaign Finance Report     | July 15 Seminannual Report    |              | [http://www.austintexas.gov/edims/document.cfm?id=258079, View Report] | 2016-07-14T00:00:00 | 10901 Enchanted Rock Cove     | Austin, TX, 78726 | R20160808101110 | Kelly, Timothy, Mr.                  | 1727 Warwick Way         | Cedar Park, TX, 78613 | 2016-07-15T00:00:00 | Zimmerman, Donald, Mr., S, "Don"             | 512-577-8842 |                 |                    | 512-919-9772    | 2016-05-12T00:00:00 | 2016-07-15T00:00:00 | 2016-11-08T00:00:00 | General       | District 6  | District 6    | 1000                     | 35707         | 0                       | 4754.23      | 30952.97        | 18000         | 0                       | 0                       | 0                     | 0                       | 0                          | 
```