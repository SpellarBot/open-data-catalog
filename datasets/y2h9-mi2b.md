# SDOT Existing and Planned Bike Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-existing-and-planned-bike-facilities) |
| Metadata | [Link](https://data.seattle.gov/api/views/y2h9-mi2b) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/y2h9-mi2b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/y2h9-mi2b/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | y2h9-mi2b |
| Name | SDOT Existing and Planned Bike Facilities |
| Tags | bike master plan, bike lanes, multi-use-trails, sharrows |
| Created | 2016-12-28T18:10:54Z |
| Publication Date | 2016-12-28T18:20:12Z |

## Description

Existing and proposed bicycle-related facilities within the city limits. Existing facilities are currently marked and available to the public, planned facilities are taken directly from the Seattle Bicycle Master Plan and may change through the project development process.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type  | Render Type |
| ======== | ============== | ====================== | ====================== | ========== | =========== |
| Yes      | series tag     | objectid               | OBJECTID               | text       | number      |
| Yes      | series tag     | street_name            | STREET_NAME            | text       | text        |
| Yes      | numeric metric | length_miles           | LENGTH_MILES           | number     | number      |
| Yes      | time           | date_completed         | DATE_COMPLETED         | date       | date        |
| Yes      | series tag     | existing_facility_type | EXISTING_FACILITY_TYPE | text       | text        |
| Yes      | series tag     | planned_facility_type  | PLANNED_FACILITY_TYPE  | text       | text        |
| Yes      | numeric metric | catalytic_projects     | CATALYTIC_PROJECTS     | number     | number      |
| Yes      | series tag     | status                 | STATUS                 | text       | text        |
| Yes      | series tag     | network                | NETWORK                | text       | text        |
| Yes      | numeric metric | compkey                | COMPKEY                | number     | number      |
| Yes      | series tag     | project_number         | PROJECT_NUMBER         | text       | text        |
| No       |                | date_planned           | DATE_PLANNED           | date       | date        |
| No       |                | date_expired           | DATE_EXPIRED           | date       | date        |
| No       |                | shape                  | Shape                  | geospatial | geospatial  |
| Yes      | numeric metric | shape_length           | Shape_Length           | number     | number      |
```

## Time Field

```ls
Value = date_completed
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date_planned,date_expired,shape
```

## Data Commands

```ls
series e:y2h9-mi2b d:2017-04-21T08:07:03.655Z t:shape.longitude=-122.29219599499999 t:status=NA t:shape.needs_recoding=false t:street_name="33RD AVE NE" t:planned_facility_type="Neighborhood Greenway" t:project_number=228 t:shape.latitude=47.672148211000035 t:objectid=1 t:network=LOCAL m:length_miles=0.12661266000000002 m:shape_length=668.5148460863437 m:catalytic_projects=0 m:compkey=5122

series e:y2h9-mi2b d:2017-04-21T08:07:03.655Z t:shape.longitude=-122.33914466199997 t:status=NA t:shape.needs_recoding=false t:street_name="WOODLAWN AVE N" t:planned_facility_type="Neighborhood Greenway" t:project_number=367 t:shape.latitude=47.66286630800005 t:objectid=2 t:network=LOCAL m:length_miles=0.04923909 m:shape_length=259.9823967351382 m:catalytic_projects=0 m:compkey=13682

series e:y2h9-mi2b d:2017-04-21T08:07:03.655Z t:shape.longitude=-122.35447474499995 t:status=NA t:shape.needs_recoding=false t:street_name="PHINNEY AVE N" t:planned_facility_type="Neighborhood Greenway" t:project_number=680 t:shape.latitude=47.65224596400003 t:objectid=3 t:network=LOCAL m:length_miles=0.1316758 m:shape_length=695.2482480176868 m:catalytic_projects=0 m:compkey=12132
```

## Meta Commands

```ls
metric m:length_miles p:decimal l:LENGTH_MILES d:LENGTH_MILES t:dataTypeName=number

metric m:catalytic_projects p:integer l:CATALYTIC_PROJECTS d:CATALYTIC_PROJECTS t:dataTypeName=number

metric m:compkey p:integer l:COMPKEY d:COMPKEY t:dataTypeName=number

metric m:shape_length p:decimal l:Shape_Length d:Shape_Length t:dataTypeName=number

entity e:y2h9-mi2b l:"SDOT Existing and Planned Bike Facilities" t:url=https://data.seattle.gov/api/views/y2h9-mi2b

property e:y2h9-mi2b t:meta.view v:id=y2h9-mi2b v:averageRating=0 v:name="SDOT Existing and Planned Bike Facilities"

property e:y2h9-mi2b t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:y2h9-mi2b t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | street_name    | length_miles                                                | date_completed | existing_facility_type | planned_facility_type       | catalytic_projects | status | network  | compkey | project_number | date_planned | date_expired | shape                                                                                                                                                         | shape_length                                     | 
| ======== | ============== | =========================================================== | ============== | ====================== | =========================== | ================== | ====== | ======== | ======= | ============== | ============ | ============ | ============================================================================================================================================================= | ================================================ | 
| 1        | 33RD AVE NE    | 0.1266126600000000157475454898303723894059658050537109375   |                |                        | Neighborhood Greenway       | 0                  | NA     | LOCAL    | 5122    | 228            |              |              | [null, 47.672148211000035, -122.29219599499999, null, false, {paths=[[[-122.29219599499999, 47.672148211000035], [-122.29220250399999, 47.67398092800005]]]}] | 668.5148460863437094303662888705730438232421875  | 
| 2        | WOODLAWN AVE N | 0.04923908999999999924757076996684190817177295684814453125  |                |                        | Neighborhood Greenway       | 0                  | NA     | LOCAL    | 13682   | 367            |              |              | [null, 47.66286630800005, -122.33914466199997, null, false, {paths=[[[-122.33914466199997, 47.66286630800005], [-122.33913891299994, 47.663579036000044]]]}]  | 259.9823967351381952539668418467044830322265625  | 
| 3        | PHINNEY AVE N  | 0.131675800000000009504219633527100086212158203125          |                |                        | Neighborhood Greenway       | 0                  | NA     | LOCAL    | 12132   | 680            |              |              | [null, 47.65224596400003, -122.35447474499995, null, false, {paths=[[[-122.35447474499995, 47.65224596400003], [-122.35446577199997, 47.654151968000065]]]}]  | 695.2482480176868193666450679302215576171875     | 
| 4        | 43RD AVE S     | 0.1270071299999999958618701612067525275051593780517578125   |                |                        | Neighborhood Greenway       | 0                  | NA     | LOCAL    | 6672    | 757            |              |              | [null, 47.538890751000054, -122.27942314899997, null, false, {paths=[[[-122.27942314899997, 47.538890751000054], [-122.27938527799995, 47.53705256000006]]]}] | 670.5727869114344912304659374058246612548828125  | 
| 5        | HIGHLAND DR    | 0.06095762999999999875999634468826116062700748443603515625  |                |                        | Neighborhood Greenway       | 0                  | NA     | LOCAL    | 10885   | 218            |              |              | [null, 47.62977027800008, -122.35536205099999, null, false, {paths=[[[-122.35536205099999, 47.62977027800008], [-122.35405676499994, 47.629765011000075]]]}]  | 321.8562871958071127664879895746707916259765625  | 
| 6        | AIRPORT WAY S  | 0.1267735299999999953879381564547657035291194915771484375   |                |                        | In Street, Major Separation | 0                  | NA     | CITYWIDE | 8658    | 355            |              |              | [null, 47.588224841000056, -122.32139126699997, null, false, {paths=[[[-122.32139126699997, 47.588224841000056], [-122.32139267999997, 47.58638978500005]]]}] | 669.364224105965831768116913735866546630859375   | 
| 7        | 32ND AVE NE    | 0.0487155999999999977934095340970088727772235870361328125   |                |                        | Neighborhood Greenway       | 0                  | NA     | LOCAL    | 4950    | 224            |              |              | [null, 47.69021795700007, -122.29339569599995, null, false, {paths=[[[-122.29339569599995, 47.69021795700007], [-122.29339167299997, 47.690923111000075]]]}]  | 257.218386181610412677400745451450347900390625   | 
| 8        | WOODLAWN AVE N | 0.0512920600000000004303757350498926825821399688720703125   |                |                        | Neighborhood Greenway       | 0                  | NA     | LOCAL    | 13684   | 367            |              |              | [null, 47.664291983000055, -122.33913316299999, null, false, {paths=[[[-122.33913316299999, 47.664291983000055], [-122.33912717299995, 47.66503442700008]]]}] | 270.82205743075809323272551409900188446044921875 | 
| 9        | NW 77TH ST     | 0.050000250000000003025579786708476603962481021881103515625 |                |                        | Neighborhood Greenway       | 0                  | NA     | LOCAL    | 18860   | 334            |              |              | [null, 47.68504712300006, -122.37786323299997, null, false, {paths=[[[-122.37786323299997, 47.68504712300006], [-122.37893498199998, 47.68503911700003]]]}]   | 264.00134414246866754183429293334484100341796875 | 
| 10       | S FERDINAND ST | 0.05877575000000000160493840439812629483640193939208984375  |                |                        | Neighborhood Greenway       | 0                  | NA     | CITYWIDE | 19971   | 724            |              |              | [null, 47.55822044800004, -122.27445037999996, null, false, {paths=[[[-122.27445037999996, 47.55822044800004], [-122.27319355699996, 47.558226965000074]]]}]  | 310.3359360926214094433817081153392791748046875  | 
```