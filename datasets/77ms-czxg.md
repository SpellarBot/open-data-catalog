# SDOT Curb Space Categories

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-curb-space-categories) |
| Metadata | [Link](https://data.seattle.gov/api/views/77ms-czxg) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/77ms-czxg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/77ms-czxg/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 77ms-czxg |
| Name | SDOT Curb Space Categories |
| Category | Transportation |
| Tags | parking |
| Created | 2016-04-21T15:47:57Z |
| Publication Date | 2016-05-03T07:44:30Z |

## Description

The existing type of space and length of the space that exists along a street segment.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type  | Render Type |
| ======== | ============== | ============== | ============== | ========== | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data  | meta_data   |
| Yes      | series tag     | objectid       | OBJECTID       | text       | number      |
| Yes      | series tag     | blockid        | BLOCKID        | text       | text        |
| Yes      | numeric metric | rownbr         | ROWNBR         | number     | number      |
| Yes      | numeric metric | block_st       | BLOCK_ST       | number     | number      |
| Yes      | numeric metric | block_end      | BLOCK_END      | number     | number      |
| No       |                | width_offset   | WIDTH_OFFSET   | number     | number      |
| Yes      | numeric metric | geobasys       | GEOBASYS       | number     | number      |
| Yes      | numeric metric | spacelength    | SPACELENGTH    | number     | number      |
| Yes      | series tag     | spacetype      | SPACETYPE      | text       | text        |
| Yes      | series tag     | spacetypedesc  | SPACETYPEDESC  | text       | text        |
| No       |                | time_limit     | TIME_LIMIT     | number     | text        |
| Yes      | series tag     | space_nb       | SPACE_NB       | text       | text        |
| Yes      | series tag     | category       | CATEGORY       | text       | text        |
| No       |                | shape          | Shape          | geospatial | geospatial  |
| Yes      | series tag     | side           | SIDE           | text       | text        |
| Yes      | series tag     | current_status | CURRENT_STATUS | text       | text        |
| Yes      | numeric metric | elmntkey       | ELMNTKEY       | number     | number      |
| Yes      | numeric metric | shape_length   | Shape_Length   | number     | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = width_offset,time_limit,shape
```

## Data Commands

```ls
series e:77ms-czxg d:2016-04-21T15:47:57.000Z t:shape.longitude=-122.38235641299997 t:blockid=NWMT-20 t:category=NP t:side=S t:shape.needs_recoding=false t:spacetypedesc=CLEARANCE t:shape.latitude=47.66859378000004 t:objectid=1 t:current_status=INSVC t:spacetype=CLR m:spacelength=6 m:shape_length=5.972465827466254 m:block_end=62 m:block_st=56 m:elmntkey=87254

series e:77ms-czxg d:2016-04-21T15:47:57.000Z t:shape.longitude=-122.36012310899997 t:category=UNR t:side=S t:shape.needs_recoding=false t:spacetypedesc=UNRESTRICTED t:shape.latitude=47.63347984400008 t:objectid=2 t:current_status=INSVC t:spacetype=UNR m:spacelength=21 m:shape_length=20.92465778735893 m:block_end=134 m:block_st=113 m:elmntkey=68442

series e:77ms-czxg d:2016-04-21T15:47:57.000Z t:shape.longitude=-122.34131332899995 t:blockid=01-19 t:category=NP t:side=NE t:shape.needs_recoding=false t:spacetypedesc=CLEARANCE t:shape.latitude=47.61037732600005 t:objectid=3 t:current_status=INSVC t:spacetype=CLR m:spacelength=1 m:shape_length=0.9975653617033926 m:block_end=29 m:block_st=28 m:elmntkey=1018
```

## Meta Commands

```ls
metric m:rownbr p:long l:ROWNBR d:ROWNBR t:dataTypeName=number

metric m:block_st p:double l:BLOCK_ST d:BLOCK_ST t:dataTypeName=number

metric m:block_end p:integer l:BLOCK_END d:BLOCK_END t:dataTypeName=number

metric m:geobasys p:long l:GEOBASYS d:GEOBASYS t:dataTypeName=number

metric m:spacelength p:integer l:SPACELENGTH d:SPACELENGTH t:dataTypeName=number

metric m:elmntkey p:integer l:ELMNTKEY d:ELMNTKEY t:dataTypeName=number

metric m:shape_length p:decimal l:Shape_Length d:Shape_Length t:dataTypeName=number

entity e:77ms-czxg l:"SDOT Curb Space Categories" t:url=https://data.seattle.gov/api/views/77ms-czxg

property e:77ms-czxg t:meta.view v:id=77ms-czxg v:category=Transportation v:averageRating=0 v:name="SDOT Curb Space Categories"

property e:77ms-czxg t:meta.view.license v:name="Public Domain"

property e:77ms-czxg t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:77ms-czxg t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| :updated_at | objectid | blockid | rownbr | block_st | block_end | width_offset | geobasys | spacelength | spacetype | spacetypedesc | time_limit | space_nb | category | shape                                                                                                                                                         | side | current_status | elmntkey | shape_length                                           | 
| =========== | ======== | ======= | ====== | ======== | ========= | ============ | ======== | =========== | ========= | ============= | ========== | ======== | ======== | ============================================================================================================================================================= | ==== | ============== | ======== | ====================================================== | 
| 0           | 1        | NWMT-20 |        | 56       | 62        | 30           |          | 6           | CLR       | CLEARANCE     |            |          | NP       | [null, 47.66859378000004, -122.38235641299997, null, false, {paths=[[[-122.38235641299997, 47.66859378000004], [-122.38238065299998, 47.66859380400007]]]}]   | S    | INSVC          | 87254    | 5.97246582746625431781239967676810920238494873046875   | 
| 0           | 2        |         |        | 113      | 134       | 18           |          | 21          | UNR       | UNRESTRICTED  |            |          | UNR      | [null, 47.63347984400008, -122.36012310899997, null, false, {paths=[[[-122.36012310899997, 47.63347984400008], [-122.36020797599997, 47.633479857000054]]]}]  | S    | INSVC          | 68442    | 20.92465778735893167095127864740788936614990234375     | 
| 0           | 3        | 01-19   |        | 28       | 29        | -26          |          | 1           | CLR       | CLEARANCE     |            |          | NP       | [null, 47.61037732600005, -122.34131332899995, null, false, {paths=[[[-122.34131332899995, 47.61037732600005], [-122.34131545599996, 47.61037965200006]]]}]   | NE   | INSVC          | 1018     | 0.9975653617033926057189319180906750261783599853515625 | 
| 0           | 4        |         |        | 132      | 152       | -19          |          | 20          | UNR       | UNRESTRICTED  |            |          | UNR      | [null, 47.63358129100004, -122.36019986099996, null, false, {paths=[[[-122.36019986099996, 47.63358129100004], [-122.36028068699994, 47.63358130300003]]]}]   | N    | INSVC          | 68441    | 19.928297678282643090597048285417258739471435546875    | 
| 0           | 5        |         |        | 107      | 125       | -22          |          | 18          | TL        | TIME LIMIT    | 120        |          | TL       | [null, 47.62290766700005, -122.29690470799994, null, false, {paths=[[[-122.29690470799994, 47.62290766700005], [-122.29685320699997, 47.62294242400003]]]}]   | SE   | INSVC          | 59722    | 17.945644276900846847411230555735528469085693359375    | 
| 0           | 6        | S07-05  |        | 155.5    | 174.5     | 24           |          | 19          | PS        | PAY STATION   | 120        | -12      | PAID     | [null, 47.59792473600004, -122.32365801399999, null, false, {paths=[[[-122.32365801399999, 47.59792473600004], [-122.32365820199999, 47.59787281400003]]]}]   | E    | INSVC          | 8302     | 18.939482180266342226104825385846197605133056640625    | 
| 0           | 7        | S7-06   |        | 18       | 31        | 26           |          | 13          | XW        | CROSSWALK     |            |          | NS       | [null, 47.59674743700003, -122.32629749699998, null, false, {paths=[[[-122.32629749699998, 47.59674743700003], [-122.32624496899996, 47.59674736000005]]]}]   | N    | INSVC          | 43117    | 12.960389917621636612921065534465014934539794921875    | 
| 0           | 8        | 7-10    |        | 150.5    | 174.5     | -18          |          | 24          | ALLEY     | ALLEY         |            | -13      | NS       | [null, 47.60690711800004, -122.32373738499996, null, false, {paths=[[[-122.32373738499996, 47.60690711800004], [-122.32365480699997, 47.60694163900007]]]}]   | SE   | INSVC          | 9698     | 23.948129808862415046633032034151256084442138671875    | 
| 0           | 9        | 05-10   |        | 82.5     | 100       | 22           |          | 18          | PS        | PAY STATION   | 120        | -05      | PAID     | [null, 47.606712757000025, -122.33204947399997, null, false, {paths=[[[-122.33204947399997, 47.606712757000025], [-122.33208670599998, 47.60675343200006]]]}] | SW   | INSVC          | 75153    | 17.449730505714580175435912678949534893035888671875    | 
| 0           | 10       |         |        | 374      | 415       | 17           |          | 41          | TAZ       | TOW AWAY ZONE |            |          | NP       | [null, 47.63697902100006, -122.35835267499999, null, false, {paths=[[[-122.35835267499999, 47.63697902100006], [-122.35835135199994, 47.63709115200004]]]}]   | W    | INSVC          | 69149    | 40.90277380739081536376033909618854522705078125        | 
```