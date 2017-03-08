# Water Quality Index Scores (1994-2013) from The WA State Department of Ecology's River and Stream Monitoring Program.

## Dataset

* [Dataset URL](https://data.wa.gov/api/views/k5fe-2e4s/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/water-quality-index-scores-1994-2013-from-the-wa-state-department-of-ecologys-river-and-st-cb79b)
* [Metadata URL](https://data.wa.gov/api/views/k5fe-2e4s)
* Id = k5fe-2e4s
* Name = Water Quality Index Scores (1994-2013) from The WA State Department of Ecology's River and Stream Monitoring Program.
* Attribution = Markus Von Prause, WA State Department of Ecology's River and Stream Monitoring Program
* [Attribution Link](http://www.ecy.wa.gov/programs/eap/fw_riv/rv_main.html)
* Category = Natural Resources & Environment
* Tags = [water quality index, washington state river and stream fresh water quality, ecology]
* Created = 2014-04-23T22:08:10Z
* Publication Date = 2014-04-28T16:52:44Z
* Rows Updated = 2014-04-23T22:29:45Z

## Description

Routine freshwater monitoring data collected by the The WA State Department of Ecology's River and Stream Monitoring Program are summarized by a technique called the "Water Quality Index" (WQI).  The WQI ranges from 1 (poor quality) to 100 (good quality). The WQI summary does not include non-standard elements like metals. For temperature, pH, oxygen, and fecal coliform bacteria, the WQI is based on criteria in Washington?s Water Quality Standards, WAC 173-201A. 
For nutrient and sediment measures where standards are not specific, results are based on expected conditions in a given region. Multiple constituents are combined and results aggregated over time to produce a single score for each station and each year.

## Columns

```ls
| Name         | Field Name   | Data Type | Render Type | Schema Type    | Included | 
| ============ | ============ | ========= | =========== | ============== | ======== | 
| updated_at   | :updated_at  | meta_data | meta_data   | time           | No       | 
| Station      | station      | text      | text        | series tag     | Yes      | 
| Station Name | station_name | text      | text        | series tag     | Yes      | 
| SSR          | ssr          | text      | text        | series tag     | Yes      | 
| 1994         | 1994         | number    | number      | numeric metric | Yes      | 
| 1995         | 1995         | number    | number      | numeric metric | Yes      | 
| 1996         | 1996         | number    | number      | numeric metric | Yes      | 
| 1997         | 1997         | number    | number      | numeric metric | Yes      | 
| 1998         | 1998         | number    | number      | numeric metric | Yes      | 
| 1999         | 1999         | number    | number      | numeric metric | Yes      | 
| 2000         | 2000         | number    | number      | numeric metric | Yes      | 
| 2001         | 2001         | number    | number      | numeric metric | Yes      | 
| 2002         | 2002         | number    | number      | numeric metric | Yes      | 
| 2003         | 2003         | number    | number      | numeric metric | Yes      | 
| 2004         | 2004         | number    | number      | numeric metric | Yes      | 
| 2005         | 2005         | number    | number      | numeric metric | Yes      | 
| 2006         | 2006         | number    | number      | numeric metric | Yes      | 
| 2007         | 2007         | number    | number      | numeric metric | Yes      | 
| 2008         | 2008         | number    | number      | numeric metric | Yes      | 
| 2009         | 2009         | number    | number      | numeric metric | Yes      | 
| 2010         | 2010         | number    | number      | numeric metric | Yes      | 
| 2011         | 2011         | number    | number      | numeric metric | Yes      | 
| 2012         | 2012         | number    | number      | numeric metric | Yes      | 
| 2013         | 2013         | number    | number      | numeric metric | Yes      | 
| Ave          | ave          | number    | number      | numeric metric | Yes      | 
| Comment      | comment      | text      | text        | series tag     | Yes      | 
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
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:k5fe-2e4s d:2014-04-23T15:08:16.000Z t:station_name="Humptulips R nr Humptulips" t:station=22A070 t:ssr=Coast t:comment="Annual sediment and phosphorus scores were usually below 80.  Temperature scores were below 80 about half the time. Average Bacteria, Oxygen, Nitrogen and pH scores were usually above 80. The Humptulips has an approved temperature management plan and is listed for oxygen and pH." m:2008=73 m:2009=78 m:2006=70 m:2007=67 m:2013=84 m:2004=68 m:2005=77 m:2002=75 m:2003=74 m:1995=76 m:1996=75 m:1997=76 m:1998=66 m:1994=84 m:2012=94 m:2011=70 m:2010=75 m:1999=76 m:ave=76 m:2001=81 m:2000=86

series e:k5fe-2e4s d:2014-04-23T15:08:16.000Z t:station_name="Hoh R @ DNR Campground" t:station=20B070 t:ssr=Coast t:comment="Annual sediment and phosphorus scores were usually below 80. Bacteria and temperature scores were occasionally below 80. Other scores were usually above 80. The watershed contains glaciers that contribute much of the sediment that is the primary contributor to overall WQI scores below 80. However, higher bacteria counts since the mid-2000s have also contributed to lower scores.  The Hoh is currently on the 303(d) list for bacteria." m:2008=68 m:2009=67 m:2006=60 m:2007=39 m:2013=68 m:2004=51 m:2005=56 m:2002=80 m:2003=72 m:1995=67 m:1996=73 m:1997=57 m:1998=66 m:1994=77 m:2012=83 m:2011=70 m:2010=60 m:1999=64 m:ave=67 m:2001=76 m:2000=79

series e:k5fe-2e4s d:2014-04-23T15:08:16.000Z t:station_name="Naselle R nr Naselle" t:station=24F070 t:ssr=Coast t:comment="Annual bacteria, temperature, nutrient, and sediment scores were all below 80 most of the time. Oxygen and pH scores were occasionally below 80.  The Naselle is currently listed for temperature." m:2008=84 m:2009=84 m:2006=76 m:2007=77 m:2013=79 m:2004=65 m:2005=78 m:2002=51 m:2003=64 m:1995=4 m:1996=60 m:1997=74 m:1998=46 m:2012=74 m:2011=63 m:2010=58 m:1999=58 m:ave=65 m:2001=69 m:2000=67
```

## Meta Commands

```ls
metric m:1994 p:integer l:1994 t:dataTypeName=number

metric m:1995 p:integer l:1995 t:dataTypeName=number

metric m:1996 p:integer l:1996 t:dataTypeName=number

metric m:1997 p:integer l:1997 t:dataTypeName=number

metric m:1998 p:integer l:1998 t:dataTypeName=number

metric m:1999 p:integer l:1999 t:dataTypeName=number

metric m:2000 p:integer l:2000 t:dataTypeName=number

metric m:2001 p:integer l:2001 t:dataTypeName=number

metric m:2002 p:integer l:2002 t:dataTypeName=number

metric m:2003 p:integer l:2003 t:dataTypeName=number

metric m:2004 p:integer l:2004 t:dataTypeName=number

metric m:2005 p:integer l:2005 t:dataTypeName=number

metric m:2006 p:integer l:2006 t:dataTypeName=number

metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:2010 p:integer l:2010 t:dataTypeName=number

metric m:2011 p:integer l:2011 t:dataTypeName=number

metric m:2012 p:integer l:2012 t:dataTypeName=number

metric m:2013 p:integer l:2013 t:dataTypeName=number

metric m:ave p:integer l:Ave d:"Average WQI Score during the period of 1994-2013." t:dataTypeName=number

entity e:k5fe-2e4s l:"Water Quality Index Scores (1994-2013) from The WA State Department of Ecology's River and Stream Monitoring Program." t:attribution="Markus Von Prause, WA State Department of Ecology's River and Stream Monitoring Program" t:url=https://data.wa.gov/api/views/k5fe-2e4s

property e:k5fe-2e4s t:meta.view d:2017-03-07T23:52:24.434Z v:id=k5fe-2e4s v:category="Natural Resources & Environment" v:attributionLink=http://www.ecy.wa.gov/programs/eap/fw_riv/rv_main.html v:averageRating=0 v:name="Water Quality Index Scores (1994-2013) from The WA State Department of Ecology's River and Stream Monitoring Program." v:attribution="Markus Von Prause, WA State Department of Ecology's River and Stream Monitoring Program"

property e:k5fe-2e4s t:meta.view.license d:2017-03-07T23:52:24.434Z v:name="Public Domain"

property e:k5fe-2e4s t:meta.view.owner d:2017-03-07T23:52:24.434Z v:id=q8y9-svx9 v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:roleName=publisher v:displayName="Markus.Von Prause@ecy.wa.gov"

property e:k5fe-2e4s t:meta.view.tableauthor d:2017-03-07T23:52:24.434Z v:id=q8y9-svx9 v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:roleName=publisher v:displayName="Markus.Von Prause@ecy.wa.gov"
```