# SDOT Curb Ramps

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-curb-ramps) |
| Metadata | [Link](https://data.seattle.gov/api/views/j3nx-ir4y) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/j3nx-ir4y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/j3nx-ir4y/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | j3nx-ir4y |
| Name | SDOT Curb Ramps |
| Category | Transportation |
| Tags | sdot asset status and condition report, assets |
| Created | 2016-04-18T16:16:50Z |
| Publication Date | 2016-04-22T15:33:38Z |

## Description

Displays the location and some attribute information about curb ramps in the City of Seattle.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | objectid            | OBJECTID            | text      | number      |
| Yes      | numeric metric | segkey              | SEGKEY              | number    | number      |
| Yes      | numeric metric | distance            | DISTANCE            | number    | number      |
| Yes      | numeric metric | width               | WIDTH               | number    | number      |
| Yes      | series tag     | seg_unitid          | SEG_UNITID          | text      | text        |
| Yes      | series tag     | seg_unitid2         | SEG_UNITID2         | text      | text        |
| Yes      | series tag     | seg_unitdesc        | SEG_UNITDESC        | text      | text        |
| Yes      | series tag     | sw_unitid           | SW_UNITID           | text      | text        |
| Yes      | series tag     | sw_stside           | SW_STSIDE           | text      | text        |
| Yes      | numeric metric | sw_compkey          | SW_COMPKEY          | number    | number      |
| Yes      | series tag     | sw_location         | SW_LOCATION         | text      | text        |
| Yes      | series tag     | category            | CATEGORY            | text      | text        |
| Yes      | series tag     | color               | COLOR               | text      | text        |
| No       |                | assessment_date     | ASSESSMENT_DATE     | date      | date        |
| Yes      | series tag     | condition           | CONDITION           | text      | text        |
| Yes      | series tag     | direction           | DIRECTION           | text      | text        |
| No       |                | install_date        | INSTALL_DATE        | date      | date        |
| Yes      | series tag     | installer           | INSTALLER           | text      | text        |
| Yes      | series tag     | model_type          | MODEL_TYPE          | text      | text        |
| Yes      | series tag     | style               | STYLE               | text      | text        |
| Yes      | numeric metric | ramp_width          | RAMP_WIDTH          | number    | number      |
| Yes      | series tag     | detect_warn_exist   | DETECT_WARN_EXIST   | text      | text        |
| Yes      | time           | verification_date   | VERIFICATION_DATE   | date      | date        |
| Yes      | series tag     | mef                 | MEF                 | text      | text        |
| Yes      | series tag     | primarydistrictcd   | PRIMARYDISTRICTCD   | text      | text        |
| Yes      | series tag     | secondarydistrictcd | SECONDARYDISTRICTCD | text      | text        |
| Yes      | series tag     | overrideyn          | OVERRIDEYN          | text      | text        |
| Yes      | series tag     | overridecomment     | OVERRIDECOMMENT     | text      | text        |
| Yes      | series tag     | ramporientationcd   | RAMPORIENTATIONCD   | text      | text        |
| Yes      | series tag     | warnmaterialcd      | WARNMATERIALCD      | text      | text        |
| Yes      | series tag     | warnmounttypecd     | WARNMOUNTTYPECD     | text      | text        |
| Yes      | series tag     | current_status      | CURRENT_STATUS      | text      | text        |
| No       |                | current_status_date | CURRENT_STATUS_DATE | date      | date        |
```

## Time Field

```ls
Value = verification_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = install_date,assessment_date,current_status_date
```

## Data Commands

```ls
series e:j3nx-ir4y d:2015-11-12T00:00:00.000Z t:warnmounttypecd=SUFMT t:warnmaterialcd=PLASTIC t:mef=N t:sw_stside=W t:condition=FAIR t:direction=S t:seg_unitdesc="ROOSEVELT WAY NE BETWEEN NE 98TH ST AND NE 100TH ST" t:seg_unitid=09485 t:sw_unitid=SDW-15071 t:sw_location=L t:current_status=INSVC t:detect_warn_exist=Y t:seg_unitid2=0980 t:category=SINGLE t:style=TYPE422A t:color=YLW t:overrideyn=N t:primarydistrictcd=DISTRICT5 t:objectid=1 m:sw_compkey=308439 m:distance=23 m:segkey=12646 m:ramp_width=49 m:width=30.5

series e:j3nx-ir4y d:2015-09-23T00:00:00.000Z t:warnmounttypecd=SUFMT t:warnmaterialcd=PLASTIC t:mef=N t:sw_stside=E t:condition=GOOD t:direction=SW t:seg_unitdesc="6TH AVE NW BETWEEN NW 76TH ST AND NW 77TH ST" t:seg_unitid=04450 t:sw_unitid=SDW-13995 t:sw_location=L t:current_status=INSVC t:detect_warn_exist=Y t:seg_unitid2=0760 t:category=SHARED t:style=TYPE422A t:color=YLW t:overrideyn=N t:primarydistrictcd=DISTRICT6 t:objectid=2 m:sw_compkey=307967 m:distance=13 m:segkey=7952 m:ramp_width=48 m:width=-20.5

series e:j3nx-ir4y d:2015-09-23T00:00:00.000Z t:warnmounttypecd=SUFMT t:warnmaterialcd=PLASTIC t:mef=N t:sw_stside=W t:condition=GOOD t:direction=NE t:seg_unitdesc="6TH AVE NW BETWEEN NW 75TH ST AND NW 76TH ST" t:seg_unitid=04450 t:sw_unitid=SDW-40837 t:sw_location=H t:current_status=INSVC t:detect_warn_exist=Y t:seg_unitid2=0750 t:category=SHARED t:style=TYPE422A t:color=YLW t:overrideyn=N t:primarydistrictcd=DISTRICT6 t:objectid=3 m:sw_compkey=307961 m:distance=254 m:segkey=7951 m:ramp_width=48 m:width=20.5
```

## Meta Commands

```ls
metric m:segkey p:integer l:SEGKEY d:SEGKEY t:dataTypeName=number

metric m:distance p:integer l:DISTANCE d:DISTANCE t:dataTypeName=number

metric m:width p:float l:WIDTH d:WIDTH t:dataTypeName=number

metric m:sw_compkey p:integer l:SW_COMPKEY d:SW_COMPKEY t:dataTypeName=number

metric m:ramp_width p:integer l:RAMP_WIDTH d:RAMP_WIDTH t:dataTypeName=number

entity e:j3nx-ir4y l:"SDOT Curb Ramps" t:url=https://data.seattle.gov/api/views/j3nx-ir4y

property e:j3nx-ir4y t:meta.view v:id=j3nx-ir4y v:category=Transportation v:averageRating=0 v:name="SDOT Curb Ramps"

property e:j3nx-ir4y t:meta.view.license v:name="Public Domain"

property e:j3nx-ir4y t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:j3nx-ir4y t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | segkey | distance | width | seg_unitid | seg_unitid2 | seg_unitdesc                                        | sw_unitid | sw_stside | sw_compkey | sw_location | category | color | assessment_date | condition | direction | install_date | installer | model_type | style    | ramp_width | detect_warn_exist | verification_date | mef | primarydistrictcd | secondarydistrictcd | overrideyn | overridecomment | ramporientationcd | warnmaterialcd | warnmounttypecd | current_status | current_status_date | 
| ======== | ====== | ======== | ===== | ========== | =========== | =================================================== | ========= | ========= | ========== | =========== | ======== | ===== | =============== | ========= | ========= | ============ | ========= | ========== | ======== | ========== | ================= | ================= | === | ================= | =================== | ========== | =============== | ================= | ============== | =============== | ============== | =================== | 
| 1        | 12646  | 23       | 30.5  | 09485      | 0980        | ROOSEVELT WAY NE BETWEEN NE 98TH ST AND NE 100TH ST | SDW-15071 | W         | 308439     | L           | SINGLE   | YLW   | 1447286400      | FAIR      | S         | 1176336000   |           |            | TYPE422A | 49         | Y                 | 1447286400        | N   | DISTRICT5         |                     | N          |                 |                   | PLASTIC        | SUFMT           | INSVC          | 1447286400          | 
| 2        | 7952   | 13       | -20.5 | 04450      | 0760        | 6TH AVE NW BETWEEN NW 76TH ST AND NW 77TH ST        | SDW-13995 | E         | 307967     | L           | SHARED   | YLW   | 1442966400      | GOOD      | SW        |              |           |            | TYPE422A | 48         | Y                 | 1442966400        | N   | DISTRICT6         |                     | N          |                 |                   | PLASTIC        | SUFMT           | INSVC          | 1442966400          | 
| 3        | 7951   | 254      | 20.5  | 04450      | 0750        | 6TH AVE NW BETWEEN NW 75TH ST AND NW 76TH ST        | SDW-40837 | W         | 307961     | H           | SHARED   | YLW   | 1442966400      | GOOD      | NE        |              |           |            | TYPE422A | 48         | Y                 | 1442966400        | N   | DISTRICT6         |                     | N          |                 |                   | PLASTIC        | SUFMT           | INSVC          | 1442966400          | 
| 4        | 1589   | 545      | -27.5 | 00330      | 0730        | 12TH AVE NE BETWEEN NE 73RD ST AND NE 75TH ST       | SDW-41316 | E         | 308188     | H           | SINGLE   | YLW   | 1444694400      | GOOD      | N         |              |           |            | TYPE422A | 48         | Y                 | 1444694400        | N   | DISTRICT4         |                     | N          |                 |                   | PLASTIC        | SUFMT           | INSVC          | 1444694400          | 
| 5        | 1590   | 13       | 25.5  | 00330      | 0750        | 12TH AVE NE BETWEEN NE 75TH ST AND NE 77TH ST       | SDW-16718 | W         | 308185     | L           | SINGLE   | YLW   | 1444694400      | GOOD      | S         |              |           |            | TYPE422A | 36         | Y                 | 1444694400        | N   | DISTRICT4         |                     | N          |                 |                   | PLASTIC        | SUFMT           | INSVC          | 1444694400          | 
| 6        | 4488   | 42       | 25.5  | 02095      | 1010        | 3RD AVE NW BETWEEN NW 101ST ST AND HOLMAN RD NW     | SDW-13990 | W         | 307960     | H           | SHARED   | YLW   | 1444003200      | GOOD      | NE        |              |           |            | TYPE422A | 60         | Y                 | 1444003200        | Y   | DISTRICT6         |                     | N          |                 |                   | PLASTIC        | SUFMT           | INSVC          | 1444003200          | 
| 7        | 7959   | 13       | 20.5  | 04450      | 0830        | 6TH AVE NW BETWEEN NW 83RD ST AND NW 84TH ST        | SDW-13997 | W         | 307970     | L           | SINGLE   |       | 1442966400      | FAIR      | S         |              |           |            | TYPE422A | 36         | N                 | 1442966400        | N   | DISTRICT6         |                     | N          |                 |                   |                |                 | INSVC          | 1442966400          | 
| 8        | 3562   | 309      | 20.5  | 01480      | 0470        | 24TH AVE NE BETWEEN NE 47TH ST AND NE 48TH ST       | SDW-40638 | W         | 307751     | H           | SHARED   |       | 1443657600      | FAIR      | N         |              |           |            | TYPE422A | 37         | N                 | 1443657600        | N   | DISTRICT4         |                     | N          |                 |                   |                |                 | INSVC          | 1443657600          | 
| 9        | 4466   | 15       | 21.5  | 02095      | 0740        | 3RD AVE NW BETWEEN NW 74TH ST AND NW 75TH ST        | SDW-40836 | W         | 307958     | L           | SINGLE   |       | 1442966400      | FAIR      | S         |              |           |            | TYPE422A | 36         | N                 | 1442966400        | N   | DISTRICT6         |                     | N          |                 |                   |                |                 | INSVC          | 1442966400          | 
| 10       | 1584   | 233      | 30.5  | 00330      | 0690        | 12TH AVE NE BETWEEN NE 69TH ST AND NE 70TH ST       | SDW-16725 | W         | 308194     | H           | SINGLE   |       | 1444003200      | GOOD      | N         |              |           |            | TYPE422A | 36         | N                 | 1444003200        | N   | DISTRICT4         |                     | N          |                 |                   |                |                 | INSVC          | 1444003200          | 
```