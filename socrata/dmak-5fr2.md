# Primary Election Precinct Results 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/primary-election-precinct-results-2012-37305) |
| Metadata | [Link](https://data.hawaii.gov/api/views/dmak-5fr2) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/dmak-5fr2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/dmak-5fr2/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | dmak-5fr2 |
| Name | Primary Election Precinct Results 2012 |
| Attribution | Office of Elections |
| Category | Government-Wide Support |
| Tags | election, primary |
| Created | 2012-08-22T18:41:55Z |
| Publication Date | 2012-08-22T18:49:04Z |

## Description

Detailed results of the 2012 Primary Election

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | precinct_name    | "Precinct_Name"  | text      | text        |
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
series e:dmak-5fr2 d:2012-01-01T00:00:00.000Z t:candidate_name="CARROLL, John" t:contest_id=2 t:candidate_type=C t:contest_title="US Senator - R" t:precinct_name=1-Jan t:precinct_splitid=1 t:choice_id=6 m:ballots=1218 m:absentee_votes=1 m:early_votes=1 m:reg_voters=2765 m:reporting=1 m:election_votes=6

series e:dmak-5fr2 d:2012-01-01T00:00:00.000Z t:candidate_name="COLLINS, Charles Augustine" t:contest_id=2 t:candidate_type=C t:contest_title="US Senator - R" t:precinct_name=1-Jan t:precinct_splitid=1 t:choice_id=7 m:ballots=1218 m:absentee_votes=2 m:early_votes=0 m:reg_voters=2765 m:reporting=1 m:election_votes=1

series e:dmak-5fr2 d:2012-01-01T00:00:00.000Z t:candidate_name="LINGLE, Linda" t:contest_id=2 t:candidate_type=C t:contest_title="US Senator - R" t:precinct_name=1-Jan t:precinct_splitid=1 t:choice_id=8 m:ballots=1218 m:absentee_votes=34 m:early_votes=6 m:reg_voters=2765 m:reporting=1 m:election_votes=56
```

## Meta Commands

```ls
metric m:reg_voters p:integer l:Reg_voters t:dataTypeName=number

metric m:ballots p:integer l:Ballots t:dataTypeName=number

metric m:reporting p:integer l:Reporting t:dataTypeName=number

metric m:absentee_votes p:integer l:Absentee_votes t:dataTypeName=number

metric m:early_votes p:integer l:Early_votes t:dataTypeName=number

metric m:election_votes p:integer l:Election_Votes t:dataTypeName=number

entity e:dmak-5fr2 l:"Primary Election Precinct Results 2012" t:attribution="Office of Elections" t:url=https://data.hawaii.gov/api/views/dmak-5fr2

property e:dmak-5fr2 t:meta.view v:id=dmak-5fr2 v:category="Government-Wide Support" v:attributionLink=http://hawaii.gov/elections/ v:averageRating=0 v:name="Primary Election Precinct Results 2012" v:attribution="Office of Elections"

property e:dmak-5fr2 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:dmak-5fr2 t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:dmak-5fr2 t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| precinct_name | split_name | precinct_splitid | reg_voters | ballots | reporting | contest_id | contest_title  | contest_party | choice_id | candidate_name             | choice_party | candidate_type | absentee_votes | early_votes | election_votes | 
| ============= | ========== | ================ | ========== | ======= | ========= | ========== | ============== | ============= | ========= | ========================== | ============ | ============== | ============== | =========== | ============== | 
| 1-Jan         |            | 1                | 2765       | 1218    | 1         | 2          | US Senator - R |               | 6         | CARROLL, John              |              | C              | 1              | 1           | 6              | 
| 1-Jan         |            | 1                | 2765       | 1218    | 1         | 2          | US Senator - R |               | 7         | COLLINS, Charles Augustine |              | C              | 2              | 0           | 1              | 
| 1-Jan         |            | 1                | 2765       | 1218    | 1         | 2          | US Senator - R |               | 8         | LINGLE, Linda              |              | C              | 34             | 6           | 56             | 
| 1-Jan         |            | 1                | 2765       | 1218    | 1         | 2          | US Senator - R |               | 9         | PIRKOWSKI, Eddie           |              | C              | 2              | 0           | 2              | 
| 1-Jan         |            | 1                | 2765       | 1218    | 1         | 2          | US Senator - R |               | 10        | ROCO, John P.              |              | C              | 0              | 0           | 0              | 
| 1-Jan         |            | 1                | 2765       | 1218    | 1         | 3          | US Senator - N |               | 11        | BEASLEY, Heath             |              | C              | 1              | 0           | 5              | 
| 1-Jan         |            | 1                | 2765       | 1218    | 1         | 4          | US Senator - D |               | 12        | CASE, Ed                   |              | C              | 181            | 28          | 192            | 
| 1-Jan         |            | 1                | 2765       | 1218    | 1         | 4          | US Senator - D |               | 13        | GILLESPIE, Michael D.      |              | C              | 1              | 0           | 1              | 
| 1-Jan         |            | 1                | 2765       | 1218    | 1         | 4          | US Senator - D |               | 14        | GIMBERNAT, Antonio         |              | C              | 1              | 0           | 3              | 
| 1-Jan         |            | 1                | 2765       | 1218    | 1         | 4          | US Senator - D |               | 15        | HIRONO, Mazie              |              | C              | 304            | 48          | 312            | 
```