# 2012 Net Grand List by Town

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-net-grand-list-by-town) |
| Metadata | [Link](https://data.ct.gov/api/views/ebya-9ie6) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/ebya-9ie6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/ebya-9ie6/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | ebya-9ie6 |
| Name | 2012 Net Grand List by Town |
| Attribution | Office of Policy and Management |
| Category | Government |
| Tags | grand list, towns, opm |
| Created | 2014-12-18T15:19:37Z |
| Publication Date | 2015-03-05T15:45:33Z |

## Description

The Grand List is the aggregate valuation of taxable property within a given town. The Total Net Grand Lists by Town Data includes a breakdown for taxable categories and exemptions under the following column headings:
Town Name, Residential, Commercial, Industrial, Public Utility, Vacant, Land Use, 10 Mill Forest, Apartments, Total Real, Real Exemptions, Total Net Real, Motor Vehicles, MV Exemptions, Total Net MV, Personal Property, Personal Property Exemptions, Total Net Personal Property, Total Net Grand List

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| Yes      | numeric metric | town                         | Town                         | number    | number      |
| Yes      | series tag     | town_name                    | Town Name                    | text      | text        |
| Yes      | numeric metric | 100_residential              | 100 Residential              | number    | number      |
| Yes      | numeric metric | 200_commercial               | 200 Commercial               | number    | number      |
| Yes      | numeric metric | 300_industrial               | 300 Industrial               | number    | number      |
| Yes      | numeric metric | 400_public_utility           | 400 Public Utility           | number    | number      |
| Yes      | numeric metric | 500_vacant_land              | 500 Vacant Land              | number    | number      |
| Yes      | numeric metric | 600_land_use                 | 600 Land Use                 | number    | number      |
| Yes      | numeric metric | 700_ten_mill_land            | 700 Ten Mill Land            | number    | number      |
| Yes      | numeric metric | 800_apartment                | 800 Apartment                | number    | number      |
| Yes      | numeric metric | total_real_property          | Total Real Property          | number    | number      |
| Yes      | numeric metric | exemptions                   | Exemptions                   | number    | number      |
| Yes      | numeric metric | net_real_property            | Net Real Property            | number    | number      |
| Yes      | numeric metric | motor_vehicle                | Motor Vehicle                | number    | number      |
| Yes      | numeric metric | motor_vehicle_exemption      | Motor Vehicle Exemption      | number    | number      |
| Yes      | numeric metric | total_net_motorvehicle       | Total Net MotorVehicle       | number    | number      |
| Yes      | numeric metric | personal_property            | Personal Property            | number    | number      |
| Yes      | numeric metric | personal_property_exemptions | Personal Property Exemptions | number    | number      |
| Yes      | numeric metric | net_personal_property        | Net Personal Property        | number    | number      |
| Yes      | numeric metric | total_net_grand_list         | Total Net Grand List         | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ebya-9ie6 d:2012-01-01T00:00:00.000Z t:town_name=Andover m:200_commercial=4491500 m:exemptions=980000 m:800_apartment=1670500 m:100_residential=215588190 m:total_net_motorvehicle=24248120 m:400_public_utility=616800 m:net_personal_property=5736815 m:personal_property_exemptions=478480 m:net_real_property=229009510 m:500_vacant_land=5918100 m:motor_vehicle_exemption=401980 m:personal_property=6215295 m:total_real_property=229989510 m:600_land_use=636120 m:700_ten_mill_land=0 m:300_industrial=1068300 m:town=1 m:motor_vehicle=24650100

series e:ebya-9ie6 d:2012-01-01T00:00:00.000Z t:town_name=Ansonia m:200_commercial=80310300 m:exemptions=6512480 m:800_apartment=15706400 m:100_residential=650539000 m:total_net_motorvehicle=91242287 m:400_public_utility=33000 m:net_personal_property=45927594 m:personal_property_exemptions=3800640 m:net_real_property=755503730 m:500_vacant_land=0 m:motor_vehicle_exemption=1159460 m:personal_property=49728234 m:total_real_property=762016210 m:600_land_use=3180 m:700_ten_mill_land=99830 m:300_industrial=15324500 m:town=2 m:motor_vehicle=92401747

series e:ebya-9ie6 d:2012-01-01T00:00:00.000Z t:town_name=Ashford m:200_commercial=12664300 m:exemptions=642575 m:800_apartment=9291200 m:100_residential=224539000 m:total_net_motorvehicle=28612060 m:400_public_utility=0 m:net_personal_property=7204829 m:personal_property_exemptions=574664 m:net_real_property=259559255 m:500_vacant_land=10648300 m:motor_vehicle_exemption=1015410 m:personal_property=7779493 m:total_real_property=260201830 m:600_land_use=3049330 m:700_ten_mill_land=9700 m:300_industrial=0 m:town=3 m:motor_vehicle=29627470
```

## Meta Commands

```ls
metric m:town p:integer l:Town t:dataTypeName=number

metric m:100_residential p:long l:"100 Residential" t:dataTypeName=number

metric m:200_commercial p:long l:"200 Commercial" t:dataTypeName=number

metric m:300_industrial p:integer l:"300 Industrial" t:dataTypeName=number

metric m:400_public_utility p:integer l:"400 Public Utility" t:dataTypeName=number

metric m:500_vacant_land p:integer l:"500 Vacant Land" t:dataTypeName=number

metric m:600_land_use p:integer l:"600 Land Use" t:dataTypeName=number

metric m:700_ten_mill_land p:integer l:"700 Ten Mill Land" t:dataTypeName=number

metric m:800_apartment p:integer l:"800 Apartment" t:dataTypeName=number

metric m:total_real_property p:long l:"Total Real Property" t:dataTypeName=number

metric m:exemptions p:integer l:Exemptions t:dataTypeName=number

metric m:net_real_property p:long l:"Net Real Property" t:dataTypeName=number

metric m:motor_vehicle p:integer l:"Motor Vehicle" t:dataTypeName=number

metric m:motor_vehicle_exemption p:integer l:"Motor Vehicle Exemption" t:dataTypeName=number

metric m:total_net_motorvehicle p:integer l:"Total Net MotorVehicle" t:dataTypeName=number

metric m:personal_property p:integer l:"Personal Property" t:dataTypeName=number

metric m:personal_property_exemptions p:integer l:"Personal Property Exemptions" t:dataTypeName=number

metric m:net_personal_property p:integer l:"Net Personal Property" t:dataTypeName=number

metric m:total_net_grand_list p:long l:"Total Net Grand List" t:dataTypeName=number

entity e:ebya-9ie6 l:"2012 Net Grand List by Town" t:attribution="Office of Policy and Management" t:url=https://data.ct.gov/api/views/ebya-9ie6

property e:ebya-9ie6 t:meta.view v:id=ebya-9ie6 v:category=Government v:attributionLink="http://www.ct.gov/opm/cwp/view.asp?A=2987&Q=385044" v:averageRating=0 v:name="2012 Net Grand List by Town" v:attribution="Office of Policy and Management"

property e:ebya-9ie6 t:meta.view.license v:name="Public Domain"

property e:ebya-9ie6 t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:ebya-9ie6 t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| town | town_name    | 100_residential | 200_commercial | 300_industrial | 400_public_utility | 500_vacant_land | 600_land_use | 700_ten_mill_land | 800_apartment | total_real_property | exemptions | net_real_property | motor_vehicle | motor_vehicle_exemption | total_net_motorvehicle | personal_property | personal_property_exemptions | net_personal_property | total_net_grand_list | 
| ==== | ============ | =============== | ============== | ============== | ================== | =============== | ============ | ================= | ============= | =================== | ========== | ================= | ============= | ======================= | ====================== | ================= | ============================ | ===================== | ==================== | 
| 1    | Andover      | 215588190       | 4491500        | 1068300        | 616800             | 5918100         | 636120       | 0                 | 1670500       | 229989510           | 980000     | 229009510         | 24650100      | 401980                  | 24248120               | 6215295           | 478480                       | 5736815               |                      | 
| 2    | Ansonia      | 650539000       | 80310300       | 15324500       | 33000              | 0               | 3180         | 99830             | 15706400      | 762016210           | 6512480    | 755503730         | 92401747      | 1159460                 | 91242287               | 49728234          | 3800640                      | 45927594              |                      | 
| 3    | Ashford      | 224539000       | 12664300       | 0              | 0                  | 10648300        | 3049330      | 9700              | 9291200       | 260201830           | 642575     | 259559255         | 29627470      | 1015410                 | 28612060               | 7779493           | 574664                       | 7204829               |                      | 
| 4    | Avon         | 2120567910      | 252394710      | 28765510       | 340090             | 5135400         | 254600       | 0                 | 37355920      | 2444814140          | 4332630    | 2440481510        | 170386470     | 851680                  | 169534790              | 92975560          | 14165240                     | 78810320              |                      | 
| 5    | Barkhamsted  | 279421500       | 13167950       | 4331720        | 0                  | 3339860         | 33648270     | 0                 | 2132050       | 336041350           | 1033290    | 335008060         | 30928180      | 568610                  | 30359570               | 13042442          | 3527510                      | 9514932               |                      | 
| 6    | Beacon Falls | 357510880       | 14471860       | 30697430       | 313640             | 13372530        | 175300       | 0                 | 732140        | 417273780           | 3150416    | 414123364         | 40894420      | 417800                  | 40476620               | 20246218          | 2388240                      | 17857978              |                      | 
| 7    | Berlin       | 1373260650      | 258191950      | 122400200      | 3005200            | 26438860        | 10615240     | 0                 | 0             | 1793912100          | 10203432   | 1783708668        | 194507770     | 6489677                 | 188018093              | 244386230         | 60455240                     | 183930990             |                      | 
| 8    | Bethany      | 517687490       | 14328070       | 19740920       | 0                  | 6987720         | 221490       | 0                 | 0             | 558965690           | 3404205    | 555561485         | 45148221      | 266141                  | 44882080               | 23058090          | 3334892                      | 19723198              |                      | 
| 9    | Bethel       | 1255956110      | 198633570      | 84265710       | 0                  | 24304000        | 4955860      | 0                 | 20778950      | 1588894200          | 5133720    | 1583760480        | 138500925     | 347910                  | 138153015              | 154811610         | 24579520                     | 130232090             |                      | 
| 10   | Bethlehem    | 332792800       | 22362400       | 3146000        | 0                  | 10590640        | 1668530      | 0                 | 0             | 370560370           | 2870540    | 367689830         | 32866944      | 150340                  | 32716604               | 7880598           | 1275863                      | 6604735               |                      | 
```