# Historic Zoning Districts - Jan 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/historic-zoning-districts-jan-2015-fc127) |
| Metadata | [Link](https://data.sfgov.org/api/views/utj8-tgqr) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/utj8-tgqr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/utj8-tgqr/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | utj8-tgqr |
| Name | Historic Zoning Districts - Jan 2015 |
| Category | Geographic Locations and Boundaries |
| Tags | planning, zoning, shapefile |
| Created | 2016-07-28T17:24:15Z |
| Publication Date | 2016-08-19T21:40:31Z |

## Description

Zoning Districts from Jan 2015. Part of the San Francisco Planning Code. Data is a zipped GIS shapefile.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | districtna | districtna | text      | text        |
| Yes      | numeric metric | shape_area | shape_area | number    | number      |
| Yes      | numeric metric | shape_len  | shape_len  | number    | number      |
| Yes      | series tag     | url        | url        | text      | text        |
| Yes      | series tag     | zoning_sim | zoning_sim | text      | text        |
| No       |                | geometry   | geometry   | polygon   | polygon     |
| Yes      | series tag     | multigeom  | multigeom  | checkbox  | checkbox    |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = geometry
```

## Data Commands

```ls
series e:utj8-tgqr d:2015-01-01T00:00:00.000Z t:multigeom=false t:zoning_sim=NC-3 t:districtna="NEIGHBORHOOD COMMERCIAL, MODERATE SCALE" t:url="http://www.amlegal.com/nxt/gateway.dll/California/planning/article7neighborhoodcommercialdistricts?f=templates$fn=default.htm$3.0$vid=amlegal:sanfrancisco_ca$anc=JD_712.1" m:shape_area=13901.1426915 m:shape_len=552.715581654

series e:utj8-tgqr d:2015-01-01T00:00:00.000Z t:multigeom=false t:zoning_sim=NC-3 t:districtna="NEIGHBORHOOD COMMERCIAL, MODERATE SCALE" t:url="http://www.amlegal.com/nxt/gateway.dll/California/planning/article7neighborhoodcommercialdistricts?f=templates$fn=default.htm$3.0$vid=amlegal:sanfrancisco_ca$anc=JD_712.1" m:shape_area=11413.2653614 m:shape_len=602.155213139

series e:utj8-tgqr d:2015-01-01T00:00:00.000Z t:multigeom=false t:zoning_sim=NC-3 t:districtna="NEIGHBORHOOD COMMERCIAL, MODERATE SCALE" t:url="http://www.amlegal.com/nxt/gateway.dll/California/planning/article7neighborhoodcommercialdistricts?f=templates$fn=default.htm$3.0$vid=amlegal:sanfrancisco_ca$anc=JD_712.1" m:shape_area=14482.4919657 m:shape_len=607.84767868
```

## Meta Commands

```ls
metric m:shape_area p:long l:shape_area t:dataTypeName=number

metric m:shape_len p:long l:shape_len t:dataTypeName=number

entity e:utj8-tgqr l:"Historic Zoning Districts - Jan 2015" t:url=https://data.sfgov.org/api/views/utj8-tgqr

property e:utj8-tgqr t:meta.view v:id=utj8-tgqr v:category="Geographic Locations and Boundaries" v:averageRating=0 v:name="Historic Zoning Districts - Jan 2015"

property e:utj8-tgqr t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:utj8-tgqr t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:utj8-tgqr t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| districtna                              | shape_area    | shape_len     | url                                                                                                                                                                        | zoning_sim | geometry                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | multigeom | 
| ======================================= | ============= | ============= | ========================================================================================================================================================================== | ========== | ======================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ========= | 
| NEIGHBORHOOD COMMERCIAL, MODERATE SCALE | 13901.1426915 | 552.715581654 | http://www.amlegal.com/nxt/gateway.dll/California/planning/article7neighborhoodcommercialdistricts?f=templates$fn=default.htm$3.0$vid=amlegal:sanfrancisco_ca$anc=JD_712.1 | NC-3       | POLYGON ((-122.39202280469173 37.7301014042066, -122.39207305656909 37.730045538117935, -122.39216255816332 37.73009625784499, -122.39206769331604 37.730379874595734, -122.39197282661053 37.73066349127509, -122.39167103496672 37.73049246898817, -122.39172128850713 37.73043660303489, -122.39177154081486 37.73038073617703, -122.39182179306995 37.73032487019808, -122.39187204638372 37.73026900417905, -122.39192229959903 37.7302131372371, -122.39197255162748 37.73015727119237, -122.39202280469173 37.7301014042066))                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | false     | 
| NEIGHBORHOOD COMMERCIAL, MODERATE SCALE | 11413.2653614 | 602.155213139 | http://www.amlegal.com/nxt/gateway.dll/California/planning/article7neighborhoodcommercialdistricts?f=templates$fn=default.htm$3.0$vid=amlegal:sanfrancisco_ca$anc=JD_712.1 | NC-3       | POLYGON ((-122.39165098276553 37.73086908939962, -122.39172133761565 37.73079087672262, -122.39188413511351 37.73088313211413, -122.3918499686441 37.730981852307806, -122.39181091982664 37.73109467474961, -122.39178651422978 37.731165187754634, -122.39168889147088 37.73144724331946, -122.39153042313205 37.731357442459704, -122.39173143842234 37.73113397700306, -122.39159069525861 37.731054220487, -122.39152032435719 37.7310143421564, -122.39157057720655 37.730958475389556, -122.39165098276553 37.73086908939962))                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | false     | 
| NEIGHBORHOOD COMMERCIAL, MODERATE SCALE | 14482.4919657 | 607.84767868  | http://www.amlegal.com/nxt/gateway.dll/California/planning/article7neighborhoodcommercialdistricts?f=templates$fn=default.htm$3.0$vid=amlegal:sanfrancisco_ca$anc=JD_712.1 | NC-3       | POLYGON ((-122.39133947496012 37.73168782510997, -122.39143998292303 37.73157609260357, -122.39161079387375 37.73167288804578, -122.39156198192009 37.73181391575538, -122.3915375758738 37.73188442960138, -122.39151316980409 37.73195494434236, -122.3914155461049 37.7322369996259, -122.39117869252914 37.73210277928429, -122.39137970975841 37.73187931447322, -122.39123896669503 37.73179955752861, -122.39128922028675 37.73174369088895, -122.39133947496012 37.73168782510997))                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | false     | 
| NEIGHBORHOOD COMMERCIAL, MODERATE SCALE | 54869.3000022 | 1524.97422258 | http://www.amlegal.com/nxt/gateway.dll/California/planning/article7neighborhoodcommercialdistricts?f=templates$fn=default.htm$3.0$vid=amlegal:sanfrancisco_ca$anc=JD_712.1 | NC-3       | POLYGON ((-122.39187443781078 37.73194729806242, -122.39189753189135 37.73188057590838, -122.39192128853911 37.73181193432798, -122.39194430959232 37.731745422417404, -122.39199615420632 37.731595626544554, -122.39201912756998 37.73152925236588, -122.39204209975838 37.73146287820019, -122.39206507190575 37.73139650402934, -122.39209953004982 37.73129694276333, -122.3921339892588 37.7311973823682, -122.39217979160793 37.731065045406766, -122.39229477027284 37.730732834467084, -122.39264283406312 37.730782068256495, -122.39256448281047 37.731124468864195, -122.39253335004074 37.731260522185266, -122.39251015907236 37.73136186455471, -122.39248696919799 37.73146320780058, -122.39227227954706 37.73142926460635, -122.39225215698734 37.731496089624315, -122.39229540505943 37.73150292739385, -122.39227809316796 37.731570196633974, -122.39222486698975 37.73156178066324, -122.39219872995089 37.73162765505025, -122.39220355720214 37.73162841835889, -122.39218880863488 37.73169609251746, -122.39217030683913 37.73178098795566, -122.39217485716736 37.73178170434362, -122.3921608818245 37.7318475275919, -122.3921461445022 37.73191693911017, -122.39212751668964 37.731914214683556, -122.39211246874495 37.73198234694825, -122.39209729253416 37.73205105804958, -122.39208252038382 37.73211794670338, -122.39215159755615 37.73212870819292, -122.39213766395083 37.73218757245463, -122.39211941510867 37.73226467187729, -122.39209377131904 37.73237301994462, -122.39174453699238 37.732322611816365, -122.39178232873466 37.73221342350206, -122.39180834227936 37.73213826234703, -122.39182837016293 37.732080399756924, -122.39187443781078 37.73194729806242))                                                                                                                                                                                                                                                                                  | false     | 
| NEIGHBORHOOD COMMERCIAL, MODERATE SCALE | 12643.7618017 | 478.416741548 | http://www.amlegal.com/nxt/gateway.dll/California/planning/article7neighborhoodcommercialdistricts?f=templates$fn=default.htm$3.0$vid=amlegal:sanfrancisco_ca$anc=JD_712.1 | NC-3       | POLYGON ((-122.39102797517454 37.73262465078401, -122.39112848487248 37.732512918560516, -122.39128794304534 37.732603279964586, -122.3912393094973 37.73274441007798, -122.39121967277248 37.73280139299206, -122.39119379619716 37.73287648420571, -122.39116791959253 37.73295157631355, -122.39114204182422 37.733026669333924, -122.39082695484903 37.73284811406679, -122.3908772106166 37.73279224849515, -122.39092731839578 37.73273654569229, -122.39097771963361 37.73268051642154, -122.39102797517454 37.73262465078401))                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | false     | 
| INNER SUNSET NEIGHBORHOOD COMMERCIAL    | 23916.0617228 | 678.321169405 | http://www.amlegal.com/nxt/gateway.dll/California/planning/article7neighborhoodcommercialdistricts?f=templates$fn=default.htm$3.0$vid=amlegal:sanfrancisco_ca$anc=JD_730.1 | NCD        | POLYGON ((-122.4682258146295 37.76406556930974, -122.46833807464297 37.764060638599496, -122.46835244716222 37.764266298723896, -122.46835723801165 37.764334851796406, -122.46815862271524 37.7643435758166, -122.46807226894742 37.764347368125456, -122.46798591405995 37.76435116129083, -122.46794273660096 37.76435305739938, -122.46789956029838 37.76435495437399, -122.46781320536935 37.76435874651202, -122.46772685045542 37.764362539487585, -122.4676404966674 37.76436633238103, -122.46753113673245 37.7643711356013, -122.46751197640351 37.76409692227185, -122.46762133593603 37.76409211906907, -122.46770769056494 37.76408832707139, -122.4677940440264 37.764084534128614, -122.46788039861376 37.76408074110362, -122.46796675205759 37.76407694803432, -122.46805310665117 37.76407315578362, -122.46813946007737 37.76406936258782, -122.4682258146295 37.76406556930974))                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | false     | 
| INNER SUNSET NEIGHBORHOOD COMMERCIAL    | 14530.1169591 | 681.205027853 | http://www.amlegal.com/nxt/gateway.dll/California/planning/article7neighborhoodcommercialdistricts?f=templates$fn=default.htm$3.0$vid=amlegal:sanfrancisco_ca$anc=JD_730.1 | NCD        | POLYGON ((-122.46464535304109 37.764429072560176, -122.46464056561062 37.764360519337984, -122.4646302026821 37.76436097415275, -122.4644920352228 37.76436703878101, -122.46431033751063 37.764375012915124, -122.46430076328373 37.76423790644125, -122.46448246063778 37.76422993142086, -122.46462062900144 37.764223867685594, -122.46471734455167 37.764219622201644, -122.46480369945309 37.764215831430526, -122.46513184600808 37.76420142793921, -122.465141421764 37.764338534346436, -122.46481327460529 37.764352937864075, -122.46481806108373 37.76442149199908, -122.46482284981668 37.76449004519439, -122.46473649457367 37.76449383507854, -122.46465014048043 37.76449762578133, -122.46464535304109 37.764429072560176))                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | false     | 
| INNER SUNSET NEIGHBORHOOD COMMERCIAL    | 12304.2466281 | 701.609536562 | http://www.amlegal.com/nxt/gateway.dll/California/planning/article7neighborhoodcommercialdistricts?f=templates$fn=default.htm$3.0$vid=amlegal:sanfrancisco_ca$anc=JD_730.1 | NCD        | POLYGON ((-122.46249936076192 37.76448371972271, -122.46249457530804 37.76441516641401, -122.46216610943345 37.76442973458227, -122.46215927875532 37.76433187675081, -122.46248775628283 37.76431746521374, -122.46257411030079 37.76431367699567, -122.46266046428613 37.76430988781352, -122.46298894050828 37.76429547579961, -122.46299574475668 37.764392936600515, -122.46266727907862 37.76440750616524, -122.46267206469128 37.76447605946699, -122.46267685031283 37.7645446127677, -122.46268163594318 37.76461316606741, -122.46259528383595 37.76461699668424, -122.46250893169608 37.76462082633699, -122.46250414622455 37.76455227303036, -122.46249936076192 37.76448371972271))                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | false     | 
| INNER SUNSET NEIGHBORHOOD COMMERCIAL    | 72167.2530528 | 1081.11524177 | http://www.amlegal.com/nxt/gateway.dll/California/planning/article7neighborhoodcommercialdistricts?f=templates$fn=default.htm$3.0$vid=amlegal:sanfrancisco_ca$anc=JD_730.1 | NCD        | POLYGON ((-122.47072383497466 37.763955820703494, -122.47155475602506 37.763919303121156, -122.47161228090512 37.76474194023254, -122.47119777915576 37.76476015726045, -122.47078135181714 37.764778458196105, -122.47072383497466 37.763955820703494))                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | false     | 
| INNER SUNSET NEIGHBORHOOD COMMERCIAL    | 78286.0280765 | 1683.31969043 | http://www.amlegal.com/nxt/gateway.dll/California/planning/article7neighborhoodcommercialdistricts?f=templates$fn=default.htm$3.0$vid=amlegal:sanfrancisco_ca$anc=JD_730.1 | NCD        | POLYGON ((-122.46715610421722 37.76411255036538, -122.46727018544514 37.764107540711585, -122.4672895553731 37.764384772386066, -122.4671754743649 37.764389806380755, -122.46708912212885 37.764393616867885, -122.46700276872538 37.76439742640989, -122.46687506027492 37.76440306153956, -122.4668798486352 37.764471614689384, -122.46688463813909 37.764540167819284, -122.46688942878659 37.76460872092924, -122.46689421717339 37.76467727407604, -122.46689900670384 37.764745827202894, -122.46690379737784 37.76481438030979, -122.46690858579117 37.764882933453556, -122.46691337534807 37.76495148657737, -122.46691816493772 37.76502004060103, -122.46692295448847 37.765088592821996, -122.46692774409578 37.76515714684358, -122.46693253368804 37.76522569996333, -122.4669373232892 37.76529425308207, -122.46694211289912 37.765362806199796, -122.46694690251796 37.76543135931652, -122.46695169214556 37.76549991243222, -122.46673398487174 37.76550951676042, -122.46675314269348 37.765783730148776, -122.46666678768082 37.76578754034457, -122.46655452556705 37.76579249288342, -122.46653536963478 37.76551828034507, -122.46652579113045 37.765381173178405, -122.46652100190342 37.765312620043986, -122.4665162126853 37.76524406690855, -122.46651142347595 37.765175513772114, -122.46650663427552 37.76510696063465, -122.46650184508384 37.765038407496164, -122.46649705587721 37.76496985345582, -122.46649226672707 37.76490130121618, -122.46648747753814 37.764832747173784, -122.4664778992344 37.7646956408877, -122.46647311009583 37.76462708774314, -122.46646832096603 37.76455853459757, -122.46646353297984 37.76448998143204, -122.46645874386773 37.76442142828445, -122.46643936450872 37.76414402364831, -122.46663797947352 37.76413530252448, -122.46672433304418 37.7641315103653, -122.4668106866299 37.76412771904371, -122.46698339599664 37.764120134371154, -122.4670697495559 37.76411634285979, -122.46715610421722 37.76411255036538)) | false     | 
```