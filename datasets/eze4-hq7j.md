# General Election 2012 Results

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/general-election-2012-results-b4f90) |
| Metadata | [Link](https://data.hawaii.gov/api/views/eze4-hq7j) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/eze4-hq7j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/eze4-hq7j/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | eze4-hq7j |
| Name | General Election 2012 Results |
| Attribution | Department of Accounting and General Services |
| Category | Government-Wide Support |
| Tags | elections |
| Created | 2013-01-23T19:27:37Z |
| Publication Date | 2013-01-23T19:31:55Z |

## Description

General Election Results 2012

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | precinct_name    | Precinct_Name    | text      | text        |
| Yes      | series tag     | split_name       | Split_Name       | text      | text        |
| Yes      | series tag     | precinct_splitid | precinct_splitId | text      | number      |
| Yes      | numeric metric | reg_voters       | Reg_voters       | number    | number      |
| Yes      | numeric metric | ballots          | Ballots          | number    | number      |
| Yes      | numeric metric | reporting        | Reporting        | number    | number      |
| Yes      | series tag     | contest_id       | Contest_id       | text      | number      |
| Yes      | series tag     | contest_title    | Contest_title    | text      | text        |
| Yes      | series tag     | contest_party    | Contest_party    | text      | text        |
| Yes      | series tag     | choice_id        | Choice_id        | text      | number      |
| Yes      | series tag     | candidate_name   | Candidate_name   | text      | text        |
| Yes      | series tag     | choice_party     | Choice_party     | text      | text        |
| Yes      | series tag     | candidate_type   | Candidate_Type   | text      | text        |
| Yes      | numeric metric | absentee_votes   | Absentee_votes   | number    | number      |
| Yes      | numeric metric | early_votes      | Early_votes      | number    | number      |
| Yes      | numeric metric | election_votes   | Election_Votes   | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:eze4-hq7j d:2012-01-01T00:00:00.000Z t:choice_party=REP t:candidate_name="(R) ROMNEY, Mitt / RYAN, Paul" t:contest_id=1 t:candidate_type=C t:contest_title="President and Vice President" t:precinct_name=1-Jan t:precinct_splitid=1 t:choice_id=1 m:ballots=1712 m:absentee_votes=82 m:early_votes=34 m:reg_voters=2839 m:reporting=1 m:election_votes=172

series e:eze4-hq7j d:2012-01-01T00:00:00.000Z t:choice_party=GRE t:candidate_name="(G) STEIN, Jill / HONKALA, Cheri" t:contest_id=1 t:candidate_type=C t:contest_title="President and Vice President" t:precinct_name=1-Jan t:precinct_splitid=1 t:choice_id=2 m:ballots=1712 m:absentee_votes=8 m:early_votes=2 m:reg_voters=2839 m:reporting=1 m:election_votes=10

series e:eze4-hq7j d:2012-01-01T00:00:00.000Z t:choice_party=LIB t:candidate_name="(L) JOHNSON, Gary / GRAY, James P." t:contest_id=1 t:candidate_type=C t:contest_title="President and Vice President" t:precinct_name=1-Jan t:precinct_splitid=1 t:choice_id=3 m:ballots=1712 m:absentee_votes=6 m:early_votes=2 m:reg_voters=2839 m:reporting=1 m:election_votes=17
```

## Meta Commands

```ls
metric m:reg_voters p:integer l:Reg_voters t:dataTypeName=number

metric m:ballots p:integer l:Ballots t:dataTypeName=number

metric m:reporting p:integer l:Reporting t:dataTypeName=number

metric m:absentee_votes p:integer l:Absentee_votes t:dataTypeName=number

metric m:early_votes p:integer l:Early_votes t:dataTypeName=number

metric m:election_votes p:integer l:Election_Votes t:dataTypeName=number

entity e:eze4-hq7j l:"General Election 2012 Results" t:attribution="Department of Accounting and General Services" t:url=https://data.hawaii.gov/api/views/eze4-hq7j

property e:eze4-hq7j t:meta.view v:id=eze4-hq7j v:category="Government-Wide Support" v:attributionLink=http://hawaii.gov/dags v:averageRating=0 v:name="General Election 2012 Results" v:attribution="Department of Accounting and General Services"

property e:eze4-hq7j t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:eze4-hq7j t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:eze4-hq7j t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| precinct_name | split_name | precinct_splitid | reg_voters | ballots | reporting | contest_id | contest_title                | contest_party | choice_id | candidate_name                     | choice_party | candidate_type | absentee_votes | early_votes | election_votes | 
| ============= | ========== | ================ | ========== | ======= | ========= | ========== | ============================ | ============= | ========= | ================================== | ============ | ============== | ============== | =========== | ============== | 
| 1-Jan         |            | 1                | 2839       | 1712    | 1         | 1          | President and Vice President |               | 1         | (R) ROMNEY, Mitt / RYAN, Paul      | REP          | C              | 82             | 34          | 172            | 
| 1-Jan         |            | 1                | 2839       | 1712    | 1         | 1          | President and Vice President |               | 2         | (G) STEIN, Jill / HONKALA, Cheri   | GRE          | C              | 8              | 2           | 10             | 
| 1-Jan         |            | 1                | 2839       | 1712    | 1         | 1          | President and Vice President |               | 3         | (L) JOHNSON, Gary / GRAY, James P. | LIB          | C              | 6              | 2           | 17             | 
| 1-Jan         |            | 1                | 2839       | 1712    | 1         | 1          | President and Vice President |               | 4         | (D) OBAMA, Barack / BIDEN, Joe     | DEM          | C              | 549            | 126         | 696            | 
| 1-Jan         |            | 1                | 2839       | 1712    | 1         | 2          | US Senator                   |               | 5         | (D) HIRONO, Mazie                  | DEM          | C              | 492            | 117         | 645            | 
| 1-Jan         |            | 1                | 2839       | 1712    | 1         | 2          | US Senator                   |               | 6         | (R) LINGLE, Linda                  | REP          | C              | 142            | 48          | 243            | 
| 1-Jan         |            | 1                | 2839       | 1712    | 1         | 4          | US Representative, Dist 2    |               | 9         | (R) CROWLEY, Kawika                | REP          | C              | 69             | 30          | 110            | 
| 1-Jan         |            | 1                | 2839       | 1712    | 1         | 4          | US Representative, Dist 2    |               | 10        | (D) GABBARD, Tulsi                 | DEM          | C              | 552            | 131         | 765            | 
| 1-Jan         |            | 1                | 2839       | 1712    | 1         | 7          | State Senator, Dist 4        |               | 15        | (G) GREENWELL, Kelly               | GRE          | C              | 186            | 54          | 252            | 
| 1-Jan         |            | 1                | 2839       | 1712    | 1         | 7          | State Senator, Dist 4        |               | 16        | (D) SOLOMON, Malama                | DEM          | C              | 428            | 106         | 590            | 
```