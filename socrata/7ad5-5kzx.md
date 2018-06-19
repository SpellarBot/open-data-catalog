# AFD Fire Incidents 2014 January Thru December

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/afd-fire-incidents-2014-january-thru-december) |
| Metadata | [Link](https://data.austintexas.gov/api/views/7ad5-5kzx) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/7ad5-5kzx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/7ad5-5kzx/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 7ad5-5kzx |
| Name | AFD Fire Incidents 2014 January Thru December |
| Attribution | Austin Fire Department (Planning & Research) |
| Category | Public Safety |
| Tags | afd, fire, incidents |
| Created | 2016-03-29T21:28:51Z |
| Publication Date | 2016-03-29T21:34:00Z |

## Description

Fire Incident data within City of Austin. Fire Incidents ONLY - no medical, hazmat, rescues, or other problem types. Calendar Year 2014

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
series e:7ad5-5kzx d:2014-01-01T00:00:00.000Z t:masterincidentnumber=14002097 t:call_type=Fire t:districts=- t:battalion=B3 t:prioritydescription=2F t:problem="AUTO - Auto Fire" t:response_status="Code 3" t:responsearea=00-2303 t:jurisdiction=AFD m:dayofmonth=7

series e:7ad5-5kzx d:2014-01-01T00:00:00.000Z t:masterincidentnumber=14002183 t:call_type=Fire t:districts=- t:battalion=B2 t:prioritydescription=2F t:problem="AUTO - Auto Fire" t:response_status="Code 3" t:responsearea=00-1603 t:jurisdiction=AFD m:dayofmonth=7

series e:7ad5-5kzx d:2014-01-01T00:00:00.000Z t:masterincidentnumber=14002327 t:call_type=Fire t:districts=- t:battalion=B1 t:prioritydescription=3F t:problem="ELEC - Electrical Fire" t:response_status="Code 3" t:responsearea=00-1001 t:jurisdiction=AFD m:dayofmonth=7
```

## Meta Commands

```ls
metric m:dayofmonth p:integer l:DayOfMonth t:dataTypeName=number

entity e:7ad5-5kzx l:"AFD Fire Incidents 2014 January Thru December" t:attribution="Austin Fire Department (Planning & Research)" t:url=https://data.austintexas.gov/api/views/7ad5-5kzx

property e:7ad5-5kzx t:meta.view v:id=7ad5-5kzx v:category="Public Safety" v:averageRating=0 v:name="AFD Fire Incidents 2014 January Thru December" v:attribution="Austin Fire Department (Planning & Research)"

property e:7ad5-5kzx t:meta.view.owner v:id=uy54-8dp2 v:profileImageUrlMedium=/api/users/uy54-8dp2/profile_images/THUMB v:profileImageUrlLarge=/api/users/uy54-8dp2/profile_images/LARGE v:screenName="Christine Thies" v:profileImageUrlSmall=/api/users/uy54-8dp2/profile_images/TINY v:displayName="Christine Thies"

property e:7ad5-5kzx t:meta.view.tableauthor v:id=uy54-8dp2 v:profileImageUrlMedium=/api/users/uy54-8dp2/profile_images/THUMB v:profileImageUrlLarge=/api/users/uy54-8dp2/profile_images/LARGE v:screenName="Christine Thies" v:profileImageUrlSmall=/api/users/uy54-8dp2/profile_images/TINY v:roleName=editor_stories v:displayName="Christine Thies"
```

## Top Records

```ls
| masterincidentnumber | calendaryear | month | dayofmonth | call_type | problem                | battalion | jurisdiction | responsearea | prioritydescription | response_status | districts | 
| ==================== | ============ | ===== | ========== | ========= | ====================== | ========= | ============ | ============ | =================== | =============== | ========= | 
| 14002097             | 2014         | Jan   | 7          | Fire      | AUTO - Auto Fire       | B3        | AFD          | 00-2303      | 2F                  | Code 3          | -         | 
| 14002183             | 2014         | Jan   | 7          | Fire      | AUTO - Auto Fire       | B2        | AFD          | 00-1603      | 2F                  | Code 3          | -         | 
| 14002327             | 2014         | Jan   | 7          | Fire      | ELEC - Electrical Fire | B1        | AFD          | 00-1001      | 3F                  | Code 3          | -         | 
| 14002361             | 2014         | Jan   | 7          | Fire      | BBQ - Unsafe Cooking   | B3        | AFD          | 00-2305      | 4F                  | Code 3          | -         | 
| 14002426             | 2014         | Jan   | 7          | Fire      | DUMP - Dumpster Fire   | B5        | AFD          | 00-2402      | 3F                  | Code 3          | -         | 
| 14002433             | 2014         | Jan   | 7          | Fire      | AUTO - Auto Fire       | B3        | AFD          | 00-2301      | 2F                  | Code 3          | -         | 
| 14002450             | 2014         | Jan   | 8          | Fire      | AUTO - Auto Fire       | B3        | AFD          | 00-2803      | 2F                  | Code 3          | -         | 
| 14002514             | 2014         | Jan   | 8          | Fire      | BOXL- Structure Fire   | B4        | AFD          | 00-2904      | 1F                  | Code 3          | -         | 
| 14002586             | 2014         | Jan   | 8          | Fire      | BOXL- Structure Fire   | B4        | AFD          | 00-2703      | 1F                  | Code 3          | -         | 
| 14002683             | 2014         | Jan   | 8          | Fire      | TRASH - Trash Fire     | B3        | AFD          | 00-3001      | 3F                  | Code 3          | -         | 
```