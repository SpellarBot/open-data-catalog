# General Election 2010 Summary Results.csv

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/general-election-2010-summary-results-csv-c4b00) |
| Metadata | [Link](https://data.hawaii.gov/api/views/8bdn-x7b5) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/8bdn-x7b5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/8bdn-x7b5/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 8bdn-x7b5 |
| Name | General Election 2010 Summary Results.csv |
| Attribution | Office of Elections |
| Category | Government-Wide Support |
| Tags | elections |
| Created | 2012-06-14T02:34:34Z |
| Publication Date | 2012-06-14T02:39:40Z |

## Description

General Elections 2010 Summary results from the Office of Elections

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | series tag     | contest_id                   | Contest ID                   | text      | number      |
| Yes      | series tag     | contest_title                | Contest Title                | text      | text        |
| Yes      | numeric metric | contest_seq_nbr              | Contest Seq Nbr              | number    | number      |
| Yes      | series tag     | contest_type                 | Contest Type                 | text      | text        |
| Yes      | series tag     | contest_party                | Contest Party                | text      | text        |
| Yes      | numeric metric | absentee_mail_blank_votes    | Absentee Mail Blank Votes    | number    | number      |
| Yes      | numeric metric | absentee_walk_in_blank_votes | Absentee Walk-in Blank Votes | number    | number      |
| Yes      | numeric metric | election_blank_votes         | Election Blank Votes         | number    | number      |
| Yes      | numeric metric | absentee_mail_over_votes     | Absentee Mail Over Votes     | number    | number      |
| Yes      | numeric metric | absentee_walk_in_over_votes  | Absentee Walk-in Over Votes  | number    | number      |
| Yes      | numeric metric | election_over_votes          | Election Over Votes          | number    | number      |
| Yes      | numeric metric | registered_voters            | Registered Voters            | number    | number      |
| Yes      | numeric metric | total_precincts              | Total Precincts              | number    | number      |
| Yes      | numeric metric | counted_precincts            | Counted Precincts            | number    | number      |
| Yes      | series tag     | candidate_id                 | Candidate ID                 | text      | number      |
| Yes      | series tag     | candidate_name               | Candidate Name               | text      | text        |
| Yes      | numeric metric | candidate_seq_nbr            | Candidate Seq Nbr            | number    | number      |
| Yes      | series tag     | candidate_party              | Candidate Party              | text      | text        |
| Yes      | numeric metric | absentee_mail_votes          | Absentee Mail Votes          | number    | number      |
| Yes      | numeric metric | absentee_walk_in_votes       | Absentee Walk-in Votes       | number    | number      |
| Yes      | numeric metric | election_votes               | Election Votes               | number    | number      |
| Yes      | numeric metric | total_votes                  | Total Votes                  | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8bdn-x7b5 d:2010-01-01T00:00:00.000Z t:candidate_name="(D) INOUYE, Daniel K." t:contest_id=1 t:contest_type=OF t:candidate_id=3 t:candidate_party=DEM t:contest_title="US Senator" m:absentee_walk_in_votes=28458 m:absentee_walk_in_over_votes=7 m:election_over_votes=125 m:total_precincts=351 m:counted_precincts=242 m:total_votes=277228 m:absentee_mail_over_votes=60 m:absentee_mail_blank_votes=5504 m:candidate_seq_nbr=3 m:registered_voters=690748 m:absentee_walk_in_blank_votes=1154 m:contest_seq_nbr=2 m:absentee_mail_votes=90373 m:election_blank_votes=8031 m:election_votes=158397

series e:8bdn-x7b5 d:2010-01-01T00:00:00.000Z t:candidate_name="(R) CAVASSO, Cam" t:contest_id=1 t:contest_type=OF t:candidate_id=2 t:candidate_party=REP t:contest_title="US Senator" m:absentee_walk_in_votes=8300 m:absentee_walk_in_over_votes=7 m:election_over_votes=125 m:total_precincts=351 m:counted_precincts=242 m:total_votes=79939 m:absentee_mail_over_votes=60 m:absentee_mail_blank_votes=5504 m:candidate_seq_nbr=2 m:registered_voters=690748 m:absentee_walk_in_blank_votes=1154 m:contest_seq_nbr=2 m:absentee_mail_votes=24876 m:election_blank_votes=8031 m:election_votes=46763

series e:8bdn-x7b5 d:2010-01-01T00:00:00.000Z t:candidate_name="(G) BREWER, Jim" t:contest_id=1 t:contest_type=OF t:candidate_id=1 t:candidate_party=GRE t:contest_title="US Senator" m:absentee_walk_in_votes=695 m:absentee_walk_in_over_votes=7 m:election_over_votes=125 m:total_precincts=351 m:counted_precincts=242 m:total_votes=7762 m:absentee_mail_over_votes=60 m:absentee_mail_blank_votes=5504 m:candidate_seq_nbr=1 m:registered_voters=690748 m:absentee_walk_in_blank_votes=1154 m:contest_seq_nbr=2 m:absentee_mail_votes=1934 m:election_blank_votes=8031 m:election_votes=5133
```

## Meta Commands

```ls
metric m:contest_seq_nbr p:integer l:"Contest Seq Nbr" t:dataTypeName=number

metric m:absentee_mail_blank_votes p:integer l:"Absentee Mail Blank Votes" t:dataTypeName=number

metric m:absentee_walk_in_blank_votes p:integer l:"Absentee Walk-in Blank Votes" t:dataTypeName=number

metric m:election_blank_votes p:integer l:"Election Blank Votes" t:dataTypeName=number

metric m:absentee_mail_over_votes p:integer l:"Absentee Mail Over Votes" t:dataTypeName=number

metric m:absentee_walk_in_over_votes p:integer l:"Absentee Walk-in Over Votes" t:dataTypeName=number

metric m:election_over_votes p:integer l:"Election Over Votes" t:dataTypeName=number

metric m:registered_voters p:integer l:"Registered Voters" t:dataTypeName=number

metric m:total_precincts p:integer l:"Total Precincts" t:dataTypeName=number

metric m:counted_precincts p:integer l:"Counted Precincts" t:dataTypeName=number

metric m:candidate_seq_nbr p:integer l:"Candidate Seq Nbr" t:dataTypeName=number

metric m:absentee_mail_votes p:integer l:"Absentee Mail Votes" t:dataTypeName=number

metric m:absentee_walk_in_votes p:integer l:"Absentee Walk-in Votes" t:dataTypeName=number

metric m:election_votes p:integer l:"Election Votes" t:dataTypeName=number

metric m:total_votes p:integer l:"Total Votes" t:dataTypeName=number

entity e:8bdn-x7b5 l:"General Election 2010 Summary Results.csv" t:attribution="Office of Elections" t:url=https://data.hawaii.gov/api/views/8bdn-x7b5

property e:8bdn-x7b5 t:meta.view v:id=8bdn-x7b5 v:category="Government-Wide Support" v:attributionLink=http://hawaii.gov/elections/results/ v:averageRating=0 v:name="General Election 2010 Summary Results.csv" v:attribution="Office of Elections"

property e:8bdn-x7b5 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:8bdn-x7b5 t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:8bdn-x7b5 t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| contest_id | contest_title             | contest_seq_nbr | contest_type | contest_party | absentee_mail_blank_votes | absentee_walk_in_blank_votes | election_blank_votes | absentee_mail_over_votes | absentee_walk_in_over_votes | election_over_votes | registered_voters | total_precincts | counted_precincts | candidate_id | candidate_name            | candidate_seq_nbr | candidate_party | absentee_mail_votes | absentee_walk_in_votes | election_votes | total_votes | 
| ========== | ========================= | =============== | ============ | ============= | ========================= | ============================ | ==================== | ======================== | =========================== | =================== | ================= | =============== | ================= | ============ | ========================= | ================= | =============== | =================== | ====================== | ============== | =========== | 
| 1          | US Senator                | 2               | OF           |               | 5504                      | 1154                         | 8031                 | 60                       | 7                           | 125                 | 690748            | 351             | 242               | 3            | (D) INOUYE, Daniel K.     | 3                 | DEM             | 90373               | 28458                  | 158397         | 277228      | 
| 1          | US Senator                | 2               | OF           |               | 5504                      | 1154                         | 8031                 | 60                       | 7                           | 125                 | 690748            | 351             | 242               | 2            | (R) CAVASSO, Cam          | 2                 | REP             | 24876               | 8300                   | 46763          | 79939       | 
| 1          | US Senator                | 2               | OF           |               | 5504                      | 1154                         | 8031                 | 60                       | 7                           | 125                 | 690748            | 351             | 242               | 1            | (G) BREWER, Jim           | 1                 | GRE             | 1934                | 695                    | 5133           | 7762        | 
| 1          | US Senator                | 2               | OF           |               | 5504                      | 1154                         | 8031                 | 60                       | 7                           | 125                 | 690748            | 351             | 242               | 5            | (L) MALLAN, Lloyd Jeffrey | 6                 | LIB             | 681                 | 258                    | 2018           | 2957        | 
| 1          | US Senator                | 2               | OF           |               | 5504                      | 1154                         | 8031                 | 60                       | 7                           | 125                 | 690748            | 351             | 242               | 4            | (N) JARRETT, Jeff         | 5                 | NPP             | 725                 | 252                    | 1720           | 2697        | 
| 2          | US Representative, Dist 1 | 3               | OF           |               | 4353                      | 584                          | 8109                 | 18                       | 0                           | 21                  | 690748            | 156             | 98                | 7            | (D) HANABUSA, Colleen     | 2                 | DEM             | 37956               | 6689                   | 49495          | 94140       | 
| 2          | US Representative, Dist 1 | 3               | OF           |               | 4353                      | 584                          | 8109                 | 18                       | 0                           | 21                  | 690748            | 156             | 98                | 6            | (R) DJOU, Charles         | 1                 | REP             | 32572               | 5709                   | 44442          | 82723       | 
| 3          | US Representative, Dist 2 | 4               | OF           |               | 3010                      | 1157                         | 7946                 | 38                       | 12                          | 95                  | 690748            | 195             | 144               | 9            | (D) HIRONO, Mazie         | 2                 | DEM             | 33867               | 18190                  | 80233          | 132290      | 
| 3          | US Representative, Dist 2 | 4               | OF           |               | 3010                      | 1157                         | 7946                 | 38                       | 12                          | 95                  | 690748            | 195             | 144               | 11           | (R) WILLOUGHBY, John W.   | 4                 | REP             | 11525               | 6247                   | 28632          | 46404       | 
| 3          | US Representative, Dist 2 | 4               | OF           |               | 3010                      | 1157                         | 7946                 | 38                       | 12                          | 95                  | 690748            | 195             | 144               | 8            | (L) BROCK, Pat            | 1                 | LIB             | 583                 | 388                    | 2283           | 3254        | 
```