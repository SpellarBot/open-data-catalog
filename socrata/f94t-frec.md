# AFD Fire Incidents 2013 January Thru December

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/afd-fire-incidents-2013-january-thru-december) |
| Metadata | [Link](https://data.austintexas.gov/api/views/f94t-frec) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/f94t-frec/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/f94t-frec/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | f94t-frec |
| Name | AFD Fire Incidents 2013 January Thru December |
| Attribution | Austin Fire Department (Planning & Research) |
| Category | Public Safety |
| Tags | afd, fire, incidents, city of austin |
| Created | 2016-03-29T21:25:30Z |
| Publication Date | 2016-03-29T21:34:41Z |

## Description

Fire Incidents within City of Austin. Fire Incidents ONLY - no medical, hazmat, rescues, or other problem types. Calendar Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | masterincidentnumber | MasterIncidentNumber | text      | number      |
| No       |                | calendaryear         | CalendarYear         | number    | number      |
| No       |                | month                | Month                | text      | text        |
| Yes      | numeric metric | dayofmonth           | DayOfMonth           | number    | number      |
| Yes      | series tag     | call_type            | Call_Type            | text      | text        |
| Yes      | series tag     | problem              | Problem              | text      | text        |
| Yes      | series tag     | battalion            | Battalion            | text      | text        |
| Yes      | series tag     | jurisdiction         | Jurisdiction         | text      | text        |
| Yes      | series tag     | responsearea         | ResponseArea         | text      | text        |
| Yes      | series tag     | prioritydescription  | PriorityDescription  | text      | text        |
| Yes      | series tag     | response_status      | Response Status      | text      | text        |
| Yes      | series tag     | districts            | Districts            | text      | text        |
```

## Time Field

```ls
Value = calendaryear-month
Format & Zone = yyyy-MMM
```

## Series Fields

```ls
Excluded Fields = calendaryear,month
```

## Data Commands

```ls
series e:f94t-frec d:2013-01-01T00:00:00.000Z t:masterincidentnumber=13006165 t:call_type=Fire t:districts=- t:battalion=B3 t:prioritydescription=4F t:problem="BBQ - Unsafe Cooking" t:response_status="Code 1" t:responsearea=00-2304 t:jurisdiction=AFD m:dayofmonth=19

series e:f94t-frec d:2013-01-01T00:00:00.000Z t:masterincidentnumber=13006178 t:call_type=Fire t:districts=- t:battalion=B4 t:prioritydescription=2F t:problem="GRASS - Small Grass Fire" t:response_status="Code 3" t:responsearea=00-1701 t:jurisdiction=AFD m:dayofmonth=19

series e:f94t-frec d:2013-01-01T00:00:00.000Z t:masterincidentnumber=13006186 t:call_type=Fire t:districts=- t:battalion=B4 t:prioritydescription=2F t:problem="GRASS - Small Grass Fire" t:response_status="Code 3" t:responsearea=00-1708 t:jurisdiction=AFD m:dayofmonth=19
```

## Meta Commands

```ls
metric m:dayofmonth p:integer l:DayOfMonth t:dataTypeName=number

entity e:f94t-frec l:"AFD Fire Incidents 2013 January Thru December" t:attribution="Austin Fire Department (Planning & Research)" t:url=https://data.austintexas.gov/api/views/f94t-frec

property e:f94t-frec t:meta.view v:id=f94t-frec v:category="Public Safety" v:averageRating=0 v:name="AFD Fire Incidents 2013 January Thru December" v:attribution="Austin Fire Department (Planning & Research)"

property e:f94t-frec t:meta.view.owner v:id=uy54-8dp2 v:profileImageUrlMedium=/api/users/uy54-8dp2/profile_images/THUMB v:profileImageUrlLarge=/api/users/uy54-8dp2/profile_images/LARGE v:screenName="Christine Thies" v:profileImageUrlSmall=/api/users/uy54-8dp2/profile_images/TINY v:displayName="Christine Thies"

property e:f94t-frec t:meta.view.tableauthor v:id=uy54-8dp2 v:profileImageUrlMedium=/api/users/uy54-8dp2/profile_images/THUMB v:profileImageUrlLarge=/api/users/uy54-8dp2/profile_images/LARGE v:screenName="Christine Thies" v:profileImageUrlSmall=/api/users/uy54-8dp2/profile_images/TINY v:roleName=editor_stories v:displayName="Christine Thies"
```

## Top Records

```ls
| masterincidentnumber | calendaryear | month | dayofmonth | call_type | problem                  | battalion | jurisdiction | responsearea | prioritydescription | response_status | districts | 
| ==================== | ============ | ===== | ========== | ========= | ======================== | ========= | ============ | ============ | =================== | =============== | ========= | 
| 13006165             | 2013         | Jan   | 19         | Fire      | BBQ - Unsafe Cooking     | B3        | AFD          | 00-2304      | 4F                  | Code 1          | -         | 
| 13006178             | 2013         | Jan   | 19         | Fire      | GRASS - Small Grass Fire | B4        | AFD          | 00-1701      | 2F                  | Code 3          | -         | 
| 13006186             | 2013         | Jan   | 19         | Fire      | GRASS - Small Grass Fire | B4        | AFD          | 00-1708      | 2F                  | Code 3          | -         | 
| 13006187             | 2013         | Jan   | 19         | Fire      | GRASS - Small Grass Fire | B5        | AFD          | 00-1504      | 2F                  | Code 3          | -         | 
| 13006201             | 2013         | Jan   | 19         | Fire      | DUMP - Dumpster Fire     | B2        | AFD          | 00-3809      | 3F                  | Code 3          | -         | 
| 13006234             | 2013         | Jan   | 19         | Fire      | ELEC - Electrical Fire   | B4        | AFD          | 00-2906      | 3F                  | Code 3          | -         | 
| 13006244             | 2013         | Jan   | 19         | Fire      | BOXL- Structure Fire     | B5        | AFD          | 00-2402      | 1F                  | Code 3          | -         | 
| 13006245             | 2013         | Jan   | 19         | Fire      | TRASH - Trash Fire       | B3        | AFD          | 00-2801      | 3F                  | Code 3          | -         | 
| 13006259             | 2013         | Jan   | 19         | Fire      | TRASH - Trash Fire       | B1        | AFD          | 00-1604      | 3F                  | Code 3          | -         | 
| 13006261             | 2013         | Jan   | 19         | Fire      | TRASH - Trash Fire       | B3        | AFD          | 00-2801      | 3F                  | Code 3          | -         | 
```