# National Highway System

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/national-highway-system) |
| Metadata | [Link](https://data.iowa.gov/api/views/8fy6-cztc) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/8fy6-cztc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/8fy6-cztc/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 8fy6-cztc |
| Name | National Highway System |
| Attribution | Iowa Department of Transportation - Office of Research and Analytics |
| Category | Transportation & Utilities |
| Tags | nhs, network, road, route, transportation, lrs, fcc, national highway system, asset, classification, iowa dot, iowa department of transportation |
| Created | 2016-11-08T18:24:48Z |
| Publication Date | 2016-11-08T18:25:54Z |

## Description

Thematic map displaying the current National Highway System (NHS) for the centerline road segments in the State of Iowa.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type  | Render Type |
| ======== | ============== | ======================= | ======================= | ========== | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data  | meta_data   |
| No       |                | id                      | ID                      | text       | text        |
| Yes      | series tag     | routeid                 | ROUTEID                 | text       | text        |
| Yes      | numeric metric | frommeasure             | FROMMEASURE             | number     | number      |
| Yes      | numeric metric | tomeasure               | TOMEASURE               | number     | number      |
| Yes      | series tag     | county_number           | COUNTY_NUMBER           | text       | number      |
| Yes      | numeric metric | road_system             | ROAD_SYSTEM             | number     | number      |
| Yes      | series tag     | road_status             | ROAD_STATUS             | text       | number      |
| Yes      | series tag     | route_name              | ROUTE_NAME              | text       | text        |
| Yes      | series tag     | route_name_1            | ROUTE_NAME_1            | text       | text        |
| Yes      | series tag     | route_name_2            | ROUTE_NAME_2            | text       | text        |
| Yes      | series tag     | route_name_3            | ROUTE_NAME_3            | text       | text        |
| Yes      | series tag     | route_name_4            | ROUTE_NAME_4            | text       | text        |
| Yes      | numeric metric | h_and_t                 | H_AND_T                 | number     | number      |
| Yes      | series tag     | city_number             | CITY_NUMBER             | text       | number      |
| Yes      | series tag     | urban_area_code         | URBAN_AREA_CODE         | text       | number      |
| Yes      | series tag     | adjacent_city_number    | ADJACENT_CITY_NUMBER    | text       | number      |
| Yes      | series tag     | adjacent_county_number  | ADJACENT_COUNTY_NUMBER  | text       | number      |
| Yes      | numeric metric | toll_charged            | TOLL_CHARGED            | number     | number      |
| Yes      | numeric metric | fed_functional_class    | FED_FUNCTIONAL_CLASS    | number     | number      |
| Yes      | numeric metric | national_highway_system | NATIONAL_HIGHWAY_SYSTEM | number     | number      |
| Yes      | numeric metric | access_control          | ACCESS_CONTROL          | number     | number      |
| Yes      | series tag     | facility_type           | FACILITY_TYPE           | text       | number      |
| Yes      | series tag     | cost_group              | COST_GROUP              | text       | number      |
| Yes      | numeric metric | truck_route             | TRUCK_ROUTE             | number     | number      |
| Yes      | series tag     | highway_responsibility  | HIGHWAY_RESPONSIBILITY  | text       | text        |
| Yes      | numeric metric | commercial_network      | COMMERCIAL_NETWORK      | number     | number      |
| Yes      | numeric metric | planning_class          | PLANNING_CLASS          | number     | number      |
| Yes      | series tag     | median_type             | MEDIAN_TYPE             | text       | number      |
| Yes      | numeric metric | median_width            | MEDIAN_WIDTH            | number     | number      |
| Yes      | numeric metric | number_lanes            | NUMBER_LANES            | number     | number      |
| Yes      | series tag     | lane_type               | LANE_TYPE               | text       | text        |
| Yes      | series tag     | lane_position           | LANE_POSITION           | text       | text        |
| Yes      | series tag     | lane_type_1             | LANE_TYPE_1             | text       | text        |
| Yes      | series tag     | lane_position_1         | LANE_POSITION_1         | text       | text        |
| Yes      | series tag     | lane_type_2             | LANE_TYPE_2             | text       | text        |
| Yes      | series tag     | lane_position_2         | LANE_POSITION_2         | text       | text        |
| Yes      | series tag     | lane_type_3             | LANE_TYPE_3             | text       | text        |
| Yes      | series tag     | lane_position_3         | LANE_POSITION_3         | text       | text        |
| Yes      | series tag     | lane_type_4             | LANE_TYPE_4             | text       | text        |
| Yes      | series tag     | lane_position_4         | LANE_POSITION_4         | text       | text        |
| Yes      | series tag     | lane_type_5             | LANE_TYPE_5             | text       | text        |
| Yes      | series tag     | lane_position_5         | LANE_POSITION_5         | text       | text        |
| Yes      | series tag     | lane_type_6             | LANE_TYPE_6             | text       | text        |
| Yes      | series tag     | lane_position_6         | LANE_POSITION_6         | text       | text        |
| Yes      | series tag     | lane_type_7             | LANE_TYPE_7             | text       | text        |
| Yes      | series tag     | lane_position_7         | LANE_POSITION_7         | text       | text        |
| Yes      | series tag     | lane_type_8             | LANE_TYPE_8             | text       | text        |
| Yes      | series tag     | lane_position_8         | LANE_POSITION_8         | text       | text        |
| Yes      | series tag     | county_name             | COUNTY_NAME             | text       | text        |
| Yes      | numeric metric | shape_len               | SHAPE.LEN               | number     | number      |
| Yes      | series tag     | objectid                | OBJECTID                | text       | number      |
| No       |                | shape                   | SHAPE                   | geospatial | geospatial  |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id,shape
```

## Data Commands

```ls
series e:8fy6-cztc d:2016-11-08T18:24:48.000Z t:shape.longitude=-96.41688487899995 t:county_number=97 t:facility_type=6 t:city_number=7057 t:route_name_2="CITY OF SIOUX CITY, HAMILTON BOULEVARD, S" t:road_status=0 t:urban_area_code=156 t:median_type=5 t:routeid=M705741425S t:shape.needs_recoding=false t:shape.latitude=42.51325101600003 t:objectid=65 t:county_name=Woodbury t:cost_group=2 m:frommeasure=3.689324 m:road_system=2 m:h_and_t=2 m:tomeasure=3.68933 m:median_width=4 m:national_highway_system=1 m:fed_functional_class=3

series e:8fy6-cztc d:2016-11-08T18:24:48.000Z t:shape.longitude=-96.41857099099997 t:lane_type=1 t:county_number=97 t:facility_type=6 t:lane_position_1=2 t:city_number=7057 t:route_name_2="CITY OF SIOUX CITY, HAMILTON BOULEVARD, S" t:lane_type_1=1 t:road_status=0 t:urban_area_code=156 t:median_type=1 t:routeid=M705741425S t:shape.needs_recoding=false t:shape.latitude=42.503269733000025 t:objectid=67 t:county_name=Woodbury t:lane_position=1 t:cost_group=2 m:frommeasure=4.4047529999999995 m:road_system=2 m:h_and_t=2 m:tomeasure=4.462664 m:median_width=4 m:national_highway_system=1 m:fed_functional_class=3 m:number_lanes=2

series e:8fy6-cztc d:2016-11-08T18:24:48.000Z t:shape.longitude=-96.41688821099996 t:lane_type=1 t:county_number=97 t:lane_position_2=3 t:lane_position_1=2 t:facility_type=6 t:city_number=7057 t:route_name_2="CITY OF SIOUX CITY, HAMILTON BOULEVARD, S" t:lane_type_1=1 t:road_status=0 t:urban_area_code=156 t:lane_type_2=4 t:median_type=5 t:routeid=M705741425S t:shape.needs_recoding=false t:shape.latitude=42.513716198000054 t:objectid=69 t:county_name=Woodbury t:lane_position=1 t:cost_group=2 m:frommeasure=3.6572259999999996 m:road_system=2 m:h_and_t=2 m:tomeasure=3.689324 m:median_width=4 m:national_highway_system=1 m:fed_functional_class=3 m:number_lanes=3
```

## Meta Commands

```ls
metric m:frommeasure p:long l:FROMMEASURE d:"From Measure" t:dataTypeName=number

metric m:tomeasure p:long l:TOMEASURE d:"To Measure" t:dataTypeName=number

metric m:road_system p:long l:ROAD_SYSTEM d:"Road System" t:dataTypeName=number

metric m:h_and_t p:long l:H_AND_T d:"H and T" t:dataTypeName=number

metric m:toll_charged p:long l:TOLL_CHARGED d:"Toll Charged" t:dataTypeName=number

metric m:fed_functional_class p:long l:FED_FUNCTIONAL_CLASS d:"Federal Functional Class" t:dataTypeName=number

metric m:national_highway_system p:long l:NATIONAL_HIGHWAY_SYSTEM d:"National Highway System" t:dataTypeName=number

metric m:access_control p:long l:ACCESS_CONTROL d:"Access Control" t:dataTypeName=number

metric m:truck_route p:long l:TRUCK_ROUTE d:"Truck Route" t:dataTypeName=number

metric m:commercial_network p:long l:COMMERCIAL_NETWORK d:"Commercial Network" t:dataTypeName=number

metric m:planning_class p:long l:PLANNING_CLASS d:"Planning Class" t:dataTypeName=number

metric m:median_width p:long l:MEDIAN_WIDTH d:"Median Width" t:dataTypeName=number

metric m:number_lanes p:long l:NUMBER_LANES d:"Number of Lanes" t:dataTypeName=number

metric m:shape_len p:long l:SHAPE.LEN d:"Length (Meter)" t:dataTypeName=number

entity e:8fy6-cztc l:"National Highway System" t:attribution="Iowa Department of Transportation - Office of Research and Analytics" t:url=https://data.iowa.gov/api/views/8fy6-cztc

property e:8fy6-cztc t:meta.view v:id=8fy6-cztc v:category="Transportation & Utilities" v:averageRating=0 v:name="National Highway System" v:attribution="Iowa Department of Transportation - Office of Research and Analytics"

property e:8fy6-cztc t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:8fy6-cztc t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | id                                   | routeid     | frommeasure                                          | tomeasure                                             | county_number | road_system | road_status | route_name | route_name_1 | route_name_2                              | route_name_3 | route_name_4 | h_and_t | city_number | urban_area_code | adjacent_city_number | adjacent_county_number | toll_charged | fed_functional_class | national_highway_system | access_control | facility_type | cost_group | truck_route | highway_responsibility | commercial_network | planning_class | median_type | median_width | number_lanes | lane_type | lane_position | lane_type_1 | lane_position_1 | lane_type_2 | lane_position_2 | lane_type_3 | lane_position_3 | lane_type_4 | lane_position_4 | lane_type_5 | lane_position_5 | lane_type_6 | lane_position_6 | lane_type_7 | lane_position_7 | lane_type_8 | lane_position_8 | county_name | shape_len | objectid | shape                                                                                                                                                                                                                                                                                                                                                                                                                                                       | 
| =========== | ==================================== | =========== | ==================================================== | ===================================================== | ============= | =========== | =========== | ========== | ============ | ========================================= | ============ | ============ | ======= | =========== | =============== | ==================== | ====================== | ============ | ==================== | ======================= | ============== | ============= | ========== | =========== | ====================== | ================== | ============== | =========== | ============ | ============ | ========= | ============= | =========== | =============== | =========== | =============== | =========== | =============== | =========== | =============== | =========== | =============== | =========== | =============== | =========== | =============== | =========== | =============== | =========== | ========= | ======== | =========================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 0           | 85cb7693-1f68-4b30-89c7-d7ab9573206e | M705741425S | 3.68932400000000004780531526193954050540924072265625 | 3.6893299999999999982946974341757595539093017578125   | 97            | 2           | 0           |            |              | CITY OF SIOUX CITY, HAMILTON BOULEVARD, S |              |              | 2       | 7057        | 156             |                      |                        |              | 3                    | 1                       |                | 6             | 2          |             |                        |                    |                | 5           | 4            |              |           |               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Woodbury    |           | 65       | [null, 42.51325101600003, -96.41688487899995, null, false, {paths=[[[-96.41688487899995, 42.51325101600003], [-96.41688487999994, 42.51325092800005]]]}]                                                                                                                                                                                                                                                                                                    | 
| 0           | 60036191-05ed-4783-ba21-5edbaeacf181 | M705741425S | 4.404752999999999474312062375247478485107421875      | 4.462664000000000186219040188007056713104248046875    | 97            | 2           | 0           |            |              | CITY OF SIOUX CITY, HAMILTON BOULEVARD, S |              |              | 2       | 7057        | 156             |                      |                        |              | 3                    | 1                       |                | 6             | 2          |             |                        |                    |                | 1           | 4            | 2            | 1         | 1             | 1           | 2               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Woodbury    |           | 67       | [null, 42.503269733000025, -96.41857099099997, null, false, {paths=[[[-96.41857099099997, 42.503269733000025], [-96.41872290799995, 42.503086093000036], [-96.41888780199997, 42.50288882000007], [-96.41896893299997, 42.502761607000025], [-96.41904024399997, 42.50263106500006], [-96.41909484299998, 42.50252814300006]]]}]                                                                                                                            | 
| 0           | b22e2e3a-7050-4bd1-975c-7aaa03bd1159 | M705741425S | 3.6572259999999996438191374181769788265228271484375  | 3.68932400000000004780531526193954050540924072265625  | 97            | 2           | 0           |            |              | CITY OF SIOUX CITY, HAMILTON BOULEVARD, S |              |              | 2       | 7057        | 156             |                      |                        |              | 3                    | 1                       |                | 6             | 2          |             |                        |                    |                | 5           | 4            | 3            | 1         | 1             | 1           | 2               | 4           | 3               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Woodbury    |           | 69       | [null, 42.513716198000054, -96.41688821099996, null, false, {paths=[[[-96.41688821099996, 42.513716198000054], [-96.41688535999998, 42.51355691200007], [-96.41688487899995, 42.51325101600003]]]}]                                                                                                                                                                                                                                                         | 
| 0           | 44dbaf6d-98a0-488e-adff-7c1e08bdcfd9 | M705741425S | 4.023483999999999838337316759862005710601806640625   | 4.07489599999999985158183335443027317523956298828125  | 97            | 2           | 0           |            |              | CITY OF SIOUX CITY, HAMILTON BOULEVARD, S |              |              | 2       | 7057        | 156             |                      |                        |              | 3                    | 1                       |                | 6             | 2          |             |                        |                    |                | 5           | 4            | 2            | 1         | 1             | 1           | 2               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Woodbury    |           | 73       | [null, 42.508408548000034, -96.41679877099995, null, false, {paths=[[[-96.41679877099995, 42.508408548000034], [-96.41678667099995, 42.507952009000064], [-96.41677338999995, 42.50766369000007]]]}]                                                                                                                                                                                                                                                        | 
| 0           | fd072edf-d024-4525-bc19-e8056f2ad9f6 | M705741425S | 2.78817000000000003723243935382924973964691162109375 | 2.924348999999999865195832171593792736530303955078125 | 97            | 2           | 0           |            |              | CITY OF SIOUX CITY, HAMILTON BOULEVARD, S |              |              | 2       | 7057        | 156             |                      |                        |              | 3                    | 1                       |                | 6             | 2          |             |                        |                    |                | 1           | 4            | 2            | 1         | 1             | 1           | 2               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Woodbury    |           | 75       | [null, 42.52563758600007, -96.41532076399994, null, false, {paths=[[[-96.41532076399994, 42.52563758600007], [-96.41532741299994, 42.525633405000065], [-96.41565320199999, 42.52542854100005], [-96.41586892399994, 42.52528363500005], [-96.41603218399996, 42.525154357000076], [-96.41618946199998, 42.525000195000075], [-96.41638257499994, 42.52478433700003], [-96.41682465999997, 42.52420101200005], [-96.41691431999999, 42.524080293000054]]]}] | 
| 0           | 2e8b4a0e-970b-4323-b4de-8e768369f512 | M705741425S | 4.21153699999999986403054208494722843170166015625    | 4.25199999999999977973175191436894237995147705078125  | 97            | 2           | 0           |            |              | CITY OF SIOUX CITY, HAMILTON BOULEVARD, S |              |              | 2       | 7057        | 156             |                      |                        |              | 3                    | 1                       |                | 6             | 2          |             |                        |                    |                | 5           | 4            | 3            | 1         | 1             | 1           | 2               | 4           | 3               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Woodbury    |           | 76       | [null, 42.505683917000056, -96.41671442599994, null, false, {paths=[[[-96.41671442599994, 42.505683917000056], [-96.41671351899998, 42.50562935800008], [-96.41675005599996, 42.50547824000006], [-96.41679789399996, 42.505362597000044], [-96.41688402299997, 42.50523883500006], [-96.41696263499995, 42.50513593200003]]]}]                                                                                                                             | 
| 0           | 3b7aa2b5-2d6b-4e3d-b838-45fe79495796 | M705741425S | 3.61979600000000001358557710773311555385589599609375 | 3.6572259999999996438191374181769788265228271484375   | 97            | 2           | 0           |            |              | CITY OF SIOUX CITY, HAMILTON BOULEVARD, S |              |              | 2       | 7057        | 156             |                      |                        |              | 3                    | 1                       |                | 6             | 2          |             |                        |                    |                | 5           | 4            | 2            | 1         | 1             | 1           | 2               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Woodbury    |           | 78       | [null, 42.51425862200006, -96.41689791699997, null, false, {paths=[[[-96.41689791699997, 42.51425862200006], [-96.41689788099995, 42.51425664000004], [-96.41688821099996, 42.513716198000054]]]}]                                                                                                                                                                                                                                                          | 
| 0           | cab7aabb-f94b-457c-8c26-da1b0ff9f669 | M705741425S | 3.82914699999999985635668053873814642429351806640625 | 3.874143999999999810057715876610018312931060791015625 | 97            | 2           | 0           |            |              | CITY OF SIOUX CITY, HAMILTON BOULEVARD, S |              |              | 2       | 7057        | 156             |                      |                        |              | 3                    | 1                       |                | 6             | 2          |             |                        |                    |                | 1           | 4            | 3            | 1         | 1             | 1           | 2               | 4           | 3               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Woodbury    |           | 82       | [null, 42.51122473700008, -96.41685505599997, null, false, {paths=[[[-96.41685505599997, 42.51122473700008], [-96.41685339999998, 42.51107945200005], [-96.41684626199998, 42.51060173800005], [-96.41684582799996, 42.51057263300004]]]}]                                                                                                                                                                                                                  | 
| 0           | 950637e9-d07f-4d56-b8ac-7a4756541ade | M705741425S | 5.08784399999999958907892505521886050701141357421875 | 5.14978399999999947311835057917051017284393310546875  | 97            | 2           | 0           |            |              | CITY OF SIOUX CITY, HAMILTON BOULEVARD, S |              |              | 2       | 7057        | 156             |                      |                        |              | 3                    | 1                       |                | 6             | 2          |             |                        |                    |                | 1           | 4            | 2            | 1         | 1             | 1           | 2               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Woodbury    |           | 85       | [null, 42.49446505000003, -96.42430592999995, null, false, {paths=[[[-96.42430592999995, 42.49446505000003], [-96.42431646999995, 42.49441918500003], [-96.42436547999995, 42.49420592100006], [-96.42447967999999, 42.49374885900005], [-96.42451336899995, 42.49358065600006]]]}]                                                                                                                                                                         | 
| 0           | 36f47ec1-b3fa-419d-b237-7a4e9b36848f | M705741425S | 3.58780099999999979587528287083841860294342041015625 | 3.61979600000000001358557710773311555385589599609375  | 97            | 2           | 0           |            |              | CITY OF SIOUX CITY, HAMILTON BOULEVARD, S |              |              | 2       | 7057        | 156             |                      |                        |              | 3                    | 1                       |                | 6             | 2          |             |                        |                    |                | 5           | 4            | 3            | 1         | 1             | 1           | 2               | 4           | 3               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Woodbury    |           | 87       | [null, 42.51472228400007, -96.41690621399994, null, false, {paths=[[[-96.41690621399994, 42.51472228400007], [-96.41689791699997, 42.51425862200006]]]}]                                                                                                                                                                                                                                                                                                    | 
```