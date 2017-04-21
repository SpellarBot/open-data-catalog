# SDOT Retaining Walls

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-retaining-walls) |
| Metadata | [Link](https://data.seattle.gov/api/views/sxr8-c6r3) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/sxr8-c6r3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/sxr8-c6r3/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | sxr8-c6r3 |
| Name | SDOT Retaining Walls |
| Category | Transportation |
| Tags | sdot asset status and condition report, assets |
| Created | 2016-04-18T16:01:21Z |
| Publication Date | 2016-04-22T15:32:03Z |

## Description

Displays the location of retaining walls in the City of Seattle.

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
| Yes      | time           | install_date        | INSTALL_DATE        | date       | date        |
| Yes      | series tag     | ownership           | OWNERSHIP           | text       | text        |
| Yes      | series tag     | maintained_by       | MAINTAINED_BY       | text       | text        |
| Yes      | series tag     | maintfinancialresp  | MAINTFINANCIALRESP  | text       | text        |
| Yes      | series tag     | current_status      | CURRENT_STATUS      | text       | text        |
| Yes      | numeric metric | retainwallrating    | RETAINWALLRATING    | number     | number      |
| Yes      | series tag     | retainwallcondition | RETAINWALLCONDITION | text       | text        |
| Yes      | numeric metric | inspectionkey       | INSPECTIONKEY       | number     | number      |
| No       |                | inspcompdate        | INSPCOMPDATE        | date       | date        |
| Yes      | series tag     | slideprone          | SLIDEPRONE          | text       | text        |
| Yes      | series tag     | retainwallmatrl     | RETAINWALLMATRL     | text       | text        |
| Yes      | numeric metric | retainwallmaxht     | RETAINWALLMAXHT     | number     | number      |
| Yes      | numeric metric | retainwallminht     | RETAINWALLMINHT     | number     | number      |
| Yes      | numeric metric | retainwalllngth     | RETAINWALLLNGTH     | number     | number      |
| No       |                | shape               | Shape               | geospatial | geospatial  |
| Yes      | series tag     | primarydistrictcd   | PRIMARYDISTRICTCD   | text       | text        |
| Yes      | series tag     | secondarydistrictcd | SECONDARYDISTRICTCD | text       | text        |
| Yes      | series tag     | overrideyn          | OVERRIDEYN          | text       | text        |
| Yes      | series tag     | overridecomment     | OVERRIDECOMMENT     | text       | text        |
| Yes      | numeric metric | shape_length        | Shape_Length        | number     | number      |
```

## Time Field

```ls
Value = install_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = inspcompdate,shape
```

## Data Commands

```ls
series e:sxr8-c6r3 d:2017-04-21T07:34:46.882Z t:shape.longitude=-122.35080246799998 t:maintained_by=SDOT t:retainwallmatrl="Concrete Gravity" t:comptype=16 t:current_status=INSVC t:unitid=RTW-739 t:ownership=SDOT t:unitdesc_asset="FREMONT AVE N" t:shape.needs_recoding=false t:unitdesc_seg="FREMONT AVE N BETWEEN N 34TH ST AND FREMONT PL N" t:overrideyn=N t:primarydistrictcd=DISTRICT6 t:shape.latitude=47.65021678700003 t:objectid=1 t:unittype=RTW m:shape_length=62.313614238165 m:segkey=10485 m:retainwallmaxht=9 m:retainwalllngth=55 m:retainwallminht=2 m:compkey=513540

series e:sxr8-c6r3 d:1971-12-31T00:00:00.000Z t:shape.longitude=-122.31628637399996 t:maintained_by=PRIV t:retainwallmatrl=Rockery t:comptype=16 t:current_status=INSVC t:unitid=RTW-611A t:ownership=PRIV t:unitdesc_asset="NE 125TH ST BETWEEN 10TH AVE NE AND 11TH AVE NE" t:shape.needs_recoding=false t:unitdesc_seg="NE 125TH ST BETWEEN NE 125TH SR W ST AND 11TH AVE NE" t:overrideyn=N t:primarydistrictcd=DISTRICT5 t:shape.latitude=47.71933989300004 t:objectid=2 t:unittype=RTW m:shape_length=77.97590487458733 m:segkey=16480 m:retainwallmaxht=6 m:retainwalllngth=95 m:retainwallminht=2 m:compkey=513334

series e:sxr8-c6r3 d:2017-04-21T07:34:46.882Z t:shape.longitude=-122.34756169599996 t:retainwallmatrl=Rubble t:comptype=16 t:current_status=INSVC t:unitid=RTW-734 t:unitdesc_asset="N 63RD ST BETWEEN AURORA AND AURORA AVE N" t:shape.needs_recoding=false t:unitdesc_seg="N 63RD ST BETWEEN EAST GREEN LAKE WAY N AND WOODLAWN S AVE N" t:primarydistrictcd=DISTRICT6 t:overrideyn=N t:shape.latitude=47.67441245500004 t:objectid=3 t:unittype=RTW m:shape_length=64.07458076697651 m:segkey=15771 m:retainwallmaxht=3 m:retainwalllngth=80 m:retainwallminht=2 m:compkey=513533
```

## Meta Commands

```ls
metric m:compkey p:integer l:COMPKEY d:COMPKEY t:dataTypeName=number

metric m:segkey p:integer l:SEGKEY d:SEGKEY t:dataTypeName=number

metric m:retainwallrating p:double l:RETAINWALLRATING d:RETAINWALLRATING t:dataTypeName=number

metric m:inspectionkey p:integer l:INSPECTIONKEY d:INSPECTIONKEY t:dataTypeName=number

metric m:retainwallmaxht p:integer l:RETAINWALLMAXHT d:RETAINWALLMAXHT t:dataTypeName=number

metric m:retainwallminht p:integer l:RETAINWALLMINHT d:RETAINWALLMINHT t:dataTypeName=number

metric m:retainwalllngth p:integer l:RETAINWALLLNGTH d:RETAINWALLLNGTH t:dataTypeName=number

metric m:shape_length p:decimal l:Shape_Length d:Shape_Length t:dataTypeName=number

entity e:sxr8-c6r3 l:"SDOT Retaining Walls" t:url=https://data.seattle.gov/api/views/sxr8-c6r3

property e:sxr8-c6r3 t:meta.view v:id=sxr8-c6r3 v:category=Transportation v:averageRating=0 v:name="SDOT Retaining Walls"

property e:sxr8-c6r3 t:meta.view.license v:name="Public Domain"

property e:sxr8-c6r3 t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:sxr8-c6r3 t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | compkey | comptype | segkey | unitid   | unitdesc_asset                                  | unitdesc_seg                                                    | unittype | install_date | ownership | maintained_by | maintfinancialresp | current_status | retainwallrating                                  | retainwallcondition | inspectionkey | inspcompdate | slideprone | retainwallmatrl          | retainwallmaxht | retainwallminht | retainwalllngth | shape                                                                                                                                                                                                                                             | primarydistrictcd | secondarydistrictcd | overrideyn | overridecomment | shape_length                                       | 
| ======== | ======= | ======== | ====== | ======== | =============================================== | =============================================================== | ======== | ============ | ========= | ============= | ================== | ============== | ================================================= | =================== | ============= | ============ | ========== | ======================== | =============== | =============== | =============== | ================================================================================================================================================================================================================================================= | ================= | =================== | ========== | =============== | ================================================== | 
| 1        | 513540  | 16       | 10485  | RTW-739  | FREMONT AVE N                                   | FREMONT AVE N BETWEEN N 34TH ST AND FREMONT PL N                | RTW      |              | SDOT      | SDOT          |                    | INSVC          |                                                   |                     |               |              |            | Concrete Gravity         | 9               | 2               | 55              | [null, 47.65021678700003, -122.35080246799998, null, false, {paths=[[[-122.35080246799998, 47.65021678700003], [-122.35057757299995, 47.65018241400003], [-122.35057377799995, 47.65019722200003]]]}]                                             | DISTRICT6         |                     | N          |                 | 62.313614238165001779634621925652027130126953125   | 
| 2        | 513334  | 16       | 16480  | RTW-611A | NE 125TH ST BETWEEN 10TH AVE NE AND 11TH AVE NE | NE 125TH ST BETWEEN NE 125TH SR W ST AND 11TH AVE NE            | RTW      | 62985600     | PRIV      | PRIV          |                    | INSVC          |                                                   |                     |               |              |            | Rockery                  | 6               | 2               | 95              | [null, 47.71933989300004, -122.31628637399996, null, false, {paths=[[[-122.31628637399996, 47.71933989300004], [-122.31660307599998, 47.71934469900003]]]}]                                                                                       | DISTRICT5         |                     | N          |                 | 77.9759048745873286634378018788993358612060546875  | 
| 3        | 513533  | 16       | 15771  | RTW-734  | N 63RD ST BETWEEN AURORA AND AURORA AVE N       | N 63RD ST BETWEEN EAST GREEN LAKE WAY N AND WOODLAWN S AVE N    | RTW      |              |           |               |                    | INSVC          |                                                   |                     |               |              |            | Rubble                   | 3               | 2               | 80              | [null, 47.67441245500004, -122.34756169599996, null, false, {paths=[[[-122.34756169599996, 47.67441245500004], [-122.34739044599996, 47.67428024900005]]]}]                                                                                       | DISTRICT6         |                     | N          |                 | 64.0745807669765099490177817642688751220703125     | 
| 4        | 512637  | 16       | 21691  | RTW-003  | SW ADMIRAL WAY BETWEEN SPOKANE AND HANFORD      | SW ADMIRAL WAY BETWEEN SW ADMIRAL WY OFF RP AND SW CITY VIEW ST | RTW      | -694396800   | SDOT      | SDOT          |                    | INSVC          | 0                                                 | Not Rated           | 3294          | 1418391420   |            | Slab & Rail Construction | 11              | 6               | 1150            | [null, 47.57534620900003, -122.37477963999999, null, false, {paths=[[[-122.37477963999999, 47.57534620900003], [-122.37395885899997, 47.57430422300007]]]}]                                                                                       | DISTRICT1         |                     | N          |                 | 430.7047317753018660368979908525943756103515625    | 
| 5        | 513263  | 16       | 5055   | RTW-569  | 32ND AVE SW BETWEEN SW HOLLY AND SW WILLOW      | 32ND AVE SW BETWEEN SW MORGAN ST AND SW HOLLY ST                | RTW      |              |           |               |                    | INSVC          | 100                                               | Good                | 1331          | 946252800    |            | RC Reinforced Concrete   | 11              | 2               | 78              | [null, 47.54208529600004, -122.37372918799997, null, false, {paths=[[[-122.37372918799997, 47.54208529600004], [-122.37372765999999, 47.542122806000066], [-122.37379712899997, 47.542124244000036], [-122.37379184099996, 47.54215347400003]]]}] | DISTRICT1         |                     | N          |                 | 41.59507989069208377941322396509349346160888671875 | 
| 6        | 513227  | 16       | 8479   | RTW-534  | 8TH AVE W AT W/O W. LEE                         | 8TH AVE W BETWEEN W LEE ST AND W GALER ST                       | RTW      | -1514851200  |           |               |                    | INSVC          | 80                                                | Good                | 1315          | 944179200    |            | Concrete Gravity         | 5               | 2               | 12              | [null, 47.63165612700004, -122.36843593599997, null, false, {paths=[[[-122.36843593599997, 47.63165612700004], [-122.36843642199995, 47.63170625600003]]]}]                                                                                       | DISTRICT7         |                     | N          |                 | 18.285676894067592002102173864841461181640625      | 
| 7        | 512702  | 16       | 8788   | RTW-047D | 2313 ALKI (SEAWALL) AVE SW                      | ALKI AVE SW BETWEEN BONAIR DR SW AND 53RD AVE SW                | RTW      | -883699200   | PARK      | PARK          |                    | INSVC          | 71.2999999999999971578290569595992565155029296875 | Fair                | 1053          | 940896000    |            | Slab & Rail Construction | 4               | 4               | 125             | [null, 47.58333674000005, -122.40149438099996, null, false, {paths=[[[-122.40149438099996, 47.58333674000005], [-122.40182937099996, 47.583047865000026], [-122.40193571599997, 47.582970859000056]]]}]                                           | DISTRICT1         |                     | N          |                 | 172.375846859457254822700633667409420013427734375  | 
| 8        | 512738  | 16       | 10821  | RTW-074  | HARBOR AVE SW BETWEEN HINDS AND PORTER WAY      | HARBOR AVE SW BETWEEN SW HARBOR LN AND SW SPOKANE NR ST         | RTW      | -441936000   | SDOT      | SDOT          |                    | INSVC          | 80                                                | Good                | 3154          | 1417593120   |            | Slab & Rail Construction | 6               | 5               | 340             | [null, 47.57397522400004, -122.37104003399998, null, false, {paths=[[[-122.37104003399998, 47.57397522400004], [-122.37094150999997, 47.57329694100008]]]}]                                                                                       | DISTRICT1         |                     | N          |                 | 248.606335374187921161137637682259082794189453125  | 
| 9        | 512177  | 16       | 6093   | RTW-867  | 8830 39TH AVE SW                                | 39TH AVE SW BETWEEN SW TRENTON ST AND SW HENDERSON ST           | RTW      | 1230681600   | PRIV      | PRIV          |                    | INSVC          |                                                   |                     |               |              |            | Concrete Gravity         | 5               | 3               | 37              | [null, 47.52383198900003, -122.38136189399995, null, false, {paths=[[[-122.38136189399995, 47.52383198900003], [-122.38136207999997, 47.52373177800007]]]}]                                                                                       | DISTRICT1         |                     | N          |                 | 36.55351403308404911740581155754625797271728515625 | 
| 10       | 513055  | 16       | 19296  | RTW-374  | ANGELINE ST AT E RAINIER                        | S ANGELINE ST BETWEEN RAINIER AVE S AND 38TH AVE S              | RTW      |              |           |               |                    | INSVC          | 0                                                 | Not Rated           | 3634          | 1418461260   |            | RC Reinforced Concrete   | 11              | 11              | 0               | [null, 47.55953917100004, -122.28523725699995, null, false, {paths=[[[-122.28523725699995, 47.55953917100004], [-122.28529515899999, 47.55953626500008], [-122.28530968899997, 47.55960797400007]]]}]                                             | DISTRICT2         |                     | N          |                 | 40.7373019172619450500860693864524364471435546875  | 
```