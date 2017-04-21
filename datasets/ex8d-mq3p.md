# Index of Municipalities and Administrative and Planning Regions (work in progress)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/index-of-municipalities-and-administrative-and-planning-regions-work-in-progress) |
| Metadata | [Link](https://data.ct.gov/api/views/ex8d-mq3p) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/ex8d-mq3p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/ex8d-mq3p/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | ex8d-mq3p |
| Name | Index of Municipalities and Administrative and Planning Regions (work in progress) |
| Attribution | Chief Data Officer |
| Category | Government |
| Tags | municipal, towns, regions |
| Created | 2016-07-21T18:13:38Z |
| Publication Date | 2016-07-25T15:32:49Z |

## Description

A listing of each municipality in Connecticut and corresponding regions that are used throughout the State for various admininstrative and planning purposes. This list is not exhaustive and will be added to over time.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type | Render Type |
| ======== | ============== | ================================= | ================================= | ========= | =========== |
| No       | time           | :updated_at                       | updated_at                        | meta_data | meta_data   |
| Yes      | series tag     | town_num                          | TOWN NUM                          | text      | number      |
| Yes      | series tag     | town                              | TOWN                              | text      | text        |
| Yes      | numeric metric | 2010_population                   | 2010 POPULATION                   | number    | number      |
| Yes      | series tag     | planning_region_cog               | PLANNING REGION/COG               | text      | text        |
| Yes      | series tag     | county                            | COUNTY                            | text      | text        |
| Yes      | series tag     | regional_education_service_center | REGIONAL EDUCATION SERVICE CENTER | text      | text        |
| Yes      | series tag     | health_district_or_status         | HEALTH DISTRICT OR STATUS         | text      | text        |
| Yes      | series tag     | labor_market_area                 | LABOR_MARKET_AREA                 | text      | text        |
| Yes      | series tag     | workforce_investment_area         | WORKFORCE INVESTMENT AREA         | text      | text        |
| Yes      | series tag     | dss_office_num                    | DSS OFFICE NUM                    | text      | number      |
| Yes      | series tag     | dss_region_num                    | DSS REGION NUM                    | text      | number      |
| Yes      | series tag     | dcf_office                        | DCF OFFICE                        | text      | text        |
| Yes      | series tag     | dcf_region                        | DCF REGION                        | text      | text        |
| Yes      | series tag     | dmhas_service_region              | DMHAS SERVICE REGION              | text      | text        |
| Yes      | series tag     | service_delivery_area             | SERVICE DELIVERY AREA             | text      | text        |
| Yes      | series tag     | dot_maintenance_district          | DOT MAINTENANCE DISTRICT          | text      | number      |
| Yes      | numeric metric | emergency_planning_region         | EMERGENCY PLANNING REGION         | number    | number      |
| Yes      | series tag     | judicial_district                 | JUDICIAL DISTRICT                 | text      | text        |
| Yes      | series tag     | judicial_geographical_area        | JUDICIAL GEOGRAPHICAL AREA        | text      | text        |
| Yes      | series tag     | state_police_troop                | STATE POLICE TROOP                | text      | text        |
| Yes      | series tag     | community_action_agency           | COMMUNITY ACTION AGENCY           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ex8d-mq3p d:2016-07-25T08:32:02.000Z t:dss_office_num=11 t:workforce_investment_area="North Central" t:town_num=1 t:judicial_geographical_area="Geographical Area 19" t:community_action_agency="The Access Community Action Agency, Inc" t:service_delivery_area="Hartford Service Delivery Area" t:judicial_district="Tolland Judicial District" t:state_police_troop=K t:dcf_region="REGION 4" t:health_district_or_status="Eastern Highlands Health District" t:dcf_office=MANCHESTER t:county=Tolland t:planning_region_cog=Capitol t:regional_education_service_center=EASTCONN t:dot_maintenance_district=1 t:dss_region_num=1 t:dmhas_service_region="REGION 4" t:town=Andover t:labor_market_area="Hartford LMA" m:2010_population=3303 m:emergency_planning_region=3

series e:ex8d-mq3p d:2016-07-25T08:32:02.000Z t:dss_office_num=20 t:workforce_investment_area=Southwest t:town_num=2 t:judicial_geographical_area="Geographical Area 5" t:community_action_agency="Training, Education, and Manpower, Inc. (TEAM)" t:service_delivery_area="Southwest Service Delivery Area" t:judicial_district="Ansonia-Milford Judicial District" t:state_police_troop=I t:dcf_region="REGION 2" t:health_district_or_status="Naugatuck Valley Health District" t:dcf_office=MILFORD t:county="New Haven" t:planning_region_cog="Naugatuck Valley" t:regional_education_service_center=ACES t:dot_maintenance_district=4 t:dss_region_num=2 t:dmhas_service_region="REGION 2" t:town=Ansonia t:labor_market_area="Bridgeport - Stamford LMA" m:2010_population=19249 m:emergency_planning_region=2

series e:ex8d-mq3p d:2016-07-25T08:32:02.000Z t:dss_office_num=42 t:workforce_investment_area=Eastern t:town_num=3 t:judicial_geographical_area="Geographical Area 11" t:community_action_agency="The Access Community Action Agency, Inc" t:service_delivery_area="Northeast Service Delivery Area" t:judicial_district="Windham Judicial District" t:state_police_troop=C t:dcf_region="REGION 3" t:health_district_or_status="Eastern Highlands Health District" t:dcf_office=WILLIMANTIC t:county=Windham t:planning_region_cog="Northeastern CT" t:regional_education_service_center=EASTCONN t:dot_maintenance_district=2 t:dss_region_num=1 t:dmhas_service_region="REGION 3" t:town=Ashford t:labor_market_area="Hartford LMA" m:2010_population=4317 m:emergency_planning_region=4
```

## Meta Commands

```ls
metric m:2010_population p:integer l:"2010 POPULATION" t:dataTypeName=number

metric m:emergency_planning_region p:integer l:"EMERGENCY PLANNING REGION" t:dataTypeName=number

entity e:ex8d-mq3p l:"Index of Municipalities and Administrative and Planning Regions (work in progress)" t:attribution="Chief Data Officer" t:url=https://data.ct.gov/api/views/ex8d-mq3p

property e:ex8d-mq3p t:meta.view v:id=ex8d-mq3p v:category=Government v:averageRating=0 v:name="Index of Municipalities and Administrative and Planning Regions (work in progress)" v:attribution="Chief Data Officer"

property e:ex8d-mq3p t:meta.view.license v:name="Public Domain"

property e:ex8d-mq3p t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:ex8d-mq3p t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | town_num | town         | 2010_population | planning_region_cog | county     | regional_education_service_center | health_district_or_status           | labor_market_area         | workforce_investment_area | dss_office_num | dss_region_num | dcf_office  | dcf_region | dmhas_service_region | service_delivery_area                    | dot_maintenance_district | emergency_planning_region | judicial_district                 | judicial_geographical_area | state_police_troop | community_action_agency                        | 
| =========== | ======== | ============ | =============== | =================== | ========== | ================================= | =================================== | ========================= | ========================= | ============== | ============== | =========== | ========== | ==================== | ======================================== | ======================== | ========================= | ================================= | ========================== | ================== | ============================================== | 
| 1469435522  | 1        | Andover      | 3303            | Capitol             | Tolland    | EASTCONN                          | Eastern Highlands Health District   | Hartford LMA              | North Central             | 11             | 1              | MANCHESTER  | REGION 4   | REGION 4             | Hartford Service Delivery Area           | 1                        | 3                         | Tolland Judicial District         | Geographical Area 19       | K                  | The Access Community Action Agency, Inc        | 
| 1469435522  | 2        | Ansonia      | 19249           | Naugatuck Valley    | New Haven  | ACES                              | Naugatuck Valley Health District    | Bridgeport - Stamford LMA | Southwest                 | 20             | 2              | MILFORD     | REGION 2   | REGION 2             | Southwest Service Delivery Area          | 4                        | 2                         | Ansonia-Milford Judicial District | Geographical Area 5        | I                  | Training, Education, and Manpower, Inc. (TEAM) | 
| 1469435522  | 3        | Ashford      | 4317            | Northeastern CT     | Windham    | EASTCONN                          | Eastern Highlands Health District   | Hartford LMA              | Eastern                   | 42             | 1              | WILLIMANTIC | REGION 3   | REGION 3             | Northeast Service Delivery Area          | 2                        | 4                         | Windham Judicial District         | Geographical Area 11       | C                  | The Access Community Action Agency, Inc        | 
| 1469435522  | 4        | Avon         | 18098           | Capitol             | Hartford   | CREC                              | Farmington Valley Health District   | Hartford LMA              | North Central             | 10             | 1              | NEW BRITAIN | REGION 6   | REGION 4             | Hartford Service Delivery Area           | 4                        | 3                         | Hartford Judicial District        | Geographical Area 14       | H                  | Community Renewal Team (CRT)                   | 
| 1469435522  | 5        | Barkhamsted  | 3799            | Northwest Hills     | Litchfield | Education Connection              | Farmington Valley Health District   | Hartford LMA              | Northwest                 | 62             | 3              | TORRINGTON  | REGION 5   | REGION 5             | Danbury/Torrington Service Delivery Area | 4                        | 5                         | Litchfield Judicial District      | Geographical Area 18       | B                  | New Opportunities, Inc. (NOI)                  | 
| 1469435522  | 6        | Beacon Falls | 6049            | Naugatuck Valley    | New Haven  | ACES                              | Naugatuck Valley Health District    | Waterbury LMA             | Southwest                 | 60             | 3              | WATERBURY   | REGION 5   | REGION 5             | Waterbury Service Delivery Area          | 4                        | 5                         | Ansonia-Milford Judicial District | Geographical Area 5        | I                  | Training, Education, and Manpower, Inc. (TEAM) | 
| 1469435522  | 7        | Berlin       | 19866           | Capitol             | Hartford   | CREC                              | Central Connecticut Health District | Hartford LMA              | North Central             | 52             | 1              | NEW BRITAIN | REGION 6   | REGION 4             | Mid-Connecticut Service Delivery Area    | 1                        | 3                         | New Britain Judicial District     | Geographical Area 15       | H                  | New Opportunities, Inc. (NOI)                  | 
| 1469435522  | 8        | Bethany      | 5563            | South Central CT    | New Haven  | ACES                              | Quinnipack Valley Health District   | New Haven LMA             | South Central             | 20             | 2              | MILFORD     | REGION 2   | REGION 2             | New Haven Service Delivery Area          | 3                        | 2                         | New Haven Judicial District       | Geographical Area 23       | I                  | Training, Education, and Manpower, Inc. (TEAM) | 
| 1469435522  | 9        | Bethel       | 18584           | Western CT          | Fairfield  | Education Connection              | Full-Time                           | Danbury LMA               | Northwest                 | 31             | 3              | DANBURY     | REGION 5   | REGION 5             | Danbury/Torrington Service Delivery Area | 4                        | 5                         | Danbury Judicial District         | Geographical Area 3        | A                  | Community Action Committee of Danbury (CACD)   | 
| 1469435522  | 10       | Bethlehem    | 3607            | Naugatuck Valley    | Litchfield | Education Connection              | Torrington Area Health District     | Torrington LMA            | Northwest                 | 62             | 3              | TORRINGTON  | REGION 5   | REGION 5             | Waterbury Service Delivery Area          | 4                        | 5                         | Litchfield Judicial District      | Geographical Area 18       | L                  | New Opportunities, Inc. (NOI)                  | 
```