# Historic Zoning Districts - 2002

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/historic-zoning-districts-2002-5c75b) |
| Metadata | [Link](https://data.sfgov.org/api/views/ftvx-vtyc) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/ftvx-vtyc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/ftvx-vtyc/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | ftvx-vtyc |
| Name | Historic Zoning Districts - 2002 |
| Category | Geographic Locations and Boundaries |
| Tags | planning, zoning, shapefile, gis |
| Created | 2016-07-28T18:37:15Z |
| Publication Date | 2016-08-19T21:38:04Z |

## Description

Zoning Districts from 2002. Part of the San Francisco Planning Code. Data is a zipped GIS shapefile.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| No       |                | address1   | address1   | text      | text        |
| No       |                | address2   | address2   | text      | text        |
| Yes      | numeric metric | bdrms      | bdrms      | number    | number      |
| Yes      | numeric metric | bldgsqft   | bldgsqft   | number    | number      |
| Yes      | series tag     | blklot     | blklot     | text      | text        |
| Yes      | series tag     | block_num  | block_num  | text      | text        |
| Yes      | numeric metric | censustrac | censustrac | number    | number      |
| Yes      | numeric metric | cie        | cie        | number    | number      |
| Yes      | series tag     | from_st    | from_st    | text      | text        |
| Yes      | numeric metric | gisdata_zo | gisdata_zo | number    | number      |
| Yes      | series tag     | heightlimi | heightlimi | text      | text        |
| Yes      | series tag     | landuse    | landuse    | text      | text        |
| Yes      | numeric metric | landval    | landval    | number    | number      |
| Yes      | series tag     | lot_num    | lot_num    | text      | text        |
| Yes      | series tag     | mapblklot  | mapblklot  | text      | text        |
| Yes      | numeric metric | mips       | mips       | number    | number      |
| Yes      | series tag     | mixed_use  | mixed_use  | text      | text        |
| Yes      | series tag     | neighborho | neighborho | text      | text        |
| Yes      | series tag     | newneighbo | newneighbo | text      | text        |
| Yes      | numeric metric | newtaz     | newtaz     | number    | number      |
| Yes      | series tag     | ownrname   | ownrname   | text      | text        |
| Yes      | numeric metric | pdr        | pdr        | number    | number      |
| Yes      | numeric metric | rescom_uni | rescom_uni | number    | number      |
| Yes      | series tag     | restype    | restype    | text      | text        |
| Yes      | numeric metric | resunits   | resunits   | number    | number      |
| Yes      | numeric metric | retail     | retail     | number    | number      |
| Yes      | numeric metric | shape_area | shape_area | number    | number      |
| Yes      | numeric metric | shape_len  | shape_len  | number    | number      |
| Yes      | numeric metric | stories    | stories    | number    | number      |
| Yes      | series tag     | street     | street     | text      | text        |
| Yes      | numeric metric | strucval   | strucval   | number    | number      |
| Yes      | numeric metric | totalvalue | totalvalue | number    | number      |
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
Value = 2002
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address1,address2,geometry
```

## Data Commands

```ls
series e:ftvx-vtyc d:2002-01-01T00:00:00.000Z t:neighborho="Rest of the City" t:blklot=1857016G t:lot_num=016G t:usetype=D t:mixed_use=RESIDENT t:street=12TH t:newneighbo="Inner Sunset" t:type=AVE t:to_st=1594 t:block_num=1857 t:ownrname="LOO JOSEPHINE S" t:heightlimi=40-X t:multigeom=false t:from_st=1594 t:landuse=RESIDENT t:mapblklot=1857016G t:zoning=RH-2 t:restype=SINGLE m:landval=217104 m:pdr=0 m:strucval=82146 m:totalvalue=94 m:cie=0 m:shape_area=3190.35215019 m:bdrms=0 m:stories=1 m:rescom_uni=1 m:total_uses=0 m:gisdata_zo=0 m:newtaz=326 m:shape_len=242.448185863 m:bldgsqft=1581 m:censustrac=303 m:mips=0 m:resunits=1 m:yrbuilt=1927 m:retail=0

series e:ftvx-vtyc d:2002-01-01T00:00:00.000Z t:neighborho="Rest of the City" t:blklot=1868015 t:lot_num=015 t:usetype=D t:mixed_use=RESIDENT t:street=22ND t:newneighbo="Outer Sunset" t:type=AVE t:to_st=1575 t:block_num=1868 t:ownrname="HSU ALEX" t:heightlimi=40-X t:multigeom=false t:from_st=1575 t:landuse=RESIDENT t:mapblklot=1868015 t:zoning=RH-1 t:restype=SINGLE m:landval=234709 m:pdr=0 m:strucval=58673 m:totalvalue=98 m:cie=0 m:shape_area=3008.23563836 m:bdrms=0 m:stories=2 m:rescom_uni=2 m:total_uses=0 m:gisdata_zo=0 m:newtaz=331 m:shape_len=290.65909432 m:bldgsqft=2065 m:censustrac=326 m:mips=0 m:resunits=2 m:yrbuilt=1911 m:retail=0

series e:ftvx-vtyc d:2002-01-01T00:00:00.000Z t:neighborho="Rest of the City" t:blklot=1887001L t:lot_num=001L t:usetype=D t:mixed_use=RESIDENT t:street=41ST t:newneighbo="Outer Sunset" t:type=AVE t:to_st=1543 t:block_num=1887 t:ownrname="LEE STANLEY & WONG-LEE TINA" t:heightlimi=40-X t:multigeom=false t:from_st=1543 t:landuse=RESIDENT t:mapblklot=1887001L t:zoning=RH-1 t:restype=SINGLE m:landval=168679 m:pdr=0 m:strucval=112451 m:totalvalue=94 m:cie=0 m:shape_area=2999.99720355 m:bdrms=0 m:stories=1 m:rescom_uni=1 m:total_uses=0 m:gisdata_zo=0 m:newtaz=344 m:shape_len=290.000022853 m:bldgsqft=1150 m:censustrac=351 m:mips=0 m:resunits=1 m:yrbuilt=1938 m:retail=0
```

## Meta Commands

```ls
metric m:bdrms p:long l:bdrms t:dataTypeName=number

metric m:bldgsqft p:long l:bldgsqft t:dataTypeName=number

metric m:censustrac p:long l:censustrac t:dataTypeName=number

metric m:cie p:long l:cie t:dataTypeName=number

metric m:gisdata_zo p:long l:gisdata_zo t:dataTypeName=number

metric m:landval p:long l:landval t:dataTypeName=number

metric m:mips p:long l:mips t:dataTypeName=number

metric m:newtaz p:long l:newtaz t:dataTypeName=number

metric m:pdr p:long l:pdr t:dataTypeName=number

metric m:rescom_uni p:long l:rescom_uni t:dataTypeName=number

metric m:resunits p:long l:resunits t:dataTypeName=number

metric m:retail p:long l:retail t:dataTypeName=number

metric m:shape_area p:long l:shape_area t:dataTypeName=number

metric m:shape_len p:long l:shape_len t:dataTypeName=number

metric m:stories p:long l:stories t:dataTypeName=number

metric m:strucval p:long l:strucval t:dataTypeName=number

metric m:totalvalue p:long l:totalvalue t:dataTypeName=number

metric m:total_uses p:long l:total_uses t:dataTypeName=number

metric m:yrbuilt p:long l:yrbuilt t:dataTypeName=number

entity e:ftvx-vtyc l:"Historic Zoning Districts - 2002" t:url=https://data.sfgov.org/api/views/ftvx-vtyc

property e:ftvx-vtyc t:meta.view v:id=ftvx-vtyc v:category="Geographic Locations and Boundaries" v:averageRating=0 v:name="Historic Zoning Districts - 2002"

property e:ftvx-vtyc t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:ftvx-vtyc t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:ftvx-vtyc t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| address1                    | address2                  | bdrms | bldgsqft | blklot   | block_num | censustrac | cie | from_st | gisdata_zo | heightlimi | landuse  | landval  | lot_num | mapblklot | mips | mixed_use | neighborho       | newneighbo     | newtaz | ownrname                       | pdr | rescom_uni | restype | resunits | retail | shape_area    | shape_len     | stories | street  | strucval | totalvalue | total_uses | to_st | type | usetype | yrbuilt | zoning | geometry                                                                                                                                                                                                                                              | multigeom | 
| =========================== | ========================= | ===== | ======== | ======== | ========= | ========== | === | ======= | ========== | ========== | ======== | ======== | ======= | ========= | ==== | ========= | ================ | ============== | ====== | ============================== | === | ========== | ======= | ======== | ====== | ============= | ============= | ======= | ======= | ======== | ========== | ========== | ===== | ==== | ======= | ======= | ====== | ===================================================================================================================================================================================================================================================== | ========= | 
| LOO JOSEPHINE S             | 1594 12TH AVE             | 0.0   | 1581.0   | 1857016G | 1857      | 303.0      | 0.0 | 1594    | 0.0        | 40-X       | RESIDENT | 217104.0 | 016G    | 1857016G  | 0.0  | RESIDENT  | Rest of the City | Inner Sunset   | 326.0  | LOO JOSEPHINE S                | 0.0 | 1.0        | SINGLE  | 1        | 0.0    | 3190.35215019 | 242.448185863 | 1.0     | 12TH    | 82146.0  | 94.0       | 0.0        | 1594  | AVE  | D       | 1927.0  | RH-2   | POLYGON ((-122.46873254097534 37.75843059481853, -122.46901783169062 37.758418053101245, -122.46902523378604 37.75852395822531, -122.46873994304732 37.758536514373574, -122.46873254097534 37.75843059481853))                                       | false     | 
| HSU ALEX                    | 2455 23RD AVE             | 0.0   | 2065.0   | 1868015  | 1868      | 326.0      | 0.0 | 1575    | 0.0        | 40-X       | RESIDENT | 234709.0 | 015     | 1868015   | 0.0  | RESIDENT  | Rest of the City | Outer Sunset   | 331.0  | HSU ALEX                       | 0.0 | 2.0        | SINGLE  | 2        | 0.0    | 3008.23563836 | 290.65909432  | 2.0     | 22ND    | 58673.0  | 98.0       | 0.0        | 1575  | AVE  | D       | 1911.0  | RH-1   | POLYGON ((-122.48051328263489 37.75825489746366, -122.48051808431691 37.75832345011276, -122.48010248426516 37.758341783355405, -122.48009768296538 37.758273230689596, -122.48051328263489 37.75825489746366))                                       | false     | 
| LEE STANLEY & WONG-LEE TINA | 1543 41ST AVE             | 0.0   | 1150.0   | 1887001L | 1887      | 351.0      | 0.0 | 1543    | 0.0        | 40-X       | RESIDENT | 168679.0 | 001L    | 1887001L  | 0.0  | RESIDENT  | Rest of the City | Outer Sunset   | 344.0  | LEE STANLEY & WONG-LEE TINA    | 0.0 | 1.0        | SINGLE  | 1        | 0.0    | 2999.99720355 | 290.000022853 | 1.0     | 41ST    | 112451.0 | 94.0       | 0.0        | 1543  | AVE  | D       | 1938.0  | RH-1   | POLYGON ((-122.5004964495033 37.75792873472944, -122.50091090743652 37.757910428156094, -122.50091572791591 37.75797897997671, -122.50050126960146 37.757997286566805, -122.5004964495033 37.75792873472944))                                         | false     | 
| TSO GATE & VIVIAN           | 2330 TOYON WAY            | 0.0   | 1450.0   | 1877036  | 1877      | 327.0      | 0.0 | 1558    | 0.0        | 40-X       | RESIDENT | 165361.0 | 036     | 1877036   | 0.0  | RESIDENT  | Rest of the City | Outer Sunset   | 337.0  | TSO GATE & VIVIAN              | 0.0 | 1.0        | SINGLE  | 1        | 0.0    | 3013.28257099 | 291.062849472 | 1.0     | 32ND    | 165361.0 | 110.0      | 0.0        | 1558  | AVE  | D       | 1931.0  | RH-1   | POLYGON ((-122.49059393688995 37.7580848365449, -122.49059874786177 37.758153388784976, -122.4901824539309 37.758171787369854, -122.49017764334192 37.75810323511301, -122.49059393688995 37.7580848365449))                                          | false     | 
| LORENZETTI GEORGE R&BARBARA | 1538 44TH AVE             | 0.0   | 1325.0   | 1889018U | 1889      | 352.0      | 0.0 | 1538    | 0.0        | 40-X       | RESIDENT | 22041.0  | 018U    | 1889018U  | 0.0  | RESIDENT  | Rest of the City | Outer Sunset   | 347.0  | LORENZETTI GEORGE R&BARBARA C  | 0.0 | 1.0        | SINGLE  | 1        | 0.0    | 3012.81649489 | 291.025567416 | 1.0     | 44TH    | 25165.0  | 16.0       | 0.0        | 1538  | AVE  | D       | 1936.0  | RH-1   | POLYGON ((-122.50306131091304 37.75788418596144, -122.50347753894658 37.75786579159757, -122.50348236179111 37.75793434331379, -122.50306613337476 37.75795273769442, -122.50306131091304 37.75788418596144))                                         | false     | 
| CHOI LEON LEE HANG & ANNIE  | % LEON L H & ANNIE L CHOI | 0.0   | 1600.0   | 1863021  | 1863      | 303.0      | 0.0 | 1583    | 0.0        | 40-X       | RESIDENT | 109990.0 | 021     | 1863021   | 0.0  | RESIDENT  | Rest of the City | Inner Sunset   | 339.0  | CHOI LEON LEE HANG & ANNIE L F | 0.0 | 1.0        | SINGLE  | 1        | 0.0    | 2699.99855467 | 240.000056804 | 1.0     | 17TH    | 137496.0 | 92.0       | 0.0        | 1583  | AVE  | D       | 1932.0  | RH-1   | POLYGON ((-122.47504587812622 37.75833367027633, -122.47505163409842 37.758415933721125, -122.47474078615038 37.75842963115255, -122.4747350305213 37.75834736769272, -122.47504587812622 37.75833367027633))                                         | false     | 
| DILLION, SUSAN JEW          | 1065 MALLARD CIRCLE       | 0.0   | 4140.0   | 1854013A | 1854      | 303.0      | 0.0 | 1575    | 0.0        | 40-X       | RESIDENT | 507193.0 | 013A    | 1854013A  | 0.0  | RESIDENT  | Rest of the City | Inner Sunset   | 326.0  | DILLION, SUSAN JEW             | 0.0 | 4.0        | APTS    | 4        | 0.0    | 2984.23179801 | 288.738782968 | 2.0     | 08TH    | 273102.0 | 261.0      | 0.0        | 1575  | AVE  | A       | 1968.0  | RH-2   | POLYGON ((-122.46541568433234 37.75891274778229, -122.46541733994579 37.75893645313863, -122.46542047212701 37.75898130103773, -122.46500817761064 37.75899938702351, -122.46500339019526 37.75893083375155, -122.46541568433234 37.75891274778229))  | false     | 
| GALLEN JOHN F & EILEEN C    | 1528 36TH AVE             | 0.0   | 1825.0   | 1881041  | 1881      | 327.0      | 0.0 | 1528    | 0.0        | 40-X       | RESIDENT | 25165.0  | 041     | 1881041   | 0.0  | RESIDENT  | Rest of the City | Judah Corridor | 346.0  | GALLEN JOHN F & EILEEN C       | 0.0 | 1.0        | SINGLE  | 1        | 0.0    | 3020.47246906 | 291.638108457 | 1.0     | 36TH    | 41273.0  | 22.0       | 0.0        | 1528  | AVE  | D       | 1932.0  | RH-1   | POLYGON ((-122.49450039260283 37.758433817359204, -122.4949176837034 37.75841540738234, -122.49492249868592 37.75848395944196, -122.4945052072015 37.758502369435654, -122.49450491855953 37.75849825657749, -122.49450039260283 37.758433817359204)) | false     | 
| MISTHOS BARBARA L 1992 TRUS | % BARBARA L MISTHOS       | 0.0   | 1830.0   | 1885003  | 1885      | 351.0      | 0.0 | 1523    | 0.0        | 40-X       | RESIDENT | 20785.0  | 003     | 1885003   | 0.0  | RESIDENT  | Rest of the City | Outer Sunset   | 344.0  | MISTHOS BARBARA L 1992 TRUST   | 0.0 | 1.0        | SINGLE  | 1        | 0.0    | 3000.01701811 | 290.000361961 | 1.0     | 39TH    | 38458.0  | 20.0       | 0.0        | 1523  | AVE  | D       | 1947.0  | RH-1   | POLYGON ((-122.49837779398374 37.75836611598434, -122.49879225487868 37.75834781686173, -122.49879707343169 37.75841636876381, -122.49838261217975 37.75843466880396, -122.49837779398374 37.75836611598434))                                         | false     | 
| YOON SOO OK                 | 1567 FUNSTON AVE          | 0.0   | 1350.0   | 1860A009 | 1860A     | 303.0      | 0.0 | 1567    | 0.0        | 40-X       | RESIDENT | 234702.0 | 009     | 1860A009  | 0.0  | RESIDENT  | Rest of the City | Inner Sunset   | 339.0  | YOON SOO OK                    | 0.0 | 1.0        | SINGLE  | 1        | 0.0    | 3025.55176391 | 292.997027956 | 1.0     | FUNSTON | 89418.0  | 107.0      | 0.0        | 1567  | AVE  | D       | 1938.0  | RH-1   | POLYGON ((-122.47036604853065 37.75883807473419, -122.47078634872328 37.75881930347683, -122.47078701136516 37.758829904381244, -122.47079067558526 37.75888848074682, -122.47037075138581 37.75890535044023, -122.47036604853065 37.75883807473419)) | false     | 
```