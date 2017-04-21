# SDOT Public Garage or Parking Lot

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-garage-or-parking-lot-includes-e-park) |
| Metadata | [Link](https://data.seattle.gov/api/views/3neb-8edu) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/3neb-8edu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/3neb-8edu/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 3neb-8edu |
| Name | SDOT Public Garage or Parking Lot |
| Category | Transportation |
| Tags | parking, garages, lots, sdot, transportation, seattle, city of seattle, e-park |
| Created | 2012-04-27T19:14:38Z |
| Publication Date | 2012-04-27T19:30:34Z |

## Description

Displays the locations of off street garages and lots along with information such as rates, operator name, etc. Off street garages participating in the e-Park program also display the availability of parking spaces.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | objectid             | OBJECTID             | text      | number      |
| Yes      | series tag     | buslic_location_id   | BUSLIC_LOCATION_ID   | text      | number      |
| No       |                | dea_facility_address | DEA_FACILITY_ADDRESS | text      | text        |
| Yes      | numeric metric | dea_stalls           | DEA_STALLS           | number    | number      |
| Yes      | series tag     | fac_name             | FAC_NAME             | text      | text        |
| Yes      | series tag     | hrs_monfri           | HRS_MONFRI           | text      | text        |
| Yes      | series tag     | hrs_sat              | HRS_SAT              | text      | text        |
| Yes      | series tag     | hrs_sun              | HRS_SUN              | text      | text        |
| Yes      | series tag     | fac_type             | FAC_TYPE             | text      | text        |
| Yes      | series tag     | rte_1hr              | RTE_1HR              | text      | text        |
| Yes      | series tag     | rte_2hr              | RTE_2HR              | text      | text        |
| Yes      | series tag     | rte_3hr              | RTE_3HR              | text      | text        |
| Yes      | series tag     | rte_allday           | RTE_ALLDAY           | text      | text        |
| Yes      | numeric metric | disabled             | DISABLED             | number    | text        |
| Yes      | series tag     | op_name              | OP_NAME              | text      | text        |
| Yes      | series tag     | op_phone             | OP_PHONE             | text      | text        |
| Yes      | series tag     | op_phone2            | OP_PHONE2            | text      | text        |
| Yes      | series tag     | payment_type         | PAYMENT_TYPE         | text      | text        |
| Yes      | series tag     | other                | OTHER                | text      | text        |
| Yes      | series tag     | webname              | WEBNAME              | text      | text        |
| Yes      | series tag     | regionid             | REGIONID             | text      | number      |
| Yes      | series tag     | outofserv            | OUTOFSERV            | text      | text        |
| Yes      | numeric metric | vacant               | VACANT               | number    | number      |
| Yes      | series tag     | status               | STATUS               | text      | text        |
| Yes      | time           | datetime             | DATETIME             | date      | date        |
| Yes      | series tag     | signid               | SIGNID               | text      | text        |
```

## Time Field

```ls
Value = datetime
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = dea_facility_address
```

## Data Commands

```ls
series e:3neb-8edu d:2017-04-21T09:07:29.444Z t:hrs_sun="24 hours" t:other=N t:hrs_sat="24 hours" t:rte_2hr=18 t:regionid=0 t:webname=IMPARK t:fac_type="SURFACE LOT" t:buslic_location_id=605781 t:fac_name="Vance BOA - Lot #60" t:objectid=1 t:rte_allday=24 t:op_name=IMPARK t:hrs_monfri="24 hours" t:rte_1hr=9 m:dea_stalls=30 m:disabled=1

series e:3neb-8edu d:2017-04-21T09:07:29.444Z t:hrs_sun="24 hours" t:other=N t:hrs_sat="24 hours" t:rte_2hr=5 t:regionid=0 t:webname=IMPARK t:fac_type="SURFACE LOT" t:buslic_location_id=548440 t:fac_name="2120 5th Avenue - Lot #13" t:objectid=2 t:rte_allday=17 t:op_name=IMPARK t:hrs_monfri="24 hours" t:rte_1hr=5 m:dea_stalls=28

series e:3neb-8edu d:2017-04-21T09:07:29.444Z t:hrs_sun="24 hours" t:other=N t:rte_2hr=14 t:hrs_sat="24 hours" t:webname=IMPARK t:buslic_location_id=593012 t:rte_3hr=14 t:hrs_monfri="24 hours" t:rte_allday=32 t:regionid=0 t:fac_type=GARAGE t:fac_name="Plaza 600 - Lot #33" t:objectid=3 t:op_name=IMPARK t:rte_1hr=10 m:dea_stalls=100
```

## Meta Commands

```ls
metric m:dea_stalls p:integer l:DEA_STALLS d:DEA_STALLS t:dataTypeName=number

metric m:disabled p:integer l:DISABLED d:DISABLED t:dataTypeName=number

metric m:vacant p:integer l:VACANT d:VACANT t:dataTypeName=number

entity e:3neb-8edu l:"SDOT Public Garage or Parking Lot" t:url=https://data.seattle.gov/api/views/3neb-8edu

property e:3neb-8edu t:meta.view v:id=3neb-8edu v:category=Transportation v:attributionLink=http://www.seattle.gov/transportation/ v:averageRating=0 v:name="SDOT Public Garage or Parking Lot"

property e:3neb-8edu t:meta.view.license v:name="Public Domain"

property e:3neb-8edu t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:3neb-8edu t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | buslic_location_id | dea_facility_address               | dea_stalls | fac_name                               | hrs_monfri       | hrs_sat          | hrs_sun          | fac_type            | rte_1hr | rte_2hr | rte_3hr | rte_allday | disabled | op_name                    | op_phone | op_phone2 | payment_type | other | webname                 | regionid | outofserv | vacant | status | datetime   | signid | 
| ======== | ================== | ================================== | ========== | ====================================== | ================ | ================ | ================ | =================== | ======= | ======= | ======= | ========== | ======== | ========================== | ======== | ========= | ============ | ===== | ======================= | ======== | ========= | ====== | ====== | ========== | ====== | 
| 1        | 605781             | 1801 6TH AV, SEATTLE, WA 98101     | 30         | Vance BOA - Lot #60                    | 24 hours         | 24 hours         | 24 hours         | SURFACE LOT         | 9       | 18      |         | 24         | 1        | IMPARK                     |          |           |              | N     | IMPARK                  | 0        |           |        |        |            |        | 
| 2        | 548440             | 2120 5TH AV, SEATTLE, WA 98121     | 28         | 2120 5th Avenue - Lot #13              | 24 hours         | 24 hours         | 24 hours         | SURFACE LOT         | 5       | 5       |         | 17         |          | IMPARK                     |          |           |              | N     | IMPARK                  | 0        |           |        |        |            |        | 
| 3        | 593012             | 600 STEWART ST, SEATTLE, WA 98101  | 100        | Plaza 600 - Lot #33                    | 24 hours         | 24 hours         | 24 hours         | GARAGE              | 10      | 14      | 14      | 32         |          | IMPARK                     |          |           |              | N     | IMPARK                  | 0        |           |        |        |            |        | 
| 4        | 655407             | 1109 WESTERN AV, SEATTLE, WA 98101 | 194        | Waterfront Place - Lot 103             |                  |                  |                  | GARAGE              | 6       |         |         |            |          | IMPARK                     |          |           |              | N     | WATERFRONT PLACE GARAGE | 22       | N         | 362    | 162    | 1492453007 | G19    | 
| 5        | 665930             | 1903 5TH AVE, SEATTLE, WA 98101    | 48         | 5th & Stewart Park LLC - Lot #106      |                  |                  |                  | GARAGE              | 11      |         |         |            |          | IMPARK                     |          |           |              | N     |                         |          |           |        |        |            |        | 
| 6        | 704189             | 515 MINOR AVE, SEATTLE, WA 98101   | 297        | First Hill Medical Building - Lot #132 |                  |                  |                  | GARAGE, SURFACE LOT | 7       | 9       |         |            |          | IMPARK                     |          |           |              | N     |                         |          |           |        |        |            |        | 
| 7        | 625374             | 1401 BROADWAY, SEATTLE, WA 98122   | 277        | Harvard Market Lot #72                 | 6:00am - 12:00am | 6:00am - 12:00am | 6:00am - 12:00am | GARAGE/SURFACE LOT  | 5       |         |         | 21         |          | IMPARK                     |          |           |              | N     | IMPARK                  | 0        |           |        |        |            |        | 
| 8        | 519369             | 314 BELL ST, SEATTLE, WA 98121     | 21         |                                        | 24 hours         | 24 hours         | 24 hours         | SURFACE LOT         | 6       | 6       | 9       | 14         |          | Republic Parking Northwest |          |           |              | N     | REPUBLIC                | 0        |           |        |        |            |        | 
| 9        | 519374             | 1935 2ND AV, SEATTLE, WA 98101     | 16         |                                        | 24 hours         | 24 hours         | 24 hours         | SURFACE LOT         | 9       | 9       | 12      | 33         | 1        | Republic Parking Northwest |          |           |              | N     | REPUBLIC                | 0        |           |        |        |            |        | 
| 10       | 605509             | 2225 ALASKAN WY, SEATTLE, WA 98121 | 29         |                                        | 6:00am - 4:30pm  | 6:00am - 4:30pm  | 6:00am - 4:30pm  | SURFACE LOT         | 2       | 4       | 6       | 12         |          | Republic Parking Northwest |          |           |              | N     | REPUBLIC - PIER 66      | 0        |           |        |        |            |        | 
```