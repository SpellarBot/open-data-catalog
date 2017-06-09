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

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | objectid   | OBJECTID   | text      | number      |
| No       |                | alm_time   | alm_time   | date      | date        |
| Yes      | time           | alm_date   | alm_date   | date      | date        |
| Yes      | series tag     | inci_no    | inci_no    | text      | text        |
| Yes      | series tag     | station    | station    | text      | number      |
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
| Yes      | series tag     | shift      | shift      | text      | text        |
| Yes      | numeric metric | alarms     | alarms     | number    | number      |
| Yes      | series tag     | alm_type   | alm_type   | text      | number      |
| Yes      | series tag     | inci_type  | inci_type  | text      | number      |
| Yes      | series tag     | descript   | descript   | text      | text        |
```

## Time Field

```ls
Value = alm_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = alm_time,latitude,longitude
```

## Data Commands

```ls
series e:rwu6-8j9d d:2013-06-14T00:00:00.000Z t:zip=6112 t:mutl_aid=N t:station=16 t:occup_id=5701 t:street=VINE t:state=CT t:descript="EMS call, excluding vehicle accident with injury" t:inci_type=321 t:city=Hartford t:alm_type=1 t:st_type=ST t:objectid=32100 t:shift=A t:inci_no=13-0165020 m:number=500 m:alarms=1

series e:rwu6-8j9d d:2012-10-26T00:00:00.000Z t:zip=6105 t:mutl_aid=N t:station=11 t:occup_id=19549 t:street=SISSON t:state=CT t:descript="Medical assist, assist EMS crew" t:inci_type=311 t:city=Hartford t:alm_type=1 t:st_type=AV t:objectid=18015 t:shift=B t:inci_no=12-0300023 m:number=170 m:alarms=1

series e:rwu6-8j9d d:2012-07-28T00:00:00.000Z t:zip=6114 t:mutl_aid=N t:station=15 t:occup_id=33109 t:street=KENNETH t:state=CT t:descript="False alarm or false call, Other" t:inci_type=700 t:city=Hartford t:alm_type=1 t:st_type=ST t:objectid=12578 t:shift=D t:inci_no=12-0210049 m:number=8 m:alarms=1
```

## Meta Commands

```ls
metric m:number p:integer l:number t:dataTypeName=number

metric m:alarms p:integer l:alarms t:dataTypeName=number

entity e:rwu6-8j9d l:GISADMIN.SOCRATA_FIRE_INCIDENTS_01012012_12312013 t:url=https://data.hartford.gov/api/views/rwu6-8j9d

property e:rwu6-8j9d t:meta.view d:2017-06-09T14:00:18.673Z v:id=rwu6-8j9d v:averageRating=0 v:name=GISADMIN.SOCRATA_FIRE_INCIDENTS_01012012_12312013

property e:rwu6-8j9d t:meta.view.owner d:2017-06-09T14:00:18.673Z v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:rwu6-8j9d t:meta.view.tableauthor d:2017-06-09T14:00:18.673Z v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| objectid | alm_time | alm_date   | inci_no    | station | occup_id | number | st_prefix | street    | st_type | st_suffix | xstreet | xst_prefix | xst_type | xst_suffix | city     | state | zip  | latitude  | longitude  | mutl_aid | shift | alarms | alm_type | inci_type | descript                                         | 
| ======== | ======== | ========== | ========== | ======= | ======== | ====== | ========= | ========= | ======= | ========= | ======= | ========== | ======== | ========== | ======== | ===== | ==== | ========= | ========== | ======== | ===== | ====== | ======== | ========= | ================================================ | 
| 32100    |          | 1371168000 | 13-0165020 | 16      | 5701     | 500    |           | VINE      | ST      |           |         |            |          |            | Hartford | CT    | 6112 | 41.794    | -72.687    | N        | A     | 1      | 1        | 321       | EMS call, excluding vehicle accident with injury | 
| 18015    |          | 1351209600 | 12-0300023 | 11      | 19549    | 170    |           | SISSON    | AV      |           |         |            |          |            | Hartford | CT    | 6105 | 41.763408 | -72.707046 | N        | B     | 1      | 1        | 311       | Medical assist, assist EMS crew                  | 
| 12578    |          | 1343433600 | 12-0210049 | 15      | 33109    | 8      |           | KENNETH   | ST      |           |         |            |          |            | Hartford | CT    | 6114 | 41.741174 | -72.6846   | N        | D     | 1      | 1        | 700       | False alarm or false call, Other                 | 
| 18704    |          | 1352073600 | 12-0310054 | 9       | 37052    | 43     |           | SOMERS    | ST      |           |         |            |          |            | Hartford | CT    | 6106 | 41.726955 | -72.7031   | N        | D     | 1      | 1        | 745       | Alarm system activation, no fire - unintentional | 
| 28321    |          | 1366156800 | 13-0107019 | 9       | 28767    | 61     |           | ARLINGTON | ST      |           |         |            |          |            | Hartford | CT    | 6106 | 41.734991 | -72.706655 | N        | C     | 1      | 3        | 735       | Alarm system sounded due to malfunction          | 
| 19004    |          | 1352505600 | 12-0315033 | 9       | 28680    | 699    |           | BROADVIEW | TER     |           |         |            |          |            | Hartford | CT    | 6106 | 41.734262 | -72.705492 | N        | A     | 1      | 1        | 321       | EMS call, excluding vehicle accident with injury | 
| 33779    |          | 1373155200 | 13-0188068 | 10      | 35841    | 7      |           | MEADOW    | ST      |           |         |            |          |            | Hartford | CT    | 6114 | 41.743531 | -72.67311  | N        | D     | 1      | 1        | 440       | Electrical wiring/equipment problem, Other       | 
| 36373    |          | 1376438400 | 13-0226045 | 2       |          |        |           | FLORENCE  | ST      |           | MAIN    |            | ST       |            | Hartford | CT    | 6120 | 41.7763   | -72.6771   | N        | B     | 1      | 1        | 324       | Motor Vehicle Accident with no injuries          | 
| 12794    |          | 1343779200 | 12-0214051 | 2       | 18440    | 73     |           | PLINY     | ST      |           |         |            |          |            | Hartford | CT    | 6120 | 41.780604 | -72.683337 | N        | D     | 1      | 1        | 321       | EMS call, excluding vehicle accident with injury | 
| 13703    |          | 1345075200 | 12-0229035 | 1       |          |        |           | RETREAT   | AV      |           | SEYMOUR |            | ST       |            | Hartford | CT    | 6106 | 41.7518   | -72.6814   | N        | C     | 1      | 1        | 311       | Medical assist, assist EMS crew                  | 
```