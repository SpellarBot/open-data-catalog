# 2015 LeanCT Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-leanct-report) |
| Metadata | [Link](https://data.ct.gov/api/views/272b-pcxv) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/272b-pcxv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/272b-pcxv/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 272b-pcxv |
| Name | 2015 LeanCT Report |
| Category | Government |
| Tags | leanct, lean, process improvement, kaizen |
| Created | 2016-01-28T14:04:48Z |
| Publication Date | 2016-01-28T14:17:54Z |

## Description

Lean and process improvement project detail by agency

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | =========== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag  | agencyname                | AgencyName                | text          | text          |
| Yes      | series tag  | project_event_name        | Project Event/Name        | text          | text          |
| Yes      | series tag  | division_program          | Division/Program          | text          | text          |
| Yes      | series tag  | opportunity_issue_problem | Opportunity/Issue/Problem | text          | text          |
| Yes      | series tag  | type_of_event             | Type of Event             | text          | text          |
| Yes      | series tag  | project_category          | Project Category          | text          | text          |
| Yes      | time        | project_start_date        | Project Start Date        | calendar_date | calendar_date |
| No       |             | project_completion_date   | Project Completion Date   | calendar_date | calendar_date |
| Yes      | series tag  | project_status            | Project Status            | text          | text          |
| Yes      | series tag  | project_funded_by         | Project Funded By         | text          | text          |
```

## Time Field

```ls
Value = project_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = project_completion_date
```

## Data Commands

```ls
series e:272b-pcxv d:2014-12-12T00:00:00.000Z t:division_program="CHRO Regional Offices/Legal" t:project_status=Initiated t:opportunity_issue_problem="What steps and improvements to the Commission's process can be implemented to reduce the number of aged cases?" t:project_category="Increased efficiency/productivity;#2;#Processing time;#5;#Processing steps;#6" t:agencyname="Commission on Human Rights and Opportunities" t:project_funded_by="My Agency" t:type_of_event="Improvement Activity" t:project_event_name="Aged Inventory Reduction Plan" m:row_number.272b-pcxv=1

series e:272b-pcxv d:2014-12-12T00:00:00.000Z t:division_program="Executive Director/Legal Division" t:project_status=Complete t:opportunity_issue_problem="By bringing all departments of the agency together for training, agency uniformity can be increased, boosting efficiency and productivity in turn." t:project_category="Increased efficiency/productivity;#2" t:agencyname="Commission on Human Rights and Opportunities" t:project_funded_by="My Agency" t:type_of_event="Improvement Activity" t:project_event_name="Full Agency Training" m:row_number.272b-pcxv=2

series e:272b-pcxv d:2015-06-30T00:00:00.000Z t:division_program="Full Agency" t:project_status=Initiated t:opportunity_issue_problem="Much of the agency's forms are in paper-only format. By making these forms electronic and available online, there will be increased availability, responsiveness, and faster processing times and accuracy. There will also be reduced costs and a positive environmental impact." t:project_category="Customer experience;#4;#Increased efficiency/productivity;#2;#Cost savings/increased revenue;#7;#Processing time;#5;#Response time;#3;#Processing steps;#6" t:agencyname="Commission on Human Rights and Opportunities" t:project_funded_by="My Agency" t:type_of_event="Improvement Activity" t:project_event_name="Paperless Committee" m:row_number.272b-pcxv=3
```

## Meta Commands

```ls
metric m:row_number.272b-pcxv p:long l:"Row Number"

entity e:272b-pcxv l:"2015 LeanCT Report" t:url=https://data.ct.gov/api/views/272b-pcxv

property e:272b-pcxv t:meta.view v:id=272b-pcxv v:category=Government v:averageRating=0 v:name="2015 LeanCT Report"

property e:272b-pcxv t:meta.view.owner v:id=6ypf-grnx v:screenName="Jamie Gamble" v:displayName="Jamie Gamble"

property e:272b-pcxv t:meta.view.tableauthor v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```

## Top Records

```ls
| agencyname                                   | project_event_name                                                               | division_program                           | opportunity_issue_problem                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | type_of_event        | project_category                                                                                                                                           | project_start_date  | project_completion_date | project_status | project_funded_by | 
| ============================================ | ================================================================================ | ========================================== | =================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ==================== | ========================================================================================================================================================== | =================== | ======================= | ============== | ================= | 
| Commission on Human Rights and Opportunities | Aged Inventory Reduction Plan                                                    | CHRO Regional Offices/Legal                | What steps and improvements to the Commission's process can be implemented to reduce the number of aged cases?                                                                                                                                                                                                                                                                                                                                                                                                                                      | Improvement Activity | Increased efficiency/productivity;#2;#Processing time;#5;#Processing steps;#6                                                                              | 2014-12-12T00:00:00 | 2015-12-31T00:00:00     | Initiated      | My Agency         | 
| Commission on Human Rights and Opportunities | Full Agency Training                                                             | Executive Director/Legal Division          | By bringing all departments of the agency together for training, agency uniformity can be increased, boosting efficiency and productivity in turn.                                                                                                                                                                                                                                                                                                                                                                                                  | Improvement Activity | Increased efficiency/productivity;#2                                                                                                                       | 2014-12-12T00:00:00 | 2014-12-12T00:00:00     | Complete       | My Agency         | 
| Commission on Human Rights and Opportunities | Paperless Committee                                                              | Full Agency                                | Much of the agency's forms are in paper-only format. By making these forms electronic and available online, there will be increased availability, responsiveness, and faster processing times and accuracy. There will also be reduced costs and a positive environmental impact.                                                                                                                                                                                                                                                                   | Improvement Activity | Customer experience;#4;#Increased efficiency/productivity;#2;#Cost savings/increased revenue;#7;#Processing time;#5;#Response time;#3;#Processing steps;#6 | 2015-06-30T00:00:00 | 2015-12-31T00:00:00     | Initiated      | My Agency         | 
| Commission on Human Rights and Opportunities | Statutory Procedural Changes                                                     | Legislative Liaison/Legal Division         | Much of the Commission's process is grounded in Connecticut's statutes. In order to make necessary changes to our process to increase efficiency, legislation needs to be passed.                                                                                                                                                                                                                                                                                                                                                                   | Other                | Increased efficiency/productivity;#2                                                                                                                       | 2014-12-12T00:00:00 | 2015-06-30T00:00:00     | Complete       | My Agency         | 
| Commission on Human Rights and Opportunities | Uniformity Committee                                                             | CHRO Regional Offices                      | The Commission's regional offices currently employ their own forms and have slight variations in process. By making all of these forms and processes uniform, there will be greater efficiency and responsiveness throughout the agency.                                                                                                                                                                                                                                                                                                            | Improvement Activity | Processing steps;#6                                                                                                                                        | 2014-12-12T00:00:00 | 2016-06-03T00:00:00     | Complete       | My Agency         | 
| Connecticut Siting Council                   | Docket Management Workflow Process                                               |                                            |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                      | Cost savings/increased revenue;#7;#Customer experience;#4;#Increased efficiency/productivity;#2;#Processing time;#5;#Processing steps;#6                   |                     |                         | Complete       |                   | 
| Connecticut State Library                    | Records Disposition and Retention Schedule Creation/Modification Process Mapping | Office of the Public Records Administrator | The Office of the Public Records Administrator is using LEAN to identify areas to improve efficiency in two current manual, paper based processes for state agencies: records retention schedule creation and modification, and disposition authorization. The LEAN mapping sessions will determine how the disposition and retention schedule creation and modification processes can become automated with the implementation of IBM Atlas and FileNet as part of the Enterprise Content Management (ECM) project in collaboration with DAS/BEST. | Improvement Activity | Customer experience;#4;#Increased efficiency/productivity;#2;#Inter-agency;#1;#Processing steps;#6;#Processing time;#5;#Response time;#3                   | 2015-03-04T00:00:00 |                         | Complete       | Host Agency       | 
| Department of Administrative Services        | IT Procurement Process Improvement                                               | BEST                                       | Improve the IT procurement process by eliminating multiple and/or duplicative steps between the agency process and the DAS/BEST procurement processes in order to improve the efficiency and decrease the time it takes for approval and purchase of technology.                                                                                                                                                                                                                                                                                    | 5-day Lean Event     | Increased efficiency/productivity;#2;#Inter-agency;#1                                                                                                      | 2013-05-06T00:00:00 | 2013-05-10T00:00:00     | Complete       | OPM               | 
| Department of Administrative Services        | IT Service Management Process Improvement                                        | DAS/BEST                                   | Coming soon...                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | 5-day Lean Event     | Customer experience;#4;#Increased efficiency/productivity;#2;#Processing steps;#6;#Processing time;#5;#Response time;#3                                    | 2015-11-02T00:00:00 | 2015-11-06T00:00:00     | Initiated      | My Agency         | 
| Department of Administrative Services        | Procurement Catalog Management Review                                            | Prcourement                                | The process of obtaining, reviewing, cleansing and loading contract vendor catalgogs is complex, timeconsuming and involves many hands. There is a significant need to review these processes and streamline the steps involved, shorten the process and increase the number of catalogs available for agency purchasers to ensure ease of ordering.                                                                                                                                                                                                | 5-day Lean Event     | Increased efficiency/productivity;#2;#Customer experience;#4;#Processing steps;#6;#Processing time;#5                                                      | 2015-01-05T00:00:00 | 2015-01-09T00:00:00     | Complete       | My Agency         | 
```