# SF Development Pipeline 2016 Q3

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sf-development-pipeline-2016-q3) |
| Metadata | [Link](https://data.sfgov.org/api/views/k7mk-w2pq) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/k7mk-w2pq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/k7mk-w2pq/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | k7mk-w2pq |
| Name | SF Development Pipeline 2016 Q3 |
| Created | 2016-11-12T15:34:15Z |
| Publication Date | 2017-03-04T23:01:50Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name             | Data Type     | Render Type   |
| ======== | ============== | =============== | ================ | ============= | ============= |
| Yes      | series tag     | projtype        | ProjType         | text          | text          |
| Yes      | series tag     | nameaddr        | NAMEADDR         | text          | text          |
| Yes      | series tag     | alias           | Alias            | text          | text          |
| Yes      | series tag     | beststat        | BESTSTAT         | text          | text          |
| Yes      | time           | bestdate        | BESTDATE         | calendar_date | calendar_date |
| Yes      | numeric metric | entitlement     | Entitlement      | number        | number        |
| Yes      | series tag     | plncaseno       | PLN_CASE_NO      | text          | text          |
| Yes      | series tag     | plndesc         | PLN_DESC         | text          | text          |
| Yes      | series tag     | bldguse         | BldgUse          | text          | text          |
| Yes      | series tag     | bpapplno        | BP_APPL_NO       | text          | text          |
| Yes      | series tag     | dbidesc         | DBI_DESC         | text          | text          |
| Yes      | numeric metric | units           | UNITS            | number        | number        |
| Yes      | numeric metric | unitsnet        | UNITSNET         | number        | number        |
| Yes      | numeric metric | affordable      | AFFORDABLE       | number        | number        |
| Yes      | numeric metric | affordablenet   | AFFORDABLENET    | number        | number        |
| Yes      | series tag     | section415      | SECTION415       | text          | text          |
| Yes      | series tag     | sec415_tenure   | SEC415_TENURE    | text          | text          |
| Yes      | numeric metric | total_gsf       | TOTAL_GSF        | number        | number        |
| Yes      | numeric metric | net_gsf         | NET_GSF          | number        | number        |
| Yes      | numeric metric | cie             | CIE              | number        | number        |
| Yes      | numeric metric | cienet          | CIENET           | number        | number        |
| Yes      | numeric metric | med             | MED              | number        | number        |
| Yes      | numeric metric | mednet          | MEDNET           | number        | number        |
| Yes      | numeric metric | mips            | MIPS             | number        | number        |
| Yes      | numeric metric | mipsnet         | MIPSNET          | number        | number        |
| Yes      | numeric metric | pdr             | PDR              | number        | number        |
| Yes      | numeric metric | pdrnet          | PDRNET           | number        | number        |
| Yes      | numeric metric | ret             | RET              | number        | number        |
| Yes      | numeric metric | retnet          | RETNET           | number        | number        |
| Yes      | numeric metric | visit           | VISIT            | number        | number        |
| Yes      | numeric metric | visitnet        | VISITNET         | number        | number        |
| Yes      | series tag     | sponsor         | SPONSOR          | text          | text          |
| Yes      | series tag     | contact         | CONTACT          | text          | text          |
| Yes      | series tag     | contactph       | CONTACTPH        | text          | text          |
| Yes      | numeric metric | cost            | COST             | money         | money         |
| No       |                | firstfiled      | FirstFiled       | calendar_date | calendar_date |
| Yes      | numeric metric | multi           | MULTI            | number        | number        |
| Yes      | series tag     | planner         | PLANNER          | text          | text          |
| Yes      | series tag     | apn             | APN              | text          | text          |
| Yes      | series tag     | plnarea         | PLAN_AREA        | text          | text          |
| Yes      | series tag     | plndistrict     | PLN_DISTRICT     | text          | text          |
| Yes      | series tag     | supedist        | SUPEDIST         | text          | text          |
| Yes      | series tag     | zoning_sim      | ZONING_SIM       | text          | text          |
| Yes      | series tag     | zoningdistname  | ZONING_NAME      | text          | text          |
| Yes      | series tag     | zoninggen       | ZONING_GEN       | text          | text          |
| Yes      | series tag     | zoning          | ZONING           | text          | text          |
| Yes      | series tag     | plnneighborhood | PLN_NEIGHBORHOOD | text          | text          |
| Yes      | series tag     | height          | HEIGHT           | text          | text          |
| Yes      | numeric metric | port            | Port             | number        | number        |
```

## Time Field

```ls
Value = bestdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = firstfiled
```

## Data Commands

```ls
series e:k7mk-w2pq d:2016-07-27T00:00:00.000Z t:alias="3150 16TH ST" t:projtype=Mixres t:zoninggen="Mixed Use" t:zoning_sim=NCT t:supedist="SUPERVISORIAL DISTRICT 8" t:plnarea="Mission (EN)" t:plncaseno=2016-003233PRJ t:plndistrict=Mission t:plndesc="Historic rehabilitation of an existing auto body shop to change use to ground floor retail with 4 units of residential within the existing building envelope." t:height=55-X t:plnneighborhood=Mission t:zoningdistname="VALENCIA STREET NEIGHBORHOOD COMMERCIAL TRANSIT" t:nameaddr="3140 16TH ST" t:apn="APN 3555018" t:zoning=NCT-VALENCIA t:beststat="PL APPROVED" m:port=0 m:ret=5404 m:med=0 m:cienet=0 m:mednet=0 m:visit=0 m:pdr=3123 m:cie=0 m:cost=0 m:mipsnet=0 m:affordable=0 m:units=4 m:unitsnet=4 m:total_gsf=8527 m:visitnet=0 m:pdrnet=-17305 m:multi=0 m:mips=0 m:retnet=5404 m:affordablenet=0 m:entitlement=1 m:net_gsf=-11901

series e:k7mk-w2pq d:2016-06-02T00:00:00.000Z t:projtype=Resident t:zoninggen=Residential t:zoning_sim=RM-2 t:bldguse=APARTMENTS t:supedist="SUPERVISORIAL DISTRICT 3" t:bpapplno=201506239654 t:plncaseno=2015-007396PRJ t:plndistrict=Northeast t:plndesc="Dwelling unit merger combining two residential units into one legal unit.  (units #804 & #805)." t:height=40-X t:plnneighborhood="Russian Hill" t:zoningdistname="RESIDENTIAL- MIXED, MODERATE DENSITY" t:nameaddr="1750 TAYLOR ST" t:apn="APN 0128C028" t:dbidesc="UNIT MERGER ONLY. COMBINE UNIT 804 AND 805. DRM# 2015-007396. REMOVE (E) DOOR & WALL DIVIDING UNITS INTERIOR RENOVATION FOR NEW HALL, ENTRY FOYER, BUTLER PANTRY, CLOSETS MATCH (E) FINISHES." t:zoning=RM-2 t:beststat="PL APPROVED" m:port=0 m:ret=0 m:med=0 m:cienet=0 m:mednet=0 m:visit=0 m:pdr=0 m:cie=0 m:cost=20000 m:mipsnet=0 m:affordable=0 m:units=1 m:unitsnet=-1 m:total_gsf=0 m:visitnet=0 m:pdrnet=0 m:multi=0 m:mips=0 m:retnet=0 m:affordablenet=0 m:entitlement=1 m:net_gsf=0

series e:k7mk-w2pq d:2016-03-24T00:00:00.000Z t:projtype=Resident t:zoninggen="Mixed Use" t:zoning_sim=RC-4 t:supedist="SUPERVISORIAL DISTRICT 3" t:plncaseno=2012 t:plndistrict=Downtown t:plndesc="Construct a 15-unit residential building." t:height=80-A t:plnneighborhood="Downtown/Civic Center" t:zoningdistname="RESIDENTIAL- COMMERCIAL, HIGH DENSITY" t:nameaddr="824 HYDE ST" t:apn="APN 0280017" t:zoning=RC-4 t:beststat="PL APPROVED" m:port=0 m:ret=0 m:med=0 m:cienet=0 m:mednet=0 m:visit=0 m:pdr=0 m:cie=0 m:cost=0 m:mipsnet=0 m:affordable=0 m:units=15 m:unitsnet=15 m:total_gsf=0 m:visitnet=0 m:pdrnet=0 m:multi=0 m:mips=0 m:retnet=0 m:affordablenet=0 m:entitlement=1 m:net_gsf=0
```

## Meta Commands

```ls
metric m:entitlement p:integer l:Entitlement t:dataTypeName=number

metric m:units p:float l:UNITS t:dataTypeName=number

metric m:unitsnet p:float l:UNITSNET t:dataTypeName=number

metric m:affordable p:float l:AFFORDABLE t:dataTypeName=number

metric m:affordablenet p:float l:AFFORDABLENET t:dataTypeName=number

metric m:total_gsf p:float l:TOTAL_GSF t:dataTypeName=number

metric m:net_gsf p:float l:NET_GSF t:dataTypeName=number

metric m:cie p:float l:CIE t:dataTypeName=number

metric m:cienet p:float l:CIENET t:dataTypeName=number

metric m:med p:float l:MED t:dataTypeName=number

metric m:mednet p:float l:MEDNET t:dataTypeName=number

metric m:mips p:float l:MIPS t:dataTypeName=number

metric m:mipsnet p:float l:MIPSNET t:dataTypeName=number

metric m:pdr p:float l:PDR t:dataTypeName=number

metric m:pdrnet p:float l:PDRNET t:dataTypeName=number

metric m:ret p:float l:RET t:dataTypeName=number

metric m:retnet p:float l:RETNET t:dataTypeName=number

metric m:visit p:float l:VISIT t:dataTypeName=number

metric m:visitnet p:float l:VISITNET t:dataTypeName=number

metric m:cost p:double l:COST t:dataTypeName=money

metric m:multi p:integer l:MULTI t:dataTypeName=number

metric m:port p:integer l:Port d:"if project is under Port jurisdiction (1 true, 0 false)" t:dataTypeName=number

entity e:k7mk-w2pq l:"SF Development Pipeline 2016 Q3" t:url=https://data.sfgov.org/api/views/k7mk-w2pq

property e:k7mk-w2pq t:meta.view v:id=k7mk-w2pq v:averageRating=0 v:name="SF Development Pipeline 2016 Q3"

property e:k7mk-w2pq t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:k7mk-w2pq t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| projtype | nameaddr           | alias        | beststat     | bestdate            | entitlement | plncaseno      | plndesc                                                                                                                                                                                                                                                        | bldguse           | bpapplno     | dbidesc                                                                                                                                                                                                                                    | units          | unitsnet       | affordable    | affordablenet | section415 | sec415_tenure | total_gsf        | net_gsf            | cie           | cienet        | med           | mednet        | mips          | mipsnet       | pdr              | pdrnet             | ret              | retnet           | visit         | visitnet      | sponsor | contact | contactph | cost                | firstfiled          | multi | planner  | apn          | plnarea               | plndistrict      | supedist                  | zoning_sim | zoningdistname                                  | zoninggen   | zoning       | plnneighborhood       | height | port | 
| ======== | ================== | ============ | ============ | =================== | =========== | ============== | ============================================================================================================================================================================================================================================================== | ================= | ============ | ========================================================================================================================================================================================================================================== | ============== | ============== | ============= | ============= | ========== | ============= | ================ | ================== | ============= | ============= | ============= | ============= | ============= | ============= | ================ | ================== | ================ | ================ | ============= | ============= | ======= | ======= | ========= | =================== | =================== | ===== | ======== | ============ | ===================== | ================ | ========================= | ========== | =============================================== | =========== | ============ | ===================== | ====== | ==== | 
| Mixres   | 3140 16TH ST       | 3150 16TH ST | PL APPROVED  | 2016-07-27T00:00:00 | 1           | 2016-003233PRJ | Historic rehabilitation of an existing auto body shop to change use to ground floor retail with 4 units of residential within the existing building envelope.                                                                                                  |                   |              |                                                                                                                                                                                                                                            | 4.00000000000  | 4.00000000000  | 0.00000000000 | 0.00000000000 |            |               | 8527.00000000000 | -11901.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 3123.00000000000 | -17305.00000000000 | 5404.00000000000 | 5404.00000000000 | 0.00000000000 | 0.00000000000 |         |         |           | 0.00000000000       | 2016-03-10T00:00:00 | 0     |          | APN 3555018  | Mission (EN)          | Mission          | SUPERVISORIAL DISTRICT 8  | NCT        | VALENCIA STREET NEIGHBORHOOD COMMERCIAL TRANSIT | Mixed Use   | NCT-VALENCIA | Mission               | 55-X   | 0    | 
| Resident | 1750 TAYLOR ST     |              | PL APPROVED  | 2016-06-02T00:00:00 | 1           | 2015-007396PRJ | Dwelling unit merger combining two residential units into one legal unit. (units #804 & #805).                                                                                                                                                                 | APARTMENTS        | 201506239654 | UNIT MERGER ONLY. COMBINE UNIT 804 AND 805. DRM# 2015-007396. REMOVE (E) DOOR & WALL DIVIDING UNITS INTERIOR RENOVATION FOR NEW HALL, ENTRY FOYER, BUTLER PANTRY, CLOSETS MATCH (E) FINISHES.                                              | 1.00000000000  | -1.00000000000 | 0.00000000000 | 0.00000000000 |            |               | 0.00000000000    | 0.00000000000      | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000    | 0.00000000000      | 0.00000000000    | 0.00000000000    | 0.00000000000 | 0.00000000000 |         |         |           | 20000.00000000000   | 2015-06-11T00:00:00 | 0     |          | APN 0128C028 |                       | Northeast        | SUPERVISORIAL DISTRICT 3  | RM-2       | RESIDENTIAL- MIXED, MODERATE DENSITY            | Residential | RM-2         | Russian Hill          | 40-X   | 0    | 
| Resident | 824 HYDE ST        |              | PL APPROVED  | 2016-03-24T00:00:00 | 1           | 2012           | Construct a 15-unit residential building.                                                                                                                                                                                                                      |                   |              |                                                                                                                                                                                                                                            | 15.00000000000 | 15.00000000000 | 0.00000000000 | 0.00000000000 |            |               | 0.00000000000    | 0.00000000000      | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000    | 0.00000000000      | 0.00000000000    | 0.00000000000    | 0.00000000000 | 0.00000000000 |         |         |           | 0.00000000000       | 2012-11-16T00:00:00 | 0     |          | APN 0280017  |                       | Downtown         | SUPERVISORIAL DISTRICT 3  | RC-4       | RESIDENTIAL- COMMERCIAL, HIGH DENSITY           | Mixed Use   | RC-4         | Downtown/Civic Center | 80-A   | 0    | 
| Resident | 930 BAKER ST       |              | PL APPROVED  | 2016-08-17T00:00:00 | 1           | 2014           | Project will expand the existing building at the front and rear of the property, excavating two stories below the existing structure and providing a detached two car garage fronting onto St. Joseph's Avenue. The project will also result in two new units, | APARTMENTS        | 201510230679 | HORIZONTL EXPANSION. ADDITION OF 2 UNITS BELOW (E) STRUCTURE & EXPANSION RECONFIGURE INTERIOR LAYOUTS, NEW WINDOWS & DOORS ATFACADE, NEW ELECTRIAL, NEW PLUMBING, NEW ROOF DECK, LANDSCAPING, NEW GARAGE STRUCTURE @ ST JOESPH'S AVE SIDE. | 4.00000000000  | 2.00000000000  | 0.00000000000 | 0.00000000000 |            |               | 0.00000000000    | 0.00000000000      | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000    | 0.00000000000      | 0.00000000000    | 0.00000000000    | 0.00000000000 | 0.00000000000 |         |         |           | 495000.00000000000  | 2014-03-19T00:00:00 | 0     |          | APN 0280017  |                       | Downtown         | SUPERVISORIAL DISTRICT 3  | RC-4       | RESIDENTIAL- COMMERCIAL, HIGH DENSITY           | Mixed Use   | RC-4         | Downtown/Civic Center | 80-A   | 0    | 
| Resident | 802-808 STEINER ST |              | PL APPROVED  | 2016-03-24T00:00:00 | 1           | 2014           | Construction of three new four-story residential buildings containing a total of eight dwelling units (19,071 sf) over one level of below-grade parking (16 spaces).                                                                                           | 1 FAMILY DWELLING | 201109144613 | TO ERECT 4 STORIES, 3 UNIT RESIDENTIAL BUILDING. AS "802 STEINER STREET, BLOCK 0798, LOT 057"                                                                                                                                              | 16.00000000000 | 16.00000000000 | 0.00000000000 | 0.00000000000 |            |               | 0.00000000000    | 0.00000000000      | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000    | 0.00000000000      | 0.00000000000    | 0.00000000000    | 0.00000000000 | 0.00000000000 |         |         |           | 1388000.00000000000 | 2011-09-14T00:00:00 | 1     |          | APN 0798055  |                       | Western Addition | SUPERVISORIAL DISTRICT 5  | RH-3       | RESIDENTIAL- HOUSE, THREE FAMILY                | Residential | RH-3         | Western Addition      | 40-X   | 0    | 
| Resident | 1211 SCOTT ST      |              | BP FILED     | 2015-09-15T00:00:00 | 1           | 2015-012514PRJ | ADDITION OF ONE ACCESSORY DWELLING UNIT AT THE GROUND FLOOR PER ORDINANCE 30-15, MISCELLANEOUS DECAY & WATER DAMAGE REPAIR, WATERPROOF (E) DECKS & FRONT STAIRCASE. SOFT STORY RETROFIT PERMIT #201509156939.                                                  | APARTMENTS        | 201509156948 | NEW APARTMENT ADDITION IN COMPLIANCE WITH ORDINANCE 30-15, MISCELLANEOUS DECAY & WATER DAMAGE REPAIR, WATERPROOF (E) DECKS & FRONT STAIRCASE. SOFT STORY RETROFIT PERMIT #201509156939                                                     | 3.00000000000  | 1.00000000000  | 0.00000000000 | 0.00000000000 |            |               | 0.00000000000    | 0.00000000000      | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000    | 0.00000000000      | 0.00000000000    | 0.00000000000    | 0.00000000000 | 0.00000000000 |         |         |           | 80000.00000000000   | 2015-09-15T00:00:00 | 0     | NKWIATKO | APN 1127003  |                       | Western Addition | SUPERVISORIAL DISTRICT 5  | RM-1       | RESIDENTIAL- MIXED, LOW DENSITY                 | Residential | RM-1         | Western Addition      | 65-A   | 0    | 
| Resident | 1212 EGBERT AV     |              | BP FILED     | 2013-12-31T00:00:00 | 0           |                |                                                                                                                                                                                                                                                                | 1 FAMILY DWELLING | 201312315375 | COMPLIANCE WITH ORDINANCE NO. 155-13 NOT REQUIRED. EXCAVATION<50 CU.YD. ERECT 2 STORIES ONE SINGLE FAMILY DWELLING.                                                                                                                        | 2.00000000000  | 2.00000000000  | 0.00000000000 | 0.00000000000 |            |               | 0.00000000000    | 0.00000000000      | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000    | 0.00000000000      | 0.00000000000    | 0.00000000000    | 0.00000000000 | 0.00000000000 |         |         |           | 325000.00000000000  | 2013-12-31T00:00:00 | 0     | CTOWNES  | APN 4909003  | Bayview Hunters Point | South Bayshore   | SUPERVISORIAL DISTRICT 10 | RH-1       | RESIDENTIAL- HOUSE, ONE FAMILY                  | Residential | RH-1         | Bayview               | 40-X   | 0    | 
| Resident | 1221 14TH AV       |              | CONSTRUCTION | 2016-06-14T00:00:00 | 1           |                |                                                                                                                                                                                                                                                                | APARTMENTS        | 201505146405 | LEGALIZATION OF DWELLING UNIT OF 598 SQ. FT. AT GROUND FLOOR LEVEL, 2 BEDROOM, LIVING ROOM, KITCHEN AND BATHROOM (UNIT LEGALIZATION ORDINANCE 43-14)                                                                                       | 3.00000000000  | 1.00000000000  | 0.00000000000 | 0.00000000000 |            |               | 0.00000000000    | 0.00000000000      | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000    | 0.00000000000      | 0.00000000000    | 0.00000000000    | 0.00000000000 | 0.00000000000 |         |         |           | 55614.00000000000   | 2015-05-14T00:00:00 | 0     | NKWIATKO | APN 1736061  |                       | Inner Sunset     | SUPERVISORIAL DISTRICT 5  | RH-2       | RESIDENTIAL- HOUSE, TWO FAMILY                  | Residential | RH-2         | Inner Sunset          | 40-X   | 0    | 
| Resident | 1225 ATHENS ST     |              | BP ISSUED    | 2015-12-14T00:00:00 | 1           |                |                                                                                                                                                                                                                                                                | 2 FAMILY DWELLING | 201506189331 | LEGALIZE (E) UNPERMITTED GROUND FLOOR AREA TO A NEW UNIT INCLUDING 2 BEDROOMS, ONE FULL BATH, ONE KITCHEN AND LIVING ROOM.                                                                                                                 | 2.00000000000  | 1.00000000000  | 0.00000000000 | 0.00000000000 |            |               | 0.00000000000    | 0.00000000000      | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000    | 0.00000000000      | 0.00000000000    | 0.00000000000    | 0.00000000000 | 0.00000000000 |         |         |           | 78000.00000000000   | 2015-06-18T00:00:00 | 0     | CLARKECO | APN 6447040  |                       | South Central    | SUPERVISORIAL DISTRICT 11 | RH-1       | RESIDENTIAL- HOUSE, ONE FAMILY                  | Residential | RH-1         | Crocker Amazon        | 40-X   | 0    | 
| Resident | 1225 DOLORES ST    |              | BP ISSUED    | 2015-04-03T00:00:00 | 1           |                |                                                                                                                                                                                                                                                                | APARTMENTS        | 200703307744 | TO ERECT 4 STORIES, SINGLE FAMILY DWELLING.                                                                                                                                                                                                | 3.00000000000  | 3.00000000000  | 0.00000000000 | 0.00000000000 |            |               | 0.00000000000    | 0.00000000000      | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000 | 0.00000000000    | 0.00000000000      | 0.00000000000    | 0.00000000000    | 0.00000000000 | 0.00000000000 |         |         |           | 928000.00000000000  | 2007-03-30T00:00:00 | 0     | MSMITH   | APN 6534029  |                       | Mission          | SUPERVISORIAL DISTRICT 8  | RH-3       | RESIDENTIAL- HOUSE, THREE FAMILY                | Residential | RH-3         | Mission               | 40-X   | 0    | 
```