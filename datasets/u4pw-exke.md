# Network - Commercial and Industrial

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/network-commercial-and-industrial) |
| Metadata | [Link](https://data.iowa.gov/api/views/u4pw-exke) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/u4pw-exke/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/u4pw-exke/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | u4pw-exke |
| Name | Network - Commercial and Industrial |
| Attribution | Iowa Department of Transportation - Office of Research and Analytics |
| Category | Transportation & Utilities |
| Tags | nhs, network, road, route, transportation, lrs, fcc, commercial, industrial, asset, classification, iowa dot, iowa department of transportation |
| Created | 2016-11-08T18:04:10Z |
| Publication Date | 2016-11-08T18:08:27Z |

## Description

Commercial and Industrial Network information for the centerline road segments in the State of Iowa.

1. Purpose.  It is the purpose of this section to enhance opportunities for the development and diversification of the state’s economy through the identification and improvement of a network of commercial and industrial highways.  The network shall consist of interconnected routes which provide long distance route continuity.  The purpose of this highway network shall be to improve the flow of commerce; to make travel more convenient, safe, and efficient; and to better connect Iowa with regional, national, and international markets.  The commission shall concentrate a major portion of its annual construction budget on this network of commercial and industrial highways.  In order to ensure the greatest possible availability of funds for the improvement of the network, primary highway funds shall not be spent beyond continuing maintenance for improvements to route segments that will be bypassed by the relocation of portions of the commercial and industrial highway network.
	
2. Network selection.
a. The commission shall identify, within the primary road system, a network of commercial and industrial highways.  The commission shall consider all of the following factors in the identification of this network:

i. The connection by the most direct routes feasible of major urban areas and regions of the state to each other and to the national system of interstate and defense highways and priority routes in adjacent states.
ii. The existence of high volumes of total traffic and commercial traffic.
iii. Long distance traffic movements.
iv. Area coverage and balance of spacing with service to major growth centers within the state.
v. Metropolitan area bypasses consistent with metropolitan or regional area plans established through cooperation by the department and local officials.

b. The network of commercial and industrial highways shall not exceed two thousand  six hundred miles including municipal extensions of these highways.
	
3. Standards.  The department shall establish standards pertaining to the specific location, design, and access control for each segment of the commercial and industrial highways.
	
4. Network development.  In establishing priorities for improvement projects, the department shall take into consideration the following additional criteria:  urban area bypasses that improve urban or regional accessibility or improve corridor travel; projects consistent with regional or metropolitan transportation plans established through cooperation by the department and local officials; and the willingness of local officials to provide financial or other assistance for the development of projects.

 Source: Iowa Code Section 313.2A Primary Roads: Commercial and Industrial Highways. http://search.legis.state.ia.us/nxt/gateway.dll/ic/1/13/10856/10857/11188/11191?f=templates&fn=default.htm.

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
series e:u4pw-exke d:2016-11-08T18:04:10.000Z t:shape.longitude=-93.49763558599994 t:lane_type=1 t:highway_responsibility=B t:county_number=77 t:lane_position_1=2 t:facility_type=1 t:city_number=6102 t:route_name_2="CITY OF PLEASANT HILL, EAST UNIVERSITY AVENUE, E" t:lane_type_1=1 t:road_status=0 t:urban_area_code=71 t:median_type=2 t:routeid=S001930163E t:shape.needs_recoding=false t:route_name="STATE OF IOWA, IA 163 E" t:shape.latitude=41.59868413500004 t:objectid=1690 t:county_name=Polk t:lane_position=1 m:frommeasure=5.351393 m:planning_class=2 m:h_and_t=0 m:tomeasure=5.378953999999999 m:median_width=50 m:national_highway_system=1 m:truck_route=1 m:fed_functional_class=3 m:access_control=3 m:number_lanes=2 m:commercial_network=1

series e:u4pw-exke d:2016-11-08T18:04:10.000Z t:shape.longitude=-93.49800354299998 t:lane_type=1 t:highway_responsibility=B t:county_number=77 t:lane_position_1=2 t:facility_type=1 t:city_number=6102 t:route_name_2="CITY OF PLEASANT HILL, EAST UNIVERSITY AVENUE, E" t:lane_type_1=1 t:road_status=0 t:urban_area_code=71 t:median_type=2 t:routeid=S001930163E t:shape.needs_recoding=false t:route_name="STATE OF IOWA, IA 163 E" t:shape.latitude=41.59869468200003 t:objectid=1692 t:county_name=Polk t:lane_position=1 m:frommeasure=5.332325 m:planning_class=2 m:h_and_t=0 m:tomeasure=5.351393 m:median_width=44 m:national_highway_system=1 m:truck_route=1 m:fed_functional_class=3 m:access_control=3 m:number_lanes=2 m:commercial_network=1

series e:u4pw-exke d:2016-11-08T18:04:10.000Z t:shape.longitude=-93.42544422799995 t:lane_type=1 t:highway_responsibility=B t:county_number=77 t:facility_type=1 t:lane_position_1=2 t:city_number=6102 t:route_name_2="CITY OF PLEASANT HILL, EAST UNIVERSITY AVENUE, E" t:lane_type_1=1 t:road_status=0 t:median_type=2 t:routeid=S001930163E t:shape.needs_recoding=false t:route_name="STATE OF IOWA, IA 163 E" t:shape.latitude=41.60032025100003 t:objectid=1693 t:county_name=Polk t:lane_position=1 m:frommeasure=9.101476 m:planning_class=2 m:h_and_t=0 m:tomeasure=9.140044 m:median_width=50 m:national_highway_system=1 m:truck_route=1 m:fed_functional_class=3 m:access_control=3 m:number_lanes=2 m:commercial_network=1
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

entity e:u4pw-exke l:"Network - Commercial and Industrial" t:attribution="Iowa Department of Transportation - Office of Research and Analytics" t:url=https://data.iowa.gov/api/views/u4pw-exke

property e:u4pw-exke t:meta.view v:id=u4pw-exke v:category="Transportation & Utilities" v:averageRating=0 v:name="Network - Commercial and Industrial" v:attribution="Iowa Department of Transportation - Office of Research and Analytics"

property e:u4pw-exke t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:u4pw-exke t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | id                                   | routeid     | frommeasure                                           | tomeasure                                             | county_number | road_system | road_status | route_name              | route_name_1 | route_name_2                                     | route_name_3 | route_name_4 | h_and_t | city_number | urban_area_code | adjacent_city_number | adjacent_county_number | toll_charged | fed_functional_class | national_highway_system | access_control | facility_type | cost_group | truck_route | highway_responsibility | commercial_network | planning_class | median_type | median_width | number_lanes | lane_type | lane_position | lane_type_1 | lane_position_1 | lane_type_2 | lane_position_2 | lane_type_3 | lane_position_3 | lane_type_4 | lane_position_4 | lane_type_5 | lane_position_5 | lane_type_6 | lane_position_6 | lane_type_7 | lane_position_7 | lane_type_8 | lane_position_8 | county_name | shape_len | objectid | shape                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 
| =========== | ==================================== | =========== | ===================================================== | ===================================================== | ============= | =========== | =========== | ======================= | ============ | ================================================ | ============ | ============ | ======= | =========== | =============== | ==================== | ====================== | ============ | ==================== | ======================= | ============== | ============= | ========== | =========== | ====================== | ================== | ============== | =========== | ============ | ============ | ========= | ============= | =========== | =============== | =========== | =============== | =========== | =============== | =========== | =============== | =========== | =============== | =========== | =============== | =========== | =============== | =========== | =============== | =========== | ========= | ======== | ================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 0           | 5b352e81-d56a-4d01-ae64-2be11e778eb3 | S001930163E | 5.3513929999999998443627191591076552867889404296875   | 5.37895399999999934692596070817671716213226318359375  | 77            |             | 0           | STATE OF IOWA, IA 163 E |              | CITY OF PLEASANT HILL, EAST UNIVERSITY AVENUE, E |              |              | 0       | 6102        | 71              |                      |                        |              | 3                    | 1                       | 3              | 1             |            | 1           | B                      | 1                  | 2              | 2           | 50           | 2            | 1         | 1             | 1           | 2               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Polk        |           | 1690     | [null, 41.59868413500004, -93.49763558599994, null, false, {paths=[[[-93.49763558599994, 41.59868413500004], [-93.49710374299997, 41.598668892000035]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | 
| 0           | 85810af9-76ea-49b8-bb4d-aaa8b7e020bd | S001930163E | 5.33232499999999998152588887023739516735076904296875  | 5.3513929999999998443627191591076552867889404296875   | 77            |             | 0           | STATE OF IOWA, IA 163 E |              | CITY OF PLEASANT HILL, EAST UNIVERSITY AVENUE, E |              |              | 0       | 6102        | 71              |                      |                        |              | 3                    | 1                       | 3              | 1             |            | 1           | B                      | 1                  | 2              | 2           | 44           | 2            | 1         | 1             | 1           | 2               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Polk        |           | 1692     | [null, 41.59869468200003, -93.49800354299998, null, false, {paths=[[[-93.49800354299998, 41.59869468200003], [-93.49763558599994, 41.59868413500004]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | 
| 0           | eb56ba72-85a2-409a-ad7d-5bf2f74352a7 | S001930163E | 9.1014759999999998996145222918130457401275634765625   | 9.140043999999999613237378071062266826629638671875    | 77            |             | 0           | STATE OF IOWA, IA 163 E |              | CITY OF PLEASANT HILL, EAST UNIVERSITY AVENUE, E |              |              | 0       | 6102        |                 |                      |                        |              | 3                    | 1                       | 3              | 1             |            | 1           | B                      | 1                  | 2              | 2           | 50           | 2            | 1         | 1             | 1           | 2               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Polk        |           | 1693     | [null, 41.60032025100003, -93.42544422799995, null, false, {paths=[[[-93.42544422799995, 41.60032025100003], [-93.42519117499995, 41.600309270000025], [-93.42470159799996, 41.60027814000006]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 
| 0           | 1bced5e5-449b-4801-aba7-cef0d4c71d73 | S001930163E | 5.28638500000000011169731806148774921894073486328125  | 5.33232499999999998152588887023739516735076904296875  | 77            |             | 0           | STATE OF IOWA, IA 163 E |              | CITY OF PLEASANT HILL, EAST UNIVERSITY AVENUE, E |              |              | 0       | 6102        | 71              |                      |                        |              | 3                    | 1                       | 3              | 1             |            | 1           | B                      | 1                  | 2              | 2           | 38           | 2            | 1         | 1             | 1           | 2               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Polk        |           | 1694     | [null, 41.59871983800008, -93.49889005999995, null, false, {paths=[[[-93.49889005999995, 41.59871983800008], [-93.49810118599999, 41.598697480000055], [-93.49800354299998, 41.59869468200003]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 
| 0           | c7ceb07e-b33d-45fd-aff9-f32951e703fe | S001930163E | 2.275456999999999840866848899167962372303009033203125 | 2.296218000000000092342133939382620155811309814453125 | 77            |             | 0           | STATE OF IOWA, IA 163 E |              | CITY OF DES MOINES, EAST UNIVERSITY AVENUE, E    |              |              | 0       | 1945        | 71              |                      |                        |              | 3                    | 1                       | 3              | 1             | 2          | 1           | B                      | 1                  | 2              | 1           | 16           | 2            | 1         | 1             | 1           | 2               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Polk        |           | 1696     | [null, 41.600483874000076, -93.55677509199995, null, false, {paths=[[[-93.55677509199995, 41.600483874000076], [-93.55637416699994, 41.60048524700005]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | 
| 0           | bcde30d4-9198-417d-ab55-8ba6f5f45681 | S001930163E | 8.6419629999999987290948411100544035434722900390625   | 9.1014759999999998996145222918130457401275634765625   | 77            |             | 0           | STATE OF IOWA, IA 163 E |              | CITY OF PLEASANT HILL, EAST UNIVERSITY AVENUE, E |              |              | 0       | 6102        | 71              |                      |                        |              | 3                    | 1                       | 3              | 1             |            | 1           | B                      | 1                  | 2              | 2           | 50           | 2            | 1         | 1             | 1           | 2               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Polk        |           | 1698     | [null, 41.60039622200003, -93.43431583299997, null, false, {paths=[[[-93.43431583299997, 41.60039622200003], [-93.43231937999997, 41.600396654000065], [-93.42875713399997, 41.60039448500004], [-93.42768655599997, 41.60039381100006], [-93.42698174299994, 41.60037906400004], [-93.42626170099999, 41.600355723000064], [-93.42544422799995, 41.60032025100003]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                            | 
| 0           | a374b5fe-d0bd-4c5e-a160-735f28d5753f | S001930163E | 5.11901599999999934453853711602278053760528564453125  | 5.28638500000000011169731806148774921894073486328125  | 77            |             | 0           | STATE OF IOWA, IA 163 E |              | CITY OF PLEASANT HILL, EAST UNIVERSITY AVENUE, E |              |              | 0       | 6102        | 71              |                      |                        |              | 3                    | 1                       | 3              | 1             |            | 1           | B                      | 1                  | 2              | 2           | 62           | 2            | 1         | 1             | 1           | 2               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Polk        |           | 1700     | [null, 41.59884266100005, -93.50211777599998, null, false, {paths=[[[-93.50211777599998, 41.59884266100005], [-93.50158333599995, 41.59881759600006], [-93.50032229199996, 41.59876041000007], [-93.49890556599996, 41.59872027700004], [-93.49889005999995, 41.59871983800008]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 
| 0           | ba1edeae-18d7-4838-87a1-a530ff421370 | S001930163E | 2.256082999999999838536268725874833762645721435546875 | 2.275456999999999840866848899167962372303009033203125 | 77            |             | 0           | STATE OF IOWA, IA 163 E |              | CITY OF DES MOINES, EAST UNIVERSITY AVENUE, E    |              |              | 0       | 1945        | 71              |                      |                        |              | 3                    | 1                       | 3              | 1             | 2          | 1           | B                      | 1                  | 2              | 1           | 10           | 2            | 1         | 1             | 1           | 2               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Polk        |           | 1701     | [null, 41.60048259200005, -93.55714923099998, null, false, {paths=[[[-93.55714923099998, 41.60048259200005], [-93.55677509199995, 41.600483874000076]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | 
| 0           | 24376121-f17c-4148-9de8-1c8fed4b36f6 | S001930163E | 8.4578340000000000742375050322152674198150634765625   | 8.6419629999999987290948411100544035434722900390625   | 77            |             | 0           | STATE OF IOWA, IA 163 E |              | CITY OF PLEASANT HILL, EAST UNIVERSITY AVENUE, E |              |              | 0       | 6102        | 71              |                      |                        |              | 3                    | 1                       | 3              | 1             |            | 1           | B                      | 1                  | 2              | 2           | 50           | 3            | 1         | 1             | 1           | 2               | 3           | 3               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Polk        |           | 1702     | [null, 41.60039366700005, -93.43787164999998, null, false, {paths=[[[-93.43787164999998, 41.60039366700005], [-93.43588543799996, 41.600395856000034], [-93.43431583299997, 41.60039622200003]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 
| 0           | a3a00fbc-f60d-4879-bb8a-4f62e0ed1eff | S001920020W | 9.501763000000000403133526560850441455841064453125    | 10.4238559999999989003072187188081443309783935546875  | 31            |             | 0           | STATE OF IOWA, US 20 W  |              |                                                  |              |              | 0       |             |                 |                      |                        |              | 3                    | 1                       | 2              | 6             |            | 1           | B                      | 1                  | 2              | 2           | 50           | 2            | 1         | 1             | 1           | 2               |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 |             |                 | Dubuque     |           | 1703     | [null, 42.43998643500004, -90.80129480699998, null, false, {paths=[[[-90.80129480699998, 42.43998643500004], [-90.80147405799994, 42.43999097100004], [-90.80291507499999, 42.44004964800007], [-90.80385571499994, 42.44006802300004], [-90.80478731699998, 42.44007187600005], [-90.80558478699999, 42.44005113900005], [-90.80644449999994, 42.44004257600005], [-90.80886835899997, 42.44014911600004], [-90.81002106599999, 42.440175956000076], [-90.81094272199994, 42.44018668100006], [-90.81193205299996, 42.440195396000036], [-90.81252965499993, 42.44022002400004], [-90.81356555199994, 42.44026914400007], [-90.81484472099999, 42.440273844000046], [-90.81627747299996, 42.44029997700005], [-90.81801738899998, 42.44036898100006], [-90.81932304599997, 42.44039337900006]]]}] | 
```