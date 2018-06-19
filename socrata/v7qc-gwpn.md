# Fare Card History for Metropolitan Transportation Authority (MTA): Beginning 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fare-card-history-for-metropolitan-transportation-authority-mta-beginning-2010) |
| Metadata | [Link](https://data.ny.gov/api/views/v7qc-gwpn) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/v7qc-gwpn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/v7qc-gwpn/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | v7qc-gwpn |
| Name | Fare Card History for Metropolitan Transportation Authority (MTA): Beginning 2010 |
| Attribution | MTA Headquarters, New York City Transit |
| Category | Transportation |
| Tags | metrocard, mta, fare |
| Created | 2013-04-30T21:04:29Z |
| Publication Date | 2017-04-16T10:08:45Z |

## Description

These files show the number of MetroCard swipes made each week by customers entering each station of the New York City Subway, PATH, AirTrain JFK and the Roosevelt Island Tram, broken out to show the relative popularity of the various types of MetroCards. MTA New York City Transit posts the latest data every Saturday by 1 a.m., and the dates listed in the links reference the date the data is posted. The data in the files covers seven-day periods beginning on the Saturday two weeks prior to the posting date and ending on the following Friday.

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                        | Data Type     | Render Type   |
| ======== | ============== | =========================================== | =========================================== | ============= | ============= |
| Yes      | time           | from_date                                   | From Date                                   | calendar_date | calendar_date |
| No       |                | to_date                                     | To Date                                     | calendar_date | calendar_date |
| Yes      | series tag     | remote_station_id                           | Remote Station ID                           | text          | text          |
| Yes      | series tag     | station                                     | Station                                     | text          | text          |
| Yes      | numeric metric | full_fare                                   | Full Fare                                   | number        | number        |
| Yes      | numeric metric | senior_citizen_disabled                     | Senior Citizen / Disabled                   | number        | number        |
| Yes      | numeric metric | 7_day_ada_farecard_access_system_unlimited  | 7 Day ADA Farecard Access System Unlimited  | number        | number        |
| Yes      | numeric metric | 30_day_ada_farecard_access_system_unlimited | 30 Day ADA Farecard Access System Unlimited | number        | number        |
| Yes      | numeric metric | joint_rail_road_ticket                      | Joint Rail Road Ticket                      | number        | number        |
| Yes      | numeric metric | 7_day_unlimited                             | 7 Day Unlimited                             | number        | number        |
| Yes      | numeric metric | 30_day_unlimited                            | 30 Day Unlimited                            | number        | number        |
| Yes      | numeric metric | 14_day_reduced_fare_media_unlimited         | 14 Day Reduced Fare Media Unlimited         | number        | number        |
| Yes      | numeric metric | 1_day_unlimited                             | 1 Day Unlimited                             | number        | number        |
| Yes      | numeric metric | 14_day_unlimited                            | 14 Day Unlimited                            | number        | number        |
| Yes      | numeric metric | 7_day_express_bus_pass                      | 7 Day Express Bus Pass                      | number        | number        |
| Yes      | numeric metric | transit_check_metrocard                     | Transit Check Metrocard                     | number        | number        |
| Yes      | numeric metric | lib_special_senior                          | LIB Special Senior                          | number        | number        |
| Yes      | numeric metric | rail_road_unlimited_no_trade                | Rail Road Unlimited No Trade                | number        | number        |
| Yes      | numeric metric | transit_check_metrocard_annual_metrocard    | Transit Check Metrocard Annual Metrocard    | number        | number        |
| Yes      | numeric metric | mail_and_ride_ezpay_express                 | Mail and Ride EZPass Express                | number        | number        |
| Yes      | numeric metric | mail_and_ride_unlimited                     | Mail and Ride Unlimited                     | number        | number        |
| Yes      | numeric metric | path_2_trip                                 | Path 2 Trip                                 | number        | number        |
| Yes      | numeric metric | airtrain_full_fare                          | Airtran Full Fare                           | number        | number        |
| Yes      | numeric metric | airtrain_30_day                             | Airtran 30 Day                              | number        | number        |
| Yes      | numeric metric | airtrain_10_trip                            | Airtran 10 Trip                             | number        | number        |
| Yes      | numeric metric | airtrain_monthly                            | Airtran Monthly                             | number        | number        |
```

## Time Field

```ls
Value = from_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = to_date
```

## Data Commands

```ls
series e:v7qc-gwpn d:2016-02-13T00:00:00.000Z t:remote_station_id=R001 t:station="WHITEHALL STREET" m:path_2_trip=0 m:mail_and_ride_ezpay_express=1202 m:7_day_ada_farecard_access_system_unlimited=264 m:airtrain_10_trip=0 m:mail_and_ride_unlimited=470 m:airtrain_monthly=0 m:30_day_unlimited=28241 m:14_day_unlimited=0 m:30_day_ada_farecard_access_system_unlimited=756 m:1_day_unlimited=0 m:rail_road_unlimited_no_trade=432 m:7_day_unlimited=21775 m:7_day_express_bus_pass=0 m:airtrain_full_fare=843 m:transit_check_metrocard_annual_metrocard=3440 m:transit_check_metrocard=773 m:lib_special_senior=430 m:senior_citizen_disabled=1811 m:joint_rail_road_ticket=231 m:full_fare=46710 m:14_day_reduced_fare_media_unlimited=0 m:airtrain_30_day=0

series e:v7qc-gwpn d:2016-02-13T00:00:00.000Z t:remote_station_id=R003 t:station="CYPRESS HILLS" m:path_2_trip=0 m:mail_and_ride_ezpay_express=6 m:7_day_ada_farecard_access_system_unlimited=14 m:airtrain_10_trip=0 m:mail_and_ride_unlimited=9 m:airtrain_monthly=0 m:30_day_unlimited=1168 m:14_day_unlimited=0 m:30_day_ada_farecard_access_system_unlimited=40 m:1_day_unlimited=0 m:rail_road_unlimited_no_trade=1 m:7_day_unlimited=2171 m:7_day_express_bus_pass=0 m:airtrain_full_fare=7 m:transit_check_metrocard_annual_metrocard=97 m:transit_check_metrocard=22 m:lib_special_senior=61 m:senior_citizen_disabled=138 m:joint_rail_road_ticket=0 m:full_fare=2793 m:14_day_reduced_fare_media_unlimited=0 m:airtrain_30_day=0

series e:v7qc-gwpn d:2016-02-13T00:00:00.000Z t:remote_station_id=R004 t:station="75TH STREET & ELDERTS LANE" m:path_2_trip=0 m:mail_and_ride_ezpay_express=32 m:7_day_ada_farecard_access_system_unlimited=28 m:airtrain_10_trip=0 m:mail_and_ride_unlimited=52 m:airtrain_monthly=0 m:30_day_unlimited=3822 m:14_day_unlimited=0 m:30_day_ada_farecard_access_system_unlimited=102 m:1_day_unlimited=0 m:rail_road_unlimited_no_trade=0 m:7_day_unlimited=5144 m:7_day_express_bus_pass=0 m:airtrain_full_fare=75 m:transit_check_metrocard_annual_metrocard=254 m:transit_check_metrocard=82 m:lib_special_senior=193 m:senior_citizen_disabled=356 m:joint_rail_road_ticket=0 m:full_fare=7229 m:14_day_reduced_fare_media_unlimited=0 m:airtrain_30_day=0
```

## Meta Commands

```ls
metric m:full_fare p:integer l:"Full Fare" t:dataTypeName=number

metric m:senior_citizen_disabled p:integer l:"Senior Citizen / Disabled" t:dataTypeName=number

metric m:7_day_ada_farecard_access_system_unlimited p:integer l:"7 Day ADA Farecard Access System Unlimited" t:dataTypeName=number

metric m:30_day_ada_farecard_access_system_unlimited p:integer l:"30 Day ADA Farecard Access System Unlimited" t:dataTypeName=number

metric m:joint_rail_road_ticket p:integer l:"Joint Rail Road Ticket" t:dataTypeName=number

metric m:7_day_unlimited p:integer l:"7 Day Unlimited" t:dataTypeName=number

metric m:30_day_unlimited p:integer l:"30 Day Unlimited" t:dataTypeName=number

metric m:14_day_reduced_fare_media_unlimited p:integer l:"14 Day Reduced Fare Media Unlimited" t:dataTypeName=number

metric m:1_day_unlimited p:integer l:"1 Day Unlimited" t:dataTypeName=number

metric m:14_day_unlimited p:integer l:"14 Day Unlimited" t:dataTypeName=number

metric m:7_day_express_bus_pass p:integer l:"7 Day Express Bus Pass" t:dataTypeName=number

metric m:transit_check_metrocard p:integer l:"Transit Check Metrocard" t:dataTypeName=number

metric m:lib_special_senior p:integer l:"LIB Special Senior" t:dataTypeName=number

metric m:rail_road_unlimited_no_trade p:integer l:"Rail Road Unlimited No Trade" t:dataTypeName=number

metric m:transit_check_metrocard_annual_metrocard p:integer l:"Transit Check Metrocard Annual Metrocard" t:dataTypeName=number

metric m:mail_and_ride_ezpay_express p:integer l:"Mail and Ride EZPass Express" t:dataTypeName=number

metric m:mail_and_ride_unlimited p:integer l:"Mail and Ride Unlimited" t:dataTypeName=number

metric m:path_2_trip p:integer l:"Path 2 Trip" t:dataTypeName=number

metric m:airtrain_full_fare p:integer l:"Airtran Full Fare" t:dataTypeName=number

metric m:airtrain_30_day p:integer l:"Airtran 30 Day" t:dataTypeName=number

metric m:airtrain_10_trip p:integer l:"Airtran 10 Trip" t:dataTypeName=number

metric m:airtrain_monthly p:integer l:"Airtran Monthly" t:dataTypeName=number

entity e:v7qc-gwpn l:"Fare Card History for Metropolitan Transportation Authority (MTA): Beginning 2010" t:attribution="MTA Headquarters, New York City Transit" t:url=https://data.ny.gov/api/views/v7qc-gwpn

property e:v7qc-gwpn t:meta.view v:id=v7qc-gwpn v:category=Transportation v:attributionLink=http://www.mta.info/developers/download.html v:averageRating=0 v:name="Fare Card History for Metropolitan Transportation Authority (MTA): Beginning 2010" v:attribution="MTA Headquarters, New York City Transit"

property e:v7qc-gwpn t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:v7qc-gwpn t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:v7qc-gwpn t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| from_date           | to_date             | remote_station_id | station                    | full_fare | senior_citizen_disabled | 7_day_ada_farecard_access_system_unlimited | 30_day_ada_farecard_access_system_unlimited | joint_rail_road_ticket | 7_day_unlimited | 30_day_unlimited | 14_day_reduced_fare_media_unlimited | 1_day_unlimited | 14_day_unlimited | 7_day_express_bus_pass | transit_check_metrocard | lib_special_senior | rail_road_unlimited_no_trade | transit_check_metrocard_annual_metrocard | mail_and_ride_ezpay_express | mail_and_ride_unlimited | path_2_trip | airtrain_full_fare | airtrain_30_day | airtrain_10_trip | airtrain_monthly | 
| =================== | =================== | ================= | ========================== | ========= | ======================= | ========================================== | =========================================== | ====================== | =============== | ================ | =================================== | =============== | ================ | ====================== | ======================= | ================== | ============================ | ======================================== | =========================== | ======================= | =========== | ================== | =============== | ================ | ================ | 
| 2016-02-13T00:00:00 | 2016-02-19T00:00:00 | R001              | WHITEHALL STREET           | 46710     | 1811                    | 264                                        | 756                                         | 231                    | 21775           | 28241            | 0                                   | 0               | 0                | 0                      | 773                     | 430                | 432                          | 3440                                     | 1202                        | 470                     | 0           | 843                | 0               | 0                | 0                | 
| 2016-02-13T00:00:00 | 2016-02-19T00:00:00 | R003              | CYPRESS HILLS              | 2793      | 138                     | 14                                         | 40                                          | 0                      | 2171            | 1168             | 0                                   | 0               | 0                | 0                      | 22                      | 61                 | 1                            | 97                                       | 6                           | 9                       | 0           | 7                  | 0               | 0                | 0                | 
| 2016-02-13T00:00:00 | 2016-02-19T00:00:00 | R004              | 75TH STREET & ELDERTS LANE | 7229      | 356                     | 28                                         | 102                                         | 0                      | 5144            | 3822             | 0                                   | 0               | 0                | 0                      | 82                      | 193                | 0                            | 254                                      | 32                          | 52                      | 0           | 75                 | 0               | 0                | 0                | 
| 2016-02-13T00:00:00 | 2016-02-19T00:00:00 | R005              | 85TH STREET & FOREST PKWAY | 7998      | 441                     | 36                                         | 177                                         | 4                      | 5407            | 4897             | 0                                   | 0               | 0                | 0                      | 66                      | 158                | 0                            | 255                                      | 51                          | 76                      | 0           | 70                 | 0               | 0                | 0                | 
| 2016-02-13T00:00:00 | 2016-02-19T00:00:00 | R006              | WOODHAVEN BOULEVARD        | 7641      | 422                     | 27                                         | 149                                         | 1                      | 6857            | 5120             | 0                                   | 0               | 0                | 0                      | 88                      | 151                | 3                            | 300                                      | 72                          | 61                      | 0           | 64                 | 0               | 0                | 0                | 
| 2016-02-13T00:00:00 | 2016-02-19T00:00:00 | R007              | 104TH STREET               | 5803      | 236                     | 31                                         | 48                                          | 10                     | 3618            | 2918             | 0                                   | 0               | 0                | 0                      | 45                      | 139                | 0                            | 162                                      | 22                          | 29                      | 0           | 20                 | 0               | 0                | 0                | 
| 2016-02-13T00:00:00 | 2016-02-19T00:00:00 | R008              | 111TH STREET               | 4720      | 228                     | 35                                         | 44                                          | 2                      | 3347            | 2283             | 0                                   | 0               | 0                | 0                      | 34                      | 139                | 3                            | 128                                      | 48                          | 16                      | 0           | 44                 | 0               | 0                | 0                | 
| 2016-02-13T00:00:00 | 2016-02-19T00:00:00 | R009              | 121ST STREET               | 4504      | 247                     | 31                                         | 61                                          | 1                      | 3790            | 2339             | 0                                   | 0               | 0                | 0                      | 44                      | 144                | 0                            | 116                                      | 57                          | 46                      | 0           | 35                 | 0               | 0                | 0                | 
| 2016-02-13T00:00:00 | 2016-02-19T00:00:00 | R010              | 42ND STREET & 8TH AVENUE   | 86193     | 4260                    | 358                                        | 1073                                        | 163                    | 46600           | 54633            | 0                                   | 0               | 0                | 0                      | 854                     | 917                | 124                          | 4589                                     | 1597                        | 1044                    | 0           | 2268               | 0               | 0                | 0                | 
| 2016-02-13T00:00:00 | 2016-02-19T00:00:00 | R011              | 42ND STREET & 8TH AVENUE   | 218357    | 9223                    | 553                                        | 1522                                        | 134                    | 42639           | 70642            | 0                                   | 1               | 0                | 0                      | 2516                    | 3745               | 85                           | 5309                                     | 4995                        | 1438                    | 0           | 2396               | 0               | 0                | 0                | 
```