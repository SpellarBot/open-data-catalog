# GISADMIN.SOCRATA_FIRE_INCIDENTS_01012012_12312013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/gisadmin-socrata-fire-incidents-01012012-12312013) |
| Metadata | [Link](https://data.hartford.gov/api/views/rwu6-8j9d) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/rwu6-8j9d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/rwu6-8j9d/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | rwu6-8j9d |
| Name | GISADMIN.SOCRATA_FIRE_INCIDENTS_01012012_12312013 |
| Created | 2015-06-25T11:48:45Z |
| Publication Date | 2015-06-25T11:50:10Z |
| Rows Updated | 2015-07-09T11:15:58Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | objectid   | OBJECTID   | text      | number      |
| Yes      | time           | alm_time   | alm_time   | date      | date        |
| No       |                | alm_date   | alm_date   | date      | date        |
| Yes      | series tag     | inci_no    | inci_no    | text      | text        |
| Yes      | numeric metric | station    | station    | number    | number      |
| Yes      | series tag     | occup_id   | occup_id   | text      | number      |
| Yes      | numeric metric | number     | number     | number    | number      |
| Yes      | series tag     | st_prefix  | st_prefix  | text      | text        |
| Yes      | series tag     | street     | street     | text      | text        |
| Yes      | series tag     | st_type    | st_type    | text      | text        |
| Yes      | series tag     | st_suffix  | st_suffix  | text      | text        |
| Yes      | series tag     | xstreet    | xstreet    | text      | text        |
| Yes      | series tag     | xst_prefix | xst_prefix | text      | text        |
| Yes      | series tag     | xst_type   | xst_type   | text      | text        |
| Yes      | series tag     | xst_suffix | xst_suffix | text      | text        |
| Yes      | series tag     | city       | city       | text      | text        |
| Yes      | series tag     | state      | state      | text      | text        |
| Yes      | series tag     | zip        | zip        | text      | number      |
| No       |                | latitude   | latitude   | number    | number      |
| No       |                | longitude  | longitude  | number    | number      |
| Yes      | series tag     | mutl_aid   | mutl_aid   | text      | text        |
| Yes      | numeric metric | shift      | shift      | number    | text        |
| Yes      | numeric metric | alarms     | alarms     | number    | number      |
| Yes      | numeric metric | alm_type   | alm_type   | number    | number      |
| Yes      | numeric metric | inci_type  | inci_type  | number    | number      |
| Yes      | series tag     | descript   | descript   | text      | text        |
```

## Time Field

```ls
Value = alm_time
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = alm_date,longitude,latitude
```

## Data Commands

```ls
series e:rwu6-8j9d d:2017-03-10T23:15:48.227Z t:zip=6112 t:mutl_aid=N t:street=VINE t:occup_id=5701 t:descript="EMS call, excluding vehicle accident with injury" t:state=CT t:st_type=ST t:objectid=32100 t:shift=A t:inci_no=13-0165020 t:city=Hartford m:alm_type=1 m:station=16 m:inci_type=321 m:number=500 m:alarms=1

series e:rwu6-8j9d d:2017-03-10T23:15:48.227Z t:zip=6105 t:mutl_aid=N t:street=SISSON t:occup_id=19549 t:descript="Medical assist, assist EMS crew" t:state=CT t:st_type=AV t:objectid=18015 t:shift=B t:inci_no=12-0300023 t:city=Hartford m:alm_type=1 m:station=11 m:inci_type=311 m:number=170 m:alarms=1

series e:rwu6-8j9d d:2017-03-10T23:15:48.227Z t:zip=6114 t:mutl_aid=N t:street=KENNETH t:occup_id=33109 t:descript="False alarm or false call, Other" t:state=CT t:st_type=ST t:objectid=12578 t:shift=D t:inci_no=12-0210049 t:city=Hartford m:alm_type=1 m:station=15 m:inci_type=700 m:number=8 m:alarms=1
```

## Meta Commands

```ls
metric m:station p:integer l:station t:dataTypeName=number

metric m:number p:integer l:number t:dataTypeName=number

metric m:alarms p:integer l:alarms t:dataTypeName=number

metric m:alm_type p:integer l:alm_type t:dataTypeName=number

metric m:inci_type p:integer l:inci_type t:dataTypeName=number

entity e:rwu6-8j9d l:GISADMIN.SOCRATA_FIRE_INCIDENTS_01012012_12312013 t:url=https://data.hartford.gov/api/views/rwu6-8j9d

property e:rwu6-8j9d t:meta.view v:id=rwu6-8j9d v:averageRating=0 v:name=GISADMIN.SOCRATA_FIRE_INCIDENTS_01012012_12312013

property e:rwu6-8j9d t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett

property e:rwu6-8j9d t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```