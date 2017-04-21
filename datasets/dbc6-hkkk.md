# 2015 Fatalities Spreadsheet

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-fatalities-spreadsheet) |
| Metadata | [Link](https://data.austintexas.gov/api/views/dbc6-hkkk) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/dbc6-hkkk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/dbc6-hkkk/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | dbc6-hkkk |
| Name | 2015 Fatalities Spreadsheet |
| Attribution | Austin Police Department |
| Category | Public Safety |
| Tags | police, traffic, fatalities, fatality |
| Created | 2016-04-25T16:28:16Z |
| Publication Date | 2016-04-25T16:45:41Z |

## Description

Dataset of traffic fatalities January 1st - December 31st 2015.  The Austin Police Department Fatality database contains only those crashes investigated by APD and is continuously being updated due to on-going investigations. The data provided here represents a snapshot of Traffic Fatality information at a specific point in time and may change. Due to the long processing times for toxicology testing, impairment and suspected impairment, statistics are based on the initial assessment of the Detectives and Medical Examiner.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                 | Data Type     | Render Type   |
| ======== | ============== | ================== | ==================== | ============= | ============= |
| Yes      | series tag     | type               | TYPE                 | text          | text          |
| Yes      | numeric metric | fatal_crash        | FATAL CRASH #        | number        | number        |
| Yes      | numeric metric | of_fatalities      | # of Fatalities      | number        | number        |
| Yes      | series tag     | case_status        | Case Status          | text          | text          |
| Yes      | series tag     | case_number        | CASE NUMBER          | text          | text          |
| Yes      | series tag     | location           | LOCATION             | text          | text          |
| Yes      | series tag     | sector             | SECTOR               | text          | text          |
| Yes      | time           | date               | Date                 | calendar_date | calendar_date |
| No       |                | month              | Month                | text          | text          |
| Yes      | series tag     | day                | Day                  | text          | text          |
| Yes      | numeric metric | hour               | Hour                 | number        | number        |
| Yes      | series tag     | time               | Time                 | text          | text          |
| Yes      | series tag     | related            | Related              | text          | text          |
| Yes      | series tag     | charge             | charge               | text          | text          |
| Yes      | series tag     | killed_driver_pass | Killed: driver/pass  | text          | text          |
| Yes      | series tag     | speeding           | Speeding             | text          | text          |
| Yes      | series tag     | ran_red_light      | Ran Red Light        | text          | text          |
| Yes      | series tag     | dl_status_incident | DL Status (incident) | text          | text          |
| Yes      | series tag     | impaired_type      | IMPAIRED TYPE        | text          | text          |
| Yes      | series tag     | restraint_helmet   | restraint / helmet   | text          | text          |
| Yes      | series tag     | type_of_road       | TYPE OF ROAD         | text          | text          |
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
series e:dbc6-hkkk d:2015-01-06T00:00:00.000Z t:sector=ID t:case_number=15-0061199 t:impaired_type=DRIVER t:location="600 Blk E Koenig Lane" t:dl_status_incident=okay t:type="Motor Vehicle" t:ran_red_light=N t:related=MV/MV t:speeding=Y t:time=17:15 t:charge=N/A t:restraint_helmet="no seatbelt" t:case_status=Closed t:day=Tues t:type_of_road="High-use roadway" t:killed_driver_pass=driver m:fatal_crash=1 m:of_fatalities=1 m:hour=17

series e:dbc6-hkkk d:2015-01-07T00:00:00.000Z t:sector=ED t:case_number=15-71386 t:impaired_type=none t:location="12900 Blk N IH35 SB" t:dl_status_incident=okay t:type=Pedestrian t:ran_red_light=N t:related=MV/Ped t:speeding=N t:time=18:36 t:charge=N/A t:restraint_helmet=n/a t:case_status=Closed t:day=Wed t:type_of_road=IH35 t:killed_driver_pass=ped m:fatal_crash=2 m:of_fatalities=1 m:hour=18

series e:dbc6-hkkk d:2015-01-10T00:00:00.000Z t:sector=ID t:case_number=15-100275 t:impaired_type=PED t:location="7400 Blk E US Hwy 290 EB" t:dl_status_incident=unknown t:type=Pedestrian t:ran_red_light=N t:related=MV/Ped t:speeding=N t:time=3:10 t:charge=N/A t:restraint_helmet=n/a t:case_status=OPEN t:day=Sat t:type_of_road="Other highway" t:killed_driver_pass=ped m:fatal_crash=3 m:of_fatalities=1 m:hour=3
```

## Meta Commands

```ls
metric m:fatal_crash p:integer l:"FATAL CRASH #" t:dataTypeName=number

metric m:of_fatalities p:integer l:"# of Fatalities" t:dataTypeName=number

metric m:hour p:integer l:Hour t:dataTypeName=number

entity e:dbc6-hkkk l:"2015 Fatalities Spreadsheet" t:attribution="Austin Police Department" t:url=https://data.austintexas.gov/api/views/dbc6-hkkk

property e:dbc6-hkkk t:meta.view v:id=dbc6-hkkk v:category="Public Safety" v:averageRating=0 v:name="2015 Fatalities Spreadsheet" v:attribution="Austin Police Department"

property e:dbc6-hkkk t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:dbc6-hkkk t:meta.view.owner v:id=q374-e9d9 v:screenName="Ron MacKay" v:displayName="Ron MacKay"

property e:dbc6-hkkk t:meta.view.tableauthor v:id=q374-e9d9 v:screenName="Ron MacKay" v:roleName=publisher_stories v:displayName="Ron MacKay"
```

## Top Records

```ls
| type          | fatal_crash | of_fatalities | case_status | case_number | location                 | sector | date                | month | day  | hour | time  | related | charge                 | killed_driver_pass | speeding | ran_red_light | dl_status_incident    | impaired_type | restraint_helmet | type_of_road     | 
| ============= | =========== | ============= | =========== | =========== | ======================== | ====== | =================== | ===== | ==== | ==== | ===== | ======= | ====================== | ================== | ======== | ============= | ===================== | ============= | ================ | ================ | 
| Motor Vehicle | 1           | 1             | Closed      | 15-0061199  | 600 Blk E Koenig Lane    | ID     | 2015-01-06T00:00:00 | Jan   | Tues | 17   | 17:15 | MV/MV   | N/A                    | driver             | Y        | N             | okay                  | DRIVER        | no seatbelt      | High-use roadway | 
| Pedestrian    | 2           | 1             | Closed      | 15-71386    | 12900 Blk N IH35 SB      | ED     | 2015-01-07T00:00:00 | Jan   | Wed  | 18   | 18:36 | MV/Ped  | N/A                    | ped                | N        | N             | okay                  | none          | n/a              | IH35             | 
| Pedestrian    | 3           | 1             | OPEN        | 15-100275   | 7400 Blk E US Hwy 290 EB | ID     | 2015-01-10T00:00:00 | Jan   | Sat  | 3    | 3:10  | MV/Ped  | N/A                    | ped                | N        | N             | unknown               | PED           | n/a              | Other highway    | 
| Motorcycle    | 4           | 1             | Closed      | 15-131517   | 4700 Blk E Riverside Dr  | HE     | 2015-01-13T00:00:00 | Jan   | Tues | 21   | 21:30 | MV/MC   | FTYROW to MC           | motorcyclist       | N        | N             | no motorcycle license | none          | helmet           | High-use roadway | 
| Motor Vehicle | 5           | 1             | OPEN        | 15-150104   | Berkman Dr/Cloverleaf Dr | ID     | 2015-01-15T00:00:00 | Jan   | Thu  | 1    | 1:41  | MV/MV   | ciminally neg homicide | driver other       | Y        | N             | okay                  | DRIVER        | seatbelt worn    | Local Street     | 
| Pedestrian    | 6           | 1             | Closed      | 15-181372   | 8400 S. Congress Ave     | FR     | 2015-01-18T00:00:00 | Jan   | Sun  | 19   | 19:37 | MV/Ped  | N/A                    | ped                | N        | N             | okay                  | PED           | n/a              | High-use roadway | 
| Motor Vehicle | 7           | 1             | Closed      | 15-181537   | 2900 N. Lamar            | BA     | 2015-01-18T00:00:00 | Jan   | Sun  | 21   | 21:23 | MV/ROR  | N/A                    | driver             | Y        | N             | okay                  | DRIVER        | seatbelt worn    | High-use roadway | 
| Pedestrian    | 8           | 1             | Closed      | 15-0201458  | 1030 Norwood Park Blvd   | ID     | 2015-01-20T00:00:00 | Jan   | Tues | 18   | 18:36 | MV/Ped  | N/A                    | ped                | N        | N             | okay                  | none          | n/a              | Local Street     | 
| Motor Vehicle | 9           | 1             | Closed      | 15-240366   | 7300 Blk Burleson Rd     | HE     | 2015-01-24T00:00:00 | Jan   | Sat  | 4    | 4:17  | MV/MV   | N/A                    | driver             | N        | N             | okay                  | DRIVER        | seatbelt worn    | High-use roadway | 
| Motor Vehicle | 10          | 1             | Closed      | 15-271694   | 8100 Blk Research Blvd   | ID     | 2015-01-27T00:00:00 | Jan   | Tues | 21   | 21:42 | MV/FO   | No Charge              | driver             | N        | N             | okay                  | none          | unknown          | Other highway    | 
```