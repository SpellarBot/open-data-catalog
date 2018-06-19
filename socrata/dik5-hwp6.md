# Los Angeles International Airport (LAX) - Parking Lots Current Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/los-angeles-international-airport-lax-parking-lots-current-status) |
| Metadata | [Link](https://data.lacity.org/api/views/dik5-hwp6) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/dik5-hwp6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/dik5-hwp6/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | dik5-hwp6 |
| Name | Los Angeles International Airport (LAX) - Parking Lots Current Status |
| Tags | parking realtime status lax lawa airport |
| Created | 2016-11-30T17:58:29Z |
| Publication Date | 2016-12-01T15:13:24Z |

## Description

Displays parking information capacity live. Information on Parking lots; 1, 2A, 2B, 3, 4, 5, 6, 7, and C. Data is updated every five minutes

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | key_value          | Key_Value          | text          | text          |
| Yes      | series tag     | lotdescription     | LotDescription     | text          | text          |
| Yes      | series tag     | parkingid          | ParkingID          | text          | text          |
| Yes      | series tag     | parkingname        | ParkingName        | text          | text          |
| Yes      | numeric metric | totalparkingspaces | TotalParkingSpaces | number        | number        |
| Yes      | numeric metric | occupied           | Occupied           | number        | number        |
| Yes      | numeric metric | freespaces         | FreeSpaces         | number        | number        |
| Yes      | numeric metric | fullcapacity       | FullCapacity       | number        | number        |
| Yes      | series tag     | color              | Color              | text          | text          |
| Yes      | time           | dataexportdatetime | DataExportDateTime | calendar_date | calendar_date |
| No       |                | long               | Long               | number        | number        |
| No       |                | lat                | Lat                | number        | number        |
```

## Time Field

```ls
Value = dataexportdatetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = long,lat
```

## Data Commands

```ls
series e:dik5-hwp6 d:2017-04-21T00:40:00.000Z t:parkingid=P1 t:parkingname=P-1 t:lotdescription="Lot 1 Occupancy" t:color=Green t:key_value=c1000 m:occupied=549 m:fullcapacity=38 m:totalparkingspaces=1428 m:freespaces=879

series e:dik5-hwp6 d:2017-04-21T00:40:00.000Z t:parkingid=P7 t:parkingname=P-7 t:lotdescription="Lot 7 Occupancy" t:color=Yellow t:key_value=c7000 m:occupied=1114 m:fullcapacity=62 m:totalparkingspaces=1785 m:freespaces=671

series e:dik5-hwp6 d:2017-04-21T00:40:00.000Z t:parkingid=P2A t:parkingname=P-2A t:lotdescription="Lot 2A Occupancy" t:color=Green t:key_value=c2000 m:occupied=187 m:fullcapacity=23 m:totalparkingspaces=828 m:freespaces=641
```

## Meta Commands

```ls
metric m:totalparkingspaces p:integer l:TotalParkingSpaces t:dataTypeName=number

metric m:occupied p:integer l:Occupied t:dataTypeName=number

metric m:freespaces p:integer l:FreeSpaces t:dataTypeName=number

metric m:fullcapacity p:integer l:FullCapacity t:dataTypeName=number

entity e:dik5-hwp6 l:"Los Angeles International Airport (LAX) - Parking Lots Current Status" t:url=https://data.lacity.org/api/views/dik5-hwp6

property e:dik5-hwp6 t:meta.view v:id=dik5-hwp6 v:averageRating=0 v:name="Los Angeles International Airport (LAX) - Parking Lots Current Status"

property e:dik5-hwp6 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:dik5-hwp6 t:meta.view.owner v:id=gudt-ccne v:profileImageUrlMedium=/api/users/gudt-ccne/profile_images/THUMB v:profileImageUrlLarge=/api/users/gudt-ccne/profile_images/LARGE v:screenName="LAWA OpenData" v:profileImageUrlSmall=/api/users/gudt-ccne/profile_images/TINY v:displayName="LAWA OpenData"

property e:dik5-hwp6 t:meta.view.tableauthor v:id=gudt-ccne v:profileImageUrlMedium=/api/users/gudt-ccne/profile_images/THUMB v:profileImageUrlLarge=/api/users/gudt-ccne/profile_images/LARGE v:screenName="LAWA OpenData" v:profileImageUrlSmall=/api/users/gudt-ccne/profile_images/TINY v:roleName=publisher v:displayName="LAWA OpenData"
```

## Top Records

```ls
| key_value | lotdescription   | parkingid | parkingname | totalparkingspaces | occupied | freespaces | fullcapacity | color  | dataexportdatetime  | long      | lat         | 
| ========= | ================ | ========= | =========== | ================== | ======== | ========== | ============ | ====== | =================== | ========= | =========== | 
| c1000     | Lot 1 Occupancy  | P1        | P-1         | 1428               | 549      | 879        | 38           | Green  | 2017-04-21T00:40:00 | 33.944847 | -118.400690 | 
| c7000     | Lot 7 Occupancy  | P7        | P-7         | 1785               | 1114     | 671        | 62           | Yellow | 2017-04-21T00:40:00 | 33.943858 | -118.400137 | 
| c2000     | Lot 2A Occupancy | P2A       | P-2A        | 828                | 187      | 641        | 23           | Green  | 2017-04-21T00:40:00 | 33.944659 | -118.403942 | 
| c3000     | Lot 3 Occupancy  | P3        | P-3         | 1278               | 550      | 728        | 43           | Green  | 2017-04-21T00:40:00 | 33.944265 | -118.407169 | 
| c4000     | Lot 4 Occupancy  | P4        | P-4         | 1188               | 330      | 858        | 28           | Green  | 2017-04-21T00:40:00 | 33.943028 | -118.407007 | 
| c5000     | Lot 5 Occupancy  | P5        | P-5         | 696                | 519      | 177        | 75           | Yellow | 2017-04-21T00:40:00 | 33.943303 | -118.405150 | 
| c6000     | Lot 6 Occupancy  | P6        | P-6         | 905                | 617      | 288        | 68           | Yellow | 2017-04-21T00:40:00 | 33.943427 | -118.403746 | 
| c9000     | Lot C Occupancy  | PC        | Lot C       | 5397               | 4179     | 1218       | 77           | Yellow | 2017-04-21T00:40:00 | 33.951378 | -118.392918 | 
| c2001     | Lot 2B Occupancy | P2B       | P-2B        | 637                | 372      | 265        | 58           | Yellow | 2017-04-21T00:40:00 | 33.944472 | -118.405295 | 
```