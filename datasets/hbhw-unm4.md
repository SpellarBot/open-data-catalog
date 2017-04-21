# Hawaii EV Charging Stations 02072013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaii-ev-charging-stations-02072013-11fcd) |
| Metadata | [Link](https://data.hawaii.gov/api/views/hbhw-unm4) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/hbhw-unm4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/hbhw-unm4/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | hbhw-unm4 |
| Name | Hawaii EV Charging Stations 02072013 |
| Category | Economic Development |
| Created | 2013-02-07T17:51:00Z |
| Publication Date | 2013-11-05T01:33:31Z |

## Description

Hawaii EV Charging Stations

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | station_name       | Station name       | text      | text        |
| Yes      | series tag     | location           | Location           | text      | text        |
| Yes      | series tag     | island             | Island             | text      | text        |
| Yes      | series tag     | zip_code           | Zip Code           | text      | text        |
| Yes      | series tag     | charge_fee         | Charge Fee         | text      | text        |
| Yes      | series tag     | park_fee           | Park Fee           | text      | text        |
| Yes      | series tag     | parking_lot        | Parking Lot        | text      | text        |
| Yes      | series tag     | hours              | Hours              | text      | text        |
| Yes      | numeric metric | ports              | Ports              | number    | number      |
| Yes      | series tag     | restrictions       | Restrictions       | text      | text        |
| Yes      | numeric metric | number_of_stations | Number of Stations | number    | number      |
| Yes      | series tag     | facilities         | Charge Fees        | text      | text        |
| Yes      | series tag     | manufacturers      | Manufacturers      | text      | text        |
| Yes      | numeric metric | charging_levels    | Charging Levels    | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hbhw-unm4 d:2013-10-18T18:10:53.000Z t:charge_fee=TBD t:park_fee="Free Self-Park and Valet during the day,  Registered Guests have a $20/night parking fee." t:station_name="Four Seasons Resort Hualalai" t:parking_lot="Four Seasons Resort Hualalai" t:zip_code=96740 t:restrictions="Priority is for Registered Guests, but restaurant guests are welcome to charge at no cost.  4 hour limit on EV charging.  Parking fees may apply." t:location="Chargers are located in the Golf Crescent self-park lot, but EV drivers must Valetto utilize Charger" t:manufacturers=OpConnect t:hours=24/7 t:facilities=Free t:island=Hawaii m:ports=2 m:charging_levels=2 m:number_of_stations=2

series e:hbhw-unm4 d:2013-10-18T18:10:53.000Z t:charge_fee=TBD t:park_fee="Free Validated parking, $15/Day Self Park overnight, $20/Day Valet overnight." t:station_name="Hapuna Beach Prince Hotel" t:parking_lot="Hapuna Beach Prince Hotel" t:zip_code=96743 t:restrictions="4 hour limit on EV charging.  Parking fees may apply." t:location=Valet t:manufacturers=OpConnect t:hours=24/7 t:facilities=Free t:island=Hawaii m:ports=4 m:charging_levels=2 m:number_of_stations=2

series e:hbhw-unm4 d:2013-10-18T18:10:53.000Z t:charge_fee=Free t:park_fee="24 hours $10.  16-30 minutes is $1, 31 minutes- 60 minutes $2, 61 minutes-2 hours $5, 2 hours-3 hours $8." t:station_name="Hilo International Airport" t:parking_lot="Hilo International Airport" t:zip_code=96720 t:restrictions="No overnight parking at EV Charger.  Parking fees may apply." t:location="In parking lot close to terminal entrance" t:manufacturers="Recharge Power" t:hours="5:00am - 10:00pm" t:facilities=Free t:island=Hawaii m:ports=2 m:charging_levels=2 m:number_of_stations=2
```

## Meta Commands

```ls
metric m:ports p:integer l:Ports t:dataTypeName=number

metric m:number_of_stations p:integer l:"Number of Stations" t:dataTypeName=number

metric m:charging_levels p:integer l:"Charging Levels" t:dataTypeName=number

entity e:hbhw-unm4 l:"Hawaii EV Charging Stations 02072013" t:url=https://data.hawaii.gov/api/views/hbhw-unm4

property e:hbhw-unm4 t:meta.view v:id=hbhw-unm4 v:category="Economic Development" v:averageRating=0 v:name="Hawaii EV Charging Stations 02072013"

property e:hbhw-unm4 t:meta.view.owner v:id=mypw-jcie v:screenName=deanna v:displayName=deanna

property e:hbhw-unm4 t:meta.view.tableauthor v:id=mypw-jcie v:screenName=deanna v:roleName=editor v:displayName=deanna
```

## Top Records

```ls
| :updated_at | station_name                          | location                                                                                             | island | zip_code | charge_fee                                                      | park_fee                                                                                                 | parking_lot                           | hours                                                               | ports | restrictions                                                                                                                                    | number_of_stations | facilities | manufacturers  | charging_levels | 
| =========== | ===================================== | ==================================================================================================== | ====== | ======== | =============================================================== | ======================================================================================================== | ===================================== | =================================================================== | ===== | =============================================================================================================================================== | ================== | ========== | ============== | =============== | 
| 1382119853  | Four Seasons Resort Hualalai          | Chargers are located in the Golf Crescent self-park lot, but EV drivers must Valetto utilize Charger | Hawaii | 96740    | TBD                                                             | Free Self-Park and Valet during the day, Registered Guests have a $20/night parking fee.                 | Four Seasons Resort Hualalai          | 24/7                                                                | 2     | Priority is for Registered Guests, but restaurant guests are welcome to charge at no cost. 4 hour limit on EV charging. Parking fees may apply. | 2                  | Free       | OpConnect      | 2               | 
| 1382119853  | Hapuna Beach Prince Hotel             | Valet                                                                                                | Hawaii | 96743    | TBD                                                             | Free Validated parking, $15/Day Self Park overnight, $20/Day Valet overnight.                            | Hapuna Beach Prince Hotel             | 24/7                                                                | 4     | 4 hour limit on EV charging. Parking fees may apply.                                                                                            | 2                  | Free       | OpConnect      | 2               | 
| 1382119853  | Hilo International Airport            | In parking lot close to terminal entrance                                                            | Hawaii | 96720    | Free                                                            | 24 hours $10. 16-30 minutes is $1, 31 minutes- 60 minutes $2, 61 minutes-2 hours $5, 2 hours-3 hours $8. | Hilo International Airport            | 5:00am - 10:00pm                                                    | 2     | No overnight parking at EV Charger. Parking fees may apply.                                                                                     | 2                  | Free       | Recharge Power | 2               | 
| 1382119853  | University of Hawaii at Hilo          | Attached to lifescience building 3344                                                                | Hawaii | 96720    | Free                                                            | Free for EV Drivers while Charging.                                                                      | University of Hawaii at Hilo          | 24/7                                                                | 1     | Free parking EV Drivers while charging.                                                                                                         | 1                  | Free       | Legrand        | 2               | 
| 1382119853  | Hilton Waikaloa                       | Valet                                                                                                | Hawaii | 96738    | TBD                                                             | $15/Day Self Park, $20/Day Valet                                                                         | Hilton Waikaloa                       | 24/7                                                                | 8     | Valet needs to swipe card to activate Charger. 4 hour limit on EV charging. Parking fees may apply.                                             | 4                  | Free       | OpConnect      | 2               | 
| 1382119853  | Kona Commons Shopping Center          | On side of Sports Authority                                                                          | Hawaii | 96740    | TBD                                                             | Free                                                                                                     | Kona Commons Shopping Center          | 8:00am-10:00pm                                                      | 4     | FOB key required to activate charging station. 4 hour limit. Parking fees may apply.                                                            | 2                  | Free       | OpConnect      | 2               | 
| 1382119853  | Kona International Airport at Keahole | 1st floor of parking structure across from entrance gate                                             | Hawaii | 96740    | Free until further notice, anticipated charging fee: $7/session | 24 hours $10. 16-30 minutes is $1, 31 minutes- 60 minutes $2, 61 minutes-2 hours $5, 2 hours-3 hours $8. | Kona International Airport at Keahole | 24/7                                                                | 2     | No overnight parking at EV Charger. Parking rates may apply.                                                                                    | 2                  | Free       | Recharge Power | 2               | 
| 1382119853  | Mauna Kea Beach Resort                | South end of the parking lot, near the Valet area                                                    | Hawaii | 96743    | TBD                                                             | Free Self-Park and Valet during the day, Registered Guests have a $20/night parking fee.                 | Mauna Kea Beach Resort                | 24/7                                                                | 4     | 4 hour limit. EV driver needs to pick up a key from the office at the first right after entering parking. Parking rates may apply.              | 2                  | Free       | OpConnect      | 2               | 
| 1382119853  | National Car Rental Kona Airport      | Outside parking, side of the building                                                                | Hawaii | 96740    | TBD                                                             | 24 hours $10. 16-30 minutes is $1, 31 minutes- 60 minutes $2, 61 minutes-2 hours $5, 2 hours-3 hours $8. | National Car Rental Kona Airport      | 5:30am-11:30pm                                                      | 2     | FOB key required to activate charging station. 4 hour limit. Parking rates may apply.                                                           | 1                  | Free       | OpConnect      | 2               | 
| 1382119853  | West Hawaii Civic Center              | 1st floor of parking structure in covered structure                                                  | Hawaii | 96740    | TBD                                                             | Free                                                                                                     | West Hawaii Civic Center              | 7:45am-4:30pm Close first Fri of month and County observed holidays | 6     | 4 hour limit. Parking fees may apply.                                                                                                           | 3                  | Free       | OpConnect      | 2               | 
```