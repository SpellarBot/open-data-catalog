# Wastewater Treatment Plants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wastewater-treatment-plants-5f9d0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/b79y-xcs9) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/b79y-xcs9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/b79y-xcs9/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | b79y-xcs9 |
| Name | Wastewater Treatment Plants |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | dep, department of environmental protection, environment, wastewater, treatment, wastewater treatment plants, healthy living |
| Created | 2013-01-31T16:45:10Z |
| Publication Date | 2013-06-21T19:44:51Z |

## Description

Wastewater Treatment Plants Visit the below link for info on SPEDES permits. http://www.nyc.gov/html/dep/pdf/harbor/spdes_bmp_report_2012.pdf

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type | Render Type |
| ======== | ============== | =============================== | =============================== | ========= | =========== |
| No       | time           | :updated_at                     | updated_at                      | meta_data | meta_data   |
| Yes      | series tag     | wastewater_treatment_plant_name | Wastewater Treatment Plant Name | text      | text        |
| Yes      | series tag     | location                        | Location                        | text      | text        |
| Yes      | series tag     | plant_in_operation              | Plant in operation              | text      | text        |
| Yes      | series tag     | design_capacity                 | Design Capacity                 | text      | text        |
| Yes      | series tag     | dewatering                      | Dewatering                      | text      | text        |
| Yes      | numeric metric | population_served               | Population Served               | number    | number      |
| Yes      | series tag     | receiving_waterbody             | Receiving Waterbody             | text      | text        |
| Yes      | series tag     | drainage_area                   | Drainage Area                   | text      | text        |
| Yes      | numeric metric | plant_staff                     | Plant Staff                     | number    | number      |
| Yes      | series tag     | note                            | Note                            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:b79y-xcs9 d:2013-01-31T08:45:12.000Z t:design_capacity="85 MGD" t:location=East t:drainage_area="5,907 Acres, eastern section of Brooklyn, near Jamaica Bay" t:plant_in_operation=1944 t:receiving_waterbody="Jamaica Bay" t:dewatering="26th Ward" t:wastewater_treatment_plant_name="26th Ward WWTP" m:population_served=283428 m:plant_staff=93

series e:b79y-xcs9 d:2013-01-31T08:45:12.000Z t:design_capacity="150 MGD" t:location=North t:drainage_area="15,203 Acres, northeast section of Queens" t:plant_in_operation=1939 t:receiving_waterbody="Upper East River" t:dewatering="Bowery Bay" t:wastewater_treatment_plant_name="Bowery Bay WWTP" m:population_served=848328 m:plant_staff=81

series e:b79y-xcs9 d:2013-01-31T08:45:12.000Z t:design_capacity="110 MGD" t:location=East t:drainage_area="15,087 Acres, south and central Brooklyn" t:plant_in_operation=1935 t:receiving_waterbody="Jamaica Bay" t:dewatering="26th Ward" t:wastewater_treatment_plant_name="Coney Island WWTP" m:population_served=596326 m:plant_staff=69
```

## Meta Commands

```ls
metric m:population_served p:integer l:"Population Served" t:dataTypeName=number

metric m:plant_staff p:integer l:"Plant Staff" t:dataTypeName=number

entity e:b79y-xcs9 l:"Wastewater Treatment Plants" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/b79y-xcs9

property e:b79y-xcs9 t:meta.view v:id=b79y-xcs9 v:category=Environment v:attributionLink=http://www.nyc.gov/html/dep/html/wastewater/wwsystem-plants.shtml v:averageRating=0 v:name="Wastewater Treatment Plants" v:attribution="Department of Environmental Protection (DEP)"

property e:b79y-xcs9 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:b79y-xcs9 t:meta.view.tableauthor v:id=ya7g-926w v:screenName="Aakash Dalwani" v:displayName="Aakash Dalwani"
```

## Top Records

```ls
| :updated_at | wastewater_treatment_plant_name | location | plant_in_operation | design_capacity | dewatering                     | population_served | receiving_waterbody | drainage_area                                                                                                              | plant_staff | note                                                                                                                                             | 
| =========== | =============================== | ======== | ================== | =============== | ============================== | ================= | =================== | ========================================================================================================================== | =========== | ================================================================================================================================================ | 
| 1359621912  | 26th Ward WWTP                  | East     | 1944               | 85 MGD          | 26th Ward                      | 283428            | Jamaica Bay         | 5,907 Acres, eastern section of Brooklyn, near Jamaica Bay                                                                 | 93          |                                                                                                                                                  | 
| 1359621912  | Bowery Bay WWTP                 | North    | 1939               | 150 MGD         | Bowery Bay                     | 848328            | Upper East River    | 15,203 Acres, northeast section of Queens                                                                                  | 81          |                                                                                                                                                  | 
| 1359621912  | Coney Island WWTP               | East     | 1935               | 110 MGD         | 26th Ward                      | 596326            | Jamaica Bay         | 15,087 Acres, south and central Brooklyn                                                                                   | 69          |                                                                                                                                                  | 
| 1359621912  | Hunts Point WWTP                | North    | 1952               | 200 MGD         | Hunts Point                    | 684569            | Upper East River    | 16,664 Acres, eastern section of the Bronx                                                                                 | 108         |                                                                                                                                                  | 
| 1359621912  | Jamaica WWTP                    | East     | 1903 / 1943        | 100 MGD         | Jamaica WWTP                   | 728123            | Jamaica Bay         | 25,313 Acres, southern section of Queens                                                                                   | 66          |                                                                                                                                                  | 
| 1359621912  | Newtown Creek WWTP              | South    | 1967               | 310 MGD         | Hunts Point WWTP               | 1068012           | East River          | 15,656 Acres, south and eastern midtown sections of Manhattan, northeast section of Brooklyn and western section of Queens | 88          |                                                                                                                                                  | 
| 1359621912  | North River WWTP                | South    | 1986               | 170 MGD         | Wards Island WWTP              | 588772            | Hudson River        | 6,030 Acres, west side of Manhattan above Bank Street                                                                      | 109         | First and only Wastewater Treatment Plant in NYC to have a public park built on top. (http://www.nyc.gov/html/dep/html/wastewater/northri.shtml) | 
| 1359621912  | Rockaway WWTP                   | East     | 1952               | 45 MGD          | 26th Ward WWTP                 | 90474             | Jamaica Bay         | 6,259 Acres, Rockaway Peninsula                                                                                            | 41          |                                                                                                                                                  | 
| 1359621912  | Owls Head WWTP                  | East     | 1952               | 120 MGD         | 26th Ward / Wards Island WWTPs | 758007            | Upper New York Bay  | 12,947 Acres, western section of Brooklyn                                                                                  | 68          |                                                                                                                                                  | 
| 1359621912  | Wards Island WWTP               | North    | 1937               | 275 MGD         | Wards Island WWTP              | 1061558           | Upper East River    | 12,056 Acres, western section of the Bronx and upper east side of Manhattan                                                | 118         |                                                                                                                                                  | 
```