# November 2016 YTD Fatalities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/november-2016-ytd-fatalities) |
| Metadata | [Link](https://data.austintexas.gov/api/views/2cx2-y3ed) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/2cx2-y3ed/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/2cx2-y3ed/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 2cx2-y3ed |
| Name | November 2016 YTD Fatalities |
| Attribution | Austin Police Department |
| Category | Public Safety |
| Tags | police, public safety, traffic, fatality |
| Created | 2016-12-21T20:53:28Z |
| Publication Date | 2016-12-21T20:57:49Z |

## Description

AUSTIN POLICE DEPARTMENT DATA DISCLAIMER
1. The data provided are for informational use only and may differ from official APD data.
2. APD?s database is continuously updated, so reports run at different times may produce different results.  Care should be taken when comparing against other reports as different data collection methods and different data sources may have been used.
3. The Austin Police Department does not assume any liability for any decision made or action taken or not taken by the recipient in reliance upon any information or data provided.
NOTE:  Many of these are open cases and final results and conclusions are still pending

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag     | type                       | TYPE                       | text          | text          |
| Yes      | numeric metric | fatal_crash                | FATAL CRASH #              | number        | number        |
| Yes      | numeric metric | of_fatalities              | # of Fatalities            | number        | number        |
| Yes      | series tag     | case_status                | Case Status                | text          | text          |
| Yes      | series tag     | detective                  | Detective                  | text          | text          |
| Yes      | series tag     | case_number                | CASE NUMBER                | text          | text          |
| Yes      | series tag     | location                   | LOCATION                   | text          | text          |
| Yes      | series tag     | area                       | AREA                       | text          | text          |
| Yes      | time           | date                       | Date                       | calendar_date | calendar_date |
| No       |                | month                      | Month                      | text          | text          |
| Yes      | series tag     | day                        | Day                        | text          | text          |
| Yes      | numeric metric | hour                       | Hour                       | number        | number        |
| Yes      | series tag     | time                       | Time                       | text          | text          |
| Yes      | series tag     | related                    | Related                    | text          | text          |
| Yes      | series tag     | charge                     | Charge                     | text          | text          |
| Yes      | series tag     | killed_driver_pass         | Killed: driver/pass        | text          | text          |
| Yes      | series tag     | speeding                   | Speeding                   | text          | text          |
| Yes      | series tag     | ran_red_light_or_stop_sign | Ran Red Light or Stop Sign | text          | text          |
| Yes      | series tag     | dl_status_incident         | DL Status (incident)       | text          | text          |
| Yes      | series tag     | impaired_type              | IMPAIRED TYPE              | text          | text          |
| Yes      | series tag     | restraint_helmet           | restraint / helmet         | text          | text          |
| Yes      | series tag     | type_of_road               | TYPE OF ROAD               | text          | text          |
| Yes      | series tag     | ftsra                      | FTSRA                      | text          | text          |
| Yes      | numeric metric | x_coord                    | X COORD                    | number        | number        |
| Yes      | numeric metric | y_coord                    | Y COORD                    | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = month
```

## Data Commands

```ls
series e:2cx2-y3ed d:2016-01-06T00:00:00.000Z t:case_number=16-0061621 t:impaired_type=PED t:location="9700 Blk Lake Creek Pkwy" t:dl_status_incident=okay t:type=Pedestrian t:related=MV/Ped t:speeding=N t:ftsra=y t:time=23:14 t:charge=FTSRA t:area=AD t:ran_red_light_or_stop_sign=N t:case_status=OPEN t:restraint_helmet=n/a t:day=Wed t:type_of_road="high use roadway" t:killed_driver_pass=n/a m:y_coord=30.475234 m:fatal_crash=1 m:of_fatalities=1 m:x_coord=-97.793878 m:hour=23

series e:2cx2-y3ed d:2016-01-14T00:00:00.000Z t:case_number=16-0140992 t:impaired_type=UNK t:location="4800 E. Riverside Dr." t:dl_status_incident=okay t:type=Pedestrian t:related=MV/Ped t:speeding=N t:ftsra=n t:time=14:46 t:charge=N/A t:area=HE t:ran_red_light_or_stop_sign=N t:case_status=Closed t:restraint_helmet=n/a t:day=Thu t:type_of_road="high use roadway" t:killed_driver_pass=n/a m:y_coord=30.231659 m:fatal_crash=2 m:of_fatalities=1 m:x_coord=-97.717471 m:hour=14

series e:2cx2-y3ed d:2016-01-22T00:00:00.000Z t:case_number=16-0221932 t:impaired_type=DRIVER t:location="6300 blk E William Cannon" t:dl_status_incident=okay t:type="Motor Vehicle" t:related=MV/FO t:speeding=Y t:ftsra=n t:time=23:29 t:charge=N/A t:area=FR t:ran_red_light_or_stop_sign=N t:case_status=Closed t:restraint_helmet=unknown t:day=Fri t:type_of_road="high use roadway" t:killed_driver_pass=driver m:y_coord=30.170877 m:fatal_crash=3 m:of_fatalities=1 m:x_coord=-97.739337 m:hour=23
```

## Meta Commands

```ls
metric m:fatal_crash p:integer l:"FATAL CRASH #" t:dataTypeName=number

metric m:of_fatalities p:integer l:"# of Fatalities" t:dataTypeName=number

metric m:hour p:integer l:Hour t:dataTypeName=number

metric m:x_coord p:decimal l:"X COORD" t:dataTypeName=number

metric m:y_coord p:float l:"Y COORD" t:dataTypeName=number

entity e:2cx2-y3ed l:"November 2016 YTD Fatalities" t:attribution="Austin Police Department" t:url=https://data.austintexas.gov/api/views/2cx2-y3ed

property e:2cx2-y3ed t:meta.view v:id=2cx2-y3ed v:category="Public Safety" v:averageRating=0 v:name="November 2016 YTD Fatalities" v:attribution="Austin Police Department"

property e:2cx2-y3ed t:meta.view.owner v:id=q374-e9d9 v:screenName="Ron MacKay" v:displayName="Ron MacKay"

property e:2cx2-y3ed t:meta.view.tableauthor v:id=q374-e9d9 v:screenName="Ron MacKay" v:roleName=publisher_stories v:displayName="Ron MacKay"
```

## Top Records

```ls
| type          | fatal_crash | of_fatalities | case_status | detective | case_number | location                             | area | date                | month | day | hour | time  | related | charge                    | killed_driver_pass | speeding | ran_red_light_or_stop_sign | dl_status_incident | impaired_type  | restraint_helmet | type_of_road     | ftsra | x_coord             | y_coord            | 
| ============= | =========== | ============= | =========== | ========= | =========== | ==================================== | ==== | =================== | ===== | === | ==== | ===== | ======= | ========================= | ================== | ======== | ========================== | ================== | ============== | ================ | ================ | ===== | =================== | ================== | 
| Pedestrian    | 1           | 1             | OPEN        |           | 16-0061621  | 9700 Blk Lake Creek Pkwy             | AD   | 2016-01-06T00:00:00 | Jan   | Wed | 23   | 23:14 | MV/Ped  | FTSRA                     | n/a                | N        | N                          | okay               | PED            | n/a              | high use roadway | y     | -97.793878000000007 | 30.475234          | 
| Pedestrian    | 2           | 1             | Closed      |           | 16-0140992  | 4800 E. Riverside Dr.                | HE   | 2016-01-14T00:00:00 | Jan   | Thu | 14   | 14:46 | MV/Ped  | N/A                       | n/a                | N        | N                          | okay               | UNK            | n/a              | high use roadway | n     | -97.717471000000003 | 30.231659000000001 | 
| Motor Vehicle | 3           | 1             | Closed      |           | 16-0221932  | 6300 blk E William Cannon            | FR   | 2016-01-22T00:00:00 | Jan   | Fri | 23   | 23:29 | MV/FO   | N/A                       | driver             | Y        | N                          | okay               | DRIVER         | unknown          | high use roadway | n     | -97.739337000000006 | 30.170877000000001 | 
| Pedestrian    | 4           | 1             | Closed      |           | 16-0301529  | 12300 N Lamar                        | ED   | 2016-01-30T00:00:00 | Jan   | Sat | 20   | 20:01 | MV/Ped  | N/A                       | n/a                | N        | N                          | okay               | UNKNOWN        | n/a              | high use roadway | n     | -97.679086999999996 | 30.402740999999999 | 
| Motorcycle    | 5           | 1             | Closed      |           | 16-0450263  | Burleson Rd / McKinney Falls Pkwy    | HE   | 2016-02-14T00:00:00 | Feb   | Sun | 2    | 2:22  | MV/MC   | N/A                       | motorcyclist       | Y        | N                          | okay               | DRIVER         | no helmet        | local street     | n     | -97.698370999999995 | 30.191989          | 
| Motor Vehicle | 6           | 1             | OPEN        |           | 16-0450294  | 6800 Cooper Ln                       | FR   | 2016-02-14T00:00:00 | Feb   | Sun | 2    | 2:36  | MV/ROR  | Intoxication Manslaughter | passenger          | Y        | N                          | okay               | DRIVER         | seatbelts worn   | local street     | n     | -97.791940999999994 | 30.197194          | 
| Pedestrian    | 7           | 1             | Closed      |           | 16-0451375  | 700 Montopolis                       | HE   | 2016-02-14T00:00:00 | Feb   | Sun | 19   | 19:05 | MV/PED  | N/A                       | n/a                | N        | N                          | okay               | PED            | n/a              | high use roadway | n     | -97.695742999999993 | 30.236872999999999 | 
| Motorcycle    | 8           | 1             | OPEN        |           | 16-0490903  | N US 183 Hwy Svrd NB/Pecan Park Blvd | AD   | 2016-02-18T00:00:00 | Feb   | Thu | 13   | 13:14 | MV/MC   | Class C                   | motorcyclist       | N        | Y                          | no MC license      | none (pending) | helmet           | other highway    | n     | -97.795248000000001 | 30.465592000000001 | 
| Pedestrian    | 9           | 1             | Closed      |           | 16-0501840  | Riverside Dr/Willow Creek            | HE   | 2016-02-19T00:00:00 | Feb   | Fri | 23   | 23:08 | MV/Ped  | N/A                       | n/a                | N        | N                          | okay               | PED            | n/a              | high use roadway | n     | -97.725656000000001 | 30.237680000000001 | 
| Motorcycle    | 10          | 1             | Closed      |           | 16-0570527  | 10100 blk FM 2222                    | AD   | 2016-02-26T00:00:00 | Feb   | Fri | 9    | 9:47  | MV/MC   | N/A                       | motorcyclist       | Y        | N                          | no DL              | NONE           | helmet           | high use roadway | n     | -97.826295999999999 | 30.389102999999999 | 
```