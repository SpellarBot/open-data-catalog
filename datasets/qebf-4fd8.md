# Rest Areas Across NY

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rest-areas-across-ny) |
| Metadata | [Link](https://data.ny.gov/api/views/qebf-4fd8) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/qebf-4fd8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/qebf-4fd8/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | qebf-4fd8 |
| Name | Rest Areas Across NY |
| Attribution | New York State Department of Transportation |
| Category | Transportation |
| Tags | rest areas |
| Created | 2013-02-26T22:40:18Z |
| Publication Date | 2016-02-05T15:38:00Z |

## Description

This data set contains the New York State Department of Transportation maintained rest areas across New York state.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | name               | Name               | text      | text        |
| Yes      | series tag     | description        | Description        | text      | text        |
| Yes      | numeric metric | vending_machine    | Vending Machine    | number    | number      |
| Yes      | numeric metric | picnictable        | PicnicTable        | number    | number      |
| Yes      | series tag     | public_phone       | Public Phone       | text      | number      |
| Yes      | series tag     | route              | Route              | text      | text        |
| Yes      | series tag     | status             | Status             | text      | text        |
| Yes      | series tag     | county             | County             | text      | text        |
| Yes      | series tag     | visitor_info       | Visitor Info       | text      | text        |
| Yes      | series tag     | nys_police         | NYS Police         | text      | text        |
| Yes      | numeric metric | car_spaces         | Car Spaces         | number    | number      |
| Yes      | numeric metric | truck_spaces       | Truck Spaces       | number    | number      |
| Yes      | numeric metric | bus_spaces         | Bus Spaces         | number    | number      |
| Yes      | numeric metric | handicapped_spaces | Handicapped Spaces | number    | number      |
| Yes      | series tag     | travel_direction   | Travel Direction   | text      | text        |
| No       |                | longitude          | Longitude          | number    | number      |
| No       |                | latitude           | Latitude           | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = longitude,latitude
```

## Data Commands

```ls
series e:qebf-4fd8 d:2016-02-05T07:37:10.000Z t:visitor_info=Yes t:county=Allegany t:status=Open t:description="Serving Westbound traffic on Interstate 86, between exits 24 adn 23 in the town of Allegany, Cattaraugus County.  The architecture reflects native American heritage, and within the enclosed lobby are interpretive historical displays." t:route=I-86 t:nys_police=Yes t:name="Allegany River" t:public_phone=1 m:vending_machine=6 m:handicapped_spaces=2 m:picnictable=-1 m:bus_spaces=2 m:truck_spaces=26 m:car_spaces=51

series e:qebf-4fd8 d:2016-02-05T07:37:10.000Z t:visitor_info=Unknown t:county=Westchester t:status=Open t:description="Serving southbound traffic on Interstate 684, between Exits 5 and 4, in the Town of Bedford, Westchester County." t:route=I-684 t:nys_police=No t:name=Bedford t:travel_direction=Southbound t:public_phone=-1 m:vending_machine=-1 m:handicapped_spaces=0 m:picnictable=-1 m:bus_spaces=0 m:truck_spaces=14 m:car_spaces=40

series e:qebf-4fd8 d:2016-02-05T07:37:10.000Z t:visitor_info=No t:county=Clinton t:status=Open t:description="Serving southbound traffic on I-87, also known as the Northway, between exits 41 and 40, in the town of Beekmantown, Clinton County." t:route=I-87 t:nys_police=No t:name=Beekmantown t:travel_direction=Southbound t:public_phone=-1 m:vending_machine=1 m:handicapped_spaces=3 m:picnictable=-1 m:bus_spaces=14 m:truck_spaces=14 m:car_spaces=36
```

## Meta Commands

```ls
metric m:vending_machine p:integer l:"Vending Machine" d:"Number of vending machines" t:dataTypeName=number

metric m:picnictable p:integer l:PicnicTable d:"Number of picnic tables" t:dataTypeName=number

metric m:car_spaces p:integer l:"Car Spaces" d:"Number of car parking spaces" t:dataTypeName=number

metric m:truck_spaces p:integer l:"Truck Spaces" d:"Number of truck parking spaces" t:dataTypeName=number

metric m:bus_spaces p:integer l:"Bus Spaces" d:"Number of bus parking spaces" t:dataTypeName=number

metric m:handicapped_spaces p:integer l:"Handicapped Spaces" d:"Number of handicapped parking spaces" t:dataTypeName=number

entity e:qebf-4fd8 l:"Rest Areas Across NY" t:attribution="New York State Department of Transportation" t:url=https://data.ny.gov/api/views/qebf-4fd8

property e:qebf-4fd8 t:meta.view v:id=qebf-4fd8 v:category=Transportation v:attributionLink=https://www.dot.ny.gov/regional-offices/statewide-rest-areas/ v:averageRating=0 v:name="Rest Areas Across NY" v:attribution="New York State Department of Transportation"

property e:qebf-4fd8 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:qebf-4fd8 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:qebf-4fd8 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | name            | description                                                                                                                                                                                                                              | vending_machine | picnictable | public_phone | route | status | county      | visitor_info | nys_police | car_spaces | truck_spaces | bus_spaces | handicapped_spaces | travel_direction | longitude    | latitude    | 
| =========== | =============== | ======================================================================================================================================================================================================================================== | =============== | =========== | ============ | ===== | ====== | =========== | ============ | ========== | ========== | ============ | ========== | ================== | ================ | ============ | =========== | 
| 1454657830  | Allegany River  | Serving Westbound traffic on Interstate 86, between exits 24 adn 23 in the town of Allegany, Cattaraugus County. The architecture reflects native American heritage, and within the enclosed lobby are interpretive historical displays. | 6               | -1          | 1            | I-86  | Open   | Allegany    | Yes          | Yes        | 51         | 26           | 2          | 2                  |                  | -78.53527417 | 42.09630333 | 
| 1454657830  | Bedford         | Serving southbound traffic on Interstate 684, between Exits 5 and 4, in the Town of Bedford, Westchester County.                                                                                                                         | -1              | -1          | -1           | I-684 | Open   | Westchester | Unknown      | No         | 40         | 14           | 0          | 0                  | Southbound       | -73.68159222 | 41.23109611 | 
| 1454657830  | Beekmantown     | Serving southbound traffic on I-87, also known as the Northway, between exits 41 and 40, in the town of Beekmantown, Clinton County.                                                                                                     | 1               | -1          | -1           | I-87  | Open   | Clinton     | No           | No         | 36         | 14           | 14         | 3                  | Southbound       | -73.44620694 | 44.807075   | 
| 1454657830  | Brewster        | Serving northbound traffic on Interstate 684, between Exits 8 and 9, in the Village of Brewster, Putnam County.                                                                                                                          | -1              | -1          | -1           | I-684 | Open   | Putnam      | Unknown      | No         | 40         | 14           | 0          | 0                  | Northbound       | -73.63141528 | 41.36120944 | 
| 1454657830  | Broome Gateway  | Serving northbound traffic on Interstate 81, between the Pennsylvania state line and exit 1, in the town of Kirkwood, Broome County.                                                                                                     | 7               | 15          | -1           | I-81  | Open   | Broome      | Yes          | Yes        | 76         | 29           | 5          | 5                  | Northbound       | -75.78027028 | 42.02113556 | 
| 1454657830  | Campbell        | Serving eastbound traffic on Interstate 86, between Exits 40 and 41, in the Town of Campbell, Steuben County.                                                                                                                            | -1              | -1          | -1           | I-86  | Open   | Steuben     | Yes          | No         | 43         | 12           | 0          | 2                  | Eastbound        | -77.19934417 | 42.24401583 | 
| 1454657830  | Chautauqua Lake | Serving eastbound traffic on Interstate 86, between exits 10 and 11, in the town of Ellery, Chautauqua County. The architecture showcases victorian style, and within the enclosed lobby are interpretive displays of the region.        | 6               | -1          | 1            | I-86  | Open   | Chautauqua  | Yes          | Yes        | -1         | -1           | -1         | -1                 | Eastbound        | -79.34887028 | 42.13464972 | 
| 1454657830  | Clifton Park    | Serving northbound traffic on Interstate 87, also known as the Northway, between exits 9 and 10, in the Town of Clifton Park, Saratoga County.                                                                                           | 6               | -1          | -1           | I-87  | Open   | Saratoga    | Yes          | Yes        | 92         | 28           | -1         | 3                  | Northbound       | -73.77683889 | 42.87749444 | 
| 1454657830  | Collins Landing | Serving Southbound traffic on Interstate 81, just over the Canadian Border, operated by the Thousand Island Bridge Authority                                                                                                             | 0               | 0           | 0            | I-81  | Open   |             |              |            | 0          | 0            | 0          | 0                  | Southbound       | -75.97566167 | 44.29576528 | 
| 1454657830  | East Branch     | Serving westbound traffic on Route 17, between Exits 90 and 89, in the Town of East Branch, Delaware County.                                                                                                                             | 0               | 0           | 0            | NY17  | Open   | Delaware    |              |            | 0          | 0            | 0          | 0                  | Westbound        | -75.16124972 | 41.99288194 | 
```