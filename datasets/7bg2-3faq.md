# Bicycle Routes Across New York State

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bicycle-routes-across-new-york-state) |
| Metadata | [Link](https://data.ny.gov/api/views/7bg2-3faq) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/7bg2-3faq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/7bg2-3faq/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 7bg2-3faq |
| Name | Bicycle Routes Across New York State |
| Attribution | NYSDOT Bicycle Routes |
| Category | Transportation |
| Tags | transportation, bicycle |
| Created | 2013-05-17T17:28:31Z |
| Publication Date | 2013-06-18T15:14:56Z |

## Description

Bicycle routes and recreational activities allowed on the route within New York State - https://www.dot.ny.gov/display/programs/bicycle. This list includes both on- and off-road bicycle routes and even includes information on surface type as well as other types of recreational activities allowed on the route.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name        | Data Type | Render Type |
| ======== | ============== | ================= | =========== | ========= | =========== |
| No       | time           | :updated_at       | updated_at  | meta_data | meta_data   |
| Yes      | series tag     | trail_name        | Name        | text      | text        |
| Yes      | series tag     | trail_description | Description | text      | text        |
| Yes      | numeric metric | trail_length      | Length      | number    | number      |
| Yes      | series tag     | biking            | Biking      | text      | text        |
| Yes      | series tag     | skiing            | Skiing      | text      | text        |
| Yes      | series tag     | horseriding       | Horseriding | text      | text        |
| Yes      | series tag     | skating           | Skating     | text      | text        |
| Yes      | series tag     | walking           | Walking     | text      | text        |
| Yes      | series tag     | atv               | ATV         | text      | text        |
| Yes      | series tag     | snowmobile        | Snowmobile  | text      | text        |
| Yes      | series tag     | trail_use         | Usage       | text      | text        |
| Yes      | series tag     | trail_highway     | Highway     | text      | text        |
| Yes      | series tag     | paved             | Paved       | text      | text        |
| Yes      | series tag     | gravel            | Gravel      | text      | text        |
| Yes      | series tag     | stone_dust        | Stone Dust  | text      | text        |
| Yes      | series tag     | dirt              | Dirt        | text      | text        |
| Yes      | series tag     | boardwalk         | Boardwalk   | text      | text        |
| Yes      | series tag     | surface_type      | SurfaceTyp  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7bg2-3faq d:2013-05-17T10:29:06.000Z t:horseriding=Y t:walking=Y t:biking=Y t:trail_use="Walking, Biking, Skating, Horse Riding" t:paved=Y t:trail_highway="Shoulder Lane" t:skating=Y t:surface_type=Paved t:trail_description="NY 65 Clover Street is signed as an on-road bicycle route for 8.1 miles from Mendon Ponds Park to East Avenue in the Town of Brighton" t:trail_name="NY 65 Clover Street BIcycle Route" m:trail_length=8.1

series e:7bg2-3faq d:2013-05-17T10:29:06.000Z t:biking=Y t:trail_use=Biking t:paved=Y t:trail_highway="Shoulder Lane" t:surface_type=Paved t:trail_description="The Lake Ontario State Parkway is a 35.05 mile parkway along the southern shore of Lake Ontario. The parkway has four travel lanes (two in each direction) with a six foot shoulder. The Parkway was opened for cycling in the early 1980's.   Its eastern ter" t:trail_name="Lake Ontario State Parkway" m:trail_length=35.05

series e:7bg2-3faq d:2013-05-17T10:29:06.000Z t:biking=Y t:trail_use=Biking t:paved=Y t:trail_highway="Shared Roadway" t:surface_type=Paved t:trail_description="NY 25 State Bike Route begins at the intersection of NY Route 25, NY Route 25A and NY Route 111, a half mile east of the Town of Smithtown central business district and it continues northeast along NY Route 25A and then diverts to local roads in St James" t:trail_name="State Bike Route 25" m:trail_length=67
```

## Meta Commands

```ls
metric m:trail_length p:double l:Length t:dataTypeName=number

entity e:7bg2-3faq l:"Bicycle Routes Across New York State" t:attribution="NYSDOT Bicycle Routes" t:url=https://data.ny.gov/api/views/7bg2-3faq

property e:7bg2-3faq t:meta.view v:id=7bg2-3faq v:category=Transportation v:attributionLink=https://www.dot.ny.gov/display/programs/bicycle v:averageRating=0 v:name="Bicycle Routes Across New York State" v:attribution="NYSDOT Bicycle Routes"

property e:7bg2-3faq t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:7bg2-3faq t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:7bg2-3faq t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | trail_name                        | trail_description                                                                                                                                                                                                                                              | trail_length | biking | skiing | horseriding | skating | walking | atv | snowmobile | trail_use                              | trail_highway  | paved | gravel | stone_dust | dirt | boardwalk | surface_type              | 
| =========== | ================================= | ============================================================================================================================================================================================================================================================== | ============ | ====== | ====== | =========== | ======= | ======= | === | ========== | ====================================== | ============== | ===== | ====== | ========== | ==== | ========= | ========================= | 
| 1368786546  | NY 65 Clover Street BIcycle Route | NY 65 Clover Street is signed as an on-road bicycle route for 8.1 miles from Mendon Ponds Park to East Avenue in the Town of Brighton                                                                                                                          | 8.1          | Y      |        | Y           | Y       | Y       |     |            | Walking, Biking, Skating, Horse Riding | Shoulder Lane  | Y     |        |            |      |           | Paved                     | 
| 1368786546  | Lake Ontario State Parkway        | The Lake Ontario State Parkway is a 35.05 mile parkway along the southern shore of Lake Ontario. The parkway has four travel lanes (two in each direction) with a six foot shoulder. The Parkway was opened for cycling in the early 1980's. Its eastern ter   | 35.05        | Y      |        |             |         |         |     |            | Biking                                 | Shoulder Lane  | Y     |        |            |      |           | Paved                     | 
| 1368786546  | State Bike Route 25               | NY 25 State Bike Route begins at the intersection of NY Route 25, NY Route 25A and NY Route 111, a half mile east of the Town of Smithtown central business district and it continues northeast along NY Route 25A and then diverts to local roads in St James | 67           | Y      |        |             |         |         |     |            | Biking                                 | Shared Roadway | Y     |        |            |      |           | Paved                     | 
| 1368786546  | State Bike Route 27               | State Bicycle Route 27 is a signed on-road bicycle route that extends 30 miles along the South Fork of eastern Long Island from Southampton Village to the historic Montauk Point Lighthouse. State Bicycle Route 27 connects with State Bicycle Route 114 in  | 30           | Y      |        |             |         |         |     |            | Biking                                 | Shared Roadway | Y     |        |            |      |           | Paved                     | 
| 1368786546  | Hempstead Lake State Park         | Hempstead Lake State Park is a multi use facility. Included are 20 tennis courts, children's playgrounds, basketball courts, bridle trails for horse back riding, biking and hiking trails, shaded picnic areas and a historic hand carved wooden carousel. Th | 3            | Y      | Y      | Y           |         | Y       |     |            | Walking, Biking, Horse Riding, Skiing  | Off Road       | Y     |        |            |      |           | Paved                     | 
| 1368786546  | US Route 11 and Black River Trail | The Black River Trail is a NY State Scenic Byway. The trail runs from Rome, through the tug hill plateau along the western edge of the Adirondacks, to Ogdensburg.                                                                                             |              | Y      | Y      | Y           | Y       | N       | N   | N          | Biking, Skating, Horse Riding, Skiing  | Shared Roadway | Y     | N      | N          | N    | N         | Paved                     | 
| 1368786546  | Olympic Trail                     | The Olympic Trail is a NY State Scenic Byway traversing the state from Sackets Harbor on Lake Ontario to Keeseville near Lake Champlain. The highlight of the route is Lake Placid which hosted the Winter Olympic Games in 1932 and 1980.                     | 170          | Y      | Y      | Y           | Y       |         |     |            | Biking, Skating, Horse Riding, Skiing  | Shared Roadway | Y     | Y      | Y          |      |           | Paved, Gravel, Stone Dust | 
| 1368786546  | Adirondack Trail                  | The Adirondack Trail is a NY State Scenic Byway. Running from the southern to the northern border of the Adirondacks, there are plenty of roadside views through the Adirondack Park.                                                                          | 188          | Y      | Y      | Y           | Y       |         |     |            | Biking, Skating, Horse Riding, Skiing  | Off Road       | Y     | Y      |            | Y    |           | Paved, Gravel, Dirt       | 
| 1368786546  | State Bike Route 19               | State Bicycle Route 19 is a signed, on-road bicycle route that extends 109 miles from the Pennsylvania state line near the Village of Shongo to Hamlin Beach State Park on the shores of Lake Ontario. This route intersects New York State Bicycle Routes 5   | 109          | Y      |        |             |         |         |     |            | Biking                                 | Shared Roadway | Y     |        |            |      |           | Paved                     | 
| 1368786546  | State Bike Route 14               | State Bicycle Route 14 is a signed, on-road bicycle route that extends 95 miles from the Pennsylvania state line near Elmira to Sodus Point on the shores of Lake Ontario. This route connects with Pennsylvania State Bicycle Route G. It also intersects N   | 95           | Y      |        |             |         |         |     |            | Biking                                 | Shared Roadway | Y     |        |            |      |           | Paved                     | 
```