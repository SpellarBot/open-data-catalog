# SFMTA Bikeway Network

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sfmta-bikeway-network) |
| Metadata | [Link](https://data.sfgov.org/api/views/x3cv-qums) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/x3cv-qums/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/x3cv-qums/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | x3cv-qums |
| Name | SFMTA Bikeway Network |
| Category | Transportation |
| Tags | bike network, bikeway network, bicycle network, bicycle routes, bicycle paths, bicycle lanes, bike lanes, bike paths, bike routes |
| Created | 2016-08-18T20:12:55Z |
| Publication Date | 2016-10-04T18:28:05Z |

## Description

The network of bike routes, lanes, and paths around the city of San Francisco. Maintained by the SFMTA. This data is subject to change and the SFMTA does not assume any responsibility or liability for any property damage, injury, or other adverse circumstances that may arise while using this mapping data. The dataset is updated quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | series tag     | object_id                   | Object ID                   | text      | number      |
| Yes      | series tag     | cnn_id                      | CNN ID                      | text      | number      |
| Yes      | series tag     | street_name                 | Street Name                 | text      | text        |
| Yes      | series tag     | street_type                 | Street Type                 | text      | text        |
| Yes      | series tag     | from_street                 | From Street                 | text      | text        |
| Yes      | series tag     | to_street                   | To Street                   | text      | text        |
| Yes      | series tag     | facility_type               | Facility Type               | text      | text        |
| Yes      | series tag     | number_of_directions        | Number of Directions        | text      | text        |
| Yes      | numeric metric | length_feet                 | Length Feet                 | number    | number      |
| Yes      | series tag     | surface_treatments          | Surface Treatments          | text      | text        |
| Yes      | series tag     | barrier_type                | Barrier Type                | text      | text        |
| Yes      | series tag     | innovative_treatments       | Innovative Treatments       | text      | text        |
| Yes      | series tag     | notes                       | Notes                       | text      | text        |
| Yes      | series tag     | direction                   | Direction                   | text      | text        |
| Yes      | numeric metric | double                      | Double                      | number    | number      |
| No       |                | fiscal_year_installed       | Fiscal Year Installed       | number    | number      |
| Yes      | numeric metric | fiscal_quarter_installed    | Fiscal Quarter Installed    | number    | number      |
| Yes      | series tag     | full_street                 | Full Street                 | text      | text        |
| Yes      | numeric metric | length_miles                | Length Miles                | number    | number      |
| Yes      | numeric metric | sharrow                     | Sharrow                     | number    | number      |
| Yes      | numeric metric | last_upgraded               | Last Upgraded               | number    | number      |
| Yes      | numeric metric | small_street_sweeper_needed | Small Street Sweeper Needed | number    | number      |
| Yes      | numeric metric | contraflow                  | Contraflow                  | number    | number      |
| No       |                | install_year                | Install Year                | number    | number      |
| Yes      | numeric metric | install_month               | Install Month               | number    | number      |
| Yes      | numeric metric | update_month                | Update Month                | number    | number      |
| Yes      | time           | last_edited_date            | Last Edited Date            | date      | date        |
| No       |                | geom                        | Geom                        | line      | line        |
```

## Time Field

```ls
Value = last_edited_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = install_year,geom,fiscal_year_installed
```

## Data Commands

```ls
series e:x3cv-qums d:2016-07-01T00:00:00.000Z t:to_street="SUNSET BLVD" t:object_id=1 t:street_name="LAKE MERCED" t:facility_type="BIKE PATH" t:number_of_directions=2W t:cnn_id=8044000 t:full_street="Lake Merced Blvd" t:from_street="BERKSHIRE WY" t:street_type=BLVD m:contraflow=0 m:sharrow=0 m:length_miles=0.36 m:fiscal_quarter_installed=0 m:double=0 m:last_upgraded=0 m:small_street_sweeper_needed=0

series e:x3cv-qums d:2016-07-01T00:00:00.000Z t:to_street="COLBY ST" t:object_id=2 t:street_name=MANSELL t:facility_type="BIKE LANE" t:number_of_directions=2W t:cnn_id=8671202 t:full_street="Mansell St" t:from_street="DARTMOUTH ST" t:street_type=ST m:contraflow=0 m:sharrow=0 m:length_miles=0.06 m:fiscal_quarter_installed=0 m:double=1 m:last_upgraded=0 m:small_street_sweeper_needed=0

series e:x3cv-qums d:2016-07-01T00:00:00.000Z t:to_street="3RD ST" t:object_id=3 t:street_name=PALOU t:facility_type="BIKE ROUTE" t:number_of_directions=2W t:cnn_id=10222000 t:full_street="Palou Ave" t:from_street="LANE ST" t:street_type=AVE m:contraflow=0 m:sharrow=1 m:length_miles=0.13 m:fiscal_quarter_installed=0 m:double=0 m:last_upgraded=0 m:small_street_sweeper_needed=0
```

## Meta Commands

```ls
metric m:length_feet p:long l:"Length Feet" t:dataTypeName=number

metric m:double p:long l:Double t:dataTypeName=number

metric m:fiscal_quarter_installed p:long l:"Fiscal Quarter Installed" t:dataTypeName=number

metric m:length_miles p:long l:"Length Miles" t:dataTypeName=number

metric m:sharrow p:long l:Sharrow t:dataTypeName=number

metric m:last_upgraded p:long l:"Last Upgraded" t:dataTypeName=number

metric m:small_street_sweeper_needed p:long l:"Small Street Sweeper Needed" t:dataTypeName=number

metric m:contraflow p:long l:Contraflow t:dataTypeName=number

metric m:install_month p:long l:"Install Month" t:dataTypeName=number

metric m:update_month p:long l:"Update Month" t:dataTypeName=number

entity e:x3cv-qums l:"SFMTA Bikeway Network" t:url=https://data.sfgov.org/api/views/x3cv-qums

property e:x3cv-qums t:meta.view v:id=x3cv-qums v:category=Transportation v:averageRating=0 v:name="SFMTA Bikeway Network"

property e:x3cv-qums t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:x3cv-qums t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:x3cv-qums t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| object_id | cnn_id   | street_name | street_type | from_street     | to_street        | facility_type | number_of_directions | length_feet | surface_treatments    | barrier_type   | innovative_treatments | notes | direction | double | fiscal_year_installed | fiscal_quarter_installed | full_street      | length_miles | sharrow | last_upgraded | small_street_sweeper_needed | contraflow | install_year | install_month | update_month | last_edited_date | geom                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 
| ========= | ======== | =========== | =========== | =============== | ================ | ============= | ==================== | =========== | ===================== | ============== | ===================== | ===== | ========= | ====== | ===================== | ======================== | ================ | ============ | ======= | ============= | =========================== | ========== | ============ | ============= | ============ | ================ | =========================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 1         | 8044000  | LAKE MERCED | BLVD        | BERKSHIRE WY    | SUNSET BLVD      | BIKE PATH     | 2W                   |             |                       |                |                       |       |           | 0      | 0                     | 0                        | Lake Merced Blvd | 0.36         | 0       | 0             | 0                           | 0          | 0            |               |              | 1467331200       | LINESTRING (-122.49801485886276 37.73128276757398, -122.4980734770587 37.73116952038867, -122.49788391454668 37.73073514616201, -122.49736686821419 37.729673315100364, -122.49724611883724 37.729494703157094, -122.49703066087292 37.729307468829816, -122.49671237025011 37.72912879531403, -122.49637070530183 37.729039142744796, -122.4960480406236 37.72901733972788, -122.49570145148454 37.72906411663118, -122.49348315441435 37.729601599064246) | 
| 2         | 8671202  | MANSELL     | ST          | DARTMOUTH ST    | COLBY ST         | BIKE LANE     | 2W                   |             |                       |                |                       |       |           | 1      | 0                     | 0                        | Mansell St       | 0.06         | 0       | 0             | 0                           | 0          | 1999         |               |              | 1467331200       | LINESTRING (-122.40895904702053 37.71948742389068, -122.41000041733915 37.71921820642891)                                                                                                                                                                                                                                                                                                                                                                   | 
| 3         | 10222000 | PALOU       | AVE         | LANE ST         | 3RD ST           | BIKE ROUTE    | 2W                   |             |                       |                |                       |       |           | 0      | 0                     | 0                        | Palou Ave        | 0.13         | 1       | 0             | 0                           | 0          | 2010         |               |              | 1467331200       | LINESTRING (-122.3890482737839 37.73292383783316, -122.39098109619937 37.734018815212366)                                                                                                                                                                                                                                                                                                                                                                   | 
| 4         | 13261000 | VICENTE     | ST          | 35TH AV         | 36TH AV          | BIKE ROUTE    | 2W                   |             |                       |                |                       |       |           | 0      | 0                     | 0                        | Vicente St       | 0.06         | 0       | 0             | 0                           | 0          | 2006         |               |              | 1467331200       | LINESTRING (-122.49258907066658 37.73857256358204, -122.49368137456592 37.73852414347019)                                                                                                                                                                                                                                                                                                                                                                   | 
| 5         | 3483000  | CABRILLO    | ST          | 16TH AV         | 17TH AV          | BIKE LANE     | 2W                   |             |                       |                |                       |       |           | 1      | 0                     | 0                        | Cabrillo St      | 0.06         | 0       | 0             | 0                           | 0          | 1974         |               |              | 1467331200       | LINESTRING (-122.47469933818041 37.774881513829556, -122.4757641925427 37.77483295848796)                                                                                                                                                                                                                                                                                                                                                                   | 
| 6         | 11535000 | SANCHEZ     | ST          | 27TH ST         | COMERFORD ST     | BIKE ROUTE    | 2W                   |             |                       |                |                       |       |           | 0      | 0                     | 0                        | Sanchez St       | 0.06         | 1       | 0             | 0                           | 0          | 2010         |               |              | 1467331200       | LINESTRING (-122.42920641186281 37.746767868427206, -122.429167755667 37.746364567523514, -122.4291294551169 37.745964982210744)                                                                                                                                                                                                                                                                                                                            | 
| 7         | 2157101  | ALEMANY     | BLVD        | HWY 280 ON RAMP | HWY 280 OFF RAMP | BIKE LANE     | 1W                   |             |                       | SAFE-HIT POSTS | SEPARATED BIKEWAY     |       | E         | 0      | 0                     | 0                        | Alemany Blvd     | 0.59         | 0       | 0             | 1                           | 0          | 2011         |               |              | 1467331200       | LINESTRING (-122.41982075781544 37.73168987923554, -122.41901338062551 37.73166019199144, -122.41573966668165 37.73139516456928, -122.41517992408488 37.731557248918286, -122.4147828681187 37.731832359356126, -122.41422814682296 37.73273689290226, -122.41386894860132 37.73302257819595, -122.41247279303444 37.733630880168405, -122.41168560585629 37.73419235005988, -122.41085433781365 37.734646385286865, -122.41085771581324 37.73473761351)    | 
| 8         | 6128201  | GENEVA      | AVE         | HOWTH ST        | LOUISBURG ST     | BIKE ROUTE    | 2W                   |             |                       |                |                       |       |           | 1      | 0                     | 0                        | Geneva Ave       | 0.05         | 1       | 0             | 0                           | 0          | 2010         |               |              | 1467331200       | LINESTRING (-122.45013143988544 37.722087733006326, -122.44930895518077 37.72175734951992)                                                                                                                                                                                                                                                                                                                                                                  | 
| 9         | 11131000 | ROMAIN      | ST          | GRAND VIEW AV   | MARKET ST        | BIKE ROUTE    | 2W                   |             |                       |                |                       |       |           | 1      | 0                     | 0                        | Romain St        | 0.05         | 1       | 0             | 0                           | 0          | 2012         |               |              | 1467331200       | LINESTRING (-122.44014710970418 37.75642762594732, -122.44091194605727 37.75625088742262, -122.44101197435748 37.75622342570756)                                                                                                                                                                                                                                                                                                                            | 
| 10        | 10418000 | PIERCE      | ST          | WALLER ST       | HAIGHT ST        | BIKE ROUTE    | 2W                   |             | GREEN-BACKED SHARROWS |                | WIGGLE IMPROVEMENTS   |       |           | 1      | 0                     | 0                        | Pierce St        | 0.07         | 1       | 0             | 0                           | 0          | 0            |               |              | 1467331200       | LINESTRING (-122.43356037695817 37.77076017416718, -122.43374799010535 37.771693216458964)                                                                                                                                                                                                                                                                                                                                                                  | 
```