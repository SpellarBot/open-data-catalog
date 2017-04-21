# LRS Routes - Ramps & Connectors

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lrs-routes-ramps-connectors) |
| Metadata | [Link](https://data.iowa.gov/api/views/tjiu-7wn5) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/tjiu-7wn5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/tjiu-7wn5/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | tjiu-7wn5 |
| Name | LRS Routes - Ramps & Connectors |
| Attribution | Iowa Department of Transportation - Office of Research & Analytics |
| Category | Transportation & Utilities |
| Tags | reference, asset, inventory, roads, lrs, road network, transportation, rams, street, iowa dot, iowa department of transportation |
| Created | 2016-11-08T18:31:58Z |
| Publication Date | 2016-11-08T18:33:53Z |

## Description

This layer contains all Ramps and Connectors in the State of Iowa. This data was derived from the Roadway Asset Management System (RAMS).

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type  | Render Type |
| ======== | ============== | =========== | =========== | ========== | =========== |
| No       | time           | :updated_at | updated_at  | meta_data  | meta_data   |
| No       |                | id          | ID          | text       | text        |
| Yes      | series tag     | routeid     | ROUTEID     | text       | text        |
| Yes      | numeric metric | frommeasure | FROMMEASURE | number     | number      |
| Yes      | numeric metric | tomeasure   | TOMEASURE   | number     | number      |
| Yes      | series tag     | ramps       | RAMPS       | text       | text        |
| Yes      | numeric metric | shape_len   | SHAPE.LEN   | number     | number      |
| Yes      | series tag     | objectid    | OBJECTID    | text       | number      |
| No       |                | shape       | SHAPE       | geospatial | geospatial  |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id,shape
```

## Data Commands

```ls
series e:tjiu-7wn5 d:2016-11-08T18:31:58.000Z t:shape.longitude=-95.91743536799999 t:routeid=S001910029N2200 t:shape.needs_recoding=false t:shape.latitude=41.54558040500007 t:objectid=16 t:ramps="STATE OF IOWA, I 29 N TO STATE OF IOWA, US 30 E" m:frommeasure=0 m:tomeasure=0.265267

series e:tjiu-7wn5 d:2016-11-08T18:31:58.000Z t:shape.longitude=-95.91627485299995 t:routeid=S001910029N2200 t:shape.needs_recoding=false t:shape.latitude=41.54930513000005 t:objectid=20 t:ramps="STATE OF IOWA, I 29 N TO STATE OF IOWA, US 30 W" m:frommeasure=0.265267 m:tomeasure=0.322807

series e:tjiu-7wn5 d:2016-11-08T18:31:58.000Z t:shape.longitude=-94.51967020099994 t:routeid=S001910080W6180 t:shape.needs_recoding=false t:shape.latitude=41.49676575700005 t:objectid=21 t:ramps="STATE OF IOWA, I 80 W TO COUNTY OF ADAIR, ANTIQUE COUNTRY DRIVE, S" m:frommeasure=0.18157099999999998 m:tomeasure=0.20568299999999998
```

## Meta Commands

```ls
metric m:frommeasure p:long l:FROMMEASURE d:"From Measure" t:dataTypeName=number

metric m:tomeasure p:long l:TOMEASURE d:"To Measure" t:dataTypeName=number

metric m:shape_len p:long l:SHAPE.LEN d:"Length (Meter)" t:dataTypeName=number

entity e:tjiu-7wn5 l:"LRS Routes - Ramps & Connectors" t:attribution="Iowa Department of Transportation - Office of Research & Analytics" t:url=https://data.iowa.gov/api/views/tjiu-7wn5

property e:tjiu-7wn5 t:meta.view v:id=tjiu-7wn5 v:category="Transportation & Utilities" v:averageRating=0 v:name="LRS Routes - Ramps & Connectors" v:attribution="Iowa Department of Transportation - Office of Research & Analytics"

property e:tjiu-7wn5 t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:tjiu-7wn5 t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | id                                   | routeid         | frommeasure                                               | tomeasure                                                    | ramps                                                                   | shape_len | objectid | shape                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 
| =========== | ==================================== | =============== | ========================================================= | ============================================================ | ======================================================================= | ========= | ======== | ==================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 0           | 399386bc-d9f1-48b2-994a-4982b3772c19 | S001910029N2200 | 0                                                         | 0.265266999999999975035080979068879969418048858642578125     | STATE OF IOWA, I 29 N TO STATE OF IOWA, US 30 E                         |           | 16       | [null, 41.54558040500007, -95.91743536799999, null, false, {paths=[[[-95.91743536799999, 41.54558040500007], [-95.91732894299997, 41.54640442800007], [-95.91729199199995, 41.54668772400004], [-95.91725423299994, 41.54694958300007], [-95.91719161599997, 41.54718335800004], [-95.91708264299996, 41.54745030300006], [-95.91679804399996, 41.54811077000005], [-95.91641223199997, 41.548991525000076], [-95.91627485299995, 41.54930513000005]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                             | 
| 0           | 7009102e-78c2-46da-a3c9-00a0135eefd8 | S001910029N2200 | 0.265266999999999975035080979068879969418048858642578125  | 0.322807000000000010597744903861894272267818450927734375     | STATE OF IOWA, I 29 N TO STATE OF IOWA, US 30 W                         |           | 20       | [null, 41.54930513000005, -95.91627485299995, null, false, {paths=[[[-95.91627485299995, 41.54930513000005], [-95.91598434999997, 41.54989477400005], [-95.91590949699997, 41.55009227100004]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | 
| 0           | 28f90bf0-9c62-4d77-a37b-022abb4edf58 | S001910080W6180 | 0.181570999999999982410514576258719898760318756103515625  | 0.2056829999999999769588754361393512226641178131103515625    | STATE OF IOWA, I 80 W TO COUNTY OF ADAIR, ANTIQUE COUNTRY DRIVE, S      |           | 21       | [null, 41.49676575700005, -94.51967020099994, null, false, {paths=[[[-94.51967020099994, 41.49676575700005], [-94.51980324599998, 41.49677393700006], [-94.51988384199996, 41.49675891500004], [-94.51995957199995, 41.49673678700003], [-94.52001130499997, 41.496700574000045], [-94.52005513999995, 41.496635998000045]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | 
| 0           | 51b9123d-aac4-419d-93e8-b81682a79e42 | S001910380S2315 | 0                                                         | 0.36746599999999995933563923244946636259555816650390625      | CITY OF HIAWATHA, BOYSON ROAD, E TO STATE OF IOWA, I 380 S              |           | 23       | [null, 42.044692747000056, -91.68614284199998, null, false, {paths=[[[-91.68614284199998, 42.044692747000056], [-91.68598953799994, 42.04460005200008], [-91.68565797499997, 42.04450022700007], [-91.68463119999996, 42.04421144500003], [-91.68368642499996, 42.04394405600004], [-91.68286999799994, 42.04371588500004], [-91.68233165299995, 42.043551886000046], [-91.68214269899994, 42.04348414800006], [-91.68195017699998, 42.04341997500006], [-91.68160435599998, 42.043288061000055], [-91.68109809699996, 42.043070586000056], [-91.68073444799995, 42.04288163000007], [-91.67975450799997, 42.04237509600006]]]}]                                                                                                                                                                                                                                                     | 
| 0           | c6f459bd-8821-48c4-b89c-4c290d49e816 | S001920020W5130 | 0                                                         | 0.30917099999999997361754822122748009860515594482421875      | CITY OF SIOUX CITY, SOUTH LAKEPORT STREET, N TO STATE OF IOWA, US 20 W  |           | 26       | [null, 42.44503897200008, -96.34686249799995, null, false, {paths=[[[-96.34686249799995, 42.44503897200008], [-96.34700224299996, 42.44506506400006], [-96.34724447799994, 42.445054904000074], [-96.34756803199997, 42.44498370300005], [-96.34783236199996, 42.44489564400004], [-96.34879286199998, 42.44458455300003], [-96.34927774999994, 42.44443634000004], [-96.34998918999997, 42.444212280000045], [-96.35063936699999, 42.44403230900008], [-96.35098910099998, 42.443947036000054], [-96.35140295899998, 42.443881469000075], [-96.35189309799995, 42.443850213000076], [-96.35260266199998, 42.44380240100003]]]}]                                                                                                                                                                                                                                                     | 
| 0           | 5ae2c580-1066-44d7-a7fc-ca51c715f044 | S001920030W6305 | 0                                                         | 0.319094999999999962003727205228642560541629791259765625     | COUNTY OF TAMA, BUSINESS US30 SIGNED ROUTE, E TO STATE OF IOWA, US 30 W |           | 32       | [null, 41.99283776200008, -92.61221286799997, null, false, {paths=[[[-92.61221286799997, 41.99283776200008], [-92.61331485699998, 41.992911735000064], [-92.61465347699999, 41.99300422600004], [-92.61523427399999, 41.99303609000003], [-92.61729440199997, 41.99316149600003], [-92.61838829799996, 41.993247617000065]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | 
| 0           | 85757416-3457-421f-9433-fdfbcee8b20e | S001920034W6065 | 0                                                         | 0.27791299999999996561683701656875200569629669189453125      | STATE OF IOWA, IA 1 N TO STATE OF IOWA, US 34 W                         |           | 35       | [null, 40.98561658800003, -91.96314169299995, null, false, {paths=[[[-91.96314169299995, 40.98561658800003], [-91.96296871199996, 40.985575475000076], [-91.96189926199997, 40.98556092000007], [-91.96161848099996, 40.98554095000003], [-91.96136850299996, 40.985476177000066], [-91.96116621099998, 40.98537976100005], [-91.96105772899995, 40.98528139000007], [-91.96093296799995, 40.98515050000003], [-91.96087219999998, 40.98501725300008], [-91.96086060099998, 40.984937341000034], [-91.96085388399996, 40.98489104400005], [-91.96084842599998, 40.98476178000004], [-91.96086419499994, 40.98463603500005], [-91.96090925499999, 40.98453329700004], [-91.96100179199999, 40.98440537000005], [-91.96111966599995, 40.98428747500003], [-91.96126659499998, 40.98420227200006], [-91.96147302199995, 40.98412434100004], [-91.96270046299998, 40.98390703300004]]]}] | 
| 0           | 644d1a80-86a2-4115-8edf-a9973a994bf2 | S001920275N     | 53.926367999999996527549228630959987640380859375          | 53.93613099999999604960976284928619861602783203125           | STATE OF IOWA, IA 92 E TO STATE OF IOWA, I 29 N                         |           | 268      | [null, 41.22130059800003, -95.83115683199998, null, false, {paths=[[[-95.83115683199998, 41.22130059800003], [-95.83120128199994, 41.22143807800006]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 
| 0           | aa6f32a0-3c7a-49c6-ad05-3fbcd9fc1a57 | S001920034E5250 | 0.1995371999999999979014120299325441010296344757080078125 | 0.2362117700000000153348622689009062014520168304443359375    | STATE OF IOWA, US 59 N TO STATE OF IOWA, US 34 E                        |           | 270      | [null, 41.03024472300007, -95.40070867599997, null, false, {paths=[[[-95.40070867599997, 41.03024472300007], [-95.40064016999997, 41.03036120000007], [-95.40057483599998, 41.03042781100004], [-95.40048644199999, 41.03047297400008], [-95.40019448099997, 41.03056732700003]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 
| 0           | f38c384c-d5db-4495-8fc9-7a935b01560e | S001920030E5150 | 0                                                         | 0.0270059999999999987563281678148996434174478054046630859375 | STATE OF IOWA, US 30 E TO CITY OF DENISON, SOUTH 7TH STREET, N          |           | 271      | [null, 42.01244130300006, -95.36358761899999, null, false, {paths=[[[-95.36358761899999, 42.01244130300006], [-95.36363388099994, 42.01240640100008], [-95.36368983899996, 42.01237963400007], [-95.36378366999998, 42.01235460300006], [-95.36406907099996, 42.01230530500004]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 
```