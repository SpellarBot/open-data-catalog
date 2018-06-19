# Department of Defense - State Civil Defense Emergency Siren Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-defense-state-civil-defense-emergency-siren-locations-30e26) |
| Metadata | [Link](https://data.hawaii.gov/api/views/jety-j7dm) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/jety-j7dm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/jety-j7dm/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | jety-j7dm |
| Name | Department of Defense - State Civil Defense Emergency Siren Locations |
| Attribution | Department of Defense |
| Category | Public Safety |
| Tags | siren, scd |
| Created | 2012-07-31T21:52:39Z |
| Publication Date | 2012-09-04T23:34:36Z |

## Description

State Civil Defense Emergency Siren Locations

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | county      | COUNTY     | text      | text        |
| Yes      | series tag     | unique_id   | UNIQUE_ID  | text      | text        |
| Yes      | series tag     | location    | LOCATION   | text      | text        |
| Yes      | numeric metric | decibel     | DECIBEL    | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jety-j7dm d:2012-07-31T14:52:40.000Z t:unique_id=HA102 t:location="Baker Ave." t:county=HAWAII m:decibel=115

series e:jety-j7dm d:2012-07-31T14:52:40.000Z t:unique_id=HA103 t:location=Onekahakaha t:county=HAWAII m:decibel=121

series e:jety-j7dm d:2012-07-31T14:52:40.000Z t:unique_id=HA104 t:location="Banyan Drive" t:county=HAWAII m:decibel=121
```

## Meta Commands

```ls
metric m:decibel p:integer l:DECIBEL t:dataTypeName=number

entity e:jety-j7dm l:"Department of Defense - State Civil Defense Emergency Siren Locations" t:attribution="Department of Defense" t:url=https://data.hawaii.gov/api/views/jety-j7dm

property e:jety-j7dm t:meta.view v:id=jety-j7dm v:category="Public Safety" v:attributionLink=http://hawaii.gov/DOD v:averageRating=0 v:name="Department of Defense - State Civil Defense Emergency Siren Locations" v:attribution="Department of Defense"

property e:jety-j7dm t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:jety-j7dm t:meta.view.owner v:id=a7ka-qy6t v:screenName="Reynold Hioki" v:displayName="Reynold Hioki"

property e:jety-j7dm t:meta.view.tableauthor v:id=a7ka-qy6t v:screenName="Reynold Hioki" v:roleName=editor v:displayName="Reynold Hioki"
```

## Top Records

```ls
| :updated_at | county | unique_id | location            | decibel | 
| =========== | ====== | ========= | =================== | ======= | 
| 1343746360  | HAWAII | HA102     | Baker Ave.          | 115     | 
| 1343746360  | HAWAII | HA103     | Onekahakaha         | 121     | 
| 1343746360  | HAWAII | HA104     | Banyan Drive        | 121     | 
| 1343746360  | HAWAII | HA105     | Kawailani Street    | 119     | 
| 1343746360  | HAWAII | HA106     | South Hilo Baseyard | 119     | 
| 1343746360  | HAWAII | HA107     | Federal Building    | 121     | 
| 1343746360  | HAWAII | HA108     | Kaumana Dr          | 119     | 
| 1343746360  | HAWAII | HA109     | Papaikou            | 119     | 
| 1343746360  | HAWAII | HA110     | Pepeekeo            | 119     | 
| 1343746360  | HAWAII | HA111     | Honomu              | 115     | 
```