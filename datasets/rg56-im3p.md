# IDOT Aeronautics - Aviation Programs Sponsored by Universities in Illinois

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idot-aeronautics-aviation-programs-sponsored-by-universities-in-illinois-ea7a9) |
| Metadata | [Link](https://data.illinois.gov/api/views/rg56-im3p) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/rg56-im3p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/rg56-im3p/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | rg56-im3p |
| Name | IDOT Aeronautics - Aviation Programs Sponsored by Universities in Illinois |
| Attribution | Illinois Department of Transportation Division of Aeronautics |
| Category | Transportation |
| Tags | aviation, programs, universities, flight, school, flying, aero |
| Created | 2012-01-20T19:30:53Z |
| Publication Date | 2012-01-20T19:43:16Z |

## Columns

```ls
| Included | Schema Type | Field Name              | Name                       | Data Type | Render Type |
| ======== | =========== | ======================= | ========================== | ========= | =========== |
| No       | time        | :updated_at             | updated_at                 | meta_data | meta_data   |
| Yes      | series tag  | institution             | Institution                | text      | text        |
| No       |             | address                 | Address                    | text      | text        |
| Yes      | series tag  | web_site                | Web Site                   | text      | text        |
| Yes      | series tag  | contact_number          | Contact Number             | text      | text        |
| Yes      | series tag  | private_pilot           | Private Pilot              | text      | text        |
| Yes      | series tag  | commercial_pilot        | Commercial Pilot           | text      | text        |
| Yes      | series tag  | flight_inst_cfi_        | Flight Inst. (CFI)         | text      | text        |
| Yes      | series tag  | airline_transport_pilot | Airline Transport Pilot    | text      | text        |
| Yes      | series tag  | aircraft_maint_mechanic | Aircraft Maint. / Mechanic | text      | text        |
| Yes      | series tag  | aviation_dispatcher     | Aviation Dispatcher        | text      | text        |
| Yes      | series tag  | air_traffic_controller  | Air Traffic Controller     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:rg56-im3p d:2012-01-20T11:31:26.000Z t:contact_number=630-513-2224 t:commercial_pilot=Y t:flight_inst_cfi_=Y t:air_traffic_controller=N t:aircraft_maint_mechanic=N t:airline_transport_pilot=Y t:private_pilot=Y t:aviation_dispatcher=N t:web_site=www.illinoisaviation.com t:institution="Illinois Aviation Academy Inc" m:row_number.rg56-im3p=1

series e:rg56-im3p d:2012-01-20T11:31:26.000Z t:contact_number=800-897-9000 t:commercial_pilot=Y t:flight_inst_cfi_=Y t:air_traffic_controller=N t:aircraft_maint_mechanic=Y t:airline_transport_pilot=Y t:private_pilot=Y t:aviation_dispatcher=N t:web_site=www.lewisu.edu/aviation t:institution="Lewis University" m:row_number.rg56-im3p=2

series e:rg56-im3p d:2012-01-20T11:31:26.000Z t:contact_number=815-787-4400 t:commercial_pilot=Y t:flight_inst_cfi_=Y t:air_traffic_controller=N t:aircraft_maint_mechanic=N t:airline_transport_pilot=N t:private_pilot=Y t:aviation_dispatcher=N t:web_site=www.midwestflightacademy.com t:institution="Midwest Flight Academy" m:row_number.rg56-im3p=3
```

## Meta Commands

```ls
metric m:row_number.rg56-im3p p:long l:"Row Number"

entity e:rg56-im3p l:"IDOT Aeronautics - Aviation Programs Sponsored by Universities in Illinois" t:attribution="Illinois Department of Transportation Division of Aeronautics" t:url=https://data.illinois.gov/api/views/rg56-im3p

property e:rg56-im3p t:meta.view v:id=rg56-im3p v:category=Transportation v:averageRating=0 v:name="IDOT Aeronautics - Aviation Programs Sponsored by Universities in Illinois" v:attribution="Illinois Department of Transportation Division of Aeronautics"

property e:rg56-im3p t:meta.view.license v:name="Public Domain"

property e:rg56-im3p t:meta.view.owner v:id=2fjt-8tt3 v:screenName=data.il.admin v:displayName=data.il.admin

property e:rg56-im3p t:meta.view.tableauthor v:id=2fjt-8tt3 v:screenName=data.il.admin v:displayName=data.il.admin
```

## Top Records

```ls
| :updated_at | institution                                         | address                                       | web_site                           | contact_number         | private_pilot   | commercial_pilot | flight_inst_cfi_ | airline_transport_pilot | aircraft_maint_mechanic | aviation_dispatcher | air_traffic_controller | 
| =========== | =================================================== | ============================================= | ================================== | ====================== | =============== | ================ | ================ | ======================= | ======================= | =================== | ====================== | 
| 1327059086  | Illinois Aviation Academy Inc                       | 32w751 Tower Road, West Chicago, IL 60185     | www.illinoisaviation.com           | 630-513-2224           | Y               | Y                | Y                | Y                       | N                       | N                   | N                      | 
| 1327059086  | Lewis University                                    | One University Parkway, Romeoville, IL 60441  | www.lewisu.edu/aviation            | 800-897-9000           | Y               | Y                | Y                | Y                       | Y                       | N                   | N                      | 
| 1327059086  | Midwest Flight Academy                              | 3232 Pleasant Street, DeKalb, IL 60115        | www.midwestflightacademy.com       | 815-787-4400           | Y               | Y                | Y                | N                       | N                       | N                   | N                      | 
| 1327059086  | Quincy University                                   | 1800 College Avenue, Quincy, IL 62301         | www.quincy.edu                     | 217-228-5432 Ext. 3232 | Y               | Y                | Y                | N                       | N                       | N                   | N                      | 
| 1327059086  | Southern Illinois University Carbondale             | 665 North Airport Road, Murphysboro, IL 62966 | www.aviation.siu.edu               | 618-453-1147           | Y               | Y                | Y                | N                       | Y                       | N                   | N                      | 
| 1327059086  | University of Illinois Institute of Aviation        | 1 Airport Road, Savoy, IL 61874               | www.aviation.illinois.edu/avimain  | 217-244-8671           | Y               | Y                | Y                | N                       | N                       | N                   | N                      | 
| 1327059086  | Southwestern Illinois College                       | 4950 Maryville Rd, Granite City, IL 62040     | www.swic.edu/divisions.aspx?id=387 | 618-931-0600 Ext. 6661 | Y               | Y                | Y                | N                       | Y                       | N                   | N                      | 
| 1327059086  | Parks College of Engineering, Aviation & Technology | 3450 Lindell Boulevard, Saint Louis, MO 63103 | http://parks.slu.edu               | 800-758-3678           | Y               | Y                | Y                | N                       | N                       | N                   | N                      | 
| 1327059086  | Lincoln Land Community College                      | 5250 Shepherd Road, Springfield, IL 62794     | www.llcc.edu                       | 217-786-2200           | Y (basic pilot) | N                | N                | N                       | Y                       | N                   | Y                      | 
| 1327059086  | Kishwaukee College                                  | 21193 Malta Road, Malta, IL 60150             | www.kishwaukeecollege.edu          | 815-825-2086           | Y               | Y                | N                | N                       | N                       | N                   | N                      | 
```