# Annual 2013 Water Quality Index Scores

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/annual-2013-water-quality-index-scores-4d1fd) |
| Metadata | [Link](https://data.wa.gov/api/views/h7j9-vgr3) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/h7j9-vgr3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/h7j9-vgr3/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | h7j9-vgr3 |
| Name | Annual 2013 Water Quality Index Scores |
| Attribution | Markus Von Prasue, WA State Department of Ecology's River and Stream Monitoring Program |
| Category | Natural Resources & Environment |
| Tags | water quality index, 2013 river and stream water quality monitoirng data, ecology, state-of-the-salmon |
| Created | 2014-04-23T22:51:19Z |
| Publication Date | 2014-04-28T16:11:25Z |

## Description

Routine freshwater monitoring data collected by the The WA State Department of Ecology's River and Stream Monitoring Program are summarized by a technique called the "Water Quality Index" (WQI).  The WQI ranges from 1 (poor quality) to 100 (good quality). The WQI summary does not include non-standard elements like metals. For temperature, pH, oxygen, and fecal coliform bacteria, the WQI is based on criteria in Washington?s Water Quality Standards, WAC 173-201A. 
For nutrient and sediment measures where standards are not specific, results are based on expected conditions in a given region. Multiple constituents are combined and results aggregated over time to produce a single score for each station and each year.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       |                | id              | ID              | text      | number      |
| Yes      | series tag     | station         | STATION         | text      | text        |
| Yes      | series tag     | station_name    | STATION NAME    | text      | text        |
| Yes      | numeric metric | overallwqi_2013 | OVERALLWQI 2013 | number    | number      |
| Yes      | numeric metric | wqifc           | WQIFC           | number    | number      |
| Yes      | numeric metric | wqioxy          | WQIOXY          | number    | number      |
| Yes      | numeric metric | wqiph           | WQIPH           | number    | number      |
| Yes      | numeric metric | wqitss          | WQITSS          | number    | number      |
| Yes      | numeric metric | wqitemp         | WQITEMP         | number    | number      |
| Yes      | numeric metric | wqitpn          | WQITPN          | number    | number      |
| Yes      | numeric metric | wqitp           | WQITP           | number    | number      |
| Yes      | numeric metric | wqiturb         | WQITURB         | number    | number      |
| Yes      | series tag     | core            | CORE            | text      | text        |
| Yes      | numeric metric | cat             | CAT             | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:h7j9-vgr3 d:2013-01-01T00:00:00.000Z t:station_name="Skagit R nr Mount Vernon" t:station=03A060 t:core=C m:cat=1 m:wqitss=66 m:wqitemp=84 m:wqiturb=85 m:wqitp=89 m:wqitpn=98 m:overallwqi_2013=86 m:wqiph=92 m:wqioxy=82 m:wqifc=94

series e:h7j9-vgr3 d:2013-01-01T00:00:00.000Z t:station_name="Samish R nr Burlington" t:station=03B050 t:core=C m:cat=1 m:wqitss=87 m:wqitemp=86 m:wqiturb=87 m:wqitp=84 m:wqitpn=41 m:overallwqi_2013=86 m:wqiph=93 m:wqioxy=77 m:wqifc=79

series e:h7j9-vgr3 d:2013-01-01T00:00:00.000Z t:station_name="Skagit R @ Marblemount" t:station=04A100 t:core=C m:cat=2 m:wqitss=67 m:wqitemp=90 m:wqiturb=59 m:wqitp=99 m:wqitpn=82 m:overallwqi_2013=75 m:wqiph=93 m:wqioxy=93 m:wqifc=98
```

## Meta Commands

```ls
metric m:overallwqi_2013 p:integer l:"OVERALLWQI 2013" t:dataTypeName=number

metric m:wqifc p:integer l:WQIFC t:dataTypeName=number

metric m:wqioxy p:integer l:WQIOXY t:dataTypeName=number

metric m:wqiph p:integer l:WQIPH t:dataTypeName=number

metric m:wqitss p:integer l:WQITSS t:dataTypeName=number

metric m:wqitemp p:integer l:WQITEMP t:dataTypeName=number

metric m:wqitpn p:integer l:WQITPN t:dataTypeName=number

metric m:wqitp p:integer l:WQITP t:dataTypeName=number

metric m:wqiturb p:integer l:WQITURB t:dataTypeName=number

metric m:cat p:integer l:CAT t:dataTypeName=number

entity e:h7j9-vgr3 l:"Annual 2013 Water Quality Index Scores" t:attribution="Markus Von Prasue, WA State Department of Ecology's River and Stream Monitoring Program" t:url=https://data.wa.gov/api/views/h7j9-vgr3

property e:h7j9-vgr3 t:meta.view v:id=h7j9-vgr3 v:category="Natural Resources & Environment" v:attributionLink=http://www.ecy.wa.gov/programs/eap/fw_riv/rv_main.html v:averageRating=0 v:name="Annual 2013 Water Quality Index Scores" v:attribution="Markus Von Prasue, WA State Department of Ecology's River and Stream Monitoring Program"

property e:h7j9-vgr3 t:meta.view.license v:name="Public Domain"

property e:h7j9-vgr3 t:meta.view.owner v:id=q8y9-svx9 v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:displayName="Markus.Von Prause@ecy.wa.gov"

property e:h7j9-vgr3 t:meta.view.tableauthor v:id=q8y9-svx9 v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:roleName=publisher v:displayName="Markus.Von Prause@ecy.wa.gov"
```

## Top Records

```ls
| id | station | station_name                        | overallwqi_2013 | wqifc | wqioxy | wqiph | wqitss | wqitemp | wqitpn | wqitp | wqiturb | core | cat | 
| == | ======= | =================================== | =============== | ===== | ====== | ===== | ====== | ======= | ====== | ===== | ======= | ==== | === | 
| 3  | 03A060  | Skagit R nr Mount Vernon            | 86              | 94    | 82     | 92    | 66     | 84      | 98     | 89    | 85      | C    | 1   | 
| 4  | 03B050  | Samish R nr Burlington              | 86              | 79    | 77     | 93    | 87     | 86      | 41     | 84    | 87      | C    | 1   | 
| 5  | 04A100  | Skagit R @ Marblemount              | 75              | 98    | 93     | 93    | 67     | 90      | 82     | 99    | 59      | C    | 2   | 
| 6  | 05A065  | N Slough Stillaquamish@ Pioneer Hwy | 79              | 86    | 83     | 92    | 73     | 72      | 81     | 78    | 73      | B    | 2   | 
| 7  | 05A070  | Stillaguamish R nr Silvana          | 79              | 86    | 86     | 94    | 72     | 73      | 85     | 79    | 68      | C    | 2   | 
| 8  | 05A090  | SF Stillaguamish R @ Arlington      | 69              | 83    | 74     | 92    | 65     | 73      | 88     | 67    | 62      | C    | 3   | 
| 9  | 05A110  | SF Stillaguamish R nr Granite Falls | 66              | 81    | 78     | 93    | 47     | 74      | 94     | 54    | 43      | C    | 3   | 
| 10 | 05B070  | NF Stillaguamish R @ Cicero         | 40              | 85    | 83     | 93    | 19     | 79      | 10     | 46    | 17      | C    | 4   | 
| 11 | 05B110  | NF Stillaguamish R nr Darrington    | 79              | 92    | 86     | 92    | 82     | 75      | 37     | 95    | 75      | C    | 2   | 
| 12 | 07A090  | Snohomish R @ Snohomish             | 88              | 86    | 87     | 89    | 86     | 78      | 84     | 90    | 89      | C    | 1   | 
```