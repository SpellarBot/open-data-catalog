# CT Transit Bus Stops

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ct-transit-bus-stops) |
| Metadata | [Link](https://data.hartford.gov/api/views/uxtm-zebz) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/uxtm-zebz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/uxtm-zebz/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | uxtm-zebz |
| Name | CT Transit Bus Stops |
| Attribution | CT Transit, Hartford Connecticut |
| Category | Community |
| Tags | bus, hartford, ct transit, transit, commute |
| Created | 2015-06-02T20:59:36Z |
| Publication Date | 2015-06-02T23:43:24Z |

## Description

This data set City of Hartford on 6/2/2015 and consists of all of the bus stops in the Hartford Area. Through an agreement with CT Transit this data set will be updated as the stops are updated.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | stopid      | StopId     | text      | number      |
| Yes      | series tag     | stopabbr    | StopAbbr   | text      | text        |
| Yes      | series tag     | stopname    | StopName   | text      | text        |
| Yes      | series tag     | onstreet    | OnStreet   | text      | text        |
| Yes      | series tag     | atstreet    | AtStreet   | text      | text        |
| Yes      | series tag     | tpfield00   | tpField00  | text      | text        |
| Yes      | numeric metric | inservice   | InService  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:uxtm-zebz d:2015-06-02T13:59:51.000Z t:tpfield00=MB t:onstreet="Spruce St" t:atstreet="Church St" t:stopname="SPRUCE ST & CHURCH ST" t:stopid=9168 t:stopabbr=SPRCHUN m:inservice=1

series e:uxtm-zebz d:2015-06-02T13:59:51.000Z t:tpfield00=FS t:onstreet="Pearl St" t:atstreet="Ann St" t:stopname="PEARL ST & ANN ST" t:stopid=7926 t:stopabbr=PEAANNE m:inservice=1

series e:uxtm-zebz d:2015-06-02T13:59:51.000Z t:tpfield00=NS t:onstreet="Pearl St" t:atstreet="Trumbull St" t:stopname="PEARL ST & TRUMBULL ST" t:stopid=7902 t:stopabbr=PEATRUE m:inservice=1
```

## Meta Commands

```ls
metric m:inservice p:integer l:InService t:dataTypeName=number

entity e:uxtm-zebz l:"CT Transit Bus Stops" t:attribution="CT Transit, Hartford Connecticut" t:url=https://data.hartford.gov/api/views/uxtm-zebz

property e:uxtm-zebz t:meta.view v:id=uxtm-zebz v:category=Community v:attributionLink=http://www.cttransit.com/ v:averageRating=0 v:name="CT Transit Bus Stops" v:attribution="CT Transit, Hartford Connecticut"

property e:uxtm-zebz t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:uxtm-zebz t:meta.view.owner v:id=vfc5-8d9r v:screenName=kberger v:displayName=kberger

property e:uxtm-zebz t:meta.view.tableauthor v:id=vfc5-8d9r v:screenName=kberger v:displayName=kberger
```

## Top Records

```ls
| :updated_at | stopid | stopabbr | stopname                       | onstreet       | atstreet       | tpfield00 | inservice | 
| =========== | ====== | ======== | ============================== | ============== | ============== | ========= | ========= | 
| 1433253591  | 9168   | SPRCHUN  | SPRUCE ST & CHURCH ST          | Spruce St      | Church St      | MB        | 1         | 
| 1433253591  | 7926   | PEAANNE  | PEARL ST & ANN ST              | Pearl St       | Ann St         | FS        | 1         | 
| 1433253591  | 7902   | PEATRUE  | PEARL ST & TRUMBULL ST         | Pearl St       | Trumbull St    | NS        | 1         | 
| 1433253591  | 7897   | PEALEWE  | PEARL ST & LEWIS ST            | Pearl St       | Lewis St       | NS        | 1         | 
| 1433253591  | 33     | CROWTRV  | CENTRAL ROW & TRAVELERS        | Central Row    | Travelers      | MB        | 1         | 
| 1433253591  | 9151   | CONCOLE  | CONVENTION CTR & COLUMBUS BLVD | Convention Ctr | Columbus Blvd  | PP        | 1         | 
| 1433253591  | 1073   | MAITRUMN | MAIN ST & TRUMBULL ST          | Main St        | Trumbull St    | FS        | 1         | 
| 1433253591  | 7609   | MAIELYN  | MAIN ST & ELY ST               | Main St        | Ely St         | NS        | 1         | 
| 1433253591  | 9651   | MAI1450N | MAIN ST & 1450 MAIN ST         | Main St        | 1450 MAIN ST   | FS        | 1         | 
| 1433253591  | 1074   | MAIFLON  | MAIN ST & OPP FLORENCE ST      | Main St        | OppFlorence St | MB        | 1         | 
```