# Unmetered Motorcycle Parking

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unmetered-motorcycle-parking) |
| Metadata | [Link](https://data.sfgov.org/api/views/iw7d-yey5) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/iw7d-yey5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/iw7d-yey5/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | iw7d-yey5 |
| Name | Unmetered Motorcycle Parking |
| Category | Transportation |
| Tags | motorcycles, parking, unmetered |
| Created | 2016-02-27T01:33:26Z |
| Publication Date | 2016-04-15T18:20:53Z |

## Description

Shows the locations and space count of unmetered motorcycle parking for the City of San Francisco. Dataset is manually updated when MTA Board resolutions are passed. This dataset is updated infrequently, several times a year at most.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | object_id        | Object ID        | text      | number      |
| Yes      | series tag     | street           | Street           | text      | text        |
| Yes      | series tag     | side_of_street   | Side of Street   | text      | text        |
| Yes      | series tag     | location         | Location         | text      | text        |
| Yes      | numeric metric | number_of_spaces | Number of Spaces | number    | number      |
| Yes      | series tag     | legislation      | Legislation      | text      | text        |
| Yes      | series tag     | description      | Description      | text      | text        |
| Yes      | time           | legislation_date | Legislation Date | date      | date        |
| No       |                | last_edited_date | Last Edited Date | date      | date        |
```

## Time Field

```ls
Value = legislation_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = last_edited_date
```

## Data Commands

```ls
series e:iw7d-yey5 d:2007-01-22T00:00:00.000Z t:side_of_street=W t:location="W. OF 7TH ST" t:description="93 FEET TO 112 FEET N. OF TOWNSEND" t:street="7TH ST" t:object_id=1 m:number_of_spaces=5

series e:iw7d-yey5 d:2007-03-05T00:00:00.000Z t:side_of_street=E t:location="E SIDE OF 8TH ST" t:description="93 FEET TO 112 FEET N. OF HERON" t:street="8TH ST" t:object_id=2 m:number_of_spaces=6

series e:iw7d-yey5 d:2007-03-05T00:00:00.000Z t:side_of_street=N t:location="N OF 15TH ST" t:description="20 FEET EAST OF MARKET ST" t:street="15TH ST" t:object_id=3 m:number_of_spaces=5
```

## Meta Commands

```ls
metric m:number_of_spaces p:integer l:"Number of Spaces" t:dataTypeName=number

entity e:iw7d-yey5 l:"Unmetered Motorcycle Parking" t:url=https://data.sfgov.org/api/views/iw7d-yey5

property e:iw7d-yey5 t:meta.view v:id=iw7d-yey5 v:category=Transportation v:averageRating=0 v:name="Unmetered Motorcycle Parking"

property e:iw7d-yey5 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:iw7d-yey5 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:iw7d-yey5 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| object_id | street     | side_of_street | location                  | number_of_spaces | legislation | description                        | legislation_date | last_edited_date | 
| ========= | ========== | ============== | ========================= | ================ | =========== | ================================== | ================ | ================ | 
| 1         | 7TH ST     | W              | W. OF 7TH ST              | 5                |             | 93 FEET TO 112 FEET N. OF TOWNSEND | 1169424000       |                  | 
| 2         | 8TH ST     | E              | E SIDE OF 8TH ST          | 6                |             | 93 FEET TO 112 FEET N. OF HERON    | 1173052800       |                  | 
| 3         | 15TH ST    | N              | N OF 15TH ST              | 5                |             | 20 FEET EAST OF MARKET ST          | 1173052800       |                  | 
| 4         | 21ST ST    | S              | 2965 21ST ST              | 3                |             | FROM 2965 TO 2971 21ST ST          | 1177286400       |                  | 
| 5         | BRANNAN ST | W              | 548 BRANNAN ST            | 3                | 08156       | 458 BRANNAN ST TO 10FT E           | 1221436800       |                  | 
| 6         | 27TH AVE   | W              | 671 27TH AVE              | 1                |             | 671 27TH AVE                       |                  |                  | 
| 7         | FILBERT ST | S              | EAST OF LAGUNA ST         | 3                |             | BTWN 1885 AND 1879 FILBERT         |                  |                  | 
| 8         | FLORIDA ST | W              | WEST S. 24 FLORIDA ST     | 6                |             | FROM 24TH FLORIDA ST TO 24FT S.    |                  |                  | 
| 9         | OAKWOOD ST | W              | W.S.FROM 20 TO 30 OAKWOOD | 3                |             | 20 TO 30 OAKWOOD ST                |                  |                  | 
| 10        | FREELON ST | N              | E. OF 4TH ST              | 6                |             | FROM 108FT TO 139 FT E. OF 4TH ST  |                  |                  | 
```