# RAMS - Cost Group

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rams-cost-group) |
| Metadata | [Link](https://data.iowa.gov/api/views/py72-ecd2) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/py72-ecd2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/py72-ecd2/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | py72-ecd2 |
| Name | RAMS - Cost Group |
| Attribution | Iowa Department of Transportation - Office of Research & Analytics |
| Category | Transportation & Utilities |
| Tags | iowa dot, iowa department of transportation, rams, cost group, asset, classification |
| Created | 2016-12-06T16:45:29Z |
| Publication Date | 2016-12-06T16:47:46Z |

## Description

Cost Group data maintained inside the Roadway Asset Management System (RAMS).

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type  | Render Type |
| ======== | ============== | ==================== | ==================== | ========== | =========== |
| Yes      | series tag     | event_id             | EVENT_ID             | text       | text        |
| Yes      | series tag     | route_id             | ROUTE_ID             | text       | text        |
| Yes      | numeric metric | from_measure         | FROM_MEASURE         | number     | number      |
| Yes      | numeric metric | to_measure           | TO_MEASURE           | number     | number      |
| Yes      | time           | business_date        | BUSINESS_DATE        | date       | date        |
| No       |                | effective_start_date | EFFECTIVE_START_DATE | date       | date        |
| No       |                | effective_end_date   | EFFECTIVE_END_DATE   | date       | date        |
| Yes      | series tag     | user_create          | USER_CREATE          | text       | text        |
| Yes      | series tag     | user_mod             | USER_MOD             | text       | text        |
| No       |                | system_create_date   | SYSTEM_CREATE_DATE   | date       | date        |
| No       |                | system_mod_date      | SYSTEM_MOD_DATE      | date       | date        |
| Yes      | series tag     | cost_group           | COST_GROUP           | text       | number      |
| Yes      | series tag     | locerror             | LOCERROR             | text       | text        |
| Yes      | numeric metric | shape_len            | SHAPE.LEN            | number     | number      |
| Yes      | series tag     | objectid             | OBJECTID             | text       | number      |
| No       |                | shape                | SHAPE                | geospatial | geospatial  |
```

## Time Field

```ls
Value = business_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = effective_start_date,effective_end_date,system_create_date,system_mod_date,shape
```

## Data Commands

```ls
series e:py72-ecd2 d:2016-01-01T06:00:00.000Z t:shape.longitude=-91.02897145599997 t:shape.needs_recoding=false t:route_id=M533042520N t:event_id=0000014668 t:user_create=RWYLLIE t:locerror="NO ERROR" t:shape.latitude=41.435235316000046 t:user_mod=RAMS t:objectid=1 t:cost_group=2 m:to_measure=0.064465 m:from_measure=0

series e:py72-ecd2 d:2016-01-01T06:00:00.000Z t:shape.longitude=-93.52021607199998 t:shape.needs_recoding=false t:route_id=M610241180N t:event_id=0000043856 t:user_create=RWYLLIE t:locerror="NO ERROR" t:shape.latitude=41.59325142400007 t:user_mod=RAMS t:objectid=2 t:cost_group=2 m:to_measure=0.389611 m:from_measure=0

series e:py72-ecd2 d:2016-01-01T06:00:00.000Z t:shape.longitude=-93.74377980599996 t:shape.needs_recoding=false t:route_id=M612246000E t:event_id=0000021819 t:user_create=RWYLLIE t:locerror="NO ERROR" t:shape.latitude=40.57980440100005 t:user_mod=RAMS t:objectid=3 t:cost_group=2 m:to_measure=0.263569 m:from_measure=0.214199
```

## Meta Commands

```ls
metric m:from_measure p:decimal l:FROM_MEASURE d:"From Measure" t:dataTypeName=number

metric m:to_measure p:decimal l:TO_MEASURE d:"To Measure" t:dataTypeName=number

metric m:shape_len p:long l:SHAPE.LEN d:"Length (Meter)" t:dataTypeName=number

entity e:py72-ecd2 l:"RAMS - Cost Group" t:attribution="Iowa Department of Transportation - Office of Research & Analytics" t:url=https://data.iowa.gov/api/views/py72-ecd2

property e:py72-ecd2 t:meta.view v:id=py72-ecd2 v:category="Transportation & Utilities" v:averageRating=0 v:name="RAMS - Cost Group" v:attribution="Iowa Department of Transportation - Office of Research & Analytics"

property e:py72-ecd2 t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:py72-ecd2 t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| event_id   | route_id    | from_measure                                              | to_measure                                                 | business_date | effective_start_date | effective_end_date | user_create | user_mod | system_create_date | system_mod_date | cost_group | locerror | shape_len | objectid | shape                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 
| ========== | =========== | ========================================================= | ========================================================== | ============= | ==================== | ================== | =========== | ======== | ================== | =============== | ========== | ======== | ========= | ======== | ========================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | 
| 0000014668 | M533042520N | 0                                                         | 0.0644649999999999945288209346472285687923431396484375     | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459765119         | 1463663540      | 2          | NO ERROR |           | 1        | [null, 41.435235316000046, -91.02897145599997, null, false, {paths=[[[-91.02897145599997, 41.435235316000046], [-91.02885963999995, 41.436165981000045]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | 
| 0000043856 | M610241180N | 0                                                         | 0.389610999999999985110576972147100605070590972900390625   | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459765131         | 1463663541      | 2          | NO ERROR |           | 2        | [null, 41.59325142400007, -93.52021607199998, null, false, {paths=[[[-93.52021607199998, 41.59325142400007], [-93.51842691399997, 41.59318318700008], [-93.51713669099996, 41.59313198500007], [-93.51697522099994, 41.593132009000044], [-93.51682109599994, 41.59315408100008], [-93.51665229999998, 41.59320188700008], [-93.51650636499994, 41.59327908800003], [-93.51641331299999, 41.59334377000005], [-93.51632291199996, 41.59342613000007], [-93.51620307199994, 41.59358602400005], [-93.51533615799997, 41.59489245200007], [-93.51531985599996, 41.59492259000007], [-93.51530681799994, 41.59496424400004], [-93.51530357599995, 41.595053678000056], [-93.51530541299996, 41.59584495900003], [-93.51531413999999, 41.595867412000075]]]}] | 
| 0000021819 | M612246000E | 0.2141990000000000005098144129078718833625316619873046875 | 0.263568999999999997729815959246479906141757965087890625   | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459765122         | 1463663541      | 2          | NO ERROR |           | 3        | [null, 40.57980440100005, -93.74377980599996, null, false, {paths=[[[-93.74377980599996, 40.57980440100005], [-93.74336330799997, 40.57982470200005], [-93.74284215899996, 40.579822972000045]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 
| 0000053657 | M612541030N | 0                                                         | 0.05479499999999999648725435008600470609962940216064453125 | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459765134         | 1463663541      | 3          | NO ERROR |           | 4        | [null, 41.39644841900008, -93.27611345899999, null, false, {paths=[[[-93.27611345899999, 41.39644841900008], [-93.27545488099997, 41.397068871000045]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 
| 0000005765 | M612541110N | 0.361341999999999996528998735811910592019557952880859375  | 0.464160999999999990262011806407826952636241912841796875   | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459765116         | 1463663541      | 2          | NO ERROR |           | 5        | [null, 41.38717043100007, -93.26994674499997, null, false, {paths=[[[-93.26994674499997, 41.38717043100007], [-93.26994029899998, 41.38741035400005], [-93.26996937399997, 41.38866060500004]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | 
| 0000028693 | M612546030E | 0                                                         | 0.41135299999999996867217078033718280494213104248046875    | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459765125         | 1463663541      | 2          | NO ERROR |           | 6        | [null, 41.38410152900008, -93.26982355399997, null, false, {paths=[[[-93.26982355399997, 41.38410152900008], [-93.26937089999996, 41.38408377400003], [-93.26853806499997, 41.38409891900005], [-93.26790651299996, 41.384093423000024], [-93.26530188099997, 41.38412175000008], [-93.26401076999997, 41.384127497000065], [-93.26287620099998, 41.38412092600004], [-93.26190766999997, 41.38413196000005]]]}]                                                                                                                                                                                                                                                                                                                                          | 
| 0000046688 | M617041490N | 0                                                         | 0.1825969999999999815454287954707979224622249603271484375  | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459765132         | 1463663541      | 2          | NO ERROR |           | 7        | [null, 41.761868519000075, -93.71203458999997, null, false, {paths=[[[-93.71203458999997, 41.761868519000075], [-93.71186749299994, 41.762098851000076], [-93.71178188299996, 41.76220942000003], [-93.71172489999998, 41.76231073500003], [-93.71167611299995, 41.762415101000045], [-93.71165237499997, 41.76252066500007], [-93.71163262699997, 41.76273845400004], [-93.71163465799998, 41.76387471400005], [-93.71164279399994, 41.764449454000044]]]}]                                                                                                                                                                                                                                                                                              | 
| 0000004556 | M620741190N | 0.2103629999999999944382267358378157950937747955322265625 | 0.266091999999999995196731106261722743511199951171875      | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459765115         | 1463663541      | 3          | NO ERROR |           | 8        | [null, 41.59762958600004, -93.23513238199996, null, false, {paths=[[[-93.23513238199996, 41.59762958600004], [-93.23513790499999, 41.59780171300008], [-93.23513786399997, 41.598362473000066], [-93.23513647099998, 41.598437346000026]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 
| 0000054892 | M624046150E | 0                                                         | 0.28305199999999997029220821787021122872829437255859375    | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459765135         | 1463663541      | 2          | NO ERROR |           | 9        | [null, 43.08906072700006, -95.62691812599996, null, false, {paths=[[[-95.62691812599996, 43.08906072700006], [-95.62541173199998, 43.08906296600003], [-95.62504865399995, 43.089063503000034], [-95.62430395599995, 43.08906393800004], [-95.62342470499999, 43.089064445000076], [-95.62281834499998, 43.08906372300004], [-95.62133462799994, 43.08906194300005], [-95.62132230599997, 43.08906187000008]]]}]                                                                                                                                                                                                                                                                                                                                          | 
| 0000043741 | M631241000N | 0                                                         | 0.07913299999999999501110181654439656995236873626708984375 | 1451628000    | 1451606401           |                    | RWYLLIE     | RAMS     | 1459765131         | 1463663541      | 2          | NO ERROR |           | 10       | [null, 42.04083597600004, -94.63510856299996, null, false, {paths=[[[-94.63510856299996, 42.04083597600004], [-94.63500118299999, 42.041060955000034], [-94.63472366299999, 42.041635668000026], [-94.63455152599994, 42.041903975000025]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 
```