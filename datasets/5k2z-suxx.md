# Relocated Vehicles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/relocated-vehicles-6b6b6) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/5k2z-suxx) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/5k2z-suxx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/5k2z-suxx/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 5k2z-suxx |
| Name | Relocated Vehicles |
| Attribution | City of Chicago |
| Category | Transportation |
| Tags | vehicles, streets |
| Created | 2011-09-30T08:00:22Z |
| Publication Date | 2016-06-10T19:43:13Z |

## Description

This dataset presents current and former locations of vehicles that have been relocated by the City of Chicago within the last 90 days. Vehicles may be relocated, but not impounded, due to inoperability, accident, severe weather, special events, construction or other work being performed in a thoroughfare where the vehicle was previously located.
Data Owner: Streets & Sanitation.
Time Period: Last 90 days.
Frequency: Data is updated daily.
Related Applications: Find Your Vehicle (http://j.mp/iZiX0B).

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | ============== | =============================== | =============================== | ============= | ============= |
| Yes      | time           | relocated_date                  | Relocated Date                  | calendar_date | calendar_date |
| Yes      | series tag     | make                            | Make                            | text          | text          |
| Yes      | series tag     | color                           | Color                           | text          | text          |
| Yes      | series tag     | plate                           | Plate                           | text          | text          |
| Yes      | series tag     | state                           | State                           | text          | text          |
| No       |                | relocated_from_address_number   | Relocated From Address Number   | text          | text          |
| Yes      | series tag     | relocated_from_street_direction | Relocated From Street Direction | text          | text          |
| Yes      | series tag     | relocated_from_street_name      | Relocated From Street Name      | text          | text          |
| Yes      | series tag     | relocated_from_suffix           | Relocated From Suffix           | text          | text          |
| No       |                | relocated_to_address_number     | Relocated To Address Number     | text          | text          |
| Yes      | series tag     | relocated_to_direction          | Relocated To Direction          | text          | text          |
| Yes      | series tag     | relocated_to_street_name        | Relocated To Street Name        | text          | text          |
| Yes      | series tag     | relocated_to_suffix             | Relocated To Suffix             | url           | url           |
| Yes      | series tag     | relocated_reason                | Relocated Reason                | text          | text          |
| Yes      | series tag     | service_request_number          | Service Request Number          | text          | text          |
| Yes      | numeric metric | relocated_from_x_coordinate     | Relocated From X Coordinate     | number        | number        |
| Yes      | numeric metric | relocated_from_y_coordinate     | Relocated From Y Coordinate     | number        | number        |
| No       |                | relocated_from_latitude         | Relocated From Latitude         | number        | number        |
| No       |                | relocated_from_longitude        | Relocated From Longitude        | number        | number        |
```

## Time Field

```ls
Value = relocated_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = relocated_from_address_number,relocated_to_address_number,relocated_from_latitude,relocated_from_longitude
```

## Data Commands

```ls
series e:5k2z-suxx d:2017-03-01T22:14:00.000Z t:relocated_from_suffix=DR t:color=Silver t:relocated_to_street_name=COLUMBUS t:relocated_from_street_name="LAKE SHORE" t:service_request_number=17-01145356 t:plate=S172350 t:state=Illinois t:relocated_reason=Stalled t:make=Toyota t:relocated_to_direction=S t:relocated_from_street_direction=S m:relocated_from_y_coordinate=1899084.92001433 m:relocated_from_x_coordinate=1179274.82033096

series e:5k2z-suxx d:2017-03-01T22:50:00.000Z t:relocated_from_suffix=DR t:color=Black t:relocated_to_street_name=HAYES t:relocated_from_street_name="LAKE SHORE" t:service_request_number=17-01146101 t:plate=AH25291 t:state=Illinois t:relocated_reason="Broken Down" t:make=Mazda t:relocated_to_direction=E t:relocated_from_street_direction=S m:relocated_from_y_coordinate=1863596.91509786 m:relocated_from_x_coordinate=1191149.88970347

series e:5k2z-suxx d:2017-03-01T00:00:00.000Z t:relocated_from_suffix=ST t:relocated_from_street_name=LAFLIN t:service_request_number=17-01146782 t:relocated_from_street_direction=S m:relocated_from_y_coordinate=1890835.56860452 m:relocated_from_x_coordinate=1166671.08891933
```

## Meta Commands

```ls
metric m:relocated_from_x_coordinate p:double l:"Relocated From X Coordinate" d:"The x coordinate of the location from which the vehicle was relocated, in State Plane Illinois East NAD 1983 projection." t:dataTypeName=number

metric m:relocated_from_y_coordinate p:double l:"Relocated From Y Coordinate" d:"The y coordinate of the location from which the vehicle was relocated, in State Plane Illinois East NAD 1983 projection." t:dataTypeName=number

entity e:5k2z-suxx l:"Relocated Vehicles" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/5k2z-suxx

property e:5k2z-suxx t:meta.view v:id=5k2z-suxx v:category=Transportation v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Relocated Vehicles" v:attribution="City of Chicago"

property e:5k2z-suxx t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:5k2z-suxx t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| relocated_date      | make       | color  | plate   | state    | relocated_from_address_number | relocated_from_street_direction | relocated_from_street_name | relocated_from_suffix | relocated_to_address_number | relocated_to_direction | relocated_to_street_name | relocated_to_suffix | relocated_reason     | service_request_number | relocated_from_x_coordinate | relocated_from_y_coordinate | relocated_from_latitude | relocated_from_longitude | 
| =================== | ========== | ====== | ======= | ======== | ============================= | =============================== | ========================== | ===================== | =========================== | ====================== | ======================== | =================== | ==================== | ====================== | =========================== | =========================== | ======================= | ======================== | 
| 2017-03-01T22:14:00 | Toyota     | Silver | S172350 | Illinois | 300.0                         | S                               | LAKE SHORE                 | DR                    | 100                         | S                      | COLUMBUS                 | [null, null]        | Stalled              | 17-01145356            | 1179274.82033096            | 1899084.92001433            | 41.878378993            | -87.617200464            | 
| 2017-03-01T22:50:00 | Mazda      | Black  | AH25291 | Illinois | 6245.0                        | S                               | LAKE SHORE                 | DR                    | 2159                        | E                      | HAYES                    | [null, null]        | Broken Down          | 17-01146101            | 1191149.88970347            | 1863596.91509786            | 41.780718003            | -87.574749296            | 
| 2017-03-01T00:00:00 |            |        |         |          | 1900.0                        | S                               | LAFLIN                     | ST                    |                             |                        |                          | [null, null]        |                      | 17-01146782            | 1166671.08891933            | 1890835.56860452            | 41.856021339            | -87.663714592            | 
| 2017-03-01T05:20:00 | Nissan     | Black  | S911380 | Illinois | 1900.0                        | S                               | LAFLIN                     | ST                    | 1518                        | W                      | 18TH ST                  | [null, null]        | Film Office          | 17-01146783            | 1166671.08891933            | 1890835.56860452            | 41.856021339            | -87.663714592            | 
| 2017-03-01T05:30:00 | Honda      | Gray   | 3692820 | Illinois | 1900.0                        | S                               | LAFLIN                     | ST                    | 1520                        | W                      | 18TH ST                  | [null, null]        | Film Office          | 17-01146784            | 1166671.08891933            | 1890835.56860452            | 41.856021339            | -87.663714592            | 
| 2017-03-01T09:15:00 | Toyota     | Silver | CDJ9045 | Texas    | 1015.0                        | W                               | AINSLIE                    | ST                    | 1017                        | W                      | AINSLIE                  | [null, null]        | CDOT Curb and Gutter | 17-01149975            | 1168580.55733344            | 1932959.64001225            | 41.97157114             | -87.655483925            | 
| 2017-03-01T10:30:00 | Nissan     | Black  | AG59780 | Illinois | 1700.0                        | S                               | LAKE SHORE                 | DR                    | 1800                        | S                      | LAKESHORE DR             | [null, null]        | Accident             | 17-01151995            | 1179383.17908427            | 1892058.0075987             | 41.859094268            | -87.617017899            | 
| 2017-03-01T01:39:00 | Volkswagen | Black  | H540534 | Illinois | 200.0                         | W                               | MADISON                    | ST                    | 323                         | E                      | LOWER WACKER             | [null, null]        | Accident             | 17-01145699            | 1174737.03080563            | 1900347.28937774            | 41.881945703            | -87.633824276            | 
| 2017-03-01T06:40:00 | Ford       | Black  | P244538 | Illinois | 2700.0                        | N                               | SB OUTER LAKE SHORE        | DR                    | 3760                        | N                      | RECREATION               | [null, null]        | Broken Down          | 17-01147685            | 1175050.22928761            | 1917782.59429502            | 41.929782001            | -87.6321509              | 
| 2017-03-01T07:30:00 | Chevrolet  | Silver | A780805 | Illinois | 1544.0                        | S                               | WASHTENAW                  | AVE                   | 1550                        | S                      | WASHTENAW                | [null, null]        | Forestry             | 17-01148227            | 1158620.5258925             | 1892233.54368806            | 41.860026012            | -87.693225968            | 
```