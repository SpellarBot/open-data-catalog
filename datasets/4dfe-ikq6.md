# Truck Parking Utilization - Parking Only

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/truck-parking-utilization-parking-only) |
| Metadata | [Link](https://data.iowa.gov/api/views/4dfe-ikq6) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/4dfe-ikq6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/4dfe-ikq6/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 4dfe-ikq6 |
| Name | Truck Parking Utilization - Parking Only |
| Attribution | Iowa DOT, HDR Engineering |
| Category | Transportation & Utilities |
| Tags | asset, classification, rest, area, truck, parking, iowa dot, iowa department of transportation |
| Created | 2016-08-19T20:29:31Z |
| Publication Date | 2016-08-19T20:31:11Z |

## Description

Iowa Department of Transportation statewide rest area data. This layer displays parking only areas with truck parking utilization.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| No       | time           | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag     | objectid                  | OBJECTID                  | text      | number      |
| Yes      | series tag     | full_name                 | Full_Name                 | text      | text        |
| Yes      | numeric metric | interstate                | Interstate                | number    | text        |
| Yes      | numeric metric | exit                      | Exit                      | number    | text        |
| Yes      | series tag     | direction                 | Direction                 | text      | text        |
| Yes      | numeric metric | approx_number_truck_space | Approx_Number_Truck_Space | number    | number      |
| Yes      | numeric metric | truck_percent             | Truck_Percent             | number    | number      |
| Yes      | series tag     | truck_perc_group          | Truck_Perc_Group          | text      | text        |
| Yes      | numeric metric | ukey                      | UKEY                      | number    | number      |
| Yes      | series tag     | inventory_                | INVENTORY_                | text      | text        |
| No       |                | address1                  | ADDRESS1                  | text      | text        |
| Yes      | series tag     | near_city                 | NEAR_CITY                 | text      | text        |
| Yes      | series tag     | phone_numb                | PHONE_NUMB                | text      | text        |
| Yes      | numeric metric | cost_cente                | COST_CENTE                | number    | text        |
| Yes      | numeric metric | square_foo                | SQUARE_FOO                | number    | number      |
| Yes      | series tag     | orig_fid                  | ORIG_FID                  | text      | number      |
| Yes      | numeric metric | year_built                | YEAR_BUILT                | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address1
```

## Data Commands

```ls
series e:4dfe-ikq6 d:2016-08-19T20:29:31.000Z t:truck_perc_group=0-74% t:inventory_=48 t:phone_numb=0 t:direction=NB t:objectid=1 t:orig_fid=0 t:full_name="I-35 NB - MP 53" t:near_city="St. Charles" m:approx_number_truck_space=6 m:interstate=35 m:truck_percent=100 m:ukey=50 m:cost_cente=555691 m:year_built=0 m:square_foo=0 m:exit=53

series e:4dfe-ikq6 d:2016-08-19T20:29:31.000Z t:truck_perc_group=0-74% t:inventory_=49 t:phone_numb=0 t:direction=SB t:objectid=2 t:orig_fid=0 t:full_name="I-35 SB - MP 51" t:near_city="St. Charles" m:approx_number_truck_space=6 m:interstate=35 m:truck_percent=100 m:ukey=49 m:cost_cente=555620 m:year_built=0 m:square_foo=0 m:exit=51

series e:4dfe-ikq6 d:2016-08-19T20:29:31.000Z t:truck_perc_group=0-74% t:inventory_=57 t:phone_numb=0 t:direction=NB t:objectid=4 t:orig_fid=0 t:full_name="I-29 NB - MP 92" t:near_city=Mondamin m:approx_number_truck_space=5 m:interstate=29 m:truck_percent=10 m:ukey=43 m:cost_cente=0 m:year_built=0 m:square_foo=0 m:exit=92
```

## Meta Commands

```ls
metric m:interstate p:integer l:Interstate d:Interstate t:dataTypeName=number

metric m:exit p:integer l:Exit d:Exit t:dataTypeName=number

metric m:approx_number_truck_space p:integer l:Approx_Number_Truck_Space d:"Approximate Number of Truck Spaces" t:dataTypeName=number

metric m:truck_percent p:integer l:Truck_Percent d:"Truck Utilization Percent" t:dataTypeName=number

metric m:ukey p:integer l:UKEY d:UKEY t:dataTypeName=number

metric m:cost_cente p:integer l:COST_CENTE d:COST_CENTE t:dataTypeName=number

metric m:square_foo p:integer l:SQUARE_FOO d:SQUARE_FOO t:dataTypeName=number

metric m:year_built p:integer l:YEAR_BUILT d:YEAR_BUILT t:dataTypeName=number

entity e:4dfe-ikq6 l:"Truck Parking Utilization - Parking Only" t:attribution="Iowa DOT, HDR Engineering" t:url=https://data.iowa.gov/api/views/4dfe-ikq6

property e:4dfe-ikq6 t:meta.view v:id=4dfe-ikq6 v:category="Transportation & Utilities" v:averageRating=0 v:name="Truck Parking Utilization - Parking Only" v:attribution="Iowa DOT, HDR Engineering"

property e:4dfe-ikq6 t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:4dfe-ikq6 t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | objectid | full_name        | interstate | exit | direction | approx_number_truck_space | truck_percent | truck_perc_group | ukey | inventory_ | address1                        | near_city   | phone_numb | cost_cente | square_foo | orig_fid | year_built | 
| =========== | ======== | ================ | ========== | ==== | ========= | ========================= | ============= | ================ | ==== | ========== | =============================== | =========== | ========== | ========== | ========== | ======== | ========== | 
| 0           | 1        | I-35 NB - MP 53  | 35         | 53   | NB        | 6                         | 100           | 0-74%            | 50   | 48         | St. Charles - Northbound I-35   | St. Charles | 0          | 555691     | 0          | 0        | 0          | 
| 0           | 2        | I-35 SB - MP 51  | 35         | 51   | SB        | 6                         | 100           | 0-74%            | 49   | 49         | St. Charles - Southbound I-35   | St. Charles | 0          | 555620     | 0          | 0        | 0          | 
| 0           | 4        | I-29 NB - MP 92  | 29         | 92   | NB        | 5                         | 10            | 0-74%            | 43   | 57         | Mondamin - Northbound I-29      | Mondamin    | 0          | 0          | 0          | 0        | 0          | 
| 0           | 5        | I-29 SB - MP 92  | 29         | 92   | SB        | 5                         | 10            | 0-74%            | 42   | 56         | Mondamin - Southbound I-29      | Mondamin    | 0          | 0          | 0          | 0        | 0          | 
| 0           | 6        | I-29 NB - MP 132 | 29         | 132  | NB        | 8                         | 50            | 0-74%            | 63   | 61         | Salix - Northbound I-29         | Salix       | 0          | 553607     | 0          | 0        | 0          | 
| 0           | 9        | I-35 SB - MP 30  | 35         | 30   | SB        | 3                         | 65            | 0-74%            | 68   | 50         | OsceolaAlt - Southbound I-35    | Osceola     | 0          | 555620     | 0          | 0        | 0          | 
| 0           | 10       | I-35 NB - MP 105 | 35         | 105  | NB        | 8                         | 90            | 0-74%            | 33   | 857H62     | 106 I-35 North Bound, Huxley IA | Huxley      | 0          | 421000     | 0          | 66       | 0          | 
| 0           | 12       | I-35 NB - MP 196 | 35         | 196  | NB        | 25                        | 100           | 0-74%            | 47   | 46         | Clear Lake - Northbound I-35    | Clear Lake  | 0          | 552698     | 0          | 0        | 0          | 
| 0           | 13       | I-35 SB - MP 196 | 35         | 196  | SB        | 25                        | 100           | 0-74%            | 48   | 45         | Clear Lake - Southbound I-35    | Clear Lake  | 0          | 552698     | 0          | 0        | 0          | 
| 0           | 14       | I-35 NB - MP 211 | 35         | 211  | NB        | 5                         | 140           | 0-74%            | 72   | 44         | Joice - Northbound I-35         | Joice       | 0          | 552698     | 0          | 0        | 0          | 
```