# FH_SOCRATA

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fh-socrata) |
| Metadata | [Link](https://data.hartford.gov/api/views/anj2-ytvy) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/anj2-ytvy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/anj2-ytvy/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | anj2-ytvy |
| Name | FH_SOCRATA |
| Attribution | City of Hartford |
| Category | Public Safety |
| Tags | fire, public safety, hartford fire department, fire incidents, hartford |
| Created | 2014-04-20T17:16:21Z |
| Publication Date | 2015-07-11T22:51:57Z |

## Description

Current Year Fire Incidents. Updated on a nightly basis. For more information on the inci_typ codes select the about tab and scroll down to the attachments and open the PDF document

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| No       |                | alm_time   | alm_time   | text          | text          |
| No       |                | alm_date   | alm_date   | calendar_date | calendar_date |
| Yes      | series tag     | inci_no    | inci_no    | text          | text          |
| Yes      | series tag     | station    | station    | text          | text          |
| Yes      | series tag     | occup_id   | occup_id   | text          | text          |
| Yes      | series tag     | number     | number     | text          | text          |
| Yes      | series tag     | st_prefix  | st_prefix  | text          | text          |
| Yes      | series tag     | street     | street     | text          | text          |
| Yes      | series tag     | st_type    | st_type    | text          | text          |
| Yes      | series tag     | st_suffix  | st_suffix  | text          | text          |
| Yes      | series tag     | xstreet    | xstreet    | text          | text          |
| Yes      | series tag     | xst_prefix | xst_prefix | text          | text          |
| Yes      | series tag     | xst_type   | xst_type   | text          | text          |
| Yes      | series tag     | xst_suffix | xst_suffix | text          | text          |
| Yes      | series tag     | city       | city       | text          | text          |
| Yes      | series tag     | state      | state      | text          | text          |
| Yes      | series tag     | zip        | zip        | text          | text          |
| Yes      | numeric metric | latitude   | latitude   | number        | number        |
| Yes      | numeric metric | longitude  | longitude  | number        | number        |
| Yes      | series tag     | mutl_aid   | mutl_aid   | text          | text          |
| Yes      | series tag     | shift      | shift      | text          | text          |
| Yes      | numeric metric | alarms     | alarms     | number        | text          |
| Yes      | series tag     | alm_type   | alm_type   | text          | text          |
| Yes      | series tag     | inci_type  | inci_type  | text          | text          |
| Yes      | series tag     | descript   | descript   | text          | text          |
| No       |                | arv_time   | arv_time   | text          | text          |
```

## Time Field

```ls
Value = alm_date-alm_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss-HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = arv_time,alm_time,alm_date
```

## Data Commands

```ls
series e:anj2-ytvy d:2015-07-11T20:07:30.000Z t:zip=06103 t:mutl_aid=N t:station=01 t:street=COLUMBUS t:state=CT t:descript="Rescue, EMS incident, other" t:inci_type=300 t:number=300 t:city=Hartford t:alm_type=6 t:st_type=BLVD t:shift=B t:inci_no=15-0192049 m:longitude=-72.669826 m:latitude=41.765092 m:alarms=1

series e:anj2-ytvy d:2015-07-11T06:44:04.000Z t:zip=06103 t:mutl_aid=N t:station=01 t:street=COLUMBUS t:state=CT t:descript="Special type of incident, Other" t:inci_type=900 t:number=300 t:city=Hartford t:alm_type=6 t:st_type=BLVD t:shift=A t:inci_no=15-0192018 m:longitude=-72.669826 m:latitude=41.765092 m:alarms=1

series e:anj2-ytvy d:2015-07-11T15:24:44.000Z t:zip=06106 t:mutl_aid=N t:station=08 t:occup_id=00000 t:street=BROAD t:state=CT t:descript="Motor vehicle/pedestrian accident (MV Ped)" t:xst_type=ST t:inci_type=323 t:city=Hartford t:xstreet=JEFFERSON t:alm_type=1 t:st_type=ST t:shift=B t:inci_no=15-0192027 m:longitude=-72.6875 m:latitude=41.755 m:alarms=1
```

## Meta Commands

```ls
metric m:latitude p:double l:latitude t:dataTypeName=number

metric m:longitude p:double l:longitude t:dataTypeName=number

metric m:alarms p:integer l:alarms t:dataTypeName=number

entity e:anj2-ytvy l:FH_SOCRATA t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/anj2-ytvy

property e:anj2-ytvy t:meta.view v:id=anj2-ytvy v:category="Public Safety" v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name=FH_SOCRATA v:attribution="City of Hartford"

property e:anj2-ytvy t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:anj2-ytvy t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:anj2-ytvy t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| alm_time | alm_date            | inci_no    | station | occup_id | number | st_prefix | street     | st_type | st_suffix | xstreet   | xst_prefix | xst_type | xst_suffix | city     | state | zip   | latitude  | longitude  | mutl_aid | shift | alarms | alm_type | inci_type | descript                                         | arv_time | 
| ======== | =================== | ========== | ======= | ======== | ====== | ========= | ========== | ======= | ========= | ========= | ========== | ======== | ========== | ======== | ===== | ===== | ========= | ========== | ======== | ===== | ====== | ======== | ========= | ================================================ | ======== | 
| 20:07:30 | 2015-07-11T00:00:00 | 15-0192049 | 01      |          | 300    |           | COLUMBUS   | BLVD    |           |           |            |          |            | Hartford | CT    | 06103 | 41.765092 | -72.669826 | N        | B     | 1      | 6        | 300       | Rescue, EMS incident, other                      | 20:07:30 | 
| 06:44:04 | 2015-07-11T00:00:00 | 15-0192018 | 01      |          | 300    |           | COLUMBUS   | BLVD    |           |           |            |          |            | Hartford | CT    | 06103 | 41.765092 | -72.669826 | N        | A     | 1      | 6        | 900       | Special type of incident, Other                  | 07:13:08 | 
| 15:24:44 | 2015-07-11T00:00:00 | 15-0192027 | 08      | 00000    |        |           | BROAD      | ST      |           | JEFFERSON |            | ST       |            | Hartford | CT    | 06106 | 41.755    | -72.6875   | N        | B     | 1      | 1        | 323       | Motor vehicle/pedestrian accident (MV Ped)       | 15:26:46 | 
| 19:56:50 | 2015-07-11T00:00:00 | 15-0192047 | 16      | 03951    | 233    |           | GRANBY     | ST      |           |           |            |          |            | Hartford | CT    | 06112 | 41.7934   | -72.706    | N        | B     | 1      | 1        | 311       | Medical assist, assist EMS crew                  | 20:03:20 | 
| 16:31:57 | 2015-07-11T00:00:00 | 15-0192031 | 01      |          | 300    |           | COLUMBUS   | BLVD    |           |           |            |          |            | Hartford | CT    | 06103 | 41.765092 | -72.669826 | N        | B     | 1      | 6        | 300       | Rescue, EMS incident, other                      | 16:31:57 | 
| 17:41:24 | 2015-07-11T00:00:00 | 15-0192037 | 02      | 00000    |        |           | ALBANY     | AV      |           | WILLIAMS  |            | ST       |            | Hartford | CT    | 06120 | 41.7767   | -72.6824   | N        | B     | 1      | 1        | 622       | No Incident found on arrival at dispatch address | 17:46:20 | 
| 07:35:45 | 2015-07-11T00:00:00 | 15-0192012 | 08      | 15172    | 24     |           | YORK       | ST      |           |           |            |          |            | Hartford | CT    | 06106 | 41.757163 | -72.693467 | N        | A     | 1      | 1        | 311       | Medical assist, assist EMS crew                  | 07:40:53 | 
| 22:13:18 | 2015-07-11T00:00:00 | 15-0192054 | 05      | 00000    |        |           | NILES      | ST      |           | WOODLAND  |            | ST       |            | Hartford | CT    | 06105 | 41.7706   | -72.7015   | N        | B     | 1      | 1        | 321       | EMS call, excluding vehicle accident with injury | 22:16:20 | 
| 13:31:29 | 2015-07-11T00:00:00 | 15-0192021 | 01      | 23811    | 80     |           | WASHINGTON | ST      |           |           |            |          |            | Hartford | CT    | 06106 | 41.761085 | -72.682326 | N        | B     | 1      | 1        | 300       | Rescue, EMS incident, other                      | 13:36:22 | 
| 10:58:50 | 2015-07-11T00:00:00 | 15-0192019 | 15      | 33181    | 23     |           | MOUNTFORD  | ST      |           |           |            |          |            | Hartford | CT    | 06114 | 41.742126 | -72.685147 | N        | B     | 1      | 1        | 321       | EMS call, excluding vehicle accident with injury | 11:02:57 | 
```