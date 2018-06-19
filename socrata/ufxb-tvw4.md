# Rest Areas - Weigh Station

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rest-areas-weigh-station) |
| Metadata | [Link](https://data.iowa.gov/api/views/ufxb-tvw4) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/ufxb-tvw4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/ufxb-tvw4/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | ufxb-tvw4 |
| Name | Rest Areas - Weigh Station |
| Attribution | Iowa DOT, HDR Engineering |
| Category | Transportation & Utilities |
| Tags | asset, classification, rest, area, iowa dot, iowa department of transportation |
| Created | 2016-08-19T20:06:33Z |
| Publication Date | 2016-08-19T20:08:05Z |

## Description

Iowa Department of Transportation statewide rest area data. This layer displays rest areas with weigh stations.

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
| Yes      | series tag     | cost_cente                | COST_CENTE                | text      | text        |
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
series e:ufxb-tvw4 d:2016-08-19T20:06:33.000Z t:truck_perc_group=0-74% t:cost_cente=000000 t:inventory_=367P72 t:phone_numb=7123550608 t:direction=NB t:objectid=3 t:orig_fid=70 t:full_name="I-29 NB - MP 11" t:near_city=Hamburg m:approx_number_truck_space=7 m:interstate=29 m:truck_percent=30 m:ukey=37 m:year_built=1999 m:square_foo=1281 m:exit=11

series e:ufxb-tvw4 d:2016-08-19T20:06:33.000Z t:truck_perc_group=0-74% t:cost_cente=553607 t:inventory_=60 t:phone_numb=0 t:direction=SB t:objectid=7 t:orig_fid=0 t:full_name="I-29 SB - MP 132" t:near_city=Salix m:approx_number_truck_space=8 m:interstate=29 m:truck_percent=0 m:ukey=62 m:year_built=0 m:square_foo=0 m:exit=132

series e:ufxb-tvw4 d:2016-08-19T20:06:33.000Z t:truck_perc_group=0-74% t:cost_cente=555620 t:inventory_=51 t:phone_numb=0 t:direction=NB t:objectid=8 t:orig_fid=0 t:full_name="I-35 NB - MP 30" t:near_city=Osceola m:approx_number_truck_space=3 m:interstate=35 m:truck_percent=35 m:ukey=67 m:year_built=0 m:square_foo=0 m:exit=30
```

## Meta Commands

```ls
metric m:interstate p:integer l:Interstate d:Interstate t:dataTypeName=number

metric m:exit p:integer l:Exit d:"Mile Post" t:dataTypeName=number

metric m:approx_number_truck_space p:integer l:Approx_Number_Truck_Space d:"Approximate Number of Truck Spaces" t:dataTypeName=number

metric m:truck_percent p:integer l:Truck_Percent d:"Truck Utilization Percent" t:dataTypeName=number

metric m:ukey p:integer l:UKEY d:UKEY t:dataTypeName=number

metric m:square_foo p:integer l:SQUARE_FOO d:SQUARE_FOO t:dataTypeName=number

metric m:year_built p:integer l:YEAR_BUILT d:YEAR_BUILT t:dataTypeName=number

entity e:ufxb-tvw4 l:"Rest Areas - Weigh Station" t:attribution="Iowa DOT, HDR Engineering" t:url=https://data.iowa.gov/api/views/ufxb-tvw4

property e:ufxb-tvw4 t:meta.view v:id=ufxb-tvw4 v:category="Transportation & Utilities" v:averageRating=0 v:name="Rest Areas - Weigh Station" v:attribution="Iowa DOT, HDR Engineering"

property e:ufxb-tvw4 t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:ufxb-tvw4 t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | objectid | full_name        | interstate | exit | direction | approx_number_truck_space | truck_percent | truck_perc_group | ukey | inventory_ | address1                                | near_city | phone_numb | cost_cente | square_foo | orig_fid | year_built | 
| =========== | ======== | ================ | ========== | ==== | ========= | ========================= | ============= | ================ | ==== | ========== | ======================================= | ========= | ========== | ========== | ========== | ======== | ========== | 
| 0           | 3        | I-29 NB - MP 11  | 29         | 11   | NB        | 7                         | 30            | 0-74%            | 37   | 367P72     | I-29 N Of Hwy 2 Interchange, Hamburg IA | Hamburg   | 7123550608 | 000000     | 1281       | 70       | 1999       | 
| 0           | 7        | I-29 SB - MP 132 | 29         | 132  | SB        | 8                         | 0             | 0-74%            | 62   | 60         | Salix Southbound I-29                   | Salix     | 0          | 553607     | 0          | 0        | 0          | 
| 0           | 8        | I-35 NB - MP 30  | 35         | 30   | NB        | 3                         | 35            | 0-74%            | 67   | 51         | OsceolaAlt - Northbound I-35            | Osceola   | 0          | 555620     | 0          | 0        | 0          | 
| 0           | 11       | I-35 SB - MP 105 | 35         | 105  | SB        | 8                         | 40            | 0-74%            | 32   | 857H61     | 106 I-35 South Bound, Huxley IA         | Huxley    | 5152505973 | 421000     | 684        | 65       | 1965       | 
| 0           | 15       | I-35 SB - MP 211 | 35         | 211  | SB        | 5                         | 0             | 0-74%            | 71   | 43         | Joice - Southbound I-35                 | Joice     | 0          | 552698     | 0          | 0        | 0          | 
| 0           | 18       | I-80 WB - MP 44  | 80         | 44   | WB        | 8                         | 75            | 0-74%            | 59   | 52         | Avoca - Westbound I-80                  | Avoca     | 0          | 554802     | 0          | 0        | 0          | 
| 0           | 20       | I-80 EB - MP 115 | 80         | 115  | EB        | 13                        | 0             | 0-74%            | 36   | 257D70     | I-80 East Of Van Meter, Van Meter IA    | Van Meter | 5152505973 | 421000     | 4081       | 69       | 1994       | 
| 0           | 21       | I-80 WB - MP 151 | 80         | 151  | WB        | 11                        | 20            | 0-74%            | 41   | 507J50     | 151 I-80 Westbound, Colfax IA           | Colfax    | 5152901282 | 421000     | 4081       | 74       | 1994       | 
| 0           | 24       | I-380 NB - MP 51 | 380        | 51   | NB        | 5                         | 0             | 0-74%            |      |            |                                         |           |            |            |            |          |            | 
| 0           | 25       | I-380 SB - MP 53 | 380        | 53   | SB        | 5                         | 40            | 0-74%            |      |            |                                         |           |            |            |            |          |            | 
```