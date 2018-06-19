# SDOT Traffic Beacons

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/traffic-beacons) |
| Metadata | [Link](https://data.seattle.gov/api/views/iwrq-qjta) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/iwrq-qjta/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/iwrq-qjta/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | iwrq-qjta |
| Name | SDOT Traffic Beacons |
| Attribution | Seattle Department of Transportation |
| Category | Transportation |
| Tags | traffic, beacon, flashing, crosswalk, warning, fire, school, crossing, overhead, camera, metered, lighted, vision zero, sdot asset status and condition report, assets |
| Created | 2015-03-19T04:53:29Z |
| Publication Date | 2015-03-19T04:56:09Z |

## Description

Displays the locations of traffic beacons for fire, regulation, school zones, warnings and crosswalks in the City of Seattle.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | objectid                  | OBJECTID                  | text      | number      |
| Yes      | numeric metric | compkey                   | COMPKEY                   | number    | number      |
| Yes      | series tag     | comptype                  | COMPTYPE                  | text      | number      |
| Yes      | numeric metric | segkey                    | SEGKEY                    | number    | number      |
| Yes      | numeric metric | distance                  | DISTANCE                  | number    | number      |
| Yes      | numeric metric | width                     | WIDTH                     | number    | number      |
| Yes      | series tag     | unitid                    | UNITID                    | text      | text        |
| Yes      | series tag     | unittype                  | UNITTYPE                  | text      | text        |
| Yes      | series tag     | unitdesc                  | UNITDESC                  | text      | text        |
| Yes      | series tag     | ownership                 | OWNERSHIP                 | text      | text        |
| Yes      | series tag     | condition                 | CONDITION                 | text      | text        |
| No       |                | condition_assessment_date | CONDITION_ASSESSMENT_DATE | date      | date        |
| Yes      | series tag     | current_status            | CURRENT_STATUS            | text      | text        |
| No       |                | current_status_date       | CURRENT_STATUS_DATE       | date      | date        |
| Yes      | series tag     | category                  | CATEGORY                  | text      | text        |
| Yes      | time           | install_date              | INSTALL_DATE              | date      | date        |
| Yes      | series tag     | installer                 | INSTALLER                 | text      | text        |
| Yes      | series tag     | electr_wire_loc           | ELECTR_WIRE_LOC           | text      | text        |
| Yes      | series tag     | control_protocol_type     | CONTROL_PROTOCOL_TYPE     | text      | text        |
| Yes      | series tag     | metered                   | METERED                   | text      | text        |
| No       |                | last_pm_date              | LAST_PM_DATE              | date      | date        |
| No       |                | solar_install_date        | SOLAR_INSTALL_DATE        | date      | date        |
| Yes      | series tag     | hansen7id                 | HANSEN7ID                 | text      | text        |
| Yes      | series tag     | disphousingcond           | DISPHOUSINGCOND           | text      | text        |
| Yes      | series tag     | mount_type                | MOUNT_TYPE                | text      | text        |
| Yes      | series tag     | crosswalk_tub             | CROSSWALK_TUB             | text      | text        |
| Yes      | series tag     | flashing                  | FLASHING                  | text      | text        |
| Yes      | series tag     | attachment_condition      | ATTACHMENT_CONDITION      | text      | text        |
| Yes      | series tag     | pole_condition            | POLE_CONDITION            | text      | text        |
| No       |                | support_install_date      | SUPPORT_INSTALL_DATE      | date      | date        |
| Yes      | series tag     | span_condition            | SPAN_CONDITION            | text      | text        |
| Yes      | series tag     | control_condition         | CONTROL_CONDITION         | text      | text        |
| Yes      | series tag     | control_type              | CONTROL_TYPE              | text      | text        |
| Yes      | series tag     | modem_type                | MODEM_TYPE                | text      | text        |
| Yes      | series tag     | model_type                | MODEL_TYPE                | text      | text        |
| Yes      | series tag     | side                      | SIDE                      | text      | text        |
| Yes      | series tag     | school_speed_camera       | SCHOOL_SPEED_CAMERA       | text      | text        |
```

## Time Field

```ls
Value = install_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = condition_assessment_date,current_status_date,last_pm_date,solar_install_date,support_install_date
```

## Data Commands

```ls
series e:iwrq-qjta d:2017-04-21T09:28:55.130Z t:crosswalk_tub=Y t:flashing=Y t:category=BCN-XWK t:unitdesc="3RD AVE NW 0560 BLOCK C SIDE ( 508) 22 FT S/O NW 58TH ST (BCN-XWK)" t:unitid=BCN-189 t:school_speed_camera=N t:side=C t:metered=N t:comptype=16 t:objectid=1 t:unittype=BCN t:mount_type=TM-OVRHEAD m:distance=508 m:segkey=4457 m:compkey=573149

series e:iwrq-qjta d:2017-04-21T09:28:55.130Z t:electr_wire_loc=AUXPOLE t:comptype=16 t:crosswalk_tub=N t:unitdesc="1ST AVE NE 1220 BLOCK C SIDE ( 890) 0 FT S/O CORLISS S AVE N (BCN-REG)" t:category=BCN-REG t:flashing=Y t:attachment_condition=POOR t:unitid=BCN-115 t:school_speed_camera=N t:side=C t:metered=N t:span_condition=POOR t:disphousingcond=POOR t:objectid=2 t:unittype=BCN t:pole_condition=FAIR t:mount_type=TM-OVRHEAD m:distance=890 m:segkey=1103 m:compkey=568620

series e:iwrq-qjta d:2017-04-21T09:28:55.130Z t:electr_wire_loc=UG t:condition=POOR t:comptype=16 t:current_status=INSVC t:crosswalk_tub=N t:control_type=HARDWIRE t:flashing=Y t:category=BCN-REG t:unitdesc="2ND AVE S 0020 BLOCK C SIDE ( 306) 0 FT N/O S MAIN ST (BCN-REG)" t:attachment_condition=POOR t:ownership=SDOT t:unitid=BCN-75 t:school_speed_camera=N t:side=C t:metered=N t:span_condition=POOR t:installer=SDOT t:disphousingcond=POOR t:objectid=3 t:unittype=BCN t:pole_condition=GOOD t:mount_type=TM-OVRHEAD m:distance=306 m:segkey=2869 m:compkey=567676
```

## Meta Commands

```ls
metric m:compkey p:integer l:COMPKEY d:COMPKEY t:dataTypeName=number

metric m:segkey p:integer l:SEGKEY d:SEGKEY t:dataTypeName=number

metric m:distance p:integer l:DISTANCE d:DISTANCE t:dataTypeName=number

metric m:width p:integer l:WIDTH d:WIDTH t:dataTypeName=number

entity e:iwrq-qjta l:"SDOT Traffic Beacons" t:attribution="Seattle Department of Transportation" t:url=https://data.seattle.gov/api/views/iwrq-qjta

property e:iwrq-qjta t:meta.view v:id=iwrq-qjta v:category=Transportation v:attributionLink=http://www.seattle.gov/transportation/ v:averageRating=0 v:name="SDOT Traffic Beacons" v:attribution="Seattle Department of Transportation"

property e:iwrq-qjta t:meta.view.license v:name="Public Domain"

property e:iwrq-qjta t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:iwrq-qjta t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | compkey | comptype | segkey | distance | width | unitid  | unittype | unitdesc                                                                 | ownership | condition | condition_assessment_date | current_status | current_status_date | category | install_date | installer | electr_wire_loc | control_protocol_type | metered | last_pm_date | solar_install_date | hansen7id | disphousingcond | mount_type | crosswalk_tub | flashing | attachment_condition | pole_condition | support_install_date | span_condition | control_condition | control_type | modem_type | model_type | side | school_speed_camera | 
| ======== | ======= | ======== | ====== | ======== | ===== | ======= | ======== | ======================================================================== | ========= | ========= | ========================= | ============== | =================== | ======== | ============ | ========= | =============== | ===================== | ======= | ============ | ================== | ========= | =============== | ========== | ============= | ======== | ==================== | ============== | ==================== | ============== | ================= | ============ | ========== | ========== | ==== | =================== | 
| 1        | 573149  | 16       | 4457   | 508      |       | BCN-189 | BCN      | 3RD AVE NW 0560 BLOCK C SIDE ( 508) 22 FT S/O NW 58TH ST (BCN-XWK)       |           |           |                           |                |                     | BCN-XWK  |              |           |                 |                       | N       |              |                    |           |                 | TM-OVRHEAD | Y             | Y        |                      |                |                      |                |                   |              |            |            | C    | N                   | 
| 2        | 568620  | 16       | 1103   | 890      |       | BCN-115 | BCN      | 1ST AVE NE 1220 BLOCK C SIDE ( 890) 0 FT S/O CORLISS S AVE N (BCN-REG)   |           |           |                           |                |                     | BCN-REG  |              |           | AUXPOLE         |                       | N       |              |                    |           | POOR            | TM-OVRHEAD | N             | Y        | POOR                 | FAIR           |                      | POOR           |                   |              |            |            | C    | N                   | 
| 3        | 567676  | 16       | 2869   | 306      |       | BCN-75  | BCN      | 2ND AVE S 0020 BLOCK C SIDE ( 306) 0 FT N/O S MAIN ST (BCN-REG)          | SDOT      | POOR      | 1305158400                | INSVC          | 1305158400          | BCN-REG  |              | SDOT      | UG              |                       | N       | 1305158400   |                    |           | POOR            | TM-OVRHEAD | N             | Y        | POOR                 | GOOD           |                      | POOR           |                   | HARDWIRE     |            |            | C    | N                   | 
| 4        | 567511  | 16       | 19663  | 40       | -22   | BCN-64  | BCN      | S CLOVERDALE ST 0447 BLOCK S SIDE ( 10) 10 FT E/O 45TH AVE S (BCN-SCHL)  | SDOT      | GOOD      | 1404691200                | INSVC          | 1404691200          | BCN-SCHL | 1404604800   | SDOT      |                 |                       | N       |              | 1404604800         |           |                 | TM-SHLDR   | N             | Y        |                      |                |                      |                |                   | WEB          |            | BCN-TC3    | S    | N                   | 
| 5        | 568644  | 16       | 2966   | 59       |       | BCN-125 | BCN      | 20TH AVE NE 0559 BLOCK C SIDE ( 59) 0 FT S/O NE RAVENNA WB BV (BCN-REG)  |           |           |                           |                |                     | BCN-REG  |              |           |                 |                       | N       |              |                    |           |                 | TM-OVRHEAD | N             | N        |                      |                |                      |                |                   |              |            |            | C    | N                   | 
| 6        | 573912  | 16       | 12298  | 262      |       | BCN-303 | BCN      | QUEEN ANNE AVE N 0050 BLOCK C SIDE ( 262) 214 FT S/O MERCER ST (BCN-XWK) |           |           |                           |                |                     | BCN-XWK  |              |           |                 |                       | N       |              |                    |           |                 | TM-OVRHEAD | N             | N        |                      |                |                      |                |                   |              |            |            | C    | N                   | 
| 7        | 568648  | 16       | 6314   | 0        |       | BCN-128 | BCN      | 40TH AVE NE 0550 BLOCK C SIDE ( 0) 0 FT N/O NE 55TH ST (BCN-REG)         |           |           |                           |                |                     | BCN-REG  |              |           |                 |                       | N       |              |                    |           |                 | TM-OVRHEAD | N             | N        |                      |                |                      |                |                   |              |            |            | C    | N                   | 
| 8        | 567679  | 16       | 7870   | 0        |       | BCN-76  | BCN      | 6TH AVE 0020 BLOCK C SIDE ( 0) 0 FT N/O YESLER WAY (BCN-REG)             | SDOT      | POOR      | 1305158400                | INSVC          | 1305158400          | BCN-REG  |              | SDOT      | AERIAL          |                       | N       | 1305158400   |                    |           | POOR            | TM-OVRHEAD | N             | Y        | POOR                 | FAIR           |                      | POOR           |                   | HARDWIRE     |            |            | C    | N                   | 
| 9        | 568521  | 16       | 4927   | 465      |       | BCN-106 | BCN      | 32ND AVE 0110 BLOCK C SIDE ( 465) 0 FT S/O E UNION ST (BCN-REG)          | SDOT      | FAIR      | 1305244800                | INSVC          | 1305244800          | BCN-REG  |              | SDOT      | AERIAL          |                       | N       | 1305244800   |                    |           | FAIR            | TM-OVRHEAD | N             | Y        | FAIR                 | FAIR           |                      | GOOD           |                   | HARDWIRE     |            |            | C    | N                   | 
| 10       | 573463  | 16       | 1809   | 0        |       | BCN-231 | BCN      | 13TH AVE S 0620 BLOCK C SIDE ( 0) 0 FT S/O S BAILEY ST (BCN-REG)         |           |           |                           |                |                     | BCN-REG  |              |           |                 |                       | N       |              |                    |           |                 | TM-OVRHEAD | N             | Y        |                      |                |                      |                |                   |              |            |            | C    | N                   | 
```