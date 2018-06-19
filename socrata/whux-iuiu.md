# Oil Usage ( Select City Owned Buildings)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oil-usage-select-city-owned-buildings-8ba3b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/whux-iuiu) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/whux-iuiu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/whux-iuiu/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | whux-iuiu |
| Name | Oil Usage ( Select City Owned Buildings) |
| Attribution | Department of Citywide Administrative Services (DCAS) |
| Category | Environment |
| Tags | oil usage ( select city owned buildings), oil, city, data, statistics, heating, energy, coned, thermostat, heat |
| Created | 2012-09-06T17:13:17Z |
| Publication Date | 2013-06-26T17:15:04Z |

## Description

Oil usage statistics for a select portfolio of City-owned buildings

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                           | Data Type | Render Type |
| ======== | ============== | ====================== | ============================== | ========= | =========== |
| No       | time           | :updated_at            | updated_at                     | meta_data | meta_data   |
| Yes      | series tag     | bin_number             | BIN Number                     | text      | number      |
| Yes      | series tag     | building               | Building                       | text      | text        |
| Yes      | numeric metric | sqft                   | SqFt                           | number    | number      |
| Yes      | series tag     | electric               | Electric                       | text      | text        |
| Yes      | series tag     | natural_gas_usage_1    | 2006 Natural Gas Usage         | text      | text        |
| Yes      | series tag     | fuel_oil_2_delivery_1  | 2006 Fuel Oil #2- Delivery     | text      | text        |
| Yes      | series tag     | fuel_oil_4_delivery_1  | 2006 Fuel Oil #4 - Delivery    | text      | text        |
| Yes      | series tag     | fuel_oil_6_delivery_1  | 2006 Fuel Oil #6 - Delivery    | text      | text        |
| Yes      | series tag     | steam_usage_1          | 2006 Steam usage               | text      | text        |
| Yes      | series tag     | electric_usage         | 2011 Electric usage            | text      | text        |
| Yes      | series tag     | natural_gas_usage_2    | 2011 Natural Gas usage         | text      | text        |
| Yes      | numeric metric | fuel_oil_2_b5_delivery | 2011 Fuel Oil #2 B5 - Delivery | number    | text        |
| Yes      | series tag     | fuel_oil_2_delivery_2  | 2011 Fuel Oil #2- Delivery     | text      | text        |
| Yes      | series tag     | fuel_oil_4_delivery_2  | 2011 Fuel Oil #4 - Delivery    | text      | text        |
| Yes      | series tag     | fuel_oil_6_delivery_2  | 2011 Fuel Oil #6 - Delivery    | text      | text        |
| Yes      | series tag     | steam_usage_2          | 2011 Steam usage               | text      | text        |
| Yes      | series tag     | types                  | Types                          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:whux-iuiu d:2012-09-06T10:13:18.000Z t:fuel_oil_2_delivery_2=1497 t:building="Office Building 100 Gold St" t:fuel_oil_6_delivery_2=N/A t:bin_number=1001289 t:types="Gas Primary/FO Secondary" t:fuel_oil_4_delivery_2=N/A m:fuel_oil_2_b5_delivery=4660

series e:whux-iuiu d:2012-09-06T10:13:18.000Z t:fuel_oil_2_delivery_2=N/A t:building="Office Building (345 Adams Street)" t:fuel_oil_6_delivery_2=N/A t:bin_number=3392969 t:types="Gas Primary/FO Secondary" t:fuel_oil_4_delivery_2=N/A m:fuel_oil_2_b5_delivery=511

series e:whux-iuiu d:2012-09-06T10:13:18.000Z t:fuel_oil_2_delivery_2=N/A t:building="Queens Supreme Court" t:fuel_oil_6_delivery_2=N/A t:bin_number=4207071 t:types="Gas Primary/FO Secondary" t:fuel_oil_4_delivery_2=N/A m:fuel_oil_2_b5_delivery=662
```

## Meta Commands

```ls
metric m:sqft p:long l:SqFt t:dataTypeName=number

entity e:whux-iuiu l:"Oil Usage ( Select City Owned Buildings)" t:attribution="Department of Citywide Administrative Services (DCAS)" t:url=https://data.cityofnewyork.us/api/views/whux-iuiu

property e:whux-iuiu t:meta.view v:id=whux-iuiu v:category=Environment v:averageRating=0 v:name="Oil Usage ( Select City Owned Buildings)" v:attribution="Department of Citywide Administrative Services (DCAS)"

property e:whux-iuiu t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:whux-iuiu t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | bin_number | building                                  | sqft | electric | natural_gas_usage_1 | fuel_oil_2_delivery_1 | fuel_oil_4_delivery_1 | fuel_oil_6_delivery_1 | steam_usage_1 | electric_usage | natural_gas_usage_2 | fuel_oil_2_b5_delivery | fuel_oil_2_delivery_2 | fuel_oil_4_delivery_2 | fuel_oil_6_delivery_2 | steam_usage_2 | types                                      | 
| =========== | ========== | ========================================= | ==== | ======== | =================== | ===================== | ===================== | ===================== | ============= | ============== | =================== | ====================== | ===================== | ===================== | ===================== | ============= | ========================================== | 
| 1346926398  | 2009911    | Bronx Bergen Building                     |      |          |                     |                       |                       |                       |               |                |                     | N/A                    | N/A                   | 1740                  | N/A                   |               | Gas Primary/FO Secondary                   | 
| 1346926398  | 1001289    | Office Building 100 Gold St               |      |          |                     |                       |                       |                       |               |                |                     | 4660                   | 1497                  | N/A                   | N/A                   |               | Gas Primary/FO Secondary                   | 
| 1346926398  | 1001835    | Clocktower Building                       |      |          |                     |                       |                       |                       |               |                |                     | N/A                    | N/A                   | N/A                   | N/A                   |               | ConEd Steam                                | 
| 1346926398  | 2099027    | Bronx Concourse Plaza                     |      |          |                     |                       |                       |                       |               |                |                     | N/A                    | N/A                   | N/A                   | N/A                   |               | Gas Only                                   | 
| 1346926398  | 1078613    | City Planning Building                    |      |          |                     |                       |                       |                       |               |                |                     | N/A                    | N/A                   | N/A                   | N/A                   |               | ConEd Steam                                | 
| 1346926398  | 3392969    | Office Building (345 Adams Street)        |      |          |                     |                       |                       |                       |               |                |                     | 511                    | N/A                   | N/A                   | N/A                   |               | Gas Primary/FO Secondary                   | 
| 1346926398  | 5000085    | Office Building (130 Stuyvesant Place SI) |      |          |                     |                       |                       |                       |               |                |                     | N/A                    | N/A                   | N/A                   | N/A                   |               | No boilers, Heated with Gas Fired Chillers | 
| 1346926398  | 1079215    | Sun Building                              |      |          |                     |                       |                       |                       |               |                |                     | N/A                    | N/A                   | N/A                   | N/A                   |               | ConEd Steam                                | 
| 1346926398  | 1002358    | Excelsior Building                        |      |          |                     |                       |                       |                       |               |                |                     | N/A                    | 1957                  | N/A                   | N/A                   |               | Gas Primary/FO Secondary                   | 
| 1346926398  | 1001830    | Louis J Lefkowitz Building                |      |          |                     |                       |                       |                       |               |                |                     | N/A                    | N/A                   | N/A                   | N/A                   |               | ConEd Steam                                | 
```