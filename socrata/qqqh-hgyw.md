# Life Safety Evaluations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/life-safety-evaluations-e3f53) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/qqqh-hgyw) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/qqqh-hgyw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/qqqh-hgyw/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | qqqh-hgyw |
| Name | Life Safety Evaluations |
| Attribution | City of Chicago |
| Category | Buildings |
| Tags | safety, inspections |
| Created | 2012-02-02T21:35:39Z |
| Publication Date | 2015-04-17T19:25:07Z |

## Description

This dataset is a listing of the report status of all residential buildings required to submit a Life Safety Evaluation under city ordinance. Because the Chicago building code has since 1975 required new high-rise residential buildings to be constructed with sprinkler systems, the Life Safety Ordinance mostly impacted high-rise residential buildings constructed prior to 1975.  This dataset does not describe the overall safety of a building, only whether or not the life safety evaluation was submitted and approved by the City of Chicago. Please note that the majority of reports ?failed? initially as a result of a new reporting process and changes to building standards. For more information on the City?s life safety ordinance, visit http://bit.ly/ygORcq. Data Owner: Buildings. Frequency: Data is updated monthly.

## Columns

```ls
| Included | Schema Type | Field Name                                                                                                                         | Name                                                                                                                                 | Data Type     | Render Type   |
| ======== | =========== | ================================================================================================================================== | ==================================================================================================================================== | ============= | ============= |
| Yes      | series tag  | building_street_number                                                                                                             | Building Street Number                                                                                                               | text          | text          |
| Yes      | series tag  | building_street_direction                                                                                                          | Building Street Direction                                                                                                            | text          | text          |
| Yes      | series tag  | building_street                                                                                                                    | Building Street Name                                                                                                                 | text          | text          |
| Yes      | series tag  | building_street_type_i                                                                                                             | Building Street Type I                                                                                                               | text          | text          |
| Yes      | series tag  | original_lse_report_approved                                                                                                       | Report Status - Original LSE Report Approved                                                                                         | text          | text          |
| Yes      | series tag  | lse_report_submitted                                                                                                               | Report Status - LSE Report Resubmitted                                                                                               | text          | text          |
| Yes      | series tag  | resubmitted_report_approved                                                                                                        | Report Status - Resubmitted Report Approved                                                                                          | text          | text          |
| Yes      | series tag  | self_reported_by_building_representative                                                                                           | Construction Status (Self-Reported by Building Representative)                                                                       | text          | text          |
| Yes      | series tag  | installing_a_full_sprinkler_system_instead_of_an_alternative_lse_compliance_scope_of_work_self_reported_by_building_representative | Installing a full sprinkler system instead of an alternative LSE Compliance scope of work (Self-Reported by Building Representative) | text          | text          |
| Yes      | series tag  | results_of_lse_committee_review                                                                                                    | Inspection Status - Inspection Results                                                                                               | text          | text          |
| No       |             | lse_report_reviewed_on_date                                                                                                        | Inspection Status - Date Passed                                                                                                      | calendar_date | calendar_date |
| Yes      | time        | scheduled_inspection_date                                                                                                          | Scheduled Inspection Date                                                                                                            | calendar_date | calendar_date |
| No       |             | rescheduled_inspection_date                                                                                                        | Rescheduled Inspection Date                                                                                                          | calendar_date | calendar_date |
```

## Time Field

```ls
Value = scheduled_inspection_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = lse_report_reviewed_on_date,rescheduled_inspection_date
```

## Data Commands

```ls
series e:qqqh-hgyw d:2015-04-17T12:24:34.000Z t:resubmitted_report_approved="Not Applicable" t:building_street=LaSalle t:installing_a_full_sprinkler_system_instead_of_an_alternative_lse_compliance_scope_of_work_self_reported_by_building_representative=No t:building_street_direction=N. t:results_of_lse_committee_review=FAILED t:building_street_number=1 t:self_reported_by_building_representative="In Process" t:lse_report_submitted="Not Applicable" t:original_lse_report_approved=Yes t:building_street_type_i=St. m:row_number.qqqh-hgyw=1

series e:qqqh-hgyw d:2015-04-17T12:24:34.000Z t:resubmitted_report_approved="Not Applicable" t:building_street=Schiller t:installing_a_full_sprinkler_system_instead_of_an_alternative_lse_compliance_scope_of_work_self_reported_by_building_representative=No t:building_street_direction=E. t:results_of_lse_committee_review=Passed t:building_street_number=1 t:self_reported_by_building_representative="Work Not Started" t:lse_report_submitted="Not Applicable" t:original_lse_report_approved=Yes t:building_street_type_i=St. m:row_number.qqqh-hgyw=2

series e:qqqh-hgyw d:2015-04-17T12:24:34.000Z t:resubmitted_report_approved="Not Applicable" t:building_street=Scott t:installing_a_full_sprinkler_system_instead_of_an_alternative_lse_compliance_scope_of_work_self_reported_by_building_representative=No t:building_street_direction=E. t:results_of_lse_committee_review=FAILED t:building_street_number=1 t:self_reported_by_building_representative="Ready for Inspection" t:lse_report_submitted="Not Applicable" t:original_lse_report_approved=Yes t:building_street_type_i=Ave. m:row_number.qqqh-hgyw=3
```

## Meta Commands

```ls
metric m:row_number.qqqh-hgyw p:long l:"Row Number"

entity e:qqqh-hgyw l:"Life Safety Evaluations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/qqqh-hgyw

property e:qqqh-hgyw t:meta.view v:id=qqqh-hgyw v:category=Buildings v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Life Safety Evaluations" v:attribution="City of Chicago"

property e:qqqh-hgyw t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:qqqh-hgyw t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| building_street_number | building_street_direction | building_street | building_street_type_i | original_lse_report_approved | lse_report_submitted | resubmitted_report_approved | self_reported_by_building_representative | installing_a_full_sprinkler_system_instead_of_an_alternative_lse_compliance_scope_of_work_self_reported_by_building_representative | results_of_lse_committee_review | lse_report_reviewed_on_date | scheduled_inspection_date | rescheduled_inspection_date | 
| ====================== | ========================= | =============== | ====================== | ============================ | ==================== | =========================== | ======================================== | ================================================================================================================================== | =============================== | =========================== | ========================= | =========================== | 
| 1                      | N.                        | LaSalle         | St.                    | Yes                          | Not Applicable       | Not Applicable              | In Process                               | No                                                                                                                                 | FAILED                          |                             |                           |                             | 
| 1                      | E.                        | Schiller        | St.                    | Yes                          | Not Applicable       | Not Applicable              | Work Not Started                         | No                                                                                                                                 | Passed                          |                             |                           |                             | 
| 1                      | E.                        | Scott           | Ave.                   | Yes                          | Not Applicable       | Not Applicable              | Ready for Inspection                     | No                                                                                                                                 | FAILED                          |                             |                           |                             | 
| 2                      | E.                        | Oak             | St.                    | No                           | Yes                  | Yes                         | Work Not Started                         | No                                                                                                                                 | FAILED                          |                             |                           |                             | 
| 5                      | S.                        | Wabash          | Ave.                   | No                           | Yes                  | No                          | Ready for Inspection                     | No                                                                                                                                 | In Court                        |                             |                           |                             | 
| 8                      | S.                        | Michigan        | Ave.                   | Yes                          | Not Applicable       | Not Applicable              | Ready for Inspection                     | No                                                                                                                                 | Passed                          |                             |                           |                             | 
| 10                     | S.                        | Canal           | St.                    | No                           | Yes                  | Yes                         | Not Submitted                            | Yes                                                                                                                                | CFD/INCOMPLETE                  |                             |                           |                             | 
| 10                     | W.                        | Elm             | St.                    | No                           | Yes                  | Yes                         | Work Not Started                         | No                                                                                                                                 | FAILED                          |                             |                           |                             | 
| 14                     | W.                        | Elm             | St.                    | No                           | No                   | Yes                         | Not Submitted                            | No                                                                                                                                 | FAILED                          |                             |                           |                             | 
| 17                     | N.                        | State           | St.                    | Yes                          | Not Applicable       | Not Applicable              | Ready for Inspection                     | Yes                                                                                                                                | Passed                          |                             |                           |                             | 
```