# Traffic Violations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/traffic-violations-56dda) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/4mse-ku6q) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/4mse-ku6q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/4mse-ku6q/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 4mse-ku6q |
| Name | Traffic Violations |
| Category | Public Safety |
| Tags | traffic, stop, violations, electronic issued. |
| Created | 2014-06-18T14:58:37Z |
| Publication Date | 2014-09-18T11:45:02Z |

## Description

This dataset contains traffic violation information from all electronic traffic violations issued in the County.  Any information that can be used to uniquely identify the vehicle, the vehicle owner or the officer issuing the violation will not be published.

Update Frequency:  Daily

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| No       |                | date_of_stop            | Date Of Stop            | calendar_date | calendar_date |
| No       |                | time_of_stop            | Time Of Stop            | text          | text          |
| Yes      | series tag     | agency                  | Agency                  | text          | text          |
| Yes      | series tag     | subagency               | SubAgency               | text          | text          |
| Yes      | series tag     | description             | Description             | text          | text          |
| Yes      | series tag     | location                | Location                | text          | text          |
| No       |                | latitude                | Latitude                | number        | number        |
| No       |                | longitude               | Longitude               | number        | number        |
| Yes      | series tag     | accident                | Accident                | text          | text          |
| Yes      | series tag     | belts                   | Belts                   | text          | text          |
| Yes      | series tag     | personal_injury         | Personal Injury         | text          | text          |
| Yes      | series tag     | property_damage         | Property Damage         | text          | text          |
| Yes      | series tag     | fatal                   | Fatal                   | text          | text          |
| Yes      | series tag     | commercial_license      | Commercial License      | text          | text          |
| Yes      | series tag     | hazmat                  | HAZMAT                  | text          | text          |
| Yes      | series tag     | commercial_vehicle      | Commercial Vehicle      | text          | text          |
| Yes      | series tag     | alcohol                 | Alcohol                 | text          | text          |
| Yes      | series tag     | work_zone               | Work Zone               | text          | text          |
| Yes      | series tag     | state                   | State                   | text          | text          |
| Yes      | series tag     | vehicle_type            | VehicleType             | text          | text          |
| Yes      | numeric metric | year                    | Year                    | number        | text          |
| Yes      | series tag     | make                    | Make                    | text          | text          |
| Yes      | series tag     | model                   | Model                   | text          | text          |
| Yes      | series tag     | color                   | Color                   | text          | text          |
| Yes      | series tag     | violation_type          | Violation Type          | text          | text          |
| Yes      | series tag     | charge                  | Charge                  | text          | text          |
| Yes      | series tag     | article                 | Article                 | text          | text          |
| Yes      | series tag     | contributed_to_accident | Contributed To Accident | text          | text          |
| Yes      | series tag     | race                    | Race                    | text          | text          |
| Yes      | series tag     | gender                  | Gender                  | text          | text          |
| Yes      | series tag     | driver_city             | Driver City             | text          | text          |
| Yes      | series tag     | driver_state            | Driver State            | text          | text          |
| Yes      | series tag     | dl_state                | DL State                | text          | text          |
| Yes      | series tag     | arrest_type             | Arrest Type             | text          | text          |
```

## Time Field

```ls
Value = date_of_stop-time_of_stop
Format & Zone = yyyy-MM-dd'T'HH:mm:ss-HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = latitude,longitude,time_of_stop,date_of_stop
```

## Data Commands

```ls
series e:4mse-ku6q d:2013-09-24T17:11:00.000Z t:model=4S t:accident=No t:location="8804 FLOWER AVE" t:vehicle_type="02 - Automobile" t:personal_injury=No t:state=MD t:race=BLACK t:hazmat=No t:violation_type=Citation t:contributed_to_accident=No t:description="DRIVING VEHICLE ON HIGHWAY WITH SUSPENDED REGISTRATION" t:gender=M t:commercial_vehicle=No t:fatal=No t:agency=MCP t:commercial_license=No t:subagency="3rd district, Silver Spring" t:belts=No t:driver_state=MD t:dl_state=MD t:charge=13-401(h) t:article="Transportation Article" t:arrest_type="A - Marked Patrol" t:color=BLACK t:alcohol=No t:work_zone=No t:make=FORD t:driver_city="TAKOMA PARK" t:property_damage=No m:year=2008

series e:4mse-ku6q d:2012-12-20T00:41:00.000Z t:model=4S t:accident=No t:location="NORFOLK AVE /  ST ELMO AVE" t:vehicle_type="02 - Automobile" t:personal_injury=No t:state=MD t:race=WHITE t:hazmat=No t:violation_type=Citation t:contributed_to_accident=No t:description="DRIVING WHILE IMPAIRED BY ALCOHOL" t:gender=M t:commercial_vehicle=No t:fatal=No t:agency=MCP t:commercial_license=No t:subagency="2nd district, Bethesda" t:belts=No t:driver_state=MD t:dl_state=MD t:charge=21-902(b1) t:article="Transportation Article" t:arrest_type="A - Marked Patrol" t:color=GRAY t:alcohol=No t:work_zone=No t:make=AUDI t:driver_city=DERWOOD t:property_damage=No m:year=2005

series e:4mse-ku6q d:2012-07-20T23:12:00.000Z t:model=4S t:accident=No t:location="WISTERIA DR @ WARING STATION RD" t:vehicle_type="02 - Automobile" t:personal_injury=No t:state=MD t:race=ASIAN t:hazmat=No t:violation_type=Citation t:contributed_to_accident=No t:description="FAILURE TO STOP AT STOP SIGN" t:gender=F t:commercial_vehicle=No t:fatal=No t:agency=MCP t:commercial_license=No t:subagency="5th district, Germantown" t:belts=No t:driver_state=MD t:dl_state=MD t:charge=21-707(a) t:article="Transportation Article" t:arrest_type="A - Marked Patrol" t:color=RED t:alcohol=No t:work_zone=No t:make=TOYT t:driver_city=GERMANTOWN t:property_damage=No m:year=2002
```

## Meta Commands

```ls
metric m:year p:integer l:Year d:"Year vehicle was made." t:dataTypeName=number

entity e:4mse-ku6q l:"Traffic Violations" t:url=https://data.montgomerycountymd.gov/api/views/4mse-ku6q

property e:4mse-ku6q t:meta.view v:id=4mse-ku6q v:category="Public Safety" v:averageRating=0 v:name="Traffic Violations"

property e:4mse-ku6q t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:4mse-ku6q t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| date_of_stop        | time_of_stop | agency | subagency                                       | description                                                                                     | location                               | latitude         | longitude         | accident | belts | personal_injury | property_damage | fatal | commercial_license | hazmat | commercial_vehicle | alcohol | work_zone | state | vehicle_type          | year | make      | model    | color  | violation_type | charge        | article                | contributed_to_accident | race     | gender | driver_city    | driver_state | dl_state | arrest_type       | 
| =================== | ============ | ====== | =============================================== | =============================================================================================== | ====================================== | ================ | ================= | ======== | ===== | =============== | =============== | ===== | ================== | ====== | ================== | ======= | ========= | ===== | ===================== | ==== | ========= | ======== | ====== | ============== | ============= | ====================== | ======================= | ======== | ====== | ============== | ============ | ======== | ================= | 
| 2013-09-24T00:00:00 | 17:11:00     | MCP    | 3rd district, Silver Spring                     | DRIVING VEHICLE ON HIGHWAY WITH SUSPENDED REGISTRATION                                          | 8804 FLOWER AVE                        |                  |                   | No       | No    | No              | No              | No    | No                 | No     | No                 | No      | No        | MD    | 02 - Automobile       | 2008 | FORD      | 4S       | BLACK  | Citation       | 13-401(h)     | Transportation Article | No                      | BLACK    | M      | TAKOMA PARK    | MD           | MD       | A - Marked Patrol | 
| 2012-12-20T00:00:00 | 00:41:00     | MCP    | 2nd district, Bethesda                          | DRIVING WHILE IMPAIRED BY ALCOHOL                                                               | NORFOLK AVE / ST ELMO AVE              | 38.9835782       | -77.09310515      | No       | No    | No              | No              | No    | No                 | No     | No                 | No      | No        | MD    | 02 - Automobile       | 2005 | AUDI      | 4S       | GRAY   | Citation       | 21-902(b1)    | Transportation Article | No                      | WHITE    | M      | DERWOOD        | MD           | MD       | A - Marked Patrol | 
| 2012-07-20T00:00:00 | 23:12:00     | MCP    | 5th district, Germantown                        | FAILURE TO STOP AT STOP SIGN                                                                    | WISTERIA DR @ WARING STATION RD        | 39.1618098166667 | -77.25358095      | No       | No    | No              | No              | No    | No                 | No     | No                 | No      | No        | MD    | 02 - Automobile       | 2002 | TOYT      | 4S       | RED    | Citation       | 21-707(a)     | Transportation Article | No                      | ASIAN    | F      | GERMANTOWN     | MD           | MD       | A - Marked Patrol | 
| 2012-03-19T00:00:00 | 16:10:00     | MCP    | 2nd district, Bethesda                          | DRIVER USING HANDS TO USE HANDHELD TELEPHONE WHILEMOTOR VEHICLE IS IN MOTION                    | CLARENDON RD @ ELM ST. N/              | 38.9827307333333 | -77.1007551666667 | No       | No    | No              | No              | No    | No                 | No     | No                 | No      | No        | VA    | 02 - Automobile       | 1996 | HONDA     | CIVIC    | SILVER | Citation       | 21-1124.2(d2) | Transportation Article | No                      | HISPANIC | M      | ARLINGTON      | VA           | VA       | A - Marked Patrol | 
| 2014-12-01T00:00:00 | 12:52:00     | MCP    | 6th district, Gaithersburg / Montgomery Village | FAILURE STOP AND YIELD AT THRU HWY                                                              | CHRISTOPHER AVE/MONTGOMERY VILLAGE AVE | 39.1628883333333 | -77.2290883333333 | No       | No    | No              | Yes             | No    | No                 | No     | No                 | No      | No        | MD    | 02 - Automobile       | 2001 | HONDA     | ACCORD   | SILVER | Citation       | 21-403(b)     | Transportation Article | No                      | BLACK    | F      | UPPER MARLBORO | MD           | MD       | A - Marked Patrol | 
| 2012-06-09T00:00:00 | 21:19:00     | MCP    | 3rd district, Silver Spring                     | OCCUPANT UNDER 16 NOT RESTRAINED BY SEATBELT                                                    | 2068 HARLEQUIN TERRACE                 | 39.06914295      | -76.9696780666667 | No       | No    | No              | No              | No    | No                 | No     | No                 | No      | No        | MD    | 02 - Automobile       | 2004 | CHEVROLET | IMPALA   | SILVER | Citation       | 22-412.3(b)   | Transportation Article | No                      | WHITE    | F      | SILVER SPRING  | MD           | MD       | A - Marked Patrol | 
| 2012-09-11T00:00:00 | 21:47:00     | MCP    | 4th district, Wheaton                           | PERSON DRIVING MOTOR VEHICLE ON HIGHWAY OR PUBLIC USE PROPERTY ON REVOKED LICENSE AND PRIVILEGE | TWIG RD AT GOOD HOPE RD                | 39.09619885      | -76.98696215      | No       | Yes   | No              | No              | No    | No                 | No     | No                 | No      | No        | MD    | 02 - Automobile       | 2009 | DODGE     | CHARGER  | BLACK  | Citation       | 16-303(d)     | Transportation Article | No                      | BLACK    | M      | SILVER SPRING  | MD           | MD       | A - Marked Patrol | 
| 2012-11-04T00:00:00 | 01:14:00     | MCP    | 4th district, Wheaton                           | DRIVING UNDER THE INFLUENCE OF ALCOHOL PER SE                                                   | RANDOLPH RD @ SPRINGTREE DR            | 39.0583676       | -77.0479825666667 | No       | No    | No              | No              | No    | No                 | No     | No                 | No      | No        | MD    | 02 - Automobile       | 2003 | FORD      | TAURUS   | WHITE  | Citation       | 21-902(a2)    | Transportation Article | No                      | BLACK    | M      | SILVER SPRING  | MD           | MD       | A - Marked Patrol | 
| 2012-08-27T00:00:00 | 00:04:00     | MCP    | 5th district, Germantown                        | PERSON DRIVING MOTOR VEHICLE WHILE LICENSE SUSPENDED UNDER 17-106, 26-204, 26-206, 27-103       | GERMANTOWN RD@CLOPPER                  | 39.1612861666667 | -77.2837891833333 | No       | No    | No              | No              | No    | No                 | No     | No                 | No      | No        | MD    | 02 - Automobile       | 2004 | INFINITY  | QX4      | SILVER | Citation       | 16-303(h)     | Transportation Article | No                      | WHITE    | M      | GERMANTOWN     | MD           | MD       | A - Marked Patrol | 
| 2012-05-21T00:00:00 | 16:47:00     | MCP    | 2nd district, Bethesda                          | OPERATOR NOT RESTRAINED BY SEATBELT                                                             | CLUB DR/CONNECTICUT AVE                | 38.9893187       | -77.0753899       | No       | No    | No              | No              | No    | No                 | No     | No                 | No      | No        | MD    | 05 - Light Duty Truck | 2005 | TOYT      | 4 RUNNER | BLACK  | Citation       | 22-412.3(b)   | Transportation Article | No                      | BLACK    | M      | OWINGS MILLS   | MD           | MD       | A - Marked Patrol | 
```