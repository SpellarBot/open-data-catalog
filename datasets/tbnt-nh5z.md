# 2015 Kaizen Goals and Measures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-kaizen-goals-and-measures) |
| Metadata | [Link](https://data.ct.gov/api/views/tbnt-nh5z) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/tbnt-nh5z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/tbnt-nh5z/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | tbnt-nh5z |
| Name | 2015 Kaizen Goals and Measures |
| Category | Government |
| Tags | leanct, lean, process improvement, kaizen |
| Created | 2016-01-28T14:26:02Z |
| Publication Date | 2016-01-28T14:27:24Z |

## Description

Agency goals and measures related to Lean and process improvement projects

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | series tag     | agency_name                    | Agency Name                    | text          | text          |
| Yes      | series tag     | project_event_name             | Project Event/Name             | text          | text          |
| Yes      | series tag     | brief_description_overall_goal | Brief Description/Overall Goal | text          | text          |
| Yes      | series tag     | measure_kpi                    | Measure/KPI                    | text          | text          |
| Yes      | numeric metric | baseline_value                 | Baseline Value                 | number        | number        |
| Yes      | numeric metric | current_value                  | Current Value                  | number        | number        |
| Yes      | time           | current_date                   | Current Date                   | calendar_date | calendar_date |
| Yes      | numeric metric | goal_value                     | Goal Value                     | number        | number        |
| Yes      | series tag     | measurement_unit               | Measurement Unit               | text          | text          |
```

## Time Field

```ls
Value = current_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:tbnt-nh5z d:2015-08-25T00:00:00.000Z t:measurement_unit=Cases t:brief_description_overall_goal="Reduce the number of aged cases currently being handled by the Commission" t:measure_kpi="Reduce the number of aged cases each regional office has in its inventory." t:agency_name="Commission on Human Rights and Opportunities" t:project_event_name="Aged Inventory Reduction Plan" m:current_value=150 m:goal_value=0 m:baseline_value=150

series e:tbnt-nh5z d:2015-08-25T00:00:00.000Z t:measurement_unit=Forms t:brief_description_overall_goal="Transfer all intake forms and records to electronic format." t:measure_kpi="Make all intake and reporting forms available electronically to the extent possible, as well as Office of Public Hearing Cases." t:agency_name="Commission on Human Rights and Opportunities" t:project_event_name="Paperless Committee" m:current_value=2 m:goal_value=8 m:baseline_value=0

series e:tbnt-nh5z d:2015-08-25T00:00:00.000Z t:measurement_unit=Days t:brief_description_overall_goal="Reduce the time frames for investigation and process of complaints." t:measure_kpi="Reduce the time frames for investigation of complaints" t:agency_name="Commission on Human Rights and Opportunities" t:project_event_name="Statutory Procedural Changes" m:current_value=60 m:goal_value=60 m:baseline_value=90
```

## Meta Commands

```ls
metric m:baseline_value p:double l:"Baseline Value" t:dataTypeName=number

metric m:current_value p:double l:"Current Value" t:dataTypeName=number

metric m:goal_value p:integer l:"Goal Value" t:dataTypeName=number

entity e:tbnt-nh5z l:"2015 Kaizen Goals and Measures" t:url=https://data.ct.gov/api/views/tbnt-nh5z

property e:tbnt-nh5z t:meta.view v:id=tbnt-nh5z v:category=Government v:averageRating=0 v:name="2015 Kaizen Goals and Measures"

property e:tbnt-nh5z t:meta.view.owner v:id=6ypf-grnx v:screenName="Jamie Gamble" v:displayName="Jamie Gamble"

property e:tbnt-nh5z t:meta.view.tableauthor v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```

## Top Records

```ls
| agency_name                                  | project_event_name                       | brief_description_overall_goal                                                                  | measure_kpi                                                                                                                     | baseline_value | current_value | current_date        | goal_value | measurement_unit | 
| ============================================ | ======================================== | =============================================================================================== | =============================================================================================================================== | ============== | ============= | =================== | ========== | ================ | 
| Commission on Human Rights and Opportunities | Aged Inventory Reduction Plan            | Reduce the number of aged cases currently being handled by the Commission                       | Reduce the number of aged cases each regional office has in its inventory.                                                      | 150            | 150           | 2015-08-25T00:00:00 | 0          | Cases            | 
| Commission on Human Rights and Opportunities | Paperless Committee                      | Transfer all intake forms and records to electronic format.                                     | Make all intake and reporting forms available electronically to the extent possible, as well as Office of Public Hearing Cases. | 0              | 2             | 2015-08-25T00:00:00 | 8          | Forms            | 
| Commission on Human Rights and Opportunities | Statutory Procedural Changes             | Reduce the time frames for investigation and process of complaints.                             | Reduce the time frames for investigation of complaints                                                                          | 90             | 60            | 2015-08-25T00:00:00 | 60         | Days             | 
| Commission on Human Rights and Opportunities | Uniformity Committee                     | Reduce the number of different intake forms used by the agency.                                 | Reduce the number of intake forms used by the agency.                                                                           | 1000           | 500           | 2015-08-25T00:00:00 | 500        | Forms            | 
| Connecticut Siting Council                   | Docket Management Workflow Process       | Reduce paper, copying and postage for communication with nine-member Council and other parties. | Reduce costs by 25%                                                                                                             | 13119          | 5327          | 2015-04-23T00:00:00 | 5000       | Dollars          | 
| Department of Administrative Services        | IT Procurement Process Improvement       | Reduce the amount of time required to complete IT ?contractual purchases?                       | Reduce the amount of time required to complete IT ?contractual purchases?                                                       | 30             | 10            | 2014-07-12T00:00:00 | 5          | Days             | 
| Department of Administrative Services        | IT Procurement Process Improvement       | Reduce the amount of time required to complete IT Invitations to Bid (ITB)                      | Reduce the amount of time required to complete IT Invitations to Bid (ITB)                                                      | 60             | 55            | 2014-07-01T00:00:00 | 30         | Days             | 
| Department of Administrative Services        | IT Procurement Process Improvement       | Reduce the amount of time required to complete IT Request for Proposals (RFP)                   | Reduce the amount of time required to complete IT Request for Proposals (RFP)                                                   | 240            | 200           | 2014-07-01T00:00:00 | 180        | Days             | 
| Department of Administrative Services        | Procurement Catalog Management Review    | Streamline catalog management process through the elimination of extra steps                    | Reduction in steps to shorten process time and increase number of catalogs avilable                                             | 15             | 7             | 2015-08-26T00:00:00 | 7          | Steps            | 
| Department of Administrative Services        | School Construction Grant Program Review | Reduction in time for Payment process                                                           | Reduction in non-value added steps will help meet the goal of days required to complete process.                                | 23             | 20            | 2015-08-24T00:00:00 | 17         | Days             | 
```