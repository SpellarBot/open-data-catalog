# Traffic Control Device Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/traffic-control-device-inventory) |
| Metadata | [Link](https://data.ny.gov/api/views/8fht-3ajj) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/8fht-3ajj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/8fht-3ajj/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 8fht-3ajj |
| Name | Traffic Control Device Inventory |
| Attribution | New York State Department of Transportation |
| Category | Transportation |
| Tags | traffic signal, traffic safety, traffic light, traffic signs |
| Created | 2014-10-01T11:28:10Z |
| Publication Date | 2016-02-02T17:30:59Z |

## Description

The New York State Department of Transportation (NYSDOT) traffic control devices data set is a list of all of the traffic devices that are either owned or maintained by NYSDOT. The devices included are of various types such as traffic signals, street lights, beacons, flashers, navigational lights, Intelligent Transportation Systems (ITS), etc.  Devices in the 5 boroughs of New York City are not owned or maintained by NYSDOT and therefore not represented in this dataset

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| No       | time           | :updated_at                | updated_at                 | meta_data | meta_data   |
| Yes      | series tag     | maintaining_region         | Maintaining Region         | text      | text        |
| Yes      | series tag     | owning_region              | Owning Region              | text      | text        |
| Yes      | series tag     | county                     | County                     | text      | text        |
| Yes      | series tag     | municipality               | Municipality               | text      | text        |
| Yes      | series tag     | device_number              | Device Number              | text      | text        |
| Yes      | series tag     | main_route                 | Main Route                 | text      | text        |
| Yes      | series tag     | intersecting_route         | Intersecting Route         | text      | text        |
| Yes      | series tag     | location                   | Location                   | text      | text        |
| Yes      | series tag     | device_type                | Device Type                | text      | text        |
| Yes      | series tag     | device_purpose             | Device Purpose             | text      | text        |
| Yes      | series tag     | device_priority            | Device Priority            | text      | text        |
| Yes      | series tag     | maintenance_responsibility | Maintenance Responsibility | text      | text        |
| Yes      | numeric metric | latitude_utm_y_meters      | Latitude (UTM Y [Meters])  | number    | number      |
| Yes      | numeric metric | longitude_utm_x_meters     | Longitude (UTM X [Meters]) | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8fht-3ajj d:2016-01-28T15:18:41.000Z t:device_number="260 L36" t:intersecting_route="US 020" t:device_priority="SELECTIVE RESPONSE 3" t:county=ALBANY t:location="Rte 9&20 Dunn Mamorial Bridge, BRIDGE LIGHTING L36 S side (also L1)" t:device_type="STREET LIGHT" t:maintaining_region="01 - Albany" t:owning_region="01 - Albany" t:municipality=RENSSELAER-CITY t:device_purpose="BRIDGE LIGHTING" t:main_route="US 009" t:maintenance_responsibility="STATE  RESPONSIBILITY (STATE OWNED SIGNAL - MAINTAINED BY STATE FORCES)" m:longitude_utm_x_meters=602752.6345 m:latitude_utm_y_meters=4721635.505

series e:8fht-3ajj d:2016-01-28T15:18:41.000Z t:device_number="260 L50" t:intersecting_route="US 020" t:device_priority="SELECTIVE RESPONSE 3" t:county=ALBANY t:location="Rte 9&20 Dunn Mamorial Bridge, BRIDGE LIGHTING L50 N side (also L1)" t:device_type="STREET LIGHT" t:maintaining_region="01 - Albany" t:owning_region="01 - Albany" t:municipality=RENSSELAER-CITY t:device_purpose="BRIDGE LIGHTING" t:main_route="US 009" t:maintenance_responsibility="STATE  RESPONSIBILITY (STATE OWNED SIGNAL - MAINTAINED BY STATE FORCES)" m:longitude_utm_x_meters=602752.6345 m:latitude_utm_y_meters=4721635.505

series e:8fht-3ajj d:2016-01-28T15:18:41.000Z t:device_number="260 L59" t:intersecting_route="US 020" t:device_priority="SELECTIVE RESPONSE 3" t:county=ALBANY t:location="Rte 9&20 Dunn Mamorial Bridge, BRIDGE LIGHTING L59 N side (also L1)" t:device_type="STREET LIGHT" t:maintaining_region="01 - Albany" t:owning_region="01 - Albany" t:municipality=RENSSELAER-CITY t:device_purpose="BRIDGE LIGHTING" t:main_route="US 009" t:maintenance_responsibility="STATE  RESPONSIBILITY (STATE OWNED SIGNAL - MAINTAINED BY STATE FORCES)" m:longitude_utm_x_meters=602752.6345 m:latitude_utm_y_meters=4721635.505
```

## Meta Commands

```ls
metric m:latitude_utm_y_meters p:double l:"Latitude (UTM Y [Meters])" d:"UTM X and UTM Y are the location coordinates in the Universal Transverse Mercator (UTM) coordinate system. Y-Coordinate (north-south). Each unit value equals one meter. Numbers become increasingly large to the north." t:dataTypeName=number

metric m:longitude_utm_x_meters p:double l:"Longitude (UTM X [Meters])" d:"UTM X and UTM Y are the location coordinates in the Universal Transverse Mercator (UTM) coordinate system. X-Coordinate (east-west). Each unit value equals one meter. Numbers become increasingly large to the east." t:dataTypeName=number

entity e:8fht-3ajj l:"Traffic Control Device Inventory" t:attribution="New York State Department of Transportation" t:url=https://data.ny.gov/api/views/8fht-3ajj

property e:8fht-3ajj t:meta.view v:id=8fht-3ajj v:category=Transportation v:attributionLink=https://www.dot.ny.gov/divisions/operating/oom/transportation-systems v:averageRating=0 v:name="Traffic Control Device Inventory" v:attribution="New York State Department of Transportation"

property e:8fht-3ajj t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:8fht-3ajj t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:8fht-3ajj t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | maintaining_region | owning_region | county | municipality       | device_number | main_route         | intersecting_route           | location                                                             | device_type       | device_purpose    | device_priority      | maintenance_responsibility                                             | latitude_utm_y_meters | longitude_utm_x_meters | 
| =========== | ================== | ============= | ====== | ================== | ============= | ================== | ============================ | ==================================================================== | ================= | ================= | ==================== | ====================================================================== | ===================== | ====================== | 
| 1453994321  | 01 - Albany        | 01 - Albany   | ALBANY | RENSSELAER-CITY    | 260 L36       | US 009             | US 020                       | Rte 9&20 Dunn Mamorial Bridge, BRIDGE LIGHTING L36 S side (also L1)  | STREET LIGHT      | BRIDGE LIGHTING   | SELECTIVE RESPONSE 3 | STATE RESPONSIBILITY (STATE OWNED SIGNAL - MAINTAINED BY STATE FORCES) | 4721635.505           | 602752.6345            | 
| 1453994321  | 01 - Albany        | 01 - Albany   | ALBANY | RENSSELAER-CITY    | 260 L50       | US 009             | US 020                       | Rte 9&20 Dunn Mamorial Bridge, BRIDGE LIGHTING L50 N side (also L1)  | STREET LIGHT      | BRIDGE LIGHTING   | SELECTIVE RESPONSE 3 | STATE RESPONSIBILITY (STATE OWNED SIGNAL - MAINTAINED BY STATE FORCES) | 4721635.505           | 602752.6345            | 
| 1453994321  | 01 - Albany        | 01 - Albany   | ALBANY | RENSSELAER-CITY    | 260 L59       | US 009             | US 020                       | Rte 9&20 Dunn Mamorial Bridge, BRIDGE LIGHTING L59 N side (also L1)  | STREET LIGHT      | BRIDGE LIGHTING   | SELECTIVE RESPONSE 3 | STATE RESPONSIBILITY (STATE OWNED SIGNAL - MAINTAINED BY STATE FORCES) | 4721635.505           | 602752.6345            | 
| 1453994321  | 01 - Albany        | 01 - Albany   | ALBANY | RENSSELAER-CITY    | 260 L71       | US 009             | US 020                       | Rte 9&20 Dunn Mamorial Bridge, BRIDGE LIGHTING L71 N side (also L1)  | STREET LIGHT      | BRIDGE LIGHTING   | SELECTIVE RESPONSE 3 | STATE RESPONSIBILITY (STATE OWNED SIGNAL - MAINTAINED BY STATE FORCES) | 4721635.505           | 602752.6345            | 
| 1453994321  | 01 - Albany        | 01 - Albany   | ALBANY | RENSSELAER-CITY    | 260 L86       | US 009             | US 020                       | Rte 9&20 Dunn Mamorial Bridge, BRIDGE LIGHTING L86 N side (also L1)  | STREET LIGHT      | BRIDGE LIGHTING   | SELECTIVE RESPONSE 3 | STATE RESPONSIBILITY (STATE OWNED SIGNAL - MAINTAINED BY STATE FORCES) | 4721635.505           | 602752.6345            | 
| 1453994321  | 01 - Albany        | 01 - Albany   | ALBANY | ALBANY-CITY        | 262 LU3       | Washington Ave Ext | Fuller Rd                    | Rte I90 @ Fuller Road UNDER BRIDGE LIGHTING LU3 (SE) 250W (also LU1) | STREET LIGHT      | BRIDGE LIGHTING   | SELECTIVE RESPONSE 3 | STATE RESPONSIBILITY (STATE OWNED SIGNAL - MAINTAINED BY STATE FORCES) | 4727497.731           | 595812.3136            | 
| 1453994321  | 01 - Albany        | 01 - Albany   | ALBANY | COLONIE-TOWN       | 266 L5        | NY 002             | NY 009                       | Rte 2 @ Rte 9 ROUND ABOUT LIGHTING L5 ENE 250W                       | STREET LIGHT      | ROUND ABOUT       | SELECTIVE RESPONSE 3 | STATE RESPONSIBILITY (STATE OWNED SIGNAL - MAINTAINED BY STATE FORCES) | 4733596.894           | 601441.3133            | 
| 1453994321  | 01 - Albany        | 01 - Albany   | ALBANY | ALBANY-CITY        | 32B           | I 087 SB           | I 087 SB Internally lit sign | I-Rte 87 SB Internally Lit Sign                                      | BEACON            | SIGN              | SELECTIVE RESPONSE 3 | STATE RESPONSIBILITY (STATE OWNED SIGNAL - MAINTAINED BY STATE FORCES) | 4728269.748           | 595406.288             | 
| 1453994321  | 01 - Albany        | 01 - Albany   | ALBANY | COHOES-CITY        | 6N            | NY 470             | 112th St Br Nav Lights       | Rte 470 @ 112 TH. STREET BR. NAVIGATION LIGHT                        | NAVIGATION LIGHTS | NAVIGATION LIGHTS | SELECTIVE RESPONSE 3 | STATE RESPONSIBILITY (STATE OWNED SIGNAL - MAINTAINED BY STATE FORCES) | 4736300.701           | 607860.7147            | 
| 1453994321  | 01 - Albany        | 01 - Albany   | ESSEX  | PORT HENRY-VILLAGE | 9B            | NY 009N            | Port Henry                   | Rte 9N SB @ PORT HENRY RM 1213                                       | BEACON            | SIGN              | SELECTIVE RESPONSE 3 | STATE RESPONSIBILITY (STATE OWNED SIGNAL - MAINTAINED BY STATE FORCES) | 4879224.941           | 623796.1093            | 
```