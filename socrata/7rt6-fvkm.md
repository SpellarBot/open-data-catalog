# SDOT Stairways

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-stairways) |
| Metadata | [Link](https://data.seattle.gov/api/views/7rt6-fvkm) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/7rt6-fvkm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/7rt6-fvkm/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 7rt6-fvkm |
| Name | SDOT Stairways |
| Category | Transportation |
| Tags | sdot asset status and condition report, assets |
| Created | 2016-04-18T16:06:00Z |
| Publication Date | 2016-04-22T15:32:24Z |

## Description

Displays the location of stairways owned by SDOT within the City of Seattle.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type  | Render Type |
| ======== | ============== | =================== | =================== | ========== | =========== |
| Yes      | series tag     | objectid            | OBJECTID            | text       | number      |
| Yes      | numeric metric | compkey             | COMPKEY             | number     | number      |
| Yes      | series tag     | comptype            | COMPTYPE            | text       | number      |
| Yes      | numeric metric | segkey              | SEGKEY              | number     | number      |
| Yes      | series tag     | unitid              | UNITID              | text       | text        |
| Yes      | series tag     | unitdesc_asset      | UNITDESC_ASSET      | text       | text        |
| Yes      | series tag     | unitdesc_seg        | UNITDESC_SEG        | text       | text        |
| Yes      | series tag     | unittype            | UNITTYPE            | text       | text        |
| No       |                | install_date        | INSTALL_DATE        | date       | date        |
| Yes      | series tag     | ownership           | OWNERSHIP           | text       | text        |
| Yes      | series tag     | maintained_by       | MAINTAINED_BY       | text       | text        |
| Yes      | series tag     | maintfinancialresp  | MAINTFINANCIALRESP  | text       | text        |
| Yes      | series tag     | current_status      | CURRENT_STATUS      | text       | text        |
| Yes      | numeric metric | stairwayrating      | STAIRWAYRATING      | number     | number      |
| Yes      | series tag     | stairwaycondition   | STAIRWAYCONDITION   | text       | text        |
| Yes      | numeric metric | railrating          | RAILRATING          | number     | number      |
| Yes      | series tag     | railcondition       | RAILCONDITION       | text       | text        |
| Yes      | numeric metric | inspectionkey       | INSPECTIONKEY       | number     | number      |
| Yes      | time           | inspcompdate        | INSPCOMPDATE        | date       | date        |
| Yes      | series tag     | slideprone          | SLIDEPRONE          | text       | text        |
| Yes      | series tag     | stairwaytype        | STAIRWAYTYPE        | text       | text        |
| Yes      | series tag     | railtype            | RAILTYPE            | text       | text        |
| Yes      | numeric metric | stairwaylength      | STAIRWAYLENGTH      | number     | number      |
| Yes      | numeric metric | stairwaywidth       | STAIRWAYWIDTH       | number     | number      |
| Yes      | numeric metric | nbr_stairlanding    | NBR_STAIRLANDING    | number     | number      |
| Yes      | numeric metric | nbr_stairriser      | NBR_STAIRRISER      | number     | number      |
| Yes      | series tag     | bikerunnel          | BIKERUNNEL          | text       | text        |
| No       |                | shape               | Shape               | geospatial | geospatial  |
| Yes      | series tag     | primarydistrictcd   | PRIMARYDISTRICTCD   | text       | text        |
| Yes      | series tag     | secondarydistrictcd | SECONDARYDISTRICTCD | text       | text        |
| Yes      | series tag     | overrideyn          | OVERRIDEYN          | text       | text        |
| Yes      | series tag     | overridecomment     | OVERRIDECOMMENT     | text       | text        |
| Yes      | numeric metric | shape_length        | Shape_Length        | number     | number      |
```

## Time Field

```ls
Value = inspcompdate
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = install_date,shape
```

## Data Commands

```ls
series e:7rt6-fvkm d:2014-11-04T08:43:00.000Z t:shape.longitude=-122.28568905299994 t:maintained_by=SDOT t:railtype="Metal Pipe" t:comptype=16 t:current_status=INSVC t:stairwaytype="RC Reinforced Concrete" t:ownership=SDOT t:unitid=STW-253B t:unitdesc_asset="501 RANDOLPH AVE BETWEEN WELLINGTON AVE AND E JAMES ST" t:shape.needs_recoding=false t:unitdesc_seg="RANDOLPH AVE BETWEEN E JEFFERSON ST AND WELLINGTON AVE" t:railcondition=Good t:overrideyn=N t:primarydistrictcd=DISTRICT3 t:shape.latitude=47.606024038000044 t:objectid=1 t:unittype=STW t:stairwaycondition=Good m:stairwaylength=0 m:nbr_stairlanding=4 m:shape_length=18.195480600122643 m:stairwayrating=80 m:segkey=12446 m:nbr_stairriser=72 m:inspectionkey=2775 m:railrating=80 m:compkey=513592

series e:7rt6-fvkm d:2014-09-11T00:00:00.000Z t:shape.longitude=-122.385084055 t:maintained_by=SDOT t:railtype="Timber (Lumber > 5 inches)" t:comptype=16 t:current_status=INSVC t:stairwaytype="Concrete Slabs" t:ownership=SDOT t:unitid=STW-143 t:unitdesc_asset="SW HILL ST BETWEEN 42ND AND CALIFORNIA" t:shape.needs_recoding=false t:unitdesc_seg="SW HILL ST BETWEEN DEAD END 4 AND CALIFORNIA AVE SW" t:railcondition=Fair t:overrideyn=N t:primarydistrictcd=DISTRICT1 t:shape.latitude=47.58535163800008 t:objectid=2 t:unittype=STW t:stairwaycondition=Good m:stairwaylength=40 m:nbr_stairlanding=1 m:shape_length=27.468327984414206 m:stairwayrating=80 m:segkey=22324 m:nbr_stairriser=33 m:inspectionkey=2296 m:railrating=75 m:compkey=512323

series e:7rt6-fvkm d:2017-01-24T14:41:00.000Z t:shape.longitude=-122.32782284999996 t:maintained_by=SDOT t:railtype="Metal Pipe" t:comptype=16 t:current_status=INSVC t:stairwaytype="RC Reinforced Concrete" t:ownership=SDOT t:unitid=STW-137 t:unitdesc_asset="E HARRISON ST BETWEEN MELROSE AVE E AND BELLEVUE AVE E" t:shape.needs_recoding=false t:unitdesc_seg="E HARRISON ST BETWEEN DEAD END AND BELLEVUE AVE E" t:railcondition=Fair t:overrideyn=N t:primarydistrictcd=DISTRICT3 t:shape.latitude=47.621979260000046 t:objectid=3 t:unittype=STW t:stairwaycondition=Fair m:stairwaylength=116 m:nbr_stairlanding=5 m:shape_length=116.99996459670193 m:stairwayrating=70 m:segkey=14099 m:nbr_stairriser=74 m:inspectionkey=7014 m:railrating=60 m:compkey=512317
```

## Meta Commands

```ls
metric m:compkey p:integer l:COMPKEY d:COMPKEY t:dataTypeName=number

metric m:segkey p:integer l:SEGKEY d:SEGKEY t:dataTypeName=number

metric m:stairwayrating p:double l:STAIRWAYRATING d:STAIRWAYRATING t:dataTypeName=number

metric m:railrating p:double l:RAILRATING d:RAILRATING t:dataTypeName=number

metric m:inspectionkey p:integer l:INSPECTIONKEY d:INSPECTIONKEY t:dataTypeName=number

metric m:stairwaylength p:integer l:STAIRWAYLENGTH d:STAIRWAYLENGTH t:dataTypeName=number

metric m:stairwaywidth p:integer l:STAIRWAYWIDTH d:STAIRWAYWIDTH t:dataTypeName=number

metric m:nbr_stairlanding p:integer l:NBR_STAIRLANDING d:NBR_STAIRLANDING t:dataTypeName=number

metric m:nbr_stairriser p:integer l:NBR_STAIRRISER d:NBR_STAIRRISER t:dataTypeName=number

metric m:shape_length p:decimal l:Shape_Length d:Shape_Length t:dataTypeName=number

entity e:7rt6-fvkm l:"SDOT Stairways" t:url=https://data.seattle.gov/api/views/7rt6-fvkm

property e:7rt6-fvkm t:meta.view v:id=7rt6-fvkm v:category=Transportation v:averageRating=0 v:name="SDOT Stairways"

property e:7rt6-fvkm t:meta.view.license v:name="Public Domain"

property e:7rt6-fvkm t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:7rt6-fvkm t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | compkey | comptype | segkey | unitid   | unitdesc_asset                                         | unitdesc_seg                                           | unittype | install_date | ownership | maintained_by | maintfinancialresp | current_status | stairwayrating | stairwaycondition | railrating | railcondition | inspectionkey | inspcompdate | slideprone | stairwaytype           | railtype                   | stairwaylength | stairwaywidth | nbr_stairlanding | nbr_stairriser | bikerunnel | shape                                                                                                                                                                                                   | primarydistrictcd | secondarydistrictcd | overrideyn | overridecomment | shape_length                                        | 
| ======== | ======= | ======== | ====== | ======== | ====================================================== | ====================================================== | ======== | ============ | ========= | ============= | ================== | ============== | ============== | ================= | ========== | ============= | ============= | ============ | ========== | ====================== | ========================== | ============== | ============= | ================ | ============== | ========== | ======================================================================================================================================================================================================= | ================= | =================== | ========== | =============== | =================================================== | 
| 1        | 513592  | 16       | 12446  | STW-253B | 501 RANDOLPH AVE BETWEEN WELLINGTON AVE AND E JAMES ST | RANDOLPH AVE BETWEEN E JEFFERSON ST AND WELLINGTON AVE | STW      |              | SDOT      | SDOT          |                    | INSVC          | 80             | Good              | 80         | Good          | 2775          | 1415090580   |            | RC Reinforced Concrete | Metal Pipe                 | 0              |               | 4                | 72             |            | [null, 47.606024038000044, -122.28568905299994, null, false, {paths=[[[-122.28568905299994, 47.606024038000044], [-122.28576265099997, 47.60602734200006]]]}]                                           | DISTRICT3         |                     | N          |                 | 18.19548060012264301121831522323191165924072265625  | 
| 2        | 512323  | 16       | 22324  | STW-143  | SW HILL ST BETWEEN 42ND AND CALIFORNIA                 | SW HILL ST BETWEEN DEAD END 4 AND CALIFORNIA AVE SW    | STW      |              | SDOT      | SDOT          |                    | INSVC          | 80             | Good              | 75         | Fair          | 2296          | 1410393600   |            | Concrete Slabs         | Timber (Lumber > 5 inches) | 40             |               | 1                | 33             |            | [null, 47.58535163800008, -122.385084055, null, false, {paths=[[[-122.385084055, 47.58535163800008], [-122.38519520999995, 47.58535554100007]]]}]                                                       | DISTRICT1         |                     | N          |                 | 27.468327984414205644725370802916586399078369140625 | 
| 3        | 512317  | 16       | 14099  | STW-137  | E HARRISON ST BETWEEN MELROSE AVE E AND BELLEVUE AVE E | E HARRISON ST BETWEEN DEAD END AND BELLEVUE AVE E      | STW      |              | SDOT      | SDOT          |                    | INSVC          | 70             | Fair              | 60         | Fair          | 7014          | 1485268860   |            | RC Reinforced Concrete | Metal Pipe                 | 116            |               | 5                | 74             |            | [null, 47.621979260000046, -122.32782284999996, null, false, {paths=[[[-122.32782284999996, 47.621979260000046], [-122.32734842299999, 47.621980525000026]]]}]                                          | DISTRICT3         |                     | N          |                 | 116.9999645967019290537791675888001918792724609375  | 
| 4        | 512235  | 16       | 23094  | STW-050  | W BERTONA ST BETWEEN 14TH AND 15TH                     | W BERTONA ST BETWEEN 12TH AVE W AND 13TH AVE W         | STW      | -757468800   | SDOT      | SDOT          |                    | INSVC          | 72.5           | Fair              | 65         | Fair          | 1556          | 1394496000   |            | Concrete Slabs         | Timber (Lumber > 5 inches) | 203            |               | 13               | 104            |            | [null, 47.65034482300007, -122.37523053899997, null, false, {paths=[[[-122.37523053899997, 47.65034482300007], [-122.37605414199999, 47.65034323700007]]]}]                                             | DISTRICT7         |                     | N          |                 | 202.999986527577362949159578420221805572509765625   | 
| 5        | 513569  | 16       | 11966  | STW-228  | NEWTON ST BETWEEN WESTLAKE AVE N AND 8TH AVE N         | NEWTON ST BETWEEN 8TH AVE N AND DEAD END 2             | STW      |              | SDOT      | SDOT          |                    | INSVC          |                |                   |            |               |               |              |            | RC Reinforced Concrete | Metal Pipe                 | 89             |               | 5                | 49             |            | [null, 47.636555359000056, -122.34102833699995, null, false, {paths=[[[-122.34102833699995, 47.636555359000056], [-122.34063041999997, 47.63647828100005]]]}]                                           | DISTRICT7         |                     | N          |                 | 102.052889131656598920017131604254245758056640625   | 
| 6        | 512244  | 16       | 164722 | STW-059A | S BRADFORD ST BETWEEN 31ST AVE S AND LETITIA AVE S     | S BRADFORD ST BETWEEN 30TH AVE S AND 31ST AVE S        | STW      |              | SDOT      | SDOT          |                    | INSVC          | 75             | Fair              | 80         | Good          | 1578          | 1392854400   |            | Concrete Slabs         | Timber (Lumber > 5 inches) | 62             |               | 3                | 47             |            | [null, 47.56916281100007, -122.29202001099998, null, false, {paths=[[[-122.29202001099998, 47.56916281100007], [-122.29206647699999, 47.56914526500003], [-122.29210783299999, 47.56911295500004]]]}]   | DISTRICT2         |                     | N          |                 | 28.7280193095822227178359753452241420745849609375   | 
| 7        | 513932  | 16       | 8920   | STW-645W | AURORA AVE N BETWEEN N 38TH ST AND AURORA AVE N        | AURORA AVE N BETWEEN BRIDGE WAY N AND N 38 UPPER ST    | STW      |              | SDOT      | SDOT          |                    | INSVC          | 88             | Good              | 82.5       | Good          | 3834          | 1420701540   |            | RC Reinforced Concrete | Metal Pipe                 | 30             |               | 3                | 27             |            | [null, 47.65250917600008, -122.34755082199996, null, false, {paths=[[[-122.34755082199996, 47.65250917600008], [-122.34749615599998, 47.652425219000065], [-122.34744788999996, 47.652304883000056]]]}] | DISTRICT4         | DISTRICT6           | N          |                 | 78.935185401480339351110160350799560546875          | 
| 8        | 512333  | 16       | 10948  | STW-155  | HOLYOKE WAY S BETWEEN WATERS AND WATERS                | HOLYOKE WAY S BETWEEN S THAYER ST AND 68TH AVE S       | STW      |              | SDOT      | SDOT          |                    | INSVC          |                |                   |            |               |               |              |            | RC Reinforced Concrete | Metal Pipe                 | 33             |               |                  | 29             |            | [null, 47.51036437600004, -122.25005394299995, null, false, {paths=[[[-122.25005394299995, 47.51036437600004], [-122.24996731299996, 47.51038929500004]]]}]                                             | DISTRICT2         |                     | N          |                 | 23.25932620299573017064176383428275585174560546875  | 
| 9        | 513772  | 16       | 18356  | STW-429  | NW 48TH ST BETWEEN MARKET AND MARKET                   | NW 48TH ST BETWEEN 1ST AVE NW AND DEAD END             | STW      |              | SDOT      | SDOT          |                    | INSVC          | 80             | Good              | 80         | Good          | 6721          | 1471392000   |            | RC Reinforced Concrete | Metal Pipe                 | 17             |               |                  | 15             |            | [null, 47.663596849000044, -122.35788493299998, null, false, {paths=[[[-122.35788493299998, 47.663596849000044], [-122.35783351399999, 47.663648186000046]]]}]                                          | DISTRICT6         |                     | N          |                 | 22.6098827651209290934275486506521701812744140625   | 
| 10       | 513849  | 16       | 14781  | STW-501  | E SHELBY ST BETWEEN BOYER AND LAKE UNION               | E SHELBY ST BETWEEN BOYER AVE E AND DEAD END 3         | STW      |              | SDOT      | SDOT          |                    | INSVC          | 0              | Not Rated         | 0          | Not Rated     | 4658          | 1431530100   |            | RC Reinforced Concrete | Metal Pipe                 | 32             |               | 2                | 18             |            | [null, 47.64698246900008, -122.31639620799996, null, false, {paths=[[[-122.31639620799996, 47.64698246900008], [-122.31634455299996, 47.646979474000034], [-122.31633782199998, 47.64695336900007]]]}]  | DISTRICT3         |                     | N          |                 | 22.444846549203642638303790590725839138031005859375 | 
```