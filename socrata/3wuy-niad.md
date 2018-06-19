# RAMS - Routes Ramp

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rams-routes-ramp) |
| Metadata | [Link](https://data.iowa.gov/api/views/3wuy-niad) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/3wuy-niad/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/3wuy-niad/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 3wuy-niad |
| Name | RAMS - Routes Ramp |
| Attribution | Iowa Department of Transportation - Office of Research & Analytics |
| Category | Transportation & Utilities |
| Tags | iowa dot, iowa department of transportation, rams, routes ramp, asset, classification |
| Created | 2016-12-06T20:16:28Z |
| Publication Date | 2016-12-06T20:17:57Z |

## Description

Routes Ramp data maintained inside the Roadway Asset Management System (RAMS).

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
| Yes      | series tag     | route_name           | ROUTE_NAME           | text       | text        |
| Yes      | numeric metric | priority             | PRIORITY             | number     | number      |
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
series e:3wuy-niad d:2016-01-01T06:00:00.000Z t:shape.longitude=-95.67418996999999 t:shape.needs_recoding=false t:route_id=S001910080E5405 t:route_name="COUNTY OF POTTAWATTAMIE, MAGNOLIA ROAD, W TO STATE OF IOWA, I 80 E" t:event_id=0000000266 t:user_create=JRENFRO t:locerror="NO ERROR" t:shape.latitude=41.37622767200003 t:user_mod=RAMS t:objectid=1 m:priority=2 m:to_measure=0.347016 m:from_measure=0

series e:3wuy-niad d:2016-01-01T06:00:00.000Z t:shape.longitude=-95.45765204799994 t:shape.needs_recoding=false t:route_id=S001910080E5600 t:route_name="STATE OF IOWA, I 80 E TO CITY OF SHELBY, EAST STREET, S" t:event_id=0000000550 t:user_create=JRENFRO t:locerror="NO ERROR" t:shape.latitude=41.498757374000036 t:user_mod=RAMS t:objectid=2 m:priority=2 m:to_measure=0.348753 m:from_measure=0

series e:3wuy-niad d:2016-01-01T06:00:00.000Z t:shape.longitude=-93.49884782599997 t:shape.needs_recoding=false t:route_id=S001920065S1410 t:route_name="STATE OF IOWA, IA 163 W TO STATE OF IOWA, US 65 S" t:event_id=0000004610 t:user_create=JRENFRO t:locerror="NO ERROR" t:shape.latitude=41.59892363000006 t:user_mod=RAMS t:objectid=3 m:priority=2 m:to_measure=0.437283 m:from_measure=0.422892
```

## Meta Commands

```ls
metric m:from_measure p:decimal l:FROM_MEASURE d:"From Measure" t:dataTypeName=number

metric m:to_measure p:decimal l:TO_MEASURE d:"To Measure" t:dataTypeName=number

metric m:priority p:integer l:PRIORITY d:Priority t:dataTypeName=number

metric m:shape_len p:long l:SHAPE.LEN d:"Length (Meter)" t:dataTypeName=number

entity e:3wuy-niad l:"RAMS - Routes Ramp" t:attribution="Iowa Department of Transportation - Office of Research & Analytics" t:url=https://data.iowa.gov/api/views/3wuy-niad

property e:3wuy-niad t:meta.view v:id=3wuy-niad v:category="Transportation & Utilities" v:averageRating=0 v:name="RAMS - Routes Ramp" v:attribution="Iowa Department of Transportation - Office of Research & Analytics"

property e:3wuy-niad t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:3wuy-niad t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| event_id   | route_id        | from_measure                                             | to_measure                                                   | business_date | effective_start_date | effective_end_date | user_create | user_mod | system_create_date | system_mod_date | route_name                                                            | priority | locerror | shape_len | objectid | shape                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 
| ========== | =============== | ======================================================== | ============================================================ | ============= | ==================== | ================== | =========== | ======== | ================== | =============== | ===================================================================== | ======== | ======== | ========= | ======== | ====================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 0000000266 | S001910080E5405 | 0                                                        | 0.347015999999999991132426657713949680328369140625           | 1451628000    | 1451606401           |                    | JRENFRO     | RAMS     | 1460019678         | 1464780158      | COUNTY OF POTTAWATTAMIE, MAGNOLIA ROAD, W TO STATE OF IOWA, I 80 E    | 2        | NO ERROR |           | 1        | [null, 41.37622767200003, -95.67418996999999, null, false, {paths=[[[-95.67418996999999, 41.37622767200003], [-95.67412966199998, 41.376395649000074], [-95.67386513499997, 41.37681856900008], [-95.67350386499999, 41.37737909100008], [-95.67317180599997, 41.37797086900008], [-95.67286914899995, 41.37843269700005], [-95.67271695199997, 41.37867953500006], [-95.67259926499997, 41.378864202000045], [-95.67244224599995, 41.37905174100007], [-95.67219239899998, 41.37932589800005], [-95.67182250399998, 41.37971476900003], [-95.67155612099998, 41.37999984500004], [-95.67116982799996, 41.38040387400008], [-95.67100126899999, 41.38062155500006]]]}]                                                                                                                                 | 
| 0000000550 | S001910080E5600 | 0                                                        | 0.34875299999999997968558318461873568594455718994140625      | 1451628000    | 1451606401           |                    | JRENFRO     | RAMS     | 1460019679         | 1464780158      | STATE OF IOWA, I 80 E TO CITY OF SHELBY, EAST STREET, S               | 2        | NO ERROR |           | 2        | [null, 41.498757374000036, -95.45765204799994, null, false, {paths=[[[-95.45765204799994, 41.498757374000036], [-95.45687241199994, 41.49869781700005], [-95.45611198299997, 41.498657982000054], [-95.45593570299997, 41.498647247000065], [-95.45547009299997, 41.498618890000046], [-95.45505037799995, 41.49857876500005], [-95.45485671499995, 41.49854311000007], [-95.45455124399996, 41.49848431500004], [-95.45429793299996, 41.49843576200004], [-95.45377506899996, 41.49829159900003], [-95.45323647399994, 41.49811707600003], [-95.45288489699999, 41.498003382000036], [-95.45226091899997, 41.49782196600006], [-95.45169271699996, 41.49764794500004], [-95.45137513699996, 41.49755593700007], [-95.45118998099997, 41.497570273000065]]]}]                                          | 
| 0000004610 | S001920065S1410 | 0.422891999999999990134114113971008919179439544677734375 | 0.43728299999999997726973788303439505398273468017578125      | 1451628000    | 1451606401           |                    | JRENFRO     | RAMS     | 1460019680         | 1464780143      | STATE OF IOWA, IA 163 W TO STATE OF IOWA, US 65 S                     | 2        | NO ERROR |           | 3        | [null, 41.59892363000006, -93.49884782599997, null, false, {paths=[[[-93.49884782599997, 41.59892363000006], [-93.49887333299995, 41.598865069000055], [-93.49889619299995, 41.59878499600006], [-93.49890556599996, 41.59872027700004]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | 
| 0000006293 | S001920065S1600 | 0                                                        | 0.024527000000000000190514271025676862336695194244384765625  | 1451628000    | 1451606401           |                    | JRENFRO     | RAMS     | 1460019681         | 1464780143      | CITY OF HUBBARD, MAPLE STREET, W TO STATE OF IOWA, US 65 S            | 2        | NO ERROR |           | 4        | [null, 42.30544108500004, -93.30970070799998, null, false, {paths=[[[-93.30970070799998, 42.30544108500004], [-93.30928501899996, 42.30561760000006]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | 
| 0000003157 | S001920065S1750 | 0.170250999999999985679011160755180753767490386962890625 | 0.5262219999999999675566186851938255131244659423828125       | 1451628000    | 1451606401           |                    | JRENFRO     | RAMS     | 1460019680         | 1464780143      | CITY OF DES MOINES, EAST BROADWAY AVENUE, E TO STATE OF IOWA, US 65 S | 4        | NO ERROR |           | 5        | [null, 41.643322684000054, -93.51080512199997, null, false, {paths=[[[-93.51080512199997, 41.643322684000054], [-93.51039070999997, 41.64293517400006], [-93.50952097599998, 41.64212562100005], [-93.50929586999996, 41.64191267800004], [-93.50913727399995, 41.64174961400005], [-93.50899914099995, 41.64160573400005], [-93.50886356599995, 41.641446503000054], [-93.50875100999997, 41.64131605000006], [-93.50864101399998, 41.641174086000035], [-93.50855659799998, 41.641062815000055], [-93.50847473799996, 41.64094003400004], [-93.50838264599997, 41.640805742000055], [-93.50829055499997, 41.64067336800008], [-93.50821892799996, 41.64056209600005], [-93.50806544499994, 41.640343392000034], [-93.50778661499999, 41.63990598100003], [-93.50713636499995, 41.63898430800003]]]}] | 
| 0000002678 | S001920065S1750 | 0.170250999999999985679011160755180753767490386962890625 | 0.5262219999999999675566186851938255131244659423828125       | 1451628000    | 1451606401           |                    | JRENFRO     | RAMS     | 1460019679         | 1464780143      | STATE OF IOWA, US 6 W TO STATE OF IOWA, US 65 S                       | 1        | NO ERROR |           | 6        | [null, 41.643322684000054, -93.51080512199997, null, false, {paths=[[[-93.51080512199997, 41.643322684000054], [-93.51039070999997, 41.64293517400006], [-93.50952097599998, 41.64212562100005], [-93.50929586999996, 41.64191267800004], [-93.50913727399995, 41.64174961400005], [-93.50899914099995, 41.64160573400005], [-93.50886356599995, 41.641446503000054], [-93.50875100999997, 41.64131605000006], [-93.50864101399998, 41.641174086000035], [-93.50855659799998, 41.641062815000055], [-93.50847473799996, 41.64094003400004], [-93.50838264599997, 41.640805742000055], [-93.50829055499997, 41.64067336800008], [-93.50821892799996, 41.64056209600005], [-93.50806544499994, 41.640343392000034], [-93.50778661499999, 41.63990598100003], [-93.50713636499995, 41.63898430800003]]]}] | 
| 0000005086 | S001920067N1250 | 0                                                        | 0.0295039999999999989765964159005307010374963283538818359375 | 1451628000    | 1451606401           |                    | JRENFRO     | RAMS     | 1460019680         | 1464780143      | COUNTY OF JACKSON, 1ST STREET, E TO STATE OF IOWA, US 67 N            | 2        | NO ERROR |           | 7        | [null, 42.03697977400003, -90.19326497499998, null, false, {paths=[[[-90.19326497499998, 42.03697977400003], [-90.19350897299995, 42.036881391000065], [-90.19368516299994, 42.036814922000076], [-90.19377870599999, 42.03679122200003]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | 
| 0000004835 | S001920069S1450 | 0                                                        | 0.1876339999999999952340345998891280032694339752197265625    | 1451628000    | 1451606401           |                    | JRENFRO     | RAMS     | 1460019680         | 1464780143      | STATE OF IOWA, US 69 N TO COUNTY OF HAMILTON, 380TH STREET, E         | 1        | NO ERROR |           | 8        | [null, 42.238292759000046, -93.62051381399999, null, false, {paths=[[[-93.62051381399999, 42.238292759000046], [-93.62042493399997, 42.23707757300008], [-93.62033475499999, 42.23557646300003]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | 
| 0000001650 | S001920075S1410 | 0                                                        | 0.377170999999999978502529529578168876469135284423828125     | 1451628000    | 1451606401           |                    | JRENFRO     | RAMS     | 1460019679         | 1464780147      | STATE OF IOWA, US 75 S TO STATE OF IOWA, IA 3 W                       | 2        | NO ERROR |           | 9        | [null, 42.79302743000005, -96.20637901499998, null, false, {paths=[[[-96.20637901499998, 42.79302743000005], [-96.20611203799996, 42.79376834300007], [-96.20598837399996, 42.79410829100004], [-96.20582775399998, 42.79436483300003], [-96.20563228999998, 42.79458707100008], [-96.20537831199994, 42.794779075000065], [-96.20480337299995, 42.79515761300007], [-96.20420687099994, 42.795589319000044], [-96.20385487299995, 42.79594159900006], [-96.20357341199997, 42.79627116900008], [-96.20271964599999, 42.79765651800005]]]}]                                                                                                                                                                                                                                                            | 
| 0000004736 | S001920075S1410 | 0                                                        | 0.377170999999999978502529529578168876469135284423828125     | 1451628000    | 1451606401           |                    | JRENFRO     | RAMS     | 1460019680         | 1464780147      | COUNTY OF PLYMOUTH, US 75 SIGNED ROUTE, S TO STATE OF IOWA, IA 3 W    | 8        | NO ERROR |           | 10       | [null, 42.79302743000005, -96.20637901499998, null, false, {paths=[[[-96.20637901499998, 42.79302743000005], [-96.20611203799996, 42.79376834300007], [-96.20598837399996, 42.79410829100004], [-96.20582775399998, 42.79436483300003], [-96.20563228999998, 42.79458707100008], [-96.20537831199994, 42.794779075000065], [-96.20480337299995, 42.79515761300007], [-96.20420687099994, 42.795589319000044], [-96.20385487299995, 42.79594159900006], [-96.20357341199997, 42.79627116900008], [-96.20271964599999, 42.79765651800005]]]}]                                                                                                                                                                                                                                                            | 
```