# Iowa Physical and Cultural Geographic Features

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-physical-and-cultural-geographic-features) |
| Metadata | [Link](https://data.iowa.gov/api/views/uedc-2fk7) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/uedc-2fk7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/uedc-2fk7/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | uedc-2fk7 |
| Name | Iowa Physical and Cultural Geographic Features |
| Attribution | U.S. Geological Survey, Geographic Names Project, U.S. Geographic Names Information System (GNIS), Address: 523 National Center, Reston, VA 20192, Phone: 703-648-4552 |
| Category | Communities & People |
| Tags | airport, arch, area, bar, bay, beach, bend, bridge, building, canal, cape, cemetery, census, channel, church, civil, cliff, crossing, dam, falls, flat, forest, gut, harbor, hospital, island, lake,... |
| Created | 2015-08-03T20:38:06Z |
| Publication Date | 2015-08-04T13:59:28Z |

## Description

This dataset contains is a list of Iowa features contained in the Geographic Names Information System (GNIS).  The GNIS is the Federal standard for geographic nomenclature. The U.S. Geological Survey developed the GNIS for the U.S. Board on Geographic Names, a Federal inter-agency body chartered by public law to maintain uniform feature name usage throughout the Government and to promulgate standard names to the public. The GNIS is the official repository of domestic geographic names data; the official vehicle for geographic names use by all departments of the Federal Government; and the source for applying geographic names to Federal electronic and printed products of all types. See http://geonames.usgs.gov for additional information.  The Geographic Names Information System contains information about physical and cultural geographic features of all types, current and historical, but not including roads and highways. The database assigns a unique, permanent feature identifier, the Feature ID, as a standard Federal key for accessing, integrating, or reconciling feature data from multiple data sets. The GNIS collects data from a broad program of partnerships with Federal, State, and local government agencies and other authorized contributors.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name                | Data Type     | Render Type   |
| ======== | ============== | ============= | =================== | ============= | ============= |
| Yes      | series tag     | feature_id    | Feature ID          | text          | number        |
| Yes      | series tag     | feature_name  | Feature Name        | text          | text          |
| Yes      | series tag     | feature_class | Feature Class       | text          | text          |
| Yes      | series tag     | state_alpha   | Primary State       | text          | text          |
| Yes      | series tag     | county_name   | Primary County Name | text          | text          |
| Yes      | numeric metric | elev_in_m     | Elevation (Meters)  | number        | number        |
| Yes      | numeric metric | elev_in_ft    | Elevation (Feet)    | number        | number        |
| Yes      | series tag     | map_name      | USGS Map Name       | text          | text          |
| Yes      | time           | date_created  | Date Created        | calendar_date | calendar_date |
| No       |                | date_edited   | Date Edited         | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_created
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_edited
```

## Data Commands

```ls
series e:uedc-2fk7 d:1999-03-30T00:00:00.000Z t:feature_name="Saint Pauls Cemetery" t:feature_id=1822725 t:state_alpha=IA t:map_name=Whittemore t:county_name=Kossuth t:feature_class=Cemetery m:elev_in_m=363 m:elev_in_ft=1191

series e:uedc-2fk7 d:2001-03-27T00:00:00.000Z t:feature_name="Boyer Chute National Wildlife Refuge" t:feature_id=1897754 t:state_alpha=NE t:map_name=Loveland t:county_name=Washington t:feature_class=Park m:elev_in_m=302 m:elev_in_ft=991

series e:uedc-2fk7 d:2001-05-07T00:00:00.000Z t:feature_name="Lake Pahoja" t:feature_id=1906779 t:state_alpha=IA t:map_name=Larchwood t:county_name=Lyon t:feature_class=Reservoir m:elev_in_m=418 m:elev_in_ft=1371
```

## Meta Commands

```ls
metric m:elev_in_m p:integer l:"Elevation (Meters)" d:"The elevation in meters above sea level of the feature at the primary point (positive number) or depth of a feature at the lowest point below sea level (negative number). Elevation figures are not official and do not represent precisely measured or surveyed values. The data are extracted from the National Elevation Dataset (http://ned.usgs.gov/) for the primary coordinates and may differ from elevations cited in other sources. The differences will be most evident for features such as summits where precision is of more concern and where the local relief (rate of change of elevation) may be more prominent. However, the elevation figures are within tolerances for the data for most points and sufficiently accurate for purposes of general information." t:dataTypeName=number

metric m:elev_in_ft p:integer l:"Elevation (Feet)" d:"The elevation in feet above sea level of the feature at the primary point (positive number) or depth of a feature at the lowest point below sea level (negative number). Elevation figures are not official and do not represent precisely measured or surveyed values. The data are extracted from the National Elevation Dataset (http://ned.usgs.gov/) for the primary coordinates and may differ from elevations cited in other sources. The differences will be most evident for features such as summits where precision is of more concern and where the local relief (rate of change of elevation) may be more prominent. However, the elevation figures are within tolerances for the data for most points and sufficiently accurate for purposes of general information." t:dataTypeName=number

entity e:uedc-2fk7 l:"Iowa Physical and Cultural Geographic Features" t:attribution="U.S. Geological Survey, Geographic Names Project, U.S. Geographic Names Information System (GNIS), Address: 523 National Center, Reston, VA 20192, Phone: 703-648-4552" t:url=https://data.iowa.gov/api/views/uedc-2fk7

property e:uedc-2fk7 t:meta.view v:id=uedc-2fk7 v:category="Communities & People" v:attributionLink=http://geonames.usgs.gov/ v:averageRating=0 v:name="Iowa Physical and Cultural Geographic Features" v:attribution="U.S. Geological Survey, Geographic Names Project, U.S. Geographic Names Information System (GNIS), Address: 523 National Center, Reston, VA 20192, Phone: 703-648-4552"

property e:uedc-2fk7 t:meta.view.license v:name="Public Domain"

property e:uedc-2fk7 t:meta.view.owner v:id=hqmd-ehvn v:profileImageUrlMedium=/api/users/hqmd-ehvn/profile_images/THUMB v:profileImageUrlLarge=/api/users/hqmd-ehvn/profile_images/LARGE v:screenName="State Data Administrator" v:profileImageUrlSmall=/api/users/hqmd-ehvn/profile_images/TINY v:lastNotificationSeenAt=1492549701 v:displayName="State Data Administrator"

property e:uedc-2fk7 t:meta.view.tableauthor v:id=hqmd-ehvn v:profileImageUrlMedium=/api/users/hqmd-ehvn/profile_images/THUMB v:profileImageUrlLarge=/api/users/hqmd-ehvn/profile_images/LARGE v:screenName="State Data Administrator" v:profileImageUrlSmall=/api/users/hqmd-ehvn/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492549701 v:displayName="State Data Administrator"
```

## Top Records

```ls
| feature_id | feature_name                         | feature_class | state_alpha | county_name | elev_in_m | elev_in_ft | map_name    | date_created        | date_edited         | 
| ========== | ==================================== | ============= | =========== | =========== | ========= | ========== | =========== | =================== | =================== | 
| 1822725    | Saint Pauls Cemetery                 | Cemetery      | IA          | Kossuth     | 363       | 1191       | Whittemore  | 1999-03-30T00:00:00 | 2016-09-22T00:00:00 | 
| 1897754    | Boyer Chute National Wildlife Refuge | Park          | NE          | Washington  | 302       | 991        | Loveland    | 2001-03-27T00:00:00 | 2016-04-08T00:00:00 | 
| 1906779    | Lake Pahoja                          | Reservoir     | IA          | Lyon        | 418       | 1371       | Larchwood   | 2001-05-07T00:00:00 | 2016-05-31T00:00:00 | 
| 1907281    | Township of West Holman              | Civil         | IA          | Osceola     | 471       | 1545       | Sibley West | 2001-05-07T00:00:00 | 2016-03-08T00:00:00 | 
| 1906821    | Saint Josephs Catholic Cemetery      | Cemetery      | IA          | Plymouth    | 381       | 1250       | Le Mars     | 2001-05-07T00:00:00 | 2016-09-22T00:00:00 | 
| 1906876    | Seney City Cemetery                  | Cemetery      | IA          | Plymouth    | 378       | 1240       | Le Mars     | 2001-05-07T00:00:00 | 2016-09-22T00:00:00 | 
| 1906952    | Assumption Catholic Cemetery         | Cemetery      | IA          | Plymouth    | 396       | 1299       | Hinton      | 2001-05-07T00:00:00 | 2016-09-21T00:00:00 | 
| 1925415    | Havelock Cemetery                    | Cemetery      | IA          | Pocahontas  | 375       | 1230       | Havelock    | 2001-06-15T00:00:00 | 2016-09-22T00:00:00 | 
| 1926168    | Bode Memorial Park Cemetery          | Cemetery      | IA          | Humboldt    | 355       | 1165       | Bode        | 2001-06-15T00:00:00 | 2016-09-23T00:00:00 | 
| 1926184    | Hardy Trinity Lutheran Cemetery      | Cemetery      | IA          | Humboldt    | 347       | 1138       | Hardy       | 2001-06-15T00:00:00 | 2016-09-21T00:00:00 | 
```