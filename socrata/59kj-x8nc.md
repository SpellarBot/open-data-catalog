# Housing Litigations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/housing-litigations-af722) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/59kj-x8nc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/59kj-x8nc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/59kj-x8nc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 59kj-x8nc |
| Name | Housing Litigations |
| Attribution | Department of Housing Preservation and Development (HPD) |
| Category | Housing & Development |
| Tags | litigations, department of housing preservation and development, hpd |
| Created | 2013-11-18T19:00:32Z |
| Publication Date | 2017-04-02T20:05:19Z |

## Description

The Department of Housing Preservation and Development (HPD) Housing Litigation Division (HLD) initiates' actions in the Housing Court against owners of privately-owned buildings to enforce compliance with the housing quality standards contained in the New York State Multiple Dwelling Law and the New York City Housing Maintenance Code.  HLD attorneys also represent HPD when tenants initiate actions against private owners.  HPD is automatically named as party to such actions.  The goal of these court proceedings is to obtain enforceable Orders to Correct, Civil Penalties (fines) and Contempt Sanctions, compelling owners to comply with the Housing Code.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type     | Render Type   |
| ======== | =========== | ============= | ============= | ============= | ============= |
| Yes      | series tag  | litigationid  | LitigationID  | text          | number        |
| Yes      | series tag  | buildingid    | BuildingID    | text          | number        |
| Yes      | series tag  | boroid        | BoroID        | text          | number        |
| Yes      | series tag  | boro          | Boro          | text          | text          |
| Yes      | series tag  | housenumber   | HouseNumber   | text          | text          |
| Yes      | series tag  | streetname    | StreetName    | text          | text          |
| Yes      | series tag  | zip           | Zip           | text          | text          |
| Yes      | series tag  | block         | Block         | text          | number        |
| Yes      | series tag  | lot           | Lot           | text          | number        |
| Yes      | series tag  | casetype      | CaseType      | text          | text          |
| Yes      | time        | caseopendate  | CaseOpenDate  | calendar_date | calendar_date |
| Yes      | series tag  | casestatus    | CaseStatus    | text          | text          |
| Yes      | series tag  | casejudgement | CaseJudgement | text          | text          |
```

## Time Field

```ls
Value = caseopendate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:59kj-x8nc d:2009-04-07T00:00:00.000Z t:zip=11212 t:buildingid=354061 t:boro=BROOKLYN t:boroid=3 t:casestatus=CLOSED t:lot=232 t:block=3709 t:casetype="Heat and Hot Water" t:housenumber=1821 t:litigationid=96279 t:streetname="PITKIN AVENUE" t:casejudgement=NO m:row_number.59kj-x8nc=1

series e:59kj-x8nc d:2009-04-09T00:00:00.000Z t:zip=10460 t:buildingid=107564 t:boro=BRONX t:boroid=2 t:casestatus=CLOSED t:lot=15 t:block=3917 t:casetype="Heat and Hot Water" t:housenumber=1532 t:litigationid=96283 t:streetname="ROSEDALE AVENUE" t:casejudgement=NO m:row_number.59kj-x8nc=2

series e:59kj-x8nc d:2009-04-08T00:00:00.000Z t:zip=11102 t:buildingid=403253 t:boro=QUEENS t:boroid=4 t:casestatus=CLOSED t:lot=27 t:block=535 t:casetype="Heat and Hot Water" t:housenumber=30-41 t:litigationid=96290 t:streetname="14 STREET" t:casejudgement=NO m:row_number.59kj-x8nc=3
```

## Meta Commands

```ls
metric m:row_number.59kj-x8nc p:long l:"Row Number"

entity e:59kj-x8nc l:"Housing Litigations" t:attribution="Department of Housing Preservation and Development (HPD)" t:url=https://data.cityofnewyork.us/api/views/59kj-x8nc

property e:59kj-x8nc t:meta.view v:id=59kj-x8nc v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/hpd/html/pr/HPD-Open-Data.shtml v:averageRating=0 v:name="Housing Litigations" v:attribution="Department of Housing Preservation and Development (HPD)"

property e:59kj-x8nc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:59kj-x8nc t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| litigationid | buildingid | boroid | boro      | housenumber | streetname        | zip   | block | lot | casetype                  | caseopendate        | casestatus | casejudgement | 
| ============ | ========== | ====== | ========= | =========== | ================= | ===== | ===== | === | ========================= | =================== | ========== | ============= | 
| 96279        | 354061     | 3      | BROOKLYN  | 1821        | PITKIN AVENUE     | 11212 | 3709  | 232 | Heat and Hot Water        | 2009-04-07T00:00:00 | CLOSED     | NO            | 
| 96283        | 107564     | 2      | BRONX     | 1532        | ROSEDALE AVENUE   | 10460 | 3917  | 15  | Heat and Hot Water        | 2009-04-09T00:00:00 | CLOSED     | NO            | 
| 96290        | 403253     | 4      | QUEENS    | 30-41       | 14 STREET         | 11102 | 535   | 27  | Heat and Hot Water        | 2009-04-08T00:00:00 | CLOSED     | NO            | 
| 96297        | 10021      | 1      | MANHATTAN | 488         | CONVENT AVENUE    | 10031 | 2066  | 46  | Access Warrant - Non-Lead | 2009-04-14T00:00:00 | CLOSED     | NO            | 
| 96299        | 639447     | 4      | QUEENS    | 42-60       | BOWNE STREET      | 11355 | 5186  | 46  | Access Warrant - Non-Lead | 2009-04-15T00:00:00 | CLOSED     | NO            | 
| 96301        | 806324     | 2      | BRONX     | 946         | BRONX PARK SOUTH  | 10460 | 3129  | 21  | Tenant Action             | 2009-03-11T00:00:00 | CLOSED     | NO            | 
| 96303        | 34556      | 1      | MANHATTAN | 20          | WEST 68 STREET    | 10023 | 1120  | 41  | Tenant Action             | 2009-03-16T00:00:00 | CLOSED     | NO            | 
| 96305        | 20185      | 1      | MANHATTAN | 347         | EAST 119 STREET   | 10035 | 1796  | 22  | Tenant Action             | 2009-03-16T00:00:00 | CLOSED     | NO            | 
| 96308        | 9894       | 1      | MANHATTAN | 106         | CONVENT AVENUE    | 10027 | 1970  | 58  | Tenant Action             | 2009-03-23T00:00:00 | CLOSED     | NO            | 
| 9631         | 321564     | 3      | BROOKLYN  | 205         | KOSCIUSZKO STREET | 11216 | 1780  | 60  | Heat and Hot Water        | 2005-03-15T00:00:00 | CLOSED     | YES           | 
```