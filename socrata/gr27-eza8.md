# Election 2013 March Primary Candidate List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-2013-march-primary-candidate-list-63ad6) |
| Metadata | [Link](https://data.lacity.org/api/views/gr27-eza8) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/gr27-eza8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/gr27-eza8/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | gr27-eza8 |
| Name | Election 2013 March Primary Candidate List |
| Category | A Well Run City |
| Created | 2014-05-30T14:42:44Z |
| Publication Date | 2014-05-30T20:10:33Z |

## Description

Candidates, Races and Measures

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
series e:gr27-eza8 d:2013-01-01T00:00:00.000Z t:candidate="JAN PERRY" t:race=MAYOR m:row_number.gr27-eza8=1

series e:gr27-eza8 d:2013-01-01T00:00:00.000Z t:candidate="EMANUEL ALBERTO PLEITEZ" t:race=MAYOR m:row_number.gr27-eza8=2

series e:gr27-eza8 d:2013-01-01T00:00:00.000Z t:candidate="ERIC GARCETTI" t:race=MAYOR m:row_number.gr27-eza8=3
```

## Meta Commands

```ls
metric m:row_number.gr27-eza8 p:long l:"Row Number"

entity e:gr27-eza8 l:"Election 2013 March Primary Candidate List" t:url=https://data.lacity.org/api/views/gr27-eza8

property e:gr27-eza8 t:meta.view v:id=gr27-eza8 v:category="A Well Run City" v:averageRating=0 v:name="Election 2013 March Primary Candidate List"

property e:gr27-eza8 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:gr27-eza8 t:meta.view.owner v:id=ika6-27vg v:profileImageUrlMedium=/api/users/ika6-27vg/profile_images/THUMB v:profileImageUrlLarge=/api/users/ika6-27vg/profile_images/LARGE v:screenName="City Clerk OpenData" v:profileImageUrlSmall=/api/users/ika6-27vg/profile_images/TINY v:displayName="City Clerk OpenData"

property e:gr27-eza8 t:meta.view.tableauthor v:id=ika6-27vg v:profileImageUrlMedium=/api/users/ika6-27vg/profile_images/THUMB v:profileImageUrlLarge=/api/users/ika6-27vg/profile_images/LARGE v:screenName="City Clerk OpenData" v:profileImageUrlSmall=/api/users/ika6-27vg/profile_images/TINY v:roleName=publisher v:displayName="City Clerk OpenData"
```

## Top Records

```ls
| race          | candidate               | 
| ============= | ======================= | 
| MAYOR         | JAN PERRY               | 
| MAYOR         | EMANUEL ALBERTO PLEITEZ | 
| MAYOR         | ERIC GARCETTI           | 
| MAYOR         | WENDY J. GREUEL         | 
| MAYOR         | ADDIE M. MILLER         | 
| MAYOR         | KEVIN JAMES             | 
| MAYOR         | NORTON SANDLER          | 
| MAYOR         | YEHUDA "YJ" DRAIMAN     | 
| CITY ATTORNEY | CARMEN "NUCH" TRUTANICH | 
| CITY ATTORNEY | NOEL WEISS              | 
```