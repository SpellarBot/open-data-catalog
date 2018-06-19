# DCAS Managed Building Energy Usage

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dcas-managed-building-energy-usage) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ubdi-jgw2) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ubdi-jgw2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ubdi-jgw2/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ubdi-jgw2 |
| Name | DCAS Managed Building Energy Usage |
| Attribution | Department of Citywide Administrative Services (DCAS) |
| Category | City Government |
| Created | 2015-12-29T22:04:07Z |
| Publication Date | 2015-12-29T22:09:40Z |

## Description

City Building Energy Usage Data.

## Columns

```ls
| Included | Schema Type    | Field Name                                                | Name                                                          | Data Type | Render Type |
| ======== | ============== | ========================================================= | ============================================================= | ========= | =========== |
| No       | time           | :updated_at                                               | updated_at                                                    | meta_data | meta_data   |
| Yes      | series tag     | borough_number                                            | Borough Number                                                | text      | number      |
| Yes      | series tag     | building_name                                             | Building Name                                                 | text      | text        |
| No       |                | building_address                                          | Building Address                                              | text      | text        |
| Yes      | series tag     | borough                                                   | Borough                                                       | text      | text        |
| Yes      | series tag     | state                                                     | State                                                         | text      | text        |
| Yes      | series tag     | zip_code                                                  | Zip Code                                                      | text      | number      |
| Yes      | series tag     | block                                                     | Block                                                         | text      | number      |
| Yes      | series tag     | lot                                                       | Lot                                                           | text      | number      |
| Yes      | numeric metric | fy15_energy_usage_mmbtu_utility_energy_excluding_fuel_oil | FY15 Energy Usage (MMBTU) [Utility energy, excluding Fuel Oil | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = building_address
```

## Data Commands

```ls
series e:ubdi-jgw2 d:2015-12-29T14:04:12.000Z t:building_name="Manhattan Municipal Building" t:borough_number=1 t:zip_code=10007 t:state="New York" t:lot=1 t:block=121 t:borough=Manhattan m:fy15_energy_usage_mmbtu_utility_energy_excluding_fuel_oil=92117

series e:ubdi-jgw2 d:2015-12-29T14:04:12.000Z t:building_name="Staten Island Borough Hall" t:borough_number=5 t:zip_code=10301 t:state="New York" t:lot=1 t:block=7 t:borough="Staten Island" m:fy15_energy_usage_mmbtu_utility_energy_excluding_fuel_oil=11385

series e:ubdi-jgw2 d:2015-12-29T14:04:12.000Z t:building_name="Manhattan Criminal Court" t:borough_number=1 t:zip_code=10013 t:state="New York" t:lot=1 t:block=167 t:borough=Manhattan m:fy15_energy_usage_mmbtu_utility_energy_excluding_fuel_oil=126511
```

## Meta Commands

```ls
metric m:fy15_energy_usage_mmbtu_utility_energy_excluding_fuel_oil p:integer l:"FY15 Energy Usage (MMBTU) [Utility energy, excluding Fuel Oil" t:dataTypeName=number

entity e:ubdi-jgw2 l:"DCAS Managed Building Energy Usage" t:attribution="Department of Citywide Administrative Services (DCAS)" t:url=https://data.cityofnewyork.us/api/views/ubdi-jgw2

property e:ubdi-jgw2 t:meta.view v:id=ubdi-jgw2 v:category="City Government" v:averageRating=0 v:name="DCAS Managed Building Energy Usage" v:attribution="Department of Citywide Administrative Services (DCAS)"

property e:ubdi-jgw2 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ubdi-jgw2 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | borough_number | building_name                | building_address     | borough       | state    | zip_code | block | lot | fy15_energy_usage_mmbtu_utility_energy_excluding_fuel_oil | 
| =========== | ============== | ============================ | ==================== | ============= | ======== | ======== | ===== | === | ========================================================= | 
| 1451397852  | 1              | Manhattan Municipal Building | 1 Centre St          | Manhattan     | New York | 10007    | 121   | 1   | 92117                                                     | 
| 1451397852  | 5              | Staten Island Borough Hall   | 10 Richmond Ter      | Staten Island | New York | 10301    | 7     | 1   | 11385                                                     | 
| 1451397852  | 1              | Manhattan Criminal Court     | 100 Centre Street    | Manhattan     | New York | 10013    | 167   | 1   | 126511                                                    | 
| 1451397852  | 1              | 100 Gold St                  | 100 Gold St          | Manhattan     | New York | 10038    | 94    | 25  | 64582                                                     | 
| 1451397852  | 5              | Staten Island Family Court   | 100 Richmond Ter     | Staten Island | New York | 10301    | 9     | 22  | 1429                                                      | 
| 1451397852  | 5              | Staten Island Village Hall   | 111 Canal St         | Staten Island | New York | 10304    | 523   | 1   | 932                                                       | 
| 1451397852  | 1              | Manhattan Civil Court        | 111 Centre St        | Manhattan     | New York | 10013    | 169   | 10  | 27287                                                     | 
| 1451397852  | 1              | 115 Chrystie                 | 115 Chrystie Street  | Manhattan     | New York | 10002    | 423   | 22  | 1974                                                      | 
| 1451397852  | 2              | Bronx Housing Court          | 1118 Grand Concourse | Bronx         | New York | 10456    | 2462  | 39  | 9119                                                      | 
| 1451397852  | 3              | Brooklyn Criminal Court      | 120 Schermerhorn St  | Brooklyn      | New York | 11201    | 169   | 17  | 104757                                                    | 
```