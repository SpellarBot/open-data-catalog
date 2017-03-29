# HPD Crime Incidents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hpd-crime-incidents) |
| Metadata | [Link](https://data.honolulu.gov/api/views/f5dd-pqys) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/f5dd-pqys/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/f5dd-pqys/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | f5dd-pqys |
| Name | HPD Crime Incidents |
| Created | 2014-12-13T00:26:29Z |
| Publication Date | 2015-03-12T00:11:07Z |

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
series e:f5dd-pqys d:2016-12-08T12:38:00.000Z t:kilonbr=LHP161208000146 t:status=U t:cmid=Honolulu_PD_HI_LHP161208000146_210 t:cmagency="Honolulu PD, HI" t:type=DUI t:objectid=776009 m:score=0

series e:f5dd-pqys d:2016-12-08T16:48:00.000Z t:kilonbr=LHP161208000335 t:status=U t:cmid=Honolulu_PD_HI_LHP161208000335_141 t:cmagency="Honolulu PD, HI" t:type=VANDALISM t:objectid=776028 m:score=0

series e:f5dd-pqys d:2016-12-09T19:44:00.000Z t:kilonbr=LHP161209000575 t:status=U t:cmid=Honolulu_PD_HI_LHP161209000575_060 t:cmagency="Honolulu PD, HI" t:type=THEFT/LARCENY t:objectid=776818 m:score=0
```

## Meta Commands

```ls
metric m:score p:integer l:Score t:dataTypeName=number

entity e:f5dd-pqys l:"HPD Crime Incidents" t:url=https://data.honolulu.gov/api/views/f5dd-pqys

property e:f5dd-pqys t:meta.view v:id=f5dd-pqys v:averageRating=0 v:name="HPD Crime Incidents"

property e:f5dd-pqys t:meta.view.owner v:id=sr3i-nqxd v:screenName="Open Data" v:displayName="Open Data"

property e:f5dd-pqys t:meta.view.tableauthor v:id=sr3i-nqxd v:screenName="Open Data" v:roleName=administrator v:displayName="Open Data"
```

## Top Records

```ls
| objectid | kilonbr         | blockaddress             | cmid                               | cmagency        | date       | type                   | status | score | side | 
| ======== | =============== | ======================== | ================================== | =============== | ========== | ====================== | ====== | ===== | ==== | 
| 776009   | LHP161208000146 | 100 BLOCK H1W FWY        | Honolulu_PD_HI_LHP161208000146_210 | Honolulu PD, HI | 1481200680 | DUI                    | U      | 0     |      | 
| 776028   | LHP161208000335 | KULIHI&WELO ST           | Honolulu_PD_HI_LHP161208000335_141 | Honolulu PD, HI | 1481215680 | VANDALISM              | U      | 0     |      | 
| 776818   | LHP161209000575 | 911400 BLOCK MIULA ST    | Honolulu_PD_HI_LHP161209000575_060 | Honolulu PD, HI | 1481312640 | THEFT/LARCENY          | U      | 0     |      | 
| 776841   | LHP161209000871 | 951000 BLOCK MELEKOMO ST | Honolulu_PD_HI_LHP161209000871_060 | Honolulu PD, HI | 1481324220 | THEFT/LARCENY          | U      | 0     |      | 
| 776858   | LHP161209001158 | 1200 BLOCK LUAKALAI ST   | Honolulu_PD_HI_LHP161209001158_064 | Honolulu PD, HI | 1481333580 | VEHICLE BREAK-IN/THEFT | U      | 0     |      | 
| 776895   | LHP161209001549 | 3000 BLOCK LYMAN RD      | Honolulu_PD_HI_LHP161209001549_060 | Honolulu PD, HI | 1481346840 | THEFT/LARCENY          | U      | 0     |      | 
| 776904   | LHP161209001778 | H1E FWY&KUALAKAI PKWY    | Honolulu_PD_HI_LHP161209001778_210 | Honolulu PD, HI | 1481355960 | DUI                    | U      | 0     |      | 
| 776919   | LHP161209001921 | 0 BLOCK H1E FWY          | Honolulu_PD_HI_LHP161209001921_210 | Honolulu PD, HI | 1481361420 | DUI                    | U      | 0     |      | 
| 777574   | LHP161210000058 | 0 BLOCK H1W FWY          | Honolulu_PD_HI_LHP161210000058_210 | Honolulu PD, HI | 1481366640 | DUI                    | U      | 0     |      | 
| 777575   | LHP161210000086 | ALA WAI & MCCULLY        | Honolulu_PD_HI_LHP161210000086_210 | Honolulu PD, HI | 1481368020 | DUI                    | U      | 0     |      | 
```