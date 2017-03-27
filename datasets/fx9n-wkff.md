# forecasted-9day-river-level-update-AutoCreated

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/forecasted-9day-river-level-update-autocreated) |
| Metadata | [Link](https://data.mo.gov/api/views/fx9n-wkff) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/fx9n-wkff/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/fx9n-wkff/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | fx9n-wkff |
| Name | forecasted-9day-river-level-update-AutoCreated |
| Created | 2014-12-17T15:09:44Z |
| Publication Date | 2015-10-15T15:12:15Z |

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
| Yes      | numeric metric | forecast    | Forecast   | number    | text        |
| Yes      | series tag     | fcsttime    | FcstTime   | text      | text        |
| Yes      | series tag     | fcstissunc  | FcstIssunc | text      | text        |
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
series e:fx9n-wkff d:2015-10-15T08:10:51.000Z t:location="Alley Spring" t:hdatum=NAD83/WGS84 t:waterbody="Jacks Fork" t:state=MO t:fcsttime=N/A t:stage=no_forecast t:units=ft t:url="http://water.weather.gov/ahps2/hydrograph.php?wfo=sgf&gage=alym7" t:wfo=sgf t:gaugelid=ALYM7 t:pedts=HGIFF t:secunit=kcfs t:fcstissunc=N/A t:lowthreshu=ft m:secvalue=-999 m:forecast=-999 m:lowthresh=1.7 m:flood=9 m:action=5.3 m:moderate=12 m:major=16

series e:fx9n-wkff d:2015-10-15T08:10:51.000Z t:location=Annapolis t:hdatum=NAD83/WGS84 t:waterbody="Black River" t:state=MO t:fcsttime=N/A t:stage=no_forecast t:units=ft t:url="http://water.weather.gov/ahps2/hydrograph.php?wfo=lsx&gage=annm7" t:wfo=lsx t:gaugelid=ANNM7 t:pedts=HGIFF t:secunit=kcfs t:fcstissunc=N/A t:lowthreshu=ft m:secvalue=-999 m:forecast=-999 m:lowthresh=0 m:flood=8 m:action=6 m:moderate=15 m:major=25

series e:fx9n-wkff d:2015-10-15T08:10:51.000Z t:location=Arnold t:hdatum=NAD83/WGS84 t:waterbody="Meramec River" t:state=MO t:fcsttime=N/A t:stage=no_forecast t:units=ft t:url="http://water.weather.gov/ahps2/hydrograph.php?wfo=lsx&gage=arnm7" t:wfo=lsx t:gaugelid=ARNM7 t:pedts=HGIFF t:secunit=kcfs t:fcstissunc=N/A t:lowthreshu=ft m:secvalue=-999 m:forecast=-999 m:lowthresh=0 m:flood=24 m:action=22 m:moderate=35 m:major=38
```

## Meta Commands

```ls
metric m:forecast p:float l:Forecast t:dataTypeName=number

metric m:action p:float l:Action t:dataTypeName=number

metric m:flood p:float l:Flood t:dataTypeName=number

metric m:moderate p:float l:Moderate t:dataTypeName=number

metric m:major p:float l:Major t:dataTypeName=number

metric m:lowthresh p:float l:LowThresh t:dataTypeName=number

metric m:secvalue p:float l:SecValue t:dataTypeName=number

entity e:fx9n-wkff l:forecasted-9day-river-level-update-AutoCreated t:url=https://data.mo.gov/api/views/fx9n-wkff

property e:fx9n-wkff t:meta.view v:id=fx9n-wkff v:averageRating=0 v:name=forecasted-9day-river-level-update-AutoCreated

property e:fx9n-wkff t:meta.view.owner v:id=jzbz-iqr6 v:screenName=Breanna v:displayName=Breanna

property e:fx9n-wkff t:meta.view.tableauthor v:id=jzbz-iqr6 v:screenName=Breanna v:roleName=administrator v:displayName=Breanna
```