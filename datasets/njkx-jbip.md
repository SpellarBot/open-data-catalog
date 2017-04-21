# SDOT Street Details

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/streets-details-greenways-pavement-condition-arterial-classification-transit-classificatio) |
| Metadata | [Link](https://data.seattle.gov/api/views/njkx-jbip) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/njkx-jbip/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/njkx-jbip/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | njkx-jbip |
| Name | SDOT Street Details |
| Attribution | Seattle Dept of Transportation, multiple Divisions. |
| Category | Transportation |
| Tags | greenways, greenway, pavement, arterial, classification, freight, truck, street, national, highway, system, signed, bike, route, vision zero, sdot asset status and condition report, assets |
| Created | 2015-03-19T15:29:19Z |
| Publication Date | 2015-03-19T15:37:34Z |

## Description

Presentation feature class that is a representation of the City's Street Network Database (SND) showing driveable public streets and other public walkways and trails, within the Seattle City limits.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type  | Render Type |
| ======== | ============== | =================== | =================== | ========== | =========== |
| Yes      | series tag     | objectid            | OBJECTID            | text       | number      |
| Yes      | numeric metric | compkey             | COMPKEY             | number     | number      |
| Yes      | series tag     | comptype            | COMPTYPE            | text       | number      |
| Yes      | series tag     | unitid              | UNITID              | text       | text        |
| Yes      | series tag     | unitid2             | UNITID2             | text       | text        |
| Yes      | series tag     | unitidsort          | UNITIDSORT          | text       | text        |
| Yes      | series tag     | unitdesc            | UNITDESC            | text       | text        |
| Yes      | series tag     | stname_ord          | STNAME_ORD          | text       | text        |
| Yes      | series tag     | onstreet            | ONSTREET            | text       | text        |
| Yes      | series tag     | xstrlo              | XSTRLO              | text       | text        |
| Yes      | series tag     | xstrhi              | XSTRHI              | text       | text        |
| Yes      | numeric metric | artclass            | ARTCLASS            | number     | number      |
| Yes      | series tag     | artdescript         | ARTDESCRIPT         | text       | text        |
| Yes      | series tag     | owner               | OWNER               | text       | text        |
| Yes      | series tag     | status              | STATUS              | text       | text        |
| Yes      | numeric metric | blocknbr            | BLOCKNBR            | number     | number      |
| Yes      | numeric metric | speedlimit          | SPEEDLIMIT          | number     | number      |
| Yes      | series tag     | segdir              | SEGDIR              | text       | text        |
| Yes      | series tag     | oneway              | ONEWAY              | text       | text        |
| Yes      | series tag     | onewaydir           | ONEWAYDIR           | text       | text        |
| Yes      | series tag     | flow                | FLOW                | text       | text        |
| Yes      | numeric metric | seglength           | SEGLENGTH           | number     | number      |
| Yes      | numeric metric | surfacewidth        | SURFACEWIDTH        | number     | number      |
| Yes      | series tag     | surfacetype_1       | SURFACETYPE_1       | text       | text        |
| Yes      | time           | surfacedate_1       | SURFACEDATE_1       | date       | date        |
| Yes      | series tag     | surfacetype_2       | SURFACETYPE_2       | text       | text        |
| No       |                | surfacedate_2       | SURFACEDATE_2       | date       | date        |
| Yes      | series tag     | intrlo              | INTRLO              | text       | text        |
| Yes      | series tag     | dirlo               | DIRLO               | text       | text        |
| Yes      | numeric metric | intkeylo            | INTKEYLO            | number     | number      |
| Yes      | series tag     | intrhi              | INTRHI              | text       | text        |
| Yes      | series tag     | dirhi               | DIRHI               | text       | text        |
| Yes      | numeric metric | intkeyhi            | INTKEYHI            | number     | number      |
| Yes      | numeric metric | gis_mid_x           | GIS_MID_X           | number     | number      |
| Yes      | numeric metric | gis_mid_y           | GIS_MID_Y           | number     | number      |
| No       |                | shape               | Shape               | geospatial | geospatial  |
| Yes      | series tag     | sgndbkroute         | SGNDBKROUTE         | text       | text        |
| Yes      | series tag     | nghbrhdgrnwy        | NGHBRHDGRNWY        | text       | text        |
| Yes      | series tag     | nationhwysys        | NATIONHWYSYS        | text       | text        |
| Yes      | series tag     | streettype          | STREETTYPE          | text       | text        |
| Yes      | series tag     | mjtrk_str_flag      | MJTRK_STR_FLAG      | text       | text        |
| Yes      | numeric metric | pvmtcondindx1       | PVMTCONDINDX1       | number     | number      |
| Yes      | numeric metric | pvmtcondindx2       | PVMTCONDINDX2       | number     | number      |
| Yes      | numeric metric | tranclass           | TRANCLASS           | number     | number      |
| Yes      | series tag     | trandescript        | TRANDESCRIPT        | text       | text        |
| Yes      | series tag     | primarydistrictcd   | PRIMARYDISTRICTCD   | text       | text        |
| Yes      | series tag     | secondarydistrictcd | SECONDARYDISTRICTCD | text       | text        |
| Yes      | series tag     | overrideyn          | OVERRIDEYN          | text       | text        |
| Yes      | series tag     | overridecomment     | OVERRIDECOMMENT     | text       | text        |
| Yes      | numeric metric | shape_length        | Shape_Length        | number     | number      |
```

## Time Field

```ls
Value = surfacedate_1
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = surfacedate_2,shape
```

## Data Commands

```ls
series e:njkx-jbip d:2013-07-25T00:00:00.000Z t:shape.longitude=-122.33493456599996 t:segdir=NW t:onstreet="1ST AVE" t:unitid2=0080 t:dirlo=NW t:comptype=68 t:artdescript="Minor Arterial" t:stname_ord="1ST AVE" t:nationhwysys=N t:unitdesc="1ST AVE BETWEEN COLUMBIA ST AND MARION ST" t:unitid=00010 t:shape.needs_recoding=false t:oneway=N t:shape.latitude=47.60326855800008 t:unitidsort=000100080 t:dirhi=SE t:surfacetype_1=AC/PCC t:status=INSVC t:sgndbkroute=N t:intrlo="1ST AVE AND COLUMBIA ST" t:intrhi="1ST AVE AND MARION ST" t:xstrlo="COLUMBIA ST" t:xstrhi="MARION ST" t:overrideyn=N t:primarydistrictcd=DISTRICT7 t:trandescript="PRINCIPAL TRANSIT ROUTE" t:nghbrhdgrnwy=N t:objectid=1 m:pvmtcondindx2=0 m:intkeyhi=29622 m:pvmtcondindx1=34 m:gis_mid_x=1269916.98206519 m:artclass=2 m:intkeylo=30348 m:surfacewidth=52 m:blocknbr=800 m:compkey=1002 m:gis_mid_y=223799.74389723 m:shape_length=305.99603848447725 m:seglength=306 m:tranclass=1 m:speedlimit=30

series e:njkx-jbip d:2013-07-25T00:00:00.000Z t:shape.longitude=-122.35154985699995 t:segdir=NW t:onstreet="1ST AVE" t:unitid2=0280 t:dirlo=NW t:comptype=68 t:artdescript="Minor Arterial" t:stname_ord="1ST AVE" t:nationhwysys=N t:unitdesc="1ST AVE BETWEEN CLAY ST AND BROAD ST" t:unitid=00010 t:shape.needs_recoding=false t:oneway=N t:shape.latitude=47.61635383400005 t:unitidsort=000100280 t:dirhi=SE t:surfacetype_1=AC/PCC t:status=INSVC t:sgndbkroute=Y t:intrlo="1ST AVE AND CLAY ST" t:intrhi="1ST AVE AND BROAD ST" t:xstrlo="CLAY ST" t:xstrhi="BROAD ST" t:overrideyn=N t:primarydistrictcd=DISTRICT7 t:trandescript="MAJOR TRANSIT ROUTE" t:nghbrhdgrnwy=N t:objectid=2 m:pvmtcondindx2=0 m:intkeyhi=29665 m:pvmtcondindx1=62 m:gis_mid_x=1265874.86686106 m:artclass=2 m:intkeylo=29677 m:surfacewidth=52 m:blocknbr=2800 m:compkey=1020 m:gis_mid_y=228625.84310217 m:shape_length=313.16707367720505 m:seglength=313 m:tranclass=2 m:speedlimit=30

series e:njkx-jbip d:2013-07-26T00:00:00.000Z t:shape.longitude=-122.35541463499999 t:onstreet="1ST AVE N" t:segdir=N t:unitid2=0050 t:dirlo=N t:comptype=68 t:flow=F t:artdescript="Principal Arterial" t:stname_ord="1ST AVE N" t:nationhwysys=N t:unitdesc="1ST AVE N BETWEEN REPUBLICAN ST AND MERCER ST" t:unitid=00015 t:shape.needs_recoding=false t:streettype=Main t:oneway=Y t:shape.latitude=47.62327152300003 t:unitidsort=000150050 t:dirhi=S t:surfacetype_1=AC/PCC t:onewaydir=N t:status=INSVC t:sgndbkroute=Y t:intrlo="1ST AVE N AND REPUBLICAN ST" t:intrhi="1ST AVE N AND MERCER ST" t:xstrlo="REPUBLICAN ST" t:xstrhi="MERCER ST" t:overrideyn=N t:primarydistrictcd=DISTRICT7 t:trandescript="MAJOR TRANSIT ROUTE" t:nghbrhdgrnwy=N t:objectid=3 m:pvmtcondindx2=0 m:intkeyhi=28919 m:pvmtcondindx1=73 m:gis_mid_x=1265093.71140425 m:artclass=1 m:intkeylo=28920 m:surfacewidth=42 m:blocknbr=500 m:compkey=1029 m:gis_mid_y=231300.4969289 m:shape_length=476.6545505079149 m:seglength=477 m:tranclass=2 m:speedlimit=30
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

entity e:njkx-jbip l:"SDOT Street Details" t:attribution="Seattle Dept of Transportation, multiple Divisions." t:url=https://data.seattle.gov/api/views/njkx-jbip

property e:njkx-jbip t:meta.view v:id=njkx-jbip v:category=Transportation v:attributionLink=http://www.seattle.gov/transportation/ v:averageRating=0 v:name="SDOT Street Details" v:attribution="Seattle Dept of Transportation, multiple Divisions."

property e:njkx-jbip t:meta.view.license v:name="Public Domain"

property e:njkx-jbip t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:njkx-jbip t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | compkey | comptype | unitid | unitid2 | unitidsort | unitdesc                                            | stname_ord | onstreet   | xstrlo           | xstrhi      | artclass | artdescript        | owner | status | blocknbr | speedlimit | segdir | oneway | onewaydir | flow | seglength | surfacewidth | surfacetype_1 | surfacedate_1 | surfacetype_2 | surfacedate_2 | intrlo                          | dirlo | intkeylo | intrhi                     | dirhi | intkeyhi | gis_mid_x                                | gis_mid_y                                  | shape                                                                                                                                                         | sgndbkroute | nghbrhdgrnwy | nationhwysys | streettype | mjtrk_str_flag | pvmtcondindx1 | pvmtcondindx2 | tranclass | trandescript            | primarydistrictcd | secondarydistrictcd | overrideyn | overridecomment | shape_length                                      | 
| ======== | ======= | ======== | ====== | ======= | ========== | =================================================== | ========== | ========== | ================ | =========== | ======== | ================== | ===== | ====== | ======== | ========== | ====== | ====== | ========= | ==== | ========= | ============ | ============= | ============= | ============= | ============= | =============================== | ===== | ======== | ========================== | ===== | ======== | ======================================== | ========================================== | ============================================================================================================================================================= | =========== | ============ | ============ | ========== | ============== | ============= | ============= | ========= | ======================= | ================= | =================== | ========== | =============== | ================================================= | 
| 1        | 1002    | 68       | 00010  | 0080    | 000100080  | 1ST AVE BETWEEN COLUMBIA ST AND MARION ST           | 1ST AVE    | 1ST AVE    | COLUMBIA ST      | MARION ST   | 2        | Minor Arterial     |       | INSVC  | 800      | 30         | NW     | N      |           |      | 306       | 52           | AC/PCC        | 1374710400    |               |               | 1ST AVE AND COLUMBIA ST         | NW    | 30348    | 1ST AVE AND MARION ST      | SE    | 29622    | 1269916.9820651900954544544219970703125  | 223799.74389722998603247106075286865234375 | [null, 47.60326855800008, -122.33493456599996, null, false, {paths=[[[-122.33493456599996, 47.60326855800008], [-122.33558646699998, 47.60398223800007]]]}]   | N           | N            | N            |            |                | 34            | 0             | 1         | PRINCIPAL TRANSIT ROUTE | DISTRICT7         |                     | N          |                 | 305.9960384844772534052026458084583282470703125   | 
| 2        | 1020    | 68       | 00010  | 0280    | 000100280  | 1ST AVE BETWEEN CLAY ST AND BROAD ST                | 1ST AVE    | 1ST AVE    | CLAY ST          | BROAD ST    | 2        | Minor Arterial     |       | INSVC  | 2800     | 30         | NW     | N      |           |      | 313       | 52           | AC/PCC        | 1374710400    |               |               | 1ST AVE AND CLAY ST             | NW    | 29677    | 1ST AVE AND BROAD ST       | SE    | 29665    | 1265874.86686106002889573574066162109375 | 228625.84310217000893317162990570068359375 | [null, 47.61635383400005, -122.35154985699995, null, false, {paths=[[[-122.35154985699995, 47.61635383400005], [-122.35250653999998, 47.61691833900005]]]}]   | Y           | N            | N            |            |                | 62            | 0             | 2         | MAJOR TRANSIT ROUTE     | DISTRICT7         |                     | N          |                 | 313.167073677205053172656334936618804931640625    | 
| 3        | 1029    | 68       | 00015  | 0050    | 000150050  | 1ST AVE N BETWEEN REPUBLICAN ST AND MERCER ST       | 1ST AVE N  | 1ST AVE N  | REPUBLICAN ST    | MERCER ST   | 1        | Principal Arterial |       | INSVC  | 500      | 30         | N      | Y      | N         | F    | 477       | 42           | AC/PCC        | 1374796800    |               |               | 1ST AVE N AND REPUBLICAN ST     | N     | 28920    | 1ST AVE N AND MERCER ST    | S     | 28919    | 1265093.711404250003397464752197265625   | 231300.49692889998550526797771453857421875 | [null, 47.62327152300003, -122.35541463499999, null, false, {paths=[[[-122.35541463499999, 47.62327152300003], [-122.355403922, 47.624578246000056]]]}]       | Y           | N            | N            | Main       |                | 73            | 0             | 2         | MAJOR TRANSIT ROUTE     | DISTRICT7         |                     | N          |                 | 476.6545505079149052107823081314563751220703125   | 
| 4        | 1057    | 68       | 00015  | 0263    | 000150263  | 1ST AVE N BETWEEN DEAD END 2 AND NEWELL N ST        | 1ST AVE N  | 1ST AVE N  | DEAD END 2       | NEWELL N ST | 0        | Not Designated     |       | INSVC  | 2700     | 0          | N      | N      |           |      | 125       | 0            | PCC           |               |               |               | 1ST AVE N AND DEAD END 2        | N     | 27984    | 1ST AVE N AND NEWELL N ST  | S     | 28065    | 1265209.9688123799860477447509765625     | 238810.42000859999097883701324462890625    | [null, 47.64434433000008, -122.35554142399997, null, false, {paths=[[[-122.35554142399997, 47.64434433000008], [-122.35553911199997, 47.64468672000004]]]}]   | N           | N            | N            |            |                | 0             | 0             | 0         | NOT DESIGNATED          | DISTRICT7         |                     | N          |                 | 124.893067672992145844546030275523662567138671875 | 
| 5        | 1069    | 68       | 00020  | 0500    | 000200500  | 1ST AVE NE BETWEEN NE 50TH ST AND NE 51ST ST        | 1ST AVE NE | 1ST AVE NE | NE 50TH ST       | NE 51ST ST  | 0        | Not Designated     |       | INSVC  | 5000     | 0          | N      | N      |           |      | 267       | 18           | PCC           | 1379980800    |               |               | 1ST AVE NE AND NE 50TH ST       | N     | 25871    | 1ST AVE NE AND NE 51ST ST  | S     | 25863    | 1272075.354675400070846080780029296875   | 246283.74059226000099442899227142333984375 | [null, 47.66500266400004, -122.32826780399995, null, false, {paths=[[[-122.32826780399995, 47.66500266400004], [-122.32829917599997, 47.665734386000054]]]}]  | N           | N            | N            |            |                | 35            | 0             | 0         | NOT DESIGNATED          | DISTRICT6         |                     | N          |                 | 267.0190966348217216363991610705852508544921875   | 
| 6        | 1074    | 68       | 00020  | 0560    | 000200560  | 1ST AVE NE BETWEEN NE 56TH ST AND NE 57TH ST        | 1ST AVE NE | 1ST AVE NE | NE 56TH ST       | NE 57TH ST  | 0        | Not Designated     |       | INSVC  | 5600     | 0          | N      | N      |           |      | 274       | 25           | PCC           | 1382400000    |               |               | 1ST AVE NE AND NE 56TH ST       | N     | 25845    | 1ST AVE NE AND NE 57TH ST  | S     | 25840    | 1272114.122803430072963237762451171875   | 247878.21880189000512473285198211669921875 | [null, 47.66936557400004, -122.32825777899996, null, false, {paths=[[[-122.32825777899996, 47.66936557400004], [-122.328245977, 47.670116430000064]]]}]       | N           | N            | N            |            |                | 92            | 0             | 0         | NOT DESIGNATED          | DISTRICT6         |                     | N          |                 | 273.90202428588219163430039770901203155517578125  | 
| 7        | 1108    | 68       | 00020  | 1333    | 000201333  | 1ST AVE NE BETWEEN ROOSEVELT WAY NE AND NE 135TH ST | 1ST AVE NE | 1ST AVE NE | ROOSEVELT WAY NE | NE 135TH ST | 3        | Collector Arterial |       | INSVC  | 13300    | 30         | N      | N      |           |      | 251       | 24           | AC            | 1374710400    |               |               | 1ST AVE NE AND ROOSEVELT WAY NE | N     | 35947    | 1ST AVE NE AND NE 135TH ST | S     | 35948    | 1272363.00523569993674755096435546875    | 268566.442823069985024631023406982421875   | [null, 47.726116105000074, -122.32887828899999, null, false, {paths=[[[-122.32887828899999, 47.726116105000074], [-122.32886892599998, 47.72680375400006]]]}] | N           | N            | N            | Mixed      |                | 17            | 0             | 3         | MINOR TRANSIT ROUTE     | DISTRICT5         |                     | N          |                 | 250.84218554839253556565381586551666259765625     | 
| 8        | 1117    | 68       | 00025  | 0395    | 000250395  | 1ST AVE NW BETWEEN NW BOWDOIN PL AND DEAD END 1     | 1ST AVE NW | 1ST AVE NW | NW BOWDOIN PL    | DEAD END 1  | 0        | Not Designated     |       | INSVC  | 3900     | 0          | N      | N      |           |      | 160       | 25           | PCC           | 1376611200    |               |               | 1ST AVE NW AND NW BOWDOIN PL    | N     | 26664    | 1ST AVE NW AND DEAD END 1  | S     | 529760   | 1264880.7268280400894582271575927734375  | 242672.9440445500076748430728912353515625  | [null, 47.65486467900007, -122.35718756399996, null, false, {paths=[[[-122.35718756399996, 47.65486467900007], [-122.35718423699996, 47.655304615000034]]]}]  | N           | N            | N            |            |                | 40            | 0             | 0         | NOT DESIGNATED          | DISTRICT6         |                     | N          |                 | 160.47577347816815063197282142937183380126953125  | 
| 9        | 1138    | 68       | 00025  | 0592    | 000250592  | 1ST AVE NW BETWEEN N 59TH ST AND NW 60TH ST         | 1ST AVE NW | 1ST AVE NW | N 59TH ST        | NW 60TH ST  | 0        | Not Designated     |       | INSVC  | 5900     | 0          | N      | N      |           |      | 174       | 25           | PCC           | 1375920000    |               |               | 1ST AVE NW AND N 59TH ST        | N     | 25269    | 1ST AVE NW AND NW 60TH ST  | S     | 336867   | 1264872.37226801994256675243377685546875 | 248885.50200291001237928867340087890625    | [null, 47.67187450200004, -122.35771847399997, null, false, {paths=[[[-122.35771847399997, 47.67187450200004], [-122.35771969299998, 47.672350478000055]]]}]  | N           | N            | N            |            |                | 42            | 0             | 0         | NOT DESIGNATED          | DISTRICT6         |                     | N          |                 | 173.620178631057086704458924941718578338623046875 | 
| 10       | 1141    | 68       | 00025  | 0650    | 000250650  | 1ST AVE NW BETWEEN NW 65TH ST AND NW 67TH ST        | 1ST AVE NW | 1ST AVE NW | NW 65TH ST       | NW 67TH ST  | 0        | Not Designated     |       | INSVC  | 6500     | 0          | N      | N      |           |      | 650       | 25           | PCC           | 1375920000    |               |               | 1ST AVE NW AND NW 65TH ST       | N     | 25240    | 1ST AVE NW AND NW 67TH ST  | S     | 24114    | 1264976.7575481398962438106536865234375  | 250626.45035669000935740768909454345703125 | [null, 47.67599925300004, -122.35743912699996, null, false, {paths=[[[-122.35743912699996, 47.67599925300004], [-122.35743170699999, 47.67778075500007]]]}]   | N           | N            | N            |            |                | 48            | 0             | 0         | NOT DESIGNATED          | DISTRICT6         |                     | N          |                 | 649.833791179325771736330352723598480224609375    | 
```