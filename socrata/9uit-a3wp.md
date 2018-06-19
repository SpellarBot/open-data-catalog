# Los Angeles International Airport - Ground Vehicle Traffic Volume

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/los-angeles-international-airport-ground-vehicle-traffic-volume-cb231) |
| Metadata | [Link](https://data.lacity.org/api/views/9uit-a3wp) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/9uit-a3wp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/9uit-a3wp/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 9uit-a3wp |
| Name | Los Angeles International Airport - Ground Vehicle Traffic Volume |
| Category | A Prosperous City |
| Tags | lax, vehicle, traffic, loop, entry, exit |
| Created | 2014-05-29T15:43:27Z |
| Publication Date | 2014-05-29T17:15:29Z |

## Description

Ground Vehicle Statistic that entered and exited LAX's Central Terminal Area

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | time           | reportingmonth | ReportingMonth | calendar_date | calendar_date |
| Yes      | series tag     | entryexit      | EntryExit      | text          | text          |
| Yes      | series tag     | upperlower     | UpperLower     | text          | text          |
| Yes      | numeric metric | total_vehicles | TOTAL VEHICLES | number        | number        |
```

## Time Field

```ls
Value = reportingmonth
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:9uit-a3wp d:2014-06-01T00:00:00.000Z t:upperlower="Lower Level" t:entryexit=Entry m:total_vehicles=1141079

series e:9uit-a3wp d:2014-06-01T00:00:00.000Z t:upperlower="Upper Level" t:entryexit=Exit m:total_vehicles=760392

series e:9uit-a3wp d:2014-06-01T00:00:00.000Z t:upperlower="Lower Level" t:entryexit=Exit m:total_vehicles=1812975
```

## Meta Commands

```ls
metric m:total_vehicles p:integer l:"TOTAL VEHICLES" t:dataTypeName=number

entity e:9uit-a3wp l:"Los Angeles International Airport - Ground Vehicle Traffic Volume" t:url=https://data.lacity.org/api/views/9uit-a3wp

property e:9uit-a3wp t:meta.view v:id=9uit-a3wp v:category="A Prosperous City" v:averageRating=0 v:name="Los Angeles International Airport - Ground Vehicle Traffic Volume"

property e:9uit-a3wp t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:9uit-a3wp t:meta.view.owner v:id=gudt-ccne v:profileImageUrlMedium=/api/users/gudt-ccne/profile_images/THUMB v:profileImageUrlLarge=/api/users/gudt-ccne/profile_images/LARGE v:screenName="LAWA OpenData" v:profileImageUrlSmall=/api/users/gudt-ccne/profile_images/TINY v:displayName="LAWA OpenData"

property e:9uit-a3wp t:meta.view.tableauthor v:id=gudt-ccne v:profileImageUrlMedium=/api/users/gudt-ccne/profile_images/THUMB v:profileImageUrlLarge=/api/users/gudt-ccne/profile_images/LARGE v:screenName="LAWA OpenData" v:profileImageUrlSmall=/api/users/gudt-ccne/profile_images/TINY v:roleName=publisher v:displayName="LAWA OpenData"
```

## Top Records

```ls
| reportingmonth      | entryexit | upperlower  | total_vehicles | 
| =================== | ========= | =========== | ============== | 
| 2014-06-01T00:00:00 | Entry     | Lower Level | 1141079        | 
| 2014-06-01T00:00:00 | Exit      | Upper Level | 760392         | 
| 2014-06-01T00:00:00 | Exit      | Lower Level | 1812975        | 
| 2014-06-01T00:00:00 | Entry     | Upper Level | 1319587        | 
| 2014-05-01T00:00:00 | Exit      | Upper Level | 731023         | 
| 2014-05-01T00:00:00 | Entry     | Lower Level | 1106597        | 
| 2014-05-01T00:00:00 | Exit      | Lower Level | 1817430        | 
| 2014-05-01T00:00:00 | Entry     | Upper Level | 1270282        | 
| 2014-04-01T00:00:00 | Entry     | Upper Level | 1181556        | 
| 2014-04-01T00:00:00 | Entry     | Lower Level | 1027606        | 
```