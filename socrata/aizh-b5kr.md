# Airport Part 77 Surfaces - Transitional

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/airport-part-77-surfaces-transitional) |
| Metadata | [Link](https://data.iowa.gov/api/views/aizh-b5kr) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/aizh-b5kr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/aizh-b5kr/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | aizh-b5kr |
| Name | Airport Part 77 Surfaces - Transitional |
| Attribution | Iowa Department of Transportation - Office of Aviation |
| Category | Transportation & Utilities |
| Tags | aviation, runway, airfield, imaginary surface, transitional, iowa dot, iowa department of transportation |
| Created | 2016-06-09T08:35:43Z |
| Publication Date | 2016-06-09T08:36:55Z |

## Description

The transitional surface extends outward and upward at right angles to the primary and approach surfaces at a slope of 7:1.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type  | Render Type |
| ======== | ============== | =========== | ========== | ========== | =========== |
| No       | time           | :updated_at | updated_at | meta_data  | meta_data   |
| Yes      | series tag     | faacode     | FAACODE    | text       | text        |
| Yes      | series tag     | fac_name    | FAC_NAME   | text       | text        |
| Yes      | numeric metric | arpelev     | ARPELEV    | number     | number      |
| Yes      | series tag     | part77surf  | PART77SURF | text       | text        |
| Yes      | series tag     | surf_desc   | SURF_DESC  | text       | text        |
| Yes      | numeric metric | innerelev   | INNERELEV  | number     | number      |
| Yes      | numeric metric | outerelev   | OUTERELEV  | number     | number      |
| Yes      | numeric metric | surfwidth   | SURFWIDTH  | number     | number      |
| Yes      | series tag     | surf_ratio  | SURF_RATIO | text       | text        |
| Yes      | series tag     | notes       | NOTES      | text       | text        |
| Yes      | numeric metric | shape_area  | SHAPE.AREA | number     | number      |
| Yes      | numeric metric | shape_len   | SHAPE.LEN  | number     | number      |
| Yes      | series tag     | objectid    | OBJECTID   | text       | number      |
| No       |                | shape       | SHAPE      | geospatial | geospatial  |
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
series e:aizh-b5kr d:2016-06-09T08:35:43.000Z t:shape.longitude=-92.53302247499994 t:part77surf="Transitional Surface" t:surf_desc="Sloped area extends from primary surface and approach surface at 7:1 ratio until it intersects with horizontal surface." t:shape.needs_recoding=false t:surf_ratio=7:1 t:fac_name="MONTEZUMA SIG FIELD" t:faacode=7C5 t:shape.latitude=41.53679671200007 t:objectid=1 t:notes="All elevations are in feet MSL" m:shape_area=1377635.95041892 m:outerelev=1079 m:arpelev=929 m:innerelev=1029 m:surfwidth=350

series e:aizh-b5kr d:2016-06-09T08:35:43.000Z t:shape.longitude=-92.53340935599994 t:part77surf="Transitional Surface" t:surf_desc="Sloped area extends from primary surface and approach surface at 7:1 ratio until it intersects with horizontal surface." t:shape.needs_recoding=false t:surf_ratio=7:1 t:fac_name="MONTEZUMA SIG FIELD" t:faacode=7C5 t:shape.latitude=41.53962578900007 t:objectid=2 t:notes="All elevations are in feet MSL" m:shape_area=756694.421656675 m:outerelev=1029 m:arpelev=929 m:innerelev=979 m:surfwidth=350

series e:aizh-b5kr d:2016-06-09T08:35:43.000Z t:shape.longitude=-92.53379627099997 t:part77surf="Transitional Surface" t:surf_desc="Sloped area extends from primary surface and approach surface at 7:1 ratio until it intersects with horizontal surface." t:shape.needs_recoding=false t:surf_ratio=7:1 t:fac_name="MONTEZUMA SIG FIELD" t:faacode=7C5 t:shape.latitude=41.542454865000025 t:objectid=3 t:notes="All elevations are in feet MSL" m:shape_area=313257.479686202 m:outerelev=979 m:arpelev=929 m:innerelev=929 m:surfwidth=350
```

## Meta Commands

```ls
metric m:arpelev p:integer l:ARPELEV d:"Airport Elevation (FT MSL)" t:dataTypeName=number

metric m:innerelev p:integer l:INNERELEV d:"Inner Elevation (FT MSL)" t:dataTypeName=number

metric m:outerelev p:integer l:OUTERELEV d:"Outer Elevation (FT MSL)" t:dataTypeName=number

metric m:surfwidth p:integer l:SURFWIDTH d:SurfWidth t:dataTypeName=number

metric m:shape_area p:decimal l:SHAPE.AREA d:"Area (SqM)" t:dataTypeName=number

metric m:shape_len p:long l:SHAPE.LEN d:"Perimeter (Meter)" t:dataTypeName=number

entity e:aizh-b5kr l:"Airport Part 77 Surfaces - Transitional" t:attribution="Iowa Department of Transportation - Office of Aviation" t:url=https://data.iowa.gov/api/views/aizh-b5kr

property e:aizh-b5kr t:meta.view v:id=aizh-b5kr v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Aviation/Airport_Part77_Surfaces/MapServer/1 v:averageRating=0 v:name="Airport Part 77 Surfaces - Transitional" v:attribution="Iowa Department of Transportation - Office of Aviation"

property e:aizh-b5kr t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:aizh-b5kr t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | faacode | fac_name                             | arpelev | part77surf           | surf_desc                                                                                                               | innerelev | outerelev | surfwidth | surf_ratio | notes                          | shape_area                               | shape_len | objectid | shape                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | 
| =========== | ======= | ==================================== | ======= | ==================== | ======================================================================================================================= | ========= | ========= | ========= | ========== | ============================== | ======================================== | ========= | ======== | =============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 0           | 7C5     | MONTEZUMA SIG FIELD                  | 929     | Transitional Surface | Sloped area extends from primary surface and approach surface at 7:1 ratio until it intersects with horizontal surface. | 1029      | 1079      | 350       | 7:1        | All elevations are in feet MSL | 1377635.95041892002336680889129638671875 |           | 1        | [null, 41.53679671200007, -92.53302247499994, null, false, {rings=[[[-92.53302247499994, 41.53679671200007], [-92.53612825899995, 41.53679033000003], [-92.53889918999994, 41.54502069000006], [-92.53892183999994, 41.55112910100007], [-92.53621102699998, 41.55937086200004], [-92.53310415299995, 41.559377246000054], [-92.53033334499997, 41.551146749000054], [-92.53031150999999, 41.54503833700005], [-92.53302247499994, 41.53679671200007]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | 
| 0           | 7C5     | MONTEZUMA SIG FIELD                  | 929     | Transitional Surface | Sloped area extends from primary surface and approach surface at 7:1 ratio until it intersects with horizontal surface. | 979       | 1029      | 350       | 7:1        | All elevations are in feet MSL | 756694.421656675054691731929779052734375 |           | 2        | [null, 41.53962578900007, -92.53340935599994, null, false, {rings=[[[-92.53340935599994, 41.53962578900007], [-92.53576197999996, 41.53962095500003], [-92.53762060999998, 41.545141648000026], [-92.53764226699997, 41.55101348100004], [-92.53582390399998, 41.55654179600003], [-92.53347066099997, 41.55654663200005], [-92.53161205799995, 41.55102587300007], [-92.53159095199999, 41.54515403900007], [-92.53340935599994, 41.53962578900007]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 
| 0           | 7C5     | MONTEZUMA SIG FIELD                  | 929     | Transitional Surface | Sloped area extends from primary surface and approach surface at 7:1 ratio until it intersects with horizontal surface. | 929       | 979       | 350       | 7:1        | All elevations are in feet MSL | 313257.4796862020157277584075927734375   |           | 3        | [null, 41.542454865000025, -92.53379627099997, null, false, {rings=[[[-92.53379627099997, 41.542454865000025], [-92.53539566899997, 41.542451578000055], [-92.53634202599994, 41.54526259200003], [-92.53636269799995, 41.550897847000044], [-92.53543681499997, 41.55371272800005], [-92.53383713699998, 41.55371601600007], [-92.53289076599998, 41.55090498200008], [-92.53287039799994, 41.54526972600007], [-92.53379627099997, 41.542454865000025]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | 
| 0           | BRL     | BURLINGTON - SOUTHEAST IOWA REGIONAL | 698     | Transitional Surface | Sloped area extends from primary surface and approach surface at 7:1 ratio until it intersects with horizontal surface. | 798       | 848       | 350       | 7:1        | All elevations are in feet MSL | 7341519.0550116002559661865234375        |           | 4        | [null, 40.77990523600005, -91.11823945099997, null, false, {rings=[[[-91.11823945099997, 40.77990523600005], [-91.11813593199997, 40.76989240300003], [-91.11765196999994, 40.74929547100004], [-91.12938334699999, 40.74922548300003], [-91.12932914599998, 40.76982495100003], [-91.12948362899994, 40.78452175500007], [-91.13898080199994, 40.78861181800005], [-91.15444291299997, 40.79616362400003], [-91.15084886599999, 40.80102822900005], [-91.13432736799996, 40.79481214100008], [-91.12784204499997, 40.79201996300003], [-91.12635287499995, 40.79590551000007], [-91.12165707099996, 40.79593399600003], [-91.11841803399994, 40.78795905000004], [-91.11779119399995, 40.78768898100003], [-91.10227599599995, 40.78010317300004], [-91.10589298699995, 40.77525599400008], [-91.11823945099997, 40.77990523600005]]]}]                                                                                        | 
| 0           | BRL     | BURLINGTON - SOUTHEAST IOWA REGIONAL | 698     | Transitional Surface | Sloped area extends from primary surface and approach surface at 7:1 ratio until it intersects with horizontal surface. | 748       | 798       | 350       | 7:1        | All elevations are in feet MSL | 4449608.370133720338344573974609375      |           | 5        | [null, 40.781798894000076, -91.10807994199996, null, false, {rings=[[[-91.10807994199996, 40.781798894000076], [-91.11078664199994, 40.77817126300005], [-91.11951957499997, 40.781459367000025], [-91.11939963399999, 40.769880037000064], [-91.11907680299998, 40.75615080400007], [-91.12810168399994, 40.75609643300004], [-91.12806534699996, 40.769827821000035], [-91.12822541599996, 40.78508417000006], [-91.13832695399998, 40.789434577000065], [-91.14864365099999, 40.794475555000076], [-91.14593762699997, 40.79810631600003], [-91.13492604199996, 40.79396527200004], [-91.12707519299994, 40.79058511300008], [-91.12613408599998, 40.79304068000005], [-91.12181559099997, 40.793066864000025], [-91.11947794299994, 40.78731124900003], [-91.11844528299997, 40.786866341000064], [-91.10807994199996, 40.781798894000076]]]}]                                                                              | 
| 0           | BRL     | BURLINGTON - SOUTHEAST IOWA REGIONAL | 698     | Transitional Surface | Sloped area extends from primary surface and approach surface at 7:1 ratio until it intersects with horizontal surface. | 698       | 748       | 350       | 7:1        | All elevations are in feet MSL | 2264440.7787730298005044460296630859375  |           | 6        | [null, 40.79017585100007, -91.12591531599998, null, false, {rings=[[[-91.12591531599998, 40.79017585100007], [-91.12197409799995, 40.790199733000065], [-91.12053783099998, 40.78666343800006], [-91.11909935499995, 40.78604369800007], [-91.11388419099995, 40.78349431700008], [-91.11568073599994, 40.78108632100003], [-91.12079976099994, 40.78301348400004], [-91.12066333399997, 40.76986765600003], [-91.12050179399995, 40.763005441000075], [-91.12681987599996, 40.76296737800004], [-91.12680154699996, 40.76983067700007], [-91.12696718199999, 40.78564657100003], [-91.13767308999996, 40.79025733200007], [-91.14284663399997, 40.792784579000056], [-91.14104841799997, 40.795197038000026], [-91.13552469999996, 40.793118400000026], [-91.12630837399996, 40.78915026000004], [-91.12591531599998, 40.79017585100007]]]}]                                                                                   | 
| 0           | AMW     | AMES MUNICIPAL                       | 955     | Transitional Surface | Sloped area extends from primary surface and approach surface at 7:1 ratio until it intersects with horizontal surface. | 955       | 1005      | 350       | 7:1        | All elevations are in feet MSL | 2175626.8282091501168906688690185546875  |           | 7        | [null, 41.99777792900005, -93.62845680699996, null, false, {rings=[[[-93.62845680699996, 41.99777792900005], [-93.63253392699994, 42.00132745500008], [-93.62985040099994, 42.00324614900006], [-93.62526847299995, 42.000057447000074], [-93.62206831899994, 41.99756679300003], [-93.62153980199997, 41.99888731000004], [-93.61926491699995, 42.00325116000005], [-93.61423943199998, 42.00213183900007], [-93.61554486799997, 41.997552073000065], [-93.61709018799996, 41.993691787000046], [-93.61535845799995, 41.99234363700003], [-93.61128286599995, 41.98879349600003], [-93.61396634299996, 41.986875231000056], [-93.61854676099995, 41.99006439100003], [-93.62196714999999, 41.98150568400007], [-93.62451009599994, 41.97490972800006], [-93.63067936099998, 41.976283755000054], [-93.62796071199995, 41.98284059000008], [-93.62352114399994, 41.99393657000007], [-93.62845680699996, 41.99777792900005]]]}] | 
| 0           | AMW     | AMES MUNICIPAL                       | 955     | Transitional Surface | Sloped area extends from primary surface and approach surface at 7:1 ratio until it intersects with horizontal surface. | 1005      | 1055      | 350       | 7:1        | All elevations are in feet MSL | 4452544.74149801023304462432861328125    |           | 8        | [null, 41.997132419000025, -93.62941158099994, null, false, {rings=[[[-93.62941158099994, 41.997132419000025], [-93.63754921999998, 42.004216392000046], [-93.63350851399997, 42.00710559500004], [-93.62436338399999, 42.00074165700005], [-93.62265025599999, 41.99940836500008], [-93.61822075399994, 42.00790502000007], [-93.61169942199996, 42.006436619000056], [-93.61429576599994, 41.99731430400004], [-93.61564151399995, 41.993952755000066], [-93.61440361399997, 41.992989031000036], [-93.60627632999996, 41.98590894300003], [-93.61031056899998, 41.98301514900004], [-93.61790631999997, 41.98830426600006], [-93.62073130399995, 41.98123558700007], [-93.62581881299997, 41.96803889000006], [-93.63463122199994, 41.97000158600008], [-93.62919286999994, 41.983119988000055], [-93.62496978599995, 41.993675504000066], [-93.62941158099994, 41.997132419000025]]]}]                                      | 
| 0           | AMW     | AMES MUNICIPAL                       | 955     | Transitional Surface | Sloped area extends from primary surface and approach surface at 7:1 ratio until it intersects with horizontal surface. | 1055      | 1105      | 350       | 7:1        | All elevations are in feet MSL | 7523925.026903259567916393280029296875   |           | 9        | [null, 41.996486900000036, -93.63036633499996, null, false, {rings=[[[-93.63036633499996, 41.996486900000036], [-93.64254933899997, 42.00709610900003], [-93.63715567099996, 42.01095289700004], [-93.62345827599995, 42.00142586000004], [-93.62311853499995, 42.00116145000004], [-93.61719130099999, 42.01253036700007], [-93.60915906999998, 42.01074133800006], [-93.61304667299999, 41.997076521000054], [-93.61419282699995, 41.99421370400006], [-93.61344875099996, 41.99363441700007], [-93.60125753299997, 41.98301309200008], [-93.60666952599996, 41.979164902000036], [-93.61726591499996, 41.98654413600008], [-93.61949546799997, 41.98096547700004], [-93.62712724899995, 41.96116802900008], [-93.63858270099996, 41.963718646000075], [-93.63042503899999, 41.983399372000065], [-93.62641841699997, 41.99341441800004], [-93.63036633499996, 41.996486900000036]]]}]                                        | 
| 0           | BNW     | BOONE MUNICIPAL                      | 1160    | Transitional Surface | Sloped area extends from primary surface and approach surface at 7:1 ratio until it intersects with horizontal surface. | 1260      | 1310      | 350       | 7:1        | All elevations are in feet MSL | 4373356.0353366099298000335693359375     |           | 10       | [null, 42.05568162700007, -93.85719137299998, null, false, {rings=[[[-93.85719137299998, 42.05568162700007], [-93.86373872199994, 42.06511939000006], [-93.85730791699996, 42.06796452100008], [-93.84866726899998, 42.05838034900006], [-93.84361108899998, 42.06285289700003], [-93.84078094199998, 42.06185430700003], [-93.84282703099996, 42.053823040000054], [-93.84371236199996, 42.05242949600006], [-93.83716490999996, 42.04420610900007], [-93.82861441799997, 42.03192977200007], [-93.83504286999994, 42.02908622700005], [-93.84539938899997, 42.04056346100003], [-93.84876388299995, 42.04478878800006], [-93.85539373399996, 42.03886741400004], [-93.85828518699998, 42.039887555000064], [-93.85611934899998, 42.047973220000074], [-93.85398135599996, 42.051339883000026], [-93.85544920599995, 42.053182640000045], [-93.85719137299998, 42.05568162700007]]]}]                                          | 
```