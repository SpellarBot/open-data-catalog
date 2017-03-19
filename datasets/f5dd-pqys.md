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
| Rows Updated | 2017-03-18T18:15:53Z |

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | objectid     | ObjectID     | text      | text        |
| Yes      | series tag     | kilonbr      | KiloNBR      | text      | text        |
| Yes      | series tag     | blockaddress | BlockAddress | text      | text        |
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

## Data Commands

```ls
series e:f5dd-pqys d:2016-12-08T12:38:00.000Z t:blockaddress="100 BLOCK H1W FWY" t:kilonbr=LHP161208000146 t:status=U t:cmid=Honolulu_PD_HI_LHP161208000146_210 t:cmagency="Honolulu PD, HI" t:type=DUI t:objectid=776009 m:score=0

series e:f5dd-pqys d:2016-12-08T16:48:00.000Z t:blockaddress="KULIHI&WELO ST" t:kilonbr=LHP161208000335 t:status=U t:cmid=Honolulu_PD_HI_LHP161208000335_141 t:cmagency="Honolulu PD, HI" t:type=VANDALISM t:objectid=776028 m:score=0

series e:f5dd-pqys d:2016-12-09T19:44:00.000Z t:blockaddress="911400 BLOCK MIULA ST" t:kilonbr=LHP161209000575 t:status=U t:cmid=Honolulu_PD_HI_LHP161209000575_060 t:cmagency="Honolulu PD, HI" t:type=THEFT/LARCENY t:objectid=776818 m:score=0
```

## Meta Commands

```ls
metric m:score p:integer l:Score t:dataTypeName=number

entity e:f5dd-pqys l:"HPD Crime Incidents" t:url=https://data.honolulu.gov/api/views/f5dd-pqys

property e:f5dd-pqys t:meta.view v:id=f5dd-pqys v:averageRating=0 v:name="HPD Crime Incidents"

property e:f5dd-pqys t:meta.view.owner v:id=sr3i-nqxd v:screenName="Open Data" v:roleName=administrator v:displayName="Open Data"

property e:f5dd-pqys t:meta.view.tableauthor v:id=sr3i-nqxd v:screenName="Open Data" v:roleName=administrator v:displayName="Open Data"
```