# Housing Maintenance Code Complaints

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/housing-maintenance-code-complaints-2b7a3) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/uwyv-629c) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/uwyv-629c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/uwyv-629c/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | uwyv-629c |
| Name | Housing Maintenance Code Complaints |
| Attribution | Department of Housing Preservation and Development (HPD) |
| Category | Housing & Development |
| Tags | complaints, department of housing preservation and development, hpd |
| Created | 2013-11-19T16:33:41Z |
| Publication Date | 2015-04-02T16:07:28Z |

## Description

The Department of Housing Preservation and Development (HPD) records complaints that are made by the public through the 311 Citizen Services Center, Code Enforcement Borough Offices or the internet for conditions which violate the New York City Housing Maintenance Code (HMC) or the New York State Multiple Dwelling Law (MDL). Each complaint is associated with one or more problems reported by the complainant. Problems are closed if a tenant verifies by phone that the condition was corrected or an inspection result is entered by an HPD inspector. A complaint is closed when all associated problems are closed.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | complaintid    | ComplaintID    | text          | number        |
| Yes      | series tag     | buildingid     | BuildingID     | text          | number        |
| Yes      | series tag     | boroughid      | BoroughID      | text          | number        |
| Yes      | series tag     | borough        | Borough        | text          | text          |
| Yes      | series tag     | housenumber    | HouseNumber    | text          | text          |
| Yes      | series tag     | streetname     | StreetName     | text          | text          |
| Yes      | series tag     | zip            | Zip            | text          | text          |
| Yes      | series tag     | block          | Block          | text          | number        |
| Yes      | series tag     | lot            | Lot            | text          | number        |
| Yes      | series tag     | apartment      | Apartment      | text          | text          |
| Yes      | numeric metric | communityboard | CommunityBoard | number        | number        |
| Yes      | time           | receiveddate   | ReceivedDate   | calendar_date | calendar_date |
| Yes      | series tag     | statusid       | StatusID       | text          | number        |
| Yes      | series tag     | status         | Status         | text          | text          |
| No       |                | statusdate     | StatusDate     | calendar_date | calendar_date |
```

## Time Field

```ls
Value = receiveddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = statusdate
```

## Data Commands

```ls
series e:uwyv-629c d:2014-07-07T00:00:00.000Z t:zip=10026 t:buildingid=3418 t:complaintid=6960137 t:status=CLOSE t:boroughid=1 t:lot=4 t:block=1904 t:apartment=12D t:statusid=2 t:borough=MANHATTAN t:housenumber=1989 t:streetname="ADAM C POWELL BOULEVARD" m:communityboard=10

series e:uwyv-629c d:2014-07-08T00:00:00.000Z t:zip=10030 t:buildingid=3512 t:complaintid=6960832 t:status=CLOSE t:boroughid=1 t:lot=4 t:block=1918 t:apartment=3B t:statusid=2 t:borough=MANHATTAN t:housenumber=2267 t:streetname="ADAM C POWELL BOULEVARD" m:communityboard=10

series e:uwyv-629c d:2014-06-19T00:00:00.000Z t:zip=10019 t:buildingid=5318 t:complaintid=6946867 t:status=CLOSE t:boroughid=1 t:lot=1 t:block=1083 t:apartment=4P t:statusid=2 t:borough=MANHATTAN t:housenumber=778 t:streetname="11 AVENUE" m:communityboard=4
```

## Meta Commands

```ls
metric m:communityboard p:integer l:CommunityBoard d:"Unique number identifying a Community District/Board, which is a political geographical area within a borough of the City of NY" t:dataTypeName=number

entity e:uwyv-629c l:"Housing Maintenance Code Complaints" t:attribution="Department of Housing Preservation and Development (HPD)" t:url=https://data.cityofnewyork.us/api/views/uwyv-629c

property e:uwyv-629c t:meta.view v:id=uwyv-629c v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/hpd/html/pr/HPD-Open-Data.shtml v:averageRating=0 v:name="Housing Maintenance Code Complaints" v:attribution="Department of Housing Preservation and Development (HPD)"

property e:uwyv-629c t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:uwyv-629c t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| complaintid | buildingid | boroughid | borough   | housenumber | streetname              | zip   | block | lot | apartment | communityboard | receiveddate        | statusid | status | statusdate          | 
| =========== | ========== | ========= | ========= | =========== | ======================= | ===== | ===== | === | ========= | ============== | =================== | ======== | ====== | =================== | 
| 6960137     | 3418       | 1         | MANHATTAN | 1989        | ADAM C POWELL BOULEVARD | 10026 | 1904  | 4   | 12D       | 10             | 2014-07-07T00:00:00 | 2        | CLOSE  | 2014-07-29T00:00:00 | 
| 6960832     | 3512       | 1         | MANHATTAN | 2267        | ADAM C POWELL BOULEVARD | 10030 | 1918  | 4   | 3B        | 10             | 2014-07-08T00:00:00 | 2        | CLOSE  | 2014-07-12T00:00:00 | 
| 6946867     | 5318       | 1         | MANHATTAN | 778         | 11 AVENUE               | 10019 | 1083  | 1   | 4P        | 4              | 2014-06-19T00:00:00 | 2        | CLOSE  | 2014-07-13T00:00:00 | 
| 6966946     | 5608       | 1         | MANHATTAN | 1640        | AMSTERDAM AVENUE        | 10031 | 2073  | 29  | 5A        | 9              | 2014-07-16T00:00:00 | 2        | CLOSE  | 2014-07-21T00:00:00 | 
| 6956574     | 17896      | 1         | MANHATTAN | 230         | EAST 88 STREET          | 10128 | 1533  | 32  | 1E        | 8              | 2014-07-01T00:00:00 | 2        | CLOSE  | 2014-07-09T00:00:00 | 
| 6959035     | 19899      | 1         | MANHATTAN | 428         | EAST 117 STREET         | 10035 | 1710  | 36  | 3D        | 11             | 2014-07-04T00:00:00 | 2        | CLOSE  | 2014-07-10T00:00:00 | 
| 6924412     | 25304      | 1         | MANHATTAN | 498         | MANHATTAN AVENUE        | 10027 | 1947  | 47  | 4         | 10             | 2014-05-21T00:00:00 | 2        | CLOSE  | 2014-07-04T00:00:00 | 
| 6944891     | 32017      | 1         | MANHATTAN | 351         | WEST 29 STREET          | 10001 | 753   | 10  | 25        | 4              | 2014-06-17T00:00:00 | 2        | CLOSE  | 2014-07-22T00:00:00 | 
| 6961276     | 37344      | 1         | MANHATTAN | 209         | WEST 101 STREET         | 10025 | 1873  | 24  | PH        | 7              | 2014-07-08T00:00:00 | 2        | CLOSE  | 2014-07-11T00:00:00 | 
| 6959795     | 41208      | 1         | MANHATTAN | 315         | WEST 138 STREET         | 10030 | 2041  | 40  | 6         | 10             | 2014-07-07T00:00:00 | 2        | CLOSE  | 2014-07-16T00:00:00 | 
```