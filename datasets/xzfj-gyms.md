# Bike Lanes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bike-lanes-8f886) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/xzfj-gyms) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/xzfj-gyms/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/xzfj-gyms/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | xzfj-gyms |
| Name | Bike Lanes |
| Attribution | Department of Transportation |
| Category | Transportation |
| Tags | bike lanes, bike, transportation |
| Created | 2012-03-26T12:30:23Z |
| Publication Date | 2014-04-03T23:40:10Z |

## Description

BikeBaltimore is the Department of Transportation??_??s bike program. Managed by the Planning Section, BikeBaltimore includes anything bike related including implementing the Bicycle Master Plan, incorporating cycling in many transportation projects, installing bike racks and coordinating cycling events. The Bicycle Master Plan was developed by the Department of Planning in 2006. With the implementation of the Bicycle Master Plan, more bike facilities are appearing on city streets. There are many different types of bike facilities. Bike Lane: an area designated for bike travel only. The bike lane is a 5??_?? wide lane with a bike symbol indicating that only bikes should use that lane, Sharrow: A roadway which is shared by bikes and automobiles. Cars should treat bikes as vehicles in the lane and pass when it is safe to do so, Signed Route: A roadway with no pavement markings, signed routes are used on low-traffic volume streets where cyclists can ??_??_??_take the lane??_??. Cars should pass bikes when it is safe to do so. Signed routes typically have mileage and destination markers with route adjustments along the way, Floating Bike Lane: Used along off-peak temporary parking, floating bike lanes adjust to the presence of parked cars. If parked cars are not present, cyclists occupy the 5??_?? bike lane along the curb. When parked cars are present, the cyclist travels in the designated area between the parked cars and vehicular travel lanes, Share The Road: When space does not exist for bike lanes, ??_??_??_SHARE THE ROAD??_?? signs are installed to remind motorists that cyclists may be present. Here cyclists are encouraged to use the shoulder of the road, or travel to the right while avoiding ??_??_??_door zones??_?? and roadside hazards, Shared Bus & Bike Lanes: On Pratt St, these lanes are only available to buses, bicycles and right turning vehicles

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | subtype       | subType       | text      | text        |
| Yes      | series tag     | name          | name          | text      | text        |
| Yes      | series tag     | block         | block         | text      | text        |
| Yes      | series tag     | type          | type          | text      | text        |
| Yes      | numeric metric | numlanes      | numLanes      | number    | number      |
| Yes      | series tag     | project       | project       | text      | text        |
| Yes      | series tag     | route         | route         | text      | text        |
| Yes      | numeric metric | length        | length        | number    | number      |
| Yes      | numeric metric | dateinstalled | dateInstalled | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:xzfj-gyms d:2013-04-05T10:38:17.000Z t:project="GUILFORD AVE BIKE BLVD" t:type="BIKE BOULEVARD" m:dateinstalled=0 m:numlanes=1 m:length=435.73787702

series e:xzfj-gyms d:2013-04-05T10:38:17.000Z t:route=NORTHERN t:type=SIDEPATH m:dateinstalled=2010 m:numlanes=1 m:length=1024.67462494

series e:xzfj-gyms d:2013-04-05T10:38:17.000Z t:project="SOUTHEAST BIKE NETWORK" t:type="SIGNED ROUTE" m:dateinstalled=2010 m:numlanes=1 m:length=3749.32263773
```

## Meta Commands

```ls
metric m:numlanes p:integer l:numLanes t:dataTypeName=number

metric m:length p:decimal l:length t:dataTypeName=number

metric m:dateinstalled p:integer l:dateInstalled t:dataTypeName=number

entity e:xzfj-gyms l:"Bike Lanes" t:attribution="Department of Transportation" t:url=https://data.baltimorecity.gov/api/views/xzfj-gyms

property e:xzfj-gyms t:meta.view v:id=xzfj-gyms v:category=Transportation v:attributionLink=http://www.baltimorecity.gov/Government/AgenciesDepartments/Transportation/Planning/BikeBaltimore.aspx v:averageRating=0 v:name="Bike Lanes" v:attribution="Department of Transportation"

property e:xzfj-gyms t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:xzfj-gyms t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:xzfj-gyms t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | subtype | name              | block                      | type           | numlanes | project                | route       | length             | dateinstalled | 
| =========== | ======= | ================= | ========================== | ============== | ======== | ====================== | =========== | ================== | ============= | 
| 1365158297  |         |                   |                            | BIKE BOULEVARD | 1        | GUILFORD AVE BIKE BLVD |             | 435.73787701999998 | 0             | 
| 1365158297  |         |                   |                            | SIDEPATH       | 1        |                        | NORTHERN    | 1024.6746249400001 | 2010          | 
| 1365158297  |         |                   |                            | SIGNED ROUTE   | 1        | SOUTHEAST BIKE NETWORK |             | 3749.3226377300002 | 2010          | 
| 1365158297  |         | HUNTINGDON PATH   |                            | SIDEPATH       | 1        |                        |             | 0                  | 0             | 
| 1365158297  | STCLN   | EDMONDSON AVE     | 5300 BLK EDMONDSON AVE     | BIKE LANE      | 1        | OPERATION ORANGE CONE  |             | 180.92546489       | 2011          | 
| 1365158297  | STRALY  | WINSTON-ROSSITER  | 1200 BLK WINSTON-ROSSITER  | SIGNED ROUTE   | 2        | COLLEGETOWN            | COLLEGETOWN | 147.97771557999999 | 2007          | 
| 1365158297  | STRALY  | WINSTON-ROSSITER  | 1200 BLK WINSTON-ROSSITER  | SIGNED ROUTE   | 2        | COLLEGETOWN            | COLLEGETOWN | 365.68471263999999 | 2007          | 
| 1365158297  | STRALY  | WINSTON-STONEWOOD | 1200 BLK WINSTON-STONEWOOD | SIGNED ROUTE   | 2        | COLLEGETOWN            | COLLEGETOWN | 262.37189461000003 | 2007          | 
| 1365158297  | STRPRD  |                   |                            | BIKE LANE      | 1        | MAINTENANCE            |             | 695.69831668999996 | 2009          | 
| 1365158297  | STRPRD  |                   |                            | SHARROW        | 1        | COLLEGETOWN            |             | 43.140832660000001 | 2007          | 
```