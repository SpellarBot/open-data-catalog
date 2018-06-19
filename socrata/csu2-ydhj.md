# Department of Revenue - Home Rule Taxes Collected - December 2010 to June 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-revenue-home-rule-taxes-collected-december-2010-to-june-2011-e3c44) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/csu2-ydhj) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/csu2-ydhj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/csu2-ydhj/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | csu2-ydhj |
| Name | Department of Revenue - Home Rule Taxes Collected - December 2010 to June 2011 |
| Attribution | Cook County Department of Revenue |
| Category | Finance & Administration |
| Created | 2011-08-18T18:25:41Z |
| Publication Date | 2014-10-09T21:22:09Z |

## Description

Total Home Rule Taxes collected per month. Data covers December 2010 through June 2011.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                                | Data Type | Render Type |
| ======== | ============== | ================================= | =================================== | ========= | =========== |
| Yes      | series tag     | month                             | Month                               | text      | text        |
| Yes      | numeric metric | sales_tax                         | Sales Tax                           | money     | money       |
| Yes      | numeric metric | use_tax                           | Use Tax                             | money     | money       |
| Yes      | numeric metric | alcoholic_beverage_tax            | Alcoholic Beverage Tax              | money     | money       |
| Yes      | numeric metric | cigarette_tax                     | Cigarette Tax                       | money     | money       |
| Yes      | numeric metric | gasoline_diesel_fuel_tax          | Gasoline / Diesel Fuel Tax          | money     | money       |
| Yes      | numeric metric | newmotor_vehicles_tax             | NewMotor Vehicles Tax               | money     | money       |
| Yes      | numeric metric | wheel_tax                         | Wheel Tax                           | money     | money       |
| Yes      | numeric metric | amusement_tax                     | Amusement Tax                       | money     | money       |
| Yes      | numeric metric | parking_lot_garage_operations_tax | Parking Lot & Garage Operations Tax | money     | money       |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:csu2-ydhj d:2010-01-01T00:00:00.000Z t:month=December-10 m:alcoholic_beverage_tax=2234000 m:wheel_tax=30000 m:parking_lot_garage_operations_tax=2736000 m:sales_tax=42385989 m:newmotor_vehicles_tax=171000 m:use_tax=3082771 m:amusement_tax=1637000 m:cigarette_tax=9643000 m:gasoline_diesel_fuel_tax=8550000

series e:csu2-ydhj d:2010-01-01T00:00:00.000Z t:month=January-11 m:alcoholic_beverage_tax=3007447 m:wheel_tax=12000 m:parking_lot_garage_operations_tax=2836757 m:sales_tax=41423712 m:newmotor_vehicles_tax=203072 m:use_tax=3353677 m:amusement_tax=935624 m:cigarette_tax=9632000 m:gasoline_diesel_fuel_tax=8350096

series e:csu2-ydhj d:2010-01-01T00:00:00.000Z t:month=February-11 m:alcoholic_beverage_tax=1274395 m:wheel_tax=20000 m:parking_lot_garage_operations_tax=3019693 m:sales_tax=41937872 m:newmotor_vehicles_tax=94813 m:use_tax=2395467 m:amusement_tax=1672428 m:cigarette_tax=9531000 m:gasoline_diesel_fuel_tax=6607976
```

## Meta Commands

```ls
metric m:sales_tax p:integer l:"Sales Tax" t:dataTypeName=money

metric m:use_tax p:integer l:"Use Tax" t:dataTypeName=money

metric m:alcoholic_beverage_tax p:integer l:"Alcoholic Beverage Tax" t:dataTypeName=money

metric m:cigarette_tax p:integer l:"Cigarette Tax" t:dataTypeName=money

metric m:gasoline_diesel_fuel_tax p:integer l:"Gasoline / Diesel Fuel Tax" t:dataTypeName=money

metric m:newmotor_vehicles_tax p:integer l:"NewMotor Vehicles Tax" t:dataTypeName=money

metric m:wheel_tax p:integer l:"Wheel Tax" t:dataTypeName=money

metric m:amusement_tax p:integer l:"Amusement Tax" t:dataTypeName=money

metric m:parking_lot_garage_operations_tax p:integer l:"Parking Lot & Garage Operations Tax" t:dataTypeName=money

entity e:csu2-ydhj l:"Department of Revenue - Home Rule Taxes Collected - December 2010 to June 2011" t:attribution="Cook County Department of Revenue" t:url=https://datacatalog.cookcountyil.gov/api/views/csu2-ydhj

property e:csu2-ydhj t:meta.view v:id=csu2-ydhj v:category="Finance & Administration" v:attributionLink=http://cookcountyil.gov/revenue v:averageRating=0 v:name="Department of Revenue - Home Rule Taxes Collected - December 2010 to June 2011" v:attribution="Cook County Department of Revenue"

property e:csu2-ydhj t:meta.view.license v:name="Public Domain"

property e:csu2-ydhj t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:csu2-ydhj t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| month       | sales_tax | use_tax | alcoholic_beverage_tax | cigarette_tax | gasoline_diesel_fuel_tax | newmotor_vehicles_tax | wheel_tax | amusement_tax | parking_lot_garage_operations_tax | 
| =========== | ========= | ======= | ====================== | ============= | ======================== | ===================== | ========= | ============= | ================================= | 
| December-10 | 42385989  | 3082771 | 2234000                | 9643000       | 8550000                  | 171000                | 30000     | 1637000       | 2736000                           | 
| January-11  | 41423712  | 3353677 | 3007447                | 9632000       | 8350096                  | 203072                | 12000     | 935624        | 2836757                           | 
| February-11 | 41937872  | 2395467 | 1274395                | 9531000       | 6607976                  | 94813                 | 20000     | 1672428       | 3019693                           | 
| March-11    | 51842961  | 2981400 | 1643687                | 9188000       | 7744000                  | 221792                | 13000     | 3970336       | 2914647                           | 
| April-11    | 34149849  | 3743189 | 2175759                | 9116000       | 7390000                  | 219000                | 25000     | 1144000       | 2331860                           | 
| May-11      | 34156010  | 3347608 | 1900330                | 11534325      | 7011883                  | 201465                | 20933     | 2448308       | 2975278                           | 
| June-11     | 41727825  | 3444458 | 2194774                | 11518505      | 7168390                  | 218537                | 846305    | 2004558       | 3591423                           | 
```