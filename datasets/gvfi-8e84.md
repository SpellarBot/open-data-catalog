# General Election 2012 Summary Results

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/general-election-2012-summary-results-6ba94) |
| Metadata | [Link](https://data.hawaii.gov/api/views/gvfi-8e84) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/gvfi-8e84/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/gvfi-8e84/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | gvfi-8e84 |
| Name | General Election 2012 Summary Results |
| Attribution | Department of Accounting and General Services |
| Category | Government-Wide Support |
| Tags | elections |
| Created | 2013-01-23T19:34:18Z |
| Publication Date | 2013-01-23T19:37:26Z |

## Description

General Election 2012 Summary results

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
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gvfi-8e84 d:2012-01-01T00:00:00.000Z t:candidate_name="(D) OBAMA, Barack / BIDEN, Joe" t:contest_id=1 t:contest_type=OF t:candidate_id=4 t:candidate_party=DEM t:contest_title="President and Vice President" m:absentee_walk_in_votes=29561 m:absentee_walk_in_over_votes=7 m:election_over_votes=106 m:total_precincts=253 m:counted_precincts=250 m:total_votes=306658 m:absentee_mail_over_votes=122 m:absentee_mail_blank_votes=1074 m:candidate_seq_nbr=4 m:registered_voters=705668 m:absentee_walk_in_blank_votes=176 m:contest_seq_nbr=1 m:absentee_mail_votes=113186 m:election_blank_votes=977 m:election_votes=163911

series e:gvfi-8e84 d:2012-01-01T00:00:00.000Z t:candidate_name="(R) ROMNEY, Mitt / RYAN, Paul" t:contest_id=1 t:contest_type=OF t:candidate_id=1 t:candidate_party=REP t:contest_title="President and Vice President" m:absentee_walk_in_votes=11436 m:absentee_walk_in_over_votes=7 m:election_over_votes=106 m:total_precincts=253 m:counted_precincts=250 m:total_votes=121015 m:absentee_mail_over_votes=122 m:absentee_mail_blank_votes=1074 m:candidate_seq_nbr=1 m:registered_voters=705668 m:absentee_walk_in_blank_votes=176 m:contest_seq_nbr=1 m:absentee_mail_votes=42478 m:election_blank_votes=977 m:election_votes=67101

series e:gvfi-8e84 d:2012-01-01T00:00:00.000Z t:candidate_name="(L) JOHNSON, Gary / GRAY, James P." t:contest_id=1 t:contest_type=OF t:candidate_id=3 t:candidate_party=LIB t:contest_title="President and Vice President" m:absentee_walk_in_votes=310 m:absentee_walk_in_over_votes=7 m:election_over_votes=106 m:total_precincts=253 m:counted_precincts=250 m:total_votes=3840 m:absentee_mail_over_votes=122 m:absentee_mail_blank_votes=1074 m:candidate_seq_nbr=3 m:registered_voters=705668 m:absentee_walk_in_blank_votes=176 m:contest_seq_nbr=1 m:absentee_mail_votes=1028 m:election_blank_votes=977 m:election_votes=2502
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

entity e:gvfi-8e84 l:"General Election 2012 Summary Results" t:attribution="Department of Accounting and General Services" t:url=https://data.hawaii.gov/api/views/gvfi-8e84

property e:gvfi-8e84 t:meta.view v:id=gvfi-8e84 v:category="Government-Wide Support" v:attributionLink=http://hawaii.gov/dags v:averageRating=0 v:name="General Election 2012 Summary Results" v:attribution="Department of Accounting and General Services"

property e:gvfi-8e84 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:gvfi-8e84 t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:gvfi-8e84 t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| contest_id | contest_title                | contest_seq_nbr | contest_type | contest_party | absentee_mail_blank_votes | absentee_walk_in_blank_votes | election_blank_votes | absentee_mail_over_votes | absentee_walk_in_over_votes | election_over_votes | registered_voters | total_precincts | counted_precincts | candidate_id | candidate_name                     | candidate_seq_nbr | candidate_party | absentee_mail_votes | absentee_walk_in_votes | election_votes | total_votes | 
| ========== | ============================ | =============== | ============ | ============= | ========================= | ============================ | ==================== | ======================== | =========================== | =================== | ================= | =============== | ================= | ============ | ================================== | ================= | =============== | =================== | ====================== | ============== | =========== | 
| 1          | President and Vice President | 1               | OF           |               | 1074                      | 176                          | 977                  | 122                      | 7                           | 106                 | 705668            | 253             | 250               | 4            | (D) OBAMA, Barack / BIDEN, Joe     | 4                 | DEM             | 113186              | 29561                  | 163911         | 306658      | 
| 1          | President and Vice President | 1               | OF           |               | 1074                      | 176                          | 977                  | 122                      | 7                           | 106                 | 705668            | 253             | 250               | 1            | (R) ROMNEY, Mitt / RYAN, Paul      | 1                 | REP             | 42478               | 11436                  | 67101          | 121015      | 
| 1          | President and Vice President | 1               | OF           |               | 1074                      | 176                          | 977                  | 122                      | 7                           | 106                 | 705668            | 253             | 250               | 3            | (L) JOHNSON, Gary / GRAY, James P. | 3                 | LIB             | 1028                | 310                    | 2502           | 3840        | 
| 1          | President and Vice President | 1               | OF           |               | 1074                      | 176                          | 977                  | 122                      | 7                           | 106                 | 705668            | 253             | 250               | 2            | (G) STEIN, Jill / HONKALA, Cheri   | 2                 | GRE             | 906                 | 268                    | 2010           | 3184        | 
| 2          | US Senator                   | 2               | OF           |               | 2717                      | 610                          | 3272                 | 34                       | 7                           | 36                  | 705668            | 252             | 250               | 5            | (D) HIRONO, Mazie                  | 1                 | DEM             | 99054               | 26046                  | 144389         | 269489      | 
| 2          | US Senator                   | 2               | OF           |               | 2717                      | 610                          | 3272                 | 34                       | 7                           | 36                  | 705668            | 252             | 250               | 6            | (R) LINGLE, Linda                  | 2                 | REP             | 56989               | 15095                  | 88910          | 160994      | 
| 3          | US Representative, Dist 1    | 3               | OF           |               | 1662                      | 209                          | 2596                 | 42                       | 3                           | 35                  | 705668            | 116             | 115               | 8            | (D) HANABUSA, Colleen W.           | 2                 | DEM             | 49186               | 9008                   | 58311          | 116505      | 
| 3          | US Representative, Dist 1    | 3               | OF           |               | 1662                      | 209                          | 2596                 | 42                       | 3                           | 35                  | 705668            | 116             | 115               | 7            | (R) DJOU, Charles K.               | 1                 | REP             | 38395               | 6919                   | 51510          | 96824       | 
| 4          | US Representative, Dist 2    | 4               | OF           |               | 3404                      | 911                          | 5637                 | 37                       | 11                          | 73                  | 705668            | 136             | 135               | 10           | (D) GABBARD, Tulsi                 | 2                 | DEM             | 53967               | 19896                  | 94640          | 168503      | 
| 4          | US Representative, Dist 2    | 4               | OF           |               | 3404                      | 911                          | 5637                 | 37                       | 11                          | 73                  | 705668            | 136             | 135               | 9            | (R) CROWLEY, Kawika                | 1                 | REP             | 12101               | 4801                   | 23805          | 40707       | 
```