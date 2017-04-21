# NYS Thruway Origin and Destination Points for All Vehicles: 2008 - 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-thruway-origin-and-destination-points-for-all-vehicles-beginning-2008) |
| Metadata | [Link](https://data.ny.gov/api/views/tw9e-7nms) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/tw9e-7nms/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/tw9e-7nms/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | tw9e-7nms |
| Name | NYS Thruway Origin and Destination Points for All Vehicles: 2008 - 2014 |
| Attribution | New York State Thruway Authority |
| Category | Transportation |
| Tags | thruway, e-zpass, origin, destination, commercial, traffic, interstate, toll, toll road, toll collection |
| Created | 2013-05-21T17:40:55Z |
| Publication Date | 2015-03-19T19:25:26Z |

## Description

This dataset contains the number of vehicles, cash and E-ZPass, entering and exiting the New York State Thruway.  The Origin and Destination numbers are organized by entrance and exit point.and by vehicle class.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | year        | Year        | number    | number      |
| Yes      | series tag     | ent         | Entrance    | text      | text        |
| Yes      | series tag     | exit        | Exit        | text      | text        |
| Yes      | numeric metric | permit      | Permit      | number    | number      |
| Yes      | numeric metric | class_2l    | Class 2L    | number    | number      |
| Yes      | numeric metric | class_3l    | Class 3L    | number    | number      |
| Yes      | numeric metric | class_4l    | Class 4L    | number    | number      |
| Yes      | numeric metric | class_2h    | Class 2H    | number    | number      |
| Yes      | numeric metric | class_3h    | Class 3H    | number    | number      |
| Yes      | numeric metric | class_4h    | Class 4H    | number    | number      |
| Yes      | numeric metric | class_5h    | Class 5H    | number    | number      |
| Yes      | numeric metric | class_5s    | Class 5S    | number    | number      |
| Yes      | numeric metric | class_6h    | Class 6H    | number    | number      |
| Yes      | numeric metric | class_6s    | Class 6S    | number    | number      |
| Yes      | numeric metric | class_7h    | Class 7H    | number    | number      |
| Yes      | numeric metric | class_7s    | Class 7S    | number    | number      |
| Yes      | numeric metric | non_revenue | Non-Revenue | number    | number      |
| Yes      | numeric metric | total       | Total       | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tw9e-7nms d:2008-01-01T00:00:00.000Z t:ent=15 t:exit=22 m:class_4l=50 m:total=30811 m:class_5s=4121 m:class_4h=142 m:class_3h=584 m:class_2h=373 m:class_7s=49 m:class_5h=1775 m:permit=437 m:class_6s=44 m:class_2l=22471 m:class_6h=15 m:class_7h=517 m:class_3l=50 m:non_revenue=183

series e:tw9e-7nms d:2008-01-01T00:00:00.000Z t:ent=15 t:exit=23 m:class_4l=1314 m:total=748298 m:class_5s=21600 m:class_4h=5423 m:class_3h=13219 m:class_2h=12686 m:class_7s=821 m:class_5h=24248 m:permit=2963 m:class_6s=500 m:class_2l=658939 m:class_6h=361 m:class_7h=2172 m:class_3l=1409 m:non_revenue=2643

series e:tw9e-7nms d:2008-01-01T00:00:00.000Z t:ent=15 t:exit=24 m:class_4l=5029 m:total=1376462 m:class_5s=63937 m:class_4h=10778 m:class_3h=16507 m:class_2h=18950 m:class_7s=1064 m:class_5h=123865 m:permit=2054 m:class_6s=3482 m:class_2l=1111255 m:class_6h=8540 m:class_7h=3174 m:class_3l=6020 m:non_revenue=1807
```

## Meta Commands

```ls
metric m:permit p:integer l:Permit d:"Number of vehicles that traveled this link and have a Thruway Permit plan on their E-ZPass account. The Permit Plan is available to frequent travelers, typically commuters, for $88 per year. With the Permit Plan the first 30 miles traveled are free, exc" t:dataTypeName=number

metric m:class_2l p:integer l:"Class 2L" d:"Number of vehicles that completed this trip that have 2 axles and whose height over the second axle is lower than 7? 6?" t:dataTypeName=number

metric m:class_3l p:integer l:"Class 3L" d:"Number of vehicles that completed this trip that have 3 axles and whose height over the second axle is lower than 7? 6?" t:dataTypeName=number

metric m:class_4l p:integer l:"Class 4L" d:"Number of vehicles that completed this trip that have 4 axles and whose height over the second axle is lower than 7? 6?" t:dataTypeName=number

metric m:class_2h p:integer l:"Class 2H" d:"Number of vehicles that completed this trip that have 2 axles and whose height over the second axle is 7? 6? or greater" t:dataTypeName=number

metric m:class_3h p:integer l:"Class 3H" d:"Number of vehicles that completed this trip that have 3 axles and whose height over the second axle is 7? 6? or greater" t:dataTypeName=number

metric m:class_4h p:integer l:"Class 4H" d:"Number of vehicles that completed this trip that have 4 axles and whose height over the second axle is 7? 6? or greater" t:dataTypeName=number

metric m:class_5h p:integer l:"Class 5H" d:"Number of vehicles that completed this trip that have 5 axles and whose height over the second axle is 7? 6? or greater" t:dataTypeName=number

metric m:class_5s p:integer l:"Class 5S" d:"Number of vehicles that completed this trip that have 5 axles and whose height over the second axle is 7? 6? or greater and are eligible for a Special Commercial E-ZPass Discount. This E-ZPass discount is given to qualified tags issued by the E-ZPass New" t:dataTypeName=number

metric m:class_6h p:integer l:"Class 6H" d:"Number of vehicles that completed this trip that have 6 axles and whose height over the second axle is 7? 6? or greater" t:dataTypeName=number

metric m:class_6s p:integer l:"Class 6S" d:"Number of vehicles that completed this trip that have 6 axles and whose height over the second axle is 7? 6? or greater and are eligible for a Special Commercial E-ZPass Discount. This E-ZPass discount is given to qualified tags issued by the E-ZPass New" t:dataTypeName=number

metric m:class_7h p:integer l:"Class 7H" d:"Number of vehicles that completed this trip that have 7 axles and whose height over the second axle is 7? 6? or greater" t:dataTypeName=number

metric m:class_7s p:integer l:"Class 7S" d:"Number of vehicles that completed this trip that have 7 axles and whose height over the second axle is 7? 6? or greater and are eligible for a Special Commercial E-ZPass Discount. This E-ZPass discount is given to qualified tags issued by the E-ZPass New" t:dataTypeName=number

metric m:non_revenue p:integer l:Non-Revenue d:"Number of vehicles that completed this trip who have been granted free passage on the Thruway. This group includes Thruway fleet vehicles (i.e., plow trucks) and NY State Police." t:dataTypeName=number

metric m:total p:integer l:Total d:"Total of all vehicles that completed this trip" t:dataTypeName=number

entity e:tw9e-7nms l:"NYS Thruway Origin and Destination Points for All Vehicles:  2008 - 2014" t:attribution="New York State Thruway Authority" t:url=https://data.ny.gov/api/views/tw9e-7nms

property e:tw9e-7nms t:meta.view v:id=tw9e-7nms v:category=Transportation v:averageRating=0 v:name="NYS Thruway Origin and Destination Points for All Vehicles:  2008 - 2014" v:attribution="New York State Thruway Authority"

property e:tw9e-7nms t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:tw9e-7nms t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:tw9e-7nms t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | ent | exit | permit | class_2l | class_3l | class_4l | class_2h | class_3h | class_4h | class_5h | class_5s | class_6h | class_6s | class_7h | class_7s | non_revenue | total   | 
| ==== | === | ==== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | =========== | ======= | 
| 2008 | 15  | 22   | 437    | 22471    | 50       | 50       | 373      | 584      | 142      | 1775     | 4121     | 15       | 44       | 517      | 49       | 183         | 30811   | 
| 2008 | 15  | 23   | 2963   | 658939   | 1409     | 1314     | 12686    | 13219    | 5423     | 24248    | 21600    | 361      | 500      | 2172     | 821      | 2643        | 748298  | 
| 2008 | 15  | 24   | 2054   | 1111255  | 6020     | 5029     | 18950    | 16507    | 10778    | 123865   | 63937    | 8540     | 3482     | 3174     | 1064     | 1807        | 1376462 | 
| 2008 | 15  | 25   | 1968   | 146600   | 233      | 231      | 2108     | 1052     | 426      | 4684     | 3069     | 61       | 40       | 19       | 73       | 456         | 161020  | 
| 2008 | 15  | 25A  | 93     | 35122    | 119      | 126      | 1144     | 1748     | 558      | 8308     | 8625     | 39       | 47       | 1609     | 336      | 106         | 57980   | 
| 2008 | 15  | 26   | 164    | 7315     | 36       | 35       | 139      | 102      | 75       | 1702     | 1009     | 19       | 3        | 20       | 3        | 39          | 10661   | 
| 2008 | 15  | 27   | 777    | 44385    | 270      | 139      | 712      | 743      | 151      | 11649    | 6117     | 37       | 89       | 127      | 87       | 119         | 65402   | 
| 2008 | 15  | 28   | 101    | 12904    | 66       | 76       | 1187     | 1849     | 287      | 20305    | 6272     | 56       | 29       | 376      | 85       | 24          | 43617   | 
| 2008 | 15  | 29   | 112    | 6661     | 74       | 91       | 131      | 23       | 90       | 608      | 328      | 8        | 9        | 14       | 4        | 14          | 8167    | 
| 2008 | 15  | 29A  | 80     | 6856     | 25       | 38       | 123      | 161      | 9        | 413      | 3766     | 5        | 5        | 0        | 1        | 8           | 11490   | 
```