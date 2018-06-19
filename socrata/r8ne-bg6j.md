# Missouri First Reports of Injury by Body Part - Upper Extremities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-first-reports-of-injury-by-body-part-upper-extremities-3dc04) |
| Metadata | [Link](https://data.mo.gov/api/views/r8ne-bg6j) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/r8ne-bg6j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/r8ne-bg6j/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | r8ne-bg6j |
| Name | Missouri First Reports of Injury by Body Part - Upper Extremities |
| Category | Labor |
| Tags | labor, injury, employment, froi |
| Created | 2012-10-03T12:36:02Z |
| Publication Date | 2013-01-03T20:54:00Z |

## Description

First reports of injury filed reporting an injury to an upper body extremity.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | recordid                   | recordid                   | text      | text        |
| No       |                | year                       | year                       | number    | number      |
| No       |                | month                      | month                      | number    | number      |
| Yes      | numeric metric | elbow_s                    | elbow(s)                   | number    | number      |
| Yes      | numeric metric | hand_s                     | hand(s)                    | number    | number      |
| Yes      | numeric metric | thumb_s                    | thumb(s)                   | number    | number      |
| Yes      | numeric metric | multiple_upper_extremities | multiple upper extremities | number    | number      |
| Yes      | numeric metric | wrist_s                    | wrist(s)                   | number    | number      |
| Yes      | numeric metric | lower_arm_s                | lower arm(s)               | number    | number      |
| Yes      | numeric metric | finger_s                   | finger(s)                  | number    | number      |
| Yes      | numeric metric | upper_arm_s                | upper arm(s)               | number    | number      |
| Yes      | numeric metric | shoulder_s                 | shoulder(s)                | number    | number      |
| Yes      | numeric metric | wrist_s_hand_s             | wrist(s) & hand(s)         | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:r8ne-bg6j d:2005-04-01T00:00:00.000Z t:recordid=42005 m:multiple_upper_extremities=158 m:shoulder_s=481 m:elbow_s=244 m:hand_s=731 m:wrist_s_hand_s=109 m:thumb_s=353 m:wrist_s=464 m:lower_arm_s=329 m:upper_arm_s=198 m:finger_s=1024

series e:r8ne-bg6j d:2004-04-01T00:00:00.000Z t:recordid=42004 m:multiple_upper_extremities=184 m:shoulder_s=590 m:elbow_s=288 m:hand_s=853 m:wrist_s_hand_s=128 m:thumb_s=405 m:wrist_s=505 m:lower_arm_s=388 m:upper_arm_s=209 m:finger_s=1257

series e:r8ne-bg6j d:2007-04-01T00:00:00.000Z t:recordid=42007 m:multiple_upper_extremities=172 m:shoulder_s=534 m:elbow_s=213 m:hand_s=754 m:wrist_s_hand_s=100 m:thumb_s=324 m:wrist_s=407 m:lower_arm_s=328 m:upper_arm_s=145 m:finger_s=1121
```

## Meta Commands

```ls
metric m:elbow_s p:integer l:elbow(s) t:dataTypeName=number

metric m:hand_s p:integer l:hand(s) t:dataTypeName=number

metric m:thumb_s p:integer l:thumb(s) t:dataTypeName=number

metric m:multiple_upper_extremities p:integer l:"multiple upper extremities" t:dataTypeName=number

metric m:wrist_s p:integer l:wrist(s) t:dataTypeName=number

metric m:lower_arm_s p:integer l:"lower arm(s)" t:dataTypeName=number

metric m:finger_s p:integer l:finger(s) t:dataTypeName=number

metric m:upper_arm_s p:integer l:"upper arm(s)" t:dataTypeName=number

metric m:shoulder_s p:integer l:shoulder(s) t:dataTypeName=number

metric m:wrist_s_hand_s p:integer l:"wrist(s) & hand(s)" t:dataTypeName=number

entity e:r8ne-bg6j l:"Missouri First Reports of Injury by Body Part - Upper Extremities" t:url=https://data.mo.gov/api/views/r8ne-bg6j

property e:r8ne-bg6j t:meta.view v:id=r8ne-bg6j v:category=Labor v:averageRating=0 v:name="Missouri First Reports of Injury by Body Part - Upper Extremities"

property e:r8ne-bg6j t:meta.view.owner v:id=fq9d-b9a3 v:screenName=Jolene v:displayName=Jolene

property e:r8ne-bg6j t:meta.view.tableauthor v:id=fq9d-b9a3 v:screenName=Jolene v:roleName=editor v:displayName=Jolene
```

## Top Records

```ls
| recordid | year | month | elbow_s | hand_s | thumb_s | multiple_upper_extremities | wrist_s | lower_arm_s | finger_s | upper_arm_s | shoulder_s | wrist_s_hand_s | 
| ======== | ==== | ===== | ======= | ====== | ======= | ========================== | ======= | =========== | ======== | =========== | ========== | ============== | 
| 42005    | 2005 | 4     | 244     | 731    | 353     | 158                        | 464     | 329         | 1024     | 198         | 481        | 109            | 
| 42004    | 2004 | 4     | 288     | 853    | 405     | 184                        | 505     | 388         | 1257     | 209         | 590        | 128            | 
| 42007    | 2007 | 4     | 213     | 754    | 324     | 172                        | 407     | 328         | 1121     | 145         | 534        | 100            | 
| 42006    | 2006 | 4     | 221     | 705    | 320     | 179                        | 433     | 370         | 1092     | 155         | 473        | 83             | 
| 42009    | 2009 | 4     | 187     | 600    | 274     | 88                         | 338     | 260         | 874      | 147         | 411        | 43             | 
| 42008    | 2008 | 4     | 216     | 641    | 331     | 109                        | 399     | 318         | 990      | 175         | 518        | 87             | 
| 42001    | 2001 | 4     | 322     | 983    | 440     | 231                        | 634     | 431         | 1351     | 288         | 582        | 133            | 
| 42003    | 2003 | 4     | 275     | 835    | 385     | 204                        | 564     | 342         | 1139     | 230         | 539        | 96             | 
| 42002    | 2002 | 4     | 318     | 1010   | 420     | 213                        | 573     | 431         | 1394     | 243         | 682        | 129            | 
| 102009   | 2009 | 10    | 164     | 587    | 298     | 99                         | 336     | 306         | 937      | 129         | 433        | 81             | 
```