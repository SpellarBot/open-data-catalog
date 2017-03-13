# IDOT - Published Annual Program 2011 - Structure Improvements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idot-published-annual-program-2011-structure-improvements-3c4ac) |
| Metadata | [Link](https://data.illinois.gov/api/views/erpn-m8ee) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/erpn-m8ee/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/erpn-m8ee/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | erpn-m8ee |
| Name | IDOT - Published Annual Program 2011 - Structure Improvements |
| Attribution | Illinois Department of Transportation |
| Category | Transportation |
| Created | 2011-06-16T15:34:48Z |
| Publication Date | 2011-06-16T15:34:48Z |
| Rows Updated | 2011-08-21T02:56:56Z |

## Description

The Annual Publication is a proposed program of road and structure projects that are planned for current fiscal year. They are the roadway, spot, structure, engineering, and land acquisition files. The Structure Layer File is populated by selecting project records containing a Structure Improvement Type.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | type        | TYPE       | text      | text        |
| Yes      | series tag     | inventory   | INVENTORY  | text      | text        |
| Yes      | numeric metric | begin_sta   | BEGIN_STA  | number    | number      |
| Yes      | numeric metric | end_sta     | END_STA    | number    | number      |
| Yes      | series tag     | sn_key      | SN_KEY     | text      | text        |
| Yes      | numeric metric | rtype1      | RTYPE1     | number    | text        |
| Yes      | numeric metric | rtype2      | RTYPE2     | number    | text        |
| Yes      | numeric metric | rtype3      | RTYPE3     | number    | text        |
| Yes      | numeric metric | rtype4      | RTYPE4     | number    | text        |
| Yes      | numeric metric | rtype5      | RTYPE5     | number    | text        |
| Yes      | numeric metric | rtype6      | RTYPE6     | number    | text        |
| Yes      | numeric metric | rtype7      | RTYPE7     | number    | text        |
| Yes      | numeric metric | rtype8      | RTYPE8     | number    | text        |
| Yes      | numeric metric | rtype9      | RTYPE9     | number    | text        |
| Yes      | numeric metric | rtype10     | RTYPE10    | number    | text        |
| Yes      | numeric metric | rtype11     | RTYPE11    | number    | text        |
| Yes      | numeric metric | rtype12     | RTYPE12    | number    | text        |
| Yes      | numeric metric | rtype13     | RTYPE13    | number    | text        |
| Yes      | numeric metric | rtype14     | RTYPE14    | number    | text        |
| Yes      | numeric metric | rtype15     | RTYPE15    | number    | text        |
| Yes      | series tag     | route1      | ROUTE1     | text      | text        |
| Yes      | series tag     | route2      | ROUTE2     | text      | text        |
| Yes      | series tag     | route3      | ROUTE3     | text      | text        |
| Yes      | series tag     | route4      | ROUTE4     | text      | text        |
| Yes      | series tag     | route5      | ROUTE5     | text      | text        |
| Yes      | series tag     | route6      | ROUTE6     | text      | text        |
| Yes      | numeric metric | route7      | ROUTE7     | number    | text        |
| Yes      | numeric metric | route8      | ROUTE8     | number    | text        |
| Yes      | numeric metric | route9      | ROUTE9     | number    | text        |
| Yes      | numeric metric | route10     | ROUTE10    | number    | text        |
| Yes      | numeric metric | route11     | ROUTE11    | number    | text        |
| Yes      | numeric metric | route12     | ROUTE12    | number    | text        |
| Yes      | numeric metric | route13     | ROUTE13    | number    | text        |
| Yes      | numeric metric | route14     | ROUTE14    | number    | text        |
| Yes      | numeric metric | route15     | ROUTE15    | number    | text        |
| Yes      | series tag     | miles_fmt   | MILES_FMT  | text      | text        |
| Yes      | numeric metric | est_cost_f  | EST_COST_F | number    | number      |
| Yes      | series tag     | location1   | LOCATION1  | text      | text        |
| Yes      | series tag     | location2   | LOCATION2  | text      | text        |
| Yes      | series tag     | location3   | LOCATION3  | text      | text        |
| Yes      | series tag     | location4   | LOCATION4  | text      | text        |
| Yes      | series tag     | location5   | LOCATION5  | text      | text        |
| Yes      | series tag     | location6   | LOCATION6  | text      | text        |
| Yes      | numeric metric | location7   | LOCATION7  | number    | text        |
| Yes      | numeric metric | location8   | LOCATION8  | number    | text        |
| Yes      | numeric metric | location9   | LOCATION9  | number    | text        |
| Yes      | numeric metric | location10  | LOCATION10 | number    | text        |
| Yes      | numeric metric | location11  | LOCATION11 | number    | text        |
| Yes      | numeric metric | location12  | LOCATION12 | number    | text        |
| Yes      | numeric metric | location13  | LOCATION13 | number    | text        |
| Yes      | numeric metric | location14  | LOCATION14 | number    | text        |
| Yes      | series tag     | imprvmnt1   | IMPRVMNT1  | text      | text        |
| Yes      | series tag     | imprvmnt2   | IMPRVMNT2  | text      | text        |
| Yes      | series tag     | imprvmnt3   | IMPRVMNT3  | text      | text        |
| Yes      | series tag     | imprvmnt4   | IMPRVMNT4  | text      | text        |
| Yes      | series tag     | imprvmnt5   | IMPRVMNT5  | text      | text        |
| Yes      | series tag     | imprvmnt6   | IMPRVMNT6  | text      | text        |
| Yes      | numeric metric | imprvmnt7   | IMPRVMNT7  | number    | text        |
| Yes      | numeric metric | imprvmnt8   | IMPRVMNT8  | number    | text        |
| Yes      | numeric metric | imprvmnt9   | IMPRVMNT9  | number    | text        |
| Yes      | numeric metric | imprvmnt10  | IMPRVMNT10 | number    | text        |
| Yes      | numeric metric | imprvmnt11  | IMPRVMNT11 | number    | text        |
| Yes      | numeric metric | imprvmnt12  | IMPRVMNT12 | number    | text        |
| Yes      | numeric metric | imprvmnt13  | IMPRVMNT13 | number    | text        |
| Yes      | numeric metric | imprvmnt14  | IMPRVMNT14 | number    | text        |
| Yes      | numeric metric | imprvmnt15  | IMPRVMNT15 | number    | text        |
| Yes      | numeric metric | footnotes1  | FOOTNOTES1 | number    | text        |
| Yes      | numeric metric | footnotes2  | FOOTNOTES2 | number    | text        |
| Yes      | numeric metric | footnotes3  | FOOTNOTES3 | number    | text        |
| Yes      | numeric metric | footnotes4  | FOOTNOTES4 | number    | text        |
| Yes      | numeric metric | footnotes5  | FOOTNOTES5 | number    | text        |
| Yes      | numeric metric | footnotes6  | FOOTNOTES6 | number    | text        |
| Yes      | numeric metric | footnotes7  | FOOTNOTES7 | number    | text        |
| Yes      | numeric metric | footnotes8  | FOOTNOTES8 | number    | text        |
| Yes      | numeric metric | footnotes9  | FOOTNOTES9 | number    | text        |
| Yes      | numeric metric | prj_rec_ty  | PRJ_REC_TY | number    | text        |
| Yes      | numeric metric | pps_projec  | PPS_PROJEC | number    | text        |
| Yes      | series tag     | pub_desc    | PUB_DESC   | text      | text        |
| Yes      | numeric metric | record      | RECORD     | number    | text        |
| Yes      | numeric metric | frequency   | FREQUENCY  | number    | number      |
| Yes      | numeric metric | loc_dist_n  | LOC_DIST_N | number    | text        |
| Yes      | series tag     | cty_nmt1    | CTY_NMT1   | text      | text        |
| Yes      | series tag     | cty_nmt2    | CTY_NMT2   | text      | text        |
| Yes      | numeric metric | cty_nmt3    | CTY_NMT3   | number    | text        |
| Yes      | numeric metric | cty_nmt4    | CTY_NMT4   | number    | text        |
| Yes      | numeric metric | cty_nmt5    | CTY_NMT5   | number    | text        |
| Yes      | numeric metric | cty_nmt6    | CTY_NMT6   | number    | text        |
| Yes      | numeric metric | cty_nmt7    | CTY_NMT7   | number    | text        |
| Yes      | numeric metric | cty_nmt8    | CTY_NMT8   | number    | text        |
| Yes      | numeric metric | cty_nmt9    | CTY_NMT9   | number    | text        |
| Yes      | series tag     | fndacr1     | FNDACR1    | text      | text        |
| Yes      | series tag     | fndacr2     | FNDACR2    | text      | text        |
| Yes      | numeric metric | fndacr3     | FNDACR3    | number    | text        |
| Yes      | numeric metric | fndacr4     | FNDACR4    | number    | text        |
| Yes      | numeric metric | fndacr5     | FNDACR5    | number    | text        |
| Yes      | numeric metric | fndacr6     | FNDACR6    | number    | text        |
| Yes      | numeric metric | fndacr7     | FNDACR7    | number    | text        |
| Yes      | numeric metric | fndacr8     | FNDACR8    | number    | text        |
| Yes      | numeric metric | fndacr9     | FNDACR9    | number    | text        |
| Yes      | numeric metric | fndacr10    | FNDACR10   | number    | text        |
| Yes      | numeric metric | fndacr11    | FNDACR11   | number    | text        |
| Yes      | numeric metric | fndacr12    | FNDACR12   | number    | text        |
| Yes      | numeric metric | fndacr13    | FNDACR13   | number    | text        |
| Yes      | numeric metric | fndacr14    | FNDACR14   | number    | text        |
| Yes      | numeric metric | fndacr15    | FNDACR15   | number    | text        |
| Yes      | numeric metric | fndacr16    | FNDACR16   | number    | text        |
| Yes      | series tag     | section_nb  | SECTION_NB | text      | text        |
| Yes      | series tag     | tracdesc1   | TRACDESC1  | text      | text        |
| Yes      | series tag     | tracdesc2   | TRACDESC2  | text      | text        |
| Yes      | series tag     | tracdesc3   | TRACDESC3  | text      | text        |
| Yes      | numeric metric | tracdesc4   | TRACDESC4  | number    | text        |
| Yes      | numeric metric | tracdesc5   | TRACDESC5  | number    | text        |
| Yes      | numeric metric | tracdesc6   | TRACDESC6  | number    | text        |
| Yes      | numeric metric | tracdesc7   | TRACDESC7  | number    | text        |
| Yes      | numeric metric | tracdesc8   | TRACDESC8  | number    | text        |
| Yes      | numeric metric | tracdesc9   | TRACDESC9  | number    | text        |
| Yes      | numeric metric | tracdesc10  | TRACDESC10 | number    | text        |
| Yes      | numeric metric | angle       | ANGLE      | number    | number      |
| Yes      | numeric metric | point_x     | POINT_X    | number    | number      |
| Yes      | numeric metric | point_y     | POINT_Y    | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:erpn-m8ee d:2011-06-16T08:34:56.000Z t:tracdesc1=NONE t:type=STR t:prj_rec_ty=P t:sn_key=0010019 t:rtype3=C t:rtype2=S t:location3="MISSISSIPPI RIVER" t:route3=QUINCY t:rtype1=M t:location2="BRIDGE AT" t:route2="MAINE ST" t:location1="QUINCY MEMORIAL" t:imprvmnt1="BRIDGE JOINT REPAIR" t:route1="US 24" t:pub_desc="20112011ANNUAL BOOK" t:inventory="001  20063 000000" t:fndacr2=OTH t:cty_nmt1=ADAMS t:fndacr1=S m:record=1208 m:point_x=-91.4203 m:est_cost_f=250000 m:point_y=39.93118 m:begin_sta=0.01 m:end_sta=0 m:pps_projec=6617500300 m:loc_dist_n=6 m:frequency=1 m:angle=89

series e:erpn-m8ee d:2011-06-16T08:34:56.000Z t:tracdesc1=NONE t:type=STR t:prj_rec_ty=P t:sn_key=0010025 t:location3="BEVERLY RD" t:rtype1=M t:location2="2 MI W OF" t:imprvmnt2="BRIDGE OFFICE P.E." t:location1="GRINDSTONE CREEK" t:imprvmnt1="BRIDGE REPLACEMENT" t:route1="ILL 104" t:pub_desc="20112011ANNUAL BOOK" t:inventory="001  20745 000000" t:fndacr2=S t:cty_nmt1=ADAMS t:fndacr1=BR m:record=1226 m:point_x=-91.0078 m:est_cost_f=1400000 m:point_y=39.82334 m:begin_sta=26.03 m:end_sta=0 m:pps_projec=6734600000 m:loc_dist_n=6 m:frequency=1 m:angle=359

series e:erpn-m8ee d:2011-06-16T08:34:56.000Z t:tracdesc1=NONE t:type=STR t:prj_rec_ty=P t:sn_key=0020022 t:rtype2=C t:location3=CAIRO t:rtype1=M t:location2="BRIDGE AT WCL OF" t:route2=CAIRO t:location1="MISSISSIPPI RIVER" t:imprvmnt1="BRIDGE DECK REPAIRS" t:route1="I 57" t:pub_desc="20112011ANNUAL BOOK" t:inventory="002  10057 000000" t:fndacr2=OTH t:cty_nmt1=ALEXANDER t:fndacr1=S m:record=1560 m:point_x=-89.211 m:est_cost_f=200000 m:point_y=37.02392 m:begin_sta=0 m:end_sta=0 m:pps_projec=9004090000 m:loc_dist_n=9 m:frequency=1 m:angle=240
```

## Meta Commands

```ls
metric m:begin_sta l:BEGIN_STA t:dataTypeName=number

metric m:end_sta l:END_STA t:dataTypeName=number

metric m:rtype7 l:RTYPE7 t:dataTypeName=number

metric m:rtype8 l:RTYPE8 t:dataTypeName=number

metric m:rtype9 l:RTYPE9 t:dataTypeName=number

metric m:rtype10 l:RTYPE10 t:dataTypeName=number

metric m:rtype11 l:RTYPE11 t:dataTypeName=number

metric m:rtype12 l:RTYPE12 t:dataTypeName=number

metric m:rtype13 l:RTYPE13 t:dataTypeName=number

metric m:rtype14 l:RTYPE14 t:dataTypeName=number

metric m:rtype15 l:RTYPE15 t:dataTypeName=number

metric m:route7 l:ROUTE7 t:dataTypeName=number

metric m:route8 l:ROUTE8 t:dataTypeName=number

metric m:route9 l:ROUTE9 t:dataTypeName=number

metric m:route10 l:ROUTE10 t:dataTypeName=number

metric m:route11 l:ROUTE11 t:dataTypeName=number

metric m:route12 l:ROUTE12 t:dataTypeName=number

metric m:route13 l:ROUTE13 t:dataTypeName=number

metric m:route14 l:ROUTE14 t:dataTypeName=number

metric m:route15 l:ROUTE15 t:dataTypeName=number

metric m:est_cost_f p:integer l:EST_COST_F t:dataTypeName=number

metric m:location7 l:LOCATION7 t:dataTypeName=number

metric m:location8 l:LOCATION8 t:dataTypeName=number

metric m:location9 l:LOCATION9 t:dataTypeName=number

metric m:location10 l:LOCATION10 t:dataTypeName=number

metric m:location11 l:LOCATION11 t:dataTypeName=number

metric m:location12 l:LOCATION12 t:dataTypeName=number

metric m:location13 l:LOCATION13 t:dataTypeName=number

metric m:location14 l:LOCATION14 t:dataTypeName=number

metric m:imprvmnt7 l:IMPRVMNT7 t:dataTypeName=number

metric m:imprvmnt8 l:IMPRVMNT8 t:dataTypeName=number

metric m:imprvmnt9 l:IMPRVMNT9 t:dataTypeName=number

metric m:imprvmnt10 l:IMPRVMNT10 t:dataTypeName=number

metric m:imprvmnt11 l:IMPRVMNT11 t:dataTypeName=number

metric m:imprvmnt12 l:IMPRVMNT12 t:dataTypeName=number

metric m:imprvmnt13 l:IMPRVMNT13 t:dataTypeName=number

metric m:imprvmnt14 l:IMPRVMNT14 t:dataTypeName=number

metric m:imprvmnt15 l:IMPRVMNT15 t:dataTypeName=number

metric m:footnotes1 l:FOOTNOTES1 t:dataTypeName=number

metric m:footnotes2 l:FOOTNOTES2 t:dataTypeName=number

metric m:footnotes3 l:FOOTNOTES3 t:dataTypeName=number

metric m:footnotes4 l:FOOTNOTES4 t:dataTypeName=number

metric m:footnotes5 l:FOOTNOTES5 t:dataTypeName=number

metric m:footnotes6 l:FOOTNOTES6 t:dataTypeName=number

metric m:footnotes7 l:FOOTNOTES7 t:dataTypeName=number

metric m:footnotes8 l:FOOTNOTES8 t:dataTypeName=number

metric m:footnotes9 l:FOOTNOTES9 t:dataTypeName=number

metric m:pps_projec p:long l:PPS_PROJEC t:dataTypeName=number

metric m:record p:integer l:RECORD t:dataTypeName=number

metric m:frequency l:FREQUENCY t:dataTypeName=number

metric m:loc_dist_n p:integer l:LOC_DIST_N t:dataTypeName=number

metric m:cty_nmt3 l:CTY_NMT3 t:dataTypeName=number

metric m:cty_nmt4 l:CTY_NMT4 t:dataTypeName=number

metric m:cty_nmt5 l:CTY_NMT5 t:dataTypeName=number

metric m:cty_nmt6 l:CTY_NMT6 t:dataTypeName=number

metric m:cty_nmt7 l:CTY_NMT7 t:dataTypeName=number

metric m:cty_nmt8 l:CTY_NMT8 t:dataTypeName=number

metric m:cty_nmt9 l:CTY_NMT9 t:dataTypeName=number

metric m:fndacr4 l:FNDACR4 t:dataTypeName=number

metric m:fndacr5 l:FNDACR5 t:dataTypeName=number

metric m:fndacr6 l:FNDACR6 t:dataTypeName=number

metric m:fndacr7 l:FNDACR7 t:dataTypeName=number

metric m:fndacr8 l:FNDACR8 t:dataTypeName=number

metric m:fndacr9 l:FNDACR9 t:dataTypeName=number

metric m:fndacr10 l:FNDACR10 t:dataTypeName=number

metric m:fndacr11 l:FNDACR11 t:dataTypeName=number

metric m:fndacr12 l:FNDACR12 t:dataTypeName=number

metric m:fndacr13 l:FNDACR13 t:dataTypeName=number

metric m:fndacr14 l:FNDACR14 t:dataTypeName=number

metric m:fndacr15 l:FNDACR15 t:dataTypeName=number

metric m:fndacr16 l:FNDACR16 t:dataTypeName=number

metric m:tracdesc4 l:TRACDESC4 t:dataTypeName=number

metric m:tracdesc5 l:TRACDESC5 t:dataTypeName=number

metric m:tracdesc6 l:TRACDESC6 t:dataTypeName=number

metric m:tracdesc7 l:TRACDESC7 t:dataTypeName=number

metric m:tracdesc8 l:TRACDESC8 t:dataTypeName=number

metric m:tracdesc9 l:TRACDESC9 t:dataTypeName=number

metric m:tracdesc10 l:TRACDESC10 t:dataTypeName=number

metric m:angle p:integer l:ANGLE t:dataTypeName=number

metric m:point_x l:POINT_X t:dataTypeName=number

metric m:point_y l:POINT_Y t:dataTypeName=number

entity e:erpn-m8ee l:"IDOT - Published Annual Program 2011 - Structure Improvements" t:attribution="Illinois Department of Transportation" t:url=https://data.illinois.gov/api/views/erpn-m8ee

property e:erpn-m8ee t:meta.view v:id=erpn-m8ee v:category=Transportation v:averageRating=0 v:name="IDOT - Published Annual Program 2011 - Structure Improvements" v:attribution="Illinois Department of Transportation"

property e:erpn-m8ee t:meta.view.owner v:id=ibpp-yb7w v:screenName="Jim Conlon" v:displayName="Jim Conlon"

property e:erpn-m8ee t:meta.view.tableauthor v:id=ibpp-yb7w v:screenName="Jim Conlon" v:displayName="Jim Conlon"
```