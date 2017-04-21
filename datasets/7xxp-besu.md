# IDoA Grant Reporting - FY14 (As of 12/31/2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idoa-grant-reporting-fy14-as-of-12-31-2013-e6eb7) |
| Metadata | [Link](https://data.illinois.gov/api/views/7xxp-besu) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/7xxp-besu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/7xxp-besu/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 7xxp-besu |
| Name | IDoA Grant Reporting - FY14 (As of 12/31/2013) |
| Attribution | Scott Norton, CIO, Illinois Department on Aging |
| Category | Social/Healthcare |
| Tags | grant reporting, grant, grant award, grantee |
| Created | 2014-01-14T22:33:16Z |
| Publication Date | 2014-01-14T22:43:34Z |

## Description

This dataset contains grant award information for grant recipients paid through IDoA.

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type     | Render Type   |
| ======== | ============== | ===================================== | ===================================== | ============= | ============= |
| Yes      | series tag     | agency                                | Agency                                | text          | text          |
| Yes      | series tag     | short_description_of_purpose_of_award | Short Description of Purpose of Award | text          | text          |
| Yes      | series tag     | fund                                  | Fund                                  | text          | text          |
| Yes      | series tag     | grantee_name                          | Grantee Name                          | text          | text          |
| Yes      | series tag     | zipcode                               | Zipcode                               | text          | text          |
| Yes      | numeric metric | amount_of_grant_award                 | Amount of Grant Award                 | money         | money         |
| Yes      | time           | grant_award_begin_date                | Grant Award Begin Date                | calendar_date | calendar_date |
| No       |                | grant_award_end_date                  | Grant Award End Date                  | calendar_date | calendar_date |
| Yes      | series tag     | grant_number                          | Grant Number                          | text          | text          |
```

## Time Field

```ls
Value = grant_award_begin_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = grant_award_end_date
```

## Data Commands

```ls
series e:7xxp-besu d:2012-07-01T00:00:00.000Z t:grant_number=CCUIC13001 t:zipcode=60612-7205 t:short_description_of_purpose_of_award="FEA for Cash and Counseling Demonstration Project" t:grantee_name="The Board of Trustees of the University of Illinois at Chicago" t:agency="Department on Aging" t:fund=GRF m:amount_of_grant_award=106361.8

series e:7xxp-besu d:2012-07-01T00:00:00.000Z t:grant_number=MM13001 t:zipcode=62705-0371 t:short_description_of_purpose_of_award="Illinois Volunteer Money Management Coordinator" t:grantee_name="Illinois Council of Care Coordination Units" t:agency="Department on Aging" t:fund=GRF m:amount_of_grant_award=134850

series e:7xxp-besu d:2013-07-01T00:00:00.000Z t:grant_number=SHAP1401 t:zipcode=61108-1652 t:short_description_of_purpose_of_award="The Senior Health Assistance Program assists older adults to maintain their health by linking them to Medicare Part D drug plans, Social Security?s Extra Help, Medicare Savings Programs." t:grantee_name="Northwestern Illinois Area Agency on Aging" t:agency="Department on Aging" t:fund="Tobacco Settlement" m:amount_of_grant_award=103471
```

## Meta Commands

```ls
metric m:amount_of_grant_award p:integer l:"Amount of Grant Award" t:dataTypeName=money

entity e:7xxp-besu l:"IDoA Grant Reporting - FY14 (As of 12/31/2013)" t:attribution="Scott Norton, CIO, Illinois Department on Aging" t:url=https://data.illinois.gov/api/views/7xxp-besu

property e:7xxp-besu t:meta.view v:id=7xxp-besu v:category=Social/Healthcare v:averageRating=0 v:name="IDoA Grant Reporting - FY14 (As of 12/31/2013)" v:attribution="Scott Norton, CIO, Illinois Department on Aging"

property e:7xxp-besu t:meta.view.license v:name="Public Domain"

property e:7xxp-besu t:meta.view.owner v:id=tvcc-rdri v:screenName="Scott Norton" v:displayName="Scott Norton"

property e:7xxp-besu t:meta.view.tableauthor v:id=tvcc-rdri v:screenName="Scott Norton" v:roleName=publisher v:displayName="Scott Norton"
```

## Top Records

```ls
| agency              | short_description_of_purpose_of_award                                                                                                                                                      | fund               | grantee_name                                                   | zipcode    | amount_of_grant_award | grant_award_begin_date | grant_award_end_date | grant_number | 
| =================== | ========================================================================================================================================================================================== | ================== | ============================================================== | ========== | ===================== | ====================== | ==================== | ============ | 
| Department on Aging | FEA for Cash and Counseling Demonstration Project                                                                                                                                          | GRF                | The Board of Trustees of the University of Illinois at Chicago | 60612-7205 | 106361.80             | 2012-07-01T00:00:00    | 2013-10-31T00:00:00  | CCUIC13001   | 
| Department on Aging | Illinois Volunteer Money Management Coordinator                                                                                                                                            | GRF                | Illinois Council of Care Coordination Units                    | 62705-0371 | 134850                | 2012-07-01T00:00:00    | 2015-06-30T00:00:00  | MM13001      | 
| Department on Aging | The Senior Health Assistance Program assists older adults to maintain their health by linking them to Medicare Part D drug plans, Social Security?s Extra Help, Medicare Savings Programs. | Tobacco Settlement | Northwestern Illinois Area Agency on Aging                     | 61108-1652 | 103471                | 2013-07-01T00:00:00    | 2014-06-30T00:00:00  | SHAP1401     | 
| Department on Aging | The Senior Health Assistance Program assists older adults to maintain their health by linking them to Medicare Part D drug plans, Social Security?s Extra Help, Medicare Savings Programs. | Tobacco Settlement | Northern Illinois Area Agency on Aging                         | 60901-0809 | 232168                | 2013-07-01T00:00:00    | 2014-06-30T00:00:00  | SHAP1402     | 
| Department on Aging | The Senior Health Assistance Program assists older adults to maintain their health by linking them to Medicare Part D drug plans, Social Security?s Extra Help, Medicare Savings Programs. | Tobacco Settlement | Western Illinois Area Agency on Aging                          | 61201-5950 | 95914                 | 2013-07-01T00:00:00    | 2014-06-30T00:00:00  | SHAP1403     | 
| Department on Aging | The Senior Health Assistance Program assists older adults to maintain their health by linking them to Medicare Part D drug plans, Social Security?s Extra Help, Medicare Savings Programs. | Tobacco Settlement | Central Illinois Agency on Aging                               | 61603-3617 | 71755                 | 2013-07-01T00:00:00    | 2014-06-30T00:00:00  | SHAP1404     | 
| Department on Aging | The Senior Health Assistance Program assists older adults to maintain their health by linking them to Medicare Part D drug plans, Social Security?s Extra Help, Medicare Savings Programs. | Tobacco Settlement | East central Illinois Area Agency on Aging                     | 61705-9327 | 112288                | 2013-07-01T00:00:00    | 2014-06-30T00:00:00  | SHAP1405     | 
| Department on Aging | The Senior Health Assistance Program assists older adults to maintain their health by linking them to Medicare Part D drug plans, Social Security?s Extra Help, Medicare Savings Programs. | Tobacco Settlement | West Central Illinois Area Agency on Aging                     | 62306-0428 | 54923                 | 2013-07-01T00:00:00    | 2014-06-30T00:00:00  | SHAP1406     | 
| Department on Aging | The Senior Health Assistance Program assists older adults to maintain their health by linking them to Medicare Part D drug plans, Social Security?s Extra Help, Medicare Savings Programs. | Tobacco Settlement | Area Agency on Aging for Lincolnland, Inc                      | 62704-4278 | 86812                 | 2013-07-01T00:00:00    | 2014-06-30T00:00:00  | SHAP1407     | 
| Department on Aging | The Senior Health Assistance Program assists older adults to maintain their health by linking them to Medicare Part D drug plans, Social Security?s Extra Help, Medicare Savings Programs. | Tobacco Settlement | Area Agency on Aging of South Western Illinois                 | 62221-2571 | 93510                 | 2013-07-01T00:00:00    | 2014-06-30T00:00:00  | SHAP1408     | 
```