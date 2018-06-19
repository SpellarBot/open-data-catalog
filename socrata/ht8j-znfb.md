# Budget Proposed FTEs 2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-proposed-ftes-2017) |
| Metadata | [Link](https://data.seattle.gov/api/views/ht8j-znfb) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/ht8j-znfb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/ht8j-znfb/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | ht8j-znfb |
| Name | Budget Proposed FTEs 2017 |
| Attribution | City of Seattle |
| Category | City Business |
| Tags | budget proposed ftes 2017 |
| Created | 2016-09-26T16:41:49Z |
| Publication Date | 2016-09-26T16:42:35Z |

## Description

Budget Proposed FTEs 2017

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| Yes      | series tag     | deptcode      | DeptCode      | text      | text        |
| Yes      | series tag     | bclname       | BCLName       | text      | text        |
| Yes      | series tag     | programname   | ProgramName   | text      | text        |
| Yes      | numeric metric | 2015_actuals  | 2015 Actuals  | number    | number      |
| Yes      | numeric metric | 2016_adopted  | 2016 Adopted  | number    | number      |
| Yes      | numeric metric | 2017_proposed | 2017 Proposed | number    | number      |
| Yes      | numeric metric | 2018_proposed | 2018 Proposed | number    | number      |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ht8j-znfb d:2017-01-01T00:00:00.000Z t:deptcode=ARTS t:programname="Administrative Services" t:bclname="Arts Account" m:2017_proposed=5 m:2015_actuals=5 m:2018_proposed=5 m:2016_adopted=5

series e:ht8j-znfb d:2017-01-01T00:00:00.000Z t:deptcode=ARTS t:programname="Community Development and Outreach" t:bclname="Arts Account" m:2017_proposed=2 m:2015_actuals=3 m:2018_proposed=2 m:2016_adopted=3

series e:ht8j-znfb d:2017-01-01T00:00:00.000Z t:deptcode=ARTS t:programname="Cultural Partnerships" t:bclname="Arts Account" m:2017_proposed=7.75 m:2015_actuals=5.75 m:2018_proposed=7.75 m:2016_adopted=6.75
```

## Meta Commands

```ls
metric m:2015_actuals p:float l:"2015 Actuals" t:dataTypeName=number

metric m:2016_adopted p:float l:"2016 Adopted" t:dataTypeName=number

metric m:2017_proposed p:float l:"2017 Proposed" t:dataTypeName=number

metric m:2018_proposed p:float l:"2018 Proposed" t:dataTypeName=number

entity e:ht8j-znfb l:"Budget Proposed FTEs 2017" t:attribution="City of Seattle" t:url=https://data.seattle.gov/api/views/ht8j-znfb

property e:ht8j-znfb t:meta.view v:id=ht8j-znfb v:category="City Business" v:attributionLink=http://www.seattle.gov v:averageRating=0 v:name="Budget Proposed FTEs 2017" v:attribution="City of Seattle"

property e:ht8j-znfb t:meta.view.license v:name="Public Domain"

property e:ht8j-znfb t:meta.view.owner v:id=58et-jnvx v:screenName="Butler, Mark" v:lastNotificationSeenAt=1491575928 v:displayName="Butler, Mark"

property e:ht8j-znfb t:meta.view.tableauthor v:id=58et-jnvx v:screenName="Butler, Mark" v:roleName=administrator v:lastNotificationSeenAt=1491575928 v:displayName="Butler, Mark"
```

## Top Records

```ls
| deptcode | bclname                | programname                               | 2015_actuals | 2016_adopted | 2017_proposed | 2018_proposed | 
| ======== | ====================== | ========================================= | ============ | ============ | ============= | ============= | 
| ARTS     | Arts Account           | Administrative Services                   | 5.00         | 5.00         | 5.00          | 5.00          | 
| ARTS     | Arts Account           | Community Development and Outreach        | 3.00         | 3.00         | 2.00          | 2.00          | 
| ARTS     | Arts Account           | Cultural Partnerships                     | 5.75         | 6.75         | 7.75          | 7.75          | 
| ARTS     | Arts Account           | Langston Hughes Performing Arts Institute | 7.09         | 3.59         | 3.59          | 3.59          | 
| ARTS     | Capital Arts           | Capital Arts                              | 0.00         | 0.00         | 1.00          | 1.00          | 
| ARTS     | Municipal Arts Fund    | Artwork Conservation                      | 0.00         | 1.00         | 1.00          | 1.00          | 
| ARTS     | Municipal Arts Fund    | Public Art                                | 10.75        | 9.75         | 10.75         | 10.75         | 
| AUD      | Office of City Auditor | Office of City Auditor                    | 9.50         | 9.50         | 9.50          | 9.50          | 
| CBO      | City Budget Office     | City Budget Office                        | 33.00        | 35.00        | 35.00         | 35.00         | 
| CEN      | Access                 | Access                                    | 9.37         | 9.37         | 9.37          | 9.37          | 
```