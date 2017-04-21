# Campaign Finance - Committee Name to Measure or Candidate Mapping for November 3, 2015 Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-committee-name-to-measure-or-candidate-mapping-for-november-3-2015-electi) |
| Metadata | [Link](https://data.sfgov.org/api/views/9gi7-6xfc) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/9gi7-6xfc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/9gi7-6xfc/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 9gi7-6xfc |
| Name | Campaign Finance - Committee Name to Measure or Candidate Mapping for November 3, 2015 Election |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | campaign finance dashboard 2015 |
| Created | 2015-08-07T17:03:15Z |
| Publication Date | 2015-10-16T18:15:31Z |

## Description

This dataset maps the name of a campaign committee to the corresponding candidate or measure.  It includes the position of each measure and FPPC ID.  This dataset is intended for campaign finance data projects.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag  | filer_id             | Filer_ID             | text      | text        |
| Yes      | series tag  | filer_naml           | Filer_NamL           | text      | text        |
| Yes      | series tag  | contest              | Contest              | text      | text        |
| Yes      | series tag  | candidate_or_measure | Candidate_or_Measure | text      | text        |
| Yes      | series tag  | position             | Position             | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9gi7-6xfc d:2015-01-01T00:00:00.000Z t:position=Support t:filer_id=1374912 t:contest="Board of Supervisors District 3" t:candidate_or_measure="Christensen, Julie" t:filer_naml="Christensen for Supervisor 2015" m:row_number.9gi7-6xfc=1

series e:9gi7-6xfc d:2015-01-01T00:00:00.000Z t:position=Support t:filer_id=1376394 t:contest="Board of Supervisors District 3" t:candidate_or_measure="Peskin, Aaron" t:filer_naml="Aaron Peskin for Supervisor 2015" m:row_number.9gi7-6xfc=2

series e:9gi7-6xfc d:2015-01-01T00:00:00.000Z t:position=Support t:filer_id=1374368 t:contest="City Attorney" t:candidate_or_measure="Herrera, Dennis" t:filer_naml="Dennis Herrera for City Attorney 2015" m:row_number.9gi7-6xfc=3
```

## Meta Commands

```ls
metric m:row_number.9gi7-6xfc p:long l:"Row Number"

entity e:9gi7-6xfc l:"Campaign Finance - Committee Name to Measure or Candidate Mapping for November 3, 2015 Election" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/9gi7-6xfc

property e:9gi7-6xfc t:meta.view v:id=9gi7-6xfc v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance - Committee Name to Measure or Candidate Mapping for November 3, 2015 Election" v:attribution="San Francisco Ethics Commission"

property e:9gi7-6xfc t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:9gi7-6xfc t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:9gi7-6xfc t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| filer_id | filer_naml                                                                     | contest                         | candidate_or_measure | position | 
| ======== | ============================================================================== | =============================== | ==================== | ======== | 
| 1374912  | Christensen for Supervisor 2015                                                | Board of Supervisors District 3 | Christensen, Julie   | Support  | 
| 1376394  | Aaron Peskin for Supervisor 2015                                               | Board of Supervisors District 3 | Peskin, Aaron        | Support  | 
| 1374368  | Dennis Herrera for City Attorney 2015                                          | City Attorney                   | Herrera, Dennis      | Support  | 
| 1377227  | Tom Temprano For College Board 2015                                            | Community College Board         | Temprano, Tom        | Support  | 
| 1377608  | Alex Randolph for Community College Board 2015                                 | Community College Board         | Randolph, Alex       | Support  | 
| 1377674  | Committee to Elect Wendy Aragon for San Francisco Community College Board 2015 | Community College Board         | Aragon, Wendy        | Support  | 
| 1368216  | RE-ELECT DISTRICT ATTORNEY GEORGE GASCON 2015                                  | District Attorney               | Gascon, George       | Support  | 
| 1371895  | Committee to Elect Robert Jordan for Mayor 2015                                | Mayor                           | Jordan, Robert       | Support  | 
| 1373497  | Ed Lee for Mayor 2015                                                          | Mayor                           | Lee, Edwin           | Support  | 
| 1374629  | (YIMBY) WEISS for Mayor 2015                                                   | Mayor                           | Weiss, Amy           | Support  | 
```