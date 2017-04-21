# Multiple Dwelling Registrations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/multiple-dwelling-registrations-c3aaa) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tesw-yqqr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tesw-yqqr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tesw-yqqr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tesw-yqqr |
| Name | Multiple Dwelling Registrations |
| Attribution | Department of Housing Preservation and Development (HPD) |
| Category | Housing & Development |
| Tags | registrations, department of housing preservation and development, hpd |
| Created | 2013-11-18T19:13:20Z |
| Publication Date | 2017-04-01T19:42:24Z |

## Description

Pursuant to New York City?s Housing Maintenance Code, the Department of Housing 
Preservation and Development (HPD) collects registration information from owners of 
residential rental units. Owners are required to register if they own residential buildings 
with three or more units or if they own one- or two-family homes and neither they nor 
members of their immediate family live there. Registrations are required upon taking 
ownership of a qualifying building, and once a year thereafter.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag     | registrationid       | RegistrationID       | text          | number        |
| Yes      | series tag     | buildingid           | BuildingID           | text          | number        |
| Yes      | series tag     | boroid               | BoroID               | text          | number        |
| Yes      | series tag     | boro                 | Boro                 | text          | text          |
| Yes      | series tag     | housenumber          | HouseNumber          | text          | text          |
| Yes      | series tag     | lowhousenumber       | LowHouseNumber       | text          | text          |
| Yes      | series tag     | highhousenumber      | HighHouseNumber      | text          | text          |
| Yes      | series tag     | streetname           | StreetName           | text          | text          |
| Yes      | series tag     | streetcode           | StreetCode           | text          | number        |
| Yes      | series tag     | zip                  | Zip                  | text          | text          |
| Yes      | series tag     | block                | Block                | text          | number        |
| Yes      | series tag     | lot                  | Lot                  | text          | number        |
| Yes      | numeric metric | bin                  | BIN                  | number        | number        |
| Yes      | numeric metric | communityboard       | CommunityBoard       | number        | number        |
| No       |                | lastregistrationdate | LastRegistrationDate | calendar_date | calendar_date |
| Yes      | time           | registrationenddate  | RegistrationEndDate  | calendar_date | calendar_date |
```

## Time Field

```ls
Value = registrationenddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = lastregistrationdate
```

## Data Commands

```ls
series e:tesw-yqqr d:2014-09-01T00:00:00.000Z t:zip=11426 t:buildingid=668537 t:boro=QUEENS t:boroid=4 t:streetcode=51090 t:lowhousenumber=248-49 t:lot=52 t:block=8664 t:housenumber=248-49 t:registrationid=913497 t:highhousenumber=248-49 t:streetname="JAMAICA AVENUE" m:communityboard=13 m:bin=4177061

series e:tesw-yqqr d:2017-09-01T00:00:00.000Z t:zip=11357 t:buildingid=813707 t:boro=QUEENS t:boroid=4 t:streetcode=6180 t:lowhousenumber=163-84 t:lot=139 t:block=5740 t:housenumber=163-84 t:registrationid=912547 t:highhousenumber=163-84 t:streetname="17 AVENUE" m:communityboard=7 m:bin=4540524

series e:tesw-yqqr d:2017-09-01T00:00:00.000Z t:zip=11207 t:buildingid=944239 t:boro=BROOKLYN t:boroid=3 t:streetcode=23930 t:lowhousenumber=1469 t:lot=6 t:block=3457 t:housenumber=1469 t:registrationid=384946 t:highhousenumber=1469 t:streetname="BUSHWICK AVENUE" m:communityboard=4 m:bin=3000000
```

## Meta Commands

```ls
metric m:bin p:integer l:BIN d:"DCP Building Identification Number for building" t:dataTypeName=number

metric m:communityboard p:integer l:CommunityBoard d:"Community Board for building" t:dataTypeName=number

entity e:tesw-yqqr l:"Multiple Dwelling Registrations" t:attribution="Department of Housing Preservation and Development (HPD)" t:url=https://data.cityofnewyork.us/api/views/tesw-yqqr

property e:tesw-yqqr t:meta.view v:id=tesw-yqqr v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/hpd/html/pr/HPD-Open-Data.shtml v:averageRating=0 v:name="Multiple Dwelling Registrations" v:attribution="Department of Housing Preservation and Development (HPD)"

property e:tesw-yqqr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tesw-yqqr t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| registrationid | buildingid | boroid | boro      | housenumber | lowhousenumber | highhousenumber | streetname             | streetcode | zip   | block | lot | bin     | communityboard | lastregistrationdate | registrationenddate | 
| ============== | ========== | ====== | ========= | =========== | ============== | =============== | ====================== | ========== | ===== | ===== | === | ======= | ============== | ==================== | =================== | 
| 913497         | 668537     | 4      | QUEENS    | 248-49      | 248-49         | 248-49          | JAMAICA AVENUE         | 51090      | 11426 | 8664  | 52  | 4177061 | 13             | 2014-01-29T00:00:00  | 2014-09-01T00:00:00 | 
| 912547         | 813707     | 4      | QUEENS    | 163-84      | 163-84         | 163-84          | 17 AVENUE              | 6180       | 11357 | 5740  | 139 | 4540524 | 7              | 2016-06-03T00:00:00  | 2017-09-01T00:00:00 | 
| 384946         | 944239     | 3      | BROOKLYN  | 1469        | 1469           | 1469            | BUSHWICK AVENUE        | 23930      | 11207 | 3457  | 6   | 3000000 | 4              | 2016-08-23T00:00:00  | 2017-09-01T00:00:00 | 
| 107647         | 42758      | 1      | MANHATTAN | 551         | 551            | 551             | WEST 157 STREET        | 36910      | 10032 | 2116  | 61  | 1062745 | 12             | 2016-09-23T00:00:00  | 2017-09-01T00:00:00 | 
| 113262         | 11367      | 1      | MANHATTAN | 424         | 424            | 424             | EAST 9 STREET          | 17170      | 10009 | 436   | 20  | 1005873 | 3              | 2016-09-14T00:00:00  | 2017-09-01T00:00:00 | 
| 914684         | 914808     | 4      | QUEENS    | 65-59       | 65-59          | 65-59           | ALDERTON STREET        | 27690      | 11374 | 3151  | 80  | 4074524 | 6              | 2016-07-26T00:00:00  | 2017-09-01T00:00:00 | 
| 116620         | 10488      | 1      | MANHATTAN | 243         | 243            | 243             | EAST 2 STREET          | 17030      | 10009 | 384   | 26  | 1004583 | 3              | 2016-10-11T00:00:00  | 2017-09-01T00:00:00 | 
| 223784         | 824384     | 2      | BRONX     | 1520        | 1520           | 1520            | BRUCKNER BOULEVARD     | 15920      | 10473 | 3651  | 39  | 2114120 | 9              | 2016-08-25T00:00:00  | 2017-09-01T00:00:00 | 
| 308646         | 133283     | 3      | BROOKLYN  | 4707        | 4707           | 4707            | 7 AVENUE               | 5780       | 11220 | 768   | 7   | 3012401 | 7              | 2011-10-06T00:00:00  | 2012-10-01T00:00:00 | 
| 375858         | 370197     | 3      | BROOKLYN  | 1730        | 1730           | 1730            | SHORE PARKWAY SR SOUTH | 77030      | 11214 | 6491  | 180 | 3170081 | 11             | 2016-07-28T00:00:00  | 2017-09-01T00:00:00 | 
```