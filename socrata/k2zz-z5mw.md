# Police Departments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/police-departments) |
| Metadata | [Link](https://data.ct.gov/api/views/k2zz-z5mw) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/k2zz-z5mw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/k2zz-z5mw/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | k2zz-z5mw |
| Name | Police Departments |
| Attribution | Department of Emergency Service and Public Protection |
| Category | Public Safety |
| Tags | police, departments, public safety, crime |
| Created | 2015-01-15T20:51:28Z |
| Publication Date | 2015-01-15T21:08:07Z |

## Description

A listing of State, Municipal, Campus, and Other police departments in Connecticut. This list does not include sub-stations within various municipalities.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | name        | NAME        | text      | text        |
| Yes      | series tag  | description | DESCRIPTION | text      | text        |
| Yes      | series tag  | telephone   | TELEPHONE   | text      | text        |
| No       |             | address     | ADDRESS     | text      | text        |
| No       |             | address2    | ADDRESS2    | number    | number      |
| Yes      | series tag  | city        | CITY        | text      | text        |
| Yes      | series tag  | state       | STATE       | text      | text        |
| Yes      | series tag  | zip         | ZIP         | text      | number      |
| Yes      | series tag  | zipp4       | ZIPP4       | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,address2
```

## Data Commands

```ls
series e:k2zz-z5mw d:2015-01-15T12:51:48.000Z t:zip=6519 t:description=OTHER t:name="AMTRAK POLICE DEPARTMENT" t:state=CT t:zipp4=1754 t:telephone=203-773-6000 t:city="NEW HAVEN" m:row_number.k2zz-z5mw=1

series e:k2zz-z5mw d:2015-01-15T12:51:48.000Z t:zip=6232 t:description=MUNICIPAL t:name="ANDOVER POLICE DEPARTMENT" t:state=CT t:zipp4=1526 t:telephone=860-742-0235 t:city=ANDOVER m:row_number.k2zz-z5mw=2

series e:k2zz-z5mw d:2015-01-15T12:51:48.000Z t:zip=6340 t:description="COLLEGE OR UNIVERSITY" t:name="AVERY POINT CAMPUS POLICE - SUBSTATION" t:state=CT t:zipp4=6048 t:telephone=860-405-9088 t:city=GROTON m:row_number.k2zz-z5mw=3
```

## Meta Commands

```ls
metric m:row_number.k2zz-z5mw p:long l:"Row Number"

entity e:k2zz-z5mw l:"Police Departments" t:attribution="Department of Emergency Service and Public Protection" t:url=https://data.ct.gov/api/views/k2zz-z5mw

property e:k2zz-z5mw t:meta.view v:id=k2zz-z5mw v:category="Public Safety" v:attributionLink="http://www.ct.gov/post/cwp/view.asp?a=2058&q=291936" v:averageRating=0 v:name="Police Departments" v:attribution="Department of Emergency Service and Public Protection"

property e:k2zz-z5mw t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:k2zz-z5mw t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | name                                                                       | description           | telephone    | address                 | address2 | city        | state | zip  | zipp4 | 
| =========== | ========================================================================== | ===================== | ============ | ======================= | ======== | =========== | ===== | ==== | ===== | 
| 1421326308  | AMTRAK POLICE DEPARTMENT                                                   | OTHER                 | 203-773-6000 | 50 UNION AVENUE         |          | NEW HAVEN   | CT    | 6519 | 1754  | 
| 1421326308  | ANDOVER POLICE DEPARTMENT                                                  | MUNICIPAL             | 860-742-0235 | 17 SCHOOL ROAD          |          | ANDOVER     | CT    | 6232 | 1526  | 
| 1421326308  | AVERY POINT CAMPUS POLICE - SUBSTATION                                     | COLLEGE OR UNIVERSITY | 860-405-9088 | 1084 SHENNECOSSETT ROAD |          | GROTON      | CT    | 6340 | 6048  | 
| 1421326308  | CAPITAL COMMUNITY TECHNICAL COLLEGE CAMPUS POLICE                          | COLLEGE OR UNIVERSITY | 860-906-5075 | 950 MAIN STREET         |          | HARTFORD    | CT    | 6103 | 1207  | 
| 1421326308  | CENTRAL CONNECTICUT STATE UNIVERSITY POLICE                                | COLLEGE OR UNIVERSITY | 860-832-2375 | 1615 STANLEY STREET     |          | NEW BRITAIN | CT    | 6050 | 2439  | 
| 1421326308  | CHESHIRE POLICE DEPARTMENT                                                 | MUNICIPAL             | 203-271-5500 | 500 HIGHLAND AVENUE     |          | CHESHIRE    | CT    | 6410 | 2249  | 
| 1421326308  | CLINTON POLICE DEPARTMENT                                                  | MUNICIPAL             | 860-669-0451 | 170 EAST MAIN STREET    |          | CLINTON     | CT    | 6413 | 2115  | 
| 1421326308  | COLCHESTER POLICE DEPARTMENT                                               | MUNICIPAL             | 860-537-2989 | 127 NORWICH AVENUE      |          | COLCHESTER  | CT    | 6415 | 1230  | 
| 1421326308  | CONNECTICUT DEPARTMENT OF ENVIRONMENTAL CONSERVATION POLICE - HEADQUARTERS | OTHER                 | 860-424-3012 | 79 ELM STREET           |          | HARTFORD    | CT    | 6106 | 1650  | 
| 1421326308  | CONNECTICUT STATE CAPITOL POLICE                                           | OTHER                 | 860-240-0240 | 210 CAPITOL AVENUE      |          | HARTFORD    | CT    | 6106 | 1535  | 
```