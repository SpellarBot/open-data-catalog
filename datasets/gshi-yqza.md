# Transportable Classroom Units- Buildings & Schools

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/transportable-classroom-units-buildings-schools) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/gshi-yqza) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/gshi-yqza/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/gshi-yqza/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | gshi-yqza |
| Name | Transportable Classroom Units- Buildings & Schools |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Created | 2015-03-02T22:12:07Z |
| Publication Date | 2015-03-02T22:13:01Z |

## Description

Transportable Classroom Units- Buildings & Schools

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | numeric metric | jur_dist          | JUR DIST          | number        | number        |
| Yes      | numeric metric | council_dist      | COUNCIL DIST      | number        | number        |
| Yes      | series tag     | bldg              | BLDG              | text          | text          |
| Yes      | series tag     | org               | ORG               | text          | text          |
| Yes      | series tag     | organization_name | ORGANIZATION NAME | text          | text          |
| Yes      | time           | room_no           | ROOM NO           | calendar_date | calendar_date |
| Yes      | series tag     | function          | FUNCTION          | text          | text          |
| Yes      | numeric metric | capacity          | CAPACITY          | number        | number        |
```

## Time Field

```ls
Value = room_no
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:gshi-yqza d:2015-03-02T14:12:10.000Z t:org=M163 t:organization_name="P.S. 163 - MANHATTAN" t:bldg=M919 t:function="FIRST GRADE" m:council_dist=7 m:jur_dist=3 m:capacity=20

series e:gshi-yqza d:2015-03-02T14:12:10.000Z t:org=M163 t:organization_name="P.S. 163 - MANHATTAN" t:bldg=M919 t:function=KINDERGARTEN m:council_dist=7 m:jur_dist=3 m:capacity=15

series e:gshi-yqza d:2015-03-02T14:12:10.000Z t:org=M163 t:organization_name="P.S. 163 - MANHATTAN" t:bldg=M919 t:function=KINDERGARTEN m:council_dist=7 m:jur_dist=3 m:capacity=15
```

## Meta Commands

```ls
metric m:jur_dist p:integer l:"JUR DIST" t:dataTypeName=number

metric m:council_dist p:integer l:"COUNCIL DIST" t:dataTypeName=number

metric m:capacity p:integer l:CAPACITY t:dataTypeName=number

entity e:gshi-yqza l:"Transportable Classroom Units- Buildings & Schools" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/gshi-yqza

property e:gshi-yqza t:meta.view v:id=gshi-yqza v:category=Education v:averageRating=0 v:name="Transportable Classroom Units- Buildings & Schools" v:attribution="School Construction Authority (SCA)"

property e:gshi-yqza t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:gshi-yqza t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| jur_dist | council_dist | bldg | org  | organization_name                     | room_no             | function      | capacity | 
| ======== | ============ | ==== | ==== | ===================================== | =================== | ============= | ======== | 
| 3        | 7            | M919 | M163 | P.S. 163 - MANHATTAN                  |                     | FIRST GRADE   | 20       | 
| 3        | 7            | M919 | M163 | P.S. 163 - MANHATTAN                  |                     | KINDERGARTEN  | 15       | 
| 3        | 7            | M919 | M163 | P.S. 163 - MANHATTAN                  |                     | KINDERGARTEN  | 15       | 
| 3        | 7            | M919 | M163 | P.S. 163 - MANHATTAN                  |                     | KINDERGARTEN  | 15       | 
| 6        | 10           | M902 | M048 | P.S. 48 - MANHATTAN                   |                     | KINDERGARTEN  | 16       | 
| 6        | 10           | M902 | M048 | P.S. 48 - MANHATTAN                   |                     | KINDERGARTEN  | 16       | 
| 6        | 10           | M902 | M048 | P.S. 48 - MANHATTAN                   |                     | KINDERGARTEN  | 16       | 
| 6        | 10           | M902 | M048 | P.S. 48 - MANHATTAN                   |                     | KINDERGARTEN  | 16       | 
| 6        | 10           | M965 | M430 | THE EQUITY PROJECT CHARTER SCHOOL - M | 1970-01-01T01:00:00 | SEVENTH GRADE | 28       | 
| 6        | 10           | M965 | M430 | THE EQUITY PROJECT CHARTER SCHOOL - M | 1970-01-01T10:00:00 | EIGHTH GRADE  | 28       | 
```