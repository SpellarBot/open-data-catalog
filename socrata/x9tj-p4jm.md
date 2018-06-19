# Election 2013 May General Candidate List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-2013-may-general-candidate-list-30ec7) |
| Metadata | [Link](https://data.lacity.org/api/views/x9tj-p4jm) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/x9tj-p4jm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/x9tj-p4jm/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | x9tj-p4jm |
| Name | Election 2013 May General Candidate List |
| Category | A Well Run City |
| Created | 2014-05-30T14:45:17Z |
| Publication Date | 2014-05-30T20:05:25Z |

## Description

Candidate Names, Races and Measures

## Columns

```ls
| Included | Schema Type | Field Name | Name      | Data Type | Render Type |
| ======== | =========== | ========== | ========= | ========= | =========== |
| Yes      | series tag  | race       | Race      | text      | text        |
| Yes      | series tag  | candidate  | Candidate | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:x9tj-p4jm d:2013-01-01T00:00:00.000Z t:candidate="ERIC GARCETTI" t:race=MAYOR m:row_number.x9tj-p4jm=1

series e:x9tj-p4jm d:2013-01-01T00:00:00.000Z t:candidate="WENDY J. GREUEL" t:race=MAYOR m:row_number.x9tj-p4jm=2

series e:x9tj-p4jm d:2013-01-01T00:00:00.000Z t:candidate="CARMEN ""NUCH"" TRUTANICH" t:race="CITY ATTORNEY" m:row_number.x9tj-p4jm=3
```

## Meta Commands

```ls
metric m:row_number.x9tj-p4jm p:long l:"Row Number"

entity e:x9tj-p4jm l:"Election 2013 May General Candidate List" t:url=https://data.lacity.org/api/views/x9tj-p4jm

property e:x9tj-p4jm t:meta.view v:id=x9tj-p4jm v:category="A Well Run City" v:averageRating=0 v:name="Election 2013 May General Candidate List"

property e:x9tj-p4jm t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:x9tj-p4jm t:meta.view.owner v:id=ika6-27vg v:profileImageUrlMedium=/api/users/ika6-27vg/profile_images/THUMB v:profileImageUrlLarge=/api/users/ika6-27vg/profile_images/LARGE v:screenName="City Clerk OpenData" v:profileImageUrlSmall=/api/users/ika6-27vg/profile_images/TINY v:displayName="City Clerk OpenData"

property e:x9tj-p4jm t:meta.view.tableauthor v:id=ika6-27vg v:profileImageUrlMedium=/api/users/ika6-27vg/profile_images/THUMB v:profileImageUrlLarge=/api/users/ika6-27vg/profile_images/LARGE v:screenName="City Clerk OpenData" v:profileImageUrlSmall=/api/users/ika6-27vg/profile_images/TINY v:roleName=publisher v:displayName="City Clerk OpenData"
```

## Top Records

```ls
| race                                  | candidate                | 
| ===================================== | ======================== | 
| MAYOR                                 | ERIC GARCETTI            | 
| MAYOR                                 | WENDY J. GREUEL          | 
| CITY ATTORNEY                         | CARMEN "NUCH" TRUTANICH  | 
| CITY ATTORNEY                         | MIKE FEUER               | 
| CONTROLLER                            | RON GALPERIN             | 
| CONTROLLER                            | DENNIS P. ZINE           | 
| MEMBER OF THE COUNCIL, DISTRICT NO. 1 | JOSE A. GARDEA           | 
| MEMBER OF THE COUNCIL, DISTRICT NO. 1 | GILBERT CEDILLO          | 
| MEMBER OF THE COUNCIL, DISTRICT NO. 6 | WALTER ALEXANDER ESCOBAR | 
| MEMBER OF THE COUNCIL, DISTRICT NO. 6 | NURY MARTINEZ            | 
```