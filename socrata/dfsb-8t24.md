# Street Intersections Served by the SFMTA School Crossing Guard Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-intersections-served-by-the-sfmta-school-crossing-guard-program) |
| Metadata | [Link](https://data.sfgov.org/api/views/dfsb-8t24) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/dfsb-8t24/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/dfsb-8t24/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | dfsb-8t24 |
| Name | Street Intersections Served by the SFMTA School Crossing Guard Program |
| Attribution | SFMTA |
| Category | Transportation |
| Tags | crossing guard intersections |
| Created | 2016-08-18T21:56:41Z |
| Publication Date | 2016-10-12T00:47:00Z |

## Description

Intersection locations served by the SFMTA Adult School Crossing Guard Program. The placement and assignment of crossing guards is dependent on a number of criteria. To find out more about the program, please visit: http://www.sfmta.com/services/streets-sidewalks/request-crossing-guard

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | object_id        | Object ID        | text      | number      |
| Yes      | series tag     | cnn_id           | CNN ID           | text      | number      |
| Yes      | series tag     | street_1         | Street 1         | text      | text        |
| Yes      | series tag     | street_2         | Street 2         | text      | text        |
| Yes      | series tag     | street_3         | Street 3         | text      | text        |
| Yes      | series tag     | street_4         | Street 4         | text      | text        |
| Yes      | series tag     | primary_street   | Primary Street   | text      | text        |
| Yes      | series tag     | secondary_street | Secondary Street | text      | text        |
| Yes      | series tag     | school_name      | School Name      | text      | text        |
| Yes      | numeric metric | number_of_guards | Number of Guards | number    | number      |
| Yes      | time           | last_edited_date | Last Edited Date | date      | date        |
```

## Time Field

```ls
Value = last_edited_date
Format & Zone = seconds
```

## Data Commands

```ls
series e:dfsb-8t24 d:2015-08-12T00:00:00.000Z t:primary_street=Broadway t:street_2="FILLMORE ST" t:street_1=BROADWAY t:school_name="Convent of the Sacred Heart" t:secondary_street=Fillmore t:cnn_id=26670000 m:number_of_guards=2

series e:dfsb-8t24 d:2015-08-12T00:00:00.000Z t:primary_street=Sunnydale t:street_2="SUNNYDALE AVE" t:street_1="RUTLAND ST" t:school_name="Our Lady of the Visitacion" t:secondary_street=Rutland t:cnn_id=20352000 m:number_of_guards=1

series e:dfsb-8t24 d:2015-08-12T00:00:00.000Z t:primary_street=Hamilton t:street_2="MANSELL ST" t:street_1="HAMILTON ST" t:school_name="El Dorado" t:secondary_street=Mansell t:cnn_id=20847000 m:number_of_guards=2
```

## Meta Commands

```ls
metric m:number_of_guards p:integer l:"Number of Guards" t:dataTypeName=number

entity e:dfsb-8t24 l:"Street Intersections Served by the SFMTA School Crossing Guard Program" t:attribution=SFMTA t:url=https://data.sfgov.org/api/views/dfsb-8t24

property e:dfsb-8t24 t:meta.view v:id=dfsb-8t24 v:category=Transportation v:attributionLink=https://www.sfmta.com/ v:averageRating=0 v:name="Street Intersections Served by the SFMTA School Crossing Guard Program" v:attribution=SFMTA

property e:dfsb-8t24 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:dfsb-8t24 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:dfsb-8t24 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| object_id | cnn_id   | street_1       | street_2      | street_3 | street_4 | primary_street | secondary_street | school_name                           | number_of_guards | last_edited_date | 
| ========= | ======== | ============== | ============= | ======== | ======== | ============== | ================ | ===================================== | ================ | ================ | 
|           | 26670000 | BROADWAY       | FILLMORE ST   |          |          | Broadway       | Fillmore         | Convent of the Sacred Heart           | 2                | 1439337600       | 
|           | 20352000 | RUTLAND ST     | SUNNYDALE AVE |          |          | Sunnydale      | Rutland          | Our Lady of the Visitacion            | 1                | 1439337600       | 
|           | 20847000 | HAMILTON ST    | MANSELL ST    |          |          | Hamilton       | Mansell          | El Dorado                             | 2                | 1439337600       | 
|           | 25683000 | DOLORES ST     | 19TH ST       |          |          | Dolores St     | 19th St          | Children's Day School                 | 1                | 1439337600       | 
|           | 23991000 | FOLSOM ST      | 23RD ST       |          |          | Folsom         | 23rd St          | Cesar Chavez                          | 1                | 1439337600       | 
|           | 20061000 | HARBOR RD      | INGALLS ST    |          |          | Harbor         | Middlepoint      | Malcolm X Academy                     | 1                | 1439337600       | 
|           | 26339000 | CENTRAL AVE    | WALLER ST     |          |          | Central        | Waller           | Chinese Immersion School at De Avilla | 1                | 1439337600       | 
|           | 25206000 | LARKIN ST      | PINE ST       |          |          | Larkin         | Pine             | Redding                               | 1                | 1439337600       | 
|           | 25631000 | DOLORES ST     | 22ND ST       |          |          | Dolores        | 22nd St          | Edison Charter Academy                | 1                | 1439337600       | 
|           | 22878000 | CLAREMONT BLVD | GRANVILLE WAY |          |          | Claremont      | Granville        | West Portal Elementary                | 2                | 1439337600       | 
```