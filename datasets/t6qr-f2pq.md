# PWS SRC Master 051115

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pws-src-master-051115) |
| Metadata | [Link](https://data.wa.gov/api/views/t6qr-f2pq) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/t6qr-f2pq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/t6qr-f2pq/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | t6qr-f2pq |
| Name | PWS SRC Master 051115 |
| Attribution | Department of Health |
| Category | Natural Resources & Environment |
| Tags | drought, well depth, source capacity |
| Created | 2015-11-20T21:28:41Z |
| Publication Date | 2015-11-20T21:54:38Z |

## Description

PWS SRC Information for Drought Planning Maps

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| No       | time           | :updated_at                    | updated_at                     | meta_data | meta_data   |
| No       |                | f                              | F                              | text      | text        |
| Yes      | series tag     | ws_grp                         | WS Grp                         | text      | text        |
| Yes      | series tag     | ws_type                        | WS Type                        | text      | text        |
| Yes      | series tag     | ws_id                          | WS ID                          | text      | text        |
| Yes      | series tag     | ws_name                        | WS Name                        | text      | text        |
| Yes      | numeric metric | srcnum                         | SrcNum                         | number    | number      |
| Yes      | series tag     | srcname                        | SrcName                        | text      | text        |
| Yes      | series tag     | srctype                        | SrcType                        | text      | text        |
| Yes      | series tag     | srcuse                         | SrcUse                         | text      | text        |
| Yes      | series tag     | wria_num                       | WRIA Num                       | text      | number      |
| Yes      | numeric metric | welldepth                      | WellDepth                      | number    | number      |
| Yes      | numeric metric | src_capacity                   | Src_Capacity                   | number    | number      |
| Yes      | series tag     | susceptibility                 | Susceptibility                 | text      | text        |
| Yes      | series tag     | county                         | County                         | text      | text        |
| Yes      | series tag     | ownership                      | Ownership                      | text      | text        |
| Yes      | numeric metric | ft_respop                      | FT ResPop                      | number    | number      |
| Yes      | numeric metric | maxtotalpop                    | MaxTotalPop                    | number    | number      |
| Yes      | numeric metric | resconn                        | ResConn                        | number    | number      |
| Yes      | numeric metric | total_conn                     | Total Conn                     | number    | number      |
| Yes      | series tag     | qtr_qtr                        | Qtr/Qtr                        | text      | text        |
| Yes      | numeric metric | township                       | Township                       | number    | number      |
| Yes      | numeric metric | section                        | Section                        | number    | number      |
| Yes      | series tag     | range                          | Range                          | text      | text        |
| Yes      | series tag     | latlongmethod                  | LatLongMethod                  | text      | text        |
| No       |                | latlongdate                    | LatLongDate                    | text      | text        |
| Yes      | series tag     | src_eq_1_no_depth              | src eq 1 no depth              | text      | text        |
| Yes      | series tag     | src_eq_1_lt_50ft               | src eq 1 lt 50ft               | text      | text        |
| Yes      | series tag     | gs_drought_src_eq_1            | gs drought src eq 1            | text      | text        |
| Yes      | series tag     | gs_drought_pws_w_src_cap_lt_20 | gs drought pws w_src cap lt 20 | text      | text        |
| Yes      | series tag     | pws_w_src_cap_null             | pws w_src cap null             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = f,latlongdate
```

## Data Commands

```ls
series e:t6qr-f2pq d:2015-11-20T13:29:44.000Z t:ws_grp=B t:ws_name="TRIPLE R RENTALS" t:range=18E t:qtr_qtr=SWNW t:latlongmethod=GPS t:ws_type=GRPB t:ownership=Investor t:srcname="WELL #1" t:gs_drought_pws_w_src_cap_lt_20=x t:county=YAKIMA t:wria_num=37 t:susceptibility=N t:ws_id=00001 t:srctype="Ground Water - Well" t:gs_drought_src_eq_1=x t:src_eq_1_no_depth=x t:srcuse=Permanent m:total_conn=1 m:township=13 m:ft_respop=0 m:welldepth=0 m:src_capacity=8 m:maxtotalpop=13 m:srcnum=1 m:section=14 m:resconn=0

series e:t6qr-f2pq d:2015-11-20T13:29:44.000Z t:latlongmethod=GPS t:ws_name="AIRPORT RANCH WATER SYSTEM" t:ws_grp=B t:srcname="Well #1" t:ownership=Private t:ws_type=GRPB t:range=23E t:county=YAKIMA t:wria_num=37 t:susceptibility=H t:qtr_qtr=NWSE t:ws_id=00003 t:srctype="Ground Water - Well" t:gs_drought_src_eq_1=x t:srcuse=Permanent m:total_conn=2 m:township=10 m:ft_respop=0 m:welldepth=196 m:src_capacity=25 m:maxtotalpop=7 m:srcnum=1 m:section=22 m:resconn=0

series e:t6qr-f2pq d:2015-11-20T13:29:44.000Z t:latlongmethod=QtrQtrSe t:ws_name="ADCO WATERMASTER - QCBID" t:ws_grp=B t:srcname="WELL 1" t:ownership=Federal t:ws_type=GRPB t:range=28E t:county=GRANT t:wria_num=41 t:susceptibility=N t:qtr_qtr=NESE t:ws_id=00005 t:srctype="Ground Water - Well" t:gs_drought_src_eq_1=x t:srcuse=Permanent m:total_conn=6 m:township=22 m:ft_respop=8 m:welldepth=222 m:src_capacity=66 m:maxtotalpop=14 m:srcnum=1 m:section=7 m:resconn=3
```

## Meta Commands

```ls
metric m:srcnum p:integer l:SrcNum t:dataTypeName=number

metric m:welldepth p:integer l:WellDepth t:dataTypeName=number

metric m:src_capacity p:integer l:Src_Capacity t:dataTypeName=number

metric m:ft_respop p:integer l:"FT ResPop" t:dataTypeName=number

metric m:maxtotalpop p:integer l:MaxTotalPop t:dataTypeName=number

metric m:resconn p:integer l:ResConn t:dataTypeName=number

metric m:total_conn p:integer l:"Total Conn" t:dataTypeName=number

metric m:township p:integer l:Township t:dataTypeName=number

metric m:section p:integer l:Section t:dataTypeName=number

entity e:t6qr-f2pq l:"PWS SRC Master 051115" t:attribution="Department of Health" t:url=https://data.wa.gov/api/views/t6qr-f2pq

property e:t6qr-f2pq t:meta.view v:id=t6qr-f2pq v:category="Natural Resources & Environment" v:averageRating=0 v:name="PWS SRC Master 051115" v:attribution="Department of Health"

property e:t6qr-f2pq t:meta.view.owner v:id=x62c-cuxv v:screenName="Joshua Plaster" v:displayName="Joshua Plaster"

property e:t6qr-f2pq t:meta.view.tableauthor v:id=x62c-cuxv v:screenName="Joshua Plaster" v:roleName=editor v:displayName="Joshua Plaster"
```

## Top Records

```ls
| :updated_at | f         | ws_grp | ws_type | ws_id | ws_name                        | srcnum | srcname             | srctype             | srcuse    | wria_num | welldepth | src_capacity | susceptibility | county  | ownership   | ft_respop | maxtotalpop | resconn | total_conn | qtr_qtr | township | section | range | latlongmethod | latlongdate | src_eq_1_no_depth | src_eq_1_lt_50ft | gs_drought_src_eq_1 | gs_drought_pws_w_src_cap_lt_20 | pws_w_src_cap_null | 
| =========== | ========= | ====== | ======= | ===== | ============================== | ====== | =================== | =================== | ========= | ======== | ========= | ============ | ============== | ======= | =========== | ========= | =========== | ======= | ========== | ======= | ======== | ======= | ===== | ============= | =========== | ================= | ================ | =================== | ============================== | ================== | 
| 1448026184  | Eastern   | B      | GRPB    | 00001 | TRIPLE R RENTALS               | 1      | WELL #1             | Ground Water - Well | Permanent | 37       | 0         | 8            | N              | YAKIMA  | Investor    | 0         | 13          | 0       | 1          | SWNW    | 13       | 14      | 18E   | GPS           |             | x                 |                  | x                   | x                              |                    | 
| 1448026184  | Eastern   | B      | GRPB    | 00003 | AIRPORT RANCH WATER SYSTEM     | 1      | Well #1             | Ground Water - Well | Permanent | 37       | 196       | 25           | H              | YAKIMA  | Private     | 0         | 7           | 0       | 2          | NWSE    | 10       | 22      | 23E   | GPS           | 28-Jan-09   |                   |                  | x                   |                                |                    | 
| 1448026184  | Eastern   | B      | GRPB    | 00005 | ADCO WATERMASTER - QCBID       | 1      | WELL 1              | Ground Water - Well | Permanent | 41       | 222       | 66           | N              | GRANT   | Federal     | 8         | 14          | 3       | 6          | NESE    | 22       | 7       | 28E   | QtrQtrSe      |             |                   |                  | x                   |                                |                    | 
| 1448026184  | Eastern   | B      | GRPB    | 00006 | AUTO VIEW DRIVE-IN             | 1      | WELL 1              | Ground Water - Well | Permanent | 59       | 190       | 1            | U              | STEVENS | Investor    | 3         | 13          | 1       | 2          |         | 0        | 0       | 0     |               |             |                   |                  | x                   | x                              |                    | 
| 1448026184  | Eastern   | A      | TNC     | 00008 | ADAMS COUNTY FAIR              | 1      | Well #1 AFL235      | Ground Water - Well | Permanent | 36       | 340       | 200          | N              | ADAMS   | County      | 0         | 503         | 0       | 157        | SESE    | 15       | 10      | 29E   | GPS           |             |                   |                  | x                   |                                |                    | 
| 1448026184  | Eastern   | B      | GRPB    | 00011 | BEN ROY RAY ROAD WELL ASSN     | 1      | WELL #1             | Ground Water - Well | Permanent | 37       | 175       | 25           | U              | YAKIMA  | Private     | 10        | 10          | 4       | 4          | NWNW    | 10       | 28      | 23E   | QtrQtrSe      |             |                   |                  | x                   |                                |                    | 
| 1448026184  | Northwest | B      | GRPB    | 00012 | ARTONDALE HILL HOMEOWNER ASSN. | 1      | WELL                | Ground Water - Well | Permanent | 15       | 205       | 33           | U              | PIERCE  | Private     | 24        | 24          | 8       | 8          | SENW    | 21       | 14      | 01E   | GPS           |             |                   |                  | x                   |                                |                    | 
| 1448026184  | Northwest | B      | GRPB    | 00014 | AQUA VIEW COMMUNITY CLUB INC.  | 1      | WELL ALT168         | Ground Water - Well | Permanent | 6        | 290       | 4            | H              | ISLAND  | Association | 10        | 10          | 5       | 5          | SESW    | 16       | 30      | 02E   | GPS           |             |                   |                  | x                   | x                              |                    | 
| 1448026184  | Northwest | B      | GRPB    | 00015 | FLANN SYSTEM                   | 1      | FLANN SYSTEM ALT114 | Ground Water - Well | Permanent | 6        | 72        | 6            | N              | ISLAND  | Association | 6         | 6           | 3       | 3          | NWSE    | 29       | 9       | 02E   | GPS           |             |                   |                  | x                   | x                              |                    | 
| 1448026184  | Northwest | B      | GRPB    | 00016 | STEELE COMMUNITY WATER SYSTEM  | 1      | WELL                | Ground Water - Well | Permanent | 8        | 112       | 20           | U              | KING    | Private     | 15        | 15          | 6       | 6          | SWSW    | 23       | 14      | 06E   | QtrQtrSe      |             |                   |                  | x                   | x                              |                    | 
```