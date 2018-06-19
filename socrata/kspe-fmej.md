# Historic Zoning Districts - 2003

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/historic-zoning-districts-2003-fc2ec) |
| Metadata | [Link](https://data.sfgov.org/api/views/kspe-fmej) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/kspe-fmej/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/kspe-fmej/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | kspe-fmej |
| Name | Historic Zoning Districts - 2003 |
| Category | Geographic Locations and Boundaries |
| Tags | planning, zoning, shapefile |
| Created | 2016-07-28T18:47:05Z |
| Publication Date | 2016-08-19T21:38:24Z |

## Description

Zoning Districts from 2003. Part of the San Francisco Planning Code. Data is a zipped GIS shapefile.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | numeric metric | acres      | acres      | number    | number      |
| No       |                | address1   | address1   | text      | text        |
| No       |                | address2   | address2   | text      | text        |
| Yes      | numeric metric | area_feet  | area_feet  | number    | number      |
| Yes      | numeric metric | bdrms      | bdrms      | number    | number      |
| Yes      | numeric metric | bldgsqft   | bldgsqft   | number    | number      |
| Yes      | series tag     | blklot     | blklot     | text      | text        |
| Yes      | series tag     | block_num  | block_num  | text      | text        |
| Yes      | numeric metric | censustrac | censustrac | number    | number      |
| Yes      | numeric metric | cie        | cie        | number    | number      |
| Yes      | series tag     | from_st    | from_st    | text      | text        |
| Yes      | numeric metric | hectares   | hectares   | number    | number      |
| Yes      | series tag     | heightlimi | heightlimi | text      | text        |
| Yes      | series tag     | landuse    | landuse    | text      | text        |
| Yes      | numeric metric | landval    | landval    | number    | number      |
| Yes      | series tag     | lot_num    | lot_num    | text      | text        |
| Yes      | series tag     | mapblklot  | mapblklot  | text      | text        |
| Yes      | numeric metric | mips       | mips       | number    | number      |
| Yes      | series tag     | mixed_use  | mixed_use  | text      | text        |
| Yes      | series tag     | newneighbo | newneighbo | text      | text        |
| Yes      | numeric metric | newtaz     | newtaz     | number    | number      |
| Yes      | series tag     | ownrname   | ownrname   | text      | text        |
| Yes      | numeric metric | pdr        | pdr        | number    | number      |
| Yes      | numeric metric | perimeter_ | perimeter_ | number    | number      |
| Yes      | series tag     | restype    | restype    | text      | text        |
| Yes      | numeric metric | resunits   | resunits   | number    | number      |
| Yes      | numeric metric | retail     | retail     | number    | number      |
| Yes      | numeric metric | shape_area | shape_area | number    | number      |
| Yes      | numeric metric | shape_len  | shape_len  | number    | number      |
| Yes      | series tag     | sourcethm  | sourcethm  | text      | text        |
| Yes      | numeric metric | stories    | stories    | number    | number      |
| Yes      | series tag     | street     | street     | text      | text        |
| Yes      | numeric metric | strucval   | strucval   | number    | number      |
| Yes      | numeric metric | total_uses | total_uses | number    | number      |
| Yes      | series tag     | to_st      | to_st      | text      | text        |
| Yes      | series tag     | type       | type       | text      | text        |
| Yes      | series tag     | usetype    | usetype    | text      | text        |
| Yes      | numeric metric | yrbuilt    | yrbuilt    | number    | number      |
| Yes      | series tag     | zoning     | zoning     | text      | text        |
| No       |                | geometry   | geometry   | polygon   | polygon     |
| Yes      | series tag     | multigeom  | multigeom  | checkbox  | checkbox    |
```

## Time Field

```ls
Value = 2003
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address1,address2,geometry
```

## Data Commands

```ls
series e:kspe-fmej d:2003-01-01T00:00:00.000Z t:blklot=1868015 t:lot_num=015 t:usetype=D t:mixed_use=RESIDENT t:street=22ND t:newneighbo="Outer Sunset" t:type=AVE t:to_st=1575 t:sourcethm=Luse03.shp t:block_num=1868 t:ownrname="HSU ALEX" t:heightlimi=40-X t:multigeom=false t:from_st=1575 t:landuse=RESIDENT t:mapblklot=1868015 t:zoning=RH-1 t:restype=SINGLE m:landval=234709 m:area_feet=3008.24 m:perimeter_=290.659 m:pdr=0 m:cie=0 m:strucval=58673 m:hectares=0.028 m:shape_area=3008.23905911 m:stories=2 m:bdrms=0 m:total_uses=0 m:newtaz=331 m:shape_len=290.659410932 m:bldgsqft=2065 m:censustrac=326 m:mips=0 m:acres=0.069 m:resunits=2 m:yrbuilt=1911 m:retail=0

series e:kspe-fmej d:2003-01-01T00:00:00.000Z t:blklot=1877036 t:lot_num=036 t:usetype=D t:mixed_use=RESIDENT t:street=32ND t:newneighbo="Outer Sunset" t:type=AVE t:to_st=1558 t:sourcethm=Luse03.shp t:block_num=1877 t:ownrname="TSO GATE & VIVIAN" t:heightlimi=40-X t:multigeom=false t:from_st=1558 t:landuse=RESIDENT t:mapblklot=1877036 t:zoning=RH-1 t:restype=SINGLE m:landval=165361 m:area_feet=3013.29 m:perimeter_=291.063 m:pdr=0 m:cie=0 m:strucval=165361 m:hectares=0.028 m:shape_area=3013.28257099 m:stories=1 m:bdrms=0 m:total_uses=0 m:newtaz=337 m:shape_len=291.062849472 m:bldgsqft=1450 m:censustrac=327 m:mips=0 m:acres=0.069 m:resunits=1 m:yrbuilt=1931 m:retail=0

series e:kspe-fmej d:2003-01-01T00:00:00.000Z t:blklot=1889018U t:lot_num=018U t:usetype=D t:mixed_use=RESIDENT t:street=44TH t:newneighbo="Outer Sunset" t:type=AVE t:to_st=1538 t:sourcethm=Luse03.shp t:block_num=1889 t:ownrname="LORENZETTI GEORGE R&BARBARA C" t:heightlimi=40-X t:multigeom=false t:from_st=1538 t:landuse=RESIDENT t:mapblklot=1889018U t:zoning=RH-1 t:restype=SINGLE m:landval=22041 m:area_feet=3012.82 m:perimeter_=291.026 m:pdr=0 m:cie=0 m:strucval=25165 m:hectares=0.028 m:shape_area=3012.81649489 m:stories=1 m:bdrms=0 m:total_uses=0 m:newtaz=347 m:shape_len=291.025567416 m:bldgsqft=1325 m:censustrac=352 m:mips=0 m:acres=0.069 m:resunits=1 m:yrbuilt=1936 m:retail=0
```

## Meta Commands

```ls
metric m:acres p:long l:acres t:dataTypeName=number

metric m:area_feet p:long l:area_feet t:dataTypeName=number

metric m:bdrms p:long l:bdrms t:dataTypeName=number

metric m:bldgsqft p:long l:bldgsqft t:dataTypeName=number

metric m:censustrac p:long l:censustrac t:dataTypeName=number

metric m:cie p:long l:cie t:dataTypeName=number

metric m:hectares p:long l:hectares t:dataTypeName=number

metric m:landval p:long l:landval t:dataTypeName=number

metric m:mips p:long l:mips t:dataTypeName=number

metric m:newtaz p:long l:newtaz t:dataTypeName=number

metric m:pdr p:long l:pdr t:dataTypeName=number

metric m:perimeter_ p:long l:perimeter_ t:dataTypeName=number

metric m:resunits p:long l:resunits t:dataTypeName=number

metric m:retail p:long l:retail t:dataTypeName=number

metric m:shape_area p:long l:shape_area t:dataTypeName=number

metric m:shape_len p:long l:shape_len t:dataTypeName=number

metric m:stories p:long l:stories t:dataTypeName=number

metric m:strucval p:long l:strucval t:dataTypeName=number

metric m:total_uses p:long l:total_uses t:dataTypeName=number

metric m:yrbuilt p:long l:yrbuilt t:dataTypeName=number

entity e:kspe-fmej l:"Historic Zoning Districts - 2003" t:url=https://data.sfgov.org/api/views/kspe-fmej

property e:kspe-fmej t:meta.view v:id=kspe-fmej v:category="Geographic Locations and Boundaries" v:averageRating=0 v:name="Historic Zoning Districts - 2003"

property e:kspe-fmej t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:kspe-fmej t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:kspe-fmej t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| acres | address1                    | address2                  | area_feet | bdrms | bldgsqft | blklot   | block_num | censustrac | cie | from_st | hectares | heightlimi | landuse  | landval  | lot_num | mapblklot | mips | mixed_use | newneighbo     | newtaz | ownrname                       | pdr | perimeter_ | restype | resunits | retail | shape_area    | shape_len     | sourcethm  | stories | street  | strucval | total_uses | to_st | type | usetype | yrbuilt | zoning | geometry                                                                                                                                                                                                                                              | multigeom | 
| ===== | =========================== | ========================= | ========= | ===== | ======== | ======== | ========= | ========== | === | ======= | ======== | ========== | ======== | ======== | ======= | ========= | ==== | ========= | ============== | ====== | ============================== | === | ========== | ======= | ======== | ====== | ============= | ============= | ========== | ======= | ======= | ======== | ========== | ===== | ==== | ======= | ======= | ====== | ===================================================================================================================================================================================================================================================== | ========= | 
| 0.069 | HSU ALEX                    | 2455 23RD AVE             | 3008.24   | 0.0   | 2065.0   | 1868015  | 1868      | 326.0      | 0.0 | 1575    | 0.028    | 40-X       | RESIDENT | 234709.0 | 015     | 1868015   | 0.0  | RESIDENT  | Outer Sunset   | 331.0  | HSU ALEX                       | 0.0 | 290.659    | SINGLE  | 2        | 0.0    | 3008.23905911 | 290.659410932 | Luse03.shp | 2.0     | 22ND    | 58673.0  | 0.0        | 1575  | AVE  | D       | 1911.0  | RH-1   | POLYGON ((-122.48051328376953 37.758254897444594, -122.48051808431691 37.75832345011276, -122.48010248426516 37.758341783355405, -122.48009768296538 37.758273230689596, -122.48051328376953 37.758254897444594))                                     | false     | 
| 0.069 | TSO GATE & VIVIAN           | 2330 TOYON WAY            | 3013.29   | 0.0   | 1450.0   | 1877036  | 1877      | 327.0      | 0.0 | 1558    | 0.028    | 40-X       | RESIDENT | 165361.0 | 036     | 1877036   | 0.0  | RESIDENT  | Outer Sunset   | 337.0  | TSO GATE & VIVIAN              | 0.0 | 291.063    | SINGLE  | 1        | 0.0    | 3013.28257099 | 291.062849472 | Luse03.shp | 1.0     | 32ND    | 165361.0 | 0.0        | 1558  | AVE  | D       | 1931.0  | RH-1   | POLYGON ((-122.49059393688995 37.7580848365449, -122.49059874786177 37.758153388784976, -122.4901824539309 37.758171787369854, -122.49017764334192 37.75810323511301, -122.49059393688995 37.7580848365449))                                          | false     | 
| 0.069 | LORENZETTI GEORGE R&BARBARA | 1538 44TH AVE             | 3012.82   | 0.0   | 1325.0   | 1889018U | 1889      | 352.0      | 0.0 | 1538    | 0.028    | 40-X       | RESIDENT | 22041.0  | 018U    | 1889018U  | 0.0  | RESIDENT  | Outer Sunset   | 347.0  | LORENZETTI GEORGE R&BARBARA C  | 0.0 | 291.026    | SINGLE  | 1        | 0.0    | 3012.81649489 | 291.025567416 | Luse03.shp | 1.0     | 44TH    | 25165.0  | 0.0        | 1538  | AVE  | D       | 1936.0  | RH-1   | POLYGON ((-122.50306131091304 37.75788418596144, -122.50347753894658 37.75786579159757, -122.50348236179111 37.75793434331379, -122.50306613337476 37.75795273769442, -122.50306131091304 37.75788418596144))                                         | false     | 
| 0.062 | CHOI LEON LEE HANG & ANNIE  | % LEON L H & ANNIE L CHOI | 2700.0    | 0.0   | 1600.0   | 1863021  | 1863      | 303.0      | 0.0 | 1583    | 0.025    | 40-X       | RESIDENT | 109990.0 | 021     | 1863021   | 0.0  | RESIDENT  | Inner Sunset   | 339.0  | CHOI LEON LEE HANG & ANNIE L F | 0.0 | 240.0      | SINGLE  | 1        | 0.0    | 2699.99414321 | 239.999740196 | Luse03.shp | 1.0     | 17TH    | 137496.0 | 0.0        | 1583  | AVE  | D       | 1932.0  | RH-1   | POLYGON ((-122.47504587812622 37.75833367027633, -122.47505163409842 37.758415933721125, -122.47474078728507 37.75842963113354, -122.4747350305213 37.75834736769272, -122.47504587812622 37.75833367027633))                                         | false     | 
| 0.069 | DILLION, SUSAN JEW          | 1065 MALLARD CIRCLE       | 2984.23   | 0.0   | 4140.0   | 1854013A | 1854      | 303.0      | 0.0 | 1575    | 0.028    | 40-X       | RESIDENT | 507193.0 | 013A    | 1854013A  | 0.0  | RESIDENT  | Inner Sunset   | 326.0  | DILLION, SUSAN JEW             | 0.0 | 288.738    | APTS    | 4        | 0.0    | 2984.22702962 | 288.738443798 | Luse03.shp | 2.0     | 08TH    | 273102.0 | 0.0        | 1575  | AVE  | A       | 1968.0  | RH-2   | POLYGON ((-122.46541568433234 37.75891274778229, -122.46541733994579 37.75893645313863, -122.46542047212701 37.75898130103773, -122.46500817761064 37.75899938702351, -122.4650033913299 37.758930833732634, -122.46541568433234 37.75891274778229))  | false     | 
| 0.069 | GALLEN JOHN F & EILEEN C    | 1528 36TH AVE             | 3020.47   | 0.0   | 1825.0   | 1881041  | 1881      | 327.0      | 0.0 | 1528    | 0.028    | 40-X       | RESIDENT | 25165.0  | 041     | 1881041   | 0.0  | RESIDENT  | Judah Corridor | 346.0  | GALLEN JOHN F & EILEEN C       | 0.0 | 291.638    | SINGLE  | 1        | 0.0    | 3020.47246906 | 291.638108457 | Luse03.shp | 1.0     | 36TH    | 41273.0  | 0.0        | 1528  | AVE  | D       | 1932.0  | RH-1   | POLYGON ((-122.49450039260283 37.758433817359204, -122.4949176837034 37.75841540738234, -122.49492249868592 37.75848395944196, -122.4945052072015 37.758502369435654, -122.49450491855953 37.75849825657749, -122.49450039260283 37.758433817359204)) | false     | 
| 0.069 | MISTHOS BARBARA L 1992 TRUS | % BARBARA L MISTHOS       | 3000.0    | 0.0   | 1830.0   | 1885003  | 1885      | 351.0      | 0.0 | 1523    | 0.028    | 40-X       | RESIDENT | 20785.0  | 003     | 1885003   | 0.0  | RESIDENT  | Outer Sunset   | 344.0  | MISTHOS BARBARA L 1992 TRUST   | 0.0 | 290.0      | SINGLE  | 1        | 0.0    | 3000.01224648 | 290.000022791 | Luse03.shp | 1.0     | 39TH    | 38458.0  | 0.0        | 1523  | AVE  | D       | 1947.0  | RH-1   | POLYGON ((-122.49837779511843 37.75836611596509, -122.49879225487868 37.75834781686173, -122.49879707343169 37.75841636876381, -122.49838261217975 37.75843466880396, -122.49837779511843 37.75836611596509))                                         | false     | 
| 0.069 | YOON SOO OK                 | 1567 FUNSTON AVE          | 3025.54   | 0.0   | 1350.0   | 1860A009 | 1860A     | 303.0      | 0.0 | 1567    | 0.028    | 40-X       | RESIDENT | 234702.0 | 009     | 1860A009  | 0.0  | RESIDENT  | Inner Sunset   | 339.0  | YOON SOO OK                    | 0.0 | 292.997    | SINGLE  | 1        | 0.0    | 3025.53578495 | 292.997027703 | Luse03.shp | 1.0     | FUNSTON | 89418.0  | 0.0        | 1567  | AVE  | D       | 1938.0  | RH-1   | POLYGON ((-122.47036604853065 37.75883807473419, -122.47078634872328 37.75881930347683, -122.47078701136516 37.758829904381244, -122.47079067671989 37.75888848072783, -122.47037075136193 37.75890534953941, -122.47036604853065 37.75883807473419)) | false     | 
| 0.069 | GEORGIAN MARVIN B           | 1550 23RD AVE             | 3000.0    | 0.0   | 1600.0   | 1868029  | 1868      | 326.0      | 0.0 | 1550    | 0.028    | 40-X       | RESIDENT | 98167.0  | 029     | 1868029   | 0.0  | RESIDENT  | Outer Sunset   | 331.0  | GEORGIAN MARVIN B              | 0.0 | 290.0      | SINGLE  | 1        | 0.0    | 2999.99575581 | 289.999902891 | Luse03.shp | 1.0     | 23RD    | 133230.0 | 0.0        | 1550  | AVE  | D       | 1967.0  | RH-1   | POLYGON ((-122.4809565562959 37.758647930128824, -122.48096135841236 37.75871648275521, -122.48054689461918 37.75873476688707, -122.48054209288402 37.758666214244, -122.4809565562959 37.758647930128824))                                           | false     | 
| 0.068 | AMY HA KEI YOUNG REVOC TR   | 1535 32ND AVE             | 2978.51   | 0.0   | 1440.0   | 1878001H | 1878      | 327.0      | 0.0 | 1535    | 0.028    | 40-X       | RESIDENT | 362916.0 | 001H    | 1878001H  | 0.0  | RESIDENT  | Outer Sunset   | 337.0  | AMY HA KEI YOUNG REVOC TR      | 0.0 | 288.28     | SINGLE  | 1        | 0.0    | 2978.51477115 | 288.280191306 | Luse03.shp | 1.0     | 32ND    | 241944.0 | 0.0        | 1535  | AVE  | D       | 1935.0  | RH-1   | POLYGON ((-122.49086497935001 37.7584912725826, -122.49127647217666 37.758473130276265, -122.4912812838276 37.7585416833847, -122.49086979059823 37.75855982480682, -122.49086497935001 37.7584912725826))                                            | false     | 
```