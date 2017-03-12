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
| Rows Updated | 2016-11-08T18:04:10Z |

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
| Included | Schema Type    | Field Name              | Name                    | Data Type  | Render Type |
| ======== | ============== | ======================= | ======================= | ========== | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data  | meta_data   |
| No       |                | id                      | ID                      | text       | text        |
| Yes      | series tag     | routeid                 | ROUTEID                 | text       | text        |
| Yes      | numeric metric | frommeasure             | FROMMEASURE             | number     | number      |
| Yes      | numeric metric | tomeasure               | TOMEASURE               | number     | number      |
| Yes      | numeric metric | county_number           | COUNTY_NUMBER           | number     | number      |
| Yes      | numeric metric | road_system             | ROAD_SYSTEM             | number     | number      |
| Yes      | numeric metric | road_status             | ROAD_STATUS             | number     | number      |
| Yes      | series tag     | route_name              | ROUTE_NAME              | text       | text        |
| Yes      | series tag     | route_name_1            | ROUTE_NAME_1            | text       | text        |
| Yes      | series tag     | route_name_2            | ROUTE_NAME_2            | text       | text        |
| Yes      | series tag     | route_name_3            | ROUTE_NAME_3            | text       | text        |
| Yes      | series tag     | route_name_4            | ROUTE_NAME_4            | text       | text        |
| Yes      | numeric metric | h_and_t                 | H_AND_T                 | number     | number      |
| Yes      | numeric metric | city_number             | CITY_NUMBER             | number     | number      |
| Yes      | series tag     | urban_area_code         | URBAN_AREA_CODE         | text       | number      |
| Yes      | numeric metric | adjacent_city_number    | ADJACENT_CITY_NUMBER    | number     | number      |
| Yes      | numeric metric | adjacent_county_number  | ADJACENT_COUNTY_NUMBER  | number     | number      |
| Yes      | numeric metric | toll_charged            | TOLL_CHARGED            | number     | number      |
| Yes      | numeric metric | fed_functional_class    | FED_FUNCTIONAL_CLASS    | number     | number      |
| Yes      | numeric metric | national_highway_system | NATIONAL_HIGHWAY_SYSTEM | number     | number      |
| Yes      | numeric metric | access_control          | ACCESS_CONTROL          | number     | number      |
| Yes      | numeric metric | facility_type           | FACILITY_TYPE           | number     | number      |
| Yes      | numeric metric | cost_group              | COST_GROUP              | number     | number      |
| Yes      | numeric metric | truck_route             | TRUCK_ROUTE             | number     | number      |
| Yes      | series tag     | highway_responsibility  | HIGHWAY_RESPONSIBILITY  | text       | text        |
| Yes      | numeric metric | commercial_network      | COMMERCIAL_NETWORK      | number     | number      |
| Yes      | numeric metric | planning_class          | PLANNING_CLASS          | number     | number      |
| Yes      | numeric metric | median_type             | MEDIAN_TYPE             | number     | number      |
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
| Yes      | series tag     | shape                   | SHAPE                   | geospatial | geospatial  |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id
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

property e:u4pw-exke t:meta.view v:id=u4pw-exke v:category="Transportation & Utilities" v:averageRating=0 v:name="Network - Commercial and Industrial" v:attribution="Iowa Department of Transportation - Office of Research and Analytics"

property e:u4pw-exke t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"

property e:u4pw-exke t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```