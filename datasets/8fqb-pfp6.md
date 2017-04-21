# Campaign Finance - Total Expenditures By Candidate Controlled Committees for Board of Supervisors as of the 6-30-2012 Campaign Finance Deadline - November 6 2012 Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-total-expenditures-by-candidate-controlled-committees-for-board-of-superv-16ccd) |
| Metadata | [Link](https://data.sfgov.org/api/views/8fqb-pfp6) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/8fqb-pfp6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/8fqb-pfp6/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 8fqb-pfp6 |
| Name | Campaign Finance - Total Expenditures By Candidate Controlled Committees for Board of Supervisors as of the 6-30-2012 Campaign Finance Deadline - November 6 2012 Election |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | campaign, finance, november 6 2012, election, general, board of supervisors, district, candidate, controlled, committee, expenditures |
| Created | 2012-08-13T22:12:23Z |
| Publication Date | 2012-09-11T17:32:03Z |

## Description

See Dashboards for more at http://www.sfethics.org/ethics/2012/08/november-6-2012-election-campaign-finance-dashboards.html

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| Yes      | series tag     | district                       | District                       | text      | text        |
| Yes      | series tag     | candidate_controlled_committee | Candidate Controlled Committee | text      | text        |
| Yes      | series tag     | fppc_id                        | FPPC ID                        | text      | text        |
| Yes      | numeric metric | total_expenditures             | Total Expenditures             | money     | money       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8fqb-pfp6 d:2012-01-01T00:00:00.000Z t:fppc_id=1346364 t:candidate_controlled_committee="Re-Elect Supervisor Eric Mar 2012" t:district="District 01 - (3 Qualified Candidates)" m:total_expenditures=24463.79

series e:8fqb-pfp6 d:2012-01-01T00:00:00.000Z t:fppc_id=1347203 t:candidate_controlled_committee="David Lee for San Francisco District 1 Supervisor 2012" t:district="District 01 - (3 Qualified Candidates)" m:total_expenditures=49408.52

series e:8fqb-pfp6 d:2012-01-01T00:00:00.000Z t:fppc_id=1346677 t:candidate_controlled_committee="Re-Elect Supervisor David Chiu 2012" t:district="District 03 - (4 Qualified Candidates)" m:total_expenditures=23873.93
```

## Meta Commands

```ls
metric m:total_expenditures p:double l:"Total Expenditures" t:dataTypeName=money

entity e:8fqb-pfp6 l:"Campaign Finance - Total Expenditures By Candidate Controlled Committees for Board of Supervisors as of the 6-30-2012 Campaign Finance Deadline - November 6 2012 Election" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/8fqb-pfp6

property e:8fqb-pfp6 t:meta.view v:id=8fqb-pfp6 v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance - Total Expenditures By Candidate Controlled Committees for Board of Supervisors as of the 6-30-2012 Campaign Finance Deadline - November 6 2012 Election" v:attribution="San Francisco Ethics Commission"

property e:8fqb-pfp6 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:8fqb-pfp6 t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:8fqb-pfp6 t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| district                               | candidate_controlled_committee                                 | fppc_id | total_expenditures | 
| ====================================== | ============================================================== | ======= | ================== | 
| District 01 - (3 Qualified Candidates) | Re-Elect Supervisor Eric Mar 2012                              | 1346364 | 24463.79           | 
| District 01 - (3 Qualified Candidates) | David Lee for San Francisco District 1 Supervisor 2012         | 1347203 | 49408.52           | 
| District 03 - (4 Qualified Candidates) | Re-Elect Supervisor David Chiu 2012                            | 1346677 | 23873.93           | 
| District 05 - (8 Qualified Candidates) | Friends of Thea Selby for D5 Supervisor 2012                   | 1342843 | 12705.81           | 
| District 05 - (8 Qualified Candidates) | John Rizzo for District 5 Supervisor 2012                      | 1343034 | 12933.42           | 
| District 05 - (8 Qualified Candidates) | Christina Olague for Supervisor 2012                           | 1345087 | 23409.00           | 
| District 05 - (8 Qualified Candidates) | Committee to Elect Andrew Resignato Supervisor District 5 2012 | 1347617 | 733.79             | 
| District 05 - (8 Qualified Candidates) | Julian Davis for Supervisor 2012                               | 1347852 | 6119.96            | 
| District 05 - (8 Qualified Candidates) | London Breed for San Francisco Supervisor 2012                 | 1345505 | 21192.82           | 
| District 07 - (9 Qualified Candidates) | Engardio For District 7 Supervisor 2012                        | 1341381 | 9879.66            | 
```