# LAPD Vehicle and Pedestrian Stops 2016

## Dataset

* [Dataset URL](https://data.lacity.org/api/views/ghrm-j3er/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/lapd-vehicle-and-pedestrian-stops-2016)
* [Metadata URL](https://data.lacity.org/api/views/ghrm-j3er)
* Id = ghrm-j3er
* Name = LAPD Vehicle and Pedestrian Stops 2016
* Category = A Safe City
* Tags = [lapd, police, stops]
* Created = 2017-01-10T23:44:14Z
* Publication Date = 2017-01-24T05:01:42Z
* Rows Updated = 2017-01-24T04:58:26Z

## Description



## Columns

```ls
| Name               | Field Name         | Data Type     | Render Type   | Schema Type    | Included | 
| ================== | ================== | ============= | ============= | ============== | ======== | 
| STOP_NBR           | stop_nbr           | number        | number        | numeric metric | Yes      | 
| FORM_REF_NBR       | form_ref_nbr       | number        | number        | numeric metric | Yes      | 
| PERSN_GENDER_CD    | persn_gender_cd    | number        | text          | numeric metric | Yes      | 
| PERSN_DESCENT_CD   | persn_descent_cd   | number        | text          | numeric metric | Yes      | 
| DESCENT_DESC       | descent_desc       | text          | text          | series tag     | Yes      | 
| STOP_DT            | stop_dt            | calendar_date | calendar_date | time           | Yes      | 
| STOP_TM            | stop_tm            | text          | text          | series tag     | Yes      | 
| OFCR1_SERL_NBR     | ofcr1_serl_nbr     | number        | number        | numeric metric | Yes      | 
| OFCR1_DIV_NBR      | ofcr1_div_nbr      | text          | text          | series tag     | Yes      | 
| DIV1_DESC          | div1_desc          | text          | text          | series tag     | Yes      | 
| OFCR2_SERL_NBR     | ofcr2_serl_nbr     | number        | number        | numeric metric | Yes      | 
| OFCR2_DIV_NBR      | ofcr2_div_nbr      | text          | text          | series tag     | Yes      | 
| DIV2_DESC          | div2_desc          | text          | text          | series tag     | Yes      | 
| RPT_DIST_NBR       | rpt_dist_nbr       | number        | number        | numeric metric | Yes      | 
| STOP_TYPE          | stop_type          | text          | text          | series tag     | Yes      | 
| POST_STOP_ACTV_IND | post_stop_actv_ind | number        | text          | numeric metric | Yes      | 
```

## Time Field

```ls
Value = stop_dt
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
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
series e:ghrm-j3er d:2016-06-25T00:00:00.000Z t:post_stop_actv_ind=N t:descent_desc=WHITE t:persn_descent_cd=W t:stop_tm=16:40 t:persn_gender_cd=M t:div1_desc="SOUTH TRAFFIC" t:stop_type=VEH t:ofcr1_div_nbr=25 m:stop_nbr=12910565 m:ofcr1_serl_nbr=16685 m:form_ref_nbr=26538544 m:rpt_dist_nbr=1801

series e:ghrm-j3er d:2016-01-01T00:00:00.000Z t:post_stop_actv_ind=N t:descent_desc=HISPANIC t:persn_descent_cd=H t:div2_desc=DEVONSHIRE t:stop_tm=23:50 t:ofcr2_div_nbr=17 t:persn_gender_cd=M t:div1_desc=DEVONSHIRE t:stop_type=VEH t:ofcr1_div_nbr=17 m:ofcr2_serl_nbr=51343 m:stop_nbr=12598583 m:ofcr1_serl_nbr=25401 m:form_ref_nbr=25184341 m:rpt_dist_nbr=1764

series e:ghrm-j3er d:2016-01-01T00:00:00.000Z t:post_stop_actv_ind=N t:descent_desc=BLACK t:persn_descent_cd=B t:div2_desc="WEST VALLEY" t:stop_tm=00:10 t:ofcr2_div_nbr=10 t:persn_gender_cd=M t:div1_desc="WEST VALLEY" t:stop_type=VEH t:ofcr1_div_nbr=10 m:ofcr2_serl_nbr=57765 m:stop_nbr=12598587 m:ofcr1_serl_nbr=49734 m:form_ref_nbr=25184346 m:rpt_dist_nbr=1039
```

## Meta Commands

```ls
metric m:stop_nbr p:integer l:STOP_NBR t:dataTypeName=number

metric m:form_ref_nbr p:integer l:FORM_REF_NBR t:dataTypeName=number

metric m:ofcr1_serl_nbr p:integer l:OFCR1_SERL_NBR t:dataTypeName=number

metric m:ofcr2_serl_nbr p:integer l:OFCR2_SERL_NBR t:dataTypeName=number

metric m:rpt_dist_nbr p:integer l:RPT_DIST_NBR t:dataTypeName=number

entity e:ghrm-j3er l:"LAPD Vehicle and Pedestrian Stops 2016" t:url=https://data.lacity.org/api/views/ghrm-j3er

property e:ghrm-j3er t:meta.view d:2017-03-08T02:27:38.013Z v:id=ghrm-j3er v:category="A Safe City" v:averageRating=0 v:name="LAPD Vehicle and Pedestrian Stops 2016"

property e:ghrm-j3er t:meta.view.license d:2017-03-08T02:27:38.013Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:ghrm-j3er t:meta.view.owner d:2017-03-08T02:27:38.013Z v:id=art8-rc4x v:profileImageUrlMedium=/api/users/art8-rc4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/art8-rc4x/profile_images/LARGE v:screenName="LAPD OpenData" v:profileImageUrlSmall=/api/users/art8-rc4x/profile_images/TINY v:roleName=publisher v:displayName="LAPD OpenData"

property e:ghrm-j3er t:meta.view.tableauthor d:2017-03-08T02:27:38.013Z v:id=art8-rc4x v:profileImageUrlMedium=/api/users/art8-rc4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/art8-rc4x/profile_images/LARGE v:screenName="LAPD OpenData" v:profileImageUrlSmall=/api/users/art8-rc4x/profile_images/TINY v:roleName=publisher v:displayName="LAPD OpenData"
```