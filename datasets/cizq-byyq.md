# Hawaii Public Electric Vehicle Charging Stations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaii-public-electric-vehicle-charging-stations-57e51) |
| Metadata | [Link](https://data.hawaii.gov/api/views/cizq-byyq) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/cizq-byyq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/cizq-byyq/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | cizq-byyq |
| Name | Hawaii Public Electric Vehicle Charging Stations |
| Created | 2013-02-06T23:49:33Z |
| Publication Date | 2017-01-26T18:51:51Z |

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| No       | time           | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag     | station_id             | Station ID             | text      | number      |
| Yes      | series tag     | property_business_name | Property/Business Name | text      | text        |
| Yes      | series tag     | street_address         | Street Address         | text      | text        |
| Yes      | series tag     | city                   | City                   | text      | text        |
| Yes      | series tag     | zip_code               | Zip Code               | text      | text        |
| Yes      | series tag     | island                 | Island                 | text      | text        |
| Yes      | series tag     | charge_fees            | Charge Fees            | text      | text        |
| Yes      | series tag     | charger_location       | Charger Location       | text      | text        |
| Yes      | series tag     | hours_of_operation     | Hours of Operation     | text      | text        |
| Yes      | numeric metric | number_of_chargers     | Number of Chargers     | number    | number      |
| Yes      | numeric metric | number_of_ports        | Number of Ports        | number    | number      |
| Yes      | numeric metric | charger_level_s        | Charger Level(s)       | number    | text        |
| Yes      | series tag     | charger_fee            | Charger Fee            | text      | text        |
| Yes      | series tag     | parking_fee            | Parking Fee            | text      | text        |
| Yes      | series tag     | manufacturer_s         | Manufacturer(s)        | text      | text        |
| Yes      | series tag     | notes                  | Notes                  | text      | text        |
| No       |                | latitude               | Latitude               | number    | number      |
| Yes      | numeric metric | logitude               | Longitude              | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude
```

## Data Commands

```ls
series e:cizq-byyq d:2017-01-26T18:51:08.000Z t:zip_code=96740 t:charger_location="The charging stations are located in the Golf Crescent self-park lot, but EV drivers must Valet to utilize them." t:hours_of_operation=24/7 t:property_business_name="Four Seasons Resort Hualalai" t:island=Hawaii t:city=Kailua-Kona t:charger_fee="$2/hour or any fraction thereof" t:parking_fee="Free Self-Park and Valet during the day,  Registered Guests have a $20/night parking fee." t:station_id=257 t:street_address="72-100 Kaupulehu Dr." t:notes="EV drivers must Valet to utilize charging stations.  Priority is for Registered Guests, but restaurant guests are welcome to charge at no cost.  4 hour limit on EV charging.  Parking fees may apply." t:charge_fees=Paid t:manufacturer_s=OpConnect m:charger_level_s=2 m:number_of_chargers=2 m:logitude=-155.9913758 m:number_of_ports=2

series e:cizq-byyq d:2017-01-26T18:51:08.000Z t:zip_code=96743 t:charger_location="The charging stations.are located in the valet" t:hours_of_operation=24/7 t:property_business_name="Hapuna Beach Prince Hotel" t:island=Hawaii t:city="Kohala Coast" t:charger_fee="$2/hour or any fraction thereof" t:parking_fee="Free Validated parking, $15/Day Self Park overnight, $20/Day Valet overnight." t:station_id=259 t:street_address="62-100 Kaunaoa Dr." t:notes="The OpConnect charging stations accept debit cards, credit cards, the Wright Express Fleet Fueling card, and the OpConnect card.  Parking fees may apply." t:charge_fees=Paid t:manufacturer_s=OpConnect m:charger_level_s=2 m:number_of_chargers=2 m:logitude=-155.824429 m:number_of_ports=4

series e:cizq-byyq d:2017-01-26T18:51:08.000Z t:zip_code=96720 t:charger_location="The charging stations.are located in the parking lot close to terminal entrance" t:hours_of_operation="5:00am - 10:00pm" t:property_business_name="Hilo International Airport" t:island=Hawaii t:city=Hilo t:charger_fee=Free t:parking_fee="24 hours $10.  16-30 minutes is $1, 31 minutes- 60 minutes $2, 61 minutes-2 hours $5, 2 hours-3 hours $8." t:station_id=261 t:street_address="2450 Kekuanaoa St" t:notes="No overnight parking at the charging station." t:charge_fees=Free t:manufacturer_s="Recharge Power" m:charger_level_s=2 m:number_of_chargers=2 m:logitude=-155.03988 m:number_of_ports=2
```

## Meta Commands

```ls
metric m:number_of_chargers p:integer l:"Number of Chargers" t:dataTypeName=number

metric m:number_of_ports p:integer l:"Number of Ports" t:dataTypeName=number

metric m:charger_level_s p:integer l:"Charger Level(s)" t:dataTypeName=number

metric m:logitude p:double l:Longitude t:dataTypeName=number

entity e:cizq-byyq l:"Hawaii Public Electric Vehicle Charging Stations" t:url=https://data.hawaii.gov/api/views/cizq-byyq

property e:cizq-byyq t:meta.view v:id=cizq-byyq v:averageRating=0 v:name="Hawaii Public Electric Vehicle Charging Stations"

property e:cizq-byyq t:meta.view.owner v:id=35qp-mmd7 v:screenName="Zheng Fang" v:displayName="Zheng Fang"

property e:cizq-byyq t:meta.view.tableauthor v:id=35qp-mmd7 v:screenName="Zheng Fang" v:roleName=publisher v:displayName="Zheng Fang"
```

## Top Records

```ls
| :updated_at | station_id | property_business_name             | street_address                | city         | zip_code | island | charge_fees | charger_location                                                                                                                          | hours_of_operation | number_of_chargers | number_of_ports | charger_level_s | charger_fee                     | parking_fee                                                                                              | manufacturer_s | notes                                                                                                                                                                                                                               | latitude   | logitude     | 
| =========== | ========== | ================================== | ============================= | ============ | ======== | ====== | =========== | ========================================================================================================================================= | ================== | ================== | =============== | =============== | =============================== | ======================================================================================================== | ============== | =================================================================================================================================================================================================================================== | ========== | ============ | 
| 1485456668  | 257        | Four Seasons Resort Hualalai       | 72-100 Kaupulehu Dr.          | Kailua-Kona  | 96740    | Hawaii | Paid        | The charging stations are located in the Golf Crescent self-park lot, but EV drivers must Valet to utilize them.                          | 24/7               | 2                  | 2               | 2               | $2/hour or any fraction thereof | Free Self-Park and Valet during the day, Registered Guests have a $20/night parking fee.                 | OpConnect      | EV drivers must Valet to utilize charging stations. Priority is for Registered Guests, but restaurant guests are welcome to charge at no cost. 4 hour limit on EV charging. Parking fees may apply.                                 | 19.8271119 | -155.9913758 | 
| 1485456668  | 259        | Hapuna Beach Prince Hotel          | 62-100 Kaunaoa Dr.            | Kohala Coast | 96743    | Hawaii | Paid        | The charging stations.are located in the valet                                                                                            | 24/7               | 2                  | 4               | 2               | $2/hour or any fraction thereof | Free Validated parking, $15/Day Self Park overnight, $20/Day Valet overnight.                            | OpConnect      | The OpConnect charging stations accept debit cards, credit cards, the Wright Express Fleet Fueling card, and the OpConnect card. Parking fees may apply.                                                                            | 19.994437  | -155.824429  | 
| 1485456668  | 261        | Hilo International Airport         | 2450 Kekuanaoa St             | Hilo         | 96720    | Hawaii | Free        | The charging stations.are located in the parking lot close to terminal entrance                                                           | 5:00am - 10:00pm   | 2                  | 2               | 2               | Free                            | 24 hours $10. 16-30 minutes is $1, 31 minutes- 60 minutes $2, 61 minutes-2 hours $5, 2 hours-3 hours $8. | Recharge Power | No overnight parking at the charging station.                                                                                                                                                                                       | 19.71471   | -155.03988   | 
| 1485456668  | 263        | University of Hawaii at Hilo       | 200 W. Kawili Street          | Hilo         | 96720    | Hawaii | Free        | The charging station is located at the life science building, 3344                                                                        | 24/7               | 1                  | 1               | 2               | Free                            | Free for EV Drivers while Charging.                                                                      | Legrand        |                                                                                                                                                                                                                                     | 19.70127   | -155.07925   | 
| 1485456668  | 267        | Hilton Waikaloa                    | 69-425 Waikoloa Beach Dr.     | Waikoloa     | 96738    | Hawaii | Paid        | The charging stations.are located in the valet                                                                                            | 24/7               | 2                  | 2               | 2               | $2/hour or any fraction thereof | $15/Day Self Park, $20/Day Valet                                                                         | Tesla          | The OpConnect charging stations accept debit cards, credit cards, the Wright Express Fleet Fueling card, and the OpConnect card. Parking fees may apply.                                                                            | 19.925895  | -155.8837629 | 
| 1485456668  | 269        | Kona Commons Shopping Center       | 74-5450 Makala Blvd           | Kailua-Kona  | 96740    | Hawaii | Paid        | On side of Sports Authority                                                                                                               | 8:00am-10:00pm     | 2                  | 4               | 2               | $2/hour or any fraction thereof | Free                                                                                                     | OpConnect      | The OpConnect charging stations accept debit cards, credit cards, the Wright Express Fleet Fueling card, and the OpConnect card. Parking fees may apply.                                                                            | 19.6494936 | -156.0049149 | 
| 1485456668  | 273        | Mauna Kea Beach Resort             | 62-100 Mauna Kea Beach Dr.    | Waimea       | 96743    | Hawaii | Paid        | The charging stations are located at the south end of the parking lot, near the Valet area                                                | 24/7               | 2                  | 4               | 2               | $2/hour or any fraction thereof | Free Self-Park and Valet during the day, Registered Guests have a $20/night parking fee.                 | OpConnect      | The OpConnect charging stations accept debit cards, credit cards, the Wright Express Fleet Fueling card, and the OpConnect card. Parking fees may apply.                                                                            | 20.00638   | -155.82445   | 
| 1485456668  | 275        | Kona International Airport         | Keahole International Airport | Kailua-Kona  | 96740    | Hawaii | Paid        | On the first floor of garage across from the entrance gate.                                                                               | 5:30am-11:30pm     | 1                  | 2               | 2               | $2/hour or any fraction thereof | 24 hours $10. 16-30 minutes is $1, 31 minutes- 60 minutes $2, 61 minutes-2 hours $5, 2 hours-3 hours $8. | OpConnect      | Restricted to customers, when available. Priority given to fleet vehicles. The OpConnect charging stations accept debit cards, credit cards, the Wright Express Fleet Fueling card, and the OpConnect card. Parking fees may apply. | 19.7367705 | -156.0397822 | 
| 1485456668  | 285        | Lihue Civic Center-Piikoi Building | 4444 Rice Street              | Lihue        | 96766    | Kauai  | Paid        | 1 charger is located on the east side of the building and 2 chargers are located at the south entrance (Rice Street side) of the building | 24/7               | 3                  | 3               | 2               | $2.00/hour, up to 4 hours       | Free for EV Drivers                                                                                      | AeroVironment  | Charging fee is $2/hour. 4 hour limit. Free parking for EV drivers.                                                                                                                                                                 | 21.9750959 | -159.3691415 | 
| 1485456668  | 289        | Princeville Shopping Center        | 5-4280 Kuhio Highway          | Princeville  | 96722    | Kauai  | Paid        | The charging stations are located in the rear parking lot, next to public restrooms                                                       | 24/7               | 2                  | 2               | 2               | per kWh/hr                      | Free                                                                                                     | Volta          |                                                                                                                                                                                                                                     | 22.2135956 | -159.4743178 | 
```