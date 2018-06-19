# General Election Results 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/general-election-results-2010-24a09) |
| Metadata | [Link](https://data.hawaii.gov/api/views/y7za-qz47) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/y7za-qz47/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/y7za-qz47/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | y7za-qz47 |
| Name | General Election Results 2010 |
| Attribution | Office of Elections |
| Category | Government-Wide Support |
| Tags | elections, vote |
| Created | 2012-06-14T02:42:05Z |
| Publication Date | 2012-06-14T02:44:57Z |

## Description

2010 General Elections Results fom Office of Elections

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
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:y7za-qz47 d:2010-01-01T00:00:00.000Z t:choice_party=GRE t:candidate_name="(G) BREWER, Jim" t:contest_id=1 t:candidate_type=C t:contest_title="US Senator" t:precinct_name=1-Jan t:precinct_splitid=1 t:choice_id=1 m:ballots=1199 m:absentee_votes=0 m:early_votes=0 m:reg_voters=3760 m:reporting=1 m:election_votes=42

series e:y7za-qz47 d:2010-01-01T00:00:00.000Z t:choice_party=REP t:candidate_name="(R) CAVASSO, Cam" t:contest_id=1 t:candidate_type=C t:contest_title="US Senator" t:precinct_name=1-Jan t:precinct_splitid=1 t:choice_id=2 m:ballots=1199 m:absentee_votes=0 m:early_votes=0 m:reg_voters=3760 m:reporting=1 m:election_votes=240

series e:y7za-qz47 d:2010-01-01T00:00:00.000Z t:choice_party=DEM t:candidate_name="(D) INOUYE, Daniel K." t:contest_id=1 t:candidate_type=C t:contest_title="US Senator" t:precinct_name=1-Jan t:precinct_splitid=1 t:choice_id=3 m:ballots=1199 m:absentee_votes=0 m:early_votes=0 m:reg_voters=3760 m:reporting=1 m:election_votes=862
```

## Meta Commands

```ls
metric m:reg_voters p:integer l:Reg_voters t:dataTypeName=number

metric m:ballots p:integer l:Ballots t:dataTypeName=number

metric m:reporting p:integer l:Reporting t:dataTypeName=number

metric m:absentee_votes p:integer l:Absentee_votes t:dataTypeName=number

metric m:early_votes p:integer l:Early_votes t:dataTypeName=number

metric m:election_votes p:integer l:Election_Votes t:dataTypeName=number

entity e:y7za-qz47 l:"General Election Results 2010" t:attribution="Office of Elections" t:url=https://data.hawaii.gov/api/views/y7za-qz47

property e:y7za-qz47 t:meta.view v:id=y7za-qz47 v:category="Government-Wide Support" v:attributionLink=http://hawaii.gov/elections/results/ v:averageRating=0 v:name="General Election Results 2010" v:attribution="Office of Elections"

property e:y7za-qz47 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:y7za-qz47 t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:y7za-qz47 t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| precinct_name | split_name | precinct_splitid | reg_voters | ballots | reporting | contest_id | contest_title                    | contest_party | choice_id | candidate_name                | choice_party | candidate_type | absentee_votes | early_votes | election_votes | 
| ============= | ========== | ================ | ========== | ======= | ========= | ========== | ================================ | ============= | ========= | ============================= | ============ | ============== | ============== | =========== | ============== | 
| 1-Jan         |            | 1                | 3760       | 1199    | 1         | 1          | US Senator                       |               | 1         | (G) BREWER, Jim               | GRE          | C              | 0              | 0           | 42             | 
| 1-Jan         |            | 1                | 3760       | 1199    | 1         | 1          | US Senator                       |               | 2         | (R) CAVASSO, Cam              | REP          | C              | 0              | 0           | 240            | 
| 1-Jan         |            | 1                | 3760       | 1199    | 1         | 1          | US Senator                       |               | 3         | (D) INOUYE, Daniel K.         | DEM          | C              | 0              | 0           | 862            | 
| 1-Jan         |            | 1                | 3760       | 1199    | 1         | 1          | US Senator                       |               | 4         | (N) JARRETT, Jeff             | NPP          | C              | 0              | 0           | 14             | 
| 1-Jan         |            | 1                | 3760       | 1199    | 1         | 1          | US Senator                       |               | 5         | (L) MALLAN, Lloyd Jeffrey     | LIB          | C              | 0              | 0           | 21             | 
| 1-Jan         |            | 1                | 3760       | 1199    | 1         | 3          | US Representative, Dist 2        |               | 8         | (L) BROCK, Pat                | LIB          | C              | 0              | 0           | 34             | 
| 1-Jan         |            | 1                | 3760       | 1199    | 1         | 3          | US Representative, Dist 2        |               | 9         | (D) HIRONO, Mazie             | DEM          | C              | 0              | 0           | 808            | 
| 1-Jan         |            | 1                | 3760       | 1199    | 1         | 3          | US Representative, Dist 2        |               | 10        | (N) VON SONN, Andrew Vsevolod | NPP          | C              | 0              | 0           | 12             | 
| 1-Jan         |            | 1                | 3760       | 1199    | 1         | 3          | US Representative, Dist 2        |               | 11        | (R) WILLOUGHBY, John W.       | REP          | C              | 0              | 0           | 278            | 
| 1-Jan         |            | 1                | 3760       | 1199    | 1         | 4          | Governor and Lieutenant Governor |               | 12        | (D) ABERCROMBIE / SCHATZ      | DEM          | C              | 0              | 0           | 716            | 
```