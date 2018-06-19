# LAPD Vehicle and Pedestrian Stops 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lapd-vehicle-and-pedestrian-stops-2015) |
| Metadata | [Link](https://data.lacity.org/api/views/fmpk-vq3h) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/fmpk-vq3h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/fmpk-vq3h/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | fmpk-vq3h |
| Name | LAPD Vehicle and Pedestrian Stops 2015 |
| Category | A Safe City |
| Tags | lapd, police, stops |
| Created | 2016-09-20T21:55:12Z |
| Publication Date | 2017-01-25T17:01:15Z |

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | numeric metric | stop_nbr           | STOP_NBR           | number    | number      |
| Yes      | numeric metric | form_ref_nbr       | FORM_REF_NBR       | number    | number      |
| Yes      | series tag     | persn_gender_cd    | PERSN_GENDER_CD    | text      | text        |
| Yes      | series tag     | persn_descent_cd   | PERSN_DESCENT_CD   | text      | text        |
| Yes      | series tag     | descent_desc       | DESCENT_DESC       | text      | text        |
| Yes      | series tag     | stop_dt            | STOP_DT            | text      | text        |
| Yes      | series tag     | stop_tm            | STOP_TM            | text      | text        |
| Yes      | numeric metric | ofcr1_serl_nbr     | OFCR1_SERL_NBR     | number    | number      |
| Yes      | numeric metric | ofcr1_div_nbr      | OFCR1_DIV_NBR      | number    | number      |
| Yes      | series tag     | div1_desc          | DIV1_DESC          | text      | text        |
| Yes      | numeric metric | ofcr2_serl_nbr     | OFCR2_SERL_NBR     | number    | number      |
| Yes      | numeric metric | ofcr2_div_nbr      | OFCR2_DIV_NBR      | number    | number      |
| Yes      | series tag     | div2_desc          | DIV2_DESC          | text      | text        |
| Yes      | numeric metric | rpt_dist_nbr       | RPT_DIST_NBR       | number    | number      |
| Yes      | series tag     | stop_type          | STOP_TYPE          | text      | text        |
| Yes      | series tag     | post_stop_actv_ind | POST_STOP_ACTV_IND | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fmpk-vq3h d:2015-01-01T00:00:00.000Z t:post_stop_actv_ind=N t:descent_desc=HISPANIC t:persn_descent_cd=H t:div2_desc=HARBOR t:stop_tm=18:50 t:persn_gender_cd=M t:stop_dt=01/01/2015 t:div1_desc=HARBOR t:stop_type=VEH m:ofcr2_serl_nbr=10783 m:stop_nbr=11979294 m:ofcr1_serl_nbr=49499 m:ofcr2_div_nbr=5 m:form_ref_nbr=23848708 m:rpt_dist_nbr=566 m:ofcr1_div_nbr=5

series e:fmpk-vq3h d:2015-01-01T00:00:00.000Z t:post_stop_actv_ind=N t:descent_desc=HISPANIC t:persn_descent_cd=H t:div2_desc=HARBOR t:stop_tm=18:50 t:persn_gender_cd=M t:stop_dt=01/01/2015 t:div1_desc=HARBOR t:stop_type=VEH m:ofcr2_serl_nbr=10783 m:stop_nbr=11979295 m:ofcr1_serl_nbr=49499 m:ofcr2_div_nbr=5 m:form_ref_nbr=23848708 m:rpt_dist_nbr=566 m:ofcr1_div_nbr=5

series e:fmpk-vq3h d:2015-01-01T00:00:00.000Z t:post_stop_actv_ind=N t:descent_desc=ASIAN t:persn_descent_cd=A t:div2_desc=HOLLYWOOD t:stop_tm=19:40 t:persn_gender_cd=F t:stop_dt=01/01/2015 t:div1_desc=HOLLYWOOD t:stop_type=VEH m:ofcr2_serl_nbr=54089 m:stop_nbr=11979296 m:ofcr1_serl_nbr=54085 m:ofcr2_div_nbr=6 m:form_ref_nbr=23848709 m:rpt_dist_nbr=636 m:ofcr1_div_nbr=6
```

## Meta Commands

```ls
metric m:stop_nbr p:integer l:STOP_NBR t:dataTypeName=number

metric m:form_ref_nbr p:integer l:FORM_REF_NBR t:dataTypeName=number

metric m:ofcr1_serl_nbr p:integer l:OFCR1_SERL_NBR t:dataTypeName=number

metric m:ofcr1_div_nbr p:integer l:OFCR1_DIV_NBR t:dataTypeName=number

metric m:ofcr2_serl_nbr p:integer l:OFCR2_SERL_NBR t:dataTypeName=number

metric m:ofcr2_div_nbr p:integer l:OFCR2_DIV_NBR t:dataTypeName=number

metric m:rpt_dist_nbr p:integer l:RPT_DIST_NBR t:dataTypeName=number

entity e:fmpk-vq3h l:"LAPD Vehicle and Pedestrian Stops 2015" t:url=https://data.lacity.org/api/views/fmpk-vq3h

property e:fmpk-vq3h t:meta.view v:id=fmpk-vq3h v:category="A Safe City" v:averageRating=0 v:name="LAPD Vehicle and Pedestrian Stops 2015"

property e:fmpk-vq3h t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:fmpk-vq3h t:meta.view.owner v:id=art8-rc4x v:profileImageUrlMedium=/api/users/art8-rc4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/art8-rc4x/profile_images/LARGE v:screenName="LAPD OpenData" v:profileImageUrlSmall=/api/users/art8-rc4x/profile_images/TINY v:lastNotificationSeenAt=1492554751 v:displayName="LAPD OpenData"

property e:fmpk-vq3h t:meta.view.tableauthor v:id=art8-rc4x v:profileImageUrlMedium=/api/users/art8-rc4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/art8-rc4x/profile_images/LARGE v:screenName="LAPD OpenData" v:profileImageUrlSmall=/api/users/art8-rc4x/profile_images/TINY v:roleName=publisher v:lastNotificationSeenAt=1492554751 v:displayName="LAPD OpenData"
```

## Top Records

```ls
| stop_nbr | form_ref_nbr | persn_gender_cd | persn_descent_cd | descent_desc | stop_dt    | stop_tm | ofcr1_serl_nbr | ofcr1_div_nbr | div1_desc       | ofcr2_serl_nbr | ofcr2_div_nbr | div2_desc       | rpt_dist_nbr | stop_type | post_stop_actv_ind | 
| ======== | ============ | =============== | ================ | ============ | ========== | ======= | ============== | ============= | =============== | ============== | ============= | =============== | ============ | ========= | ================== | 
| 11979294 | 23848708     | M               | H                | HISPANIC     | 01/01/2015 | 18:50   | 49499          | 5             | HARBOR          | 10783          | 5             | HARBOR          | 566          | VEH       | N                  | 
| 11979295 | 23848708     | M               | H                | HISPANIC     | 01/01/2015 | 18:50   | 49499          | 5             | HARBOR          | 10783          | 5             | HARBOR          | 566          | VEH       | N                  | 
| 11979296 | 23848709     | F               | A                | ASIAN        | 01/01/2015 | 19:40   | 54085          | 6             | HOLLYWOOD       | 54089          | 6             | HOLLYWOOD       | 636          | VEH       | N                  | 
| 11979297 | 23848710     | M               | B                | BLACK        | 01/01/2015 | 19:50   | 54141          | 6             | HOLLYWOOD       | 53569          | 6             | HOLLYWOOD       | 636          | VEH       | N                  | 
| 11979298 | 23848711     | M               | W                | WHITE        | 01/01/2015 | 19:20   | 49125          | 15            | NORTH HOLLYWOOD | 48264          | 15            | NORTH HOLLYWOOD | 1516         | PED       | N                  | 
| 11979299 | 23848711     | M               | W                | WHITE        | 01/01/2015 | 19:20   | 49125          | 15            | NORTH HOLLYWOOD | 48264          | 15            | NORTH HOLLYWOOD | 1516         | PED       | N                  | 
| 11979300 | 23848711     | M               | W                | WHITE        | 01/01/2015 | 19:20   | 49125          | 15            | NORTH HOLLYWOOD | 48264          | 15            | NORTH HOLLYWOOD | 1516         | PED       | N                  | 
| 11979301 | 23848712     | M               | B                | BLACK        | 01/01/2015 | 19:15   | 53330          | 3             | SOUTH WEST      | 53331          | 3             | SOUTH WEST      | 363          | VEH       | N                  | 
| 11979302 | 23848712     | F               | B                | BLACK        | 01/01/2015 | 19:15   | 53330          | 3             | SOUTH WEST      | 53331          | 3             | SOUTH WEST      | 363          | VEH       | N                  | 
| 11979303 | 23848712     | F               | B                | BLACK        | 01/01/2015 | 19:15   | 53330          | 3             | SOUTH WEST      | 53331          | 3             | SOUTH WEST      | 363          | VEH       | N                  | 
```