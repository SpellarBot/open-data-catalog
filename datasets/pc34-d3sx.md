# Safe Route to Schools - Priority Schools

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/safe-route-to-schools-priority-schools-4c0cb) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pc34-d3sx) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pc34-d3sx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pc34-d3sx/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pc34-d3sx |
| Name | Safe Route to Schools - Priority Schools |
| Attribution | Department of Transportation (DOT) |
| Category | Transportation |
| Tags | dot, safe route, schools, priority school, clean web |
| Created | 2013-03-06T16:46:46Z |
| Publication Date | 2013-03-19T20:46:45Z |

## Description

DOT has analyzed the latest citywide crash data and school data in order to identify a new group of 135 public, private and parochial elementary and middle schools Priority Schools. Each of DOT's Priority Schools receives an individualized planning study which determines both short-term and long-term measures to improve safety.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name             | Data Type | Render Type |
| ======== | ============== | =============== | ================ | ========= | =========== |
| No       | time           | :updated_at     | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | borough         | Borough          | text      | text        |
| Yes      | numeric metric | community_board | Community Board  | number    | number      |
| Yes      | series tag     | school_type     | School Type      | text      | text        |
| Yes      | series tag     | school_name_id  | School Name / ID | text      | text        |
| No       |                | address         | Address          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:pc34-d3sx d:2013-03-06T08:46:47.000Z t:school_type=Public t:school_name_id="P.S. 157 GROVE HILL" t:borough=Bronx m:community_board=1

series e:pc34-d3sx d:2013-03-06T08:46:47.000Z t:school_type=Public t:school_name_id="P.S. 60 (New School #2)" t:borough=Bronx m:community_board=2

series e:pc34-d3sx d:2013-03-06T08:46:47.000Z t:school_type=Public t:school_name_id="HARRIET TUBMAN CHARTER SCHOOL" t:borough=Bronx m:community_board=3
```

## Meta Commands

```ls
metric m:community_board p:integer l:"Community Board" t:dataTypeName=number

entity e:pc34-d3sx l:"Safe Route to Schools - Priority Schools" t:attribution="Department of Transportation (DOT)" t:url=https://data.cityofnewyork.us/api/views/pc34-d3sx

property e:pc34-d3sx t:meta.view v:id=pc34-d3sx v:category=Transportation v:attributionLink=http://www.nyc.gov/html/dot/html/safety/saferoutes.shtml v:averageRating=0 v:name="Safe Route to Schools - Priority Schools" v:attribution="Department of Transportation (DOT)"

property e:pc34-d3sx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:pc34-d3sx t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | borough | community_board | school_type | school_name_id                               | address                        | 
| =========== | ======= | =============== | =========== | ============================================ | ============================== | 
| 1362559607  | Bronx   | 1               | Public      | P.S. 157 GROVE HILL                          | 757 Caudwell Avenue            | 
| 1362559607  | Bronx   | 2               | Public      | P.S. 60 (New School #2)                      | 888 Rev James A. Polite Avenue | 
| 1362559607  | Bronx   | 3               | Public      | HARRIET TUBMAN CHARTER SCHOOL                | 3565 3rd Avenue                | 
| 1362559607  | Bronx   | 3               | Public      | P.S. 132 GARRETT A. MORGAN SCHOOL            | 1245 Washington Avenue         | 
| 1362559607  | Bronx   | 3               | Public      | P.S. 140 EAGLE SCHOOL                        | 916 Eagle Avenue               | 
| 1362559607  | Bronx   | 4               | Public      | FAMILY LIFE ACADEMY CHARTER SCHOOL           | 14 West 170th Street           | 
| 1362559607  | Bronx   | 4               | Public      | GRAND CONCOURSE ADADEMY CHARTER SCHOOL       | 116 East 169th Street          | 
| 1362559607  | Bronx   | 4               | Public      | JHS 166 ROBERTO CLEMENTE SCHOOL              | 250 East 164 Street            | 
| 1362559607  | Bronx   | 4               | Public      | P.S. 64 PURA BELPRE SCHOOL                   | 1425 Walton Avenue             | 
| 1362559607  | Bronx   | 4               | Public      | P.S. 88 S. SILVERSTEIN LITTLE SPARROW SCHOOL | 1340 Sheridan Avenue           | 
```