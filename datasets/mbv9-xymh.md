# SDOT Potential Street Closures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-potential-street-closures) |
| Metadata | [Link](https://data.seattle.gov/api/views/mbv9-xymh) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/mbv9-xymh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/mbv9-xymh/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | mbv9-xymh |
| Name | SDOT Potential Street Closures |
| Attribution | Seattle Dept of Transportation, multiple Divisions. |
| Category | Transportation |
| Tags | impacts, sdot, street, street use, street closures, closures |
| Created | 2016-04-21T15:56:52Z |
| Publication Date | 2016-04-21T17:15:21Z |

## Description

Displays driveable public streets with in the city limits that have the potential for closure due to some permitted work that is being conducted.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type  | Render Type |
| ======== | ============== | ============== | ============== | ========== | =========== |
| Yes      | series tag     | objectid       | OBJECTID       | text       | number      |
| Yes      | numeric metric | compkey        | COMPKEY        | number     | number      |
| Yes      | series tag     | comptype       | COMPTYPE       | text       | number      |
| Yes      | series tag     | unitid         | UNITID         | text       | text        |
| Yes      | series tag     | unitid2        | UNITID2        | text       | text        |
| Yes      | series tag     | unitidsort     | UNITIDSORT     | text       | text        |
| Yes      | series tag     | unitdesc       | UNITDESC       | text       | text        |
| Yes      | series tag     | stname_ord     | STNAME_ORD     | text       | text        |
| Yes      | series tag     | onstreet       | ONSTREET       | text       | text        |
| Yes      | series tag     | xstrlo         | XSTRLO         | text       | text        |
| Yes      | series tag     | xstrhi         | XSTRHI         | text       | text        |
| Yes      | numeric metric | artclass       | ARTCLASS       | number     | number      |
| Yes      | series tag     | artdescript    | ARTDESCRIPT    | text       | text        |
| Yes      | series tag     | owner          | OWNER          | text       | text        |
| Yes      | series tag     | status         | STATUS         | text       | text        |
| Yes      | numeric metric | blocknbr       | BLOCKNBR       | number     | number      |
| Yes      | numeric metric | speedlimit     | SPEEDLIMIT     | number     | number      |
| Yes      | series tag     | segdir         | SEGDIR         | text       | text        |
| Yes      | series tag     | oneway         | ONEWAY         | text       | text        |
| Yes      | series tag     | onewaydir      | ONEWAYDIR      | text       | text        |
| Yes      | series tag     | flow           | FLOW           | text       | text        |
| Yes      | numeric metric | seglength      | SEGLENGTH      | number     | number      |
| Yes      | numeric metric | surfacewidth   | SURFACEWIDTH   | number     | number      |
| Yes      | series tag     | surfacetype_1  | SURFACETYPE_1  | text       | text        |
| No       |                | surfacedate_1  | SURFACEDATE_1  | date       | date        |
| Yes      | series tag     | surfacetype_2  | SURFACETYPE_2  | text       | text        |
| No       |                | surfacedate_2  | SURFACEDATE_2  | date       | date        |
| Yes      | series tag     | intrlo         | INTRLO         | text       | text        |
| Yes      | series tag     | dirlo          | DIRLO          | text       | text        |
| Yes      | numeric metric | intkeylo       | INTKEYLO       | number     | number      |
| Yes      | series tag     | intrhi         | INTRHI         | text       | text        |
| Yes      | series tag     | dirhi          | DIRHI          | text       | text        |
| Yes      | numeric metric | intkeyhi       | INTKEYHI       | number     | number      |
| Yes      | numeric metric | gis_mid_x      | GIS_MID_X      | number     | number      |
| Yes      | numeric metric | gis_mid_y      | GIS_MID_Y      | number     | number      |
| Yes      | series tag     | sgndbkroute    | SGNDBKROUTE    | text       | text        |
| Yes      | series tag     | nghbrhdgrnwy   | NGHBRHDGRNWY   | text       | text        |
| Yes      | series tag     | nationhwysys   | NATIONHWYSYS   | text       | text        |
| Yes      | series tag     | streettype     | STREETTYPE     | text       | text        |
| Yes      | series tag     | mjtrk_str_flag | MJTRK_STR_FLAG | text       | text        |
| Yes      | numeric metric | pvmtcondindx1  | PVMTCONDINDX1  | number     | number      |
| Yes      | numeric metric | pvmtcondindx2  | PVMTCONDINDX2  | number     | number      |
| Yes      | numeric metric | tranclass      | TRANCLASS      | number     | number      |
| Yes      | series tag     | trandescript   | TRANDESCRIPT   | text       | text        |
| No       |                | shape          | Shape          | geospatial | geospatial  |
| No       |                | year           | YEAR           | number     | text        |
| Yes      | time           | editdate       | EDITDATE       | date       | date        |
| Yes      | numeric metric | shape_length   | Shape_Length   | number     | number      |
```

## Time Field

```ls
Value = editdate
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = surfacedate_2,shape,surfacedate_1,year
```

## Data Commands

```ls
series e:mbv9-xymh d:2014-10-22T00:00:00.000Z t:shape.longitude=-122.38856226299998 t:onstreet="SW OTHELLO ST" t:segdir=W t:unitid2=0440 t:dirlo=W t:comptype=68 t:artdescript="Not Designated" t:nationhwysys=N t:stname_ord="SW OTHELLO ST" t:unitdesc="SW OTHELLO ST BETWEEN 44TH W AVE SW AND WOODSIDE PL SW" t:unitid=18075 t:shape.needs_recoding=false t:oneway=N t:unitidsort=180750440 t:shape.latitude=47.53820067800007 t:dirhi=E t:surfacetype_1=PCC t:sgndbkroute=N t:status=INSVC t:intrlo="44TH AVE SW AND SW OTHELLO W ST" t:intrhi="WOODSIDE PL SW AND SW OTHELLO ST" t:xstrlo="44TH W AVE SW" t:xstrhi="WOODSIDE PL SW" t:trandescript="NOT DESIGNATED" t:nghbrhdgrnwy=N t:objectid=1 m:pvmtcondindx2=0 m:intkeyhi=33902 m:pvmtcondindx1=58 m:gis_mid_x=1256181.02569912 m:artclass=0 m:intkeylo=33903 m:surfacewidth=25 m:blocknbr=4400 m:compkey=22697 m:gis_mid_y=200162.59622502 m:shape_length=229.135998299155 m:seglength=229 m:tranclass=0 m:speedlimit=0

series e:mbv9-xymh d:2014-10-22T00:00:00.000Z t:shape.longitude=-122.26579934999995 t:onstreet="S GRATTAN ST" t:segdir=E t:unitid2=0535 t:dirlo=E t:comptype=68 t:artdescript="Not Designated" t:nationhwysys=N t:stname_ord="S GRATTAN ST" t:unitdesc="S GRATTAN ST BETWEEN SEWARD PARK AVE S AND 54TH W AVE S" t:unitid=16080 t:shape.needs_recoding=false t:oneway=N t:unitidsort=160800535 t:shape.latitude=47.52851280500005 t:dirhi=W t:surfacetype_1=ST t:sgndbkroute=N t:status=INSVC t:intrlo="SEWARD PARK AVE S AND S GRATTAN ST" t:intrhi="54TH AVE S AND S GRATTAN W ST" t:xstrlo="SEWARD PARK AVE S" t:xstrhi="54TH W AVE S" t:trandescript="NOT DESIGNATED" t:nghbrhdgrnwy=N t:objectid=2 m:pvmtcondindx2=0 m:intkeyhi=35421 m:pvmtcondindx1=0 m:gis_mid_x=1286614.44512229 m:artclass=0 m:intkeylo=38515 m:surfacewidth=0 m:blocknbr=5300 m:compkey=20160 m:gis_mid_y=196077.96402884 m:shape_length=149.17705526004147 m:seglength=149 m:tranclass=0 m:speedlimit=0

series e:mbv9-xymh d:2014-10-22T00:00:00.000Z t:shape.longitude=-122.33945069199996 t:onstreet="OLSON PL SW" t:segdir=S t:unitid2=0945 t:dirlo=S t:comptype=68 t:artdescript="Principal Arterial" t:nationhwysys=Y t:stname_ord="OLSON PL SW" t:unitdesc="OLSON PL SW BETWEEN SW CAMBRIDGE PL AND SW ROXBURY ST" t:unitid=08955 t:shape.needs_recoding=false t:streettype=Regional t:oneway=N t:unitidsort=089550945 t:shape.latitude=47.51853575100006 t:dirhi=N t:surfacetype_1=PCC t:sgndbkroute=N t:status=INSVC t:intrlo="OLSON PL SW AND SW CAMBRIDGE PL" t:intrhi="OLSON PL SW AND SW ROXBURY ST" t:xstrlo="SW CAMBRIDGE PL" t:xstrhi="SW ROXBURY ST" t:trandescript="MAJOR TRANSIT ROUTE" t:nghbrhdgrnwy=N t:objectid=3 m:pvmtcondindx2=0 m:intkeyhi=34984 m:pvmtcondindx1=79 m:gis_mid_x=1268187.55051142 m:artclass=1 m:intkeylo=34988 m:surfacewidth=56 m:blocknbr=9400 m:compkey=12054 m:gis_mid_y=192559.46405724 m:shape_length=490.470778228786 m:seglength=490 m:tranclass=2 m:speedlimit=35
```

## Meta Commands

```ls
metric m:compkey p:integer l:COMPKEY d:COMPKEY t:dataTypeName=number

metric m:artclass p:integer l:ARTCLASS d:ARTCLASS t:dataTypeName=number

metric m:blocknbr p:integer l:BLOCKNBR d:BLOCKNBR t:dataTypeName=number

metric m:speedlimit p:integer l:SPEEDLIMIT d:SPEEDLIMIT t:dataTypeName=number

metric m:seglength p:integer l:SEGLENGTH d:SEGLENGTH t:dataTypeName=number

metric m:surfacewidth p:integer l:SURFACEWIDTH d:SURFACEWIDTH t:dataTypeName=number

metric m:intkeylo p:integer l:INTKEYLO d:INTKEYLO t:dataTypeName=number

metric m:intkeyhi p:integer l:INTKEYHI d:INTKEYHI t:dataTypeName=number

metric m:gis_mid_x p:decimal l:GIS_MID_X d:GIS_MID_X t:dataTypeName=number

metric m:gis_mid_y p:decimal l:GIS_MID_Y d:GIS_MID_Y t:dataTypeName=number

metric m:pvmtcondindx1 p:integer l:PVMTCONDINDX1 d:PVMTCONDINDX1 t:dataTypeName=number

metric m:pvmtcondindx2 p:integer l:PVMTCONDINDX2 d:PVMTCONDINDX2 t:dataTypeName=number

metric m:tranclass p:integer l:TRANCLASS d:TRANCLASS t:dataTypeName=number

metric m:shape_length p:decimal l:Shape_Length d:Shape_Length t:dataTypeName=number

entity e:mbv9-xymh l:"SDOT Potential Street Closures" t:attribution="Seattle Dept of Transportation, multiple Divisions." t:url=https://data.seattle.gov/api/views/mbv9-xymh

property e:mbv9-xymh t:meta.view v:id=mbv9-xymh v:category=Transportation v:averageRating=0 v:name="SDOT Potential Street Closures" v:attribution="Seattle Dept of Transportation, multiple Divisions."

property e:mbv9-xymh t:meta.view.license v:name="Public Domain"

property e:mbv9-xymh t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:mbv9-xymh t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | compkey | comptype | unitid | unitid2 | unitidsort | unitdesc                                                   | stname_ord       | onstreet         | xstrlo            | xstrhi               | artclass | artdescript        | owner | status | blocknbr | speedlimit | segdir | oneway | onewaydir | flow | seglength | surfacewidth | surfacetype_1 | surfacedate_1 | surfacetype_2 | surfacedate_2 | intrlo                             | dirlo | intkeylo | intrhi                                | dirhi | intkeyhi | gis_mid_x                                | gis_mid_y                                  | sgndbkroute | nghbrhdgrnwy | nationhwysys | streettype | mjtrk_str_flag | pvmtcondindx1 | pvmtcondindx2 | tranclass | trandescript        | shape                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | year | editdate   | shape_length                                      | 
| ======== | ======= | ======== | ====== | ======= | ========== | ========================================================== | ================ | ================ | ================= | ==================== | ======== | ================== | ===== | ====== | ======== | ========== | ====== | ====== | ========= | ==== | ========= | ============ | ============= | ============= | ============= | ============= | ================================== | ===== | ======== | ===================================== | ===== | ======== | ======================================== | ========================================== | =========== | ============ | ============ | ========== | ============== | ============= | ============= | ========= | =================== | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | ==== | ========== | ================================================= | 
| 1        | 22697   | 68       | 18075  | 0440    | 180750440  | SW OTHELLO ST BETWEEN 44TH W AVE SW AND WOODSIDE PL SW     | SW OTHELLO ST    | SW OTHELLO ST    | 44TH W AVE SW     | WOODSIDE PL SW       | 0        | Not Designated     |       | INSVC  | 4400     | 0          | W      | N      |           |      | 229       | 25           | PCC           | 1392076800    |               |               | 44TH AVE SW AND SW OTHELLO W ST    | W     | 33903    | WOODSIDE PL SW AND SW OTHELLO ST      | E     | 33902    | 1256181.0256991200149059295654296875     | 200162.5962250200100243091583251953125     | N           | N            | N            |            |                | 58            | 0             | 0         | NOT DESIGNATED      | [null, 47.53820067800007, -122.38856226299998, null, false, {paths=[[[-122.38856226299998, 47.53820067800007], [-122.38930279599998, 47.538008226000045], [-122.38943723799997, 47.53800898500003]]]}]                                                                                                                                                                                                                                                                                                        | 2014 | 1413936000 | 229.13599829915500549759599380195140838623046875  | 
| 2        | 20160   | 68       | 16080  | 0535    | 160800535  | S GRATTAN ST BETWEEN SEWARD PARK AVE S AND 54TH W AVE S    | S GRATTAN ST     | S GRATTAN ST     | SEWARD PARK AVE S | 54TH W AVE S         | 0        | Not Designated     |       | INSVC  | 5300     | 0          | E      | N      |           |      | 149       | 0            | ST            |               |               |               | SEWARD PARK AVE S AND S GRATTAN ST | E     | 38515    | 54TH AVE S AND S GRATTAN W ST         | W     | 35421    | 1286614.4451222899369895458221435546875  | 196077.9640288400114513933658599853515625  | N           | N            | N            |            |                | 0             | 0             | 0         | NOT DESIGNATED      | [null, 47.52851280500005, -122.26579934999995, null, false, {paths=[[[-122.26579934999995, 47.52851280500005], [-122.26519552799999, 47.528512731000035]]]}]                                                                                                                                                                                                                                                                                                                                                  | 2014 | 1413936000 | 149.17705526004147031926549971103668212890625     | 
| 3        | 12054   | 68       | 08955  | 0945    | 089550945  | OLSON PL SW BETWEEN SW CAMBRIDGE PL AND SW ROXBURY ST      | OLSON PL SW      | OLSON PL SW      | SW CAMBRIDGE PL   | SW ROXBURY ST        | 1        | Principal Arterial |       | INSVC  | 9400     | 35         | S      | N      |           |      | 490       | 56           | PCC           | 1374710400    |               |               | OLSON PL SW AND SW CAMBRIDGE PL    | S     | 34988    | OLSON PL SW AND SW ROXBURY ST         | N     | 34984    | 1268187.55051142000593245029449462890625 | 192559.4640572399948723614215850830078125  | N           | N            | Y            | Regional   |                | 79            | 0             | 2         | MAJOR TRANSIT ROUTE | [null, 47.51853575100006, -122.33945069199996, null, false, {paths=[[[-122.33945069199996, 47.51853575100006], [-122.34013076399998, 47.51727251800003]]]}]                                                                                                                                                                                                                                                                                                                                                   | 2014 | 1413936000 | 490.470778228786002728156745433807373046875       | 
| 4        | 22202   | 68       | 17720  | 0300    | 177200300  | SW GENESEE ST BETWEEN 30TH AVE SW AND 31ST AVE SW          | SW GENESEE ST    | SW GENESEE ST    | 30TH AVE SW       | 31ST AVE SW          | 3        | Collector Arterial |       | INSVC  | 3000     | 30         | W      | N      |           |      | 323       | 26           | PCC           | 1374710400    |               |               | 30TH AVE SW AND SW GENESEE ST      | W     | 32144    | 31ST AVE SW AND SW GENESEE ST         | E     | 341595   | 1260703.9929997599683701992034912109375  | 209783.898058880004100501537322998046875   | N           | N            | N            | Local      |                | 58            | 0             | 3         | MINOR TRANSIT ROUTE | [null, 47.564713967000046, -122.37080770699998, null, false, {paths=[[[-122.37080770699998, 47.564713967000046], [-122.37211775899999, 47.56470549200003]]]}]                                                                                                                                                                                                                                                                                                                                                 | 2014 | 1413936000 | 323.44414886045296952943317592144012451171875     | 
| 5        | 3546    | 68       | 01475  | 0150    | 014750150  | 24TH AVE E BETWEEN E GALER ST AND INTERLAKEN PL E          | 24TH AVE E       | 24TH AVE E       | E GALER ST        | INTERLAKEN PL E      | 1        | Principal Arterial |       | INSVC  | 1500     | 30         | N      | N      |           |      | 480       | 47           | AC/PCC        | 1374710400    |               |               | 24TH AVE E AND E GALER ST          | N     | 29193    | 24TH AVE E AND INTERLAKEN PL E        | S     | 28379    | 1278422.81285790004767477512359619140625 | 234329.21565200001350603997707366943359375 | N           | N            | Y            | Regional   |                | 13            | 0             | 2         | MAJOR TRANSIT ROUTE | [null, 47.63227855300005, -122.30161296799997, null, false, {paths=[[[-122.30161296799997, 47.63227855300005], [-122.30159187399994, 47.63359430400004]]]}]                                                                                                                                                                                                                                                                                                                                                   | 2014 | 1413936000 | 479.9684793524673978026839904487133026123046875   | 
| 6        | 5003    | 68       | 02385  | 0850    | 023850850  | 32ND AVE NW BETWEEN NW 85TH ST AND GOLDEN GARDENS DR NW    | 32ND AVE NW      | 32ND AVE NW      | NW 85TH ST        | GOLDEN GARDENS DR NW | 2        | Minor Arterial     |       | INSVC  | 8500     | 30         | N      | N      |           |      | 670       | 30           | PCC           | 1374710400    |               |               | 32ND AVE NW AND NW 85TH ST         | N     | 37079    | 32ND AVE NW AND GOLDEN GARDENS DR NW  | S     | 37065    | 1254966.8403538800776004791259765625     | 256145.34866635999060235917568206787109375 | N           | N            | N            | Commercial |                | 58            | 0             | 3         | MINOR TRANSIT ROUTE | [null, 47.69057293100008, -122.39832737999996, null, false, {paths=[[[-122.39832737999996, 47.69057293100008], [-122.39844892299999, 47.69068420100007], [-122.39849750699995, 47.69075663800004], [-122.39851464499998, 47.69081210200005], [-122.39851548599995, 47.691625814000076], [-122.39852847099996, 47.69183398500007], [-122.39857458299997, 47.69204002500004], [-122.39870786199998, 47.69235937600007]]]}]                                                                                      | 2014 | 1413936000 | 669.95491404836866422556340694427490234375        | 
| 7        | 17530   | 68       | 13595  | 0320    | 135950320  | NE 75TH ST BETWEEN 32ND AVE NE AND 33RD AVE NE             | NE 75TH ST       | NE 75TH ST       | 32ND AVE NE       | 33RD AVE NE          | 2        | Minor Arterial     |       | INSVC  | 3200     | 30         | E      | N      |           |      | 260       | 40           | PCC           | 1374710400    |               |               | 32ND AVE NE AND NE 75TH ST         | E     | 24654    | 33RD AVE NE AND NE 75TH ST            | W     | 24653    | 1280849.04735637991689145565032958984375 | 252565.4175266799866221845149993896484375  | Y           | N            | N            | Commercial |                | 84            | 0             | 3         | MINOR TRANSIT ROUTE | [null, 47.683048204000045, -122.29369478899997, null, false, {paths=[[[-122.29369478899997, 47.683048204000045], [-122.29263878899997, 47.68304819800005]]]}]                                                                                                                                                                                                                                                                                                                                                 | 2014 | 1413936000 | 260.1162220911490976504865102469921112060546875   | 
| 8        | 18054   | 68       | 13965  | 0480    | 139650480  | NE PRINCETON WAY BETWEEN NE 65TH W ST AND PRINCETON AVE NE | NE PRINCETON WAY | NE PRINCETON WAY | NE 65TH W ST      | PRINCETON AVE NE     | 2        | Minor Arterial     |       | INSVC  | 4800     | 30         | E      | N      |           |      | 491       | 30           | AC/PCC        | 1374710400    |               |               | NE 65TH ST AND NE PRINCETON W WAY  | E     | 24873    | PRINCETON AVE NE AND NE PRINCETON WAY | W     | 26096    | 1285133.37600077991373836994171142578125 | 249665.32869170999038033187389373779296875 | N           | N            | N            | Commercial |                | 100           | 0             | 3         | MINOR TRANSIT ROUTE | [null, 47.674863704000074, -122.27481708099998, null, false, {paths=[[[-122.27481708099998, 47.674863704000074], [-122.27525892299997, 47.67487923700003], [-122.27539016099996, 47.67491972000005], [-122.27547477399997, 47.67497296100004], [-122.27553372199998, 47.67504015700007], [-122.27555812399999, 47.67509646100007], [-122.27555788099994, 47.67535436000003], [-122.27558764599996, 47.67545719900005], [-122.27565115399995, 47.67555280500005], [-122.27586271599995, 47.67577526800005]]]}] | 2014 | 1413936000 | 489.88490982405352269779541529715061187744140625  | 
| 9        | 23226   | 68       | 18525  | 0230    | 185250230  | W DRAVUS ST BETWEEN 23RD AVE W AND 24TH AVE W              | W DRAVUS ST      | W DRAVUS ST      | 23RD AVE W        | 24TH AVE W           | 2        | Minor Arterial     |       | INSVC  | 2300     | 30         | W      | N      |           |      | 359       | 24           | PCC           | 1374710400    |               |               | 23RD AVE W AND W DRAVUS ST         | W     | 26475    | 24TH AVE W AND W DRAVUS ST            | E     | 26476    | 1257560.0690285400487482547760009765625  | 240406.47697022999636828899383544921875    | N           | N            | N            | Commercial |                | 63            | 0             | 0         | NOT DESIGNATED      | [null, 47.64845008900005, -122.38596978699996, null, false, {paths=[[[-122.38596978699996, 47.64845008900005], [-122.38742644399997, 47.648492254000075]]]}]                                                                                                                                                                                                                                                                                                                                                  | 2014 | 1413936000 | 359.3747124609745924317394383251667022705078125   | 
| 10       | 23575   | 68       | 18865  | 0360    | 188650360  | W MCGRAW ST BETWEEN 36TH AVE W AND MORLEY PL W             | W MCGRAW ST      | W MCGRAW ST      | 36TH AVE W        | MORLEY PL W          | 3        | Collector Arterial |       | INSVC  | 3600     | 30         | W      | N      |           |      | 164       | 25           | PCC           | 1374710400    |               |               | 36TH AVE W AND W MCGRAW ST         | W     | 27502    | MORLEY PL W AND W MCGRAW ST           | E     | 27503    | 1253225.5827520899474620819091796875     | 237238.27901498999563045799732208251953125 | N           | N            | N            | Local      |                | 48            | 0             | 0         | NOT DESIGNATED      | [null, 47.63954740400004, -122.40368452799999, null, false, {paths=[[[-122.40368452799999, 47.63954740400004], [-122.40434998599994, 47.639545017000046]]]}]                                                                                                                                                                                                                                                                                                                                                  | 2014 | 1413936000 | 164.056593360004200121693429537117481231689453125 | 
```