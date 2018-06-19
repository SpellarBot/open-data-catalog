# Los Angeles International Airport (LAX) - Object Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/los-angeles-international-airport-lax-object-locations) |
| Metadata | [Link](https://data.lacity.org/api/views/r8xf-vixa) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/r8xf-vixa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/r8xf-vixa/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | r8xf-vixa |
| Name | Los Angeles International Airport (LAX) - Object Locations |
| Category | A Safe City |
| Tags | lax defibrillators airport emergency |
| Created | 2016-12-01T22:23:08Z |
| Publication Date | 2016-12-01T22:54:23Z |

## Description

GIS locations of items located at LAWA Campus'. Currently populated with defibrillator (Monthly) Data is push daily, but not all datasets are updated daily http://www.lawa.org

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | dataset            | DataSet            | text      | text        |
| No       |                | id                 | ID                 | text      | text        |
| Yes      | series tag     | locationname       | LocationName       | text      | text        |
| Yes      | series tag     | terminal           | Terminal           | text      | text        |
| Yes      | numeric metric | terminallevel      | TerminalLevel      | number    | text        |
| Yes      | series tag     | locationtype       | LocationType       | text      | text        |
| Yes      | series tag     | campus             | Campus             | text      | text        |
| Yes      | series tag     | dataexportdatetime | DataExportDateTime | text      | text        |
| No       |                | lat                | Lat                | number    | text        |
| No       |                | long               | Long               | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id,lat,long
```

## Data Commands

```ls
series e:r8xf-vixa d:2017-04-21T07:00:15.000Z t:dataexportdatetime=2017-04-21T00:00:13.390 t:terminal=3 t:dataset=Defibrillator t:locationtype=Defibrillator t:locationname=Defibrillator t:campus=LAX m:terminallevel=1

series e:r8xf-vixa d:2017-04-21T07:00:15.000Z t:dataexportdatetime=2017-04-21T00:00:13.390 t:terminal=3 t:dataset=Defibrillator t:locationtype=Defibrillator t:locationname=Defibrillator t:campus=LAX m:terminallevel=1

series e:r8xf-vixa d:2017-04-21T07:00:15.000Z t:dataexportdatetime=2017-04-21T00:00:13.390 t:terminal=3 t:dataset=Defibrillator t:locationtype=Defibrillator t:locationname=Defibrillator t:campus=LAX m:terminallevel=1
```

## Meta Commands

```ls
metric m:terminallevel p:integer l:TerminalLevel t:dataTypeName=number

entity e:r8xf-vixa l:"Los Angeles International Airport (LAX) - Object Locations" t:url=https://data.lacity.org/api/views/r8xf-vixa

property e:r8xf-vixa t:meta.view v:id=r8xf-vixa v:category="A Safe City" v:averageRating=0 v:name="Los Angeles International Airport (LAX) - Object Locations"

property e:r8xf-vixa t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:r8xf-vixa t:meta.view.owner v:id=gudt-ccne v:profileImageUrlMedium=/api/users/gudt-ccne/profile_images/THUMB v:profileImageUrlLarge=/api/users/gudt-ccne/profile_images/LARGE v:screenName="LAWA OpenData" v:profileImageUrlSmall=/api/users/gudt-ccne/profile_images/TINY v:displayName="LAWA OpenData"

property e:r8xf-vixa t:meta.view.tableauthor v:id=gudt-ccne v:profileImageUrlMedium=/api/users/gudt-ccne/profile_images/THUMB v:profileImageUrlLarge=/api/users/gudt-ccne/profile_images/LARGE v:screenName="LAWA OpenData" v:profileImageUrlSmall=/api/users/gudt-ccne/profile_images/TINY v:roleName=publisher v:displayName="LAWA OpenData"
```

## Top Records

```ls
| :updated_at | dataset       | id         | locationname  | terminal | terminallevel | locationtype  | campus | dataexportdatetime      | lat                | long                | 
| =========== | ============= | ========== | ============= | ======== | ============= | ============= | ====== | ======================= | ================== | =================== | 
| 1492758015  | Defibrillator | Defib44598 | Defibrillator | 3        | 1             | Defibrillator | LAX    | 2017-04-21T00:00:13.390 | 33.945028430000001 | -118.40732401       | 
| 1492758015  | Defibrillator | Defib44597 | Defibrillator | 3        | 1             | Defibrillator | LAX    | 2017-04-21T00:00:13.390 | 33.945119089999999 | -118.40663238       | 
| 1492758015  | Defibrillator | Defib44599 | Defibrillator | 3        | 1             | Defibrillator | LAX    | 2017-04-21T00:00:13.390 | 33.946315990000002 | -118.40738589       | 
| 1492758015  | Defibrillator | Defib44600 | Defibrillator | 3        | 2             | Defibrillator | LAX    | 2017-04-21T00:00:13.390 | 33.94502456        | -118.40707113000001 | 
| 1492758015  | Defibrillator | Defib44601 | Defibrillator | 3        | 3             | Defibrillator | LAX    | 2017-04-21T00:00:13.390 | 33.945520870000003 | -118.4072738        | 
| 1492758015  | Defibrillator | Defib44602 | Defibrillator | 3        | 3             | Defibrillator | LAX    | 2017-04-21T00:00:13.390 | 33.94657248        | -118.40722629       | 
| 1492758015  | Defibrillator | Defib44603 | Defibrillator | 3        | 3             | Defibrillator | LAX    | 2017-04-21T00:00:13.390 | 33.946537730000003 | -118.40754324       | 
| 1492758015  | Defibrillator | Defib44604 | Defibrillator | TBIT     | 3             | Defibrillator | LAX    | 2017-04-21T00:00:13.390 | 33.939943470000003 | -118.41003653       | 
| 1492758015  | Defibrillator | Defib44605 | Defibrillator | TBIT     | 3             | Defibrillator | LAX    | 2017-04-21T00:00:13.390 | 33.940827730000002 | -118.41015078       | 
| 1492758015  | Defibrillator | Defib44606 | Defibrillator | TBIT     | 3             | Defibrillator | LAX    | 2017-04-21T00:00:13.390 | 33.94220979        | -118.41038786       | 
```