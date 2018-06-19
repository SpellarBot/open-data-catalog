# Canal System Boat Launches Across New York State

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/canal-system-boat-launches-across-new-york-state) |
| Metadata | [Link](https://data.ny.gov/api/views/7nbx-apd3) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/7nbx-apd3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/7nbx-apd3/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 7nbx-apd3 |
| Name | Canal System Boat Launches Across New York State |
| Attribution | New York State Canal Corporation |
| Category | Transportation |
| Tags | canal, waterway, boat launch, erie canal, champlain canal, oswego canal, cayuga-seneca canal, glens falls feeder canal |
| Created | 2013-06-12T15:36:03Z |
| Publication Date | 2013-06-12T15:45:21Z |

## Description

The New York State Canal System is a 524 mile inland waterway that includes 125 public access points for placing a boat into the water, 74 of which are ramps for trailer-able boats. Information provided in this data set includes the name of the facility, the type of launch, if overnight parking of tow vehicles is permitted, and specific location by mileage along the canal, shore, and geographic coordinates.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | waterway          | Waterway          | text      | text        |
| Yes      | numeric metric | mile              | Mile              | number    | number      |
| Yes      | series tag     | shore             | Shore             | text      | text        |
| Yes      | series tag     | name              | Name              | text      | text        |
| Yes      | series tag     | launch_type       | Launch Type       | text      | text        |
| No       |                | latitude          | Latitude          | number    | number      |
| No       |                | longitude         | Longitude         | number    | number      |
| Yes      | series tag     | parking           | Parking           | text      | text        |
| Yes      | series tag     | overnight_parking | Overnight Parking | text      | text        |
| Yes      | series tag     | camping           | Camping           | text      | text        |
| Yes      | series tag     | day_use_amenities | Day Use Amenities | text      | text        |
| Yes      | series tag     | portage_distance  | Portage Distance  | text      | text        |
| Yes      | series tag     | potable_water     | Potable Water     | text      | text        |
| Yes      | series tag     | restrooms         | Restrooms         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:7nbx-apd3 d:2013-06-12T08:36:06.000Z t:shore=west t:parking="Cars (40)" t:portage_distance="525' +/-" t:potable_water=Yes t:camping=No t:launch_type="Car Top - Beach Landing" t:day_use_amenities="Picnicking, Pavilion, Hibachi, Walking Trails, Historic Interpretation, Fishing" t:name="Peebles Island State Park" t:waterway="Erie Canal" t:restrooms="Yes (Flush)" m:mile=0.22

series e:7nbx-apd3 d:2013-06-12T08:36:06.000Z t:shore=east t:parking="Cars (10) / Cars with Trailer (4)" t:potable_water=No t:camping=No t:launch_type=Ramp t:day_use_amenities=Fishing t:name="Lansingburg Boat Launch" t:waterway="Champlain Canal" t:restrooms=No m:mile=0.27

series e:7nbx-apd3 d:2013-06-12T08:36:06.000Z t:shore=east t:parking="Cars (2)" t:potable_water=No t:camping=No t:launch_type=Ramp t:day_use_amenities=Fishing t:name="Schaghticoke Boat Launch" t:waterway="Champlain Canal" t:restrooms=No m:mile=1.51
```

## Meta Commands

```ls
metric m:mile p:float l:Mile t:dataTypeName=number

entity e:7nbx-apd3 l:"Canal System Boat Launches Across New York State" t:attribution="New York State Canal Corporation" t:url=https://data.ny.gov/api/views/7nbx-apd3

property e:7nbx-apd3 t:meta.view v:id=7nbx-apd3 v:category=Transportation v:attributionLink=http://www.canals.ny.gov/boating/boatlaunches.cgi v:averageRating=0 v:name="Canal System Boat Launches Across New York State" v:attribution="New York State Canal Corporation"

property e:7nbx-apd3 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:7nbx-apd3 t:meta.view.tableauthor v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:7nbx-apd3 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | waterway        | mile  | shore | name                                 | launch_type             | latitude | longitude | parking                            | overnight_parking        | camping | day_use_amenities                                                               | portage_distance | potable_water | restrooms             | 
| =========== | =============== | ===== | ===== | ==================================== | ======================= | ======== | ========= | ================================== | ======================== | ======= | =============================================================================== | ================ | ============= | ===================== | 
| 1371026166  | Erie Canal      | 0.22  | west  | Peebles Island State Park            | Car Top - Beach Landing | 42.78437 | -73.67857 | Cars (40)                          |                          | No      | Picnicking, Pavilion, Hibachi, Walking Trails, Historic Interpretation, Fishing | 525' +/-         | Yes           | Yes (Flush)           | 
| 1371026166  | Champlain Canal | 0.27  | east  | Lansingburg Boat Launch              | Ramp                    | 42.78463 | -73.67440 | Cars (10) / Cars with Trailer (4)  |                          | No      | Fishing                                                                         |                  | No            | No                    | 
| 1371026166  | Champlain Canal | 1.51  | east  | Schaghticoke Boat Launch             | Ramp                    | 42.79946 | -73.66625 | Cars (2)                           |                          | No      | Fishing                                                                         |                  | No            | No                    | 
| 1371026166  | Champlain Canal | 3.55  | west  | Lock C1                              | Ramp                    | 42.82550 | -73.66519 | Cars (30) / Cars with Trailer (20) | Yes, call (518) 237-8566 | No      | Picnic, Fishing                                                                 |                  | No            | Yes (Portable toilet) | 
| 1371026166  | Champlain Canal | 4.55  | west  | Lighthouse Park                      | Car Top - Dock          | 42.83853 | -73.67151 | Cars (20)                          |                          | No      | Picnicking, Pavilion, Hibachi, Fishing, Canalway Trail                          | 200' +/-         | Yes           | Yes                   | 
| 1371026166  | Champlain Canal | 7.30  | west  | Lock C2, South of Hydro Facility     | Car Top - Beach Landing | 42.87656 | -73.67644 | Cars (5)                           |                          | No      | Fishing                                                                         | 50' +/-          | No            | No                    | 
| 1371026166  | Champlain Canal | 9.34  | west  | Mechanicville Canoe and Kayak Launch | Car Top - Dock          | 42.90451 | -73.68381 | Cars (15) / Cars with Trailer (5)  |                          | No      | Picnicking, Fishing                                                             | 20' +/-          | No            | No                    | 
| 1371026166  | Champlain Canal | 11.68 | west  | Lock C4, West Side, Below Lock       | Car Top - Beach Landing | 42.93156 | -73.65602 | Cars (5)                           |                          | No      | Picnicking, Hibachi, Fishing                                                    | 500' +/-         | No            | No                    | 
| 1371026166  | Champlain Canal | 20.37 | west  | Saratoga Informal Dirt Launch        | Ramp - Unpaved          | 43.03613 | -73.59223 | Cars (5) / Cars with Trailer (2)   |                          | No      | Fishing                                                                         |                  | No            | No                    | 
| 1371026166  | Champlain Canal | 25.20 | west  | Fort Hardy Park                      | Car Top - Beach Landing | 43.09910 | -73.57601 | Cars (15)                          |                          | No      | Picnicking, Hibachi, Gazebo, Pavilion, Fishing                                  | 150' +/-         | Yes           | Yes (Flush)           | 
```