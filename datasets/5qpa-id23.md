# Traffic Counts for Select Bridges: Beginning 1933

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/traffic-counts-for-select-bridges-beginning-1933) |
| Metadata | [Link](https://data.ny.gov/api/views/5qpa-id23) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/5qpa-id23/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/5qpa-id23/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 5qpa-id23 |
| Name | Traffic Counts for Select Bridges: Beginning 1933 |
| Attribution | New York State Bridge Authority |
| Category | Transportation |
| Tags | traffic, bridge |
| Created | 2013-02-26T16:31:36Z |
| Publication Date | 2016-01-27T23:01:11Z |

## Description

Traffic counts by bridge for 1933 forward for each bridge in the New York State Bridge Authority system.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | numeric metric | rip_van_winkle_bridge      | Rip Van Winkle Bridge      | number    | number      |
| Yes      | numeric metric | kingston_rhinecliff_bridge | Kingston-Rhinecliff Bridge | number    | number      |
| Yes      | numeric metric | mid_hudson_bridge          | Mid-Hudson Bridge          | number    | number      |
| Yes      | numeric metric | newburgh_beacon_bridge     | Newburgh-Beacon Bridge     | number    | number      |
| Yes      | numeric metric | bear_mountain_bridge       | Bear Mountain Bridge       | number    | number      |
| Yes      | numeric metric | total                      | Total                      | number    | number      |
| Yes      | numeric metric | deviation_1                | Deviation                  | number    | number      |
| Yes      | numeric metric | deviation_2                | Deviation %                | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5qpa-id23 d:1933-01-01T00:00:00.000Z m:total=394797 m:mid_hudson_bridge=394797 m:rip_van_winkle_bridge=0 m:bear_mountain_bridge=0 m:kingston_rhinecliff_bridge=0 m:newburgh_beacon_bridge=0

series e:5qpa-id23 d:1934-01-01T00:00:00.000Z m:total=479512 m:mid_hudson_bridge=479512 m:rip_van_winkle_bridge=0 m:deviation_1=84715 m:bear_mountain_bridge=0 m:kingston_rhinecliff_bridge=0 m:newburgh_beacon_bridge=0 m:deviation_2=21.46

series e:5qpa-id23 d:1935-01-01T00:00:00.000Z m:total=673117 m:mid_hudson_bridge=582838 m:rip_van_winkle_bridge=90279 m:deviation_1=193605 m:bear_mountain_bridge=0 m:kingston_rhinecliff_bridge=0 m:newburgh_beacon_bridge=0 m:deviation_2=40.38
```

## Meta Commands

```ls
metric m:rip_van_winkle_bridge p:integer l:"Rip Van Winkle Bridge" t:dataTypeName=number

metric m:kingston_rhinecliff_bridge p:integer l:"Kingston-Rhinecliff Bridge" t:dataTypeName=number

metric m:mid_hudson_bridge p:integer l:"Mid-Hudson Bridge" t:dataTypeName=number

metric m:newburgh_beacon_bridge p:integer l:"Newburgh-Beacon Bridge" t:dataTypeName=number

metric m:bear_mountain_bridge p:integer l:"Bear Mountain Bridge" t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

metric m:deviation_1 p:long l:Deviation t:dataTypeName=number

metric m:deviation_2 p:float l:"Deviation %" t:dataTypeName=percent

entity e:5qpa-id23 l:"Traffic Counts for Select Bridges: Beginning 1933" t:attribution="New York State Bridge Authority" t:url=https://data.ny.gov/api/views/5qpa-id23

property e:5qpa-id23 t:meta.view v:id=5qpa-id23 v:category=Transportation v:attributionLink=http://nysba.net/Index%20Page/General%20Info.html v:averageRating=0 v:name="Traffic Counts for Select Bridges: Beginning 1933" v:attribution="New York State Bridge Authority"

property e:5qpa-id23 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:5qpa-id23 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:5qpa-id23 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | rip_van_winkle_bridge | kingston_rhinecliff_bridge | mid_hudson_bridge | newburgh_beacon_bridge | bear_mountain_bridge | total   | deviation_1 | deviation_2 | 
| ==== | ===================== | ========================== | ================= | ====================== | ==================== | ======= | =========== | =========== | 
| 1933 | 0                     | 0                          | 394797            | 0                      | 0                    | 394797  |             |             | 
| 1934 | 0                     | 0                          | 479512            | 0                      | 0                    | 479512  | 84715       | 21.46       | 
| 1935 | 90279                 | 0                          | 582838            | 0                      | 0                    | 673117  | 193605      | 40.38       | 
| 1936 | 175323                | 0                          | 638150            | 0                      | 0                    | 813473  | 140356      | 20.85       | 
| 1937 | 234396                | 0                          | 739200            | 0                      | 0                    | 973596  | 160123      | 19.68       | 
| 1938 | 366461                | 0                          | 873850            | 0                      | 0                    | 1240311 | 266715      | 27.39       | 
| 1939 | 408550                | 0                          | 1000017           | 0                      | 0                    | 1408567 | 168256      | 13.57       | 
| 1940 | 460499                | 0                          | 1083893           | 0                      | 143417               | 1687809 | 279242      | 19.82       | 
| 1941 | 570361                | 0                          | 1248558           | 0                      | 702044               | 2520963 | 833154      | 49.36       | 
| 1942 | 361463                | 0                          | 1198641           | 0                      | 484210               | 2044314 | -476649     | -18.91      | 
```