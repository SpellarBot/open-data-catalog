# SDOT Street Signs [OLD]

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-street-signs-5bb4a) |
| Metadata | [Link](https://data.seattle.gov/api/views/kb3s-zi3z) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/kb3s-zi3z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/kb3s-zi3z/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | kb3s-zi3z |
| Name | SDOT Street Signs [OLD] |
| Category | Transportation |
| Tags | signs, streets, sdot, seattle, stop, parking, bike, route, regulation, speed limit, traffic, vision zero |
| Created | 2015-03-19T04:57:27Z |
| Publication Date | 2015-03-19T04:58:59Z |

## Description

THIS DATASET IS SET TO BE RETIRED. PLEASE USE THE DATASET AT THE FOLLOWING URL: https://data.seattle.gov/Transportation/SDOT-Street-Signs/atig-uucb

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | objectid            | OBJECTID            | text      | number      |
| Yes      | series tag     | unitid              | UNITID              | text      | text        |
| Yes      | series tag     | unittype            | UNITTYPE            | text      | text        |
| Yes      | series tag     | signtype            | SIGNTYPE            | text      | text        |
| Yes      | series tag     | category            | CATEGORY            | text      | text        |
| Yes      | series tag     | categorydescr       | CATEGORYDESCR       | text      | text        |
| Yes      | series tag     | unitdesc            | UNITDESC            | text      | text        |
| Yes      | series tag     | facing              | FACING              | text      | text        |
| Yes      | series tag     | support             | SUPPORT             | text      | text        |
| Yes      | series tag     | supportdescr        | SUPPORTDESCR        | text      | text        |
| Yes      | series tag     | color1              | COLOR1              | text      | text        |
| Yes      | series tag     | signsz              | SIGNSZ              | text      | text        |
| Yes      | series tag     | reflectiveyn        | REFLECTIVEYN        | text      | text        |
| Yes      | series tag     | fieldnotes          | FIELDNOTES          | text      | text        |
| Yes      | series tag     | custom              | CUSTOM              | text      | text        |
| Yes      | numeric metric | compkey             | COMPKEY             | number    | number      |
| Yes      | series tag     | comptype            | COMPTYPE            | text      | number      |
| Yes      | numeric metric | segkey              | SEGKEY              | number    | number      |
| Yes      | numeric metric | intkey              | INTKEY              | number    | number      |
| Yes      | numeric metric | elmntkey            | ELMNTKEY            | number    | number      |
| Yes      | numeric metric | distance            | DISTANCE            | number    | number      |
| Yes      | numeric metric | width               | WIDTH               | number    | number      |
| Yes      | numeric metric | supportkey          | SUPPORTKEY          | number    | number      |
| Yes      | series tag     | supportid           | SUPPORTID           | text      | text        |
| Yes      | series tag     | startday            | STARTDAY            | text      | text        |
| Yes      | series tag     | endday              | ENDDAY              | text      | text        |
| Yes      | series tag     | starttime           | STARTTIME           | text      | text        |
| Yes      | series tag     | endtime             | ENDTIME             | text      | text        |
| Yes      | series tag     | side                | SIDE                | text      | text        |
| Yes      | series tag     | ownership           | OWNERSHIP           | text      | text        |
| Yes      | series tag     | current_status      | CURRENT_STATUS      | text      | text        |
| Yes      | series tag     | condition           | CONDITION           | text      | text        |
| Yes      | series tag     | text                | TEXT                | text      | text        |
| Yes      | time           | adddttm             | ADDDTTM             | date      | date        |
| No       |                | moddttm             | MODDTTM             | date      | date        |
| No       |                | instdate            | INSTDATE            | date      | date        |
| No       |                | expdate             | EXPDATE             | date      | date        |
| Yes      | series tag     | primarydistrictcd   | PRIMARYDISTRICTCD   | text      | text        |
| Yes      | series tag     | secondarydistrictcd | SECONDARYDISTRICTCD | text      | text        |
| Yes      | series tag     | overrideyn          | OVERRIDEYN          | text      | text        |
| Yes      | series tag     | overridecomment     | OVERRIDECOMMENT     | text      | text        |
```

## Time Field

```ls
Value = adddttm
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = moddttm,instdate,expdate
```

## Data Commands

```ls
series e:kb3s-zi3z d:2012-05-16T00:00:00.000Z t:endtime=1800 t:supportid=SAS-61253 t:comptype=20 t:startday=1 t:categorydescr="Restricted Parking Zone permited parking" t:unitdesc="WESTLAKE EAST RDWY AVE N 0090 BLOCK NE SIDE ( 302) 302 FT NW/O ALOHA ST (R8-BL4Z25 -35W/R8PSX)" t:unitid=SGN-168347 t:side=NE t:unittype=01-RS t:endday=6 t:signsz=12X18 t:custom=N t:fieldnotes=-35W/R8PSX t:text="[CIRCLE P] 4 HOURS MAX PAY 9A-4P" t:support=TS-10 t:starttime=800 t:condition=GOOD t:current_status=INSVC t:category=PRZ t:ownership=SDOT t:supportdescr="Telespar Post - 10'" t:facing=W t:primarydistrictcd=DISTRICT7 t:overrideyn=N t:reflectiveyn=Y t:objectid=1 t:color1=WHITE/BLUE t:signtype=R8-BL4Z25 m:distance=302 m:segkey=13549 m:width=-29 m:intkey=1 m:elmntkey=36158 m:supportkey=414125 m:compkey=585127

series e:kb3s-zi3z d:2012-12-17T00:00:00.000Z t:endtime=2359 t:supportid=SAS-124399 t:comptype=20 t:startday=1 t:categorydescr="No Parking, but ""standing"" allowed" t:unitdesc="COLORADO AVE S 0150 BLOCK W SIDE ( 690) 44 FT N/O S MASSACHUSETTS ST (R7-NPLR )" t:unitid=SGN-172392 t:side=W t:unittype=01-RS t:endday=7 t:signsz=18X18 t:text="[SLASH OVER CIRCLE] P [LEFT & RIGHT ARROW]" t:support=CW t:starttime=0 t:current_status=INSVC t:category=PNP t:ownership=SDOT t:supportdescr="Concrete Wall or Column" t:facing=E t:primarydistrictcd=DISTRICT2 t:overrideyn=N t:reflectiveyn=N t:objectid=2 t:color1=RED/WHITE t:signtype=R7-NPLR m:distance=715 m:segkey=9704 m:width=-8 m:intkey=1 m:elmntkey=9737 m:supportkey=592667 m:compkey=592673

series e:kb3s-zi3z d:2012-12-05T00:00:00.000Z t:endtime=900 t:supportid=SAS-107538 t:comptype=20 t:startday=1 t:categorydescr="Peak Parking Restrictions, TOW" t:unitdesc="NW MARKET ST 0240 BLOCK S SIDE ( 134) 134 FT W/O 24TH AVE NW (R7-PKAB -11)" t:unitid=SGN-172279 t:side=S t:unittype=01-RS t:endday=5 t:signsz=12x18 t:custom=N t:fieldnotes=-11 t:text="NO PARKING 6-9 AM EXC SAT-SUN-HOL TAZ" t:support=LP t:starttime=600 t:condition=GOOD t:current_status=INSVC t:category=PPEAK t:ownership=SDOT t:supportdescr="SCL Light Post" t:facing=W t:primarydistrictcd=DISTRICT6 t:overrideyn=N t:reflectiveyn=N t:objectid=3 t:color1=R/W t:signtype=R7-PKAB m:distance=158 m:segkey=19236 m:width=31 m:intkey=1 m:elmntkey=41726 m:supportkey=530747 m:compkey=592353
```

## Meta Commands

```ls
metric m:compkey p:integer l:COMPKEY d:COMPKEY t:dataTypeName=number

metric m:segkey p:long l:SEGKEY d:SEGKEY t:dataTypeName=number

metric m:intkey p:long l:INTKEY d:INTKEY t:dataTypeName=number

metric m:elmntkey p:long l:ELMNTKEY d:ELMNTKEY t:dataTypeName=number

metric m:distance p:long l:DISTANCE d:DISTANCE t:dataTypeName=number

metric m:width p:long l:WIDTH d:WIDTH t:dataTypeName=number

metric m:supportkey p:long l:SUPPORTKEY d:SUPPORTKEY t:dataTypeName=number

entity e:kb3s-zi3z l:"SDOT Street Signs [OLD]" t:url=https://data.seattle.gov/api/views/kb3s-zi3z

property e:kb3s-zi3z t:meta.view v:id=kb3s-zi3z v:category=Transportation v:attributionLink=http://www.seattle.gov/transportation/ v:averageRating=0 v:name="SDOT Street Signs [OLD]"

property e:kb3s-zi3z t:meta.view.license v:name="Public Domain"

property e:kb3s-zi3z t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:kb3s-zi3z t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| objectid | unitid     | unittype | signtype  | category | categorydescr                                                                                      | unitdesc                                                                                       | facing | support | supportdescr            | color1     | signsz   | reflectiveyn | fieldnotes | custom | compkey | comptype | segkey | intkey | elmntkey | distance | width | supportkey | supportid  | startday | endday | starttime | endtime | side | ownership | current_status | condition | text                                                                | adddttm    | moddttm    | instdate   | expdate | primarydistrictcd | secondarydistrictcd | overrideyn | overridecomment | 
| ======== | ========== | ======== | ========= | ======== | ================================================================================================== | ============================================================================================== | ====== | ======= | ======================= | ========== | ======== | ============ | ========== | ====== | ======= | ======== | ====== | ====== | ======== | ======== | ===== | ========== | ========== | ======== | ====== | ========= | ======= | ==== | ========= | ============== | ========= | =================================================================== | ========== | ========== | ========== | ======= | ================= | =================== | ========== | =============== | 
| 1        | SGN-168347 | 01-RS    | R8-BL4Z25 | PRZ      | Restricted Parking Zone permited parking                                                           | WESTLAKE EAST RDWY AVE N 0090 BLOCK NE SIDE ( 302) 302 FT NW/O ALOHA ST (R8-BL4Z25 -35W/R8PSX) | W      | TS-10   | Telespar Post - 10'     | WHITE/BLUE | 12X18    | Y            | -35W/R8PSX | N      | 585127  | 20       | 13549  | 1      | 36158    | 302      | -29   | 414125     | SAS-61253  | 1        | 6      | 800       | 1800    | NE   | SDOT      | INSVC          | GOOD      | [CIRCLE P] 4 HOURS MAX PAY 9A-4P                                    | 1337126400 | 1438041600 | 1333411200 |         | DISTRICT7         |                     | N          |                 | 
| 2        | SGN-172392 | 01-RS    | R7-NPLR   | PNP      | No Parking, but "standing" allowed                                                                 | COLORADO AVE S 0150 BLOCK W SIDE ( 690) 44 FT N/O S MASSACHUSETTS ST (R7-NPLR )                | E      | CW      | Concrete Wall or Column | RED/WHITE  | 18X18    | N            |            |        | 592673  | 20       | 9704   | 1      | 9737     | 715      | -8    | 592667     | SAS-124399 | 1        | 7      | 0         | 2359    | W    | SDOT      | INSVC          |           | [SLASH OVER CIRCLE] P [LEFT & RIGHT ARROW]                          | 1355702400 |            |            |         | DISTRICT2         |                     | N          |                 | 
| 3        | SGN-172279 | 01-RS    | R7-PKAB   | PPEAK    | Peak Parking Restrictions, TOW                                                                     | NW MARKET ST 0240 BLOCK S SIDE ( 134) 134 FT W/O 24TH AVE NW (R7-PKAB -11)                     | W      | LP      | SCL Light Post          | R/W        | 12x18    | N            | -11        | N      | 592353  | 20       | 19236  | 1      | 41726    | 158      | 31    | 530747     | SAS-107538 | 1        | 5      | 600       | 900     | S    | SDOT      | INSVC          | GOOD      | NO PARKING 6-9 AM EXC SAT-SUN-HOL TAZ                               | 1354665600 | 1354665600 | 1349136000 |         | DISTRICT6         |                     | N          |                 | 
| 4        | SGN-170091 | 03-GSC   | D3-103X   | SNS      | Street Name Signs                                                                                  | NE 92ND ST 0010 BLOCK S SIDE ( 305) 0 FT W/O 2ND AVE NE (D3-103X )                             |        | 3INRND  | 3 Inch Round Pole       | WHITE/GREN | VariesX9 | Y            |            | N      | 588163  | 20       | 17841  | 37577  | 85814    | 318      | -14   | 588162     | SAS-123209 |          |        |           |         | S    | SDOT      | INSVC          | GOOD      | N SIDE: NE 92nd St S SIDE: NE 92nd St                               | 1342656000 |            | 1339113600 |         | DISTRICT5         |                     | N          |                 | 
| 5        | SGN-166367 | 03-GSC   | D3-103X   | SNS      | Street Name Signs                                                                                  | 6TH AVE N 0070 BLOCK W SIDE ( 287) 0 FT S/O VALLEY ST (D3-103X )                               |        | 3INRND  | 3 Inch Round Pole       | WHITE/GREN | VariesX9 | Y            |            | N      | 579590  | 20       | 7900   | 28738  | 8013     | 300      | 17    | 579589     | SAS-121326 |          |        |           |         | W    | SDOT      | INSVC          | GOOD      | N SIDE: Valley St 700 S SIDE: Valley St 800                         | 1328832000 |            | 1325808000 |         | DISTRICT7         |                     | N          |                 | 
| 6        | SGN-173951 | 01-RS    | R7-STX    | PZONE    | Includes charter bus, event, funeral, consel, carshare, miscellaneous, ambulance, taxi, motorcycle | SUMMIT AVE E 0100 BLOCK W SIDE ( 275) 275 FT N/O BELLEVUE E PL E (R7-STX 20' DF)               | S      | UP      | Wood Pole               | RED/WHITE  |          | N            | 20' DF     | N      | 596068  | 20       | 13000  | 1      | 35609    | 288      | 17    | 410062     | SAS-57190  | 1        | 7      | 0         | 2359    | W    | SDOT      | INSVC          |           | {15}NO STOPS 9AM-2PM WED [CAR BEING TOWED] PHONE 684-5444           | 1362614400 | 1375315200 |            |         | DISTRICT3         |                     | N          |                 | 
| 7        | SGN-165685 | 02-WS    | W11-2     | WARNCW   | Warning-Crosswalk                                                                                  | ROOSEVELT WAY NE 0430 BLOCK W SIDE ( 215) 215 FT N/O NE 43RD N ST (W11-2 )                     | N      | TS-10   | Telespar Post - 10'     | BLACK/FLGR | 30x30    | Y            |            | N      | 577946  | 20       | 12598  | 1      | 35237    | 215      | 24    | 577942     | SAS-121029 |          |        |           |         | W    | SDOT      | INSVC          | GOOD      | [PEDESTRIAN]                                                        | 1324425600 | 1423440000 | 1323734400 |         | DISTRICT4         |                     | N          |                 | 
| 8        | SGN-170889 | 01-RS    | R3-102L   | REGBP    | Regulatory-Bike Ped                                                                                | NE RAVENNA WB BV 0060 BLOCK SW SIDE ( 205) 205 FT SE/O NE 65TH ST (R3-102L )                   | SE     | TS-10   | Telespar Post - 10'     | RED/WHITE  | 30X36    | Y            |            |        | 589850  | 20       | 18084  | 1      | 86062    | 228      | -17   | 589846     | SAS-123646 |          |        |           |         | SW   | SDOT      | INSVC          |           | [GREEN BIKE LANE PARALLEL] [UP ARROW] [BIKE] [YIELD] [LEFT S ARROW] | 1346198400 |            | 1346112000 |         | DISTRICT6         | DISTRICT4           | N          |                 | 
| 9        | SGN-168196 | 03-GSC   | D3-103X   | SNS      | Street Name Signs                                                                                  | 29TH AVE 0080 BLOCK E SIDE ( 0) 0 FT N/O E COLUMBIA ST (D3-103X )                              |        | 3INRND  | 3 Inch Round Pole       | WHITE/GREN | VariesX9 | Y            |            | N      | 584596  | 20       | 4267   | 30058  | 27150    | 13       | -17   | 584594     | SAS-122288 |          |        |           |         | E    | SDOT      | INSVC          | GOOD      | N SIDE: E Columbia St 700 S SIDE: E Columbia St 800                 | 1335312000 |            | 1331596800 |         | DISTRICT3         |                     | N          |                 | 
| 10       | SGN-170197 | 03-GSC   | D3-103X   | SNS      | Street Name Signs                                                                                  | RAVENNA AVE NE 0549 BLOCK W SIDE ( 107) 0 FT S/O NE 55TH N ST (D3-103X )                       |        | 3INRND  | 3 Inch Round Pole       | WHITE/GREN | VariesX9 | Y            |            | N      | 588320  | 20       | 12454  | 26021  | 12449    | 107      | 30    | 588319     | SAS-123260 |          |        |           |         | W    | SDOT      | INSVC          | GOOD      | E SIDE: Ravenna Ave NE 2100 W SIDE: Ravenna Ave NE                  | 1342656000 | 1455148800 | 1337904000 |         | DISTRICT4         |                     | N          |                 | 
```