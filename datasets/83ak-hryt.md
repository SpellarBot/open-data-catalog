# SDOT Crash Cushions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-crash-cushions) |
| Metadata | [Link](https://data.seattle.gov/api/views/83ak-hryt) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/83ak-hryt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/83ak-hryt/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 83ak-hryt |
| Name | SDOT Crash Cushions |
| Category | Transportation |
| Tags | transportation, street, sdot asset status and condition report, assets |
| Created | 2016-04-19T15:28:59Z |
| Publication Date | 2016-04-22T15:34:13Z |

## Description

Displays the location and attributes of crash cushions in the City of Seattle.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | objectid                  | OBJECTID                  | text      | number      |
| Yes      | numeric metric | intr_compkey              | INTR_COMPKEY              | number    | number      |
| Yes      | series tag     | intr_unitid               | INTR_UNITID               | text      | text        |
| Yes      | numeric metric | intr_distance             | INTR_DISTANCE             | number    | number      |
| Yes      | series tag     | description               | DESCRIPTION               | text      | text        |
| Yes      | numeric metric | seg_compkey               | SEG_COMPKEY               | number    | number      |
| Yes      | series tag     | location                  | LOCATION                  | text      | text        |
| Yes      | series tag     | assetid                   | ASSETID                   | text      | text        |
| Yes      | series tag     | unitid                    | UNITID                    | text      | text        |
| Yes      | series tag     | comptype                  | COMPTYPE                  | text      | number      |
| Yes      | numeric metric | compkey                   | COMPKEY                   | number    | number      |
| Yes      | numeric metric | hansegkey                 | HANSEGKEY                 | number    | number      |
| Yes      | series tag     | unittype                  | UNITTYPE                  | text      | text        |
| Yes      | series tag     | unitdesc_crs              | UNITDESC_CRS              | text      | text        |
| Yes      | series tag     | unitdesc_seg              | UNITDESC_SEG              | text      | text        |
| No       |                | install_date              | INSTALL_DATE              | date      | date        |
| Yes      | series tag     | addby                     | ADDBY                     | text      | text        |
| Yes      | time           | adddttm                   | ADDDTTM                   | date      | date        |
| Yes      | series tag     | modby                     | MODBY                     | text      | text        |
| No       |                | moddttm                   | MODDTTM                   | date      | date        |
| No       |                | expdate                   | EXPDATE                   | date      | date        |
| Yes      | series tag     | maintby                   | MAINTBY                   | text      | text        |
| Yes      | series tag     | current_status            | CURRENT_STATUS            | text      | text        |
| No       |                | current_status_date       | CURRENT_STATUS_DATE       | date      | date        |
| Yes      | series tag     | condition                 | CONDITION                 | text      | text        |
| No       |                | condition_assessment_date | CONDITION_ASSESSMENT_DATE | date      | date        |
| Yes      | series tag     | ownership                 | OWNERSHIP                 | text      | text        |
| No       |                | ownership_date            | OWNERSHIP_DATE            | date      | date        |
| Yes      | series tag     | primarydistrictcd         | PRIMARYDISTRICTCD         | text      | text        |
| Yes      | series tag     | secondarydistrictcd       | SECONDARYDISTRICTCD       | text      | text        |
| Yes      | series tag     | overrideyn                | OVERRIDEYN                | text      | text        |
| Yes      | series tag     | overridecomment           | OVERRIDECOMMENT           | text      | text        |
| Yes      | series tag     | subarea                   | SUBAREA                   | text      | text        |
| Yes      | series tag     | crstype                   | CRSTYPE                   | text      | text        |
| Yes      | series tag     | crsdesc                   | CRSDESC                   | text      | text        |
| Yes      | series tag     | trafdir                   | TRAFDIR                   | text      | text        |
| Yes      | series tag     | bckstpwid                 | BCKSTPWID                 | text      | number      |
| Yes      | numeric metric | nbrofbays                 | NBROFBAYS                 | number    | number      |
| Yes      | numeric metric | spdlimit                  | SPDLIMIT                  | number    | number      |
```

## Time Field

```ls
Value = adddttm
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = install_date,moddttm,expdate,current_status_date,condition_assessment_date,ownership_date
```

## Data Commands

```ls
series e:83ak-hryt d:2009-08-26T00:00:00.000Z t:subarea=GRDWM t:addby=ALRASHL t:trafdir=W t:comptype=16 t:unitdesc_crs="WEST SEATTLE BR WB AND WSB-WB SPOK-NR RP" t:current_status=REMOVED t:crsdesc=QuadGuard t:modby=BURNSW t:crstype=QUAD t:ownership=SDOT t:unitid=CRS-11 t:overrideyn=N t:primarydistrictcd=DISTRICT2 t:objectid=1 t:unittype=CRS t:assetid=CC001 t:maintby=SDOT t:bckstpwid=91 m:hansegkey=1 m:spdlimit=35 m:compkey=506262 m:nbrofbays=7

series e:83ak-hryt d:2009-08-28T00:00:00.000Z t:subarea=DLRD t:addby=ALRASHL t:condition=GOOD t:trafdir=S t:comptype=16 t:unitdesc_crs="1ST AV S OFF RP AND SR509 SB" t:current_status=INSVC t:modby=BURNSW t:crsdesc=Hex-Foam t:crstype=HEX t:ownership=SDOT t:unitid=CRS-21 t:overrideyn=N t:primarydistrictcd=DISTRICT1 t:objectid=2 t:unittype=CRS t:assetid=CC015 t:maintby=SDOT t:bckstpwid=24 m:hansegkey=1 m:spdlimit=60 m:compkey=506425 m:nbrofbays=7

series e:83ak-hryt d:2009-08-31T00:00:00.000Z t:subarea=BLRD t:addby=ALRASHL t:condition=GOOD t:trafdir=N t:comptype=16 t:unitdesc_crs="BALLARD BR AND BALLARD BR OFF RP" t:current_status=INSVC t:modby=ALRASHL t:crsdesc=TAU-II t:crstype=TAU-II t:ownership=SDOT t:unitid=CRS-34 t:overrideyn=N t:primarydistrictcd=DISTRICT6 t:objectid=3 t:unittype=CRS t:assetid=CC030 t:maintby=SDOT t:bckstpwid=30 m:hansegkey=1 m:spdlimit=30 m:compkey=506581 m:nbrofbays=3
```

## Meta Commands

```ls
metric m:intr_compkey p:long l:INTR_COMPKEY d:INTR_COMPKEY t:dataTypeName=number

metric m:intr_distance p:long l:INTR_DISTANCE d:INTR_DISTANCE t:dataTypeName=number

metric m:seg_compkey p:long l:SEG_COMPKEY d:SEG_COMPKEY t:dataTypeName=number

metric m:compkey p:integer l:COMPKEY d:COMPKEY t:dataTypeName=number

metric m:hansegkey p:integer l:HANSEGKEY d:HANSEGKEY t:dataTypeName=number

metric m:nbrofbays p:integer l:NBROFBAYS d:NBROFBAYS t:dataTypeName=number

metric m:spdlimit p:integer l:SPDLIMIT d:SPDLIMIT t:dataTypeName=number

entity e:83ak-hryt l:"SDOT Crash Cushions" t:url=https://data.seattle.gov/api/views/83ak-hryt

property e:83ak-hryt t:meta.view v:id=83ak-hryt v:category=Transportation v:averageRating=0 v:name="SDOT Crash Cushions"

property e:83ak-hryt t:meta.view.license v:name="Public Domain"

property e:83ak-hryt t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:83ak-hryt t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | intr_compkey | intr_unitid | intr_distance | description | seg_compkey | location | assetid | unitid | comptype | compkey | hansegkey | unittype | unitdesc_crs                             | unitdesc_seg                                     | install_date | addby   | adddttm    | modby    | moddttm    | expdate    | maintby | current_status | current_status_date | condition | condition_assessment_date | ownership | ownership_date | primarydistrictcd | secondarydistrictcd | overrideyn | overridecomment | subarea | crstype | crsdesc     | trafdir | bckstpwid | nbrofbays | spdlimit | 
| ======== | ============ | =========== | ============= | =========== | =========== | ======== | ======= | ====== | ======== | ======= | ========= | ======== | ======================================== | ================================================ | ============ | ======= | ========== | ======== | ========== | ========== | ======= | ============== | =================== | ========= | ========================= | ========= | ============== | ================= | =================== | ========== | =============== | ======= | ======= | =========== | ======= | ========= | ========= | ======== | 
| 1        |              |             |               |             |             |          | CC001   | CRS-11 | 16       | 506262  | 1         | CRS      | WEST SEATTLE BR WB AND WSB-WB SPOK-NR RP |                                                  |              | ALRASHL | 1251244800 | BURNSW   | 1455667200 | 1455667200 | SDOT    | REMOVED        | 1455667200          |           | 1455667200                | SDOT      |                | DISTRICT2         |                     | N          |                 | GRDWM   | QUAD    | QuadGuard   | W       | 91        | 7         | 35       | 
| 2        |              |             |               |             |             |          | CC015   | CRS-21 | 16       | 506425  | 1         | CRS      | 1ST AV S OFF RP AND SR509 SB             |                                                  |              | ALRASHL | 1251417600 | BURNSW   | 1455062400 |            | SDOT    | INSVC          | 1454457600          | GOOD      | 1454457600                | SDOT      |                | DISTRICT1         |                     | N          |                 | DLRD    | HEX     | Hex-Foam    | S       | 24        | 7         | 60       | 
| 3        |              |             |               |             |             |          | CC030   | CRS-34 | 16       | 506581  | 1         | CRS      | BALLARD BR AND BALLARD BR OFF RP         |                                                  |              | ALRASHL | 1251676800 | ALRASHL  | 1298851200 |            | SDOT    | INSVC          | 1453420800          | GOOD      | 1453420800                | SDOT      |                | DISTRICT6         |                     | N          |                 | BLRD    | TAU-II  | TAU-II      | N       | 30        | 3         | 30       | 
| 4        |              |             |               |             |             |          | CC025   | CRS-29 | 16       | 506551  | 1         | CRS      | AURORA AVE N AND BRIDGE WAY N            |                                                  |              | ALRASHL | 1251676800 | BURNSW   | 1326931200 |            | SDOT    | INSVC          | 1453507200          | GOOD      | 1453507200                | SDOT      |                | DISTRICT4         | DISTRICT6           | N          |                 | LKUN    | TAU-II  | TAU-II      | N       | 60        | 3         | 40       | 
| 5        |              |             |               |             |             |          | CC038   | CRS-9  | 16       | 506233  | 1         | CRS      | MAGNOLIA BR AND W GARFIELD ST OFF RP     |                                                  |              | ALRASHL | 1251244800 | PHILLID1 | 1469059200 |            | SDOT    | INSVC          | 1459728000          | FAIR      | 1459728000                | SDOT      |                | DISTRICT7         |                     | N          |                 | MGNL-QA | TAU-II  | TAU-II      | W       | 63        | 3         | 30       | 
| 6        |              |             |               |             |             |          | CC018   | CRS-24 | 16       | 506434  | 1         | CRS      | ALASKAN WY VI NB AND EAST MARGINAL WAY S |                                                  |              | ALRASHL | 1251417600 | BURNSW   | 1455580800 |            | SDOT    | INSVC          | 1454630400          | GOOD      | 1454630400                | SDOT      |                | DISTRICT2         |                     | N          |                 | GRDWM   | TAU-II  | TAU-II      | N       | 6         | 8         | 40       | 
| 7        |              |             |               |             |             |          | CC023   | CRS-27 | 16       | 506541  | 1         | CRS      | ALASKAN WY VI SB AND S SPOKANE ST RP     |                                                  |              | ALRASHL | 1251676800 | BURNSW   | 1455580800 |            | SDOT    | INSVC          | 1454716800          | GOOD      | 1454716800                | SDOT      |                | DISTRICT2         |                     | N          |                 | GRDWM   | TAU-II  | TAU-II      | S       | 90        | 5         | 50       | 
| 8        |              |             |               |             |             |          | CC016   | CRS-22 | 16       | 506428  | 6244      | CRS      | 4TH AVE S AND 4TH AV S OFF RP            | 4TH AVE S BETWEEN S HINDS ST AND S SPOKANE NR ST |              | ALRASHL | 1251417600 | KLARNEE  | 1447286400 | 1447286400 | SDOT    | REMOVED        | 1447286400          | GOOD      | 1203379200                | SDOT      |                |                   |                     | N          |                 | GRDWM   | HEXII   | Hex-Foam II | S       | 24        | 5         | 35       | 
| 9        |              |             |               |             |             |          | CC019   | CRS-25 | 16       | 506537  | 1         | CRS      | ALASKAN WY VI NB AND SENECA ST OFF RP    |                                                  | 1086393600   | ALRASHL | 1251676800 | ALRASHL  | 1304467200 |            | SDOT    | INSVC          | 1453593600          | GOOD      | 1453593600                | SDOT      |                | DISTRICT7         |                     | N          |                 | DWNTN   | TAU-II  | TAU-II      | N       | 132       | 4         | 50       | 
| 10       |              |             |               |             |             |          | CC017   | CRS-23 | 16       | 506429  | 1         | CRS      | ALASKAN WY VI NB AND EAST MARGINAL WAY S |                                                  |              | ALRASHL | 1251417600 | PHILLID1 | 1469059200 |            | SDOT    | INSVC          | 1454284800          | GOOD      | 1454284800                | SDOT      |                | DISTRICT2         |                     | N          |                 | GRDWM   | TAU-II  | TAU-II      | N       | 33        | 8         | 45       | 
```