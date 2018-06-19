# Directory Of Tennis Courts With Online Registration

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-tennis-courts-with-online-registration-b1c40) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/j6ik-kjbs) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/j6ik-kjbs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/j6ik-kjbs/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | j6ik-kjbs |
| Name | Directory Of Tennis Courts With Online Registration |
| Attribution | Department of Parks and Recreation (DPR) |
| Category | Recreation |
| Tags | dpr, recreation, park, tennis, online, registration, healthy living |
| Created | 2013-01-24T15:41:42Z |
| Publication Date | 2013-06-21T20:28:25Z |

## Description

List of Tennis Courts with the facility of registering online

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | location           | Location           | text      | text        |
| Yes      | numeric metric | reservation_courts | Reservation Courts | number    | number      |
| Yes      | numeric metric | walk_on_courts     | Walk-on Courts     | number    | number      |
| Yes      | series tag     | first_reservation  | First Reservation  | text      | text        |
| Yes      | series tag     | last_reservation   | Last Reservation   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:j6ik-kjbs d:2013-01-24T07:41:43.000Z t:last_reservation=9-Oct t:location="Alley Pond Park, Queens" t:first_reservation=8-May m:walk_on_courts=16 m:reservation_courts=4

series e:j6ik-kjbs d:2013-01-24T07:41:43.000Z t:last_reservation=8-Oct t:location="Bensonhurst Park, Brooklyn" t:first_reservation=1-May m:walk_on_courts=8 m:reservation_courts=2

series e:j6ik-kjbs d:2013-01-24T07:41:43.000Z t:last_reservation=4-Nov t:location="Central Park, Manhattan" t:first_reservation=7-Apr m:walk_on_courts=26 m:reservation_courts=4
```

## Meta Commands

```ls
metric m:reservation_courts p:integer l:"Reservation Courts" t:dataTypeName=number

metric m:walk_on_courts p:integer l:"Walk-on Courts" t:dataTypeName=number

entity e:j6ik-kjbs l:"Directory Of Tennis Courts With Online Registration" t:attribution="Department of Parks and Recreation (DPR)" t:url=https://data.cityofnewyork.us/api/views/j6ik-kjbs

property e:j6ik-kjbs t:meta.view v:id=j6ik-kjbs v:category=Recreation v:attributionLink=https://www.nycgovparks.org/tennisreservation/ v:averageRating=0 v:name="Directory Of Tennis Courts With Online Registration" v:attribution="Department of Parks and Recreation (DPR)"

property e:j6ik-kjbs t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:j6ik-kjbs t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | location                             | reservation_courts | walk_on_courts | first_reservation | last_reservation | 
| =========== | ==================================== | ================== | ============== | ================= | ================ | 
| 1359013303  | Alley Pond Park, Queens              | 4                  | 16             | 8-May             | 9-Oct            | 
| 1359013303  | Bensonhurst Park, Brooklyn           | 2                  | 8              | 1-May             | 8-Oct            | 
| 1359013303  | Central Park, Manhattan              | 4                  | 26             | 7-Apr             | 4-Nov            | 
| 1359013303  | Cunningham Park, Queens              | 4                  | 20             | 1-May             | 9-Oct            | 
| 1359013303  | East River Park, Manhattan           | 3                  | 12             | 7-Apr             | 30-Sep           | 
| 1359013303  | Flushing Meadows Corona Park, Queens | 4                  | 11             | 15-Apr            | 30-Oct           | 
| 1359013303  | McCarren Park, Brooklyn              | 2                  | 7              | 7-Apr             | 28-Oct           | 
| 1359013303  | Mill Pond Park, Bronx                | 3                  | 12             | 1-May             | 8-Oct            | 
| 1359013303  | Prospect Park, Brooklyn              | 3                  | 11             | 19-May            | 7-Oct            | 
| 1359013303  | Randall's Island Park, Manhattan     | 2                  | 10             | 1-May             | 7-Oct            | 
```