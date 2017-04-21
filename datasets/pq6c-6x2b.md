# Illinois Criminal Justice Information Authority Active Grants Beginning SFY16

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/illinois-criminal-justice-information-authority-active-grants-beginning-sfy16) |
| Metadata | [Link](https://data.illinois.gov/api/views/pq6c-6x2b) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/pq6c-6x2b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/pq6c-6x2b/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | pq6c-6x2b |
| Name | Illinois Criminal Justice Information Authority Active Grants Beginning SFY16 |
| Attribution | Illinois Criminal Justice Information Authority |
| Category | Public Safety |
| Tags | icjia, illinois criminal justice information authority, grants, grantees, programs |
| Created | 2015-11-19T20:55:07Z |
| Publication Date | 2017-04-04T14:32:01Z |

## Description

List of all grants issued by the Illinois Criminal Justice Information Authority that were active at any point beginning with State Fiscal Year 2016 (7/1/2015) through the most recent quarter.

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                      | Data Type | Render Type |
| ======== | ============== | ===================================== | ========================================= | ========= | =========== |
| No       | time           | :updated_at                           | updated_at                                | meta_data | meta_data   |
| Yes      | series tag     | grantor_agency                        | Grantor Agency                            | text      | text        |
| Yes      | series tag     | grantee                               | Grantee                                   | text      | text        |
| Yes      | series tag     | description_of_purpose_of_award       | Description of Purpose of Award           | text      | text        |
| Yes      | numeric metric | grant_amount                          | Grant Amount                              | money     | money       |
| No       |                | start_date                            | Start Date                                | text      | text        |
| No       |                | completion_date                       | Completion Date                           | text      | text        |
| Yes      | numeric metric | duration_days_optional                | Duration (days) (optional)                | number    | number      |
| Yes      | series tag     | grantee_zip_code_optional             | Grantee Zip Code (optional)               | text      | text        |
| Yes      | series tag     | duplicate_ignore_in_explorer_optional | Duplicate - Ignore in Explorer (optional) | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = start_date,completion_date
```

## Data Commands

```ls
series e:pq6c-6x2b d:2015-11-19T12:55:17.000Z t:grantor_agency="Illinois Criminal Justice Information Authority" t:description_of_purpose_of_award="Crime prevention." t:grantee_zip_code_optional=60637 t:grantee="University of Chicago" m:grant_amount=83935 m:duration_days_optional=364

series e:pq6c-6x2b d:2015-11-19T12:55:17.000Z t:grantor_agency="Illinois Criminal Justice Information Authority" t:description_of_purpose_of_award="Crime prevention." t:grantee_zip_code_optional=60603 t:grantee="CHICAGO PUBLIC SCHOOLS" m:grant_amount=118896 m:duration_days_optional=364

series e:pq6c-6x2b d:2015-11-19T12:55:17.000Z t:grantor_agency="Illinois Criminal Justice Information Authority" t:description_of_purpose_of_award="Crime prevention." t:grantee_zip_code_optional=60602 t:grantee="Youth Guidance" m:grant_amount=71738 m:duration_days_optional=364
```

## Meta Commands

```ls
metric m:grant_amount p:integer l:"Grant Amount" t:dataTypeName=money

metric m:duration_days_optional p:integer l:"Duration (days) (optional)" t:dataTypeName=number

entity e:pq6c-6x2b l:"Illinois Criminal Justice Information Authority Active Grants Beginning SFY16" t:attribution="Illinois Criminal Justice Information Authority" t:url=https://data.illinois.gov/api/views/pq6c-6x2b

property e:pq6c-6x2b t:meta.view v:id=pq6c-6x2b v:category="Public Safety" v:attributionLink=http://www.icjia.state.il.us v:averageRating=0 v:name="Illinois Criminal Justice Information Authority Active Grants Beginning SFY16" v:attribution="Illinois Criminal Justice Information Authority"

property e:pq6c-6x2b t:meta.view.owner v:id=avuj-ix5c v:screenName="Jude Lemrow" v:displayName="Jude Lemrow"

property e:pq6c-6x2b t:meta.view.tableauthor v:id=avuj-ix5c v:screenName="Jude Lemrow" v:roleName=publisher v:displayName="Jude Lemrow"
```

## Top Records

```ls
| :updated_at | grantor_agency                                  | grantee                               | description_of_purpose_of_award                                                                                                                                                                                            | grant_amount | start_date | completion_date | duration_days_optional | grantee_zip_code_optional | duplicate_ignore_in_explorer_optional | 
| =========== | =============================================== | ===================================== | ========================================================================================================================================================================================================================== | ============ | ========== | =============== | ====================== | ========================= | ===================================== | 
| 1447937717  | Illinois Criminal Justice Information Authority | University of Chicago                 | Crime prevention.                                                                                                                                                                                                          | 83935        | 01-Feb-15  | 31-Jan-16       | 364                    | 60637                     |                                       | 
| 1447937717  | Illinois Criminal Justice Information Authority | CHICAGO PUBLIC SCHOOLS                | Crime prevention.                                                                                                                                                                                                          | 118896       | 01-Feb-15  | 31-Jan-16       | 364                    | 60603                     |                                       | 
| 1447937717  | Illinois Criminal Justice Information Authority | Youth Guidance                        | Crime prevention.                                                                                                                                                                                                          | 71738        | 01-Feb-15  | 31-Jan-16       | 364                    | 60602                     |                                       | 
| 1447937717  | Illinois Criminal Justice Information Authority | Yale University                       | Data analysis and research integration.                                                                                                                                                                                    | 53189        | 01-Jan-15  | 31-Dec-15       | 364                    | 06520                     |                                       | 
| 1447937717  | Illinois Criminal Justice Information Authority | TASC, Inc.                            | Crime prevention.                                                                                                                                                                                                          | 10000        | 01-Jan-15  | 31-Dec-15       | 364                    | 60607                     |                                       | 
| 1447937717  | Illinois Criminal Justice Information Authority | COOK COUNTY STATE'S ATTORNEY'S OFFICE | Specialized gun prosecutor to review arrests made on gun charges in the PSN districts and identify those offenders eligible for federal prosecution.                                                                       | 112000       | 01-Jan-15  | 31-Dec-15       | 364                    | 60602-3174                |                                       | 
| 1447937717  | Illinois Criminal Justice Information Authority | ILLINOIS DEPARTMENT OF CORRECTIONS    | Coordinator is to organize and schedule PSN forums, select parolees for attendance, schedule speakers for the forum, ensure offender participation and track offender arrests and convictions while on parole.             | 60000        | 01-Jan-15  | 31-Dec-15       | 364                    | 62702-5643                |                                       | 
| 1447937717  | Illinois Criminal Justice Information Authority | ILLINOIS DEPARTMENT OF CORRECTIONS    | Coordinator is to organize and schedule PSN forums, select parolees for attendance, schedule speakers for the forum, ensure offender participation and track offender arrests and convictions while on parole.             | 50000        | 01-Jan-15  | 31-Dec-15       | 364                    | 62702-5643                |                                       | 
| 1447937717  | Illinois Criminal Justice Information Authority | ILLINOIS DEPARTMENT OF CORRECTIONS    | Coordinator is to organize and schedule PSN forums, select parolees for attendance, schedule speakers for the forum, ensure offender participation and track offender arrests and convictions while on parole.             | 50000        | 01-Aug-15  | 31-Dec-16       | 518                    | 62702-5643                |                                       | 
| 1447937717  | Illinois Criminal Justice Information Authority | ILLINOIS DEPARTMENT OF CORRECTIONS    | Provide for the analysis of the incidence and effects of prison rape in Federal, State, and local institutions and to provide information, resources, recommendations and funding to protect individuals from prison rape. | 131697       | 01-Jan-15  | 30-Sep-16       | 638                    | 62702-5643                |                                       | 
```