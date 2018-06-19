# Passenger Counts May 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/passenger-counts-may-2013-4ce5c) |
| Metadata | [Link](https://data.hawaii.gov/api/views/k5s6-yfqg) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/k5s6-yfqg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/k5s6-yfqg/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | k5s6-yfqg |
| Name | Passenger Counts May 2013 |
| Attribution | DBEDT |
| Category | Economic Development |
| Created | 2013-05-30T00:05:56Z |
| Publication Date | 2013-07-05T20:43:55Z |

## Description

Updated daily, Monday through Friday. International Passenger Count excluding flights from Canada. May 2012 counts included for comparison.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | series tag     | 2013                         | 2013                         | text      | text        |
| Yes      | series tag     | 2012                         | 2012                         | text      | text        |
| Yes      | series tag     | day                          | Day                          | text      | text        |
| Yes      | numeric metric | may_2013_international_japan | may-2013-international-Japan | number    | number      |
| Yes      | numeric metric | may_2013_international_other | may-2013-international-other | number    | number      |
| Yes      | numeric metric | may_2013_domestic_honolulu   | may-2013-domestic-Honolulu   | number    | number      |
| Yes      | numeric metric | may_2013_domestic_maui       | may-2013-domestic-Maui       | number    | number      |
| Yes      | numeric metric | may_2013_domestic_big_island | may-2013-domestic-Big Island | number    | number      |
| Yes      | numeric metric | may_2013_domestic_kauai      | may-2013-domestic -Kauai     | number    | number      |
| Yes      | numeric metric | may_2012_international_japan | may-2012-international-Japan | number    | number      |
| Yes      | numeric metric | may_2012_international_other | may-2012-international-other | number    | number      |
| Yes      | numeric metric | may_2012_domestic_honolulu   | may-2012-domestic-Honolulu   | number    | number      |
| Yes      | numeric metric | may_2012_domestic_maui       | may-2012-domestic-Maui       | number    | number      |
| Yes      | numeric metric | may_2012_domestic_big_island | may-2012-domestic-Big Island | number    | number      |
| Yes      | numeric metric | may_2012_domestic_kauai      | may-2012-domestic -Kauai     | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:k5s6-yfqg d:2013-01-01T00:00:00.000Z t:2013=1-May-13 t:2012=2-May-12 t:day=Wed m:may_2013_domestic_honolulu=10315 m:may_2012_domestic_big_island=1281 m:may_2013_domestic_big_island=1293 m:may_2013_domestic_kauai=1210 m:may_2013_international_other=1489 m:may_2012_international_japan=4642 m:may_2012_domestic_maui=3677 m:may_2012_international_other=1137 m:may_2012_domestic_honolulu=10140 m:may_2012_domestic_kauai=1222 m:may_2013_domestic_maui=3701 m:may_2013_international_japan=4069

series e:k5s6-yfqg d:2013-01-01T00:00:00.000Z t:2013=2-May-13 t:2012=3-May-12 t:day=Thu m:may_2013_domestic_honolulu=11054 m:may_2012_domestic_big_island=1499 m:may_2013_domestic_big_island=1397 m:may_2013_domestic_kauai=1354 m:may_2013_international_other=2257 m:may_2012_international_japan=4587 m:may_2012_domestic_maui=2445 m:may_2012_international_other=1734 m:may_2012_domestic_honolulu=10951 m:may_2012_domestic_kauai=1331 m:may_2013_domestic_maui=3469 m:may_2013_international_japan=4699

series e:k5s6-yfqg d:2013-01-01T00:00:00.000Z t:2013=4-May-13 t:2012=5-May-12 t:day=Sat m:may_2013_domestic_honolulu=11281 m:may_2012_domestic_big_island=1647 m:may_2013_domestic_big_island=1557 m:may_2013_domestic_kauai=1670 m:may_2013_international_other=2302 m:may_2012_international_japan=2711 m:may_2012_domestic_maui=4388 m:may_2012_international_other=1544 m:may_2012_domestic_honolulu=10093 m:may_2012_domestic_kauai=1660 m:may_2013_domestic_maui=3245 m:may_2013_international_japan=3134
```

## Meta Commands

```ls
metric m:may_2013_international_japan p:integer l:may-2013-international-Japan t:dataTypeName=number

metric m:may_2013_international_other p:integer l:may-2013-international-other t:dataTypeName=number

metric m:may_2013_domestic_honolulu p:integer l:may-2013-domestic-Honolulu t:dataTypeName=number

metric m:may_2013_domestic_maui p:integer l:may-2013-domestic-Maui t:dataTypeName=number

metric m:may_2013_domestic_big_island p:integer l:"may-2013-domestic-Big Island" t:dataTypeName=number

metric m:may_2013_domestic_kauai p:integer l:"may-2013-domestic -Kauai" t:dataTypeName=number

metric m:may_2012_international_japan p:integer l:may-2012-international-Japan t:dataTypeName=number

metric m:may_2012_international_other p:integer l:may-2012-international-other t:dataTypeName=number

metric m:may_2012_domestic_honolulu p:integer l:may-2012-domestic-Honolulu t:dataTypeName=number

metric m:may_2012_domestic_maui p:integer l:may-2012-domestic-Maui t:dataTypeName=number

metric m:may_2012_domestic_big_island p:integer l:"may-2012-domestic-Big Island" t:dataTypeName=number

metric m:may_2012_domestic_kauai p:integer l:"may-2012-domestic -Kauai" t:dataTypeName=number

entity e:k5s6-yfqg l:"Passenger Counts May 2013" t:attribution=DBEDT t:url=https://data.hawaii.gov/api/views/k5s6-yfqg

property e:k5s6-yfqg t:meta.view v:id=k5s6-yfqg v:category="Economic Development" v:attributionLink=http://dbedt.hawaii.gov/economic/data_reports/special/ v:averageRating=0 v:name="Passenger Counts May 2013" v:attribution=DBEDT

property e:k5s6-yfqg t:meta.view.license v:name="Public Domain"

property e:k5s6-yfqg t:meta.view.owner v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:displayName="Open Data Portal Administrator"

property e:k5s6-yfqg t:meta.view.tableauthor v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"
```

## Top Records

```ls
| 2013      | 2012      | day | may_2013_international_japan | may_2013_international_other | may_2013_domestic_honolulu | may_2013_domestic_maui | may_2013_domestic_big_island | may_2013_domestic_kauai | may_2012_international_japan | may_2012_international_other | may_2012_domestic_honolulu | may_2012_domestic_maui | may_2012_domestic_big_island | may_2012_domestic_kauai | 
| ========= | ========= | === | ============================ | ============================ | ========================== | ====================== | ============================ | ======================= | ============================ | ============================ | ========================== | ====================== | ============================ | ======================= | 
| 1-May-13  | 2-May-12  | Wed | 4069                         | 1489                         | 10315                      | 3701                   | 1293                         | 1210                    | 4642                         | 1137                         | 10140                      | 3677                   | 1281                         | 1222                    | 
| 2-May-13  | 3-May-12  | Thu | 4699                         | 2257                         | 11054                      | 3469                   | 1397                         | 1354                    | 4587                         | 1734                         | 10951                      | 2445                   | 1499                         | 1331                    | 
| 4-May-13  | 5-May-12  | Sat | 3134                         | 2302                         | 11281                      | 3245                   | 1557                         | 1670                    | 2711                         | 1544                         | 10093                      | 4388                   | 1647                         | 1660                    | 
| 6-May-13  | 7-May-12  | Mon | 2674                         | 1791                         | 10431                      | 3258                   | 1297                         | 1183                    | 3138                         | 1420                         | 10708                      | 3245                   | 1150                         | 1171                    | 
| 7-May-13  | 8-May-12  | Tue | 2451                         | 2339                         | 10805                      | 3284                   | 1298                         | 1041                    | 2740                         | 1807                         | 10224                      | 3237                   | 1085                         | 1222                    | 
| 8-May-13  | 9-May-12  | Wed | 3576                         | 1610                         | 10545                      | 3733                   | 1223                         | 1308                    | 3354                         | 1008                         | 10121                      | 2948                   | 1422                         | 1151                    | 
| 10-May-13 | 11-May-12 | Fri | 2953                         | 2005                         | 11843                      | 3664                   | 1308                         | 1340                    | 3229                         | 1575                         | 10914                      | 3403                   | 1258                         | 1450                    | 
| 11-May-13 | 12-May-12 | Sat | 3067                         | 2466                         | 11743                      | 4135                   | 1549                         | 1687                    | 3453                         | 1614                         | 10838                      | 4109                   | 1576                         | 1646                    | 
| 12-May-13 | 13-May-12 | Sun | 4522                         | 1923                         | 11493                      | 3571                   | 1295                         | 1327                    | 4028                         | 1482                         | 10871                      | 3992                   | 1311                         | 1510                    | 
| 13-May-13 | 14-May-12 | Mon | 4062                         | 1817                         | 11139                      | 3547                   | 1379                         | 1261                    | 3540                         | 1469                         | 11048                      | 5393                   | 1372                         | 1310                    | 
```