# Crime Incidents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/crime-incidents-a7479) |
| Metadata | [Link](https://data.honolulu.gov/api/views/a96q-gyhq) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/a96q-gyhq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/a96q-gyhq/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | a96q-gyhq |
| Name | Crime Incidents |
| Category | Public Safety |
| Created | 2012-08-29T18:35:58Z |
| Publication Date | 2012-08-29T18:43:21Z |

## Description

A snapshot of Crime Incidents from the Honolulu Police Department

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | objectid     | ObjectID     | text      | text        |
| Yes      | series tag     | kilonbr      | KiloNBR      | text      | text        |
| No       |                | blockaddress | BlockAddress | text      | text        |
| Yes      | series tag     | cmid         | CMID         | text      | text        |
| Yes      | series tag     | cmagency     | CMAgency     | text      | text        |
| Yes      | time           | date         | Date         | date      | date        |
| Yes      | series tag     | type         | Type         | text      | text        |
| Yes      | series tag     | status       | Status       | text      | text        |
| Yes      | numeric metric | score        | Score        | number    | text        |
| Yes      | series tag     | side         | Side         | text      | text        |
```

## Time Field

```ls
Value = date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = blockaddress
```

## Data Commands

```ls
series e:a96q-gyhq d:2015-11-17T18:34:00.000Z t:kilonbr=LHP151117000412 t:status=U t:cmid=Honolulu_PD_HI_LHP151117000412_077 t:cmagency="Honolulu PD, HI" t:type="MOTOR VEHICLE THEFT" t:objectid=583660 m:score=0

series e:a96q-gyhq d:2015-11-18T03:40:00.000Z t:kilonbr=LHP151117001422 t:status=U t:cmid=Honolulu_PD_HI_LHP151117001422_064 t:cmagency="Honolulu PD, HI" t:type="VEHICLE BREAK-IN/THEFT" t:objectid=583719 m:score=0

series e:a96q-gyhq d:2015-11-18T11:21:00.000Z t:kilonbr=LHP151118000054 t:status=U t:cmid=Honolulu_PD_HI_LHP151118000054_077 t:cmagency="Honolulu PD, HI" t:type="MOTOR VEHICLE THEFT" t:objectid=584226 m:score=0
```

## Meta Commands

```ls
metric m:score p:integer l:Score t:dataTypeName=number

entity e:a96q-gyhq l:"Crime Incidents" t:url=https://data.honolulu.gov/api/views/a96q-gyhq

property e:a96q-gyhq t:meta.view v:id=a96q-gyhq v:category="Public Safety" v:averageRating=0 v:name="Crime Incidents"

property e:a96q-gyhq t:meta.view.owner v:id=gcjf-354x v:screenName="Mick Thompson" v:displayName="Mick Thompson"

property e:a96q-gyhq t:meta.view.tableauthor v:id=gcjf-354x v:screenName="Mick Thompson" v:displayName="Mick Thompson"
```

## Top Records

```ls
| objectid | kilonbr         | blockaddress               | cmid                               | cmagency        | date       | type                   | status | score | side | 
| ======== | =============== | ========================== | ================================== | =============== | ========== | ====================== | ====== | ===== | ==== | 
| 583660   | LHP151117000412 | H3W HALAWA VLY UP          | Honolulu_PD_HI_LHP151117000412_077 | Honolulu PD, HI | 1447785240 | MOTOR VEHICLE THEFT    | U      | 0     |      | 
| 583719   | LHP151117001422 | HOLOMOANA ST&KAHANAMOKU ST | Honolulu_PD_HI_LHP151117001422_064 | Honolulu PD, HI | 1447818000 | VEHICLE BREAK-IN/THEFT | U      | 0     |      | 
| 584226   | LHP151118000054 | 2600 BLOCK GORDON ST       | Honolulu_PD_HI_LHP151118000054_077 | Honolulu PD, HI | 1447845660 | MOTOR VEHICLE THEFT    | U      | 0     |      | 
| 584261   | LHP151118000541 | 0 BLOCK H2N FWY            | Honolulu_PD_HI_LHP151118000541_060 | Honolulu PD, HI | 1447875780 | THEFT/LARCENY          | U      | 0     |      | 
| 584273   | LHP151118000642 | 4400 BLOCK KAPOLEI PKWY    | Honolulu_PD_HI_LHP151118000642_060 | Honolulu PD, HI | 1447880220 | THEFT/LARCENY          | U      | 0     |      | 
| 584275   | LHP151118000662 | 911100 BLOCK KEAUNUI DR    | Honolulu_PD_HI_LHP151118000662_064 | Honolulu PD, HI | 1447881120 | VEHICLE BREAK-IN/THEFT | U      | 0     |      | 
| 584848   | LHP151119000387 | KUKULU ST&WAKEA ST         | Honolulu_PD_HI_LHP151119000387_060 | Honolulu PD, HI | 1447956360 | THEFT/LARCENY          | U      | 0     |      | 
| 584859   | LHP151119000431 | 100 BLOCK WHITE PLAINS ST  | Honolulu_PD_HI_LHP151119000431_064 | Honolulu PD, HI | 1447958100 | VEHICLE BREAK-IN/THEFT | U      | 0     |      | 
| 584881   | LHP151119000774 | 4400 BLOCK KAPOLEI PKWY    | Honolulu_PD_HI_LHP151119000774_064 | Honolulu PD, HI | 1447971060 | VEHICLE BREAK-IN/THEFT | U      | 0     |      | 
| 584896   | LHP151119000977 | 910300 BLOCK PELELEU PL    | Honolulu_PD_HI_LHP151119000977_060 | Honolulu PD, HI | 1447978920 | THEFT/LARCENY          | U      | 0     |      | 
```