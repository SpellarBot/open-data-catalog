# Budget Proposed Dollars 2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-proposed-dollars-2017) |
| Metadata | [Link](https://data.seattle.gov/api/views/qys7-zpj5) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/qys7-zpj5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/qys7-zpj5/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | qys7-zpj5 |
| Name | Budget Proposed Dollars 2017 |
| Attribution | City of Seattle |
| Category | City Business |
| Tags | budget proposed dollars 2017 |
| Created | 2016-09-22T21:15:48Z |
| Publication Date | 2016-09-22T21:18:54Z |

## Description

Budget Proposed Dollars 2017

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
series e:qys7-zpj5 d:2017-01-01T00:00:00.000Z t:deptcode=12LIBLEVY t:programname="Library Levy Operating Transfer" t:bclname="Library Levy Operating Transfer" m:2017_proposed=14503161 m:2015_actuals=12859594 m:2018_proposed=14905762 m:2016_adopted=13665837

series e:qys7-zpj5 d:2017-01-01T00:00:00.000Z t:deptcode=ARTS t:programname="Administrative Services" t:bclname="Arts Account" m:2017_proposed=1606543 m:2015_actuals=646334.08 m:2018_proposed=1556142 m:2016_adopted=598187

series e:qys7-zpj5 d:2017-01-01T00:00:00.000Z t:deptcode=ARTS t:programname="Community Development and Outreach" t:bclname="Arts Account" m:2017_proposed=502657 m:2015_actuals=567607.43 m:2018_proposed=517260 m:2016_adopted=611425
```

## Meta Commands

```ls
metric m:2015_actuals p:decimal l:"2015 Actuals" t:dataTypeName=number

metric m:2016_adopted p:integer l:"2016 Adopted" t:dataTypeName=number

metric m:2017_proposed p:integer l:"2017 Proposed" t:dataTypeName=number

metric m:2018_proposed p:integer l:"2018 Proposed" t:dataTypeName=number

entity e:qys7-zpj5 l:"Budget Proposed Dollars 2017" t:attribution="City of Seattle" t:url=https://data.seattle.gov/api/views/qys7-zpj5

property e:qys7-zpj5 t:meta.view v:id=qys7-zpj5 v:category="City Business" v:attributionLink=http://www.seattle.gov v:averageRating=0 v:name="Budget Proposed Dollars 2017" v:attribution="City of Seattle"

property e:qys7-zpj5 t:meta.view.license v:name="Public Domain"

property e:qys7-zpj5 t:meta.view.owner v:id=58et-jnvx v:screenName="Butler, Mark" v:lastNotificationSeenAt=1491575928 v:displayName="Butler, Mark"

property e:qys7-zpj5 t:meta.view.tableauthor v:id=58et-jnvx v:screenName="Butler, Mark" v:roleName=administrator v:lastNotificationSeenAt=1491575928 v:displayName="Butler, Mark"
```

## Top Records

```ls
| deptcode  | bclname                                          | programname                               | 2015_actuals       | 2016_adopted | 2017_proposed | 2018_proposed | 
| ========= | ================================================ | ========================================= | ================== | ============ | ============= | ============= | 
| 12LIBLEVY | Library Levy Operating Transfer                  | Library Levy Operating Transfer           | 12859594           | 13665837     | 14503161      | 14905762      | 
| ARTS      | Arts Account                                     | Administrative Services                   | 646334.07999999996 | 598187       | 1606543       | 1556142       | 
| ARTS      | Arts Account                                     | Community Development and Outreach        | 567607.43000000005 | 611425       | 502657        | 517260        | 
| ARTS      | Arts Account                                     | Cultural Partnerships                     | 3555729.84         | 4517092      | 4827362       | 5132161       | 
| ARTS      | Arts Account                                     | Langston Hughes Performing Arts Institute | 872322.51          | 428046       | 473066        | 487169        | 
| ARTS      | Capital Arts                                     | Capital Arts                              | 0                  | 1856000      | 1921765       | 1392294       | 
| ARTS      | Municipal Arts Fund                              | Artwork Conservation                      | 0                  | 187000       | 192527        | 195486        | 
| ARTS      | Municipal Arts Fund                              | Public Art                                | 2644768.2400000002 | 3099449      | 3163493       | 3195336       | 
| AUD       | Office of City Auditor                           | Office of City Auditor                    | 1858746.95         | 1792064      | 1947748       | 1795041       | 
| CBLFEE    | Cable Fee Support to Information Technology Fund | Applications                              | 0                  | 0            | 742062        | 430062        | 
```