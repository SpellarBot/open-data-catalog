# Missouri First Reports of Injury by Body Part - Lower Extremities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-first-reports-of-injury-by-body-part-lower-extremities-7787c) |
| Metadata | [Link](https://data.mo.gov/api/views/kadm-zhzb) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/kadm-zhzb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/kadm-zhzb/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | kadm-zhzb |
| Name | Missouri First Reports of Injury by Body Part - Lower Extremities |
| Category | Labor |
| Tags | labor, injury, employment, froi |
| Created | 2012-10-03T12:35:56Z |
| Publication Date | 2013-01-03T20:53:51Z |

## Description

First reports of injury filed reporting an injury to a lower extremity.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | recordid                   | recordid                   | text      | text        |
| No       |                | year                       | year                       | number    | number      |
| No       |                | month                      | month                      | number    | number      |
| Yes      | numeric metric | upper_leg_s                | upper leg(s)               | number    | number      |
| Yes      | numeric metric | hip_s                      | hip(s)                     | number    | number      |
| Yes      | numeric metric | foot                       | foot                       | number    | number      |
| Yes      | numeric metric | multiple_lower_extremities | multiple lower extremities | number    | number      |
| Yes      | numeric metric | ankle_s                    | ankle(s)                   | number    | number      |
| Yes      | numeric metric | lower_leg_s                | lower leg(s)               | number    | number      |
| Yes      | numeric metric | knee_s                     | knee(s)                    | number    | number      |
| Yes      | numeric metric | great_toe_s                | great toe(s)               | number    | number      |
| Yes      | numeric metric | toe_s                      | toe(s)                     | number    | number      |
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
series e:kadm-zhzb d:2005-04-01T00:00:00.000Z t:recordid=42005 m:great_toe_s=17 m:lower_leg_s=192 m:knee_s=694 m:toe_s=49 m:hip_s=88 m:multiple_lower_extremities=59 m:ankle_s=398 m:foot=289 m:upper_leg_s=70

series e:kadm-zhzb d:2004-04-01T00:00:00.000Z t:recordid=42004 m:great_toe_s=50 m:lower_leg_s=244 m:knee_s=756 m:toe_s=66 m:hip_s=82 m:multiple_lower_extremities=57 m:ankle_s=407 m:foot=305 m:upper_leg_s=84

series e:kadm-zhzb d:2007-04-01T00:00:00.000Z t:recordid=42007 m:great_toe_s=26 m:lower_leg_s=207 m:knee_s=698 m:toe_s=53 m:hip_s=71 m:multiple_lower_extremities=78 m:ankle_s=370 m:foot=309 m:upper_leg_s=90
```

## Meta Commands

```ls
metric m:upper_leg_s p:integer l:"upper leg(s)" t:dataTypeName=number

metric m:hip_s p:integer l:hip(s) t:dataTypeName=number

metric m:foot p:integer l:foot t:dataTypeName=number

metric m:multiple_lower_extremities p:integer l:"multiple lower extremities" t:dataTypeName=number

metric m:ankle_s p:integer l:ankle(s) t:dataTypeName=number

metric m:lower_leg_s p:integer l:"lower leg(s)" t:dataTypeName=number

metric m:knee_s p:integer l:knee(s) t:dataTypeName=number

metric m:great_toe_s p:integer l:"great toe(s)" t:dataTypeName=number

metric m:toe_s p:integer l:toe(s) t:dataTypeName=number

entity e:kadm-zhzb l:"Missouri First Reports of Injury by Body Part - Lower Extremities" t:url=https://data.mo.gov/api/views/kadm-zhzb

property e:kadm-zhzb t:meta.view v:id=kadm-zhzb v:category=Labor v:averageRating=0 v:name="Missouri First Reports of Injury by Body Part - Lower Extremities"

property e:kadm-zhzb t:meta.view.owner v:id=fq9d-b9a3 v:screenName=Jolene v:displayName=Jolene

property e:kadm-zhzb t:meta.view.tableauthor v:id=fq9d-b9a3 v:screenName=Jolene v:roleName=editor v:displayName=Jolene
```

## Top Records

```ls
| recordid | year | month | upper_leg_s | hip_s | foot | multiple_lower_extremities | ankle_s | lower_leg_s | knee_s | great_toe_s | toe_s | 
| ======== | ==== | ===== | =========== | ===== | ==== | ========================== | ======= | =========== | ====== | =========== | ===== | 
| 42005    | 2005 | 4     | 70          | 88    | 289  | 59                         | 398     | 192         | 694    | 17          | 49    | 
| 42004    | 2004 | 4     | 84          | 82    | 305  | 57                         | 407     | 244         | 756    | 50          | 66    | 
| 42007    | 2007 | 4     | 90          | 71    | 309  | 78                         | 370     | 207         | 698    | 26          | 53    | 
| 42006    | 2006 | 4     | 69          | 61    | 321  | 74                         | 330     | 190         | 631    | 17          | 57    | 
| 42009    | 2009 | 4     | 47          | 62    | 247  | 69                         | 307     | 157         | 574    | 17          | 41    | 
| 42008    | 2008 | 4     | 66          | 78    | 286  | 72                         | 368     | 185         | 691    | 19          | 54    | 
| 42001    | 2001 | 4     | 96          | 83    | 363  | 56                         | 444     | 269         | 774    | 30          | 65    | 
| 42003    | 2003 | 4     | 71          | 78    | 278  | 53                         | 416     | 228         | 710    | 26          | 65    | 
| 42002    | 2002 | 4     | 78          | 95    | 363  | 48                         | 455     | 261         | 845    | 38          | 61    | 
| 102009   | 2009 | 10    | 47          | 72    | 236  | 68                         | 346     | 192         | 660    | 21          | 54    | 
```