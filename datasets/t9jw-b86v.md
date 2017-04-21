# RAMS - Type Area

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rams-type-area) |
| Metadata | [Link](https://data.iowa.gov/api/views/t9jw-b86v) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/t9jw-b86v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/t9jw-b86v/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | t9jw-b86v |
| Name | RAMS - Type Area |
| Attribution | Iowa Department of Transportation - Office of Research & Analytics |
| Category | Transportation & Utilities |
| Tags | iowa dot, iowa department of transportation, rams, type area, asset, classification |
| Created | 2016-12-06T20:55:21Z |
| Publication Date | 2016-12-06T20:56:35Z |

## Description

Type Area data maintained inside the Roadway Asset Management System (RAMS).

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type  | Render Type |
| ======== | ============== | ==================== | ==================== | ========== | =========== |
| Yes      | series tag     | event_id             | EVENT_ID             | text       | text        |
| Yes      | series tag     | route_id             | ROUTE_ID             | text       | text        |
| Yes      | numeric metric | from_measure         | FROM_MEASURE         | number     | number      |
| Yes      | numeric metric | to_measure           | TO_MEASURE           | number     | number      |
| No       |                | business_date        | BUSINESS_DATE        | date       | date        |
| Yes      | time           | effective_start_date | EFFECTIVE_START_DATE | date       | date        |
| No       |                | effective_end_date   | EFFECTIVE_END_DATE   | date       | date        |
| Yes      | series tag     | user_create          | USER_CREATE          | text       | text        |
| Yes      | series tag     | user_mod             | USER_MOD             | text       | text        |
| No       |                | system_create_date   | SYSTEM_CREATE_DATE   | date       | date        |
| No       |                | system_mod_date      | SYSTEM_MOD_DATE      | date       | date        |
| Yes      | numeric metric | type_area            | TYPE_AREA            | number     | number      |
| Yes      | series tag     | locerror             | LOCERROR             | text       | text        |
| Yes      | numeric metric | shape_len            | SHAPE.LEN            | number     | number      |
| Yes      | series tag     | objectid             | OBJECTID             | text       | number      |
| No       |                | shape                | SHAPE                | geospatial | geospatial  |
```

## Time Field

```ls
Value = effective_start_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = business_date,effective_end_date,system_create_date,system_mod_date,shape
```

## Data Commands

```ls
series e:t9jw-b86v d:2016-01-01T00:00:01.000Z t:shape.longitude=-93.65850967799997 t:shape.needs_recoding=false t:route_id=M015547415E t:event_id=0000001075 t:user_create=JDENKER t:locerror="NO ERROR" t:shape.latitude=42.062192665000055 t:objectid=1 m:to_measure=0.29817 m:from_measure=0 m:type_area=4

series e:t9jw-b86v d:2016-01-01T00:00:01.000Z t:shape.longitude=-93.65843944899996 t:shape.needs_recoding=false t:route_id=M015547425E t:event_id=0000005284 t:user_create=JDENKER t:locerror="NO ERROR" t:shape.latitude=42.062932999000054 t:objectid=2 m:to_measure=0.29267899999999997 m:from_measure=0.000164 m:type_area=4

series e:t9jw-b86v d:2016-01-01T00:00:01.000Z t:shape.longitude=-91.28387471299999 t:shape.needs_recoding=false t:route_id=M016541250N t:event_id=0000009467 t:user_create=JDENKER t:locerror="NO ERROR" t:shape.latitude=42.10829217400004 t:objectid=3 m:to_measure=0.065039 m:from_measure=0 m:type_area=1
```

## Meta Commands

```ls
metric m:from_measure p:decimal l:FROM_MEASURE d:"From Measure" t:dataTypeName=number

metric m:to_measure p:decimal l:TO_MEASURE d:"To Measure" t:dataTypeName=number

metric m:type_area p:integer l:TYPE_AREA d:"Area Type" t:dataTypeName=number

metric m:shape_len p:long l:SHAPE.LEN d:"Length (Meter)" t:dataTypeName=number

entity e:t9jw-b86v l:"RAMS - Type Area" t:attribution="Iowa Department of Transportation - Office of Research & Analytics" t:url=https://data.iowa.gov/api/views/t9jw-b86v

property e:t9jw-b86v t:meta.view v:id=t9jw-b86v v:category="Transportation & Utilities" v:averageRating=0 v:name="RAMS - Type Area" v:attribution="Iowa Department of Transportation - Office of Research & Analytics"

property e:t9jw-b86v t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:t9jw-b86v t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| event_id   | route_id    | from_measure                                                        | to_measure                                                 | business_date | effective_start_date | effective_end_date | user_create | user_mod | system_create_date | system_mod_date | type_area | locerror | shape_len | objectid | shape                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | 
| ========== | =========== | =================================================================== | ========================================================== | ============= | ==================== | ================== | =========== | ======== | ================== | =============== | ========= | ======== | ========= | ======== | ======================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | 
| 0000001075 | M015547415E | 0                                                                   | 0.298169999999999990603072319572675041854381561279296875   | 1451606401    | 1451606401           |                    | JDENKER     |          | 1459767127         |                 | 4         | NO ERROR |           | 1        | [null, 42.062192665000055, -93.65850967799997, null, false, {paths=[[[-93.65850967799997, 42.062192665000055], [-93.65589322999995, 42.06222222400004], [-93.65467074699995, 42.06219429300006], [-93.65421366299995, 42.06219490700005], [-93.65393352599995, 42.062200777000044], [-93.65366079699999, 42.06222037100008], [-93.65338809899998, 42.06225369600003], [-93.65273013599995, 42.062356727000065]]]}]                                                                                                                                                                      | 
| 0000005284 | M015547425E | 0.00016400000000000000189605275924265015419223345816135406494140625 | 0.292678999999999966963315500834141857922077178955078125   | 1451606401    | 1451606401           |                    | JDENKER     |          | 1459767128         |                 | 4         | NO ERROR |           | 2        | [null, 42.062932999000054, -93.65843944899996, null, false, {paths=[[[-93.65843944899996, 42.062932999000054], [-93.65841303199994, 42.06297259400003], [-93.65836992599998, 42.063006005000034], [-93.65827641999994, 42.063043263000054], [-93.65814008199999, 42.063059664000036], [-93.65793382599998, 42.06306091000005], [-93.65591773899996, 42.06307306100007], [-93.65503655799995, 42.06307836000008], [-93.65306308099997, 42.06306948500003], [-93.65296513099997, 42.06305451900005], [-93.65289079299998, 42.06302946000005], [-93.65283518799998, 42.06300366700003]]]}] | 
| 0000009467 | M016541250N | 0                                                                   | 0.06503899999999999959054974851824226789176464080810546875 | 1451606401    | 1451606401           |                    | JDENKER     |          | 1459767130         |                 | 1         | NO ERROR |           | 3        | [null, 42.10829217400004, -91.28387471299999, null, false, {paths=[[[-91.28387471299999, 42.10829217400004], [-91.28391456699995, 42.10923441600005]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                | 
| 0000006006 | M016541250N | 0.06503899999999999959054974851824226789176464080810546875          | 0.130255999999999982907894491290790028870105743408203125   | 1451606401    | 1451606401           |                    | JDENKER     |          | 1459767129         |                 | 2         | NO ERROR |           | 4        | [null, 42.10923441600005, -91.28391456699995, null, false, {paths=[[[-91.28391456699995, 42.10923441600005], [-91.28392773599995, 42.109960527000055], [-91.28392843399996, 42.11007853800004], [-91.28392758099994, 42.11017964000007]]]}]                                                                                                                                                                                                                                                                                                                                             | 
| 0000025784 | M016541250N | 0.130255999999999982907894491290790028870105743408203125            | 0.381734999999999990993870824240730144083499908447265625   | 1451606401    | 1451606401           |                    | JDENKER     |          | 1459767136         |                 | 4         | NO ERROR |           | 5        | [null, 42.11017964000007, -91.28392758099994, null, false, {paths=[[[-91.28392758099994, 42.11017964000007], [-91.28392382199996, 42.11062552200008], [-91.28392140899996, 42.11112914300003], [-91.28391998599994, 42.111426393000045], [-91.28392972499995, 42.11211310500005], [-91.28392859299998, 42.112238294000065], [-91.28391425599995, 42.11382461900007]]]}]                                                                                                                                                                                                                 | 
| 0000032041 | M016541320N | 0                                                                   | 0.062273999999999996024513393422239460051059722900390625   | 1451606401    | 1451606401           |                    | JDENKER     |          | 1459767138         |                 | 4         | NO ERROR |           | 6        | [null, 42.10559032100008, -91.28066000999996, null, false, {paths=[[[-91.28066000999996, 42.10559032100008], [-91.28066656599998, 42.10649294400008]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                | 
| 0000002015 | M016541320N | 0.062273999999999996024513393422239460051059722900390625            | 0.1858059999999999989395149668780504725873470306396484375  | 1451606401    | 1451606401           |                    | JDENKER     |          | 1459767127         |                 | 2         | NO ERROR |           | 7        | [null, 42.10649294400008, -91.28066656599998, null, false, {paths=[[[-91.28066656599998, 42.10649294400008], [-91.28066788399997, 42.10667481300004], [-91.28070056699994, 42.10808067600004], [-91.28070148599994, 42.10828326600006]]]}]                                                                                                                                                                                                                                                                                                                                              | 
| 0000024449 | M016546110E | 0.09915099999999998914290699758566915988922119140625                | 0.1973769999999999968931518878889619372785091400146484375  | 1451606401    | 1451606401           |                    | JDENKER     |          | 1459767136         |                 | 3         | NO ERROR |           | 8        | [null, 42.10662989900004, -91.29322722599994, null, false, {paths=[[[-91.29322722599994, 42.10662989900004], [-91.29297502899999, 42.10652100000004], [-91.29255856999998, 42.10634494800007], [-91.29237879499999, 42.10626790600003], [-91.29210434499998, 42.10615029200005], [-91.29157352199996, 42.10591543000004]]]}]                                                                                                                                                                                                                                                            | 
| 0000031778 | M016546110E | 0.1973769999999999968931518878889619372785091400146484375           | 0.283314000000000010270895245412248186767101287841796875   | 1451606401    | 1451606401           |                    | JDENKER     |          | 1459767138         |                 | 4         | NO ERROR |           | 9        | [null, 42.10591543000004, -91.29157352199996, null, false, {paths=[[[-91.29157352199996, 42.10591543000004], [-91.29123416699997, 42.10576528300004], [-91.29073014399995, 42.105548862000035], [-91.29012704799999, 42.10528989800008]]]}]                                                                                                                                                                                                                                                                                                                                             | 
| 0000001039 | M016546110E | 0                                                                   | 0.09915099999999998914290699758566915988922119140625       | 1451606401    | 1451606401           |                    | JDENKER     |          | 1459767127         |                 | 4         | NO ERROR |           | 10       | [null, 42.10739514800008, -91.29481930399999, null, false, {paths=[[[-91.29481930399999, 42.10739514800008], [-91.29481472499998, 42.107335798000065], [-91.29470645699996, 42.10727293400004], [-91.29435162999994, 42.10711952500003], [-91.29405131499999, 42.10698709600007], [-91.29390231699995, 42.10692139400004], [-91.29322722599994, 42.10662989900004]]]}]                                                                                                                                                                                                                  | 
```