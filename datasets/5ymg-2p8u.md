# Trips Taken on Public Transit by Transit Type - Monthly Total Trips

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/trips-taken-on-public-transit-by-transit-type-4abd1) |
| Metadata | [Link](https://data.maryland.gov/api/views/5ymg-2p8u) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/5ymg-2p8u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/5ymg-2p8u/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 5ymg-2p8u |
| Name | Trips Taken on Public Transit by Transit Type - Monthly Total Trips |
| Attribution | Maryland Transit Authority |
| Category | Transportation |
| Tags | transit, mta, maryland transit administration, governor's office of performance improvement, bus, metro, marc, rail, mobility, paratransit, ridership |
| Created | 2012-08-21T19:01:05Z |
| Publication Date | 2015-09-08T15:53:01Z |

## Description

Data are provided by the Maryland Transit Administration (MTA). This data set includes total trips taken by bus, metro, rail, and mobility/paratransit services. 

Beginning in FY2014, the Maryland Transit Administration (MTA) began counting Core Bus ridership using an Automated Passenger Count (APC) system to better track the number of people boarding and leaving the buses. In order to maintain the integrity of historical comparisons for the Transit Ridership Goal, the MTA used ridership estimate differences between the new APC system and previous counting estimates for its Bus Service to allow for apples-to-apples comparisons between fiscal years.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year        | Fiscal Year        | text      | text        |
| Yes      | series tag     | month              | Month              | text      | text        |
| Yes      | numeric metric | bus                | Bus                | number    | number      |
| Yes      | numeric metric | metro              | Metro              | number    | number      |
| Yes      | numeric metric | light_rail         | Light Rail         | number    | number      |
| Yes      | numeric metric | mobility           | Mobility           | number    | number      |
| Yes      | numeric metric | taxi_access_trips  | Taxi Access Trips  | number    | number      |
| Yes      | numeric metric | marc_total         | MARC Total         | number    | number      |
| Yes      | numeric metric | commuter_bus_total | Commuter Bus Total | number    | number      |
| Yes      | numeric metric | baltimore          | Baltimore          | number    | number      |
| Yes      | numeric metric | washington         | Washington         | number    | number      |
| Yes      | numeric metric | icc                | ICC                | number    | number      |
| Yes      | numeric metric | total_ridership    | Total Trips        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:5ymg-2p8u d:2014-08-28T09:31:07.000Z t:fiscal_year=2007 t:month=Jul-06 m:marc_total=566473 m:bus=5022875 m:metro=1062276 m:total_ridership=7560691 m:mobility=66973 m:light_rail=563420 m:taxi_access_trips=29592 m:commuter_bus_total=249082

series e:5ymg-2p8u d:2014-08-28T09:31:07.000Z t:fiscal_year=2007 t:month=Aug-06 m:marc_total=665676 m:bus=5601827 m:metro=1155017 m:total_ridership=8423584 m:mobility=73217 m:light_rail=590410 m:taxi_access_trips=30637 m:commuter_bus_total=306800

series e:5ymg-2p8u d:2014-08-28T09:31:07.000Z t:fiscal_year=2007 t:month=Sep-06 m:marc_total=621184 m:bus=5978326 m:metro=1046468 m:total_ridership=8591923 m:mobility=69152 m:light_rail=572017 m:taxi_access_trips=31137 m:commuter_bus_total=273639
```

## Meta Commands

```ls
metric m:bus p:integer l:Bus t:dataTypeName=number

metric m:metro p:integer l:Metro t:dataTypeName=number

metric m:light_rail p:integer l:"Light Rail" t:dataTypeName=number

metric m:mobility p:integer l:Mobility t:dataTypeName=number

metric m:taxi_access_trips p:integer l:"Taxi Access Trips" t:dataTypeName=number

metric m:marc_total p:integer l:"MARC Total" t:dataTypeName=number

metric m:commuter_bus_total p:integer l:"Commuter Bus Total" t:dataTypeName=number

metric m:baltimore p:integer l:Baltimore t:dataTypeName=number

metric m:washington p:integer l:Washington t:dataTypeName=number

metric m:icc p:integer l:ICC t:dataTypeName=number

metric m:total_ridership p:integer l:"Total Trips" d:"The total number of trips taken by transit." t:dataTypeName=number

entity e:5ymg-2p8u l:"Trips Taken on Public Transit by Transit Type - Monthly Total Trips" t:attribution="Maryland Transit Authority" t:url=https://data.maryland.gov/api/views/5ymg-2p8u

property e:5ymg-2p8u t:meta.view v:id=5ymg-2p8u v:category=Transportation v:attributionLink=http://mta.maryland.gov/ v:averageRating=0 v:name="Trips Taken on Public Transit by Transit Type - Monthly Total Trips" v:attribution="Maryland Transit Authority"

property e:5ymg-2p8u t:meta.view.license v:name="Public Domain"

property e:5ymg-2p8u t:meta.view.owner v:id=ktdw-k6sj v:screenName=MRaifman v:displayName=MRaifman

property e:5ymg-2p8u t:meta.view.tableauthor v:id=ktdw-k6sj v:screenName=MRaifman v:displayName=MRaifman
```

## Top Records

```ls
| :updated_at | fiscal_year | month  | bus     | metro   | light_rail | mobility | taxi_access_trips | marc_total | commuter_bus_total | baltimore | washington | icc | total_ridership | 
| =========== | =========== | ====== | ======= | ======= | ========== | ======== | ================= | ========== | ================== | ========= | ========== | === | =============== | 
| 1409218267  | 2007        | Jul-06 | 5022875 | 1062276 | 563420     | 66973    | 29592             | 566473     | 249082             |           |            |     | 7560691         | 
| 1409218267  | 2007        | Aug-06 | 5601827 | 1155017 | 590410     | 73217    | 30637             | 665676     | 306800             |           |            |     | 8423584         | 
| 1409218267  | 2007        | Sep-06 | 5978326 | 1046468 | 572017     | 69152    | 31137             | 621184     | 273639             |           |            |     | 8591923         | 
| 1409218267  | 2007        | Oct-06 | 6356666 | 1149124 | 575015     | 75491    | 32746             | 660357     | 294433             |           |            |     | 9143832         | 
| 1409218267  | 2007        | Nov-06 | 5993449 | 1054117 | 554012     | 71881    | 29423             | 559310     | 265580             |           |            |     | 8527772         | 
| 1409218267  | 2007        | Dec-06 | 5577895 | 1015775 | 567745     | 69907    | 32136             | 577788     | 237577             |           |            |     | 8078823         | 
| 1409218267  | 2007        | Jan-07 | 6083549 | 1120371 | 585422     | 73160    | 30140             | 625836     | 288123             |           |            |     | 8806601         | 
| 1409218267  | 2007        | Feb-07 | 5062070 | 990891  | 599427     | 62940    | 27626             | 585828     | 249248             |           |            |     | 7578030         | 
| 1409218267  | 2007        | Mar-07 | 6379101 | 1173170 | 595223     | 79701    | 27558             | 663535     | 307900             |           |            |     | 9226188         | 
| 1409218267  | 2007        | Apr-07 | 5678757 | 1101482 | 616013     | 74734    | 29457             | 666082     | 279924             |           |            |     | 8446449         | 
```