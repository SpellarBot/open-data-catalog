# HPD Traffic Incidents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hpd-traffic-incidents) |
| Metadata | [Link](https://data.honolulu.gov/api/views/qg2s-mjkr) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/qg2s-mjkr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/qg2s-mjkr/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | qg2s-mjkr |
| Name | HPD Traffic Incidents |
| Created | 2014-09-15T21:59:37Z |
| Publication Date | 2015-03-12T00:11:12Z |

## Columns

```ls
| Included | Schema Type | Field Name | Name     | Data Type     | Render Type   |
| ======== | =========== | ========== | ======== | ============= | ============= |
| Yes      | time        | date       | Date     | calendar_date | calendar_date |
| Yes      | series tag  | code       | Code     | text          | text          |
| Yes      | series tag  | type       | Type     | text          | text          |
| No       |             | address    | Address  | text          | text          |
| Yes      | series tag  | location   | Location | text          | text          |
| Yes      | series tag  | area       | Area     | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:qg2s-mjkr d:2017-04-20T21:39:57.000Z t:area=KAIMUKI t:code=550 t:type="MOTOR VEHICLE COLLISION" m:row_number.qg2s-mjkr=1

series e:qg2s-mjkr d:2017-04-20T21:31:33.000Z t:area=DOWNTOWN t:code=550 t:type="MOTOR VEHICLE COLLISION" m:row_number.qg2s-mjkr=2

series e:qg2s-mjkr d:2017-04-20T21:22:48.000Z t:area=AIEA t:code=550 t:type="MOTOR VEHICLE COLLISION" m:row_number.qg2s-mjkr=3
```

## Meta Commands

```ls
metric m:row_number.qg2s-mjkr p:long l:"Row Number"

entity e:qg2s-mjkr l:"HPD Traffic Incidents" t:url=https://data.honolulu.gov/api/views/qg2s-mjkr

property e:qg2s-mjkr t:meta.view v:id=qg2s-mjkr v:averageRating=0 v:name="HPD Traffic Incidents"

property e:qg2s-mjkr t:meta.view.owner v:id=sr3i-nqxd v:screenName="Open Data" v:displayName="Open Data"

property e:qg2s-mjkr t:meta.view.tableauthor v:id=sr3i-nqxd v:screenName="Open Data" v:roleName=administrator v:displayName="Open Data"
```

## Top Records

```ls
| date                | code | type                                  | address                      | location            | area     | 
| =================== | ==== | ===================================== | ============================ | =================== | ======== | 
| 2017-04-20T21:39:57 | 550  | MOTOR VEHICLE COLLISION               | 11TH AVE&KILAUEA AVE         |                     | KAIMUKI  | 
| 2017-04-20T21:31:33 | 550  | MOTOR VEHICLE COLLISION               | PUNCHBOWL ST&S VINEYARD BLVD |                     | DOWNTOWN | 
| 2017-04-20T21:22:48 | 550  | MOTOR VEHICLE COLLISION               | KAAHELE ST&MOANALUA RD       |                     | AIEA     | 
| 2017-04-20T21:20:59 | 630  | TRAFFIC NUISANCE OR PARKING VIOLATION | 94050X KAM HWY               | BRIDGE KIPAPA D2 NB | MILILANI | 
| 2017-04-20T21:14:54 | 630  | TRAFFIC NUISANCE OR PARKING VIOLATION | FARRINGTON HWY&KAUKONAHUA RD |                     | WAIALUA  | 
| 2017-04-20T20:49:27 | 632  | HAZARDOUS DRIVER                      | FARRINGTON HWY&HAKIMO RD     |                     | NANAKULI | 
| 2017-04-20T20:47:37 | 630  | TRAFFIC NUISANCE OR PARKING VIOLATION | 162X N SCHOOL ST             | KAM SC              | KALIHI   | 
| 2017-04-20T20:36:04 | 634  | TRAFFIC SIGNAL PROBLEM                | KAM HWY&MAKALAPA RD          |                     | AIEA     | 
| 2017-04-20T20:35:19 | 633  | STALLED/HAZARDOUS VEHICLE             | 14X H1W FWY                  | H1W KANEOHE OFF     | AIEA     | 
| 2017-04-20T20:33:04 | 550  | MOTOR VEHICLE COLLISION               | GULICK AVE&N KING ST         |                     | KALIHI   | 
```