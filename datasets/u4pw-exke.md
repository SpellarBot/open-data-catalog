# Network - Commercial and Industrial

## Dataset

* [Dataset URL](https://data.iowa.gov/api/views/u4pw-exke/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/network-commercial-and-industrial)
* [Metadata URL](https://data.iowa.gov/api/views/u4pw-exke)
* Id = u4pw-exke
* Name = Network - Commercial and Industrial
* Attribution = Iowa Department of Transportation - Office of Research and Analytics
* Category = Transportation & Utilities
* Tags = [nhs, network, road, route, transportation, lrs, fcc, commercial, industrial, asset, classification, iowa dot, iowa department of transportation]
* Created = 2016-11-08T18:04:10Z
* Publication Date = 2016-11-08T18:08:27Z
* Rows Updated = 2016-11-08T18:04:10Z

## Description

Commercial and Industrial Network information for the centerline road segments in the State of Iowa.

1. Purpose.  It is the purpose of this section to enhance opportunities for the development and diversification of the state?s economy through the identification and improvement of a network of commercial and industrial highways.  The network shall consist of interconnected routes which provide long distance route continuity.  The purpose of this highway network shall be to improve the flow of commerce; to make travel more convenient, safe, and efficient; and to better connect Iowa with regional, national, and international markets.  The commission shall concentrate a major portion of its annual construction budget on this network of commercial and industrial highways.  In order to ensure the greatest possible availability of funds for the improvement of the network, primary highway funds shall not be spent beyond continuing maintenance for improvements to route segments that will be bypassed by the relocation of portions of the commercial and industrial highway network.
	
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
| Name                    | Field Name              | Data Type  | Render Type | Schema Type    | Included | 
| ======================= | ======================= | ========== | =========== | ============== | ======== | 
| updated_at              | :updated_at             | meta_data  | meta_data   | time           | No       | 
| ID                      | id                      | text       | text        |                | No       | 
| ROUTEID                 | routeid                 | text       | text        | series tag     | Yes      | 
| FROMMEASURE             | frommeasure             | number     | number      | numeric metric | Yes      | 
| TOMEASURE               | tomeasure               | number     | number      | numeric metric | Yes      | 
| COUNTY_NUMBER           | county_number           | number     | number      | numeric metric | Yes      | 
| ROAD_SYSTEM             | road_system             | number     | number      | numeric metric | Yes      | 
| ROAD_STATUS             | road_status             | number     | number      | numeric metric | Yes      | 
| ROUTE_NAME              | route_name              | text       | text        | series tag     | Yes      | 
| ROUTE_NAME_1            | route_name_1            | text       | text        | series tag     | Yes      | 
| ROUTE_NAME_2            | route_name_2            | text       | text        | series tag     | Yes      | 
| ROUTE_NAME_3            | route_name_3            | text       | text        | series tag     | Yes      | 
| ROUTE_NAME_4            | route_name_4            | text       | text        | series tag     | Yes      | 
| H_AND_T                 | h_and_t                 | number     | number      | numeric metric | Yes      | 
| CITY_NUMBER             | city_number             | number     | number      | numeric metric | Yes      | 
| URBAN_AREA_CODE         | urban_area_code         | text       | number      | series tag     | Yes      | 
| ADJACENT_CITY_NUMBER    | adjacent_city_number    | number     | number      | numeric metric | Yes      | 
| ADJACENT_COUNTY_NUMBER  | adjacent_county_number  | number     | number      | numeric metric | Yes      | 
| TOLL_CHARGED            | toll_charged            | number     | number      | numeric metric | Yes      | 
| FED_FUNCTIONAL_CLASS    | fed_functional_class    | number     | number      | numeric metric | Yes      | 
| NATIONAL_HIGHWAY_SYSTEM | national_highway_system | number     | number      | numeric metric | Yes      | 
| ACCESS_CONTROL          | access_control          | number     | number      | numeric metric | Yes      | 
| FACILITY_TYPE           | facility_type           | number     | number      | numeric metric | Yes      | 
| COST_GROUP              | cost_group              | number     | number      | numeric metric | Yes      | 
| TRUCK_ROUTE             | truck_route             | number     | number      | numeric metric | Yes      | 
| HIGHWAY_RESPONSIBILITY  | highway_responsibility  | text       | text        | series tag     | Yes      | 
| COMMERCIAL_NETWORK      | commercial_network      | number     | number      | numeric metric | Yes      | 
| PLANNING_CLASS          | planning_class          | number     | number      | numeric metric | Yes      | 
| MEDIAN_TYPE             | median_type             | number     | number      | numeric metric | Yes      | 
| MEDIAN_WIDTH            | median_width            | number     | number      | numeric metric | Yes      | 
| NUMBER_LANES            | number_lanes            | number     | number      | numeric metric | Yes      | 
| LANE_TYPE               | lane_type               | text       | text        | series tag     | Yes      | 
| LANE_POSITION           | lane_position           | text       | text        | series tag     | Yes      | 
| LANE_TYPE_1             | lane_type_1             | text       | text        | series tag     | Yes      | 
| LANE_POSITION_1         | lane_position_1         | text       | text        | series tag     | Yes      | 
| LANE_TYPE_2             | lane_type_2             | text       | text        | series tag     | Yes      | 
| LANE_POSITION_2         | lane_position_2         | text       | text        | series tag     | Yes      | 
| LANE_TYPE_3             | lane_type_3             | text       | text        | series tag     | Yes      | 
| LANE_POSITION_3         | lane_position_3         | text       | text        | series tag     | Yes      | 
| LANE_TYPE_4             | lane_type_4             | text       | text        | series tag     | Yes      | 
| LANE_POSITION_4         | lane_position_4         | text       | text        | series tag     | Yes      | 
| LANE_TYPE_5             | lane_type_5             | text       | text        | series tag     | Yes      | 
| LANE_POSITION_5         | lane_position_5         | text       | text        | series tag     | Yes      | 
| LANE_TYPE_6             | lane_type_6             | text       | text        | series tag     | Yes      | 
| LANE_POSITION_6         | lane_position_6         | text       | text        | series tag     | Yes      | 
| LANE_TYPE_7             | lane_type_7             | text       | text        | series tag     | Yes      | 
| LANE_POSITION_7         | lane_position_7         | text       | text        | series tag     | Yes      | 
| LANE_TYPE_8             | lane_type_8             | text       | text        | series tag     | Yes      | 
| LANE_POSITION_8         | lane_position_8         | text       | text        | series tag     | Yes      | 
| COUNTY_NAME             | county_name             | text       | text        | series tag     | Yes      | 
| SHAPE.LEN               | shape_len               | number     | number      | numeric metric | Yes      | 
| OBJECTID                | objectid                | text       | number      | series tag     | Yes      | 
| SHAPE                   | shape                   | geospatial | geospatial  | series tag     | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = id
Annotation Fields = 
```

## Data Commands

```ls
series e:u4pw-exke d:1970-01-01T00:00:00.000Z t:lane_type=1 t:urban_area_code=71 t:highway_responsibility=B t:routeid=S001930163E t:route_name="STATE OF IOWA, IA 163 E" t:lane_position_1=2 t:objectid=1690 t:route_name_2="CITY OF PLEASANT HILL, EAST UNIVERSITY AVENUE, E" t:county_name=Polk t:lane_position=1 t:lane_type_1=1 m:county_number=77 m:median_width=50 m:tomeasure=5.37895 m:truck_route=1 m:fed_functional_class=3 m:facility_type=1 m:city_number=6102 m:number_lanes=2 m:commercial_network=1 m:road_status=0 m:frommeasure=5.35139 m:median_type=2 m:planning_class=2 m:h_and_t=0 m:national_highway_system=1 m:access_control=3

series e:u4pw-exke d:1970-01-01T00:00:00.000Z t:lane_type=1 t:urban_area_code=71 t:highway_responsibility=B t:routeid=S001930163E t:route_name="STATE OF IOWA, IA 163 E" t:lane_position_1=2 t:objectid=1692 t:route_name_2="CITY OF PLEASANT HILL, EAST UNIVERSITY AVENUE, E" t:county_name=Polk t:lane_position=1 t:lane_type_1=1 m:county_number=77 m:median_width=44 m:tomeasure=5.35139 m:truck_route=1 m:fed_functional_class=3 m:facility_type=1 m:city_number=6102 m:number_lanes=2 m:commercial_network=1 m:road_status=0 m:frommeasure=5.33232 m:median_type=2 m:planning_class=2 m:h_and_t=0 m:national_highway_system=1 m:access_control=3

series e:u4pw-exke d:1970-01-01T00:00:00.000Z t:lane_type=1 t:highway_responsibility=B t:routeid=S001930163E t:route_name="STATE OF IOWA, IA 163 E" t:lane_position_1=2 t:objectid=1693 t:route_name_2="CITY OF PLEASANT HILL, EAST UNIVERSITY AVENUE, E" t:county_name=Polk t:lane_position=1 t:lane_type_1=1 m:county_number=77 m:median_width=50 m:tomeasure=9.14004 m:truck_route=1 m:fed_functional_class=3 m:facility_type=1 m:city_number=6102 m:number_lanes=2 m:commercial_network=1 m:road_status=0 m:frommeasure=9.10148 m:median_type=2 m:planning_class=2 m:h_and_t=0 m:national_highway_system=1 m:access_control=3
```

## Meta Commands

```ls
metric m:frommeasure l:FROMMEASURE d:"From Measure" t:dataTypeName=number

metric m:tomeasure l:TOMEASURE d:"To Measure" t:dataTypeName=number

metric m:county_number l:COUNTY_NUMBER d:"County Number" t:dataTypeName=number

metric m:road_system l:ROAD_SYSTEM d:"Road System" t:dataTypeName=number

metric m:road_status l:ROAD_STATUS d:"Road Status" t:dataTypeName=number

metric m:h_and_t l:H_AND_T d:"H and T" t:dataTypeName=number

metric m:city_number l:CITY_NUMBER d:"City Number" t:dataTypeName=number

metric m:adjacent_city_number l:ADJACENT_CITY_NUMBER d:"Adjacent City Number" t:dataTypeName=number

metric m:adjacent_county_number l:ADJACENT_COUNTY_NUMBER d:"Adjacent County Number" t:dataTypeName=number

metric m:toll_charged l:TOLL_CHARGED d:"Toll Charged" t:dataTypeName=number

metric m:fed_functional_class l:FED_FUNCTIONAL_CLASS d:"Federal Functional Class" t:dataTypeName=number

metric m:national_highway_system l:NATIONAL_HIGHWAY_SYSTEM d:"National Highway System" t:dataTypeName=number

metric m:access_control l:ACCESS_CONTROL d:"Access Control" t:dataTypeName=number

metric m:facility_type l:FACILITY_TYPE d:"Facility Type" t:dataTypeName=number

metric m:cost_group l:COST_GROUP d:"Cost Group" t:dataTypeName=number

metric m:truck_route l:TRUCK_ROUTE d:"Truck Route" t:dataTypeName=number

metric m:commercial_network l:COMMERCIAL_NETWORK d:"Commercial Network" t:dataTypeName=number

metric m:planning_class l:PLANNING_CLASS d:"Planning Class" t:dataTypeName=number

metric m:median_type l:MEDIAN_TYPE d:"Median Type" t:dataTypeName=number

metric m:median_width l:MEDIAN_WIDTH d:"Median Width" t:dataTypeName=number

metric m:number_lanes l:NUMBER_LANES d:"Number of Lanes" t:dataTypeName=number

metric m:shape_len l:SHAPE.LEN d:"Length (Meter)" t:dataTypeName=number

entity e:u4pw-exke l:"Network - Commercial and Industrial" t:attribution="Iowa Department of Transportation - Office of Research and Analytics" t:url=https://data.iowa.gov/api/views/u4pw-exke

property e:u4pw-exke t:meta.view d:2017-03-08T01:53:44.754Z v:id=u4pw-exke v:category="Transportation & Utilities" v:averageRating=0 v:name="Network - Commercial and Industrial" v:attribution="Iowa Department of Transportation - Office of Research and Analytics"

property e:u4pw-exke t:meta.view.owner d:2017-03-08T01:53:44.754Z v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"

property e:u4pw-exke t:meta.view.tableauthor d:2017-03-08T01:53:44.754Z v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```