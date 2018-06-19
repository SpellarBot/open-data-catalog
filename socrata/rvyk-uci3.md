# SHL Vehicle Endorsed bases

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/shl-vehicle-endorsed-bases-e40d9) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rvyk-uci3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rvyk-uci3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rvyk-uci3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rvyk-uci3 |
| Name | SHL Vehicle Endorsed bases |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | shl vehicle endorsed bases, tlc, taxi and limousine commission (tlc) |
| Created | 2014-03-06T06:16:10Z |
| Publication Date | 2014-03-06T06:17:11Z |

## Description

This list contains information on SHL endorsed bases

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| No       | time           | :updated_at                | updated_at                 | meta_data | meta_data   |
| Yes      | series tag     | license_number             | License Number             | text      | text        |
| Yes      | series tag     | name_of_licensee           | Name Of Licensee           | text      | text        |
| Yes      | series tag     | alternate_name_of_licensee | Alternate Name Of Licensee | text      | text        |
| Yes      | series tag     | license_status             | License Status             | text      | text        |
| Yes      | series tag     | license_type               | License Type               | text      | text        |
| No       |                | address                    | Address                    | text      | text        |
| Yes      | series tag     | telephone_number           | Telephone Number           | text      | text        |
| Yes      | numeric metric | attached_shl_vehicles_wv   | Attached SHL Vehicles WV   | number    | number      |
| Yes      | numeric metric | attached_shl_vehicles_nw   | Attached SHL Vehicles NW   | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:rvyk-uci3 d:2014-03-05T22:16:13.000Z t:alternate_name_of_licensee="AZTECA EXPRESS" t:telephone_number="(718) 436-1111" t:license_type="TLC Licensed Base - Livery" t:license_status=CURRENT t:license_number=B00131 t:name_of_licensee="NEW MEXICANA CAR SERVICE II INC." m:attached_shl_vehicles_wv=2 m:attached_shl_vehicles_nw=11

series e:rvyk-uci3 d:2014-03-05T22:16:13.000Z t:alternate_name_of_licensee="KELLY'S PRIVATE CAR SERVICE" t:telephone_number="(718) 229-4141" t:license_type="TLC Licensed Base - Livery" t:license_status=CURRENT t:license_number=B00171 t:name_of_licensee="SHAMROCK DISPATCH INC" m:attached_shl_vehicles_wv=1 m:attached_shl_vehicles_nw=3

series e:rvyk-uci3 d:2014-03-05T22:16:13.000Z t:telephone_number="(212) 360-6241" t:license_type="TLC Licensed Base - Livery" t:license_status=CURRENT t:license_number=B00196 t:name_of_licensee="NEW EASY WAY RADIO DISP INC" m:attached_shl_vehicles_nw=28
```

## Meta Commands

```ls
metric m:attached_shl_vehicles_wv p:integer l:"Attached SHL Vehicles WV" t:dataTypeName=number

metric m:attached_shl_vehicles_nw p:integer l:"Attached SHL Vehicles NW" t:dataTypeName=number

entity e:rvyk-uci3 l:"SHL Vehicle Endorsed bases" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/rvyk-uci3

property e:rvyk-uci3 t:meta.view v:id=rvyk-uci3 v:category=Transportation v:averageRating=0 v:name="SHL Vehicle Endorsed bases" v:attribution="Taxi and Limousine Commission (TLC)"

property e:rvyk-uci3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rvyk-uci3 t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| :updated_at | license_number | name_of_licensee                 | alternate_name_of_licensee  | license_status | license_type               | address                                 | telephone_number | attached_shl_vehicles_wv | attached_shl_vehicles_nw | 
| =========== | ============== | ================================ | =========================== | ============== | ========================== | ======================================= | ================ | ======================== | ======================== | 
| 1394057773  | B00131         | NEW MEXICANA CAR SERVICE II INC. | AZTECA EXPRESS              | CURRENT        | TLC Licensed Base - Livery | 469 53 STREET BROOKLYN NY 11220         | (718) 436-1111   | 2                        | 11                       | 
| 1394057773  | B00171         | SHAMROCK DISPATCH INC            | KELLY'S PRIVATE CAR SERVICE | CURRENT        | TLC Licensed Base - Livery | 212-35 42 AVENUE BAYSIDE NY 11361       | (718) 229-4141   | 1                        | 3                        | 
| 1394057773  | B00196         | NEW EASY WAY RADIO DISP INC      |                             | CURRENT        | TLC Licensed Base - Livery | 151 EAST 106 STREET NEW YORK NY 10029   | (212) 360-6241   |                          | 28                       | 
| 1394057773  | B00221         | PROFESSIONAL CAR SERVICE INC     |                             | CURRENT        | TLC Licensed Base - Livery | 376 AUDUBON AVENUE NEW YORK NY 10033    | (212) 923-6565   | 2                        | 33                       | 
| 1394057773  | B00222         | REYNO CAR SVC, INC.              |                             | CURRENT        | TLC Licensed Base - Livery | 199 AUDUBON AVENUE NEW YORK NY 10033    | (212) 923-6800   |                          | 5                        | 
| 1394057773  | B00248         | YELLOWSTONE TRANSPORTATION INC.  | YES CAR SERVICE             | CURRENT        | TLC Licensed Base - Livery | 133-56 41 AVENUE FLUSHING NY 11355      | (718) 492-9300   |                          | 2                        | 
| 1394057773  | B00290         | ZPI CORPORATION                  | NATIONAL HIGH CLASS         | CURRENT        | TLC Licensed Base - Livery | 112-47 ROOSEVELT AVENUE CORONA NY 11368 | (718) 507-6363   |                          | 7                        | 
| 1394057773  | B00310         | WATSON CAR SERVICE INC.          |                             | CURRENT        | TLC Licensed Base - Livery | 1681 BRUCKNER BOULEVARD BRONX NY 10472  | (718) 991-8484   | 4                        | 22                       | 
| 1394057773  | B00319         | AVENTINE AUTO RENTAL INC         | SAFEWAY CAR SVCE            | CURRENT        | TLC Licensed Base - Livery | 2079 EAST 16 STREET BROOKLYN NY 11229   | (718) 336-1010   | 2                        | 10                       | 
| 1394057773  | B00334         | DO MAX CORP.                     | HIGH BRIDGE C/S             | CURRENT        | TLC Licensed Base - Livery | 2402 AMSTERDAM AVENUE NEW YORK NY 10033 | (212) 927-4600   |                          | 5                        | 
```