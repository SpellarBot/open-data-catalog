# river-level-update-AutoCreated

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/river-level-update-autocreated) |
| Metadata | [Link](https://data.mo.gov/api/views/t6tp-ifh8) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/t6tp-ifh8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/t6tp-ifh8/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | t6tp-ifh8 |
| Name | river-level-update-AutoCreated |
| Created | 2014-12-18T18:53:09Z |
| Publication Date | 2015-09-19T04:10:31Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| No       |                | the_geom    | the_geom   | text      | text        |
| Yes      | series tag     | gaugelid    | GaugeLID   | text      | text        |
| Yes      | series tag     | stage       | Stage      | text      | text        |
| Yes      | series tag     | location    | Location   | text      | text        |
| No       |                | latitude    | Latitude   | number    | text        |
| No       |                | longitude   | Longitude  | number    | text        |
| Yes      | series tag     | waterbody   | Waterbody  | text      | text        |
| Yes      | series tag     | state       | State      | text      | text        |
| Yes      | numeric metric | observed    | Observed   | number    | text        |
| Yes      | series tag     | obstime     | ObsTime    | text      | text        |
| Yes      | series tag     | units       | Units      | text      | text        |
| Yes      | numeric metric | action      | Action     | number    | text        |
| Yes      | numeric metric | flood       | Flood      | number    | text        |
| Yes      | numeric metric | moderate    | Moderate   | number    | text        |
| Yes      | numeric metric | major       | Major      | number    | text        |
| Yes      | numeric metric | lowthresh   | LowThresh  | number    | text        |
| Yes      | series tag     | lowthreshu  | LowThreshU | text      | text        |
| Yes      | series tag     | wfo         | WFO        | text      | text        |
| Yes      | series tag     | hdatum      | HDatum     | text      | text        |
| Yes      | series tag     | pedts       | PEDTS      | text      | text        |
| Yes      | numeric metric | secvalue    | SecValue   | number    | text        |
| Yes      | series tag     | secunit     | SecUnit    | text      | text        |
| Yes      | series tag     | url         | URL        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = the_geom,latitude,longitude
```

## Data Commands

```ls
series e:t6tp-ifh8 d:2015-09-18T21:06:11.000Z t:obstime="2015-09-19 03:30:00" t:location=Akers t:hdatum=NAD83/WGS84 t:waterbody="Current River" t:state=MO t:stage=no_flooding t:units=ft t:url="http://water.weather.gov/ahps2/hydrograph.php?wfo=sgf&gage=akfm7" t:wfo=sgf t:gaugelid=AKFM7 t:pedts=hgirg t:secunit=kcfs t:lowthreshu=ft m:observed=1.17 m:secvalue=0.28 m:lowthresh=0 m:flood=0 m:moderate=0 m:action=4 m:major=0

series e:t6tp-ifh8 d:2015-09-18T21:06:11.000Z t:obstime="2015-09-19 03:30:00" t:location="Alley Spring" t:hdatum=NAD83/WGS84 t:waterbody="Jacks Fork" t:state=MO t:stage=no_flooding t:units=ft t:url="http://water.weather.gov/ahps2/hydrograph.php?wfo=sgf&gage=alym7" t:wfo=sgf t:gaugelid=ALYM7 t:pedts=hgirg t:secunit=kcfs t:lowthreshu=ft m:observed=2.46 m:secvalue=0.16 m:lowthresh=1.7 m:flood=9 m:moderate=12 m:action=5.3 m:major=16

series e:t6tp-ifh8 d:2015-09-18T21:06:11.000Z t:obstime="2015-09-19 03:15:00" t:location=Annapolis t:hdatum=NAD83/WGS84 t:waterbody="Black River" t:state=MO t:stage=no_flooding t:units=ft t:url="http://water.weather.gov/ahps2/hydrograph.php?wfo=lsx&gage=annm7" t:wfo=lsx t:gaugelid=ANNM7 t:pedts=hgirg t:secunit=kcfs t:lowthreshu=ft m:observed=2.72 m:secvalue=0.15 m:lowthresh=0 m:flood=8 m:moderate=15 m:action=6 m:major=25
```

## Meta Commands

```ls
metric m:observed p:float l:Observed t:dataTypeName=number

metric m:action p:float l:Action t:dataTypeName=number

metric m:flood p:float l:Flood t:dataTypeName=number

metric m:moderate p:float l:Moderate t:dataTypeName=number

metric m:major p:float l:Major t:dataTypeName=number

metric m:lowthresh p:float l:LowThresh t:dataTypeName=number

metric m:secvalue p:float l:SecValue t:dataTypeName=number

entity e:t6tp-ifh8 l:river-level-update-AutoCreated t:url=https://data.mo.gov/api/views/t6tp-ifh8

property e:t6tp-ifh8 t:meta.view v:id=t6tp-ifh8 v:averageRating=0 v:name=river-level-update-AutoCreated

property e:t6tp-ifh8 t:meta.view.owner v:id=jzbz-iqr6 v:screenName=Breanna v:lastNotificationSeenAt=1492723347 v:displayName=Breanna

property e:t6tp-ifh8 t:meta.view.tableauthor v:id=jzbz-iqr6 v:screenName=Breanna v:roleName=administrator v:lastNotificationSeenAt=1492723347 v:displayName=Breanna
```

## Top Records

```ls
| :updated_at | the_geom                     | gaugelid | stage       | location                  | latitude  | longitude  | waterbody          | state | observed | obstime             | units | action | flood | moderate | major | lowthresh | lowthreshu | wfo | hdatum      | pedts | secvalue | secunit | url                                                              | 
| =========== | ============================ | ======== | =========== | ========================= | ========= | ========== | ================== | ===== | ======== | =================== | ===== | ====== | ===== | ======== | ===== | ========= | ========== | === | =========== | ===== | ======== | ======= | ================================================================ | 
| 1442610371  | POINT (-91.5525 37.375556)   | AKFM7    | no_flooding | Akers                     | 37.375556 | -91.5525   | Current River      | MO    | 1.17     | 2015-09-19 03:30:00 | ft    | 4.0    | 0.0   | 0.0      | 0.0   | 0.0       | ft         | sgf | NAD83/WGS84 | hgirg | 0.28     | kcfs    | http://water.weather.gov/ahps2/hydrograph.php?wfo=sgf&gage=akfm7 | 
| 1442610371  | POINT (-91.443056 37.148056) | ALYM7    | no_flooding | Alley Spring              | 37.148056 | -91.443056 | Jacks Fork         | MO    | 2.46     | 2015-09-19 03:30:00 | ft    | 5.3    | 9.0   | 12.0     | 16.0  | 1.7       | ft         | sgf | NAD83/WGS84 | hgirg | 0.16     | kcfs    | http://water.weather.gov/ahps2/hydrograph.php?wfo=sgf&gage=alym7 | 
| 1442610371  | POINT (-90.788611 37.336111) | ANNM7    | no_flooding | Annapolis                 | 37.336111 | -90.788611 | Black River        | MO    | 2.72     | 2015-09-19 03:15:00 | ft    | 6.0    | 8.0   | 15.0     | 25.0  | 0.0       | ft         | lsx | NAD83/WGS84 | hgirg | 0.15     | kcfs    | http://water.weather.gov/ahps2/hydrograph.php?wfo=lsx&gage=annm7 | 
| 1442610371  | POINT (-90.360556 38.456667) | ARNM7    | no_flooding | Arnold                    | 38.456667 | -90.360556 | Meramec River      | MO    | 6.2      | 2015-09-19 03:00:00 | ft    | 22.0   | 24.0  | 35.0     | 38.0  | 0.0       | ft         | lsx | NAD83/WGS84 | hgirg | 8.09     | kcfs    | http://water.weather.gov/ahps2/hydrograph.php?wfo=lsx&gage=arnm7 | 
| 1442610371  | POINT (-93.206667 36.717778) | BBCM7    | no_flooding | Walnut Shade              | 36.717778 | -93.206667 | Bull Creek         | MO    | 3.61     | 2015-09-19 03:15:00 | ft    | 0.0    | 9.5   | 0.0      | 0.0   | 1.2       | ft         | sgf | NAD83/WGS84 | hgirg | 0.07     | kcfs    | http://water.weather.gov/ahps2/hydrograph.php?wfo=sgf&gage=bbcm7 | 
| 1442610371  | POINT (-94.603889 36.670833) | BCCM7    | no_flooding | Tiff City                 | 36.670833 | -94.603889 | Buffalo Creek (MO) | MO    | 2.76     | 2015-09-19 03:00:00 | ft    | 11.0   | 0.0   | 0.0      | 0.0   | 1.0       | ft         | sgf | NAD83/WGS84 | hgirg | 0.02     | kcfs    | http://water.weather.gov/ahps2/hydrograph.php?wfo=sgf&gage=bccm7 | 
| 1442610371  | POINT (-92.058056 37.760278) | BIGM7    | no_flooding | Ft. Wood - East Gate      | 37.760278 | -92.058056 | Big Piney          | MO    | 2.09     | 2015-09-19 03:16:00 | ft    | 6.0    | 8.0   | 15.0     | 23.0  | 1.7       | ft         | sgf | NAD83/WGS84 | hgirg | 0.23     | kcfs    | http://water.weather.gov/ahps2/hydrograph.php?wfo=sgf&gage=bigm7 | 
| 1442610371  | POINT (-93.965278 38.555)    | BLRM7    | no_flooding | Blairstown                | 38.555    | -93.965278 | Big Creek          | MO    | 7.75     | 2015-09-19 03:00:00 | ft    | 15.0   | 20.0  | 23.0     | 36.0  | 0.0       | ft         | eax | NAD83/WGS84 | hgirg | 0.0      | kcfs    | http://water.weather.gov/ahps2/hydrograph.php?wfo=eax&gage=blrm7 | 
| 1442610371  | POINT (-93.196667 38.992222) | BLVM7    | no_flooding | Blue Lick                 | 38.992222 | -93.196667 | Blackwater River   | MO    | 7.34     | 2015-09-19 02:45:00 | ft    | 19.0   | 24.0  | 29.0     | 37.0  | 0.0       | ft         | eax | NAD83/WGS84 | hgirg | 0.13     | kcfs    | http://water.weather.gov/ahps2/hydrograph.php?wfo=eax&gage=blvm7 | 
| 1442610371  | POINT (-92.8575 37.717222)   | BNSM7    | no_flooding | Bennett Spring State Park | 37.717222 | -92.8575   | Bennett Spring     | MO    | 1.99     | 2015-09-19 03:00:00 | ft    | 3.5    | 5.0   | 0.0      | 0.0   | 0.0       | ft         | sgf | NAD83/WGS84 | hgirg | 0.15     | kcfs    | http://water.weather.gov/ahps2/hydrograph.php?wfo=sgf&gage=bnsm7 | 
```