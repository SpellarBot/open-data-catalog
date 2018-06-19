# Land-rec-permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/land-rec-permits) |
| Metadata | [Link](https://data.mo.gov/api/views/njsj-885m) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/njsj-885m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/njsj-885m/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | njsj-885m |
| Name | Land-rec-permits |
| Category | Natural Resources |
| Created | 2015-07-01T20:55:18Z |
| Publication Date | 2017-03-24T16:06:51Z |

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | record_no          | Record No          | text      | text        |
| Yes      | series tag     | permitee_name      | Permitee Name      | text      | text        |
| Yes      | series tag     | permit_type        | Permit Type        | text      | text        |
| Yes      | series tag     | operator_names     | Operator Names     | text      | text        |
| Yes      | series tag     | permit_number      | Permit Number      | text      | text        |
| Yes      | series tag     | county_name        | County Name        | text      | text        |
| Yes      | series tag     | commodity          | Commodity          | text      | text        |
| Yes      | numeric metric | acres_net          | Acres Net          | number    | text        |
| Yes      | series tag     | status             | Status             | text      | text        |
| Yes      | time           | max_of_permit_year | Max Of Permit Year | number    | text        |
| Yes      | series tag     | site_number        | Site Number        | text      | text        |
| Yes      | series tag     | site_name          | Site Name          | text      | text        |
| Yes      | series tag     | section1           | Section1           | text      | text        |
| Yes      | series tag     | township1          | Township1          | text      | text        |
| Yes      | series tag     | range1             | Range1             | text      | text        |
| Yes      | series tag     | stream_name        | Stream Name        | text      | text        |
| Yes      | series tag     | onrw               | ONRW               | text      | text        |
| Yes      | series tag     | osrw               | OSRW               | text      | text        |
| Yes      | series tag     | phone              | Phone              | phone     | phone       |
| Yes      | series tag     | inspector          | Inspector          | text      | text        |
| Yes      | series tag     | area_number        | Area Number        | text      | text        |
| Yes      | series tag     | comments           | Comments           | text      | text        |
| Yes      | numeric metric | utmeasting         | UTMEasting         | number    | text        |
| Yes      | numeric metric | utmnorthing        | UTMNorthing        | number    | text        |
```

## Time Field

```ls
Value = max_of_permit_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:njsj-885m d:2015-01-01T00:00:00.000Z t:permit_type="Open Pit" t:phone_number=6306533700 t:status=Active t:township1=46N t:site_number=1 t:section1="23 26" t:site_name="Dresden Quarry" t:record_no=1616 t:range1=22W t:osrw=No t:permit_number=0001T t:onrw=No t:operator_names="Kevin Coughlin" t:commodity=Limestone t:permitee_name="Pettis County Properties Co., LC" t:county_name=Pettis t:area_number=1 m:acres_net=168.5 m:utmnorthing=4288856.60173 m:utmeasting=473504.751695

series e:njsj-885m d:2016-01-01T00:00:00.000Z t:permit_type="Open Pit" t:phone_number=6606794128 t:status=Active t:township1=38N t:site_number=2 t:section1=36 t:site_name="Osceola #79" t:record_no=1617 t:range1=25W t:osrw=No t:permit_number=0002 t:onrw=No t:operator_names="Jeff Burton" t:commodity=Limestone t:permitee_name="Ash Grove Aggregates Inc." t:county_name="St. Clair" t:area_number=2 m:acres_net=28 m:utmnorthing=4206637.84494 m:utmeasting=444226.395817

series e:njsj-885m d:2016-01-01T00:00:00.000Z t:permit_type="Open Pit" t:phone_number=6606794128 t:status=Active t:township1=37N t:site_number=3 t:section1="19 20 29" t:site_name="Wheatland #92" t:record_no=1618 t:range1=22W t:osrw=No t:permit_number=0002 t:onrw=No t:operator_names="Jeff Burton" t:commodity=Limestone t:permitee_name="Ash Grove Aggregates Inc." t:county_name=Hickory t:area_number=2 m:acres_net=61 m:utmnorthing=4199359.79653 m:utmeasting=466452.171614
```

## Meta Commands

```ls
metric m:acres_net p:integer l:"Acres Net" t:dataTypeName=number

metric m:utmeasting p:double l:UTMEasting t:dataTypeName=number

metric m:utmnorthing p:double l:UTMNorthing t:dataTypeName=number

entity e:njsj-885m l:Land-rec-permits t:url=https://data.mo.gov/api/views/njsj-885m

property e:njsj-885m t:meta.view v:id=njsj-885m v:category="Natural Resources" v:averageRating=0 v:name=Land-rec-permits

property e:njsj-885m t:meta.view.license v:name="Public Domain"

property e:njsj-885m t:meta.view.owner v:id=jzbz-iqr6 v:screenName=Breanna v:lastNotificationSeenAt=1492723347 v:displayName=Breanna

property e:njsj-885m t:meta.view.tableauthor v:id=jzbz-iqr6 v:screenName=Breanna v:roleName=administrator v:lastNotificationSeenAt=1492723347 v:displayName=Breanna
```

## Top Records

```ls
| record_no | permitee_name                    | permit_type | operator_names | permit_number | county_name | commodity | acres_net | status | max_of_permit_year | site_number | site_name                 | section1 | township1 | range1 | stream_name | onrw | osrw | phone              | inspector | area_number | comments | utmeasting    | utmnorthing   | 
| ========= | ================================ | =========== | ============== | ============= | =========== | ========= | ========= | ====== | ================== | =========== | ========================= | ======== | ========= | ====== | =========== | ==== | ==== | ================== | ========= | =========== | ======== | ============= | ============= | 
| 1616      | Pettis County Properties Co., LC | Open Pit    | Kevin Coughlin | 0001T         | Pettis      | Limestone | 168.5     | Active | 2015               | 1           | Dresden Quarry            | 23 26    | 46N       | 22W    |             | No   | No   | [6306533700, null] |           | 1           |          | 473504.751695 | 4288856.60173 | 
| 1617      | Ash Grove Aggregates Inc.        | Open Pit    | Jeff Burton    | 0002          | St. Clair   | Limestone | 28        | Active | 2016               | 2           | Osceola #79               | 36       | 38N       | 25W    |             | No   | No   | [6606794128, null] |           | 2           |          | 444226.395817 | 4206637.84494 | 
| 1618      | Ash Grove Aggregates Inc.        | Open Pit    | Jeff Burton    | 0002          | Hickory     | Limestone | 61        | Active | 2016               | 3           | Wheatland #92             | 19 20 29 | 37N       | 22W    |             | No   | No   | [6606794128, null] |           | 2           |          | 466452.171614 | 4199359.79653 | 
| 1619      | Ash Grove Aggregates Inc.        | Open Pit    | Jeff Burton    | 0002          | Cedar       | Limestone | 22        | Active | 2016               | 4           | Stockton #77              | 06       | 34N       | 26W    |             | No   | No   | [6606794128, null] |           | 2           |          | 426949.004337 | 4175150.14588 | 
| 1620      | Ash Grove Aggregates Inc.        | Open Pit    | Jeff Burton    | 0002          | Bates       | Limestone | 37        | Active | 2016               | 6           | Rich Hill #74, Craigmiles | 28       | 39N       | 32W    |             | No   | No   | [6606794128, null] |           | 2           |          | 373474.893    | 4221203.827   | 
| 1621      | Ash Grove Aggregates Inc.        | Open Pit    | Jeff Burton    | 0002          | Hickory     | Limestone | 13        | Active | 2016               | 7           | Pittsburg #94             | 36       | 36N       | 22W    |             | No   | No   | [6606794128, null] |           | 2           |          | 473307.055702 | 4186186.83818 | 
| 1622      | Ash Grove Aggregates Inc.        | Open Pit    | Jeff Burton    | 0002          | Vernon      | Limestone | 42        | Active | 2016               | 8           | Montevallo                | 05 06    | 34N       | 29W    |             | No   | No   | [6606794128, null] |           | 2           |          | 399499.025528 | 4177158.80486 | 
| 1623      | Ash Grove Aggregates Inc.        | Open Pit    | Jeff Burton    | 0002          | Webster     | Limestone | 57        | Active | 2016               | 9           | Marshfield #96            | 34       | 32N       | 18W    |             | No   | No   | [6606794128, null] |           | 2           |          | 508704.203063 | 4144011.09167 | 
| 1624      | Ash Grove Aggregates Inc.        | Open Pit    | Jeff Burton    | 0002          | Bates       | Limestone | 32        | Active | 2016               | 12          | Butler #71                | 19 20 30 | 40N       | 31W    |             | No   | No   | [6606794128, null] |           | 2           |          | 378330.43949  | 4234456.65666 | 
| 1625      | Ash Grove Aggregates Inc.        | Open Pit    | Jeff Burton    | 0002          | Dallas      | Limestone | 28        | Active | 2016               | 13          | Buffalo #93               | 29       | 34N       | 19W    |             | No   | No   | [6606794128, null] |           | 2           |          | 496020.928813 | 4165597.08933 | 
```