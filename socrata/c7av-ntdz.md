# Education: Actual Operating Cost Per Student

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/education-actual-operating-cost-per-student-fa1f8) |
| Metadata | [Link](https://data.oregon.gov/api/views/c7av-ntdz) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/c7av-ntdz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/c7av-ntdz/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | c7av-ntdz |
| Name | Education: Actual Operating Cost Per Student |
| Attribution | Oregon Department of Educaiton (http://www.ode.state.or.us/) |
| Category | Education |
| Created | 2011-03-24T22:59:23Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

Actual expenditures for operating funds (General, Special Revenue, Enterprise and Food Services Funds) per student. Student count is enrollment as of October 1.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| No       | time           | :updated_at                      | updated_at                       | meta_data | meta_data   |
| Yes      | series tag     | district_id                      | District ID                      | text      | number      |
| Yes      | series tag     | county_name                      | County Name                      | text      | text        |
| Yes      | numeric metric | operating_cost_per_student       | Operating Cost Per Student       | money     | money       |
| Yes      | series tag     | district_number                  | District Number                  | text      | text        |
| Yes      | series tag     | school_year                      | School Year                      | text      | text        |
| Yes      | numeric metric | student_count                    | Student Count                    | number    | number      |
| Yes      | numeric metric | state_student_count              | State Student Count              | number    | number      |
| Yes      | numeric metric | operating_cost                   | Operating Cost                   | money     | money       |
| Yes      | numeric metric | state_operating_cost             | State Operating Cost             | money     | money       |
| Yes      | numeric metric | state_operating_cost_per_student | State Operating Cost Per Student | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:c7av-ntdz d:2011-03-24T15:59:30.000Z t:district_id=1894 t:school_year=07/01/1999 t:county_name=BAKER t:district_number="BAKER SCH DIST 05J" m:state_operating_cost=3556941887.4 m:student_count=2317 m:state_operating_cost_per_student=6548.87 m:operating_cost=16342661.74 m:state_student_count=543138 m:operating_cost_per_student=7053.37

series e:c7av-ntdz d:2011-03-24T15:59:30.000Z t:district_id=1894 t:school_year=07/01/2000 t:county_name=BAKER t:district_number="BAKER SCH DIST 05J" m:state_operating_cost=3796207419.43 m:student_count=2343 m:state_operating_cost_per_student=6975.18 m:operating_cost=16631694.66 m:state_student_count=544245 m:operating_cost_per_student=7098.46

series e:c7av-ntdz d:2011-03-24T15:59:30.000Z t:district_id=1894 t:school_year=07/01/2001 t:county_name=BAKER t:district_number="Baker SD 5J" m:state_operating_cost=3966871635.47 m:student_count=2199 m:state_operating_cost_per_student=7215.68 m:operating_cost=16118655.82 m:state_student_count=549757 m:operating_cost_per_student=7329.99
```

## Meta Commands

```ls
metric m:operating_cost_per_student p:double l:"Operating Cost Per Student" t:dataTypeName=money

metric m:student_count p:integer l:"Student Count" t:dataTypeName=number

metric m:state_student_count p:integer l:"State Student Count" t:dataTypeName=number

metric m:operating_cost p:double l:"Operating Cost" t:dataTypeName=money

metric m:state_operating_cost p:double l:"State Operating Cost" t:dataTypeName=money

metric m:state_operating_cost_per_student p:double l:"State Operating Cost Per Student" t:dataTypeName=money

entity e:c7av-ntdz l:"Education: Actual Operating Cost Per Student" t:attribution="Oregon Department of Educaiton (http://www.ode.state.or.us/)" t:url=https://data.oregon.gov/api/views/c7av-ntdz

property e:c7av-ntdz t:meta.view v:id=c7av-ntdz v:category=Education v:attributionLink=http://www.ode.state.or.us/sfda/reports/r0051Select.asp v:averageRating=0 v:name="Education: Actual Operating Cost Per Student" v:attribution="Oregon Department of Educaiton (http://www.ode.state.or.us/)"

property e:c7av-ntdz t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:c7av-ntdz t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| :updated_at | district_id | county_name | operating_cost_per_student | district_number    | school_year | student_count | state_student_count | operating_cost | state_operating_cost | state_operating_cost_per_student | 
| =========== | =========== | =========== | ========================== | ================== | =========== | ============= | =================== | ============== | ==================== | ================================ | 
| 1300982370  | 1894        | BAKER       | 7053.37                    | BAKER SCH DIST 05J | 07/01/1999  | 2317          | 543138              | 16342661.74    | 3556941887.4         | 6548.87                          | 
| 1300982370  | 1894        | BAKER       | 7098.46                    | BAKER SCH DIST 05J | 07/01/2000  | 2343          | 544245              | 16631694.66    | 3796207419.43        | 6975.18                          | 
| 1300982370  | 1894        | BAKER       | 7329.99                    | Baker SD 5J        | 07/01/2001  | 2199          | 549757              | 16118655.82    | 3966871635.47        | 7215.68                          | 
| 1300982370  | 1894        | BAKER       | 7025.58                    | Baker SD 5J        | 07/01/2002  | 2151          | 552161              | 15112028.86    | 3889552066.13        | 7044.24                          | 
| 1300982370  | 1894        | BAKER       | 7475.36                    | Baker SD 5J        | 07/01/2003  | 2115          | 549169              | 15810377.82    | 3970643658.44        | 7230.28                          | 
| 1300982370  | 1894        | BAKER       | 7804.90                    | Baker SD 5J        | 07/01/2004  | 2055          | 549793              | 16039065.86    | 4198534676.94        | 7636.57                          | 
| 1300982370  | 1894        | BAKER       | 8407.71                    | Baker SD 5J        | 07/01/2005  | 2009          | 555146              | 16891098.00    | 4513950428.6         | 8131.11                          | 
| 1300982370  | 1894        | BAKER       | 8977.35                    | Baker SD 5J        | 07/01/2006  | 2007          | 558366              | 18017546.04    | 4768933786.7         | 8540.87                          | 
| 1300982370  | 1894        | BAKER       | 9659.93                    | Baker SD 5J        | 07/01/2007  | 1979          | 561354              | 19117010.12    | 5144636555.37        | 9164.69                          | 
| 1300982370  | 1894        | BAKER       | 9944.95                    | Baker SD 5J        | 07/01/2008  | 1901          | 559271              | 18905359.03    | 5248233458.1         | 9384.06                          | 
```