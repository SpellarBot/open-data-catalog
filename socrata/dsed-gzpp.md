# SDOT Sidewalks

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-sidewalks-1e9c2) |
| Metadata | [Link](https://data.seattle.gov/api/views/dsed-gzpp) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/dsed-gzpp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/dsed-gzpp/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | dsed-gzpp |
| Name | SDOT Sidewalks |
| Category | Transportation |
| Tags | seattle, streets, sdot, transporation, sidewalks, sdot asset status and condition report, assets |
| Created | 2016-06-14T23:09:55Z |
| Publication Date | 2016-06-15T19:52:25Z |

## Description

Displays the location and some attribute information for Seattle sidewalks managed by SDOT.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type  | Render Type |
| ======== | ============== | ========================== | ========================== | ========== | =========== |
| Yes      | series tag     | objectid                   | OBJECTID                   | text       | number      |
| Yes      | numeric metric | compkey                    | COMPKEY                    | number     | number      |
| Yes      | series tag     | comptype                   | COMPTYPE                   | text       | number      |
| Yes      | numeric metric | segkey                     | SEGKEY                     | number     | number      |
| Yes      | numeric metric | distance                   | DISTANCE                   | number     | number      |
| Yes      | numeric metric | enddistance                | ENDDISTANCE                | number     | number      |
| Yes      | numeric metric | width                      | WIDTH                      | number     | number      |
| Yes      | series tag     | unitid                     | UNITID                     | text       | text        |
| Yes      | series tag     | unittype                   | UNITTYPE                   | text       | text        |
| Yes      | series tag     | unitdesc                   | UNITDESC                   | text       | text        |
| Yes      | series tag     | addby                      | ADDBY                      | text       | text        |
| Yes      | time           | adddttm                    | ADDDTTM                    | date       | date        |
| Yes      | series tag     | asblt                      | ASBLT                      | text       | text        |
| Yes      | series tag     | condition                  | CONDITION                  | text       | text        |
| No       |                | condition_assessment_date  | CONDITION_ASSESSMENT_DATE  | date       | date        |
| Yes      | series tag     | curbtype                   | CURBTYPE                   | text       | text        |
| Yes      | series tag     | current_status             | CURRENT_STATUS             | text       | text        |
| No       |                | current_status_date        | CURRENT_STATUS_DATE        | date       | date        |
| Yes      | series tag     | fillertype                 | FILLERTYPE                 | text       | text        |
| Yes      | series tag     | fillerwid                  | FILLERWID                  | text       | number      |
| No       |                | install_date               | INSTALL_DATE               | date       | date        |
| Yes      | numeric metric | hansen_rpt_mvw_gis_sdw_len | HANSEN_RPT_MVW_GIS_SDW_LEN | number     | number      |
| Yes      | series tag     | lenuom                     | LENUOM                     | text       | text        |
| Yes      | numeric metric | sw_width                   | SW_WIDTH                   | number     | number      |
| Yes      | series tag     | maintained_by              | MAINTAINED_BY              | text       | text        |
| Yes      | series tag     | matl                       | MATL                       | text       | text        |
| Yes      | series tag     | modby                      | MODBY                      | text       | text        |
| No       |                | moddttm                    | MODDTTM                    | date       | date        |
| Yes      | series tag     | ownership                  | OWNERSHIP                  | text       | text        |
| Yes      | series tag     | side                       | SIDE                       | text       | text        |
| Yes      | series tag     | surftype                   | SURFTYPE                   | text       | text        |
| Yes      | series tag     | buildercd                  | BUILDERCD                  | text       | text        |
| Yes      | series tag     | invalidswrecordyn          | INVALIDSWRECORDYN          | text       | text        |
| Yes      | series tag     | maintbyrdwystructyn        | MAINTBYRDWYSTRUCTYN        | text       | text        |
| Yes      | series tag     | notswcandidateyn           | NOTSWCANDIDATEYN           | text       | text        |
| Yes      | series tag     | swincompleteyn             | SWINCOMPLETEYN             | text       | text        |
| Yes      | numeric metric | incstpointlowend           | INCSTPOINTLOWEND           | number     | number      |
| Yes      | series tag     | incstpointunknown          | INCSTPOINTUNKNOWN          | text       | text        |
| Yes      | series tag     | multiplesurfaceyn          | MULTIPLESURFACEYN          | text       | text        |
| Yes      | series tag     | gsitypecd                  | GSITYPECD                  | text       | text        |
| Yes      | series tag     | hansen7id                  | HANSEN7ID                  | text       | text        |
| No       |                | date_mvw_last_updated      | DATE_MVW_LAST_UPDATED      | date       | date        |
| No       |                | shape                      | Shape                      | geospatial | geospatial  |
| Yes      | series tag     | primarydistrictcd          | PRIMARYDISTRICTCD          | text       | text        |
| Yes      | series tag     | secondarydistrictcd        | SECONDARYDISTRICTCD        | text       | text        |
| Yes      | series tag     | overrideyn                 | OVERRIDEYN                 | text       | text        |
| Yes      | series tag     | overridecomment            | OVERRIDECOMMENT            | text       | text        |
| Yes      | series tag     | curbramphigh               | CURBRAMPHIGH               | text       | text        |
| Yes      | series tag     | curbrampmid                | CURBRAMPMID                | text       | text        |
| Yes      | series tag     | curbramplow                | CURBRAMPLOW                | text       | text        |
| Yes      | numeric metric | srts_sidewalk_rank         | SRTS_SIDEWALK_RANK         | number     | number      |
| Yes      | numeric metric | shape_length               | Shape_Length               | number     | number      |
```

## Time Field

```ls
Value = adddttm
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = condition_assessment_date,current_status_date,install_date,moddttm,date_mvw_last_updated,shape
```

## Data Commands

```ls
series e:dsed-gzpp d:2007-09-26T17:17:34.000Z t:shape.longitude=-122.39031873999994 t:curbramplow=Y t:addby="SW DATA LOAD" t:comptype=97 t:curbtype=410C t:invalidswrecordyn=N t:lenuom=Feet t:notswcandidateyn=N t:incstpointunknown=N t:unitdesc="SW OTHELLO ST BETWEEN 45TH AVE SW AND BLAKE PL SW, N SIDE" t:unitid=SDW-27678 t:side=N t:shape.needs_recoding=false t:shape.latitude=47.538070151000056 t:unittype=SDW t:swincompleteyn=N t:multiplesurfaceyn=N t:hansen7id=180750450N t:surftype=PCC t:curbramphigh=U t:fillerwid=16 t:current_status=INSVC t:maintbyrdwystructyn=N t:primarydistrictcd=DISTRICT1 t:overrideyn=N t:objectid=1 t:fillertype=LSCP t:curbrampmid=U m:shape_length=127.1745673604235 m:enddistance=141 m:distance=13 m:segkey=22700 m:srts_sidewalk_rank=1 m:sw_width=60 m:width=-20.5 m:incstpointlowend=0 m:compkey=324669

series e:dsed-gzpp d:2007-09-26T17:17:34.000Z t:shape.longitude=-122.39094222499995 t:curbramplow=U t:addby="SW DATA LOAD" t:comptype=97 t:curbtype=410C t:invalidswrecordyn=N t:lenuom=Feet t:notswcandidateyn=N t:incstpointunknown=N t:unitdesc="SW OTHELLO ST BETWEEN BLAKE PL SW AND FAUNTLEROY WAY SW, N SIDE" t:unitid=SDW-27677 t:side=N t:shape.needs_recoding=false t:shape.latitude=47.53807365800003 t:unittype=SDW t:swincompleteyn=N t:multiplesurfaceyn=N t:hansen7id=180750455N t:surftype=PCC t:curbramphigh=Y t:fillerwid=16 t:current_status=INSVC t:maintbyrdwystructyn=N t:primarydistrictcd=DISTRICT1 t:overrideyn=N t:objectid=2 t:fillertype=LSCP t:curbrampmid=U m:shape_length=114.36099986096643 m:enddistance=128 m:distance=13 m:segkey=22701 m:srts_sidewalk_rank=1 m:sw_width=60 m:width=-20.5 m:incstpointlowend=0 m:compkey=324668

series e:dsed-gzpp d:2007-09-26T17:17:34.000Z t:shape.longitude=-122.39151345799996 t:curbramplow=U t:addby="SW DATA LOAD" t:comptype=97 t:curbtype=ROLLCB t:invalidswrecordyn=N t:lenuom=Feet t:notswcandidateyn=N t:incstpointunknown=N t:unitdesc="SW OTHELLO ST BETWEEN FAUNTLEROY WAY SW AND BAINBRIDGE PL SW, N SIDE" t:unitid=SDW-27676 t:side=N t:shape.needs_recoding=false t:shape.latitude=47.538077025000064 t:unittype=SDW t:swincompleteyn=N t:multiplesurfaceyn=N t:hansen7id=180750460N t:surftype=PCC t:curbramphigh=U t:fillerwid=30 t:current_status=INSVC t:maintbyrdwystructyn=N t:primarydistrictcd=DISTRICT1 t:overrideyn=N t:objectid=3 t:fillertype=PCC t:curbrampmid=U m:shape_length=85.41556978338008 m:enddistance=99 m:distance=13 m:segkey=22702 m:srts_sidewalk_rank=1 m:sw_width=60 m:width=-20.5 m:incstpointlowend=0 m:compkey=324667
```

## Meta Commands

```ls
metric m:compkey p:integer l:COMPKEY d:COMPKEY t:dataTypeName=number

metric m:segkey p:integer l:SEGKEY d:SEGKEY t:dataTypeName=number

metric m:distance p:integer l:DISTANCE d:DISTANCE t:dataTypeName=number

metric m:enddistance p:double l:ENDDISTANCE d:ENDDISTANCE t:dataTypeName=number

metric m:width p:float l:WIDTH d:WIDTH t:dataTypeName=number

metric m:hansen_rpt_mvw_gis_sdw_len p:long l:HANSEN_RPT_MVW_GIS_SDW_LEN d:HANSEN_RPT.MVW_GIS_SDW.LEN t:dataTypeName=number

metric m:sw_width p:integer l:SW_WIDTH d:SW_WIDTH t:dataTypeName=number

metric m:incstpointlowend p:integer l:INCSTPOINTLOWEND d:INCSTPOINTLOWEND t:dataTypeName=number

metric m:srts_sidewalk_rank p:integer l:SRTS_SIDEWALK_RANK d:SRTS_SIDEWALK_RANK t:dataTypeName=number

metric m:shape_length p:decimal l:Shape_Length d:Shape_Length t:dataTypeName=number

entity e:dsed-gzpp l:"SDOT Sidewalks" t:url=https://data.seattle.gov/api/views/dsed-gzpp

property e:dsed-gzpp t:meta.view v:id=dsed-gzpp v:category=Transportation v:averageRating=0 v:name="SDOT Sidewalks"

property e:dsed-gzpp t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:dsed-gzpp t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | compkey | comptype | segkey | distance | enddistance | width | unitid    | unittype | unitdesc                                                             | addby        | adddttm    | asblt | condition | condition_assessment_date | curbtype | current_status | current_status_date | fillertype | fillerwid | install_date | hansen_rpt_mvw_gis_sdw_len | lenuom | sw_width | maintained_by | matl | modby                 | moddttm    | ownership | side | surftype | buildercd | invalidswrecordyn | maintbyrdwystructyn | notswcandidateyn | swincompleteyn | incstpointlowend | incstpointunknown | multiplesurfaceyn | gsitypecd | hansen7id   | date_mvw_last_updated | shape                                                                                                                                                          | primarydistrictcd | secondarydistrictcd | overrideyn | overridecomment | curbramphigh | curbrampmid | curbramplow | srts_sidewalk_rank | shape_length                                       | 
| ======== | ======= | ======== | ====== | ======== | =========== | ===== | ========= | ======== | ==================================================================== | ============ | ========== | ===== | ========= | ========================= | ======== | ============== | =================== | ========== | ========= | ============ | ========================== | ====== | ======== | ============= | ==== | ===================== | ========== | ========= | ==== | ======== | ========= | ================= | =================== | ================ | ============== | ================ | ================= | ================= | ========= | =========== | ===================== | ============================================================================================================================================================== | ================= | =================== | ========== | =============== | ============ | =========== | =========== | ================== | ================================================== | 
| 1        | 324669  | 97       | 22700  | 13       | 141         | -20.5 | SDW-27678 | SDW      | SW OTHELLO ST BETWEEN 45TH AVE SW AND BLAKE PL SW, N SIDE            | SW DATA LOAD | 1190827054 |       |           |                           | 410C     | INSVC          | 1190827054          | LSCP       | 16        |              |                            | Feet   | 60       |               |      |                       |            |           | N    | PCC      |           | N                 | N                   | N                | N              | 0                | N                 | N                 |           | 180750450N  | 1492461209            | [null, 47.538070151000056, -122.39031873999994, null, false, {paths=[[[-122.39031873999994, 47.538070151000056], [-122.39083357999999, 47.53807304700007]]]}]  | DISTRICT1         |                     | N          |                 | U            | U           | Y           | 1                  | 127.1745673604234951881153392605483531951904296875 | 
| 2        | 324668  | 97       | 22701  | 13       | 128         | -20.5 | SDW-27677 | SDW      | SW OTHELLO ST BETWEEN BLAKE PL SW AND FAUNTLEROY WAY SW, N SIDE      | SW DATA LOAD | 1190827054 |       |           |                           | 410C     | INSVC          | 1190827054          | LSCP       | 16        |              |                            | Feet   | 60       |               |      |                       |            |           | N    | PCC      |           | N                 | N                   | N                | N              | 0                | N                 | N                 |           | 180750455N  | 1492461209            | [null, 47.53807365800003, -122.39094222499995, null, false, {paths=[[[-122.39094222499995, 47.53807365800003], [-122.39140519199998, 47.53807626200006]]]}]    | DISTRICT1         |                     | N          |                 | Y            | U           | U           | 1                  | 114.3609998609664302193777984939515590667724609375 | 
| 3        | 324667  | 97       | 22702  | 13       | 99          | -20.5 | SDW-27676 | SDW      | SW OTHELLO ST BETWEEN FAUNTLEROY WAY SW AND BAINBRIDGE PL SW, N SIDE | SW DATA LOAD | 1190827054 |       |           |                           | ROLLCB   | INSVC          | 1190827054          | PCC        | 30        |              |                            | Feet   | 60       |               |      |                       |            |           | N    | PCC      |           | N                 | N                   | N                | N              | 0                | N                 | N                 |           | 180750460N  | 1492461209            | [null, 47.538077025000064, -122.39151345799996, null, false, {paths=[[[-122.39151345799996, 47.538077025000064], [-122.39185922899998, 47.53807999500003]]]}]  | DISTRICT1         |                     | N          |                 | U            | U           | U           | 1                  | 85.415569783380078661139123141765594482421875      | 
| 4        | 324661  | 97       | 22707  | 13       | 155         | 20.5  | SDW-27670 | SDW      | SW OTHELLO ST BETWEEN LEDROIT CT SW AND VIEW LN SW, SE SIDE          | SW DATA LOAD | 1190827054 |       |           |                           | ROLLCB   | INSVC          | 1190827054          | PCC        | 30        |              |                            | Feet   | 60       |               |      |                       |            |           | SE   | PCC      |           | N                 | N                   | N                | N              | 0                | N                 | N                 |           | 180750482SE | 1492461209            | [null, 47.53771313300007, -122.39451804799995, null, false, {paths=[[[-122.39451804799995, 47.53771313300007], [-122.39498216999999, 47.53748677600004]]]}]    | DISTRICT1         |                     | N          |                 | U            | U           | U           | 1                  | 141.281511166420870040383306331932544708251953125  | 
| 5        | 324549  | 97       | 11877  | 27       | 426         | 22.5  | SDW-29025 | SDW      | MINOR AVE BETWEEN PIKE ST AND PINE ST, SW SIDE                       | SW DATA LOAD | 1190827054 |       | GOOD      | 1355270400                | 410C     | INSVC          | 1374624000          | LSCP       | 66        |              |                            | Feet   | 72       |               |      | POONK                 | 1374663252 |           | SW   | PCC      |           | N                 | N                   | N                | N              | 0                | N                 | N                 |           | 086650150SW | 1492461209            | [null, 47.61396056600006, -122.32793962599999, null, false, {paths=[[[-122.32793962599999, 47.61396056600006], [-122.32878926299998, 47.61488862300007]]]}]    | DISTRICT3         | DISTRICT7           | N          |                 | U            | Y           | Y           | 1                  | 398.137407098035282615455798804759979248046875     | 
| 6        | 324556  | 97       | 12049  | 26       | 302         | 28.5  | SDW-29032 | SDW      | OLIVE WAY BETWEEN BOREN AVE AND MINOR AVE, NW SIDE                   | SW DATA LOAD | 1190827054 |       | GOOD      | 1185926400                | MONO     | INSVC          | 1280575640          | TR/PCC     | 78        |              |                            | Feet   | 60       |               |      | SDW_CONDITION_UPDATES | 1280575604 |           | NW   | PCC      |           | N                 | N                   | N                | N              | 0                | N                 | N                 |           | 089500110NW | 1492461209            | [null, 47.615553532000035, -122.33070113399998, null, false, {paths=[[[-122.33070113399998, 47.615553532000035], [-122.32975270399999, 47.615950164000026]]]}] | DISTRICT7         |                     | N          |                 | Y            | U           | Y           | 3                  | 275.04721830272455918020568788051605224609375      | 
| 7        | 324451  | 97       | 22010  | 13       | 320         | -20.5 | SDW-27638 | SDW      | SW CLOVERDALE ST BETWEEN 32ND AVE SW AND 34TH AVE SW, N SIDE         | SW DATA LOAD | 1190827054 |       |           |                           | 410C     | INSVC          | 1190827054          | LSCP       | 120       |              |                            | Feet   | 60       |               |      |                       |            |           | N    | PCC      |           | N                 | N                   | N                | N              | 0                | N                 | N                 |           | 175400320N  | 1492461209            | [null, 47.526528263000046, -122.37399407899994, null, false, {paths=[[[-122.37399407899994, 47.526528263000046], [-122.375231311, 47.52652688900008]]]}]       | DISTRICT1         |                     | N          |                 | Y            | U           | U           | 1                  | 305.67572210215911354680429212749004364013671875   | 
| 8        | 324560  | 97       | 12047  | 23       | 299         | 30.5  | SDW-29036 | SDW      | OLIVE WAY BETWEEN 9TH AVE AND TERRY AVE, NW SIDE                     | SW DATA LOAD | 1190827054 |       | GOOD      | 1185926400                | MONO     | INSVC          | 1280534400          | NONE       | 0         |              |                            | Feet   | 140      |               |      | POONK                 | 1377010031 |           | NW   | PCC      |           | N                 | N                   | N                | N              | 0                | N                 | Y                 |           | 089500090NW | 1492461209            | [null, 47.61462523000006, -122.33293633499994, null, false, {paths=[[[-122.33293633499994, 47.61462523000006], [-122.33198792499996, 47.61502193600006]]]}]    | DISTRICT7         |                     | N          |                 | Y            | U           | Y           | 3                  | 275.06096786692779687655274756252765655517578125   | 
| 9        | 324564  | 97       | 12044  | 20       | 296         | -26.5 | SDW-29040 | SDW      | OLIVE WAY BETWEEN 6TH AVE AND 7TH AVE, SE SIDE                       | SW DATA LOAD | 1190827054 |       | GOOD      | 1185926400                | 410A     | INSVC          | 1280575640          | TR/PCC     | 68        |              |                            | Feet   | 106      |               |      | SDW_CONDITION_UPDATES | 1280575604 |           | SE   | PCC      |           | N                 | N                   | N                | N              | 0                | N                 | N                 |           | 089500060SE | 1492461209            | [null, 47.61309721500004, -122.33615651099996, null, false, {paths=[[[-122.33615651099996, 47.61309721500004], [-122.33520876799997, 47.61349489400004]]]}]    | DISTRICT7         |                     | N          |                 | Y            | U           | Y           | 3                  | 275.1140432778648801104282028973102569580078125    | 
| 10       | 324567  | 97       | 6590   | 13       | 413         | -20.5 | SDW-29042 | SDW      | 42ND AVE SW BETWEEN SW HINDS ST AND SW SPOKANE ST, W SIDE            | SW DATA LOAD | 1190827054 |       |           |                           | 410C     | INSVC          | 1190827054          | LSCP       | 108       |              |                            | Feet   | 72       |               |      |                       |            |           | W    | PCC      |           | N                 | N                   | N                | N              | 0                | N                 | N                 |           | 034200340W  | 1492461209            | [null, 47.573138820000054, -122.385753051, null, false, {paths=[[[-122.385753051, 47.573138820000054], [-122.38575443599996, 47.572046011000054]]]}]           | DISTRICT1         |                     | N          |                 | Y            | U           | U           | 1                  | 398.61850100580744538092403672635555267333984375   | 
```