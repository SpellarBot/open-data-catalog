# RAMS - Reference Posts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rams-reference-posts) |
| Metadata | [Link](https://data.iowa.gov/api/views/vitm-v5aq) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/vitm-v5aq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/vitm-v5aq/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | vitm-v5aq |
| Name | RAMS - Reference Posts |
| Attribution | Iowa Department of Transportation - Office of Research & Analytics |
| Category | Transportation & Utilities |
| Tags | iowa dot, iowa department of transportation, rams, reference posts, asset, inventory |
| Created | 2016-12-06T19:15:39Z |
| Publication Date | 2016-12-06T19:17:33Z |

## Description

Reference Posts data maintained inside the Roadway Asset Management System (RAMS).

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | event_id             | EVENT_ID             | text      | text        |
| Yes      | series tag     | route_id             | ROUTE_ID             | text      | text        |
| Yes      | numeric metric | measure              | MEASURE              | number    | number      |
| Yes      | time           | business_date        | BUSINESS_DATE        | date      | date        |
| No       |                | effective_start_date | EFFECTIVE_START_DATE | date      | date        |
| No       |                | effective_end_date   | EFFECTIVE_END_DATE   | date      | date        |
| Yes      | series tag     | user_create          | USER_CREATE          | text      | text        |
| Yes      | series tag     | user_mod             | USER_MOD             | text      | text        |
| No       |                | system_create_date   | SYSTEM_CREATE_DATE   | date      | date        |
| No       |                | system_mod_date      | SYSTEM_MOD_DATE      | date      | date        |
| Yes      | numeric metric | reference_post_value | REFERENCE_POST_VALUE | number    | text        |
| Yes      | series tag     | reference_post_name  | REFERENCE_POST_NAME  | text      | text        |
| Yes      | numeric metric | opposite_side        | OPPOSITE_SIDE        | number    | text        |
| Yes      | numeric metric | virtual              | VIRTUAL              | number    | text        |
| No       |                | measured_lat         | MEASURED_LAT         | number    | number      |
| Yes      | numeric metric | measured_lon         | MEASURED_LON         | number    | number      |
| Yes      | series tag     | locerror             | LOCERROR             | text      | text        |
| Yes      | series tag     | objectid             | OBJECTID             | text      | number      |
```

## Time Field

```ls
Value = business_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = effective_start_date,effective_end_date,system_create_date,system_mod_date,measured_lat
```

## Data Commands

```ls
series e:vitm-v5aq d:2016-01-01T06:00:00.000Z t:reference_post_name=169N-135 t:route_id=S001920169N t:event_id=0000003530 t:user_create=RWYLLIE t:locerror="NO ERROR" t:user_mod=RAMS t:objectid=1 m:virtual=0 m:measure=135.89220071 m:opposite_side=0 m:measured_lon=-94.10606 m:reference_post_value=135

series e:vitm-v5aq d:2016-01-01T06:00:00.000Z t:reference_post_name=169N-129 t:route_id=S001920169N t:event_id=0000003531 t:user_create=RWYLLIE t:locerror="NO ERROR" t:user_mod=RAMS t:objectid=2 m:virtual=0 m:measure=129.87511499 m:opposite_side=0 m:measured_lon=-94.10579 m:reference_post_value=129

series e:vitm-v5aq d:2016-01-01T06:00:00.000Z t:reference_post_name=169N-58 t:route_id=S001920169N t:event_id=0000009646 t:user_create=RWYLLIE t:locerror="NO ERROR" t:user_mod=RAMS t:objectid=3 m:virtual=0 m:measure=58.116529 m:opposite_side=0 m:measured_lon=-94.04713 m:reference_post_value=58
```

## Meta Commands

```ls
metric m:measure p:decimal l:MEASURE d:MEASURE t:dataTypeName=number

metric m:reference_post_value p:integer l:REFERENCE_POST_VALUE d:"Reference Post Value" t:dataTypeName=number

metric m:opposite_side p:integer l:OPPOSITE_SIDE d:"Opposite Side" t:dataTypeName=number

metric m:virtual p:integer l:VIRTUAL d:Virtual t:dataTypeName=number

metric m:measured_lon p:decimal l:MEASURED_LON d:Longitude t:dataTypeName=number

entity e:vitm-v5aq l:"RAMS - Reference Posts" t:attribution="Iowa Department of Transportation - Office of Research & Analytics" t:url=https://data.iowa.gov/api/views/vitm-v5aq

property e:vitm-v5aq t:meta.view v:id=vitm-v5aq v:category="Transportation & Utilities" v:averageRating=0 v:name="RAMS - Reference Posts" v:attribution="Iowa Department of Transportation - Office of Research & Analytics"

property e:vitm-v5aq t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:vitm-v5aq t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| event_id   | route_id    | measure                                             | business_date | effective_start_date | effective_end_date | user_create | user_mod | system_create_date | system_mod_date | reference_post_value | reference_post_name | opposite_side | virtual | measured_lat                                       | measured_lon                                       | locerror | objectid | 
| ========== | =========== | =================================================== | ============= | ==================== | ================== | =========== | ======== | ================== | =============== | ==================== | =================== | ============= | ======= | ================================================== | ================================================== | ======== | ======== | 
| 0000003530 | S001920169N | 135.8922007099999973434023559093475341796875        | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769115         | 1464789723      | 135                  | 169N-135            | 0             | 0       | 42.23344999999999771489456179551780223846435546875 | -94.1060599999999993769961292855441570281982421875 | NO ERROR | 1        | 
| 0000003531 | S001920169N | 129.87511498999998593717464245855808258056640625    | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769115         | 1464789723      | 129                  | 169N-129            | 0             | 0       | 42.14623999999999881538315094076097011566162109375 | -94.1057899999999989404386724345386028289794921875 | NO ERROR | 2        | 
| 0000009646 | S001920169N | 58.1165289999999998826751834712922573089599609375   | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769131         | 1464789723      | 58                   | 169N-58             | 0             | 0       | 41.1916499999999956571627990342676639556884765625  | -94.0471299999999956753526930697262287139892578125 | NO ERROR | 3        | 
| 0000009566 | S001920169N | 52.031102709999998978673829697072505950927734375    | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769131         | 1464789723      | 52                   | 169N-52             | 0             | 0       | 41.10598999999999847432263777591288089752197265625 | -94.0628200000000020963852875865995883941650390625 | NO ERROR | 4        | 
| 0000012686 | S001920169N | 75.6356714500000038015059544704854488372802734375   | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769139         | 1464789723      | 75                   | 169N-75             | 0             | 0       | 41.42430999999999841065800865180790424346923828125 | -94.013239999999996143742464482784271240234375     | NO ERROR | 5        | 
| 0000013063 | S001920169N | 87.61965311000000156127498485147953033447265625     | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769140         | 1464789723      | 87                   | 169N-87             | 0             | 0       | 41.59543000000000034788172342814505100250244140625 | -94.012779999999992242010193876922130584716796875  | NO ERROR | 6        | 
| 0000013064 | S001920169N | 170.699649090000008300194167532026767730712890625   | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769140         | 1464789723      | 170                  | 169N-170            | 0             | 0       | 42.670119999999997162376530468463897705078125      | -94.2266399999999890724211581982672214508056640625 | NO ERROR | 7        | 
| 0000013065 | S001920169N | 172.700973449999992226366885006427764892578125      | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769140         | 1464789723      | 172                  | 169N-172            | 0             | 0       | 42.69912000000000062982508097775280475616455078125 | -94.2269299999999958572516334243118762969970703125 | NO ERROR | 8        | 
| 0000013016 | S001920169N | 194.66231397000001379637978971004486083984375       | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769140         | 1464789723      | 194                  | 169N-194            | 0             | 0       | 43.01735000000000042064129956997931003570556640625 | -94.2275399999999905276126810349524021148681640625 | NO ERROR | 9        | 
| 0000012987 | S001920169N | 4.9981563500000003585910235415212810039520263671875 | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459769140         | 1464789723      | 5                    | 169N-5              | 0             | 0       | 40.610219999999998208295437507331371307373046875   | -94.341039999999992460288922302424907684326171875  | NO ERROR | 10       | 
```