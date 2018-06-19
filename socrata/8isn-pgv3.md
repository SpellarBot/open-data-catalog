# NYC Clean Heat dataset

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-clean-heat-dataset-d5995) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/8isn-pgv3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/8isn-pgv3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/8isn-pgv3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 8isn-pgv3 |
| Name | NYC Clean Heat dataset |
| Attribution | Office of the Mayor (OTM) |
| Category | City Government |
| Tags | clean heat, otm, city government |
| Created | 2014-10-21T21:24:41Z |
| Publication Date | 2014-10-21T21:31:34Z |

## Description

NYC Clean Heat dataset

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                        | Data Type | Render Type |
| ======== | ============== | ========================= | =========================== | ========= | =========== |
| Yes      | numeric metric | borough_block_lot         | Borough, Block, Lot #       | number    | number      |
| Yes      | series tag     | street_address            | Street Address              | text      | text        |
| Yes      | series tag     | zip_code                  | Zip Code                    | text      | number      |
| Yes      | series tag     | borough                   | Borough                     | text      | text        |
| Yes      | series tag     | utility                   | Utility                     | text      | text        |
| Yes      | series tag     | building_manager          | Building Manager            | text      | text        |
| Yes      | series tag     | owner                     | Owner                       | text      | text        |
| No       |                | owner_address             | Owner Address               | text      | text        |
| Yes      | series tag     | owner_telephone           | Owner Telephone             | text      | text        |
| Yes      | series tag     | dep_boiler_application    | DEP Boiler Application #    | text      | text        |
| Yes      | numeric metric | 6_deadline                | #6 Deadline                 | number    | number      |
| Yes      | series tag     | boiler_model              | Boiler Model                | text      | text        |
| Yes      | numeric metric | of_identical_boilers      | # of Identical Boilers      | number    | number      |
| Yes      | numeric metric | boiler_capacity_gross_btu | Boiler Capacity (Gross BTU) | number    | number      |
| No       |                | boiler_installation_date  | Boiler Installation Date    | text      | number      |
| Yes      | series tag     | boiler_age_range          | Boiler Age Range            | text      | text        |
| Yes      | time           | est_retirement_year       | Est. Retirement Year        | number    | number      |
| Yes      | series tag     | burner_model              | Burner Model                | text      | text        |
| Yes      | series tag     | primary_fuel              | Primary Fuel                | text      | text        |
| Yes      | numeric metric | total_gallons_high        | Total Gallons (High)        | number    | number      |
| Yes      | numeric metric | total_gallons_low         | Total Gallons (Low)         | number    | number      |
| Yes      | numeric metric | total_mmbtu_high          | Total MMBTU (High)          | number    | number      |
| Yes      | numeric metric | total_mmbtu_low           | Total MMBTU (low)           | number    | number      |
| Yes      | numeric metric | greener_greater_buildings | Greener Greater Buildings   | number    | number      |
| Yes      | numeric metric | ggb_deadline              | GGB Deadline                | number    | number      |
| Yes      | series tag     | building_type             | Building Type               | text      | text        |
| Yes      | series tag     | city_council_district     | City Council District       | text      | number      |
| Yes      | series tag     | city_community_board      | City Community Board        | text      | text        |
| Yes      | series tag     | bldg_sqft                 | Bldg Sqft                   | text      | text        |
| Yes      | numeric metric | of_bldgs                  | # of Bldgs                  | number    | number      |
| Yes      | numeric metric | of_floors                 | # of Floors                 | number    | number      |
| Yes      | numeric metric | of_res_units              | # of Res. Units             | number    | number      |
| Yes      | numeric metric | total_units               | Total Units                 | number    | number      |
| Yes      | numeric metric | year_built                | Year Built                  | number    | number      |
| Yes      | series tag     | condo                     | Condo?                      | text      | text        |
| Yes      | series tag     | coop                      | Coop?                       | text      | text        |
```

## Time Field

```ls
Value = est_retirement_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = owner_address,boiler_installation_date
```

## Data Commands

```ls
series e:8isn-pgv3 d:2020-01-01T00:00:00.000Z t:city_council_district=1 t:zip_code=10280 t:building_manager="ROCKROSE DEVELOPMENT CORP.COR" t:owner_telephone="212 34-5437" t:primary_fuel=#6 t:burner_model=INTEGRAL t:borough=Manhattan t:building_type="Elevator Apartments" t:bldg_sqft="* 219,703" t:utility="Con Edison" t:city_community_board="M 01" t:boiler_model="CLEAVER-BROOKS MOD. CB-600-200" t:owner="333 RECTOR REALTY LLC. COOPER SQUARE" t:boiler_age_range="21 to 26 years old" t:dep_boiler_application=CA182185M t:street_address="333 RECTOR PLACE" m:6_deadline=2014 m:year_built=1985 m:greener_greater_buildings=1 m:total_units=232 m:total_mmbtu_low=6000 m:total_gallons_high=48000 m:total_mmbtu_high=4200 m:boiler_capacity_gross_btu=8.4 m:of_identical_boilers=2 m:borough_block_lot=1000160080 m:of_bldgs=1 m:total_gallons_low=33600 m:ggb_deadline=2016 m:of_floors=15 m:of_res_units=227

series e:8isn-pgv3 d:2024-01-01T00:00:00.000Z t:city_council_district=1 t:condo=Yes t:zip_code=10280 t:building_manager="21 SOUTHEND OWNERS CORP." t:owner_telephone="212 842-7310" t:primary_fuel=#4 t:burner_model="S.T.JOHNSON FD68CAHM-200" t:borough=Manhattan t:building_type=Condominiums t:bldg_sqft="* 194,762" t:utility="Con Edison" t:city_community_board="M 01" t:boiler_model="FEDERAL FST 200" t:owner="THE REGATTA CONDOMINIUM/LISA MASULLO" t:boiler_age_range="21 to 26 years old" t:dep_boiler_application=CA052589N t:street_address="21 SOUTH END AVENUE" m:6_deadline=0 m:year_built=1988 m:greener_greater_buildings=1 m:total_units=184 m:total_mmbtu_low=21750 m:total_gallons_high=150877 m:total_mmbtu_high=15225 m:boiler_capacity_gross_btu=8.4 m:of_identical_boilers=2 m:borough_block_lot=1000167509 m:of_bldgs=1 m:total_gallons_low=105614 m:ggb_deadline=2016 m:of_floors=9 m:of_res_units=182

series e:8isn-pgv3 d:2021-01-01T00:00:00.000Z t:city_council_district=1 t:condo=Yes t:zip_code=10280 t:building_manager="RELATED MANAGEMENT" t:owner_telephone=212-996-6670 t:primary_fuel=#6 t:burner_model="ST. JOHNSON FD 68CAHM-300" t:borough=Manhattan t:building_type=Condominiums t:bldg_sqft="* 251,289" t:utility="Con Edison" t:city_community_board="M 01" t:boiler_model="FEDERAL PLW-265" t:owner="RELATED MGMT/CO. LP" t:boiler_age_range="21 to 26 years old" t:dep_boiler_application=CA442886N t:street_address="225 RECTOR PLACE" m:6_deadline=2014 m:year_built=1985 m:greener_greater_buildings=1 m:total_units=306 m:total_mmbtu_low=18750 m:total_gallons_high=124976 m:total_mmbtu_high=13125 m:boiler_capacity_gross_btu=11.2 m:of_identical_boilers=2 m:borough_block_lot=1000167515 m:of_bldgs=1 m:total_gallons_low=87483 m:ggb_deadline=2016 m:of_floors=23 m:of_res_units=304
```

## Meta Commands

```ls
metric m:borough_block_lot p:long l:"Borough, Block, Lot #" t:dataTypeName=number

metric m:6_deadline p:integer l:"#6 Deadline" t:dataTypeName=number

metric m:of_identical_boilers p:integer l:"# of Identical Boilers" t:dataTypeName=number

metric m:boiler_capacity_gross_btu p:double l:"Boiler Capacity (Gross BTU)" t:dataTypeName=number

metric m:total_gallons_high p:long l:"Total Gallons (High)" t:dataTypeName=number

metric m:total_gallons_low p:long l:"Total Gallons (Low)" t:dataTypeName=number

metric m:total_mmbtu_high p:float l:"Total MMBTU (High)" t:dataTypeName=number

metric m:total_mmbtu_low p:double l:"Total MMBTU (low)" t:dataTypeName=number

metric m:greener_greater_buildings p:integer l:"Greener Greater Buildings" t:dataTypeName=number

metric m:ggb_deadline p:integer l:"GGB Deadline" t:dataTypeName=number

metric m:of_bldgs p:integer l:"# of Bldgs" t:dataTypeName=number

metric m:of_floors p:integer l:"# of Floors" t:dataTypeName=number

metric m:of_res_units p:integer l:"# of Res. Units" t:dataTypeName=number

metric m:total_units p:integer l:"Total Units" t:dataTypeName=number

metric m:year_built p:integer l:"Year Built" t:dataTypeName=number

entity e:8isn-pgv3 l:"NYC Clean Heat dataset" t:attribution="Office of the Mayor (OTM)" t:url=https://data.cityofnewyork.us/api/views/8isn-pgv3

property e:8isn-pgv3 t:meta.view v:id=8isn-pgv3 v:category="City Government" v:averageRating=0 v:name="NYC Clean Heat dataset" v:attribution="Office of the Mayor (OTM)"

property e:8isn-pgv3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:8isn-pgv3 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough_block_lot | street_address      | zip_code | borough   | utility    | building_manager               | owner                                         | owner_address                                 | owner_telephone | dep_boiler_application | 6_deadline | boiler_model                   | of_identical_boilers | boiler_capacity_gross_btu | boiler_installation_date | boiler_age_range   | est_retirement_year | burner_model                   | primary_fuel | total_gallons_high | total_gallons_low | total_mmbtu_high   | total_mmbtu_low    | greener_greater_buildings | ggb_deadline | building_type       | city_council_district | city_community_board | bldg_sqft | of_bldgs | of_floors | of_res_units | total_units | year_built | condo | coop | 
| ================= | =================== | ======== | ========= | ========== | ============================== | ============================================= | ============================================= | =============== | ====================== | ========== | ============================== | ==================== | ========================= | ======================== | ================== | =================== | ============================== | ============ | ================== | ================= | ================== | ================== | ========================= | ============ | =================== | ===================== | ==================== | ========= | ======== | ========= | ============ | =========== | ========== | ===== | ==== | 
| 1000160080        | 333 RECTOR PLACE    | 10280    | Manhattan | Con Edison | ROCKROSE DEVELOPMENT CORP.COR  | 333 RECTOR REALTY LLC. COOPER SQUARE          | 6 EAST 43RD ST., MANHATTAN NY 10017           | 212 34-5437     | CA182185M              | 2014       | CLEAVER-BROOKS MOD. CB-600-200 | 2                    | 8.4                       | 1985                     | 21 to 26 years old | 2020                | INTEGRAL                       | #6           | 48000              | 33600             | 4200               | 6000               | 1                         | 2016         | Elevator Apartments | 1                     | M 01                 | * 219,703 | 1        | 15        | 227          | 232         | 1985       |       |      | 
| 1000167509        | 21 SOUTH END AVENUE | 10280    | Manhattan | Con Edison | 21 SOUTHEND OWNERS CORP.       | THE REGATTA CONDOMINIUM/LISA MASULLO          | 21 SOUTH END AVE, MANHATTAN NY 10280          | 212 842-7310    | CA052589N              | 0          | FEDERAL FST 200                | 2                    | 8.4                       | 1989                     | 21 to 26 years old | 2024                | S.T.JOHNSON FD68CAHM-200       | #4           | 150877             | 105614            | 15225              | 21750              | 1                         | 2016         | Condominiums        | 1                     | M 01                 | * 194,762 | 1        | 9         | 182          | 184         | 1988       | Yes   |      | 
| 1000167515        | 225 RECTOR PLACE    | 10280    | Manhattan | Con Edison | RELATED MANAGEMENT             | RELATED MGMT/CO. LP                           | 203 EAST 86TH STREET, MANHATTAN NY 10028      | 212-996-6670    | CA442886N              | 2014       | FEDERAL PLW-265                | 2                    | 11.2                      | 1986                     | 21 to 26 years old | 2021                | ST. JOHNSON FD 68CAHM-300      | #6           | 124976             | 87483             | 13125              | 18750              | 1                         | 2016         | Condominiums        | 1                     | M 01                 | * 251,289 | 1        | 23        | 304          | 306         | 1985       | Yes   |      | 
| 1000220013        | 26 BROADWAY         | 10004    | Manhattan | Con Edison | CONSTITUTION REALTY ASSOCIATES | NEWMARK & CO.REAL ESTATE INC.                 | 125 PARK AVENUE, NEW YORK NY 10017            | 718 763-6100    | CA003181Z              | 0          | ROCKMILLS MP 600               | 2                    | 25.2                      | 1981                     | 26 to 30 years old | 2016                | ICI DEG-252(P)                 | #4           | 234062             | 163844            | 31711.68           | 45302.400000000001 | 1                         | 2022         | Office Buildings    | 1                     | M 01                 | * 860,889 | 1        | 32        | 0            | 117         | 1923       |       |      | 
| 1000220013        | 26 BROADWAY         | 10004    | Manhattan | Con Edison | CONSTITUTION REALTY            | CONSTITUTION REALTY                           | 26 BROADWAY, MANHATTAN NY 10004               | 212 344-2150    | CA109275P              | 0          | ROCKMILLS MP 900               | 1                    | 37.5                      | 1975                     | 31 to 35 years old | 2010                | SUPERIOR AB 600                | #4           | 586920             | 410844            | 61626.6            | 88038              | 1                         | 2022         | Office Buildings    | 1                     | M 01                 | * 860,889 | 1        | 32        | 0            | 117         | 1923       |       |      | 
| 1000280001        | 3 HANOVER SQUARE    | 10004    | Manhattan | Con Edison | 3 HANOVER SQ OWNERS CORP.      | 3 HANOVER SQUARE OWNERS c/o ROSE ASSOCS.      | 200 MADISON AVE 5th fl., MANHATTAN NY 10016   | 212 328-5539    | CA164187R              | 0          | FEDERAL FST 300                | 2                    | 12.6                      | 1987                     | 21 to 26 years old | 2022                | ICI DEG 145 P                  | #4           | 202027             | 141419            | 20695.5            | 29565              | 1                         | 2018         | Elevator Apartments | 1                     | M 01                 | * 239,121 | 1        | 23        | 202          | 209         | 1926       |       | Yes  | 
| 1000300005        | 46 WATER STREET     | 10004    | Manhattan | Con Edison | EDWORD GORDON CO INC           | CB RICHARD ELLIS                              | 200 PARK AVENUE -16 FLOOR, MANHATTAN NY 10166 | 212-984-8373    | CA004487X              | 0          | TITUSVILLE 5475 SERIES W       | 1                    | 4.46                      | 1987                     | 21 to 26 years old | 2022                | HEVE/AM 3/4                    | #4           | 67343              | 47140             | 6783.5249999999996 | 9690.75            | 1                         | 2020         | Loft Buildings      | 1                     | M 01                 | * 85,472  | 1        | 11        | 0            | 3           | 1929       |       |      | 
| 1000520021        | 120 LIBERTY STREET  | 10006    | Manhattan | Con Edison | SAMSON                         | SAMSON MGMT. LLC                              | 97-77 QUEENS BLVD, REGO PARK NY 11374         | XXXX            | CA011497P              | 0          | FEDERAL FST-125 (NEW)          | 1                    | 5.3                       | 1997                     | 11 to 15 years old | 2032                | INDUSTRIAL COMB. MM-54S(EXIST) | #4           | 57487              | 40241             | 5834.9813000000004 | 8335.69            | 1                         | 2022         | Elevator Apartments | 1                     | M 01                 | * 57,945  | 1        | 13        | 21           | 24          | 1900       |       | Yes  | 
| 1000640015        | 160 BROADWAY        | 10038    | Manhattan | Con Edison | DAROR ASSOC.                   | DAROR ASSOC. LLC CO.,% BRUN MGMT.             | 160 BROADWAY, MANHATTAN NY 10038              | 212-349-2154    | CB000311K              | 0          | ROCKMILLS MP175                | 1                    | 7.3                       | 1980                     | 26 to 30 years old | 2015                | IRON FIREMAN A0-6-9.8RK        | #4           | 341640             | 239148            | 15943.2            | 22776              | 1                         | 2014         | Office Buildings    | 1                     | M 01                 | * 150,000 | 4        | 16        | 0            | 77          | 1908       |       |      | 
| 1000640016        | 170 BROADWAY        | 10038    | Manhattan | Con Edison | AMG REALTY PARTNERS LLP        | 170 BROADWAY OWNERS CORP c/o CB RICHARD ELLIS | 170 BROADWAY, MANHATTAN NY 10037              | XXX             | CA063777Y              | 2014       | ROCKMILLS MP-200               | 1                    | 9                         | 1977                     | 31 to 35 years old | 2012                | HEV-E-OIL DE-105(S) ( I.C.I.)  | #6           | 91250              | 63875             | 9581.25            | 13687.5            | 1                         | 2014         | Office Buildings    | 1                     | M 01                 | * 147,844 | 1        | 18        | 0            | 81          | 1903       |       |      | 
```