# Regularly scheduled tow-away zone GIS data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/regularly-scheduled-tow-away-zone-gis-data) |
| Metadata | [Link](https://data.sfgov.org/api/views/wnhf-gu86) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/wnhf-gu86/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/wnhf-gu86/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | wnhf-gu86 |
| Name | Regularly scheduled tow-away zone GIS data |
| Category | Transportation |
| Tags | municipal transportation agency |
| Created | 2016-07-29T00:22:21Z |
| Publication Date | 2016-08-19T21:35:22Z |

## Description

This dataset contains locations and schedules of regular tow-away zones which apply at the blockface-level in San Francisco. It does not include temporary street closures which could result in towing. The dataset contains:Geospatial information for blockfaces with known tow schedulesTow schedules with starting and ending hours and days applicableAddress ranges for the blockface segmentThe centerline identifier of the street segment on which the blockface occursNotes, if known, to enhance the information about the regulation. 

This dataset was compiled in October and November of 2011. It reflects legislated changes through November 1, 2011. It is at least 95% accurate and may not include all blockface-level tow-away zones with regular, weekly schedules. Please email corrections or discrepancies to info@sfpark.org. Always look for signage near your parking space and follow posted regulations to avoid parking citations and possible towage. See http://sfpark.org/resources/regularly-scheduled-tow-away-zone-gis-data/ for more.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | numeric metric | centrdlat   | centrdlat  | number    | number      |
| Yes      | numeric metric | centrdlong  | centrdlong | number    | number      |
| Yes      | numeric metric | cnn         | cnn        | number    | number      |
| Yes      | numeric metric | endptlat    | endptlat   | number    | number      |
| Yes      | numeric metric | endptlon    | endptlon   | number    | number      |
| Yes      | series tag     | evenorodd   | evenorodd  | text      | text        |
| Yes      | numeric metric | lf_fadd     | lf_fadd    | number    | number      |
| Yes      | numeric metric | lf_toadd    | lf_toadd   | number    | number      |
| Yes      | series tag     | notes       | notes      | text      | text        |
| Yes      | numeric metric | rt_fadd     | rt_fadd    | number    | number      |
| Yes      | numeric metric | rt_toadd    | rt_toadd   | number    | number      |
| Yes      | numeric metric | shape__len  | shape__len | number    | number      |
| Yes      | series tag     | side        | side       | text      | text        |
| Yes      | numeric metric | startptlat  | startptlat | number    | number      |
| Yes      | numeric metric | startptlon  | startptlon | number    | number      |
| Yes      | series tag     | street      | street     | text      | text        |
| Yes      | series tag     | st_type     | st_type    | text      | text        |
| Yes      | series tag     | tow1days    | tow1days   | text      | text        |
| Yes      | numeric metric | tow1end     | tow1end    | number    | number      |
| Yes      | numeric metric | tow1start   | tow1start  | number    | number      |
| Yes      | series tag     | tow2days    | tow2days   | text      | text        |
| Yes      | numeric metric | tow2end     | tow2end    | number    | number      |
| Yes      | numeric metric | tow2start   | tow2start  | number    | number      |
| Yes      | series tag     | towperiod   | towperiod  | text      | text        |
| Yes      | numeric metric | towsegid    | towsegid   | number    | number      |
| Yes      | series tag     | geometry    | geometry   | line      | line        |
| Yes      | series tag     | multigeom   | multigeom  | checkbox  | checkbox    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wnhf-gu86 d:2017-04-15T15:31:06.000Z t:tow1days=Mo,Tu,We,Th,Fr t:evenorodd=Even t:side=Right t:towperiod=PMpeak t:street=BRYANT t:multigeom=false t:st_type=ST t:geometry="LINESTRING (-122.39287667088217 37.783721835507464, -122.39365469780084 37.78310704738786)" m:startptlat=37.78372 m:rt_toadd=398 m:centrdlat=37.78341 m:lf_fadd=369 m:shape__len=317 m:centrdlong=-122.39327 m:lf_toadd=399 m:rt_fadd=368 m:tow2start=0 m:endptlon=-122.39365 m:cnn=3279000 m:tow1start=1600 m:endptlat=37.78311 m:tow2end=0 m:tow1end=1900 m:towsegid=5 m:startptlon=-122.39288

series e:wnhf-gu86 d:2017-04-15T15:31:06.000Z t:tow1days=Mo,Tu,We,Th,Fr t:evenorodd=Even t:side=Right t:tow2days=Mo,Tu,We,Th,Fr t:towperiod=AMPMpeak t:street=MAIN t:multigeom=false t:st_type=ST t:geometry="LINESTRING (-122.39189519792987 37.78934029923172, -122.39035639093409 37.78810553467187)" m:startptlat=37.78934 m:rt_toadd=398 m:centrdlat=37.78872 m:lf_fadd=301 m:shape__len=632 m:centrdlong=-122.39113 m:lf_toadd=399 m:rt_fadd=300 m:tow2start=1500 m:endptlon=-122.39036 m:cnn=8630000 m:tow1start=600 m:endptlat=37.78811 m:tow2end=1900 m:tow1end=900 m:towsegid=7 m:startptlon=-122.3919

series e:wnhf-gu86 d:2017-04-15T15:31:06.000Z t:tow1days=Mo,Tu,We,Th,Fr t:evenorodd=Even t:side=Right t:towperiod=AMpeak t:street=POLK t:multigeom=false t:st_type=ST t:geometry="LINESTRING (-122.42360381464778 37.805293528832344, -122.4237934193369 37.80622843922618)" m:startptlat=37.80529 m:rt_toadd=3198 m:centrdlat=37.80576 m:lf_fadd=3101 m:shape__len=345 m:centrdlong=-122.4237 m:lf_toadd=3199 m:rt_fadd=3100 m:tow2start=0 m:endptlon=-122.42379 m:cnn=10587000 m:tow1start=600 m:endptlat=37.80623 m:tow2end=0 m:tow1end=930 m:towsegid=19 m:startptlon=-122.4236
```

## Meta Commands

```ls
metric m:centrdlat p:long l:centrdlat t:dataTypeName=number

metric m:centrdlong p:long l:centrdlong t:dataTypeName=number

metric m:cnn p:long l:cnn t:dataTypeName=number

metric m:endptlat p:long l:endptlat t:dataTypeName=number

metric m:endptlon p:long l:endptlon t:dataTypeName=number

metric m:lf_fadd p:long l:lf_fadd t:dataTypeName=number

metric m:lf_toadd p:long l:lf_toadd t:dataTypeName=number

metric m:rt_fadd p:long l:rt_fadd t:dataTypeName=number

metric m:rt_toadd p:long l:rt_toadd t:dataTypeName=number

metric m:shape__len p:long l:shape__len t:dataTypeName=number

metric m:startptlat p:long l:startptlat t:dataTypeName=number

metric m:startptlon p:long l:startptlon t:dataTypeName=number

metric m:tow1end p:long l:tow1end t:dataTypeName=number

metric m:tow1start p:long l:tow1start t:dataTypeName=number

metric m:tow2end p:long l:tow2end t:dataTypeName=number

metric m:tow2start p:long l:tow2start t:dataTypeName=number

metric m:towsegid p:long l:towsegid t:dataTypeName=number

entity e:wnhf-gu86 l:"Regularly scheduled tow-away zone GIS data" t:url=https://data.sfgov.org/api/views/wnhf-gu86

property e:wnhf-gu86 t:meta.view v:id=wnhf-gu86 v:category=Transportation v:averageRating=0 v:name="Regularly scheduled tow-away zone GIS data"

property e:wnhf-gu86 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:wnhf-gu86 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:wnhf-gu86 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | centrdlat | centrdlong | cnn        | endptlat | endptlon   | evenorodd | lf_fadd | lf_toadd | notes | rt_fadd | rt_toadd | shape__len | side  | startptlat | startptlon | street  | st_type | tow1days       | tow1end | tow1start | tow2days       | tow2end | tow2start | towperiod | towsegid | geometry                                                                                                                                                                                                                                              | multigeom | 
| =========== | ========= | ========== | ========== | ======== | ========== | ========= | ======= | ======== | ===== | ======= | ======== | ========== | ===== | ========== | ========== | ======= | ======= | ============== | ======= | ========= | ============== | ======= | ========= | ========= | ======== | ===================================================================================================================================================================================================================================================== | ========= | 
| 1492270266  | 37.78341  | -122.39327 | 3279000.0  | 37.78311 | -122.39365 | Even      | 369.0   | 399.0    |       | 368.0   | 398.0    | 317.0      | Right | 37.78372   | -122.39288 | BRYANT  | ST      | Mo,Tu,We,Th,Fr | 1900.0  | 1600.0    |                | 0.0     | 0.0       | PMpeak    | 5.0      | LINESTRING (-122.39287667088217 37.783721835507464, -122.39365469780084 37.78310704738786)                                                                                                                                                            | false     | 
| 1492270266  | 37.78872  | -122.39113 | 8630000.0  | 37.78811 | -122.39036 | Even      | 301.0   | 399.0    |       | 300.0   | 398.0    | 632.0      | Right | 37.78934   | -122.3919  | MAIN    | ST      | Mo,Tu,We,Th,Fr | 900.0   | 600.0     | Mo,Tu,We,Th,Fr | 1900.0  | 1500.0    | AMPMpeak  | 7.0      | LINESTRING (-122.39189519792987 37.78934029923172, -122.39035639093409 37.78810553467187)                                                                                                                                                             | false     | 
| 1492270266  | 37.80576  | -122.4237  | 10587000.0 | 37.80623 | -122.42379 | Even      | 3101.0  | 3199.0   |       | 3100.0  | 3198.0   | 345.0      | Right | 37.80529   | -122.4236  | POLK    | ST      | Mo,Tu,We,Th,Fr | 930.0   | 600.0     |                | 0.0     | 0.0       | AMpeak    | 19.0     | LINESTRING (-122.42360381464778 37.805293528832344, -122.4237934193369 37.80622843922618)                                                                                                                                                             | false     | 
| 1492270266  | 37.79574  | -122.39811 | 4608000.0  | 37.79618 | -122.3982  | Odd       | 301.0   | 399.0    |       | 300.0   | 398.0    | 322.0      | Left  | 37.79531   | -122.39803 | DAVIS   | ST      | Mo,Tu,We,Th,Fr | 1800.0  | 1500.0    |                | 0.0     | 0.0       | PMpeak    | 30.0     | LINESTRING (-122.39802600157425 37.79530638788589, -122.39820332010969 37.79617951766606)                                                                                                                                                             | false     | 
| 1492270266  | 37.78742  | -122.4074  | 6109000.0  | 37.78732 | -122.40822 | Odd       | 201.0   | 299.0    |       | 200.0   | 298.0    | 479.0      | Left  | 37.78753   | -122.40658 | GEARY   | ST      | Mo,Tu,We,Th,Fr | 1800.0  | 1600.0    |                | 0.0     | 0.0       | PMpeak    | 36.0     | LINESTRING (-122.40658164809773 37.787527351685505, -122.40821848891218 37.7873185891687)                                                                                                                                                             | false     | 
| 1492270266  | 37.77696  | -122.40376 | 338000.0   | 37.77669 | -122.40341 | Even      | 401.0   | 449.0    |       | 400.0   | 434.0    | 287.0      | Right | 37.77724   | -122.40411 | 06TH    | ST      | Mo,Tu,We,Th,Fr | 900.0   | 700.0     | Mo,Tu,We,Th,Fr | 1900.0  | 1500.0    | AMPMpeak  | 45.0     | LINESTRING (-122.4041070474693 37.77724364533325, -122.4034075286988 37.77668564319867)                                                                                                                                                               | false     | 
| 1492270266  | 37.77635  | -122.40298 | 339000.0   | 37.77601 | -122.40256 | Even      | 451.0   | 499.0    |       | 436.0   | 498.0    | 347.0      | Right | 37.77669   | -122.40341 | 06TH    | ST      | Mo,Tu,We,Th,Fr | 900.0   | 700.0     | Mo,Tu,We,Th,Fr | 1900.0  | 1500.0    | AMPMpeak  | 46.0     | LINESTRING (-122.4034075286993 37.77668564319908, -122.40256088713669 37.776010265193705)                                                                                                                                                             | false     | 
| 1492270266  | 37.77746  | -122.40437 | 337000.0   | 37.77724 | -122.40411 | Even      | 365.0   | 399.0    |       | 364.0   | 398.0    | 219.0      | Right | 37.77767   | -122.40464 | 06TH    | ST      | Mo,Tu,We,Th,Fr | 900.0   | 700.0     | Mo,Tu,We,Th,Fr | 1900.0  | 1500.0    | AMPMpeak  | 47.0     | LINESTRING (-122.40464229699485 37.77767060282342, -122.40410704749061 37.77724364535027)                                                                                                                                                             | false     | 
| 1492270266  | 37.77539  | -122.40179 | 340000.0   | 37.77478 | -122.40102 | Even      | 501.0   | 599.0    |       | 500.0   | 598.0    | 632.0      | Right | 37.77601   | -122.40256 | 06TH    | ST      | Mo,Tu,We,Th,Fr | 900.0   | 700.0     | Mo,Tu,We,Th,Fr | 1900.0  | 1500.0    | AMPMpeak  | 48.0     | LINESTRING (-122.40256088714959 37.776010265204015, -122.40101835827892 37.7747797197261)                                                                                                                                                             | false     | 
| 1492270266  | 37.78174  | -122.44768 | 8843201.0  | 37.78104 | -122.44755 | Even      | 0.0     | 0.0      |       | 5.0     | 99.0     | 534.0      | Right | 37.78241   | -122.44735 | MASONIC | AVE     | Mo,Tu,We,Th,Fr | 900.0   | 700.0     |                | 0.0     | 0.0       | AMpeak    | 50.0     | LINESTRING (-122.44734595067973 37.78241293037863, -122.44749859411506 37.78221222185796, -122.44768797273345 37.781728578232276, -122.44773184597358 37.78150992298066, -122.44765153462065 37.78112180597429, -122.44755573086064 37.7810412365746) | false     | 
```