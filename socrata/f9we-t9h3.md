# NYS Thruway Origin and Destination for E-ZPass Vehicles Only: 2008 - 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-thruway-origin-and-destination-for-e-zpass-vehicles-only-beginning-2008) |
| Metadata | [Link](https://data.ny.gov/api/views/f9we-t9h3) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/f9we-t9h3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/f9we-t9h3/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | f9we-t9h3 |
| Name | NYS Thruway Origin and Destination for E-ZPass Vehicles Only: 2008 - 2014 |
| Attribution | New York State Thruway Authority |
| Category | Transportation |
| Tags | thruway, e-zpass, origin, destination, commercial, traffic, interstate, toll, toll road, toll collection |
| Created | 2013-05-21T18:13:53Z |
| Publication Date | 2015-03-19T19:21:34Z |

## Description

This dataset contains the number of vehicles entering and exiting the New York State Thruway who have used E-ZPass.  The Origin and Destination numbers are organized by entrance and exit point and by vehicle class.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | year        | Year        | number    | number      |
| Yes      | series tag     | entrance    | Entrance    | text      | text        |
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
series e:f9we-t9h3 d:2008-01-01T00:00:00.000Z t:entrance=16 t:exit=47 m:class_4l=0 m:total=9 m:class_5s=0 m:class_4h=0 m:class_3h=0 m:class_2h=0 m:class_7s=0 m:class_5h=1 m:permit=0 m:class_6s=0 m:class_2l=5 m:class_6h=0 m:class_7h=0 m:class_3l=0 m:non_revenue=3

series e:f9we-t9h3 d:2009-01-01T00:00:00.000Z t:entrance=16 t:exit=47 m:class_4l=0 m:total=12 m:class_5s=0 m:class_4h=0 m:class_3h=1 m:class_2h=0 m:class_7s=0 m:class_5h=0 m:permit=0 m:class_6s=0 m:class_2l=9 m:class_6h=1 m:class_7h=0 m:class_3l=0 m:non_revenue=1

series e:f9we-t9h3 d:2011-01-01T00:00:00.000Z t:entrance=40 t:exit=16 m:class_4l=0 m:total=23 m:class_5s=0 m:class_4h=1 m:class_3h=0 m:class_2h=0 m:class_7s=0 m:class_5h=6 m:permit=0 m:class_6s=0 m:class_2l=11 m:class_6h=5 m:class_7h=0 m:class_3l=0 m:non_revenue=0
```

## Meta Commands

```ls
metric m:permit p:integer l:Permit d:"Number of vehicles that traveled this link and have a Thruway Permit plan on their E-ZPass account. The Permit Plan is available to frequent travelers, typically commuters, for $88 per year. With the Permit Plan the first 30 miles traveled are free, excep" t:dataTypeName=number

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

entity e:f9we-t9h3 l:"NYS Thruway Origin and Destination for E-ZPass Vehicles Only:  2008 - 2014" t:attribution="New York State Thruway Authority" t:url=https://data.ny.gov/api/views/f9we-t9h3

property e:f9we-t9h3 t:meta.view v:id=f9we-t9h3 v:category=Transportation v:averageRating=0 v:name="NYS Thruway Origin and Destination for E-ZPass Vehicles Only:  2008 - 2014" v:attribution="New York State Thruway Authority"

property e:f9we-t9h3 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:f9we-t9h3 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:f9we-t9h3 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | entrance | exit | permit | class_2l | class_3l | class_4l | class_2h | class_3h | class_4h | class_5h | class_5s | class_6h | class_6s | class_7h | class_7s | non_revenue | total | 
| ==== | ======== | ==== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | =========== | ===== | 
| 2008 | 16       | 47   | 0      | 5        | 0        | 0        | 0        | 0        | 0        | 1        | 0        | 0        | 0        | 0        | 0        | 3           | 9     | 
| 2009 | 16       | 47   | 0      | 9        | 0        | 0        | 0        | 1        | 0        | 0        | 0        | 1        | 0        | 0        | 0        | 1           | 12    | 
| 2011 | 40       | 16   | 0      | 11       | 0        | 0        | 0        | 0        | 1        | 6        | 0        | 5        | 0        | 0        | 0        | 0           | 23    | 
| 2009 | 16       | 48   | 0      | 28       | 0        | 0        | 1        | 0        | 0        | 0        | 7        | 2        | 0        | 0        | 0        | 0           | 38    | 
| 2010 | 17       | 44   | 5      | 347      | 0        | 3        | 1        | 0        | 0        | 2        | 0        | 6        | 2        | 0        | 0        | 0           | 366   | 
| 2010 | 46       | 16   | 0      | 100      | 0        | 0        | 1        | 1        | 0        | 1        | 0        | 1        | 0        | 1        | 0        | 0           | 105   | 
| 2011 | 47       | 16   | 0      | 4        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 1           | 5     | 
| 2011 | 48       | 16   | 0      | 15       | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0           | 15    | 
| 2008 | 15       | 15   | 20     | 3798     | 1        | 2        | 368      | 341      | 141      | 392      | 511      | 33       | 19       | 10       | 0        | 1611        | 7247  | 
| 2008 | 15       | 16   | 40     | 4734     | 0        | 0        | 93       | 47       | 17       | 23       | 21       | 4        | 0        | 0        | 0        | 1625        | 6604  | 
```