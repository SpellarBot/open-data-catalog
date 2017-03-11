# forecasted-9day-river-level-update-AutoCreated

## Dataset

* [Dataset URL](https://data.mo.gov/api/views/fx9n-wkff/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/forecasted-9day-river-level-update-autocreated)
* [Metadata URL](https://data.mo.gov/api/views/fx9n-wkff)
* Id = fx9n-wkff
* Name = forecasted-9day-river-level-update-AutoCreated
* Created = 2014-12-17T15:09:44Z
* Publication Date = 2015-10-15T15:12:15Z
* Rows Updated = 2015-10-15T15:11:24Z

## Description



## Columns

```ls
| Name       | Field Name  | Data Type | Render Type | Schema Type    | Included | 
| ========== | =========== | ========= | =========== | ============== | ======== | 
| updated_at | :updated_at | meta_data | meta_data   | time           | No       | 
| the_geom   | the_geom    | text      | text        | series tag     | Yes      | 
| GaugeLID   | gaugelid    | text      | text        | series tag     | Yes      | 
| Stage      | stage       | text      | text        | series tag     | Yes      | 
| Location   | location    | text      | text        | series tag     | Yes      | 
| Latitude   | latitude    | number    | text        |                | No       | 
| Longitude  | longitude   | number    | text        |                | No       | 
| Waterbody  | waterbody   | text      | text        | series tag     | Yes      | 
| State      | state       | text      | text        | series tag     | Yes      | 
| Forecast   | forecast    | number    | text        | numeric metric | Yes      | 
| FcstTime   | fcsttime    | text      | text        | series tag     | Yes      | 
| FcstIssunc | fcstissunc  | text      | text        | series tag     | Yes      | 
| Units      | units       | text      | text        | series tag     | Yes      | 
| Action     | action      | number    | text        | numeric metric | Yes      | 
| Flood      | flood       | number    | text        | numeric metric | Yes      | 
| Moderate   | moderate    | number    | text        | numeric metric | Yes      | 
| Major      | major       | number    | text        | numeric metric | Yes      | 
| LowThresh  | lowthresh   | number    | text        | numeric metric | Yes      | 
| LowThreshU | lowthreshu  | text      | text        | series tag     | Yes      | 
| WFO        | wfo         | text      | text        | series tag     | Yes      | 
| HDatum     | hdatum      | text      | text        | series tag     | Yes      | 
| PEDTS      | pedts       | text      | text        | series tag     | Yes      | 
| SecValue   | secvalue    | number    | text        | numeric metric | Yes      | 
| SecUnit    | secunit     | text      | text        | series tag     | Yes      | 
| URL        | url         | text      | text        | series tag     | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = longitude,latitude
Annotation Fields = 
```

## Data Commands

```ls
series e:fx9n-wkff d:2015-10-15T08:10:51.000Z t:location="Alley Spring" t:hdatum=NAD83/WGS84 t:waterbody="Jacks Fork" t:the_geom="POINT (-91.443056 37.148056)" t:state=MO t:fcsttime=N/A t:stage=no_forecast t:units=ft t:url="http://water.weather.gov/ahps2/hydrograph.php?wfo=sgf&gage=alym7" t:wfo=sgf t:gaugelid=ALYM7 t:pedts=HGIFF t:secunit=kcfs t:fcstissunc=N/A t:lowthreshu=ft m:secvalue=-999 m:forecast=-999 m:lowthresh=1.7 m:flood=9 m:action=5.3 m:moderate=12 m:major=16

series e:fx9n-wkff d:2015-10-15T08:10:51.000Z t:location=Annapolis t:hdatum=NAD83/WGS84 t:waterbody="Black River" t:the_geom="POINT (-90.788611 37.336111)" t:state=MO t:fcsttime=N/A t:stage=no_forecast t:units=ft t:url="http://water.weather.gov/ahps2/hydrograph.php?wfo=lsx&gage=annm7" t:wfo=lsx t:gaugelid=ANNM7 t:pedts=HGIFF t:secunit=kcfs t:fcstissunc=N/A t:lowthreshu=ft m:secvalue=-999 m:forecast=-999 m:lowthresh=0 m:flood=8 m:action=6 m:moderate=15 m:major=25

series e:fx9n-wkff d:2015-10-15T08:10:51.000Z t:location=Arnold t:hdatum=NAD83/WGS84 t:waterbody="Meramec River" t:the_geom="POINT (-90.360556 38.456667)" t:state=MO t:fcsttime=N/A t:stage=no_forecast t:units=ft t:url="http://water.weather.gov/ahps2/hydrograph.php?wfo=lsx&gage=arnm7" t:wfo=lsx t:gaugelid=ARNM7 t:pedts=HGIFF t:secunit=kcfs t:fcstissunc=N/A t:lowthreshu=ft m:secvalue=-999 m:forecast=-999 m:lowthresh=0 m:flood=24 m:action=22 m:moderate=35 m:major=38
```

## Meta Commands

```ls
metric m:forecast l:Forecast t:dataTypeName=number

metric m:action l:Action t:dataTypeName=number

metric m:flood l:Flood t:dataTypeName=number

metric m:moderate l:Moderate t:dataTypeName=number

metric m:major l:Major t:dataTypeName=number

metric m:lowthresh l:LowThresh t:dataTypeName=number

metric m:secvalue l:SecValue t:dataTypeName=number

entity e:fx9n-wkff l:forecasted-9day-river-level-update-AutoCreated t:url=https://data.mo.gov/api/views/fx9n-wkff

property e:fx9n-wkff t:meta.view d:2017-03-08T02:31:46.195Z v:id=fx9n-wkff v:averageRating=0 v:name=forecasted-9day-river-level-update-AutoCreated

property e:fx9n-wkff t:meta.view.owner d:2017-03-08T02:31:46.195Z v:id=jzbz-iqr6 v:screenName=Breanna v:roleName=administrator v:displayName=Breanna

property e:fx9n-wkff t:meta.view.tableauthor d:2017-03-08T02:31:46.195Z v:id=jzbz-iqr6 v:screenName=Breanna v:roleName=administrator v:displayName=Breanna
```