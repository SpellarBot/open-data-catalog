# Lodging Near NYS Canal System

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lodging-near-nys-canal-system) |
| Metadata | [Link](https://data.ny.gov/api/views/2xud-cuua) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/2xud-cuua/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/2xud-cuua/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 2xud-cuua |
| Name | Lodging Near NYS Canal System |
| Attribution | NYS Canal Corporation |
| Category | Transportation |
| Tags | nys canal, boating, hotel, motel, nys thruway |
| Created | 2014-04-22T19:49:32Z |
| Publication Date | 2015-11-19T21:25:02Z |

## Description

This dataset contains a listing of lodging available near the NYS Canal System

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | type               | Type               | text      | text        |
| Yes      | series tag     | body_of_water      | Body of Water      | text      | text        |
| Yes      | numeric metric | mile               | Mile               | number    | number      |
| Yes      | series tag     | shore              | Shore              | text      | text        |
| Yes      | series tag     | accomodation       | Accommodation      | text      | text        |
| Yes      | series tag     | accomodation_url   | Accommodation URL  | url       | url         |
| Yes      | series tag     | phone_number       | Phone number       | text      | text        |
| Yes      | series tag     | dock               | Dock               | text      | text        |
| Yes      | series tag     | dock_url           | Dock URL           | url       | url         |
| Yes      | series tag     | distance_from_dock | Distance from dock | text      | text        |
| No       |                | latitude           | Latitude           | number    | number      |
| No       |                | longitude          | Longitude          | number    | number      |
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
series e:2xud-cuua d:2015-11-19T13:23:31.000Z t:shore=east t:accomodation="Best Western" t:phone_number="(518) 274-8800" t:distance_from_dock="0.2 miles" t:body_of_water=hudson t:dock_url=http://www.downtowntroy.org/tourism-information/attractions-list/7-troy-dock.html t:type=lodging t:dock="Troy Downtown Marina" t:accomodation_url=http://bestwesternnewyork.com/hotels/best-western-plus-franklin-square-inn-troy-albany m:mile=155.9

series e:2xud-cuua d:2015-11-19T13:23:31.000Z t:shore=west t:accomodation="Schuyler Yacht Basin RV Park" t:phone_number="(518) 695-3193" t:distance_from_dock="200 feet" t:body_of_water=champlain t:type=camping t:dock="dedicated dock" t:accomodation_url=http://www.schuyleryachtbasin.com/ m:mile=25

series e:2xud-cuua d:2015-11-19T13:23:31.000Z t:shore=west t:accomodation="Dovegate Inn B&B" t:phone_number="(518) 695-3699" t:distance_from_dock="0.5 miles" t:body_of_water=champlain t:dock_url=http://www.schuyleryachtbasin.com/ t:type=lodging t:dock="Schuyler Yacht Basin" t:accomodation_url=http://www.dovegateinn.com/ m:mile=25
```

## Meta Commands

```ls
metric m:mile p:float l:Mile d:"Mile of lodging on the body of water" t:dataTypeName=number

entity e:2xud-cuua l:"Lodging Near NYS Canal System" t:attribution="NYS Canal Corporation" t:url=https://data.ny.gov/api/views/2xud-cuua

property e:2xud-cuua t:meta.view v:id=2xud-cuua v:category=Transportation v:attributionLink=http://www.canals.ny.gov/boating/lodging.cgi v:averageRating=0 v:name="Lodging Near NYS Canal System" v:attribution="NYS Canal Corporation"

property e:2xud-cuua t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:2xud-cuua t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:2xud-cuua t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | type    | body_of_water | mile               | shore | accomodation                 | accomodation_url                                                                               | phone_number   | dock                     | dock_url                                                                                  | distance_from_dock | latitude           | longitude           | 
| =========== | ======= | ============= | ================== | ===== | ============================ | ============================================================================================== | ============== | ======================== | ========================================================================================= | ================== | ================== | =================== | 
| 1447939411  | lodging | hudson        | 155.9              | east  | Best Western                 | [http://bestwesternnewyork.com/hotels/best-western-plus-franklin-square-inn-troy-albany, null] | (518) 274-8800 | Troy Downtown Marina     | [http://www.downtowntroy.org/tourism-information/attractions-list/7-troy-dock.html, null] | 0.2 miles          | 42.733857          | -73.688799000000003 | 
| 1447939411  | camping | champlain     | 25                 | west  | Schuyler Yacht Basin RV Park | [http://www.schuyleryachtbasin.com/, null]                                                     | (518) 695-3193 | dedicated dock           | [null, null]                                                                              | 200 feet           | 43.097099999999998 | -73.575230000000005 | 
| 1447939411  | lodging | champlain     | 25                 | west  | Dovegate Inn B&B             | [http://www.dovegateinn.com/, null]                                                            | (518) 695-3699 | Schuyler Yacht Basin     | [http://www.schuyleryachtbasin.com/, null]                                                | 0.5 miles          | 43.102764000000001 | -73.579868000000005 | 
| 1447939411  | lodging | champlain     | 25                 | west  | Old Saratoga Motor Inn       | [http://www.oldsaratogamotorinn.com/, null]                                                    | (518) 695-9997 | Schuyler Yacht Basin     | [http://www.schuyleryachtbasin.com/, null]                                                | 0.5 miles          | 43.102564000000001 | -73.580405999999996 | 
| 1447939411  | lodging | champlain     | 36.93              | east  | Historic Inn of Fort Edward  | [http://www.historicinnfe.com/, null]                                                          | (518) 747-0778 | Fort Edward Yacht Basin  | [http://www.fortedwardchamber.org/fort.edward.photo.tour/, null]                          | 0.3 miles          | 43.272514000000001 | -73.588437999999996 | 
| 1447939411  | lodging | erie          | 20.010000000000002 | north | The Waters Edge Lighthouse   | [http://www.thewatersedgelighthouse.com/lodging.php, null]                                     | (518) 370-5300 | dedicated dock           | [null, null]                                                                              | 100 feet           | 42.831780000000002 | -73.930291999999994 | 
| 1447939411  | lodging | erie          | 21.96              | north | Glen Sanders Mansion         | [http://www.glensandersmansion.com/, null]                                                     | (518) 374-7262 | dedicated dock           | [null, null]                                                                              | 150 feet           | 42.822110000000002 | -73.959464999999994 | 
| 1447939411  | camping | erie          | 26.06              | north | Arrowhead Marina & RV Park   | [http://www.arrowheadmrvp.com/, null]                                                          | (518) 382-8966 | dedicated dock           | [null, null]                                                                              | 200 feet           | 42.849155000000003 | -74.014728000000005 | 
| 1447939411  | lodging | erie          | 37.950000000000003 | north | Best Value Inn               | [null, null]                                                                                   | (518) 843-5760 | Amsterdam Riverlink Park | [http://www.riverlinkconcerts.com/, null]                                                 | 0.5 miles          | 42.938175000000001 | -74.193534          | 
| 1447939411  | lodging | erie          | 48.63              | north | Riverside Motel              | [null, null]                                                                                   | (518) 853-3314 | Fonda Wall               | [http://www.nycanals.com/Fonda_and_Fultonville, null]                                     | 0.3 miles          | 42.949461999999997 | -74.368329000000003 | 
```