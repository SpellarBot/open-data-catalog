# Bus Breakdown and Delays

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bus-breakdown-and-delays) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ez4e-fazm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ez4e-fazm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ez4e-fazm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ez4e-fazm |
| Name | Bus Breakdown and Delays |
| Attribution | Department of Education (DOE) |
| Category | Transportation |
| Tags | bus, schools, transportation, doe |
| Created | 2015-09-30T17:08:23Z |
| Publication Date | 2016-05-03T22:59:56Z |

## Description

The Bus Breakdown and Delay system collects information from school bus vendors operating out in the field in real time. Bus staff that encounter delays during the route are instructed to radio the dispatcher at the bus vendor?s central office. The bus vendor staff are then instructed to log into the Bus Breakdown and Delay system to record the event and notify OPT. OPT customer service agents use this system to inform parents who call with questions regarding bus service. The Bus Breakdown and Delay system is publicly accessible and contains real time updates. All information in the system is entered by school bus vendor staff.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | ============== | =============================== | =============================== | ============= | ============= |
| Yes      | series tag     | school_year                     | School_Year                     | text          | text          |
| Yes      | series tag     | busbreakdown_id                 | Busbreakdown_ID                 | text          | number        |
| Yes      | series tag     | run_type                        | Run_Type                        | text          | text          |
| Yes      | series tag     | bus_no                          | Bus_No                          | text          | text          |
| Yes      | series tag     | route_number                    | Route_Number                    | text          | text          |
| Yes      | series tag     | reason                          | Reason                          | text          | text          |
| Yes      | series tag     | schools_serviced                | Schools_Serviced                | text          | text          |
| Yes      | time           | occurred_on                     | Occurred_On                     | calendar_date | calendar_date |
| No       |                | created_on                      | Created_On                      | calendar_date | calendar_date |
| Yes      | series tag     | boro                            | Boro                            | text          | text          |
| Yes      | series tag     | bus_company_name                | Bus_Company_Name                | text          | text          |
| Yes      | series tag     | how_long_delayed                | How_Long_Delayed                | text          | text          |
| Yes      | numeric metric | number_of_students_on_the_bus   | Number_Of_Students_On_The_Bus   | number        | number        |
| Yes      | series tag     | has_contractor_notified_schools | Has_Contractor_Notified_Schools | text          | text          |
| Yes      | series tag     | has_contractor_notified_parents | Has_Contractor_Notified_Parents | text          | text          |
| Yes      | series tag     | have_you_alerted_opt            | Have_You_Alerted_OPT            | text          | text          |
| No       |                | informed_on                     | Informed_On                     | calendar_date | calendar_date |
| Yes      | series tag     | incident_number                 | Incident_Number                 | text          | text          |
| No       |                | last_updated_on                 | Last_Updated_On                 | calendar_date | calendar_date |
| Yes      | series tag     | breakdown_or_running_late       | Breakdown_or_Running_Late       | text          | text          |
| Yes      | series tag     | school_age_or_prek              | School_Age_or_PreK              | text          | text          |
```

## Time Field

```ls
Value = occurred_on
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = created_on,informed_on,last_updated_on
```

## Data Commands

```ls
series e:ez4e-fazm d:2015-10-08T07:00:00.000Z t:breakdown_or_running_late=Breakdown t:school_age_or_prek=School-Age t:boro=Brooklyn t:reason="Mechanical Problem" t:busbreakdown_id=1220252 t:run_type="Special Ed AM Run" t:school_year=2015-2016 t:route_number=K638 t:schools_serviced=22001 t:has_contractor_notified_schools=Yes t:bus_no=104 t:have_you_alerted_opt=No t:bus_company_name="Y & M TRANSIT CORP (B2192" t:has_contractor_notified_parents=Yes m:number_of_students_on_the_bus=0

series e:ez4e-fazm d:2015-10-16T07:13:00.000Z t:breakdown_or_running_late="Running Late" t:school_age_or_prek=School-Age t:boro=Bronx t:reason="Heavy Traffic" t:busbreakdown_id=1222207 t:run_type="Special Ed AM Run" t:school_year=2015-2016 t:route_number=Y888 t:how_long_delayed="25 MINS" t:schools_serviced=07697 t:has_contractor_notified_schools=Yes t:bus_no=GT1473 t:have_you_alerted_opt=Yes t:bus_company_name="DON THOMAS BUSES, INC. (B" t:has_contractor_notified_parents=Yes m:number_of_students_on_the_bus=6

series e:ez4e-fazm d:2015-10-16T07:22:00.000Z t:breakdown_or_running_late="Running Late" t:school_age_or_prek=School-Age t:boro=Manhattan t:reason="Heavy Traffic" t:busbreakdown_id=1222301 t:run_type="Special Ed AM Run" t:school_year=2015-2016 t:route_number=M572 t:how_long_delayed="25 min" t:schools_serviced=02001 t:has_contractor_notified_schools=No t:bus_no=2714 t:have_you_alerted_opt=Yes t:bus_company_name="RELIANT TRANS, INC. (B232" t:has_contractor_notified_parents=No m:number_of_students_on_the_bus=4
```

## Meta Commands

```ls
metric m:number_of_students_on_the_bus p:integer l:Number_Of_Students_On_The_Bus d:"Number of students on the bus at the time of the incident as estimated by the staff employed by the reporting bus vendor. OPT does not systematically monitor the contents of this field in real time." t:dataTypeName=number

entity e:ez4e-fazm l:"Bus Breakdown and Delays" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/ez4e-fazm

property e:ez4e-fazm t:meta.view v:id=ez4e-fazm v:category=Transportation v:averageRating=0 v:name="Bus Breakdown and Delays" v:attribution="Department of Education (DOE)"

property e:ez4e-fazm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ez4e-fazm t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| school_year | busbreakdown_id | run_type          | bus_no | route_number | reason             | schools_serviced | occurred_on         | created_on          | boro      | bus_company_name          | how_long_delayed | number_of_students_on_the_bus | has_contractor_notified_schools | has_contractor_notified_parents | have_you_alerted_opt | informed_on         | incident_number | last_updated_on     | breakdown_or_running_late | school_age_or_prek | 
| =========== | =============== | ================= | ====== | ============ | ================== | ================ | =================== | =================== | ========= | ========================= | ================ | ============================= | =============================== | =============================== | ==================== | =================== | =============== | =================== | ========================= | ================== | 
| 2015-2016   | 1220252         | Special Ed AM Run | 104    | K638         | Mechanical Problem | 22001            | 2015-10-08T07:00:00 | 2015-10-08T07:21:00 | Brooklyn  | Y & M TRANSIT CORP (B2192 |                  | 0                             | Yes                             | Yes                             | No                   | 2015-10-08T07:21:00 |                 | 2015-10-08T07:21:51 | Breakdown                 | School-Age         | 
| 2015-2016   | 1222207         | Special Ed AM Run | GT1473 | Y888         | Heavy Traffic      | 07697            | 2015-10-16T07:13:00 | 2015-10-16T07:28:00 | Bronx     | DON THOMAS BUSES, INC. (B | 25 MINS          | 6                             | Yes                             | Yes                             | Yes                  | 2015-10-16T07:28:00 |                 | 2015-10-16T07:28:54 | Running Late              | School-Age         | 
| 2015-2016   | 1222301         | Special Ed AM Run | 2714   | M572         | Heavy Traffic      | 02001            | 2015-10-16T07:22:00 | 2015-10-16T08:00:00 | Manhattan | RELIANT TRANS, INC. (B232 | 25 min           | 4                             | No                              | No                              | Yes                  | 2015-10-16T08:00:00 |                 | 2015-10-16T08:00:50 | Running Late              | School-Age         | 
| 2015-2016   | 1226511         | Special Ed PM Run | 9032   | K191         | Heavy Traffic      | 32299            | 2015-10-30T12:56:00 | 2015-10-30T13:08:00 | Brooklyn  | L & M BUS CORP. (B2192)   | 20               | 0                             | No                              | Yes                             | No                   | 2015-10-30T13:08:00 |                 | 2015-10-30T13:08:47 | Running Late              | School-Age         | 
| 2015-2016   | 1227241         | Pre-K/EI          | 9815   | 3            | Heavy Traffic      | C329             | 2015-11-04T08:46:00 | 2015-11-04T08:49:00 | Bronx     | G.V.C., LTD.              | 15MIN            | 16                            | Yes                             | Yes                             | Yes                  | 2015-11-04T08:49:00 |                 | 2015-11-04T08:49:05 | Running Late              | Pre-K              | 
| 2015-2016   | 1231783         | General Ed AM Run | 16376  | M1276        | Heavy Traffic      | 02267            | 2015-11-24T07:29:00 | 2015-11-24T07:36:00 | Manhattan | SNT BUS INC               | 10mins           | 4                             | Yes                             | No                              | No                   | 2015-11-24T07:36:00 |                 | 2015-11-24T07:36:38 | Running Late              | School-Age         | 
| 2015-2016   | 1233179         | Special Ed PM Run | 2024   | X716         | Mechanical Problem | 11910            | 2015-12-01T14:42:00 | 2015-12-01T14:44:00 | Bronx     | RELIANT TRANS, INC. (B232 |                  | 0                             | Yes                             | Yes                             | Yes                  | 2015-12-01T14:44:00 |                 | 2015-12-01T14:44:09 | Breakdown                 | School-Age         | 
| 2015-2016   | 1233468         | Pre-K/EI          | GV0358 | 2            | Heavy Traffic      | C195             | 2015-12-02T07:59:00 | 2015-12-02T07:59:00 | Bronx     | G.V.C., LTD.              | 5-10             | 16                            | Yes                             | Yes                             | Yes                  | 2015-12-02T07:59:00 |                 | 2015-12-02T07:59:07 | Running Late              | Pre-K              | 
| 2015-2016   | 1236372         | Pre-K/EI          | 730    | 6            | Heavy Traffic      | S194             | 2015-12-14T07:57:00 | 2015-12-14T08:00:00 | Bronx     | G.V.C., LTD.              | 20 MINS          | 1                             | Yes                             | Yes                             | No                   | 2015-12-14T08:00:00 |                 | 2015-12-14T08:00:43 | Running Late              | Pre-K              | 
| 2015-2016   | 1236780         | Pre-K/EI          | 52128  | B0506Z       | Other              | C118             | 2015-12-15T15:25:00 | 2015-12-15T15:39:00 | Brooklyn  | L & M BUS CORP.           | 45 mins          | 21                            | Yes                             | Yes                             | No                   | 2015-12-15T15:39:00 |                 | 2015-12-15T15:39:06 | Running Late              | Pre-K              | 
```