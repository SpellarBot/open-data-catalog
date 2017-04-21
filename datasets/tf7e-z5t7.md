# PWS SRC Source Capacity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pws-src-source-capacity) |
| Metadata | [Link](https://data.wa.gov/api/views/tf7e-z5t7) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/tf7e-z5t7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/tf7e-z5t7/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | tf7e-z5t7 |
| Name | PWS SRC Source Capacity |
| Category | Natural Resources & Environment |
| Tags | drought, source capacity |
| Created | 2015-11-20T21:59:16Z |
| Publication Date | 2015-11-20T22:00:54Z |

## Description

PWS SRC's whose source capacity is less than 20 gal/min

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
series e:tf7e-z5t7 d:2015-11-20T13:59:26.000Z t:latlongmethod=GPS t:ws_name="TRIPLE R RENTALS" t:ownership=Investor t:srcname="WELL #1" t:range=18E t:county=YAKIMA t:wria_num=37 t:susceptibility=N t:qtr_qtr=SWNW t:ws_id=00001 t:srctype="Ground Water - Well" t:srcuse=Permanent m:total_conn=1 m:welldepth=0 m:ft_respop=0 m:township=13 m:src_capacity=8 m:maxtotalpop=13 m:srcnum=1 m:section=14 m:resconn=0

series e:tf7e-z5t7 d:2015-11-20T13:59:26.000Z t:ws_name="AUTO VIEW DRIVE-IN" t:ownership=Investor t:srcname="WELL 1" t:range=0 t:county=STEVENS t:wria_num=59 t:susceptibility=U t:ws_id=00006 t:srctype="Ground Water - Well" t:srcuse=Permanent m:total_conn=2 m:welldepth=190 m:ft_respop=3 m:township=0 m:src_capacity=1 m:maxtotalpop=13 m:srcnum=1 m:section=0 m:resconn=1

series e:tf7e-z5t7 d:2015-11-20T13:59:26.000Z t:latlongmethod=GPS t:ws_name="AQUA VIEW COMMUNITY CLUB INC." t:ownership=Association t:srcname="WELL ALT168" t:range=02E t:county=ISLAND t:wria_num=6 t:susceptibility=H t:qtr_qtr=SESW t:ws_id=00014 t:srctype="Ground Water - Well" t:srcuse=Permanent m:total_conn=5 m:welldepth=290 m:ft_respop=10 m:township=16 m:src_capacity=4 m:maxtotalpop=10 m:srcnum=1 m:section=30 m:resconn=5
```

## Meta Commands

```ls
metric m:srcnum p:integer l:SrcNum t:dataTypeName=number

metric m:welldepth p:integer l:WellDepth t:dataTypeName=number

metric m:src_capacity p:double l:Src_Capacity t:dataTypeName=number

metric m:ft_respop p:integer l:"FT ResPop" t:dataTypeName=number

metric m:maxtotalpop p:integer l:MaxTotalPop t:dataTypeName=number

metric m:resconn p:integer l:ResConn t:dataTypeName=number

metric m:total_conn p:integer l:"Total Conn" t:dataTypeName=number

metric m:township p:integer l:Township t:dataTypeName=number

metric m:section p:integer l:Section t:dataTypeName=number

entity e:tf7e-z5t7 l:"PWS SRC Source Capacity" t:url=https://data.wa.gov/api/views/tf7e-z5t7

property e:tf7e-z5t7 t:meta.view v:id=tf7e-z5t7 v:category="Natural Resources & Environment" v:averageRating=0 v:name="PWS SRC Source Capacity"

property e:tf7e-z5t7 t:meta.view.owner v:id=x62c-cuxv v:screenName="Joshua Plaster" v:displayName="Joshua Plaster"

property e:tf7e-z5t7 t:meta.view.tableauthor v:id=x62c-cuxv v:screenName="Joshua Plaster" v:roleName=editor v:displayName="Joshua Plaster"
```

## Top Records

```ls
| :updated_at | f         | ws_id | ws_name                            | srcnum | srcname             | srctype             | srcuse    | wria_num | welldepth | src_capacity | susceptibility | county    | ownership   | ft_respop | maxtotalpop | resconn | total_conn | qtr_qtr | township | section | range | latlongmethod | 
| =========== | ========= | ===== | ================================== | ====== | =================== | =================== | ========= | ======== | ========= | ============ | ============== | ========= | =========== | ========= | =========== | ======= | ========== | ======= | ======== | ======= | ===== | ============= | 
| 1448027966  | Eastern   | 00001 | TRIPLE R RENTALS                   | 1      | WELL #1             | Ground Water - Well | Permanent | 37       | 0         | 8            | N              | YAKIMA    | Investor    | 0         | 13          | 0       | 1          | SWNW    | 13       | 14      | 18E   | GPS           | 
| 1448027966  | Eastern   | 00006 | AUTO VIEW DRIVE-IN                 | 1      | WELL 1              | Ground Water - Well | Permanent | 59       | 190       | 1            | U              | STEVENS   | Investor    | 3         | 13          | 1       | 2          |         | 0        | 0       | 0     |               | 
| 1448027966  | Northwest | 00014 | AQUA VIEW COMMUNITY CLUB INC.      | 1      | WELL ALT168         | Ground Water - Well | Permanent | 6        | 290       | 4            | H              | ISLAND    | Association | 10        | 10          | 5       | 5          | SESW    | 16       | 30      | 02E   | GPS           | 
| 1448027966  | Northwest | 00015 | FLANN SYSTEM                       | 1      | FLANN SYSTEM ALT114 | Ground Water - Well | Permanent | 6        | 72        | 6            | N              | ISLAND    | Association | 6         | 6           | 3       | 3          | NWSE    | 29       | 9       | 02E   | GPS           | 
| 1448027966  | Northwest | 00016 | STEELE COMMUNITY WATER SYSTEM      | 1      | WELL                | Ground Water - Well | Permanent | 8        | 112       | 20           | U              | KING      | Private     | 15        | 15          | 6       | 6          | SWSW    | 23       | 14      | 06E   | QtrQtrSe      | 
| 1448027966  | Northwest | 00017 | KISER #2 COMMUNITY WATER SYSTEM    | 1      | WELL                | Ground Water - Well | Permanent | 7        | 200       | 5            | H              | KING      | Private     | 5         | 5           | 2       | 2          | NWSW    | 23       | 25      | 08E   | QtrQtrSe      | 
| 1448027966  | Northwest | 00018 | LARSON WATER SYSTEM                | 1      | WELL                | Ground Water - Well | Permanent | 5        | 165       | 20           | U              | SNOHOMISH | Private     | 5         | 5           | 3       | 3          | SWNW    | 32       | 8       | 04E   | QtrQtrSe      | 
| 1448027966  | Northwest | 00030 | BAILY MICHAEL M.                   | 1      | WELL #1             | Ground Water - Well | Permanent | 8        | 210       | 8            | U              | KING      | Private     | 10        | 10          | 4       | 4          | NWSW    | 22       | 9       | 06E   | GPS           | 
| 1448027966  | Northwest | 00033 | CONCORD LANE COMMUNITY ASSOCIATION | 1      | WELL #1             | Ground Water - Well | Permanent | 3        | 147       | 1.5          | H              | SKAGIT    | Private     | 6         | 6           | 2       | 2          | SWSW    | 35       | 12      | 04E   | Map           | 
| 1448027966  | Northwest | 00039 | OSHAUGHNESSY, KEVIN                | 1      | WELL #1             | Ground Water - Well | Permanent | 8        | 60        | 18           | U              | KING      | Investor    | 12        | 12          | 5       | 5          | NESW    | 23       | 14      | 06E   | QtrQtrSe      | 
```