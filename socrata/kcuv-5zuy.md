# SDOT Winter Weather Service Level

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-winter-weather-service-level) |
| Metadata | [Link](https://data.seattle.gov/api/views/kcuv-5zuy) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/kcuv-5zuy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/kcuv-5zuy/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | kcuv-5zuy |
| Name | SDOT Winter Weather Service Level |
| Category | Transportation |
| Tags | winter, weather, sdot, streets |
| Created | 2016-04-21T16:08:53Z |
| Publication Date | 2016-04-22T15:25:17Z |

## Description

Displays City of Seattle streets covered under SDOT?s Winter Storm Response Plan, showing snow and ice removal routes categorized by targeted level of service.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type  | Render Type |
| ======== | ============== | ============ | ============ | ========== | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data  | meta_data   |
| Yes      | series tag     | objectid     | OBJECTID     | text       | number      |
| Yes      | series tag     | route_name   | ROUTE_NAME   | text       | text        |
| Yes      | series tag     | si_shop      | SI_SHOP      | text       | text        |
| Yes      | numeric metric | si_los       | SI_LOS       | number     | number      |
| Yes      | numeric metric | si_route     | SI_ROUTE     | number     | number      |
| Yes      | series tag     | geo_area     | GEO_AREA     | text       | text        |
| Yes      | numeric metric | scale        | SCALE        | number     | number      |
| Yes      | series tag     | sort         | SORT         | text       | text        |
| Yes      | numeric metric | routemiles   | ROUTEMILES   | number     | number      |
| Yes      | numeric metric | compkey      | COMPKEY      | number     | number      |
| Yes      | series tag     | unitid       | UNITID       | text       | text        |
| Yes      | series tag     | description  | DESCRIPTION  | text       | text        |
| Yes      | series tag     | fulldescript | FULLDESCRIPT | text       | text        |
| No       |                | shape        | Shape        | geospatial | geospatial  |
| Yes      | numeric metric | shape_length | Shape_Length | number     | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = shape
```

## Data Commands

```ls
series e:kcuv-5zuy d:2016-04-21T16:08:53.000Z t:shape.longitude=-122.25590540899998 t:si_shop=CH t:shape.needs_recoding=false t:route_name="67 - C/S - Emerald - CH" t:shape.latitude=47.508200344000045 t:geo_area=C/S t:objectid=1 m:shape_length=2404.251789431141 m:si_route=67 m:si_los=2 m:routemiles=0.45535101

series e:kcuv-5zuy d:2016-04-21T16:08:53.000Z t:shape.longitude=-122.38676064799995 t:si_shop=WS t:shape.needs_recoding=false t:route_name="83 - SW - Emerald - WS" t:shape.latitude=47.575626251000074 t:geo_area=SW t:objectid=2 m:shape_length=11219.097912669136 m:si_route=83 m:si_los=2 m:routemiles=2.12482923

series e:kcuv-5zuy d:2016-04-21T16:08:53.000Z t:shape.longitude=-122.34858898399995 t:si_shop=HL t:shape.needs_recoding=false t:route_name="13 - NW - Emerald - HL" t:shape.latitude=47.65272750400004 t:geo_area=NW t:objectid=3 m:shape_length=3585.0405736916064 m:si_route=13 m:si_los=2 m:routemiles=0.67898682
```

## Meta Commands

```ls
metric m:si_los p:integer l:SI_LOS d:SI_LevelofService t:dataTypeName=number

metric m:si_route p:integer l:SI_ROUTE d:SI_ROUTE_NUM t:dataTypeName=number

metric m:scale p:long l:SCALE d:SCALE t:dataTypeName=number

metric m:routemiles p:decimal l:ROUTEMILES d:ROUTEMILES t:dataTypeName=number

metric m:compkey p:long l:COMPKEY d:COMPKEY t:dataTypeName=number

metric m:shape_length p:decimal l:Shape_Length d:Shape_Length t:dataTypeName=number

entity e:kcuv-5zuy l:"SDOT Winter Weather Service Level" t:url=https://data.seattle.gov/api/views/kcuv-5zuy

property e:kcuv-5zuy t:meta.view v:id=kcuv-5zuy v:category=Transportation v:averageRating=0 v:name="SDOT Winter Weather Service Level"

property e:kcuv-5zuy t:meta.view.license v:name="Public Domain"

property e:kcuv-5zuy t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:kcuv-5zuy t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| :updated_at | objectid | route_name               | si_shop | si_los | si_route | geo_area | scale | sort | routemiles                                                   | compkey | unitid | description | fulldescript | shape                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | shape_length                                    | 
| =========== | ======== | ======================== | ======= | ====== | ======== | ======== | ===== | ==== | ============================================================ | ======= | ====== | =========== | ============ | ================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================ | =============================================== | 
| 0           | 1        | 67 - C/S - Emerald - CH  | CH      | 2      | 67       | C/S      |       |      | 0.4553510100000000004882849680143408477306365966796875       |         |        |             |              | [null, 47.508200344000045, -122.25590540899998, null, false, {paths=[[[-122.25590540899998, 47.508200344000045], [-122.25584075399996, 47.514791434000074]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | 2404.25178943114087815047241747379302978515625  | 
| 0           | 2        | 83 - SW - Emerald - WS   | WS      | 2      | 83       | SW       |       |      | 2.124829230000000013234284779173322021961212158203125        |         |        |             |              | [null, 47.575626251000074, -122.38676064799995, null, false, {paths=[[[-122.38676064799995, 47.575626251000074], [-122.38677811099996, 47.56110646800005], [-122.38719498699999, 47.546707645000026], [-122.38721483399996, 47.54487200800003]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | 11219.097912669136348995380103588104248046875   | 
| 0           | 3        | 13 - NW - Emerald - HL   | HL      | 2      | 13       | NW       |       |      | 0.678986819999999990926653481437824666500091552734375        |         |        |             |              | [null, 47.65272750400004, -122.34858898399995, null, false, {paths=[[[-122.34858898399995, 47.65272750400004], [-122.34833869799996, 47.652611034000074], [-122.34821149299995, 47.65259133500007], [-122.34731588299996, 47.65262361500004], [-122.346394654, 47.65260265500007], [-122.34620540299994, 47.652626560000044], [-122.34596370599996, 47.65274500100003], [-122.34471401499997, 47.65340596500005], [-122.34247461899997, 47.65466247200004], [-122.34243924099997, 47.65538287600003], [-122.34080818599995, 47.65567174700004], [-122.33625707199997, 47.65564871500004]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 3585.0405736916063688113354146480560302734375   | 
| 0           | 4        | 87 - SW - Emerald - WS   | WS      | 2      | 87       | SW       |       |      | 1.755688249999999950290430206223390996456146240234375        |         |        |             |              | [null, 47.50820078600003, -122.37087513299997, null, false, {paths=[[[-122.37087513299997, 47.50820078600003], [-122.37593289499995, 47.50818911300007], [-122.387789769, 47.50829304000007], [-122.38778640599998, 47.508456084000045], [-122.38780698, 47.50866389300006], [-122.38794455099998, 47.50952224800005], [-122.38802219999997, 47.509806714000035], [-122.38808490999998, 47.50994707700005], [-122.38816333799997, 47.51008456000005], [-122.38830151499997, 47.51027300100003], [-122.38850748099998, 47.51048618100003], [-122.38874326899997, 47.51067034500005], [-122.38864364299997, 47.51150265800004], [-122.38852820999995, 47.51210353700003], [-122.38861262299997, 47.513794045000054], [-122.38733295499998, 47.51378069300006], [-122.37637371399995, 47.51372392700006]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 9269.77220550118363462388515472412109375        | 
| 0           | 5        | 61 - C/S - Gold - CH     | CH      | 1      | 61       | C/S      |       |      | 0.4295364200000000298729219139204360544681549072265625       |         |        |             |              | [null, 47.57980956400007, -122.33912973599996, null, false, {paths=[[[-122.33912973599996, 47.57980956400007], [-122.33951833699996, 47.58602157300004], [-122.33949990899998, 47.586183066000046], [-122.33945285299995, 47.58634824400008], [-122.33936796699999, 47.586584059000074], [-122.33923227899999, 47.586855617000026], [-122.33907931799996, 47.58708154200008], [-122.33821446299999, 47.58819900700007], [-122.33786756399996, 47.588751211000044], [-122.33760366199999, 47.58927803600005], [-122.33616112899995, 47.59177601400006], [-122.33600593099999, 47.592006566000066], [-122.33586245099997, 47.59227742600007], [-122.33553245399997, 47.59279115100003], [-122.33538974099997, 47.59296679200003], [-122.33465314799997, 47.593657259000054], [-122.33445737599999, 47.59394546900006], [-122.33433898499999, 47.59423265800007], [-122.33430478499997, 47.59443021300007], [-122.33424510599997, 47.59609503100006], [-122.33429287299998, 47.59626711100003], [-122.33440584399995, 47.59643289100006], [-122.33536696699997, 47.59751505600008], [-122.33546743, 47.59789290300006], [-122.33551029099999, 47.60051499400004], [-122.33553782799999, 47.600711802000035], [-122.33558043599999, 47.60088599000005], [-122.33570622099995, 47.601177188000065], [-122.33584090199997, 47.60138670400005], [-122.33611073999998, 47.601724929000056], [-122.33747330299997, 47.603192136000075], [-122.33812109699994, 47.60390518500003], [-122.33875374099995, 47.60462606800007], [-122.33924210299995, 47.605155452000076]]]}] | 9850.881751746774170896969735622406005859375    | 
| 0           | 6        | 70 - C/S - Emerald - CH  | CH      | 2      | 70       | C/S      |       |      | 0.51257220000000003334861276016454212367534637451171875      |         |        |             |              | [null, 47.57525447200004, -122.28494355599997, null, false, {paths=[[[-122.28494355599997, 47.57525447200004], [-122.28501978299994, 47.57520509700004], [-122.28503177299996, 47.57517983300005], [-122.28508422399995, 47.571668491000025], [-122.28507152499998, 47.57163133200004], [-122.28500361699997, 47.57158729900004]], [[-122.28494355599997, 47.57525447200004], [-122.28487881799998, 47.575205432000075], [-122.28486981299994, 47.57518182000007], [-122.28490324699999, 47.572434600000065], [-122.28491921199998, 47.57166900300007], [-122.28493500899998, 47.571632554000075], [-122.28500361699997, 47.57158729900004]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 2705.5336292654028511606156826019287109375      | 
| 0           | 7        | 39 - NE - Emerald - HL   | HL      | 2      | 39       | NE       |       |      | 0.6094866899999999976245135258068330585956573486328125       |         |        |             |              | [null, 47.618534269000065, -122.33848456799996, null, false, {paths=[[[-122.33848456799996, 47.618534269000065], [-122.33842834299998, 47.625508704000026], [-122.33962236299999, 47.62717089500006]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | 3218.08966352415518485940992832183837890625     | 
| 0           | 8        | 69 - C/S - Gold - CH     | CH      | 1      | 69       | C/S      |       |      | 0.11591034000000000059316107581253163516521453857421875      |         |        |             |              | [null, 47.61001650700007, -122.32115834099994, null, false, {paths=[[[-122.32115834099994, 47.61001650700007], [-122.32180983499995, 47.61073022700003]], [[-122.32579164599997, 47.61005181000007], [-122.32644427199995, 47.610765435000076]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | 612.0065922504380750979180447757244110107421875 | 
| 0           | 9        | 33 - NE - Emerald - HL   | HL      | 2      | 33       | NE       |       |      | 0.25262061000000002319865188837866298854351043701171875      |         |        |             |              | [null, 47.66129873700004, -122.31763816199998, null, false, {paths=[[[-122.31763816199998, 47.66129873700004], [-122.31754006399996, 47.66148462800004], [-122.31746668799997, 47.661682116000065], [-122.31742343199994, 47.66311774400003], [-122.31740379099995, 47.664937344000066]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | 1333.7803277572829756536521017551422119140625   | 
| 0           | 10       | 360 - C/S - Emerald - CH | CH      | 2      | 360      | C/S      |       |      | 0.0212560500000000020259793842569706612266600131988525390625 |         |        |             |              | [null, 47.57171560200004, -122.32598469899995, null, false, {paths=[[[-122.32598469899995, 47.57171560200004], [-122.32598557299997, 47.57140800600007]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | 112.200344461382655936176888644695281982421875  | 
```