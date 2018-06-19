# AFD Fire Incidents 2015 January Thru December

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/afd-fire-incidents-2015-january-thru-december) |
| Metadata | [Link](https://data.austintexas.gov/api/views/h77e-esmt) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/h77e-esmt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/h77e-esmt/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | h77e-esmt |
| Name | AFD Fire Incidents 2015 January Thru December |
| Category | Public Safety |
| Tags | afd, fire, incidents |
| Created | 2016-03-29T21:32:00Z |
| Publication Date | 2016-03-29T21:33:13Z |

## Description

Fire Incident data within City of Austin. Fire Incidents ONLY - no medical, hazmat, rescues, or other problem types. Calendar Year 2015

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
| Yes      | series tag     | districts            | Districts            | text      | number      |
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
series e:h77e-esmt d:2015-01-01T00:00:00.000Z t:masterincidentnumber=15000001 t:call_type=Fire t:districts=3 t:battalion=B5 t:prioritydescription=3F t:problem="TRASH - Trash Fire" t:response_status="Code 3" t:responsearea=00-0501 t:jurisdiction=AFD m:dayofmonth=1

series e:h77e-esmt d:2015-01-01T00:00:00.000Z t:masterincidentnumber=15000011 t:call_type=Fire t:districts=7 t:battalion=B3 t:prioritydescription=3F t:problem="TRASH - Trash Fire" t:response_status="Code 3" t:responsearea=00-2801 t:jurisdiction=AFD m:dayofmonth=1

series e:h77e-esmt d:2015-01-01T00:00:00.000Z t:masterincidentnumber=15000012 t:call_type=Fire t:districts=8 t:battalion=B4 t:prioritydescription=3F t:problem="TRASH - Trash Fire" t:response_status="Code 3" t:responsearea=00-3701 t:jurisdiction=AFD m:dayofmonth=1
```

## Meta Commands

```ls
metric m:dayofmonth p:integer l:DayOfMonth t:dataTypeName=number

entity e:h77e-esmt l:"AFD Fire Incidents 2015 January Thru December" t:url=https://data.austintexas.gov/api/views/h77e-esmt

property e:h77e-esmt t:meta.view v:id=h77e-esmt v:category="Public Safety" v:averageRating=0 v:name="AFD Fire Incidents 2015 January Thru December"

property e:h77e-esmt t:meta.view.owner v:id=uy54-8dp2 v:profileImageUrlMedium=/api/users/uy54-8dp2/profile_images/THUMB v:profileImageUrlLarge=/api/users/uy54-8dp2/profile_images/LARGE v:screenName="Christine Thies" v:profileImageUrlSmall=/api/users/uy54-8dp2/profile_images/TINY v:displayName="Christine Thies"

property e:h77e-esmt t:meta.view.tableauthor v:id=uy54-8dp2 v:profileImageUrlMedium=/api/users/uy54-8dp2/profile_images/THUMB v:profileImageUrlLarge=/api/users/uy54-8dp2/profile_images/LARGE v:screenName="Christine Thies" v:profileImageUrlSmall=/api/users/uy54-8dp2/profile_images/TINY v:roleName=editor_stories v:displayName="Christine Thies"
```

## Top Records

```ls
| masterincidentnumber | calendaryear | month | dayofmonth | call_type | problem                | battalion | jurisdiction | responsearea | prioritydescription | response_status | districts | 
| ==================== | ============ | ===== | ========== | ========= | ====================== | ========= | ============ | ============ | =================== | =============== | ========= | 
| 15000001             | 2015         | Jan   | 1          | Fire      | TRASH - Trash Fire     | B5        | AFD          | 00-0501      | 3F                  | Code 3          | 3         | 
| 15000011             | 2015         | Jan   | 1          | Fire      | TRASH - Trash Fire     | B3        | AFD          | 00-2801      | 3F                  | Code 3          | 7         | 
| 15000012             | 2015         | Jan   | 1          | Fire      | TRASH - Trash Fire     | B4        | AFD          | 00-3701      | 3F                  | Code 3          | 8         | 
| 15000032             | 2015         | Jan   | 1          | Fire      | TRASH - Trash Fire     | B3        | AFD          | 00-3004      | 3F                  | Left Blank      | 1         | 
| 15000035             | 2015         | Jan   | 1          | Fire      | TRASH - Trash Fire     | B4        | AFD          | 00-2904      | 3F                  | Code 1          | 8         | 
| 15000044             | 2015         | Jan   | 1          | Fire      | DUMP - Dumpster Fire   | B5        | AFD          | 00-2401      | 3F                  | Code 3          | 2         | 
| 15000052             | 2015         | Jan   | 1          | Fire      | TRASH - Trash Fire     | B3        | AFD          | 00-3001      | 3F                  | Code 3          | 4         | 
| 15000055             | 2015         | Jan   | 1          | Fire      | TRASH - Trash Fire     | B2        | AFD          | 00-2104      | 3F                  | Code 3          | 10        | 
| 15000081             | 2015         | Jan   | 1          | Fire      | ELEC - Electrical Fire | B4        | AFD          | 00-2702      | 3F                  | Code 3          | 8         | 
| 15000084             | 2015         | Jan   | 1          | Fire      | DUMP - Dumpster Fire   | B3        | AFD          | 00-0802      | 3F                  | Code 3          | 4         | 
```