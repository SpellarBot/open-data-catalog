# PWS SRC Source Cap And Well Depth

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pws-src-source-cap-and-well-depth) |
| Metadata | [Link](https://data.wa.gov/api/views/hsuv-x2dz) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/hsuv-x2dz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/hsuv-x2dz/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | hsuv-x2dz |
| Name | PWS SRC Source Cap And Well Depth |
| Category | Natural Resources & Environment |
| Tags | drought, source capacity, well depth |
| Created | 2015-11-20T21:55:23Z |
| Publication Date | 2015-11-20T21:58:33Z |

## Description

PWS SRCs whose source capacity is less than 20 gal/min and well depth is less than 50ft.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| No       |                | f              | F              | text      | text        |
| Yes      | series tag     | ws_id          | WS ID          | text      | text        |
| Yes      | series tag     | ws_name        | WS Name        | text      | text        |
| Yes      | numeric metric | srcnum         | SrcNum         | number    | number      |
| Yes      | series tag     | srcname        | SrcName        | text      | text        |
| Yes      | series tag     | srctype        | SrcType        | text      | text        |
| Yes      | series tag     | srcuse         | SrcUse         | text      | text        |
| Yes      | series tag     | wria_num       | WRIA Num       | text      | number      |
| Yes      | numeric metric | welldepth      | WellDepth      | number    | number      |
| Yes      | numeric metric | src_capacity   | Src_Capacity   | number    | number      |
| Yes      | series tag     | susceptibility | Susceptibility | text      | text        |
| Yes      | series tag     | county         | County         | text      | text        |
| Yes      | series tag     | ownership      | Ownership      | text      | text        |
| Yes      | numeric metric | ft_respop      | FT ResPop      | number    | number      |
| Yes      | numeric metric | maxtotalpop    | MaxTotalPop    | number    | number      |
| Yes      | numeric metric | resconn        | ResConn        | number    | number      |
| Yes      | numeric metric | total_conn     | Total Conn     | number    | number      |
| Yes      | series tag     | qtr_qtr        | Qtr/Qtr        | text      | text        |
| Yes      | numeric metric | township       | Township       | number    | number      |
| Yes      | numeric metric | section        | Section        | number    | number      |
| Yes      | series tag     | range          | Range          | text      | text        |
| Yes      | series tag     | latlongmethod  | LatLongMethod  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = f
```

## Data Commands

```ls
series e:hsuv-x2dz d:2015-11-20T13:55:28.000Z t:latlongmethod=GPS t:ws_name="TRIPLE R RENTALS" t:ownership=Investor t:srcname="WELL #1" t:range=18E t:county=YAKIMA t:wria_num=37 t:susceptibility=N t:qtr_qtr=SWNW t:ws_id=00001 t:srctype="Ground Water - Well" t:srcuse=Permanent m:total_conn=1 m:welldepth=0 m:ft_respop=0 m:township=13 m:src_capacity=8 m:maxtotalpop=13 m:srcnum=1 m:section=14 m:resconn=0

series e:hsuv-x2dz d:2015-11-20T13:55:28.000Z t:latlongmethod=QtrQtrSe t:ws_name="DAMRILL, LOYD" t:ownership=Private t:srcname=WELL t:range=03E t:county=CLARK t:wria_num=27 t:susceptibility=U t:qtr_qtr=NWSE t:ws_id=00055 t:srctype="Ground Water - Well" t:srcuse=Permanent m:total_conn=2 m:welldepth=45 m:ft_respop=5 m:township=5 m:src_capacity=17 m:maxtotalpop=5 m:srcnum=1 m:section=7 m:resconn=2

series e:hsuv-x2dz d:2015-11-20T13:55:28.000Z t:latlongmethod=GPS t:ws_name="SPOKANE RIFLE CLUB NORTH" t:ownership=Private t:srcname="Well #1 AHC114" t:range=42E t:county=SPOKANE t:wria_num=54 t:susceptibility=H t:qtr_qtr=SESE t:ws_id=00079 t:srctype="Ground Water - Well" t:srcuse=Permanent m:total_conn=1 m:welldepth=50 m:ft_respop=0 m:township=26 m:src_capacity=15 m:maxtotalpop=18 m:srcnum=1 m:section=28 m:resconn=0
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

entity e:hsuv-x2dz l:"PWS SRC Source Cap And Well Depth" t:url=https://data.wa.gov/api/views/hsuv-x2dz

property e:hsuv-x2dz t:meta.view v:id=hsuv-x2dz v:category="Natural Resources & Environment" v:averageRating=0 v:name="PWS SRC Source Cap And Well Depth"

property e:hsuv-x2dz t:meta.view.owner v:id=x62c-cuxv v:screenName="Joshua Plaster" v:displayName="Joshua Plaster"

property e:hsuv-x2dz t:meta.view.tableauthor v:id=x62c-cuxv v:screenName="Joshua Plaster" v:roleName=editor v:displayName="Joshua Plaster"
```

## Top Records

```ls
| :updated_at | f         | ws_id | ws_name                         | srcnum | srcname           | srctype             | srcuse    | wria_num | welldepth | src_capacity | susceptibility | county   | ownership | ft_respop | maxtotalpop | resconn | total_conn | qtr_qtr | township | section | range | latlongmethod | 
| =========== | ========= | ===== | =============================== | ====== | ================= | =================== | ========= | ======== | ========= | ============ | ============== | ======== | ========= | ========= | =========== | ======= | ========== | ======= | ======== | ======= | ===== | ============= | 
| 1448027728  | Eastern   | 00001 | TRIPLE R RENTALS                | 1      | WELL #1           | Ground Water - Well | Permanent | 37       | 0         | 8            | N              | YAKIMA   | Investor  | 0         | 13          | 0       | 1          | SWNW    | 13       | 14      | 18E   | GPS           | 
| 1448027728  | Southwest | 00055 | DAMRILL, LOYD                   | 1      | WELL              | Ground Water - Well | Permanent | 27       | 45        | 17           | U              | CLARK    | Private   | 5         | 5           | 2       | 2          | NWSE    | 5        | 7       | 03E   | QtrQtrSe      | 
| 1448027728  | Eastern   | 00079 | SPOKANE RIFLE CLUB NORTH        | 1      | Well #1 AHC114    | Ground Water - Well | Permanent | 54       | 50        | 15           | H              | SPOKANE  | Private   | 0         | 18          | 0       | 1          | SESE    | 26       | 28      | 42E   | GPS           | 
| 1448027728  | Eastern   | 00106 | J & J WELL WATER SYSTEM         | 1      | WELL # 1          | Ground Water - Well | Permanent | 34       | 30        | 15           | U              | SPOKANE  | Private   | 5         | 5           | 2       | 2          | SWNE    | 22       | 5       | 40E   | QtrQtrSe      | 
| 1448027728  | Northwest | 00119 | KONTREE APARTMENTS WATER SYSTEM | 1      | Well 1 - West     | Ground Water - Well | Emergency | 1        | 18        | 20           | H              | WHATCOM  | Investor  | 60        | 60          | 36      | 36         | SWSW    | 40       | 23      | 02E   | GPS           | 
| 1448027728  | Northwest | 00122 | DODGE-STURGEON WATER SYSTEM     | 1      | WELL 1            | Ground Water - Well | Permanent | 15       | 31        | 10           | U              | PIERCE   | Private   | 4         | 4           | 2       | 2          | SWSW    | 21       | 33      | 01W   | GPS           | 
| 1448027728  | Northwest | 00122 | DODGE-STURGEON WATER SYSTEM     | 1      | WELL 1            | Ground Water - Well | Permanent | 15       | 31        | 10           | U              | PIERCE   | Private   | 4         | 4           | 2       | 2          | SWSW    | 21       | 33      | 01W   | GPS           | 
| 1448027728  | Northwest | 00143 | BRIGGS BOYS                     | 1      | DUG WELL          | Ground Water - Well | Permanent | 7        | 32        | 3            | N              | KING     | Private   | 5         | 5           | 2       | 2          | SENE    | 24       | 17      | 07E   | GPS           | 
| 1448027728  | Northwest | 00222 | BOUMA SHORT PLAT                | 1      | WELL              | Ground Water - Well | Permanent | 1        | 40        | 5            | U              | WHATCOM  | Private   | 11        | 11          | 3       | 3          | SWSE    | 29       | 11      | 03E   | QtrQtrSe      | 
| 1448027728  | Southwest | 00240 | G&M ESTATE                      | 1      | WELL #1 ABK184 8" | Ground Water - Well | Permanent | 23       | 45        | 0            | N              | THURSTON | Investor  | 2         | 39          | 2       | 5          | NWSW    | 15       | 13      | 03W   | GPS           | 
```